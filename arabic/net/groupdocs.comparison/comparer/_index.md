---
title: Comparer
second_title: GroupDocs.Comparison لمرجع .NET API
description: يمثل الفئة الرئيسية التي تتحكم في عملية مقارنة المستندات.
type: docs
weight: 100
url: /ar/net/groupdocs.comparison/comparer/
---
## Comparer class

يمثل الفئة الرئيسية التي تتحكم في عملية مقارنة المستندات.

```csharp
public class Comparer : IDisposable
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [Comparer](comparer#constructor)(Stream) | تهيئة مثيل جديد لـ[`Comparer`](../comparer) فئة مع دفق المستند المصدر. |
| [Comparer](comparer#constructor_4)(string) | تهيئة مثيل جديد لـ[`Comparer`](../comparer) فئة بمسار الملف المصدر. |
| [Comparer](comparer#constructor_1)(Stream, ComparerSettings) | تهيئة مثيل جديد لـ[`Comparer`](../comparer)فئة مع مصدر وثيقة دفق و[`ComparerSettings`](../comparersettings) . |
| [Comparer](comparer#constructor_2)(Stream, LoadOptions) | تهيئة مثيل جديد لـ[`Comparer`](../comparer) مع مصدر وثيقة دفق و[`LoadOptions`](../../groupdocs.comparison.options/loadoptions) . |
| [Comparer](comparer#constructor_5)(string, ComparerSettings) | تهيئة مثيل جديد لـ[`Comparer`](../comparer) فئة مع مسار الملف المصدر و[`ComparerSettings`](../comparersettings) . |
| [Comparer](comparer#constructor_6)(string, LoadOptions) | تهيئة مثيل جديد لـ[`Comparer`](../comparer) مع مسار الملف المصدر و[`LoadOptions`](../../groupdocs.comparison.options/loadoptions) . |
| [Comparer](comparer#constructor_3)(Stream, LoadOptions, ComparerSettings) | تهيئة مثيل جديد لـ[`Comparer`](../comparer) فئة مع دفق المستند ،[`LoadOptions`](../../groupdocs.comparison.options/loadoptions) و[`ComparerSettings`](../comparersettings) . |
| [Comparer](comparer#constructor_7)(string, LoadOptions, ComparerSettings) | تهيئة مثيل جديد لـ[`Comparer`](../comparer) فئة مع مسار الملف المصدر ،[`LoadOptions`](../../groupdocs.comparison.options/loadoptions) و[`ComparerSettings`](../comparersettings) . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Source](../../groupdocs.comparison/comparer/source) { get; } | ملف المصدر الذي تتم مقارنته . |
| [Targets](../../groupdocs.comparison/comparer/targets) { get; } | قائمة الملفات الهدف للمقارنة مع الملف المصدر. |

## طُرق

| اسم | وصف |
| --- | --- |
| [Add](../../groupdocs.comparison/comparer/add#add)(Stream) | يضيف دفق المستند للمقارنة . |
| [Add](../../groupdocs.comparison/comparer/add#add_2)(string) | إضافة ملف للمقارنة . |
| [Add](../../groupdocs.comparison/comparer/add#add_1)(Stream, LoadOptions) | يضيف تدفق المستند للمقارنة بخيارات التحميل المحددة. |
| [Add](../../groupdocs.comparison/comparer/add#add_3)(string, LoadOptions) | إضافة ملف للمقارنة بخيارات التحميل المحددة. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges)(Stream, ApplyChangeOptions) | قبول التغييرات أو رفضها وتطبيقها على المستند الناتج. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_2)(string, ApplyChangeOptions) | قبول التغييرات أو رفضها وتطبيقها على المستند الناتج. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_1)(Stream, SaveOptions, ApplyChangeOptions) | قبول التغييرات أو رفضها وتطبيقها على المستند الناتج. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_3)(string, SaveOptions, ApplyChangeOptions) | قبول التغييرات أو رفضها وتطبيقها على المستند الناتج. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare)() | مقارنة المستندات بدون حفظ النتيجة بالخيارات الافتراضية |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_1)(CompareOptions) | مقارنة المستندات بدون حفظ النتيجة. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_3)(Stream) | يقارن المستندات ويحفظ النتيجة في ملف Stream |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_7)(string) | مقارنة المستندات وحفظ النتيجة في مسار الملف |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_2)(SaveOptions, CompareOptions) | مقارنة المستندات بدون حفظ النتيجة. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_4)(Stream, CompareOptions) | يقارن المستندات ويحفظ النتيجة في ملف Stream |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_5)(Stream, SaveOptions) | مقارنة المستندات وحفظ النتيجة في ملف Stream |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_8)(string, CompareOptions) | مقارنة المستندات وحفظ النتيجة في مسار الملف |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_9)(string, SaveOptions) | مقارنة المستندات وحفظ النتيجة في مسار الملف |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_6)(Stream, SaveOptions, CompareOptions) | مقارنة المستندات وحفظ النتيجة في دفق . |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_10)(string, SaveOptions, CompareOptions) | مقارنة المستندات وحفظ النتيجة في مسار الملف |
| [Dispose](../../groupdocs.comparison/comparer/dispose)() | إصدارات الموارد . |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges)() | الحصول على قائمة بالتغييرات بين الملف (الملفات) المصدر والهدف. |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges_1)(GetChangeOptions) | الحصول على قائمة بالتغييرات بين الملف (الملفات) المصدر والهدف. |
| [GetResultString](../../groupdocs.comparison/comparer/getresultstring)() | الحصول على سلسلة النتائج بعد المقارنة (لمقارنة النص فقط) . |

### أنظر أيضا

* مساحة الاسم [GroupDocs.Comparison](../../groupdocs.comparison)
* المجسم [GroupDocs.Comparison](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Comparison.dll -->
