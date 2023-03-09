---
title: Comparer
second_title: GroupDocs.Comparison untuk Referensi .NET API
description: Mewakili kelas utama yang mengontrol proses perbandingan dokumen.
type: docs
weight: 100
url: /id/net/groupdocs.comparison/comparer/
---
## Comparer class

Mewakili kelas utama yang mengontrol proses perbandingan dokumen.

```csharp
public class Comparer : IDisposable
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [Comparer](comparer#constructor)(Stream) | Menginisialisasi instance baru[`Comparer`](../comparer) kelas dengan aliran dokumen sumber. |
| [Comparer](comparer#constructor_4)(string) | Menginisialisasi instance baru[`Comparer`](../comparer) kelas dengan jalur file sumber. |
| [Comparer](comparer#constructor_1)(Stream, ComparerSettings) | Menginisialisasi instance baru[`Comparer`](../comparer)kelas dengan aliran dokumen sumber dan[`ComparerSettings`](../comparersettings) . |
| [Comparer](comparer#constructor_2)(Stream, LoadOptions) | Menginisialisasi instance baru[`Comparer`](../comparer) dengan aliran dokumen sumber dan[`LoadOptions`](../../groupdocs.comparison.options/loadoptions) . |
| [Comparer](comparer#constructor_5)(string, ComparerSettings) | Menginisialisasi instance baru[`Comparer`](../comparer) kelas dengan jalur file sumber dan[`ComparerSettings`](../comparersettings) . |
| [Comparer](comparer#constructor_6)(string, LoadOptions) | Menginisialisasi instance baru[`Comparer`](../comparer) dengan path file sumber dan[`LoadOptions`](../../groupdocs.comparison.options/loadoptions) . |
| [Comparer](comparer#constructor_3)(Stream, LoadOptions, ComparerSettings) | Menginisialisasi instance baru[`Comparer`](../comparer) kelas dengan aliran dokumen,[`LoadOptions`](../../groupdocs.comparison.options/loadoptions) Dan[`ComparerSettings`](../comparersettings) . |
| [Comparer](comparer#constructor_7)(string, LoadOptions, ComparerSettings) | Menginisialisasi instance baru[`Comparer`](../comparer) kelas dengan jalur file sumber,[`LoadOptions`](../../groupdocs.comparison.options/loadoptions) Dan[`ComparerSettings`](../comparersettings) . |

## Properti

| Nama | Keterangan |
| --- | --- |
| [Source](../../groupdocs.comparison/comparer/source) { get; } | File sumber yang dibandingkan. |
| [Targets](../../groupdocs.comparison/comparer/targets) { get; } | Daftar file target untuk dibandingkan dengan file sumber. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [Add](../../groupdocs.comparison/comparer/add#add)(Stream) | Menambahkan aliran dokumen ke perbandingan. |
| [Add](../../groupdocs.comparison/comparer/add#add_2)(string) | Menambahkan file ke perbandingan. |
| [Add](../../groupdocs.comparison/comparer/add#add_1)(Stream, LoadOptions) | Menambahkan aliran dokumen untuk dibandingkan dengan opsi pemuatan yang ditentukan. |
| [Add](../../groupdocs.comparison/comparer/add#add_3)(string, LoadOptions) | Menambahkan file untuk dibandingkan dengan opsi pemuatan yang ditentukan. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges)(Stream, ApplyChangeOptions) | Menerima atau menolak perubahan dan menerapkannya ke dokumen yang dihasilkan. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_2)(string, ApplyChangeOptions) | Menerima atau menolak perubahan dan menerapkannya ke dokumen yang dihasilkan. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_1)(Stream, SaveOptions, ApplyChangeOptions) | Menerima atau menolak perubahan dan menerapkannya ke dokumen yang dihasilkan. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_3)(string, SaveOptions, ApplyChangeOptions) | Menerima atau menolak perubahan dan menerapkannya ke dokumen yang dihasilkan. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare)() | Membandingkan dokumen tanpa menyimpan hasil dengan opsi default |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_1)(CompareOptions) | Membandingkan dokumen tanpa menyimpan hasil. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_3)(Stream) | Membandingkan dokumen dan menyimpan hasilnya ke file stream |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_7)(string) | Membandingkan dokumen dan menyimpan hasilnya ke file path |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_2)(SaveOptions, CompareOptions) | Membandingkan dokumen tanpa menyimpan hasil. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_4)(Stream, CompareOptions) | Membandingkan dokumen dan menyimpan hasilnya ke file stream |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_5)(Stream, SaveOptions) | Membandingkan dokumen dan menyimpan hasilnya ke file stream |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_8)(string, CompareOptions) | Membandingkan dokumen dan menyimpan hasilnya ke file path |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_9)(string, SaveOptions) | Membandingkan dokumen dan menyimpan hasilnya ke file path |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_6)(Stream, SaveOptions, CompareOptions) | Membandingkan dokumen dan menyimpan hasil ke aliran. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_10)(string, SaveOptions, CompareOptions) | Membandingkan dokumen dan menyimpan hasilnya ke file path |
| [Dispose](../../groupdocs.comparison/comparer/dispose)() | Merilis sumber daya. |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges)() | Mendapat daftar perubahan antara file sumber dan target. |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges_1)(GetChangeOptions) | Mendapat daftar perubahan antara file sumber dan target. |
| [GetResultString](../../groupdocs.comparison/comparer/getresultstring)() | Dapatkan string hasil setelah perbandingan (Hanya untuk Perbandingan Teks). |

### Lihat juga

* ruang nama [GroupDocs.Comparison](../../groupdocs.comparison)
* perakitan [GroupDocs.Comparison](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Comparison.dll -->
