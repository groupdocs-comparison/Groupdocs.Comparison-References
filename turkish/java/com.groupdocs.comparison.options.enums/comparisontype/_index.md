---
title: "ComparisonType"
second_title: "GroupDocs.Comparison for Java API Referansı"
description: "Gerçekleştirilecek karşılaştırma türünü temsil eder."
type: docs
weight: 10
url: /tr/java/com.groupdocs.comparison.options.enums/comparisontype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ComparisonType extends Enum<ComparisonType>
```

Gerçekleştirilecek karşılaştırma türünü temsil eder.


Örnek kullanım:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setComparisonType(ComparisonType.CELLS);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [TEXT](#TEXT) | Dosyalar metin belgeleri olarak karşılaştırılmalıdır. |
|
|  | [SLIDES](#SLIDES) | Dosyalar sunum belgeleri olarak karşılaştırılmalıdır. |
|
|  | [WORDS](#WORDS) | Dosyalar Word belgeleri olarak karşılaştırılmalıdır. |
|
|  | [CELLS](#CELLS) | Dosyalar Excel belgeleri olarak karşılaştırılmalıdır. |
|
|  | [PDF](#PDF) | Dosyalar PDF belgeleri olarak karşılaştırılmalıdır. |
|
|  | [IMAGING](#IMAGING) | Dosyalar görüntü belgeleri olarak karşılaştırılmalıdır. |
|
|  | [EMAIL](#EMAIL) | Dosyalar e-posta belgeleri olarak karşılaştırılmalıdır. |
|
|  | [NOTE](#NOTE) | Dosyalar not belgeleri olarak karşılaştırılmalıdır. |
|
|  | [HTML](#HTML) | Dosyalar HTML belgeleri olarak karşılaştırılmalıdır. |
|
|  | [DIAGRAM](#DIAGRAM) | Dosyalar diyagram belgeleri olarak karşılaştırılmalıdır. |
|
|  | [DIFFERENT](#DIFFERENT) | Dosyalar farklı formatlarda belgeler olarak karşılaştırılmalıdır. |
|
|  | [SVG](#SVG) | Dosyalar SVG belgeleri olarak karşılaştırılmalıdır. |
|
|  | [UNDEFINED](#UNDEFINED) | Dahili kullanım için. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | ComparisonType'ın dize temsilini ayrıştırarak enum sabitini alır. |
|
|  | [toString()](#toString--) | ComparisonType'ın dize temsili. |
|
### TEXT {#TEXT}
```
public static final ComparisonType TEXT
```


Dosyalar metin belgeleri olarak karşılaştırılmalıdır.


### SLIDES {#SLIDES}
```
public static final ComparisonType SLIDES
```


Dosyalar sunum belgeleri olarak karşılaştırılmalıdır.


### WORDS {#WORDS}
```
public static final ComparisonType WORDS
```


Dosyalar Word belgeleri olarak karşılaştırılmalıdır.


### CELLS {#CELLS}
```
public static final ComparisonType CELLS
```


Dosyalar Excel belgeleri olarak karşılaştırılmalıdır.


### PDF {#PDF}
```
public static final ComparisonType PDF
```


Dosyalar PDF belgeleri olarak karşılaştırılmalıdır.


### IMAGING {#IMAGING}
```
public static final ComparisonType IMAGING
```


Dosyalar görüntü belgeleri olarak karşılaştırılmalıdır.


### EMAIL {#EMAIL}
```
public static final ComparisonType EMAIL
```


Dosyalar e-posta belgeleri olarak karşılaştırılmalıdır.


### NOTE {#NOTE}
```
public static final ComparisonType NOTE
```


Dosyalar not belgeleri olarak karşılaştırılmalıdır.


### HTML {#HTML}
```
public static final ComparisonType HTML
```


Dosyalar HTML belgeleri olarak karşılaştırılmalıdır.


### DIAGRAM {#DIAGRAM}
```
public static final ComparisonType DIAGRAM
```


Dosyalar diyagram belgeleri olarak karşılaştırılmalıdır.


### DIFFERENT {#DIFFERENT}
```
public static final ComparisonType DIFFERENT
```


Dosyalar farklı formatlarda belgeler olarak karşılaştırılmalıdır.


### SVG {#SVG}
```
public static final ComparisonType SVG
```


Dosyalar SVG belgeleri olarak karşılaştırılmalıdır.


### UNDEFINED {#UNDEFINED}
```
public static final ComparisonType UNDEFINED
```


Dahili kullanım için.


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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static ComparisonType fromString(String toStringValue)
```


ComparisonType'ın dize temsilini ayrıştırarak enum sabitini alır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | toStringValue | java.lang.String | ComparisonType'ın dize temsili |
|

**Returns:**
[ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) - ComparisonType enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


ComparisonType'ın dize temsili.


**Returns:**
java.lang.String - enum sabitinin dize değeri

