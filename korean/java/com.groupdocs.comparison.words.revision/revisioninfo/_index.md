---
title: "RevisionInfo"
second_title: "GroupDocs.Comparison for Java API 참조"
description: "문서 내의 수정을 나타냅니다."
type: docs
weight: 12
url: /ko/java/com.groupdocs.comparison.words.revision/revisioninfo/
---
**Inheritance:**
java.lang.Object
```
public class RevisionInfo
```

문서 내의 수정을 나타냅니다.


수정은 문서에 적용된 수정 변경에 대한 정보를 캡슐화합니다.
이 클래스는 수정에 대한 정보를 검색하는 메서드를 제공하며, 예를 들어 유형,
내용, 작성자 등과 같은 정보를 제공합니다.

사용 예시:

````

 try (RevisionHandler revisionHandler = new RevisionHandler(sourceFile)) {
     List revisionList = revisionHandler.getRevisions();

     for (RevisionInfo revisionInfo : revisionList) {
         System.out.println("Revision Type: " + revisionInfo.getType());
         System.out.println("Text: " + revisionInfo.getText());
         System.out.println("Author: " + revisionInfo.getAuthor());
     }
 }
 
````


## 생성자

| 생성자 | 설명 |
| --- | --- |
| [RevisionInfo()](#RevisionInfo--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getAction()](#getAction--) | 수정과 연결된 작업(수락 또는 거부)을 가져옵니다. |
|
|  | [setAction(RevisionAction value)](#setAction-com.groupdocs.comparison.words.revision.RevisionAction-) | 수정과 연결된 값을 설정합니다(수락 또는 거부). |
|
|  | [getText()](#getText--) | 수정의 텍스트 내용을 가져옵니다. |
|
|  | [setText(String value)](#setText-java.lang.String-) | 수정의 값 내용을 설정합니다. |
|
|  | [getAuthor()](#getAuthor--) | 수정의 작성자를 가져옵니다. |
|
|  | [setAuthor(String value)](#setAuthor-java.lang.String-) | 수정의 값을 설정합니다. |
|
|  | [getType()](#getType--) | 수정의 유형을 가져옵니다. 유형에 따라 작업(수락 또는 거부) 로직이 변경됩니다. |
|
|  | [setType(RevisionType value)](#setType-com.groupdocs.comparison.words.revision.RevisionType-) | 수정의 값을 설정합니다. 값에 따라 작업(수락 또는 거부) 로직이 변경됩니다. |
|
### RevisionInfo() {#RevisionInfo--}
```
public RevisionInfo()
```


### getAction() {#getAction--}
```
public RevisionAction getAction()
```


수정과 연결된 작업(수락 또는 거부)을 가져옵니다. 이 필드를 사용하면 수정 표시를 제어할 수 있습니다.


**Returns:**
[RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) - the action associated with the revision.

### setAction(RevisionAction value) {#setAction-com.groupdocs.comparison.words.revision.RevisionAction-}
```
public void setAction(RevisionAction value)
```


수정과 연결된 값을 설정합니다(수락 또는 거부). 이 필드를 사용하면 수정 표시를 제어할 수 있습니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | value | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | 수정과 연결된 값. |
|

### getText() {#getText--}
```
public String getText()
```


수정의 텍스트 내용을 가져옵니다.


**Returns:**
java.lang.String - 수정의 텍스트 내용.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


수정의 값 내용을 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | java.lang.String | 수정의 값 내용. |
|

### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


수정의 작성자를 가져옵니다.


**Returns:**
java.lang.String - 수정의 작성자.

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public void setAuthor(String value)
```


수정의 값을 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | java.lang.String | 수정의 값. |
|

### getType() {#getType--}
```
public RevisionType getType()
```


수정의 유형을 가져옵니다. 유형에 따라 작업(수락 또는 거부) 로직이 변경됩니다.


**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) - the type of the revision.

### setType(RevisionType value) {#setType-com.groupdocs.comparison.words.revision.RevisionType-}
```
public void setType(RevisionType value)
```


수정의 값을 설정합니다. 값에 따라 작업(수락 또는 거부) 로직이 변경됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | value | [RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) | 수정의 값. |
|

