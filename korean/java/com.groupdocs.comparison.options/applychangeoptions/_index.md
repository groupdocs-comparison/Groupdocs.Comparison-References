---
title: "ApplyChangeOptions"
second_title: "GroupDocs.Comparison for Java API 참조"
description: "결과 문서에 적용하기 전에 변경 목록을 업데이트할 수 있습니다."
type: docs
weight: 10
url: /ko/java/com.groupdocs.comparison.options/applychangeoptions/
---
**Inheritance:**
java.lang.Object
```
public class ApplyChangeOptions
```

결과 문서에 적용하기 전에 변경 목록을 업데이트할 수 있습니다.


사용 예시:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);
     comparer.compare();
     ChangeInfo[] changes = comparer.getChanges();
     changes[0].setComparisonAction(ComparisonAction.REJECT);

     final ApplyChangeOptions applyChangeOptions = new ApplyChangeOptions(changes);

     comparer.applyChanges(resultFile, applyChangeOptions);
 }
 
````


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [ApplyChangeOptions()](#ApplyChangeOptions--) | ApplyChangeOptions 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [ApplyChangeOptions(List<ChangeInfo> changes)](#ApplyChangeOptions-java.util.List-com.groupdocs.comparison.result.ChangeInfo--) | ApplyChangeOptions 클래스의 새 인스턴스를 변경 목록과 함께 초기화합니다. |
|
|  | [ApplyChangeOptions(ChangeInfo[] changes)](#ApplyChangeOptions-com.groupdocs.comparison.result.ChangeInfo---) | ApplyChangeOptions 클래스의 새 인스턴스를 변경 배열과 함께 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getChanges()](#getChanges--) | 결과 문서에 적용해야 할 변경 배열을 가져옵니다. |
|
|  | [setChanges(ChangeInfo[] value)](#setChanges-com.groupdocs.comparison.result.ChangeInfo---) | 결과 문서에 적용해야 할 변경 배열을 설정합니다. |
|
|  | [setChanges(List<ChangeInfo> value)](#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--) | 결과 문서에 적용해야 할 변경 목록을 설정합니다. |
|
|  | [isSaveOriginalState()](#isSaveOriginalState--) | 원본 상태를 저장해야 하는지 여부를 결정하는 플래그를 가져옵니다. |
|
|  | [setSaveOriginalState(boolean saveOriginalState)](#setSaveOriginalState-boolean-) | 원본 상태를 저장해야 하는지 여부를 결정하는 플래그를 설정합니다. |
|
### ApplyChangeOptions() {#ApplyChangeOptions--}
```
public ApplyChangeOptions()
```


ApplyChangeOptions 클래스의 새 인스턴스를 초기화합니다.


### ApplyChangeOptions(List<ChangeInfo> changes) {#ApplyChangeOptions-java.util.List-com.groupdocs.comparison.result.ChangeInfo--}
```
public ApplyChangeOptions(List<ChangeInfo> changes)
```


ApplyChangeOptions 클래스의 새 인스턴스를 변경 목록과 함께 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 변경 사항 | java.util.List<com.groupdocs.comparison.result.ChangeInfo> | 적용될 변경 목록 |
|

### ApplyChangeOptions(ChangeInfo[] changes) {#ApplyChangeOptions-com.groupdocs.comparison.result.ChangeInfo---}
```
public ApplyChangeOptions(ChangeInfo[] changes)
```


ApplyChangeOptions 클래스의 새 인스턴스를 변경 배열과 함께 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | changes | [ChangeInfo\[\]](../../com.groupdocs.comparison.result/changeinfo) | 적용될 변경 목록 |
|

### getChanges() {#getChanges--}
```
public final ChangeInfo[] getChanges()
```


결과 문서에 적용해야 할 변경 배열을 가져옵니다.


**Returns:**
com.groupdocs.comparison.result.ChangeInfo[] - 적용될 변경 배열

### setChanges(ChangeInfo[] value) {#setChanges-com.groupdocs.comparison.result.ChangeInfo---}
```
public final void setChanges(ChangeInfo[] value)
```


결과 문서에 적용해야 할 변경 배열을 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | value | [ChangeInfo\[\]](../../com.groupdocs.comparison.result/changeinfo) | 적용될 변경 배열 |
|

### setChanges(List<ChangeInfo> value) {#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--}
```
public final void setChanges(List<ChangeInfo> value)
```


결과 문서에 적용해야 할 변경 목록을 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | java.util.List<com.groupdocs.comparison.result.ChangeInfo> | 적용될 변경 목록 |
|

### isSaveOriginalState() {#isSaveOriginalState--}
```
public boolean isSaveOriginalState()
```


원본 상태를 저장해야 하는지 여부를 결정하는 플래그를 가져옵니다. 기본값: false.


**Returns:**
boolean - 원본 상태를 저장해야 하면 true, 그렇지 않으면 false

### setSaveOriginalState(boolean saveOriginalState) {#setSaveOriginalState-boolean-}
```
public void setSaveOriginalState(boolean saveOriginalState)
```


원본 상태를 저장해야 하는지 여부를 결정하는 플래그를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | saveOriginalState | boolean | 원본 상태를 저장해야 하면 true, 그렇지 않으면 false |
|

