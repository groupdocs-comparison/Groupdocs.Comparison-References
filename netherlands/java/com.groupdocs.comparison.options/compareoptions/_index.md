---
title: "CompareOptions"
second_title: "GroupDocs.Comparison voor Java API-referentie"
description: "Staat toe het proces van documentvergelijking te configureren."
type: docs
weight: 11
url: /nl/java/com.groupdocs.comparison.options/compareoptions/
---
**Inheritance:**
java.lang.Object
```
public class CompareOptions
```

Staat toe het proces van documentvergelijking te configureren.


Voorbeeldgebruik:

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


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [CompareOptions()](#CompareOptions--) | Initialiseert een nieuw exemplaar van de CompareOptions-klasse. |
|
|  | [CompareOptions(StyleSettings insertedItemStyle, StyleSettings deletedItemStyle, StyleSettings changedItemStyle)](#CompareOptions-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-) | Initialiseert een nieuw exemplaar van de CompareOptions-klasse met instellingen voor verschillende stijlen. |
|
## Velden

| Veld | Beschrijving |
| --- | --- |
| [ignoreChangeSettings](#ignoreChangeSettings) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getIgnoreChangeSettings()](#getIgnoreChangeSettings--) | Haalt instellingen op om wijzigingen op basis van gelijkenis te negeren. |
|
|  | [setIgnoreChangeSettings(IgnoreChangeSensitivitySettings ignoreChangeSettings)](#setIgnoreChangeSettings-com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings-) | Stelt instellingen in om wijzigingen op basis van gelijkenis te negeren. |
|
|  | [getUserMasterPath()](#getUserMasterPath--) | Haalt het pad op naar de master-sjabloon van de gebruiker voor Diagrammen. |
|
|  | [setUserMasterPath(String userMasterPath)](#setUserMasterPath-java.lang.String-) | Stelt het pad in naar de master-sjabloon van de gebruiker voor Diagrammen. |
|
|  | [getComparisonType()](#getComparisonType--) | Haalt een type van bron- en doeldocumenten op als [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) object zodat Comparison weet hoe deze te vergelijken. |
|
|  | [setComparisonType(ComparisonType comparisonType)](#setComparisonType-com.groupdocs.comparison.options.enums.ComparisonType-) | Stelt een type van bron- en doeldocumenten in als [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) object zodat Comparison weet hoe deze te vergelijken. |
|
|  | [getPaperSize()](#getPaperSize--) | Haalt een papierformaat op in het resultaatdocument als [PaperSize](../../com.groupdocs.comparison.options.enums/papersize) object. |
|
|  | [setPaperSize(PaperSize value)](#setPaperSize-com.groupdocs.comparison.options.enums.PaperSize-) | Stelt een papierformaat in in het resultaatdocument als [PaperSize](../../com.groupdocs.comparison.options.enums/papersize) object. |
|
|  | [getCalculateCoordinatesMode()](#getCalculateCoordinatesMode--) | Haalt een bereken-coördinaten-modus op als [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) object. |
|
|  | [setCalculateCoordinatesMode(CalculateCoordinatesModeEnumeration calculateCoordinatesMode)](#setCalculateCoordinatesMode-com.groupdocs.comparison.options.enums.CalculateCoordinatesModeEnumeration-) | Stelt een bereken-coördinaten-modus in als [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) object. |
|
|  | [isShowDeletedContent()](#isShowDeletedContent--) | Haalt een vlag op die aangeeft of verwijderde componenten in het resulterende document moeten worden weergegeven of niet. |
|
|  | [setShowDeletedContent(boolean value)](#setShowDeletedContent-boolean-) | Stelt een vlag in die aangeeft of verwijderde componenten in het resulterende document moeten worden weergegeven of niet. |
|
|  | [isShowInsertedContent()](#isShowInsertedContent--) | Haalt een vlag op die aangeeft of ingevoegde componenten in het resulterende document moeten worden weergegeven of niet. |
|
|  | [setShowInsertedContent(boolean value)](#setShowInsertedContent-boolean-) | Stelt een vlag in die aangeeft of ingevoegde componenten in het resulterende document moeten worden weergegeven of niet. |
|
|  | [isGenerateSummaryPage()](#isGenerateSummaryPage--) | Haalt een vlag op die aangeeft of een samenvattingspagina met statistieken van gedetecteerde wijzigingen aan het resulterende document moet worden toegevoegd of niet. |
|
|  | [setGenerateSummaryPage(boolean value)](#setGenerateSummaryPage-boolean-) | Stelt een vlag in die aangeeft of een samenvattingspagina met statistieken van gedetecteerde wijzigingen aan het resulterende document moet worden toegevoegd of niet. |
|
|  | [isExtendedSummaryPage()](#isExtendedSummaryPage--) | Haalt een vlag op die aangeeft of uitgebreide bestandsvergelijkingsinformatie aan de samenvattingspagina moet worden toegevoegd of niet. |
|
|  | [setExtendedSummaryPage(boolean value)](#setExtendedSummaryPage-boolean-) | Stelt een vlag in die aangeeft of uitgebreide bestandsvergelijkingsinformatie aan de samenvattingspagina moet worden toegevoegd of niet. |
|
|  | [isShowOnlySummaryPage()](#isShowOnlySummaryPage--) | Haalt een vlag op die aangeeft of alleen een pagina met statistieken van gedetecteerde wijzigingen in het resulterende document moet worden achtergelaten of niet. |
|
|  | [setShowOnlySummaryPage(boolean value)](#setShowOnlySummaryPage-boolean-) | Stelt een vlag in die aangeeft of alleen een pagina met statistieken van gedetecteerde wijzigingen in het resulterende document moet worden achtergelaten of niet. |
|
|  | [isDetectStyleChanges()](#isDetectStyleChanges--) | Haalt een vlag op die aangeeft of stijlwijzigingen moeten worden gedetecteerd of niet. |
|
|  | [setDetectStyleChanges(boolean value)](#setDetectStyleChanges-boolean-) | Stelt een vlag in die aangeeft of stijlwijzigingen moeten worden gedetecteerd of niet. |
|
|  | [isMarkNestedContent()](#isMarkNestedContent--) | Haalt een vlag op die aangeeft of de kinderen van de verwijderde of ingevoegde elementen als verwijderd of ingevoegd moeten worden gemarkeerd. |
|
|  | [setMarkNestedContent(boolean value)](#setMarkNestedContent-boolean-) | Stelt een vlag in die aangeeft of de kinderen van de verwijderde of ingevoegde elementen als verwijderd of ingevoegd moeten worden gemarkeerd. |
|
|  | [isCalculateCoordinates()](#isCalculateCoordinates--) | Haalt een vlag op die aangeeft of coördinaten voor gewijzigde componenten moeten worden berekend. |
|
|  | [setCalculateCoordinates(boolean value)](#setCalculateCoordinates-boolean-) | Stelt een vlag in die aangeeft of coördinaten voor gewijzigde componenten moeten worden berekend. |
|
|  | [isHeaderFootersComparison()](#isHeaderFootersComparison--) | Haalt een vlag op die aangeeft of header/footer-inhoud moet worden vergeleken. |
|
|  | [setHeaderFootersComparison(boolean value)](#setHeaderFootersComparison-boolean-) | Stelt een vlag in die aangeeft of header/footer-inhoud moet worden vergeleken. |
|
|  | [getDetalisationLevel()](#getDetalisationLevel--) | Haalt een detailniveau van vergelijking op, weergegeven als [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel). |
|
|  | [setDetalisationLevel(DetalisationLevel value)](#setDetalisationLevel-com.groupdocs.comparison.options.style.DetalisationLevel-) | Stelt een detailniveau van vergelijking in, weergegeven als [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel). |
|
|  | [isMarkChangedContent()](#isMarkChangedContent--) | Haalt een vlag op die aangeeft of frames voor vormen in Word Processing en voor rechthoeken in afbeeldingsdocumenten zullen worden gebruikt. |
|
|  | [setMarkChangedContent(boolean value)](#setMarkChangedContent-boolean-) | Stelt een vlag in die aangeeft of frames voor vormen in Word Processing en voor rechthoeken in afbeeldingsdocumenten zullen worden gebruikt. |
|
|  | [getInsertedItemStyle()](#getInsertedItemStyle--) | Haalt een stijlinstelling op die op ingevoegde items zal worden toegepast. |
|
|  | [setInsertedItemStyle(StyleSettings value)](#setInsertedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-) | Stelt een stijlinstelling in die op ingevoegde items zal worden toegepast. |
|
|  | [getDeletedItemStyle()](#getDeletedItemStyle--) | Haalt een stijlinstelling op die op verwijderde items zal worden toegepast. |
|
|  | [setDeletedItemStyle(StyleSettings value)](#setDeletedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-) | Stelt een stijlinstelling in die op verwijderde items zal worden toegepast. |
|
|  | [getChangedItemStyle()](#getChangedItemStyle--) | Haalt een stijlinstelling op die op gewijzigde items zal worden toegepast. |
|
|  | [setChangedItemStyle(StyleSettings value)](#setChangedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-) | Stelt een stijlinstelling in die wordt toegepast op gewijzigde items. |
|
|  | [getSensitivityOfComparison()](#getSensitivityOfComparison--) | Haalt de gevoeligheid van de vergelijking op. |
|
|  | [setSensitivityOfComparison(int value)](#setSensitivityOfComparison-int-) | Stelt de gevoeligheid van de vergelijking in. |
|
|  | [setSensitivityOfComparisonForTables(Integer value)](#setSensitivityOfComparisonForTables-java.lang.Integer-) | Stelt de gevoeligheid van de vergelijking voor tabellen in. |
|
|  | [getSensitivityOfComparisonForTables()](#getSensitivityOfComparisonForTables--) | Haalt de gevoeligheid van de vergelijking voor tabellen op. |
|
|  | [setWordsSeparatorChars(char[] value)](#setWordsSeparatorChars-char---) | Stelt een array van delimiters in die wordt gebruikt om tekst in woorden te splitsen. |
|
|  | [getPasswordSaveOption()](#getPasswordSaveOption--) | Haalt een wachtwoordbewaaroptie op die wordt weergegeven door het [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) object. |
|
|  | [setPasswordSaveOption(PasswordSaveOption value)](#setPasswordSaveOption-com.groupdocs.comparison.options.enums.PasswordSaveOption-) | Stelt een wachtwoordbewaaroptie in die wordt weergegeven door het [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) object. |
|
|  | [getOriginalSize()](#getOriginalSize--) | Haalt de originele afmetingen van vergeleken documenten op die worden weergegeven door het [OriginalSize](../../com.groupdocs.comparison.options/originalsize) object. |
|
|  | [setOriginalSize(OriginalSize value)](#setOriginalSize-com.groupdocs.comparison.options.OriginalSize-) | Stelt de originele afmetingen van vergeleken documenten in die worden weergegeven door het [OriginalSize](../../com.groupdocs.comparison.options/originalsize) object. |
|
|  | [getDiagramMasterSetting()](#getDiagramMasterSetting--) | Haalt een instelling van de masterpagina voor Diagram-documenten op die wordt weergegeven door het [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) object. |
|
|  | [setDiagramMasterSetting(DiagramMasterSetting value)](#setDiagramMasterSetting-com.groupdocs.comparison.options.style.DiagramMasterSetting-) | Stelt een instelling van de masterpagina voor Diagram-documenten in die wordt weergegeven door het [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) object. |
|
|  | [isDirectoryCompare()](#isDirectoryCompare--) | Retourneert een vlag die aangeeft of mapvergelijking is ingeschakeld. |
|
|  | [setDirectoryCompare(boolean directoryCompare)](#setDirectoryCompare-boolean-) | Stelt een vlag in die aangeeft of mapvergelijking moet worden ingeschakeld. |
|
|  | [isShowOnlyChanged()](#isShowOnlyChanged--) | Retourneert een booleaanse waarde die aangeeft of alleen gewijzigde items moeten worden weergegeven. |
|
|  | [setShowOnlyChanged(boolean showOnlyChanged)](#setShowOnlyChanged-boolean-) | Stelt de waarde in die aangeeft of alleen gewijzigde items moeten worden weergegeven. |
|
|  | [getFolderComparisonExtension()](#getFolderComparisonExtension--) | Haalt het formaat van het resulterende mapvergelijkingsbestand op. |
|
|  | [setFolderComparisonExtension(FolderComparisonExtension folderComparisonExtension)](#setFolderComparisonExtension-com.groupdocs.comparison.options.enums.FolderComparisonExtension-) | Stelt het formaat van het resulterende mapvergelijkingsbestand in. |
|
### CompareOptions() {#CompareOptions--}
```
public CompareOptions()
```


Initialiseert een nieuw exemplaar van de CompareOptions-klasse.


### CompareOptions(StyleSettings insertedItemStyle, StyleSettings deletedItemStyle, StyleSettings changedItemStyle) {#CompareOptions-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-}
```
public CompareOptions(StyleSettings insertedItemStyle, StyleSettings deletedItemStyle, StyleSettings changedItemStyle)
```


Initialiseert een nieuw exemplaar van de CompareOptions-klasse met instellingen voor verschillende stijlen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | insertedItemStyle | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Stijlinstellingen voor ingevoegde items |
|
|  | deletedItemStyle | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Stijlinstellingen voor verwijderde items |
|
|  | changedItemStyle | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Stijlinstellingen voor gewijzigde stijlitems |
|

### ignoreChangeSettings {#ignoreChangeSettings}
```
public IgnoreChangeSensitivitySettings ignoreChangeSettings
```


### getIgnoreChangeSettings() {#getIgnoreChangeSettings--}
```
public IgnoreChangeSensitivitySettings getIgnoreChangeSettings()
```


Haalt instellingen op om wijzigingen op basis van gelijkenis te negeren.


**Returns:**
com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings - Instellingen om wijzigingen te negeren.

### setIgnoreChangeSettings(IgnoreChangeSensitivitySettings ignoreChangeSettings) {#setIgnoreChangeSettings-com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings-}
```
public void setIgnoreChangeSettings(IgnoreChangeSensitivitySettings ignoreChangeSettings)
```


Stelt instellingen in om wijzigingen op basis van gelijkenis te negeren.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | ignoreChangeSettings | com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings | Instellingen om wijzigingen te negeren. |
|

### getUserMasterPath() {#getUserMasterPath--}
```
public String getUserMasterPath()
```


Haalt het pad op naar de master-sjabloon van de gebruiker voor Diagrammen.


**Returns:**
java.lang.String - Het pad naar de sjabloon van de gebruikersmaster voor Diagrammen.

### setUserMasterPath(String userMasterPath) {#setUserMasterPath-java.lang.String-}
```
public void setUserMasterPath(String userMasterPath)
```


Stelt het pad in naar de master-sjabloon van de gebruiker voor Diagrammen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | userMasterPath | java.lang.String | Het pad naar de sjabloon van de gebruikersmaster voor Diagrammen. |
|

### getComparisonType() {#getComparisonType--}
```
public ComparisonType getComparisonType()
```


Haalt een type van bron- en doeldocumenten op als [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) object zodat Comparison weet hoe deze te vergelijken.
Wanneer deze optie is ingesteld, zal de optie [LoadOptions.getFileType()](../../com.groupdocs.comparison.options.load/loadoptions#getFileType--) worden weggelaten.


**Returns:**
[ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) - the type of source and target documents

### setComparisonType(ComparisonType comparisonType) {#setComparisonType-com.groupdocs.comparison.options.enums.ComparisonType-}
```
public void setComparisonType(ComparisonType comparisonType)
```


Stelt een type van bron- en doeldocumenten in als [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) object zodat Comparison weet hoe deze te vergelijken.
Wanneer deze optie is ingesteld, zal de optie [LoadOptions.setFileType(FileType)](../../com.groupdocs.comparison.options.load/loadoptions#setFileType-FileType-) worden weggelaten.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | comparisonType | [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) | Het type van bron- en doeldocumenten |
|

### getPaperSize() {#getPaperSize--}
```
public final PaperSize getPaperSize()
```


Haalt een papierformaat op in het resultaatdocument als [PaperSize](../../com.groupdocs.comparison.options.enums/papersize) object.


**Returns:**
[PaperSize](../../com.groupdocs.comparison.options.enums/papersize) - the size of a paper in result document

### setPaperSize(PaperSize value) {#setPaperSize-com.groupdocs.comparison.options.enums.PaperSize-}
```
public final void setPaperSize(PaperSize value)
```


Stelt een papierformaat in in het resultaatdocument als [PaperSize](../../com.groupdocs.comparison.options.enums/papersize) object.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [PaperSize](../../com.groupdocs.comparison.options.enums/papersize) | De grootte van een papier in het resultaatdocument |
|

### getCalculateCoordinatesMode() {#getCalculateCoordinatesMode--}
```
public CalculateCoordinatesModeEnumeration getCalculateCoordinatesMode()
```


Haalt een bereken-coördinaten-modus op als [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) object.


**Returns:**
[CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) - the calculate coordinates mode

### setCalculateCoordinatesMode(CalculateCoordinatesModeEnumeration calculateCoordinatesMode) {#setCalculateCoordinatesMode-com.groupdocs.comparison.options.enums.CalculateCoordinatesModeEnumeration-}
```
public void setCalculateCoordinatesMode(CalculateCoordinatesModeEnumeration calculateCoordinatesMode)
```


Stelt een bereken-coördinaten-modus in als [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) object.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | calculateCoordinatesMode | [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) | De modus voor het berekenen van coördinaten |
|

### isShowDeletedContent() {#isShowDeletedContent--}
```
public final boolean isShowDeletedContent()
```


Haalt een vlag op die aangeeft of verwijderde componenten in het resulterende document moeten worden weergegeven of niet.


**Returns:**
boolean - true als verwijderde componenten in het resulterende document worden weergegeven, anders false

### setShowDeletedContent(boolean value) {#setShowDeletedContent-boolean-}
```
public final void setShowDeletedContent(boolean value)
```


Stelt een vlag in die aangeeft of verwijderde componenten in het resulterende document moeten worden weergegeven of niet.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | boolean | true als verwijderde componenten in het resulterende document moeten worden weergegeven, anders false |
|

### isShowInsertedContent() {#isShowInsertedContent--}
```
public final boolean isShowInsertedContent()
```


Haalt een vlag op die aangeeft of ingevoegde componenten in het resulterende document moeten worden weergegeven of niet.


**Returns:**
boolean - true als ingevoegde componenten in het resulterende document moeten worden weergegeven, anders false

### setShowInsertedContent(boolean value) {#setShowInsertedContent-boolean-}
```
public final void setShowInsertedContent(boolean value)
```


Stelt een vlag in die aangeeft of ingevoegde componenten in het resulterende document moeten worden weergegeven of niet.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | boolean | true als ingevoegde componenten in het resulterende document moeten worden weergegeven, anders false |
|

### isGenerateSummaryPage() {#isGenerateSummaryPage--}
```
public final boolean isGenerateSummaryPage()
```


Haalt een vlag op die aangeeft of een samenvattingspagina met statistieken van gedetecteerde wijzigingen aan het resulterende document moet worden toegevoegd of niet.


**Returns:**
boolean - true als een samenvattingspagina wordt toegevoegd, anders false

### setGenerateSummaryPage(boolean value) {#setGenerateSummaryPage-boolean-}
```
public final void setGenerateSummaryPage(boolean value)
```


Stelt een vlag in die aangeeft of een samenvattingspagina met statistieken van gedetecteerde wijzigingen aan het resulterende document moet worden toegevoegd of niet.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | boolean | true als een samenvattingspagina moet worden toegevoegd, anders false |
|

### isExtendedSummaryPage() {#isExtendedSummaryPage--}
```
public boolean isExtendedSummaryPage()
```


Haalt een vlag op die aangeeft of uitgebreide bestandsvergelijkingsinformatie aan de samenvattingspagina moet worden toegevoegd of niet.


**Returns:**
boolean - true als uitgebreide bestandsvergelijkingsinformatie wordt toegevoegd aan de samenvattingspagina, anders false

### setExtendedSummaryPage(boolean value) {#setExtendedSummaryPage-boolean-}
```
public void setExtendedSummaryPage(boolean value)
```


Stelt een vlag in die aangeeft of uitgebreide bestandsvergelijkingsinformatie aan de samenvattingspagina moet worden toegevoegd of niet.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | boolean | true als uitgebreide bestandsvergelijkingsinformatie moet worden toegevoegd aan de samenvattingspagina, anders false |
|

### isShowOnlySummaryPage() {#isShowOnlySummaryPage--}
```
public boolean isShowOnlySummaryPage()
```


Haalt een vlag op die aangeeft of alleen een pagina met statistieken van gedetecteerde wijzigingen in het resulterende document moet worden achtergelaten of niet.


**Returns:**
boolean - true als in het resulterende document alleen een pagina met statistieken van gedetecteerde wijzigingen overblijft, anders false

### setShowOnlySummaryPage(boolean value) {#setShowOnlySummaryPage-boolean-}
```
public void setShowOnlySummaryPage(boolean value)
```


Stelt een vlag in die aangeeft of alleen een pagina met statistieken van gedetecteerde wijzigingen in het resulterende document moet worden achtergelaten of niet.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | boolean | true als in het resulterende document alleen een pagina met statistieken van gedetecteerde wijzigingen moet overblijven, anders false |
|

### isDetectStyleChanges() {#isDetectStyleChanges--}
```
public final boolean isDetectStyleChanges()
```


Haalt een vlag op die aangeeft of stijlwijzigingen moeten worden gedetecteerd of niet.


**Returns:**
boolean - true als stijlwijzigingen worden gedetecteerd, anders false

### setDetectStyleChanges(boolean value) {#setDetectStyleChanges-boolean-}
```
public final void setDetectStyleChanges(boolean value)
```


Stelt een vlag in die aangeeft of stijlwijzigingen moeten worden gedetecteerd of niet.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | boolean | true als stijlwijzigingen moeten worden gedetecteerd, anders false |
|

### isMarkNestedContent() {#isMarkNestedContent--}
```
public final boolean isMarkNestedContent()
```


Haalt een vlag op die aangeeft of de kinderen van de verwijderde of ingevoegde elementen als verwijderd of ingevoegd moeten worden gemarkeerd.


**Returns:**
boolean - true als de onderliggende elementen van de verwijderde of ingevoegde elementen worden gemarkeerd als verwijderd of ingevoegd, anders false

### setMarkNestedContent(boolean value) {#setMarkNestedContent-boolean-}
```
public final void setMarkNestedContent(boolean value)
```


Stelt een vlag in die aangeeft of de kinderen van de verwijderde of ingevoegde elementen als verwijderd of ingevoegd moeten worden gemarkeerd.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | boolean | true als de onderliggende elementen van de verwijderde of ingevoegde elementen moeten worden gemarkeerd als verwijderd of ingevoegd, anders false |
|

### isCalculateCoordinates() {#isCalculateCoordinates--}
```
public final boolean isCalculateCoordinates()
```


Haalt een vlag op die aangeeft of coördinaten voor gewijzigde componenten moeten worden berekend.


**Returns:**
boolean - true als coördinaten voor gewijzigde componenten worden berekend, anders false

### setCalculateCoordinates(boolean value) {#setCalculateCoordinates-boolean-}
```
public final void setCalculateCoordinates(boolean value)
```


Stelt een vlag in die aangeeft of coördinaten voor gewijzigde componenten moeten worden berekend.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | boolean | true als coördinaten voor gewijzigde componenten moeten worden berekend, anders false |
|

### isHeaderFootersComparison() {#isHeaderFootersComparison--}
```
public final boolean isHeaderFootersComparison()
```


Haalt een vlag op die aangeeft of header/footer-inhoud moet worden vergeleken.


**Returns:**
boolean - true als header/footer-inhoud wordt vergeleken, anders false

### setHeaderFootersComparison(boolean value) {#setHeaderFootersComparison-boolean-}
```
public final void setHeaderFootersComparison(boolean value)
```


Stelt een vlag in die aangeeft of header/footer-inhoud moet worden vergeleken.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | boolean | true als de inhoud van header/footer moet worden vergeleken, anders false |
|

### getDetalisationLevel() {#getDetalisationLevel--}
```
public final DetalisationLevel getDetalisationLevel()
```


Haalt een detailniveau van vergelijking op, weergegeven als [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel).
Standaardwaarde is [DetalisationLevel.LOW](../../com.groupdocs.comparison.options.style/detalisationlevel#LOW).


**Returns:**
[DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) - the level of comparison detalization

### setDetalisationLevel(DetalisationLevel value) {#setDetalisationLevel-com.groupdocs.comparison.options.style.DetalisationLevel-}
```
public final void setDetalisationLevel(DetalisationLevel value)
```


Stelt een detailniveau van vergelijking in, weergegeven als [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel).
Standaardwaarde is [DetalisationLevel.LOW](../../com.groupdocs.comparison.options.style/detalisationlevel#LOW)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) | Het niveau van detailering van de vergelijking |
|

### isMarkChangedContent() {#isMarkChangedContent--}
```
public final boolean isMarkChangedContent()
```


Haalt een vlag op die aangeeft of frames voor vormen in Word Processing en voor rechthoeken in afbeeldingsdocumenten zullen worden gebruikt.


**Returns:**
boolean - true als frames worden gebruikt, anders false

### setMarkChangedContent(boolean value) {#setMarkChangedContent-boolean-}
```
public final void setMarkChangedContent(boolean value)
```


Stelt een vlag in die aangeeft of frames voor vormen in Word Processing en voor rechthoeken in afbeeldingsdocumenten zullen worden gebruikt.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | boolean | true als frames moeten worden gebruikt, anders false |
|

### getInsertedItemStyle() {#getInsertedItemStyle--}
```
public final StyleSettings getInsertedItemStyle()
```


Haalt een stijlinstelling op die op ingevoegde items zal worden toegepast.


**Returns:**
[StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) - style settings of inserted items

### setInsertedItemStyle(StyleSettings value) {#setInsertedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-}
```
public final void setInsertedItemStyle(StyleSettings value)
```


Stelt een stijlinstelling in die op ingevoegde items zal worden toegepast.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Stijlinstellingen van ingevoegde items |
|

### getDeletedItemStyle() {#getDeletedItemStyle--}
```
public final StyleSettings getDeletedItemStyle()
```


Haalt een stijlinstelling op die op verwijderde items zal worden toegepast.


**Returns:**
[StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) - style settings of deleted items

### setDeletedItemStyle(StyleSettings value) {#setDeletedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-}
```
public final void setDeletedItemStyle(StyleSettings value)
```


Stelt een stijlinstelling in die op verwijderde items zal worden toegepast.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Stijlinstellingen van verwijderde items |
|

### getChangedItemStyle() {#getChangedItemStyle--}
```
public final StyleSettings getChangedItemStyle()
```


Haalt een stijlinstelling op die op gewijzigde items zal worden toegepast.


**Returns:**
[StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) - style settings of changed items

### setChangedItemStyle(StyleSettings value) {#setChangedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-}
```
public final void setChangedItemStyle(StyleSettings value)
```


Stelt een stijlinstelling in die wordt toegepast op gewijzigde items.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Stijlinstellingen van gewijzigde items |
|

### getSensitivityOfComparison() {#getSensitivityOfComparison--}
```
public final int getSensitivityOfComparison()
```


Haalt de gevoeligheid van de vergelijking op.
Het percentage van verwijderde en ingevoegde elementen van twee te vergelijken objecten ten opzichte van alle elementen van deze objecten.

* If this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Returns:**
int - de gevoeligheid van de vergelijking

### setSensitivityOfComparison(int value) {#setSensitivityOfComparison-int-}
```
public final void setSensitivityOfComparison(int value)
```


Stelt de gevoeligheid van de vergelijking in.
Het percentage van verwijderde en ingevoegde elementen van twee te vergelijken objecten ten opzichte van alle elementen van deze objecten.

* If this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | int | De gevoeligheid van de vergelijking |
|

### setSensitivityOfComparisonForTables(Integer value) {#setSensitivityOfComparisonForTables-java.lang.Integer-}
```
public void setSensitivityOfComparisonForTables(Integer value)
```


Stelt de gevoeligheid van de vergelijking voor tabellen in.
Als de waarde null is, wordt SensitivityOfComparison gebruikt. Het percentage van verwijderde en ingevoegde elementen van twee te vergelijken objecten ten opzichte van alle elementen van deze objecten.

* if this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs, if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.lang.Integer | De gevoeligheid van de vergelijking voor tabellen |
|

### getSensitivityOfComparisonForTables() {#getSensitivityOfComparisonForTables--}
```
public final Integer getSensitivityOfComparisonForTables()
```


Haalt de gevoeligheid van de vergelijking voor tabellen op.
Als de waarde null is, wordt SensitivityOfComparison gebruikt. Het percentage van verwijderde en ingevoegde elementen van twee te vergelijken objecten ten opzichte van alle elementen van deze objecten.

* if this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs, if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Returns:**
java.lang.Integer - De gevoeligheid van de vergelijking voor tabellen

### setWordsSeparatorChars(char[] value) {#setWordsSeparatorChars-char---}
```
public final void setWordsSeparatorChars(char[] value)
```


Stelt een array van delimiters in die wordt gebruikt om tekst in woorden te splitsen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | char[] | De array van scheidingstekens om tekst in woorden te splitsen |
|

### getPasswordSaveOption() {#getPasswordSaveOption--}
```
public final PasswordSaveOption getPasswordSaveOption()
```


Haalt een wachtwoordbewaaroptie op die wordt weergegeven door het [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) object.


**Returns:**
[PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) - the password save option

### setPasswordSaveOption(PasswordSaveOption value) {#setPasswordSaveOption-com.groupdocs.comparison.options.enums.PasswordSaveOption-}
```
public final void setPasswordSaveOption(PasswordSaveOption value)
```


Stelt een wachtwoordbewaaroptie in die wordt weergegeven door het [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) object.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) | De optie om wachtwoord op te slaan |
|

### getOriginalSize() {#getOriginalSize--}
```
public final OriginalSize getOriginalSize()
```


Haalt de originele afmetingen van vergeleken documenten op die worden weergegeven door het [OriginalSize](../../com.groupdocs.comparison.options/originalsize) object.


**Returns:**
[OriginalSize](../../com.groupdocs.comparison.options/originalsize) - the original size of documents

### setOriginalSize(OriginalSize value) {#setOriginalSize-com.groupdocs.comparison.options.OriginalSize-}
```
public final void setOriginalSize(OriginalSize value)
```


Stelt de originele afmetingen van vergeleken documenten in die worden weergegeven door het [OriginalSize](../../com.groupdocs.comparison.options/originalsize) object.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [OriginalSize](../../com.groupdocs.comparison.options/originalsize) | De oorspronkelijke grootte van documenten |
|

### getDiagramMasterSetting() {#getDiagramMasterSetting--}
```
public final DiagramMasterSetting getDiagramMasterSetting()
```


Haalt een instelling van de masterpagina voor Diagram-documenten op die wordt weergegeven door het [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) object.


**Returns:**
[DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) - the diagram master page setting

### setDiagramMasterSetting(DiagramMasterSetting value) {#setDiagramMasterSetting-com.groupdocs.comparison.options.style.DiagramMasterSetting-}
```
public final void setDiagramMasterSetting(DiagramMasterSetting value)
```


Stelt een instelling van de masterpagina voor Diagram-documenten in die wordt weergegeven door het [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) object.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) | De instelling voor de masterpagina van het diagram |
|

### isDirectoryCompare() {#isDirectoryCompare--}
```
public boolean isDirectoryCompare()
```


Retourneert een vlag die aangeeft of mapvergelijking is ingeschakeld.


**Returns:**
boolean - true als mapvergelijking is ingeschakeld, anders false

### setDirectoryCompare(boolean directoryCompare) {#setDirectoryCompare-boolean-}
```
public void setDirectoryCompare(boolean directoryCompare)
```


Stelt een vlag in die aangeeft of mapvergelijking moet worden ingeschakeld.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | directoryCompare | boolean | true als mapvergelijking moet worden ingeschakeld, anders false |
|

### isShowOnlyChanged() {#isShowOnlyChanged--}
```
public boolean isShowOnlyChanged()
```


Retourneert een booleaanse waarde die aangeeft of alleen gewijzigde items moeten worden weergegeven.


**Returns:**
boolean - true als alleen gewijzigde items moeten worden weergegeven, anders false

### setShowOnlyChanged(boolean showOnlyChanged) {#setShowOnlyChanged-boolean-}
```
public void setShowOnlyChanged(boolean showOnlyChanged)
```


Stelt de waarde in die aangeeft of alleen gewijzigde items moeten worden weergegeven.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | showOnlyChanged | boolean | de booleaanse waarde die aangeeft of alleen gewijzigde items moeten worden weergegeven |
|

### getFolderComparisonExtension() {#getFolderComparisonExtension--}
```
public FolderComparisonExtension getFolderComparisonExtension()
```


Haalt het formaat van het resulterende mapvergelijkingsbestand op.


**Returns:**
com.groupdocs.comparison.options.enums.FolderComparisonExtension - de FolderComparisonExtension die het formaat van het resulterende mapvergelijkingsbestand vertegenwoordigt

### setFolderComparisonExtension(FolderComparisonExtension folderComparisonExtension) {#setFolderComparisonExtension-com.groupdocs.comparison.options.enums.FolderComparisonExtension-}
```
public void setFolderComparisonExtension(FolderComparisonExtension folderComparisonExtension)
```


Stelt het formaat van het resulterende mapvergelijkingsbestand in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | folderComparisonExtension | com.groupdocs.comparison.options.enums.FolderComparisonExtension | de FolderComparisonExtension die het formaat van het resulterende mapvergelijkingsbestand vertegenwoordigt |
|

