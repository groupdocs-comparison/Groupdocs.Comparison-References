---
title: "IDocumentInfo"
second_title: "Referencia de API de GroupDocs.Comparison for Java"
description: "Proporciona acceso a las propiedades del documento."
type: docs
weight: 10
url: /es/java/com.groupdocs.comparison.interfaces/idocumentinfo/
---
**All Implemented Interfaces:**
java.io.Closeable
```
public interface IDocumentInfo extends Closeable
```

Proporciona acceso a las propiedades del documento.


Más detalles sobre su uso se pueden encontrar en el método [Document.getDocumentInfo()](../../com.groupdocs.comparison/document#getDocumentInfo--) o en una [documentación](../https://docs.groupdocs.com/comparison/java/get-file-info/).


Ejemplo de uso:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    try (IDocumentInfo documentInfo = comparer.getSource().getDocumentInfo()) {
      for (int i = 0; i < documentInfo.getPageCount(); i++) {
          System.out.printf("File type: %s%nNumber of pages: %d", documentInfo.getFileType().getFileFormat(), documentInfo.getPageCount());
      }
    }
 }
 
````


## Métodos

| Método | Descripción |
| --- | --- |
|  | [getFileType()](#getFileType--) | Obtiene el tipo del archivo representado por el enum [FileType](../../com.groupdocs.comparison.result/filetype). |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.comparison.result.FileType-) | Establece el tipo del archivo usando el enum [FileType](../../com.groupdocs.comparison.result/filetype). |
|
|  | [getPageCount()](#getPageCount--) | Obtiene el recuento del archivo. |
|
|  | [setPageCount(int value)](#setPageCount-int-) | Establece el recuento del archivo. |
|
|  | [getSize()](#getSize--) | Obtiene el tamaño del archivo. |
|
|  | [setSize(long value)](#setSize-long-) | Establece el tamaño del archivo. |
|
|  | [getPagesInfo()](#getPagesInfo--) | Obtiene información de cada página del archivo usando la clase [PageInfo](../../com.groupdocs.comparison.result/pageinfo). |
|
|  | [setPagesInfo(List<PageInfo> pageInfos)](#setPagesInfo-java.util.List-com.groupdocs.comparison.result.PageInfo--) | Establece información de cada página del archivo usando la clase [PageInfo](../../com.groupdocs.comparison.result/pageinfo). |
|
|  | [close()](#close--) | Destruye el objeto, lo que hace imposible obtener información del documento usando esta instancia del objeto [IDocumentInfo](../../com.groupdocs.comparison.interfaces/idocumentinfo). |
|
### getFileType() {#getFileType--}
```
public abstract FileType getFileType()
```


Obtiene el tipo del archivo representado por el enum [FileType](../../com.groupdocs.comparison.result/filetype).


**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the type of the file

### setFileType(FileType value) {#setFileType-com.groupdocs.comparison.result.FileType-}
```
public abstract void setFileType(FileType value)
```


Establece el tipo del archivo usando el enum [FileType](../../com.groupdocs.comparison.result/filetype).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [FileType](../../com.groupdocs.comparison.result/filetype) | El tipo del archivo |
|

### getPageCount() {#getPageCount--}
```
public abstract int getPageCount()
```


Obtiene el recuento del archivo.


**Returns:**
int - el recuento del archivo

### setPageCount(int value) {#setPageCount-int-}
```
public abstract void setPageCount(int value)
```


Establece el recuento del archivo.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int | El recuento del archivo |
|

### getSize() {#getSize--}
```
public abstract long getSize()
```


Obtiene el tamaño del archivo.


**Returns:**
long - el tamaño del archivo

### setSize(long value) {#setSize-long-}
```
public abstract void setSize(long value)
```


Establece el tamaño del archivo.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | long | El tamaño del archivo |
|

### getPagesInfo() {#getPagesInfo--}
```
public abstract List<PageInfo> getPagesInfo()
```


Obtiene información de cada página del archivo usando la clase [PageInfo](../../com.groupdocs.comparison.result/pageinfo).


**Returns:**
java.util.List<com.groupdocs.comparison.result.PageInfo> - información para cada página del archivo

### setPagesInfo(List<PageInfo> pageInfos) {#setPagesInfo-java.util.List-com.groupdocs.comparison.result.PageInfo--}
```
public abstract void setPagesInfo(List<PageInfo> pageInfos)
```


Establece información de cada página del archivo usando la clase [PageInfo](../../com.groupdocs.comparison.result/pageinfo).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | pageInfos | java.util.List<com.groupdocs.comparison.result.PageInfo> | Información para cada página del archivo |
|

### close() {#close--}
```
public abstract void close()
```


Destruye el objeto, lo que hace imposible obtener información del documento usando esta instancia del objeto [IDocumentInfo](../../com.groupdocs.comparison.interfaces/idocumentinfo).
También elimina archivos temporales y libera los recursos utilizados.


