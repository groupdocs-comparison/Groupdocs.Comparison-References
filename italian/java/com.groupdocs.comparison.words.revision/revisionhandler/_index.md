---
title: "RevisionHandler"
second_title: "Riferimento API di GroupDocs.Comparison per Java"
description: "Rappresenta una classe che controlla la gestione delle revisioni."
type: docs
weight: 11
url: /it/java/com.groupdocs.comparison.words.revision/revisionhandler/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class RevisionHandler implements Closeable
```

Rappresenta una classe che controlla la gestione delle revisioni.


La classe RevisionHandler consente di lavorare con le revisioni nei documenti.
Fornisce metodi per recuperare l'elenco delle revisioni, applicare modifiche alle revisioni e salvare il documento modificato.


Esempio di utilizzo:

````

 try (RevisionHandler revisionHandler = new RevisionHandler(sourceFile)) {
     List revisionList = revisionHandler.getRevisions();

     for (RevisionInfo revisionInfo : revisionList) {
         if (revisionInfo.getType() == RevisionType.DELETION)
             // Set an action to be applied to the revision
             revisionInfo.setAction(RevisionAction.Accept);
     }
     // Create an instance of ApplyRevisionOptions
     ApplyRevisionOptions revisionChanges = new ApplyRevisionOptions();
     revisionChanges.setChanges(revisionList);
     // Apply the revisions using the options
     revisionHandler.applyRevisionChanges(resultFile, revisionChanges);
 }
 
````


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [RevisionHandler(String filePath)](#RevisionHandler-java.lang.String-) | Inizializza una nuova istanza della classe RevisionHandler con il percorso del file contenente le revisioni. |
|
|  | [RevisionHandler(Path filePath)](#RevisionHandler-java.nio.file.Path-) | Inizializza una nuova istanza della classe RevisionHandler con il percorso del file contenente le revisioni. |
|
|  | [RevisionHandler(InputStream file, FileType fileType)](#RevisionHandler-java.io.InputStream-com.groupdocs.comparison.result.FileType-) | Inizializza una nuova istanza della classe RevisionHandler con un flusso di file contenente le revisioni. |
|
|  | [RevisionHandler(Document document)](#RevisionHandler-com.aspose.words.Document-) | Inizializza una nuova istanza della classe RevisionHandler con un documento. |
|
## Campi

| Campo | Descrizione |
| --- | --- |
| [SOURCE_PATH_IS_NULL](#SOURCE-PATH-IS-NULL) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getRevisions()](#getRevisions--) | Ottiene l'elenco di tutte le revisioni. |
|
|  | [applyRevisionChanges(ApplyRevisionOptions changes)](#applyRevisionChanges-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | Elabora le modifiche nelle revisioni e le applica al file originale. |
|
|  | [applyRevisionChanges(Path filePath, ApplyRevisionOptions changes)](#applyRevisionChanges-java.nio.file.Path-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | Elabora le modifiche nelle revisioni e scrive il risultato nel file specificato. |
|
|  | [applyRevisionChanges(String filePath, ApplyRevisionOptions changes)](#applyRevisionChanges-java.lang.String-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | Elabora le modifiche nelle revisioni e scrive il risultato nel file specificato. |
|
|  | [applyRevisionChanges(OutputStream outputStream, ApplyRevisionOptions changes)](#applyRevisionChanges-java.io.OutputStream-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | Elabora le modifiche nelle revisioni e scrive il risultato nel flusso del documento. |
|
| [close()](#close--) |  |
### RevisionHandler(String filePath) {#RevisionHandler-java.lang.String-}
```
public RevisionHandler(String filePath)
```


Inizializza una nuova istanza della classe RevisionHandler con il percorso del file contenente le revisioni.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.lang.String | Il percorso del file. |
|

### RevisionHandler(Path filePath) {#RevisionHandler-java.nio.file.Path-}
```
public RevisionHandler(Path filePath)
```


Inizializza una nuova istanza della classe RevisionHandler con il percorso del file contenente le revisioni.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Il percorso del file. |
|

### RevisionHandler(InputStream file, FileType fileType) {#RevisionHandler-java.io.InputStream-com.groupdocs.comparison.result.FileType-}
```
public RevisionHandler(InputStream file, FileType fileType)
```


Inizializza una nuova istanza della classe RevisionHandler con un flusso di file contenente le revisioni.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | file | java.io.InputStream | Il flusso del documento sorgente. |
|
|  | fileType | [FileType](../../com.groupdocs.comparison.result/filetype) | Il tipo del file. |
|

### RevisionHandler(Document document) {#RevisionHandler-com.aspose.words.Document-}
```
public RevisionHandler(Document document)
```


Inizializza una nuova istanza della classe RevisionHandler con un documento.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | documento | com.aspose.words.Document | Il documento. |
|

### SOURCE_PATH_IS_NULL {#SOURCE-PATH-IS-NULL}
```
public static final String SOURCE_PATH_IS_NULL
```


### getRevisions() {#getRevisions--}
```
public List<RevisionInfo> getRevisions()
```


Ottiene l'elenco di tutte le revisioni.


Poiché le revisioni erano originariamente ordinate in un gruppo, le revisioni devono essere prelevate da una Lista.
Nella Lista, una singola revisione può essere suddivisa in più revisioni con lo stesso testo generale.
Poiché la Lista può contenere revisioni con lo stesso testo generale, ciò deve essere controllato durante la creazione di un elenco di revisioni per l'utente.
Questo è controllato qui usando i gruppi List\<RevisionGroup\>.


**Returns:**
java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> - l'elenco delle revisioni.

### applyRevisionChanges(ApplyRevisionOptions changes) {#applyRevisionChanges-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(ApplyRevisionOptions changes)
```


Elabora le modifiche nelle revisioni e le applica al file originale.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | L'elenco delle revisioni modificate. |
|

### applyRevisionChanges(Path filePath, ApplyRevisionOptions changes) {#applyRevisionChanges-java.nio.file.Path-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(Path filePath, ApplyRevisionOptions changes)
```


Elabora le modifiche nelle revisioni e scrive il risultato nel file specificato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Il percorso del file di risultato. |
|
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | L'elenco delle revisioni modificate. |
|

### applyRevisionChanges(String filePath, ApplyRevisionOptions changes) {#applyRevisionChanges-java.lang.String-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(String filePath, ApplyRevisionOptions changes)
```


Elabora le modifiche nelle revisioni e scrive il risultato nel file specificato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.lang.String | Il percorso del file di risultato. |
|
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | L'elenco delle revisioni modificate. |
|

### applyRevisionChanges(OutputStream outputStream, ApplyRevisionOptions changes) {#applyRevisionChanges-java.io.OutputStream-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(OutputStream outputStream, ApplyRevisionOptions changes)
```


Elabora le modifiche nelle revisioni e scrive il risultato nel flusso del documento.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | outputStream | java.io.OutputStream | Il flusso del documento di risultato. |
|
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | L'elenco delle revisioni modificate. |
|

### close() {#close--}
```
public void close()
```




