---
title: "LoadOptions"
second_title: "GroupDocs.Comparison für .NET API-Referenz"
description: "Ermöglicht das Angeben zusätzlicher Optionen beim Laden eines Dokuments."
type: docs
weight: 300
url: /de/net/groupdocs.comparison.options/loadoptions/
---
## LoadOptions class

Ermöglicht das Angeben zusätzlicher Optionen beim Laden eines Dokuments.

```csharp
public class LoadOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [LoadOptions](loadoptions)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [FileType](../../groupdocs.comparison.options/loadoptions/filetype) { get; set; } | Setzen Sie den Dateityp für den Vergleich manuell, um die automatische Dateityperkennung zu überschreiben. |
| [FontDirectories](../../groupdocs.comparison.options/loadoptions/fontdirectories) { get; set; } | Liste der zu ladenden Schriftartverzeichnisse. |
| [LoadText](../../groupdocs.comparison.options/loadoptions/loadtext) { get; set; } | Gibt an, dass die übergebenen Zeichenketten Vergleichstext sind und keine Dateipfade (nur für Textvergleich). |
| [Password](../../groupdocs.comparison.options/loadoptions/password) { get; set; } | Passwort des Dokuments. |
| [SkipExternalResources](../../groupdocs.comparison.options/loadoptions/skipexternalresources) { get; set; } | Deaktiviert das Laden aller externen Ressourcen (z. B. Bilder, die über eine entfernte URL referenziert werden) außer [`WhitelistedResources`](./whitelistedresources). |
| [WhitelistedResources](../../groupdocs.comparison.options/loadoptions/whitelistedresources) { get; set; } | Die Liste der URL‑Fragmente, die externen Ressourcen entsprechen und geladen werden sollen, wenn [`SkipExternalResources`](./skipexternalresources) auf `true` gesetzt ist. |

### Siehe auch

* namespace [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.Comparison.dll -->
