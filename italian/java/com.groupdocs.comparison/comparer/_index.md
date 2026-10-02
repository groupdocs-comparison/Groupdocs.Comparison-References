---
title: "Comparer"
second_title: "Riferimento API di GroupDocs.Comparison per Java"
description: "La classe Comparer fornisce funzionalità per confrontare documenti e generare risultati di confronto."
type: docs
weight: 10
url: /it/java/com.groupdocs.comparison/comparer/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public class Comparer implements System.IDisposable, Closeable
```

La classe Comparer fornisce funzionalità per confrontare documenti e generare risultati di confronto.


Consente di confrontare vari tipi di documenti, come PDF, Word, Excel, PowerPoint e altri.


Esempio di utilizzo:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     CompareOptions compareOptions = new CompareOptions();
     compareOptions.setDetectStyleChanges(true);

     comparer.compare(resultFile, compareOptions);
 }
 
````


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [Comparer(String filePath)](#Comparer-java.lang.String-) | Inizializza una nuova istanza della classe Comparer con il percorso del file di origine specificato. |
|
|  | [Comparer(String filePath, CompareOptions compareOptions)](#Comparer-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | Inizializza una nuova istanza della classe Comparer con il percorso della cartella specificato e le opzioni di confronto. |
|
|  | [Comparer(Path filePath)](#Comparer-java.nio.file.Path-) | Inizializza una nuova istanza della classe Comparer con il percorso del file di origine specificato. |
|
|  | [Comparer(String filePath, LoadOptions loadOptions)](#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-) | Inizializza una nuova istanza di Comparer con il percorso del file di origine specificato e [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions). |
|
|  | [Comparer(Path filePath, LoadOptions loadOptions)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-) | Inizializza una nuova istanza di Comparer con il percorso del file di origine specificato e [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions). |
|
|  | [Comparer(Path filePath, CompareOptions compareOptions)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | Inizializza una nuova istanza di Comparer con il percorso del file di origine specificato e [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions). |
|
|  | [Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings)](#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-) | Inizializza una nuova istanza della classe Comparer con il percorso del file sorgente specificato, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) e [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)](#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-) | Inizializza una nuova istanza della classe Comparer con il percorso del file sorgente specificato, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) e [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(String filePath, ComparerSettings settings)](#Comparer-java.lang.String-com.groupdocs.comparison.ComparerSettings-) | Inizializza una nuova istanza della classe Comparer con il percorso del file sorgente specificato e [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(Path filePath, ComparerSettings settings)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.ComparerSettings-) | Inizializza una nuova istanza della classe Comparer con il percorso del file sorgente specificato e [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-) | Inizializza una nuova istanza della classe Comparer con il percorso del file sorgente specificato, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) e [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-) | Inizializza una nuova istanza della classe Comparer con il percorso del file sorgente specificato, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) e [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(InputStream document)](#Comparer-java.io.InputStream-) | Inizializza una nuova istanza della classe Comparer con lo stream del documento sorgente specificato. |
|
|  | [Comparer(InputStream document, LoadOptions loadOptions)](#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-) | Inizializza una nuova istanza di Comparer con lo stream del documento sorgente specificato e [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions). |
|
|  | [Comparer(InputStream document, ComparerSettings settings)](#Comparer-java.io.InputStream-com.groupdocs.comparison.ComparerSettings-) | Inizializza una nuova istanza della classe Comparer con lo stream del documento sorgente specificato e [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(InputStream document, LoadOptions loadOptions, ComparerSettings settings)](#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-) | Inizializza una nuova istanza della classe Comparer con lo stream del documento specificato, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) e [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(ComparerSettings settings)](#Comparer-com.groupdocs.comparison.ComparerSettings-) | Inizializza una nuova istanza della classe Comparer con i [ComparerSettings](../../com.groupdocs.comparison/comparersettings) specificati. |
|
## Campi

| Campo | Descrizione |
| --- | --- |
| [FILE_PATH](#FILE-PATH) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getSource()](#getSource--) | Ottiene il documento sorgente che viene confrontato. |
|
|  | [getTargets()](#getTargets--) | Elenco dei documenti di destinazione da confrontare con il file sorgente. |
|
|  | [compare()](#compare--) | Confronta il file specificato con i documenti di destinazione senza salvare il risultato, usando le opzioni predefinite. |
|
|  | [compare(String filePath)](#compare-java.lang.String-) | Confronta il file specificato con i documenti di destinazione e genera un risultato di confronto. |
|
|  | [compare(Path filePath)](#compare-java.nio.file.Path-) | Confronta il file specificato con i documenti di destinazione e genera un risultato di confronto. |
|
|  | [compare(OutputStream outputStream)](#compare-java.io.OutputStream-) | Confronta il file specificato con i documenti di destinazione e scrive il risultato del confronto nello stream di output. |
|
|  | [compare(String filePath, CompareOptions compareOptions)](#compare-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | Confronta il file specificato con i documenti di destinazione e scrive il risultato del confronto nel percorso file fornito. |
|
|  | [compare(Path filePath, CompareOptions compareOptions)](#compare-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | Confronta il file specificato con i documenti di destinazione e scrive il risultato del confronto nel percorso file fornito. |
|
|  | [compare(OutputStream stream, CompareOptions compareOptions)](#compare-java.io.OutputStream-com.groupdocs.comparison.options.CompareOptions-) | Confronta il file specificato con i documenti di destinazione e scrive il risultato del confronto nello stream di output. |
|
|  | [compare(SaveOptions saveOptions, CompareOptions compareOptions)](#compare-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | Confronta il file specificato con i documenti di destinazione senza salvare il risultato. |
|
|  | [compare(String filePath, SaveOptions saveOptions)](#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-) | Confronta il file specificato con i documenti di destinazione e scrive il risultato del confronto nel percorso file fornito. |
|
|  | [compare(Path filePath, SaveOptions saveOptions)](#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-) | Confronta il file specificato con i documenti di destinazione e scrive il risultato del confronto nel percorso file fornito. |
|
|  | [compare(OutputStream stream, SaveOptions saveOptions)](#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-) | Confronta il file specificato con i documenti di destinazione e scrive il risultato del confronto nel percorso file fornito. |
|
|  | [compare(CompareOptions compareOptions)](#compare-com.groupdocs.comparison.options.CompareOptions-) | Confronta il file specificato con i documenti di destinazione senza salvare il risultato. |
|
|  | [compare(OutputStream outputStream, SaveOptions saveOptions, CompareOptions compareOptions)](#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | Confronta il file specificato con i documenti di destinazione e scrive il risultato del confronto nello stream di output fornito. |
|
|  | [compare(String filePath, SaveOptions saveOptions, CompareOptions compareOptions)](#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | Confronta il file specificato con i documenti di destinazione e scrive il risultato del confronto nel percorso file fornito. |
|
|  | [compareDirectory(String filePath, CompareOptions compareOptions)](#compareDirectory-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | Confronta la directory specificata con la directory di destinazione e salva il risultato del confronto nel percorso file fornito. |
|
|  | [compareDirectory(Path filePath, CompareOptions compareOptions)](#compareDirectory-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | Confronta la directory specificata con la directory di destinazione e salva il risultato del confronto nel percorso file fornito. |
|
|  | [compare(Path filePath, SaveOptions saveOptions, CompareOptions compareOptions)](#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | Confronta il file specificato con i documenti di destinazione e scrive il risultato del confronto nel percorso file fornito. |
|
|  | [add(String filePath)](#add-java.lang.String-) | Aggiunge il documento di destinazione specificato al processo di confronto. |
|
|  | [add(String filePath, CompareOptions compareOptions)](#add-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | Aggiunge il documento o la cartella di destinazione specificati al processo di confronto. |
|
|  | [add(Path filePath)](#add-java.nio.file.Path-) | Aggiunge il documento di destinazione specificato al processo di confronto. |
|
|  | [add(String[] filePaths)](#add-java.lang.String...-) | Aggiunge i documenti di destinazione specificati al processo di confronto. |
|
|  | [add(Path[] filePaths)](#add-java.nio.file.Path...-) | Aggiunge i documenti di destinazione specificati al processo di confronto. |
|
|  | [add(String filePath, LoadOptions loadOptions)](#add-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-) | Aggiunge il documento di destinazione specificato al processo di confronto con le opzioni di caricamento specificate. |
|
|  | [add(Path filePath, LoadOptions loadOptions)](#add-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-) | Aggiunge il documento di destinazione specificato al processo di confronto con le opzioni di caricamento specificate. |
|
|  | [add(Path filePath, CompareOptions compareOptions)](#add-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | Aggiunge il documento di destinazione specificato al processo di confronto con le opzioni di caricamento specificate. |
|
|  | [add(InputStream document)](#add-java.io.InputStream-) | Aggiunge il documento di destinazione specificato al processo di confronto. |
|
|  | [add(InputStream[] documents)](#add-java.io.InputStream...-) | Aggiunge i documenti di destinazione specificati al processo di confronto. |
|
|  | [add(InputStream document, LoadOptions loadOptions)](#add-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-) | Aggiunge il documento di destinazione specificato al processo di confronto con le opzioni di caricamento specificate. |
|
|  | [getChanges()](#getChanges--) | Recupera un array di oggetti [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) che rappresentano le modifiche rilevate durante il processo di confronto. |
|
|  | [getChanges(GetChangeOptions getChangeOptions)](#getChanges-com.groupdocs.comparison.options.GetChangeOptions-) | Recupera un array di oggetti [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) che rappresentano le modifiche rilevate durante il processo di confronto. |
|
|  | [applyChanges(String filePath, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.lang.String-com.groupdocs.comparison.options.ApplyChangeOptions-) | Accetta o rifiuta le modifiche e le applica al documento risultato. |
|
|  | [applyChanges(Path filePath, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.ApplyChangeOptions-) | Accetta o rifiuta le modifiche e le applica al documento risultante. |
|
|  | [applyChanges(OutputStream document, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.ApplyChangeOptions-) | Accetta o rifiuta le modifiche e le applica al documento risultante. |
|
|  | [applyChanges(String filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-) | Accetta o rifiuta le modifiche e le applica al documento risultante. |
|
|  | [applyChanges(Path filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-) | Accetta o rifiuta le modifiche e le applica al documento risultante. |
|
|  | [applyChanges(OutputStream document, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-) | Accetta o rifiuta le modifiche e le applica al documento risultante. |
|
|  | [getResultString()](#getResultString--) | Ottiene la stringa del risultato dopo il confronto (solo per il confronto di testo). |
|
|  | [getSourceFolder()](#getSourceFolder--) | Restituisce la cartella sorgente che viene confrontata. |
|
|  | [getTargetFolder()](#getTargetFolder--) | Restituisce la cartella di destinazione che viene confrontata. |
|
|  | [selfComparisonCheck(Document source, Document target)](#selfComparisonCheck-com.groupdocs.comparison.Document-com.groupdocs.comparison.Document-) | Controllo di auto-confronto (e498c23). |
|
|  | [close()](#close--) | Rilascia le risorse. |
|
### Comparer(String filePath) {#Comparer-java.lang.String-}
```
public Comparer(String filePath)
```


Inizializza una nuova istanza della classe Comparer con il percorso del file di origine specificato.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.lang.String | Il percorso del documento sorgente |
|

### Comparer(String filePath, CompareOptions compareOptions) {#Comparer-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(String filePath, CompareOptions compareOptions)
```


Inizializza una nuova istanza della classe Comparer con il percorso della cartella specificato e le opzioni di confronto.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.lang.String | Il percorso del documento o della cartella sorgente |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Le opzioni di confronto per il confronto di cartelle |
|

### Comparer(Path filePath) {#Comparer-java.nio.file.Path-}
```
public Comparer(Path filePath)
```


Inizializza una nuova istanza della classe Comparer con il percorso del file di origine specificato.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Il percorso del documento sorgente |
|

### Comparer(String filePath, LoadOptions loadOptions) {#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Comparer(String filePath, LoadOptions loadOptions)
```


Inizializza una nuova istanza di Comparer con il percorso del file di origine specificato e [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.lang.String | Il percorso del documento sorgente |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Le opzioni di caricamento personalizzate da applicare al documento |
|

### Comparer(Path filePath, LoadOptions loadOptions) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Comparer(Path filePath, LoadOptions loadOptions)
```


Inizializza una nuova istanza di Comparer con il percorso del file di origine specificato e [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Il percorso del documento sorgente |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Le opzioni di caricamento personalizzate da applicare al documento |
|

### Comparer(Path filePath, CompareOptions compareOptions) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(Path filePath, CompareOptions compareOptions)
```


Inizializza una nuova istanza di Comparer con il percorso del file di origine specificato e [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Il percorso del documento sorgente |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Le opzioni di confronto per il confronto di cartelle |
|

### Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings) {#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings)
```


Inizializza una nuova istanza della classe Comparer con il percorso del file sorgente specificato, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) e [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.lang.String | Il percorso del documento sorgente |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Le opzioni di caricamento personalizzate da applicare al documento |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Le impostazioni del comparatore da utilizzare per il processo di confronto |
|

### Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions) {#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)
```


Inizializza una nuova istanza della classe Comparer con il percorso del file sorgente specificato, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) e [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.lang.String | Il percorso del documento, della cartella o del testo sorgente da confrontare |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Le opzioni di caricamento personalizzate da applicare al documento |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Le impostazioni del comparatore da utilizzare per il processo di confronto |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Le opzioni di confronto per il confronto di cartelle |
|

### Comparer(String filePath, ComparerSettings settings) {#Comparer-java.lang.String-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(String filePath, ComparerSettings settings)
```


Inizializza una nuova istanza della classe Comparer con il percorso del file sorgente specificato e [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.lang.String | Il percorso del documento sorgente |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Le impostazioni del comparatore da utilizzare per il processo di confronto |
|

### Comparer(Path filePath, ComparerSettings settings) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(Path filePath, ComparerSettings settings)
```


Inizializza una nuova istanza della classe Comparer con il percorso del file sorgente specificato e [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Il percorso del documento sorgente |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Le impostazioni del comparatore da utilizzare per il processo di confronto |
|

### Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings)
```


Inizializza una nuova istanza della classe Comparer con il percorso del file sorgente specificato, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) e [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Il percorso del documento sorgente |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Le opzioni di caricamento personalizzate da applicare al documento |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Le impostazioni del comparatore da utilizzare per il processo di confronto |
|

### Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)
```


Inizializza una nuova istanza della classe Comparer con il percorso del file sorgente specificato, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) e [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Il percorso del documento o della cartella sorgente |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Le opzioni di caricamento personalizzate da applicare al documento |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Le impostazioni del comparatore da utilizzare per il processo di confronto |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Le opzioni di confronto per il confronto di cartelle |
|

### Comparer(InputStream document) {#Comparer-java.io.InputStream-}
```
public Comparer(InputStream document)
```


Inizializza una nuova istanza della classe Comparer con lo stream del documento sorgente specificato.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | documento | java.io.InputStream | Il flusso di input del documento sorgente |
|

### Comparer(InputStream document, LoadOptions loadOptions) {#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Comparer(InputStream document, LoadOptions loadOptions)
```


Inizializza una nuova istanza di Comparer con lo stream del documento sorgente specificato e [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | documento | java.io.InputStream | Il flusso di input del documento sorgente |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Le opzioni di caricamento personalizzate da applicare al documento |
|

### Comparer(InputStream document, ComparerSettings settings) {#Comparer-java.io.InputStream-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(InputStream document, ComparerSettings settings)
```


Inizializza una nuova istanza della classe Comparer con lo stream del documento sorgente specificato e [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | documento | java.io.InputStream | Il flusso di input del documento sorgente |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Le impostazioni del comparatore da utilizzare per il processo di confronto |
|

### Comparer(InputStream document, LoadOptions loadOptions, ComparerSettings settings) {#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(InputStream document, LoadOptions loadOptions, ComparerSettings settings)
```


Inizializza una nuova istanza della classe Comparer con lo stream del documento specificato, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) e [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | documento | java.io.InputStream | Il flusso con i dati di un documento da confrontare |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Le opzioni di caricamento personalizzate da applicare al documento |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Le impostazioni del comparatore da utilizzare per il processo di confronto |
|

### Comparer(ComparerSettings settings) {#Comparer-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(ComparerSettings settings)
```


Inizializza una nuova istanza della classe Comparer con i [ComparerSettings](../../com.groupdocs.comparison/comparersettings) specificati.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | le impostazioni |
|

### FILE_PATH {#FILE-PATH}
```
public static final String FILE_PATH
```


### getSource() {#getSource--}
```
public final Document getSource()
```


Ottiene il documento sorgente che viene confrontato.


**Returns:**
[Document](../../com.groupdocs.comparison/document) - the source document

### getTargets() {#getTargets--}
```
public final List<Document> getTargets()
```


Elenco dei documenti di destinazione da confrontare con il file sorgente.


**Returns:**
java.util.List<com.groupdocs.comparison.Document> - i documenti di destinazione

### compare() {#compare--}
```
public final Path compare()
```


Confronta il file specificato con i documenti di destinazione senza salvare il risultato, usando le opzioni predefinite.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Returns:**
java.nio.file.Path - il percorso del documento risultato o null

### compare(String filePath) {#compare-java.lang.String-}
```
public final Path compare(String filePath)
```


Confronta il file specificato con i documenti di destinazione e genera un risultato di confronto.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.lang.String | Percorso del documento risultato |
|

**Returns:**
java.nio.file.Path - percorso del file risultato o null. In alcune situazioni la sua estensione può essere modificata

### compare(Path filePath) {#compare-java.nio.file.Path-}
```
public final Path compare(Path filePath)
```


Confronta il file specificato con i documenti di destinazione e genera un risultato di confronto.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Percorso del documento risultato |
|

**Returns:**
java.nio.file.Path - percorso del file risultato, in alcune situazioni la sua estensione può essere modificata

### compare(OutputStream outputStream) {#compare-java.io.OutputStream-}
```
public final Path compare(OutputStream outputStream)
```


Confronta il file specificato con i documenti di destinazione e scrive il risultato del confronto nello stream di output.


Nota: nei casi in cui il valore restituito è null, utilizzare i dati scritti in outputStream

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | outputStream | java.io.OutputStream | Flusso del documento risultato |
|

**Returns:**
java.nio.file.Path - percorso del file risultato o null quando i dati da  outputStream  devono essere usati. In alcune situazioni l'estensione del file risultato può essere modificata

### compare(String filePath, CompareOptions compareOptions) {#compare-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(String filePath, CompareOptions compareOptions)
```


Confronta il file specificato con i documenti di destinazione e scrive il risultato del confronto nel percorso file fornito.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.lang.String | Percorso del file del documento risultato |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Le opzioni di confronto da utilizzare per il processo di confronto |
|

**Returns:**
java.nio.file.Path - percorso del file risultato, in alcune situazioni la sua estensione può essere modificata

### compare(Path filePath, CompareOptions compareOptions) {#compare-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(Path filePath, CompareOptions compareOptions)
```


Confronta il file specificato con i documenti di destinazione e scrive il risultato del confronto nel percorso file fornito.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Percorso del file del documento risultato |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Le opzioni di confronto da utilizzare per il processo di confronto |
|

**Returns:**
java.nio.file.Path - percorso del file risultato, in alcune situazioni la sua estensione può essere modificata

### compare(OutputStream stream, CompareOptions compareOptions) {#compare-java.io.OutputStream-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(OutputStream stream, CompareOptions compareOptions)
```


Confronta il file specificato con i documenti di destinazione e scrive il risultato del confronto nello stream di output.


Nota: nel caso in cui il valore restituito sia null, utilizzare i dati scritti in outputStream.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | stream | java.io.OutputStream | Flusso del documento risultato |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Le opzioni di confronto da utilizzare per il processo di confronto |
|

**Returns:**
java.nio.file.Path - percorso del file risultato o null quando i dati da  outputStream  devono essere usati. In alcune situazioni l'estensione del file risultato può essere modificata

### compare(SaveOptions saveOptions, CompareOptions compareOptions) {#compare-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(SaveOptions saveOptions, CompareOptions compareOptions)
```


Confronta il file specificato con i documenti di destinazione senza salvare il risultato.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparison options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Opzioni di salvataggio |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Le opzioni di confronto da utilizzare per il processo di confronto |
|

**Returns:**
java.nio.file.Path - il percorso del documento risultato o null

### compare(String filePath, SaveOptions saveOptions) {#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-}
```
public final Path compare(String filePath, SaveOptions saveOptions)
```


Confronta il file specificato con i documenti di destinazione e scrive il risultato del confronto nel percorso file fornito.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.lang.String | Percorso del file del documento risultato |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Opzioni di salvataggio |
|

**Returns:**
java.nio.file.Path - percorso del file risultato, in alcune situazioni la sua estensione può essere modificata

### compare(Path filePath, SaveOptions saveOptions) {#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-}
```
public final Path compare(Path filePath, SaveOptions saveOptions)
```


Confronta il file specificato con i documenti di destinazione e scrive il risultato del confronto nel percorso file fornito.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Percorso del file del documento risultato |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Opzioni di salvataggio |
|

**Returns:**
java.nio.file.Path - percorso del file risultato, in alcune situazioni la sua estensione può essere modificata

### compare(OutputStream stream, SaveOptions saveOptions) {#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-}
```
public final Path compare(OutputStream stream, SaveOptions saveOptions)
```


Confronta il file specificato con i documenti di destinazione e scrive il risultato del confronto nel percorso file fornito.


Nota: nel caso in cui il valore di ritorno sia nullo, utilizzare i dati scritti in outputStream

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | stream | java.io.OutputStream | Flusso del documento risultato |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Opzioni di salvataggio |
|

**Returns:**
java.nio.file.Path - percorso del file risultato o null quando i dati da  outputStream  devono essere usati. In alcune situazioni l'estensione del file risultato può essere modificata

### compare(CompareOptions compareOptions) {#compare-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(CompareOptions compareOptions)
```


Confronta il file specificato con i documenti di destinazione senza salvare il risultato.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Le opzioni di confronto da utilizzare per il processo di confronto |
|

**Returns:**
java.nio.file.Path - il percorso al file di risultato o null

### compare(OutputStream outputStream, SaveOptions saveOptions, CompareOptions compareOptions) {#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(OutputStream outputStream, SaveOptions saveOptions, CompareOptions compareOptions)
```


Confronta il file specificato con i documenti di destinazione e scrive il risultato del confronto nello stream di output fornito.


Nota: nel caso in cui il valore di ritorno sia nullo, utilizzare i dati scritti in outputStream

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | outputStream | java.io.OutputStream | Flusso del documento risultato |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Le opzioni di salvataggio da utilizzare per il salvataggio del documento risultato |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Le opzioni di confronto da utilizzare per il processo di confronto |
|

**Returns:**
java.nio.file.Path - percorso del file risultato o null quando i dati da  outputStream  devono essere usati. In alcune situazioni l'estensione del file risultato può essere modificata

### compare(String filePath, SaveOptions saveOptions, CompareOptions compareOptions) {#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(String filePath, SaveOptions saveOptions, CompareOptions compareOptions)
```


Confronta il file specificato con i documenti di destinazione e scrive il risultato del confronto nel percorso file fornito.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparison options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.lang.String | Percorso del file del documento risultato |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Le opzioni di salvataggio da utilizzare per il salvataggio del documento risultato |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Le opzioni di confronto da utilizzare per il processo di confronto |
|

**Returns:**
java.nio.file.Path - percorso del file risultato, in alcune situazioni la sua estensione può essere modificata

### compareDirectory(String filePath, CompareOptions compareOptions) {#compareDirectory-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public void compareDirectory(String filePath, CompareOptions compareOptions)
```


Confronta la directory specificata con la directory di destinazione e salva il risultato del confronto nel percorso file fornito.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.lang.String | Il percorso del file dove verrà salvato il risultato del confronto. |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Le opzioni da utilizzare per il processo di confronto delle directory. |
|

### compareDirectory(Path filePath, CompareOptions compareOptions) {#compareDirectory-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public void compareDirectory(Path filePath, CompareOptions compareOptions)
```


Confronta la directory specificata con la directory di destinazione e salva il risultato del confronto nel percorso file fornito.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Il percorso del file dove verrà salvato il risultato del confronto. |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Le opzioni da utilizzare per il processo di confronto delle directory. |
|

### compare(Path filePath, SaveOptions saveOptions, CompareOptions compareOptions) {#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(Path filePath, SaveOptions saveOptions, CompareOptions compareOptions)
```


Confronta il file specificato con i documenti di destinazione e scrive il risultato del confronto nel percorso file fornito.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Percorso del file del documento risultato |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Le opzioni di salvataggio da utilizzare per il salvataggio del documento risultato |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Le opzioni di confronto da utilizzare per il processo di confronto |
|

**Returns:**
java.nio.file.Path - percorso del file risultato, in alcune situazioni la sua estensione può essere modificata

### add(String filePath) {#add-java.lang.String-}
```
public final void add(String filePath)
```


Aggiunge il documento di destinazione specificato al processo di confronto.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.lang.String | Il percorso al documento di destinazione da aggiungere |
|

### add(String filePath, CompareOptions compareOptions) {#add-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public void add(String filePath, CompareOptions compareOptions)
```


Aggiunge il documento o la cartella di destinazione specificati al processo di confronto.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.lang.String | Il percorso al documento o cartella di destinazione da aggiungere |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Le opzioni per il confronto |
|

### add(Path filePath) {#add-java.nio.file.Path-}
```
public final void add(Path filePath)
```


Aggiunge il documento di destinazione specificato al processo di confronto.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Il percorso al documento di destinazione da aggiungere |
|

### add(String[] filePaths) {#add-java.lang.String...-}
```
public final void add(String[] filePaths)
```


Aggiunge i documenti di destinazione specificati al processo di confronto.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePaths | java.lang.String[] | Percorsi ai documenti di destinazione da aggiungere |
|

### add(Path[] filePaths) {#add-java.nio.file.Path...-}
```
public final void add(Path[] filePaths)
```


Aggiunge i documenti di destinazione specificati al processo di confronto.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePaths | java.nio.file.Path[] | Percorsi ai documenti di destinazione da aggiungere |
|

### add(String filePath, LoadOptions loadOptions) {#add-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-}
```
public final void add(String filePath, LoadOptions loadOptions)
```


Aggiunge il documento di destinazione specificato al processo di confronto con le opzioni di caricamento specificate.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.lang.String | Percorso al documento di destinazione da aggiungere |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Le opzioni di caricamento personalizzate da applicare al documento |
|

### add(Path filePath, LoadOptions loadOptions) {#add-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-}
```
public final void add(Path filePath, LoadOptions loadOptions)
```


Aggiunge il documento di destinazione specificato al processo di confronto con le opzioni di caricamento specificate.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Percorso al documento di destinazione da aggiungere |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Le opzioni di caricamento personalizzate da applicare al documento |
|

### add(Path filePath, CompareOptions compareOptions) {#add-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public final void add(Path filePath, CompareOptions compareOptions)
```


Aggiunge il documento di destinazione specificato al processo di confronto con le opzioni di caricamento specificate.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Il percorso al documento o cartella di destinazione da aggiungere |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Le opzioni per il confronto |
|

### add(InputStream document) {#add-java.io.InputStream-}
```
public final void add(InputStream document)
```


Aggiunge il documento di destinazione specificato al processo di confronto.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | documento | java.io.InputStream | Il flusso con i dati di un documento da confrontare |
|

### add(InputStream[] documents) {#add-java.io.InputStream...-}
```
public final void add(InputStream[] documents)
```


Aggiunge i documenti di destinazione specificati al processo di confronto.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | documenti | java.io.InputStream[] | Stream con i dati dei documenti da confrontare |
|

### add(InputStream document, LoadOptions loadOptions) {#add-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-}
```
public final void add(InputStream document, LoadOptions loadOptions)
```


Aggiunge il documento di destinazione specificato al processo di confronto con le opzioni di caricamento specificate.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | documento | java.io.InputStream | Il flusso con i dati di un documento da confrontare |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Le opzioni di caricamento personalizzate da applicare al documento |
|

### getChanges() {#getChanges--}
```
public final ChangeInfo[] getChanges()
```


Recupera un array di oggetti [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) che rappresentano le modifiche rilevate durante il processo di confronto.


Utilizza questo metodo per ottenere informazioni dettagliate sulle modifiche tra il documento di origine e il(i) documento(i) di destinazione.
Ogni oggetto [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) contiene informazioni come il tipo di modifica, l'area interessata,
e il contenuto prima e dopo la modifica.

* More about how to obtain collection of detected differences between compared documents in Java: [How to get list of changes between documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Get+list+of+changes)
* More about how to get changes coordinates at pages image preview when comparing documents using GroupDocs.Comparison for Java: [How to get changes coordinates programmatically](../https://docs.groupdocs.com/display/comparisonjava/Get+changes+coordinates)


**Returns:**
com.groupdocs.comparison.result.ChangeInfo[] - un array di oggetti [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) che rappresentano le modifiche rilevate durante il processo di confronto

### getChanges(GetChangeOptions getChangeOptions) {#getChanges-com.groupdocs.comparison.options.GetChangeOptions-}
```
public final ChangeInfo[] getChanges(GetChangeOptions getChangeOptions)
```


Recupera un array di oggetti [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) che rappresentano le modifiche rilevate durante il processo di confronto.


Utilizza questo metodo per ottenere informazioni dettagliate sulle modifiche tra il documento di origine e il(i) documento(i) di destinazione.
Ogni oggetto [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) contiene informazioni come il tipo di modifica, l'area interessata,
e il contenuto prima e dopo la modifica.


Il parametro [GetChangeOptions](../../com.groupdocs.comparison.options/getchangeoptions) consente di filtrare le modifiche in modo diverso.

* More about how to obtain collection of detected differences between compared documents in Java: [How to get list of changes between documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Get+list+of+changes)
* More about how to get changes coordinates at pages image preview when comparing documents using GroupDocs.Comparison for Java: [How to get changes coordinates programmatically](../https://docs.groupdocs.com/display/comparisonjava/Get+changes+coordinates)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | getChangeOptions | [GetChangeOptions](../../com.groupdocs.comparison.options/getchangeoptions) | L'oggetto che consente di filtrare le modifiche |
|

**Returns:**
com.groupdocs.comparison.result.ChangeInfo[] - un array di oggetti [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) che rappresentano le modifiche rilevate durante il processo di confronto

### applyChanges(String filePath, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.lang.String-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(String filePath, ApplyChangeOptions applyChangeOptions)
```


Accetta o rifiuta le modifiche e le applica al documento risultato.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.lang.String | Percorso del file del documento risultato |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | Le opzioni personalizzate di applicazione delle modifiche per configurare il processo di applicazione delle modifiche |
|

### applyChanges(Path filePath, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(Path filePath, ApplyChangeOptions applyChangeOptions)
```


Accetta o rifiuta le modifiche e le applica al documento risultante.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Percorso del file del documento risultato |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | Le opzioni personalizzate di applicazione delle modifiche per configurare il processo di applicazione delle modifiche |
|

### applyChanges(OutputStream document, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(OutputStream document, ApplyChangeOptions applyChangeOptions)
```


Accetta o rifiuta le modifiche e le applica al documento risultante.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | documento | java.io.OutputStream | Stream di output del documento risultato |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | Le opzioni personalizzate di applicazione delle modifiche per configurare il processo di applicazione delle modifiche |
|

### applyChanges(String filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(String filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)
```


Accetta o rifiuta le modifiche e le applica al documento risultante.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.lang.String | Percorso del file del documento risultato |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Le opzioni di salvataggio per configurare il salvataggio del documento risultato |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | Le opzioni personalizzate di applicazione delle modifiche per configurare il processo di applicazione delle modifiche |
|

### applyChanges(Path filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(Path filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)
```


Accetta o rifiuta le modifiche e le applica al documento risultante.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Percorso del file del documento risultato |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Le opzioni di salvataggio per configurare il salvataggio del documento risultato |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | Le opzioni personalizzate di applicazione delle modifiche per configurare il processo di applicazione delle modifiche |
|

### applyChanges(OutputStream document, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(OutputStream document, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)
```


Accetta o rifiuta le modifiche e le applica al documento risultante.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | documento | java.io.OutputStream | Stream di output del documento risultato |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Le opzioni di salvataggio per configurare il salvataggio del documento risultato |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | Le opzioni personalizzate di applicazione delle modifiche per configurare il processo di applicazione delle modifiche |
|

### getResultString() {#getResultString--}
```
public String getResultString()
```


Ottiene la stringa del risultato dopo il confronto (solo per il confronto di testo).


**Returns:**
java.lang.String - la stringa risultato

### getSourceFolder() {#getSourceFolder--}
```
public String getSourceFolder()
```


Restituisce la cartella sorgente che viene confrontata.


**Returns:**
java.lang.String - la cartella di origine

### getTargetFolder() {#getTargetFolder--}
```
public String getTargetFolder()
```


Restituisce la cartella di destinazione che viene confrontata.


**Returns:**
java.lang.String - la cartella di destinazione

### selfComparisonCheck(Document source, Document target) {#selfComparisonCheck-com.groupdocs.comparison.Document-com.groupdocs.comparison.Document-}
```
public static void selfComparisonCheck(Document source, Document target)
```


Controllo di auto-confronto (e498c23). C# 7a7668c interno; mantenuto pubblico così i test core.common possono chiamarlo.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [Document](../../com.groupdocs.comparison/document) |  |
| target | [Document](../../com.groupdocs.comparison/document) |  |

### close() {#close--}
```
public void close()
```


Rilascia le risorse.


