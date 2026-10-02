---
title: "PageInfo"
second_title: "Referensi API GroupDocs.Comparison untuk Java"
description: "Kelas PageInfo mewakili informasi tentang halaman spesifik dalam sebuah dokumen."
type: docs
weight: 11
url: /id/java/com.groupdocs.comparison.result/pageinfo/
---
**Inheritance:**
java.lang.Object
```
public class PageInfo
```

Kelas PageInfo mewakili informasi tentang halaman spesifik dalam sebuah dokumen.


Ini menyediakan detail seperti nomor halaman, lebar, tinggi, dan properti relevan lainnya.
Gunakan kelas ini untuk mengambil informasi tentang halaman individual dalam dokumen selama proses perbandingan.


Contoh penggunaan:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     comparer.compare(resultFile);
     final ChangeInfo[] changes = comparer.getChanges();
     for (ChangeInfo change : changes) {
         final PageInfo pageInfo = change.getPageInfo();
         // Print the page information
         System.out.println("Page Number: " + pageInfo.getPageNumber());
         System.out.println("Page Width: " + pageInfo.getWidth());
         System.out.println("Page Height: " + pageInfo.getHeight());
     }
 }
 
````


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [PageInfo(int pageNumber, int width, int height)](#PageInfo-int-int-int-) | Menginisialisasi instance baru dari kelas PageInfo dengan mengkonfigurasi pageNumber, lebar, dan tinggi. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getWidth()](#getWidth--) | Mendapatkan lebar halaman |
|
|  | [setWidth(int value)](#setWidth-int-) | Mengatur lebar halaman |
|
|  | [getHeight()](#getHeight--) | Mendapatkan tinggi halaman |
|
|  | [setHeight(int value)](#setHeight-int-) | Mengatur tinggi halaman |
|
|  | [getPageNumber()](#getPageNumber--) | Mendapatkan nomor halaman |
|
|  | [setPageNumber(int value)](#setPageNumber-int-) | Mengatur nomor halaman |
|
| [toString()](#toString--) |  |
### PageInfo(int pageNumber, int width, int height) {#PageInfo-int-int-int-}
```
public PageInfo(int pageNumber, int width, int height)
```


Menginisialisasi instance baru dari kelas PageInfo dengan mengkonfigurasi pageNumber, lebar, dan tinggi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | pageNumber | int | Nomor halaman |
|
|  | lebar | int | Lebar halaman |
|
|  | tinggi | int | Tinggi halaman |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Mendapatkan lebar halaman


**Returns:**
int - lebar halaman

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Mengatur lebar halaman


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | int | Lebar halaman |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Mendapatkan tinggi halaman


**Returns:**
int - tinggi halaman

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Mengatur tinggi halaman


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | int | Tinggi halaman |
|

### getPageNumber() {#getPageNumber--}
```
public final int getPageNumber()
```


Mendapatkan nomor halaman


**Returns:**
int - nomor halaman

### setPageNumber(int value) {#setPageNumber-int-}
```
public final void setPageNumber(int value)
```


Mengatur nomor halaman


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | int | Nomor halaman |
|

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
