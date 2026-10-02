---
title: "WordCompareOptions"
second_title: "Referensi API GroupDocs.Comparison untuk .NET"
description: "Opsi perbandingan khusus dokumen Word. Mewarisi opsi umum dari CompareOptions./compareoptions."
type: docs
weight: 440
url: /id/net/groupdocs.comparison.options/wordcompareoptions/
---
## WordCompareOptions class

Opsi perbandingan khusus dokumen Word. Mewarisi opsi umum dari [`CompareOptions`](../compareoptions).

```csharp
public class WordCompareOptions : CompareOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [WordCompareOptions](wordcompareoptions)() | Menginisialisasi instance baru dari kelas [`WordCompareOptions`](../wordcompareoptions). |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [CalculateCoordinates](../../groupdocs.comparison.options/compareoptions/calculatecoordinates) { get; set; } | Menunjukkan apakah menghitung koordinat untuk komponen yang berubah. |
| [CalculateCoordinatesMode](../../groupdocs.comparison.options/compareoptions/calculatecoordinatesmode) { get; set; } | Menentukan perhitungan koordinat untuk mode komponen yang berubah. |
| [ChangedItemStyle](../../groupdocs.comparison.options/compareoptions/changeditemstyle) { get; set; } | Menjelaskan gaya untuk komponen yang berubah. |
| [CompareBookmarks](../../groupdocs.comparison.options/wordcompareoptions/comparebookmarks) { get; set; } | Mendapatkan atau mengatur apakah bookmark dalam dokumen sumber dan target dibandingkan dan perbedaan disertakan dalam hasil. |
| [CompareDocumentProperty](../../groupdocs.comparison.options/wordcompareoptions/comparedocumentproperty) { get; set; } | Mendapatkan atau mengatur apakah properti dokumen bawaan dan khusus dibandingkan dan perbedaan disertakan dalam hasil (misalnya pada halaman ringkasan properti). |
| [CompareVariableProperty](../../groupdocs.comparison.options/wordcompareoptions/comparevariableproperty) { get; set; } | Mendapatkan atau mengatur apakah properti variabel dokumen (misalnya bidang DOCVARIABLE) dibandingkan dan perbedaan disertakan dalam hasil. |
| [DeletedItemStyle](../../groupdocs.comparison.options/compareoptions/deleteditemstyle) { get; set; } | Menjelaskan gaya untuk komponen yang dihapus. |
| [DetalisationLevel](../../groupdocs.comparison.options/compareoptions/detalisationlevel) { get; set; } | Mendapatkan atau mengatur tingkat detail perbandingan. |
| [DetectStyleChanges](../../groupdocs.comparison.options/compareoptions/detectstylechanges) { get; set; } | Menunjukkan apakah mendeteksi perubahan gaya atau tidak. |
| [DiagramMasterSetting](../../groupdocs.comparison.options/compareoptions/diagrammastersetting) { get; set; } | Mendapatkan atau mengatur nilai jalur untuk master atau menggunakan perbandingan tanpa jalur master. Opsi ini hanya untuk Diagram. |
| [DirectoryCompare](../../groupdocs.comparison.options/compareoptions/directorycompare) { get; set; } | Kontrol untuk mengaktifkan perbandingan folder. |
| [DisplayMode](../../groupdocs.comparison.options/wordcompareoptions/displaymode) { get; set; } | Mendapatkan atau mengatur cara hasil perbandingan ditampilkan: sebagai revisi Word dalam mode Lacak Perubahan (Revisions) atau sebagai perubahan yang disorot yang langsung diterapkan ke dokumen (Highlight). |
| [ExtendedSummaryPage](../../groupdocs.comparison.options/compareoptions/extendedsummarypage) { get; set; } | Menunjukkan apakah menambahkan informasi perbandingan file yang diperluas ke halaman ringkasan atau tidak. |
| [FolderComparisonExtension](../../groupdocs.comparison.options/compareoptions/foldercomparisonextension) { get; set; } | Mendapatkan atau mengatur format file perbandingan folder yang dihasilkan. |
| [GenerateSummaryPage](../../groupdocs.comparison.options/compareoptions/generatesummarypage) { get; set; } | Menunjukkan apakah menambahkan halaman ringkasan dengan statistik perubahan yang terdeteksi ke dokumen hasil atau tidak. |
| [HeaderFootersComparison](../../groupdocs.comparison.options/compareoptions/headerfooterscomparison) { get; set; } | Kontrol untuk mengaktifkan perbandingan konten header/footer. |
| [IgnoreChangeSettings](../../groupdocs.comparison.options/compareoptions/ignorechangesettings) { get; set; } | Mendapatkan atau mengatur pengaturan untuk mengabaikan perubahan berdasarkan kemiripan. |
| [InsertedItemStyle](../../groupdocs.comparison.options/compareoptions/inserteditemstyle) { get; set; } | Menjelaskan gaya untuk komponen yang disisipkan. |
| [LeaveGaps](../../groupdocs.comparison.options/wordcompareoptions/leavegaps) { get; set; } | Mendapatkan atau mengatur apakah baris kosong dibiarkan menggantikan konten yang disisipkan atau dihapus untuk mempertahankan tata letak dan jumlah baris; digunakan dengan [`ShowInsertedContent`](../compareoptions/showinsertedcontent) dan [`ShowDeletedContent`](../compareoptions/showdeletedcontent). |
| [MarkChangedContent](../../groupdocs.comparison.options/compareoptions/markchangedcontent) { get; set; } | Menunjukkan apakah menggunakan bingkai untuk bentuk dalam Pengolahan Kata dan untuk persegi panjang dalam dokumen Gambar. |
| [MarkLineBreaks](../../groupdocs.comparison.options/wordcompareoptions/marklinebreaks) { get; set; } | Mendapatkan atau mengatur apakah jeda paragraf (baris) yang berbeda antar dokumen ditandai secara visual dalam hasil. |
| [MarkNestedContent](../../groupdocs.comparison.options/compareoptions/marknestedcontent) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah menandai anak elemen yang dihapus atau disisipkan sebagai dihapus atau disisipkan. |
| [OriginalSize](../../groupdocs.comparison.options/compareoptions/originalsize) { get; set; } | Mendapatkan atau mengatur ukuran asli dokumen yang dibandingkan. |
| [PaperSize](../../groupdocs.comparison.options/compareoptions/papersize) { get; set; } | Mendapatkan atau mengatur ukuran kertas dokumen hasil. |
| [PasswordSaveOption](../../groupdocs.comparison.options/compareoptions/passwordsaveoption) { get; set; } | Mendapatkan atau mengatur opsi penyimpanan kata sandi. |
| [RevisionAuthorName](../../groupdocs.comparison.options/wordcompareoptions/revisionauthorname) { get; set; } | Mendapatkan atau mengatur nama penulis yang digunakan untuk revisi ketika !:WordTrackChanges diaktifkan. Jika diatur, nama ini diterapkan pada penandaan revisi dalam dokumen hasil. |
| [SensitivityOfComparison](../../groupdocs.comparison.options/compareoptions/sensitivityofcomparison) { get; set; } | Mendapatkan atau mengatur sensitivitas perbandingan. |
| [SensitivityOfComparisonForTables](../../groupdocs.comparison.options/compareoptions/sensitivityofcomparisonfortables) { get; set; } | Mendapatkan atau mengatur sensitivitas perbandingan untuk tabel. |
| [ShowDeletedContent](../../groupdocs.comparison.options/compareoptions/showdeletedcontent) { get; set; } | Menunjukkan apakah menampilkan komponen yang dihapus dalam dokumen hasil atau tidak. |
| [ShowInsertedContent](../../groupdocs.comparison.options/compareoptions/showinsertedcontent) { get; set; } | Menunjukkan apakah menampilkan komponen yang disisipkan dalam dokumen hasil atau tidak. |
| [ShowOnlyChanged](../../groupdocs.comparison.options/compareoptions/showonlychanged) { get; set; } | Kontrol untuk mengaktifkan tampilan hanya item yang berubah. |
| [ShowOnlySummaryPage](../../groupdocs.comparison.options/compareoptions/showonlysummarypage) { get; set; } | Menunjukkan apakah meninggalkan dalam dokumen hasil hanya satu halaman dengan statistik perubahan yang terdeteksi dalam dokumen hasil atau tidak. |
| [ShowRevisions](../../groupdocs.comparison.options/wordcompareoptions/showrevisions) { get; set; } | Mendapatkan atau mengatur apakah dokumen hasil mempertahankan penanda revisi terlihat. Jika false, semua revisi diterima dan hasilnya muncul sebagai teks akhir. Pengaturan ini hanya berarti ketika [`DisplayMode`](./displaymode) disetel ke Highlight. Nilai default adalah true. |
| [UserMasterPath](../../groupdocs.comparison.options/compareoptions/usermasterpath) { get; set; } | Jalur ke templat master pengguna untuk Diagram. |
| [WordsSeparatorChars](../../groupdocs.comparison.options/compareoptions/wordsseparatorchars) { set; } | Mendapatkan atau mengatur array pemisah untuk memecah teks menjadi kata. |

### Lihat Juga

* class [CompareOptions](../compareoptions)
* namespace [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Comparison.dll -->
