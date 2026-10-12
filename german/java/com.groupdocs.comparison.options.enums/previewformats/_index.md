---
title: "PreviewFormats"
second_title: "GroupDocs.Comparison für Java API-Referenz"
description: "Enumeriert die unterstützten Vorschaueformate für den Dokumentvergleich."
type: docs
weight: 15
url: /de/java/com.groupdocs.comparison.options.enums/previewformats/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PreviewFormats extends Enum<PreviewFormats>
```

Enumeriert die unterstützten Vorschaueformate für den Dokumentvergleich.
Das PreviewFormats-Enum stellt eine Liste von Formaten bereit, die zur Erstellung von Vorschaubildern verglichener Dokumente verwendet werden können.

Unterstützte Formate umfassen:

* #PNG.PNG - Portable Network Graphics (.png)
* #JPEG.JPEG - Joint Photographic Experts Group (.jpeg)
* #BMP.BMP - Bitmap Picture (.bmp)


Beispielverwendung:

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


## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [PNG](#PNG) | PNG – kann bei Seiten mit vielen Farbgrafiken erheblichen Festplattenspeicher oder Netzwerkverkehr verbrauchen. |
|
|  | [JPEG](#JPEG) | Jpeg – ermöglicht schnellere Verarbeitung bei geringerem Festplattenspeicher- und Netzwerkverbrauch, kann jedoch zu geringerer Bildqualität führen. |
|
|  | [BMP](#BMP) | BMP – bietet die beste Bildqualität, erfordert jedoch langsamere Verarbeitung bei höherem Festplatten- und Netzwerkverbrauch. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Parst die Zeichenkettenrepräsentation von PreviewFormats, um die Enum-Konstante zu erhalten. |
|
|  | [toString()](#toString--) | Zeichenkettenrepräsentation von PreviewFormats. |
|
### PNG {#PNG}
```
public static final PreviewFormats PNG
```


PNG – kann bei Seiten mit vielen Farbgrafiken erheblichen Festplattenspeicher oder Netzwerkverkehr verbrauchen. Standard-Vorschaubildformat.


### JPEG {#JPEG}
```
public static final PreviewFormats JPEG
```


Jpeg – ermöglicht schnellere Verarbeitung bei geringerem Festplattenspeicher- und Netzwerkverbrauch, kann jedoch zu geringerer Bildqualität führen.


### BMP {#BMP}
```
public static final PreviewFormats BMP
```


BMP – bietet die beste Bildqualität, erfordert jedoch langsamere Verarbeitung bei höherem Festplatten- und Netzwerkverbrauch.


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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String |  |

**Returns:**
[PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static PreviewFormats fromString(String toStringValue)
```


Parst die Zeichenkettenrepräsentation von PreviewFormats, um die Enum-Konstante zu erhalten.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | toStringValue | java.lang.String | Die Zeichenkettenrepräsentation von PreviewFormats |
|

**Returns:**
[PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats) - PreviewFormats enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


Zeichenkettenrepräsentation von PreviewFormats.


**Returns:**
java.lang.String - String-Wert der Enum-Konstante

