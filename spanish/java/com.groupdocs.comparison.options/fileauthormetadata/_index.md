---
title: "FileAuthorMetadata"
second_title: "Referencia de API de GroupDocs.Comparison for Java"
description: "Permite configurar la información sobre los metadatos del autor del documento."
type: docs
weight: 12
url: /es/java/com.groupdocs.comparison.options/fileauthormetadata/
---
**Inheritance:**
java.lang.Object
```
public class FileAuthorMetadata
```

Permite configurar la información sobre los metadatos del autor del documento.


Ejemplo de uso:

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


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [FileAuthorMetadata()](#FileAuthorMetadata--) | Inicializa una nueva instancia de la clase FileAuthorMetadata. |
|
## Campos

| Campo | Descripción |
| --- | --- |
| [GROUP_DOCS](#GROUP-DOCS) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getAuthor()](#getAuthor--) | Obtiene el autor de un documento. |
|
|  | [setAuthor(String value)](#setAuthor-java.lang.String-) | Establece el autor de un documento. |
|
|  | [getLastSaveBy()](#getLastSaveBy--) | Obtiene el nombre de la persona que guardó el documento por última vez. |
|
|  | [setLastSaveBy(String value)](#setLastSaveBy-java.lang.String-) | Establece el nombre de la persona que guardó el documento por última vez. |
|
|  | [getCompany()](#getCompany--) | Obtiene el nombre de una empresa cuyo documento es. |
|
|  | [setCompany(String value)](#setCompany-java.lang.String-) | Establece el nombre de una empresa cuyo documento es. |
|
### FileAuthorMetadata() {#FileAuthorMetadata--}
```
public FileAuthorMetadata()
```


Inicializa una nueva instancia de la clase FileAuthorMetadata.


### GROUP_DOCS {#GROUP-DOCS}
```
public static final String GROUP_DOCS
```


### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```


Obtiene el autor de un documento.


**Returns:**
java.lang.String - el autor

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```


Establece el autor de un documento.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.String | El autor |
|

### getLastSaveBy() {#getLastSaveBy--}
```
public final String getLastSaveBy()
```


Obtiene el nombre de la persona que guardó el documento por última vez.


**Returns:**
java.lang.String - el nombre

### setLastSaveBy(String value) {#setLastSaveBy-java.lang.String-}
```
public final void setLastSaveBy(String value)
```


Establece el nombre de la persona que guardó el documento por última vez.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.String | El nombre de una persona |
|

### getCompany() {#getCompany--}
```
public final String getCompany()
```


Obtiene el nombre de una empresa cuyo documento es.


**Returns:**
java.lang.String - el nombre de una empresa

### setCompany(String value) {#setCompany-java.lang.String-}
```
public final void setCompany(String value)
```


Establece el nombre de una empresa cuyo documento es.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.String | El nombre de una empresa |
|

