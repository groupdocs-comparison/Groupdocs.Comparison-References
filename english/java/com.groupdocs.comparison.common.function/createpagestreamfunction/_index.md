---
title: CreatePageStreamFunction
second_title: GroupDocs.Comparison for Java API Reference
description: Functional interface that is used to create output stream used by Comparison to save preview image.
type: docs
weight: 10
url: /java/com.groupdocs.comparison.common.function/createpagestreamfunction/
---```
public interface CreatePageStreamFunction
```

Functional interface that is used to create output stream used by Comparison to save preview image.

More details about its usage can be found in [PreviewOptions](../../com.groupdocs.comparison.options/previewoptions) class or in a [documentation][].

Example usage:

```

 PreviewOptions previewOptions = new PreviewOptions(pageNumber -> {
     return new FileOutputStream("/path/to/pages/page-" + pageNumber + ".png");
 });
 
```


[documentation]: https://docs.groupdocs.com/comparison/java/generate-document-pages-preview/
## Methods

| Method | Description |
| --- | --- |
| [invoke(int pageNumber)](#invoke-int-) | Function that is called by Comparison to create output stream where page preview image will be saved. |
### invoke(int pageNumber) {#invoke-int-}
```
public abstract OutputStream invoke(int pageNumber)
```


Function that is called by Comparison to create output stream where page preview image will be saved.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | The number of previewed page. |

**Returns:**
java.io.OutputStream - stream to save image data
