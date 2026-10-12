---
title: "CompareOptions"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "Позволяет настраивать процесс сравнения документов."
type: docs
weight: 11
url: /ru/java/com.groupdocs.comparison.options/compareoptions/
---
**Inheritance:**
java.lang.Object
```
public class CompareOptions
```

Позволяет настраивать процесс сравнения документов.


Пример использования:

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


## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [CompareOptions()](#CompareOptions--) | Инициализирует новый экземпляр класса CompareOptions. |
|
|  | [CompareOptions(StyleSettings insertedItemStyle, StyleSettings deletedItemStyle, StyleSettings changedItemStyle)](#CompareOptions-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-) | Инициализирует новый экземпляр класса CompareOptions с настройками для разных стилей. |
|
## Поля

| Поле | Описание |
| --- | --- |
| [ignoreChangeSettings](#ignoreChangeSettings) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getIgnoreChangeSettings()](#getIgnoreChangeSettings--) | Получить настройки для игнорирования изменений на основе сходства. |
|
|  | [setIgnoreChangeSettings(IgnoreChangeSensitivitySettings ignoreChangeSettings)](#setIgnoreChangeSettings-com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings-) | Устанавливает настройки для игнорирования изменений на основе сходства. |
|
|  | [getUserMasterPath()](#getUserMasterPath--) | Получает путь к шаблону мастера пользователя для Диаграмм. |
|
|  | [setUserMasterPath(String userMasterPath)](#setUserMasterPath-java.lang.String-) | Устанавливает путь к шаблону мастера пользователя для Диаграмм. |
|
|  | [getComparisonType()](#getComparisonType--) | Получает тип исходных и целевых документов как объект [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype), чтобы Comparison знал, как их сравнивать. |
|
|  | [setComparisonType(ComparisonType comparisonType)](#setComparisonType-com.groupdocs.comparison.options.enums.ComparisonType-) | Устанавливает тип исходных и целевых документов как объект [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype), чтобы Comparison знал, как их сравнивать. |
|
|  | [getPaperSize()](#getPaperSize--) | Получает размер бумаги в результирующем документе как объект [PaperSize](../../com.groupdocs.comparison.options.enums/papersize). |
|
|  | [setPaperSize(PaperSize value)](#setPaperSize-com.groupdocs.comparison.options.enums.PaperSize-) | Устанавливает размер бумаги в результирующем документе как объект [PaperSize](../../com.groupdocs.comparison.options.enums/papersize). |
|
|  | [getCalculateCoordinatesMode()](#getCalculateCoordinatesMode--) | Получает режим вычисления координат как объект [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration). |
|
|  | [setCalculateCoordinatesMode(CalculateCoordinatesModeEnumeration calculateCoordinatesMode)](#setCalculateCoordinatesMode-com.groupdocs.comparison.options.enums.CalculateCoordinatesModeEnumeration-) | Устанавливает режим вычисления координат как объект [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration). |
|
|  | [isShowDeletedContent()](#isShowDeletedContent--) | Получает флаг, указывающий, показывать ли удалённые компоненты в результирующем документе. |
|
|  | [setShowDeletedContent(boolean value)](#setShowDeletedContent-boolean-) | Устанавливает флаг, указывающий, показывать ли удалённые компоненты в результирующем документе. |
|
|  | [isShowInsertedContent()](#isShowInsertedContent--) | Получает флаг, указывающий, показывать ли вставленные компоненты в результирующем документе или нет. |
|
|  | [setShowInsertedContent(boolean value)](#setShowInsertedContent-boolean-) | Устанавливает флаг, указывающий, показывать ли вставленные компоненты в результирующем документе или нет. |
|
|  | [isGenerateSummaryPage()](#isGenerateSummaryPage--) | Получает флаг, указывающий, добавлять ли страницу сводки со статистикой обнаруженных изменений в результирующий документ или нет. |
|
|  | [setGenerateSummaryPage(boolean value)](#setGenerateSummaryPage-boolean-) | Устанавливает флаг, указывающий, добавлять ли страницу сводки со статистикой обнаруженных изменений в результирующий документ или нет. |
|
|  | [isExtendedSummaryPage()](#isExtendedSummaryPage--) | Получает флаг, указывающий, добавлять ли расширенную информацию о сравнении файлов на страницу сводки или нет. |
|
|  | [setExtendedSummaryPage(boolean value)](#setExtendedSummaryPage-boolean-) | Устанавливает флаг, указывающий, добавлять ли расширенную информацию о сравнении файлов на страницу сводки или нет. |
|
|  | [isShowOnlySummaryPage()](#isShowOnlySummaryPage--) | Получает флаг, указывающий, оставлять ли в результирующем документе только страницу со статистикой обнаруженных изменений или нет. |
|
|  | [setShowOnlySummaryPage(boolean value)](#setShowOnlySummaryPage-boolean-) | Устанавливает флаг, указывающий, оставлять ли в результирующем документе только страницу со статистикой обнаруженных изменений или нет. |
|
|  | [isDetectStyleChanges()](#isDetectStyleChanges--) | Получает флаг, указывающий, обнаруживать ли изменения стиля или нет. |
|
|  | [setDetectStyleChanges(boolean value)](#setDetectStyleChanges-boolean-) | Устанавливает флаг, указывающий, обнаруживать ли изменения стиля или нет. |
|
|  | [isMarkNestedContent()](#isMarkNestedContent--) | Получает флаг, указывающий, помечать ли дочерние элементы удалённых или вставленных элементов как удалённые или вставленные. |
|
|  | [setMarkNestedContent(boolean value)](#setMarkNestedContent-boolean-) | Устанавливает флаг, указывающий, помечать ли дочерние элементы удалённых или вставленных элементов как удалённые или вставленные. |
|
|  | [isCalculateCoordinates()](#isCalculateCoordinates--) | Получает флаг, указывающий, вычислять ли координаты изменённых компонентов. |
|
|  | [setCalculateCoordinates(boolean value)](#setCalculateCoordinates-boolean-) | Устанавливает флаг, указывающий, вычислять ли координаты изменённых компонентов. |
|
|  | [isHeaderFootersComparison()](#isHeaderFootersComparison--) | Получает флаг, указывающий, сравнивать ли содержимое верхнего/нижнего колонтитула. |
|
|  | [setHeaderFootersComparison(boolean value)](#setHeaderFootersComparison-boolean-) | Устанавливает флаг, указывающий, сравнивать ли содержимое верхнего/нижнего колонтитула. |
|
|  | [getDetalisationLevel()](#getDetalisationLevel--) | Получает уровень детализации сравнения, представленный как [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel). |
|
|  | [setDetalisationLevel(DetalisationLevel value)](#setDetalisationLevel-com.groupdocs.comparison.options.style.DetalisationLevel-) | Устанавливает уровень детализации сравнения, представленный как [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel). |
|
|  | [isMarkChangedContent()](#isMarkChangedContent--) | Получает флаг, указывающий, будут ли использоваться рамки для фигур в обработке Word и для прямоугольников в документах Image. |
|
|  | [setMarkChangedContent(boolean value)](#setMarkChangedContent-boolean-) | Устанавливает флаг, указывающий, будут ли использоваться рамки для фигур в обработке Word и для прямоугольников в документах Image. |
|
|  | [getInsertedItemStyle()](#getInsertedItemStyle--) | Получает настройки стиля, которые будут применяться к вставленным элементам. |
|
|  | [setInsertedItemStyle(StyleSettings value)](#setInsertedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-) | Устанавливает настройки стиля, которые будут применяться к вставленным элементам. |
|
|  | [getDeletedItemStyle()](#getDeletedItemStyle--) | Получает настройки стиля, которые будут применяться к удалённым элементам. |
|
|  | [setDeletedItemStyle(StyleSettings value)](#setDeletedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-) | Устанавливает настройки стиля, которые будут применяться к удалённым элементам. |
|
|  | [getChangedItemStyle()](#getChangedItemStyle--) | Получает настройки стиля, которые будут применяться к изменённым элементам. |
|
|  | [setChangedItemStyle(StyleSettings value)](#setChangedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-) | Устанавливает настройки стиля, которые будут применяться к изменённым элементам. |
|
|  | [getSensitivityOfComparison()](#getSensitivityOfComparison--) | Получает чувствительность сравнения. |
|
|  | [setSensitivityOfComparison(int value)](#setSensitivityOfComparison-int-) | Устанавливает чувствительность сравнения. |
|
|  | [setSensitivityOfComparisonForTables(Integer value)](#setSensitivityOfComparisonForTables-java.lang.Integer-) | Устанавливает чувствительность сравнения для таблиц. |
|
|  | [getSensitivityOfComparisonForTables()](#getSensitivityOfComparisonForTables--) | Получает чувствительность сравнения для таблиц. |
|
|  | [setWordsSeparatorChars(char[] value)](#setWordsSeparatorChars-char---) | Устанавливает массив разделителей, которые будут использоваться для разбиения текста на слова. |
|
|  | [getPasswordSaveOption()](#getPasswordSaveOption--) | Получает параметр сохранения пароля, представленный объектом [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption). |
|
|  | [setPasswordSaveOption(PasswordSaveOption value)](#setPasswordSaveOption-com.groupdocs.comparison.options.enums.PasswordSaveOption-) | Устанавливает параметр сохранения пароля, представленный объектом [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption). |
|
|  | [getOriginalSize()](#getOriginalSize--) | Получает оригинальные размеры сравниваемых документов, представленные объектом [OriginalSize](../../com.groupdocs.comparison.options/originalsize). |
|
|  | [setOriginalSize(OriginalSize value)](#setOriginalSize-com.groupdocs.comparison.options.OriginalSize-) | Устанавливает оригинальные размеры сравниваемых документов, представленные объектом [OriginalSize](../../com.groupdocs.comparison.options/originalsize). |
|
|  | [getDiagramMasterSetting()](#getDiagramMasterSetting--) | Получает настройку главной страницы для документов Diagram, представленную объектом [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting). |
|
|  | [setDiagramMasterSetting(DiagramMasterSetting value)](#setDiagramMasterSetting-com.groupdocs.comparison.options.style.DiagramMasterSetting-) | Устанавливает настройку главной страницы для документов Diagram, представленную объектом [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting). |
|
|  | [isDirectoryCompare()](#isDirectoryCompare--) | Возвращает флаг, указывающий, включено ли сравнение каталогов. |
|
|  | [setDirectoryCompare(boolean directoryCompare)](#setDirectoryCompare-boolean-) | Устанавливает флаг, указывающий, должно ли быть включено сравнение каталогов. |
|
|  | [isShowOnlyChanged()](#isShowOnlyChanged--) | Возвращает логическое значение, указывающее, должны ли отображаться только изменённые элементы. |
|
|  | [setShowOnlyChanged(boolean showOnlyChanged)](#setShowOnlyChanged-boolean-) | Устанавливает значение, указывающее, должны ли отображаться только изменённые элементы. |
|
|  | [getFolderComparisonExtension()](#getFolderComparisonExtension--) | Получает формат результирующего файла сравнения папок. |
|
|  | [setFolderComparisonExtension(FolderComparisonExtension folderComparisonExtension)](#setFolderComparisonExtension-com.groupdocs.comparison.options.enums.FolderComparisonExtension-) | Устанавливает формат результирующего файла сравнения папок. |
|
### CompareOptions() {#CompareOptions--}
```
public CompareOptions()
```


Инициализирует новый экземпляр класса CompareOptions.


### CompareOptions(StyleSettings insertedItemStyle, StyleSettings deletedItemStyle, StyleSettings changedItemStyle) {#CompareOptions-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-}
```
public CompareOptions(StyleSettings insertedItemStyle, StyleSettings deletedItemStyle, StyleSettings changedItemStyle)
```


Инициализирует новый экземпляр класса CompareOptions с настройками для разных стилей.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | insertedItemStyle | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Настройки стиля для вставленных элементов |
|
|  | deletedItemStyle | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Настройки стиля для удалённых элементов |
|
|  | changedItemStyle | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Настройки стиля для изменённых элементов стиля |
|

### ignoreChangeSettings {#ignoreChangeSettings}
```
public IgnoreChangeSensitivitySettings ignoreChangeSettings
```


### getIgnoreChangeSettings() {#getIgnoreChangeSettings--}
```
public IgnoreChangeSensitivitySettings getIgnoreChangeSettings()
```


Получить настройки для игнорирования изменений на основе сходства.


**Returns:**
com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings - Настройки для игнорирования изменений.

### setIgnoreChangeSettings(IgnoreChangeSensitivitySettings ignoreChangeSettings) {#setIgnoreChangeSettings-com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings-}
```
public void setIgnoreChangeSettings(IgnoreChangeSensitivitySettings ignoreChangeSettings)
```


Устанавливает настройки для игнорирования изменений на основе сходства.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | ignoreChangeSettings | com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings | Настройки для игнорирования изменений. |
|

### getUserMasterPath() {#getUserMasterPath--}
```
public String getUserMasterPath()
```


Получает путь к шаблону мастера пользователя для Диаграмм.


**Returns:**
java.lang.String - Путь к шаблону мастера пользователя для диаграмм.

### setUserMasterPath(String userMasterPath) {#setUserMasterPath-java.lang.String-}
```
public void setUserMasterPath(String userMasterPath)
```


Устанавливает путь к шаблону мастера пользователя для Диаграмм.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | userMasterPath | java.lang.String | Путь к шаблону мастера пользователя для диаграмм. |
|

### getComparisonType() {#getComparisonType--}
```
public ComparisonType getComparisonType()
```


Получает тип исходных и целевых документов как объект [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype), чтобы Comparison знал, как их сравнивать.
Когда эта опция установлена, [LoadOptions.getFileType()](../../com.groupdocs.comparison.options.load/loadoptions#getFileType--) опция будет опущена.


**Returns:**
[ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) - the type of source and target documents

### setComparisonType(ComparisonType comparisonType) {#setComparisonType-com.groupdocs.comparison.options.enums.ComparisonType-}
```
public void setComparisonType(ComparisonType comparisonType)
```


Устанавливает тип исходных и целевых документов как объект [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype), чтобы Comparison знал, как их сравнивать.
Когда эта опция установлена, [LoadOptions.setFileType(FileType)](../../com.groupdocs.comparison.options.load/loadoptions#setFileType-FileType-) опция будет опущена.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | comparisonType | [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) | Тип исходного и целевого документов |
|

### getPaperSize() {#getPaperSize--}
```
public final PaperSize getPaperSize()
```


Получает размер бумаги в результирующем документе как объект [PaperSize](../../com.groupdocs.comparison.options.enums/papersize).


**Returns:**
[PaperSize](../../com.groupdocs.comparison.options.enums/papersize) - the size of a paper in result document

### setPaperSize(PaperSize value) {#setPaperSize-com.groupdocs.comparison.options.enums.PaperSize-}
```
public final void setPaperSize(PaperSize value)
```


Устанавливает размер бумаги в результирующем документе как объект [PaperSize](../../com.groupdocs.comparison.options.enums/papersize).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | [PaperSize](../../com.groupdocs.comparison.options.enums/papersize) | Размер листа в результирующем документе |
|

### getCalculateCoordinatesMode() {#getCalculateCoordinatesMode--}
```
public CalculateCoordinatesModeEnumeration getCalculateCoordinatesMode()
```


Получает режим вычисления координат как объект [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration).


**Returns:**
[CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) - the calculate coordinates mode

### setCalculateCoordinatesMode(CalculateCoordinatesModeEnumeration calculateCoordinatesMode) {#setCalculateCoordinatesMode-com.groupdocs.comparison.options.enums.CalculateCoordinatesModeEnumeration-}
```
public void setCalculateCoordinatesMode(CalculateCoordinatesModeEnumeration calculateCoordinatesMode)
```


Устанавливает режим вычисления координат как объект [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | calculateCoordinatesMode | [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) | Режим вычисления координат |
|

### isShowDeletedContent() {#isShowDeletedContent--}
```
public final boolean isShowDeletedContent()
```


Получает флаг, указывающий, показывать ли удалённые компоненты в результирующем документе.


**Returns:**
boolean - true если удалённые компоненты в результирующем документе будут отображаться, иначе false

### setShowDeletedContent(boolean value) {#setShowDeletedContent-boolean-}
```
public final void setShowDeletedContent(boolean value)
```


Устанавливает флаг, указывающий, показывать ли удалённые компоненты в результирующем документе.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | boolean | true если удалённые компоненты в результирующем документе должны отображаться, иначе false |
|

### isShowInsertedContent() {#isShowInsertedContent--}
```
public final boolean isShowInsertedContent()
```


Получает флаг, указывающий, показывать ли вставленные компоненты в результирующем документе или нет.


**Returns:**
boolean - true если вставленные компоненты в результирующем документе должны отображаться, иначе false

### setShowInsertedContent(boolean value) {#setShowInsertedContent-boolean-}
```
public final void setShowInsertedContent(boolean value)
```


Устанавливает флаг, указывающий, показывать ли вставленные компоненты в результирующем документе или нет.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | boolean | true если вставленные компоненты в результирующем документе должны отображаться, иначе false |
|

### isGenerateSummaryPage() {#isGenerateSummaryPage--}
```
public final boolean isGenerateSummaryPage()
```


Получает флаг, указывающий, добавлять ли страницу сводки со статистикой обнаруженных изменений в результирующий документ или нет.


**Returns:**
boolean - true если будет добавлена сводная страница, иначе false

### setGenerateSummaryPage(boolean value) {#setGenerateSummaryPage-boolean-}
```
public final void setGenerateSummaryPage(boolean value)
```


Устанавливает флаг, указывающий, добавлять ли страницу сводки со статистикой обнаруженных изменений в результирующий документ или нет.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | boolean | true если сводная страница должна быть добавлена, иначе false |
|

### isExtendedSummaryPage() {#isExtendedSummaryPage--}
```
public boolean isExtendedSummaryPage()
```


Получает флаг, указывающий, добавлять ли расширенную информацию о сравнении файлов на страницу сводки или нет.


**Returns:**
boolean - true если расширенная информация сравнения файлов будет добавлена к сводной странице, иначе false

### setExtendedSummaryPage(boolean value) {#setExtendedSummaryPage-boolean-}
```
public void setExtendedSummaryPage(boolean value)
```


Устанавливает флаг, указывающий, добавлять ли расширенную информацию о сравнении файлов на страницу сводки или нет.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | boolean | true если расширенная информация сравнения файлов должна быть добавлена к сводной странице, иначе false |
|

### isShowOnlySummaryPage() {#isShowOnlySummaryPage--}
```
public boolean isShowOnlySummaryPage()
```


Получает флаг, указывающий, оставлять ли в результирующем документе только страницу со статистикой обнаруженных изменений или нет.


**Returns:**
boolean - true если в результирующем документе останется только страница со статистикой обнаруженных изменений, иначе false

### setShowOnlySummaryPage(boolean value) {#setShowOnlySummaryPage-boolean-}
```
public void setShowOnlySummaryPage(boolean value)
```


Устанавливает флаг, указывающий, оставлять ли в результирующем документе только страницу со статистикой обнаруженных изменений или нет.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | boolean | true если в результирующем документе должна остаться только страница со статистикой обнаруженных изменений, иначе false |
|

### isDetectStyleChanges() {#isDetectStyleChanges--}
```
public final boolean isDetectStyleChanges()
```


Получает флаг, указывающий, обнаруживать ли изменения стиля или нет.


**Returns:**
boolean - true если будут обнаружены изменения стиля, иначе false

### setDetectStyleChanges(boolean value) {#setDetectStyleChanges-boolean-}
```
public final void setDetectStyleChanges(boolean value)
```


Устанавливает флаг, указывающий, обнаруживать ли изменения стиля или нет.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | boolean | true если изменения стиля должны быть обнаружены, иначе false |
|

### isMarkNestedContent() {#isMarkNestedContent--}
```
public final boolean isMarkNestedContent()
```


Получает флаг, указывающий, помечать ли дочерние элементы удалённых или вставленных элементов как удалённые или вставленные.


**Returns:**
boolean - true если дочерние элементы удалённых или вставленных элементов будут помечены как удалённые или вставленные, иначе false

### setMarkNestedContent(boolean value) {#setMarkNestedContent-boolean-}
```
public final void setMarkNestedContent(boolean value)
```


Устанавливает флаг, указывающий, помечать ли дочерние элементы удалённых или вставленных элементов как удалённые или вставленные.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | boolean | true если дочерние элементы удалённых или вставленных элементов должны быть помечены как удалённые или вставленные, иначе false |
|

### isCalculateCoordinates() {#isCalculateCoordinates--}
```
public final boolean isCalculateCoordinates()
```


Получает флаг, указывающий, вычислять ли координаты изменённых компонентов.


**Returns:**
boolean - true если координаты изменённых компонентов будут рассчитаны, иначе false

### setCalculateCoordinates(boolean value) {#setCalculateCoordinates-boolean-}
```
public final void setCalculateCoordinates(boolean value)
```


Устанавливает флаг, указывающий, вычислять ли координаты изменённых компонентов.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | boolean | true если координаты изменённых компонентов должны быть рассчитаны, иначе false |
|

### isHeaderFootersComparison() {#isHeaderFootersComparison--}
```
public final boolean isHeaderFootersComparison()
```


Получает флаг, указывающий, сравнивать ли содержимое верхнего/нижнего колонтитула.


**Returns:**
boolean - true если содержимое верхнего/нижнего колонтитула будет сравниваться, иначе false

### setHeaderFootersComparison(boolean value) {#setHeaderFootersComparison-boolean-}
```
public final void setHeaderFootersComparison(boolean value)
```


Устанавливает флаг, указывающий, сравнивать ли содержимое верхнего/нижнего колонтитула.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | boolean | true если содержимое верхнего/нижнего колонтитула должно сравниваться, иначе false |
|

### getDetalisationLevel() {#getDetalisationLevel--}
```
public final DetalisationLevel getDetalisationLevel()
```


Получает уровень детализации сравнения, представленный как [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel).
Значение по умолчанию — [DetalisationLevel.LOW](../../com.groupdocs.comparison.options.style/detalisationlevel#LOW).


**Returns:**
[DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) - the level of comparison detalization

### setDetalisationLevel(DetalisationLevel value) {#setDetalisationLevel-com.groupdocs.comparison.options.style.DetalisationLevel-}
```
public final void setDetalisationLevel(DetalisationLevel value)
```


Устанавливает уровень детализации сравнения, представленный как [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel).
Значение по умолчанию — [DetalisationLevel.LOW](../../com.groupdocs.comparison.options.style/detalisationlevel#LOW)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) | Уровень детализации сравнения |
|

### isMarkChangedContent() {#isMarkChangedContent--}
```
public final boolean isMarkChangedContent()
```


Получает флаг, указывающий, будут ли использоваться рамки для фигур в обработке Word и для прямоугольников в документах Image.


**Returns:**
boolean — true, если будут использоваться кадры, иначе false

### setMarkChangedContent(boolean value) {#setMarkChangedContent-boolean-}
```
public final void setMarkChangedContent(boolean value)
```


Устанавливает флаг, указывающий, будут ли использоваться рамки для фигур в обработке Word и для прямоугольников в документах Image.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | boolean | true, если кадры должны использоваться, иначе false |
|

### getInsertedItemStyle() {#getInsertedItemStyle--}
```
public final StyleSettings getInsertedItemStyle()
```


Получает настройки стиля, которые будут применяться к вставленным элементам.


**Returns:**
[StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) - style settings of inserted items

### setInsertedItemStyle(StyleSettings value) {#setInsertedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-}
```
public final void setInsertedItemStyle(StyleSettings value)
```


Устанавливает настройки стиля, которые будут применяться к вставленным элементам.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Настройки стиля вставленных элементов |
|

### getDeletedItemStyle() {#getDeletedItemStyle--}
```
public final StyleSettings getDeletedItemStyle()
```


Получает настройки стиля, которые будут применяться к удалённым элементам.


**Returns:**
[StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) - style settings of deleted items

### setDeletedItemStyle(StyleSettings value) {#setDeletedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-}
```
public final void setDeletedItemStyle(StyleSettings value)
```


Устанавливает настройки стиля, которые будут применяться к удалённым элементам.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Настройки стиля удалённых элементов |
|

### getChangedItemStyle() {#getChangedItemStyle--}
```
public final StyleSettings getChangedItemStyle()
```


Получает настройки стиля, которые будут применяться к изменённым элементам.


**Returns:**
[StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) - style settings of changed items

### setChangedItemStyle(StyleSettings value) {#setChangedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-}
```
public final void setChangedItemStyle(StyleSettings value)
```


Устанавливает настройки стиля, которые будут применяться к изменённым элементам.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Настройки стиля изменённых элементов |
|

### getSensitivityOfComparison() {#getSensitivityOfComparison--}
```
public final int getSensitivityOfComparison()
```


Получает чувствительность сравнения.
Процент удалённых и вставленных элементов двух сравниваемых объектов относительно всех элементов этих объектов.

* If this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Returns:**
int — чувствительность сравнения

### setSensitivityOfComparison(int value) {#setSensitivityOfComparison-int-}
```
public final void setSensitivityOfComparison(int value)
```


Устанавливает чувствительность сравнения.
Процент удалённых и вставленных элементов двух сравниваемых объектов относительно всех элементов этих объектов.

* If this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | int | Чувствительность сравнения |
|

### setSensitivityOfComparisonForTables(Integer value) {#setSensitivityOfComparisonForTables-java.lang.Integer-}
```
public void setSensitivityOfComparisonForTables(Integer value)
```


Устанавливает чувствительность сравнения для таблиц.
Если значение равно null, используется SensitivityOfComparison. Процент удалённых и вставленных элементов двух сравниваемых объектов относительно всех элементов этих объектов.

* if this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs, if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | java.lang.Integer | Чувствительность сравнения для таблиц |
|

### getSensitivityOfComparisonForTables() {#getSensitivityOfComparisonForTables--}
```
public final Integer getSensitivityOfComparisonForTables()
```


Получает чувствительность сравнения для таблиц.
Если значение равно null, используется SensitivityOfComparison. Процент удалённых и вставленных элементов двух сравниваемых объектов относительно всех элементов этих объектов.

* if this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs, if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Returns:**
java.lang.Integer — чувствительность сравнения для таблиц

### setWordsSeparatorChars(char[] value) {#setWordsSeparatorChars-char---}
```
public final void setWordsSeparatorChars(char[] value)
```


Устанавливает массив разделителей, которые будут использоваться для разбиения текста на слова.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | char[] | Массив разделителей для разбиения текста на слова |
|

### getPasswordSaveOption() {#getPasswordSaveOption--}
```
public final PasswordSaveOption getPasswordSaveOption()
```


Получает параметр сохранения пароля, представленный объектом [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption).


**Returns:**
[PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) - the password save option

### setPasswordSaveOption(PasswordSaveOption value) {#setPasswordSaveOption-com.groupdocs.comparison.options.enums.PasswordSaveOption-}
```
public final void setPasswordSaveOption(PasswordSaveOption value)
```


Устанавливает параметр сохранения пароля, представленный объектом [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) | Опция сохранения пароля |
|

### getOriginalSize() {#getOriginalSize--}
```
public final OriginalSize getOriginalSize()
```


Получает оригинальные размеры сравниваемых документов, представленные объектом [OriginalSize](../../com.groupdocs.comparison.options/originalsize).


**Returns:**
[OriginalSize](../../com.groupdocs.comparison.options/originalsize) - the original size of documents

### setOriginalSize(OriginalSize value) {#setOriginalSize-com.groupdocs.comparison.options.OriginalSize-}
```
public final void setOriginalSize(OriginalSize value)
```


Устанавливает оригинальные размеры сравниваемых документов, представленные объектом [OriginalSize](../../com.groupdocs.comparison.options/originalsize).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | [OriginalSize](../../com.groupdocs.comparison.options/originalsize) | Исходный размер документов |
|

### getDiagramMasterSetting() {#getDiagramMasterSetting--}
```
public final DiagramMasterSetting getDiagramMasterSetting()
```


Получает настройку главной страницы для документов Diagram, представленную объектом [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting).


**Returns:**
[DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) - the diagram master page setting

### setDiagramMasterSetting(DiagramMasterSetting value) {#setDiagramMasterSetting-com.groupdocs.comparison.options.style.DiagramMasterSetting-}
```
public final void setDiagramMasterSetting(DiagramMasterSetting value)
```


Устанавливает настройку главной страницы для документов Diagram, представленную объектом [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) | Настройка главной страницы диаграммы |
|

### isDirectoryCompare() {#isDirectoryCompare--}
```
public boolean isDirectoryCompare()
```


Возвращает флаг, указывающий, включено ли сравнение каталогов.


**Returns:**
boolean — true, если сравнение каталогов включено, иначе false

### setDirectoryCompare(boolean directoryCompare) {#setDirectoryCompare-boolean-}
```
public void setDirectoryCompare(boolean directoryCompare)
```


Устанавливает флаг, указывающий, должно ли быть включено сравнение каталогов.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | directoryCompare | boolean | true, если сравнение каталогов должно быть включено, иначе false |
|

### isShowOnlyChanged() {#isShowOnlyChanged--}
```
public boolean isShowOnlyChanged()
```


Возвращает логическое значение, указывающее, должны ли отображаться только изменённые элементы.


**Returns:**
boolean — true, если должны отображаться только изменённые элементы, иначе false

### setShowOnlyChanged(boolean showOnlyChanged) {#setShowOnlyChanged-boolean-}
```
public void setShowOnlyChanged(boolean showOnlyChanged)
```


Устанавливает значение, указывающее, должны ли отображаться только изменённые элементы.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | showOnlyChanged | boolean | логическое значение, указывающее, должны ли отображаться только изменённые элементы |
|

### getFolderComparisonExtension() {#getFolderComparisonExtension--}
```
public FolderComparisonExtension getFolderComparisonExtension()
```


Получает формат результирующего файла сравнения папок.


**Returns:**
com.groupdocs.comparison.options.enums.FolderComparisonExtension - FolderComparisonExtension, представляющий формат результирующего файла сравнения папок

### setFolderComparisonExtension(FolderComparisonExtension folderComparisonExtension) {#setFolderComparisonExtension-com.groupdocs.comparison.options.enums.FolderComparisonExtension-}
```
public void setFolderComparisonExtension(FolderComparisonExtension folderComparisonExtension)
```


Устанавливает формат результирующего файла сравнения папок.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | folderComparisonExtension | com.groupdocs.comparison.options.enums.FolderComparisonExtension | FolderComparisonExtension, представляющий формат результирующего файла сравнения папок |
|

