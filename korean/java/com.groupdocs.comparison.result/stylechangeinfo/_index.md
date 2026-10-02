---
title: "StyleChangeInfo"
second_title: "GroupDocs.Comparison for Java API 참조"
description: "StyleChangeInfo 클래스는 비교된 문서에서 스타일 변경에 대한 정보를 나타냅니다."
type: docs
weight: 13
url: /ko/java/com.groupdocs.comparison.result/stylechangeinfo/
---
**Inheritance:**
java.lang.Object
```
public class StyleChangeInfo
```

StyleChangeInfo 클래스는 비교된 문서에서 스타일 변경에 대한 정보를 나타냅니다.


변경된 속성 이름, 변경 전후 값 등과 같은 세부 정보를 제공합니다.
문서 비교 과정에서 스타일 변경에 대한 정보를 가져오려면 이 클래스를 사용하십시오.


사용 예시:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     comparer.compare();
     final ChangeInfo[] changes = comparer.getChanges();
     for (ChangeInfo change : changes) {
         // Access the style change information
         final List styleChanges = change.getStyleChanges();
         for (StyleChangeInfo styleChange : styleChanges) {
             // Print the style change information
             System.out.println("PropertyName: " + styleChange.getPropertyName());
             System.out.println("OldValue: " + styleChange.getOldValue());
             System.out.println("NewValue: " + styleChange.getNewValue());
         }
     }
 }
 
````


## 생성자

| 생성자 | 설명 |
| --- | --- |
| [StyleChangeInfo()](#StyleChangeInfo--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getPropertyName()](#getPropertyName--) | 변경된 속성의 이름을 가져옵니다. |
|
|  | [setPropertyName(String value)](#setPropertyName-java.lang.String-) | 변경된 속성의 이름을 설정합니다. |
|
|  | [getNewValue()](#getNewValue--) | 속성의 새 값을 가져옵니다. |
|
|  | [setNewValue(Object value)](#setNewValue-java.lang.Object-) | 속성의 새 값을 설정합니다. |
|
|  | [getOldValue()](#getOldValue--) | 속성의 이전 값을 가져옵니다. |
|
|  | [setOldValue(Object value)](#setOldValue-java.lang.Object-) | 속성의 이전 값을 설정합니다. |
|
|  | [equals(Object o)](#equals-java.lang.Object-) | {@inheritDoc} |
|
|  | [hashCode()](#hashCode--) | {@inheritDoc} |
|
### StyleChangeInfo() {#StyleChangeInfo--}
```
public StyleChangeInfo()
```


### getPropertyName() {#getPropertyName--}
```
public final String getPropertyName()
```


변경된 속성의 이름을 가져옵니다.


**Returns:**
java.lang.String - 속성 이름

### setPropertyName(String value) {#setPropertyName-java.lang.String-}
```
public final void setPropertyName(String value)
```


변경된 속성의 이름을 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | java.lang.String | 속성 이름 |
|

### getNewValue() {#getNewValue--}
```
public final Object getNewValue()
```


속성의 새 값을 가져옵니다.


**Returns:**
java.lang.Object - 속성의 새 값

### setNewValue(Object value) {#setNewValue-java.lang.Object-}
```
public final void setNewValue(Object value)
```


속성의 새 값을 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | java.lang.Object | 속성의 새 값 |
|

### getOldValue() {#getOldValue--}
```
public final Object getOldValue()
```


속성의 이전 값을 가져옵니다.


**Returns:**
java.lang.Object - 속성의 이전 값

### setOldValue(Object value) {#setOldValue-java.lang.Object-}
```
public final void setOldValue(Object value)
```


속성의 이전 값을 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | java.lang.Object | 속성의 이전 값 |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| o | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
