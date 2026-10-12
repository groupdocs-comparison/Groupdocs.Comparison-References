---
title: "ApplyRevisionChanges"
second_title: "GroupDocs.Comparison för .NET API-referens"
description: "Bearbetar förändringar i revisioner och tillämpar dem på samma fil som revisionerna togs från."
type: docs
weight: 20
url: /sv/net/groupdocs.comparison.words.revision/revisionhandler/applyrevisionchanges/
---
## ApplyRevisionChanges(ApplyRevisionOptions) {#applyrevisionchanges}

Bearbetar förändringar i revisioner och tillämpar dem på samma fil som revisionerna togs från.

```csharp
public void ApplyRevisionChanges(ApplyRevisionOptions changes)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ändringar | ApplyRevisionOptions | Lista över ändrade revisioner |

### Se även

* class [ApplyRevisionOptions](../../applyrevisionoptions)
* class [RevisionHandler](../../revisionhandler)
* namespace [GroupDocs.Comparison.Words.Revision](../../../groupdocs.comparison.words.revision)
* assembly [GroupDocs.Comparison](../../../)

---

## ApplyRevisionChanges(string, ApplyRevisionOptions) {#applyrevisionchanges_2}

Bearbetar förändringar i revisioner, och resultatet skrivs till den angivna filen via sökväg.

```csharp
public void ApplyRevisionChanges(string filePath, ApplyRevisionOptions changes)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | Sträng | Resultatfilens sökväg |
| ändringar | ApplyRevisionOptions | Lista över ändrade revisioner |

### Se även

* class [ApplyRevisionOptions](../../applyrevisionoptions)
* class [RevisionHandler](../../revisionhandler)
* namespace [GroupDocs.Comparison.Words.Revision](../../../groupdocs.comparison.words.revision)
* assembly [GroupDocs.Comparison](../../../)

---

## ApplyRevisionChanges(Stream, ApplyRevisionOptions) {#applyrevisionchanges_1}

Bearbetar förändringar i revisioner och resultatet skrivs till dokumentströmmen.

```csharp
public void ApplyRevisionChanges(Stream document, ApplyRevisionOptions changes)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dokument | Stream | Resultatdokument |
| ändringar | ApplyRevisionOptions | Lista över ändrade revisioner |

### Se även

* class [ApplyRevisionOptions](../../applyrevisionoptions)
* class [RevisionHandler](../../revisionhandler)
* namespace [GroupDocs.Comparison.Words.Revision](../../../groupdocs.comparison.words.revision)
* assembly [GroupDocs.Comparison](../../../)

<!-- DO NOT EDIT: genererad av xmldocmd för GroupDocs.Comparison.dll -->
