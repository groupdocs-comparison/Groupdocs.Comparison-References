---
title: "LoadOptions"
second_title: "Referensi API GroupDocs.Comparison untuk Java"
description: "Memungkinkan penentuan opsi tambahan saat memuat dokumen."
type: docs
weight: 10
url: /id/java/com.groupdocs.comparison.options.load/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

Memungkinkan penentuan opsi tambahan saat memuat dokumen.


Contoh penggunaan:

````

 final LoadOptions loadOptions = new LoadOptions();
 loadOptions.setPassword("passw");
 loadOptions.setFileType(FileType.PDF);

 try (Comparer comparer = new Comparer(sourceFile, loadOptions)) {
    comparer.add(targetFile);

    comparer.compare(resultFile);
 }
 
````


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [LoadOptions()](#LoadOptions--) | Menginisialisasi instance baru dari kelas LoadOptions. |
|
|  | [LoadOptions(boolean isLoadText)](#LoadOptions-boolean-) | Menginisialisasi instance baru dari kelas LoadOptions dengan flag yang berarti string masukan adalah teks untuk dibandingkan, bukan jalur. |
|
|  | [LoadOptions(String password)](#LoadOptions-java.lang.String-) | Menginisialisasi instance baru dari kelas LoadOptions dengan kata sandi untuk memuat dokumen. |
|
|  | [LoadOptions(boolean isLoadText, String password)](#LoadOptions-boolean-java.lang.String-) | Menginisialisasi instance baru dari kelas LoadOptions dengan flag yang berarti string masukan adalah teks untuk dibandingkan dan kata sandi untuk memuat dokumen. |
|
|  | [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.comparison.result.FileType-) | Menginisialisasi instance baru dari kelas LoadOptions dengan tipe file. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [isLoadText()](#isLoadText--) | Mendapatkan flag yang menunjukkan bahwa string yang diberikan ke konstruktor [Comparer](../../com.groupdocs.comparison/comparer) atau ke metode [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) adalah teks perbandingan, bukan jalur file (Hanya untuk Perbandingan Teks). |
|
|  | [setLoadText(boolean value)](#setLoadText-boolean-) | Mengatur flag yang menunjukkan bahwa string yang diberikan ke konstruktor [Comparer](../../com.groupdocs.comparison/comparer) atau ke metode [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) adalah teks perbandingan, bukan jalur file (Hanya untuk Perbandingan Teks). |
|
|  | [getPassword()](#getPassword--) | Mendapatkan kata sandi yang akan digunakan untuk memuat dokumen. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Mengatur kata sandi yang harus digunakan untuk memuat dokumen. |
|
|  | [getFontDirectories()](#getFontDirectories--) | Mendapatkan daftar direktori tempat file font untuk memuat dokumen ditempatkan. |
|
|  | [setFontDirectories(List<String> value)](#setFontDirectories-java.util.List-java.lang.String--) | Mengatur daftar direktori tempat file font untuk memuat dokumen ditempatkan. |
|
|  | [getFileType()](#getFileType--) | Mendapatkan tipe file yang sedang dimuat. |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.comparison.result.FileType-) | Mengatur tipe file yang sedang dimuat. |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


Menginisialisasi instance baru dari kelas LoadOptions.


### LoadOptions(boolean isLoadText) {#LoadOptions-boolean-}
```
public LoadOptions(boolean isLoadText)
```


Menginisialisasi instance baru dari kelas LoadOptions dengan flag yang berarti string masukan adalah teks untuk dibandingkan, bukan jalur.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | isLoadText | boolean | Bendera yang berarti bahwa string input adalah teks untuk dibandingkan, bukan jalur |
|

### LoadOptions(String password) {#LoadOptions-java.lang.String-}
```
public LoadOptions(String password)
```


Menginisialisasi instance baru dari kelas LoadOptions dengan kata sandi untuk memuat dokumen.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | kata sandi | java.lang.String | Kata sandi untuk memuat dokumen |
|

### LoadOptions(boolean isLoadText, String password) {#LoadOptions-boolean-java.lang.String-}
```
public LoadOptions(boolean isLoadText, String password)
```


Menginisialisasi instance baru dari kelas LoadOptions dengan flag yang berarti string masukan adalah teks untuk dibandingkan dan kata sandi untuk memuat dokumen.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | isLoadText | boolean | Bendera yang berarti bahwa string input adalah teks untuk dibandingkan, bukan jalur |
|
|  | kata sandi | java.lang.String | Kata sandi untuk memuat dokumen |
|

### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.comparison.result.FileType-}
```
public LoadOptions(FileType fileType)
```


Menginisialisasi instance baru dari kelas LoadOptions dengan tipe file.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.comparison.result/filetype) | Tipe file |
|

### isLoadText() {#isLoadText--}
```
public boolean isLoadText()
```


Mendapatkan flag yang menunjukkan bahwa string yang diberikan ke konstruktor [Comparer](../../com.groupdocs.comparison/comparer) atau ke metode [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) adalah teks perbandingan, bukan jalur file (Hanya untuk Perbandingan Teks).


**Returns:**
boolean - true jika string input adalah teks untuk dibandingkan, jika tidak false

### setLoadText(boolean value) {#setLoadText-boolean-}
```
public void setLoadText(boolean value)
```


Mengatur flag yang menunjukkan bahwa string yang diberikan ke konstruktor [Comparer](../../com.groupdocs.comparison/comparer) atau ke metode [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) adalah teks perbandingan, bukan jalur file (Hanya untuk Perbandingan Teks).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | boolean | true jika string input adalah teks untuk dibandingkan, jika tidak false |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Mendapatkan kata sandi yang akan digunakan untuk memuat dokumen.


**Returns:**
java.lang.String - kata sandi untuk memuat dokumen

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Mengatur kata sandi yang harus digunakan untuk memuat dokumen.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | java.lang.String | Kata sandi untuk memuat dokumen |
|

### getFontDirectories() {#getFontDirectories--}
```
public List<String> getFontDirectories()
```


Mendapatkan daftar direktori tempat file font untuk memuat dokumen ditempatkan.


**Returns:**
java.util.List<java.lang.String> - daftar direktori dengan file font

### setFontDirectories(List<String> value) {#setFontDirectories-java.util.List-java.lang.String--}
```
public void setFontDirectories(List<String> value)
```


Mengatur daftar direktori tempat file font untuk memuat dokumen ditempatkan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | java.util.List<java.lang.String> | Daftar direktori dengan file font |
|

### getFileType() {#getFileType--}
```
public FileType getFileType()
```


Mendapatkan tipe file yang sedang dimuat.


**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the type of the file

### setFileType(FileType value) {#setFileType-com.groupdocs.comparison.result.FileType-}
```
public void setFileType(FileType value)
```


Mengatur tipe file yang sedang dimuat.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [FileType](../../com.groupdocs.comparison.result/filetype) | Tipe file |
|

