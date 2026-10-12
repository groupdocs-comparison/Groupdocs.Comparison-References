---
title: "PreviewFormats"
second_title: "GroupDocs.Comparison för Java API-referens"
description: "Uppräkning av de stödda förhandsgranskningsformaten för dokumentjämförelse."
type: docs
weight: 15
url: /sv/java/com.groupdocs.comparison.options.enums/previewformats/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PreviewFormats extends Enum<PreviewFormats>
```

Uppräkning av de stödda förhandsgranskningsformaten för dokumentjämförelse.
PreviewFormats-enumen tillhandahåller en lista med format som kan användas för att generera förhandsvisningar av jämförda dokument.

Följande format stöds:

* #PNG.PNG - Portable Network Graphics (.png)
* #JPEG.JPEG - Joint Photographic Experts Group (.jpeg)
* #BMP.BMP - Bitmap Picture (.bmp)


Exempel på användning:

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


## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [PNG](#PNG) | PNG - kan förbruka betydande diskutrymme eller nätverkstrafik om sidan innehåller många färggrafik. |
|
|  | [JPEG](#JPEG) | Jpeg - ger snabbare bearbetning med mindre diskutrymme och nätverkstrafik, men kan leda till lägre bildkvalitet. |
|
|  | [BMP](#BMP) | BMP - erbjuder bästa bildkvalitet men kräver långsammare bearbetning med högre diskutrymme och nätverkstrafik. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Analyserar strängrepresentationen av PreviewFormats för att få enum-konstanten. |
|
|  | [toString()](#toString--) | Strängrepresentation av PreviewFormats. |
|
### PNG {#PNG}
```
public static final PreviewFormats PNG
```


PNG - kan förbruka betydande diskutrymme eller nätverkstrafik om sidan innehåller många färggrafik. Standardförhandsvisningsformat.


### JPEG {#JPEG}
```
public static final PreviewFormats JPEG
```


Jpeg - ger snabbare bearbetning med mindre diskutrymme och nätverkstrafik, men kan leda till lägre bildkvalitet.


### BMP {#BMP}
```
public static final PreviewFormats BMP
```


BMP - erbjuder bästa bildkvalitet men kräver långsammare bearbetning med högre diskutrymme och nätverkstrafik.


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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String |  |

**Returns:**
[PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static PreviewFormats fromString(String toStringValue)
```


Analyserar strängrepresentationen av PreviewFormats för att få enum-konstanten.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | toStringValue | java.lang.String | Strängrepresentationen av PreviewFormats |
|

**Returns:**
[PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats) - PreviewFormats enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


Strängrepresentation av PreviewFormats.


**Returns:**
java.lang.String - strängvärde av enum‑konstant

