---
title: "DetalisationLevel"
second_title: "GroupDocs.Comparison for Java API 참조"
description: "비교 세부 수준을 지정합니다."
type: docs
weight: 13
url: /ko/java/com.groupdocs.comparison.options.style/detalisationlevel/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DetalisationLevel extends Enum<DetalisationLevel>
```

비교 세부 수준을 지정합니다.


사용 예시:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setDetectStyleChanges(false);
    compareOptions.setDetalisationLevel(DetalisationLevel.HIGH);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## 필드

| 필드 | 설명 |
| --- | --- |
|  | [LOW](#LOW) | Low 비교 수준을 나타냅니다. |
|
|  | [MIDDLE](#MIDDLE) | Middle 비교 수준을 나타냅니다. |
|
|  | [HIGH](#HIGH) | High 비교 수준을 나타냅니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | DetalisationLevel의 문자열 표현을 파싱하여 enum 상수를 가져옵니다. |
|
|  | [toString()](#toString--) | DetalisationLevel의 문자열 표현. |
|
### LOW {#LOW}
```
public static final DetalisationLevel LOW
```


Low 비교 수준을 나타냅니다.


\"Low\" 수준은 비교 속도를 최대로 제공하지만 비교 품질을 희생합니다.
비교는 단어 단위로 수행됩니다.


### MIDDLE {#MIDDLE}
```
public static final DetalisationLevel MIDDLE
```


Middle 비교 수준을 나타냅니다.


\"Middle\" 수준은 비교 속도와 품질 사이의 합리적인 타협입니다.
비교는 문자 단위로 수행되지만 문자 대소문자와 공백 수는 무시합니다.


### HIGH {#HIGH}
```
public static final DetalisationLevel HIGH
```


High 비교 수준을 나타냅니다.


\"High\" 수준은 최고의 비교 품질을 제공하지만 속도는 가장 낮습니다.
비교는 문자 대소문자와 공백 수를 고려하여 문자 단위로 수행됩니다.


### values() {#values--}
```
public static DetalisationLevel[] values()
```




**Returns:**
com.groupdocs.comparison.options.style.DetalisationLevel[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static DetalisationLevel valueOf(String name)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |

**Returns:**
[DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static DetalisationLevel fromString(String toStringValue)
```


DetalisationLevel의 문자열 표현을 파싱하여 enum 상수를 가져옵니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | toStringValue | java.lang.String | DetalisationLevel의 문자열 표현 |
|

**Returns:**
[DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) - DetalisationLevel enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


DetalisationLevel의 문자열 표현.


**Returns:**
java.lang.String - enum 상수의 문자열 값

