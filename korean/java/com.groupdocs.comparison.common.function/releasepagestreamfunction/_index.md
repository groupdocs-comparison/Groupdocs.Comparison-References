---
title: "ReleasePageStreamFunction"
second_title: "GroupDocs.Comparison for Java API 참조"
description: "Comparison이 미리 보기 이미지를 저장하기 위해 사용한 출력 스트림을 닫는 데 사용되는 함수형 인터페이스입니다."
type: docs
weight: 11
url: /ko/java/com.groupdocs.comparison.common.function/releasepagestreamfunction/
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

