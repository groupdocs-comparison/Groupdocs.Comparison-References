---
title: "Documento"
second_title: "Referencia de API de GroupDocs.Comparison for Java"
description: "Representa un documento para el proceso de comparación."
type: docs
weight: 12
url: /es/java/com.groupdocs.comparison/document/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Document implements Closeable
```

Representa un documento para el proceso de comparación.


La clase Document proporciona métodos para cargar, generar imágenes de vista previa y manipular documentos durante el proceso de comparación.


Ejemplo de uso:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     try (IDocumentInfo info = comparer.getSource().getDocumentInfo()) {
         System.out.println("File type: " + info.getFileType());
         System.out.println("Number of pages: " + info.getPageCount());
         System.out.println("Document size: " + info.getSize());
     }
 }
 
````


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [Document(InputStream stream)](#Document-java.io.InputStream-) | Inicializa una nueva instancia de la clase Document con el flujo de documento especificado. |
|
|  | [Document(String filePath)](#Document-java.lang.String-) | Inicializa una nueva instancia de la clase Document con la ruta de documento especificada. |
|
|  | [Document(Path filePath)](#Document-java.nio.file.Path-) | Inicializa una nueva instancia de la clase Document con la ruta de documento especificada. |
|
|  | [Document(Path filePath, String password)](#Document-java.nio.file.Path-java.lang.String-) | Inicializa una nueva instancia de la clase Document con la ruta de documento especificada y una contraseña. |
|
|  | [Document(Path filePath, LoadOptions loadOptions)](#Document-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-) | Inicializa una nueva instancia de la clase Document con la ruta de documento especificada y opciones de carga. |
|
|  | [Document(String filePath, String password)](#Document-java.lang.String-java.lang.String-) | Inicializa una nueva instancia de la clase Document con la ruta de documento especificada y una contraseña. |
|
|  | [Document(String filePath, LoadOptions loadOptions)](#Document-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-) | Inicializa una nueva instancia de la clase Document con la ruta de documento especificada y opciones de carga. |
|
|  | [Document(InputStream stream, String password)](#Document-java.io.InputStream-java.lang.String-) | Inicializa una nueva instancia de la clase Document con el flujo de documento especificado y una contraseña. |
|
|  | [Document(String filePathOrTextContent, boolean isLoadText)](#Document-java.lang.String-boolean-) | Inicializa una nueva instancia de la clase Document con la ruta de documento o contenido de texto especificado y una bandera que indica qué se pasó. |
|
|  | [Document(InputStream inputStream, LoadOptions loadOptions)](#Document-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-) | Inicializa una nueva instancia de la clase Document con el flujo de documento especificado y opciones de carga. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getChanges()](#getChanges--) | Obtiene una lista de objetos [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) que representan los cambios detectados durante el proceso de comparación. |
|
|  | [setChanges(List<ChangeInfo> value)](#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--) | Establece una lista de objetos [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) que representan los cambios detectados durante el proceso de comparación. |
|
|  | [getName()](#getName--) | Obtiene el nombre del documento. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Establece el nombre del documento. |
|
|  | [getFileType()](#getFileType--) | Obtiene el tipo del documento. |
|
|  | [setFileType(FileType fileType)](#setFileType-com.groupdocs.comparison.result.FileType-) | Establece el tipo del documento. |
|
|  | [createStream()](#createStream--) | Crea un nuevo flujo con el contenido del documento. |
|
|  | [getStreamLength()](#getStreamLength--) | Obtiene el tamaño del documento |
|
|  | [getPassword()](#getPassword--) | Obtiene la contraseña del documento |
|
|  | [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.comparison.options.PreviewOptions-) | Genera vistas previas del documento basadas en los [PreviewOptions](../../com.groupdocs.comparison.options/previewoptions) proporcionados. |
|
|  | [getDocumentInfo()](#getDocumentInfo--) | Obtiene información sobre el documento, incluyendo el tipo de documento, el recuento de páginas, los tamaños de página y más. |
|
| [close()](#close--) |  |
### Document(InputStream stream) {#Document-java.io.InputStream-}
```
public Document(InputStream stream)
```


Inicializa una nueva instancia de la clase Document con el flujo de documento especificado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | flujo | java.io.InputStream | Flujo del documento |
|

### Document(String filePath) {#Document-java.lang.String-}
```
public Document(String filePath)
```


Inicializa una nueva instancia de la clase Document con la ruta de documento especificada.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.lang.String | Ruta del documento |
|

### Document(Path filePath) {#Document-java.nio.file.Path-}
```
public Document(Path filePath)
```


Inicializa una nueva instancia de la clase Document con la ruta de documento especificada.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Ruta del documento |
|

### Document(Path filePath, String password) {#Document-java.nio.file.Path-java.lang.String-}
```
public Document(Path filePath, String password)
```


Inicializa una nueva instancia de la clase Document con la ruta de documento especificada y una contraseña.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Ruta del documento |
|
|  | contraseña | java.lang.String | Contraseña del documento |
|

### Document(Path filePath, LoadOptions loadOptions) {#Document-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Document(Path filePath, LoadOptions loadOptions)
```


Inicializa una nueva instancia de la clase Document con la ruta de documento especificada y opciones de carga.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Ruta del documento |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Opciones de carga |
|

### Document(String filePath, String password) {#Document-java.lang.String-java.lang.String-}
```
public Document(String filePath, String password)
```


Inicializa una nueva instancia de la clase Document con la ruta de documento especificada y una contraseña.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.lang.String | Ruta del documento |
|
|  | contraseña | java.lang.String | Contraseña del documento |
|

### Document(String filePath, LoadOptions loadOptions) {#Document-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Document(String filePath, LoadOptions loadOptions)
```


Inicializa una nueva instancia de la clase Document con la ruta de documento especificada y opciones de carga.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.lang.String | Ruta del documento |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Opciones de carga |
|

### Document(InputStream stream, String password) {#Document-java.io.InputStream-java.lang.String-}
```
public Document(InputStream stream, String password)
```


Inicializa una nueva instancia de la clase Document con el flujo de documento especificado y una contraseña.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | flujo | java.io.InputStream | Flujo del documento |
|
|  | contraseña | java.lang.String | Contraseña del documento |
|

### Document(String filePathOrTextContent, boolean isLoadText) {#Document-java.lang.String-boolean-}
```
public Document(String filePathOrTextContent, boolean isLoadText)
```


Inicializa una nueva instancia de la clase Document con la ruta de documento o contenido de texto especificado y una bandera que indica qué se pasó.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePathOrTextContent | java.lang.String | la ruta del archivo |
|
|  | isLoadText | boolean | el texto cargado |
|

### Document(InputStream inputStream, LoadOptions loadOptions) {#Document-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Document(InputStream inputStream, LoadOptions loadOptions)
```


Inicializa una nueva instancia de la clase Document con el flujo de documento especificado y opciones de carga.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | inputStream | java.io.InputStream | Flujo del documento |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Opciones de carga |
|

### getChanges() {#getChanges--}
```
public final List<ChangeInfo> getChanges()
```


Obtiene una lista de objetos [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) que representan los cambios detectados durante el proceso de comparación.


Utilice este método para obtener información detallada sobre los cambios entre el documento de origen y el(los) documento(s) de destino.
Cada objeto [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) contiene información como el tipo de cambio, el área afectada,
y el contenido antes y después del cambio.


**Returns:**
java.util.List<com.groupdocs.comparison.result.ChangeInfo> - una lista de objetos [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) que representan los cambios detectados durante el proceso de comparación

### setChanges(List<ChangeInfo> value) {#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--}
```
public final void setChanges(List<ChangeInfo> value)
```


Establece una lista de objetos [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) que representan los cambios detectados durante el proceso de comparación.


Utilice este método para obtener información detallada sobre los cambios entre el documento de origen y el(los) documento(s) de destino.
Cada objeto [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) contiene información como el tipo de cambio, el área afectada,
y el contenido antes y después del cambio.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | java.util.List<com.groupdocs.comparison.result.ChangeInfo> | una lista de objetos [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) que representan los cambios detectados durante el proceso de comparación |
|

### getName() {#getName--}
```
public final String getName()
```


Obtiene el nombre del documento.


**Returns:**
java.lang.String - el nombre del documento

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Establece el nombre del documento.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.String | el nombre del documento |
|

### getFileType() {#getFileType--}
```
public FileType getFileType()
```


Obtiene el tipo del documento.


**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the type of the document

### setFileType(FileType fileType) {#setFileType-com.groupdocs.comparison.result.FileType-}
```
public void setFileType(FileType fileType)
```


Establece el tipo del documento.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.comparison.result/filetype) | el tipo del documento |
|

### createStream() {#createStream--}
```
public InputStream createStream()
```


Crea un nuevo flujo con el contenido del documento.


**Returns:**
java.io.InputStream - el flujo con el contenido del documento

### getStreamLength() {#getStreamLength--}
```
public long getStreamLength()
```


Obtiene el tamaño del documento


**Returns:**
long - el tamaño del documento

### getPassword() {#getPassword--}
```
public String getPassword()
```


Obtiene la contraseña del documento


**Returns:**
java.lang.String - la contraseña del documento

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.comparison.options.PreviewOptions-}
```
public final void generatePreview(PreviewOptions previewOptions)
```


Genera vistas previas del documento basadas en los [PreviewOptions](../../com.groupdocs.comparison.options/previewoptions) proporcionados.


Este método genera vistas previas de las páginas del documento según las opciones especificadas, como el formato de vista previa,
números de página y el proveedor del flujo de salida. Las vistas previas generadas pueden guardarse o procesarse adicionalmente según sea necesario.

* Learn more about how to generate previews for document pages: [How to generate document pages preview using GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Generate+document+pages+preview)


Ejemplo de uso:

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | previewOptions | [PreviewOptions](../../com.groupdocs.comparison.options/previewoptions) | Las opciones de vista previa que especifican el formato, los números de página, etc. |
|

### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Obtiene información sobre el documento, incluyendo el tipo de documento, el recuento de páginas, los tamaños de página y más.

* Learn more about document file type, page count, size, and other format-specific properties: [How to get document info using GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Get+file+info)


**Returns:**
[IDocumentInfo](../../com.groupdocs.comparison.interfaces/idocumentinfo) - the document information

### close() {#close--}
```
public void close()
```




