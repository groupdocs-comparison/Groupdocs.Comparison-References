---
title: "LoadOptions"
second_title: "Referencia de API de GroupDocs.Comparison for Java"
description: "Permite especificar opciones adicionales al cargar un documento."
type: docs
weight: 10
url: /es/java/com.groupdocs.comparison.options.load/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

Permite especificar opciones adicionales al cargar un documento.


Ejemplo de uso:

````

 final LoadOptions loadOptions = new LoadOptions();
 loadOptions.setPassword("passw");
 loadOptions.setFileType(FileType.PDF);

 try (Comparer comparer = new Comparer(sourceFile, loadOptions)) {
    comparer.add(targetFile);

    comparer.compare(resultFile);
 }
 
````


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [LoadOptions()](#LoadOptions--) | Inicializa una nueva instancia de la clase LoadOptions. |
|
|  | [LoadOptions(boolean isLoadText)](#LoadOptions-boolean-) | Inicializa una nueva instancia de la clase LoadOptions con una bandera que indica que la cadena de entrada es un texto a comparar, no una ruta. |
|
|  | [LoadOptions(String password)](#LoadOptions-java.lang.String-) | Inicializa una nueva instancia de la clase LoadOptions con una contraseña para cargar el documento. |
|
|  | [LoadOptions(boolean isLoadText, String password)](#LoadOptions-boolean-java.lang.String-) | Inicializa una nueva instancia de la clase LoadOptions con una bandera que indica que la cadena de entrada es un texto a comparar y una contraseña para cargar el documento. |
|
|  | [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.comparison.result.FileType-) | Inicializa una nueva instancia de la clase LoadOptions con un tipo de archivo. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [isLoadText()](#isLoadText--) | Obtiene una bandera que indica que la cadena pasada al constructor [Comparer](../../com.groupdocs.comparison/comparer) o al método [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) es texto de comparación, no rutas de archivo (Solo para Comparación de Texto). |
|
|  | [setLoadText(boolean value)](#setLoadText-boolean-) | Establece una bandera que indica que la cadena pasada al constructor [Comparer](../../com.groupdocs.comparison/comparer) o al método [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) es texto de comparación, no rutas de archivo (Solo para Comparación de Texto). |
|
|  | [getPassword()](#getPassword--) | Obtiene una contraseña que se usará para cargar un documento. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Establece una contraseña que debe usarse para cargar un documento. |
|
|  | [getFontDirectories()](#getFontDirectories--) | Obtiene una lista de directorios donde se encuentran los archivos de fuentes para cargar un documento. |
|
|  | [setFontDirectories(List<String> value)](#setFontDirectories-java.util.List-java.lang.String--) | Establece una lista de directorios donde se encuentran los archivos de fuentes para cargar un documento. |
|
|  | [getFileType()](#getFileType--) | Obtiene el tipo de archivo que se está cargando. |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.comparison.result.FileType-) | Establece un tipo de archivo que se está cargando. |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


Inicializa una nueva instancia de la clase LoadOptions.


### LoadOptions(boolean isLoadText) {#LoadOptions-boolean-}
```
public LoadOptions(boolean isLoadText)
```


Inicializa una nueva instancia de la clase LoadOptions con una bandera que indica que la cadena de entrada es un texto a comparar, no una ruta.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | isLoadText | boolean | La bandera que indica que la cadena de entrada es un texto para comparar, no una ruta |
|

### LoadOptions(String password) {#LoadOptions-java.lang.String-}
```
public LoadOptions(String password)
```


Inicializa una nueva instancia de la clase LoadOptions con una contraseña para cargar el documento.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | contraseña | java.lang.String | La contraseña para cargar el documento |
|

### LoadOptions(boolean isLoadText, String password) {#LoadOptions-boolean-java.lang.String-}
```
public LoadOptions(boolean isLoadText, String password)
```


Inicializa una nueva instancia de la clase LoadOptions con una bandera que indica que la cadena de entrada es un texto a comparar y una contraseña para cargar el documento.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | isLoadText | boolean | La bandera que indica que la cadena de entrada es un texto para comparar, no una ruta |
|
|  | contraseña | java.lang.String | La contraseña para cargar el documento |
|

### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.comparison.result.FileType-}
```
public LoadOptions(FileType fileType)
```


Inicializa una nueva instancia de la clase LoadOptions con un tipo de archivo.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.comparison.result/filetype) | El tipo del archivo |
|

### isLoadText() {#isLoadText--}
```
public boolean isLoadText()
```


Obtiene una bandera que indica que la cadena pasada al constructor [Comparer](../../com.groupdocs.comparison/comparer) o al método [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) es texto de comparación, no rutas de archivo (Solo para Comparación de Texto).


**Returns:**
boolean - verdadero si la cadena de entrada es un texto para comparar, de lo contrario falso

### setLoadText(boolean value) {#setLoadText-boolean-}
```
public void setLoadText(boolean value)
```


Establece una bandera que indica que la cadena pasada al constructor [Comparer](../../com.groupdocs.comparison/comparer) o al método [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) es texto de comparación, no rutas de archivo (Solo para Comparación de Texto).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | verdadero si la cadena de entrada es un texto para comparar, de lo contrario falso |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Obtiene una contraseña que se usará para cargar un documento.


**Returns:**
java.lang.String - la contraseña para cargar el documento

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Establece una contraseña que debe usarse para cargar un documento.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.String | La contraseña para cargar el documento |
|

### getFontDirectories() {#getFontDirectories--}
```
public List<String> getFontDirectories()
```


Obtiene una lista de directorios donde se encuentran los archivos de fuentes para cargar un documento.


**Returns:**
java.util.List<java.lang.String> - la lista de directorios con archivos de fuentes

### setFontDirectories(List<String> value) {#setFontDirectories-java.util.List-java.lang.String--}
```
public void setFontDirectories(List<String> value)
```


Establece una lista de directorios donde se encuentran los archivos de fuentes para cargar un documento.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.util.List<java.lang.String> | La lista de directorios con archivos de fuentes |
|

### getFileType() {#getFileType--}
```
public FileType getFileType()
```


Obtiene el tipo de archivo que se está cargando.


**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the type of the file

### setFileType(FileType value) {#setFileType-com.groupdocs.comparison.result.FileType-}
```
public void setFileType(FileType value)
```


Establece un tipo de archivo que se está cargando.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [FileType](../../com.groupdocs.comparison.result/filetype) | El tipo del archivo |
|

