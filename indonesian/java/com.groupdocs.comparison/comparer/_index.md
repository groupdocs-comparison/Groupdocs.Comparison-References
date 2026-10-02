---
title: "Comparer"
second_title: "Referensi API GroupDocs.Comparison untuk Java"
description: "Kelas Comparer menyediakan fungsionalitas untuk membandingkan dokumen dan menghasilkan hasil perbandingan."
type: docs
weight: 10
url: /id/java/com.groupdocs.comparison/comparer/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public class Comparer implements System.IDisposable, Closeable
```

Kelas Comparer menyediakan fungsionalitas untuk membandingkan dokumen dan menghasilkan hasil perbandingan.


Ini memungkinkan Anda membandingkan berbagai jenis dokumen, seperti PDF, Word, Excel, PowerPoint, dan lainnya.


Contoh penggunaan:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     CompareOptions compareOptions = new CompareOptions();
     compareOptions.setDetectStyleChanges(true);

     comparer.compare(resultFile, compareOptions);
 }
 
````


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [Comparer(String filePath)](#Comparer-java.lang.String-) | Menginisialisasi instance baru kelas Comparer dengan jalur file sumber yang ditentukan. |
|
|  | [Comparer(String filePath, CompareOptions compareOptions)](#Comparer-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | Menginisialisasi instance baru kelas Comparer dengan jalur folder dan opsi perbandingan yang ditentukan. |
|
|  | [Comparer(Path filePath)](#Comparer-java.nio.file.Path-) | Menginisialisasi instance baru kelas Comparer dengan jalur file sumber yang ditentukan. |
|
|  | [Comparer(String filePath, LoadOptions loadOptions)](#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-) | Menginisialisasi instance baru Comparer dengan jalur file sumber yang ditentukan dan [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions). |
|
|  | [Comparer(Path filePath, LoadOptions loadOptions)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-) | Menginisialisasi instance baru Comparer dengan jalur file sumber yang ditentukan dan [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions). |
|
|  | [Comparer(Path filePath, CompareOptions compareOptions)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | Menginisialisasi instance baru Comparer dengan jalur file sumber yang ditentukan dan [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions). |
|
|  | [Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings)](#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-) | Menginisialisasi instance baru dari kelas Comparer dengan jalur file sumber yang ditentukan, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) dan [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)](#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-) | Menginisialisasi instance baru dari kelas Comparer dengan jalur file sumber yang ditentukan, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) dan [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(String filePath, ComparerSettings settings)](#Comparer-java.lang.String-com.groupdocs.comparison.ComparerSettings-) | Menginisialisasi instance baru dari kelas Comparer dengan jalur file sumber yang ditentukan dan [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(Path filePath, ComparerSettings settings)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.ComparerSettings-) | Menginisialisasi instance baru dari kelas Comparer dengan jalur file sumber yang ditentukan dan [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-) | Menginisialisasi instance baru dari kelas Comparer dengan jalur file sumber yang ditentukan, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) dan [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-) | Menginisialisasi instance baru dari kelas Comparer dengan jalur file sumber yang ditentukan, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) dan [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(InputStream document)](#Comparer-java.io.InputStream-) | Menginisialisasi instance baru dari kelas Comparer dengan aliran dokumen sumber yang ditentukan. |
|
|  | [Comparer(InputStream document, LoadOptions loadOptions)](#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-) | Menginisialisasi instance baru dari Comparer dengan aliran dokumen sumber yang ditentukan dan [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions). |
|
|  | [Comparer(InputStream document, ComparerSettings settings)](#Comparer-java.io.InputStream-com.groupdocs.comparison.ComparerSettings-) | Menginisialisasi instance baru dari kelas Comparer dengan aliran dokumen sumber yang ditentukan dan [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(InputStream document, LoadOptions loadOptions, ComparerSettings settings)](#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-) | Menginisialisasi instance baru dari kelas Comparer dengan aliran dokumen yang ditentukan, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) dan [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(ComparerSettings settings)](#Comparer-com.groupdocs.comparison.ComparerSettings-) | Menginisialisasi instance baru dari kelas Comparer dengan [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [FILE_PATH](#FILE-PATH) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getSource()](#getSource--) | Mendapatkan dokumen sumber yang sedang dibandingkan. |
|
|  | [getTargets()](#getTargets--) | Daftar dokumen target untuk dibandingkan dengan file sumber. |
|
|  | [compare()](#compare--) | Membandingkan file yang ditentukan dengan dokumen target tanpa menyimpan hasil dengan opsi default. |
|
|  | [compare(String filePath)](#compare-java.lang.String-) | Membandingkan file yang ditentukan dengan dokumen target dan menghasilkan hasil perbandingan. |
|
|  | [compare(Path filePath)](#compare-java.nio.file.Path-) | Membandingkan file yang ditentukan dengan dokumen target dan menghasilkan hasil perbandingan. |
|
|  | [compare(OutputStream outputStream)](#compare-java.io.OutputStream-) | Membandingkan file yang ditentukan dengan dokumen target dan menulis hasil perbandingan ke aliran output. |
|
|  | [compare(String filePath, CompareOptions compareOptions)](#compare-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | Membandingkan file yang ditentukan dengan dokumen target dan menulis hasil perbandingan ke jalur file yang disediakan. |
|
|  | [compare(Path filePath, CompareOptions compareOptions)](#compare-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | Membandingkan file yang ditentukan dengan dokumen target dan menulis hasil perbandingan ke jalur file yang disediakan. |
|
|  | [compare(OutputStream stream, CompareOptions compareOptions)](#compare-java.io.OutputStream-com.groupdocs.comparison.options.CompareOptions-) | Membandingkan file yang ditentukan dengan dokumen target dan menulis hasil perbandingan ke aliran output. |
|
|  | [compare(SaveOptions saveOptions, CompareOptions compareOptions)](#compare-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | Membandingkan file yang ditentukan dengan dokumen target tanpa menyimpan hasil. |
|
|  | [compare(String filePath, SaveOptions saveOptions)](#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-) | Membandingkan file yang ditentukan dengan dokumen target dan menulis hasil perbandingan ke jalur file yang disediakan. |
|
|  | [compare(Path filePath, SaveOptions saveOptions)](#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-) | Membandingkan file yang ditentukan dengan dokumen target dan menulis hasil perbandingan ke jalur file yang disediakan. |
|
|  | [compare(OutputStream stream, SaveOptions saveOptions)](#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-) | Membandingkan file yang ditentukan dengan dokumen target dan menulis hasil perbandingan ke jalur file yang disediakan. |
|
|  | [compare(CompareOptions compareOptions)](#compare-com.groupdocs.comparison.options.CompareOptions-) | Membandingkan file yang ditentukan dengan dokumen target tanpa menyimpan hasil. |
|
|  | [compare(OutputStream outputStream, SaveOptions saveOptions, CompareOptions compareOptions)](#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | Membandingkan file yang ditentukan dengan dokumen target dan menulis hasil perbandingan ke aliran output yang disediakan. |
|
|  | [compare(String filePath, SaveOptions saveOptions, CompareOptions compareOptions)](#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | Membandingkan file yang ditentukan dengan dokumen target dan menulis hasil perbandingan ke jalur file yang disediakan. |
|
|  | [compareDirectory(String filePath, CompareOptions compareOptions)](#compareDirectory-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | Membandingkan direktori yang ditentukan dengan direktori target dan menyimpan hasil perbandingan ke jalur file yang disediakan. |
|
|  | [compareDirectory(Path filePath, CompareOptions compareOptions)](#compareDirectory-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | Membandingkan direktori yang ditentukan dengan direktori target dan menyimpan hasil perbandingan ke jalur file yang disediakan. |
|
|  | [compare(Path filePath, SaveOptions saveOptions, CompareOptions compareOptions)](#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | Membandingkan file yang ditentukan dengan dokumen target dan menulis hasil perbandingan ke jalur file yang disediakan. |
|
|  | [add(String filePath)](#add-java.lang.String-) | Menambahkan dokumen target yang ditentukan ke proses perbandingan. |
|
|  | [add(String filePath, CompareOptions compareOptions)](#add-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | Menambahkan dokumen atau folder target yang ditentukan ke proses perbandingan. |
|
|  | [add(Path filePath)](#add-java.nio.file.Path-) | Menambahkan dokumen target yang ditentukan ke proses perbandingan. |
|
|  | [add(String[] filePaths)](#add-java.lang.String...-) | Menambahkan dokumen target yang ditentukan ke proses perbandingan. |
|
|  | [add(Path[] filePaths)](#add-java.nio.file.Path...-) | Menambahkan dokumen target yang ditentukan ke proses perbandingan. |
|
|  | [add(String filePath, LoadOptions loadOptions)](#add-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-) | Menambahkan dokumen target yang ditentukan ke proses perbandingan dengan opsi pemuatan yang ditentukan. |
|
|  | [add(Path filePath, LoadOptions loadOptions)](#add-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-) | Menambahkan dokumen target yang ditentukan ke proses perbandingan dengan opsi pemuatan yang ditentukan. |
|
|  | [add(Path filePath, CompareOptions compareOptions)](#add-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | Menambahkan dokumen target yang ditentukan ke proses perbandingan dengan opsi pemuatan yang ditentukan. |
|
|  | [add(InputStream document)](#add-java.io.InputStream-) | Menambahkan dokumen target yang ditentukan ke proses perbandingan. |
|
|  | [add(InputStream[] documents)](#add-java.io.InputStream...-) | Menambahkan dokumen target yang ditentukan ke proses perbandingan. |
|
|  | [add(InputStream document, LoadOptions loadOptions)](#add-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-) | Menambahkan dokumen target yang ditentukan ke proses perbandingan dengan opsi pemuatan yang ditentukan. |
|
|  | [getChanges()](#getChanges--) | Mengambil array objek [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) yang mewakili perubahan yang terdeteksi selama proses perbandingan. |
|
|  | [getChanges(GetChangeOptions getChangeOptions)](#getChanges-com.groupdocs.comparison.options.GetChangeOptions-) | Mengambil array objek [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) yang mewakili perubahan yang terdeteksi selama proses perbandingan. |
|
|  | [applyChanges(String filePath, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.lang.String-com.groupdocs.comparison.options.ApplyChangeOptions-) | Menerima atau menolak perubahan dan menerapkannya ke dokumen hasil. |
|
|  | [applyChanges(Path filePath, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.ApplyChangeOptions-) | Menerima atau menolak perubahan dan menerapkannya ke dokumen yang dihasilkan. |
|
|  | [applyChanges(OutputStream document, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.ApplyChangeOptions-) | Menerima atau menolak perubahan dan menerapkannya ke dokumen yang dihasilkan. |
|
|  | [applyChanges(String filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-) | Menerima atau menolak perubahan dan menerapkannya ke dokumen yang dihasilkan. |
|
|  | [applyChanges(Path filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-) | Menerima atau menolak perubahan dan menerapkannya ke dokumen yang dihasilkan. |
|
|  | [applyChanges(OutputStream document, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-) | Menerima atau menolak perubahan dan menerapkannya ke dokumen yang dihasilkan. |
|
|  | [getResultString()](#getResultString--) | Mendapatkan string hasil setelah perbandingan (Hanya untuk Perbandingan Teks). |
|
|  | [getSourceFolder()](#getSourceFolder--) | Mengembalikan folder sumber yang sedang dibandingkan. |
|
|  | [getTargetFolder()](#getTargetFolder--) | Mengembalikan folder target yang sedang dibandingkan. |
|
|  | [selfComparisonCheck(Document source, Document target)](#selfComparisonCheck-com.groupdocs.comparison.Document-com.groupdocs.comparison.Document-) | Pemeriksaan perbandingan diri (e498c23). |
|
|  | [close()](#close--) | Melepaskan sumber daya. |
|
### Comparer(String filePath) {#Comparer-java.lang.String-}
```
public Comparer(String filePath)
```


Menginisialisasi instance baru kelas Comparer dengan jalur file sumber yang ditentukan.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.lang.String | Path ke dokumen sumber |
|

### Comparer(String filePath, CompareOptions compareOptions) {#Comparer-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(String filePath, CompareOptions compareOptions)
```


Menginisialisasi instance baru kelas Comparer dengan jalur folder dan opsi perbandingan yang ditentukan.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.lang.String | Path ke dokumen atau folder sumber |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Opsi perbandingan untuk perbandingan folder |
|

### Comparer(Path filePath) {#Comparer-java.nio.file.Path-}
```
public Comparer(Path filePath)
```


Menginisialisasi instance baru kelas Comparer dengan jalur file sumber yang ditentukan.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Path ke dokumen sumber |
|

### Comparer(String filePath, LoadOptions loadOptions) {#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Comparer(String filePath, LoadOptions loadOptions)
```


Menginisialisasi instance baru Comparer dengan jalur file sumber yang ditentukan dan [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.lang.String | Path ke dokumen sumber |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Opsi muat khusus yang akan diterapkan pada dokumen |
|

### Comparer(Path filePath, LoadOptions loadOptions) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Comparer(Path filePath, LoadOptions loadOptions)
```


Menginisialisasi instance baru Comparer dengan jalur file sumber yang ditentukan dan [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Path ke dokumen sumber |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Opsi muat khusus yang akan diterapkan pada dokumen |
|

### Comparer(Path filePath, CompareOptions compareOptions) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(Path filePath, CompareOptions compareOptions)
```


Menginisialisasi instance baru Comparer dengan jalur file sumber yang ditentukan dan [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Path ke dokumen sumber |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Opsi perbandingan untuk perbandingan folder |
|

### Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings) {#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings)
```


Menginisialisasi instance baru dari kelas Comparer dengan jalur file sumber yang ditentukan, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) dan [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.lang.String | Path ke dokumen sumber |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Opsi muat khusus yang akan diterapkan pada dokumen |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Pengaturan pembanding yang akan digunakan untuk proses perbandingan |
|

### Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions) {#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)
```


Menginisialisasi instance baru dari kelas Comparer dengan jalur file sumber yang ditentukan, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) dan [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.lang.String | Path ke dokumen, folder, atau teks sumber yang akan dibandingkan |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Opsi muat khusus yang akan diterapkan pada dokumen |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Pengaturan pembanding yang akan digunakan untuk proses perbandingan |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Opsi perbandingan untuk perbandingan folder |
|

### Comparer(String filePath, ComparerSettings settings) {#Comparer-java.lang.String-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(String filePath, ComparerSettings settings)
```


Menginisialisasi instance baru dari kelas Comparer dengan jalur file sumber yang ditentukan dan [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.lang.String | Path ke dokumen sumber |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Pengaturan pembanding yang akan digunakan untuk proses perbandingan |
|

### Comparer(Path filePath, ComparerSettings settings) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(Path filePath, ComparerSettings settings)
```


Menginisialisasi instance baru dari kelas Comparer dengan jalur file sumber yang ditentukan dan [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Path ke dokumen sumber |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Pengaturan pembanding yang akan digunakan untuk proses perbandingan |
|

### Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings)
```


Menginisialisasi instance baru dari kelas Comparer dengan jalur file sumber yang ditentukan, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) dan [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Path ke dokumen sumber |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Opsi muat khusus yang akan diterapkan pada dokumen |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Pengaturan pembanding yang akan digunakan untuk proses perbandingan |
|

### Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)
```


Menginisialisasi instance baru dari kelas Comparer dengan jalur file sumber yang ditentukan, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) dan [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Path ke dokumen atau folder sumber |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Opsi muat khusus yang akan diterapkan pada dokumen |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Pengaturan pembanding yang akan digunakan untuk proses perbandingan |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Opsi perbandingan untuk perbandingan folder |
|

### Comparer(InputStream document) {#Comparer-java.io.InputStream-}
```
public Comparer(InputStream document)
```


Menginisialisasi instance baru dari kelas Comparer dengan aliran dokumen sumber yang ditentukan.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | dokumen | java.io.InputStream | Aliran masukan dokumen sumber |
|

### Comparer(InputStream document, LoadOptions loadOptions) {#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Comparer(InputStream document, LoadOptions loadOptions)
```


Menginisialisasi instance baru dari Comparer dengan aliran dokumen sumber yang ditentukan dan [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | dokumen | java.io.InputStream | Aliran masukan dokumen sumber |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Opsi muat khusus yang akan diterapkan pada dokumen |
|

### Comparer(InputStream document, ComparerSettings settings) {#Comparer-java.io.InputStream-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(InputStream document, ComparerSettings settings)
```


Menginisialisasi instance baru dari kelas Comparer dengan aliran dokumen sumber yang ditentukan dan [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | dokumen | java.io.InputStream | Aliran masukan dokumen sumber |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Pengaturan pembanding yang akan digunakan untuk proses perbandingan |
|

### Comparer(InputStream document, LoadOptions loadOptions, ComparerSettings settings) {#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(InputStream document, LoadOptions loadOptions, ComparerSettings settings)
```


Menginisialisasi instance baru dari kelas Comparer dengan aliran dokumen yang ditentukan, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) dan [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | dokumen | java.io.InputStream | Aliran dengan data dokumen yang akan dibandingkan |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Opsi muat khusus yang akan diterapkan pada dokumen |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Pengaturan pembanding yang akan digunakan untuk proses perbandingan |
|

### Comparer(ComparerSettings settings) {#Comparer-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(ComparerSettings settings)
```


Menginisialisasi instance baru dari kelas Comparer dengan [ComparerSettings](../../com.groupdocs.comparison/comparersettings).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | pengaturan |
|

### FILE_PATH {#FILE-PATH}
```
public static final String FILE_PATH
```


### getSource() {#getSource--}
```
public final Document getSource()
```


Mendapatkan dokumen sumber yang sedang dibandingkan.


**Returns:**
[Document](../../com.groupdocs.comparison/document) - the source document

### getTargets() {#getTargets--}
```
public final List<Document> getTargets()
```


Daftar dokumen target untuk dibandingkan dengan file sumber.


**Returns:**
java.util.List<com.groupdocs.comparison.Document> - dokumen target

### compare() {#compare--}
```
public final Path compare()
```


Membandingkan file yang ditentukan dengan dokumen target tanpa menyimpan hasil dengan opsi default.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Returns:**
java.nio.file.Path - path dokumen hasil atau null

### compare(String filePath) {#compare-java.lang.String-}
```
public final Path compare(String filePath)
```


Membandingkan file yang ditentukan dengan dokumen target dan menghasilkan hasil perbandingan.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.lang.String | Path dokumen hasil |
|

**Returns:**
java.nio.file.Path - path file hasil atau null. Dalam beberapa situasi ekstensi dapat diubah

### compare(Path filePath) {#compare-java.nio.file.Path-}
```
public final Path compare(Path filePath)
```


Membandingkan file yang ditentukan dengan dokumen target dan menghasilkan hasil perbandingan.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Path dokumen hasil |
|

**Returns:**
java.nio.file.Path - path file hasil, dalam beberapa situasi ekstensi dapat diubah

### compare(OutputStream outputStream) {#compare-java.io.OutputStream-}
```
public final Path compare(OutputStream outputStream)
```


Membandingkan file yang ditentukan dengan dokumen target dan menulis hasil perbandingan ke aliran output.


Catatan: Jika nilai kembali null, gunakan data yang ditulis ke outputStream

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | outputStream | java.io.OutputStream | Aliran dokumen hasil |
|

**Returns:**
java.nio.file.Path - path file hasil atau null ketika data dari outputStream harus digunakan. Dalam beberapa situasi ekstensi file hasil dapat diubah

### compare(String filePath, CompareOptions compareOptions) {#compare-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(String filePath, CompareOptions compareOptions)
```


Membandingkan file yang ditentukan dengan dokumen target dan menulis hasil perbandingan ke jalur file yang disediakan.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.lang.String | Path file dokumen hasil |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Opsi perbandingan yang akan digunakan untuk proses perbandingan |
|

**Returns:**
java.nio.file.Path - path file hasil, dalam beberapa situasi ekstensi dapat diubah

### compare(Path filePath, CompareOptions compareOptions) {#compare-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(Path filePath, CompareOptions compareOptions)
```


Membandingkan file yang ditentukan dengan dokumen target dan menulis hasil perbandingan ke jalur file yang disediakan.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Path file dokumen hasil |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Opsi perbandingan yang akan digunakan untuk proses perbandingan |
|

**Returns:**
java.nio.file.Path - path file hasil, dalam beberapa situasi ekstensi dapat diubah

### compare(OutputStream stream, CompareOptions compareOptions) {#compare-java.io.OutputStream-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(OutputStream stream, CompareOptions compareOptions)
```


Membandingkan file yang ditentukan dengan dokumen target dan menulis hasil perbandingan ke aliran output.


Catatan: Jika nilai kembali null, gunakan data yang ditulis ke outputStream.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | aliran | java.io.OutputStream | Aliran dokumen hasil |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Opsi perbandingan yang akan digunakan untuk proses perbandingan |
|

**Returns:**
java.nio.file.Path - path file hasil atau null ketika data dari outputStream harus digunakan. Dalam beberapa situasi ekstensi file hasil dapat diubah

### compare(SaveOptions saveOptions, CompareOptions compareOptions) {#compare-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(SaveOptions saveOptions, CompareOptions compareOptions)
```


Membandingkan file yang ditentukan dengan dokumen target tanpa menyimpan hasil.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparison options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Opsi penyimpanan |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Opsi perbandingan yang akan digunakan untuk proses perbandingan |
|

**Returns:**
java.nio.file.Path - path dokumen hasil atau null

### compare(String filePath, SaveOptions saveOptions) {#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-}
```
public final Path compare(String filePath, SaveOptions saveOptions)
```


Membandingkan file yang ditentukan dengan dokumen target dan menulis hasil perbandingan ke jalur file yang disediakan.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.lang.String | Path file dokumen hasil |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Opsi penyimpanan |
|

**Returns:**
java.nio.file.Path - path file hasil, dalam beberapa situasi ekstensi dapat diubah

### compare(Path filePath, SaveOptions saveOptions) {#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-}
```
public final Path compare(Path filePath, SaveOptions saveOptions)
```


Membandingkan file yang ditentukan dengan dokumen target dan menulis hasil perbandingan ke jalur file yang disediakan.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Path file dokumen hasil |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Opsi penyimpanan |
|

**Returns:**
java.nio.file.Path - path file hasil, dalam beberapa situasi ekstensi dapat diubah

### compare(OutputStream stream, SaveOptions saveOptions) {#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-}
```
public final Path compare(OutputStream stream, SaveOptions saveOptions)
```


Membandingkan file yang ditentukan dengan dokumen target dan menulis hasil perbandingan ke jalur file yang disediakan.


Catatan: Jika nilai kembali null, gunakan data yang telah ditulis ke outputStream

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | aliran | java.io.OutputStream | Aliran dokumen hasil |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Opsi penyimpanan |
|

**Returns:**
java.nio.file.Path - path file hasil atau null ketika data dari outputStream harus digunakan. Dalam beberapa situasi ekstensi file hasil dapat diubah

### compare(CompareOptions compareOptions) {#compare-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(CompareOptions compareOptions)
```


Membandingkan file yang ditentukan dengan dokumen target tanpa menyimpan hasil.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Opsi perbandingan yang akan digunakan untuk proses perbandingan |
|

**Returns:**
java.nio.file.Path - jalur ke file hasil atau null

### compare(OutputStream outputStream, SaveOptions saveOptions, CompareOptions compareOptions) {#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(OutputStream outputStream, SaveOptions saveOptions, CompareOptions compareOptions)
```


Membandingkan file yang ditentukan dengan dokumen target dan menulis hasil perbandingan ke aliran output yang disediakan.


Catatan: Jika nilai kembali null, gunakan data yang telah ditulis ke outputStream

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | outputStream | java.io.OutputStream | Aliran dokumen hasil |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Opsi penyimpanan yang akan digunakan untuk menyimpan dokumen hasil |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Opsi perbandingan yang akan digunakan untuk proses perbandingan |
|

**Returns:**
java.nio.file.Path - path file hasil atau null ketika data dari outputStream harus digunakan. Dalam beberapa situasi ekstensi file hasil dapat diubah

### compare(String filePath, SaveOptions saveOptions, CompareOptions compareOptions) {#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(String filePath, SaveOptions saveOptions, CompareOptions compareOptions)
```


Membandingkan file yang ditentukan dengan dokumen target dan menulis hasil perbandingan ke jalur file yang disediakan.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparison options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.lang.String | Path file dokumen hasil |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Opsi penyimpanan yang akan digunakan untuk menyimpan dokumen hasil |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Opsi perbandingan yang akan digunakan untuk proses perbandingan |
|

**Returns:**
java.nio.file.Path - path file hasil, dalam beberapa situasi ekstensi dapat diubah

### compareDirectory(String filePath, CompareOptions compareOptions) {#compareDirectory-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public void compareDirectory(String filePath, CompareOptions compareOptions)
```


Membandingkan direktori yang ditentukan dengan direktori target dan menyimpan hasil perbandingan ke jalur file yang disediakan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.lang.String | Jalur file tempat hasil perbandingan akan disimpan. |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Opsi yang akan digunakan untuk proses perbandingan direktori. |
|

### compareDirectory(Path filePath, CompareOptions compareOptions) {#compareDirectory-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public void compareDirectory(Path filePath, CompareOptions compareOptions)
```


Membandingkan direktori yang ditentukan dengan direktori target dan menyimpan hasil perbandingan ke jalur file yang disediakan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Jalur file tempat hasil perbandingan akan disimpan. |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Opsi yang akan digunakan untuk proses perbandingan direktori. |
|

### compare(Path filePath, SaveOptions saveOptions, CompareOptions compareOptions) {#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(Path filePath, SaveOptions saveOptions, CompareOptions compareOptions)
```


Membandingkan file yang ditentukan dengan dokumen target dan menulis hasil perbandingan ke jalur file yang disediakan.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Path file dokumen hasil |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Opsi penyimpanan yang akan digunakan untuk menyimpan dokumen hasil |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Opsi perbandingan yang akan digunakan untuk proses perbandingan |
|

**Returns:**
java.nio.file.Path - path file hasil, dalam beberapa situasi ekstensi dapat diubah

### add(String filePath) {#add-java.lang.String-}
```
public final void add(String filePath)
```


Menambahkan dokumen target yang ditentukan ke proses perbandingan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.lang.String | Jalur ke dokumen target yang akan ditambahkan |
|

### add(String filePath, CompareOptions compareOptions) {#add-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public void add(String filePath, CompareOptions compareOptions)
```


Menambahkan dokumen atau folder target yang ditentukan ke proses perbandingan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.lang.String | Jalur ke dokumen atau folder target yang akan ditambahkan |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Opsi untuk perbandingan |
|

### add(Path filePath) {#add-java.nio.file.Path-}
```
public final void add(Path filePath)
```


Menambahkan dokumen target yang ditentukan ke proses perbandingan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Jalur ke dokumen target yang akan ditambahkan |
|

### add(String[] filePaths) {#add-java.lang.String...-}
```
public final void add(String[] filePaths)
```


Menambahkan dokumen target yang ditentukan ke proses perbandingan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePaths | java.lang.String[] | Jalur ke dokumen-dokumen target yang akan ditambahkan |
|

### add(Path[] filePaths) {#add-java.nio.file.Path...-}
```
public final void add(Path[] filePaths)
```


Menambahkan dokumen target yang ditentukan ke proses perbandingan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePaths | java.nio.file.Path[] | Jalur ke dokumen-dokumen target yang akan ditambahkan |
|

### add(String filePath, LoadOptions loadOptions) {#add-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-}
```
public final void add(String filePath, LoadOptions loadOptions)
```


Menambahkan dokumen target yang ditentukan ke proses perbandingan dengan opsi pemuatan yang ditentukan.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.lang.String | Jalur ke dokumen target yang akan ditambahkan |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Opsi muat khusus yang akan diterapkan pada dokumen |
|

### add(Path filePath, LoadOptions loadOptions) {#add-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-}
```
public final void add(Path filePath, LoadOptions loadOptions)
```


Menambahkan dokumen target yang ditentukan ke proses perbandingan dengan opsi pemuatan yang ditentukan.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Jalur ke dokumen target yang akan ditambahkan |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Opsi muat khusus yang akan diterapkan pada dokumen |
|

### add(Path filePath, CompareOptions compareOptions) {#add-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public final void add(Path filePath, CompareOptions compareOptions)
```


Menambahkan dokumen target yang ditentukan ke proses perbandingan dengan opsi pemuatan yang ditentukan.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Jalur ke dokumen atau folder target yang akan ditambahkan |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Opsi untuk perbandingan |
|

### add(InputStream document) {#add-java.io.InputStream-}
```
public final void add(InputStream document)
```


Menambahkan dokumen target yang ditentukan ke proses perbandingan.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | dokumen | java.io.InputStream | Aliran dengan data dokumen yang akan dibandingkan |
|

### add(InputStream[] documents) {#add-java.io.InputStream...-}
```
public final void add(InputStream[] documents)
```


Menambahkan dokumen target yang ditentukan ke proses perbandingan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | dokumen | java.io.InputStream[] | Aliran dengan data dokumen yang akan dibandingkan |
|

### add(InputStream document, LoadOptions loadOptions) {#add-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-}
```
public final void add(InputStream document, LoadOptions loadOptions)
```


Menambahkan dokumen target yang ditentukan ke proses perbandingan dengan opsi pemuatan yang ditentukan.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | dokumen | java.io.InputStream | Aliran dengan data dokumen yang akan dibandingkan |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Opsi muat khusus yang akan diterapkan pada dokumen |
|

### getChanges() {#getChanges--}
```
public final ChangeInfo[] getChanges()
```


Mengambil array objek [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) yang mewakili perubahan yang terdeteksi selama proses perbandingan.


Gunakan metode ini untuk mendapatkan informasi terperinci tentang perubahan antara dokumen sumber dan dokumen target.
Setiap objek [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) berisi informasi seperti jenis perubahan, area yang terpengaruh,
dan konten sebelum serta sesudah perubahan.

* More about how to obtain collection of detected differences between compared documents in Java: [How to get list of changes between documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Get+list+of+changes)
* More about how to get changes coordinates at pages image preview when comparing documents using GroupDocs.Comparison for Java: [How to get changes coordinates programmatically](../https://docs.groupdocs.com/display/comparisonjava/Get+changes+coordinates)


**Returns:**
com.groupdocs.comparison.result.ChangeInfo[] - sebuah array dari objek [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) yang mewakili perubahan yang terdeteksi selama proses perbandingan

### getChanges(GetChangeOptions getChangeOptions) {#getChanges-com.groupdocs.comparison.options.GetChangeOptions-}
```
public final ChangeInfo[] getChanges(GetChangeOptions getChangeOptions)
```


Mengambil array objek [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) yang mewakili perubahan yang terdeteksi selama proses perbandingan.


Gunakan metode ini untuk mendapatkan informasi terperinci tentang perubahan antara dokumen sumber dan dokumen target.
Setiap objek [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) berisi informasi seperti jenis perubahan, area yang terpengaruh,
dan konten sebelum serta sesudah perubahan.


Parameter [GetChangeOptions](../../com.groupdocs.comparison.options/getchangeoptions) memungkinkan untuk memfilter perubahan dengan cara yang berbeda.

* More about how to obtain collection of detected differences between compared documents in Java: [How to get list of changes between documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Get+list+of+changes)
* More about how to get changes coordinates at pages image preview when comparing documents using GroupDocs.Comparison for Java: [How to get changes coordinates programmatically](../https://docs.groupdocs.com/display/comparisonjava/Get+changes+coordinates)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | getChangeOptions | [GetChangeOptions](../../com.groupdocs.comparison.options/getchangeoptions) | Objek yang memungkinkan memfilter perubahan |
|

**Returns:**
com.groupdocs.comparison.result.ChangeInfo[] - sebuah array dari objek [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) yang mewakili perubahan yang terdeteksi selama proses perbandingan

### applyChanges(String filePath, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.lang.String-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(String filePath, ApplyChangeOptions applyChangeOptions)
```


Menerima atau menolak perubahan dan menerapkannya ke dokumen hasil.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.lang.String | Path file dokumen hasil |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | Opsi penerapan perubahan khusus untuk mengonfigurasi proses penerapan perubahan |
|

### applyChanges(Path filePath, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(Path filePath, ApplyChangeOptions applyChangeOptions)
```


Menerima atau menolak perubahan dan menerapkannya ke dokumen yang dihasilkan.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Path file dokumen hasil |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | Opsi penerapan perubahan khusus untuk mengonfigurasi proses penerapan perubahan |
|

### applyChanges(OutputStream document, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(OutputStream document, ApplyChangeOptions applyChangeOptions)
```


Menerima atau menolak perubahan dan menerapkannya ke dokumen yang dihasilkan.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | dokumen | java.io.OutputStream | Aliran output dokumen hasil |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | Opsi penerapan perubahan khusus untuk mengonfigurasi proses penerapan perubahan |
|

### applyChanges(String filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(String filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)
```


Menerima atau menolak perubahan dan menerapkannya ke dokumen yang dihasilkan.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.lang.String | Path file dokumen hasil |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Opsi penyimpanan untuk mengonfigurasi penyimpanan dokumen hasil |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | Opsi penerapan perubahan khusus untuk mengonfigurasi proses penerapan perubahan |
|

### applyChanges(Path filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(Path filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)
```


Menerima atau menolak perubahan dan menerapkannya ke dokumen yang dihasilkan.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Path file dokumen hasil |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Opsi penyimpanan untuk mengonfigurasi penyimpanan dokumen hasil |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | Opsi penerapan perubahan khusus untuk mengonfigurasi proses penerapan perubahan |
|

### applyChanges(OutputStream document, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(OutputStream document, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)
```


Menerima atau menolak perubahan dan menerapkannya ke dokumen yang dihasilkan.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | dokumen | java.io.OutputStream | Aliran output dokumen hasil |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Opsi penyimpanan untuk mengonfigurasi penyimpanan dokumen hasil |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | Opsi penerapan perubahan khusus untuk mengonfigurasi proses penerapan perubahan |
|

### getResultString() {#getResultString--}
```
public String getResultString()
```


Mendapatkan string hasil setelah perbandingan (Hanya untuk Perbandingan Teks).


**Returns:**
java.lang.String - string hasil

### getSourceFolder() {#getSourceFolder--}
```
public String getSourceFolder()
```


Mengembalikan folder sumber yang sedang dibandingkan.


**Returns:**
java.lang.String - folder sumber

### getTargetFolder() {#getTargetFolder--}
```
public String getTargetFolder()
```


Mengembalikan folder target yang sedang dibandingkan.


**Returns:**
java.lang.String - folder target

### selfComparisonCheck(Document source, Document target) {#selfComparisonCheck-com.groupdocs.comparison.Document-com.groupdocs.comparison.Document-}
```
public static void selfComparisonCheck(Document source, Document target)
```


Pemeriksaan perbandingan diri (e498c23). C# 7a7668c internal; tetap publik sehingga tes core.common dapat memanggil.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| source | [Document](../../com.groupdocs.comparison/document) |  |
| target | [Document](../../com.groupdocs.comparison/document) |  |

### close() {#close--}
```
public void close()
```


Melepaskan sumber daya.


