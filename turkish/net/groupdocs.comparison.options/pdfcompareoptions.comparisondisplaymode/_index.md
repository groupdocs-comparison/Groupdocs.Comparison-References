---
title: "PdfCompareOptions.ComparisonDisplayMode"
second_title: "GroupDocs.Comparison .NET için API Referansı"
description: "Pdf karşılaştırma sonuç belgesinin nasıl düzenleneceğini kontrol eder."
type: docs
weight: 370
url: /tr/net/groupdocs.comparison.options/pdfcompareoptions.comparisondisplaymode/
---
## PdfCompareOptions.ComparisonDisplayMode enumeration

Pdf karşılaştırma sonuç belgesinin nasıl düzenleneceğini kontrol eder.

```csharp
public enum ComparisonDisplayMode
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Inline | `0` | Varsayılan mod. Silinen içerik bir renkle, eklenen içerik başka bir renkle vurgulanan tek bir birleştirilmiş PDF belgesi üretir. Hem kaynak hem hedef içerik aynı sayfalarda bir arada bulunur; belgeler önemli ölçüde farklı olduğunda bu durum çakışmaya neden olabilir. |
| SideBySide | `1` | Her sonuç sayfası, bir kaynak sayfasını ve ona karşılık gelen hedef sayfayı yan yana gösterir. Silmeler sol tarafta (kaynak tarafı) ve eklemeler sağ tarafta (hedef tarafı) görünür. İki belgeden gelen içerik asla çakışmaz, bu da bu modu belgeler büyük ölçüde farklı olduğunda uygun kılar. |
| Interleaved | `2` | Belgeyi, sayfalar sırayla değişen bir şekilde üretir: tek sayılı sayfalar kaynak belgeden (silmeleri göstererek) ve çift sayılı sayfalar hedef belgeden (eklemeleri göstererek) gelir. Sonucu, \"Two Page View\" etkinleştirilmiş bir PDF görüntüleyicide açarak her kaynak/hedef çiftini ekranda yan yana görebilirsiniz. SideBySide gibi, bu mod içerik çakışmasını önler ve büyük ölçüde farklı belgeler için en uygunudur. |

### Ayrıca Bakınız

* class [PdfCompareOptions](../pdfcompareoptions)
* namespace [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../)

<!-- DÜZENLEMEYİN: GroupDocs.Comparison.dll için xmldocmd tarafından oluşturuldu -->
