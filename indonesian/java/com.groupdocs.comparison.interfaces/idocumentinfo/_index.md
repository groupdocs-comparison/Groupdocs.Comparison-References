---
title: "IDocumentInfo"
second_title: "Referensi API GroupDocs.Comparison untuk Java"
description: "Menyediakan akses ke properti dokumen."
type: docs
weight: 10
url: /id/java/com.groupdocs.comparison.interfaces/idocumentinfo/
---
**All Implemented Interfaces:**
java.io.Closeable
```
public interface IDocumentInfo extends Closeable
```

Menyediakan akses ke properti dokumen.


Detail lebih lanjut tentang penggunaannya dapat ditemukan di metode [Document.getDocumentInfo()](../../com.groupdocs.comparison/document#getDocumentInfo--) atau dalam [dokumentasi](../https://docs.groupdocs.com/comparison/java/get-file-info/).


Contoh penggunaan:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    try (IDocumentInfo documentInfo = comparer.getSource().getDocumentInfo()) {
      for (int i = 0; i < documentInfo.getPageCount(); i++) {
          System.out.printf("File type: %s%nNumber of pages: %d", documentInfo.getFileType().getFileFormat(), documentInfo.getPageCount());
      }
    }
 }
 
````


## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getFileType()](#getFileType--) | Mendapatkan tipe file yang direpresentasikan oleh enum [FileType](../../com.groupdocs.comparison.result/filetype). |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.comparison.result.FileType-) | Mengatur tipe file menggunakan enum [FileType](../../com.groupdocs.comparison.result/filetype). |
|
|  | [getPageCount()](#getPageCount--) | Mendapatkan jumlah file. |
|
|  | [setPageCount(int value)](#setPageCount-int-) | Mengatur jumlah file. |
|
|  | [getSize()](#getSize--) | Mendapatkan ukuran file. |
|
|  | [setSize(long value)](#setSize-long-) | Mengatur ukuran file. |
|
|  | [getPagesInfo()](#getPagesInfo--) | Mendapatkan informasi untuk setiap halaman file menggunakan kelas [PageInfo](../../com.groupdocs.comparison.result/pageinfo). |
|
|  | [setPagesInfo(List<PageInfo> pageInfos)](#setPagesInfo-java.util.List-com.groupdocs.comparison.result.PageInfo--) | Mengatur informasi untuk setiap halaman file menggunakan kelas [PageInfo](../../com.groupdocs.comparison.result/pageinfo). |
|
|  | [close()](#close--) | Menghancurkan objek sehingga tidak mungkin mendapatkan informasi dokumen menggunakan instance [IDocumentInfo](../../com.groupdocs.comparison.interfaces/idocumentinfo) ini. |
|
### getFileType() {#getFileType--}
```
public abstract FileType getFileType()
```


Mendapatkan tipe file yang direpresentasikan oleh enum [FileType](../../com.groupdocs.comparison.result/filetype).


**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the type of the file

### setFileType(FileType value) {#setFileType-com.groupdocs.comparison.result.FileType-}
```
public abstract void setFileType(FileType value)
```


Mengatur tipe file menggunakan enum [FileType](../../com.groupdocs.comparison.result/filetype).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [FileType](../../com.groupdocs.comparison.result/filetype) | Tipe file |
|

### getPageCount() {#getPageCount--}
```
public abstract int getPageCount()
```


Mendapatkan jumlah file.


**Returns:**
int - jumlah file

### setPageCount(int value) {#setPageCount-int-}
```
public abstract void setPageCount(int value)
```


Mengatur jumlah file.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | int | Jumlah file |
|

### getSize() {#getSize--}
```
public abstract long getSize()
```


Mendapatkan ukuran file.


**Returns:**
long - ukuran file

### setSize(long value) {#setSize-long-}
```
public abstract void setSize(long value)
```


Mengatur ukuran file.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | long | Ukuran file |
|

### getPagesInfo() {#getPagesInfo--}
```
public abstract List<PageInfo> getPagesInfo()
```


Mendapatkan informasi untuk setiap halaman file menggunakan kelas [PageInfo](../../com.groupdocs.comparison.result/pageinfo).


**Returns:**
java.util.List<com.groupdocs.comparison.result.PageInfo> - informasi untuk setiap halaman file

### setPagesInfo(List<PageInfo> pageInfos) {#setPagesInfo-java.util.List-com.groupdocs.comparison.result.PageInfo--}
```
public abstract void setPagesInfo(List<PageInfo> pageInfos)
```


Mengatur informasi untuk setiap halaman file menggunakan kelas [PageInfo](../../com.groupdocs.comparison.result/pageinfo).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | pageInfos | java.util.List<com.groupdocs.comparison.result.PageInfo> | Informasi untuk setiap halaman file |
|

### close() {#close--}
```
public abstract void close()
```


Menghancurkan objek sehingga tidak mungkin mendapatkan informasi dokumen menggunakan instance [IDocumentInfo](../../com.groupdocs.comparison.interfaces/idocumentinfo) ini.
Juga menghapus file sementara dan melepaskan sumber daya yang digunakan.


