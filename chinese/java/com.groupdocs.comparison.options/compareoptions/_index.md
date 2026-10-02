---
title: "CompareOptions"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "允许配置文档比较的过程。"
type: docs
weight: 11
url: /zh/java/com.groupdocs.comparison.options/compareoptions/
---
**Inheritance:**
java.lang.Object
```
public class CompareOptions
```

允许配置文档比较的过程。


示例用法：

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


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [CompareOptions()](#CompareOptions--) | 初始化 CompareOptions 类的新实例。 |
|
|  | [CompareOptions(StyleSettings insertedItemStyle, StyleSettings deletedItemStyle, StyleSettings changedItemStyle)](#CompareOptions-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-) | 使用不同样式的设置初始化 CompareOptions 类的新实例。 |
|
## 字段

| 字段 | 描述 |
| --- | --- |
| [ignoreChangeSettings](#ignoreChangeSettings) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getIgnoreChangeSettings()](#getIgnoreChangeSettings--) | 获取基于相似性忽略更改的设置。 |
|
|  | [setIgnoreChangeSettings(IgnoreChangeSensitivitySettings ignoreChangeSettings)](#setIgnoreChangeSettings-com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings-) | 设置基于相似性忽略更改的设置。 |
|
|  | [getUserMasterPath()](#getUserMasterPath--) | 获取用于图表的用户主模板的路径。 |
|
|  | [setUserMasterPath(String userMasterPath)](#setUserMasterPath-java.lang.String-) | 设置用于图表的用户主模板的路径。 |
|
|  | [getComparisonType()](#getComparisonType--) | 获取源文档和目标文档的类型，作为 [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) 对象，以便 Comparison 知道如何比较它们。 |
|
|  | [setComparisonType(ComparisonType comparisonType)](#setComparisonType-com.groupdocs.comparison.options.enums.ComparisonType-) | 设置源文档和目标文档的类型，作为 [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) 对象，以便 Comparison 知道如何比较它们。 |
|
|  | [getPaperSize()](#getPaperSize--) | 获取结果文档中纸张的尺寸，作为 [PaperSize](../../com.groupdocs.comparison.options.enums/papersize) 对象。 |
|
|  | [setPaperSize(PaperSize value)](#setPaperSize-com.groupdocs.comparison.options.enums.PaperSize-) | 设置结果文档中纸张的尺寸，作为 [PaperSize](../../com.groupdocs.comparison.options.enums/papersize) 对象。 |
|
|  | [getCalculateCoordinatesMode()](#getCalculateCoordinatesMode--) | 获取计算坐标模式，作为 [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) 对象。 |
|
|  | [setCalculateCoordinatesMode(CalculateCoordinatesModeEnumeration calculateCoordinatesMode)](#setCalculateCoordinatesMode-com.groupdocs.comparison.options.enums.CalculateCoordinatesModeEnumeration-) | 设置计算坐标模式，作为 [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) 对象。 |
|
|  | [isShowDeletedContent()](#isShowDeletedContent--) | 获取指示是否在结果文档中显示已删除组件的标志。 |
|
|  | [setShowDeletedContent(boolean value)](#setShowDeletedContent-boolean-) | 设置指示是否在结果文档中显示已删除组件的标志。 |
|
|  | [isShowInsertedContent()](#isShowInsertedContent--) | 获取一个标志，指示是否在生成的文档中显示插入的组件。 |
|
|  | [setShowInsertedContent(boolean value)](#setShowInsertedContent-boolean-) | 设置一个标志，指示是否在生成的文档中显示插入的组件。 |
|
|  | [isGenerateSummaryPage()](#isGenerateSummaryPage--) | 获取一个标志，指示是否在生成的文档中添加包含检测到的更改统计信息的摘要页。 |
|
|  | [setGenerateSummaryPage(boolean value)](#setGenerateSummaryPage-boolean-) | 设置一个标志，指示是否在生成的文档中添加包含检测到的更改统计信息的摘要页。 |
|
|  | [isExtendedSummaryPage()](#isExtendedSummaryPage--) | 获取一个标志，指示是否在摘要页中添加扩展的文件比较信息。 |
|
|  | [setExtendedSummaryPage(boolean value)](#setExtendedSummaryPage-boolean-) | 设置一个标志，指示是否在摘要页中添加扩展的文件比较信息。 |
|
|  | [isShowOnlySummaryPage()](#isShowOnlySummaryPage--) | 获取一个标志，指示是否在生成的文档中仅保留包含检测到的更改统计信息的页面。 |
|
|  | [setShowOnlySummaryPage(boolean value)](#setShowOnlySummaryPage-boolean-) | 设置一个标志，指示是否在生成的文档中仅保留包含检测到的更改统计信息的页面。 |
|
|  | [isDetectStyleChanges()](#isDetectStyleChanges--) | 获取一个标志，指示是否检测样式更改。 |
|
|  | [setDetectStyleChanges(boolean value)](#setDetectStyleChanges-boolean-) | 设置一个标志，指示是否检测样式更改。 |
|
|  | [isMarkNestedContent()](#isMarkNestedContent--) | 获取一个标志，指示是否将已删除或已插入元素的子项标记为已删除或已插入。 |
|
|  | [setMarkNestedContent(boolean value)](#setMarkNestedContent-boolean-) | 设置一个标志，指示是否将已删除或已插入元素的子项标记为已删除或已插入。 |
|
|  | [isCalculateCoordinates()](#isCalculateCoordinates--) | 获取一个标志，指示是否为更改的组件计算坐标。 |
|
|  | [setCalculateCoordinates(boolean value)](#setCalculateCoordinates-boolean-) | 设置一个标志，指示是否为更改的组件计算坐标。 |
|
|  | [isHeaderFootersComparison()](#isHeaderFootersComparison--) | 获取一个标志，指示是否比较页眉/页脚内容。 |
|
|  | [setHeaderFootersComparison(boolean value)](#setHeaderFootersComparison-boolean-) | 设置一个标志，指示是否比较页眉/页脚内容。 |
|
|  | [getDetalisationLevel()](#getDetalisationLevel--) | 获取一个比较细化级别，表示为 [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel)。 |
|
|  | [setDetalisationLevel(DetalisationLevel value)](#setDetalisationLevel-com.groupdocs.comparison.options.style.DetalisationLevel-) | 设置一个比较细化级别，表示为 [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel)。 |
|
|  | [isMarkChangedContent()](#isMarkChangedContent--) | 获取一个标志，指示是否在文字处理文档的形状以及图像文档的矩形中使用框架。 |
|
|  | [setMarkChangedContent(boolean value)](#setMarkChangedContent-boolean-) | 设置一个标志，指示是否在文字处理文档的形状以及图像文档的矩形中使用框架。 |
|
|  | [getInsertedItemStyle()](#getInsertedItemStyle--) | 获取将应用于插入项的样式设置。 |
|
|  | [setInsertedItemStyle(StyleSettings value)](#setInsertedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-) | 设置将应用于插入项的样式设置。 |
|
|  | [getDeletedItemStyle()](#getDeletedItemStyle--) | 获取将应用于删除项的样式设置。 |
|
|  | [setDeletedItemStyle(StyleSettings value)](#setDeletedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-) | 设置将应用于删除项的样式设置。 |
|
|  | [getChangedItemStyle()](#getChangedItemStyle--) | 获取将应用于更改项的样式设置。 |
|
|  | [setChangedItemStyle(StyleSettings value)](#setChangedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-) | 设置将在更改的项目上应用的样式设置。 |
|
|  | [getSensitivityOfComparison()](#getSensitivityOfComparison--) | 获取比较的灵敏度。 |
|
|  | [setSensitivityOfComparison(int value)](#setSensitivityOfComparison-int-) | 设置比较的灵敏度。 |
|
|  | [setSensitivityOfComparisonForTables(Integer value)](#setSensitivityOfComparisonForTables-java.lang.Integer-) | 设置表格比较的灵敏度。 |
|
|  | [getSensitivityOfComparisonForTables()](#getSensitivityOfComparisonForTables--) | 获取表格比较的灵敏度。 |
|
|  | [setWordsSeparatorChars(char[] value)](#setWordsSeparatorChars-char---) | 设置用于将文本拆分为单词的分隔符数组。 |
|
|  | [getPasswordSaveOption()](#getPasswordSaveOption--) | 获取由 [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) 对象表示的密码保存选项。 |
|
|  | [setPasswordSaveOption(PasswordSaveOption value)](#setPasswordSaveOption-com.groupdocs.comparison.options.enums.PasswordSaveOption-) | 设置由 [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) 对象表示的密码保存选项。 |
|
|  | [getOriginalSize()](#getOriginalSize--) | 获取由 [OriginalSize](../../com.groupdocs.comparison.options/originalsize) 对象表示的比较文档的原始尺寸。 |
|
|  | [setOriginalSize(OriginalSize value)](#setOriginalSize-com.groupdocs.comparison.options.OriginalSize-) | 设置由 [OriginalSize](../../com.groupdocs.comparison.options/originalsize) 对象表示的比较文档的原始尺寸。 |
|
|  | [getDiagramMasterSetting()](#getDiagramMasterSetting--) | 获取由 [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) 对象表示的图表文档的母版页设置。 |
|
|  | [setDiagramMasterSetting(DiagramMasterSetting value)](#setDiagramMasterSetting-com.groupdocs.comparison.options.style.DiagramMasterSetting-) | 设置由 [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) 对象表示的图表文档的母版页设置。 |
|
|  | [isDirectoryCompare()](#isDirectoryCompare--) | 返回指示是否启用目录比较的标志。 |
|
|  | [setDirectoryCompare(boolean directoryCompare)](#setDirectoryCompare-boolean-) | 设置指示是否应启用目录比较的标志。 |
|
|  | [isShowOnlyChanged()](#isShowOnlyChanged--) | 返回指示是否仅显示更改项的布尔值。 |
|
|  | [setShowOnlyChanged(boolean showOnlyChanged)](#setShowOnlyChanged-boolean-) | 设置指示是否仅显示更改项的值。 |
|
|  | [getFolderComparisonExtension()](#getFolderComparisonExtension--) | 获取生成的文件夹比较文件的格式。 |
|
|  | [setFolderComparisonExtension(FolderComparisonExtension folderComparisonExtension)](#setFolderComparisonExtension-com.groupdocs.comparison.options.enums.FolderComparisonExtension-) | 设置生成的文件夹比较文件的格式。 |
|
### CompareOptions() {#CompareOptions--}
```
public CompareOptions()
```


初始化 CompareOptions 类的新实例。


### CompareOptions(StyleSettings insertedItemStyle, StyleSettings deletedItemStyle, StyleSettings changedItemStyle) {#CompareOptions-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-}
```
public CompareOptions(StyleSettings insertedItemStyle, StyleSettings deletedItemStyle, StyleSettings changedItemStyle)
```


使用不同样式的设置初始化 CompareOptions 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | insertedItemStyle | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | 插入项的样式设置 |
|
|  | deletedItemStyle | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | 删除项的样式设置 |
|
|  | changedItemStyle | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | 已更改样式项的样式设置 |
|

### ignoreChangeSettings {#ignoreChangeSettings}
```
public IgnoreChangeSensitivitySettings ignoreChangeSettings
```


### getIgnoreChangeSettings() {#getIgnoreChangeSettings--}
```
public IgnoreChangeSensitivitySettings getIgnoreChangeSettings()
```


获取基于相似性忽略更改的设置。


**Returns:**
com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings - 用于忽略更改的设置。

### setIgnoreChangeSettings(IgnoreChangeSensitivitySettings ignoreChangeSettings) {#setIgnoreChangeSettings-com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings-}
```
public void setIgnoreChangeSettings(IgnoreChangeSensitivitySettings ignoreChangeSettings)
```


设置基于相似性忽略更改的设置。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | ignoreChangeSettings | com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings | 用于忽略更改的设置。 |
|

### getUserMasterPath() {#getUserMasterPath--}
```
public String getUserMasterPath()
```


获取用于图表的用户主模板的路径。


**Returns:**
java.lang.String - 用户主模板在图表中的路径。

### setUserMasterPath(String userMasterPath) {#setUserMasterPath-java.lang.String-}
```
public void setUserMasterPath(String userMasterPath)
```


设置用于图表的用户主模板的路径。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | userMasterPath | java.lang.String | 用户主模板在图表中的路径。 |
|

### getComparisonType() {#getComparisonType--}
```
public ComparisonType getComparisonType()
```


获取源文档和目标文档的类型，作为 [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) 对象，以便 Comparison 知道如何比较它们。
当设置此选项时，[LoadOptions.getFileType()](../../com.groupdocs.comparison.options.load/loadoptions#getFileType--) 选项将被省略。


**Returns:**
[ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) - the type of source and target documents

### setComparisonType(ComparisonType comparisonType) {#setComparisonType-com.groupdocs.comparison.options.enums.ComparisonType-}
```
public void setComparisonType(ComparisonType comparisonType)
```


设置源文档和目标文档的类型，作为 [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) 对象，以便 Comparison 知道如何比较它们。
当设置此选项时，[LoadOptions.setFileType(FileType)](../../com.groupdocs.comparison.options.load/loadoptions#setFileType-FileType-) 选项将被省略。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | comparisonType | [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) | 源文档和目标文档的类型 |
|

### getPaperSize() {#getPaperSize--}
```
public final PaperSize getPaperSize()
```


获取结果文档中纸张的尺寸，作为 [PaperSize](../../com.groupdocs.comparison.options.enums/papersize) 对象。


**Returns:**
[PaperSize](../../com.groupdocs.comparison.options.enums/papersize) - the size of a paper in result document

### setPaperSize(PaperSize value) {#setPaperSize-com.groupdocs.comparison.options.enums.PaperSize-}
```
public final void setPaperSize(PaperSize value)
```


设置结果文档中纸张的尺寸，作为 [PaperSize](../../com.groupdocs.comparison.options.enums/papersize) 对象。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [PaperSize](../../com.groupdocs.comparison.options.enums/papersize) | 结果文档中纸张的尺寸 |
|

### getCalculateCoordinatesMode() {#getCalculateCoordinatesMode--}
```
public CalculateCoordinatesModeEnumeration getCalculateCoordinatesMode()
```


获取计算坐标模式，作为 [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) 对象。


**Returns:**
[CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) - the calculate coordinates mode

### setCalculateCoordinatesMode(CalculateCoordinatesModeEnumeration calculateCoordinatesMode) {#setCalculateCoordinatesMode-com.groupdocs.comparison.options.enums.CalculateCoordinatesModeEnumeration-}
```
public void setCalculateCoordinatesMode(CalculateCoordinatesModeEnumeration calculateCoordinatesMode)
```


设置计算坐标模式，作为 [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) 对象。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | calculateCoordinatesMode | [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) | 计算坐标模式 |
|

### isShowDeletedContent() {#isShowDeletedContent--}
```
public final boolean isShowDeletedContent()
```


获取指示是否在结果文档中显示已删除组件的标志。


**Returns:**
boolean - 如果在结果文档中显示已删除的组件则为 true，否则为 false

### setShowDeletedContent(boolean value) {#setShowDeletedContent-boolean-}
```
public final void setShowDeletedContent(boolean value)
```


设置指示是否在结果文档中显示已删除组件的标志。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | 如果应在结果文档中显示已删除的组件则为 true，否则为 false |
|

### isShowInsertedContent() {#isShowInsertedContent--}
```
public final boolean isShowInsertedContent()
```


获取一个标志，指示是否在生成的文档中显示插入的组件。


**Returns:**
boolean - 如果应在结果文档中显示已插入的组件则为 true，否则为 false

### setShowInsertedContent(boolean value) {#setShowInsertedContent-boolean-}
```
public final void setShowInsertedContent(boolean value)
```


设置一个标志，指示是否在生成的文档中显示插入的组件。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | 如果应在结果文档中显示已插入的组件则为 true，否则为 false |
|

### isGenerateSummaryPage() {#isGenerateSummaryPage--}
```
public final boolean isGenerateSummaryPage()
```


获取一个标志，指示是否在生成的文档中添加包含检测到的更改统计信息的摘要页。


**Returns:**
boolean - 如果将添加摘要页则为 true，否则为 false

### setGenerateSummaryPage(boolean value) {#setGenerateSummaryPage-boolean-}
```
public final void setGenerateSummaryPage(boolean value)
```


设置一个标志，指示是否在生成的文档中添加包含检测到的更改统计信息的摘要页。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | 如果应添加摘要页则为 true，否则为 false |
|

### isExtendedSummaryPage() {#isExtendedSummaryPage--}
```
public boolean isExtendedSummaryPage()
```


获取一个标志，指示是否在摘要页中添加扩展的文件比较信息。


**Returns:**
boolean - 如果将把扩展文件比较信息添加到摘要页则为 true，否则为 false

### setExtendedSummaryPage(boolean value) {#setExtendedSummaryPage-boolean-}
```
public void setExtendedSummaryPage(boolean value)
```


设置一个标志，指示是否在摘要页中添加扩展的文件比较信息。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | 如果应把扩展文件比较信息添加到摘要页则为 true，否则为 false |
|

### isShowOnlySummaryPage() {#isShowOnlySummaryPage--}
```
public boolean isShowOnlySummaryPage()
```


获取一个标志，指示是否在生成的文档中仅保留包含检测到的更改统计信息的页面。


**Returns:**
boolean - 如果在结果文档中只保留包含检测到的更改统计信息的页面则为 true，否则为 false

### setShowOnlySummaryPage(boolean value) {#setShowOnlySummaryPage-boolean-}
```
public void setShowOnlySummaryPage(boolean value)
```


设置一个标志，指示是否在生成的文档中仅保留包含检测到的更改统计信息的页面。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | 如果在结果文档中只应保留包含检测到的更改统计信息的页面则为 true，否则为 false |
|

### isDetectStyleChanges() {#isDetectStyleChanges--}
```
public final boolean isDetectStyleChanges()
```


获取一个标志，指示是否检测样式更改。


**Returns:**
boolean - 如果将检测样式更改则为 true，否则为 false

### setDetectStyleChanges(boolean value) {#setDetectStyleChanges-boolean-}
```
public final void setDetectStyleChanges(boolean value)
```


设置一个标志，指示是否检测样式更改。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | 如果应检测样式更改则为 true，否则为 false |
|

### isMarkNestedContent() {#isMarkNestedContent--}
```
public final boolean isMarkNestedContent()
```


获取一个标志，指示是否将已删除或已插入元素的子项标记为已删除或已插入。


**Returns:**
boolean - 如果已删除或已插入元素的子项将被标记为已删除或已插入则为 true，否则为 false

### setMarkNestedContent(boolean value) {#setMarkNestedContent-boolean-}
```
public final void setMarkNestedContent(boolean value)
```


设置一个标志，指示是否将已删除或已插入元素的子项标记为已删除或已插入。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | 如果已删除或已插入元素的子项应被标记为已删除或已插入则为 true，否则为 false |
|

### isCalculateCoordinates() {#isCalculateCoordinates--}
```
public final boolean isCalculateCoordinates()
```


获取一个标志，指示是否为更改的组件计算坐标。


**Returns:**
boolean - 如果将计算已更改组件的坐标则为 true，否则为 false

### setCalculateCoordinates(boolean value) {#setCalculateCoordinates-boolean-}
```
public final void setCalculateCoordinates(boolean value)
```


设置一个标志，指示是否为更改的组件计算坐标。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | 如果应计算已更改组件的坐标则为 true，否则为 false |
|

### isHeaderFootersComparison() {#isHeaderFootersComparison--}
```
public final boolean isHeaderFootersComparison()
```


获取一个标志，指示是否比较页眉/页脚内容。


**Returns:**
boolean - 如果将比较页眉/页脚内容则为 true，否则为 false

### setHeaderFootersComparison(boolean value) {#setHeaderFootersComparison-boolean-}
```
public final void setHeaderFootersComparison(boolean value)
```


设置一个标志，指示是否比较页眉/页脚内容。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | 如果应比较页眉/页脚内容，则为 true，否则为 false |
|

### getDetalisationLevel() {#getDetalisationLevel--}
```
public final DetalisationLevel getDetalisationLevel()
```


获取一个比较细化级别，表示为 [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel)。
默认值是 [DetalisationLevel.LOW](../../com.groupdocs.comparison.options.style/detalisationlevel#LOW)。


**Returns:**
[DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) - the level of comparison detalization

### setDetalisationLevel(DetalisationLevel value) {#setDetalisationLevel-com.groupdocs.comparison.options.style.DetalisationLevel-}
```
public final void setDetalisationLevel(DetalisationLevel value)
```


设置一个比较细化级别，表示为 [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel)。
默认值是 [DetalisationLevel.LOW](../../com.groupdocs.comparison.options.style/detalisationlevel#LOW)


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) | 比较细化的级别 |
|

### isMarkChangedContent() {#isMarkChangedContent--}
```
public final boolean isMarkChangedContent()
```


获取一个标志，指示是否在文字处理文档的形状以及图像文档的矩形中使用框架。


**Returns:**
布尔型 - 如果将使用帧，则为 true，否则为 false

### setMarkChangedContent(boolean value) {#setMarkChangedContent-boolean-}
```
public final void setMarkChangedContent(boolean value)
```


设置一个标志，指示是否在文字处理文档的形状以及图像文档的矩形中使用框架。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | 如果应使用帧，则为 true，否则为 false |
|

### getInsertedItemStyle() {#getInsertedItemStyle--}
```
public final StyleSettings getInsertedItemStyle()
```


获取将应用于插入项的样式设置。


**Returns:**
[StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) - style settings of inserted items

### setInsertedItemStyle(StyleSettings value) {#setInsertedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-}
```
public final void setInsertedItemStyle(StyleSettings value)
```


设置将应用于插入项的样式设置。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | 插入项的样式设置 |
|

### getDeletedItemStyle() {#getDeletedItemStyle--}
```
public final StyleSettings getDeletedItemStyle()
```


获取将应用于删除项的样式设置。


**Returns:**
[StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) - style settings of deleted items

### setDeletedItemStyle(StyleSettings value) {#setDeletedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-}
```
public final void setDeletedItemStyle(StyleSettings value)
```


设置将应用于删除项的样式设置。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | 删除项的样式设置 |
|

### getChangedItemStyle() {#getChangedItemStyle--}
```
public final StyleSettings getChangedItemStyle()
```


获取将应用于更改项的样式设置。


**Returns:**
[StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) - style settings of changed items

### setChangedItemStyle(StyleSettings value) {#setChangedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-}
```
public final void setChangedItemStyle(StyleSettings value)
```


设置将在更改的项目上应用的样式设置。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | 更改项的样式设置 |
|

### getSensitivityOfComparison() {#getSensitivityOfComparison--}
```
public final int getSensitivityOfComparison()
```


获取比较的灵敏度。
两个被比较对象中已删除和已插入元素占这些对象所有元素的百分比。

* If this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Returns:**
int - 比较的灵敏度

### setSensitivityOfComparison(int value) {#setSensitivityOfComparison-int-}
```
public final void setSensitivityOfComparison(int value)
```


设置比较的灵敏度。
两个被比较对象中已删除和已插入元素占这些对象所有元素的百分比。

* If this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | int | 比较的灵敏度 |
|

### setSensitivityOfComparisonForTables(Integer value) {#setSensitivityOfComparisonForTables-java.lang.Integer-}
```
public void setSensitivityOfComparisonForTables(Integer value)
```


设置表格比较的灵敏度。
如果该值为 null，则使用 SensitivityOfComparison。两个被比较对象中已删除和已插入元素占这些对象所有元素的百分比。

* if this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs, if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.lang.Integer | 表格比较的灵敏度 |
|

### getSensitivityOfComparisonForTables() {#getSensitivityOfComparisonForTables--}
```
public final Integer getSensitivityOfComparisonForTables()
```


获取表格比较的灵敏度。
如果该值为 null，则使用 SensitivityOfComparison。两个被比较对象中已删除和已插入元素占这些对象所有元素的百分比。

* if this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs, if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Returns:**
java.lang.Integer - 表格比较的灵敏度

### setWordsSeparatorChars(char[] value) {#setWordsSeparatorChars-char---}
```
public final void setWordsSeparatorChars(char[] value)
```


设置用于将文本拆分为单词的分隔符数组。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | char[] | 用于将文本拆分为单词的分隔符数组 |
|

### getPasswordSaveOption() {#getPasswordSaveOption--}
```
public final PasswordSaveOption getPasswordSaveOption()
```


获取由 [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) 对象表示的密码保存选项。


**Returns:**
[PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) - the password save option

### setPasswordSaveOption(PasswordSaveOption value) {#setPasswordSaveOption-com.groupdocs.comparison.options.enums.PasswordSaveOption-}
```
public final void setPasswordSaveOption(PasswordSaveOption value)
```


设置由 [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) 对象表示的密码保存选项。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) | 密码保存选项 |
|

### getOriginalSize() {#getOriginalSize--}
```
public final OriginalSize getOriginalSize()
```


获取由 [OriginalSize](../../com.groupdocs.comparison.options/originalsize) 对象表示的比较文档的原始尺寸。


**Returns:**
[OriginalSize](../../com.groupdocs.comparison.options/originalsize) - the original size of documents

### setOriginalSize(OriginalSize value) {#setOriginalSize-com.groupdocs.comparison.options.OriginalSize-}
```
public final void setOriginalSize(OriginalSize value)
```


设置由 [OriginalSize](../../com.groupdocs.comparison.options/originalsize) 对象表示的比较文档的原始尺寸。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [OriginalSize](../../com.groupdocs.comparison.options/originalsize) | 文档的原始大小 |
|

### getDiagramMasterSetting() {#getDiagramMasterSetting--}
```
public final DiagramMasterSetting getDiagramMasterSetting()
```


获取由 [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) 对象表示的图表文档的母版页设置。


**Returns:**
[DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) - the diagram master page setting

### setDiagramMasterSetting(DiagramMasterSetting value) {#setDiagramMasterSetting-com.groupdocs.comparison.options.style.DiagramMasterSetting-}
```
public final void setDiagramMasterSetting(DiagramMasterSetting value)
```


设置由 [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) 对象表示的图表文档的母版页设置。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) | 图表母版页设置 |
|

### isDirectoryCompare() {#isDirectoryCompare--}
```
public boolean isDirectoryCompare()
```


返回指示是否启用目录比较的标志。


**Returns:**
布尔型 - 如果已启用目录比较，则为 true，否则为 false

### setDirectoryCompare(boolean directoryCompare) {#setDirectoryCompare-boolean-}
```
public void setDirectoryCompare(boolean directoryCompare)
```


设置指示是否应启用目录比较的标志。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | directoryCompare | boolean | 如果应启用目录比较，则为 true，否则为 false |
|

### isShowOnlyChanged() {#isShowOnlyChanged--}
```
public boolean isShowOnlyChanged()
```


返回指示是否仅显示更改项的布尔值。


**Returns:**
布尔型 - 如果仅应显示已更改的项，则为 true，否则为 false

### setShowOnlyChanged(boolean showOnlyChanged) {#setShowOnlyChanged-boolean-}
```
public void setShowOnlyChanged(boolean showOnlyChanged)
```


设置指示是否仅显示更改项的值。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | showOnlyChanged | boolean | 布尔值，指示是否仅显示已更改的项 |
|

### getFolderComparisonExtension() {#getFolderComparisonExtension--}
```
public FolderComparisonExtension getFolderComparisonExtension()
```


获取生成的文件夹比较文件的格式。


**Returns:**
com.groupdocs.comparison.options.enums.FolderComparisonExtension - 表示生成的文件夹比较文件格式的 FolderComparisonExtension

### setFolderComparisonExtension(FolderComparisonExtension folderComparisonExtension) {#setFolderComparisonExtension-com.groupdocs.comparison.options.enums.FolderComparisonExtension-}
```
public void setFolderComparisonExtension(FolderComparisonExtension folderComparisonExtension)
```


设置生成的文件夹比较文件的格式。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | folderComparisonExtension | com.groupdocs.comparison.options.enums.FolderComparisonExtension | 表示生成的文件夹比较文件格式的 FolderComparisonExtension |
|

