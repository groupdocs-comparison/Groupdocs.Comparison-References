---
title: "Documento"
second_title: "Riferimento API di GroupDocs.Comparison per Java"
description: "Rappresenta un documento per il processo di confronto dei documenti."
type: docs
weight: 12
url: /it/java/com.groupdocs.comparison/document/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Document implements Closeable
```

Rappresenta un documento per il processo di confronto dei documenti.


La classe Document fornisce metodi per caricare, generare immagini di anteprima e manipolare i documenti durante il processo di confronto.


Esempio di utilizzo:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     try (IDocumentInfo info = comparer.getSource().getDocumentInfo()) {
         System.out.println("File type: " + info.getFileType());
         System.out.println("Number of pages: " + info.getPageCount());
         System.out.println("Document size: " + info.getSize());
     }
 }
 
````


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [Document(InputStream stream)](#Document-java.io.InputStream-) | Inizializza una nuova istanza della classe Document con lo stream del documento specificato. |
|
|  | [Document(String filePath)](#Document-java.lang.String-) | Inizializza una nuova istanza della classe Document con il percorso del documento specificato. |
|
|  | [Document(Path filePath)](#Document-java.nio.file.Path-) | Inizializza una nuova istanza della classe Document con il percorso del documento specificato. |
|
|  | [Document(Path filePath, String password)](#Document-java.nio.file.Path-java.lang.String-) | Inizializza una nuova istanza della classe Document con il percorso del documento specificato e una password. |
|
|  | [Document(Path filePath, LoadOptions loadOptions)](#Document-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-) | Inizializza una nuova istanza della classe Document con il percorso del documento specificato e le opzioni di caricamento. |
|
|  | [Document(String filePath, String password)](#Document-java.lang.String-java.lang.String-) | Inizializza una nuova istanza della classe Document con il percorso del documento specificato e una password. |
|
|  | [Document(String filePath, LoadOptions loadOptions)](#Document-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-) | Inizializza una nuova istanza della classe Document con il percorso del documento specificato e le opzioni di caricamento. |
|
|  | [Document(InputStream stream, String password)](#Document-java.io.InputStream-java.lang.String-) | Inizializza una nuova istanza della classe Document con lo stream del documento specificato e una password. |
|
|  | [Document(String filePathOrTextContent, boolean isLoadText)](#Document-java.lang.String-boolean-) | Inizializza una nuova istanza della classe Document con il percorso del documento o il contenuto testuale specificato e un flag che indica cosa è stato passato. |
|
|  | [Document(InputStream inputStream, LoadOptions loadOptions)](#Document-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-) | Inizializza una nuova istanza della classe Document con lo stream del documento specificato e le opzioni di caricamento. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getChanges()](#getChanges--) | Ottiene un elenco di oggetti [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) che rappresentano le modifiche rilevate durante il processo di confronto. |
|
|  | [setChanges(List<ChangeInfo> value)](#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--) | Imposta un elenco di oggetti [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) che rappresentano le modifiche rilevate durante il processo di confronto. |
|
|  | [getName()](#getName--) | Ottiene il nome del documento. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Imposta il nome del documento. |
|
|  | [getFileType()](#getFileType--) | Ottiene il tipo del documento. |
|
|  | [setFileType(FileType fileType)](#setFileType-com.groupdocs.comparison.result.FileType-) | Imposta il tipo del documento. |
|
|  | [createStream()](#createStream--) | Crea un nuovo stream con il contenuto del documento. |
|
|  | [getStreamLength()](#getStreamLength--) | Ottiene la dimensione del documento |
|
|  | [getPassword()](#getPassword--) | Ottiene la password del documento |
|
|  | [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.comparison.options.PreviewOptions-) | Genera anteprime del documento basate sulle [PreviewOptions](../../com.groupdocs.comparison.options/previewoptions) fornite. |
|
|  | [getDocumentInfo()](#getDocumentInfo--) | Ottiene informazioni sul documento, inclusi tipo di documento, numero di pagine, dimensioni delle pagine e altro. |
|
| [close()](#close--) |  |
### Document(InputStream stream) {#Document-java.io.InputStream-}
```
public Document(InputStream stream)
```


Inizializza una nuova istanza della classe Document con lo stream del documento specificato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | stream | java.io.InputStream | Stream del documento |
|

### Document(String filePath) {#Document-java.lang.String-}
```
public Document(String filePath)
```


Inizializza una nuova istanza della classe Document con il percorso del documento specificato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.lang.String | Percorso del documento |
|

### Document(Path filePath) {#Document-java.nio.file.Path-}
```
public Document(Path filePath)
```


Inizializza una nuova istanza della classe Document con il percorso del documento specificato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Percorso del documento |
|

### Document(Path filePath, String password) {#Document-java.nio.file.Path-java.lang.String-}
```
public Document(Path filePath, String password)
```


Inizializza una nuova istanza della classe Document con il percorso del documento specificato e una password.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Percorso del documento |
|
|  | password | java.lang.String | Password del documento |
|

### Document(Path filePath, LoadOptions loadOptions) {#Document-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Document(Path filePath, LoadOptions loadOptions)
```


Inizializza una nuova istanza della classe Document con il percorso del documento specificato e le opzioni di caricamento.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Percorso del documento |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Opzioni di caricamento |
|

### Document(String filePath, String password) {#Document-java.lang.String-java.lang.String-}
```
public Document(String filePath, String password)
```


Inizializza una nuova istanza della classe Document con il percorso del documento specificato e una password.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.lang.String | Percorso del documento |
|
|  | password | java.lang.String | Password del documento |
|

### Document(String filePath, LoadOptions loadOptions) {#Document-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Document(String filePath, LoadOptions loadOptions)
```


Inizializza una nuova istanza della classe Document con il percorso del documento specificato e le opzioni di caricamento.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.lang.String | Percorso del documento |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Opzioni di caricamento |
|

### Document(InputStream stream, String password) {#Document-java.io.InputStream-java.lang.String-}
```
public Document(InputStream stream, String password)
```


Inizializza una nuova istanza della classe Document con lo stream del documento specificato e una password.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | stream | java.io.InputStream | Stream del documento |
|
|  | password | java.lang.String | Password del documento |
|

### Document(String filePathOrTextContent, boolean isLoadText) {#Document-java.lang.String-boolean-}
```
public Document(String filePathOrTextContent, boolean isLoadText)
```


Inizializza una nuova istanza della classe Document con il percorso del documento o il contenuto testuale specificato e un flag che indica cosa è stato passato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePathOrTextContent | java.lang.String | il percorso del file |
|
|  | isLoadText | boolean | il testo caricato |
|

### Document(InputStream inputStream, LoadOptions loadOptions) {#Document-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Document(InputStream inputStream, LoadOptions loadOptions)
```


Inizializza una nuova istanza della classe Document con lo stream del documento specificato e le opzioni di caricamento.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | inputStream | java.io.InputStream | Stream del documento |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Opzioni di caricamento |
|

### getChanges() {#getChanges--}
```
public final List<ChangeInfo> getChanges()
```


Ottiene un elenco di oggetti [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) che rappresentano le modifiche rilevate durante il processo di confronto.


Utilizza questo metodo per ottenere informazioni dettagliate sulle modifiche tra il documento di origine e il(i) documento(i) di destinazione.
Ogni oggetto [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) contiene informazioni come il tipo di modifica, l'area interessata,
e il contenuto prima e dopo la modifica.


**Returns:**
java.util.List<com.groupdocs.comparison.result.ChangeInfo> - un elenco di oggetti [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) che rappresentano le modifiche rilevate durante il processo di confronto

### setChanges(List<ChangeInfo> value) {#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--}
```
public final void setChanges(List<ChangeInfo> value)
```


Imposta un elenco di oggetti [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) che rappresentano le modifiche rilevate durante il processo di confronto.


Utilizza questo metodo per ottenere informazioni dettagliate sulle modifiche tra il documento di origine e il(i) documento(i) di destinazione.
Ogni oggetto [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) contiene informazioni come il tipo di modifica, l'area interessata,
e il contenuto prima e dopo la modifica.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | java.util.List<com.groupdocs.comparison.result.ChangeInfo> | un elenco di oggetti [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) che rappresentano le modifiche rilevate durante il processo di confronto |
|

### getName() {#getName--}
```
public final String getName()
```


Ottiene il nome del documento.


**Returns:**
java.lang.String - il nome del documento

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Imposta il nome del documento.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.lang.String | il nome del documento |
|

### getFileType() {#getFileType--}
```
public FileType getFileType()
```


Ottiene il tipo del documento.


**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the type of the document

### setFileType(FileType fileType) {#setFileType-com.groupdocs.comparison.result.FileType-}
```
public void setFileType(FileType fileType)
```


Imposta il tipo del documento.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.comparison.result/filetype) | il tipo del documento |
|

### createStream() {#createStream--}
```
public InputStream createStream()
```


Crea un nuovo stream con il contenuto del documento.


**Returns:**
java.io.InputStream - lo stream con il contenuto del documento

### getStreamLength() {#getStreamLength--}
```
public long getStreamLength()
```


Ottiene la dimensione del documento


**Returns:**
long - la dimensione del documento

### getPassword() {#getPassword--}
```
public String getPassword()
```


Ottiene la password del documento


**Returns:**
java.lang.String - la password del documento

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.comparison.options.PreviewOptions-}
```
public final void generatePreview(PreviewOptions previewOptions)
```


Genera anteprime del documento basate sulle [PreviewOptions](../../com.groupdocs.comparison.options/previewoptions) fornite.


Questo metodo genera anteprime delle pagine del documento in base alle opzioni specificate, come il formato dell'anteprima,
i numeri di pagina e il provider dello stream di output. Le anteprime generate possono essere salvate o ulteriormente elaborate secondo necessità.

* Learn more about how to generate previews for document pages: [How to generate document pages preview using GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Generate+document+pages+preview)


Esempio di utilizzo:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     PreviewOptions previewOptions = new PreviewOptions(
             pageNumber -> Files.newOutputStream(Paths.get("preview-image-page-" + pageNumber + ".png"))
     );
     previewOptions.setPreviewFormat(PreviewFormats.PNG);
     previewOptions.setPageNumbers(new int[]{1, 2});
     comparer.getSource().generatePreview(previewOptions);
 }
 
````



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | previewOptions | [PreviewOptions](../../com.groupdocs.comparison.options/previewoptions) | Le opzioni di anteprima che specificano il formato, i numeri di pagina e così via |
|

### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Ottiene informazioni sul documento, inclusi tipo di documento, numero di pagine, dimensioni delle pagine e altro.

* Learn more about document file type, page count, size, and other format-specific properties: [How to get document info using GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Get+file+info)


**Returns:**
[IDocumentInfo](../../com.groupdocs.comparison.interfaces/idocumentinfo) - the document information

### close() {#close--}
```
public void close()
```




