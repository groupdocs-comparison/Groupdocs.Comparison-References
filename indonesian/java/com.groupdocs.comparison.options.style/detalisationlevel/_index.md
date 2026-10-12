---
title: "DetalisationLevel"
second_title: "Referensi API GroupDocs.Comparison untuk Java"
description: "Menentukan tingkat detail perbandingan."
type: docs
weight: 13
url: /id/java/com.groupdocs.comparison.options.style/detalisationlevel/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DetalisationLevel extends Enum<DetalisationLevel>
```

Menentukan tingkat detail perbandingan.


Contoh penggunaan:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setDetectStyleChanges(false);
    compareOptions.setDetalisationLevel(DetalisationLevel.HIGH);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [LOW](#LOW) | Mewakili tingkat perbandingan rendah. |
|
|  | [MIDDLE](#MIDDLE) | Mewakili tingkat perbandingan menengah. |
|
|  | [HIGH](#HIGH) | Mewakili tingkat perbandingan tinggi. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Mengurai representasi string dari DetalisationLevel untuk mendapatkan konstanta enum. |
|
|  | [toString()](#toString--) | Representasi string dari DetalisationLevel. |
|
### LOW {#LOW}
```
public static final DetalisationLevel LOW
```


Mewakili tingkat perbandingan rendah.


Level "Low" memberikan kecepatan terbaik untuk perbandingan tetapi mengorbankan kualitas perbandingan.
Perbandingan dilakukan per kata.


### MIDDLE {#MIDDLE}
```
public static final DetalisationLevel MIDDLE
```


Mewakili tingkat perbandingan menengah.


Level "Middle" merupakan kompromi yang wajar antara kecepatan perbandingan dan kualitas.
Perbandingan dilakukan per karakter, tetapi mengabaikan huruf besar/kecil dan menghitung spasi.


### HIGH {#HIGH}
```
public static final DetalisationLevel HIGH
```


Mewakili tingkat perbandingan tinggi.


Level "High" memiliki kualitas perbandingan terbaik, tetapi kecepatan terendah.
Perbandingan dilakukan per karakter dengan mempertimbangkan huruf besar/kecil dan menghitung spasi.


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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static DetalisationLevel fromString(String toStringValue)
```


Mengurai representasi string dari DetalisationLevel untuk mendapatkan konstanta enum.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | toStringValue | java.lang.String | Representasi string dari DetalisationLevel |
|

**Returns:**
[DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) - DetalisationLevel enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


Representasi string dari DetalisationLevel.


**Returns:**
java.lang.String - nilai string dari konstanta enum

