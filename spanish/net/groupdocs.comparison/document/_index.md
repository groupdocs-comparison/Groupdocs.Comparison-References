---
title: "Documento"
second_title: "Referencia de API de GroupDocs.Comparison para .NET"
description: "Representa el documento comparado."
type: docs
weight: 120
url: /es/net/groupdocs.comparison/document/
---
## Document class

Representa el documento comparado.

```csharp
public class Document
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Document](document#constructor)(Stream) | Inicializa una nueva instancia de la clase [`Document`](../document). |
| [Document](document#constructor_2)(string) | Inicializa una nueva instancia de la clase [`Document`](../document). |
| [Document](document#constructor_1)(Stream, string) | Inicializa una nueva instancia de la clase [`Document`](../document). |
| [Document](document#constructor_3)(string, string) | Inicializa una nueva instancia de la clase [`Document`](../document). |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Changes](../../groupdocs.comparison/document/changes) { get; set; } | Lista de cambios. Contiene una descripción extensa sobre el tipo de cambio, posición, contenido, etc. |
| [FileType](../../groupdocs.comparison/document/filetype) { get; } | Tipo de archivo del documento. |
| [Name](../../groupdocs.comparison/document/name) { get; set; } | Nombre del documento. |
| [Password](../../groupdocs.comparison/document/password) { get; } | Contraseña del documento. |
| [Stream](../../groupdocs.comparison/document/stream) { get; } | Secuencia del documento. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GeneratePreview](../../groupdocs.comparison/document/generatepreview)(PreviewOptions) | Genera una vista previa de las páginas del documento. |
| [GetDocumentInfo](../../groupdocs.comparison/document/getdocumentinfo)() | Obtiene información sobre el documento: tipo de documento, número de páginas, tamaños de página, etc. |

### Ver también

* namespace [GroupDocs.Comparison](../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Comparison.dll -->
