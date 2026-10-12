---
title: "ChangeInfo"
second_title: "مرجع API لـ GroupDocs.Comparison لـ .NET"
description: "يمثل معلومات حول التغيير."
type: docs
weight: 460
url: /ar/net/groupdocs.comparison.result/changeinfo/
---
## ChangeInfo class

يمثل معلومات حول التغيير.

```csharp
public class ChangeInfo
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [ChangeInfo](changeinfo)() | المُنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Authors](../../groupdocs.comparison.result/changeinfo/authors) { get; set; } | قائمة المؤلفين. |
| [Box](../../groupdocs.comparison.result/changeinfo/box) { get; set; } | إحداثيات العنصر المتغير. |
| [Column](../../groupdocs.comparison.result/changeinfo/column) { get; set; } | فهرس العمود صفر-مبني للخلية المتغيرة. يُملأ لمقارن الخلايا (XLSX, CSV, ODS, إلخ)، وإلا يكون null. |
| [ColumnHeader](../../groupdocs.comparison.result/changeinfo/columnheader) { get; set; } | نص عنوان العمود مأخوذ من الصف الأول من ورقة العمل للعمود المقابل. يُملأ لمقارن الخلايا عندما يحتوي الصف الأول على قيم العناوين، وإلا يكون null. |
| [ComparisonAction](../../groupdocs.comparison.result/changeinfo/comparisonaction) { get; set; } | الإجراء (قبول أو رفض). هذا الحقل يخبر المقارنة بما يجب فعله بهذا التغيير. |
| [ComponentType](../../groupdocs.comparison.result/changeinfo/componenttype) { get; set; } | نوع المكوّن المتغيّر. |
| [Id](../../groupdocs.comparison.result/changeinfo/id) { get; set; } | معرف التغيير. |
| [PageInfo](../../groupdocs.comparison.result/changeinfo/pageinfo) { get; set; } | الصفحة التي تم وضع التغيير الحالي فيها. |
| [Row](../../groupdocs.comparison.result/changeinfo/row) { get; set; } | فهرس الصف صفر-مبني للخلية المتغيرة. يُملأ لمقارن الخلايا (XLSX, CSV, ODS, إلخ)، وإلا يكون null. |
| [SourceText](../../groupdocs.comparison.result/changeinfo/sourcetext) { get; set; } | النص المتغيّر في المستند المصدر. |
| [StyleChanges](../../groupdocs.comparison.result/changeinfo/stylechanges) { get; set; } | مصفوفة تغييرات النمط. |
| [TargetText](../../groupdocs.comparison.result/changeinfo/targettext) { get; set; } | النص المتغيّر في المستند الهدف. |
| [Text](../../groupdocs.comparison.result/changeinfo/text) { get; set; } | قيمة النص للتغيير. |
| [Type](../../groupdocs.comparison.result/changeinfo/type) { get; } | نوع التغيير. |

### انظر أيضًا

* namespace [GroupDocs.Comparison.Result](../../groupdocs.comparison.result)
* assembly [GroupDocs.Comparison](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldoccmd لـ GroupDocs.Comparison.dll -->
