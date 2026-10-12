---
title: "GetChangeOptions"
second_title: "GroupDocs.Comparison for Java API 참조"
description: "비교 결과에서 특정 변경 유형을 검색하기 위한 필터링을 구성할 수 있습니다."
type: docs
weight: 13
url: /ko/java/com.groupdocs.comparison.options/getchangeoptions/
---
**Inheritance:**
java.lang.Object
```
public class GetChangeOptions
```

비교 결과에서 특정 변경 유형을 검색하기 위한 필터링을 구성할 수 있습니다.


사용 예시:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);
     comparer.compare();

     GetChangeOptions getChangeOptions = new GetChangeOptions();

     getChangeOptions.setFilter(ChangeType.DELETED);

     ChangeInfo[] changes = comparer.getChanges(getChangeOptions);
     System.out.println(Arrays.toString(changes));
 }
 
````


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [GetChangeOptions()](#GetChangeOptions--) | GetChangeOptions 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [GetChangeOptions(ChangeType filter)](#GetChangeOptions-com.groupdocs.comparison.result.ChangeType-) | 지정된 필터 유형에 대해 GetChangeOptions 클래스의 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getFilter()](#getFilter--) | 비교 결과에서 특정 변경 유형을 검색하기 위한 필터를 가져옵니다. |
|
|  | [setFilter(ChangeType value)](#setFilter-com.groupdocs.comparison.result.ChangeType-) | 비교 결과에서 특정 변경 유형을 검색하기 위한 필터를 설정합니다. |
|
### GetChangeOptions() {#GetChangeOptions--}
```
public GetChangeOptions()
```


GetChangeOptions 클래스의 새 인스턴스를 초기화합니다.


### GetChangeOptions(ChangeType filter) {#GetChangeOptions-com.groupdocs.comparison.result.ChangeType-}
```
public GetChangeOptions(ChangeType filter)
```


지정된 필터 유형에 대해 GetChangeOptions 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filter | [ChangeType](../../com.groupdocs.comparison.result/changetype) |  |

### getFilter() {#getFilter--}
```
public final ChangeType getFilter()
```


비교 결과에서 특정 변경 유형을 검색하기 위한 필터를 가져옵니다.


**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - the filter specifying the types of changes to be retrieved.

### setFilter(ChangeType value) {#setFilter-com.groupdocs.comparison.result.ChangeType-}
```
public final void setFilter(ChangeType value)
```


비교 결과에서 특정 변경 유형을 검색하기 위한 필터를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | value | [ChangeType](../../com.groupdocs.comparison.result/changetype) | 검색될 변경 유형을 지정하는 필터입니다. |
|

