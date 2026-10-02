---
title: "RevisionHandler"
second_title: "مرجع API لـ GroupDocs.Comparison لـ .NET"
description: "يُنشئ نسخة جديدة من الفئة RevisionHandlergroupdocs.comparison.words.revision/revisionhandler باستخدام المسار إلى الملف الذي يحتوي على المراجعات."
type: docs
weight: 10
url: /ar/net/groupdocs.comparison.words.revision/revisionhandler/revisionhandler/
---
## RevisionHandler(string) {#constructor_2}

يُنشئ نسخة جديدة من الفئة [`RevisionHandler`](../../revisionhandler) باستخدام المسار إلى الملف الذي يحتوي على المراجعات.

```csharp
public RevisionHandler(string filePath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| مسار الملف | String | مسار الملف |

### انظر أيضًا

* class [RevisionHandler](../../revisionhandler)
* namespace [GroupDocs.Comparison.Words.Revision](../../../groupdocs.comparison.words.revision)
* assembly [GroupDocs.Comparison](../../../)

---

## RevisionHandler(Stream) {#constructor}

يُنشئ نسخة جديدة من الفئة [`RevisionHandler`](../../revisionhandler) باستخدام تدفق ملف يحتوي على المراجعات.

```csharp
public RevisionHandler(Stream file)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| file | Stream | تدفق مستند المصدر |

### انظر أيضًا

* class [RevisionHandler](../../revisionhandler)
* namespace [GroupDocs.Comparison.Words.Revision](../../../groupdocs.comparison.words.revision)
* assembly [GroupDocs.Comparison](../../../)

---

## RevisionHandler(Stream, bool) {#constructor_1}

يُنشئ نسخة جديدة من الفئة [`RevisionHandler`](../../revisionhandler) باستخدام تدفق ملف يحتوي على المراجعات والتحكم الصريح في ملكية التدفق.

```csharp
public RevisionHandler(Stream file, bool leaveOpen)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| file | Stream | تدفق مستند المصدر |
| leaveOpen | Boolean | عند كونها true، يحتفظ المستدعي بملكية *file* ويتحمل مسؤولية التخلص منها. عند كونها false (الافتراضي)، [`Dispose`](../dispose) يغلق الدفق. |

### انظر أيضًا

* class [RevisionHandler](../../revisionhandler)
* namespace [GroupDocs.Comparison.Words.Revision](../../../groupdocs.comparison.words.revision)
* assembly [GroupDocs.Comparison](../../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldoccmd لـ GroupDocs.Comparison.dll -->
