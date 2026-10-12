---
title: "RevisionType"
second_title: "GroupDocs.Comparison for Java API 참조"
description: "문서의 수정 유형을 나타냅니다."
type: docs
weight: 14
url: /ko/java/com.groupdocs.comparison.words.revision/revisiontype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum RevisionType extends Enum<RevisionType>
```

문서의 수정 유형을 나타냅니다.


사용 예시:

````

 try (RevisionHandler revisionHandler = new RevisionHandler(sourceFile)) {
     List revisionList = revisionHandler.getRevisions();

     for (RevisionInfo revisionInfo : revisionList) {
         if (revisionInfo.getType() == RevisionType.DELETION)
             // Set an action to be applied to the revision
             revisionInfo.setAction(RevisionAction.Accept);
     }
     // Create an instance of ApplyRevisionOptions
     ApplyRevisionOptions revisionChanges = new ApplyRevisionOptions();
     revisionChanges.setChanges(revisionList);
     // Apply the revisions using the options
     revisionHandler.applyRevisionChanges(resultFile, revisionChanges);
 }
 
````


## 필드

| 필드 | 설명 |
| --- | --- |
|  | [INSERTION](#INSERTION) | 문서에 새 콘텐츠가 삽입될 때의 유형을 나타냅니다. |
|
|  | [DELETION](#DELETION) | 문서에서 콘텐츠가 제거될 때의 유형을 나타냅니다. |
|
|  | [FORMAT_CHANGE](#FORMAT-CHANGE) | 부모 노드에 서식 변경이 적용될 때의 유형을 나타냅니다. |
|
|  | [STYLE_DEFINITION_CHANGE](#STYLE-DEFINITION-CHANGE) | 부모 스타일에 서식 변경이 적용될 때의 유형을 나타냅니다. |
|
|  | [MOVING](#MOVING) | 문서 내에서 콘텐츠가 이동될 때의 유형을 나타냅니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromInt(int toIntValue)](#fromInt-int-) | 제공된 숫자 값을 사용하여 enum RevisionType의 새 상수를 생성합니다. |
|
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | RevisionType의 문자열 표현을 파싱하여 enum 상수를 가져옵니다. |
|
|  | [toInt()](#toInt--) | RevisionType의 숫자 표현. |
|
|  | [toString()](#toString--) | RevisionType의 문자열 표현. |
|
### INSERTION {#INSERTION}
```
public static final RevisionType INSERTION
```


문서에 새 콘텐츠가 삽입될 때의 유형을 나타냅니다.


### DELETION {#DELETION}
```
public static final RevisionType DELETION
```


문서에서 콘텐츠가 제거될 때의 유형을 나타냅니다.


### FORMAT_CHANGE {#FORMAT-CHANGE}
```
public static final RevisionType FORMAT_CHANGE
```


부모 노드에 서식 변경이 적용될 때의 유형을 나타냅니다.


### STYLE_DEFINITION_CHANGE {#STYLE-DEFINITION-CHANGE}
```
public static final RevisionType STYLE_DEFINITION_CHANGE
```


부모 스타일에 서식 변경이 적용될 때의 유형을 나타냅니다.


### MOVING {#MOVING}
```
public static final RevisionType MOVING
```


문서 내에서 콘텐츠가 이동될 때의 유형을 나타냅니다.


### values() {#values--}
```
public static RevisionType[] values()
```




**Returns:**
com.groupdocs.comparison.words.revision.RevisionType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static RevisionType valueOf(String name)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |

**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype)
### fromInt(int toIntValue) {#fromInt-int-}
```
public static RevisionType fromInt(int toIntValue)
```


제공된 숫자 값을 사용하여 enum RevisionType의 새 상수를 생성합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | toIntValue | int | RevisionType의 숫자 표현 |
|

**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) - RevisionType enum constant associated with numeric value

### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static RevisionType fromString(String toStringValue)
```


RevisionType의 문자열 표현을 파싱하여 enum 상수를 가져옵니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | toStringValue | java.lang.String | RevisionType의 문자열 표현 |
|

**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) - RevisionType enum constant associated with input string

### toInt() {#toInt--}
```
public int toInt()
```


RevisionType의 숫자 표현.


**Returns:**
int - enum 상수의 숫자 값

### toString() {#toString--}
```
public String toString()
```


RevisionType의 문자열 표현.


**Returns:**
java.lang.String - enum 상수의 문자열 값

