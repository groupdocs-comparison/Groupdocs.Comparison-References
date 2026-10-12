---
title: "ComparisonType"
second_title: "GroupDocs.Comparison for Java API 참조"
description: "수행될 비교 유형을 나타냅니다."
type: docs
weight: 10
url: /ko/java/com.groupdocs.comparison.options.enums/comparisontype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ComparisonType extends Enum<ComparisonType>
```

수행될 비교 유형을 나타냅니다.


사용 예시:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setComparisonType(ComparisonType.CELLS);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## 필드

| 필드 | 설명 |
| --- | --- |
|  | [TEXT](#TEXT) | 파일은 텍스트 문서로 비교되어야 합니다. |
|
|  | [SLIDES](#SLIDES) | 파일은 프레젠테이션 문서로 비교되어야 합니다. |
|
|  | [WORDS](#WORDS) | 파일은 워드 문서로 비교되어야 합니다. |
|
|  | [CELLS](#CELLS) | 파일은 엑셀 문서로 비교되어야 합니다. |
|
|  | [PDF](#PDF) | 파일은 PDF 문서로 비교되어야 합니다. |
|
|  | [IMAGING](#IMAGING) | 파일은 이미지 문서로 비교되어야 합니다. |
|
|  | [EMAIL](#EMAIL) | 파일은 이메일 문서로 비교되어야 합니다. |
|
|  | [NOTE](#NOTE) | 파일은 노트 문서로 비교되어야 합니다. |
|
|  | [HTML](#HTML) | 파일은 HTML 문서로 비교되어야 합니다. |
|
|  | [DIAGRAM](#DIAGRAM) | 파일은 다이어그램 문서로 비교되어야 합니다. |
|
|  | [DIFFERENT](#DIFFERENT) | 파일은 서로 다른 형식의 문서로 비교되어야 합니다. |
|
|  | [SVG](#SVG) | 파일은 SVG 문서로 비교되어야 합니다. |
|
|  | [UNDEFINED](#UNDEFINED) | 내부 용도로만 사용됩니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | ComparisonType의 문자열 표현을 구문 분석하여 열거형 상수를 가져옵니다. |
|
|  | [toString()](#toString--) | ComparisonType의 문자열 표현. |
|
### TEXT {#TEXT}
```
public static final ComparisonType TEXT
```


파일은 텍스트 문서로 비교되어야 합니다.


### SLIDES {#SLIDES}
```
public static final ComparisonType SLIDES
```


파일은 프레젠테이션 문서로 비교되어야 합니다.


### WORDS {#WORDS}
```
public static final ComparisonType WORDS
```


파일은 워드 문서로 비교되어야 합니다.


### CELLS {#CELLS}
```
public static final ComparisonType CELLS
```


파일은 엑셀 문서로 비교되어야 합니다.


### PDF {#PDF}
```
public static final ComparisonType PDF
```


파일은 PDF 문서로 비교되어야 합니다.


### IMAGING {#IMAGING}
```
public static final ComparisonType IMAGING
```


파일은 이미지 문서로 비교되어야 합니다.


### EMAIL {#EMAIL}
```
public static final ComparisonType EMAIL
```


파일은 이메일 문서로 비교되어야 합니다.


### NOTE {#NOTE}
```
public static final ComparisonType NOTE
```


파일은 노트 문서로 비교되어야 합니다.


### HTML {#HTML}
```
public static final ComparisonType HTML
```


파일은 HTML 문서로 비교되어야 합니다.


### DIAGRAM {#DIAGRAM}
```
public static final ComparisonType DIAGRAM
```


파일은 다이어그램 문서로 비교되어야 합니다.


### DIFFERENT {#DIFFERENT}
```
public static final ComparisonType DIFFERENT
```


파일은 서로 다른 형식의 문서로 비교되어야 합니다.


### SVG {#SVG}
```
public static final ComparisonType SVG
```


파일은 SVG 문서로 비교되어야 합니다.


### UNDEFINED {#UNDEFINED}
```
public static final ComparisonType UNDEFINED
```


내부 용도로만 사용됩니다.


### values() {#values--}
```
public static ComparisonType[] values()
```




**Returns:**
com.groupdocs.comparison.options.enums.ComparisonType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static ComparisonType valueOf(String name)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |

**Returns:**
[ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static ComparisonType fromString(String toStringValue)
```


ComparisonType의 문자열 표현을 구문 분석하여 열거형 상수를 가져옵니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | toStringValue | java.lang.String | ComparisonType의 문자열 표현 |
|

**Returns:**
[ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) - ComparisonType enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


ComparisonType의 문자열 표현.


**Returns:**
java.lang.String - enum 상수의 문자열 값

