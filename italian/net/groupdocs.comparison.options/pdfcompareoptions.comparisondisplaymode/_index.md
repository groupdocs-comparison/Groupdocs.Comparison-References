---
title: "PdfCompareOptions.ComparisonDisplayMode"
second_title: "GroupDocs.Comparison per .NET Riferimento API"
description: "Controlla come è disposto il documento risultato del confronto PDF."
type: docs
weight: 370
url: /it/net/groupdocs.comparison.options/pdfcompareoptions.comparisondisplaymode/
---
## PdfCompareOptions.ComparisonDisplayMode enumeration

Controlla come è disposto il documento risultato del confronto PDF.

```csharp
public enum ComparisonDisplayMode
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Inline | `0` | Modalità predefinita. Produce un unico documento PDF unito in cui il contenuto eliminato è evidenziato in un colore e il contenuto inserito in un altro. Sia il contenuto di origine sia quello di destinazione coesistono nelle stesse pagine, il che può causare sovrapposizioni quando i documenti differiscono in modo significativo. |
| SideBySide | `1` | Ogni pagina di risultato mostra una pagina di origine e la sua pagina di destinazione corrispondente affiancate. Le cancellazioni appaiono a sinistra (lato origine) e le inserzioni a destra (lato destinazione). Il contenuto dei due documenti non si sovrappone mai, rendendo questa modalità adatta quando i documenti differiscono notevolmente. |
| Interleaved | `2` | Produce un documento con pagine alternate: le pagine dispari provengono dal documento di origine (mostrando le cancellazioni) e le pagine pari provengono dal documento di destinazione (mostrando le inserzioni). Apri il risultato in un visualizzatore PDF con la visualizzazione "Two Page View" abilitata per vedere ogni coppia origine/destinazione affiancata sullo schermo. Come SideBySide, questa modalità impedisce la sovrapposizione del contenuto ed è la più adatta per documenti con differenze marcate. |

### Vedi anche

* class [PdfCompareOptions](../pdfcompareoptions)
* namespace [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.Comparison.dll -->
