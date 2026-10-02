---
title: "RevisionHandler"
second_title: "GroupDocs.Comparison per .NET Riferimento API"
description: "Rappresenta la classe principale che gestisce il trattamento delle revisioni."
type: docs
weight: 540
url: /it/net/groupdocs.comparison.words.revision/revisionhandler/
---
## RevisionHandler class

Rappresenta la classe principale che gestisce il trattamento delle revisioni.

```csharp
public sealed class RevisionHandler : IDisposable
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [RevisionHandler](revisionhandler#constructor)(Stream) | Inizializza una nuova istanza della classe [`RevisionHandler`](../revisionhandler) con un flusso di file contenente revisioni. |
| [RevisionHandler](revisionhandler#constructor_2)(string) | Inizializza una nuova istanza della classe [`RevisionHandler`](../revisionhandler) con il percorso del file contenente revisioni. |
| [RevisionHandler](revisionhandler#constructor_1)(Stream, bool) | Inizializza una nuova istanza della classe [`RevisionHandler`](../revisionhandler) con un flusso di file contenente revisioni e controllo esplicito della proprietà del flusso. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [ApplyRevisionChanges](../../groupdocs.comparison.words.revision/revisionhandler/applyrevisionchanges#applyrevisionchanges)(ApplyRevisionOptions) | Elabora le modifiche nelle revisioni e le applica allo stesso file da cui sono state prese le revisioni. |
| [ApplyRevisionChanges](../../groupdocs.comparison.words.revision/revisionhandler/applyrevisionchanges#applyrevisionchanges_1)(Stream, ApplyRevisionOptions) | Elabora le modifiche nelle revisioni e il risultato viene scritto nel flusso del documento. |
| [ApplyRevisionChanges](../../groupdocs.comparison.words.revision/revisionhandler/applyrevisionchanges#applyrevisionchanges_2)(string, ApplyRevisionOptions) | Elabora le modifiche nelle revisioni e il risultato viene scritto nel file specificato per percorso. |
| [Dispose](../../groupdocs.comparison.words.revision/revisionhandler/dispose)() | Rilascia le risorse. |
| [GetRevisions](../../groupdocs.comparison.words.revision/revisionhandler/getrevisions)() | Ottiene l'elenco di tutte le revisioni. |

### Vedi anche

* namespace [GroupDocs.Comparison.Words.Revision](../../groupdocs.comparison.words.revision)
* assembly [GroupDocs.Comparison](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.Comparison.dll -->
