---
title: "RevisionHandler"
second_title: "GroupDocs.Comparison för .NET API-referens"
description: "Representerar huvudklassen som styr hantering av revisioner."
type: docs
weight: 540
url: /sv/net/groupdocs.comparison.words.revision/revisionhandler/
---
## RevisionHandler class

Representerar huvudklassen som styr hantering av revisioner.

```csharp
public sealed class RevisionHandler : IDisposable
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [RevisionHandler](revisionhandler#constructor)(Stream) | Initierar en ny instans av [`RevisionHandler`](../revisionhandler)-klassen med en filström med revisioner. |
| [RevisionHandler](revisionhandler#constructor_2)(string) | Initierar en ny instans av [`RevisionHandler`](../revisionhandler)-klassen med sökvägen till filen med revisioner. |
| [RevisionHandler](revisionhandler#constructor_1)(Stream, bool) | Initierar en ny instans av [`RevisionHandler`](../revisionhandler)-klassen med en filström med revisioner och explicit kontroll av strömmens ägandeskap. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [ApplyRevisionChanges](../../groupdocs.comparison.words.revision/revisionhandler/applyrevisionchanges#applyrevisionchanges)(ApplyRevisionOptions) | Bearbetar förändringar i revisioner och tillämpar dem på samma fil som revisionerna togs från. |
| [ApplyRevisionChanges](../../groupdocs.comparison.words.revision/revisionhandler/applyrevisionchanges#applyrevisionchanges_1)(Stream, ApplyRevisionOptions) | Bearbetar förändringar i revisioner och resultatet skrivs till dokumentströmmen. |
| [ApplyRevisionChanges](../../groupdocs.comparison.words.revision/revisionhandler/applyrevisionchanges#applyrevisionchanges_2)(string, ApplyRevisionOptions) | Bearbetar förändringar i revisioner, och resultatet skrivs till den angivna filen via sökväg. |
| [Dispose](../../groupdocs.comparison.words.revision/revisionhandler/dispose)() | Frigör resurser. |
| [GetRevisions](../../groupdocs.comparison.words.revision/revisionhandler/getrevisions)() | Hämtar lista över alla revisioner. |

### Se även

* namespace [GroupDocs.Comparison.Words.Revision](../../groupdocs.comparison.words.revision)
* assembly [GroupDocs.Comparison](../../)

<!-- DO NOT EDIT: genererad av xmldocmd för GroupDocs.Comparison.dll -->
