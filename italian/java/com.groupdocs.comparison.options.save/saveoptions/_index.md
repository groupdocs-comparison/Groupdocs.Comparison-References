---
title: "SaveOptions"
second_title: "Riferimento API di GroupDocs.Comparison per Java"
description: "Consente di specificare opzioni aggiuntive durante il salvataggio di un documento."
type: docs
weight: 10
url: /it/java/com.groupdocs.comparison.options.save/saveoptions/
---
**Inheritance:**
java.lang.Object
```
public class SaveOptions
```

Consente di specificare opzioni aggiuntive durante il salvataggio di un documento.


Esempio di utilizzo:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    final SaveOptions saveOptions = new SaveOptions();
    saveOptions.setPassword("passw");

    comparer.compare(resultFile, saveOptions);
 }
 
````


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [SaveOptions()](#SaveOptions--) | Inizializza una nuova istanza della classe SaveOptions. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getCloneMetadataType()](#getCloneMetadataType--) | Ottiene una strategia di elaborazione del salvataggio dei metadati del documento risultato. |
|
|  | [setCloneMetadataType(MetadataType value)](#setCloneMetadataType-com.groupdocs.comparison.options.enums.MetadataType-) | Imposta una strategia di elaborazione del salvataggio dei metadati del documento risultato. |
|
|  | [getFileAuthorMetadata()](#getFileAuthorMetadata--) | Ottiene un oggetto metadata che verrà impostato nel documento risultato quando [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) è impostato su [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR). |
|
|  | [setFileAuthorMetadata(FileAuthorMetadata value)](#setFileAuthorMetadata-com.groupdocs.comparison.options.FileAuthorMetadata-) | Imposta un oggetto metadata che dovrebbe essere impostato nel documento risultato quando [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) è impostato su [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR). |
|
|  | [getPassword()](#getPassword--) | Ottiene una password per il documento risultato. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Imposta una password per il documento risultato. |
|
|  | [getFolderPath()](#getFolderPath--) | Ottiene il percorso della cartella in cui verranno salvate le immagini risultato. |
|
|  | [setFolderPath(String value)](#setFolderPath-java.lang.String-) | Imposta il percorso della cartella in cui dovrebbero essere salvate le immagini risultato. |
|
|  | [setFolderPath(Path value)](#setFolderPath-java.nio.file.Path-) | Imposta il percorso della cartella in cui dovrebbero essere salvate le immagini risultato. |
|
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```


Inizializza una nuova istanza della classe SaveOptions.


### getCloneMetadataType() {#getCloneMetadataType--}
```
public final MetadataType getCloneMetadataType()
```


Ottiene una strategia di elaborazione del salvataggio dei metadati del documento risultato.
I valori possibili sono nell'enum [MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype)


**Returns:**
[MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) - the stragegy of processing metadata

### setCloneMetadataType(MetadataType value) {#setCloneMetadataType-com.groupdocs.comparison.options.enums.MetadataType-}
```
public final void setCloneMetadataType(MetadataType value)
```


Imposta una strategia di elaborazione del salvataggio dei metadati del documento risultato.
I valori possibili sono nell'enum [MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) | La strategia di elaborazione dei metadati |
|

### getFileAuthorMetadata() {#getFileAuthorMetadata--}
```
public final FileAuthorMetadata getFileAuthorMetadata()
```


Ottiene un oggetto metadata che verrà impostato nel documento risultato quando [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) è impostato su [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR).


**Returns:**
[FileAuthorMetadata](../../com.groupdocs.comparison.options/fileauthormetadata) - the metadata object

### setFileAuthorMetadata(FileAuthorMetadata value) {#setFileAuthorMetadata-com.groupdocs.comparison.options.FileAuthorMetadata-}
```
public final void setFileAuthorMetadata(FileAuthorMetadata value)
```


Imposta un oggetto metadata che dovrebbe essere impostato nel documento risultato quando [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) è impostato su [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [FileAuthorMetadata](../../com.groupdocs.comparison.options/fileauthormetadata) | L'oggetto metadata |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Ottiene una password per il documento risultato.


**Returns:**
java.lang.String - la password

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Imposta una password per il documento risultato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.lang.String | La password |
|

### getFolderPath() {#getFolderPath--}
```
public final String getFolderPath()
```


Ottiene il percorso della cartella in cui verranno salvate le immagini risultato.
Utilizzato solo per il confronto di immagini.


**Returns:**
java.lang.String - il percorso della cartella per salvare le immagini risultato

### setFolderPath(String value) {#setFolderPath-java.lang.String-}
```
public final void setFolderPath(String value)
```


Imposta il percorso della cartella in cui dovrebbero essere salvate le immagini risultato.
Utilizzato solo per il confronto di immagini.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.lang.String | Il percorso della cartella per salvare le immagini risultato |
|

### setFolderPath(Path value) {#setFolderPath-java.nio.file.Path-}
```
public final void setFolderPath(Path value)
```


Imposta il percorso della cartella in cui dovrebbero essere salvate le immagini risultato.
Utilizzato solo per il confronto di immagini.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.nio.file.Path | Il percorso della cartella per salvare le immagini risultato |
|

