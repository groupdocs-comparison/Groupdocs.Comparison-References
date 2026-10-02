---
title: "SaveOptions"
second_title: "Referensi API GroupDocs.Comparison untuk Java"
description: "Memungkinkan penentuan opsi tambahan saat menyimpan sebuah dokumen."
type: docs
weight: 10
url: /id/java/com.groupdocs.comparison.options.save/saveoptions/
---
**Inheritance:**
java.lang.Object
```
public class SaveOptions
```

Memungkinkan penentuan opsi tambahan saat menyimpan sebuah dokumen.


Contoh penggunaan:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    final SaveOptions saveOptions = new SaveOptions();
    saveOptions.setPassword("passw");

    comparer.compare(resultFile, saveOptions);
 }
 
````


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [SaveOptions()](#SaveOptions--) | Menginisialisasi instance baru dari kelas SaveOptions. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getCloneMetadataType()](#getCloneMetadataType--) | Mendapatkan strategi pemrosesan metadata penyimpanan dokumen hasil. |
|
|  | [setCloneMetadataType(MetadataType value)](#setCloneMetadataType-com.groupdocs.comparison.options.enums.MetadataType-) | Mengatur strategi pemrosesan metadata penyimpanan dokumen hasil. |
|
|  | [getFileAuthorMetadata()](#getFileAuthorMetadata--) | Mendapatkan objek metadata yang akan dimasukkan ke dalam dokumen hasil ketika [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) disetel ke [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR). |
|
|  | [setFileAuthorMetadata(FileAuthorMetadata value)](#setFileAuthorMetadata-com.groupdocs.comparison.options.FileAuthorMetadata-) | Mengatur objek metadata yang harus dimasukkan ke dalam dokumen hasil ketika [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) disetel ke [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR). |
|
|  | [getPassword()](#getPassword--) | Mendapatkan kata sandi untuk dokumen hasil. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Mengatur kata sandi untuk dokumen hasil. |
|
|  | [getFolderPath()](#getFolderPath--) | Mendapatkan jalur folder tempat gambar hasil akan disimpan. |
|
|  | [setFolderPath(String value)](#setFolderPath-java.lang.String-) | Mengatur jalur folder tempat gambar hasil harus disimpan. |
|
|  | [setFolderPath(Path value)](#setFolderPath-java.nio.file.Path-) | Mengatur jalur folder tempat gambar hasil harus disimpan. |
|
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```


Menginisialisasi instance baru dari kelas SaveOptions.


### getCloneMetadataType() {#getCloneMetadataType--}
```
public final MetadataType getCloneMetadataType()
```


Mendapatkan strategi pemrosesan metadata penyimpanan dokumen hasil.
Nilai yang mungkin ada di enum [MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype)


**Returns:**
[MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) - the stragegy of processing metadata

### setCloneMetadataType(MetadataType value) {#setCloneMetadataType-com.groupdocs.comparison.options.enums.MetadataType-}
```
public final void setCloneMetadataType(MetadataType value)
```


Mengatur strategi pemrosesan metadata penyimpanan dokumen hasil.
Nilai yang mungkin ada di enum [MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) | Strategi pemrosesan metadata |
|

### getFileAuthorMetadata() {#getFileAuthorMetadata--}
```
public final FileAuthorMetadata getFileAuthorMetadata()
```


Mendapatkan objek metadata yang akan dimasukkan ke dalam dokumen hasil ketika [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) disetel ke [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR).


**Returns:**
[FileAuthorMetadata](../../com.groupdocs.comparison.options/fileauthormetadata) - the metadata object

### setFileAuthorMetadata(FileAuthorMetadata value) {#setFileAuthorMetadata-com.groupdocs.comparison.options.FileAuthorMetadata-}
```
public final void setFileAuthorMetadata(FileAuthorMetadata value)
```


Mengatur objek metadata yang harus dimasukkan ke dalam dokumen hasil ketika [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) disetel ke [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [FileAuthorMetadata](../../com.groupdocs.comparison.options/fileauthormetadata) | Objek metadata |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Mendapatkan kata sandi untuk dokumen hasil.


**Returns:**
java.lang.String - kata sandi

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Mengatur kata sandi untuk dokumen hasil.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | java.lang.String | Kata sandi |
|

### getFolderPath() {#getFolderPath--}
```
public final String getFolderPath()
```


Mendapatkan jalur folder tempat gambar hasil akan disimpan.
Hanya digunakan untuk Perbandingan Imaging.


**Returns:**
java.lang.String - jalur folder untuk menyimpan gambar hasil

### setFolderPath(String value) {#setFolderPath-java.lang.String-}
```
public final void setFolderPath(String value)
```


Mengatur jalur folder tempat gambar hasil harus disimpan.
Hanya digunakan untuk Perbandingan Imaging.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | java.lang.String | Jalur folder untuk menyimpan gambar hasil |
|

### setFolderPath(Path value) {#setFolderPath-java.nio.file.Path-}
```
public final void setFolderPath(Path value)
```


Mengatur jalur folder tempat gambar hasil harus disimpan.
Hanya digunakan untuk Perbandingan Imaging.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | java.nio.file.Path | Jalur folder untuk menyimpan gambar hasil |
|

