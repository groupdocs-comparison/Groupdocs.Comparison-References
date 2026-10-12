---
title: "LoadOptions"
second_title: "Riferimento API di GroupDocs.Comparison per Java"
description: "Consente di specificare opzioni aggiuntive durante il caricamento di un documento."
type: docs
weight: 10
url: /it/java/com.groupdocs.comparison.options.load/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

Consente di specificare opzioni aggiuntive durante il caricamento di un documento.


Esempio di utilizzo:

````

 final LoadOptions loadOptions = new LoadOptions();
 loadOptions.setPassword("passw");
 loadOptions.setFileType(FileType.PDF);

 try (Comparer comparer = new Comparer(sourceFile, loadOptions)) {
    comparer.add(targetFile);

    comparer.compare(resultFile);
 }
 
````


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [LoadOptions()](#LoadOptions--) | Inizializza una nuova istanza della classe LoadOptions. |
|
|  | [LoadOptions(boolean isLoadText)](#LoadOptions-boolean-) | Inizializza una nuova istanza della classe LoadOptions con un flag che indica che la stringa di input è un testo da confrontare, non un percorso. |
|
|  | [LoadOptions(String password)](#LoadOptions-java.lang.String-) | Inizializza una nuova istanza della classe LoadOptions con una password per caricare il documento. |
|
|  | [LoadOptions(boolean isLoadText, String password)](#LoadOptions-boolean-java.lang.String-) | Inizializza una nuova istanza della classe LoadOptions con un flag che indica che la stringa di input è un testo da confrontare e una password per caricare il documento. |
|
|  | [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.comparison.result.FileType-) | Inizializza una nuova istanza della classe LoadOptions con un tipo di file. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [isLoadText()](#isLoadText--) | Restituisce un flag che indica che la stringa passata al costruttore [Comparer](../../com.groupdocs.comparison/comparer) o al metodo [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) è un testo di confronto, non percorsi di file (solo per il confronto di testo). |
|
|  | [setLoadText(boolean value)](#setLoadText-boolean-) | Imposta un flag che indica che la stringa passata al costruttore [Comparer](../../com.groupdocs.comparison/comparer) o al metodo [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) è un testo di confronto, non percorsi di file (solo per il confronto di testo). |
|
|  | [getPassword()](#getPassword--) | Restituisce una password che verrà utilizzata per caricare un documento. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Imposta una password da utilizzare per caricare un documento. |
|
|  | [getFontDirectories()](#getFontDirectories--) | Restituisce un elenco di directory in cui sono posizionati i file di font per caricare un documento. |
|
|  | [setFontDirectories(List<String> value)](#setFontDirectories-java.util.List-java.lang.String--) | Imposta un elenco di directory in cui sono posizionati i file di font per caricare un documento. |
|
|  | [getFileType()](#getFileType--) | Restituisce il tipo di file che viene caricato. |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.comparison.result.FileType-) | Imposta il tipo di file che viene caricato. |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


Inizializza una nuova istanza della classe LoadOptions.


### LoadOptions(boolean isLoadText) {#LoadOptions-boolean-}
```
public LoadOptions(boolean isLoadText)
```


Inizializza una nuova istanza della classe LoadOptions con un flag che indica che la stringa di input è un testo da confrontare, non un percorso.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | isLoadText | boolean | Il flag che indica che la stringa di input è un testo da confrontare, non un percorso |
|

### LoadOptions(String password) {#LoadOptions-java.lang.String-}
```
public LoadOptions(String password)
```


Inizializza una nuova istanza della classe LoadOptions con una password per caricare il documento.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | password | java.lang.String | La password per caricare il documento |
|

### LoadOptions(boolean isLoadText, String password) {#LoadOptions-boolean-java.lang.String-}
```
public LoadOptions(boolean isLoadText, String password)
```


Inizializza una nuova istanza della classe LoadOptions con un flag che indica che la stringa di input è un testo da confrontare e una password per caricare il documento.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | isLoadText | boolean | Il flag che indica che la stringa di input è un testo da confrontare, non un percorso |
|
|  | password | java.lang.String | La password per caricare il documento |
|

### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.comparison.result.FileType-}
```
public LoadOptions(FileType fileType)
```


Inizializza una nuova istanza della classe LoadOptions con un tipo di file.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.comparison.result/filetype) | Il tipo del file |
|

### isLoadText() {#isLoadText--}
```
public boolean isLoadText()
```


Restituisce un flag che indica che la stringa passata al costruttore [Comparer](../../com.groupdocs.comparison/comparer) o al metodo [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) è un testo di confronto, non percorsi di file (solo per il confronto di testo).


**Returns:**
boolean - true se la stringa di input è un testo da confrontare, altrimenti false

### setLoadText(boolean value) {#setLoadText-boolean-}
```
public void setLoadText(boolean value)
```


Imposta un flag che indica che la stringa passata al costruttore [Comparer](../../com.groupdocs.comparison/comparer) o al metodo [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) è un testo di confronto, non percorsi di file (solo per il confronto di testo).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | true se la stringa di input è un testo da confrontare, altrimenti false |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Restituisce una password che verrà utilizzata per caricare un documento.


**Returns:**
java.lang.String - la password per caricare il documento

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Imposta una password da utilizzare per caricare un documento.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.lang.String | La password per caricare il documento |
|

### getFontDirectories() {#getFontDirectories--}
```
public List<String> getFontDirectories()
```


Restituisce un elenco di directory in cui sono posizionati i file di font per caricare un documento.


**Returns:**
java.util.List<java.lang.String> - l'elenco delle directory con file di font

### setFontDirectories(List<String> value) {#setFontDirectories-java.util.List-java.lang.String--}
```
public void setFontDirectories(List<String> value)
```


Imposta un elenco di directory in cui sono posizionati i file di font per caricare un documento.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.util.List<java.lang.String> | L'elenco delle directory con file di font |
|

### getFileType() {#getFileType--}
```
public FileType getFileType()
```


Restituisce il tipo di file che viene caricato.


**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the type of the file

### setFileType(FileType value) {#setFileType-com.groupdocs.comparison.result.FileType-}
```
public void setFileType(FileType value)
```


Imposta il tipo di file che viene caricato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [FileType](../../com.groupdocs.comparison.result/filetype) | Il tipo del file |
|

