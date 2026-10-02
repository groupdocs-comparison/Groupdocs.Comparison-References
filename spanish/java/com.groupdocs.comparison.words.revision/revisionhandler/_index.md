---
title: "RevisionHandler"
second_title: "Referencia de API de GroupDocs.Comparison for Java"
description: "Representa una clase que controla el manejo de revisiones."
type: docs
weight: 11
url: /es/java/com.groupdocs.comparison.words.revision/revisionhandler/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class RevisionHandler implements Closeable
```

Representa una clase que controla el manejo de revisiones.


La clase RevisionHandler le permite trabajar con revisiones en documentos.
Proporciona métodos para obtener la lista de revisiones, aplicar cambios a las revisiones y guardar el documento modificado.


Ejemplo de uso:

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


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [RevisionHandler(String filePath)](#RevisionHandler-java.lang.String-) | Inicializa una nueva instancia de la clase RevisionHandler con la ruta al archivo que contiene revisiones. |
|
|  | [RevisionHandler(Path filePath)](#RevisionHandler-java.nio.file.Path-) | Inicializa una nueva instancia de la clase RevisionHandler con la ruta al archivo que contiene revisiones. |
|
|  | [RevisionHandler(InputStream file, FileType fileType)](#RevisionHandler-java.io.InputStream-com.groupdocs.comparison.result.FileType-) | Inicializa una nueva instancia de la clase RevisionHandler con un flujo de archivo que contiene revisiones. |
|
|  | [RevisionHandler(Document document)](#RevisionHandler-com.aspose.words.Document-) | Inicializa una nueva instancia de la clase RevisionHandler con un documento. |
|
## Campos

| Campo | Descripción |
| --- | --- |
| [SOURCE_PATH_IS_NULL](#SOURCE-PATH-IS-NULL) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getRevisions()](#getRevisions--) | Obtiene la lista de todas las revisiones. |
|
|  | [applyRevisionChanges(ApplyRevisionOptions changes)](#applyRevisionChanges-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | Procesa los cambios en las revisiones y los aplica al archivo original. |
|
|  | [applyRevisionChanges(Path filePath, ApplyRevisionOptions changes)](#applyRevisionChanges-java.nio.file.Path-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | Procesa los cambios en las revisiones y escribe el resultado en el archivo especificado. |
|
|  | [applyRevisionChanges(String filePath, ApplyRevisionOptions changes)](#applyRevisionChanges-java.lang.String-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | Procesa los cambios en las revisiones y escribe el resultado en el archivo especificado. |
|
|  | [applyRevisionChanges(OutputStream outputStream, ApplyRevisionOptions changes)](#applyRevisionChanges-java.io.OutputStream-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | Procesa los cambios en las revisiones y escribe el resultado en el flujo del documento. |
|
| [close()](#close--) |  |
### RevisionHandler(String filePath) {#RevisionHandler-java.lang.String-}
```
public RevisionHandler(String filePath)
```


Inicializa una nueva instancia de la clase RevisionHandler con la ruta al archivo que contiene revisiones.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.lang.String | La ruta al archivo. |
|

### RevisionHandler(Path filePath) {#RevisionHandler-java.nio.file.Path-}
```
public RevisionHandler(Path filePath)
```


Inicializa una nueva instancia de la clase RevisionHandler con la ruta al archivo que contiene revisiones.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | La ruta al archivo. |
|

### RevisionHandler(InputStream file, FileType fileType) {#RevisionHandler-java.io.InputStream-com.groupdocs.comparison.result.FileType-}
```
public RevisionHandler(InputStream file, FileType fileType)
```


Inicializa una nueva instancia de la clase RevisionHandler con un flujo de archivo que contiene revisiones.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | archivo | java.io.InputStream | El flujo del documento de origen. |
|
|  | fileType | [FileType](../../com.groupdocs.comparison.result/filetype) | El tipo del archivo. |
|

### RevisionHandler(Document document) {#RevisionHandler-com.aspose.words.Document-}
```
public RevisionHandler(Document document)
```


Inicializa una nueva instancia de la clase RevisionHandler con un documento.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | documento | com.aspose.words.Document | El documento. |
|

### SOURCE_PATH_IS_NULL {#SOURCE-PATH-IS-NULL}
```
public static final String SOURCE_PATH_IS_NULL
```


### getRevisions() {#getRevisions--}
```
public List<RevisionInfo> getRevisions()
```


Obtiene la lista de todas las revisiones.


Debido a que las revisiones se ordenaron originalmente en un grupo, las revisiones deben tomarse de una Lista.
En la Lista, una sola revisión puede dividirse en múltiples revisiones con el mismo texto general.
Dado que la Lista puede contener revisiones con el mismo texto general, esto debe controlarse al crear una lista de revisiones para el usuario.
Esto se controla aquí usando List\<RevisionGroup\> grupos.


**Returns:**
java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> - la lista de revisiones.

### applyRevisionChanges(ApplyRevisionOptions changes) {#applyRevisionChanges-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(ApplyRevisionOptions changes)
```


Procesa los cambios en las revisiones y los aplica al archivo original.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | La lista de revisiones modificadas. |
|

### applyRevisionChanges(Path filePath, ApplyRevisionOptions changes) {#applyRevisionChanges-java.nio.file.Path-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(Path filePath, ApplyRevisionOptions changes)
```


Procesa los cambios en las revisiones y escribe el resultado en el archivo especificado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | La ruta del archivo resultante. |
|
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | La lista de revisiones modificadas. |
|

### applyRevisionChanges(String filePath, ApplyRevisionOptions changes) {#applyRevisionChanges-java.lang.String-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(String filePath, ApplyRevisionOptions changes)
```


Procesa los cambios en las revisiones y escribe el resultado en el archivo especificado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.lang.String | La ruta del archivo resultante. |
|
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | La lista de revisiones modificadas. |
|

### applyRevisionChanges(OutputStream outputStream, ApplyRevisionOptions changes) {#applyRevisionChanges-java.io.OutputStream-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(OutputStream outputStream, ApplyRevisionOptions changes)
```


Procesa los cambios en las revisiones y escribe el resultado en el flujo del documento.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | outputStream | java.io.OutputStream | El flujo del documento resultante. |
|
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | La lista de revisiones modificadas. |
|

### close() {#close--}
```
public void close()
```




