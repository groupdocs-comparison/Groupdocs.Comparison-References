---
title: "FileAuthorMetadata"
second_title: "Referensi API GroupDocs.Comparison untuk Java"
description: "Memungkinkan mengonfigurasi informasi tentang metadata penulis dokumen."
type: docs
weight: 12
url: /id/java/com.groupdocs.comparison.options/fileauthormetadata/
---
**Inheritance:**
java.lang.Object
```
public class FileAuthorMetadata
```

Memungkinkan konfigurasi informasi tentang metadata penulis dokumen.


Contoh penggunaan:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     SaveOptions saveOptions = new SaveOptions();
     saveOptions.setCloneMetadataType(MetadataType.FILE_AUTHOR);

     final FileAuthorMetadata fileAuthorMetadata = new FileAuthorMetadata();
     fileAuthorMetadata.setAuthor("Tom");
     fileAuthorMetadata.setCompany("GroupDocs");
     fileAuthorMetadata.setLastSaveBy("Jack");

     saveOptions.setFileAuthorMetadata(fileAuthorMetadata);

     comparer.compare(resultFile, saveOptions);
 }
 
````


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [FileAuthorMetadata()](#FileAuthorMetadata--) | Menginisialisasi instance baru dari kelas FileAuthorMetadata. |
|
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [GROUP_DOCS](#GROUP-DOCS) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getAuthor()](#getAuthor--) | Mendapatkan penulis dokumen. |
|
|  | [setAuthor(String value)](#setAuthor-java.lang.String-) | Mengatur penulis dokumen. |
|
|  | [getLastSaveBy()](#getLastSaveBy--) | Mendapatkan nama orang yang menyimpan dokumen untuk terakhir kalinya. |
|
|  | [setLastSaveBy(String value)](#setLastSaveBy-java.lang.String-) | Mengatur nama orang yang menyimpan dokumen untuk terakhir kalinya. |
|
|  | [getCompany()](#getCompany--) | Mendapatkan nama perusahaan yang dokumennya. |
|
|  | [setCompany(String value)](#setCompany-java.lang.String-) | Mengatur nama perusahaan yang dokumennya. |
|
### FileAuthorMetadata() {#FileAuthorMetadata--}
```
public FileAuthorMetadata()
```


Menginisialisasi instance baru dari kelas FileAuthorMetadata.


### GROUP_DOCS {#GROUP-DOCS}
```
public static final String GROUP_DOCS
```


### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```


Mendapatkan penulis dokumen.


**Returns:**
java.lang.String - penulis

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```


Mengatur penulis dokumen.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | java.lang.String | Penulis |
|

### getLastSaveBy() {#getLastSaveBy--}
```
public final String getLastSaveBy()
```


Mendapatkan nama orang yang menyimpan dokumen untuk terakhir kalinya.


**Returns:**
java.lang.String - nama

### setLastSaveBy(String value) {#setLastSaveBy-java.lang.String-}
```
public final void setLastSaveBy(String value)
```


Mengatur nama orang yang menyimpan dokumen untuk terakhir kalinya.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | java.lang.String | Nama orang |
|

### getCompany() {#getCompany--}
```
public final String getCompany()
```


Mendapatkan nama perusahaan yang dokumennya.


**Returns:**
java.lang.String - nama perusahaan

### setCompany(String value) {#setCompany-java.lang.String-}
```
public final void setCompany(String value)
```


Mengatur nama perusahaan yang dokumennya.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | java.lang.String | Nama perusahaan |
|

