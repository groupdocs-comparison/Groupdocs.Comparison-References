---
title: "LoadOptions"
second_title: "GroupDocs.Comparison per .NET Riferimento API"
description: "Consente di specificare opzioni aggiuntive durante il caricamento di un documento."
type: docs
weight: 300
url: /it/net/groupdocs.comparison.options/loadoptions/
---
## LoadOptions class

Consente di specificare opzioni aggiuntive durante il caricamento di un documento.

```csharp
public class LoadOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [LoadOptions](loadoptions)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [FileType](../../groupdocs.comparison.options/loadoptions/filetype) { get; set; } | Imposta manualmente il tipo di file per il confronto per sovrascrivere il rilevamento automatico del tipo di file. |
| [FontDirectories](../../groupdocs.comparison.options/loadoptions/fontdirectories) { get; set; } | Elenco delle directory dei font da caricare. |
| [LoadText](../../groupdocs.comparison.options/loadoptions/loadtext) { get; set; } | Indica che le stringhe passate sono testo di confronto, non percorsi di file (solo per il confronto di testo). |
| [Password](../../groupdocs.comparison.options/loadoptions/password) { get; set; } | Password del documento. |
| [SkipExternalResources](../../groupdocs.comparison.options/loadoptions/skipexternalresources) { get; set; } | Disabilita il caricamento di tutte le risorse esterne (ad es. immagini referenziate da un URL remoto) eccetto [`WhitelistedResources`](./whitelistedresources). |
| [WhitelistedResources](../../groupdocs.comparison.options/loadoptions/whitelistedresources) { get; set; } | L'elenco dei frammenti URL corrispondenti alle risorse esterne che devono essere caricate quando [`SkipExternalResources`](./skipexternalresources) è impostato su `true`. |

### Vedi anche

* namespace [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.Comparison.dll -->
