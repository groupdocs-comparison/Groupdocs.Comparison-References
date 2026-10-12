---
title: "PaperSize"
second_title: "GroupDocs.Comparison for Java API 참조"
description: "문서 비교를 위한 용지 크기 옵션을 나타냅니다."
type: docs
weight: 13
url: /ko/java/com.groupdocs.comparison.options.enums/papersize/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PaperSize extends Enum<PaperSize>
```

문서 비교를 위한 용지 크기 옵션을 나타냅니다.


사용 예시:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setPaperSize(PaperSize.A6);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## 필드

| 필드 | 설명 |
| --- | --- |
|  | [DEFAULT](#DEFAULT) | 기본 용지 크기. |
|
|  | [A0](#A0) | 표준 용지 크기 A0 (841mm x 1189mm). |
|
|  | [A1](#A1) | 표준 용지 크기 A1 (594mm x 841mm). |
|
|  | [A2](#A2) | 표준 용지 크기 A2 (420mm x 594mm). |
|
|  | [A3](#A3) | 표준 용지 크기 A3 (297mm x 420mm). |
|
|  | [A4](#A4) | 표준 용지 크기 A4 (210mm x 297mm). |
|
|  | [A5](#A5) | 표준 용지 크기 A5 (148mm x 210mm). |
|
|  | [A6](#A6) | 표준 용지 크기 A6 (105mm x 148mm). |
|
|  | [A7](#A7) | 표준 용지 크기 A7 (74mm x 105mm). |
|
|  | [A8](#A8) | 표준 용지 크기 A8 (52mm x 74mm). |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | PaperSize의 문자열 표현을 구문 분석하여 열거형 상수를 가져옵니다. |
|
|  | [toString()](#toString--) | PaperSize의 문자열 표현. |
|
### DEFAULT {#DEFAULT}
```
public static final PaperSize DEFAULT
```


기본 용지 크기.


### A0 {#A0}
```
public static final PaperSize A0
```


표준 용지 크기 A0 (841mm x 1189mm).


### A1 {#A1}
```
public static final PaperSize A1
```


표준 용지 크기 A1 (594mm x 841mm).


### A2 {#A2}
```
public static final PaperSize A2
```


표준 용지 크기 A2 (420mm x 594mm).


### A3 {#A3}
```
public static final PaperSize A3
```


표준 용지 크기 A3 (297mm x 420mm).


### A4 {#A4}
```
public static final PaperSize A4
```


표준 용지 크기 A4 (210mm x 297mm).


### A5 {#A5}
```
public static final PaperSize A5
```


표준 용지 크기 A5 (148mm x 210mm).


### A6 {#A6}
```
public static final PaperSize A6
```


표준 용지 크기 A6 (105mm x 148mm).


### A7 {#A7}
```
public static final PaperSize A7
```


표준 용지 크기 A7 (74mm x 105mm).


### A8 {#A8}
```
public static final PaperSize A8
```


표준 용지 크기 A8 (52mm x 74mm).


### values() {#values--}
```
public static PaperSize[] values()
```




**Returns:**
com.groupdocs.comparison.options.enums.PaperSize[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PaperSize valueOf(String name)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |

**Returns:**
[PaperSize](../../com.groupdocs.comparison.options.enums/papersize)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static PaperSize fromString(String toStringValue)
```


PaperSize의 문자열 표현을 구문 분석하여 열거형 상수를 가져옵니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | toStringValue | java.lang.String | PaperSize의 문자열 표현 |
|

**Returns:**
[PaperSize](../../com.groupdocs.comparison.options.enums/papersize) - PaperSize enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


PaperSize의 문자열 표현.


**Returns:**
java.lang.String - enum 상수의 문자열 값

