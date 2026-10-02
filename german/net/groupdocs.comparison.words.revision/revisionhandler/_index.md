---
title: "RevisionHandler"
second_title: "GroupDocs.Comparison für .NET API-Referenz"
description: "Stellt die Hauptklasse dar, die die Revisionenverwaltung steuert."
type: docs
weight: 540
url: /de/net/groupdocs.comparison.words.revision/revisionhandler/
---
## RevisionHandler class

Stellt die Hauptklasse dar, die die Revisionenverwaltung steuert.

```csharp
public sealed class RevisionHandler : IDisposable
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [RevisionHandler](revisionhandler#constructor)(Stream) | Initialisiert eine neue Instanz der Klasse [`RevisionHandler`](../revisionhandler) mit einem Dateistream, der Revisionen enthält. |
| [RevisionHandler](revisionhandler#constructor_2)(string) | Initialisiert eine neue Instanz der Klasse [`RevisionHandler`](../revisionhandler) mit dem Pfad zur Datei mit Revisionen. |
| [RevisionHandler](revisionhandler#constructor_1)(Stream, bool) | Initialisiert eine neue Instanz der Klasse [`RevisionHandler`](../revisionhandler) mit einem Dateistream, der Revisionen enthält, und expliziter Kontrolle des Stream-Eigentums. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [ApplyRevisionChanges](../../groupdocs.comparison.words.revision/revisionhandler/applyrevisionchanges#applyrevisionchanges)(ApplyRevisionOptions) | Verarbeitet Änderungen in Revisionen und wendet sie auf dieselbe Datei an, aus der die Revisionen entnommen wurden. |
| [ApplyRevisionChanges](../../groupdocs.comparison.words.revision/revisionhandler/applyrevisionchanges#applyrevisionchanges_1)(Stream, ApplyRevisionOptions) | Verarbeitet Änderungen in Revisionen und das Ergebnis wird in den Dokumentenstream geschrieben. |
| [ApplyRevisionChanges](../../groupdocs.comparison.words.revision/revisionhandler/applyrevisionchanges#applyrevisionchanges_2)(string, ApplyRevisionOptions) | Verarbeitet Änderungen in Revisionen, und das Ergebnis wird in die angegebene Datei nach Pfad geschrieben. |
| [Dispose](../../groupdocs.comparison.words.revision/revisionhandler/dispose)() | Gibt Ressourcen frei. |
| [GetRevisions](../../groupdocs.comparison.words.revision/revisionhandler/getrevisions)() | Ermittelt die Liste aller Revisionen. |

### Siehe auch

* namespace [GroupDocs.Comparison.Words.Revision](../../groupdocs.comparison.words.revision)
* assembly [GroupDocs.Comparison](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.Comparison.dll -->
