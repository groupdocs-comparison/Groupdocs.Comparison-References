---
title: "SaveOptions"
second_title: "Referencia de API de GroupDocs.Comparison for Java"
description: "Permite especificar opciones adicionales al guardar un documento."
type: docs
weight: 10
url: /es/java/com.groupdocs.comparison.options.save/saveoptions/
---
**Inheritance:**
java.lang.Object
```
public class SaveOptions
```

Permite especificar opciones adicionales al guardar un documento.


Ejemplo de uso:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    final SaveOptions saveOptions = new SaveOptions();
    saveOptions.setPassword("passw");

    comparer.compare(resultFile, saveOptions);
 }
 
````


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [SaveOptions()](#SaveOptions--) | Inicializa una nueva instancia de la clase SaveOptions. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getCloneMetadataType()](#getCloneMetadataType--) | Obtiene una estrategia de procesamiento del documento de resultados al guardar metadatos. |
|
|  | [setCloneMetadataType(MetadataType value)](#setCloneMetadataType-com.groupdocs.comparison.options.enums.MetadataType-) | Establece una estrategia de procesamiento del documento de resultados al guardar metadatos. |
|
|  | [getFileAuthorMetadata()](#getFileAuthorMetadata--) | Obtiene un objeto de metadatos que se establecerá en el documento de resultados cuando [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) esté configurado a [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR). |
|
|  | [setFileAuthorMetadata(FileAuthorMetadata value)](#setFileAuthorMetadata-com.groupdocs.comparison.options.FileAuthorMetadata-) | Establece un objeto de metadatos que debe establecerse en el documento de resultados cuando [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) esté configurado a [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR). |
|
|  | [getPassword()](#getPassword--) | Obtiene una contraseña para el documento de resultados. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Establece una contraseña para el documento de resultados. |
|
|  | [getFolderPath()](#getFolderPath--) | Obtiene la ruta de carpeta donde se guardarán las imágenes de resultados. |
|
|  | [setFolderPath(String value)](#setFolderPath-java.lang.String-) | Establece la ruta de carpeta donde se deben guardar las imágenes de resultados. |
|
|  | [setFolderPath(Path value)](#setFolderPath-java.nio.file.Path-) | Establece la ruta de carpeta donde se deben guardar las imágenes de resultados. |
|
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```


Inicializa una nueva instancia de la clase SaveOptions.


### getCloneMetadataType() {#getCloneMetadataType--}
```
public final MetadataType getCloneMetadataType()
```


Obtiene una estrategia de procesamiento del documento de resultados al guardar metadatos.
Los valores posibles están en el enum [MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype)


**Returns:**
[MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) - the stragegy of processing metadata

### setCloneMetadataType(MetadataType value) {#setCloneMetadataType-com.groupdocs.comparison.options.enums.MetadataType-}
```
public final void setCloneMetadataType(MetadataType value)
```


Establece una estrategia de procesamiento del documento de resultados al guardar metadatos.
Los valores posibles están en el enum [MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) | La estrategia de procesamiento de metadatos |
|

### getFileAuthorMetadata() {#getFileAuthorMetadata--}
```
public final FileAuthorMetadata getFileAuthorMetadata()
```


Obtiene un objeto de metadatos que se establecerá en el documento de resultados cuando [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) esté configurado a [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR).


**Returns:**
[FileAuthorMetadata](../../com.groupdocs.comparison.options/fileauthormetadata) - the metadata object

### setFileAuthorMetadata(FileAuthorMetadata value) {#setFileAuthorMetadata-com.groupdocs.comparison.options.FileAuthorMetadata-}
```
public final void setFileAuthorMetadata(FileAuthorMetadata value)
```


Establece un objeto de metadatos que debe establecerse en el documento de resultados cuando [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) esté configurado a [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [FileAuthorMetadata](../../com.groupdocs.comparison.options/fileauthormetadata) | El objeto de metadatos |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Obtiene una contraseña para el documento de resultados.


**Returns:**
java.lang.String - la contraseña

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Establece una contraseña para el documento de resultados.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.String | La contraseña |
|

### getFolderPath() {#getFolderPath--}
```
public final String getFolderPath()
```


Obtiene la ruta de carpeta donde se guardarán las imágenes de resultados.
Usado solo para Comparación de Imágenes.


**Returns:**
java.lang.String - la ruta de carpeta para guardar imágenes de resultados

### setFolderPath(String value) {#setFolderPath-java.lang.String-}
```
public final void setFolderPath(String value)
```


Establece la ruta de carpeta donde se deben guardar las imágenes de resultados.
Usado solo para Comparación de Imágenes.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.String | La ruta de carpeta para guardar imágenes de resultados |
|

### setFolderPath(Path value) {#setFolderPath-java.nio.file.Path-}
```
public final void setFolderPath(Path value)
```


Establece la ruta de carpeta donde se deben guardar las imágenes de resultados.
Usado solo para Comparación de Imágenes.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.nio.file.Path | La ruta de carpeta para guardar imágenes de resultados |
|

