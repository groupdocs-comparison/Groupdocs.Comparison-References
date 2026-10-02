---
title: "PasswordSaveOption"
second_title: "GroupDocs.Comparison for Java API 참조"
description: "비교 과정 중 문서에 비밀번호 정보를 저장하는 옵션을 열거합니다."
type: docs
weight: 14
url: /ko/java/com.groupdocs.comparison.options.enums/passwordsaveoption/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PasswordSaveOption extends Enum<PasswordSaveOption>
```

비교 과정 중 문서에 비밀번호 정보를 저장하는 옵션을 열거합니다.


사용 예시:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setPasswordSaveOption(PasswordSaveOption.SOURCE);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## 필드

| 필드 | 설명 |
| --- | --- |
|  | [NONE](#NONE) | 비밀번호를 저장하지 않습니다. |
|
|  | [SOURCE](#SOURCE) | 소스 문서의 비밀번호를 사용합니다. |
|
|  | [TARGET](#TARGET) | 대상 문서의 비밀번호를 사용합니다. |
|
|  | [USER](#USER) | \\* 사용자가 제공한 비밀번호를 사용합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | PasswordSaveOption의 문자열 표현을 구문 분석하여 열거형 상수를 가져옵니다. |
|
|  | [toString()](#toString--) | PasswordSaveOption의 문자열 표현. |
|
### NONE {#NONE}
```
public static final PasswordSaveOption NONE
```


비밀번호를 저장하지 않습니다.


### SOURCE {#SOURCE}
```
public static final PasswordSaveOption SOURCE
```


소스 문서의 비밀번호를 사용합니다.


### TARGET {#TARGET}
```
public static final PasswordSaveOption TARGET
```


대상 문서의 비밀번호를 사용합니다.


### USER {#USER}
```
public static final PasswordSaveOption USER
```


\\* 사용자가 제공한 비밀번호를 사용합니다.


### values() {#values--}
```
public static PasswordSaveOption[] values()
```




**Returns:**
com.groupdocs.comparison.options.enums.PasswordSaveOption[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PasswordSaveOption valueOf(String name)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |

**Returns:**
[PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static PasswordSaveOption fromString(String toStringValue)
```


PasswordSaveOption의 문자열 표현을 구문 분석하여 열거형 상수를 가져옵니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | toStringValue | java.lang.String | PasswordSaveOption의 문자열 표현 |
|

**Returns:**
[PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) - PasswordSaveOption enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


PasswordSaveOption의 문자열 표현.


**Returns:**
java.lang.String - enum 상수의 문자열 값

