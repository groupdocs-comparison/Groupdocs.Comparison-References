---
title: "LoadOptions"
second_title: "GroupDocs.Comparison .NET için API Referansı"
description: "Bir belge yüklenirken ek seçenekleri belirtmeye izin verir."
type: docs
weight: 300
url: /tr/net/groupdocs.comparison.options/loadoptions/
---
## LoadOptions class

Bir belge yüklenirken ek seçenekleri belirtmeye izin verir.

```csharp
public class LoadOptions
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [LoadOptions](loadoptions)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [FileType](../../groupdocs.comparison.options/loadoptions/filetype) { get; set; } | Karşılaştırma için dosya türünü manuel olarak ayarlayarak otomatik dosya türü algılamasını geçersiz kılar. |
| [FontDirectories](../../groupdocs.comparison.options/loadoptions/fontdirectories) { get; set; } | Yüklenmesi gereken yazı tipi dizinlerinin listesi. |
| [LoadText](../../groupdocs.comparison.options/loadoptions/loadtext) { get; set; } | Geçen dizelerin karşılaştırma metni olduğunu, dosya yolu olmadığını gösterir (Yalnızca Metin Karşılaştırması için). |
| [Password](../../groupdocs.comparison.options/loadoptions/password) { get; set; } | Belgenin parolası. |
| [SkipExternalResources](../../groupdocs.comparison.options/loadoptions/skipexternalresources) { get; set; } | Tüm harici kaynakların (ör. uzak bir URL'den referans verilen görüntüler) yüklenmesini devre dışı bırakır, sadece [`WhitelistedResources`](./whitelistedresources) hariç. |
| [WhitelistedResources](../../groupdocs.comparison.options/loadoptions/whitelistedresources) { get; set; } | [`SkipExternalResources`](./skipexternalresources) `true` olarak ayarlandığında yüklenmesi gereken harici kaynaklara karşılık gelen URL parçacıklarının listesi. |

### Ayrıca Bakınız

* namespace [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../)

<!-- DÜZENLEMEYİN: GroupDocs.Comparison.dll için xmldocmd tarafından oluşturuldu -->
