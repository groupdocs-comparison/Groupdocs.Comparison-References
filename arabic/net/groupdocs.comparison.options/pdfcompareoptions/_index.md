---
title: "PdfCompareOptions"
second_title: "مرجع API لـ GroupDocs.Comparison لـ .NET"
description: "خيارات مقارنة خاصة بمستند PDF. يرث الخيارات العامة من CompareOptions./compareoptions."
type: docs
weight: 360
url: /ar/net/groupdocs.comparison.options/pdfcompareoptions/
---
## PdfCompareOptions class

خيارات مقارنة خاصة بمستند PDF. يرث الخيارات العامة من [`CompareOptions`](../compareoptions).

```csharp
public class PdfCompareOptions : CompareOptions
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [PdfCompareOptions](pdfcompareoptions)() | ينشئ مثيلاً جديدًا للفئة [`PdfCompareOptions`](../pdfcompareoptions). |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AnnotationAuthorName](../../groupdocs.comparison.options/pdfcompareoptions/annotationauthorname) { get; set; } | يحصل أو يعيّن اسم المؤلف المستخدم للتعليقات التوضيحية عندما يكون [`DisplayMode`](./displaymode) مضبوطًا على Interleaved. |
| [CalculateCoordinates](../../groupdocs.comparison.options/compareoptions/calculatecoordinates) { get; set; } | يشير إلى ما إذا كان يجب حساب إحداثيات المكونات المتغيّرة. |
| [CalculateCoordinatesMode](../../groupdocs.comparison.options/compareoptions/calculatecoordinatesmode) { get; set; } | يحدد حساب الإحداثيات لوضع المكونات المتغيّرة. |
| [ChangedItemStyle](../../groupdocs.comparison.options/compareoptions/changeditemstyle) { get; set; } | يصف النمط للمكونات المتغيّرة. |
| [CompareImagesPdf](../../groupdocs.comparison.options/pdfcompareoptions/compareimagespdf) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب مقارنة الصور في مستندات PDF. |
| [DeletedItemStyle](../../groupdocs.comparison.options/compareoptions/deleteditemstyle) { get; set; } | يصف النمط للمكونات المحذوفة. |
| [DetalisationLevel](../../groupdocs.comparison.options/compareoptions/detalisationlevel) { get; set; } | يحصل أو يعيّن مستوى تفاصيل المقارنة. |
| [DetectStyleChanges](../../groupdocs.comparison.options/compareoptions/detectstylechanges) { get; set; } | يحدد ما إذا كان يجب اكتشاف تغييرات النمط أم لا. |
| [DiagramMasterSetting](../../groupdocs.comparison.options/compareoptions/diagrammastersetting) { get; set; } | يحصل أو يعيّن قيمة المسار للملف الرئيسي أو يستخدم المقارنة بدون مسار للملف الرئيسي. هذا الخيار مخصص فقط للرسوم البيانية. |
| [DirectoryCompare](../../groupdocs.comparison.options/compareoptions/directorycompare) { get; set; } | تحكم لتفعيل مقارنة المجلدات. |
| [DisplayMode](../../groupdocs.comparison.options/pdfcompareoptions/displaymode) { get; set; } | يحصل أو يعيّن طريقة ترتيب مستند نتيجة المقارنة. القيمة الافتراضية هي Inline. |
| [ExtendedSummaryPage](../../groupdocs.comparison.options/compareoptions/extendedsummarypage) { get; set; } | يحدد ما إذا كان يجب إضافة معلومات مقارنة الملفات الموسعة إلى صفحة الملخص أم لا. |
| [FolderComparisonExtension](../../groupdocs.comparison.options/compareoptions/foldercomparisonextension) { get; set; } | يحصل أو يعيّن تنسيق ملف مقارنة المجلد الناتج. |
| [GenerateSummaryPage](../../groupdocs.comparison.options/compareoptions/generatesummarypage) { get; set; } | يحدد ما إذا كان يجب إضافة صفحة ملخص بإحصائيات التغييرات المكتشفة إلى المستند الناتج أم لا. |
| [HeaderFootersComparison](../../groupdocs.comparison.options/compareoptions/headerfooterscomparison) { get; set; } | تحكم لتفعيل مقارنة محتويات الرأس/التذييل. |
| [IgnoreChangeSettings](../../groupdocs.comparison.options/compareoptions/ignorechangesettings) { get; set; } | يحصل أو يعيّن الإعدادات لتجاهل التغييرات بناءً على التشابه. |
| [ImagesInheritanceMode](../../groupdocs.comparison.options/pdfcompareoptions/imagesinheritancemode) { get; set; } | يحدد مصدر وراثة الصور عندما تكون مقارنة الصور معطلة. |
| [InsertedItemStyle](../../groupdocs.comparison.options/compareoptions/inserteditemstyle) { get; set; } | يصف النمط للمكونات المُدرَجة. |
| [MarkChangedContent](../../groupdocs.comparison.options/compareoptions/markchangedcontent) { get; set; } | يحدد ما إذا كان يجب استخدام إطارات للأشكال في معالجة النصوص وللمستطيلات في مستندات الصور. |
| [MarkNestedContent](../../groupdocs.comparison.options/compareoptions/marknestedcontent) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب تعليم عناصر الأطفال للعنصر المحذوف أو المُدرَج كحذف أو إدراج. |
| [OriginalSize](../../groupdocs.comparison.options/compareoptions/originalsize) { get; set; } | يحصل أو يعيّن الأحجام الأصلية للمستندات المقارنة. |
| [PagesSetup](../../groupdocs.comparison.options/pdfcompareoptions/pagessetup) { get; set; } | يحصل أو يعيّن نطاق الصفحات للمقارنة. عندما تكون القيمة null، يتم مقارنة جميع الصفحات. |
| [PaperSize](../../groupdocs.comparison.options/compareoptions/papersize) { get; set; } | يحصل أو يعيّن حجم ورق المستند الناتج. |
| [PasswordSaveOption](../../groupdocs.comparison.options/compareoptions/passwordsaveoption) { get; set; } | يحصل أو يعيّن خيار حفظ كلمة المرور. |
| [SensitivityOfComparison](../../groupdocs.comparison.options/compareoptions/sensitivityofcomparison) { get; set; } | يحصل أو يعيّن حساسية المقارنة. |
| [SensitivityOfComparisonForTables](../../groupdocs.comparison.options/compareoptions/sensitivityofcomparisonfortables) { get; set; } | يحصل أو يعيّن حساسية المقارنة للجداول. |
| [ShowDeletedContent](../../groupdocs.comparison.options/compareoptions/showdeletedcontent) { get; set; } | يحدد ما إذا كان يجب إظهار المكونات المحذوفة في المستند الناتج أم لا. |
| [ShowInsertedContent](../../groupdocs.comparison.options/compareoptions/showinsertedcontent) { get; set; } | يحدد ما إذا كان يجب إظهار المكونات المُدرَجة في المستند الناتج أم لا. |
| [ShowOnlyChanged](../../groupdocs.comparison.options/compareoptions/showonlychanged) { get; set; } | تحكم لتمكين عرض العناصر المتغيّرة فقط. |
| [ShowOnlySummaryPage](../../groupdocs.comparison.options/compareoptions/showonlysummarypage) { get; set; } | يحدد ما إذا كان يجب ترك صفحة واحدة فقط في المستند الناتج تحتوي على إحصائيات التغييرات المكتشفة في المستند الناتج أم لا. |
| [UserMasterPath](../../groupdocs.comparison.options/compareoptions/usermasterpath) { get; set; } | مسار قالب الماستر للمستخدم للرسوم التخطيطية. |
| [WordsSeparatorChars](../../groupdocs.comparison.options/compareoptions/wordsseparatorchars) { set; } | يحصل أو يضبط مصفوفة من الفواصل لتقسيم النص إلى كلمات. |

### انظر أيضًا

* class [CompareOptions](../compareoptions)
* namespace [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldoccmd لـ GroupDocs.Comparison.dll -->
