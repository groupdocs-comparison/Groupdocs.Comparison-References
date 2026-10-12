---
title: "ComparisonType"
second_title: "Referensi API GroupDocs.Comparison untuk Java"
description: "Mewakili jenis perbandingan yang akan dilakukan."
type: docs
weight: 10
url: /id/java/com.groupdocs.comparison.options.enums/comparisontype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ComparisonType extends Enum<ComparisonType>
```

Mewakili jenis perbandingan yang akan dilakukan.


Contoh penggunaan:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setComparisonType(ComparisonType.CELLS);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [TEXT](#TEXT) | File harus dibandingkan sebagai dokumen teks. |
|
|  | [SLIDES](#SLIDES) | File harus dibandingkan sebagai dokumen presentasi. |
|
|  | [WORDS](#WORDS) | File harus dibandingkan sebagai dokumen Word. |
|
|  | [CELLS](#CELLS) | File harus dibandingkan sebagai dokumen Excel. |
|
|  | [PDF](#PDF) | File harus dibandingkan sebagai dokumen PDF. |
|
|  | [IMAGING](#IMAGING) | File harus dibandingkan sebagai dokumen gambar. |
|
|  | [EMAIL](#EMAIL) | File harus dibandingkan sebagai dokumen email. |
|
|  | [NOTE](#NOTE) | File harus dibandingkan sebagai dokumen catatan. |
|
|  | [HTML](#HTML) | File harus dibandingkan sebagai dokumen HTML. |
|
|  | [DIAGRAM](#DIAGRAM) | File harus dibandingkan sebagai dokumen diagram. |
|
|  | [DIFFERENT](#DIFFERENT) | File harus dibandingkan sebagai dokumen dalam format yang berbeda. |
|
|  | [SVG](#SVG) | File harus dibandingkan sebagai dokumen SVG. |
|
|  | [UNDEFINED](#UNDEFINED) | Untuk penggunaan internal. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Menganalisis representasi string dari ComparisonType untuk mendapatkan konstanta enum. |
|
|  | [toString()](#toString--) | Representasi string dari ComparisonType. |
|
### TEXT {#TEXT}
```
public static final ComparisonType TEXT
```


File harus dibandingkan sebagai dokumen teks.


### SLIDES {#SLIDES}
```
public static final ComparisonType SLIDES
```


File harus dibandingkan sebagai dokumen presentasi.


### WORDS {#WORDS}
```
public static final ComparisonType WORDS
```


File harus dibandingkan sebagai dokumen Word.


### CELLS {#CELLS}
```
public static final ComparisonType CELLS
```


File harus dibandingkan sebagai dokumen Excel.


### PDF {#PDF}
```
public static final ComparisonType PDF
```


File harus dibandingkan sebagai dokumen PDF.


### IMAGING {#IMAGING}
```
public static final ComparisonType IMAGING
```


File harus dibandingkan sebagai dokumen gambar.


### EMAIL {#EMAIL}
```
public static final ComparisonType EMAIL
```


File harus dibandingkan sebagai dokumen email.


### NOTE {#NOTE}
```
public static final ComparisonType NOTE
```


File harus dibandingkan sebagai dokumen catatan.


### HTML {#HTML}
```
public static final ComparisonType HTML
```


File harus dibandingkan sebagai dokumen HTML.


### DIAGRAM {#DIAGRAM}
```
public static final ComparisonType DIAGRAM
```


File harus dibandingkan sebagai dokumen diagram.


### DIFFERENT {#DIFFERENT}
```
public static final ComparisonType DIFFERENT
```


File harus dibandingkan sebagai dokumen dalam format yang berbeda.


### SVG {#SVG}
```
public static final ComparisonType SVG
```


File harus dibandingkan sebagai dokumen SVG.


### UNDEFINED {#UNDEFINED}
```
public static final ComparisonType UNDEFINED
```


Untuk penggunaan internal.


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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static ComparisonType fromString(String toStringValue)
```


Menganalisis representasi string dari ComparisonType untuk mendapatkan konstanta enum.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | toStringValue | java.lang.String | Representasi string dari ComparisonType |
|

**Returns:**
[ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) - ComparisonType enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


Representasi string dari ComparisonType.


**Returns:**
java.lang.String - nilai string dari konstanta enum

