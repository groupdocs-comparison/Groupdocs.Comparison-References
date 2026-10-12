---
title: "PreviewFormats"
second_title: "GroupDocs.Comparison for Java API 참조"
description: "문서 비교를 위한 지원되는 미리보기 형식을 열거합니다."
type: docs
weight: 15
url: /ko/java/com.groupdocs.comparison.options.enums/previewformats/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PreviewFormats extends Enum<PreviewFormats>
```

문서 비교를 위한 지원되는 미리보기 형식을 열거합니다.
PreviewFormats 열거형은 비교된 문서의 미리보기를 생성하는 데 사용할 수 있는 형식 목록을 제공합니다.

지원되는 형식은 다음과 같습니다:

* #PNG.PNG - Portable Network Graphics (.png)
* #JPEG.JPEG - Joint Photographic Experts Group (.jpeg)
* #BMP.BMP - Bitmap Picture (.bmp)


사용 예시:

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


## 필드

| 필드 | 설명 |
| --- | --- |
|  | [PNG](#PNG) | PNG - 페이지에 다수의 컬러 그래픽이 포함된 경우 상당한 디스크 공간이나 네트워크 트래픽을 사용할 수 있습니다. |
|
|  | [JPEG](#JPEG) | Jpeg - 더 작은 디스크 공간 사용량과 네트워크 트래픽으로 빠른 처리를 제공하지만 이미지 품질이 낮아질 수 있습니다. |
|
|  | [BMP](#BMP) | BMP - 최고의 이미지 품질을 제공하지만 더 높은 디스크 공간 사용량과 네트워크 트래픽으로 처리 속도가 느려집니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | PreviewFormats의 문자열 표현을 구문 분석하여 열거형 상수를 가져옵니다. |
|
|  | [toString()](#toString--) | PreviewFormats의 문자열 표현. |
|
### PNG {#PNG}
```
public static final PreviewFormats PNG
```


PNG - 페이지에 다수의 컬러 그래픽이 포함된 경우 상당한 디스크 공간이나 네트워크 트래픽을 사용할 수 있습니다. 기본 미리보기 형식.


### JPEG {#JPEG}
```
public static final PreviewFormats JPEG
```


Jpeg - 더 작은 디스크 공간 사용량과 네트워크 트래픽으로 빠른 처리를 제공하지만 이미지 품질이 낮아질 수 있습니다.


### BMP {#BMP}
```
public static final PreviewFormats BMP
```


BMP - 최고의 이미지 품질을 제공하지만 더 높은 디스크 공간 사용량과 네트워크 트래픽으로 처리 속도가 느려집니다.


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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |

**Returns:**
[PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static PreviewFormats fromString(String toStringValue)
```


PreviewFormats의 문자열 표현을 구문 분석하여 열거형 상수를 가져옵니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | toStringValue | java.lang.String | PreviewFormats의 문자열 표현 |
|

**Returns:**
[PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats) - PreviewFormats enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


PreviewFormats의 문자열 표현.


**Returns:**
java.lang.String - enum 상수의 문자열 값

