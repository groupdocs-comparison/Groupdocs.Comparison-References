---
title: "Karşılaştırıcı"
second_title: "GroupDocs.Comparison .NET için API Referansı"
description: "Belgelerin karşılaştırma sürecini kontrol eden ana sınıfı temsil eder."
type: docs
weight: 100
url: /tr/net/groupdocs.comparison/comparer/
---
## Comparer class

Belgelerin karşılaştırma sürecini kontrol eden ana sınıfı temsil eder.

```csharp
public sealed class Comparer : IDisposable
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [Comparer](comparer#constructor)(Stream) | Kaynak belge akışıyla yeni bir [`Comparer`](../comparer) sınıfı örneği başlatır. |
| [Comparer](comparer#constructor_4)(string) | Kaynak dosya yolu ile yeni bir [`Comparer`](../comparer) sınıfı örneği başlatır. |
| [Comparer](comparer#constructor_1)(Stream, ComparerSettings) | Kaynak belge akışı ve [`ComparerSettings`](../comparersettings) ile yeni bir [`Comparer`](../comparer) sınıfı örneği başlatır. |
| [Comparer](comparer#constructor_2)(Stream, LoadOptions) | Kaynak belge akışı ve [`LoadOptions`](../../groupdocs.comparison.options/loadoptions) ile yeni bir [`Comparer`](../comparer) örneği başlatır. |
| [Comparer](comparer#constructor_6)(string, CompareOptions) | Kaynak klasör yolu ve [`CompareOptions`](../../groupdocs.comparison.options/compareoptions) ile yeni bir [`Comparer`](../comparer) örneği başlatır. |
| [Comparer](comparer#constructor_5)(string, ComparerSettings) | Kaynak dosya yolu ve [`ComparerSettings`](../comparersettings) ile yeni bir [`Comparer`](../comparer) sınıfı örneği başlatır. |
| [Comparer](comparer#constructor_7)(string, LoadOptions) | Kaynak dosya yolu ve [`LoadOptions`](../../groupdocs.comparison.options/loadoptions) ile yeni bir [`Comparer`](../comparer) örneği başlatır. |
| [Comparer](comparer#constructor_3)(Stream, LoadOptions, ComparerSettings) | Belge akışı, [`LoadOptions`](../../groupdocs.comparison.options/loadoptions) ve [`ComparerSettings`](../comparersettings) ile yeni bir [`Comparer`](../comparer) sınıfı örneği başlatır. |
| [Comparer](comparer#constructor_8)(string, LoadOptions, ComparerSettings) | Kaynak dosya yolu, [`LoadOptions`](../../groupdocs.comparison.options/loadoptions) ve [`ComparerSettings`](../comparersettings) ile yeni bir [`Comparer`](../comparer) sınıfı örneği başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Result](../../groupdocs.comparison/comparer/result) { get; } | Sonuç belgesi. |
| [Source](../../groupdocs.comparison/comparer/source) { get; } | Karşılaştırılan kaynak dosya. |
| [SourceFolder](../../groupdocs.comparison/comparer/sourcefolder) { get; } | Karşılaştırılan kaynak klasör. |
| [TargetFolder](../../groupdocs.comparison/comparer/targetfolder) { get; set; } | Karşılaştırılan hedef klasör. |
| [Targets](../../groupdocs.comparison/comparer/targets) { get; } | Kaynak dosyayla karşılaştırılacak hedef dosyaların listesi. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Add](../../groupdocs.comparison/comparer/add#add)(Stream) | Karşılaştırmaya belge akışı ekler. |
| [Add](../../groupdocs.comparison/comparer/add#add_2)(string) | Karşılaştırmaya dosya ekler. |
| [Add](../../groupdocs.comparison/comparer/add#add_1)(Stream, LoadOptions) | Belirtilen yükleme seçenekleriyle karşılaştırmaya belge akışı ekler. |
| [Add](../../groupdocs.comparison/comparer/add#add_3)(string, CompareOptions) | Karşılaştırmaya klasör ekler. |
| [Add](../../groupdocs.comparison/comparer/add#add_4)(string, LoadOptions) | Belirtilen yükleme seçenekleriyle karşılaştırmaya dosya ekler. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges)(Stream, ApplyChangeOptions) | Değişiklikleri kabul eder veya reddeder ve sonuç belgesine uygular. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_2)(string, ApplyChangeOptions) | Değişiklikleri kabul eder veya reddeder ve sonuç belgesine uygular. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_1)(Stream, SaveOptions, ApplyChangeOptions) | Değişiklikleri kabul eder veya reddeder ve sonuç belgesine uygular. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_3)(string, SaveOptions, ApplyChangeOptions) | Değişiklikleri kabul eder veya reddeder ve sonuç belgesine uygular. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare)() | Belgeleri varsayılan seçeneklerle sonucu kaydetmeden karşılaştırır |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_1)(CompareOptions) | Belgeleri sonucu kaydetmeden karşılaştırır. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_3)(Stream) | Belgeleri karşılaştırır ve sonucu dosya akışına kaydeder |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_7)(string) | Belgeleri karşılaştırır ve sonucu dosya yoluna kaydeder |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_2)(SaveOptions, CompareOptions) | Belgeleri sonucu kaydetmeden karşılaştırır. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_4)(Stream, CompareOptions) | Belgeleri karşılaştırır ve sonucu dosya akışına kaydeder |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_5)(Stream, SaveOptions) | Belgeleri karşılaştırır ve sonucu dosya akışına kaydeder |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_8)(string, CompareOptions) | Belgeleri karşılaştırır ve sonucu dosya yoluna kaydeder |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_9)(string, SaveOptions) | Belgeleri karşılaştırır ve sonucu dosya yoluna kaydeder |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_6)(Stream, SaveOptions, CompareOptions) | Belgeleri karşılaştırır ve sonucu bir akışa kaydeder. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_10)(string, SaveOptions, CompareOptions) | Belgeleri karşılaştırır ve sonucu dosya yoluna kaydeder |
| [CompareDirectory](../../groupdocs.comparison/comparer/comparedirectory)(string, CompareOptions) | Dizini karşılaştırır ve sonucu dosya yoluna kaydeder |
| [Dispose](../../groupdocs.comparison/comparer/dispose)() | Kaynakları serbest bırakır. |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges)() | Kaynak ve hedef dosya(lar) arasındaki değişikliklerin listesini alır. |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges_1)(ChangeType) | Kaynak ve hedef dosya(lar) arasındaki değişikliklerin listesini alır. |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges_2)(GetChangeOptions) | Kaynak ve hedef dosya(lar) arasındaki değişikliklerin listesini alır. |
| [GetResultDocumentStream](../../groupdocs.comparison/comparer/getresultdocumentstream)() | Sonuç belgesinin akışını alır, akış mevcut değilse null döndürür |
| [GetResultString](../../groupdocs.comparison/comparer/getresultstring)() | Karşılaştırmadan sonra sonuç dizesini al (Yalnızca Metin Karşılaştırması için). |

### Ayrıca Bakınız

* namespace [GroupDocs.Comparison](../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../)

<!-- DÜZENLEMEYİN: GroupDocs.Comparison.dll için xmldocmd tarafından oluşturuldu -->
