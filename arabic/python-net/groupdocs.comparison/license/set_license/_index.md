---
title: "set_license طريقة"
second_title: "مراجع API لـ GroupDocs.Comparison للـ Python عبر .NET"
description: 
type: docs
url: /ar/python-net/groupdocs.comparison/license/set_license/
is_root: false
weight: 1010
---


## set_license {#license_source}

تطبيق ترخيص على العملية الحالية.

```python
def set_license(self, license_source):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| license_source |  | إما مسار سلسلة إلى ملف ``.lic`` أو كائن شبيه بالملف قابل للقراءة يُنتج بايتات الترخيص. تُكتب مدخلات شبيهة بالملف إلى ملف مؤقت قبل تمريرها إلى الجسر. |

| الاستثناءات | الوصف |
| :- | :- |
| `TypeError` | إذا لم يكن ``license_source`` مسار سلسلة ولا كائن شبيه بالملف قابل للقراءة. |

### انظر أيضًا
* class [`License`](/comparison/python-net/groupdocs.comparison/license/)
