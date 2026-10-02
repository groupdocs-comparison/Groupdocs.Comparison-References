---
title: "DetalisationLevel"
second_title: "Справочник API GroupDocs.Comparison для .NET"
description: "Указывает уровень детализации сравнения."
type: docs
weight: 230
url: /ru/net/groupdocs.comparison.options/detalisationlevel/
---
## DetalisationLevel enumeration

Указывает уровень детализации сравнения.

```csharp
public enum DetalisationLevel
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Low | `0` | Низкий уровень. Обеспечивает наилучшую скорость сравнения за счёт качества сравнения. Сравнение выполняется по словам. |
| Middle | `1` | Средний уровень. Разумный компромисс между скоростью сравнения и качеством. Сравнение выполняется по символам, но без учёта регистра символов и количества пробелов. |
| High | `2` | Высокий уровень. Наилучшее качество сравнения, но самая низкая скорость. Сравнение выполняется по символам с учётом регистра символов и количества пробелов. |

### См. также

* namespace [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Comparison.dll -->
