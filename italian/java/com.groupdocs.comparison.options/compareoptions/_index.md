---
title: "CompareOptions"
second_title: "Riferimento API di GroupDocs.Comparison per Java"
description: "Consente di configurare il processo di confronto dei documenti."
type: docs
weight: 11
url: /it/java/com.groupdocs.comparison.options/compareoptions/
---
**Inheritance:**
java.lang.Object
```
public class CompareOptions
```

Consente di configurare il processo di confronto dei documenti.


Esempio di utilizzo:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     final StyleSettings styleSettings = new StyleSettings();
     styleSettings.setHighlightColor(Color.RED);
     styleSettings.setFontColor(Color.GREEN);
     styleSettings.setUnderline(true);

     CompareOptions compareOptions = new CompareOptions();
     compareOptions.setInsertedItemStyle(styleSettings);

     comparer.compare(resultFile, compareOptions);
 }
 
````


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [CompareOptions()](#CompareOptions--) | Inizializza una nuova istanza della classe CompareOptions. |
|
|  | [CompareOptions(StyleSettings insertedItemStyle, StyleSettings deletedItemStyle, StyleSettings changedItemStyle)](#CompareOptions-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-) | Inizializza una nuova istanza della classe CompareOptions con impostazioni per diversi stili. |
|
## Campi

| Campo | Descrizione |
| --- | --- |
| [ignoreChangeSettings](#ignoreChangeSettings) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getIgnoreChangeSettings()](#getIgnoreChangeSettings--) | Ottieni le impostazioni per ignorare le modifiche basate sulla somiglianza. |
|
|  | [setIgnoreChangeSettings(IgnoreChangeSensitivitySettings ignoreChangeSettings)](#setIgnoreChangeSettings-com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings-) | Imposta le impostazioni per ignorare le modifiche basate sulla somiglianza. |
|
|  | [getUserMasterPath()](#getUserMasterPath--) | Ottiene il percorso del modello master dell'utente per Diagrammi. |
|
|  | [setUserMasterPath(String userMasterPath)](#setUserMasterPath-java.lang.String-) | Imposta il percorso del modello master dell'utente per Diagrammi. |
|
|  | [getComparisonType()](#getComparisonType--) | Ottiene un tipo di documenti sorgente e destinazione come oggetto [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) in modo che Comparison sappia come confrontarli. |
|
|  | [setComparisonType(ComparisonType comparisonType)](#setComparisonType-com.groupdocs.comparison.options.enums.ComparisonType-) | Imposta un tipo di documenti sorgente e destinazione come oggetto [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) in modo che Comparison sappia come confrontarli. |
|
|  | [getPaperSize()](#getPaperSize--) | Ottiene una dimensione di carta nel documento risultato come oggetto [PaperSize](../../com.groupdocs.comparison.options.enums/papersize). |
|
|  | [setPaperSize(PaperSize value)](#setPaperSize-com.groupdocs.comparison.options.enums.PaperSize-) | Imposta una dimensione di carta nel documento risultato come oggetto [PaperSize](../../com.groupdocs.comparison.options.enums/papersize). |
|
|  | [getCalculateCoordinatesMode()](#getCalculateCoordinatesMode--) | Ottiene una modalità di calcolo delle coordinate come oggetto [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration). |
|
|  | [setCalculateCoordinatesMode(CalculateCoordinatesModeEnumeration calculateCoordinatesMode)](#setCalculateCoordinatesMode-com.groupdocs.comparison.options.enums.CalculateCoordinatesModeEnumeration-) | Imposta una modalità di calcolo delle coordinate come oggetto [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration). |
|
|  | [isShowDeletedContent()](#isShowDeletedContent--) | Ottiene un flag che indica se mostrare o meno i componenti eliminati nel documento risultante. |
|
|  | [setShowDeletedContent(boolean value)](#setShowDeletedContent-boolean-) | Imposta un flag che indica se mostrare o meno i componenti eliminati nel documento risultante. |
|
|  | [isShowInsertedContent()](#isShowInsertedContent--) | Ottiene un flag che indica se mostrare i componenti inseriti nel documento risultante o meno. |
|
|  | [setShowInsertedContent(boolean value)](#setShowInsertedContent-boolean-) | Imposta un flag che indica se mostrare i componenti inseriti nel documento risultante o meno. |
|
|  | [isGenerateSummaryPage()](#isGenerateSummaryPage--) | Ottiene un flag che indica se aggiungere una pagina di riepilogo con le statistiche delle modifiche rilevate al documento risultante o meno. |
|
|  | [setGenerateSummaryPage(boolean value)](#setGenerateSummaryPage-boolean-) | Imposta un flag che indica se aggiungere una pagina di riepilogo con le statistiche delle modifiche rilevate al documento risultante o meno. |
|
|  | [isExtendedSummaryPage()](#isExtendedSummaryPage--) | Ottiene un flag che indica se aggiungere informazioni estese di confronto file alla pagina di riepilogo o meno. |
|
|  | [setExtendedSummaryPage(boolean value)](#setExtendedSummaryPage-boolean-) | Imposta un flag che indica se aggiungere informazioni estese di confronto file alla pagina di riepilogo o meno. |
|
|  | [isShowOnlySummaryPage()](#isShowOnlySummaryPage--) | Ottiene un flag che indica se lasciare nel documento risultante solo una pagina con le statistiche delle modifiche rilevate o meno. |
|
|  | [setShowOnlySummaryPage(boolean value)](#setShowOnlySummaryPage-boolean-) | Imposta un flag che indica se lasciare nel documento risultante solo una pagina con le statistiche delle modifiche rilevate o meno. |
|
|  | [isDetectStyleChanges()](#isDetectStyleChanges--) | Ottiene un flag che indica se rilevare le modifiche di stile o meno. |
|
|  | [setDetectStyleChanges(boolean value)](#setDetectStyleChanges-boolean-) | Imposta un flag che indica se rilevare le modifiche di stile o meno. |
|
|  | [isMarkNestedContent()](#isMarkNestedContent--) | Ottiene un flag che indica se contrassegnare i figli degli elementi eliminati o inseriti come eliminati o inseriti. |
|
|  | [setMarkNestedContent(boolean value)](#setMarkNestedContent-boolean-) | Imposta un flag che indica se contrassegnare i figli degli elementi eliminati o inseriti come eliminati o inseriti. |
|
|  | [isCalculateCoordinates()](#isCalculateCoordinates--) | Ottiene un flag che indica se calcolare le coordinate per i componenti modificati. |
|
|  | [setCalculateCoordinates(boolean value)](#setCalculateCoordinates-boolean-) | Imposta un flag che indica se calcolare le coordinate per i componenti modificati. |
|
|  | [isHeaderFootersComparison()](#isHeaderFootersComparison--) | Ottiene un flag che indica se confrontare i contenuti di intestazione/piè di pagina. |
|
|  | [setHeaderFootersComparison(boolean value)](#setHeaderFootersComparison-boolean-) | Imposta un flag che indica se confrontare i contenuti di intestazione/piè di pagina. |
|
|  | [getDetalisationLevel()](#getDetalisationLevel--) | Ottiene un livello di dettaglio di confronto rappresentato come [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel). |
|
|  | [setDetalisationLevel(DetalisationLevel value)](#setDetalisationLevel-com.groupdocs.comparison.options.style.DetalisationLevel-) | Imposta un livello di dettaglio di confronto rappresentato come [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel). |
|
|  | [isMarkChangedContent()](#isMarkChangedContent--) | Ottiene un flag che indica se verranno utilizzati i riquadri per le forme nell'elaborazione testi e per i rettangoli nei documenti immagine. |
|
|  | [setMarkChangedContent(boolean value)](#setMarkChangedContent-boolean-) | Imposta un flag che indica se verranno utilizzati i riquadri per le forme nell'elaborazione testi e per i rettangoli nei documenti immagine. |
|
|  | [getInsertedItemStyle()](#getInsertedItemStyle--) | Ottiene le impostazioni di stile che saranno applicate agli elementi inseriti. |
|
|  | [setInsertedItemStyle(StyleSettings value)](#setInsertedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-) | Imposta le impostazioni di stile che saranno applicate agli elementi inseriti. |
|
|  | [getDeletedItemStyle()](#getDeletedItemStyle--) | Ottiene le impostazioni di stile che saranno applicate agli elementi eliminati. |
|
|  | [setDeletedItemStyle(StyleSettings value)](#setDeletedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-) | Imposta le impostazioni di stile che saranno applicate agli elementi eliminati. |
|
|  | [getChangedItemStyle()](#getChangedItemStyle--) | Ottiene le impostazioni di stile che saranno applicate agli elementi modificati. |
|
|  | [setChangedItemStyle(StyleSettings value)](#setChangedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-) | Imposta le impostazioni di stile che verranno applicate agli elementi modificati. |
|
|  | [getSensitivityOfComparison()](#getSensitivityOfComparison--) | Ottiene la sensibilità del confronto. |
|
|  | [setSensitivityOfComparison(int value)](#setSensitivityOfComparison-int-) | Imposta la sensibilità del confronto. |
|
|  | [setSensitivityOfComparisonForTables(Integer value)](#setSensitivityOfComparisonForTables-java.lang.Integer-) | Imposta la sensibilità del confronto per le tabelle. |
|
|  | [getSensitivityOfComparisonForTables()](#getSensitivityOfComparisonForTables--) | Ottiene la sensibilità del confronto per le tabelle. |
|
|  | [setWordsSeparatorChars(char[] value)](#setWordsSeparatorChars-char---) | Imposta un array di delimitatori che verrà utilizzato per suddividere il testo in parole. |
|
|  | [getPasswordSaveOption()](#getPasswordSaveOption--) | Ottiene un'opzione di salvataggio della password rappresentata dall'oggetto [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption). |
|
|  | [setPasswordSaveOption(PasswordSaveOption value)](#setPasswordSaveOption-com.groupdocs.comparison.options.enums.PasswordSaveOption-) | Imposta un'opzione di salvataggio della password rappresentata dall'oggetto [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption). |
|
|  | [getOriginalSize()](#getOriginalSize--) | Ottiene le dimensioni originali dei documenti confrontati rappresentate dall'oggetto [OriginalSize](../../com.groupdocs.comparison.options/originalsize). |
|
|  | [setOriginalSize(OriginalSize value)](#setOriginalSize-com.groupdocs.comparison.options.OriginalSize-) | Imposta le dimensioni originali dei documenti confrontati rappresentate dall'oggetto [OriginalSize](../../com.groupdocs.comparison.options/originalsize). |
|
|  | [getDiagramMasterSetting()](#getDiagramMasterSetting--) | Ottiene un'impostazione della pagina master per i documenti Diagram rappresentata dall'oggetto [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting). |
|
|  | [setDiagramMasterSetting(DiagramMasterSetting value)](#setDiagramMasterSetting-com.groupdocs.comparison.options.style.DiagramMasterSetting-) | Imposta un'impostazione della pagina master per i documenti Diagram rappresentata dall'oggetto [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting). |
|
|  | [isDirectoryCompare()](#isDirectoryCompare--) | Restituisce un flag che indica se il confronto delle directory è abilitato. |
|
|  | [setDirectoryCompare(boolean directoryCompare)](#setDirectoryCompare-boolean-) | Imposta un flag che indica se il confronto delle directory deve essere abilitato. |
|
|  | [isShowOnlyChanged()](#isShowOnlyChanged--) | Restituisce un valore booleano che indica se devono essere visualizzati solo gli elementi modificati. |
|
|  | [setShowOnlyChanged(boolean showOnlyChanged)](#setShowOnlyChanged-boolean-) | Imposta il valore che indica se devono essere visualizzati solo gli elementi modificati. |
|
|  | [getFolderComparisonExtension()](#getFolderComparisonExtension--) | Ottiene il formato del file di confronto della cartella risultante. |
|
|  | [setFolderComparisonExtension(FolderComparisonExtension folderComparisonExtension)](#setFolderComparisonExtension-com.groupdocs.comparison.options.enums.FolderComparisonExtension-) | Imposta il formato del file di confronto della cartella risultante. |
|
### CompareOptions() {#CompareOptions--}
```
public CompareOptions()
```


Inizializza una nuova istanza della classe CompareOptions.


### CompareOptions(StyleSettings insertedItemStyle, StyleSettings deletedItemStyle, StyleSettings changedItemStyle) {#CompareOptions-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-}
```
public CompareOptions(StyleSettings insertedItemStyle, StyleSettings deletedItemStyle, StyleSettings changedItemStyle)
```


Inizializza una nuova istanza della classe CompareOptions con impostazioni per diversi stili.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | insertedItemStyle | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Impostazioni di stile per gli elementi inseriti |
|
|  | deletedItemStyle | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Impostazioni di stile per gli elementi eliminati |
|
|  | changedItemStyle | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Impostazioni di stile per gli elementi di stile modificati |
|

### ignoreChangeSettings {#ignoreChangeSettings}
```
public IgnoreChangeSensitivitySettings ignoreChangeSettings
```


### getIgnoreChangeSettings() {#getIgnoreChangeSettings--}
```
public IgnoreChangeSensitivitySettings getIgnoreChangeSettings()
```


Ottieni le impostazioni per ignorare le modifiche basate sulla somiglianza.


**Returns:**
com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings - Impostazioni per ignorare le modifiche.

### setIgnoreChangeSettings(IgnoreChangeSensitivitySettings ignoreChangeSettings) {#setIgnoreChangeSettings-com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings-}
```
public void setIgnoreChangeSettings(IgnoreChangeSensitivitySettings ignoreChangeSettings)
```


Imposta le impostazioni per ignorare le modifiche basate sulla somiglianza.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | ignoreChangeSettings | com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings | Impostazioni per ignorare le modifiche. |
|

### getUserMasterPath() {#getUserMasterPath--}
```
public String getUserMasterPath()
```


Ottiene il percorso del modello master dell'utente per Diagrammi.


**Returns:**
java.lang.String - Il percorso al modello master dell'utente per i Diagrammi.

### setUserMasterPath(String userMasterPath) {#setUserMasterPath-java.lang.String-}
```
public void setUserMasterPath(String userMasterPath)
```


Imposta il percorso del modello master dell'utente per Diagrammi.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | userMasterPath | java.lang.String | Il percorso al modello master dell'utente per i Diagrammi. |
|

### getComparisonType() {#getComparisonType--}
```
public ComparisonType getComparisonType()
```


Ottiene un tipo di documenti sorgente e destinazione come oggetto [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) in modo che Comparison sappia come confrontarli.
Quando questa opzione è impostata, l'opzione [LoadOptions.getFileType()](../../com.groupdocs.comparison.options.load/loadoptions#getFileType--) verrà omessa.


**Returns:**
[ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) - the type of source and target documents

### setComparisonType(ComparisonType comparisonType) {#setComparisonType-com.groupdocs.comparison.options.enums.ComparisonType-}
```
public void setComparisonType(ComparisonType comparisonType)
```


Imposta un tipo di documenti sorgente e destinazione come oggetto [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) in modo che Comparison sappia come confrontarli.
Quando questa opzione è impostata, l'opzione [LoadOptions.setFileType(FileType)](../../com.groupdocs.comparison.options.load/loadoptions#setFileType-FileType-) verrà omessa.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | comparisonType | [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) | Il tipo dei documenti sorgente e destinazione |
|

### getPaperSize() {#getPaperSize--}
```
public final PaperSize getPaperSize()
```


Ottiene una dimensione di carta nel documento risultato come oggetto [PaperSize](../../com.groupdocs.comparison.options.enums/papersize).


**Returns:**
[PaperSize](../../com.groupdocs.comparison.options.enums/papersize) - the size of a paper in result document

### setPaperSize(PaperSize value) {#setPaperSize-com.groupdocs.comparison.options.enums.PaperSize-}
```
public final void setPaperSize(PaperSize value)
```


Imposta una dimensione di carta nel documento risultato come oggetto [PaperSize](../../com.groupdocs.comparison.options.enums/papersize).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [PaperSize](../../com.groupdocs.comparison.options.enums/papersize) | La dimensione di un foglio nel documento risultato |
|

### getCalculateCoordinatesMode() {#getCalculateCoordinatesMode--}
```
public CalculateCoordinatesModeEnumeration getCalculateCoordinatesMode()
```


Ottiene una modalità di calcolo delle coordinate come oggetto [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration).


**Returns:**
[CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) - the calculate coordinates mode

### setCalculateCoordinatesMode(CalculateCoordinatesModeEnumeration calculateCoordinatesMode) {#setCalculateCoordinatesMode-com.groupdocs.comparison.options.enums.CalculateCoordinatesModeEnumeration-}
```
public void setCalculateCoordinatesMode(CalculateCoordinatesModeEnumeration calculateCoordinatesMode)
```


Imposta una modalità di calcolo delle coordinate come oggetto [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | calculateCoordinatesMode | [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) | La modalità di calcolo delle coordinate |
|

### isShowDeletedContent() {#isShowDeletedContent--}
```
public final boolean isShowDeletedContent()
```


Ottiene un flag che indica se mostrare o meno i componenti eliminati nel documento risultante.


**Returns:**
boolean - true se i componenti eliminati nel documento risultante saranno mostrati, altrimenti false

### setShowDeletedContent(boolean value) {#setShowDeletedContent-boolean-}
```
public final void setShowDeletedContent(boolean value)
```


Imposta un flag che indica se mostrare o meno i componenti eliminati nel documento risultante.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | true se i componenti eliminati nel documento risultante dovrebbero essere mostrati, altrimenti false |
|

### isShowInsertedContent() {#isShowInsertedContent--}
```
public final boolean isShowInsertedContent()
```


Ottiene un flag che indica se mostrare i componenti inseriti nel documento risultante o meno.


**Returns:**
boolean - true se i componenti inseriti nel documento risultante dovrebbero essere mostrati, altrimenti false

### setShowInsertedContent(boolean value) {#setShowInsertedContent-boolean-}
```
public final void setShowInsertedContent(boolean value)
```


Imposta un flag che indica se mostrare i componenti inseriti nel documento risultante o meno.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | true se i componenti inseriti nel documento risultante dovrebbero essere mostrati, altrimenti false |
|

### isGenerateSummaryPage() {#isGenerateSummaryPage--}
```
public final boolean isGenerateSummaryPage()
```


Ottiene un flag che indica se aggiungere una pagina di riepilogo con le statistiche delle modifiche rilevate al documento risultante o meno.


**Returns:**
boolean - true se la pagina di riepilogo sarà aggiunta, altrimenti false

### setGenerateSummaryPage(boolean value) {#setGenerateSummaryPage-boolean-}
```
public final void setGenerateSummaryPage(boolean value)
```


Imposta un flag che indica se aggiungere una pagina di riepilogo con le statistiche delle modifiche rilevate al documento risultante o meno.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | true se la pagina di riepilogo dovrebbe essere aggiunta, altrimenti false |
|

### isExtendedSummaryPage() {#isExtendedSummaryPage--}
```
public boolean isExtendedSummaryPage()
```


Ottiene un flag che indica se aggiungere informazioni estese di confronto file alla pagina di riepilogo o meno.


**Returns:**
boolean - true se le informazioni estese di confronto file saranno aggiunte alla pagina di riepilogo, altrimenti false

### setExtendedSummaryPage(boolean value) {#setExtendedSummaryPage-boolean-}
```
public void setExtendedSummaryPage(boolean value)
```


Imposta un flag che indica se aggiungere informazioni estese di confronto file alla pagina di riepilogo o meno.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | true se le informazioni estese di confronto file dovrebbero essere aggiunte alla pagina di riepilogo, altrimenti false |
|

### isShowOnlySummaryPage() {#isShowOnlySummaryPage--}
```
public boolean isShowOnlySummaryPage()
```


Ottiene un flag che indica se lasciare nel documento risultante solo una pagina con le statistiche delle modifiche rilevate o meno.


**Returns:**
boolean - true se nel documento risultante rimarrà solo una pagina con le statistiche delle modifiche rilevate, altrimenti false

### setShowOnlySummaryPage(boolean value) {#setShowOnlySummaryPage-boolean-}
```
public void setShowOnlySummaryPage(boolean value)
```


Imposta un flag che indica se lasciare nel documento risultante solo una pagina con le statistiche delle modifiche rilevate o meno.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | true se nel documento risultante dovrebbe rimanere solo una pagina con le statistiche delle modifiche rilevate, altrimenti false |
|

### isDetectStyleChanges() {#isDetectStyleChanges--}
```
public final boolean isDetectStyleChanges()
```


Ottiene un flag che indica se rilevare le modifiche di stile o meno.


**Returns:**
boolean - true se le modifiche di stile saranno rilevate, altrimenti false

### setDetectStyleChanges(boolean value) {#setDetectStyleChanges-boolean-}
```
public final void setDetectStyleChanges(boolean value)
```


Imposta un flag che indica se rilevare le modifiche di stile o meno.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | true se le modifiche di stile dovrebbero essere rilevate, altrimenti false |
|

### isMarkNestedContent() {#isMarkNestedContent--}
```
public final boolean isMarkNestedContent()
```


Ottiene un flag che indica se contrassegnare i figli degli elementi eliminati o inseriti come eliminati o inseriti.


**Returns:**
boolean - true se i figli degli elementi eliminati o inseriti saranno contrassegnati come eliminati o inseriti, altrimenti false

### setMarkNestedContent(boolean value) {#setMarkNestedContent-boolean-}
```
public final void setMarkNestedContent(boolean value)
```


Imposta un flag che indica se contrassegnare i figli degli elementi eliminati o inseriti come eliminati o inseriti.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | true se i figli degli elementi eliminati o inseriti dovrebbero essere contrassegnati come eliminati o inseriti, altrimenti false |
|

### isCalculateCoordinates() {#isCalculateCoordinates--}
```
public final boolean isCalculateCoordinates()
```


Ottiene un flag che indica se calcolare le coordinate per i componenti modificati.


**Returns:**
boolean - true se le coordinate per i componenti modificati saranno calcolate, altrimenti false

### setCalculateCoordinates(boolean value) {#setCalculateCoordinates-boolean-}
```
public final void setCalculateCoordinates(boolean value)
```


Imposta un flag che indica se calcolare le coordinate per i componenti modificati.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | true se le coordinate per i componenti modificati dovrebbero essere calcolate, altrimenti false |
|

### isHeaderFootersComparison() {#isHeaderFootersComparison--}
```
public final boolean isHeaderFootersComparison()
```


Ottiene un flag che indica se confrontare i contenuti di intestazione/piè di pagina.


**Returns:**
boolean - true se i contenuti di intestazione/piè di pagina saranno confrontati, altrimenti false

### setHeaderFootersComparison(boolean value) {#setHeaderFootersComparison-boolean-}
```
public final void setHeaderFootersComparison(boolean value)
```


Imposta un flag che indica se confrontare i contenuti di intestazione/piè di pagina.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | true se i contenuti di header/footer devono essere confrontati, altrimenti false |
|

### getDetalisationLevel() {#getDetalisationLevel--}
```
public final DetalisationLevel getDetalisationLevel()
```


Ottiene un livello di dettaglio di confronto rappresentato come [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel).
Il valore predefinito è [DetalisationLevel.LOW](../../com.groupdocs.comparison.options.style/detalisationlevel#LOW).


**Returns:**
[DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) - the level of comparison detalization

### setDetalisationLevel(DetalisationLevel value) {#setDetalisationLevel-com.groupdocs.comparison.options.style.DetalisationLevel-}
```
public final void setDetalisationLevel(DetalisationLevel value)
```


Imposta un livello di dettaglio di confronto rappresentato come [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel).
Il valore predefinito è [DetalisationLevel.LOW](../../com.groupdocs.comparison.options.style/detalisationlevel#LOW)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) | Il livello di dettaglio del confronto |
|

### isMarkChangedContent() {#isMarkChangedContent--}
```
public final boolean isMarkChangedContent()
```


Ottiene un flag che indica se verranno utilizzati i riquadri per le forme nell'elaborazione testi e per i rettangoli nei documenti immagine.


**Returns:**
boolean - true se i frame verranno utilizzati, altrimenti false

### setMarkChangedContent(boolean value) {#setMarkChangedContent-boolean-}
```
public final void setMarkChangedContent(boolean value)
```


Imposta un flag che indica se verranno utilizzati i riquadri per le forme nell'elaborazione testi e per i rettangoli nei documenti immagine.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | true se i frame devono essere utilizzati, altrimenti false |
|

### getInsertedItemStyle() {#getInsertedItemStyle--}
```
public final StyleSettings getInsertedItemStyle()
```


Ottiene le impostazioni di stile che saranno applicate agli elementi inseriti.


**Returns:**
[StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) - style settings of inserted items

### setInsertedItemStyle(StyleSettings value) {#setInsertedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-}
```
public final void setInsertedItemStyle(StyleSettings value)
```


Imposta le impostazioni di stile che saranno applicate agli elementi inseriti.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Impostazioni di stile degli elementi inseriti |
|

### getDeletedItemStyle() {#getDeletedItemStyle--}
```
public final StyleSettings getDeletedItemStyle()
```


Ottiene le impostazioni di stile che saranno applicate agli elementi eliminati.


**Returns:**
[StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) - style settings of deleted items

### setDeletedItemStyle(StyleSettings value) {#setDeletedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-}
```
public final void setDeletedItemStyle(StyleSettings value)
```


Imposta le impostazioni di stile che saranno applicate agli elementi eliminati.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Impostazioni di stile degli elementi eliminati |
|

### getChangedItemStyle() {#getChangedItemStyle--}
```
public final StyleSettings getChangedItemStyle()
```


Ottiene le impostazioni di stile che saranno applicate agli elementi modificati.


**Returns:**
[StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) - style settings of changed items

### setChangedItemStyle(StyleSettings value) {#setChangedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-}
```
public final void setChangedItemStyle(StyleSettings value)
```


Imposta le impostazioni di stile che verranno applicate agli elementi modificati.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Impostazioni di stile degli elementi modificati |
|

### getSensitivityOfComparison() {#getSensitivityOfComparison--}
```
public final int getSensitivityOfComparison()
```


Ottiene la sensibilità del confronto.
La percentuale di elementi eliminati e inseriti di due oggetti confrontati rispetto a tutti gli elementi di questi oggetti.

* If this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Returns:**
int - la sensibilità del confronto

### setSensitivityOfComparison(int value) {#setSensitivityOfComparison-int-}
```
public final void setSensitivityOfComparison(int value)
```


Imposta la sensibilità del confronto.
La percentuale di elementi eliminati e inseriti di due oggetti confrontati rispetto a tutti gli elementi di questi oggetti.

* If this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | int | La sensibilità del confronto |
|

### setSensitivityOfComparisonForTables(Integer value) {#setSensitivityOfComparisonForTables-java.lang.Integer-}
```
public void setSensitivityOfComparisonForTables(Integer value)
```


Imposta la sensibilità del confronto per le tabelle.
Se il valore è null, viene utilizzato SensitivityOfComparison. La percentuale di elementi eliminati e inseriti di due oggetti confrontati rispetto a tutti gli elementi di questi oggetti.

* if this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs, if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.lang.Integer | La sensibilità del confronto per le tabelle |
|

### getSensitivityOfComparisonForTables() {#getSensitivityOfComparisonForTables--}
```
public final Integer getSensitivityOfComparisonForTables()
```


Ottiene la sensibilità del confronto per le tabelle.
Se il valore è null, viene utilizzato SensitivityOfComparison. La percentuale di elementi eliminati e inseriti di due oggetti confrontati rispetto a tutti gli elementi di questi oggetti.

* if this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs, if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Returns:**
java.lang.Integer - La sensibilità del confronto per le tabelle

### setWordsSeparatorChars(char[] value) {#setWordsSeparatorChars-char---}
```
public final void setWordsSeparatorChars(char[] value)
```


Imposta un array di delimitatori che verrà utilizzato per suddividere il testo in parole.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | char[] | L'array di delimitatori per suddividere il testo in parole |
|

### getPasswordSaveOption() {#getPasswordSaveOption--}
```
public final PasswordSaveOption getPasswordSaveOption()
```


Ottiene un'opzione di salvataggio della password rappresentata dall'oggetto [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption).


**Returns:**
[PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) - the password save option

### setPasswordSaveOption(PasswordSaveOption value) {#setPasswordSaveOption-com.groupdocs.comparison.options.enums.PasswordSaveOption-}
```
public final void setPasswordSaveOption(PasswordSaveOption value)
```


Imposta un'opzione di salvataggio della password rappresentata dall'oggetto [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) | L'opzione di salvataggio della password |
|

### getOriginalSize() {#getOriginalSize--}
```
public final OriginalSize getOriginalSize()
```


Ottiene le dimensioni originali dei documenti confrontati rappresentate dall'oggetto [OriginalSize](../../com.groupdocs.comparison.options/originalsize).


**Returns:**
[OriginalSize](../../com.groupdocs.comparison.options/originalsize) - the original size of documents

### setOriginalSize(OriginalSize value) {#setOriginalSize-com.groupdocs.comparison.options.OriginalSize-}
```
public final void setOriginalSize(OriginalSize value)
```


Imposta le dimensioni originali dei documenti confrontati rappresentate dall'oggetto [OriginalSize](../../com.groupdocs.comparison.options/originalsize).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [OriginalSize](../../com.groupdocs.comparison.options/originalsize) | La dimensione originale dei documenti |
|

### getDiagramMasterSetting() {#getDiagramMasterSetting--}
```
public final DiagramMasterSetting getDiagramMasterSetting()
```


Ottiene un'impostazione della pagina master per i documenti Diagram rappresentata dall'oggetto [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting).


**Returns:**
[DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) - the diagram master page setting

### setDiagramMasterSetting(DiagramMasterSetting value) {#setDiagramMasterSetting-com.groupdocs.comparison.options.style.DiagramMasterSetting-}
```
public final void setDiagramMasterSetting(DiagramMasterSetting value)
```


Imposta un'impostazione della pagina master per i documenti Diagram rappresentata dall'oggetto [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) | L'impostazione della pagina master del diagramma |
|

### isDirectoryCompare() {#isDirectoryCompare--}
```
public boolean isDirectoryCompare()
```


Restituisce un flag che indica se il confronto delle directory è abilitato.


**Returns:**
boolean - true se il confronto di directory è abilitato, altrimenti false

### setDirectoryCompare(boolean directoryCompare) {#setDirectoryCompare-boolean-}
```
public void setDirectoryCompare(boolean directoryCompare)
```


Imposta un flag che indica se il confronto delle directory deve essere abilitato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | directoryCompare | boolean | true se il confronto di directory dovrebbe essere abilitato, altrimenti false |
|

### isShowOnlyChanged() {#isShowOnlyChanged--}
```
public boolean isShowOnlyChanged()
```


Restituisce un valore booleano che indica se devono essere visualizzati solo gli elementi modificati.


**Returns:**
boolean - true se devono essere visualizzati solo gli elementi modificati, altrimenti false

### setShowOnlyChanged(boolean showOnlyChanged) {#setShowOnlyChanged-boolean-}
```
public void setShowOnlyChanged(boolean showOnlyChanged)
```


Imposta il valore che indica se devono essere visualizzati solo gli elementi modificati.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | showOnlyChanged | boolean | il valore booleano che indica se devono essere visualizzati solo gli elementi modificati |
|

### getFolderComparisonExtension() {#getFolderComparisonExtension--}
```
public FolderComparisonExtension getFolderComparisonExtension()
```


Ottiene il formato del file di confronto della cartella risultante.


**Returns:**
com.groupdocs.comparison.options.enums.FolderComparisonExtension - la FolderComparisonExtension che rappresenta il formato del file di confronto delle cartelle risultante

### setFolderComparisonExtension(FolderComparisonExtension folderComparisonExtension) {#setFolderComparisonExtension-com.groupdocs.comparison.options.enums.FolderComparisonExtension-}
```
public void setFolderComparisonExtension(FolderComparisonExtension folderComparisonExtension)
```


Imposta il formato del file di confronto della cartella risultante.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | folderComparisonExtension | com.groupdocs.comparison.options.enums.FolderComparisonExtension | la FolderComparisonExtension che rappresenta il formato del file di confronto delle cartelle risultante |
|

