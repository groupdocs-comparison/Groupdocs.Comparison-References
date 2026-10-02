---
title: "PdfCompareOptions.ComparisonDisplayMode"
second_title: "GroupDocs.Comparison för .NET API-referens"
description: "Styr hur PDF-jämförelsens resultatsdokument läggs upp."
type: docs
weight: 370
url: /sv/net/groupdocs.comparison.options/pdfcompareoptions.comparisondisplaymode/
---
## PdfCompareOptions.ComparisonDisplayMode enumeration

Styr hur PDF-jämförelsens resultatsdokument läggs upp.

```csharp
public enum ComparisonDisplayMode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Inline | `0` | Standardläge. Skapar ett enda sammanslaget PDF-dokument där borttaget innehåll markeras med en färg och infogat innehåll med en annan. Både käll- och mål-innehåll samexisterar på samma sidor, vilket kan orsaka överlappning när dokumenten skiljer sig avsevärt. |
| SideBySide | `1` | Varje resultatsida visar en källsida och dess motsvarande målsida sida vid sida. Borttagningar visas till vänster (källsidan) och insättningar till höger (målsidan). Innehållet från de två dokumenten överlappar aldrig, vilket gör detta läge lämpligt när dokumenten skiljer sig kraftigt. |
| Interleaved | `2` | Skapar ett dokument med alternerande sidor: udda sidnummer kommer från källdokumentet (visar borttagningar) och jämna sidnummer kommer från måldokumentet (visar insättningar). Öppna resultatet i en PDF‑visare med "Tvåsidig vy" aktiverad för att se varje käll‑/målpaar sida vid sida på skärmen. Precis som SideBySide förhindrar detta läge innehållsöverlappning och är bäst lämpat för kraftigt olika dokument. |

### Se även

* class [PdfCompareOptions](../pdfcompareoptions)
* namespace [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../)

<!-- DO NOT EDIT: genererad av xmldocmd för GroupDocs.Comparison.dll -->
