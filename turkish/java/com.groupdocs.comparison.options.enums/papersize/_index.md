---
title: "PaperSize"
second_title: "GroupDocs.Comparison for Java API Referansı"
description: "Belge karşılaştırması için kağıt boyutu seçeneklerini temsil eder."
type: docs
weight: 13
url: /tr/java/com.groupdocs.comparison.options.enums/papersize/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PaperSize extends Enum<PaperSize>
```

Belge karşılaştırması için kağıt boyutu seçeneklerini temsil eder.


Örnek kullanım:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setPaperSize(PaperSize.A6);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [DEFAULT](#DEFAULT) | Varsayılan kağıt boyutu. |
|
|  | [A0](#A0) | Standart kağıt boyutu A0 (841mm x 1189mm). |
|
|  | [A1](#A1) | Standart kağıt boyutu A1 (594mm x 841mm). |
|
|  | [A2](#A2) | Standart kağıt boyutu A2 (420mm x 594mm). |
|
|  | [A3](#A3) | Standart kağıt boyutu A3 (297mm x 420mm). |
|
|  | [A4](#A4) | Standart kağıt boyutu A4 (210mm x 297mm). |
|
|  | [A5](#A5) | Standart kağıt boyutu A5 (148mm x 210mm). |
|
|  | [A6](#A6) | Standart kağıt boyutu A6 (105mm x 148mm). |
|
|  | [A7](#A7) | Standart kağıt boyutu A7 (74mm x 105mm). |
|
|  | [A8](#A8) | Standart kağıt boyutu A8 (52mm x 74mm). |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | PaperSize'ın dize temsilini ayrıştırarak enum sabitini alır. |
|
|  | [toString()](#toString--) | PaperSize'ın dize temsili. |
|
### DEFAULT {#DEFAULT}
```
public static final PaperSize DEFAULT
```


Varsayılan kağıt boyutu.


### A0 {#A0}
```
public static final PaperSize A0
```


Standart kağıt boyutu A0 (841mm x 1189mm).


### A1 {#A1}
```
public static final PaperSize A1
```


Standart kağıt boyutu A1 (594mm x 841mm).


### A2 {#A2}
```
public static final PaperSize A2
```


Standart kağıt boyutu A2 (420mm x 594mm).


### A3 {#A3}
```
public static final PaperSize A3
```


Standart kağıt boyutu A3 (297mm x 420mm).


### A4 {#A4}
```
public static final PaperSize A4
```


Standart kağıt boyutu A4 (210mm x 297mm).


### A5 {#A5}
```
public static final PaperSize A5
```


Standart kağıt boyutu A5 (148mm x 210mm).


### A6 {#A6}
```
public static final PaperSize A6
```


Standart kağıt boyutu A6 (105mm x 148mm).


### A7 {#A7}
```
public static final PaperSize A7
```


Standart kağıt boyutu A7 (74mm x 105mm).


### A8 {#A8}
```
public static final PaperSize A8
```


Standart kağıt boyutu A8 (52mm x 74mm).


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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[PaperSize](../../com.groupdocs.comparison.options.enums/papersize)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static PaperSize fromString(String toStringValue)
```


PaperSize'ın dize temsilini ayrıştırarak enum sabitini alır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | toStringValue | java.lang.String | PaperSize'ın dize temsili |
|

**Returns:**
[PaperSize](../../com.groupdocs.comparison.options.enums/papersize) - PaperSize enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


PaperSize'ın dize temsili.


**Returns:**
java.lang.String - enum sabitinin dize değeri

