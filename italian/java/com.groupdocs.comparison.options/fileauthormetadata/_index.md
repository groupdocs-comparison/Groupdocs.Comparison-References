---
title: "FileAuthorMetadata"
second_title: "Riferimento API di GroupDocs.Comparison per Java"
description: "Consente di configurare le informazioni sui metadati dell'autore del documento."
type: docs
weight: 12
url: /it/java/com.groupdocs.comparison.options/fileauthormetadata/
---
**Inheritance:**
java.lang.Object
```
public class FileAuthorMetadata
```

Consente di configurare le informazioni sui metadati dell'autore del documento.


Esempio di utilizzo:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     SaveOptions saveOptions = new SaveOptions();
     saveOptions.setCloneMetadataType(MetadataType.FILE_AUTHOR);

     final FileAuthorMetadata fileAuthorMetadata = new FileAuthorMetadata();
     fileAuthorMetadata.setAuthor("Tom");
     fileAuthorMetadata.setCompany("GroupDocs");
     fileAuthorMetadata.setLastSaveBy("Jack");

     saveOptions.setFileAuthorMetadata(fileAuthorMetadata);

     comparer.compare(resultFile, saveOptions);
 }
 
````


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [FileAuthorMetadata()](#FileAuthorMetadata--) | Inizializza una nuova istanza della classe FileAuthorMetadata. |
|
## Campi

| Campo | Descrizione |
| --- | --- |
| [GROUP_DOCS](#GROUP-DOCS) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getAuthor()](#getAuthor--) | Ottiene l'autore di un documento. |
|
|  | [setAuthor(String value)](#setAuthor-java.lang.String-) | Imposta l'autore di un documento. |
|
|  | [getLastSaveBy()](#getLastSaveBy--) | Ottiene il nome della persona che ha salvato il documento per l'ultima volta. |
|
|  | [setLastSaveBy(String value)](#setLastSaveBy-java.lang.String-) | Imposta il nome della persona che ha salvato il documento per l'ultima volta. |
|
|  | [getCompany()](#getCompany--) | Ottiene il nome di un'azienda di cui è il documento. |
|
|  | [setCompany(String value)](#setCompany-java.lang.String-) | Imposta il nome di un'azienda di cui è il documento. |
|
### FileAuthorMetadata() {#FileAuthorMetadata--}
```
public FileAuthorMetadata()
```


Inizializza una nuova istanza della classe FileAuthorMetadata.


### GROUP_DOCS {#GROUP-DOCS}
```
public static final String GROUP_DOCS
```


### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```


Ottiene l'autore di un documento.


**Returns:**
java.lang.String - l'autore

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```


Imposta l'autore di un documento.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.lang.String | L'autore |
|

### getLastSaveBy() {#getLastSaveBy--}
```
public final String getLastSaveBy()
```


Ottiene il nome della persona che ha salvato il documento per l'ultima volta.


**Returns:**
java.lang.String - il nome

### setLastSaveBy(String value) {#setLastSaveBy-java.lang.String-}
```
public final void setLastSaveBy(String value)
```


Imposta il nome della persona che ha salvato il documento per l'ultima volta.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.lang.String | Il nome di una persona |
|

### getCompany() {#getCompany--}
```
public final String getCompany()
```


Ottiene il nome di un'azienda di cui è il documento.


**Returns:**
java.lang.String - il nome di un'azienda

### setCompany(String value) {#setCompany-java.lang.String-}
```
public final void setCompany(String value)
```


Imposta il nome di un'azienda di cui è il documento.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.lang.String | Il nome di un'azienda |
|

