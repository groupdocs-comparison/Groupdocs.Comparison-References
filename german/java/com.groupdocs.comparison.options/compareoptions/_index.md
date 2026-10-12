---
title: "CompareOptions"
second_title: "GroupDocs.Comparison für Java API-Referenz"
description: "Ermöglicht die Konfiguration des Dokumentvergleichsprozesses."
type: docs
weight: 11
url: /de/java/com.groupdocs.comparison.options/compareoptions/
---
**Inheritance:**
java.lang.Object
```
public class CompareOptions
```

Ermöglicht die Konfiguration des Dokumentvergleichsprozesses.


Beispielverwendung:

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


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [CompareOptions()](#CompareOptions--) | Initialisiert eine neue Instanz der CompareOptions-Klasse. |
|
|  | [CompareOptions(StyleSettings insertedItemStyle, StyleSettings deletedItemStyle, StyleSettings changedItemStyle)](#CompareOptions-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-) | Initialisiert eine neue Instanz der CompareOptions-Klasse mit Einstellungen für verschiedene Stile. |
|
## Felder

| Feld | Beschreibung |
| --- | --- |
| [ignoreChangeSettings](#ignoreChangeSettings) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getIgnoreChangeSettings()](#getIgnoreChangeSettings--) | Ruft Einstellungen ab, um Änderungen basierend auf Ähnlichkeit zu ignorieren. |
|
|  | [setIgnoreChangeSettings(IgnoreChangeSensitivitySettings ignoreChangeSettings)](#setIgnoreChangeSettings-com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings-) | Setzt Einstellungen, um Änderungen basierend auf Ähnlichkeit zu ignorieren. |
|
|  | [getUserMasterPath()](#getUserMasterPath--) | Liefert den Pfad zur Mastervorlage des Benutzers für Diagramme. |
|
|  | [setUserMasterPath(String userMasterPath)](#setUserMasterPath-java.lang.String-) | Setzt den Pfad zur Mastervorlage des Benutzers für Diagramme. |
|
|  | [getComparisonType()](#getComparisonType--) | Liefert einen Typ von Quell- und Zieldokumenten als [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype)-Objekt, damit Comparison weiß, wie sie zu vergleichen sind. |
|
|  | [setComparisonType(ComparisonType comparisonType)](#setComparisonType-com.groupdocs.comparison.options.enums.ComparisonType-) | Setzt einen Typ von Quell- und Zieldokumenten als [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype)-Objekt, damit Comparison weiß, wie sie zu vergleichen sind. |
|
|  | [getPaperSize()](#getPaperSize--) | Liefert eine Papiergröße im Ergebnisdokument als [PaperSize](../../com.groupdocs.comparison.options.enums/papersize)-Objekt. |
|
|  | [setPaperSize(PaperSize value)](#setPaperSize-com.groupdocs.comparison.options.enums.PaperSize-) | Setzt eine Papiergröße im Ergebnisdokument als [PaperSize](../../com.groupdocs.comparison.options.enums/papersize)-Objekt. |
|
|  | [getCalculateCoordinatesMode()](#getCalculateCoordinatesMode--) | Liefert einen Berechnungskoordinatenmodus als [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration)-Objekt. |
|
|  | [setCalculateCoordinatesMode(CalculateCoordinatesModeEnumeration calculateCoordinatesMode)](#setCalculateCoordinatesMode-com.groupdocs.comparison.options.enums.CalculateCoordinatesModeEnumeration-) | Setzt einen Berechnungskoordinatenmodus als [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration)-Objekt. |
|
|  | [isShowDeletedContent()](#isShowDeletedContent--) | Liefert ein Flag, das angibt, ob gelöschte Komponenten im Ergebnisdokument angezeigt werden sollen oder nicht. |
|
|  | [setShowDeletedContent(boolean value)](#setShowDeletedContent-boolean-) | Setzt ein Flag, das angibt, ob gelöschte Komponenten im Ergebnisdokument angezeigt werden sollen oder nicht. |
|
|  | [isShowInsertedContent()](#isShowInsertedContent--) | Gibt ein Flag zurück, das angibt, ob eingefügte Komponenten im resultierenden Dokument angezeigt werden sollen oder nicht. |
|
|  | [setShowInsertedContent(boolean value)](#setShowInsertedContent-boolean-) | Setzt ein Flag, das angibt, ob eingefügte Komponenten im resultierenden Dokument angezeigt werden sollen oder nicht. |
|
|  | [isGenerateSummaryPage()](#isGenerateSummaryPage--) | Gibt ein Flag zurück, das angibt, ob eine Zusammenfassungsseite mit Statistiken der erkannten Änderungen dem resultierenden Dokument hinzugefügt werden soll oder nicht. |
|
|  | [setGenerateSummaryPage(boolean value)](#setGenerateSummaryPage-boolean-) | Setzt ein Flag, das angibt, ob eine Zusammenfassungsseite mit Statistiken der erkannten Änderungen dem resultierenden Dokument hinzugefügt werden soll oder nicht. |
|
|  | [isExtendedSummaryPage()](#isExtendedSummaryPage--) | Gibt ein Flag zurück, das angibt, ob erweiterte Dateivergleichsinformationen zur Zusammenfassungsseite hinzugefügt werden sollen oder nicht. |
|
|  | [setExtendedSummaryPage(boolean value)](#setExtendedSummaryPage-boolean-) | Setzt ein Flag, das angibt, ob erweiterte Dateivergleichsinformationen zur Zusammenfassungsseite hinzugefügt werden sollen oder nicht. |
|
|  | [isShowOnlySummaryPage()](#isShowOnlySummaryPage--) | Gibt ein Flag zurück, das angibt, ob im resultierenden Dokument nur eine Seite mit Statistiken der erkannten Änderungen belassen werden soll oder nicht. |
|
|  | [setShowOnlySummaryPage(boolean value)](#setShowOnlySummaryPage-boolean-) | Setzt ein Flag, das angibt, ob im resultierenden Dokument nur eine Seite mit Statistiken der erkannten Änderungen belassen werden soll oder nicht. |
|
|  | [isDetectStyleChanges()](#isDetectStyleChanges--) | Gibt ein Flag zurück, das angibt, ob Stiländerungen erkannt werden sollen oder nicht. |
|
|  | [setDetectStyleChanges(boolean value)](#setDetectStyleChanges-boolean-) | Setzt ein Flag, das angibt, ob Stiländerungen erkannt werden sollen oder nicht. |
|
|  | [isMarkNestedContent()](#isMarkNestedContent--) | Gibt ein Flag zurück, das angibt, ob die Kinder der gelöschten oder eingefügten Elemente als gelöscht oder eingefügt markiert werden sollen. |
|
|  | [setMarkNestedContent(boolean value)](#setMarkNestedContent-boolean-) | Setzt ein Flag, das angibt, ob die Kinder der gelöschten oder eingefügten Elemente als gelöscht oder eingefügt markiert werden sollen. |
|
|  | [isCalculateCoordinates()](#isCalculateCoordinates--) | Gibt ein Flag zurück, das angibt, ob Koordinaten für geänderte Komponenten berechnet werden sollen. |
|
|  | [setCalculateCoordinates(boolean value)](#setCalculateCoordinates-boolean-) | Setzt ein Flag, das angibt, ob Koordinaten für geänderte Komponenten berechnet werden sollen. |
|
|  | [isHeaderFootersComparison()](#isHeaderFootersComparison--) | Gibt ein Flag zurück, das angibt, ob Kopf-/Fußzeileninhalte verglichen werden sollen. |
|
|  | [setHeaderFootersComparison(boolean value)](#setHeaderFootersComparison-boolean-) | Setzt ein Flag, das angibt, ob Kopf-/Fußzeileninhalte verglichen werden sollen. |
|
|  | [getDetalisationLevel()](#getDetalisationLevel--) | Gibt ein Detaillierungsniveau des Vergleichs zurück, dargestellt als [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel). |
|
|  | [setDetalisationLevel(DetalisationLevel value)](#setDetalisationLevel-com.groupdocs.comparison.options.style.DetalisationLevel-) | Setzt ein Detaillierungsniveau des Vergleichs, dargestellt als [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel). |
|
|  | [isMarkChangedContent()](#isMarkChangedContent--) | Gibt ein Flag zurück, das angibt, ob Rahmen für Formen in der Textverarbeitung und für Rechtecke in Bilddokumenten verwendet werden. |
|
|  | [setMarkChangedContent(boolean value)](#setMarkChangedContent-boolean-) | Setzt ein Flag, das angibt, ob Rahmen für Formen in der Textverarbeitung und für Rechtecke in Bilddokumenten verwendet werden. |
|
|  | [getInsertedItemStyle()](#getInsertedItemStyle--) | Gibt eine Stileinstellung zurück, die auf eingefügte Elemente angewendet wird. |
|
|  | [setInsertedItemStyle(StyleSettings value)](#setInsertedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-) | Setzt eine Stileinstellung, die auf eingefügte Elemente angewendet wird. |
|
|  | [getDeletedItemStyle()](#getDeletedItemStyle--) | Gibt eine Stileinstellung zurück, die auf gelöschte Elemente angewendet wird. |
|
|  | [setDeletedItemStyle(StyleSettings value)](#setDeletedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-) | Setzt eine Stileinstellung, die auf gelöschte Elemente angewendet wird. |
|
|  | [getChangedItemStyle()](#getChangedItemStyle--) | Gibt eine Stileinstellung zurück, die auf geänderte Elemente angewendet wird. |
|
|  | [setChangedItemStyle(StyleSettings value)](#setChangedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-) | Legt die Stil‑Einstellungen fest, die auf geänderte Elemente angewendet werden. |
|
|  | [getSensitivityOfComparison()](#getSensitivityOfComparison--) | Liefert die Empfindlichkeit des Vergleichs. |
|
|  | [setSensitivityOfComparison(int value)](#setSensitivityOfComparison-int-) | Legt die Empfindlichkeit des Vergleichs fest. |
|
|  | [setSensitivityOfComparisonForTables(Integer value)](#setSensitivityOfComparisonForTables-java.lang.Integer-) | Legt die Empfindlichkeit des Vergleichs für Tabellen fest. |
|
|  | [getSensitivityOfComparisonForTables()](#getSensitivityOfComparisonForTables--) | Liefert die Empfindlichkeit des Vergleichs für Tabellen. |
|
|  | [setWordsSeparatorChars(char[] value)](#setWordsSeparatorChars-char---) | Legt ein Array von Trennzeichen fest, das zum Aufteilen von Text in Wörter verwendet wird. |
|
|  | [getPasswordSaveOption()](#getPasswordSaveOption--) | Liefert eine Passwort‑Speicheroption, die durch das Objekt [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) dargestellt wird. |
|
|  | [setPasswordSaveOption(PasswordSaveOption value)](#setPasswordSaveOption-com.groupdocs.comparison.options.enums.PasswordSaveOption-) | Legt eine Passwort‑Speicheroption fest, die durch das Objekt [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) dargestellt wird. |
|
|  | [getOriginalSize()](#getOriginalSize--) | Liefert die Originalgrößen der verglichenen Dokumente, die durch das Objekt [OriginalSize](../../com.groupdocs.comparison.options/originalsize) dargestellt werden. |
|
|  | [setOriginalSize(OriginalSize value)](#setOriginalSize-com.groupdocs.comparison.options.OriginalSize-) | Legt die Originalgrößen der verglichenen Dokumente fest, die durch das Objekt [OriginalSize](../../com.groupdocs.comparison.options/originalsize) dargestellt werden. |
|
|  | [getDiagramMasterSetting()](#getDiagramMasterSetting--) | Liefert eine Einstellung der Masterseite für Diagrammdokumente, die durch das Objekt [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) dargestellt wird. |
|
|  | [setDiagramMasterSetting(DiagramMasterSetting value)](#setDiagramMasterSetting-com.groupdocs.comparison.options.style.DiagramMasterSetting-) | Legt eine Einstellung der Masterseite für Diagrammdokumente fest, die durch das Objekt [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) dargestellt wird. |
|
|  | [isDirectoryCompare()](#isDirectoryCompare--) | Gibt ein Flag zurück, das anzeigt, ob der Verzeichnisvergleich aktiviert ist. |
|
|  | [setDirectoryCompare(boolean directoryCompare)](#setDirectoryCompare-boolean-) | Legt ein Flag fest, das angibt, ob der Verzeichnisvergleich aktiviert werden soll. |
|
|  | [isShowOnlyChanged()](#isShowOnlyChanged--) | Gibt einen booleschen Wert zurück, der angibt, ob nur geänderte Elemente angezeigt werden sollen. |
|
|  | [setShowOnlyChanged(boolean showOnlyChanged)](#setShowOnlyChanged-boolean-) | Legt den Wert fest, der angibt, ob nur geänderte Elemente angezeigt werden sollen. |
|
|  | [getFolderComparisonExtension()](#getFolderComparisonExtension--) | Liefert das Format der resultierenden Ordnervergleichsdatei. |
|
|  | [setFolderComparisonExtension(FolderComparisonExtension folderComparisonExtension)](#setFolderComparisonExtension-com.groupdocs.comparison.options.enums.FolderComparisonExtension-) | Legt das Format der resultierenden Ordnervergleichsdatei fest. |
|
### CompareOptions() {#CompareOptions--}
```
public CompareOptions()
```


Initialisiert eine neue Instanz der CompareOptions-Klasse.


### CompareOptions(StyleSettings insertedItemStyle, StyleSettings deletedItemStyle, StyleSettings changedItemStyle) {#CompareOptions-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-}
```
public CompareOptions(StyleSettings insertedItemStyle, StyleSettings deletedItemStyle, StyleSettings changedItemStyle)
```


Initialisiert eine neue Instanz der CompareOptions-Klasse mit Einstellungen für verschiedene Stile.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | insertedItemStyle | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Stileinstellungen für eingefügte Elemente |
|
|  | deletedItemStyle | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Stileinstellungen für gelöschte Elemente |
|
|  | changedItemStyle | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Stileinstellungen für geänderte Stilelemente |
|

### ignoreChangeSettings {#ignoreChangeSettings}
```
public IgnoreChangeSensitivitySettings ignoreChangeSettings
```


### getIgnoreChangeSettings() {#getIgnoreChangeSettings--}
```
public IgnoreChangeSensitivitySettings getIgnoreChangeSettings()
```


Ruft Einstellungen ab, um Änderungen basierend auf Ähnlichkeit zu ignorieren.


**Returns:**
com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings - Einstellungen zum Ignorieren von Änderungen.

### setIgnoreChangeSettings(IgnoreChangeSensitivitySettings ignoreChangeSettings) {#setIgnoreChangeSettings-com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings-}
```
public void setIgnoreChangeSettings(IgnoreChangeSensitivitySettings ignoreChangeSettings)
```


Setzt Einstellungen, um Änderungen basierend auf Ähnlichkeit zu ignorieren.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | ignoreChangeSettings | com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings | Einstellungen zum Ignorieren von Änderungen. |
|

### getUserMasterPath() {#getUserMasterPath--}
```
public String getUserMasterPath()
```


Liefert den Pfad zur Mastervorlage des Benutzers für Diagramme.


**Returns:**
java.lang.String - Der Pfad zur Benutzermaster‑Vorlage für Diagramme.

### setUserMasterPath(String userMasterPath) {#setUserMasterPath-java.lang.String-}
```
public void setUserMasterPath(String userMasterPath)
```


Setzt den Pfad zur Mastervorlage des Benutzers für Diagramme.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | userMasterPath | java.lang.String | Der Pfad zur Benutzermaster‑Vorlage für Diagramme. |
|

### getComparisonType() {#getComparisonType--}
```
public ComparisonType getComparisonType()
```


Liefert einen Typ von Quell- und Zieldokumenten als [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype)-Objekt, damit Comparison weiß, wie sie zu vergleichen sind.
Wenn diese Option gesetzt ist, wird die Option [LoadOptions.getFileType()](../../com.groupdocs.comparison.options.load/loadoptions#getFileType--) weggelassen.


**Returns:**
[ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) - the type of source and target documents

### setComparisonType(ComparisonType comparisonType) {#setComparisonType-com.groupdocs.comparison.options.enums.ComparisonType-}
```
public void setComparisonType(ComparisonType comparisonType)
```


Setzt einen Typ von Quell- und Zieldokumenten als [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype)-Objekt, damit Comparison weiß, wie sie zu vergleichen sind.
Wenn diese Option gesetzt ist, wird die Option [LoadOptions.setFileType(FileType)](../../com.groupdocs.comparison.options.load/loadoptions#setFileType-FileType-) weggelassen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | comparisonType | [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) | Der Typ der Quell‑ und Zieldokumente |
|

### getPaperSize() {#getPaperSize--}
```
public final PaperSize getPaperSize()
```


Liefert eine Papiergröße im Ergebnisdokument als [PaperSize](../../com.groupdocs.comparison.options.enums/papersize)-Objekt.


**Returns:**
[PaperSize](../../com.groupdocs.comparison.options.enums/papersize) - the size of a paper in result document

### setPaperSize(PaperSize value) {#setPaperSize-com.groupdocs.comparison.options.enums.PaperSize-}
```
public final void setPaperSize(PaperSize value)
```


Setzt eine Papiergröße im Ergebnisdokument als [PaperSize](../../com.groupdocs.comparison.options.enums/papersize)-Objekt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [PaperSize](../../com.groupdocs.comparison.options.enums/papersize) | Die Größe des Papiers im Ergebnisdokument |
|

### getCalculateCoordinatesMode() {#getCalculateCoordinatesMode--}
```
public CalculateCoordinatesModeEnumeration getCalculateCoordinatesMode()
```


Liefert einen Berechnungskoordinatenmodus als [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration)-Objekt.


**Returns:**
[CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) - the calculate coordinates mode

### setCalculateCoordinatesMode(CalculateCoordinatesModeEnumeration calculateCoordinatesMode) {#setCalculateCoordinatesMode-com.groupdocs.comparison.options.enums.CalculateCoordinatesModeEnumeration-}
```
public void setCalculateCoordinatesMode(CalculateCoordinatesModeEnumeration calculateCoordinatesMode)
```


Setzt einen Berechnungskoordinatenmodus als [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration)-Objekt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | calculateCoordinatesMode | [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) | Der Modus zur Berechnung von Koordinaten |
|

### isShowDeletedContent() {#isShowDeletedContent--}
```
public final boolean isShowDeletedContent()
```


Liefert ein Flag, das angibt, ob gelöschte Komponenten im Ergebnisdokument angezeigt werden sollen oder nicht.


**Returns:**
boolean - true, wenn gelöschte Komponenten im Ergebnisdokument angezeigt werden, sonst false

### setShowDeletedContent(boolean value) {#setShowDeletedContent-boolean-}
```
public final void setShowDeletedContent(boolean value)
```


Setzt ein Flag, das angibt, ob gelöschte Komponenten im Ergebnisdokument angezeigt werden sollen oder nicht.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | boolean | true, wenn gelöschte Komponenten im Ergebnisdokument angezeigt werden sollen, sonst false |
|

### isShowInsertedContent() {#isShowInsertedContent--}
```
public final boolean isShowInsertedContent()
```


Gibt ein Flag zurück, das angibt, ob eingefügte Komponenten im resultierenden Dokument angezeigt werden sollen oder nicht.


**Returns:**
boolean - true, wenn eingefügte Komponenten im Ergebnisdokument angezeigt werden sollen, sonst false

### setShowInsertedContent(boolean value) {#setShowInsertedContent-boolean-}
```
public final void setShowInsertedContent(boolean value)
```


Setzt ein Flag, das angibt, ob eingefügte Komponenten im resultierenden Dokument angezeigt werden sollen oder nicht.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | boolean | true, wenn eingefügte Komponenten im Ergebnisdokument angezeigt werden sollen, sonst false |
|

### isGenerateSummaryPage() {#isGenerateSummaryPage--}
```
public final boolean isGenerateSummaryPage()
```


Gibt ein Flag zurück, das angibt, ob eine Zusammenfassungsseite mit Statistiken der erkannten Änderungen dem resultierenden Dokument hinzugefügt werden soll oder nicht.


**Returns:**
boolean - true, wenn eine Zusammenfassungsseite hinzugefügt wird, sonst false

### setGenerateSummaryPage(boolean value) {#setGenerateSummaryPage-boolean-}
```
public final void setGenerateSummaryPage(boolean value)
```


Setzt ein Flag, das angibt, ob eine Zusammenfassungsseite mit Statistiken der erkannten Änderungen dem resultierenden Dokument hinzugefügt werden soll oder nicht.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | boolean | true, wenn eine Zusammenfassungsseite hinzugefügt werden soll, sonst false |
|

### isExtendedSummaryPage() {#isExtendedSummaryPage--}
```
public boolean isExtendedSummaryPage()
```


Gibt ein Flag zurück, das angibt, ob erweiterte Dateivergleichsinformationen zur Zusammenfassungsseite hinzugefügt werden sollen oder nicht.


**Returns:**
boolean - true, wenn erweiterte Dateivergleichsinformationen zur Zusammenfassungsseite hinzugefügt werden, sonst false

### setExtendedSummaryPage(boolean value) {#setExtendedSummaryPage-boolean-}
```
public void setExtendedSummaryPage(boolean value)
```


Setzt ein Flag, das angibt, ob erweiterte Dateivergleichsinformationen zur Zusammenfassungsseite hinzugefügt werden sollen oder nicht.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | boolean | true, wenn erweiterte Dateivergleichsinformationen zur Zusammenfassungsseite hinzugefügt werden sollen, sonst false |
|

### isShowOnlySummaryPage() {#isShowOnlySummaryPage--}
```
public boolean isShowOnlySummaryPage()
```


Gibt ein Flag zurück, das angibt, ob im resultierenden Dokument nur eine Seite mit Statistiken der erkannten Änderungen belassen werden soll oder nicht.


**Returns:**
boolean - true, wenn im Ergebnisdokument nur eine Seite mit Statistiken der erkannten Änderungen verbleibt, sonst false

### setShowOnlySummaryPage(boolean value) {#setShowOnlySummaryPage-boolean-}
```
public void setShowOnlySummaryPage(boolean value)
```


Setzt ein Flag, das angibt, ob im resultierenden Dokument nur eine Seite mit Statistiken der erkannten Änderungen belassen werden soll oder nicht.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | boolean | true, wenn im Ergebnisdokument nur eine Seite mit Statistiken der erkannten Änderungen verbleiben soll, sonst false |
|

### isDetectStyleChanges() {#isDetectStyleChanges--}
```
public final boolean isDetectStyleChanges()
```


Gibt ein Flag zurück, das angibt, ob Stiländerungen erkannt werden sollen oder nicht.


**Returns:**
boolean - true, wenn Stiländerungen erkannt werden, sonst false

### setDetectStyleChanges(boolean value) {#setDetectStyleChanges-boolean-}
```
public final void setDetectStyleChanges(boolean value)
```


Setzt ein Flag, das angibt, ob Stiländerungen erkannt werden sollen oder nicht.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | boolean | true, wenn Stiländerungen erkannt werden sollen, sonst false |
|

### isMarkNestedContent() {#isMarkNestedContent--}
```
public final boolean isMarkNestedContent()
```


Gibt ein Flag zurück, das angibt, ob die Kinder der gelöschten oder eingefügten Elemente als gelöscht oder eingefügt markiert werden sollen.


**Returns:**
boolean - true, wenn die Kinder der gelöschten oder eingefügten Elemente als gelöscht oder eingefügt markiert werden, sonst false

### setMarkNestedContent(boolean value) {#setMarkNestedContent-boolean-}
```
public final void setMarkNestedContent(boolean value)
```


Setzt ein Flag, das angibt, ob die Kinder der gelöschten oder eingefügten Elemente als gelöscht oder eingefügt markiert werden sollen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | boolean | true, wenn die Kinder der gelöschten oder eingefügten Elemente als gelöscht oder eingefügt markiert werden sollen, sonst false |
|

### isCalculateCoordinates() {#isCalculateCoordinates--}
```
public final boolean isCalculateCoordinates()
```


Gibt ein Flag zurück, das angibt, ob Koordinaten für geänderte Komponenten berechnet werden sollen.


**Returns:**
boolean - true, wenn Koordinaten für geänderte Komponenten berechnet werden, sonst false

### setCalculateCoordinates(boolean value) {#setCalculateCoordinates-boolean-}
```
public final void setCalculateCoordinates(boolean value)
```


Setzt ein Flag, das angibt, ob Koordinaten für geänderte Komponenten berechnet werden sollen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | boolean | true, wenn Koordinaten für geänderte Komponenten berechnet werden sollen, sonst false |
|

### isHeaderFootersComparison() {#isHeaderFootersComparison--}
```
public final boolean isHeaderFootersComparison()
```


Gibt ein Flag zurück, das angibt, ob Kopf-/Fußzeileninhalte verglichen werden sollen.


**Returns:**
boolean - true, wenn Kopf‑/Fußzeileninhalte verglichen werden, sonst false

### setHeaderFootersComparison(boolean value) {#setHeaderFootersComparison-boolean-}
```
public final void setHeaderFootersComparison(boolean value)
```


Setzt ein Flag, das angibt, ob Kopf-/Fußzeileninhalte verglichen werden sollen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | boolean | true, wenn Header-/Footer-Inhalte verglichen werden sollen, sonst false |
|

### getDetalisationLevel() {#getDetalisationLevel--}
```
public final DetalisationLevel getDetalisationLevel()
```


Gibt ein Detaillierungsniveau des Vergleichs zurück, dargestellt als [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel).
Standardwert ist [DetalisationLevel.LOW](../../com.groupdocs.comparison.options.style/detalisationlevel#LOW).


**Returns:**
[DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) - the level of comparison detalization

### setDetalisationLevel(DetalisationLevel value) {#setDetalisationLevel-com.groupdocs.comparison.options.style.DetalisationLevel-}
```
public final void setDetalisationLevel(DetalisationLevel value)
```


Setzt ein Detaillierungsniveau des Vergleichs, dargestellt als [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel).
Standardwert ist [DetalisationLevel.LOW](../../com.groupdocs.comparison.options.style/detalisationlevel#LOW)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) | Der Detaillierungsgrad des Vergleichs |
|

### isMarkChangedContent() {#isMarkChangedContent--}
```
public final boolean isMarkChangedContent()
```


Gibt ein Flag zurück, das angibt, ob Rahmen für Formen in der Textverarbeitung und für Rechtecke in Bilddokumenten verwendet werden.


**Returns:**
boolean - true, wenn Rahmen verwendet werden, sonst false

### setMarkChangedContent(boolean value) {#setMarkChangedContent-boolean-}
```
public final void setMarkChangedContent(boolean value)
```


Setzt ein Flag, das angibt, ob Rahmen für Formen in der Textverarbeitung und für Rechtecke in Bilddokumenten verwendet werden.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | boolean | true, wenn Rahmen verwendet werden sollen, sonst false |
|

### getInsertedItemStyle() {#getInsertedItemStyle--}
```
public final StyleSettings getInsertedItemStyle()
```


Gibt eine Stileinstellung zurück, die auf eingefügte Elemente angewendet wird.


**Returns:**
[StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) - style settings of inserted items

### setInsertedItemStyle(StyleSettings value) {#setInsertedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-}
```
public final void setInsertedItemStyle(StyleSettings value)
```


Setzt eine Stileinstellung, die auf eingefügte Elemente angewendet wird.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Stileinstellungen für eingefügte Elemente |
|

### getDeletedItemStyle() {#getDeletedItemStyle--}
```
public final StyleSettings getDeletedItemStyle()
```


Gibt eine Stileinstellung zurück, die auf gelöschte Elemente angewendet wird.


**Returns:**
[StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) - style settings of deleted items

### setDeletedItemStyle(StyleSettings value) {#setDeletedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-}
```
public final void setDeletedItemStyle(StyleSettings value)
```


Setzt eine Stileinstellung, die auf gelöschte Elemente angewendet wird.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Stileinstellungen für gelöschte Elemente |
|

### getChangedItemStyle() {#getChangedItemStyle--}
```
public final StyleSettings getChangedItemStyle()
```


Gibt eine Stileinstellung zurück, die auf geänderte Elemente angewendet wird.


**Returns:**
[StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) - style settings of changed items

### setChangedItemStyle(StyleSettings value) {#setChangedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-}
```
public final void setChangedItemStyle(StyleSettings value)
```


Legt die Stil‑Einstellungen fest, die auf geänderte Elemente angewendet werden.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Stileinstellungen für geänderte Elemente |
|

### getSensitivityOfComparison() {#getSensitivityOfComparison--}
```
public final int getSensitivityOfComparison()
```


Liefert die Empfindlichkeit des Vergleichs.
Der Prozentsatz der gelöschten und eingefügten Elemente zweier verglichener Objekte im Verhältnis zu allen Elementen dieser Objekte.

* If this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Returns:**
int - die Empfindlichkeit des Vergleichs

### setSensitivityOfComparison(int value) {#setSensitivityOfComparison-int-}
```
public final void setSensitivityOfComparison(int value)
```


Legt die Empfindlichkeit des Vergleichs fest.
Der Prozentsatz der gelöschten und eingefügten Elemente zweier verglichener Objekte im Verhältnis zu allen Elementen dieser Objekte.

* If this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | int | Die Empfindlichkeit des Vergleichs |
|

### setSensitivityOfComparisonForTables(Integer value) {#setSensitivityOfComparisonForTables-java.lang.Integer-}
```
public void setSensitivityOfComparisonForTables(Integer value)
```


Legt die Empfindlichkeit des Vergleichs für Tabellen fest.
Wenn der Wert null ist, wird SensitivityOfComparison stattdessen verwendet. Der Prozentsatz der gelöschten und eingefügten Elemente zweier verglichener Objekte im Verhältnis zu allen Elementen dieser Objekte.

* if this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs, if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | java.lang.Integer | Die Empfindlichkeit des Vergleichs für Tabellen |
|

### getSensitivityOfComparisonForTables() {#getSensitivityOfComparisonForTables--}
```
public final Integer getSensitivityOfComparisonForTables()
```


Liefert die Empfindlichkeit des Vergleichs für Tabellen.
Wenn der Wert null ist, wird SensitivityOfComparison stattdessen verwendet. Der Prozentsatz der gelöschten und eingefügten Elemente zweier verglichener Objekte im Verhältnis zu allen Elementen dieser Objekte.

* if this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs, if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Returns:**
java.lang.Integer - Die Empfindlichkeit des Vergleichs für Tabellen

### setWordsSeparatorChars(char[] value) {#setWordsSeparatorChars-char---}
```
public final void setWordsSeparatorChars(char[] value)
```


Legt ein Array von Trennzeichen fest, das zum Aufteilen von Text in Wörter verwendet wird.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | char[] | Das Array von Trennzeichen zum Aufteilen von Text in Wörter |
|

### getPasswordSaveOption() {#getPasswordSaveOption--}
```
public final PasswordSaveOption getPasswordSaveOption()
```


Liefert eine Passwort‑Speicheroption, die durch das Objekt [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) dargestellt wird.


**Returns:**
[PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) - the password save option

### setPasswordSaveOption(PasswordSaveOption value) {#setPasswordSaveOption-com.groupdocs.comparison.options.enums.PasswordSaveOption-}
```
public final void setPasswordSaveOption(PasswordSaveOption value)
```


Legt eine Passwort‑Speicheroption fest, die durch das Objekt [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) dargestellt wird.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) | Die Passwort‑Speicheroption |
|

### getOriginalSize() {#getOriginalSize--}
```
public final OriginalSize getOriginalSize()
```


Liefert die Originalgrößen der verglichenen Dokumente, die durch das Objekt [OriginalSize](../../com.groupdocs.comparison.options/originalsize) dargestellt werden.


**Returns:**
[OriginalSize](../../com.groupdocs.comparison.options/originalsize) - the original size of documents

### setOriginalSize(OriginalSize value) {#setOriginalSize-com.groupdocs.comparison.options.OriginalSize-}
```
public final void setOriginalSize(OriginalSize value)
```


Legt die Originalgrößen der verglichenen Dokumente fest, die durch das Objekt [OriginalSize](../../com.groupdocs.comparison.options/originalsize) dargestellt werden.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [OriginalSize](../../com.groupdocs.comparison.options/originalsize) | Die Originalgröße der Dokumente |
|

### getDiagramMasterSetting() {#getDiagramMasterSetting--}
```
public final DiagramMasterSetting getDiagramMasterSetting()
```


Liefert eine Einstellung der Masterseite für Diagrammdokumente, die durch das Objekt [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) dargestellt wird.


**Returns:**
[DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) - the diagram master page setting

### setDiagramMasterSetting(DiagramMasterSetting value) {#setDiagramMasterSetting-com.groupdocs.comparison.options.style.DiagramMasterSetting-}
```
public final void setDiagramMasterSetting(DiagramMasterSetting value)
```


Legt eine Einstellung der Masterseite für Diagrammdokumente fest, die durch das Objekt [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) dargestellt wird.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) | Die Diagramm‑Masterseiten‑Einstellung |
|

### isDirectoryCompare() {#isDirectoryCompare--}
```
public boolean isDirectoryCompare()
```


Gibt ein Flag zurück, das anzeigt, ob der Verzeichnisvergleich aktiviert ist.


**Returns:**
boolean - true, wenn Verzeichnisvergleich aktiviert ist, sonst false

### setDirectoryCompare(boolean directoryCompare) {#setDirectoryCompare-boolean-}
```
public void setDirectoryCompare(boolean directoryCompare)
```


Legt ein Flag fest, das angibt, ob der Verzeichnisvergleich aktiviert werden soll.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | directoryCompare | boolean | true, wenn der Verzeichnisvergleich aktiviert werden soll, sonst false |
|

### isShowOnlyChanged() {#isShowOnlyChanged--}
```
public boolean isShowOnlyChanged()
```


Gibt einen booleschen Wert zurück, der angibt, ob nur geänderte Elemente angezeigt werden sollen.


**Returns:**
boolean - true, wenn nur geänderte Elemente angezeigt werden sollen, sonst false

### setShowOnlyChanged(boolean showOnlyChanged) {#setShowOnlyChanged-boolean-}
```
public void setShowOnlyChanged(boolean showOnlyChanged)
```


Legt den Wert fest, der angibt, ob nur geänderte Elemente angezeigt werden sollen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | showOnlyChanged | boolean | Der boolesche Wert, der angibt, ob nur geänderte Elemente angezeigt werden sollen |
|

### getFolderComparisonExtension() {#getFolderComparisonExtension--}
```
public FolderComparisonExtension getFolderComparisonExtension()
```


Liefert das Format der resultierenden Ordnervergleichsdatei.


**Returns:**
com.groupdocs.comparison.options.enums.FolderComparisonExtension - die FolderComparisonExtension, die das Format der resultierenden Ordnervergleichsdatei darstellt

### setFolderComparisonExtension(FolderComparisonExtension folderComparisonExtension) {#setFolderComparisonExtension-com.groupdocs.comparison.options.enums.FolderComparisonExtension-}
```
public void setFolderComparisonExtension(FolderComparisonExtension folderComparisonExtension)
```


Legt das Format der resultierenden Ordnervergleichsdatei fest.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | folderComparisonExtension | com.groupdocs.comparison.options.enums.FolderComparisonExtension | die FolderComparisonExtension, die das Format der resultierenden Ordnervergleichsdatei darstellt |
|

