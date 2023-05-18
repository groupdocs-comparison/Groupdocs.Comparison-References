---
title: PreviewOptions
second_title: GroupDocs.Comparison for Java API Reference
description: Provides options for generating document previews in the comparison process.
type: docs
weight: 15
url: /java/com.groupdocs.comparison.options/previewoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewOptions
```

Provides options for generating document previews in the comparison process.

Example usage:

```

 try (Comparer comparer = new Comparer(sourceFile)) {

    PreviewOptions previewOptions = new PreviewOptions(
            pageNumber -> Files.newOutputStream(Paths.get(String.format("preview-page_%d.png", pageNumber)))
    );
    previewOptions.setPreviewFormat(PreviewFormats.PNG);
    previewOptions.setPageNumbers(new int[]{1, 2});

    comparer.getSource().generatePreview(previewOptions);
 }
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [PreviewOptions(Delegates.CreatePageStream createPageStream)](#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-) | Initializes a new instance of the PreviewOptions class specifying Delegates.CreatePageStream function. |
| [PreviewOptions(CreatePageStreamFunction createPageStream)](#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-) | Initializes a new instance of the PreviewOptions class specifying [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) function. |
| [PreviewOptions(Delegates.CreatePageStream createPageStream, Delegates.ReleasePageStream releasePageStream)](#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-) | Initializes a new instance of the PreviewOptions class specifying Delegates.CreatePageStream and Delegates.ReleasePageStream function. |
| [PreviewOptions(CreatePageStreamFunction createPageStream, ReleasePageStreamFunction releasePageStream)](#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-) | Initializes a new instance of the PreviewOptions class specifying [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) and [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) function. |
## Methods

| Method | Description |
| --- | --- |
| [getCreatePageStream()](#getCreatePageStream--) | Gets a function to create output page preview stream. |
| [setCreatePageStream(Delegates.CreatePageStream createPageStream)](#setCreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-) | Sets a function to create output page preview stream. |
| [setCreatePageStream(CreatePageStreamFunction createPageStream)](#setCreatePageStream-com.groupdocs.comparison.common.function.CreatePageStreamFunction-) | Sets a function to create output page preview stream. |
| [getReleasePageStream()](#getReleasePageStream--) | Gets a function to release output page preview stream. |
| [setReleasePageStream(Delegates.ReleasePageStream releasePageStream)](#setReleasePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-) | Gets a function to release output page preview stream. |
| [setReleasePageStream(ReleasePageStreamFunction releasePageStream)](#setReleasePageStream-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-) | Sets a function to release output page preview stream. |
| [getWidth()](#getWidth--) | Gets the width of the preview images. |
| [setWidth(int value)](#setWidth-int-) | Sets the width of the preview images. |
| [getHeight()](#getHeight--) | Gets the height of the preview images. |
| [setHeight(int value)](#setHeight-int-) | Sets the height of the preview images. |
| [getPageNumbers()](#getPageNumbers--) | Gets an array of page numbers for which preview images will be generated. |
| [setPageNumbers(int[] value)](#setPageNumbers-int---) | Sets an array of page numbers for which preview images will be generated. |
| [getPreviewFormat()](#getPreviewFormat--) | Gets a format of preview images. |
| [setPreviewFormat(PreviewFormats value)](#setPreviewFormat-com.groupdocs.comparison.options.enums.PreviewFormats-) | Sets a format of preview images. |
### PreviewOptions(Delegates.CreatePageStream createPageStream) {#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-}
```
public PreviewOptions(Delegates.CreatePageStream createPageStream)
```


Initializes a new instance of the PreviewOptions class specifying Delegates.CreatePageStream function.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.comparison.common.delegates/createpagestream) | The function to create output page preview stream. |

### PreviewOptions(CreatePageStreamFunction createPageStream) {#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-}
```
public PreviewOptions(CreatePageStreamFunction createPageStream)
```


Initializes a new instance of the PreviewOptions class specifying [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) function.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) | The function to create output page preview stream. |

### PreviewOptions(Delegates.CreatePageStream createPageStream, Delegates.ReleasePageStream releasePageStream) {#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-}
```
public PreviewOptions(Delegates.CreatePageStream createPageStream, Delegates.ReleasePageStream releasePageStream)
```


Initializes a new instance of the PreviewOptions class specifying Delegates.CreatePageStream and Delegates.ReleasePageStream function.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.comparison.common.delegates/createpagestream) | The function to create output page preview stream. |
| releasePageStream | [ReleasePageStream](../../com.groupdocs.comparison.common.delegates/releasepagestream) | The function to release output page preview stream. |

### PreviewOptions(CreatePageStreamFunction createPageStream, ReleasePageStreamFunction releasePageStream) {#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-}
```
public PreviewOptions(CreatePageStreamFunction createPageStream, ReleasePageStreamFunction releasePageStream)
```


Initializes a new instance of the PreviewOptions class specifying [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) and [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) function.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) | The function to create output page preview stream. |
| releasePageStream | [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) | The function to release output page preview stream. |

### getCreatePageStream() {#getCreatePageStream--}
```
public CreatePageStreamFunction getCreatePageStream()
```


Gets a function to create output page preview stream.

**Returns:**
[CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) - the function to create output page preview stream.
### setCreatePageStream(Delegates.CreatePageStream createPageStream) {#setCreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-}
```
public void setCreatePageStream(Delegates.CreatePageStream createPageStream)
```


Sets a function to create output page preview stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.comparison.common.delegates/createpagestream) | The function to create output page preview stream. |

### setCreatePageStream(CreatePageStreamFunction createPageStream) {#setCreatePageStream-com.groupdocs.comparison.common.function.CreatePageStreamFunction-}
```
public void setCreatePageStream(CreatePageStreamFunction createPageStream)
```


Sets a function to create output page preview stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) | The function to create output page preview stream. |

### getReleasePageStream() {#getReleasePageStream--}
```
public ReleasePageStreamFunction getReleasePageStream()
```


Gets a function to release output page preview stream.

**Returns:**
[ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) - the function to release output page preview stream.
### setReleasePageStream(Delegates.ReleasePageStream releasePageStream) {#setReleasePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-}
```
public void setReleasePageStream(Delegates.ReleasePageStream releasePageStream)
```


Gets a function to release output page preview stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| releasePageStream | [ReleasePageStream](../../com.groupdocs.comparison.common.delegates/releasepagestream) | The function to release output page preview stream. |

### setReleasePageStream(ReleasePageStreamFunction releasePageStream) {#setReleasePageStream-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-}
```
public void setReleasePageStream(ReleasePageStreamFunction releasePageStream)
```


Sets a function to release output page preview stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| releasePageStream | [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) | The function to release output page preview stream. |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Gets the width of the preview images.

**Returns:**
int - the width of the preview images.
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Sets the width of the preview images.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The width of the preview images. |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Gets the height of the preview images.

**Returns:**
int - the height of the preview images.
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Sets the height of the preview images.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The height of the preview images. |

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Gets an array of page numbers for which preview images will be generated.

**Returns:**
int[] - page numbers array
### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Sets an array of page numbers for which preview images will be generated.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] | Page numbers array |

### getPreviewFormat() {#getPreviewFormat--}
```
public final PreviewFormats getPreviewFormat()
```


Gets a format of preview images.

**Returns:**
[PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats) - preview images format
### setPreviewFormat(PreviewFormats value) {#setPreviewFormat-com.groupdocs.comparison.options.enums.PreviewFormats-}
```
public final void setPreviewFormat(PreviewFormats value)
```


Sets a format of preview images.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats) | Preview images format |

