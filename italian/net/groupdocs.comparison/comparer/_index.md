---
title: "Comparer"
second_title: "GroupDocs.Comparison per .NET Riferimento API"
description: "Rappresenta la classe principale che controlla il processo di confronto dei documenti."
type: docs
weight: 100
url: /it/net/groupdocs.comparison/comparer/
---
## Comparer class

Rappresenta la classe principale che controlla il processo di confronto dei documenti.

```csharp
public sealed class Comparer : IDisposable
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Comparer](comparer#constructor)(Stream) | Inizializza una nuova istanza della classe [`Comparer`](../comparer) con lo stream del documento sorgente. |
| [Comparer](comparer#constructor_4)(string) | Inizializza una nuova istanza della classe [`Comparer`](../comparer) con il percorso del file sorgente. |
| [Comparer](comparer#constructor_1)(Stream, ComparerSettings) | Inizializza una nuova istanza della classe [`Comparer`](../comparer) con lo stream del documento sorgente e [`ComparerSettings`](../comparersettings). |
| [Comparer](comparer#constructor_2)(Stream, LoadOptions) | Inizializza una nuova istanza di [`Comparer`](../comparer) con lo stream del documento sorgente e [`LoadOptions`](../../groupdocs.comparison.options/loadoptions). |
| [Comparer](comparer#constructor_6)(string, CompareOptions) | Inizializza una nuova istanza di [`Comparer`](../comparer) con il percorso della cartella sorgente e [`CompareOptions`](../../groupdocs.comparison.options/compareoptions). |
| [Comparer](comparer#constructor_5)(string, ComparerSettings) | Inizializza una nuova istanza della classe [`Comparer`](../comparer) con il percorso del file sorgente e [`ComparerSettings`](../comparersettings). |
| [Comparer](comparer#constructor_7)(string, LoadOptions) | Inizializza una nuova istanza di [`Comparer`](../comparer) con il percorso del file di origine e [`LoadOptions`](../../groupdocs.comparison.options/loadoptions). |
| [Comparer](comparer#constructor_3)(Stream, LoadOptions, ComparerSettings) | Inizializza una nuova istanza della classe [`Comparer`](../comparer) con lo stream del documento, [`LoadOptions`](../../groupdocs.comparison.options/loadoptions) e [`ComparerSettings`](../comparersettings). |
| [Comparer](comparer#constructor_8)(string, LoadOptions, ComparerSettings) | Inizializza una nuova istanza della classe [`Comparer`](../comparer) con il percorso del file di origine, [`LoadOptions`](../../groupdocs.comparison.options/loadoptions) e [`ComparerSettings`](../comparersettings). |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Result](../../groupdocs.comparison/comparer/result) { get; } | Documento risultato. |
| [Source](../../groupdocs.comparison/comparer/source) { get; } | File di origine che viene confrontato. |
| [SourceFolder](../../groupdocs.comparison/comparer/sourcefolder) { get; } | Cartella di origine che viene confrontata. |
| [TargetFolder](../../groupdocs.comparison/comparer/targetfolder) { get; set; } | Cartella di destinazione che viene confrontata. |
| [Targets](../../groupdocs.comparison/comparer/targets) { get; } | Elenco dei file di destinazione da confrontare con il file di origine. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Add](../../groupdocs.comparison/comparer/add#add)(Stream) | Aggiunge lo stream del documento al confronto. |
| [Add](../../groupdocs.comparison/comparer/add#add_2)(string) | Aggiunge il file al confronto. |
| [Add](../../groupdocs.comparison/comparer/add#add_1)(Stream, LoadOptions) | Aggiunge lo stream del documento al confronto con le opzioni di caricamento specificate. |
| [Add](../../groupdocs.comparison/comparer/add#add_3)(string, CompareOptions) | Aggiunge la cartella al confronto. |
| [Add](../../groupdocs.comparison/comparer/add#add_4)(string, LoadOptions) | Aggiunge il file al confronto con le opzioni di caricamento specificate. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges)(Stream, ApplyChangeOptions) | Accetta o rifiuta le modifiche e le applica al documento risultante. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_2)(string, ApplyChangeOptions) | Accetta o rifiuta le modifiche e le applica al documento risultante. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_1)(Stream, SaveOptions, ApplyChangeOptions) | Accetta o rifiuta le modifiche e le applica al documento risultante. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_3)(string, SaveOptions, ApplyChangeOptions) | Accetta o rifiuta le modifiche e le applica al documento risultante. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare)() | Confronta i documenti senza salvare il risultato con le opzioni predefinite |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_1)(CompareOptions) | Confronta i documenti senza salvare il risultato. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_3)(Stream) | Confronta i documenti e salva il risultato in uno stream di file |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_7)(string) | Confronta i documenti e salva il risultato nel percorso del file |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_2)(SaveOptions, CompareOptions) | Confronta i documenti senza salvare il risultato. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_4)(Stream, CompareOptions) | Confronta i documenti e salva il risultato in uno stream di file |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_5)(Stream, SaveOptions) | Confronta i documenti e salva il risultato in uno stream di file |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_8)(string, CompareOptions) | Confronta i documenti e salva il risultato nel percorso del file |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_9)(string, SaveOptions) | Confronta i documenti e salva il risultato nel percorso del file |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_6)(Stream, SaveOptions, CompareOptions) | Confronta i documenti e salva il risultato in uno stream. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_10)(string, SaveOptions, CompareOptions) | Confronta i documenti e salva il risultato nel percorso del file |
| [CompareDirectory](../../groupdocs.comparison/comparer/comparedirectory)(string, CompareOptions) | Confronta la directory e salva il risultato nel percorso del file |
| [Dispose](../../groupdocs.comparison/comparer/dispose)() | Rilascia le risorse. |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges)() | Ottiene l'elenco delle modifiche tra il file di origine e quello di destinazione. |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges_1)(ChangeType) | Ottiene l'elenco delle modifiche tra il file di origine e quello di destinazione. |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges_2)(GetChangeOptions) | Ottiene l'elenco delle modifiche tra il file di origine e quello di destinazione. |
| [GetResultDocumentStream](../../groupdocs.comparison/comparer/getresultdocumentstream)() | Ottiene lo stream del documento risultato, restituisce null se lo stream non esiste |
| [GetResultString](../../groupdocs.comparison/comparer/getresultstring)() | Ottieni la stringa risultato dopo il confronto (solo per Confronto Testuale). |

### Vedi anche

* namespace [GroupDocs.Comparison](../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.Comparison.dll -->
