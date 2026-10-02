---
title: "ReleasePageStream"
second_title: "GroupDocs.Comparison per .NET Riferimento API"
description: "Delegate che definisce il metodo per rilasciare lo stream di anteprima della pagina di output utilizzato da PreviewOptions../groupdocs.comparison.options/previewoptions."
type: docs
weight: 30
url: /it/net/groupdocs.comparison.common.delegates/releasepagestream/
---
## ReleasePageStream delegate

Delegate che definisce il metodo per rilasciare lo stream di anteprima della pagina di output utilizzato da [`PreviewOptions`](../../groupdocs.comparison.options/previewoptions).

```csharp
public delegate void ReleasePageStream(int pageNumber, Stream pageStream);
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageNumber | Int32 | Il numero di pagina visualizzata in anteprima. |
| pageStream | Stream | Lo stream della pagina da rilasciare. |

### Vedi anche

* namespace [GroupDocs.Comparison.Common.Delegates](../../groupdocs.comparison.common.delegates)
* assembly [GroupDocs.Comparison](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.Comparison.dll -->
