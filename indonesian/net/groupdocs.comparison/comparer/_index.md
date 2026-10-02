---
title: "Pembanding"
second_title: "Referensi API GroupDocs.Comparison untuk .NET"
description: "Mewakili kelas utama yang mengontrol proses perbandingan dokumen."
type: docs
weight: 100
url: /id/net/groupdocs.comparison/comparer/
---
## Comparer class

Mewakili kelas utama yang mengontrol proses perbandingan dokumen.

```csharp
public sealed class Comparer : IDisposable
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Comparer](comparer#constructor)(Stream) | Menginisialisasi instance baru dari kelas [`Comparer`](../comparer) dengan aliran dokumen sumber. |
| [Comparer](comparer#constructor_4)(string) | Menginisialisasi instance baru dari kelas [`Comparer`](../comparer) dengan jalur berkas sumber. |
| [Comparer](comparer#constructor_1)(Stream, ComparerSettings) | Menginisialisasi instance baru dari kelas [`Comparer`](../comparer) dengan aliran dokumen sumber dan [`ComparerSettings`](../comparersettings). |
| [Comparer](comparer#constructor_2)(Stream, LoadOptions) | Menginisialisasi instance baru dari [`Comparer`](../comparer) dengan aliran dokumen sumber dan [`LoadOptions`](../../groupdocs.comparison.options/loadoptions). |
| [Comparer](comparer#constructor_6)(string, CompareOptions) | Menginisialisasi instance baru dari [`Comparer`](../comparer) dengan jalur folder sumber dan [`CompareOptions`](../../groupdocs.comparison.options/compareoptions). |
| [Comparer](comparer#constructor_5)(string, ComparerSettings) | Menginisialisasi instance baru dari kelas [`Comparer`](../comparer) dengan jalur berkas sumber dan [`ComparerSettings`](../comparersettings). |
| [Comparer](comparer#constructor_7)(string, LoadOptions) | Menginisialisasi instance baru dari [`Comparer`](../comparer) dengan jalur file sumber dan [`LoadOptions`](../../groupdocs.comparison.options/loadoptions). |
| [Comparer](comparer#constructor_3)(Stream, LoadOptions, ComparerSettings) | Menginisialisasi instance baru dari kelas [`Comparer`](../comparer) dengan aliran dokumen, [`LoadOptions`](../../groupdocs.comparison.options/loadoptions) dan [`ComparerSettings`](../comparersettings). |
| [Comparer](comparer#constructor_8)(string, LoadOptions, ComparerSettings) | Menginisialisasi instance baru dari kelas [`Comparer`](../comparer) dengan jalur file sumber, [`LoadOptions`](../../groupdocs.comparison.options/loadoptions) dan [`ComparerSettings`](../comparersettings). |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Result](../../groupdocs.comparison/comparer/result) { get; } | Dokumen hasil. |
| [Source](../../groupdocs.comparison/comparer/source) { get; } | File sumber yang sedang dibandingkan. |
| [SourceFolder](../../groupdocs.comparison/comparer/sourcefolder) { get; } | Folder sumber yang sedang dibandingkan. |
| [TargetFolder](../../groupdocs.comparison/comparer/targetfolder) { get; set; } | Folder target yang sedang dibandingkan. |
| [Targets](../../groupdocs.comparison/comparer/targets) { get; } | Daftar file target untuk dibandingkan dengan file sumber. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Add](../../groupdocs.comparison/comparer/add#add)(Stream) | Menambahkan aliran dokumen ke perbandingan. |
| [Add](../../groupdocs.comparison/comparer/add#add_2)(string) | Menambahkan file ke perbandingan. |
| [Add](../../groupdocs.comparison/comparer/add#add_1)(Stream, LoadOptions) | Menambahkan aliran dokumen ke perbandingan dengan opsi pemuatan yang ditentukan. |
| [Add](../../groupdocs.comparison/comparer/add#add_3)(string, CompareOptions) | Menambahkan folder ke perbandingan. |
| [Add](../../groupdocs.comparison/comparer/add#add_4)(string, LoadOptions) | Menambahkan file ke perbandingan dengan opsi pemuatan yang ditentukan. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges)(Stream, ApplyChangeOptions) | Menerima atau menolak perubahan dan menerapkannya ke dokumen hasil. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_2)(string, ApplyChangeOptions) | Menerima atau menolak perubahan dan menerapkannya ke dokumen hasil. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_1)(Stream, SaveOptions, ApplyChangeOptions) | Menerima atau menolak perubahan dan menerapkannya ke dokumen hasil. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_3)(string, SaveOptions, ApplyChangeOptions) | Menerima atau menolak perubahan dan menerapkannya ke dokumen hasil. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare)() | Membandingkan dokumen tanpa menyimpan hasil dengan opsi default |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_1)(CompareOptions) | Membandingkan dokumen tanpa menyimpan hasil. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_3)(Stream) | Membandingkan dokumen dan menyimpan hasil ke aliran file |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_7)(string) | Membandingkan dokumen dan menyimpan hasil ke jalur file |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_2)(SaveOptions, CompareOptions) | Membandingkan dokumen tanpa menyimpan hasil. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_4)(Stream, CompareOptions) | Membandingkan dokumen dan menyimpan hasil ke aliran file |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_5)(Stream, SaveOptions) | Membandingkan dokumen dan menyimpan hasil ke aliran file |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_8)(string, CompareOptions) | Membandingkan dokumen dan menyimpan hasil ke jalur file |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_9)(string, SaveOptions) | Membandingkan dokumen dan menyimpan hasil ke jalur file |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_6)(Stream, SaveOptions, CompareOptions) | Membandingkan dokumen dan menyimpan hasil ke aliran. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_10)(string, SaveOptions, CompareOptions) | Membandingkan dokumen dan menyimpan hasil ke jalur file |
| [CompareDirectory](../../groupdocs.comparison/comparer/comparedirectory)(string, CompareOptions) | Membandingkan direktori dan menyimpan hasil ke jalur file |
| [Dispose](../../groupdocs.comparison/comparer/dispose)() | Melepaskan sumber daya. |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges)() | Mendapatkan daftar perubahan antara file sumber dan target file(s). |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges_1)(ChangeType) | Mendapatkan daftar perubahan antara file sumber dan target file(s). |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges_2)(GetChangeOptions) | Mendapatkan daftar perubahan antara file sumber dan target file(s). |
| [GetResultDocumentStream](../../groupdocs.comparison/comparer/getresultdocumentstream)() | Mendapatkan aliran dokumen hasil, mengembalikan null jika aliran tidak ada |
| [GetResultString](../../groupdocs.comparison/comparer/getresultstring)() | Dapatkan string hasil setelah perbandingan (Hanya untuk Perbandingan Teks). |

### Lihat Juga

* namespace [GroupDocs.Comparison](../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Comparison.dll -->
