---
title: "Comparer"
second_title: "GroupDocs.Comparison für Java API-Referenz"
description: "Die Comparer-Klasse bietet Funktionalität zum Vergleichen von Dokumenten und zum Erzeugen von Vergleichsergebnissen."
type: docs
weight: 10
url: /de/java/com.groupdocs.comparison/comparer/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public class Comparer implements System.IDisposable, Closeable
```

Die Comparer-Klasse bietet Funktionalität zum Vergleichen von Dokumenten und zum Erzeugen von Vergleichsergebnissen.


Sie ermöglicht den Vergleich verschiedener Dokumenttypen, wie PDF, Word, Excel, PowerPoint und mehr.


Beispielverwendung:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     CompareOptions compareOptions = new CompareOptions();
     compareOptions.setDetectStyleChanges(true);

     comparer.compare(resultFile, compareOptions);
 }
 
````


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [Comparer(String filePath)](#Comparer-java.lang.String-) | Initialisiert eine neue Instanz der Comparer-Klasse mit dem angegebenen Quelldateipfad. |
|
|  | [Comparer(String filePath, CompareOptions compareOptions)](#Comparer-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | Initialisiert eine neue Instanz der Comparer-Klasse mit dem angegebenen Ordnerpfad und den Vergleichsoptionen. |
|
|  | [Comparer(Path filePath)](#Comparer-java.nio.file.Path-) | Initialisiert eine neue Instanz der Comparer-Klasse mit dem angegebenen Quelldateipfad. |
|
|  | [Comparer(String filePath, LoadOptions loadOptions)](#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-) | Initialisiert eine neue Instanz von Comparer mit dem angegebenen Quelldateipfad und [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions). |
|
|  | [Comparer(Path filePath, LoadOptions loadOptions)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-) | Initialisiert eine neue Instanz von Comparer mit dem angegebenen Quelldateipfad und [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions). |
|
|  | [Comparer(Path filePath, CompareOptions compareOptions)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | Initialisiert eine neue Instanz von Comparer mit dem angegebenen Quelldateipfad und [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions). |
|
|  | [Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings)](#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-) | Initialisiert eine neue Instanz der Comparer-Klasse mit dem angegebenen Quelldateipfad, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) und [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)](#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-) | Initialisiert eine neue Instanz der Comparer-Klasse mit dem angegebenen Quelldateipfad, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) und [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(String filePath, ComparerSettings settings)](#Comparer-java.lang.String-com.groupdocs.comparison.ComparerSettings-) | Initialisiert eine neue Instanz der Comparer-Klasse mit dem angegebenen Quelldateipfad und [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(Path filePath, ComparerSettings settings)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.ComparerSettings-) | Initialisiert eine neue Instanz der Comparer-Klasse mit dem angegebenen Quelldateipfad und [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-) | Initialisiert eine neue Instanz der Comparer-Klasse mit dem angegebenen Quelldateipfad, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) und [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-) | Initialisiert eine neue Instanz der Comparer-Klasse mit dem angegebenen Quelldateipfad, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) und [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(InputStream document)](#Comparer-java.io.InputStream-) | Initialisiert eine neue Instanz der Comparer-Klasse mit dem angegebenen Quell-Dokumenten-Stream. |
|
|  | [Comparer(InputStream document, LoadOptions loadOptions)](#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-) | Initialisiert eine neue Instanz von Comparer mit dem angegebenen Quell-Dokumenten-Stream und [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions). |
|
|  | [Comparer(InputStream document, ComparerSettings settings)](#Comparer-java.io.InputStream-com.groupdocs.comparison.ComparerSettings-) | Initialisiert eine neue Instanz der Comparer-Klasse mit dem angegebenen Quell-Dokumenten-Stream und [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(InputStream document, LoadOptions loadOptions, ComparerSettings settings)](#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-) | Initialisiert eine neue Instanz der Comparer-Klasse mit dem angegebenen Dokumenten-Stream, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) und [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(ComparerSettings settings)](#Comparer-com.groupdocs.comparison.ComparerSettings-) | Initialisiert eine neue Instanz der Comparer-Klasse mit den angegebenen [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
## Felder

| Feld | Beschreibung |
| --- | --- |
| [FILE_PATH](#FILE-PATH) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getSource()](#getSource--) | Liefert das Quell-Dokument, das verglichen wird. |
|
|  | [getTargets()](#getTargets--) | Liste der Ziel-Dokumente, die mit der Quelldatei verglichen werden. |
|
|  | [compare()](#compare--) | Vergleicht die angegebene Datei mit den Ziel-Dokumenten, ohne das Ergebnis mit den Standardoptionen zu speichern. |
|
|  | [compare(String filePath)](#compare-java.lang.String-) | Vergleicht die angegebene Datei mit den Ziel-Dokumenten und erzeugt ein Vergleichsergebnis. |
|
|  | [compare(Path filePath)](#compare-java.nio.file.Path-) | Vergleicht die angegebene Datei mit den Ziel-Dokumenten und erzeugt ein Vergleichsergebnis. |
|
|  | [compare(OutputStream outputStream)](#compare-java.io.OutputStream-) | Vergleicht die angegebene Datei mit den Ziel-Dokumenten und schreibt das Vergleichsergebnis in den Ausgabestream. |
|
|  | [compare(String filePath, CompareOptions compareOptions)](#compare-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | Vergleicht die angegebene Datei mit den Ziel-Dokumenten und schreibt das Vergleichsergebnis in den angegebenen Dateipfad. |
|
|  | [compare(Path filePath, CompareOptions compareOptions)](#compare-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | Vergleicht die angegebene Datei mit den Ziel-Dokumenten und schreibt das Vergleichsergebnis in den angegebenen Dateipfad. |
|
|  | [compare(OutputStream stream, CompareOptions compareOptions)](#compare-java.io.OutputStream-com.groupdocs.comparison.options.CompareOptions-) | Vergleicht die angegebene Datei mit den Ziel-Dokumenten und schreibt das Vergleichsergebnis in den Ausgabestream. |
|
|  | [compare(SaveOptions saveOptions, CompareOptions compareOptions)](#compare-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | Vergleicht die angegebene Datei mit den Ziel-Dokumenten, ohne das Ergebnis zu speichern. |
|
|  | [compare(String filePath, SaveOptions saveOptions)](#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-) | Vergleicht die angegebene Datei mit den Ziel-Dokumenten und schreibt das Vergleichsergebnis in den angegebenen Dateipfad. |
|
|  | [compare(Path filePath, SaveOptions saveOptions)](#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-) | Vergleicht die angegebene Datei mit den Ziel-Dokumenten und schreibt das Vergleichsergebnis in den angegebenen Dateipfad. |
|
|  | [compare(OutputStream stream, SaveOptions saveOptions)](#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-) | Vergleicht die angegebene Datei mit den Ziel-Dokumenten und schreibt das Vergleichsergebnis in den angegebenen Dateipfad. |
|
|  | [compare(CompareOptions compareOptions)](#compare-com.groupdocs.comparison.options.CompareOptions-) | Vergleicht die angegebene Datei mit den Ziel-Dokumenten, ohne das Ergebnis zu speichern. |
|
|  | [compare(OutputStream outputStream, SaveOptions saveOptions, CompareOptions compareOptions)](#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | Vergleicht die angegebene Datei mit den Ziel-Dokumenten und schreibt das Vergleichsergebnis in den bereitgestellten Ausgabestream. |
|
|  | [compare(String filePath, SaveOptions saveOptions, CompareOptions compareOptions)](#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | Vergleicht die angegebene Datei mit den Ziel-Dokumenten und schreibt das Vergleichsergebnis in den angegebenen Dateipfad. |
|
|  | [compareDirectory(String filePath, CompareOptions compareOptions)](#compareDirectory-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | Vergleicht das angegebene Verzeichnis mit dem Zielverzeichnis und speichert das Vergleichsergebnis im angegebenen Dateipfad. |
|
|  | [compareDirectory(Path filePath, CompareOptions compareOptions)](#compareDirectory-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | Vergleicht das angegebene Verzeichnis mit dem Zielverzeichnis und speichert das Vergleichsergebnis im angegebenen Dateipfad. |
|
|  | [compare(Path filePath, SaveOptions saveOptions, CompareOptions compareOptions)](#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | Vergleicht die angegebene Datei mit den Ziel-Dokumenten und schreibt das Vergleichsergebnis in den angegebenen Dateipfad. |
|
|  | [add(String filePath)](#add-java.lang.String-) | Fügt das angegebene Zieldokument zum Vergleichsprozess hinzu. |
|
|  | [add(String filePath, CompareOptions compareOptions)](#add-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | Fügt das angegebene Zieldokument oder den Ordner zum Vergleichsprozess hinzu. |
|
|  | [add(Path filePath)](#add-java.nio.file.Path-) | Fügt das angegebene Zieldokument zum Vergleichsprozess hinzu. |
|
|  | [add(String[] filePaths)](#add-java.lang.String...-) | Fügt die angegebenen Zieldokumente zum Vergleichsprozess hinzu. |
|
|  | [add(Path[] filePaths)](#add-java.nio.file.Path...-) | Fügt die angegebenen Zieldokumente zum Vergleichsprozess hinzu. |
|
|  | [add(String filePath, LoadOptions loadOptions)](#add-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-) | Fügt das angegebene Zieldokument zum Vergleichsprozess mit den angegebenen Ladeoptionen hinzu. |
|
|  | [add(Path filePath, LoadOptions loadOptions)](#add-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-) | Fügt das angegebene Zieldokument zum Vergleichsprozess mit den angegebenen Ladeoptionen hinzu. |
|
|  | [add(Path filePath, CompareOptions compareOptions)](#add-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | Fügt das angegebene Zieldokument zum Vergleichsprozess mit den angegebenen Ladeoptionen hinzu. |
|
|  | [add(InputStream document)](#add-java.io.InputStream-) | Fügt das angegebene Zieldokument zum Vergleichsprozess hinzu. |
|
|  | [add(InputStream[] documents)](#add-java.io.InputStream...-) | Fügt die angegebenen Zieldokumente zum Vergleichsprozess hinzu. |
|
|  | [add(InputStream document, LoadOptions loadOptions)](#add-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-) | Fügt das angegebene Zieldokument zum Vergleichsprozess mit den angegebenen Ladeoptionen hinzu. |
|
|  | [getChanges()](#getChanges--) | Ruft ein Array von [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo)-Objekten ab, die die während des Vergleichsprozesses erkannten Änderungen darstellen. |
|
|  | [getChanges(GetChangeOptions getChangeOptions)](#getChanges-com.groupdocs.comparison.options.GetChangeOptions-) | Ruft ein Array von [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo)-Objekten ab, die die während des Vergleichsprozesses erkannten Änderungen darstellen. |
|
|  | [applyChanges(String filePath, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.lang.String-com.groupdocs.comparison.options.ApplyChangeOptions-) | Akzeptiert oder verwirft Änderungen und wendet sie auf das Ergebnisdokument an. |
|
|  | [applyChanges(Path filePath, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.ApplyChangeOptions-) | Akzeptiert oder verwirft Änderungen und wendet sie auf das resultierende Dokument an. |
|
|  | [applyChanges(OutputStream document, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.ApplyChangeOptions-) | Akzeptiert oder verwirft Änderungen und wendet sie auf das resultierende Dokument an. |
|
|  | [applyChanges(String filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-) | Akzeptiert oder verwirft Änderungen und wendet sie auf das resultierende Dokument an. |
|
|  | [applyChanges(Path filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-) | Akzeptiert oder verwirft Änderungen und wendet sie auf das resultierende Dokument an. |
|
|  | [applyChanges(OutputStream document, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-) | Akzeptiert oder verwirft Änderungen und wendet sie auf das resultierende Dokument an. |
|
|  | [getResultString()](#getResultString--) | Liefert die Ergebniszeichenfolge nach dem Vergleich (nur für Textvergleich). |
|
|  | [getSourceFolder()](#getSourceFolder--) | Gibt den Quellordner zurück, der verglichen wird. |
|
|  | [getTargetFolder()](#getTargetFolder--) | Gibt den Zielordner zurück, der verglichen wird. |
|
|  | [selfComparisonCheck(Document source, Document target)](#selfComparisonCheck-com.groupdocs.comparison.Document-com.groupdocs.comparison.Document-) | Selbstvergleichsprüfung (e498c23). |
|
|  | [close()](#close--) | Gibt Ressourcen frei. |
|
### Comparer(String filePath) {#Comparer-java.lang.String-}
```
public Comparer(String filePath)
```


Initialisiert eine neue Instanz der Comparer-Klasse mit dem angegebenen Quelldateipfad.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.lang.String | Der Pfad zum Quelldokument |
|

### Comparer(String filePath, CompareOptions compareOptions) {#Comparer-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(String filePath, CompareOptions compareOptions)
```


Initialisiert eine neue Instanz der Comparer-Klasse mit dem angegebenen Ordnerpfad und den Vergleichsoptionen.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.lang.String | Der Pfad zum Quelldokument oder Ordner |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Die Vergleichsoptionen für den Ordnervergleich |
|

### Comparer(Path filePath) {#Comparer-java.nio.file.Path-}
```
public Comparer(Path filePath)
```


Initialisiert eine neue Instanz der Comparer-Klasse mit dem angegebenen Quelldateipfad.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Der Pfad zum Quelldokument |
|

### Comparer(String filePath, LoadOptions loadOptions) {#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Comparer(String filePath, LoadOptions loadOptions)
```


Initialisiert eine neue Instanz von Comparer mit dem angegebenen Quelldateipfad und [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.lang.String | Der Pfad zum Quelldokument |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Die benutzerdefinierten Ladeoptionen, die auf das Dokument angewendet werden |
|

### Comparer(Path filePath, LoadOptions loadOptions) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Comparer(Path filePath, LoadOptions loadOptions)
```


Initialisiert eine neue Instanz von Comparer mit dem angegebenen Quelldateipfad und [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Der Pfad zum Quelldokument |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Die benutzerdefinierten Ladeoptionen, die auf das Dokument angewendet werden |
|

### Comparer(Path filePath, CompareOptions compareOptions) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(Path filePath, CompareOptions compareOptions)
```


Initialisiert eine neue Instanz von Comparer mit dem angegebenen Quelldateipfad und [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Der Pfad zum Quelldokument |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Die Vergleichsoptionen für den Ordnervergleich |
|

### Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings) {#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings)
```


Initialisiert eine neue Instanz der Comparer-Klasse mit dem angegebenen Quelldateipfad, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) und [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.lang.String | Der Pfad zum Quelldokument |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Die benutzerdefinierten Ladeoptionen, die auf das Dokument angewendet werden |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Die Vergleichereinstellungen, die für den Vergleichsvorgang verwendet werden |
|

### Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions) {#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)
```


Initialisiert eine neue Instanz der Comparer-Klasse mit dem angegebenen Quelldateipfad, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) und [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.lang.String | Der Pfad zum Quelldokument, Ordner oder Text, der verglichen werden soll |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Die benutzerdefinierten Ladeoptionen, die auf das Dokument angewendet werden |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Die Vergleichereinstellungen, die für den Vergleichsvorgang verwendet werden |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Die Vergleichsoptionen für den Ordnervergleich |
|

### Comparer(String filePath, ComparerSettings settings) {#Comparer-java.lang.String-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(String filePath, ComparerSettings settings)
```


Initialisiert eine neue Instanz der Comparer-Klasse mit dem angegebenen Quelldateipfad und [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.lang.String | Der Pfad zum Quelldokument |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Die Vergleichereinstellungen, die für den Vergleichsvorgang verwendet werden |
|

### Comparer(Path filePath, ComparerSettings settings) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(Path filePath, ComparerSettings settings)
```


Initialisiert eine neue Instanz der Comparer-Klasse mit dem angegebenen Quelldateipfad und [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Der Pfad zum Quelldokument |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Die Vergleichereinstellungen, die für den Vergleichsvorgang verwendet werden |
|

### Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings)
```


Initialisiert eine neue Instanz der Comparer-Klasse mit dem angegebenen Quelldateipfad, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) und [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Der Pfad zum Quelldokument |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Die benutzerdefinierten Ladeoptionen, die auf das Dokument angewendet werden |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Die Vergleichereinstellungen, die für den Vergleichsvorgang verwendet werden |
|

### Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)
```


Initialisiert eine neue Instanz der Comparer-Klasse mit dem angegebenen Quelldateipfad, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) und [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Der Pfad zum Quelldokument oder Ordner |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Die benutzerdefinierten Ladeoptionen, die auf das Dokument angewendet werden |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Die Vergleichereinstellungen, die für den Vergleichsvorgang verwendet werden |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Die Vergleichsoptionen für den Ordnervergleich |
|

### Comparer(InputStream document) {#Comparer-java.io.InputStream-}
```
public Comparer(InputStream document)
```


Initialisiert eine neue Instanz der Comparer-Klasse mit dem angegebenen Quell-Dokumenten-Stream.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dokument | java.io.InputStream | Der Eingabestream des Quelldokuments |
|

### Comparer(InputStream document, LoadOptions loadOptions) {#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Comparer(InputStream document, LoadOptions loadOptions)
```


Initialisiert eine neue Instanz von Comparer mit dem angegebenen Quell-Dokumenten-Stream und [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dokument | java.io.InputStream | Der Eingabestream des Quelldokuments |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Die benutzerdefinierten Ladeoptionen, die auf das Dokument angewendet werden |
|

### Comparer(InputStream document, ComparerSettings settings) {#Comparer-java.io.InputStream-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(InputStream document, ComparerSettings settings)
```


Initialisiert eine neue Instanz der Comparer-Klasse mit dem angegebenen Quell-Dokumenten-Stream und [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dokument | java.io.InputStream | Der Eingabestream des Quelldokuments |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Die Vergleichereinstellungen, die für den Vergleichsvorgang verwendet werden |
|

### Comparer(InputStream document, LoadOptions loadOptions, ComparerSettings settings) {#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(InputStream document, LoadOptions loadOptions, ComparerSettings settings)
```


Initialisiert eine neue Instanz der Comparer-Klasse mit dem angegebenen Dokumenten-Stream, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) und [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dokument | java.io.InputStream | Der Stream mit Daten eines zu vergleichenden Dokuments |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Die benutzerdefinierten Ladeoptionen, die auf das Dokument angewendet werden |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Die Vergleichereinstellungen, die für den Vergleichsvorgang verwendet werden |
|

### Comparer(ComparerSettings settings) {#Comparer-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(ComparerSettings settings)
```


Initialisiert eine neue Instanz der Comparer-Klasse mit den angegebenen [ComparerSettings](../../com.groupdocs.comparison/comparersettings).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | die Einstellungen |
|

### FILE_PATH {#FILE-PATH}
```
public static final String FILE_PATH
```


### getSource() {#getSource--}
```
public final Document getSource()
```


Liefert das Quell-Dokument, das verglichen wird.


**Returns:**
[Document](../../com.groupdocs.comparison/document) - the source document

### getTargets() {#getTargets--}
```
public final List<Document> getTargets()
```


Liste der Ziel-Dokumente, die mit der Quelldatei verglichen werden.


**Returns:**
java.util.List<com.groupdocs.comparison.Document> - die Ziel-Dokumente

### compare() {#compare--}
```
public final Path compare()
```


Vergleicht die angegebene Datei mit den Ziel-Dokumenten, ohne das Ergebnis mit den Standardoptionen zu speichern.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Returns:**
java.nio.file.Path - der Pfad des Ergebnisdokuments oder null

### compare(String filePath) {#compare-java.lang.String-}
```
public final Path compare(String filePath)
```


Vergleicht die angegebene Datei mit den Ziel-Dokumenten und erzeugt ein Vergleichsergebnis.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.lang.String | Pfad des Ergebnisdokuments |
|

**Returns:**
java.nio.file.Path - Ergebnisdateipfad oder null. In einigen Situationen kann die Erweiterung geändert werden

### compare(Path filePath) {#compare-java.nio.file.Path-}
```
public final Path compare(Path filePath)
```


Vergleicht die angegebene Datei mit den Ziel-Dokumenten und erzeugt ein Vergleichsergebnis.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Pfad des Ergebnisdokuments |
|

**Returns:**
java.nio.file.Path - Ergebnisdateipfad, in einigen Situationen kann die Erweiterung geändert werden

### compare(OutputStream outputStream) {#compare-java.io.OutputStream-}
```
public final Path compare(OutputStream outputStream)
```


Vergleicht die angegebene Datei mit den Ziel-Dokumenten und schreibt das Vergleichsergebnis in den Ausgabestream.


Hinweis: In Fällen, in denen der Rückgabewert null ist, verwenden Sie die Daten, die in outputStream geschrieben wurden

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | outputStream | java.io.OutputStream | Ergebnisdokument-Stream |
|

**Returns:**
java.nio.file.Path - Ergebnisdateipfad oder null, wenn Daten aus outputStream verwendet werden müssen. In einigen Situationen kann die Erweiterung der Ergebnisdatei geändert werden

### compare(String filePath, CompareOptions compareOptions) {#compare-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(String filePath, CompareOptions compareOptions)
```


Vergleicht die angegebene Datei mit den Ziel-Dokumenten und schreibt das Vergleichsergebnis in den angegebenen Dateipfad.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.lang.String | Dateipfad des Ergebnisdokuments |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Die Vergleichsoptionen, die für den Vergleichsvorgang verwendet werden sollen |
|

**Returns:**
java.nio.file.Path - Ergebnisdateipfad, in einigen Situationen kann die Erweiterung geändert werden

### compare(Path filePath, CompareOptions compareOptions) {#compare-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(Path filePath, CompareOptions compareOptions)
```


Vergleicht die angegebene Datei mit den Ziel-Dokumenten und schreibt das Vergleichsergebnis in den angegebenen Dateipfad.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Dateipfad des Ergebnisdokuments |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Die Vergleichsoptionen, die für den Vergleichsvorgang verwendet werden sollen |
|

**Returns:**
java.nio.file.Path - Ergebnisdateipfad, in einigen Situationen kann die Erweiterung geändert werden

### compare(OutputStream stream, CompareOptions compareOptions) {#compare-java.io.OutputStream-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(OutputStream stream, CompareOptions compareOptions)
```


Vergleicht die angegebene Datei mit den Ziel-Dokumenten und schreibt das Vergleichsergebnis in den Ausgabestream.


Hinweis: Falls der Rückgabewert null ist, verwenden Sie die Daten, die in outputStream geschrieben wurden.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Stream | java.io.OutputStream | Ergebnisdokument-Stream |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Die Vergleichsoptionen, die für den Vergleichsvorgang verwendet werden sollen |
|

**Returns:**
java.nio.file.Path - Ergebnisdateipfad oder null, wenn Daten aus outputStream verwendet werden müssen. In einigen Situationen kann die Erweiterung der Ergebnisdatei geändert werden

### compare(SaveOptions saveOptions, CompareOptions compareOptions) {#compare-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(SaveOptions saveOptions, CompareOptions compareOptions)
```


Vergleicht die angegebene Datei mit den Ziel-Dokumenten, ohne das Ergebnis zu speichern.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparison options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Speicheroptionen |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Die Vergleichsoptionen, die für den Vergleichsvorgang verwendet werden sollen |
|

**Returns:**
java.nio.file.Path - der Pfad des Ergebnisdokuments oder null

### compare(String filePath, SaveOptions saveOptions) {#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-}
```
public final Path compare(String filePath, SaveOptions saveOptions)
```


Vergleicht die angegebene Datei mit den Ziel-Dokumenten und schreibt das Vergleichsergebnis in den angegebenen Dateipfad.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.lang.String | Dateipfad des Ergebnisdokuments |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Speicheroptionen |
|

**Returns:**
java.nio.file.Path - Ergebnisdateipfad, in einigen Situationen kann die Erweiterung geändert werden

### compare(Path filePath, SaveOptions saveOptions) {#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-}
```
public final Path compare(Path filePath, SaveOptions saveOptions)
```


Vergleicht die angegebene Datei mit den Ziel-Dokumenten und schreibt das Vergleichsergebnis in den angegebenen Dateipfad.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Dateipfad des Ergebnisdokuments |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Speicheroptionen |
|

**Returns:**
java.nio.file.Path - Ergebnisdateipfad, in einigen Situationen kann die Erweiterung geändert werden

### compare(OutputStream stream, SaveOptions saveOptions) {#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-}
```
public final Path compare(OutputStream stream, SaveOptions saveOptions)
```


Vergleicht die angegebene Datei mit den Ziel-Dokumenten und schreibt das Vergleichsergebnis in den angegebenen Dateipfad.


Hinweis: Falls der Rückgabewert null ist, verwenden Sie die Daten, die in outputStream geschrieben wurden

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Stream | java.io.OutputStream | Ergebnisdokument-Stream |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Speicheroptionen |
|

**Returns:**
java.nio.file.Path - Ergebnisdateipfad oder null, wenn Daten aus outputStream verwendet werden müssen. In einigen Situationen kann die Erweiterung der Ergebnisdatei geändert werden

### compare(CompareOptions compareOptions) {#compare-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(CompareOptions compareOptions)
```


Vergleicht die angegebene Datei mit den Ziel-Dokumenten, ohne das Ergebnis zu speichern.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Die Vergleichsoptionen, die für den Vergleichsvorgang verwendet werden sollen |
|

**Returns:**
java.nio.file.Path - der Pfad zur Ergebnisdatei oder null

### compare(OutputStream outputStream, SaveOptions saveOptions, CompareOptions compareOptions) {#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(OutputStream outputStream, SaveOptions saveOptions, CompareOptions compareOptions)
```


Vergleicht die angegebene Datei mit den Ziel-Dokumenten und schreibt das Vergleichsergebnis in den bereitgestellten Ausgabestream.


Hinweis: Falls der Rückgabewert null ist, verwenden Sie die Daten, die in outputStream geschrieben wurden

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | outputStream | java.io.OutputStream | Ergebnisdokument-Stream |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Die Speicheroptionen, die zum Speichern des Ergebnisdokuments verwendet werden sollen |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Die Vergleichsoptionen, die für den Vergleichsvorgang verwendet werden sollen |
|

**Returns:**
java.nio.file.Path - Ergebnisdateipfad oder null, wenn Daten aus outputStream verwendet werden müssen. In einigen Situationen kann die Erweiterung der Ergebnisdatei geändert werden

### compare(String filePath, SaveOptions saveOptions, CompareOptions compareOptions) {#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(String filePath, SaveOptions saveOptions, CompareOptions compareOptions)
```


Vergleicht die angegebene Datei mit den Ziel-Dokumenten und schreibt das Vergleichsergebnis in den angegebenen Dateipfad.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparison options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.lang.String | Dateipfad des Ergebnisdokuments |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Die Speicheroptionen, die zum Speichern des Ergebnisdokuments verwendet werden sollen |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Die Vergleichsoptionen, die für den Vergleichsvorgang verwendet werden sollen |
|

**Returns:**
java.nio.file.Path - Ergebnisdateipfad, in einigen Situationen kann die Erweiterung geändert werden

### compareDirectory(String filePath, CompareOptions compareOptions) {#compareDirectory-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public void compareDirectory(String filePath, CompareOptions compareOptions)
```


Vergleicht das angegebene Verzeichnis mit dem Zielverzeichnis und speichert das Vergleichsergebnis im angegebenen Dateipfad.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.lang.String | Der Dateipfad, an dem das Vergleichsergebnis gespeichert wird. |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Die Optionen, die für den Verzeichnisvergleichsprozess verwendet werden sollen |
|

### compareDirectory(Path filePath, CompareOptions compareOptions) {#compareDirectory-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public void compareDirectory(Path filePath, CompareOptions compareOptions)
```


Vergleicht das angegebene Verzeichnis mit dem Zielverzeichnis und speichert das Vergleichsergebnis im angegebenen Dateipfad.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Der Dateipfad, an dem das Vergleichsergebnis gespeichert wird. |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Die Optionen, die für den Verzeichnisvergleichsprozess verwendet werden sollen |
|

### compare(Path filePath, SaveOptions saveOptions, CompareOptions compareOptions) {#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(Path filePath, SaveOptions saveOptions, CompareOptions compareOptions)
```


Vergleicht die angegebene Datei mit den Ziel-Dokumenten und schreibt das Vergleichsergebnis in den angegebenen Dateipfad.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Dateipfad des Ergebnisdokuments |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Die Speicheroptionen, die zum Speichern des Ergebnisdokuments verwendet werden sollen |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Die Vergleichsoptionen, die für den Vergleichsvorgang verwendet werden sollen |
|

**Returns:**
java.nio.file.Path - Ergebnisdateipfad, in einigen Situationen kann die Erweiterung geändert werden

### add(String filePath) {#add-java.lang.String-}
```
public final void add(String filePath)
```


Fügt das angegebene Zieldokument zum Vergleichsprozess hinzu.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.lang.String | Der Pfad zum Ziel-Dokument, das hinzugefügt werden soll |
|

### add(String filePath, CompareOptions compareOptions) {#add-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public void add(String filePath, CompareOptions compareOptions)
```


Fügt das angegebene Zieldokument oder den Ordner zum Vergleichsprozess hinzu.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.lang.String | Der Pfad zum Ziel-Dokument oder -Ordner, das hinzugefügt werden soll |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Die Optionen für den Vergleich |
|

### add(Path filePath) {#add-java.nio.file.Path-}
```
public final void add(Path filePath)
```


Fügt das angegebene Zieldokument zum Vergleichsprozess hinzu.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Der Pfad zum Ziel-Dokument, das hinzugefügt werden soll |
|

### add(String[] filePaths) {#add-java.lang.String...-}
```
public final void add(String[] filePaths)
```


Fügt die angegebenen Zieldokumente zum Vergleichsprozess hinzu.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePaths | java.lang.String[] | Pfade zu den Ziel-Dokumenten, die hinzugefügt werden sollen |
|

### add(Path[] filePaths) {#add-java.nio.file.Path...-}
```
public final void add(Path[] filePaths)
```


Fügt die angegebenen Zieldokumente zum Vergleichsprozess hinzu.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePaths | java.nio.file.Path[] | Pfade zu den Ziel-Dokumenten, die hinzugefügt werden sollen |
|

### add(String filePath, LoadOptions loadOptions) {#add-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-}
```
public final void add(String filePath, LoadOptions loadOptions)
```


Fügt das angegebene Zieldokument zum Vergleichsprozess mit den angegebenen Ladeoptionen hinzu.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.lang.String | Pfad zum Ziel-Dokument, das hinzugefügt werden soll |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Die benutzerdefinierten Ladeoptionen, die auf das Dokument angewendet werden |
|

### add(Path filePath, LoadOptions loadOptions) {#add-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-}
```
public final void add(Path filePath, LoadOptions loadOptions)
```


Fügt das angegebene Zieldokument zum Vergleichsprozess mit den angegebenen Ladeoptionen hinzu.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Pfad zum Ziel-Dokument, das hinzugefügt werden soll |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Die benutzerdefinierten Ladeoptionen, die auf das Dokument angewendet werden |
|

### add(Path filePath, CompareOptions compareOptions) {#add-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public final void add(Path filePath, CompareOptions compareOptions)
```


Fügt das angegebene Zieldokument zum Vergleichsprozess mit den angegebenen Ladeoptionen hinzu.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Der Pfad zum Ziel-Dokument oder -Ordner, das hinzugefügt werden soll |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Die Optionen für den Vergleich |
|

### add(InputStream document) {#add-java.io.InputStream-}
```
public final void add(InputStream document)
```


Fügt das angegebene Zieldokument zum Vergleichsprozess hinzu.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dokument | java.io.InputStream | Der Stream mit Daten eines zu vergleichenden Dokuments |
|

### add(InputStream[] documents) {#add-java.io.InputStream...-}
```
public final void add(InputStream[] documents)
```


Fügt die angegebenen Zieldokumente zum Vergleichsprozess hinzu.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | documents | java.io.InputStream[] | Streams mit Daten von Dokumenten, die verglichen werden sollen |
|

### add(InputStream document, LoadOptions loadOptions) {#add-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-}
```
public final void add(InputStream document, LoadOptions loadOptions)
```


Fügt das angegebene Zieldokument zum Vergleichsprozess mit den angegebenen Ladeoptionen hinzu.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dokument | java.io.InputStream | Der Stream mit Daten eines zu vergleichenden Dokuments |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Die benutzerdefinierten Ladeoptionen, die auf das Dokument angewendet werden |
|

### getChanges() {#getChanges--}
```
public final ChangeInfo[] getChanges()
```


Ruft ein Array von [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo)-Objekten ab, die die während des Vergleichsprozesses erkannten Änderungen darstellen.


Verwenden Sie diese Methode, um detaillierte Informationen über die Änderungen zwischen dem Quelldokument und dem Zieldokument (en) zu erhalten.
Jedes [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo)-Objekt enthält Informationen wie den Typ der Änderung, den betroffenen Bereich,
und den Inhalt vor und nach der Änderung.

* More about how to obtain collection of detected differences between compared documents in Java: [How to get list of changes between documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Get+list+of+changes)
* More about how to get changes coordinates at pages image preview when comparing documents using GroupDocs.Comparison for Java: [How to get changes coordinates programmatically](../https://docs.groupdocs.com/display/comparisonjava/Get+changes+coordinates)


**Returns:**
com.groupdocs.comparison.result.ChangeInfo[] - ein Array von [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo)-Objekten, die die während des Vergleichs erkannten Änderungen darstellen

### getChanges(GetChangeOptions getChangeOptions) {#getChanges-com.groupdocs.comparison.options.GetChangeOptions-}
```
public final ChangeInfo[] getChanges(GetChangeOptions getChangeOptions)
```


Ruft ein Array von [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo)-Objekten ab, die die während des Vergleichsprozesses erkannten Änderungen darstellen.


Verwenden Sie diese Methode, um detaillierte Informationen über die Änderungen zwischen dem Quelldokument und dem Zieldokument (en) zu erhalten.
Jedes [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo)-Objekt enthält Informationen wie den Typ der Änderung, den betroffenen Bereich,
und den Inhalt vor und nach der Änderung.


Parameter [GetChangeOptions](../../com.groupdocs.comparison.options/getchangeoptions) ermöglicht das Filtern von Änderungen auf unterschiedliche Weise.

* More about how to obtain collection of detected differences between compared documents in Java: [How to get list of changes between documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Get+list+of+changes)
* More about how to get changes coordinates at pages image preview when comparing documents using GroupDocs.Comparison for Java: [How to get changes coordinates programmatically](../https://docs.groupdocs.com/display/comparisonjava/Get+changes+coordinates)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | getChangeOptions | [GetChangeOptions](../../com.groupdocs.comparison.options/getchangeoptions) | Das Objekt, das das Filtern von Änderungen ermöglicht |
|

**Returns:**
com.groupdocs.comparison.result.ChangeInfo[] - ein Array von [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo)-Objekten, die die während des Vergleichs erkannten Änderungen darstellen

### applyChanges(String filePath, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.lang.String-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(String filePath, ApplyChangeOptions applyChangeOptions)
```


Akzeptiert oder verwirft Änderungen und wendet sie auf das Ergebnisdokument an.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.lang.String | Dateipfad des Ergebnisdokuments |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | Die benutzerdefinierten Apply-Change-Optionen, um den Vorgang des Anwendens von Änderungen zu konfigurieren |
|

### applyChanges(Path filePath, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(Path filePath, ApplyChangeOptions applyChangeOptions)
```


Akzeptiert oder verwirft Änderungen und wendet sie auf das resultierende Dokument an.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Dateipfad des Ergebnisdokuments |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | Die benutzerdefinierten Apply-Change-Optionen, um den Vorgang des Anwendens von Änderungen zu konfigurieren |
|

### applyChanges(OutputStream document, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(OutputStream document, ApplyChangeOptions applyChangeOptions)
```


Akzeptiert oder verwirft Änderungen und wendet sie auf das resultierende Dokument an.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dokument | java.io.OutputStream | Ausgabestream des Ergebnisdokuments |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | Die benutzerdefinierten Apply-Change-Optionen, um den Vorgang des Anwendens von Änderungen zu konfigurieren |
|

### applyChanges(String filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(String filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)
```


Akzeptiert oder verwirft Änderungen und wendet sie auf das resultierende Dokument an.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.lang.String | Dateipfad des Ergebnisdokuments |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Die Speicheroptionen, um das Speichern des Ergebnisdokuments zu konfigurieren |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | Die benutzerdefinierten Apply-Change-Optionen, um den Vorgang des Anwendens von Änderungen zu konfigurieren |
|

### applyChanges(Path filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(Path filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)
```


Akzeptiert oder verwirft Änderungen und wendet sie auf das resultierende Dokument an.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Dateipfad des Ergebnisdokuments |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Die Speicheroptionen, um das Speichern des Ergebnisdokuments zu konfigurieren |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | Die benutzerdefinierten Apply-Change-Optionen, um den Vorgang des Anwendens von Änderungen zu konfigurieren |
|

### applyChanges(OutputStream document, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(OutputStream document, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)
```


Akzeptiert oder verwirft Änderungen und wendet sie auf das resultierende Dokument an.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dokument | java.io.OutputStream | Ausgabestream des Ergebnisdokuments |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Die Speicheroptionen, um das Speichern des Ergebnisdokuments zu konfigurieren |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | Die benutzerdefinierten Apply-Change-Optionen, um den Vorgang des Anwendens von Änderungen zu konfigurieren |
|

### getResultString() {#getResultString--}
```
public String getResultString()
```


Liefert die Ergebniszeichenfolge nach dem Vergleich (nur für Textvergleich).


**Returns:**
java.lang.String - die Ergebniszeichenkette

### getSourceFolder() {#getSourceFolder--}
```
public String getSourceFolder()
```


Gibt den Quellordner zurück, der verglichen wird.


**Returns:**
java.lang.String - der Quellordner

### getTargetFolder() {#getTargetFolder--}
```
public String getTargetFolder()
```


Gibt den Zielordner zurück, der verglichen wird.


**Returns:**
java.lang.String - der Zielordner

### selfComparisonCheck(Document source, Document target) {#selfComparisonCheck-com.groupdocs.comparison.Document-com.groupdocs.comparison.Document-}
```
public static void selfComparisonCheck(Document source, Document target)
```


Selbstvergleichsprüfung (e498c23). C# 7a7668c intern; öffentlich belassen, damit core.common-Tests aufrufen können.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [Document](../../com.groupdocs.comparison/document) |  |
| target | [Document](../../com.groupdocs.comparison/document) |  |

### close() {#close--}
```
public void close()
```


Gibt Ressourcen frei.


