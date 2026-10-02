---
title: "ComparisonAction"
second_title: "GroupDocs.Comparison for Java API 참조"
description: "ComparisonAction 열거형은 문서 비교 프로세스 중 변경에 적용될 수 있는 작업을 나타냅니다."
type: docs
weight: 15
url: /ko/java/com.groupdocs.comparison.result/comparisonaction/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ComparisonAction extends Enum<ComparisonAction>
```

ComparisonAction 열거형은 문서 비교 프로세스 중 변경에 적용될 수 있는 작업을 나타냅니다.


이 열거형의 각 상수는 특정 작업을 나타내며 사람이 읽을 수 있는 설명과 숫자 값을 제공합니다.


사용 예시:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);
     comparer.compare();

     final ChangeInfo[] changes = comparer.getChanges();
     for (ChangeInfo changeInfo : changes) {
         if (changeInfo.getId() % 2 == 0) {
             changeInfo.setComparisonAction(ComparisonAction.REJECT);
         }
     }
     comparer.applyChanges(resultFile, changes);
 }
 
````


## 필드

| 필드 | 설명 |
| --- | --- |
|  | [NONE](#NONE) | 동작이 없습니다. |
|
|  | [ACCEPT](#ACCEPT) | 수락 작업을 나타냅니다. |
|
|  | [REJECT](#REJECT) | 거부 작업을 나타냅니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | ComparisonAction의 문자열 표현을 구문 분석하여 열거형 상수를 가져옵니다. |
|
|  | [fromInt(int intValue)](#fromInt-int-) | 제공된 숫자 값을 사용하여 ComparisonAction 열거형의 새 상수를 생성합니다. |
|
|  | [toString()](#toString--) | ComparisonAction의 문자열 표현. |
|
|  | [toInt()](#toInt--) | ComparisonAction의 숫자 표현. |
|
### NONE {#NONE}
```
public static final ComparisonAction NONE
```


동작이 없습니다. 변경 사항은 영향을 주지 않습니다.


### ACCEPT {#ACCEPT}
```
public static final ComparisonAction ACCEPT
```


수락 작업을 나타냅니다. 변경 사항이 결과 파일에 표시됩니다.


### REJECT {#REJECT}
```
public static final ComparisonAction REJECT
```


거부 작업을 나타냅니다. 변경 사항이 결과 파일에 표시되지 않습니다.


### values() {#values--}
```
public static ComparisonAction[] values()
```




**Returns:**
com.groupdocs.comparison.result.ComparisonAction[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static ComparisonAction valueOf(String name)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |

**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static ComparisonAction fromString(String toStringValue)
```


ComparisonAction의 문자열 표현을 구문 분석하여 열거형 상수를 가져옵니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | toStringValue | java.lang.String | ComparisonAction의 문자열 표현 |
|

**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) - ComparisonAction enum constant associated with input string

### fromInt(int intValue) {#fromInt-int-}
```
public static ComparisonAction fromInt(int intValue)
```


제공된 숫자 값을 사용하여 ComparisonAction 열거형의 새 상수를 생성합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | intValue | int | ComparisonAction의 숫자 표현 |
|

**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) - ComparisonAction enum constant associated with numeric value

### toString() {#toString--}
```
public String toString()
```


ComparisonAction의 문자열 표현.


**Returns:**
java.lang.String - enum 상수의 문자열 값

### toInt() {#toInt--}
```
public int toInt()
```


ComparisonAction의 숫자 표현.


**Returns:**
int - enum 상수의 숫자 값

