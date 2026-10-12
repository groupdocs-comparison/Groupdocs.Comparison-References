---
title: "CompareOptions"
second_title: "Referencia de API de GroupDocs.Comparison for Java"
description: "Permite configurar el proceso de comparación de documentos."
type: docs
weight: 11
url: /es/java/com.groupdocs.comparison.options/compareoptions/
---
**Inheritance:**
java.lang.Object
```
public class CompareOptions
```

Permite configurar el proceso de comparación de documentos.


Ejemplo de uso:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     final StyleSettings styleSettings = new StyleSettings();
     styleSettings.setHighlightColor(Color.RED);
     styleSettings.setFontColor(Color.GREEN);
     styleSettings.setUnderline(true);

     CompareOptions compareOptions = new CompareOptions();
     compareOptions.setInsertedItemStyle(styleSettings);

     comparer.compare(resultFile, compareOptions);
 }
 
````


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [CompareOptions()](#CompareOptions--) | Inicializa una nueva instancia de la clase CompareOptions. |
|
|  | [CompareOptions(StyleSettings insertedItemStyle, StyleSettings deletedItemStyle, StyleSettings changedItemStyle)](#CompareOptions-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-) | Inicializa una nueva instancia de la clase CompareOptions con configuraciones para diferentes estilos. |
|
## Campos

| Campo | Descripción |
| --- | --- |
| [ignoreChangeSettings](#ignoreChangeSettings) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getIgnoreChangeSettings()](#getIgnoreChangeSettings--) | Obtiene la configuración para ignorar cambios basados en la similitud. |
|
|  | [setIgnoreChangeSettings(IgnoreChangeSensitivitySettings ignoreChangeSettings)](#setIgnoreChangeSettings-com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings-) | Establece la configuración para ignorar cambios basados en la similitud. |
|
|  | [getUserMasterPath()](#getUserMasterPath--) | Obtiene la ruta a la plantilla maestra del usuario para Diagramas. |
|
|  | [setUserMasterPath(String userMasterPath)](#setUserMasterPath-java.lang.String-) | Establece la ruta a la plantilla maestra del usuario para Diagramas. |
|
|  | [getComparisonType()](#getComparisonType--) | Obtiene un tipo de documentos origen y destino como objeto [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) para que Comparison sepa cómo compararlos. |
|
|  | [setComparisonType(ComparisonType comparisonType)](#setComparisonType-com.groupdocs.comparison.options.enums.ComparisonType-) | Establece un tipo de documentos origen y destino como objeto [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) para que Comparison sepa cómo compararlos. |
|
|  | [getPaperSize()](#getPaperSize--) | Obtiene un tamaño de papel en el documento resultante como objeto [PaperSize](../../com.groupdocs.comparison.options.enums/papersize). |
|
|  | [setPaperSize(PaperSize value)](#setPaperSize-com.groupdocs.comparison.options.enums.PaperSize-) | Establece un tamaño de papel en el documento resultante como objeto [PaperSize](../../com.groupdocs.comparison.options.enums/papersize). |
|
|  | [getCalculateCoordinatesMode()](#getCalculateCoordinatesMode--) | Obtiene un modo de cálculo de coordenadas como objeto [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration). |
|
|  | [setCalculateCoordinatesMode(CalculateCoordinatesModeEnumeration calculateCoordinatesMode)](#setCalculateCoordinatesMode-com.groupdocs.comparison.options.enums.CalculateCoordinatesModeEnumeration-) | Establece un modo de cálculo de coordenadas como objeto [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration). |
|
|  | [isShowDeletedContent()](#isShowDeletedContent--) | Obtiene una bandera que indica si se deben mostrar los componentes eliminados en el documento resultante o no. |
|
|  | [setShowDeletedContent(boolean value)](#setShowDeletedContent-boolean-) | Establece una bandera que indica si se deben mostrar los componentes eliminados en el documento resultante o no. |
|
|  | [isShowInsertedContent()](#isShowInsertedContent--) | Obtiene una bandera que indica si se deben mostrar los componentes insertados en el documento resultante o no. |
|
|  | [setShowInsertedContent(boolean value)](#setShowInsertedContent-boolean-) | Establece una bandera que indica si se deben mostrar los componentes insertados en el documento resultante o no. |
|
|  | [isGenerateSummaryPage()](#isGenerateSummaryPage--) | Obtiene una bandera que indica si se debe agregar una página de resumen con estadísticas de cambios detectados al documento resultante o no. |
|
|  | [setGenerateSummaryPage(boolean value)](#setGenerateSummaryPage-boolean-) | Establece una bandera que indica si se debe agregar una página de resumen con estadísticas de cambios detectados al documento resultante o no. |
|
|  | [isExtendedSummaryPage()](#isExtendedSummaryPage--) | Obtiene una bandera que indica si se debe agregar información de comparación de archivos extendida a la página de resumen o no. |
|
|  | [setExtendedSummaryPage(boolean value)](#setExtendedSummaryPage-boolean-) | Establece una bandera que indica si se debe agregar información de comparación de archivos extendida a la página de resumen o no. |
|
|  | [isShowOnlySummaryPage()](#isShowOnlySummaryPage--) | Obtiene una bandera que indica si se debe dejar en el documento resultante solo una página con estadísticas de cambios detectados o no. |
|
|  | [setShowOnlySummaryPage(boolean value)](#setShowOnlySummaryPage-boolean-) | Establece una bandera que indica si se debe dejar en el documento resultante solo una página con estadísticas de cambios detectados o no. |
|
|  | [isDetectStyleChanges()](#isDetectStyleChanges--) | Obtiene una bandera que indica si se deben detectar cambios de estilo o no. |
|
|  | [setDetectStyleChanges(boolean value)](#setDetectStyleChanges-boolean-) | Establece una bandera que indica si se deben detectar cambios de estilo o no. |
|
|  | [isMarkNestedContent()](#isMarkNestedContent--) | Obtiene una bandera que indica si se deben marcar los hijos de los elementos eliminados o insertados como eliminados o insertados. |
|
|  | [setMarkNestedContent(boolean value)](#setMarkNestedContent-boolean-) | Establece una bandera que indica si se deben marcar los hijos de los elementos eliminados o insertados como eliminados o insertados. |
|
|  | [isCalculateCoordinates()](#isCalculateCoordinates--) | Obtiene una bandera que indica si se deben calcular coordenadas para los componentes modificados. |
|
|  | [setCalculateCoordinates(boolean value)](#setCalculateCoordinates-boolean-) | Establece una bandera que indica si se deben calcular coordenadas para los componentes modificados. |
|
|  | [isHeaderFootersComparison()](#isHeaderFootersComparison--) | Obtiene una bandera que indica si se deben comparar los contenidos de encabezado/pie de página. |
|
|  | [setHeaderFootersComparison(boolean value)](#setHeaderFootersComparison-boolean-) | Establece una bandera que indica si se deben comparar los contenidos de encabezado/pie de página. |
|
|  | [getDetalisationLevel()](#getDetalisationLevel--) | Obtiene un nivel de detalización de comparación representado como [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel). |
|
|  | [setDetalisationLevel(DetalisationLevel value)](#setDetalisationLevel-com.groupdocs.comparison.options.style.DetalisationLevel-) | Establece un nivel de detalización de comparación representado como [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel). |
|
|  | [isMarkChangedContent()](#isMarkChangedContent--) | Obtiene una bandera que indica si se usarán marcos para formas en procesamiento de texto y para rectángulos en documentos de imagen. |
|
|  | [setMarkChangedContent(boolean value)](#setMarkChangedContent-boolean-) | Establece una bandera que indica si se usarán marcos para formas en procesamiento de texto y para rectángulos en documentos de imagen. |
|
|  | [getInsertedItemStyle()](#getInsertedItemStyle--) | Obtiene una configuración de estilo que se aplicará a los elementos insertados. |
|
|  | [setInsertedItemStyle(StyleSettings value)](#setInsertedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-) | Establece una configuración de estilo que se aplicará a los elementos insertados. |
|
|  | [getDeletedItemStyle()](#getDeletedItemStyle--) | Obtiene una configuración de estilo que se aplicará a los elementos eliminados. |
|
|  | [setDeletedItemStyle(StyleSettings value)](#setDeletedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-) | Establece una configuración de estilo que se aplicará a los elementos eliminados. |
|
|  | [getChangedItemStyle()](#getChangedItemStyle--) | Obtiene una configuración de estilo que se aplicará a los elementos modificados. |
|
|  | [setChangedItemStyle(StyleSettings value)](#setChangedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-) | Establece una configuración de estilo que se aplicará a los elementos modificados. |
|
|  | [getSensitivityOfComparison()](#getSensitivityOfComparison--) | Obtiene una sensibilidad de comparación. |
|
|  | [setSensitivityOfComparison(int value)](#setSensitivityOfComparison-int-) | Establece una sensibilidad de comparación. |
|
|  | [setSensitivityOfComparisonForTables(Integer value)](#setSensitivityOfComparisonForTables-java.lang.Integer-) | Establece una sensibilidad de comparación para tablas. |
|
|  | [getSensitivityOfComparisonForTables()](#getSensitivityOfComparisonForTables--) | Obtiene una sensibilidad de comparación para tablas. |
|
|  | [setWordsSeparatorChars(char[] value)](#setWordsSeparatorChars-char---) | Establece una matriz de delimitadores que se utilizará para dividir el texto en palabras. |
|
|  | [getPasswordSaveOption()](#getPasswordSaveOption--) | Obtiene una opción de guardado de contraseña representada por el objeto [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption). |
|
|  | [setPasswordSaveOption(PasswordSaveOption value)](#setPasswordSaveOption-com.groupdocs.comparison.options.enums.PasswordSaveOption-) | Establece una opción de guardado de contraseña representada por el objeto [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption). |
|
|  | [getOriginalSize()](#getOriginalSize--) | Obtiene los tamaños originales de los documentos comparados representados por el objeto [OriginalSize](../../com.groupdocs.comparison.options/originalsize). |
|
|  | [setOriginalSize(OriginalSize value)](#setOriginalSize-com.groupdocs.comparison.options.OriginalSize-) | Establece los tamaños originales de los documentos comparados representados por el objeto [OriginalSize](../../com.groupdocs.comparison.options/originalsize). |
|
|  | [getDiagramMasterSetting()](#getDiagramMasterSetting--) | Obtiene una configuración de página maestra para documentos Diagram representada por el objeto [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting). |
|
|  | [setDiagramMasterSetting(DiagramMasterSetting value)](#setDiagramMasterSetting-com.groupdocs.comparison.options.style.DiagramMasterSetting-) | Establece una configuración de página maestra para documentos Diagram representada por el objeto [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting). |
|
|  | [isDirectoryCompare()](#isDirectoryCompare--) | Devuelve una bandera que indica si la comparación de directorios está habilitada. |
|
|  | [setDirectoryCompare(boolean directoryCompare)](#setDirectoryCompare-boolean-) | Establece una bandera que indica si la comparación de directorios debe estar habilitada. |
|
|  | [isShowOnlyChanged()](#isShowOnlyChanged--) | Devuelve un valor booleano que indica si solo se deben mostrar los elementos modificados. |
|
|  | [setShowOnlyChanged(boolean showOnlyChanged)](#setShowOnlyChanged-boolean-) | Establece el valor que indica si solo se deben mostrar los elementos modificados. |
|
|  | [getFolderComparisonExtension()](#getFolderComparisonExtension--) | Obtiene el formato del archivo resultante de comparación de carpetas. |
|
|  | [setFolderComparisonExtension(FolderComparisonExtension folderComparisonExtension)](#setFolderComparisonExtension-com.groupdocs.comparison.options.enums.FolderComparisonExtension-) | Establece el formato del archivo resultante de comparación de carpetas. |
|
### CompareOptions() {#CompareOptions--}
```
public CompareOptions()
```


Inicializa una nueva instancia de la clase CompareOptions.


### CompareOptions(StyleSettings insertedItemStyle, StyleSettings deletedItemStyle, StyleSettings changedItemStyle) {#CompareOptions-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-}
```
public CompareOptions(StyleSettings insertedItemStyle, StyleSettings deletedItemStyle, StyleSettings changedItemStyle)
```


Inicializa una nueva instancia de la clase CompareOptions con configuraciones para diferentes estilos.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | insertedItemStyle | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Configuración de estilo para elementos insertados |
|
|  | deletedItemStyle | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Configuración de estilo para elementos eliminados |
|
|  | changedItemStyle | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Configuración de estilo para elementos con estilo modificado |
|

### ignoreChangeSettings {#ignoreChangeSettings}
```
public IgnoreChangeSensitivitySettings ignoreChangeSettings
```


### getIgnoreChangeSettings() {#getIgnoreChangeSettings--}
```
public IgnoreChangeSensitivitySettings getIgnoreChangeSettings()
```


Obtiene la configuración para ignorar cambios basados en la similitud.


**Returns:**
com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings - Configuración para ignorar cambios.

### setIgnoreChangeSettings(IgnoreChangeSensitivitySettings ignoreChangeSettings) {#setIgnoreChangeSettings-com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings-}
```
public void setIgnoreChangeSettings(IgnoreChangeSensitivitySettings ignoreChangeSettings)
```


Establece la configuración para ignorar cambios basados en la similitud.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | ignoreChangeSettings | com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings | Configuración para ignorar cambios. |
|

### getUserMasterPath() {#getUserMasterPath--}
```
public String getUserMasterPath()
```


Obtiene la ruta a la plantilla maestra del usuario para Diagramas.


**Returns:**
java.lang.String - La ruta a la plantilla maestra del usuario para Diagramas.

### setUserMasterPath(String userMasterPath) {#setUserMasterPath-java.lang.String-}
```
public void setUserMasterPath(String userMasterPath)
```


Establece la ruta a la plantilla maestra del usuario para Diagramas.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | userMasterPath | java.lang.String | La ruta a la plantilla maestra del usuario para Diagramas. |
|

### getComparisonType() {#getComparisonType--}
```
public ComparisonType getComparisonType()
```


Obtiene un tipo de documentos origen y destino como objeto [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) para que Comparison sepa cómo compararlos.
Cuando se establece esta opción, la opción [LoadOptions.getFileType()](../../com.groupdocs.comparison.options.load/loadoptions#getFileType--) será omitida.


**Returns:**
[ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) - the type of source and target documents

### setComparisonType(ComparisonType comparisonType) {#setComparisonType-com.groupdocs.comparison.options.enums.ComparisonType-}
```
public void setComparisonType(ComparisonType comparisonType)
```


Establece un tipo de documentos origen y destino como objeto [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) para que Comparison sepa cómo compararlos.
Cuando se establece esta opción, la opción [LoadOptions.setFileType(FileType)](../../com.groupdocs.comparison.options.load/loadoptions#setFileType-FileType-) será omitida.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | comparisonType | [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) | El tipo de documentos de origen y destino |
|

### getPaperSize() {#getPaperSize--}
```
public final PaperSize getPaperSize()
```


Obtiene un tamaño de papel en el documento resultante como objeto [PaperSize](../../com.groupdocs.comparison.options.enums/papersize).


**Returns:**
[PaperSize](../../com.groupdocs.comparison.options.enums/papersize) - the size of a paper in result document

### setPaperSize(PaperSize value) {#setPaperSize-com.groupdocs.comparison.options.enums.PaperSize-}
```
public final void setPaperSize(PaperSize value)
```


Establece un tamaño de papel en el documento resultante como objeto [PaperSize](../../com.groupdocs.comparison.options.enums/papersize).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [PaperSize](../../com.groupdocs.comparison.options.enums/papersize) | El tamaño de una hoja en el documento resultante |
|

### getCalculateCoordinatesMode() {#getCalculateCoordinatesMode--}
```
public CalculateCoordinatesModeEnumeration getCalculateCoordinatesMode()
```


Obtiene un modo de cálculo de coordenadas como objeto [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration).


**Returns:**
[CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) - the calculate coordinates mode

### setCalculateCoordinatesMode(CalculateCoordinatesModeEnumeration calculateCoordinatesMode) {#setCalculateCoordinatesMode-com.groupdocs.comparison.options.enums.CalculateCoordinatesModeEnumeration-}
```
public void setCalculateCoordinatesMode(CalculateCoordinatesModeEnumeration calculateCoordinatesMode)
```


Establece un modo de cálculo de coordenadas como objeto [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | calculateCoordinatesMode | [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) | El modo de cálculo de coordenadas |
|

### isShowDeletedContent() {#isShowDeletedContent--}
```
public final boolean isShowDeletedContent()
```


Obtiene una bandera que indica si se deben mostrar los componentes eliminados en el documento resultante o no.


**Returns:**
boolean - true si los componentes eliminados en el documento resultante se mostrarán, de lo contrario false

### setShowDeletedContent(boolean value) {#setShowDeletedContent-boolean-}
```
public final void setShowDeletedContent(boolean value)
```


Establece una bandera que indica si se deben mostrar los componentes eliminados en el documento resultante o no.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | true si los componentes eliminados en el documento resultante deben mostrarse, de lo contrario false |
|

### isShowInsertedContent() {#isShowInsertedContent--}
```
public final boolean isShowInsertedContent()
```


Obtiene una bandera que indica si se deben mostrar los componentes insertados en el documento resultante o no.


**Returns:**
boolean - true si los componentes insertados en el documento resultante deben mostrarse, de lo contrario false

### setShowInsertedContent(boolean value) {#setShowInsertedContent-boolean-}
```
public final void setShowInsertedContent(boolean value)
```


Establece una bandera que indica si se deben mostrar los componentes insertados en el documento resultante o no.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | true si los componentes insertados en el documento resultante deben mostrarse, de lo contrario false |
|

### isGenerateSummaryPage() {#isGenerateSummaryPage--}
```
public final boolean isGenerateSummaryPage()
```


Obtiene una bandera que indica si se debe agregar una página de resumen con estadísticas de cambios detectados al documento resultante o no.


**Returns:**
boolean - true si se añadirá la página de resumen, de lo contrario false

### setGenerateSummaryPage(boolean value) {#setGenerateSummaryPage-boolean-}
```
public final void setGenerateSummaryPage(boolean value)
```


Establece una bandera que indica si se debe agregar una página de resumen con estadísticas de cambios detectados al documento resultante o no.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | true si la página de resumen debe añadirse, de lo contrario false |
|

### isExtendedSummaryPage() {#isExtendedSummaryPage--}
```
public boolean isExtendedSummaryPage()
```


Obtiene una bandera que indica si se debe agregar información de comparación de archivos extendida a la página de resumen o no.


**Returns:**
boolean - true si la información extendida de comparación de archivos se añadirá a la página de resumen, de lo contrario false

### setExtendedSummaryPage(boolean value) {#setExtendedSummaryPage-boolean-}
```
public void setExtendedSummaryPage(boolean value)
```


Establece una bandera que indica si se debe agregar información de comparación de archivos extendida a la página de resumen o no.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | true si la información extendida de comparación de archivos debe añadirse a la página de resumen, de lo contrario false |
|

### isShowOnlySummaryPage() {#isShowOnlySummaryPage--}
```
public boolean isShowOnlySummaryPage()
```


Obtiene una bandera que indica si se debe dejar en el documento resultante solo una página con estadísticas de cambios detectados o no.


**Returns:**
boolean - true si en el documento resultante solo quedará una página con estadísticas de los cambios detectados, de lo contrario false

### setShowOnlySummaryPage(boolean value) {#setShowOnlySummaryPage-boolean-}
```
public void setShowOnlySummaryPage(boolean value)
```


Establece una bandera que indica si se debe dejar en el documento resultante solo una página con estadísticas de cambios detectados o no.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | true si en el documento resultante solo debe quedar una página con estadísticas de los cambios detectados, de lo contrario false |
|

### isDetectStyleChanges() {#isDetectStyleChanges--}
```
public final boolean isDetectStyleChanges()
```


Obtiene una bandera que indica si se deben detectar cambios de estilo o no.


**Returns:**
boolean - true si se detectarán cambios de estilo, de lo contrario false

### setDetectStyleChanges(boolean value) {#setDetectStyleChanges-boolean-}
```
public final void setDetectStyleChanges(boolean value)
```


Establece una bandera que indica si se deben detectar cambios de estilo o no.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | true si los cambios de estilo deben detectarse, de lo contrario false |
|

### isMarkNestedContent() {#isMarkNestedContent--}
```
public final boolean isMarkNestedContent()
```


Obtiene una bandera que indica si se deben marcar los hijos de los elementos eliminados o insertados como eliminados o insertados.


**Returns:**
boolean - true si los hijos de los elementos eliminados o insertados serán marcados como eliminados o insertados, de lo contrario false

### setMarkNestedContent(boolean value) {#setMarkNestedContent-boolean-}
```
public final void setMarkNestedContent(boolean value)
```


Establece una bandera que indica si se deben marcar los hijos de los elementos eliminados o insertados como eliminados o insertados.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | true si los hijos de los elementos eliminados o insertados deben marcarse como eliminados o insertados, de lo contrario false |
|

### isCalculateCoordinates() {#isCalculateCoordinates--}
```
public final boolean isCalculateCoordinates()
```


Obtiene una bandera que indica si se deben calcular coordenadas para los componentes modificados.


**Returns:**
boolean - true si se calcularán las coordenadas de los componentes modificados, de lo contrario false

### setCalculateCoordinates(boolean value) {#setCalculateCoordinates-boolean-}
```
public final void setCalculateCoordinates(boolean value)
```


Establece una bandera que indica si se deben calcular coordenadas para los componentes modificados.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | true si las coordenadas de los componentes modificados deben calcularse, de lo contrario false |
|

### isHeaderFootersComparison() {#isHeaderFootersComparison--}
```
public final boolean isHeaderFootersComparison()
```


Obtiene una bandera que indica si se deben comparar los contenidos de encabezado/pie de página.


**Returns:**
boolean - true si los contenidos de encabezado/pie de página serán comparados, de lo contrario false

### setHeaderFootersComparison(boolean value) {#setHeaderFootersComparison-boolean-}
```
public final void setHeaderFootersComparison(boolean value)
```


Establece una bandera que indica si se deben comparar los contenidos de encabezado/pie de página.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | true si el contenido de encabezado/pie de página debe compararse, de lo contrario false |
|

### getDetalisationLevel() {#getDetalisationLevel--}
```
public final DetalisationLevel getDetalisationLevel()
```


Obtiene un nivel de detalización de comparación representado como [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel).
El valor predeterminado es [DetalisationLevel.LOW](../../com.groupdocs.comparison.options.style/detalisationlevel#LOW).


**Returns:**
[DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) - the level of comparison detalization

### setDetalisationLevel(DetalisationLevel value) {#setDetalisationLevel-com.groupdocs.comparison.options.style.DetalisationLevel-}
```
public final void setDetalisationLevel(DetalisationLevel value)
```


Establece un nivel de detalización de comparación representado como [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel).
El valor predeterminado es [DetalisationLevel.LOW](../../com.groupdocs.comparison.options.style/detalisationlevel#LOW)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) | El nivel de detalización de la comparación |
|

### isMarkChangedContent() {#isMarkChangedContent--}
```
public final boolean isMarkChangedContent()
```


Obtiene una bandera que indica si se usarán marcos para formas en procesamiento de texto y para rectángulos en documentos de imagen.


**Returns:**
boolean - true si se usarán marcos, de lo contrario false

### setMarkChangedContent(boolean value) {#setMarkChangedContent-boolean-}
```
public final void setMarkChangedContent(boolean value)
```


Establece una bandera que indica si se usarán marcos para formas en procesamiento de texto y para rectángulos en documentos de imagen.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | true si se deben usar marcos, de lo contrario false |
|

### getInsertedItemStyle() {#getInsertedItemStyle--}
```
public final StyleSettings getInsertedItemStyle()
```


Obtiene una configuración de estilo que se aplicará a los elementos insertados.


**Returns:**
[StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) - style settings of inserted items

### setInsertedItemStyle(StyleSettings value) {#setInsertedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-}
```
public final void setInsertedItemStyle(StyleSettings value)
```


Establece una configuración de estilo que se aplicará a los elementos insertados.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Configuración de estilo de los elementos insertados |
|

### getDeletedItemStyle() {#getDeletedItemStyle--}
```
public final StyleSettings getDeletedItemStyle()
```


Obtiene una configuración de estilo que se aplicará a los elementos eliminados.


**Returns:**
[StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) - style settings of deleted items

### setDeletedItemStyle(StyleSettings value) {#setDeletedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-}
```
public final void setDeletedItemStyle(StyleSettings value)
```


Establece una configuración de estilo que se aplicará a los elementos eliminados.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Configuración de estilo de los elementos eliminados |
|

### getChangedItemStyle() {#getChangedItemStyle--}
```
public final StyleSettings getChangedItemStyle()
```


Obtiene una configuración de estilo que se aplicará a los elementos modificados.


**Returns:**
[StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) - style settings of changed items

### setChangedItemStyle(StyleSettings value) {#setChangedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-}
```
public final void setChangedItemStyle(StyleSettings value)
```


Establece una configuración de estilo que se aplicará a los elementos modificados.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Configuración de estilo de los elementos modificados |
|

### getSensitivityOfComparison() {#getSensitivityOfComparison--}
```
public final int getSensitivityOfComparison()
```


Obtiene una sensibilidad de comparación.
El porcentaje de elementos eliminados e insertados de dos objetos comparados en relación con todos los elementos de estos objetos.

* If this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Returns:**
int - la sensibilidad de la comparación

### setSensitivityOfComparison(int value) {#setSensitivityOfComparison-int-}
```
public final void setSensitivityOfComparison(int value)
```


Establece una sensibilidad de comparación.
El porcentaje de elementos eliminados e insertados de dos objetos comparados en relación con todos los elementos de estos objetos.

* If this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int | La sensibilidad de la comparación |
|

### setSensitivityOfComparisonForTables(Integer value) {#setSensitivityOfComparisonForTables-java.lang.Integer-}
```
public void setSensitivityOfComparisonForTables(Integer value)
```


Establece una sensibilidad de comparación para tablas.
Si el valor es null, se utiliza SensitivityOfComparison en su lugar. El porcentaje de elementos eliminados e insertados de dos objetos comparados en relación con todos los elementos de estos objetos.

* if this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs, if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.Integer | La sensibilidad de la comparación para tablas |
|

### getSensitivityOfComparisonForTables() {#getSensitivityOfComparisonForTables--}
```
public final Integer getSensitivityOfComparisonForTables()
```


Obtiene una sensibilidad de comparación para tablas.
Si el valor es null, se utiliza SensitivityOfComparison en su lugar. El porcentaje de elementos eliminados e insertados de dos objetos comparados en relación con todos los elementos de estos objetos.

* if this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs, if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Returns:**
java.lang.Integer - La sensibilidad de la comparación para tablas

### setWordsSeparatorChars(char[] value) {#setWordsSeparatorChars-char---}
```
public final void setWordsSeparatorChars(char[] value)
```


Establece una matriz de delimitadores que se utilizará para dividir el texto en palabras.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | char[] | La matriz de delimitadores para dividir el texto en palabras |
|

### getPasswordSaveOption() {#getPasswordSaveOption--}
```
public final PasswordSaveOption getPasswordSaveOption()
```


Obtiene una opción de guardado de contraseña representada por el objeto [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption).


**Returns:**
[PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) - the password save option

### setPasswordSaveOption(PasswordSaveOption value) {#setPasswordSaveOption-com.groupdocs.comparison.options.enums.PasswordSaveOption-}
```
public final void setPasswordSaveOption(PasswordSaveOption value)
```


Establece una opción de guardado de contraseña representada por el objeto [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) | La opción de guardado de contraseña |
|

### getOriginalSize() {#getOriginalSize--}
```
public final OriginalSize getOriginalSize()
```


Obtiene los tamaños originales de los documentos comparados representados por el objeto [OriginalSize](../../com.groupdocs.comparison.options/originalsize).


**Returns:**
[OriginalSize](../../com.groupdocs.comparison.options/originalsize) - the original size of documents

### setOriginalSize(OriginalSize value) {#setOriginalSize-com.groupdocs.comparison.options.OriginalSize-}
```
public final void setOriginalSize(OriginalSize value)
```


Establece los tamaños originales de los documentos comparados representados por el objeto [OriginalSize](../../com.groupdocs.comparison.options/originalsize).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [OriginalSize](../../com.groupdocs.comparison.options/originalsize) | El tamaño original de los documentos |
|

### getDiagramMasterSetting() {#getDiagramMasterSetting--}
```
public final DiagramMasterSetting getDiagramMasterSetting()
```


Obtiene una configuración de página maestra para documentos Diagram representada por el objeto [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting).


**Returns:**
[DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) - the diagram master page setting

### setDiagramMasterSetting(DiagramMasterSetting value) {#setDiagramMasterSetting-com.groupdocs.comparison.options.style.DiagramMasterSetting-}
```
public final void setDiagramMasterSetting(DiagramMasterSetting value)
```


Establece una configuración de página maestra para documentos Diagram representada por el objeto [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) | La configuración de la página maestra del diagrama |
|

### isDirectoryCompare() {#isDirectoryCompare--}
```
public boolean isDirectoryCompare()
```


Devuelve una bandera que indica si la comparación de directorios está habilitada.


**Returns:**
boolean - true si la comparación de directorios está habilitada, de lo contrario false

### setDirectoryCompare(boolean directoryCompare) {#setDirectoryCompare-boolean-}
```
public void setDirectoryCompare(boolean directoryCompare)
```


Establece una bandera que indica si la comparación de directorios debe estar habilitada.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | directoryCompare | boolean | true si la comparación de directorios debe estar habilitada, de lo contrario false |
|

### isShowOnlyChanged() {#isShowOnlyChanged--}
```
public boolean isShowOnlyChanged()
```


Devuelve un valor booleano que indica si solo se deben mostrar los elementos modificados.


**Returns:**
boolean - true si solo los elementos modificados deben mostrarse, de lo contrario false

### setShowOnlyChanged(boolean showOnlyChanged) {#setShowOnlyChanged-boolean-}
```
public void setShowOnlyChanged(boolean showOnlyChanged)
```


Establece el valor que indica si solo se deben mostrar los elementos modificados.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | showOnlyChanged | boolean | el valor booleano que indica si solo los elementos modificados deben mostrarse |
|

### getFolderComparisonExtension() {#getFolderComparisonExtension--}
```
public FolderComparisonExtension getFolderComparisonExtension()
```


Obtiene el formato del archivo resultante de comparación de carpetas.


**Returns:**
com.groupdocs.comparison.options.enums.FolderComparisonExtension - la FolderComparisonExtension que representa el formato del archivo de comparación de carpetas resultante

### setFolderComparisonExtension(FolderComparisonExtension folderComparisonExtension) {#setFolderComparisonExtension-com.groupdocs.comparison.options.enums.FolderComparisonExtension-}
```
public void setFolderComparisonExtension(FolderComparisonExtension folderComparisonExtension)
```


Establece el formato del archivo resultante de comparación de carpetas.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | folderComparisonExtension | com.groupdocs.comparison.options.enums.FolderComparisonExtension | la FolderComparisonExtension que representa el formato del archivo de comparación de carpetas resultante |
|

