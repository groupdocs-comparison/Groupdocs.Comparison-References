---
title: "IDocumentInfo"
second_title: "Riferimento API di GroupDocs.Comparison per Java"
description: "Fornisce l'accesso alle proprietà del documento."
type: docs
weight: 10
url: /it/java/com.groupdocs.comparison.interfaces/idocumentinfo/
---
**All Implemented Interfaces:**
java.io.Closeable
```
public interface IDocumentInfo extends Closeable
```

Fornisce l'accesso alle proprietà del documento.


Maggiori dettagli sul suo utilizzo possono essere trovati nel metodo [Document.getDocumentInfo()](../../com.groupdocs.comparison/document#getDocumentInfo--) o in una [documentazione](../https://docs.groupdocs.com/comparison/java/get-file-info/).


Esempio di utilizzo:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    try (IDocumentInfo documentInfo = comparer.getSource().getDocumentInfo()) {
      for (int i = 0; i < documentInfo.getPageCount(); i++) {
          System.out.printf("File type: %s%nNumber of pages: %d", documentInfo.getFileType().getFileFormat(), documentInfo.getPageCount());
      }
    }
 }
 
````


## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getFileType()](#getFileType--) | Restituisce un tipo di file rappresentato dall'enum [FileType](../../com.groupdocs.comparison.result/filetype). |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.comparison.result.FileType-) | Imposta un tipo di file utilizzando l'enum [FileType](../../com.groupdocs.comparison.result/filetype). |
|
|  | [getPageCount()](#getPageCount--) | Restituisce un conteggio del file. |
|
|  | [setPageCount(int value)](#setPageCount-int-) | Imposta un conteggio del file. |
|
|  | [getSize()](#getSize--) | Restituisce una dimensione del file. |
|
|  | [setSize(long value)](#setSize-long-) | Imposta una dimensione del file. |
|
|  | [getPagesInfo()](#getPagesInfo--) | Restituisce informazioni per ogni pagina del file utilizzando la classe [PageInfo](../../com.groupdocs.comparison.result/pageinfo). |
|
|  | [setPagesInfo(List<PageInfo> pageInfos)](#setPagesInfo-java.util.List-com.groupdocs.comparison.result.PageInfo--) | Imposta informazioni per ogni pagina del file utilizzando la classe [PageInfo](../../com.groupdocs.comparison.result/pageinfo). |
|
|  | [close()](#close--) | Distrugge l'oggetto rendendo impossibile ottenere informazioni sul documento utilizzando questa istanza dell'oggetto [IDocumentInfo](../../com.groupdocs.comparison.interfaces/idocumentinfo). |
|
### getFileType() {#getFileType--}
```
public abstract FileType getFileType()
```


Restituisce un tipo di file rappresentato dall'enum [FileType](../../com.groupdocs.comparison.result/filetype).


**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the type of the file

### setFileType(FileType value) {#setFileType-com.groupdocs.comparison.result.FileType-}
```
public abstract void setFileType(FileType value)
```


Imposta un tipo di file utilizzando l'enum [FileType](../../com.groupdocs.comparison.result/filetype).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [FileType](../../com.groupdocs.comparison.result/filetype) | Il tipo del file |
|

### getPageCount() {#getPageCount--}
```
public abstract int getPageCount()
```


Restituisce un conteggio del file.


**Returns:**
int - il conteggio del file

### setPageCount(int value) {#setPageCount-int-}
```
public abstract void setPageCount(int value)
```


Imposta un conteggio del file.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | int | Il conteggio del file |
|

### getSize() {#getSize--}
```
public abstract long getSize()
```


Restituisce una dimensione del file.


**Returns:**
long - la dimensione del file

### setSize(long value) {#setSize-long-}
```
public abstract void setSize(long value)
```


Imposta una dimensione del file.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | long | La dimensione del file |
|

### getPagesInfo() {#getPagesInfo--}
```
public abstract List<PageInfo> getPagesInfo()
```


Restituisce informazioni per ogni pagina del file utilizzando la classe [PageInfo](../../com.groupdocs.comparison.result/pageinfo).


**Returns:**
java.util.List<com.groupdocs.comparison.result.PageInfo> - informazioni per ogni pagina del file

### setPagesInfo(List<PageInfo> pageInfos) {#setPagesInfo-java.util.List-com.groupdocs.comparison.result.PageInfo--}
```
public abstract void setPagesInfo(List<PageInfo> pageInfos)
```


Imposta informazioni per ogni pagina del file utilizzando la classe [PageInfo](../../com.groupdocs.comparison.result/pageinfo).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | pageInfos | java.util.List<com.groupdocs.comparison.result.PageInfo> | Informazioni per ogni pagina del file |
|

### close() {#close--}
```
public abstract void close()
```


Distrugge l'oggetto rendendo impossibile ottenere informazioni sul documento utilizzando questa istanza dell'oggetto [IDocumentInfo](../../com.groupdocs.comparison.interfaces/idocumentinfo).
Elimina anche i file temporanei e rilascia le risorse utilizzate.


