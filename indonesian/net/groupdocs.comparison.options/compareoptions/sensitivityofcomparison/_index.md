---
title: SensitivityOfComparison
second_title: GroupDocs.Comparison untuk Referensi .NET API
description: Mendapat atau menyetel sensitivitas perbandingan.
type: docs
weight: 210
url: /id/net/groupdocs.comparison.options/compareoptions/sensitivityofcomparison/
---
## CompareOptions.SensitivityOfComparison property

Mendapat atau menyetel sensitivitas perbandingan.

```csharp
public int SensitivityOfComparison { get; set; }
```

### Nilai properti

Persentase elemen yang dihapus dan disisipkan dari dua objek yang dibandingkan dalam kaitannya dengan semua elemen objek tersebut. jika persentase ini dilampaui, objek tidak dibandingkan tetapi dianggap disisipkan dan dihapus seluruhnya. Nilai min - 0% = &gt; Perbandingan tidak terjadi untuk setiap panjang dari urutan umum dari dua objek yang dibandingkan. Nilai default - 75% =&gt; Perbandingan terjadi jika persentase elemen yang dihapus dan disisipkan dari dua objek yang dibandingkan sehubungan dengan semua elemen objek ini tidak lebih dari 75. Nilai maks - 100% =&gt; Perbandingan terjadi pada jarak berapa pun dari urutan umum dua objek yang dibandingkan.

### Lihat juga

* class [CompareOptions](../../compareoptions)
* ruang nama [GroupDocs.Comparison.Options](../../compareoptions)
* perakitan [GroupDocs.Comparison](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Comparison.dll -->
