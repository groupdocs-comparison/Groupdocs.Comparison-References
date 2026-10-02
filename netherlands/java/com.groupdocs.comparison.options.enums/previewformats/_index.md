---
title: "PreviewFormats"
second_title: "GroupDocs.Comparison voor Java API-referentie"
description: "Somt de opties op voor preview-formaten voor documentvergelijking."
type: docs
weight: 15
url: /nl/java/com.groupdocs.comparison.options.enums/previewformats/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PreviewFormats extends Enum<PreviewFormats>
```

Somt de opties op voor preview-formaten voor documentvergelijking.
De PreviewFormats-enum biedt een lijst met formaten die kunnen worden gebruikt om voorbeeldweergaven van te vergelijken documenten te genereren.

Ondersteunde formaten omvatten:

* #PNG.PNG - Portable Network Graphics (.png)
* #JPEG.JPEG - Joint Photographic Experts Group (.jpeg)
* #BMP.BMP - Bitmap Picture (.bmp)


Voorbeeldgebruik:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    PreviewOptions previewOptions = new PreviewOptions(
            pageNumber -> Files.newOutputStream(Paths.get(String.format("preview-page_%d.png", pageNumber)))
    );
    previewOptions.setPreviewFormat(PreviewFormats.PNG);

    comparer.getTargets().get(0).generatePreview(previewOptions);
 }
 
````


## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [PNG](#PNG) | PNG - kan aanzienlijke schijfruimte of netwerkverkeer verbruiken als de pagina veel kleurgrafieken bevat. |
|
|  | [JPEG](#JPEG) | Jpeg - biedt snellere verwerking met minder schijfruimtegebruik en netwerkverkeer, maar kan resulteren in een lagere beeldkwaliteit. |
|
|  | [BMP](#BMP) | BMP - biedt de beste beeldkwaliteit maar vereist een tragere verwerking met hoger schijfruimtegebruik en netwerkverkeer. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Parseert de tekenreeksrepresentatie van PreviewFormats om de enum-constante te verkrijgen. |
|
|  | [toString()](#toString--) | Tekenreeksrepresentatie van PreviewFormats. |
|
### PNG {#PNG}
```
public static final PreviewFormats PNG
```


PNG - kan aanzienlijke schijfruimte of netwerkverkeer verbruiken als de pagina veel kleurgrafieken bevat. Standaard voorbeeldformaat.


### JPEG {#JPEG}
```
public static final PreviewFormats JPEG
```


Jpeg - biedt snellere verwerking met minder schijfruimtegebruik en netwerkverkeer, maar kan resulteren in een lagere beeldkwaliteit.


### BMP {#BMP}
```
public static final PreviewFormats BMP
```


BMP - biedt de beste beeldkwaliteit maar vereist een tragere verwerking met hoger schijfruimtegebruik en netwerkverkeer.


### values() {#values--}
```
public static PreviewFormats[] values()
```




**Returns:**
com.groupdocs.comparison.options.enums.PreviewFormats[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PreviewFormats valueOf(String name)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String |  |

**Returns:**
[PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static PreviewFormats fromString(String toStringValue)
```


Parseert de tekenreeksrepresentatie van PreviewFormats om de enum-constante te verkrijgen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | toStringValue | java.lang.String | De tekenreeksrepresentatie van PreviewFormats |
|

**Returns:**
[PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats) - PreviewFormats enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


Tekenreeksrepresentatie van PreviewFormats.


**Returns:**
java.lang.String - tekenreekswaarde van enum-constante

