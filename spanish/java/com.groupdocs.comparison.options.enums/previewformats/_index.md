---
title: "PreviewFormats"
second_title: "Referencia de API de GroupDocs.Comparison for Java"
description: "Enumera los formatos de vista previa compatibles para la comparación de documentos."
type: docs
weight: 15
url: /es/java/com.groupdocs.comparison.options.enums/previewformats/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PreviewFormats extends Enum<PreviewFormats>
```

Enumera los formatos de vista previa compatibles para la comparación de documentos.
El enumerado PreviewFormats proporciona una lista de formatos que pueden usarse para generar vistas previas de documentos comparados.

Los formatos compatibles incluyen:

* #PNG.PNG - Portable Network Graphics (.png)
* #JPEG.JPEG - Joint Photographic Experts Group (.jpeg)
* #BMP.BMP - Bitmap Picture (.bmp)


Ejemplo de uso:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    PreviewOptions previewOptions = new PreviewOptions(
            pageNumber -> Files.newOutputStream(Paths.get(String.format("preview-page_%d.png", pageNumber)))
    );
    previewOptions.setPreviewFormat(PreviewFormats.PNG);

    comparer.getTargets().get(0).generatePreview(previewOptions);
 }
 
````


## Campos

| Campo | Descripción |
| --- | --- |
|  | [PNG](#PNG) | PNG - puede consumir un espacio en disco significativo o tráfico de red si la página contiene numerosos gráficos en color. |
|
|  | [JPEG](#JPEG) | Jpeg - ofrece un procesamiento más rápido con menor uso de espacio en disco y tráfico de red, pero puede resultar en una calidad de imagen inferior. |
|
|  | [BMP](#BMP) | BMP - ofrece la mejor calidad de imagen pero requiere un procesamiento más lento con mayor uso de espacio en disco y tráfico de red. |
|
## Métodos

| Método | Descripción |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Analiza la representación en cadena de PreviewFormats para obtener la constante del enumerado. |
|
|  | [toString()](#toString--) | Representación en cadena de PreviewFormats. |
|
### PNG {#PNG}
```
public static final PreviewFormats PNG
```


PNG - puede consumir un espacio en disco significativo o tráfico de red si la página contiene numerosos gráficos en color. Formato de vista previa predeterminado.


### JPEG {#JPEG}
```
public static final PreviewFormats JPEG
```


Jpeg - ofrece un procesamiento más rápido con menor uso de espacio en disco y tráfico de red, pero puede resultar en una calidad de imagen inferior.


### BMP {#BMP}
```
public static final PreviewFormats BMP
```


BMP - ofrece la mejor calidad de imagen pero requiere un procesamiento más lento con mayor uso de espacio en disco y tráfico de red.


### values() {#values--}
```
public static PreviewFormats[] values()
```




**Returns:**
com.groupdocs.comparison.options.enums.PreviewFormats[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PreviewFormats valueOf(String name)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String |  |

**Returns:**
[PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static PreviewFormats fromString(String toStringValue)
```


Analiza la representación en cadena de PreviewFormats para obtener la constante del enumerado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | toStringValue | java.lang.String | La representación en cadena de PreviewFormats |
|

**Returns:**
[PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats) - PreviewFormats enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


Representación en cadena de PreviewFormats.


**Returns:**
java.lang.String - valor en cadena de la constante del enum

