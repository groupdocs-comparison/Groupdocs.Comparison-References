---
title: "RevisionHandler"
second_title: "GroupDocs.Comparison pour .NET API Reference"
description: "Représente la classe principale qui contrôle la gestion des révisions."
type: docs
weight: 540
url: /fr/net/groupdocs.comparison.words.revision/revisionhandler/
---
## RevisionHandler class

Représente la classe principale qui contrôle la gestion des révisions.

```csharp
public sealed class RevisionHandler : IDisposable
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [RevisionHandler](revisionhandler#constructor)(Stream) | Initialise une nouvelle instance de la classe [`RevisionHandler`](../revisionhandler) avec un flux de fichier contenant des révisions. |
| [RevisionHandler](revisionhandler#constructor_2)(string) | Initialise une nouvelle instance de la classe [`RevisionHandler`](../revisionhandler) avec le chemin du fichier contenant des révisions. |
| [RevisionHandler](revisionhandler#constructor_1)(Stream, bool) | Initialise une nouvelle instance de la classe [`RevisionHandler`](../revisionhandler) avec un flux de fichier contenant des révisions et un contrôle explicite de la propriété du flux. |

## Méthodes

| Nom | Description |
| --- | --- |
| [ApplyRevisionChanges](../../groupdocs.comparison.words.revision/revisionhandler/applyrevisionchanges#applyrevisionchanges)(ApplyRevisionOptions) | Traite les modifications des révisions et les applique au même fichier dont les révisions proviennent. |
| [ApplyRevisionChanges](../../groupdocs.comparison.words.revision/revisionhandler/applyrevisionchanges#applyrevisionchanges_1)(Stream, ApplyRevisionOptions) | Traite les modifications des révisions et le résultat est écrit dans le flux du document. |
| [ApplyRevisionChanges](../../groupdocs.comparison.words.revision/revisionhandler/applyrevisionchanges#applyrevisionchanges_2)(string, ApplyRevisionOptions) | Traite les modifications des révisions, et le résultat est écrit dans le fichier spécifié par son chemin. |
| [Dispose](../../groupdocs.comparison.words.revision/revisionhandler/dispose)() | Libère les ressources. |
| [GetRevisions](../../groupdocs.comparison.words.revision/revisionhandler/getrevisions)() | Obtient la liste de toutes les révisions. |

### Voir aussi

* namespace [GroupDocs.Comparison.Words.Revision](../../groupdocs.comparison.words.revision)
* assembly [GroupDocs.Comparison](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Comparison.dll -->
