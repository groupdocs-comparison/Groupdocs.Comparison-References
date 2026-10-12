---
title: "RevisionHandler"
second_title: "Referencia de API de GroupDocs.Comparison para .NET"
description: "Representa la clase principal que controla el manejo de revisiones."
type: docs
weight: 540
url: /es/net/groupdocs.comparison.words.revision/revisionhandler/
---
## RevisionHandler class

Representa la clase principal que controla el manejo de revisiones.

```csharp
public sealed class RevisionHandler : IDisposable
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [RevisionHandler](revisionhandler#constructor)(Stream) | Inicializa una nueva instancia de la clase [`RevisionHandler`](../revisionhandler) con un flujo de archivo con revisiones. |
| [RevisionHandler](revisionhandler#constructor_2)(string) | Inicializa una nueva instancia de la clase [`RevisionHandler`](../revisionhandler) con la ruta al archivo con revisiones. |
| [RevisionHandler](revisionhandler#constructor_1)(Stream, bool) | Inicializa una nueva instancia de la clase [`RevisionHandler`](../revisionhandler) con un flujo de archivo con revisiones y control explícito de la propiedad del flujo. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [ApplyRevisionChanges](../../groupdocs.comparison.words.revision/revisionhandler/applyrevisionchanges#applyrevisionchanges)(ApplyRevisionOptions) | Procesa los cambios en las revisiones y los aplica al mismo archivo del que se tomaron las revisiones. |
| [ApplyRevisionChanges](../../groupdocs.comparison.words.revision/revisionhandler/applyrevisionchanges#applyrevisionchanges_1)(Stream, ApplyRevisionOptions) | Procesa los cambios en las revisiones y el resultado se escribe en el flujo del documento. |
| [ApplyRevisionChanges](../../groupdocs.comparison.words.revision/revisionhandler/applyrevisionchanges#applyrevisionchanges_2)(string, ApplyRevisionOptions) | Procesa los cambios en las revisiones, y el resultado se escribe en el archivo especificado por ruta. |
| [Dispose](../../groupdocs.comparison.words.revision/revisionhandler/dispose)() | Libera recursos. |
| [GetRevisions](../../groupdocs.comparison.words.revision/revisionhandler/getrevisions)() | Obtiene la lista de todas las revisiones. |

### Ver también

* namespace [GroupDocs.Comparison.Words.Revision](../../groupdocs.comparison.words.revision)
* assembly [GroupDocs.Comparison](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Comparison.dll -->
