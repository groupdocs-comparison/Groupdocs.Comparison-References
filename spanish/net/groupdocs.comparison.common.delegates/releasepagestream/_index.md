---
title: "ReleasePageStream"
second_title: "Referencia de API de GroupDocs.Comparison para .NET"
description: "Delegado que define el método para liberar el flujo de vista previa de página de salida utilizado por PreviewOptions../groupdocs.comparison.options/previewoptions."
type: docs
weight: 30
url: /es/net/groupdocs.comparison.common.delegates/releasepagestream/
---
## ReleasePageStream delegate

Delegado que define el método para liberar el flujo de vista previa de página de salida utilizado por [`PreviewOptions`](../../groupdocs.comparison.options/previewoptions).

```csharp
public delegate void ReleasePageStream(int pageNumber, Stream pageStream);
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageNumber | Int32 | El número de la página previsualizada. |
| pageStream | Stream | El flujo de página a liberar. |

### Ver también

* namespace [GroupDocs.Comparison.Common.Delegates](../../groupdocs.comparison.common.delegates)
* assembly [GroupDocs.Comparison](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Comparison.dll -->
