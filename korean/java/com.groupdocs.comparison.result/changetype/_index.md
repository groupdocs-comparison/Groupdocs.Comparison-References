---
title: "ChangeType"
second_title: "GroupDocs.Comparison for Java API 참조"
description: "ChangeType 열거형은 문서 비교 프로세스 중 발생할 수 있는 변경 유형을 나타냅니다."
type: docs
weight: 14
url: /ko/java/com.groupdocs.comparison.result/changetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ChangeType extends Enum<ChangeType>
```

ChangeType 열거형은 문서 비교 프로세스 중 발생할 수 있는 변경 유형을 나타냅니다.


이 열거형의 각 상수는 특정 변경 유형을 나타내며 사람이 읽을 수 있는 설명과 숫자 값을 제공합니다.


사용 예시:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);
     comparer.compare();
     final ChangeInfo[] changes = comparer.getChanges();
     for (ChangeInfo changeInfo : changes) {
         // Get the ChangeType for a specific change
         final ChangeType changeType = changeInfo.getType();
         // Print the ChangeType information
         System.out.println("Description: " + changeType.toString());
         System.out.println("Value: " + changeType.toInt());
     }
 }
 
````


## 필드

| 필드 | 설명 |
| --- | --- |
|  | [NONE](#NONE) | 변경 사항이 없습니다. |
|
|  | [MODIFIED](#MODIFIED) | 수정된 변경을 나타냅니다. |
|
|  | [INSERTED](#INSERTED) | 삽입된 변경을 나타냅니다. |
|
|  | [DELETED](#DELETED) | 삭제된 변경을 나타냅니다. |
|
|  | [ADDED](#ADDED) | 추가된 변경을 나타냅니다. |
|
|  | [NOT_MODIFIED](#NOT-MODIFIED) | 수정되지 않은 변경을 나타냅니다. |
|
|  | [STYLE_CHANGED](#STYLE-CHANGED) | 스타일이 변경된 변경을 나타냅니다. |
|
|  | [RESIZED](#RESIZED) | 크기 조정된 변경을 나타냅니다. |
|
|  | [MOVED](#MOVED) | 이동된 변경을 나타냅니다. |
|
|  | [MOVED_AND_RESIZED](#MOVED-AND-RESIZED) | 이동 및 크기 조정된 변경을 나타냅니다. |
|
|  | [SHIFTED_AND_RESIZED](#SHIFTED-AND-RESIZED) | 이동 및 크기 조정된 변경을 나타냅니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | ChangeType의 문자열 표현을 구문 분석하여 열거형 상수를 가져옵니다. |
|
|  | [fromInt(int intValue)](#fromInt-int-) | 제공된 숫자 값을 사용하여 ChangeType 열거형의 새 상수를 생성합니다. |
|
|  | [toString()](#toString--) | ChangeType의 문자열 표현. |
|
|  | [toInt()](#toInt--) | ChangeType의 숫자 표현. |
|
### NONE {#NONE}
```
public static final ChangeType NONE
```


변경 사항이 없습니다.


### MODIFIED {#MODIFIED}
```
public static final ChangeType MODIFIED
```


수정된 변경을 나타냅니다.


### INSERTED {#INSERTED}
```
public static final ChangeType INSERTED
```


삽입된 변경을 나타냅니다.


### DELETED {#DELETED}
```
public static final ChangeType DELETED
```


삭제된 변경을 나타냅니다.


### ADDED {#ADDED}
```
public static final ChangeType ADDED
```


추가된 변경을 나타냅니다.


### NOT_MODIFIED {#NOT-MODIFIED}
```
public static final ChangeType NOT_MODIFIED
```


수정되지 않은 변경을 나타냅니다.


### STYLE_CHANGED {#STYLE-CHANGED}
```
public static final ChangeType STYLE_CHANGED
```


스타일이 변경된 변경을 나타냅니다.


### RESIZED {#RESIZED}
```
public static final ChangeType RESIZED
```


크기 조정된 변경을 나타냅니다.


### MOVED {#MOVED}
```
public static final ChangeType MOVED
```


이동된 변경을 나타냅니다.


### MOVED_AND_RESIZED {#MOVED-AND-RESIZED}
```
public static final ChangeType MOVED_AND_RESIZED
```


이동 및 크기 조정된 변경을 나타냅니다.


### SHIFTED_AND_RESIZED {#SHIFTED-AND-RESIZED}
```
public static final ChangeType SHIFTED_AND_RESIZED
```


이동 및 크기 조정된 변경을 나타냅니다.


### values() {#values--}
```
public static ChangeType[] values()
```




**Returns:**
com.groupdocs.comparison.result.ChangeType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static ChangeType valueOf(String name)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |

**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static ChangeType fromString(String toStringValue)
```


ChangeType의 문자열 표현을 구문 분석하여 열거형 상수를 가져옵니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | toStringValue | java.lang.String | ChangeType의 문자열 표현 |
|

**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - ChangeType enum constant associated with input string

### fromInt(int intValue) {#fromInt-int-}
```
public static ChangeType fromInt(int intValue)
```


제공된 숫자 값을 사용하여 ChangeType 열거형의 새 상수를 생성합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | intValue | int | ChangeType의 숫자 표현 |
|

**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - ChangeType enum constant associated with numeric value

### toString() {#toString--}
```
public String toString()
```


ChangeType의 문자열 표현.


**Returns:**
java.lang.String - enum 상수의 문자열 값

### toInt() {#toInt--}
```
public int toInt()
```


ChangeType의 숫자 표현.


**Returns:**
int - enum 상수의 숫자 값

