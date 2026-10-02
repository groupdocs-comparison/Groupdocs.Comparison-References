---
title: "Size"
second_title: "GroupDocs.Comparison for Java API 참조"
description: "비교에서 문서의 크기를 나타냅니다."
type: docs
weight: 11
url: /ko/java/com.groupdocs.comparison.options.style/size/
---
**Inheritance:**
java.lang.Object
```
public class Size
```

비교에서 문서의 크기를 나타냅니다.


사용 예시:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     final Size originalSize = new Size(100, 200);

     StyleSettings styleSettings = new StyleSettings();
     styleSettings.setOriginalSize(originalSize);

     final CompareOptions compareOptions = new CompareOptions();
     compareOptions.setInsertedItemStyle(styleSettings);

     comparer.compare(resultFile, compareOptions);
 }
 
````


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [Size()](#Size--) | Size 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [Size(int width, int height)](#Size-int-int-) | 문서의 너비와 높이를 사용하여 Size 클래스의 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getWidth()](#getWidth--) | 원본 문서의 너비를 가져옵니다. |
|
|  | [setWidth(int value)](#setWidth-int-) | 원본 문서의 너비를 설정합니다. |
|
|  | [getHeight()](#getHeight--) | 원본 문서의 높이를 가져옵니다. |
|
|  | [setHeight(int value)](#setHeight-int-) | 원본 문서의 높이를 설정합니다. |
|
### Size() {#Size--}
```
public Size()
```


Size 클래스의 새 인스턴스를 초기화합니다.


### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


문서의 너비와 높이를 사용하여 Size 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| width | int |  |
| height | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


원본 문서의 너비를 가져옵니다.


**Returns:**
int - 문서의 너비

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


원본 문서의 너비를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | int | 문서의 너비 |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


원본 문서의 높이를 가져옵니다.


**Returns:**
int - 문서의 높이

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


원본 문서의 높이를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | int | 문서의 높이 |
|

