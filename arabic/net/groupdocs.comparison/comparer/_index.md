---
title: "مقارن"
second_title: "مرجع API لـ GroupDocs.Comparison لـ .NET"
description: "يمثل الفئة الرئيسية التي تتحكم في عملية مقارنة المستندات."
type: docs
weight: 100
url: /ar/net/groupdocs.comparison/comparer/
---
## Comparer class

يمثل الفئة الرئيسية التي تتحكم في عملية مقارنة المستندات.

```csharp
public sealed class Comparer : IDisposable
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [Comparer](comparer#constructor)(Stream) | ينشئ مثيلاً جديدًا لفئة [`Comparer`](../comparer) باستخدام تدفق المستند المصدر. |
| [Comparer](comparer#constructor_4)(string) | ينشئ مثيلاً جديدًا لفئة [`Comparer`](../comparer) باستخدام مسار الملف المصدر. |
| [Comparer](comparer#constructor_1)(Stream, ComparerSettings) | ينشئ مثيلاً جديدًا لفئة [`Comparer`](../comparer) باستخدام تدفق المستند المصدر و[`ComparerSettings`](../comparersettings). |
| [Comparer](comparer#constructor_2)(Stream, LoadOptions) | ينشئ مثيلاً جديدًا لـ[`Comparer`](../comparer) باستخدام تدفق المستند المصدر و[`LoadOptions`](../../groupdocs.comparison.options/loadoptions). |
| [Comparer](comparer#constructor_6)(string, CompareOptions) | ينشئ مثيلاً جديدًا لـ[`Comparer`](../comparer) باستخدام مسار المجلد المصدر و[`CompareOptions`](../../groupdocs.comparison.options/compareoptions). |
| [Comparer](comparer#constructor_5)(string, ComparerSettings) | ينشئ مثيلاً جديدًا لفئة [`Comparer`](../comparer) باستخدام مسار الملف المصدر و[`ComparerSettings`](../comparersettings). |
| [Comparer](comparer#constructor_7)(string, LoadOptions) | يُنشئ مثلاً جديدًا من [`Comparer`](../comparer) باستخدام مسار ملف المصدر و[`LoadOptions`](../../groupdocs.comparison.options/loadoptions). |
| [Comparer](comparer#constructor_3)(Stream, LoadOptions, ComparerSettings) | يُنشئ مثلاً جديدًا من فئة [`Comparer`](../comparer) باستخدام تدفق المستند، و[`LoadOptions`](../../groupdocs.comparison.options/loadoptions) و[`ComparerSettings`](../comparersettings). |
| [Comparer](comparer#constructor_8)(string, LoadOptions, ComparerSettings) | يُنشئ مثلاً جديدًا من فئة [`Comparer`](../comparer) باستخدام مسار ملف المصدر، و[`LoadOptions`](../../groupdocs.comparison.options/loadoptions) و[`ComparerSettings`](../comparersettings). |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Result](../../groupdocs.comparison/comparer/result) { get; } | مستند النتيجة. |
| [Source](../../groupdocs.comparison/comparer/source) { get; } | ملف المصدر الذي يتم مقارنته. |
| [SourceFolder](../../groupdocs.comparison/comparer/sourcefolder) { get; } | مجلد المصدر الذي يتم مقارنته. |
| [TargetFolder](../../groupdocs.comparison/comparer/targetfolder) { get; set; } | مجلد الهدف الذي يتم مقارنته. |
| [Targets](../../groupdocs.comparison/comparer/targets) { get; } | قائمة ملفات الهدف للمقارنة مع ملف المصدر. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Add](../../groupdocs.comparison/comparer/add#add)(Stream) | يضيف تدفق المستند إلى المقارنة. |
| [Add](../../groupdocs.comparison/comparer/add#add_2)(string) | يضيف ملفًا إلى المقارنة. |
| [Add](../../groupdocs.comparison/comparer/add#add_1)(Stream, LoadOptions) | يضيف تدفق المستند إلى المقارنة مع خيارات التحميل المحددة. |
| [Add](../../groupdocs.comparison/comparer/add#add_3)(string, CompareOptions) | يضيف مجلدًا إلى المقارنة. |
| [Add](../../groupdocs.comparison/comparer/add#add_4)(string, LoadOptions) | يضيف ملفًا إلى المقارنة مع خيارات التحميل المحددة. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges)(Stream, ApplyChangeOptions) | يقبل أو يرفض التغييرات ويطبقها على المستند الناتج. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_2)(string, ApplyChangeOptions) | يقبل أو يرفض التغييرات ويطبقها على المستند الناتج. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_1)(Stream, SaveOptions, ApplyChangeOptions) | يقبل أو يرفض التغييرات ويطبقها على المستند الناتج. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_3)(string, SaveOptions, ApplyChangeOptions) | يقبل أو يرفض التغييرات ويطبقها على المستند الناتج. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare)() | يقارن المستندات دون حفظ النتيجة باستخدام الخيارات الافتراضية |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_1)(CompareOptions) | يقارن المستندات دون حفظ النتيجة. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_3)(Stream) | يقارن المستندات ويحفظ النتيجة إلى تدفق الملف |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_7)(string) | يقارن المستندات ويحفظ النتيجة إلى مسار الملف |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_2)(SaveOptions, CompareOptions) | يقارن المستندات دون حفظ النتيجة. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_4)(Stream, CompareOptions) | يقارن المستندات ويحفظ النتيجة إلى تدفق الملف |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_5)(Stream, SaveOptions) | يقارن المستندات ويحفظ النتيجة إلى تدفق الملف |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_8)(string, CompareOptions) | يقارن المستندات ويحفظ النتيجة إلى مسار الملف |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_9)(string, SaveOptions) | يقارن المستندات ويحفظ النتيجة إلى مسار الملف |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_6)(Stream, SaveOptions, CompareOptions) | يقارن المستندات ويحفظ النتيجة إلى تدفق. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_10)(string, SaveOptions, CompareOptions) | يقارن المستندات ويحفظ النتيجة إلى مسار الملف |
| [CompareDirectory](../../groupdocs.comparison/comparer/comparedirectory)(string, CompareOptions) | يقارن الدليل ويحفظ النتيجة إلى مسار الملف |
| [Dispose](../../groupdocs.comparison/comparer/dispose)() | يطلق الموارد. |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges)() | يحصل على قائمة التغييرات بين ملف(ات) المصدر والهدف. |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges_1)(ChangeType) | يحصل على قائمة التغييرات بين ملف(ات) المصدر والهدف. |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges_2)(GetChangeOptions) | يحصل على قائمة التغييرات بين ملف(ات) المصدر والهدف. |
| [GetResultDocumentStream](../../groupdocs.comparison/comparer/getresultdocumentstream)() | يحصل على تدفق مستند النتيجة، يرجع null إذا لم يكن التدفق موجودًا |
| [GetResultString](../../groupdocs.comparison/comparer/getresultstring)() | احصل على سلسلة النتيجة بعد المقارنة (للمقارنة النصية فقط). |

### انظر أيضًا

* namespace [GroupDocs.Comparison](../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldoccmd لـ GroupDocs.Comparison.dll -->
