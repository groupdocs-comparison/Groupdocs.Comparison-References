---
title: "RevisionHandler"
second_title: "مرجع API لـ GroupDocs.Comparison لـ .NET"
description: "يمثل الفئة الرئيسية التي تتحكم في معالجة المراجعات."
type: docs
weight: 540
url: /ar/net/groupdocs.comparison.words.revision/revisionhandler/
---
## RevisionHandler class

يمثل الفئة الرئيسية التي تتحكم في معالجة المراجعات.

```csharp
public sealed class RevisionHandler : IDisposable
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [RevisionHandler](revisionhandler#constructor)(Stream) | ينشئ مثيلًا جديدًا من الفئة [`RevisionHandler`](../revisionhandler) باستخدام تدفق ملف يحتوي على مراجعات. |
| [RevisionHandler](revisionhandler#constructor_2)(string) | ينشئ مثيلًا جديدًا من الفئة [`RevisionHandler`](../revisionhandler) باستخدام المسار إلى الملف الذي يحتوي على مراجعات. |
| [RevisionHandler](revisionhandler#constructor_1)(Stream, bool) | ينشئ مثيلًا جديدًا من الفئة [`RevisionHandler`](../revisionhandler) باستخدام تدفق ملف يحتوي على مراجعات وتحكم صريح في ملكية التدفق. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [ApplyRevisionChanges](../../groupdocs.comparison.words.revision/revisionhandler/applyrevisionchanges#applyrevisionchanges)(ApplyRevisionOptions) | يعالج التغييرات في المراجعات ويطبقها على نفس الملف الذي تم أخذ المراجعات منه. |
| [ApplyRevisionChanges](../../groupdocs.comparison.words.revision/revisionhandler/applyrevisionchanges#applyrevisionchanges_1)(Stream, ApplyRevisionOptions) | يعالج التغييرات في المراجعات وتُكتب النتيجة إلى تدفق المستند. |
| [ApplyRevisionChanges](../../groupdocs.comparison.words.revision/revisionhandler/applyrevisionchanges#applyrevisionchanges_2)(string, ApplyRevisionOptions) | يعالج التغييرات في المراجعات، وتُكتب النتيجة إلى الملف المحدد بالمسار. |
| [Dispose](../../groupdocs.comparison.words.revision/revisionhandler/dispose)() | يطلق الموارد. |
| [GetRevisions](../../groupdocs.comparison.words.revision/revisionhandler/getrevisions)() | يحصل على قائمة بجميع المراجعات. |

### انظر أيضًا

* namespace [GroupDocs.Comparison.Words.Revision](../../groupdocs.comparison.words.revision)
* assembly [GroupDocs.Comparison](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldoccmd لـ GroupDocs.Comparison.dll -->
