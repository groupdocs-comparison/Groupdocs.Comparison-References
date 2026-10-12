---
title: "PdfCompareOptions"
second_title: "Referensi API GroupDocs.Comparison untuk .NET"
description: "Opsi perbandingan khusus dokumen PDF. Mewarisi opsi umum dari CompareOptions./compareoptions."
type: docs
weight: 360
url: /id/net/groupdocs.comparison.options/pdfcompareoptions/
---
## PdfCompareOptions class

Opsi perbandingan khusus dokumen PDF. Mewarisi opsi umum dari [`CompareOptions`](../compareoptions).

```csharp
public class PdfCompareOptions : CompareOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PdfCompareOptions](pdfcompareoptions)() | Menginisialisasi instance baru dari kelas [`PdfCompareOptions`](../pdfcompareoptions). |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AnnotationAuthorName](../../groupdocs.comparison.options/pdfcompareoptions/annotationauthorname) { get; set; } | Mendapatkan atau mengatur nama penulis yang digunakan untuk anotasi ketika [`DisplayMode`](./displaymode) diatur ke Interleaved. |
| [CalculateCoordinates](../../groupdocs.comparison.options/compareoptions/calculatecoordinates) { get; set; } | Menunjukkan apakah menghitung koordinat untuk komponen yang berubah. |
| [CalculateCoordinatesMode](../../groupdocs.comparison.options/compareoptions/calculatecoordinatesmode) { get; set; } | Menentukan perhitungan koordinat untuk mode komponen yang berubah. |
| [ChangedItemStyle](../../groupdocs.comparison.options/compareoptions/changeditemstyle) { get; set; } | Menjelaskan gaya untuk komponen yang berubah. |
| [CompareImagesPdf](../../groupdocs.comparison.options/pdfcompareoptions/compareimagespdf) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah akan membandingkan gambar dalam dokumen PDF. |
| [DeletedItemStyle](../../groupdocs.comparison.options/compareoptions/deleteditemstyle) { get; set; } | Menjelaskan gaya untuk komponen yang dihapus. |
| [DetalisationLevel](../../groupdocs.comparison.options/compareoptions/detalisationlevel) { get; set; } | Mendapatkan atau mengatur tingkat detail perbandingan. |
| [DetectStyleChanges](../../groupdocs.comparison.options/compareoptions/detectstylechanges) { get; set; } | Menunjukkan apakah mendeteksi perubahan gaya atau tidak. |
| [DiagramMasterSetting](../../groupdocs.comparison.options/compareoptions/diagrammastersetting) { get; set; } | Mendapatkan atau mengatur nilai jalur untuk master atau menggunakan perbandingan tanpa jalur master. Opsi ini hanya untuk Diagram. |
| [DirectoryCompare](../../groupdocs.comparison.options/compareoptions/directorycompare) { get; set; } | Kontrol untuk mengaktifkan perbandingan folder. |
| [DisplayMode](../../groupdocs.comparison.options/pdfcompareoptions/displaymode) { get; set; } | Mendapatkan atau mengatur cara tata letak dokumen hasil perbandingan. Nilai default adalah Inline. |
| [ExtendedSummaryPage](../../groupdocs.comparison.options/compareoptions/extendedsummarypage) { get; set; } | Menunjukkan apakah menambahkan informasi perbandingan file yang diperluas ke halaman ringkasan atau tidak. |
| [FolderComparisonExtension](../../groupdocs.comparison.options/compareoptions/foldercomparisonextension) { get; set; } | Mendapatkan atau mengatur format file perbandingan folder yang dihasilkan. |
| [GenerateSummaryPage](../../groupdocs.comparison.options/compareoptions/generatesummarypage) { get; set; } | Menunjukkan apakah menambahkan halaman ringkasan dengan statistik perubahan yang terdeteksi ke dokumen hasil atau tidak. |
| [HeaderFootersComparison](../../groupdocs.comparison.options/compareoptions/headerfooterscomparison) { get; set; } | Kontrol untuk mengaktifkan perbandingan konten header/footer. |
| [IgnoreChangeSettings](../../groupdocs.comparison.options/compareoptions/ignorechangesettings) { get; set; } | Mendapatkan atau mengatur pengaturan untuk mengabaikan perubahan berdasarkan kemiripan. |
| [ImagesInheritanceMode](../../groupdocs.comparison.options/pdfcompareoptions/imagesinheritancemode) { get; set; } | Menentukan sumber pewarisan gambar ketika perbandingan gambar dinonaktifkan. |
| [InsertedItemStyle](../../groupdocs.comparison.options/compareoptions/inserteditemstyle) { get; set; } | Menjelaskan gaya untuk komponen yang disisipkan. |
| [MarkChangedContent](../../groupdocs.comparison.options/compareoptions/markchangedcontent) { get; set; } | Menunjukkan apakah menggunakan bingkai untuk bentuk dalam Pengolahan Kata dan untuk persegi panjang dalam dokumen Gambar. |
| [MarkNestedContent](../../groupdocs.comparison.options/compareoptions/marknestedcontent) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah menandai anak elemen yang dihapus atau disisipkan sebagai dihapus atau disisipkan. |
| [OriginalSize](../../groupdocs.comparison.options/compareoptions/originalsize) { get; set; } | Mendapatkan atau mengatur ukuran asli dokumen yang dibandingkan. |
| [PagesSetup](../../groupdocs.comparison.options/pdfcompareoptions/pagessetup) { get; set; } | Mendapatkan atau mengatur rentang halaman yang akan dibandingkan. Jika null, semua halaman akan dibandingkan. |
| [PaperSize](../../groupdocs.comparison.options/compareoptions/papersize) { get; set; } | Mendapatkan atau mengatur ukuran kertas dokumen hasil. |
| [PasswordSaveOption](../../groupdocs.comparison.options/compareoptions/passwordsaveoption) { get; set; } | Mendapatkan atau mengatur opsi penyimpanan kata sandi. |
| [SensitivityOfComparison](../../groupdocs.comparison.options/compareoptions/sensitivityofcomparison) { get; set; } | Mendapatkan atau mengatur sensitivitas perbandingan. |
| [SensitivityOfComparisonForTables](../../groupdocs.comparison.options/compareoptions/sensitivityofcomparisonfortables) { get; set; } | Mendapatkan atau mengatur sensitivitas perbandingan untuk tabel. |
| [ShowDeletedContent](../../groupdocs.comparison.options/compareoptions/showdeletedcontent) { get; set; } | Menunjukkan apakah menampilkan komponen yang dihapus dalam dokumen hasil atau tidak. |
| [ShowInsertedContent](../../groupdocs.comparison.options/compareoptions/showinsertedcontent) { get; set; } | Menunjukkan apakah menampilkan komponen yang disisipkan dalam dokumen hasil atau tidak. |
| [ShowOnlyChanged](../../groupdocs.comparison.options/compareoptions/showonlychanged) { get; set; } | Kontrol untuk mengaktifkan tampilan hanya item yang berubah. |
| [ShowOnlySummaryPage](../../groupdocs.comparison.options/compareoptions/showonlysummarypage) { get; set; } | Menunjukkan apakah meninggalkan dalam dokumen hasil hanya satu halaman dengan statistik perubahan yang terdeteksi dalam dokumen hasil atau tidak. |
| [UserMasterPath](../../groupdocs.comparison.options/compareoptions/usermasterpath) { get; set; } | Jalur ke templat master pengguna untuk Diagram. |
| [WordsSeparatorChars](../../groupdocs.comparison.options/compareoptions/wordsseparatorchars) { set; } | Mendapatkan atau mengatur array pemisah untuk memecah teks menjadi kata. |

### Lihat Juga

* class [CompareOptions](../compareoptions)
* namespace [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Comparison.dll -->
