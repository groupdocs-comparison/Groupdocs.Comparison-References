---
title: "LoadOptions"
second_title: "مرجع API لـ GroupDocs.Comparison لـ .NET"
description: "يسمح بتحديد خيارات إضافية عند تحميل مستند."
type: docs
weight: 300
url: /ar/net/groupdocs.comparison.options/loadoptions/
---
## LoadOptions class

يسمح بتحديد خيارات إضافية عند تحميل مستند.

```csharp
public class LoadOptions
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [LoadOptions](loadoptions)() | المُنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [FileType](../../groupdocs.comparison.options/loadoptions/filetype) { get; set; } | قم بتعيين نوع الملف للمقارنة يدويًا لتجاوز الكشف التلقائي عن نوع الملف. |
| [FontDirectories](../../groupdocs.comparison.options/loadoptions/fontdirectories) { get; set; } | قائمة دلائل الخطوط للتحميل. |
| [LoadText](../../groupdocs.comparison.options/loadoptions/loadtext) { get; set; } | يشير إلى أن السلاسل الممررة هي نص مقارنة، وليس مسارات ملفات (للمقارنة النصية فقط). |
| [Password](../../groupdocs.comparison.options/loadoptions/password) { get; set; } | كلمة مرور المستند. |
| [SkipExternalResources](../../groupdocs.comparison.options/loadoptions/skipexternalresources) { get; set; } | يعطل تحميل جميع الموارد الخارجية (مثل الصور المشار إليها عبر URL بعيد) باستثناء [`WhitelistedResources`](./whitelistedresources). |
| [WhitelistedResources](../../groupdocs.comparison.options/loadoptions/whitelistedresources) { get; set; } | قائمة مقاطع URL التي تتطابق مع الموارد الخارجية التي يجب تحميلها عندما يتم تعيين [`SkipExternalResources`](./skipexternalresources) إلى `true`. |

### انظر أيضًا

* namespace [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldoccmd لـ GroupDocs.Comparison.dll -->
