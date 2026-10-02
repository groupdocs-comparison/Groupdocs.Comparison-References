---
title: "DetalisationLevel"
second_title: "GroupDocs.Comparison for Java API Referansı"
description: "Karşılaştırma detay seviyesini belirtir."
type: docs
weight: 13
url: /tr/java/com.groupdocs.comparison.options.style/detalisationlevel/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DetalisationLevel extends Enum<DetalisationLevel>
```

Karşılaştırma detay seviyesini belirtir.


Örnek kullanım:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setDetectStyleChanges(false);
    compareOptions.setDetalisationLevel(DetalisationLevel.HIGH);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [LOW](#LOW) | Düşük karşılaştırma seviyesini temsil eder. |
|
|  | [MIDDLE](#MIDDLE) | Orta karşılaştırma seviyesini temsil eder. |
|
|  | [HIGH](#HIGH) | Yüksek karşılaştırma seviyesini temsil eder. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Enum sabitini elde etmek için DetalisationLevel'ın dize temsili ayrıştırılır. |
|
|  | [toString()](#toString--) | DetalisationLevel'ın dize temsili. |
|
### LOW {#LOW}
```
public static final DetalisationLevel LOW
```


Düşük karşılaştırma seviyesini temsil eder.


"Low" seviyesi karşılaştırmalar için en iyi hızı sağlar ancak karşılaştırma kalitesinden ödün verir.
Karşılaştırma kelime bazında yapılır.


### MIDDLE {#MIDDLE}
```
public static final DetalisationLevel MIDDLE
```


Orta karşılaştırma seviyesini temsil eder.


"Middle" seviyesi karşılaştırma hızı ve kalitesi arasında makul bir denge sunar.
Karşılaştırma karakter bazında yapılır, ancak karakter büyük/küçük harf ve boşluk sayısı göz ardı edilir.


### HIGH {#HIGH}
```
public static final DetalisationLevel HIGH
```


Yüksek karşılaştırma seviyesini temsil eder.


"High" seviyesi en iyi karşılaştırma kalitesini sağlar, ancak en düşük hıza sahiptir.
Karşılaştırma karakter bazında, karakter büyük/küçük harf ve boşluk sayısını dikkate alarak yapılır.


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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static DetalisationLevel fromString(String toStringValue)
```


Enum sabitini elde etmek için DetalisationLevel'ın dize temsili ayrıştırılır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | toStringValue | java.lang.String | DetalisationLevel'ın dize temsili |
|

**Returns:**
[DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) - DetalisationLevel enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


DetalisationLevel'ın dize temsili.


**Returns:**
java.lang.String - enum sabitinin dize değeri

