---
title: "CompareOptions"
second_title: "Referensi API GroupDocs.Comparison untuk Java"
description: "Memungkinkan konfigurasi proses perbandingan dokumen."
type: docs
weight: 11
url: /id/java/com.groupdocs.comparison.options/compareoptions/
---
**Inheritance:**
java.lang.Object
```
public class CompareOptions
```

Memungkinkan konfigurasi proses perbandingan dokumen.


Contoh penggunaan:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     final StyleSettings styleSettings = new StyleSettings();
     styleSettings.setHighlightColor(Color.RED);
     styleSettings.setFontColor(Color.GREEN);
     styleSettings.setUnderline(true);

     CompareOptions compareOptions = new CompareOptions();
     compareOptions.setInsertedItemStyle(styleSettings);

     comparer.compare(resultFile, compareOptions);
 }
 
````


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [CompareOptions()](#CompareOptions--) | Menginisialisasi instance baru dari kelas CompareOptions. |
|
|  | [CompareOptions(StyleSettings insertedItemStyle, StyleSettings deletedItemStyle, StyleSettings changedItemStyle)](#CompareOptions-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-) | Menginisialisasi instance baru dari kelas CompareOptions dengan pengaturan untuk gaya yang berbeda. |
|
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [ignoreChangeSettings](#ignoreChangeSettings) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getIgnoreChangeSettings()](#getIgnoreChangeSettings--) | Dapatkan pengaturan untuk mengabaikan perubahan berdasarkan kemiripan. |
|
|  | [setIgnoreChangeSettings(IgnoreChangeSensitivitySettings ignoreChangeSettings)](#setIgnoreChangeSettings-com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings-) | Mengatur pengaturan untuk mengabaikan perubahan berdasarkan kemiripan. |
|
|  | [getUserMasterPath()](#getUserMasterPath--) | Mendapatkan jalur ke templat master pengguna untuk Diagram. |
|
|  | [setUserMasterPath(String userMasterPath)](#setUserMasterPath-java.lang.String-) | Mengatur jalur ke templat master pengguna untuk Diagram. |
|
|  | [getComparisonType()](#getComparisonType--) | Mendapatkan tipe dokumen sumber dan target sebagai objek [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) sehingga Comparison dapat mengetahui cara membandingkannya. |
|
|  | [setComparisonType(ComparisonType comparisonType)](#setComparisonType-com.groupdocs.comparison.options.enums.ComparisonType-) | Mengatur tipe dokumen sumber dan target sebagai objek [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) sehingga Comparison dapat mengetahui cara membandingkannya. |
|
|  | [getPaperSize()](#getPaperSize--) | Mendapatkan ukuran kertas dalam dokumen hasil sebagai objek [PaperSize](../../com.groupdocs.comparison.options.enums/papersize). |
|
|  | [setPaperSize(PaperSize value)](#setPaperSize-com.groupdocs.comparison.options.enums.PaperSize-) | Mengatur ukuran kertas dalam dokumen hasil sebagai objek [PaperSize](../../com.groupdocs.comparison.options.enums/papersize). |
|
|  | [getCalculateCoordinatesMode()](#getCalculateCoordinatesMode--) | Mendapatkan mode perhitungan koordinat sebagai objek [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration). |
|
|  | [setCalculateCoordinatesMode(CalculateCoordinatesModeEnumeration calculateCoordinatesMode)](#setCalculateCoordinatesMode-com.groupdocs.comparison.options.enums.CalculateCoordinatesModeEnumeration-) | Mengatur mode perhitungan koordinat sebagai objek [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration). |
|
|  | [isShowDeletedContent()](#isShowDeletedContent--) | Mendapatkan flag yang menunjukkan apakah menampilkan komponen yang dihapus dalam dokumen hasil atau tidak. |
|
|  | [setShowDeletedContent(boolean value)](#setShowDeletedContent-boolean-) | Mengatur flag yang menunjukkan apakah menampilkan komponen yang dihapus dalam dokumen hasil atau tidak. |
|
|  | [isShowInsertedContent()](#isShowInsertedContent--) | Mendapatkan flag yang menunjukkan apakah menampilkan komponen yang disisipkan dalam dokumen hasil atau tidak. |
|
|  | [setShowInsertedContent(boolean value)](#setShowInsertedContent-boolean-) | Menetapkan flag yang menunjukkan apakah menampilkan komponen yang disisipkan dalam dokumen hasil atau tidak. |
|
|  | [isGenerateSummaryPage()](#isGenerateSummaryPage--) | Mendapatkan flag yang menunjukkan apakah menambahkan halaman ringkasan dengan statistik perubahan yang terdeteksi ke dokumen hasil atau tidak. |
|
|  | [setGenerateSummaryPage(boolean value)](#setGenerateSummaryPage-boolean-) | Menetapkan flag yang menunjukkan apakah menambahkan halaman ringkasan dengan statistik perubahan yang terdeteksi ke dokumen hasil atau tidak. |
|
|  | [isExtendedSummaryPage()](#isExtendedSummaryPage--) | Mendapatkan flag yang menunjukkan apakah menambahkan informasi perbandingan file yang diperluas ke halaman ringkasan atau tidak. |
|
|  | [setExtendedSummaryPage(boolean value)](#setExtendedSummaryPage-boolean-) | Menetapkan flag yang menunjukkan apakah menambahkan informasi perbandingan file yang diperluas ke halaman ringkasan atau tidak. |
|
|  | [isShowOnlySummaryPage()](#isShowOnlySummaryPage--) | Mendapatkan flag yang menunjukkan apakah hanya meninggalkan satu halaman dengan statistik perubahan yang terdeteksi dalam dokumen hasil atau tidak. |
|
|  | [setShowOnlySummaryPage(boolean value)](#setShowOnlySummaryPage-boolean-) | Menetapkan flag yang menunjukkan apakah hanya meninggalkan satu halaman dengan statistik perubahan yang terdeteksi dalam dokumen hasil atau tidak. |
|
|  | [isDetectStyleChanges()](#isDetectStyleChanges--) | Mendapatkan flag yang menunjukkan apakah mendeteksi perubahan gaya atau tidak. |
|
|  | [setDetectStyleChanges(boolean value)](#setDetectStyleChanges-boolean-) | Menetapkan flag yang menunjukkan apakah mendeteksi perubahan gaya atau tidak. |
|
|  | [isMarkNestedContent()](#isMarkNestedContent--) | Mendapatkan flag yang menunjukkan apakah menandai anak-anak elemen yang dihapus atau disisipkan sebagai dihapus atau disisipkan. |
|
|  | [setMarkNestedContent(boolean value)](#setMarkNestedContent-boolean-) | Menetapkan flag yang menunjukkan apakah menandai anak-anak elemen yang dihapus atau disisipkan sebagai dihapus atau disisipkan. |
|
|  | [isCalculateCoordinates()](#isCalculateCoordinates--) | Mendapatkan flag yang menunjukkan apakah menghitung koordinat untuk komponen yang berubah. |
|
|  | [setCalculateCoordinates(boolean value)](#setCalculateCoordinates-boolean-) | Menetapkan flag yang menunjukkan apakah menghitung koordinat untuk komponen yang berubah. |
|
|  | [isHeaderFootersComparison()](#isHeaderFootersComparison--) | Mendapatkan flag yang menunjukkan apakah membandingkan konten header/footer. |
|
|  | [setHeaderFootersComparison(boolean value)](#setHeaderFootersComparison-boolean-) | Menetapkan flag yang menunjukkan apakah membandingkan konten header/footer. |
|
|  | [getDetalisationLevel()](#getDetalisationLevel--) | Mendapatkan tingkat detail perbandingan yang direpresentasikan sebagai [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel). |
|
|  | [setDetalisationLevel(DetalisationLevel value)](#setDetalisationLevel-com.groupdocs.comparison.options.style.DetalisationLevel-) | Menetapkan tingkat detail perbandingan yang direpresentasikan sebagai [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel). |
|
|  | [isMarkChangedContent()](#isMarkChangedContent--) | Mendapatkan flag yang menunjukkan apakah bingkai untuk bentuk dalam Word Processing dan untuk persegi panjang dalam dokumen Image akan digunakan. |
|
|  | [setMarkChangedContent(boolean value)](#setMarkChangedContent-boolean-) | Menetapkan flag yang menunjukkan apakah bingkai untuk bentuk dalam Word Processing dan untuk persegi panjang dalam dokumen Image akan digunakan. |
|
|  | [getInsertedItemStyle()](#getInsertedItemStyle--) | Mendapatkan pengaturan gaya yang akan diterapkan pada item yang disisipkan. |
|
|  | [setInsertedItemStyle(StyleSettings value)](#setInsertedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-) | Menetapkan pengaturan gaya yang akan diterapkan pada item yang disisipkan. |
|
|  | [getDeletedItemStyle()](#getDeletedItemStyle--) | Mendapatkan pengaturan gaya yang akan diterapkan pada item yang dihapus. |
|
|  | [setDeletedItemStyle(StyleSettings value)](#setDeletedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-) | Menetapkan pengaturan gaya yang akan diterapkan pada item yang dihapus. |
|
|  | [getChangedItemStyle()](#getChangedItemStyle--) | Mendapatkan pengaturan gaya yang akan diterapkan pada item yang berubah. |
|
|  | [setChangedItemStyle(StyleSettings value)](#setChangedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-) | Mengatur pengaturan gaya yang akan diterapkan pada item yang berubah. |
|
|  | [getSensitivityOfComparison()](#getSensitivityOfComparison--) | Mendapatkan sensitivitas perbandingan. |
|
|  | [setSensitivityOfComparison(int value)](#setSensitivityOfComparison-int-) | Mengatur sensitivitas perbandingan. |
|
|  | [setSensitivityOfComparisonForTables(Integer value)](#setSensitivityOfComparisonForTables-java.lang.Integer-) | Mengatur sensitivitas perbandingan untuk tabel. |
|
|  | [getSensitivityOfComparisonForTables()](#getSensitivityOfComparisonForTables--) | Mendapatkan sensitivitas perbandingan untuk tabel. |
|
|  | [setWordsSeparatorChars(char[] value)](#setWordsSeparatorChars-char---) | Mengatur array pemisah yang akan digunakan untuk memisahkan teks menjadi kata. |
|
|  | [getPasswordSaveOption()](#getPasswordSaveOption--) | Mendapatkan opsi penyimpanan kata sandi yang diwakili oleh objek [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption). |
|
|  | [setPasswordSaveOption(PasswordSaveOption value)](#setPasswordSaveOption-com.groupdocs.comparison.options.enums.PasswordSaveOption-) | Mengatur opsi penyimpanan kata sandi yang diwakili oleh objek [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption). |
|
|  | [getOriginalSize()](#getOriginalSize--) | Mendapatkan ukuran asli dokumen yang dibandingkan yang diwakili oleh objek [OriginalSize](../../com.groupdocs.comparison.options/originalsize). |
|
|  | [setOriginalSize(OriginalSize value)](#setOriginalSize-com.groupdocs.comparison.options.OriginalSize-) | Mengatur ukuran asli dokumen yang dibandingkan yang diwakili oleh objek [OriginalSize](../../com.groupdocs.comparison.options/originalsize). |
|
|  | [getDiagramMasterSetting()](#getDiagramMasterSetting--) | Mendapatkan pengaturan halaman master untuk dokumen Diagram yang diwakili oleh objek [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting). |
|
|  | [setDiagramMasterSetting(DiagramMasterSetting value)](#setDiagramMasterSetting-com.groupdocs.comparison.options.style.DiagramMasterSetting-) | Mengatur pengaturan halaman master untuk dokumen Diagram yang diwakili oleh objek [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting). |
|
|  | [isDirectoryCompare()](#isDirectoryCompare--) | Mengembalikan flag yang menunjukkan apakah perbandingan direktori diaktifkan. |
|
|  | [setDirectoryCompare(boolean directoryCompare)](#setDirectoryCompare-boolean-) | Mengatur flag yang menunjukkan apakah perbandingan direktori harus diaktifkan. |
|
|  | [isShowOnlyChanged()](#isShowOnlyChanged--) | Mengembalikan nilai boolean yang menunjukkan apakah hanya item yang berubah yang harus ditampilkan. |
|
|  | [setShowOnlyChanged(boolean showOnlyChanged)](#setShowOnlyChanged-boolean-) | Mengatur nilai yang menunjukkan apakah hanya item yang berubah yang harus ditampilkan. |
|
|  | [getFolderComparisonExtension()](#getFolderComparisonExtension--) | Mendapatkan format file perbandingan folder yang dihasilkan. |
|
|  | [setFolderComparisonExtension(FolderComparisonExtension folderComparisonExtension)](#setFolderComparisonExtension-com.groupdocs.comparison.options.enums.FolderComparisonExtension-) | Mengatur format file perbandingan folder yang dihasilkan. |
|
### CompareOptions() {#CompareOptions--}
```
public CompareOptions()
```


Menginisialisasi instance baru dari kelas CompareOptions.


### CompareOptions(StyleSettings insertedItemStyle, StyleSettings deletedItemStyle, StyleSettings changedItemStyle) {#CompareOptions-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-}
```
public CompareOptions(StyleSettings insertedItemStyle, StyleSettings deletedItemStyle, StyleSettings changedItemStyle)
```


Menginisialisasi instance baru dari kelas CompareOptions dengan pengaturan untuk gaya yang berbeda.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | insertedItemStyle | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Pengaturan gaya untuk item yang disisipkan |
|
|  | deletedItemStyle | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Pengaturan gaya untuk item yang dihapus |
|
|  | changedItemStyle | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Pengaturan gaya untuk item gaya yang berubah |
|

### ignoreChangeSettings {#ignoreChangeSettings}
```
public IgnoreChangeSensitivitySettings ignoreChangeSettings
```


### getIgnoreChangeSettings() {#getIgnoreChangeSettings--}
```
public IgnoreChangeSensitivitySettings getIgnoreChangeSettings()
```


Dapatkan pengaturan untuk mengabaikan perubahan berdasarkan kemiripan.


**Returns:**
com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings - Pengaturan untuk mengabaikan perubahan.

### setIgnoreChangeSettings(IgnoreChangeSensitivitySettings ignoreChangeSettings) {#setIgnoreChangeSettings-com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings-}
```
public void setIgnoreChangeSettings(IgnoreChangeSensitivitySettings ignoreChangeSettings)
```


Mengatur pengaturan untuk mengabaikan perubahan berdasarkan kemiripan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | ignoreChangeSettings | com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings | Pengaturan untuk mengabaikan perubahan. |
|

### getUserMasterPath() {#getUserMasterPath--}
```
public String getUserMasterPath()
```


Mendapatkan jalur ke templat master pengguna untuk Diagram.


**Returns:**
java.lang.String - Jalur ke templat master pengguna untuk Diagram.

### setUserMasterPath(String userMasterPath) {#setUserMasterPath-java.lang.String-}
```
public void setUserMasterPath(String userMasterPath)
```


Mengatur jalur ke templat master pengguna untuk Diagram.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | userMasterPath | java.lang.String | Jalur ke templat master pengguna untuk Diagram. |
|

### getComparisonType() {#getComparisonType--}
```
public ComparisonType getComparisonType()
```


Mendapatkan tipe dokumen sumber dan target sebagai objek [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) sehingga Comparison dapat mengetahui cara membandingkannya.
Ketika opsi ini diatur, opsi [LoadOptions.getFileType()](../../com.groupdocs.comparison.options.load/loadoptions#getFileType--) akan diabaikan.


**Returns:**
[ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) - the type of source and target documents

### setComparisonType(ComparisonType comparisonType) {#setComparisonType-com.groupdocs.comparison.options.enums.ComparisonType-}
```
public void setComparisonType(ComparisonType comparisonType)
```


Mengatur tipe dokumen sumber dan target sebagai objek [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) sehingga Comparison dapat mengetahui cara membandingkannya.
Ketika opsi ini diatur, opsi [LoadOptions.setFileType(FileType)](../../com.groupdocs.comparison.options.load/loadoptions#setFileType-FileType-) akan diabaikan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | comparisonType | [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) | Jenis dokumen sumber dan target |
|

### getPaperSize() {#getPaperSize--}
```
public final PaperSize getPaperSize()
```


Mendapatkan ukuran kertas dalam dokumen hasil sebagai objek [PaperSize](../../com.groupdocs.comparison.options.enums/papersize).


**Returns:**
[PaperSize](../../com.groupdocs.comparison.options.enums/papersize) - the size of a paper in result document

### setPaperSize(PaperSize value) {#setPaperSize-com.groupdocs.comparison.options.enums.PaperSize-}
```
public final void setPaperSize(PaperSize value)
```


Mengatur ukuran kertas dalam dokumen hasil sebagai objek [PaperSize](../../com.groupdocs.comparison.options.enums/papersize).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [PaperSize](../../com.groupdocs.comparison.options.enums/papersize) | Ukuran kertas dalam dokumen hasil |
|

### getCalculateCoordinatesMode() {#getCalculateCoordinatesMode--}
```
public CalculateCoordinatesModeEnumeration getCalculateCoordinatesMode()
```


Mendapatkan mode perhitungan koordinat sebagai objek [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration).


**Returns:**
[CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) - the calculate coordinates mode

### setCalculateCoordinatesMode(CalculateCoordinatesModeEnumeration calculateCoordinatesMode) {#setCalculateCoordinatesMode-com.groupdocs.comparison.options.enums.CalculateCoordinatesModeEnumeration-}
```
public void setCalculateCoordinatesMode(CalculateCoordinatesModeEnumeration calculateCoordinatesMode)
```


Mengatur mode perhitungan koordinat sebagai objek [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | calculateCoordinatesMode | [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) | Mode menghitung koordinat |
|

### isShowDeletedContent() {#isShowDeletedContent--}
```
public final boolean isShowDeletedContent()
```


Mendapatkan flag yang menunjukkan apakah menampilkan komponen yang dihapus dalam dokumen hasil atau tidak.


**Returns:**
boolean - true jika komponen yang dihapus dalam dokumen hasil akan ditampilkan, sebaliknya false

### setShowDeletedContent(boolean value) {#setShowDeletedContent-boolean-}
```
public final void setShowDeletedContent(boolean value)
```


Mengatur flag yang menunjukkan apakah menampilkan komponen yang dihapus dalam dokumen hasil atau tidak.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | boolean | true jika komponen yang dihapus dalam dokumen hasil harus ditampilkan, sebaliknya false |
|

### isShowInsertedContent() {#isShowInsertedContent--}
```
public final boolean isShowInsertedContent()
```


Mendapatkan flag yang menunjukkan apakah menampilkan komponen yang disisipkan dalam dokumen hasil atau tidak.


**Returns:**
boolean - true jika komponen yang disisipkan dalam dokumen hasil harus ditampilkan, sebaliknya false

### setShowInsertedContent(boolean value) {#setShowInsertedContent-boolean-}
```
public final void setShowInsertedContent(boolean value)
```


Menetapkan flag yang menunjukkan apakah menampilkan komponen yang disisipkan dalam dokumen hasil atau tidak.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | boolean | true jika komponen yang disisipkan dalam dokumen hasil harus ditampilkan, sebaliknya false |
|

### isGenerateSummaryPage() {#isGenerateSummaryPage--}
```
public final boolean isGenerateSummaryPage()
```


Mendapatkan flag yang menunjukkan apakah menambahkan halaman ringkasan dengan statistik perubahan yang terdeteksi ke dokumen hasil atau tidak.


**Returns:**
boolean - true jika halaman ringkasan akan ditambahkan, sebaliknya false

### setGenerateSummaryPage(boolean value) {#setGenerateSummaryPage-boolean-}
```
public final void setGenerateSummaryPage(boolean value)
```


Menetapkan flag yang menunjukkan apakah menambahkan halaman ringkasan dengan statistik perubahan yang terdeteksi ke dokumen hasil atau tidak.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | boolean | true jika halaman ringkasan harus ditambahkan, sebaliknya false |
|

### isExtendedSummaryPage() {#isExtendedSummaryPage--}
```
public boolean isExtendedSummaryPage()
```


Mendapatkan flag yang menunjukkan apakah menambahkan informasi perbandingan file yang diperluas ke halaman ringkasan atau tidak.


**Returns:**
boolean - true jika informasi perbandingan file yang diperluas akan ditambahkan ke halaman ringkasan, sebaliknya false

### setExtendedSummaryPage(boolean value) {#setExtendedSummaryPage-boolean-}
```
public void setExtendedSummaryPage(boolean value)
```


Menetapkan flag yang menunjukkan apakah menambahkan informasi perbandingan file yang diperluas ke halaman ringkasan atau tidak.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | boolean | true jika informasi perbandingan file yang diperluas harus ditambahkan ke halaman ringkasan, sebaliknya false |
|

### isShowOnlySummaryPage() {#isShowOnlySummaryPage--}
```
public boolean isShowOnlySummaryPage()
```


Mendapatkan flag yang menunjukkan apakah hanya meninggalkan satu halaman dengan statistik perubahan yang terdeteksi dalam dokumen hasil atau tidak.


**Returns:**
boolean - true jika dalam dokumen hasil hanya satu halaman dengan statistik perubahan yang terdeteksi yang akan disisakan, sebaliknya false

### setShowOnlySummaryPage(boolean value) {#setShowOnlySummaryPage-boolean-}
```
public void setShowOnlySummaryPage(boolean value)
```


Menetapkan flag yang menunjukkan apakah hanya meninggalkan satu halaman dengan statistik perubahan yang terdeteksi dalam dokumen hasil atau tidak.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | boolean | true jika dalam dokumen hasil hanya satu halaman dengan statistik perubahan yang terdeteksi yang harus disisakan, sebaliknya false |
|

### isDetectStyleChanges() {#isDetectStyleChanges--}
```
public final boolean isDetectStyleChanges()
```


Mendapatkan flag yang menunjukkan apakah mendeteksi perubahan gaya atau tidak.


**Returns:**
boolean - true jika perubahan gaya akan terdeteksi, sebaliknya false

### setDetectStyleChanges(boolean value) {#setDetectStyleChanges-boolean-}
```
public final void setDetectStyleChanges(boolean value)
```


Menetapkan flag yang menunjukkan apakah mendeteksi perubahan gaya atau tidak.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | boolean | true jika perubahan gaya harus terdeteksi, sebaliknya false |
|

### isMarkNestedContent() {#isMarkNestedContent--}
```
public final boolean isMarkNestedContent()
```


Mendapatkan flag yang menunjukkan apakah menandai anak-anak elemen yang dihapus atau disisipkan sebagai dihapus atau disisipkan.


**Returns:**
boolean - true jika anak-anak elemen yang dihapus atau disisipkan akan ditandai sebagai dihapus atau disisipkan, sebaliknya false

### setMarkNestedContent(boolean value) {#setMarkNestedContent-boolean-}
```
public final void setMarkNestedContent(boolean value)
```


Menetapkan flag yang menunjukkan apakah menandai anak-anak elemen yang dihapus atau disisipkan sebagai dihapus atau disisipkan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | boolean | true jika anak-anak elemen yang dihapus atau disisipkan harus ditandai sebagai dihapus atau disisipkan, sebaliknya false |
|

### isCalculateCoordinates() {#isCalculateCoordinates--}
```
public final boolean isCalculateCoordinates()
```


Mendapatkan flag yang menunjukkan apakah menghitung koordinat untuk komponen yang berubah.


**Returns:**
boolean - true jika koordinat untuk komponen yang berubah akan dihitung, sebaliknya false

### setCalculateCoordinates(boolean value) {#setCalculateCoordinates-boolean-}
```
public final void setCalculateCoordinates(boolean value)
```


Menetapkan flag yang menunjukkan apakah menghitung koordinat untuk komponen yang berubah.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | boolean | true jika koordinat untuk komponen yang berubah harus dihitung, sebaliknya false |
|

### isHeaderFootersComparison() {#isHeaderFootersComparison--}
```
public final boolean isHeaderFootersComparison()
```


Mendapatkan flag yang menunjukkan apakah membandingkan konten header/footer.


**Returns:**
boolean - true jika konten header/footer akan dibandingkan, sebaliknya false

### setHeaderFootersComparison(boolean value) {#setHeaderFootersComparison-boolean-}
```
public final void setHeaderFootersComparison(boolean value)
```


Menetapkan flag yang menunjukkan apakah membandingkan konten header/footer.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | boolean | true jika konten header/footer harus dibandingkan, jika tidak false |
|

### getDetalisationLevel() {#getDetalisationLevel--}
```
public final DetalisationLevel getDetalisationLevel()
```


Mendapatkan tingkat detail perbandingan yang direpresentasikan sebagai [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel).
Nilai default adalah [DetalisationLevel.LOW](../../com.groupdocs.comparison.options.style/detalisationlevel#LOW).


**Returns:**
[DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) - the level of comparison detalization

### setDetalisationLevel(DetalisationLevel value) {#setDetalisationLevel-com.groupdocs.comparison.options.style.DetalisationLevel-}
```
public final void setDetalisationLevel(DetalisationLevel value)
```


Menetapkan tingkat detail perbandingan yang direpresentasikan sebagai [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel).
Nilai default adalah [DetalisationLevel.LOW](../../com.groupdocs.comparison.options.style/detalisationlevel#LOW)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) | Tingkat detail perbandingan |
|

### isMarkChangedContent() {#isMarkChangedContent--}
```
public final boolean isMarkChangedContent()
```


Mendapatkan flag yang menunjukkan apakah bingkai untuk bentuk dalam Word Processing dan untuk persegi panjang dalam dokumen Image akan digunakan.


**Returns:**
boolean - true jika frame akan digunakan, jika tidak false

### setMarkChangedContent(boolean value) {#setMarkChangedContent-boolean-}
```
public final void setMarkChangedContent(boolean value)
```


Menetapkan flag yang menunjukkan apakah bingkai untuk bentuk dalam Word Processing dan untuk persegi panjang dalam dokumen Image akan digunakan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | boolean | true jika frame harus digunakan, jika tidak false |
|

### getInsertedItemStyle() {#getInsertedItemStyle--}
```
public final StyleSettings getInsertedItemStyle()
```


Mendapatkan pengaturan gaya yang akan diterapkan pada item yang disisipkan.


**Returns:**
[StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) - style settings of inserted items

### setInsertedItemStyle(StyleSettings value) {#setInsertedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-}
```
public final void setInsertedItemStyle(StyleSettings value)
```


Menetapkan pengaturan gaya yang akan diterapkan pada item yang disisipkan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Pengaturan gaya untuk item yang disisipkan |
|

### getDeletedItemStyle() {#getDeletedItemStyle--}
```
public final StyleSettings getDeletedItemStyle()
```


Mendapatkan pengaturan gaya yang akan diterapkan pada item yang dihapus.


**Returns:**
[StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) - style settings of deleted items

### setDeletedItemStyle(StyleSettings value) {#setDeletedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-}
```
public final void setDeletedItemStyle(StyleSettings value)
```


Menetapkan pengaturan gaya yang akan diterapkan pada item yang dihapus.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Pengaturan gaya untuk item yang dihapus |
|

### getChangedItemStyle() {#getChangedItemStyle--}
```
public final StyleSettings getChangedItemStyle()
```


Mendapatkan pengaturan gaya yang akan diterapkan pada item yang berubah.


**Returns:**
[StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) - style settings of changed items

### setChangedItemStyle(StyleSettings value) {#setChangedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-}
```
public final void setChangedItemStyle(StyleSettings value)
```


Mengatur pengaturan gaya yang akan diterapkan pada item yang berubah.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Pengaturan gaya untuk item yang diubah |
|

### getSensitivityOfComparison() {#getSensitivityOfComparison--}
```
public final int getSensitivityOfComparison()
```


Mendapatkan sensitivitas perbandingan.
Persentase elemen yang dihapus dan disisipkan dari dua objek yang dibandingkan relatif terhadap semua elemen objek tersebut.

* If this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Returns:**
int - sensitivitas perbandingan

### setSensitivityOfComparison(int value) {#setSensitivityOfComparison-int-}
```
public final void setSensitivityOfComparison(int value)
```


Mengatur sensitivitas perbandingan.
Persentase elemen yang dihapus dan disisipkan dari dua objek yang dibandingkan relatif terhadap semua elemen objek tersebut.

* If this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | int | Sensitivitas perbandingan |
|

### setSensitivityOfComparisonForTables(Integer value) {#setSensitivityOfComparisonForTables-java.lang.Integer-}
```
public void setSensitivityOfComparisonForTables(Integer value)
```


Mengatur sensitivitas perbandingan untuk tabel.
Jika nilai null, SensitivityOfComparison digunakan sebagai gantinya. Persentase elemen yang dihapus dan disisipkan dari dua objek yang dibandingkan relatif terhadap semua elemen objek tersebut.

* if this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs, if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | java.lang.Integer | Sensitivitas perbandingan untuk tabel |
|

### getSensitivityOfComparisonForTables() {#getSensitivityOfComparisonForTables--}
```
public final Integer getSensitivityOfComparisonForTables()
```


Mendapatkan sensitivitas perbandingan untuk tabel.
Jika nilai null, SensitivityOfComparison digunakan sebagai gantinya. Persentase elemen yang dihapus dan disisipkan dari dua objek yang dibandingkan relatif terhadap semua elemen objek tersebut.

* if this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs, if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Returns:**
java.lang.Integer - Sensitivitas perbandingan untuk tabel

### setWordsSeparatorChars(char[] value) {#setWordsSeparatorChars-char---}
```
public final void setWordsSeparatorChars(char[] value)
```


Mengatur array pemisah yang akan digunakan untuk memisahkan teks menjadi kata.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | char[] | Array pemisah untuk memecah teks menjadi kata-kata |
|

### getPasswordSaveOption() {#getPasswordSaveOption--}
```
public final PasswordSaveOption getPasswordSaveOption()
```


Mendapatkan opsi penyimpanan kata sandi yang diwakili oleh objek [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption).


**Returns:**
[PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) - the password save option

### setPasswordSaveOption(PasswordSaveOption value) {#setPasswordSaveOption-com.groupdocs.comparison.options.enums.PasswordSaveOption-}
```
public final void setPasswordSaveOption(PasswordSaveOption value)
```


Mengatur opsi penyimpanan kata sandi yang diwakili oleh objek [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) | Opsi penyimpanan kata sandi |
|

### getOriginalSize() {#getOriginalSize--}
```
public final OriginalSize getOriginalSize()
```


Mendapatkan ukuran asli dokumen yang dibandingkan yang diwakili oleh objek [OriginalSize](../../com.groupdocs.comparison.options/originalsize).


**Returns:**
[OriginalSize](../../com.groupdocs.comparison.options/originalsize) - the original size of documents

### setOriginalSize(OriginalSize value) {#setOriginalSize-com.groupdocs.comparison.options.OriginalSize-}
```
public final void setOriginalSize(OriginalSize value)
```


Mengatur ukuran asli dokumen yang dibandingkan yang diwakili oleh objek [OriginalSize](../../com.groupdocs.comparison.options/originalsize).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [OriginalSize](../../com.groupdocs.comparison.options/originalsize) | Ukuran asli dokumen |
|

### getDiagramMasterSetting() {#getDiagramMasterSetting--}
```
public final DiagramMasterSetting getDiagramMasterSetting()
```


Mendapatkan pengaturan halaman master untuk dokumen Diagram yang diwakili oleh objek [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting).


**Returns:**
[DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) - the diagram master page setting

### setDiagramMasterSetting(DiagramMasterSetting value) {#setDiagramMasterSetting-com.groupdocs.comparison.options.style.DiagramMasterSetting-}
```
public final void setDiagramMasterSetting(DiagramMasterSetting value)
```


Mengatur pengaturan halaman master untuk dokumen Diagram yang diwakili oleh objek [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) | Pengaturan halaman master diagram |
|

### isDirectoryCompare() {#isDirectoryCompare--}
```
public boolean isDirectoryCompare()
```


Mengembalikan flag yang menunjukkan apakah perbandingan direktori diaktifkan.


**Returns:**
boolean - true jika perbandingan direktori diaktifkan, jika tidak false

### setDirectoryCompare(boolean directoryCompare) {#setDirectoryCompare-boolean-}
```
public void setDirectoryCompare(boolean directoryCompare)
```


Mengatur flag yang menunjukkan apakah perbandingan direktori harus diaktifkan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | directoryCompare | boolean | true jika perbandingan direktori harus diaktifkan, jika tidak false |
|

### isShowOnlyChanged() {#isShowOnlyChanged--}
```
public boolean isShowOnlyChanged()
```


Mengembalikan nilai boolean yang menunjukkan apakah hanya item yang berubah yang harus ditampilkan.


**Returns:**
boolean - true jika hanya item yang diubah yang harus ditampilkan, jika tidak false

### setShowOnlyChanged(boolean showOnlyChanged) {#setShowOnlyChanged-boolean-}
```
public void setShowOnlyChanged(boolean showOnlyChanged)
```


Mengatur nilai yang menunjukkan apakah hanya item yang berubah yang harus ditampilkan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | showOnlyChanged | boolean | nilai boolean yang menunjukkan apakah hanya item yang diubah yang harus ditampilkan |
|

### getFolderComparisonExtension() {#getFolderComparisonExtension--}
```
public FolderComparisonExtension getFolderComparisonExtension()
```


Mendapatkan format file perbandingan folder yang dihasilkan.


**Returns:**
com.groupdocs.comparison.options.enums.FolderComparisonExtension - FolderComparisonExtension yang mewakili format file perbandingan folder yang dihasilkan

### setFolderComparisonExtension(FolderComparisonExtension folderComparisonExtension) {#setFolderComparisonExtension-com.groupdocs.comparison.options.enums.FolderComparisonExtension-}
```
public void setFolderComparisonExtension(FolderComparisonExtension folderComparisonExtension)
```


Mengatur format file perbandingan folder yang dihasilkan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | folderComparisonExtension | com.groupdocs.comparison.options.enums.FolderComparisonExtension | FolderComparisonExtension yang mewakili format file perbandingan folder yang dihasilkan |
|

