---
title: "ReleasePageStreamFunction"
second_title: "GroupDocs.Comparison voor Java API-referentie"
description: "Functionele interface die wordt gebruikt om de outputstream te sluiten die door Comparison werd gebruikt om een voorbeeldafbeelding op te slaan."
type: docs
weight: 11
url: /nl/java/com.groupdocs.comparison.common.function/releasepagestreamfunction/
---```
public interface ReleasePageStreamFunction
```

Functional interface that is used to close output stream that was used by Comparison to save preview image.


More details about its usage can be found in [PreviewOptions](../../com.groupdocs.comparison.options/previewoptions) class or in a [documentation](../https://docs.groupdocs.com/comparison/java/generate-document-pages-preview/).


Example usage:

````

 PreviewOptions previewOptions = new PreviewOptions(pageNumber -> {
    return new FileOutputStream("/path/page-" + pageNumber + ".png");
 }, (pageNumber, pageStream) -> {
    // do something
    pageStream.close();
 });
 
````


## Methods

| Method | Description |
| --- | --- |
| [invoke(int pageNumber, OutputStream pageStream)](#invoke-int-java.io.OutputStream-) | Function that is called by Comparison to close output stream where page preview image was saved.
 |
### invoke(int pageNumber, OutputStream pageStream) {#invoke-int-java.io.OutputStream-}
```
public abstract void invoke(int pageNumber, OutputStream pageStream)
```


Function that is called by Comparison to close output stream where page preview image was saved.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | The number of previewed page.
 |
| pageStream | java.io.OutputStream | The stream to be closed.
 |

