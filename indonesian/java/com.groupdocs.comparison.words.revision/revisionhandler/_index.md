---
title: "RevisionHandler"
second_title: "Referensi API GroupDocs.Comparison untuk Java"
description: "Mewakili kelas yang mengontrol penanganan revisi."
type: docs
weight: 11
url: /id/java/com.groupdocs.comparison.words.revision/revisionhandler/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class RevisionHandler implements Closeable
```

Mewakili kelas yang mengontrol penanganan revisi.


Kelas RevisionHandler memungkinkan Anda bekerja dengan revisi dalam dokumen.
Ini menyediakan metode untuk mengambil daftar revisi, menerapkan perubahan pada revisi, dan menyimpan dokumen yang dimodifikasi.


Contoh penggunaan:

````

 try (RevisionHandler revisionHandler = new RevisionHandler(sourceFile)) {
     List revisionList = revisionHandler.getRevisions();

     for (RevisionInfo revisionInfo : revisionList) {
         if (revisionInfo.getType() == RevisionType.DELETION)
             // Set an action to be applied to the revision
             revisionInfo.setAction(RevisionAction.Accept);
     }
     // Create an instance of ApplyRevisionOptions
     ApplyRevisionOptions revisionChanges = new ApplyRevisionOptions();
     revisionChanges.setChanges(revisionList);
     // Apply the revisions using the options
     revisionHandler.applyRevisionChanges(resultFile, revisionChanges);
 }
 
````


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [RevisionHandler(String filePath)](#RevisionHandler-java.lang.String-) | Menginisialisasi instance baru dari kelas RevisionHandler dengan jalur ke file yang berisi revisi. |
|
|  | [RevisionHandler(Path filePath)](#RevisionHandler-java.nio.file.Path-) | Menginisialisasi instance baru dari kelas RevisionHandler dengan jalur ke file yang berisi revisi. |
|
|  | [RevisionHandler(InputStream file, FileType fileType)](#RevisionHandler-java.io.InputStream-com.groupdocs.comparison.result.FileType-) | Menginisialisasi instance baru dari kelas RevisionHandler dengan aliran file yang berisi revisi. |
|
|  | [RevisionHandler(Document document)](#RevisionHandler-com.aspose.words.Document-) | Menginisialisasi instance baru dari kelas RevisionHandler dengan sebuah dokumen. |
|
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [SOURCE_PATH_IS_NULL](#SOURCE-PATH-IS-NULL) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getRevisions()](#getRevisions--) | Mendapatkan daftar semua revisi. |
|
|  | [applyRevisionChanges(ApplyRevisionOptions changes)](#applyRevisionChanges-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | Memproses perubahan dalam revisi dan menerapkannya ke file asli. |
|
|  | [applyRevisionChanges(Path filePath, ApplyRevisionOptions changes)](#applyRevisionChanges-java.nio.file.Path-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | Memproses perubahan dalam revisi dan menulis hasilnya ke file yang ditentukan. |
|
|  | [applyRevisionChanges(String filePath, ApplyRevisionOptions changes)](#applyRevisionChanges-java.lang.String-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | Memproses perubahan dalam revisi dan menulis hasilnya ke file yang ditentukan. |
|
|  | [applyRevisionChanges(OutputStream outputStream, ApplyRevisionOptions changes)](#applyRevisionChanges-java.io.OutputStream-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | Memproses perubahan dalam revisi dan menulis hasilnya ke aliran dokumen. |
|
| [close()](#close--) |  |
### RevisionHandler(String filePath) {#RevisionHandler-java.lang.String-}
```
public RevisionHandler(String filePath)
```


Menginisialisasi instance baru dari kelas RevisionHandler dengan jalur ke file yang berisi revisi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.lang.String | Jalur ke file. |
|

### RevisionHandler(Path filePath) {#RevisionHandler-java.nio.file.Path-}
```
public RevisionHandler(Path filePath)
```


Menginisialisasi instance baru dari kelas RevisionHandler dengan jalur ke file yang berisi revisi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Jalur ke file. |
|

### RevisionHandler(InputStream file, FileType fileType) {#RevisionHandler-java.io.InputStream-com.groupdocs.comparison.result.FileType-}
```
public RevisionHandler(InputStream file, FileType fileType)
```


Menginisialisasi instance baru dari kelas RevisionHandler dengan aliran file yang berisi revisi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | file | java.io.InputStream | Aliran dokumen sumber. |
|
|  | fileType | [FileType](../../com.groupdocs.comparison.result/filetype) | Tipe berkas. |
|

### RevisionHandler(Document document) {#RevisionHandler-com.aspose.words.Document-}
```
public RevisionHandler(Document document)
```


Menginisialisasi instance baru dari kelas RevisionHandler dengan sebuah dokumen.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | dokumen | com.aspose.words.Document | Dokumen. |
|

### SOURCE_PATH_IS_NULL {#SOURCE-PATH-IS-NULL}
```
public static final String SOURCE_PATH_IS_NULL
```


### getRevisions() {#getRevisions--}
```
public List<RevisionInfo> getRevisions()
```


Mendapatkan daftar semua revisi.


Karena revisi awalnya diurutkan dalam satu grup, revisi harus diambil dari sebuah List.
Dalam List, satu revisi dapat dibagi menjadi beberapa revisi dengan teks umum yang sama.
Karena List dapat berisi revisi dengan teks umum yang sama, hal ini harus dikendalikan saat membuat daftar revisi untuk pengguna.
Ini dikendalikan di sini menggunakan grup List\<RevisionGroup\>.


**Returns:**
java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> - daftar revisi.

### applyRevisionChanges(ApplyRevisionOptions changes) {#applyRevisionChanges-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(ApplyRevisionOptions changes)
```


Memproses perubahan dalam revisi dan menerapkannya ke file asli.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | Daftar revisi yang diubah. |
|

### applyRevisionChanges(Path filePath, ApplyRevisionOptions changes) {#applyRevisionChanges-java.nio.file.Path-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(Path filePath, ApplyRevisionOptions changes)
```


Memproses perubahan dalam revisi dan menulis hasilnya ke file yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Jalur berkas hasil. |
|
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | Daftar revisi yang diubah. |
|

### applyRevisionChanges(String filePath, ApplyRevisionOptions changes) {#applyRevisionChanges-java.lang.String-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(String filePath, ApplyRevisionOptions changes)
```


Memproses perubahan dalam revisi dan menulis hasilnya ke file yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.lang.String | Jalur berkas hasil. |
|
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | Daftar revisi yang diubah. |
|

### applyRevisionChanges(OutputStream outputStream, ApplyRevisionOptions changes) {#applyRevisionChanges-java.io.OutputStream-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(OutputStream outputStream, ApplyRevisionOptions changes)
```


Memproses perubahan dalam revisi dan menulis hasilnya ke aliran dokumen.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | outputStream | java.io.OutputStream | Aliran dokumen hasil. |
|
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | Daftar revisi yang diubah. |
|

### close() {#close--}
```
public void close()
```




