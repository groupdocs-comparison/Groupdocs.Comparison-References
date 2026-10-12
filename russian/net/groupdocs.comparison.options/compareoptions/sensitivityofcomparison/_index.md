---
title: "SensitivityOfComparison"
second_title: "Справочник API GroupDocs.Comparison для .NET"
description: "Получает или задает чувствительность сравнения."
type: docs
weight: 210
url: /ru/net/groupdocs.comparison.options/compareoptions/sensitivityofcomparison/
---
## CompareOptions.SensitivityOfComparison property

Получает или задает чувствительность сравнения.

```csharp
public int SensitivityOfComparison { get; set; }
```

### Property Value

Процент удалённых и вставленных элементов двух сравниваемых объектов относительно всех элементов этих объектов. Если этот процент превышен, объекты не сравниваются, а считаются полностью вставленными и удалёнными. Минимальное значение - 0% => Сравнение не происходит при любой длине общей подпоследовательности двух сравниваемых объектов. Значение по умолчанию - 75% => Сравнение происходит, если процент удалённых и вставленных элементов двух сравниваемых объектов относительно всех элементов этих объектов не превышает 75. Максимальное значение - 100% => Сравнение происходит при любой длине общей подпоследовательности двух сравниваемых объектов.

### См. также

* class [CompareOptions](../../compareoptions)
* namespace [GroupDocs.Comparison.Options](../../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Comparison.dll -->
