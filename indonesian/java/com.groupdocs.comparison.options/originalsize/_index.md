---
title: "OriginalSize"
second_title: "Referensi API GroupDocs.Comparison untuk Java"
description: "Mewakili ukuran asli dokumen dalam hasil perbandingan."
type: docs
weight: 14
url: /id/java/com.groupdocs.comparison.options/originalsize/
---
**Inheritance:**
java.lang.Object
```
public class OriginalSize
```

Mewakili ukuran asli dokumen dalam hasil perbandingan.


Ukuran asli mencakup dimensi (lebar dan tinggi) halaman dokumen.


Contoh penggunaan:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     CompareOptions compareOptions = new CompareOptions();
     final OriginalSize originalSize = compareOptions.getOriginalSize();
     originalSize.setWidth(480);
     originalSize.setHeight(640);

     comparer.compare(resultFile, compareOptions);
 }
 
````


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [OriginalSize()](#OriginalSize--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getWidth()](#getWidth--) | Mendapatkan lebar halaman dokumen. |
|
|  | [setWidth(int value)](#setWidth-int-) | Mengatur lebar halaman dokumen. |
|
|  | [getHeight()](#getHeight--) | Mendapatkan tinggi halaman dokumen. |
|
|  | [setHeight(int value)](#setHeight-int-) | Mengatur tinggi halaman dokumen. |
|
### OriginalSize() {#OriginalSize--}
```
public OriginalSize()
```


### getWidth() {#getWidth--}
```
public final int getWidth()
```


Mendapatkan lebar halaman dokumen.


**Returns:**
int - lebar halaman dokumen.

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Mengatur lebar halaman dokumen.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | int | Lebar halaman dokumen. |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Mendapatkan tinggi halaman dokumen.


**Returns:**
int - tinggi halaman dokumen.

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Mengatur tinggi halaman dokumen.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | int | Tinggi halaman dokumen. |
|

