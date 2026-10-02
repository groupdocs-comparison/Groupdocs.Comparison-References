---
title: "SensitivityOfComparison"
second_title: "GroupDocs.Comparison .NET için API Referansı"
description: "Karşılaştırma hassasiyetini alır veya ayarlar."
type: docs
weight: 210
url: /tr/net/groupdocs.comparison.options/compareoptions/sensitivityofcomparison/
---
## CompareOptions.SensitivityOfComparison property

Karşılaştırma hassasiyetini alır veya ayarlar.

```csharp
public int SensitivityOfComparison { get; set; }
```

### Property Value

İki karşılaştırılan nesnenin tüm öğelerine göre silinen ve eklenen öğelerin yüzdesi. Bu yüzde aşılırsa, nesne karşılaştırılmaz ancak tamamen eklenmiş ve silinmiş olarak kabul edilir. Minimum değer - 0% => Karşılaştırma, iki karşılaştırılan nesnenin ortak alt dizisinin herhangi bir uzunluğu için gerçekleşmez. Varsayılan değer - 75% => Karşılaştırma, iki karşılaştırılan nesnenin tüm öğelerine göre silinen ve eklenen öğelerin yüzdesi %75'ten fazla olmadığında gerçekleşir. Maksimum değer - 100% => Karşılaştırma, iki karşılaştırılan nesnenin ortak alt dizisinin herhangi bir uzunluğunda gerçekleşir.

### Ayrıca Bakınız

* class [CompareOptions](../../compareoptions)
* namespace [GroupDocs.Comparison.Options](../../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.Comparison.dll için xmldocmd tarafından oluşturuldu -->
