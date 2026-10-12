---
title: "PageInfo"
second_title: "GroupDocs.Comparison for Java API 참조"
description: "PageInfo 클래스는 문서의 특정 페이지에 대한 정보를 나타냅니다."
type: docs
weight: 11
url: /ko/java/com.groupdocs.comparison.result/pageinfo/
---
**Inheritance:**
java.lang.Object
```
public class PageInfo
```

PageInfo 클래스는 문서의 특정 페이지에 대한 정보를 나타냅니다.


페이지 번호, 너비, 높이 및 기타 관련 속성과 같은 세부 정보를 제공합니다.
비교 과정 중 문서의 개별 페이지에 대한 정보를 검색하려면 이 클래스를 사용하십시오.


사용 예시:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     comparer.compare(resultFile);
     final ChangeInfo[] changes = comparer.getChanges();
     for (ChangeInfo change : changes) {
         final PageInfo pageInfo = change.getPageInfo();
         // Print the page information
         System.out.println("Page Number: " + pageInfo.getPageNumber());
         System.out.println("Page Width: " + pageInfo.getWidth());
         System.out.println("Page Height: " + pageInfo.getHeight());
     }
 }
 
````


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [PageInfo(int pageNumber, int width, int height)](#PageInfo-int-int-int-) | pageNumber, 너비 및 높이를 구성하여 PageInfo 클래스의 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getWidth()](#getWidth--) | 페이지의 너비를 가져옵니다 |
|
|  | [setWidth(int value)](#setWidth-int-) | 페이지의 너비를 설정합니다 |
|
|  | [getHeight()](#getHeight--) | 페이지의 높이를 가져옵니다 |
|
|  | [setHeight(int value)](#setHeight-int-) | 페이지의 높이를 설정합니다 |
|
|  | [getPageNumber()](#getPageNumber--) | 페이지 번호를 가져옵니다 |
|
|  | [setPageNumber(int value)](#setPageNumber-int-) | 페이지 번호를 설정합니다 |
|
| [toString()](#toString--) |  |
### PageInfo(int pageNumber, int width, int height) {#PageInfo-int-int-int-}
```
public PageInfo(int pageNumber, int width, int height)
```


pageNumber, 너비 및 높이를 구성하여 PageInfo 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | pageNumber | int | 페이지 번호 |
|
|  | width | int | 페이지의 너비 |
|
|  | height | int | 페이지의 높이 |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


페이지의 너비를 가져옵니다


**Returns:**
int - 페이지의 너비

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


페이지의 너비를 설정합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | int | 페이지의 너비 |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


페이지의 높이를 가져옵니다


**Returns:**
int - 페이지의 높이

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


페이지의 높이를 설정합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | int | 페이지의 높이 |
|

### getPageNumber() {#getPageNumber--}
```
public final int getPageNumber()
```


페이지 번호를 가져옵니다


**Returns:**
int - 페이지 번호

### setPageNumber(int value) {#setPageNumber-int-}
```
public final void setPageNumber(int value)
```


페이지 번호를 설정합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | int | 페이지 번호 |
|

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
