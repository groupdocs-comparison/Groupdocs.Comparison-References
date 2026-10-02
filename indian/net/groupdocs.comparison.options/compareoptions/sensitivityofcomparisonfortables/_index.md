---
title: "SensitivityOfComparisonForTables"
second_title: "GroupDocs.Comparison for .NET API संदर्भ"
description: "टेबलों के लिए तुलना की संवेदनशीलता को प्राप्त करता है या सेट करता है।"
type: docs
weight: 220
url: /hi/net/groupdocs.comparison.options/compareoptions/sensitivityofcomparisonfortables/
---
## CompareOptions.SensitivityOfComparisonForTables property

टेबलों के लिए तुलना की संवेदनशीलता को प्राप्त करता है या सेट करता है।

```csharp
public int? SensitivityOfComparisonForTables { get; set; }
```

### Property Value

यदि मान null है, तो SensitivityOfComparison का उपयोग किया जाता है। दो तुलना किए गए वस्तुओं के सभी तत्वों के संबंध में हटाए और सम्मिलित किए गए तत्वों का प्रतिशत। यदि यह प्रतिशत अधिक हो जाता है, तो वस्तु की तुलना नहीं की जाती बल्कि उसे पूरी तरह सम्मिलित और हटाया हुआ माना जाता है। Min value - 0% => तुलना दो तुलना किए गए वस्तु के सामान्य उपक्रम की किसी भी लंबाई के लिए नहीं होती। Default value - 75% => तुलना तब होती है जब दो तुलना किए गए वस्तुओं के सभी तत्वों के संबंध में हटाए और सम्मिलित तत्वों का प्रतिशत 75 से अधिक नहीं होता। Max value - 100% => तुलना दो तुलना किए गए वस्तुओं के सामान्य उपक्रम की किसी भी लंबाई पर होती है।

### साथ ही देखें

* class [CompareOptions](../../compareoptions)
* namespace [GroupDocs.Comparison.Options](../../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Comparison.dll के लिए उत्पन्न किया गया -->
