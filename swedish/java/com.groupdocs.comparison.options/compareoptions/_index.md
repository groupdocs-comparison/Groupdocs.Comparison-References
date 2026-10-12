---
title: "CompareOptions"
second_title: "GroupDocs.Comparison för Java API-referens"
description: "Tillåter att konfigurera processen för dokumentjämförelse."
type: docs
weight: 11
url: /sv/java/com.groupdocs.comparison.options/compareoptions/
---
**Inheritance:**
java.lang.Object
```
public class CompareOptions
```

Tillåter att konfigurera processen för dokumentjämförelse.


Exempel på användning:

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


## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [CompareOptions()](#CompareOptions--) | Initierar en ny instans av klassen CompareOptions. |
|
|  | [CompareOptions(StyleSettings insertedItemStyle, StyleSettings deletedItemStyle, StyleSettings changedItemStyle)](#CompareOptions-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-) | Initierar en ny instans av klassen CompareOptions med inställningar för olika stilar. |
|
## Fält

| Fält | Beskrivning |
| --- | --- |
| [ignoreChangeSettings](#ignoreChangeSettings) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getIgnoreChangeSettings()](#getIgnoreChangeSettings--) | Hämta inställningar för att ignorera ändringar baserade på likhet. |
|
|  | [setIgnoreChangeSettings(IgnoreChangeSensitivitySettings ignoreChangeSettings)](#setIgnoreChangeSettings-com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings-) | Ställer in inställningar för att ignorera ändringar baserade på likhet. |
|
|  | [getUserMasterPath()](#getUserMasterPath--) | Hämtar sökvägen till användarens huvudmall för Diagram. |
|
|  | [setUserMasterPath(String userMasterPath)](#setUserMasterPath-java.lang.String-) | Ställer in sökvägen till användarens huvudmall för Diagram. |
|
|  | [getComparisonType()](#getComparisonType--) | Hämtar en typ av käll- och mål-dokument som [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) objekt så att Comparison vet hur de ska jämföras. |
|
|  | [setComparisonType(ComparisonType comparisonType)](#setComparisonType-com.groupdocs.comparison.options.enums.ComparisonType-) | Ställer in en typ av käll- och mål-dokument som [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) objekt så att Comparison vet hur de ska jämföras. |
|
|  | [getPaperSize()](#getPaperSize--) | Hämtar en pappersstorlek i resultatsdokumentet som [PaperSize](../../com.groupdocs.comparison.options.enums/papersize) objekt. |
|
|  | [setPaperSize(PaperSize value)](#setPaperSize-com.groupdocs.comparison.options.enums.PaperSize-) | Ställer in en pappersstorlek i resultatsdokumentet som [PaperSize](../../com.groupdocs.comparison.options.enums/papersize) objekt. |
|
|  | [getCalculateCoordinatesMode()](#getCalculateCoordinatesMode--) | Hämtar ett beräkningskoordinatläge som [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) objekt. |
|
|  | [setCalculateCoordinatesMode(CalculateCoordinatesModeEnumeration calculateCoordinatesMode)](#setCalculateCoordinatesMode-com.groupdocs.comparison.options.enums.CalculateCoordinatesModeEnumeration-) | Ställer in ett beräkningskoordinatläge som [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) objekt. |
|
|  | [isShowDeletedContent()](#isShowDeletedContent--) | Hämtar en flagga som indikerar om raderade komponenter ska visas i det resulterande dokumentet eller inte. |
|
|  | [setShowDeletedContent(boolean value)](#setShowDeletedContent-boolean-) | Ställer in en flagga som indikerar om raderade komponenter ska visas i det resulterande dokumentet eller inte. |
|
|  | [isShowInsertedContent()](#isShowInsertedContent--) | Hämtar en flagga som anger om infogade komponenter ska visas i det resulterande dokumentet eller inte. |
|
|  | [setShowInsertedContent(boolean value)](#setShowInsertedContent-boolean-) | Ställer in en flagga som anger om infogade komponenter ska visas i det resulterande dokumentet eller inte. |
|
|  | [isGenerateSummaryPage()](#isGenerateSummaryPage--) | Hämtar en flagga som anger om en sammanfattningssida med statistik över upptäckta ändringar ska läggas till i det resulterande dokumentet eller inte. |
|
|  | [setGenerateSummaryPage(boolean value)](#setGenerateSummaryPage-boolean-) | Ställer in en flagga som anger om en sammanfattningssida med statistik över upptäckta ändringar ska läggas till i det resulterande dokumentet eller inte. |
|
|  | [isExtendedSummaryPage()](#isExtendedSummaryPage--) | Hämtar en flagga som anger om utökad filjämförelsinformation ska läggas till i sammanfattningssidan eller inte. |
|
|  | [setExtendedSummaryPage(boolean value)](#setExtendedSummaryPage-boolean-) | Ställer in en flagga som anger om utökad filjämförelsinformation ska läggas till i sammanfattningssidan eller inte. |
|
|  | [isShowOnlySummaryPage()](#isShowOnlySummaryPage--) | Hämtar en flagga som anger om endast en sida med statistik över upptäckta ändringar ska lämnas i det resulterande dokumentet eller inte. |
|
|  | [setShowOnlySummaryPage(boolean value)](#setShowOnlySummaryPage-boolean-) | Ställer in en flagga som anger om endast en sida med statistik över upptäckta ändringar ska lämnas i det resulterande dokumentet eller inte. |
|
|  | [isDetectStyleChanges()](#isDetectStyleChanges--) | Hämtar en flagga som anger om stiländringar ska upptäckas eller inte. |
|
|  | [setDetectStyleChanges(boolean value)](#setDetectStyleChanges-boolean-) | Ställer in en flagga som anger om stiländringar ska upptäckas eller inte. |
|
|  | [isMarkNestedContent()](#isMarkNestedContent--) | Hämtar en flagga som anger om underordnade till de borttagna eller infogade elementen ska markeras som borttagna eller infogade. |
|
|  | [setMarkNestedContent(boolean value)](#setMarkNestedContent-boolean-) | Ställer in en flagga som anger om underordnade till de borttagna eller infogade elementen ska markeras som borttagna eller infogade. |
|
|  | [isCalculateCoordinates()](#isCalculateCoordinates--) | Hämtar en flagga som anger om koordinater för ändrade komponenter ska beräknas. |
|
|  | [setCalculateCoordinates(boolean value)](#setCalculateCoordinates-boolean-) | Ställer in en flagga som anger om koordinater för ändrade komponenter ska beräknas. |
|
|  | [isHeaderFootersComparison()](#isHeaderFootersComparison--) | Hämtar en flagga som anger om innehållet i sidhuvud/sidfot ska jämföras. |
|
|  | [setHeaderFootersComparison(boolean value)](#setHeaderFootersComparison-boolean-) | Ställer in en flagga som anger om innehållet i sidhuvud/sidfot ska jämföras. |
|
|  | [getDetalisationLevel()](#getDetalisationLevel--) | Hämtar en nivå av jämförelsedetaljering representerad som [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel). |
|
|  | [setDetalisationLevel(DetalisationLevel value)](#setDetalisationLevel-com.groupdocs.comparison.options.style.DetalisationLevel-) | Ställer in en nivå av jämförelsedetaljering representerad som [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel). |
|
|  | [isMarkChangedContent()](#isMarkChangedContent--) | Hämtar en flagga som anger om ramar för former i ordbehandling och för rektanglar i bilddokument ska användas. |
|
|  | [setMarkChangedContent(boolean value)](#setMarkChangedContent-boolean-) | Ställer in en flagga som anger om ramar för former i ordbehandling och för rektanglar i bilddokument ska användas. |
|
|  | [getInsertedItemStyle()](#getInsertedItemStyle--) | Hämtar en stilinställning som kommer att tillämpas på infogade objekt. |
|
|  | [setInsertedItemStyle(StyleSettings value)](#setInsertedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-) | Ställer in en stilinställning som kommer att tillämpas på infogade objekt. |
|
|  | [getDeletedItemStyle()](#getDeletedItemStyle--) | Hämtar en stilinställning som kommer att tillämpas på borttagna objekt. |
|
|  | [setDeletedItemStyle(StyleSettings value)](#setDeletedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-) | Ställer in en stilinställning som kommer att tillämpas på borttagna objekt. |
|
|  | [getChangedItemStyle()](#getChangedItemStyle--) | Hämtar en stilinställning som kommer att tillämpas på ändrade objekt. |
|
|  | [setChangedItemStyle(StyleSettings value)](#setChangedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-) | Ställer in en stilinställning som kommer att tillämpas på ändrade objekt. |
|
|  | [getSensitivityOfComparison()](#getSensitivityOfComparison--) | Hämtar en jämförelsesensitivitet. |
|
|  | [setSensitivityOfComparison(int value)](#setSensitivityOfComparison-int-) | Ställer in en jämförelsesensitivitet. |
|
|  | [setSensitivityOfComparisonForTables(Integer value)](#setSensitivityOfComparisonForTables-java.lang.Integer-) | Ställer in en jämförelsesensitivitet för tabeller. |
|
|  | [getSensitivityOfComparisonForTables()](#getSensitivityOfComparisonForTables--) | Hämtar en jämförelsesensitivitet för tabeller. |
|
|  | [setWordsSeparatorChars(char[] value)](#setWordsSeparatorChars-char---) | Ställer in en matris av avgränsare som kommer att användas för att dela upp text i ord. |
|
|  | [getPasswordSaveOption()](#getPasswordSaveOption--) | Hämtar ett lösenordssparalternativ som representeras av [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) objekt. |
|
|  | [setPasswordSaveOption(PasswordSaveOption value)](#setPasswordSaveOption-com.groupdocs.comparison.options.enums.PasswordSaveOption-) | Ställer in ett lösenordssparalternativ som representeras av [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) objekt. |
|
|  | [getOriginalSize()](#getOriginalSize--) | Hämtar originalstorlekar för jämförda dokument som representeras av [OriginalSize](../../com.groupdocs.comparison.options/originalsize) objekt. |
|
|  | [setOriginalSize(OriginalSize value)](#setOriginalSize-com.groupdocs.comparison.options.OriginalSize-) | Ställer in originalstorlekar för jämförda dokument som representeras av [OriginalSize](../../com.groupdocs.comparison.options/originalsize) objekt. |
|
|  | [getDiagramMasterSetting()](#getDiagramMasterSetting--) | Hämtar en inställning för master-sida för Diagram-dokument som representeras av [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) objekt. |
|
|  | [setDiagramMasterSetting(DiagramMasterSetting value)](#setDiagramMasterSetting-com.groupdocs.comparison.options.style.DiagramMasterSetting-) | Ställer in en inställning för master-sida för Diagram-dokument som representeras av [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) objekt. |
|
|  | [isDirectoryCompare()](#isDirectoryCompare--) | Returnerar en flagga som indikerar om katalogjämförelse är aktiverad. |
|
|  | [setDirectoryCompare(boolean directoryCompare)](#setDirectoryCompare-boolean-) | Ställer in en flagga som indikerar om katalogjämförelse ska vara aktiverad. |
|
|  | [isShowOnlyChanged()](#isShowOnlyChanged--) | Returnerar ett booleskt värde som indikerar om endast ändrade objekt ska visas. |
|
|  | [setShowOnlyChanged(boolean showOnlyChanged)](#setShowOnlyChanged-boolean-) | Ställer in värdet som indikerar om endast ändrade objekt ska visas. |
|
|  | [getFolderComparisonExtension()](#getFolderComparisonExtension--) | Hämtar formatet för den resulterande mappjämförelsfilen. |
|
|  | [setFolderComparisonExtension(FolderComparisonExtension folderComparisonExtension)](#setFolderComparisonExtension-com.groupdocs.comparison.options.enums.FolderComparisonExtension-) | Ställer in formatet för den resulterande mappjämförelsfilen. |
|
### CompareOptions() {#CompareOptions--}
```
public CompareOptions()
```


Initierar en ny instans av klassen CompareOptions.


### CompareOptions(StyleSettings insertedItemStyle, StyleSettings deletedItemStyle, StyleSettings changedItemStyle) {#CompareOptions-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-}
```
public CompareOptions(StyleSettings insertedItemStyle, StyleSettings deletedItemStyle, StyleSettings changedItemStyle)
```


Initierar en ny instans av klassen CompareOptions med inställningar för olika stilar.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | insertedItemStyle | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Stilinställningar för infogade objekt |
|
|  | deletedItemStyle | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Stilinställningar för raderade objekt |
|
|  | changedItemStyle | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Stilinställningar för ändrade stilobjekt |
|

### ignoreChangeSettings {#ignoreChangeSettings}
```
public IgnoreChangeSensitivitySettings ignoreChangeSettings
```


### getIgnoreChangeSettings() {#getIgnoreChangeSettings--}
```
public IgnoreChangeSensitivitySettings getIgnoreChangeSettings()
```


Hämta inställningar för att ignorera ändringar baserade på likhet.


**Returns:**
com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings - Inställningar för att ignorera förändringar.

### setIgnoreChangeSettings(IgnoreChangeSensitivitySettings ignoreChangeSettings) {#setIgnoreChangeSettings-com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings-}
```
public void setIgnoreChangeSettings(IgnoreChangeSensitivitySettings ignoreChangeSettings)
```


Ställer in inställningar för att ignorera ändringar baserade på likhet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | ignoreChangeSettings | com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings | Inställningar för att ignorera förändringar. |
|

### getUserMasterPath() {#getUserMasterPath--}
```
public String getUserMasterPath()
```


Hämtar sökvägen till användarens huvudmall för Diagram.


**Returns:**
java.lang.String - Sökvägen till användarens huvudmall för diagram.

### setUserMasterPath(String userMasterPath) {#setUserMasterPath-java.lang.String-}
```
public void setUserMasterPath(String userMasterPath)
```


Ställer in sökvägen till användarens huvudmall för Diagram.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | userMasterPath | java.lang.String | Sökvägen till användarens huvudmall för diagram. |
|

### getComparisonType() {#getComparisonType--}
```
public ComparisonType getComparisonType()
```


Hämtar en typ av käll- och mål-dokument som [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) objekt så att Comparison vet hur de ska jämföras.
När detta alternativ är inställt, [LoadOptions.getFileType()](../../com.groupdocs.comparison.options.load/loadoptions#getFileType--) alternativet kommer att utelämnas.


**Returns:**
[ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) - the type of source and target documents

### setComparisonType(ComparisonType comparisonType) {#setComparisonType-com.groupdocs.comparison.options.enums.ComparisonType-}
```
public void setComparisonType(ComparisonType comparisonType)
```


Ställer in en typ av käll- och mål-dokument som [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) objekt så att Comparison vet hur de ska jämföras.
När detta alternativ är inställt, [LoadOptions.setFileType(FileType)](../../com.groupdocs.comparison.options.load/loadoptions#setFileType-FileType-) alternativet kommer att utelämnas.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | comparisonType | [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) | Typen av käll- och mål dokument |
|

### getPaperSize() {#getPaperSize--}
```
public final PaperSize getPaperSize()
```


Hämtar en pappersstorlek i resultatsdokumentet som [PaperSize](../../com.groupdocs.comparison.options.enums/papersize) objekt.


**Returns:**
[PaperSize](../../com.groupdocs.comparison.options.enums/papersize) - the size of a paper in result document

### setPaperSize(PaperSize value) {#setPaperSize-com.groupdocs.comparison.options.enums.PaperSize-}
```
public final void setPaperSize(PaperSize value)
```


Ställer in en pappersstorlek i resultatsdokumentet som [PaperSize](../../com.groupdocs.comparison.options.enums/papersize) objekt.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [PaperSize](../../com.groupdocs.comparison.options.enums/papersize) | Storleken på ett papper i resultatdokumentet |
|

### getCalculateCoordinatesMode() {#getCalculateCoordinatesMode--}
```
public CalculateCoordinatesModeEnumeration getCalculateCoordinatesMode()
```


Hämtar ett beräkningskoordinatläge som [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) objekt.


**Returns:**
[CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) - the calculate coordinates mode

### setCalculateCoordinatesMode(CalculateCoordinatesModeEnumeration calculateCoordinatesMode) {#setCalculateCoordinatesMode-com.groupdocs.comparison.options.enums.CalculateCoordinatesModeEnumeration-}
```
public void setCalculateCoordinatesMode(CalculateCoordinatesModeEnumeration calculateCoordinatesMode)
```


Ställer in ett beräkningskoordinatläge som [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) objekt.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | calculateCoordinatesMode | [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) | Läget för beräkning av koordinater |
|

### isShowDeletedContent() {#isShowDeletedContent--}
```
public final boolean isShowDeletedContent()
```


Hämtar en flagga som indikerar om raderade komponenter ska visas i det resulterande dokumentet eller inte.


**Returns:**
boolean - true om borttagna komponenter i det resulterande dokumentet kommer att visas, annars false

### setShowDeletedContent(boolean value) {#setShowDeletedContent-boolean-}
```
public final void setShowDeletedContent(boolean value)
```


Ställer in en flagga som indikerar om raderade komponenter ska visas i det resulterande dokumentet eller inte.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | boolean | true om borttagna komponenter i det resulterande dokumentet bör visas, annars false |
|

### isShowInsertedContent() {#isShowInsertedContent--}
```
public final boolean isShowInsertedContent()
```


Hämtar en flagga som anger om infogade komponenter ska visas i det resulterande dokumentet eller inte.


**Returns:**
boolean - true om infogade komponenter i det resulterande dokumentet bör visas, annars false

### setShowInsertedContent(boolean value) {#setShowInsertedContent-boolean-}
```
public final void setShowInsertedContent(boolean value)
```


Ställer in en flagga som anger om infogade komponenter ska visas i det resulterande dokumentet eller inte.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | boolean | true om infogade komponenter i det resulterande dokumentet bör visas, annars false |
|

### isGenerateSummaryPage() {#isGenerateSummaryPage--}
```
public final boolean isGenerateSummaryPage()
```


Hämtar en flagga som anger om en sammanfattningssida med statistik över upptäckta ändringar ska läggas till i det resulterande dokumentet eller inte.


**Returns:**
boolean - true om sammanfattningssida kommer att läggas till, annars false

### setGenerateSummaryPage(boolean value) {#setGenerateSummaryPage-boolean-}
```
public final void setGenerateSummaryPage(boolean value)
```


Ställer in en flagga som anger om en sammanfattningssida med statistik över upptäckta ändringar ska läggas till i det resulterande dokumentet eller inte.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | boolean | true om sammanfattningssida bör läggas till, annars false |
|

### isExtendedSummaryPage() {#isExtendedSummaryPage--}
```
public boolean isExtendedSummaryPage()
```


Hämtar en flagga som anger om utökad filjämförelsinformation ska läggas till i sammanfattningssidan eller inte.


**Returns:**
boolean - true om utökad information om filjämförelse kommer att läggas till på sammanfattningssidan, annars false

### setExtendedSummaryPage(boolean value) {#setExtendedSummaryPage-boolean-}
```
public void setExtendedSummaryPage(boolean value)
```


Ställer in en flagga som anger om utökad filjämförelsinformation ska läggas till i sammanfattningssidan eller inte.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | boolean | true om utökad information om filjämförelse bör läggas till på sammanfattningssidan, annars false |
|

### isShowOnlySummaryPage() {#isShowOnlySummaryPage--}
```
public boolean isShowOnlySummaryPage()
```


Hämtar en flagga som anger om endast en sida med statistik över upptäckta ändringar ska lämnas i det resulterande dokumentet eller inte.


**Returns:**
boolean - true om i det resulterande dokumentet endast en sida med statistik över upptäckta förändringar kommer att finnas kvar, annars false

### setShowOnlySummaryPage(boolean value) {#setShowOnlySummaryPage-boolean-}
```
public void setShowOnlySummaryPage(boolean value)
```


Ställer in en flagga som anger om endast en sida med statistik över upptäckta ändringar ska lämnas i det resulterande dokumentet eller inte.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | boolean | true om i det resulterande dokumentet endast en sida med statistik över upptäckta förändringar bör finnas kvar, annars false |
|

### isDetectStyleChanges() {#isDetectStyleChanges--}
```
public final boolean isDetectStyleChanges()
```


Hämtar en flagga som anger om stiländringar ska upptäckas eller inte.


**Returns:**
boolean - true om stilförändringar kommer att upptäckas, annars false

### setDetectStyleChanges(boolean value) {#setDetectStyleChanges-boolean-}
```
public final void setDetectStyleChanges(boolean value)
```


Ställer in en flagga som anger om stiländringar ska upptäckas eller inte.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | boolean | true om stilförändringar bör upptäckas, annars false |
|

### isMarkNestedContent() {#isMarkNestedContent--}
```
public final boolean isMarkNestedContent()
```


Hämtar en flagga som anger om underordnade till de borttagna eller infogade elementen ska markeras som borttagna eller infogade.


**Returns:**
boolean - true om barnen till de borttagna eller infogade elementen kommer att markeras som borttagna eller infogade, annars false

### setMarkNestedContent(boolean value) {#setMarkNestedContent-boolean-}
```
public final void setMarkNestedContent(boolean value)
```


Ställer in en flagga som anger om underordnade till de borttagna eller infogade elementen ska markeras som borttagna eller infogade.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | boolean | true om barnen till de borttagna eller infogade elementen bör markeras som borttagna eller infogade, annars false |
|

### isCalculateCoordinates() {#isCalculateCoordinates--}
```
public final boolean isCalculateCoordinates()
```


Hämtar en flagga som anger om koordinater för ändrade komponenter ska beräknas.


**Returns:**
boolean - true om koordinater för ändrade komponenter kommer att beräknas, annars false

### setCalculateCoordinates(boolean value) {#setCalculateCoordinates-boolean-}
```
public final void setCalculateCoordinates(boolean value)
```


Ställer in en flagga som anger om koordinater för ändrade komponenter ska beräknas.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | boolean | true om koordinater för ändrade komponenter bör beräknas, annars false |
|

### isHeaderFootersComparison() {#isHeaderFootersComparison--}
```
public final boolean isHeaderFootersComparison()
```


Hämtar en flagga som anger om innehållet i sidhuvud/sidfot ska jämföras.


**Returns:**
boolean - true om innehållet i sidhuvud/sidfot kommer att jämföras, annars false

### setHeaderFootersComparison(boolean value) {#setHeaderFootersComparison-boolean-}
```
public final void setHeaderFootersComparison(boolean value)
```


Ställer in en flagga som anger om innehållet i sidhuvud/sidfot ska jämföras.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | boolean | true om innehållet i sidhuvud/sidfot ska jämföras, annars false |
|

### getDetalisationLevel() {#getDetalisationLevel--}
```
public final DetalisationLevel getDetalisationLevel()
```


Hämtar en nivå av jämförelsedetaljering representerad som [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel).
Standardvärdet är [DetalisationLevel.LOW](../../com.groupdocs.comparison.options.style/detalisationlevel#LOW).


**Returns:**
[DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) - the level of comparison detalization

### setDetalisationLevel(DetalisationLevel value) {#setDetalisationLevel-com.groupdocs.comparison.options.style.DetalisationLevel-}
```
public final void setDetalisationLevel(DetalisationLevel value)
```


Ställer in en nivå av jämförelsedetaljering representerad som [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel).
Standardvärdet är [DetalisationLevel.LOW](../../com.groupdocs.comparison.options.style/detalisationlevel#LOW)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) | Nivån på jämförelsedetaljering |
|

### isMarkChangedContent() {#isMarkChangedContent--}
```
public final boolean isMarkChangedContent()
```


Hämtar en flagga som anger om ramar för former i ordbehandling och för rektanglar i bilddokument ska användas.


**Returns:**
boolean - true om ramar kommer att användas, annars false

### setMarkChangedContent(boolean value) {#setMarkChangedContent-boolean-}
```
public final void setMarkChangedContent(boolean value)
```


Ställer in en flagga som anger om ramar för former i ordbehandling och för rektanglar i bilddokument ska användas.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | boolean | true om ramar ska användas, annars false |
|

### getInsertedItemStyle() {#getInsertedItemStyle--}
```
public final StyleSettings getInsertedItemStyle()
```


Hämtar en stilinställning som kommer att tillämpas på infogade objekt.


**Returns:**
[StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) - style settings of inserted items

### setInsertedItemStyle(StyleSettings value) {#setInsertedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-}
```
public final void setInsertedItemStyle(StyleSettings value)
```


Ställer in en stilinställning som kommer att tillämpas på infogade objekt.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Stilinställningar för infogade objekt |
|

### getDeletedItemStyle() {#getDeletedItemStyle--}
```
public final StyleSettings getDeletedItemStyle()
```


Hämtar en stilinställning som kommer att tillämpas på borttagna objekt.


**Returns:**
[StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) - style settings of deleted items

### setDeletedItemStyle(StyleSettings value) {#setDeletedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-}
```
public final void setDeletedItemStyle(StyleSettings value)
```


Ställer in en stilinställning som kommer att tillämpas på borttagna objekt.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Stilinställningar för borttagna objekt |
|

### getChangedItemStyle() {#getChangedItemStyle--}
```
public final StyleSettings getChangedItemStyle()
```


Hämtar en stilinställning som kommer att tillämpas på ändrade objekt.


**Returns:**
[StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) - style settings of changed items

### setChangedItemStyle(StyleSettings value) {#setChangedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-}
```
public final void setChangedItemStyle(StyleSettings value)
```


Ställer in en stilinställning som kommer att tillämpas på ändrade objekt.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Stilinställningar för ändrade objekt |
|

### getSensitivityOfComparison() {#getSensitivityOfComparison--}
```
public final int getSensitivityOfComparison()
```


Hämtar en jämförelsesensitivitet.
Procentandelen av borttagna och infogade element i två jämförda objekt i förhållande till alla element i dessa objekt.

* If this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Returns:**
int - känsligheten för jämförelse

### setSensitivityOfComparison(int value) {#setSensitivityOfComparison-int-}
```
public final void setSensitivityOfComparison(int value)
```


Ställer in en jämförelsesensitivitet.
Procentandelen av borttagna och infogade element i två jämförda objekt i förhållande till alla element i dessa objekt.

* If this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | int | Känsligheten för jämförelse |
|

### setSensitivityOfComparisonForTables(Integer value) {#setSensitivityOfComparisonForTables-java.lang.Integer-}
```
public void setSensitivityOfComparisonForTables(Integer value)
```


Ställer in en jämförelsesensitivitet för tabeller.
Om värdet är null används SensitivityOfComparison istället. Procentandelen av borttagna och infogade element i två jämförda objekt i förhållande till alla element i dessa objekt.

* if this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs, if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | java.lang.Integer | Känsligheten för jämförelse av tabeller |
|

### getSensitivityOfComparisonForTables() {#getSensitivityOfComparisonForTables--}
```
public final Integer getSensitivityOfComparisonForTables()
```


Hämtar en jämförelsesensitivitet för tabeller.
Om värdet är null används SensitivityOfComparison istället. Procentandelen av borttagna och infogade element i två jämförda objekt i förhållande till alla element i dessa objekt.

* if this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs, if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Returns:**
java.lang.Integer - Känsligheten för jämförelse av tabeller

### setWordsSeparatorChars(char[] value) {#setWordsSeparatorChars-char---}
```
public final void setWordsSeparatorChars(char[] value)
```


Ställer in en matris av avgränsare som kommer att användas för att dela upp text i ord.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | char[] | Arrayen av avgränsare för att dela upp text i ord |
|

### getPasswordSaveOption() {#getPasswordSaveOption--}
```
public final PasswordSaveOption getPasswordSaveOption()
```


Hämtar ett lösenordssparalternativ som representeras av [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) objekt.


**Returns:**
[PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) - the password save option

### setPasswordSaveOption(PasswordSaveOption value) {#setPasswordSaveOption-com.groupdocs.comparison.options.enums.PasswordSaveOption-}
```
public final void setPasswordSaveOption(PasswordSaveOption value)
```


Ställer in ett lösenordssparalternativ som representeras av [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) objekt.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) | Alternativet för att spara lösenord |
|

### getOriginalSize() {#getOriginalSize--}
```
public final OriginalSize getOriginalSize()
```


Hämtar originalstorlekar för jämförda dokument som representeras av [OriginalSize](../../com.groupdocs.comparison.options/originalsize) objekt.


**Returns:**
[OriginalSize](../../com.groupdocs.comparison.options/originalsize) - the original size of documents

### setOriginalSize(OriginalSize value) {#setOriginalSize-com.groupdocs.comparison.options.OriginalSize-}
```
public final void setOriginalSize(OriginalSize value)
```


Ställer in originalstorlekar för jämförda dokument som representeras av [OriginalSize](../../com.groupdocs.comparison.options/originalsize) objekt.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [OriginalSize](../../com.groupdocs.comparison.options/originalsize) | Den ursprungliga storleken på dokumenten |
|

### getDiagramMasterSetting() {#getDiagramMasterSetting--}
```
public final DiagramMasterSetting getDiagramMasterSetting()
```


Hämtar en inställning för master-sida för Diagram-dokument som representeras av [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) objekt.


**Returns:**
[DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) - the diagram master page setting

### setDiagramMasterSetting(DiagramMasterSetting value) {#setDiagramMasterSetting-com.groupdocs.comparison.options.style.DiagramMasterSetting-}
```
public final void setDiagramMasterSetting(DiagramMasterSetting value)
```


Ställer in en inställning för master-sida för Diagram-dokument som representeras av [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) objekt.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) | Inställning för diagrammets huvudsida |
|

### isDirectoryCompare() {#isDirectoryCompare--}
```
public boolean isDirectoryCompare()
```


Returnerar en flagga som indikerar om katalogjämförelse är aktiverad.


**Returns:**
boolean - true om katalogjämförelse är aktiverad, annars false

### setDirectoryCompare(boolean directoryCompare) {#setDirectoryCompare-boolean-}
```
public void setDirectoryCompare(boolean directoryCompare)
```


Ställer in en flagga som indikerar om katalogjämförelse ska vara aktiverad.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | directoryCompare | boolean | true om katalogjämförelse ska aktiveras, annars false |
|

### isShowOnlyChanged() {#isShowOnlyChanged--}
```
public boolean isShowOnlyChanged()
```


Returnerar ett booleskt värde som indikerar om endast ändrade objekt ska visas.


**Returns:**
boolean - true om endast ändrade objekt ska visas, annars false

### setShowOnlyChanged(boolean showOnlyChanged) {#setShowOnlyChanged-boolean-}
```
public void setShowOnlyChanged(boolean showOnlyChanged)
```


Ställer in värdet som indikerar om endast ändrade objekt ska visas.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | showOnlyChanged | boolean | det booleska värdet som indikerar om endast ändrade objekt ska visas |
|

### getFolderComparisonExtension() {#getFolderComparisonExtension--}
```
public FolderComparisonExtension getFolderComparisonExtension()
```


Hämtar formatet för den resulterande mappjämförelsfilen.


**Returns:**
com.groupdocs.comparison.options.enums.FolderComparisonExtension - FolderComparisonExtension som representerar formatet för den resulterande mappjämförelsfilen

### setFolderComparisonExtension(FolderComparisonExtension folderComparisonExtension) {#setFolderComparisonExtension-com.groupdocs.comparison.options.enums.FolderComparisonExtension-}
```
public void setFolderComparisonExtension(FolderComparisonExtension folderComparisonExtension)
```


Ställer in formatet för den resulterande mappjämförelsfilen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | folderComparisonExtension | com.groupdocs.comparison.options.enums.FolderComparisonExtension | FolderComparisonExtension som representerar formatet för den resulterande mappjämförelsfilen |
|

