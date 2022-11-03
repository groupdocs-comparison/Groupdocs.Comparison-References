---
title: PreviewOptions
second_title: GroupDocs.Comparison for Java API Reference
description: Represents document preview options.
type: docs
weight: 15
url: /java/com.groupdocs.comparison.options/previewoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewOptions
```

Represents document preview options.
## Constructors

| Constructor | Description |
| --- | --- |
| [PreviewOptions(Delegates.CreatePageStream createPageStream)](#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-) | Initializes a new instance of [PreviewOptions](../../com.groupdocs.comparison.options/previewoptions) class. |
| [PreviewOptions(Delegates.CreatePageStream createPageStream, Delegates.ReleasePageStream releasePageStream)](#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-) | Initializes a new instance of [PreviewOptions](../../com.groupdocs.comparison.options/previewoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [getCreatePageStream()](#getCreatePageStream--) | Delegate which defines method to create output page preview stream. |
| [setCreatePageStream(Delegates.CreatePageStream createPageStream)](#setCreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-) | Delegate which defines method to create output page preview stream. |
| [getReleasePageStream()](#getReleasePageStream--) | Delegate which defines method to remove output page preview stream. |
| [setReleasePageStream(Delegates.ReleasePageStream releasePageStream)](#setReleasePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-) | Delegate which defines method to remove output page preview stream. |
| [getWidth()](#getWidth--) | Preview width. |
| [setWidth(int value)](#setWidth-int-) | Preview width. |
| [getHeight()](#getHeight--) | Preview height. |
| [setHeight(int value)](#setHeight-int-) | Preview height. |
| [getPageNumbers()](#getPageNumbers--) | Page numbers that will be previewed. |
| [setPageNumbers(int[] value)](#setPageNumbers-int---) | Page numbers that will be previewed. |
| [getPreviewFormat()](#getPreviewFormat--) | Preview image format. |
| [setPreviewFormat(int value)](#setPreviewFormat-int-) | Preview image format. |
### PreviewOptions(Delegates.CreatePageStream createPageStream) {#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-}
```
public PreviewOptions(Delegates.CreatePageStream createPageStream)
```


Initializes a new instance of [PreviewOptions](../../com.groupdocs.comparison.options/previewoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.comparison.common.delegates/createpagestream) | Delegate which defines method to create output page preview stream. |

### PreviewOptions(Delegates.CreatePageStream createPageStream, Delegates.ReleasePageStream releasePageStream) {#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-}
```
public PreviewOptions(Delegates.CreatePageStream createPageStream, Delegates.ReleasePageStream releasePageStream)
```


Initializes a new instance of [PreviewOptions](../../com.groupdocs.comparison.options/previewoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.comparison.common.delegates/createpagestream) | Delegate which defines method to create output page preview stream. |
| releasePageStream | [ReleasePageStream](../../com.groupdocs.comparison.common.delegates/releasepagestream) | Delegate which defines method to release output page preview stream. |

### getCreatePageStream() {#getCreatePageStream--}
```
public Delegates.CreatePageStream getCreatePageStream()
```


Delegate which defines method to create output page preview stream.

**Returns:**
[CreatePageStream](../../com.groupdocs.comparison.common.delegates/createpagestream) - CreatePageStream callback
### setCreatePageStream(Delegates.CreatePageStream createPageStream) {#setCreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-}
```
public void setCreatePageStream(Delegates.CreatePageStream createPageStream)
```


Delegate which defines method to create output page preview stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.comparison.common.delegates/createpagestream) | CreatePageStream callback |

### getReleasePageStream() {#getReleasePageStream--}
```
public Delegates.ReleasePageStream getReleasePageStream()
```


Delegate which defines method to remove output page preview stream.

**Returns:**
[ReleasePageStream](../../com.groupdocs.comparison.common.delegates/releasepagestream) - ReleasePageStream callback
### setReleasePageStream(Delegates.ReleasePageStream releasePageStream) {#setReleasePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-}
```
public void setReleasePageStream(Delegates.ReleasePageStream releasePageStream)
```


Delegate which defines method to remove output page preview stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| releasePageStream | [ReleasePageStream](../../com.groupdocs.comparison.common.delegates/releasepagestream) | ReleasePageStream callback |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Preview width.

**Returns:**
int - width width
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Preview width.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | width |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Preview height.

**Returns:**
int - height height
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Preview height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | height |

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Page numbers that will be previewed.

**Returns:**
int[] - page numbers
### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Page numbers that will be previewed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] | page numbers |

### getPreviewFormat() {#getPreviewFormat--}
```
public final int getPreviewFormat()
```


Preview image format.

**Returns:**
int - preview format
### setPreviewFormat(int value) {#setPreviewFormat-int-}
```
public final void setPreviewFormat(int value)
```


Preview image format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | the value |

