---
title: "PaperSize"
second_title: "Referensi API GroupDocs.Comparison untuk Java"
description: "Mewakili opsi ukuran kertas untuk perbandingan dokumen."
type: docs
weight: 13
url: /id/java/com.groupdocs.comparison.options.enums/papersize/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PaperSize extends Enum<PaperSize>
```

Mewakili opsi ukuran kertas untuk perbandingan dokumen.


Contoh penggunaan:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setPaperSize(PaperSize.A6);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [DEFAULT](#DEFAULT) | Ukuran kertas default. |
|
|  | [A0](#A0) | Ukuran kertas standar A0 (841mm x 1189mm). |
|
|  | [A1](#A1) | Ukuran kertas standar A1 (594mm x 841mm). |
|
|  | [A2](#A2) | Ukuran kertas standar A2 (420mm x 594mm). |
|
|  | [A3](#A3) | Ukuran kertas standar A3 (297mm x 420mm). |
|
|  | [A4](#A4) | Ukuran kertas standar A4 (210mm x 297mm). |
|
|  | [A5](#A5) | Ukuran kertas standar A5 (148mm x 210mm). |
|
|  | [A6](#A6) | Ukuran kertas standar A6 (105mm x 148mm). |
|
|  | [A7](#A7) | Ukuran kertas standar A7 (74mm x 105mm). |
|
|  | [A8](#A8) | Ukuran kertas standar A8 (52mm x 74mm). |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Mengurai representasi string dari PaperSize untuk mendapatkan konstanta enum. |
|
|  | [toString()](#toString--) | Representasi string dari PaperSize. |
|
### DEFAULT {#DEFAULT}
```
public static final PaperSize DEFAULT
```


Ukuran kertas default.


### A0 {#A0}
```
public static final PaperSize A0
```


Ukuran kertas standar A0 (841mm x 1189mm).


### A1 {#A1}
```
public static final PaperSize A1
```


Ukuran kertas standar A1 (594mm x 841mm).


### A2 {#A2}
```
public static final PaperSize A2
```


Ukuran kertas standar A2 (420mm x 594mm).


### A3 {#A3}
```
public static final PaperSize A3
```


Ukuran kertas standar A3 (297mm x 420mm).


### A4 {#A4}
```
public static final PaperSize A4
```


Ukuran kertas standar A4 (210mm x 297mm).


### A5 {#A5}
```
public static final PaperSize A5
```


Ukuran kertas standar A5 (148mm x 210mm).


### A6 {#A6}
```
public static final PaperSize A6
```


Ukuran kertas standar A6 (105mm x 148mm).


### A7 {#A7}
```
public static final PaperSize A7
```


Ukuran kertas standar A7 (74mm x 105mm).


### A8 {#A8}
```
public static final PaperSize A8
```


Ukuran kertas standar A8 (52mm x 74mm).


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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[PaperSize](../../com.groupdocs.comparison.options.enums/papersize)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static PaperSize fromString(String toStringValue)
```


Mengurai representasi string dari PaperSize untuk mendapatkan konstanta enum.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | toStringValue | java.lang.String | Representasi string dari PaperSize |
|

**Returns:**
[PaperSize](../../com.groupdocs.comparison.options.enums/papersize) - PaperSize enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


Representasi string dari PaperSize.


**Returns:**
java.lang.String - nilai string dari konstanta enum

