---
title: "PdfCompareOptions.ComparisonDisplayMode"
second_title: "مرجع API لـ GroupDocs.Comparison لـ .NET"
description: "يتحكم في كيفية تنسيق مستند نتيجة مقارنة PDF."
type: docs
weight: 370
url: /ar/net/groupdocs.comparison.options/pdfcompareoptions.comparisondisplaymode/
---
## PdfCompareOptions.ComparisonDisplayMode enumeration

يتحكم في كيفية تنسيق مستند نتيجة مقارنة PDF.

```csharp
public enum ComparisonDisplayMode
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Inline | `0` | الوضع الافتراضي. ينتج مستند PDF موحد واحد حيث يتم تمييز المحتوى المحذوف بلون واحد والمحتوى المُدرج بلون آخر. يتواجد كل من المحتوى المصدر والهدف على نفس الصفحات، مما قد يسبب تداخلًا عندما تختلف المستندات بشكل كبير. |
| SideBySide | `1` | يعرض كل صفحة نتيجة صفحة مصدر وصفحة الهدف المقابلة جنبًا إلى جنب. تظهر الحذفيات على اليسار (جانب المصدر) والإدخالات على اليمين (جانب الهدف). لا يتداخل المحتوى من المستندين أبداً، مما يجعل هذا الوضع مناسبًا عندما تختلف المستندات بشكل كبير. |
| Interleaved | `2` | ينتج مستندًا بصفحات متناوبة: الصفحات ذات الأرقام الفردية تأتي من مستند المصدر (تظهر الحذفيات) والصفحات ذات الأرقام الزوجية تأتي من مستند الهدف (تظهر الإدخالات). افتح النتيجة في عارض PDF مع تمكين \"Two Page View\" لرؤية كل زوج مصدر/هدف جنبًا إلى جنب على الشاشة. مثل SideBySide، يمنع هذا الوضع تداخل المحتوى وهو الأنسب للمستندات التي تختلف اختلافًا كبيرًا. |

### انظر أيضًا

* class [PdfCompareOptions](../pdfcompareoptions)
* namespace [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldoccmd لـ GroupDocs.Comparison.dll -->
