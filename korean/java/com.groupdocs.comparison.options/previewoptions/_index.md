---
title: "PreviewOptions"
second_title: "GroupDocs.Comparison for Java API 참조"
description: "비교 프로세스에서 문서 미리보기를 생성하기 위한 옵션을 제공합니다."
type: docs
weight: 15
url: /ko/java/com.groupdocs.comparison.options/previewoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewOptions
```

비교 프로세스에서 문서 미리보기를 생성하기 위한 옵션을 제공합니다.


사용 예시:

````

 try (Comparer comparer = new Comparer(sourceFile)) {

    PreviewOptions previewOptions = new PreviewOptions(
            pageNumber -> Files.newOutputStream(Paths.get(String.format("preview-page_%d.png", pageNumber)))
    );
    previewOptions.setPreviewFormat(PreviewFormats.PNG);
    previewOptions.setPageNumbers(new int[]{1, 2});

    comparer.getSource().generatePreview(previewOptions);
 }
 
````


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [PreviewOptions(Delegates.CreatePageStream createPageStream)](#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-) | Delegates.CreatePageStream 함수를 지정하여 PreviewOptions 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [PreviewOptions(CreatePageStreamFunction createPageStream)](#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-) | 함수 [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction)를 지정하여 PreviewOptions 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [PreviewOptions(Delegates.CreatePageStream createPageStream, Delegates.ReleasePageStream releasePageStream)](#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-) | Delegates.CreatePageStream 및 Delegates.ReleasePageStream 함수를 지정하여 PreviewOptions 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [PreviewOptions(CreatePageStreamFunction createPageStream, ReleasePageStreamFunction releasePageStream)](#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-) | 함수 [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction)와 [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction)를 지정하여 PreviewOptions 클래스의 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getCreatePageStream()](#getCreatePageStream--) | 출력 페이지 미리보기 스트림을 생성하는 함수를 가져옵니다. |
|
|  | [setCreatePageStream(Delegates.CreatePageStream createPageStream)](#setCreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-) | 출력 페이지 미리보기 스트림을 생성하는 함수를 설정합니다. |
|
|  | [setCreatePageStream(CreatePageStreamFunction createPageStream)](#setCreatePageStream-com.groupdocs.comparison.common.function.CreatePageStreamFunction-) | 출력 페이지 미리보기 스트림을 생성하는 함수를 설정합니다. |
|
|  | [getReleasePageStream()](#getReleasePageStream--) | 출력 페이지 미리보기 스트림을 해제하는 함수를 가져옵니다. |
|
|  | [setReleasePageStream(Delegates.ReleasePageStream releasePageStream)](#setReleasePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-) | 출력 페이지 미리보기 스트림을 해제하는 함수를 가져옵니다. |
|
|  | [setReleasePageStream(ReleasePageStreamFunction releasePageStream)](#setReleasePageStream-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-) | 출력 페이지 미리보기 스트림을 해제하는 함수를 설정합니다. |
|
|  | [getWidth()](#getWidth--) | 미리 보기 이미지의 너비를 가져옵니다. |
|
|  | [setWidth(int value)](#setWidth-int-) | 미리 보기 이미지의 너비를 설정합니다. |
|
|  | [getHeight()](#getHeight--) | 미리 보기 이미지의 높이를 가져옵니다. |
|
|  | [setHeight(int value)](#setHeight-int-) | 미리 보기 이미지의 높이를 설정합니다. |
|
|  | [getPageNumbers()](#getPageNumbers--) | 미리 보기 이미지가 생성될 페이지 번호 배열을 가져옵니다. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | 미리 보기 이미지가 생성될 페이지 번호 배열을 설정합니다. |
|
|  | [getPreviewFormat()](#getPreviewFormat--) | 미리 보기 이미지 형식을 가져옵니다. |
|
|  | [setPreviewFormat(PreviewFormats value)](#setPreviewFormat-com.groupdocs.comparison.options.enums.PreviewFormats-) | 미리 보기 이미지 형식을 설정합니다. |
|
### PreviewOptions(Delegates.CreatePageStream createPageStream) {#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-}
```
public PreviewOptions(Delegates.CreatePageStream createPageStream)
```


Delegates.CreatePageStream 함수를 지정하여 PreviewOptions 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.comparison.common.delegates/createpagestream) | 출력 페이지 미리 보기 스트림을 생성하는 함수입니다. |
|

### PreviewOptions(CreatePageStreamFunction createPageStream) {#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-}
```
public PreviewOptions(CreatePageStreamFunction createPageStream)
```


함수 [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction)를 지정하여 PreviewOptions 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | createPageStream | [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) | 출력 페이지 미리 보기 스트림을 생성하는 함수입니다. |
|

### PreviewOptions(Delegates.CreatePageStream createPageStream, Delegates.ReleasePageStream releasePageStream) {#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-}
```
public PreviewOptions(Delegates.CreatePageStream createPageStream, Delegates.ReleasePageStream releasePageStream)
```


Delegates.CreatePageStream 및 Delegates.ReleasePageStream 함수를 지정하여 PreviewOptions 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.comparison.common.delegates/createpagestream) | 출력 페이지 미리 보기 스트림을 생성하는 함수입니다. |
|
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.comparison.common.delegates/releasepagestream) | 출력 페이지 미리 보기 스트림을 해제하는 함수입니다. |
|

### PreviewOptions(CreatePageStreamFunction createPageStream, ReleasePageStreamFunction releasePageStream) {#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-}
```
public PreviewOptions(CreatePageStreamFunction createPageStream, ReleasePageStreamFunction releasePageStream)
```


함수 [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction)와 [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction)를 지정하여 PreviewOptions 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | createPageStream | [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) | 출력 페이지 미리 보기 스트림을 생성하는 함수입니다. |
|
|  | releasePageStream | [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) | 출력 페이지 미리 보기 스트림을 해제하는 함수입니다. |
|

### getCreatePageStream() {#getCreatePageStream--}
```
public CreatePageStreamFunction getCreatePageStream()
```


출력 페이지 미리보기 스트림을 생성하는 함수를 가져옵니다.


**Returns:**
[CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) - the function to create output page preview stream.

### setCreatePageStream(Delegates.CreatePageStream createPageStream) {#setCreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-}
```
public void setCreatePageStream(Delegates.CreatePageStream createPageStream)
```


출력 페이지 미리보기 스트림을 생성하는 함수를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.comparison.common.delegates/createpagestream) | 출력 페이지 미리 보기 스트림을 생성하는 함수입니다. |
|

### setCreatePageStream(CreatePageStreamFunction createPageStream) {#setCreatePageStream-com.groupdocs.comparison.common.function.CreatePageStreamFunction-}
```
public void setCreatePageStream(CreatePageStreamFunction createPageStream)
```


출력 페이지 미리보기 스트림을 생성하는 함수를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | createPageStream | [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) | 출력 페이지 미리 보기 스트림을 생성하는 함수입니다. |
|

### getReleasePageStream() {#getReleasePageStream--}
```
public ReleasePageStreamFunction getReleasePageStream()
```


출력 페이지 미리보기 스트림을 해제하는 함수를 가져옵니다.


**Returns:**
[ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) - the function to release output page preview stream.

### setReleasePageStream(Delegates.ReleasePageStream releasePageStream) {#setReleasePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-}
```
public void setReleasePageStream(Delegates.ReleasePageStream releasePageStream)
```


출력 페이지 미리보기 스트림을 해제하는 함수를 가져옵니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.comparison.common.delegates/releasepagestream) | 출력 페이지 미리 보기 스트림을 해제하는 함수입니다. |
|

### setReleasePageStream(ReleasePageStreamFunction releasePageStream) {#setReleasePageStream-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-}
```
public void setReleasePageStream(ReleasePageStreamFunction releasePageStream)
```


출력 페이지 미리보기 스트림을 해제하는 함수를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | releasePageStream | [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) | 출력 페이지 미리 보기 스트림을 해제하는 함수입니다. |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


미리 보기 이미지의 너비를 가져옵니다.


**Returns:**
int - 미리 보기 이미지의 너비.

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


미리 보기 이미지의 너비를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | int | 미리 보기 이미지의 너비. |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


미리 보기 이미지의 높이를 가져옵니다.


**Returns:**
int - 미리 보기 이미지의 높이.

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


미리 보기 이미지의 높이를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | int | 미리 보기 이미지의 높이. |
|

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


미리 보기 이미지가 생성될 페이지 번호 배열을 가져옵니다.


**Returns:**
int[] - 페이지 번호 배열

### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


미리 보기 이미지가 생성될 페이지 번호 배열을 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | int[] | 페이지 번호 배열 |
|

### getPreviewFormat() {#getPreviewFormat--}
```
public final PreviewFormats getPreviewFormat()
```


미리 보기 이미지 형식을 가져옵니다.


**Returns:**
[PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats) - preview images format

### setPreviewFormat(PreviewFormats value) {#setPreviewFormat-com.groupdocs.comparison.options.enums.PreviewFormats-}
```
public final void setPreviewFormat(PreviewFormats value)
```


미리 보기 이미지 형식을 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | value | [PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats) | 미리 보기 이미지 형식 |
|

