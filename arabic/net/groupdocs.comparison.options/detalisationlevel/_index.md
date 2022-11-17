---
title: DetalisationLevel
second_title: GroupDocs.Comparison لمرجع .NET API
description: يحدد مستوى تفاصيل المقارنة .
type: docs
weight: 220
url: /ar/net/groupdocs.comparison.options/detalisationlevel/
---
## DetalisationLevel enumeration

يحدد مستوى تفاصيل المقارنة .

```csharp
public enum DetalisationLevel
```

### قيم

| اسم | قيمة | وصف |
| --- | --- | --- |
| Low | `0` | مستوى منخفض. يوفر أفضل مقارنة للسرعة مع التضحية بجودة المقارنة. يتم إجراء المقارنة لكل كلمة. |
| Middle | `1` | المستوى المتوسط. حل وسط معقول بين سرعة المقارنة والجودة. يتم إجراء المقارنة لكل حرف ، ولكن يتم تجاهل حالة الأحرف وعدد المسافات. |
| High | `2` | مستوى عال. أفضل جودة مقارنة ، ولكن أقل سرعة . يتم إجراء المقارنة لكل حرف مع مراعاة عدد الأحرف والمسافات. |

### أنظر أيضا

* مساحة الاسم [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* المجسم [GroupDocs.Comparison](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Comparison.dll -->