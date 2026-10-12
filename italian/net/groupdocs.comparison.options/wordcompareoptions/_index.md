---
title: "WordCompareOptions"
second_title: "GroupDocs.Comparison per .NET Riferimento API"
description: "Opzioni di confronto specifiche per documenti Word. Eredita le opzioni comuni da CompareOptions./compareoptions."
type: docs
weight: 440
url: /it/net/groupdocs.comparison.options/wordcompareoptions/
---
## WordCompareOptions class

Opzioni di confronto specifiche per documenti Word. Eredita le opzioni comuni da [`CompareOptions`](../compareoptions).

```csharp
public class WordCompareOptions : CompareOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [WordCompareOptions](wordcompareoptions)() | Inizializza una nuova istanza della classe [`WordCompareOptions`](../wordcompareoptions). |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CalculateCoordinates](../../groupdocs.comparison.options/compareoptions/calculatecoordinates) { get; set; } | Indica se calcolare le coordinate per i componenti modificati. |
| [CalculateCoordinatesMode](../../groupdocs.comparison.options/compareoptions/calculatecoordinatesmode) { get; set; } | Specifica il calcolo delle coordinate per la modalità dei componenti modificati. |
| [ChangedItemStyle](../../groupdocs.comparison.options/compareoptions/changeditemstyle) { get; set; } | Descrive lo stile per i componenti modificati. |
| [CompareBookmarks](../../groupdocs.comparison.options/wordcompareoptions/comparebookmarks) { get; set; } | Ottiene o imposta se i segnalibri nei documenti di origine e destinazione sono confrontati e le differenze incluse nel risultato. |
| [CompareDocumentProperty](../../groupdocs.comparison.options/wordcompareoptions/comparedocumentproperty) { get; set; } | Ottiene o imposta se le proprietà di documento integrate e personalizzate sono confrontate e le differenze incluse nel risultato (ad es. nella pagina di riepilogo delle proprietà). |
| [CompareVariableProperty](../../groupdocs.comparison.options/wordcompareoptions/comparevariableproperty) { get; set; } | Ottiene o imposta se le proprietà variabili del documento (ad es. campi DOCVARIABLE) sono confrontate e le differenze incluse nel risultato. |
| [DeletedItemStyle](../../groupdocs.comparison.options/compareoptions/deleteditemstyle) { get; set; } | Descrive lo stile per i componenti eliminati. |
| [DetalisationLevel](../../groupdocs.comparison.options/compareoptions/detalisationlevel) { get; set; } | Ottiene o imposta il livello di dettaglio del confronto. |
| [DetectStyleChanges](../../groupdocs.comparison.options/compareoptions/detectstylechanges) { get; set; } | Indica se rilevare le modifiche di stile o meno. |
| [DiagramMasterSetting](../../groupdocs.comparison.options/compareoptions/diagrammastersetting) { get; set; } | Ottiene o imposta il valore del percorso per il master o utilizza il confronto senza percorso del master. Questa opzione è solo per Diagram. |
| [DirectoryCompare](../../groupdocs.comparison.options/compareoptions/directorycompare) { get; set; } | Controllo per attivare il confronto delle cartelle. |
| [DisplayMode](../../groupdocs.comparison.options/wordcompareoptions/displaymode) { get; set; } | Ottiene o imposta come vengono visualizzati i risultati del confronto: come revisioni Word in modalità Traccia modifiche (Revisions) o come modifiche evidenziate renderizzate direttamente nel documento (Highlight). |
| [ExtendedSummaryPage](../../groupdocs.comparison.options/compareoptions/extendedsummarypage) { get; set; } | Indica se aggiungere informazioni estese sul confronto dei file alla pagina di riepilogo o meno. |
| [FolderComparisonExtension](../../groupdocs.comparison.options/compareoptions/foldercomparisonextension) { get; set; } | Ottiene o imposta il formato del file di confronto delle cartelle risultante. |
| [GenerateSummaryPage](../../groupdocs.comparison.options/compareoptions/generatesummarypage) { get; set; } | Indica se aggiungere una pagina di riepilogo con le statistiche delle modifiche rilevate al documento risultante o meno. |
| [HeaderFootersComparison](../../groupdocs.comparison.options/compareoptions/headerfooterscomparison) { get; set; } | Controllo per attivare il confronto dei contenuti di intestazione/piè di pagina. |
| [IgnoreChangeSettings](../../groupdocs.comparison.options/compareoptions/ignorechangesettings) { get; set; } | Ottiene o imposta le impostazioni per ignorare le modifiche basate sulla somiglianza. |
| [InsertedItemStyle](../../groupdocs.comparison.options/compareoptions/inserteditemstyle) { get; set; } | Descrive lo stile per i componenti inseriti. |
| [LeaveGaps](../../groupdocs.comparison.options/wordcompareoptions/leavegaps) { get; set; } | Ottiene o imposta se le righe vuote vengono lasciate al posto del contenuto inserito o eliminato per preservare il layout e il conteggio delle righe; usato con [`ShowInsertedContent`](../compareoptions/showinsertedcontent) e [`ShowDeletedContent`](../compareoptions/showdeletedcontent). |
| [MarkChangedContent](../../groupdocs.comparison.options/compareoptions/markchangedcontent) { get; set; } | Indica se utilizzare cornici per le forme nell'elaborazione di Word e per i rettangoli nei documenti immagine. |
| [MarkLineBreaks](../../groupdocs.comparison.options/wordcompareoptions/marklinebreaks) { get; set; } | Ottiene o imposta se le interruzioni di paragrafo (riga) che differiscono tra i documenti sono evidenziate visivamente nel risultato. |
| [MarkNestedContent](../../groupdocs.comparison.options/compareoptions/marknestedcontent) { get; set; } | Ottiene o imposta un valore che indica se contrassegnare i figli dell'elemento eliminato o inserito come eliminati o inseriti. |
| [OriginalSize](../../groupdocs.comparison.options/compareoptions/originalsize) { get; set; } | Ottiene o imposta le dimensioni originali dei documenti confrontati. |
| [PaperSize](../../groupdocs.comparison.options/compareoptions/papersize) { get; set; } | Ottiene o imposta la dimensione della carta del documento risultato. |
| [PasswordSaveOption](../../groupdocs.comparison.options/compareoptions/passwordsaveoption) { get; set; } | Ottiene o imposta l'opzione di salvataggio della password. |
| [RevisionAuthorName](../../groupdocs.comparison.options/wordcompareoptions/revisionauthorname) { get; set; } | Ottiene o imposta il nome dell'autore utilizzato per le revisioni quando !:WordTrackChanges è abilitato. Se impostato, questo nome viene applicato al markup delle revisioni nel documento risultato. |
| [SensitivityOfComparison](../../groupdocs.comparison.options/compareoptions/sensitivityofcomparison) { get; set; } | Ottiene o imposta una sensibilità del confronto. |
| [SensitivityOfComparisonForTables](../../groupdocs.comparison.options/compareoptions/sensitivityofcomparisonfortables) { get; set; } | Ottiene o imposta una sensibilità del confronto per le tabelle. |
| [ShowDeletedContent](../../groupdocs.comparison.options/compareoptions/showdeletedcontent) { get; set; } | Indica se mostrare i componenti eliminati nel documento risultante o meno. |
| [ShowInsertedContent](../../groupdocs.comparison.options/compareoptions/showinsertedcontent) { get; set; } | Indica se mostrare i componenti inseriti nel documento risultante o meno. |
| [ShowOnlyChanged](../../groupdocs.comparison.options/compareoptions/showonlychanged) { get; set; } | Controlli per abilitare la visualizzazione solo degli elementi modificati. |
| [ShowOnlySummaryPage](../../groupdocs.comparison.options/compareoptions/showonlysummarypage) { get; set; } | Indica se lasciare nel documento risultante solo una pagina con le statistiche delle modifiche rilevate nel documento risultante o meno. |
| [ShowRevisions](../../groupdocs.comparison.options/wordcompareoptions/showrevisions) { get; set; } | Ottiene o imposta se il documento risultato mantiene visibile il markup delle revisioni. Se false, tutte le revisioni sono accettate e il risultato appare come testo finale. Questa impostazione ha senso solo quando [`DisplayMode`](./displaymode) è impostato su Highlight. Il valore predefinito è true. |
| [UserMasterPath](../../groupdocs.comparison.options/compareoptions/usermasterpath) { get; set; } | Percorso al modello master dell'utente per Diagrammi. |
| [WordsSeparatorChars](../../groupdocs.comparison.options/compareoptions/wordsseparatorchars) { set; } | Ottiene o imposta un array di delimitatori per suddividere il testo in parole. |

### Vedi anche

* class [CompareOptions](../compareoptions)
* namespace [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.Comparison.dll -->
