---
title: PreviewFormats
second_title: GroupDocs.Comparison for Java API Reference
description: Document preview supported formats.
type: docs
weight: 14
url: /java/com.groupdocs.comparison.options.enums/previewformats/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PreviewFormats extends Enum<PreviewFormats>
```

Document preview supported formats.
## Fields

| Field | Description |
| --- | --- |
| [PNG](#PNG) | Png (by default), can be take a lot of disc space / traffic if page contains a lot of color graphics. |
| [JPEG](#JPEG) | Jpeg - faster processing, small disc space using / traffic, but can be worst quality. |
| [BMP](#BMP) | BMP - slow processing, high disc space usage / traffic, but best quality. |
## Methods

| Method | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [fromString(String toStringValue)](#fromString-java.lang.String-) |  |
| [toString()](#toString--) |  |
### PNG {#PNG}
```
public static final PreviewFormats PNG
```


Png (by default), can be take a lot of disc space / traffic if page contains a lot of color graphics.

### JPEG {#JPEG}
```
public static final PreviewFormats JPEG
```


Jpeg - faster processing, small disc space using / traffic, but can be worst quality.

### BMP {#BMP}
```
public static final PreviewFormats BMP
```


BMP - slow processing, high disc space usage / traffic, but best quality.

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




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| toStringValue | java.lang.String |  |

**Returns:**
[PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats)
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
