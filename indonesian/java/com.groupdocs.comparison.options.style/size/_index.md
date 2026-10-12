---
title: "Ukuran"
second_title: "Referensi API GroupDocs.Comparison untuk Java"
description: "Mewakili ukuran dokumen dalam perbandingan."
type: docs
weight: 11
url: /id/java/com.groupdocs.comparison.options.style/size/
---
**Inheritance:**
java.lang.Object
```
public class Size
```

Mewakili ukuran dokumen dalam perbandingan.


Contoh penggunaan:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     final Size originalSize = new Size(100, 200);

     StyleSettings styleSettings = new StyleSettings();
     styleSettings.setOriginalSize(originalSize);

     final CompareOptions compareOptions = new CompareOptions();
     compareOptions.setInsertedItemStyle(styleSettings);

     comparer.compare(resultFile, compareOptions);
 }
 
````


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [Size()](#Size--) | Menginisialisasi instance baru dari kelas Size. |
|
|  | [Size(int width, int height)](#Size-int-int-) | Menginisialisasi instance baru dari kelas Size dengan lebar dan tinggi dokumen. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getWidth()](#getWidth--) | Mendapatkan lebar dokumen asli. |
|
|  | [setWidth(int value)](#setWidth-int-) | Mengatur lebar dokumen asli. |
|
|  | [getHeight()](#getHeight--) | Mendapatkan tinggi dokumen asli. |
|
|  | [setHeight(int value)](#setHeight-int-) | Mengatur tinggi dokumen asli. |
|
### Size() {#Size--}
```
public Size()
```


Menginisialisasi instance baru dari kelas Size.


### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


Menginisialisasi instance baru dari kelas Size dengan lebar dan tinggi dokumen.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lebar | int |  |
| tinggi | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Mendapatkan lebar dokumen asli.


**Returns:**
int - lebar dokumen

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Mengatur lebar dokumen asli.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | int | Lebar dokumen |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Mendapatkan tinggi dokumen asli.


**Returns:**
int - tinggi dokumen

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Mengatur tinggi dokumen asli.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | int | Tinggi dokumen |
|

