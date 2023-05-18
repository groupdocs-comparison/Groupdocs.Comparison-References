---
title: PreviewFormats
second_title: GroupDocs.Comparison for Java API Reference
description: Enumerates the supported preview formats for document comparison.
type: docs
weight: 14
url: /java/com.groupdocs.comparison.options.enums/previewformats/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PreviewFormats extends Enum<PreviewFormats>
```

Enumerates the supported preview formats for document comparison.

The PreviewFormats enum provides a list of formats that can be used to generate previews of compared documents.

Supported formats include:

 *  \#PNG.PNG - Portable Network Graphics (.png)
 *  \#JPEG.JPEG - Joint Photographic Experts Group (.jpeg)
 *  \#BMP.BMP - Bitmap Picture (.bmp)

Example usage:

```

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    PreviewOptions previewOptions = new PreviewOptions(
            pageNumber -> Files.newOutputStream(Paths.get(String.format("preview-page_%d.png", pageNumber)))
    );
    previewOptions.setPreviewFormat(PreviewFormats.PNG);

    comparer.getTargets().get(0).generatePreview(previewOptions);
 }
 
```
## Fields

| Field | Description |
| --- | --- |
| [PNG](#PNG) | PNG - may consume significant disk space or network traffic if the page contains numerous color graphics. |
| [JPEG](#JPEG) | Jpeg - provides faster processing with smaller disk space usage and network traffic, but may result in lower image quality. |
| [BMP](#BMP) | BMP - offers the best image quality but requires slower processing with higher disk space usage and network traffic. |
## Methods

| Method | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [fromString(String toStringValue)](#fromString-java.lang.String-) | Parses string representation of PreviewFormats to get the enum constant. |
| [toString()](#toString--) | String representation of PreviewFormats. |
### PNG {#PNG}
```
public static final PreviewFormats PNG
```


PNG - may consume significant disk space or network traffic if the page contains numerous color graphics. Default preview format.

### JPEG {#JPEG}
```
public static final PreviewFormats JPEG
```


Jpeg - provides faster processing with smaller disk space usage and network traffic, but may result in lower image quality.

### BMP {#BMP}
```
public static final PreviewFormats BMP
```


BMP - offers the best image quality but requires slower processing with higher disk space usage and network traffic.

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
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static PreviewFormats fromString(String toStringValue)
```


Parses string representation of PreviewFormats to get the enum constant.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| toStringValue | java.lang.String | The string representation of PreviewFormats |

**Returns:**
[PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats) - PreviewFormats enum constant associated with input string
### toString() {#toString--}
```
public String toString()
```


String representation of PreviewFormats.

**Returns:**
java.lang.String - string value of enum constant
