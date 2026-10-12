---
title: "CreatePageStreamFunction"
second_title: "GroupDocs.Comparison for Java API 참조"
description: "Comparison이 미리 보기 이미지를 저장하기 위해 사용하는 출력 스트림을 생성하는 데 사용되는 함수형 인터페이스입니다."
type: docs
weight: 10
url: /ko/java/com.groupdocs.comparison.common.function/createpagestreamfunction/
---```
public interface CreatePageStreamFunction
```

Functional interface that is used to create output stream used by Comparison to save preview image.


More details about its usage can be found in [PreviewOptions](../../com.groupdocs.comparison.options/previewoptions) class or in a [documentation](../https://docs.groupdocs.com/comparison/java/generate-document-pages-preview/).


Example usage:

````

 PreviewOptions previewOptions = new PreviewOptions(pageNumber -> {
     return new FileOutputStream("/path/to/pages/page-" + pageNumber + ".png");
 });
 
````


## Methods

| Method | Description |
| --- | --- |
| [invoke(int pageNumber)](#invoke-int-) | Function that is called by Comparison to create output stream where page preview image will be saved.
 |
### invoke(int pageNumber) {#invoke-int-}
```
public abstract OutputStream invoke(int pageNumber)
```


Function that is called by Comparison to create output stream where page preview image will be saved.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | The number of previewed page.
 |

**Returns:**
java.io.OutputStream - stream to save image data

