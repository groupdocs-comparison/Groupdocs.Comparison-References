---
title: Comparer
second_title: GroupDocs.Confronto per Riferimento API .NET
description: Rappresenta la classe principale che controlla il processo di confronto dei documenti.
type: docs
weight: 100
url: /it/net/groupdocs.comparison/comparer/
---
## Comparer class

Rappresenta la classe principale che controlla il processo di confronto dei documenti.

```csharp
public class Comparer : IDisposable
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Comparer](comparer#constructor)(Stream) | Inizializza la nuova istanza di[`Comparer`](../comparer) classe con flusso di documenti di origine. |
| [Comparer](comparer#constructor_4)(string) | Inizializza la nuova istanza di[`Comparer`](../comparer) classe con percorso del file di origine. |
| [Comparer](comparer#constructor_1)(Stream, ComparerSettings) | Inizializza la nuova istanza di[`Comparer`](../comparer)class con il flusso del documento di origine e[`ComparerSettings`](../comparersettings) . |
| [Comparer](comparer#constructor_2)(Stream, LoadOptions) | Inizializza la nuova istanza di[`Comparer`](../comparer) con flusso di documenti di origine e[`LoadOptions`](../../groupdocs.comparison.options/loadoptions) . |
| [Comparer](comparer#constructor_5)(string, ComparerSettings) | Inizializza la nuova istanza di[`Comparer`](../comparer) classe con percorso del file di origine e[`ComparerSettings`](../comparersettings) . |
| [Comparer](comparer#constructor_6)(string, LoadOptions) | Inizializza la nuova istanza di[`Comparer`](../comparer) con percorso del file di origine e[`LoadOptions`](../../groupdocs.comparison.options/loadoptions) . |
| [Comparer](comparer#constructor_3)(Stream, LoadOptions, ComparerSettings) | Inizializza la nuova istanza di[`Comparer`](../comparer) classe con flusso di documenti,[`LoadOptions`](../../groupdocs.comparison.options/loadoptions) e[`ComparerSettings`](../comparersettings) . |
| [Comparer](comparer#constructor_7)(string, LoadOptions, ComparerSettings) | Inizializza la nuova istanza di[`Comparer`](../comparer) classe con percorso del file di origine,[`LoadOptions`](../../groupdocs.comparison.options/loadoptions) e[`ComparerSettings`](../comparersettings) . |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Source](../../groupdocs.comparison/comparer/source) { get; } | File sorgente che viene confrontato. |
| [Targets](../../groupdocs.comparison/comparer/targets) { get; } | Elenco dei file di destinazione da confrontare con il file di origine. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Add](../../groupdocs.comparison/comparer/add#add)(Stream) | Aggiunge il flusso di documenti al confronto. |
| [Add](../../groupdocs.comparison/comparer/add#add_2)(string) | Aggiunge file al confronto. |
| [Add](../../groupdocs.comparison/comparer/add#add_1)(Stream, LoadOptions) | Aggiunge il flusso di documenti al confronto con le opzioni di caricamento specificate. |
| [Add](../../groupdocs.comparison/comparer/add#add_3)(string, LoadOptions) | Aggiunge il file al confronto con le opzioni di caricamento specificate. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges)(Stream, ApplyChangeOptions) | Accetta o rifiuta le modifiche e le applica al documento risultante. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_2)(string, ApplyChangeOptions) | Accetta o rifiuta le modifiche e le applica al documento risultante. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_1)(Stream, SaveOptions, ApplyChangeOptions) | Accetta o rifiuta le modifiche e le applica al documento risultante. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_3)(string, SaveOptions, ApplyChangeOptions) | Accetta o rifiuta le modifiche e le applica al documento risultante. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare)() | Confronta i documenti senza salvare il risultato con le opzioni predefinite |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_1)(CompareOptions) | Confronta i documenti senza salvare il risultato. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_3)(Stream) | Confronta i documenti e salva i risultati nel file stream |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_7)(string) | Confronta i documenti e salva i risultati nel file path |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_2)(SaveOptions, CompareOptions) | Confronta i documenti senza salvare il risultato. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_4)(Stream, CompareOptions) | Confronta i documenti e salva i risultati nel file stream |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_5)(Stream, SaveOptions) | Confronta i documenti e salva il risultato nel file stream |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_8)(string, CompareOptions) | Confronta i documenti e salva i risultati nel file path |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_9)(string, SaveOptions) | Confronta i documenti e salva il risultato nel file path |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_6)(Stream, SaveOptions, CompareOptions) | Confronta i documenti e salva i risultati in un flusso. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_10)(string, SaveOptions, CompareOptions) | Confronta i documenti e salva i risultati nel file path |
| [Dispose](../../groupdocs.comparison/comparer/dispose)() | Rilascia risorse. |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges)() | Ottiene l'elenco delle modifiche tra i file di origine e di destinazione. |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges_1)(GetChangeOptions) | Ottiene l'elenco delle modifiche tra i file di origine e di destinazione. |
| [GetResultString](../../groupdocs.comparison/comparer/getresultstring)() | Ottieni la stringa del risultato dopo il confronto (solo per il confronto del testo). |

### Guarda anche

* spazio dei nomi [GroupDocs.Comparison](../../groupdocs.comparison)
* assemblea [GroupDocs.Comparison](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Comparison.dll -->
