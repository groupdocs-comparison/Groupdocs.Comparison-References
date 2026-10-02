---
title: "ChangeInfo"
second_title: "GroupDocs.Comparison for Java API 참조"
description: "ChangeInfo 클래스는 문서 비교에서 특정 변경에 대한 정보를 나타냅니다."
type: docs
weight: 10
url: /ko/java/com.groupdocs.comparison.result/changeinfo/
---
**Inheritance:**
java.lang.Object
```
public class ChangeInfo
```

ChangeInfo 클래스는 문서 비교에서 특정 변경에 대한 정보를 나타냅니다.


변경 유형, 영향을 받은 영역, 그리고 변경 전후의 내용을 포함한 세부 정보를 제공합니다.
이 클래스를 사용하여 비교 결과 내 개별 변경에 대한 정보를 검색합니다.


사용 예시:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     comparer.compare(resultFile);
     // Get a list of changes from the comparison result
     ChangeInfo[] changes = comparer.getChanges();
     // Iterate through the changes and retrieve information
     for (ChangeInfo change : changes) {
         ChangeType changeType = change.getType();
         String componentType = change.getComponentType();
         PageInfo pageInfo = change.getPageInfo();
         // Process the change information as needed
         // ...
     }
 }
 
````


## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ChangeInfo()](#ChangeInfo--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getRow()](#getRow--) |  |
| [setRow(Integer row)](#setRow-java.lang.Integer-) |  |
| [getColumn()](#getColumn--) |  |
| [setColumn(Integer column)](#setColumn-java.lang.Integer-) |  |
| [getColumnHeader()](#getColumnHeader--) |  |
| [setColumnHeader(String columnHeader)](#setColumnHeader-java.lang.String-) |  |
|  | [getId()](#getId--) | 변경의 고유 ID를 가져옵니다. |
|
|  | [setId(int value)](#setId-int-) | 변경의 고유 ID를 설정합니다. |
|
|  | [getComparisonAction()](#getComparisonAction--) | 변경에 적용될 작업을 가져옵니다. |
|
|  | [setComparisonAction(ComparisonAction value)](#setComparisonAction-com.groupdocs.comparison.result.ComparisonAction-) | 변경에 적용되어야 할 작업을 설정합니다. |
|
|  | [getPageInfo()](#getPageInfo--) | 현재 변경이 발견된 페이지에 대한 정보를 가져옵니다. |
|
|  | [setPageInfo(PageInfo value)](#setPageInfo-com.groupdocs.comparison.result.PageInfo-) | 현재 변경이 발견된 페이지에 대한 정보를 설정합니다. |
|
|  | [getBox()](#getBox--) | 페이지에서 변경된 요소의 좌표를 가져옵니다. |
|
|  | [setBox(Rectangle value)](#setBox-com.groupdocs.comparison.result.Rectangle-) | 페이지에서 변경된 요소의 좌표를 설정합니다. |
|
|  | [getText()](#getText--) | 변경의 텍스트 값을 가져옵니다. |
|
|  | [setText(String value)](#setText-java.lang.String-) | 변경의 텍스트 값을 설정합니다. |
|
|  | [getStyleChanges()](#getStyleChanges--) | 스타일 변경 목록을 가져옵니다. |
|
|  | [setStyleChanges(List<StyleChangeInfo> value)](#setStyleChanges-java.util.List-com.groupdocs.comparison.result.StyleChangeInfo--) | 스타일 변경 목록을 설정합니다. |
|
|  | [getAuthors()](#getAuthors--) | 작성자 목록을 가져옵니다. |
|
|  | [setAuthors(List<String> value)](#setAuthors-java.util.List-java.lang.String--) | 작성자 목록을 설정합니다. |
|
|  | [getType()](#getType--) | enum [ChangeType](../../com.groupdocs.comparison.result/changetype)으로 표시된 변경 유형을 가져옵니다. |
|
|  | [getTargetText()](#getTargetText--) | 대상 문서에서 변경된 텍스트를 가져옵니다. |
|
|  | [setTargetText(String value)](#setTargetText-java.lang.String-) | 대상 문서에서 변경된 텍스트를 설정합니다. |
|
|  | [getSourceText()](#getSourceText--) | 원본 문서에서 변경된 텍스트를 가져옵니다. |
|
|  | [setSourceText(String value)](#setSourceText-java.lang.String-) | 소스 문서에서 변경된 텍스트를 설정합니다. |
|
|  | [getComponentType()](#getComponentType--) | 변경된 구성 요소의 유형을 가져옵니다. |
|
|  | [setComponentType(String value)](#setComponentType-java.lang.String-) | 변경된 구성 요소의 유형을 설정합니다. |
|
| [toString()](#toString--) |  |
### ChangeInfo() {#ChangeInfo--}
```
public ChangeInfo()
```


### getRow() {#getRow--}
```
public Integer getRow()
```




**Returns:**
java.lang.Integer
### setRow(Integer row) {#setRow-java.lang.Integer-}
```
public void setRow(Integer row)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 행 | java.lang.Integer |  |

### getColumn() {#getColumn--}
```
public Integer getColumn()
```




**Returns:**
java.lang.Integer
### setColumn(Integer column) {#setColumn-java.lang.Integer-}
```
public void setColumn(Integer column)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 열 | java.lang.Integer |  |

### getColumnHeader() {#getColumnHeader--}
```
public String getColumnHeader()
```




**Returns:**
java.lang.String
### setColumnHeader(String columnHeader) {#setColumnHeader-java.lang.String-}
```
public void setColumnHeader(String columnHeader)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| columnHeader | java.lang.String |  |

### getId() {#getId--}
```
public final int getId()
```


변경의 고유 ID를 가져옵니다.


**Returns:**
int - 변경의 ID

### setId(int value) {#setId-int-}
```
public final void setId(int value)
```


변경의 고유 ID를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | int | 변경의 ID |
|

### getComparisonAction() {#getComparisonAction--}
```
public final ComparisonAction getComparisonAction()
```


변경에 적용될 작업을 가져옵니다.
Action ([ComparisonAction.ACCEPT](../../com.groupdocs.comparison.result/comparisonaction#ACCEPT) or [ComparisonAction.REJECT](../../com.groupdocs.comparison.result/comparisonaction#REJECT)) 은(는) 비교에 이 변경을 어떻게 처리할지 알려줍니다.


**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) - the action that will be applied to the change

### setComparisonAction(ComparisonAction value) {#setComparisonAction-com.groupdocs.comparison.result.ComparisonAction-}
```
public final void setComparisonAction(ComparisonAction value)
```


변경에 적용되어야 할 작업을 설정합니다.
Action ([ComparisonAction.ACCEPT](../../com.groupdocs.comparison.result/comparisonaction#ACCEPT) or [ComparisonAction.REJECT](../../com.groupdocs.comparison.result/comparisonaction#REJECT)) 은(는) 비교에 이 변경을 어떻게 처리할지 알려줍니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | value | [ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) | 변경에 적용되어야 하는 작업 |
|

### getPageInfo() {#getPageInfo--}
```
public final PageInfo getPageInfo()
```


현재 변경이 발견된 페이지에 대한 정보를 가져옵니다.


**Returns:**
[PageInfo](../../com.groupdocs.comparison.result/pageinfo) - information about the page

### setPageInfo(PageInfo value) {#setPageInfo-com.groupdocs.comparison.result.PageInfo-}
```
public final void setPageInfo(PageInfo value)
```


현재 변경이 발견된 페이지에 대한 정보를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | value | [PageInfo](../../com.groupdocs.comparison.result/pageinfo) | 페이지에 대한 정보 |
|

### getBox() {#getBox--}
```
public final Rectangle getBox()
```


페이지에서 변경된 요소의 좌표를 가져옵니다.


**Returns:**
[Rectangle](../../com.groupdocs.comparison.result/rectangle) - coordinates of changed element

### setBox(Rectangle value) {#setBox-com.groupdocs.comparison.result.Rectangle-}
```
public final void setBox(Rectangle value)
```


페이지에서 변경된 요소의 좌표를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | value | [Rectangle](../../com.groupdocs.comparison.result/rectangle) | 변경된 요소의 좌표, null이 아님 |
|

### getText() {#getText--}
```
public final String getText()
```


변경의 텍스트 값을 가져옵니다.


**Returns:**
java.lang.String - 변경의 텍스트 값

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


변경의 텍스트 값을 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | java.lang.String | 변경의 텍스트 값 |
|

### getStyleChanges() {#getStyleChanges--}
```
public final List<StyleChangeInfo> getStyleChanges()
```


스타일 변경 목록을 가져옵니다.


**Returns:**
java.util.List<com.groupdocs.comparison.result.StyleChangeInfo> - 스타일 변경 목록

### setStyleChanges(List<StyleChangeInfo> value) {#setStyleChanges-java.util.List-com.groupdocs.comparison.result.StyleChangeInfo--}
```
public final void setStyleChanges(List<StyleChangeInfo> value)
```


스타일 변경 목록을 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | java.util.List<com.groupdocs.comparison.result.StyleChangeInfo> | 스타일 변경 목록 |
|

### getAuthors() {#getAuthors--}
```
public final List<String> getAuthors()
```


작성자 목록을 가져옵니다.


**Returns:**
java.util.List<java.lang.String> - 작성자 목록

### setAuthors(List<String> value) {#setAuthors-java.util.List-java.lang.String--}
```
public final void setAuthors(List<String> value)
```


작성자 목록을 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | java.util.List<java.lang.String> | 작성자 목록 |
|

### getType() {#getType--}
```
public final ChangeType getType()
```


enum [ChangeType](../../com.groupdocs.comparison.result/changetype)으로 표시된 변경 유형을 가져옵니다.


**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - the type of the change

### getTargetText() {#getTargetText--}
```
public String getTargetText()
```


대상 문서에서 변경된 텍스트를 가져옵니다.


**Returns:**
java.lang.String - 변경된 텍스트

### setTargetText(String value) {#setTargetText-java.lang.String-}
```
public void setTargetText(String value)
```


대상 문서에서 변경된 텍스트를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | java.lang.String | 변경된 텍스트 |
|

### getSourceText() {#getSourceText--}
```
public String getSourceText()
```


원본 문서에서 변경된 텍스트를 가져옵니다.


**Returns:**
java.lang.String - 변경된 텍스트

### setSourceText(String value) {#setSourceText-java.lang.String-}
```
public void setSourceText(String value)
```


소스 문서에서 변경된 텍스트를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | java.lang.String | 변경된 텍스트 |
|

### getComponentType() {#getComponentType--}
```
public String getComponentType()
```


변경된 구성 요소의 유형을 가져옵니다.


**Returns:**
java.lang.String - 변경된 구성 요소의 유형

### setComponentType(String value) {#setComponentType-java.lang.String-}
```
public void setComponentType(String value)
```


변경된 구성 요소의 유형을 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | java.lang.String | 변경된 구성 요소의 유형 |
|

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
