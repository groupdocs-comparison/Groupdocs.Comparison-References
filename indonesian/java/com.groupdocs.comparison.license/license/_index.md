---
title: "Lisensi"
second_title: "Referensi API GroupDocs.Comparison untuk Java"
description: "Kelas License menyediakan metode untuk mengatur dan menerapkan lisensi untuk GroupDocs.Comparison."
type: docs
weight: 10
url: /id/java/com.groupdocs.comparison.license/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

Kelas License menyediakan metode untuk mengatur dan menerapkan lisensi untuk GroupDocs.Comparison.


Ini memungkinkan Anda mengaktifkan atau menonaktifkan fitur khusus dari perpustakaan berdasarkan lisensi yang diterapkan.

* More about GroupDocs.Comparison licensing: [Evaluation Limitations and Licensing](../https://docs.groupdocs.com/display/comparisonjava/Evaluation+Limitations+and+Licensing+of+GroupDocs.Comparison)


Contoh penggunaan:

````

 final License license = new License();
 license.setLicense("GroupDocs.License.lic");
 
````


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [License()](#License--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [isValidLicense()](#isValidLicense--) | Mendapatkan nilai yang menunjukkan apakah lisensi telah diatur atau tidak. |
|
|  | [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | Mengatur lisensi untuk Comparison menggunakan aliran masukan. |
|
|  | [setLicense(Path licensePath)](#setLicense-java.nio.file.Path-) | Mengatur lisensi untuk Comparison menggunakan jalur file lisensi. |
|
|  | [setLicense(String licensePath)](#setLicense-java.lang.String-) | Mengatur lisensi untuk Comparison menggunakan jalur file lisensi. |
|
### License() {#License--}
```
public License()
```


### isValidLicense() {#isValidLicense--}
```
public static boolean isValidLicense()
```


Mendapatkan nilai yang menunjukkan apakah lisensi telah diatur atau tidak.


**Returns:**
boolean - true jika lisensi berhasil diatur, jika tidak false

### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


Mengatur lisensi untuk Comparison menggunakan aliran masukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | licenseStream | java.io.InputStream | Aliran lisensi, null menghapus lisensi |
|

### setLicense(Path licensePath) {#setLicense-java.nio.file.Path-}
```
public final void setLicense(Path licensePath)
```


Mengatur lisensi untuk Comparison menggunakan jalur file lisensi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | licensePath | java.nio.file.Path | Jalur file lisensi |
|

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


Mengatur lisensi untuk Comparison menggunakan jalur file lisensi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | licensePath | java.lang.String | Jalur file lisensi |
|

