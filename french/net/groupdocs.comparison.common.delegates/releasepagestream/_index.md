---
title: "ReleasePageStream"
second_title: "GroupDocs.Comparison pour .NET API Reference"
description: "Délégué qui définit la méthode pour libérer le flux d'aperçu de page de sortie utilisé par PreviewOptions../groupdocs.comparison.options/previewoptions."
type: docs
weight: 30
url: /fr/net/groupdocs.comparison.common.delegates/releasepagestream/
---
## ReleasePageStream delegate

Délégué qui définit la méthode pour libérer le flux d'aperçu de page de sortie utilisé par [`PreviewOptions`](../../groupdocs.comparison.options/previewoptions).

```csharp
public delegate void ReleasePageStream(int pageNumber, Stream pageStream);
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | Le nombre de pages prévisualisées. |
| pageStream | Stream | Le flux de page à libérer. |

### Voir aussi

* namespace [GroupDocs.Comparison.Common.Delegates](../../groupdocs.comparison.common.delegates)
* assembly [GroupDocs.Comparison](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Comparison.dll -->
