---
title: "SensitivityOfComparisonForTables"
second_title: "مرجع API لـ GroupDocs.Comparison لـ .NET"
description: "يحصل أو يعيّن حساسية المقارنة للجداول."
type: docs
weight: 220
url: /ar/net/groupdocs.comparison.options/compareoptions/sensitivityofcomparisonfortables/
---
## CompareOptions.SensitivityOfComparisonForTables property

يحصل أو يعيّن حساسية المقارنة للجداول.

```csharp
public int? SensitivityOfComparisonForTables { get; set; }
```

### Property Value

إذا كانت القيمة null، يتم استخدام SensitivityOfComparison بدلاً منها. نسبة العناصر المحذوفة والمدخلة لكائنين تم مقارنتهما بالنسبة إلى جميع عناصر هذه الكائنات. إذا تم تجاوز هذه النسبة، لا يتم مقارنة الكائن بل يُعتبر مدخلًا ومحذوفًا بالكامل. القيمة الدنيا - 0% => لا تحدث المقارنة لأي طول من المتتالية المشتركة لكائنين تم مقارنتهما. القيمة الافتراضية - 75% => تحدث المقارنة إذا لم تكن نسبة العناصر المحذوفة والمدخلة لكائنين مقارنةً بجميع عناصر هذه الكائنات أكثر من 75. القيمة القصوى - 100% => تحدث المقارنة لأي طول من المتتالية المشتركة لكائنين تم مقارنتهما.

### انظر أيضًا

* class [CompareOptions](../../compareoptions)
* namespace [GroupDocs.Comparison.Options](../../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldoccmd لـ GroupDocs.Comparison.dll -->
