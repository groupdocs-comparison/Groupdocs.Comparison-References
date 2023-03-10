---
title: Comparer
second_title: .NET API Başvurusu için GroupDocs.Comparison
description: Belge karşılaştırma sürecini kontrol eden ana sınıfı temsil eder.
type: docs
weight: 100
url: /tr/net/groupdocs.comparison/comparer/
---
## Comparer class

Belge karşılaştırma sürecini kontrol eden ana sınıfı temsil eder.

```csharp
public class Comparer : IDisposable
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [Comparer](comparer#constructor)(Stream) | Yeni örneğini başlatır[`Comparer`](../comparer) kaynak belge akışına sahip sınıf. |
| [Comparer](comparer#constructor_4)(string) | Yeni örneğini başlatır[`Comparer`](../comparer) kaynak dosya path. ile sınıf |
| [Comparer](comparer#constructor_1)(Stream, ComparerSettings) | Yeni örneğini başlatır[`Comparer`](../comparer)kaynak belge akışına sahip sınıf ve[`ComparerSettings`](../comparersettings) . |
| [Comparer](comparer#constructor_2)(Stream, LoadOptions) | Yeni örneğini başlatır[`Comparer`](../comparer) kaynak belge akışı ile ve[`LoadOptions`](../../groupdocs.comparison.options/loadoptions) . |
| [Comparer](comparer#constructor_5)(string, ComparerSettings) | Yeni örneğini başlatır[`Comparer`](../comparer) kaynak dosya yolu ile sınıf ve[`ComparerSettings`](../comparersettings) . |
| [Comparer](comparer#constructor_6)(string, LoadOptions) | Yeni örneğini başlatır[`Comparer`](../comparer) kaynak dosya yolu ile ve[`LoadOptions`](../../groupdocs.comparison.options/loadoptions) . |
| [Comparer](comparer#constructor_3)(Stream, LoadOptions, ComparerSettings) | Yeni örneğini başlatır[`Comparer`](../comparer) belge akışı ile sınıf,[`LoadOptions`](../../groupdocs.comparison.options/loadoptions) Ve[`ComparerSettings`](../comparersettings) . |
| [Comparer](comparer#constructor_7)(string, LoadOptions, ComparerSettings) | Yeni örneğini başlatır[`Comparer`](../comparer) kaynak dosya yoluna sahip sınıf,[`LoadOptions`](../../groupdocs.comparison.options/loadoptions) Ve[`ComparerSettings`](../comparersettings) . |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Source](../../groupdocs.comparison/comparer/source) { get; } | Karşılaştırılan kaynak dosya. |
| [Targets](../../groupdocs.comparison/comparer/targets) { get; } | Kaynak dosyayla karşılaştırılacak hedef dosyaların listesi. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [Add](../../groupdocs.comparison/comparer/add#add)(Stream) | Belge akışını karşılaştırmaya ekler. |
| [Add](../../groupdocs.comparison/comparer/add#add_2)(string) | Dosyayı karşılaştırmaya ekler. |
| [Add](../../groupdocs.comparison/comparer/add#add_1)(Stream, LoadOptions) | Belirtilen yükleme seçenekleriyle karşılaştırmak için belge akışı ekler. |
| [Add](../../groupdocs.comparison/comparer/add#add_3)(string, LoadOptions) | Dosyayı belirtilen yükleme seçenekleriyle karşılaştırmaya ekler. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges)(Stream, ApplyChangeOptions) | Değişiklikleri kabul eder veya reddeder ve bunları sonuç belgesine uygular. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_2)(string, ApplyChangeOptions) | Değişiklikleri kabul eder veya reddeder ve bunları sonuç belgesine uygular. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_1)(Stream, SaveOptions, ApplyChangeOptions) | Değişiklikleri kabul eder veya reddeder ve bunları sonuç belgesine uygular. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_3)(string, SaveOptions, ApplyChangeOptions) | Değişiklikleri kabul eder veya reddeder ve bunları sonuç belgesine uygular. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare)() | Sonuçları varsayılan seçeneklerle kaydetmeden belgeleri karşılaştırır |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_1)(CompareOptions) | Sonucu kaydetmeden belgeleri karşılaştırır. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_3)(Stream) | Belgeleri karşılaştırır ve sonucu stream dosyasına kaydeder |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_7)(string) | Belgeleri karşılaştırır ve sonucu path dosyasına kaydeder |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_2)(SaveOptions, CompareOptions) | Sonucu kaydetmeden belgeleri karşılaştırır. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_4)(Stream, CompareOptions) | Belgeleri karşılaştırır ve sonucu stream dosyasına kaydeder |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_5)(Stream, SaveOptions) | Belgeleri karşılaştırır ve sonucu stream dosyasına kaydeder |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_8)(string, CompareOptions) | Belgeleri karşılaştırır ve sonucu path dosyasına kaydeder |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_9)(string, SaveOptions) | Belgeleri karşılaştırır ve sonucu path dosyasına kaydeder |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_6)(Stream, SaveOptions, CompareOptions) | Belgeleri karşılaştırır ve sonucu bir akışa kaydeder. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_10)(string, SaveOptions, CompareOptions) | Belgeleri karşılaştırır ve sonucu path dosyasına kaydeder |
| [Dispose](../../groupdocs.comparison/comparer/dispose)() | Kaynakları serbest bırakır. |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges)() | Kaynak ve hedef dosya(lar) arasındaki değişikliklerin listesini alır. |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges_1)(GetChangeOptions) | Kaynak ve hedef dosya(lar) arasındaki değişikliklerin listesini alır. |
| [GetResultString](../../groupdocs.comparison/comparer/getresultstring)() | Karşılaştırmadan sonra sonuç dizesini al (Yalnızca Metin Karşılaştırma için). |

### Ayrıca bakınız

* ad alanı [GroupDocs.Comparison](../../groupdocs.comparison)
* toplantı [GroupDocs.Comparison](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Comparison.dll -->
