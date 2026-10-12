---
title: "Comparer"
second_title: "Referencia de API de GroupDocs.Comparison for Java"
description: "La clase Comparer proporciona funcionalidad para comparar documentos y generar resultados de comparación."
type: docs
weight: 10
url: /es/java/com.groupdocs.comparison/comparer/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public class Comparer implements System.IDisposable, Closeable
```

La clase Comparer proporciona funcionalidad para comparar documentos y generar resultados de comparación.


Permite comparar varios tipos de documentos, como PDF, Word, Excel, PowerPoint y más.


Ejemplo de uso:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     CompareOptions compareOptions = new CompareOptions();
     compareOptions.setDetectStyleChanges(true);

     comparer.compare(resultFile, compareOptions);
 }
 
````


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [Comparer(String filePath)](#Comparer-java.lang.String-) | Inicializa una nueva instancia de la clase Comparer con la ruta del archivo fuente especificada. |
|
|  | [Comparer(String filePath, CompareOptions compareOptions)](#Comparer-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | Inicializa una nueva instancia de la clase Comparer con la ruta de la carpeta especificada y las opciones de comparación. |
|
|  | [Comparer(Path filePath)](#Comparer-java.nio.file.Path-) | Inicializa una nueva instancia de la clase Comparer con la ruta del archivo fuente especificada. |
|
|  | [Comparer(String filePath, LoadOptions loadOptions)](#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-) | Inicializa una nueva instancia de Comparer con la ruta del archivo fuente especificada y [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions). |
|
|  | [Comparer(Path filePath, LoadOptions loadOptions)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-) | Inicializa una nueva instancia de Comparer con la ruta del archivo fuente especificada y [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions). |
|
|  | [Comparer(Path filePath, CompareOptions compareOptions)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | Inicializa una nueva instancia de Comparer con la ruta del archivo fuente especificada y [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions). |
|
|  | [Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings)](#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-) | Inicializa una nueva instancia de la clase Comparer con la ruta del archivo fuente especificada, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) y [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)](#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-) | Inicializa una nueva instancia de la clase Comparer con la ruta del archivo fuente especificada, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) y [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(String filePath, ComparerSettings settings)](#Comparer-java.lang.String-com.groupdocs.comparison.ComparerSettings-) | Inicializa una nueva instancia de la clase Comparer con la ruta del archivo fuente especificada y [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(Path filePath, ComparerSettings settings)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.ComparerSettings-) | Inicializa una nueva instancia de la clase Comparer con la ruta del archivo fuente especificada y [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-) | Inicializa una nueva instancia de la clase Comparer con la ruta del archivo fuente especificada, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) y [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-) | Inicializa una nueva instancia de la clase Comparer con la ruta del archivo fuente especificada, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) y [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(InputStream document)](#Comparer-java.io.InputStream-) | Inicializa una nueva instancia de la clase Comparer con el flujo del documento fuente especificado. |
|
|  | [Comparer(InputStream document, LoadOptions loadOptions)](#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-) | Inicializa una nueva instancia de Comparer con el flujo del documento fuente especificado y [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions). |
|
|  | [Comparer(InputStream document, ComparerSettings settings)](#Comparer-java.io.InputStream-com.groupdocs.comparison.ComparerSettings-) | Inicializa una nueva instancia de la clase Comparer con el flujo del documento fuente especificado y [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(InputStream document, LoadOptions loadOptions, ComparerSettings settings)](#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-) | Inicializa una nueva instancia de la clase Comparer con el flujo del documento especificado, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) y [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(ComparerSettings settings)](#Comparer-com.groupdocs.comparison.ComparerSettings-) | Inicializa una nueva instancia de la clase Comparer con los [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
## Campos

| Campo | Descripción |
| --- | --- |
| [FILE_PATH](#FILE-PATH) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getSource()](#getSource--) | Obtiene el documento fuente que se está comparando. |
|
|  | [getTargets()](#getTargets--) | Lista de documentos objetivo para comparar con el archivo fuente. |
|
|  | [compare()](#compare--) | Compara el archivo especificado con los documentos objetivo sin guardar el resultado con las opciones predeterminadas. |
|
|  | [compare(String filePath)](#compare-java.lang.String-) | Compara el archivo especificado con los documentos objetivo y genera un resultado de comparación. |
|
|  | [compare(Path filePath)](#compare-java.nio.file.Path-) | Compara el archivo especificado con los documentos objetivo y genera un resultado de comparación. |
|
|  | [compare(OutputStream outputStream)](#compare-java.io.OutputStream-) | Compara el archivo especificado con los documentos objetivo y escribe un resultado de comparación en el flujo de salida. |
|
|  | [compare(String filePath, CompareOptions compareOptions)](#compare-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | Compara el archivo especificado con los documentos objetivo y escribe un resultado de comparación en la ruta de archivo proporcionada. |
|
|  | [compare(Path filePath, CompareOptions compareOptions)](#compare-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | Compara el archivo especificado con los documentos objetivo y escribe un resultado de comparación en la ruta de archivo proporcionada. |
|
|  | [compare(OutputStream stream, CompareOptions compareOptions)](#compare-java.io.OutputStream-com.groupdocs.comparison.options.CompareOptions-) | Compara el archivo especificado con los documentos objetivo y escribe un resultado de comparación en el flujo de salida. |
|
|  | [compare(SaveOptions saveOptions, CompareOptions compareOptions)](#compare-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | Compara el archivo especificado con los documentos objetivo sin guardar el resultado. |
|
|  | [compare(String filePath, SaveOptions saveOptions)](#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-) | Compara el archivo especificado con los documentos objetivo y escribe un resultado de comparación en la ruta de archivo proporcionada. |
|
|  | [compare(Path filePath, SaveOptions saveOptions)](#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-) | Compara el archivo especificado con los documentos objetivo y escribe un resultado de comparación en la ruta de archivo proporcionada. |
|
|  | [compare(OutputStream stream, SaveOptions saveOptions)](#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-) | Compara el archivo especificado con los documentos objetivo y escribe un resultado de comparación en la ruta de archivo proporcionada. |
|
|  | [compare(CompareOptions compareOptions)](#compare-com.groupdocs.comparison.options.CompareOptions-) | Compara el archivo especificado con los documentos objetivo sin guardar el resultado. |
|
|  | [compare(OutputStream outputStream, SaveOptions saveOptions, CompareOptions compareOptions)](#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | Compara el archivo especificado con los documentos objetivo y escribe un resultado de comparación en el flujo de salida proporcionado. |
|
|  | [compare(String filePath, SaveOptions saveOptions, CompareOptions compareOptions)](#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | Compara el archivo especificado con los documentos objetivo y escribe un resultado de comparación en la ruta de archivo proporcionada. |
|
|  | [compareDirectory(String filePath, CompareOptions compareOptions)](#compareDirectory-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | Compara el directorio especificado con el directorio objetivo y guarda el resultado de comparación en la ruta de archivo proporcionada. |
|
|  | [compareDirectory(Path filePath, CompareOptions compareOptions)](#compareDirectory-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | Compara el directorio especificado con el directorio objetivo y guarda el resultado de comparación en la ruta de archivo proporcionada. |
|
|  | [compare(Path filePath, SaveOptions saveOptions, CompareOptions compareOptions)](#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | Compara el archivo especificado con los documentos objetivo y escribe un resultado de comparación en la ruta de archivo proporcionada. |
|
|  | [add(String filePath)](#add-java.lang.String-) | Agrega el documento objetivo especificado al proceso de comparación. |
|
|  | [add(String filePath, CompareOptions compareOptions)](#add-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | Agrega el documento objetivo o la carpeta especificada al proceso de comparación. |
|
|  | [add(Path filePath)](#add-java.nio.file.Path-) | Agrega el documento objetivo especificado al proceso de comparación. |
|
|  | [add(String[] filePaths)](#add-java.lang.String...-) | Agrega los documentos objetivo especificados al proceso de comparación. |
|
|  | [add(Path[] filePaths)](#add-java.nio.file.Path...-) | Agrega los documentos objetivo especificados al proceso de comparación. |
|
|  | [add(String filePath, LoadOptions loadOptions)](#add-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-) | Agrega el documento objetivo especificado al proceso de comparación con las opciones de carga especificadas. |
|
|  | [add(Path filePath, LoadOptions loadOptions)](#add-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-) | Agrega el documento objetivo especificado al proceso de comparación con las opciones de carga especificadas. |
|
|  | [add(Path filePath, CompareOptions compareOptions)](#add-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | Agrega el documento objetivo especificado al proceso de comparación con las opciones de carga especificadas. |
|
|  | [add(InputStream document)](#add-java.io.InputStream-) | Agrega el documento objetivo especificado al proceso de comparación. |
|
|  | [add(InputStream[] documents)](#add-java.io.InputStream...-) | Agrega los documentos objetivo especificados al proceso de comparación. |
|
|  | [add(InputStream document, LoadOptions loadOptions)](#add-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-) | Agrega el documento objetivo especificado al proceso de comparación con las opciones de carga especificadas. |
|
|  | [getChanges()](#getChanges--) | Recupera una matriz de objetos [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) que representan los cambios detectados durante el proceso de comparación. |
|
|  | [getChanges(GetChangeOptions getChangeOptions)](#getChanges-com.groupdocs.comparison.options.GetChangeOptions-) | Recupera una matriz de objetos [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) que representan los cambios detectados durante el proceso de comparación. |
|
|  | [applyChanges(String filePath, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.lang.String-com.groupdocs.comparison.options.ApplyChangeOptions-) | Acepta o rechaza cambios y los aplica al documento resultante. |
|
|  | [applyChanges(Path filePath, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.ApplyChangeOptions-) | Acepta o rechaza cambios y los aplica al documento resultante. |
|
|  | [applyChanges(OutputStream document, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.ApplyChangeOptions-) | Acepta o rechaza cambios y los aplica al documento resultante. |
|
|  | [applyChanges(String filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-) | Acepta o rechaza cambios y los aplica al documento resultante. |
|
|  | [applyChanges(Path filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-) | Acepta o rechaza cambios y los aplica al documento resultante. |
|
|  | [applyChanges(OutputStream document, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-) | Acepta o rechaza cambios y los aplica al documento resultante. |
|
|  | [getResultString()](#getResultString--) | Obtiene la cadena de resultado después de la comparación (solo para comparación de texto). |
|
|  | [getSourceFolder()](#getSourceFolder--) | Devuelve la carpeta fuente que se está comparando. |
|
|  | [getTargetFolder()](#getTargetFolder--) | Devuelve la carpeta de destino que se está comparando. |
|
|  | [selfComparisonCheck(Document source, Document target)](#selfComparisonCheck-com.groupdocs.comparison.Document-com.groupdocs.comparison.Document-) | Verificación de auto-comparación (e498c23). |
|
|  | [close()](#close--) | Libera los recursos. |
|
### Comparer(String filePath) {#Comparer-java.lang.String-}
```
public Comparer(String filePath)
```


Inicializa una nueva instancia de la clase Comparer con la ruta del archivo fuente especificada.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.lang.String | La ruta al documento fuente |
|

### Comparer(String filePath, CompareOptions compareOptions) {#Comparer-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(String filePath, CompareOptions compareOptions)
```


Inicializa una nueva instancia de la clase Comparer con la ruta de la carpeta especificada y las opciones de comparación.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.lang.String | La ruta al documento o carpeta fuente |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Las opciones de comparación para la comparación de carpetas |
|

### Comparer(Path filePath) {#Comparer-java.nio.file.Path-}
```
public Comparer(Path filePath)
```


Inicializa una nueva instancia de la clase Comparer con la ruta del archivo fuente especificada.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | La ruta al documento fuente |
|

### Comparer(String filePath, LoadOptions loadOptions) {#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Comparer(String filePath, LoadOptions loadOptions)
```


Inicializa una nueva instancia de Comparer con la ruta del archivo fuente especificada y [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.lang.String | La ruta al documento fuente |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Las opciones de carga personalizadas que se aplicarán al documento |
|

### Comparer(Path filePath, LoadOptions loadOptions) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Comparer(Path filePath, LoadOptions loadOptions)
```


Inicializa una nueva instancia de Comparer con la ruta del archivo fuente especificada y [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | La ruta al documento fuente |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Las opciones de carga personalizadas que se aplicarán al documento |
|

### Comparer(Path filePath, CompareOptions compareOptions) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(Path filePath, CompareOptions compareOptions)
```


Inicializa una nueva instancia de Comparer con la ruta del archivo fuente especificada y [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | La ruta al documento fuente |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Las opciones de comparación para la comparación de carpetas |
|

### Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings) {#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings)
```


Inicializa una nueva instancia de la clase Comparer con la ruta del archivo fuente especificada, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) y [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.lang.String | La ruta al documento fuente |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Las opciones de carga personalizadas que se aplicarán al documento |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | La configuración del comparador que se usará para el proceso de comparación |
|

### Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions) {#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)
```


Inicializa una nueva instancia de la clase Comparer con la ruta del archivo fuente especificada, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) y [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.lang.String | La ruta al documento, carpeta o texto fuente que se va a comparar |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Las opciones de carga personalizadas que se aplicarán al documento |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | La configuración del comparador que se usará para el proceso de comparación |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Las opciones de comparación para la comparación de carpetas |
|

### Comparer(String filePath, ComparerSettings settings) {#Comparer-java.lang.String-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(String filePath, ComparerSettings settings)
```


Inicializa una nueva instancia de la clase Comparer con la ruta del archivo fuente especificada y [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.lang.String | La ruta al documento fuente |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | La configuración del comparador que se usará para el proceso de comparación |
|

### Comparer(Path filePath, ComparerSettings settings) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(Path filePath, ComparerSettings settings)
```


Inicializa una nueva instancia de la clase Comparer con la ruta del archivo fuente especificada y [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | La ruta al documento fuente |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | La configuración del comparador que se usará para el proceso de comparación |
|

### Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings)
```


Inicializa una nueva instancia de la clase Comparer con la ruta del archivo fuente especificada, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) y [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | La ruta al documento fuente |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Las opciones de carga personalizadas que se aplicarán al documento |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | La configuración del comparador que se usará para el proceso de comparación |
|

### Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)
```


Inicializa una nueva instancia de la clase Comparer con la ruta del archivo fuente especificada, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) y [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | La ruta al documento o carpeta fuente |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Las opciones de carga personalizadas que se aplicarán al documento |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | La configuración del comparador que se usará para el proceso de comparación |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Las opciones de comparación para la comparación de carpetas |
|

### Comparer(InputStream document) {#Comparer-java.io.InputStream-}
```
public Comparer(InputStream document)
```


Inicializa una nueva instancia de la clase Comparer con el flujo del documento fuente especificado.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | documento | java.io.InputStream | El flujo de entrada del documento fuente |
|

### Comparer(InputStream document, LoadOptions loadOptions) {#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Comparer(InputStream document, LoadOptions loadOptions)
```


Inicializa una nueva instancia de Comparer con el flujo del documento fuente especificado y [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | documento | java.io.InputStream | El flujo de entrada del documento fuente |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Las opciones de carga personalizadas que se aplicarán al documento |
|

### Comparer(InputStream document, ComparerSettings settings) {#Comparer-java.io.InputStream-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(InputStream document, ComparerSettings settings)
```


Inicializa una nueva instancia de la clase Comparer con el flujo del documento fuente especificado y [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | documento | java.io.InputStream | El flujo de entrada del documento fuente |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | La configuración del comparador que se usará para el proceso de comparación |
|

### Comparer(InputStream document, LoadOptions loadOptions, ComparerSettings settings) {#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(InputStream document, LoadOptions loadOptions, ComparerSettings settings)
```


Inicializa una nueva instancia de la clase Comparer con el flujo del documento especificado, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) y [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | documento | java.io.InputStream | El flujo con los datos de un documento a comparar |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Las opciones de carga personalizadas que se aplicarán al documento |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | La configuración del comparador que se usará para el proceso de comparación |
|

### Comparer(ComparerSettings settings) {#Comparer-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(ComparerSettings settings)
```


Inicializa una nueva instancia de la clase Comparer con los [ComparerSettings](../../com.groupdocs.comparison/comparersettings).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | la configuración |
|

### FILE_PATH {#FILE-PATH}
```
public static final String FILE_PATH
```


### getSource() {#getSource--}
```
public final Document getSource()
```


Obtiene el documento fuente que se está comparando.


**Returns:**
[Document](../../com.groupdocs.comparison/document) - the source document

### getTargets() {#getTargets--}
```
public final List<Document> getTargets()
```


Lista de documentos objetivo para comparar con el archivo fuente.


**Returns:**
java.util.List<com.groupdocs.comparison.Document> - los documentos de destino

### compare() {#compare--}
```
public final Path compare()
```


Compara el archivo especificado con los documentos objetivo sin guardar el resultado con las opciones predeterminadas.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Returns:**
java.nio.file.Path - la ruta del documento resultante o null

### compare(String filePath) {#compare-java.lang.String-}
```
public final Path compare(String filePath)
```


Compara el archivo especificado con los documentos objetivo y genera un resultado de comparación.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.lang.String | Ruta del documento resultante |
|

**Returns:**
java.nio.file.Path - ruta del archivo resultante o null. En algunas situaciones su extensión puede cambiarse

### compare(Path filePath) {#compare-java.nio.file.Path-}
```
public final Path compare(Path filePath)
```


Compara el archivo especificado con los documentos objetivo y genera un resultado de comparación.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Ruta del documento resultante |
|

**Returns:**
java.nio.file.Path - ruta del archivo resultante, en algunas situaciones su extensión puede cambiarse

### compare(OutputStream outputStream) {#compare-java.io.OutputStream-}
```
public final Path compare(OutputStream outputStream)
```


Compara el archivo especificado con los documentos objetivo y escribe un resultado de comparación en el flujo de salida.


Nota: En los casos en que el valor de retorno sea null, use los datos que se escribieron en outputStream

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | outputStream | java.io.OutputStream | Flujo del documento resultante |
|

**Returns:**
java.nio.file.Path - ruta del archivo resultante o null cuando se deben usar los datos de outputStream. En algunas situaciones la extensión del archivo resultante puede cambiarse

### compare(String filePath, CompareOptions compareOptions) {#compare-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(String filePath, CompareOptions compareOptions)
```


Compara el archivo especificado con los documentos objetivo y escribe un resultado de comparación en la ruta de archivo proporcionada.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.lang.String | Ruta del archivo del documento resultante |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Las opciones de comparación que se usarán para el proceso de comparación |
|

**Returns:**
java.nio.file.Path - ruta del archivo resultante, en algunas situaciones su extensión puede cambiarse

### compare(Path filePath, CompareOptions compareOptions) {#compare-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(Path filePath, CompareOptions compareOptions)
```


Compara el archivo especificado con los documentos objetivo y escribe un resultado de comparación en la ruta de archivo proporcionada.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Ruta del archivo del documento resultante |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Las opciones de comparación que se usarán para el proceso de comparación |
|

**Returns:**
java.nio.file.Path - ruta del archivo resultante, en algunas situaciones su extensión puede cambiarse

### compare(OutputStream stream, CompareOptions compareOptions) {#compare-java.io.OutputStream-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(OutputStream stream, CompareOptions compareOptions)
```


Compara el archivo especificado con los documentos objetivo y escribe un resultado de comparación en el flujo de salida.


Nota: En caso de que el valor de retorno sea null, use los datos que se escribieron en outputStream.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | flujo | java.io.OutputStream | Flujo del documento resultante |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Las opciones de comparación que se usarán para el proceso de comparación |
|

**Returns:**
java.nio.file.Path - ruta del archivo resultante o null cuando se deben usar los datos de outputStream. En algunas situaciones la extensión del archivo resultante puede cambiarse

### compare(SaveOptions saveOptions, CompareOptions compareOptions) {#compare-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(SaveOptions saveOptions, CompareOptions compareOptions)
```


Compara el archivo especificado con los documentos objetivo sin guardar el resultado.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparison options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Opciones de guardado |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Las opciones de comparación que se usarán para el proceso de comparación |
|

**Returns:**
java.nio.file.Path - la ruta del documento resultante o null

### compare(String filePath, SaveOptions saveOptions) {#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-}
```
public final Path compare(String filePath, SaveOptions saveOptions)
```


Compara el archivo especificado con los documentos objetivo y escribe un resultado de comparación en la ruta de archivo proporcionada.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.lang.String | Ruta del archivo del documento resultante |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Opciones de guardado |
|

**Returns:**
java.nio.file.Path - ruta del archivo resultante, en algunas situaciones su extensión puede cambiarse

### compare(Path filePath, SaveOptions saveOptions) {#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-}
```
public final Path compare(Path filePath, SaveOptions saveOptions)
```


Compara el archivo especificado con los documentos objetivo y escribe un resultado de comparación en la ruta de archivo proporcionada.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Ruta del archivo del documento resultante |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Opciones de guardado |
|

**Returns:**
java.nio.file.Path - ruta del archivo resultante, en algunas situaciones su extensión puede cambiarse

### compare(OutputStream stream, SaveOptions saveOptions) {#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-}
```
public final Path compare(OutputStream stream, SaveOptions saveOptions)
```


Compara el archivo especificado con los documentos objetivo y escribe un resultado de comparación en la ruta de archivo proporcionada.


Nota: En caso de que el valor de retorno sea nulo, use los datos que se escribieron en outputStream

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | flujo | java.io.OutputStream | Flujo del documento resultante |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Opciones de guardado |
|

**Returns:**
java.nio.file.Path - ruta del archivo resultante o null cuando se deben usar los datos de outputStream. En algunas situaciones la extensión del archivo resultante puede cambiarse

### compare(CompareOptions compareOptions) {#compare-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(CompareOptions compareOptions)
```


Compara el archivo especificado con los documentos objetivo sin guardar el resultado.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Las opciones de comparación que se usarán para el proceso de comparación |
|

**Returns:**
java.nio.file.Path - la ruta al archivo de resultado o nulo

### compare(OutputStream outputStream, SaveOptions saveOptions, CompareOptions compareOptions) {#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(OutputStream outputStream, SaveOptions saveOptions, CompareOptions compareOptions)
```


Compara el archivo especificado con los documentos objetivo y escribe un resultado de comparación en el flujo de salida proporcionado.


Nota: En caso de que el valor de retorno sea nulo, use los datos que se escribieron en outputStream

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | outputStream | java.io.OutputStream | Flujo del documento resultante |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Las opciones de guardado que se usarán para guardar el documento resultante |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Las opciones de comparación que se usarán para el proceso de comparación |
|

**Returns:**
java.nio.file.Path - ruta del archivo resultante o null cuando se deben usar los datos de outputStream. En algunas situaciones la extensión del archivo resultante puede cambiarse

### compare(String filePath, SaveOptions saveOptions, CompareOptions compareOptions) {#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(String filePath, SaveOptions saveOptions, CompareOptions compareOptions)
```


Compara el archivo especificado con los documentos objetivo y escribe un resultado de comparación en la ruta de archivo proporcionada.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparison options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.lang.String | Ruta del archivo del documento resultante |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Las opciones de guardado que se usarán para guardar el documento resultante |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Las opciones de comparación que se usarán para el proceso de comparación |
|

**Returns:**
java.nio.file.Path - ruta del archivo resultante, en algunas situaciones su extensión puede cambiarse

### compareDirectory(String filePath, CompareOptions compareOptions) {#compareDirectory-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public void compareDirectory(String filePath, CompareOptions compareOptions)
```


Compara el directorio especificado con el directorio objetivo y guarda el resultado de comparación en la ruta de archivo proporcionada.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.lang.String | La ruta del archivo donde se guardará el resultado de la comparación. |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Las opciones que se usarán para el proceso de comparación de directorios. |
|

### compareDirectory(Path filePath, CompareOptions compareOptions) {#compareDirectory-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public void compareDirectory(Path filePath, CompareOptions compareOptions)
```


Compara el directorio especificado con el directorio objetivo y guarda el resultado de comparación en la ruta de archivo proporcionada.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | La ruta del archivo donde se guardará el resultado de la comparación. |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Las opciones que se usarán para el proceso de comparación de directorios. |
|

### compare(Path filePath, SaveOptions saveOptions, CompareOptions compareOptions) {#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(Path filePath, SaveOptions saveOptions, CompareOptions compareOptions)
```


Compara el archivo especificado con los documentos objetivo y escribe un resultado de comparación en la ruta de archivo proporcionada.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Ruta del archivo del documento resultante |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Las opciones de guardado que se usarán para guardar el documento resultante |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Las opciones de comparación que se usarán para el proceso de comparación |
|

**Returns:**
java.nio.file.Path - ruta del archivo resultante, en algunas situaciones su extensión puede cambiarse

### add(String filePath) {#add-java.lang.String-}
```
public final void add(String filePath)
```


Agrega el documento objetivo especificado al proceso de comparación.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.lang.String | La ruta al documento objetivo que se añadirá |
|

### add(String filePath, CompareOptions compareOptions) {#add-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public void add(String filePath, CompareOptions compareOptions)
```


Agrega el documento objetivo o la carpeta especificada al proceso de comparación.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.lang.String | La ruta al documento o carpeta objetivo que se añadirá |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Las opciones para la comparación |
|

### add(Path filePath) {#add-java.nio.file.Path-}
```
public final void add(Path filePath)
```


Agrega el documento objetivo especificado al proceso de comparación.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | La ruta al documento objetivo que se añadirá |
|

### add(String[] filePaths) {#add-java.lang.String...-}
```
public final void add(String[] filePaths)
```


Agrega los documentos objetivo especificados al proceso de comparación.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePaths | java.lang.String[] | Rutas a los documentos objetivo que se añadirán |
|

### add(Path[] filePaths) {#add-java.nio.file.Path...-}
```
public final void add(Path[] filePaths)
```


Agrega los documentos objetivo especificados al proceso de comparación.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePaths | java.nio.file.Path[] | Rutas a los documentos objetivo que se añadirán |
|

### add(String filePath, LoadOptions loadOptions) {#add-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-}
```
public final void add(String filePath, LoadOptions loadOptions)
```


Agrega el documento objetivo especificado al proceso de comparación con las opciones de carga especificadas.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.lang.String | Ruta al documento objetivo que se añadirá |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Las opciones de carga personalizadas que se aplicarán al documento |
|

### add(Path filePath, LoadOptions loadOptions) {#add-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-}
```
public final void add(Path filePath, LoadOptions loadOptions)
```


Agrega el documento objetivo especificado al proceso de comparación con las opciones de carga especificadas.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Ruta al documento objetivo que se añadirá |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Las opciones de carga personalizadas que se aplicarán al documento |
|

### add(Path filePath, CompareOptions compareOptions) {#add-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public final void add(Path filePath, CompareOptions compareOptions)
```


Agrega el documento objetivo especificado al proceso de comparación con las opciones de carga especificadas.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | La ruta al documento o carpeta objetivo que se añadirá |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Las opciones para la comparación |
|

### add(InputStream document) {#add-java.io.InputStream-}
```
public final void add(InputStream document)
```


Agrega el documento objetivo especificado al proceso de comparación.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | documento | java.io.InputStream | El flujo con los datos de un documento a comparar |
|

### add(InputStream[] documents) {#add-java.io.InputStream...-}
```
public final void add(InputStream[] documents)
```


Agrega los documentos objetivo especificados al proceso de comparación.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | documents | java.io.InputStream[] | Flujos con datos de documentos que se compararán |
|

### add(InputStream document, LoadOptions loadOptions) {#add-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-}
```
public final void add(InputStream document, LoadOptions loadOptions)
```


Agrega el documento objetivo especificado al proceso de comparación con las opciones de carga especificadas.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | documento | java.io.InputStream | El flujo con los datos de un documento a comparar |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Las opciones de carga personalizadas que se aplicarán al documento |
|

### getChanges() {#getChanges--}
```
public final ChangeInfo[] getChanges()
```


Recupera una matriz de objetos [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) que representan los cambios detectados durante el proceso de comparación.


Utilice este método para obtener información detallada sobre los cambios entre el documento de origen y el(los) documento(s) de destino.
Cada objeto [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) contiene información como el tipo de cambio, el área afectada,
y el contenido antes y después del cambio.

* More about how to obtain collection of detected differences between compared documents in Java: [How to get list of changes between documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Get+list+of+changes)
* More about how to get changes coordinates at pages image preview when comparing documents using GroupDocs.Comparison for Java: [How to get changes coordinates programmatically](../https://docs.groupdocs.com/display/comparisonjava/Get+changes+coordinates)


**Returns:**
com.groupdocs.comparison.result.ChangeInfo[] - una matriz de objetos [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) que representan los cambios detectados durante el proceso de comparación

### getChanges(GetChangeOptions getChangeOptions) {#getChanges-com.groupdocs.comparison.options.GetChangeOptions-}
```
public final ChangeInfo[] getChanges(GetChangeOptions getChangeOptions)
```


Recupera una matriz de objetos [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) que representan los cambios detectados durante el proceso de comparación.


Utilice este método para obtener información detallada sobre los cambios entre el documento de origen y el(los) documento(s) de destino.
Cada objeto [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) contiene información como el tipo de cambio, el área afectada,
y el contenido antes y después del cambio.


El parámetro [GetChangeOptions](../../com.groupdocs.comparison.options/getchangeoptions) permite filtrar los cambios de manera diferente.

* More about how to obtain collection of detected differences between compared documents in Java: [How to get list of changes between documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Get+list+of+changes)
* More about how to get changes coordinates at pages image preview when comparing documents using GroupDocs.Comparison for Java: [How to get changes coordinates programmatically](../https://docs.groupdocs.com/display/comparisonjava/Get+changes+coordinates)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | getChangeOptions | [GetChangeOptions](../../com.groupdocs.comparison.options/getchangeoptions) | El objeto que permite filtrar los cambios |
|

**Returns:**
com.groupdocs.comparison.result.ChangeInfo[] - una matriz de objetos [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) que representan los cambios detectados durante el proceso de comparación

### applyChanges(String filePath, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.lang.String-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(String filePath, ApplyChangeOptions applyChangeOptions)
```


Acepta o rechaza cambios y los aplica al documento resultante.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.lang.String | Ruta del archivo del documento resultante |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | Las opciones personalizadas de aplicar cambios para configurar el proceso de aplicación de cambios |
|

### applyChanges(Path filePath, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(Path filePath, ApplyChangeOptions applyChangeOptions)
```


Acepta o rechaza cambios y los aplica al documento resultante.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Ruta del archivo del documento resultante |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | Las opciones personalizadas de aplicar cambios para configurar el proceso de aplicación de cambios |
|

### applyChanges(OutputStream document, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(OutputStream document, ApplyChangeOptions applyChangeOptions)
```


Acepta o rechaza cambios y los aplica al documento resultante.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | documento | java.io.OutputStream | Flujo de salida del documento resultante |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | Las opciones personalizadas de aplicar cambios para configurar el proceso de aplicación de cambios |
|

### applyChanges(String filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(String filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)
```


Acepta o rechaza cambios y los aplica al documento resultante.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.lang.String | Ruta del archivo del documento resultante |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Las opciones de guardado para configurar el guardado del documento resultante |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | Las opciones personalizadas de aplicar cambios para configurar el proceso de aplicación de cambios |
|

### applyChanges(Path filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(Path filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)
```


Acepta o rechaza cambios y los aplica al documento resultante.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Ruta del archivo del documento resultante |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Las opciones de guardado para configurar el guardado del documento resultante |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | Las opciones personalizadas de aplicar cambios para configurar el proceso de aplicación de cambios |
|

### applyChanges(OutputStream document, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(OutputStream document, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)
```


Acepta o rechaza cambios y los aplica al documento resultante.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | documento | java.io.OutputStream | Flujo de salida del documento resultante |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Las opciones de guardado para configurar el guardado del documento resultante |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | Las opciones personalizadas de aplicar cambios para configurar el proceso de aplicación de cambios |
|

### getResultString() {#getResultString--}
```
public String getResultString()
```


Obtiene la cadena de resultado después de la comparación (solo para comparación de texto).


**Returns:**
java.lang.String - la cadena de resultado

### getSourceFolder() {#getSourceFolder--}
```
public String getSourceFolder()
```


Devuelve la carpeta fuente que se está comparando.


**Returns:**
java.lang.String - la carpeta de origen

### getTargetFolder() {#getTargetFolder--}
```
public String getTargetFolder()
```


Devuelve la carpeta de destino que se está comparando.


**Returns:**
java.lang.String - la carpeta de destino

### selfComparisonCheck(Document source, Document target) {#selfComparisonCheck-com.groupdocs.comparison.Document-com.groupdocs.comparison.Document-}
```
public static void selfComparisonCheck(Document source, Document target)
```


Verificación de auto-comparación (e498c23). C# 7a7668c interno; mantenido público para que las pruebas core.common puedan llamarlo.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [Document](../../com.groupdocs.comparison/document) |  |
| target | [Document](../../com.groupdocs.comparison/document) |  |

### close() {#close--}
```
public void close()
```


Libera los recursos.


