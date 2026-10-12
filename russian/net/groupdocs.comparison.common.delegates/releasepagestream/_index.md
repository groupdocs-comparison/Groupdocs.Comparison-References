---
title: "ReleasePageStream"
second_title: "Справочник API GroupDocs.Comparison для .NET"
description: "Делегат, определяющий метод освобождения потока предварительного просмотра выходной страницы, используемого PreviewOptions../groupdocs.comparison.options/previewoptions."
type: docs
weight: 30
url: /ru/net/groupdocs.comparison.common.delegates/releasepagestream/
---
## ReleasePageStream delegate

Делегат, определяющий метод освобождения потока предварительного просмотра выходной страницы, используемого [`PreviewOptions`](../../groupdocs.comparison.options/previewoptions).

```csharp
public delegate void ReleasePageStream(int pageNumber, Stream pageStream);
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumber | Int32 | Количество предварительно просмотренных страниц. |
| pageStream | Stream | Поток страницы для освобождения. |

### См. также

* namespace [GroupDocs.Comparison.Common.Delegates](../../groupdocs.comparison.common.delegates)
* assembly [GroupDocs.Comparison](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Comparison.dll -->
