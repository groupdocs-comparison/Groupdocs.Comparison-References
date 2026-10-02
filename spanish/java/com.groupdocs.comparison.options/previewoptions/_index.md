---
title: "PreviewOptions"
second_title: "Referencia de API de GroupDocs.Comparison for Java"
description: "Proporciona opciones para generar vistas previas de documentos en el proceso de comparación."
type: docs
weight: 15
url: /es/java/com.groupdocs.comparison.options/previewoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewOptions
```

Proporciona opciones para generar vistas previas de documentos en el proceso de comparación.


Ejemplo de uso:

````

 try (Comparer comparer = new Comparer(sourceFile)) {

    PreviewOptions previewOptions = new PreviewOptions(
            pageNumber -> Files.newOutputStream(Paths.get(String.format("preview-page_%d.png", pageNumber)))
    );
    previewOptions.setPreviewFormat(PreviewFormats.PNG);
    previewOptions.setPageNumbers(new int[]{1, 2});

    comparer.getSource().generatePreview(previewOptions);
 }
 
````


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [PreviewOptions(Delegates.CreatePageStream createPageStream)](#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-) | Inicializa una nueva instancia de la clase PreviewOptions especificando la función Delegates.CreatePageStream. |
|
|  | [PreviewOptions(CreatePageStreamFunction createPageStream)](#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-) | Inicializa una nueva instancia de la clase PreviewOptions especificando la función [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction). |
|
|  | [PreviewOptions(Delegates.CreatePageStream createPageStream, Delegates.ReleasePageStream releasePageStream)](#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-) | Inicializa una nueva instancia de la clase PreviewOptions especificando las funciones Delegates.CreatePageStream y Delegates.ReleasePageStream. |
|
|  | [PreviewOptions(CreatePageStreamFunction createPageStream, ReleasePageStreamFunction releasePageStream)](#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-) | Inicializa una nueva instancia de la clase PreviewOptions especificando las funciones [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) y [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction). |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getCreatePageStream()](#getCreatePageStream--) | Obtiene una función para crear el flujo de vista previa de la página de salida. |
|
|  | [setCreatePageStream(Delegates.CreatePageStream createPageStream)](#setCreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-) | Establece una función para crear el flujo de vista previa de la página de salida. |
|
|  | [setCreatePageStream(CreatePageStreamFunction createPageStream)](#setCreatePageStream-com.groupdocs.comparison.common.function.CreatePageStreamFunction-) | Establece una función para crear el flujo de vista previa de la página de salida. |
|
|  | [getReleasePageStream()](#getReleasePageStream--) | Obtiene una función para liberar el flujo de vista previa de la página de salida. |
|
|  | [setReleasePageStream(Delegates.ReleasePageStream releasePageStream)](#setReleasePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-) | Obtiene una función para liberar el flujo de vista previa de la página de salida. |
|
|  | [setReleasePageStream(ReleasePageStreamFunction releasePageStream)](#setReleasePageStream-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-) | Establece una función para liberar el flujo de vista previa de la página de salida. |
|
|  | [getWidth()](#getWidth--) | Obtiene el ancho de las imágenes de vista previa. |
|
|  | [setWidth(int value)](#setWidth-int-) | Establece el ancho de las imágenes de vista previa. |
|
|  | [getHeight()](#getHeight--) | Obtiene la altura de las imágenes de vista previa. |
|
|  | [setHeight(int value)](#setHeight-int-) | Establece la altura de las imágenes de vista previa. |
|
|  | [getPageNumbers()](#getPageNumbers--) | Obtiene una matriz de números de página para los cuales se generarán imágenes de vista previa. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | Establece una matriz de números de página para los cuales se generarán imágenes de vista previa. |
|
|  | [getPreviewFormat()](#getPreviewFormat--) | Obtiene un formato de imágenes de vista previa. |
|
|  | [setPreviewFormat(PreviewFormats value)](#setPreviewFormat-com.groupdocs.comparison.options.enums.PreviewFormats-) | Establece un formato de imágenes de vista previa. |
|
### PreviewOptions(Delegates.CreatePageStream createPageStream) {#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-}
```
public PreviewOptions(Delegates.CreatePageStream createPageStream)
```


Inicializa una nueva instancia de la clase PreviewOptions especificando la función Delegates.CreatePageStream.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.comparison.common.delegates/createpagestream) | La función para crear el flujo de vista previa de página de salida. |
|

### PreviewOptions(CreatePageStreamFunction createPageStream) {#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-}
```
public PreviewOptions(CreatePageStreamFunction createPageStream)
```


Inicializa una nueva instancia de la clase PreviewOptions especificando la función [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | createPageStream | [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) | La función para crear el flujo de vista previa de página de salida. |
|

### PreviewOptions(Delegates.CreatePageStream createPageStream, Delegates.ReleasePageStream releasePageStream) {#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-}
```
public PreviewOptions(Delegates.CreatePageStream createPageStream, Delegates.ReleasePageStream releasePageStream)
```


Inicializa una nueva instancia de la clase PreviewOptions especificando las funciones Delegates.CreatePageStream y Delegates.ReleasePageStream.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.comparison.common.delegates/createpagestream) | La función para crear el flujo de vista previa de página de salida. |
|
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.comparison.common.delegates/releasepagestream) | La función para liberar el flujo de vista previa de página de salida. |
|

### PreviewOptions(CreatePageStreamFunction createPageStream, ReleasePageStreamFunction releasePageStream) {#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-}
```
public PreviewOptions(CreatePageStreamFunction createPageStream, ReleasePageStreamFunction releasePageStream)
```


Inicializa una nueva instancia de la clase PreviewOptions especificando las funciones [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) y [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | createPageStream | [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) | La función para crear el flujo de vista previa de página de salida. |
|
|  | releasePageStream | [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) | La función para liberar el flujo de vista previa de página de salida. |
|

### getCreatePageStream() {#getCreatePageStream--}
```
public CreatePageStreamFunction getCreatePageStream()
```


Obtiene una función para crear el flujo de vista previa de la página de salida.


**Returns:**
[CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) - the function to create output page preview stream.

### setCreatePageStream(Delegates.CreatePageStream createPageStream) {#setCreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-}
```
public void setCreatePageStream(Delegates.CreatePageStream createPageStream)
```


Establece una función para crear el flujo de vista previa de la página de salida.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.comparison.common.delegates/createpagestream) | La función para crear el flujo de vista previa de página de salida. |
|

### setCreatePageStream(CreatePageStreamFunction createPageStream) {#setCreatePageStream-com.groupdocs.comparison.common.function.CreatePageStreamFunction-}
```
public void setCreatePageStream(CreatePageStreamFunction createPageStream)
```


Establece una función para crear el flujo de vista previa de la página de salida.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | createPageStream | [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) | La función para crear el flujo de vista previa de página de salida. |
|

### getReleasePageStream() {#getReleasePageStream--}
```
public ReleasePageStreamFunction getReleasePageStream()
```


Obtiene una función para liberar el flujo de vista previa de la página de salida.


**Returns:**
[ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) - the function to release output page preview stream.

### setReleasePageStream(Delegates.ReleasePageStream releasePageStream) {#setReleasePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-}
```
public void setReleasePageStream(Delegates.ReleasePageStream releasePageStream)
```


Obtiene una función para liberar el flujo de vista previa de la página de salida.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.comparison.common.delegates/releasepagestream) | La función para liberar el flujo de vista previa de página de salida. |
|

### setReleasePageStream(ReleasePageStreamFunction releasePageStream) {#setReleasePageStream-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-}
```
public void setReleasePageStream(ReleasePageStreamFunction releasePageStream)
```


Establece una función para liberar el flujo de vista previa de la página de salida.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | releasePageStream | [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) | La función para liberar el flujo de vista previa de página de salida. |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Obtiene el ancho de las imágenes de vista previa.


**Returns:**
int - el ancho de las imágenes de vista previa.

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Establece el ancho de las imágenes de vista previa.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int | El ancho de las imágenes de vista previa. |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Obtiene la altura de las imágenes de vista previa.


**Returns:**
int - la altura de las imágenes de vista previa.

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Establece la altura de las imágenes de vista previa.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int | La altura de las imágenes de vista previa. |
|

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Obtiene una matriz de números de página para los cuales se generarán imágenes de vista previa.


**Returns:**
int[] - matriz de números de página

### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Establece una matriz de números de página para los cuales se generarán imágenes de vista previa.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int[] | Matriz de números de página |
|

### getPreviewFormat() {#getPreviewFormat--}
```
public final PreviewFormats getPreviewFormat()
```


Obtiene un formato de imágenes de vista previa.


**Returns:**
[PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats) - preview images format

### setPreviewFormat(PreviewFormats value) {#setPreviewFormat-com.groupdocs.comparison.options.enums.PreviewFormats-}
```
public final void setPreviewFormat(PreviewFormats value)
```


Establece un formato de imágenes de vista previa.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats) | Formato de imágenes de vista previa |
|

