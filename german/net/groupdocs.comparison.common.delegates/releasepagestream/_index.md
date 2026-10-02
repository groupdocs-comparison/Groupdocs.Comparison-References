---
title: "ReleasePageStream"
second_title: "GroupDocs.Comparison für .NET API-Referenz"
description: "Delegat, der die Methode zum Freigeben des Ausgabeseiten-Vorschau-Streams definiert, der von PreviewOptions../groupdocs.comparison.options/previewoptions verwendet wird."
type: docs
weight: 30
url: /de/net/groupdocs.comparison.common.delegates/releasepagestream/
---
## ReleasePageStream delegate

Delegat, der die Methode zum Freigeben des Ausgabeseiten-Vorschau-Streams definiert, der von [`PreviewOptions`](../../groupdocs.comparison.options/previewoptions) verwendet wird.

```csharp
public delegate void ReleasePageStream(int pageNumber, Stream pageStream);
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageNumber | Int32 | Die Anzahl der vorschaugezeigten Seite. |
| pageStream | Stream | Der Seiten-Stream zum Freigeben. |

### Siehe auch

* namespace [GroupDocs.Comparison.Common.Delegates](../../groupdocs.comparison.common.delegates)
* assembly [GroupDocs.Comparison](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.Comparison.dll -->
