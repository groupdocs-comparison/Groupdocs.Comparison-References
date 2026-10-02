---
title: "OriginalSize"
second_title: "GroupDocs.Comparison for Java API 참조"
description: "비교 결과에서 문서의 원래 크기를 나타냅니다."
type: docs
weight: 14
url: /ko/java/com.groupdocs.comparison.options/originalsize/
---
**Inheritance:**
java.lang.Object
```
public class OriginalSize
```

비교 결과에서 문서의 원래 크기를 나타냅니다.


원래 크기에는 문서 페이지의 차원(너비와 높이)이 포함됩니다.


사용 예시:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     CompareOptions compareOptions = new CompareOptions();
     final OriginalSize originalSize = compareOptions.getOriginalSize();
     originalSize.setWidth(480);
     originalSize.setHeight(640);

     comparer.compare(resultFile, compareOptions);
 }
 
````


## 생성자

| 생성자 | 설명 |
| --- | --- |
| [OriginalSize()](#OriginalSize--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getWidth()](#getWidth--) | 문서 페이지의 너비를 가져옵니다. |
|
|  | [setWidth(int value)](#setWidth-int-) | 문서 페이지의 너비를 설정합니다. |
|
|  | [getHeight()](#getHeight--) | 문서 페이지의 높이를 가져옵니다. |
|
|  | [setHeight(int value)](#setHeight-int-) | 문서 페이지의 높이를 설정합니다. |
|
### OriginalSize() {#OriginalSize--}
```
public OriginalSize()
```


### getWidth() {#getWidth--}
```
public final int getWidth()
```


문서 페이지의 너비를 가져옵니다.


**Returns:**
int - 문서 페이지의 너비.

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


문서 페이지의 너비를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | int | 문서 페이지의 너비. |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


문서 페이지의 높이를 가져옵니다.


**Returns:**
int - 문서 페이지의 높이.

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


문서 페이지의 높이를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | int | 문서 페이지의 높이. |
|

