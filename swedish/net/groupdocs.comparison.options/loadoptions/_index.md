---
title: "LoadOptions"
second_title: "GroupDocs.Comparison för .NET API-referens"
description: "Tillåter att ange ytterligare alternativ vid inläsning av ett dokument."
type: docs
weight: 300
url: /sv/net/groupdocs.comparison.options/loadoptions/
---
## LoadOptions class

Tillåter att ange ytterligare alternativ vid inläsning av ett dokument.

```csharp
public class LoadOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [LoadOptions](loadoptions)() | Standardkonstruktören. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [FileType](../../groupdocs.comparison.options/loadoptions/filetype) { get; set; } | Ställ in filtypen för jämförelse manuellt för att åsidosätta automatisk filtypsdetektering. |
| [FontDirectories](../../groupdocs.comparison.options/loadoptions/fontdirectories) { get; set; } | Lista över teckensnittskataloger att läsa in. |
| [LoadText](../../groupdocs.comparison.options/loadoptions/loadtext) { get; set; } | Indikerar att de överförda strängarna är jämförelsetext, inte filsökvägar (endast för textjämförelse). |
| [Password](../../groupdocs.comparison.options/loadoptions/password) { get; set; } | Dokumentets lösenord. |
| [SkipExternalResources](../../groupdocs.comparison.options/loadoptions/skipexternalresources) { get; set; } | Inaktiverar inläsning av alla externa resurser (t.ex. bilder som refereras via en fjärr‑URL) förutom [`WhitelistedResources`](./whitelistedresources). |
| [WhitelistedResources](../../groupdocs.comparison.options/loadoptions/whitelistedresources) { get; set; } | Listan över URL‑fragment som motsvarar externa resurser som ska läsas in när [`SkipExternalResources`](./skipexternalresources) är satt till `true`. |

### Se även

* namespace [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../)

<!-- DO NOT EDIT: genererad av xmldocmd för GroupDocs.Comparison.dll -->
