---
title: "GetChangeOptions"
second_title: "Referensi API GroupDocs.Comparison untuk Java"
description: "Memungkinkan konfigurasi penyaringan untuk mengambil jenis perubahan tertentu dari hasil perbandingan."
type: docs
weight: 13
url: /id/java/com.groupdocs.comparison.options/getchangeoptions/
---
**Inheritance:**
java.lang.Object
```
public class GetChangeOptions
```

Memungkinkan konfigurasi penyaringan untuk mengambil jenis perubahan tertentu dari hasil perbandingan.


Contoh penggunaan:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);
     comparer.compare();

     GetChangeOptions getChangeOptions = new GetChangeOptions();

     getChangeOptions.setFilter(ChangeType.DELETED);

     ChangeInfo[] changes = comparer.getChanges(getChangeOptions);
     System.out.println(Arrays.toString(changes));
 }
 
````


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [GetChangeOptions()](#GetChangeOptions--) | Menginisialisasi instance baru dari kelas GetChangeOptions. |
|
|  | [GetChangeOptions(ChangeType filter)](#GetChangeOptions-com.groupdocs.comparison.result.ChangeType-) | Menginisialisasi instance baru dari kelas GetChangeOptions untuk tipe filter yang ditentukan. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getFilter()](#getFilter--) | Mendapatkan filter untuk mengambil tipe perubahan spesifik dari hasil perbandingan. |
|
|  | [setFilter(ChangeType value)](#setFilter-com.groupdocs.comparison.result.ChangeType-) | Mengatur filter untuk mengambil tipe perubahan spesifik dari hasil perbandingan. |
|
### GetChangeOptions() {#GetChangeOptions--}
```
public GetChangeOptions()
```


Menginisialisasi instance baru dari kelas GetChangeOptions.


### GetChangeOptions(ChangeType filter) {#GetChangeOptions-com.groupdocs.comparison.result.ChangeType-}
```
public GetChangeOptions(ChangeType filter)
```


Menginisialisasi instance baru dari kelas GetChangeOptions untuk tipe filter yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filter | [ChangeType](../../com.groupdocs.comparison.result/changetype) |  |

### getFilter() {#getFilter--}
```
public final ChangeType getFilter()
```


Mendapatkan filter untuk mengambil tipe perubahan spesifik dari hasil perbandingan.


**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - the filter specifying the types of changes to be retrieved.

### setFilter(ChangeType value) {#setFilter-com.groupdocs.comparison.result.ChangeType-}
```
public final void setFilter(ChangeType value)
```


Mengatur filter untuk mengambil tipe perubahan spesifik dari hasil perbandingan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [ChangeType](../../com.groupdocs.comparison.result/changetype) | Filter yang menentukan tipe perubahan yang akan diambil. |
|

