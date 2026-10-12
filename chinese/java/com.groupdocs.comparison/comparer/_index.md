---
title: "Comparer"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "Comparer 类提供比较文档并生成比较结果的功能。"
type: docs
weight: 10
url: /zh/java/com.groupdocs.comparison/comparer/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public class Comparer implements System.IDisposable, Closeable
```

Comparer 类提供比较文档并生成比较结果的功能。


它允许您比较各种类型的文档，例如 PDF、Word、Excel、PowerPoint 等。


示例用法：

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     CompareOptions compareOptions = new CompareOptions();
     compareOptions.setDetectStyleChanges(true);

     comparer.compare(resultFile, compareOptions);
 }
 
````


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [Comparer(String filePath)](#Comparer-java.lang.String-) | 使用指定的源文件路径初始化 Comparer 类的新实例。 |
|
|  | [Comparer(String filePath, CompareOptions compareOptions)](#Comparer-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | 使用指定的文件夹路径和比较选项初始化 Comparer 类的新实例。 |
|
|  | [Comparer(Path filePath)](#Comparer-java.nio.file.Path-) | 使用指定的源文件路径初始化 Comparer 类的新实例。 |
|
|  | [Comparer(String filePath, LoadOptions loadOptions)](#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-) | 使用指定的源文件路径和 [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) 初始化 Comparer 的新实例。 |
|
|  | [Comparer(Path filePath, LoadOptions loadOptions)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-) | 使用指定的源文件路径和 [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) 初始化 Comparer 的新实例。 |
|
|  | [Comparer(Path filePath, CompareOptions compareOptions)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | 使用指定的源文件路径和 [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) 初始化 Comparer 的新实例。 |
|
|  | [Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings)](#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-) | 使用指定的源文件路径、[LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) 和 [ComparerSettings](../../com.groupdocs.comparison/comparersettings) 初始化 Comparer 类的新实例。 |
|
|  | [Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)](#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-) | 使用指定的源文件路径、[LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) 和 [ComparerSettings](../../com.groupdocs.comparison/comparersettings) 初始化 Comparer 类的新实例。 |
|
|  | [Comparer(String filePath, ComparerSettings settings)](#Comparer-java.lang.String-com.groupdocs.comparison.ComparerSettings-) | 使用指定的源文件路径和 [ComparerSettings](../../com.groupdocs.comparison/comparersettings) 初始化 Comparer 类的新实例。 |
|
|  | [Comparer(Path filePath, ComparerSettings settings)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.ComparerSettings-) | 使用指定的源文件路径和 [ComparerSettings](../../com.groupdocs.comparison/comparersettings) 初始化 Comparer 类的新实例。 |
|
|  | [Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-) | 使用指定的源文件路径、[LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) 和 [ComparerSettings](../../com.groupdocs.comparison/comparersettings) 初始化 Comparer 类的新实例。 |
|
|  | [Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-) | 使用指定的源文件路径、[LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) 和 [ComparerSettings](../../com.groupdocs.comparison/comparersettings) 初始化 Comparer 类的新实例。 |
|
|  | [Comparer(InputStream document)](#Comparer-java.io.InputStream-) | 使用指定的源文档流初始化 Comparer 类的新实例。 |
|
|  | [Comparer(InputStream document, LoadOptions loadOptions)](#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-) | 使用指定的源文档流和 [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) 初始化 Comparer 的新实例。 |
|
|  | [Comparer(InputStream document, ComparerSettings settings)](#Comparer-java.io.InputStream-com.groupdocs.comparison.ComparerSettings-) | 使用指定的源文档流和 [ComparerSettings](../../com.groupdocs.comparison/comparersettings) 初始化 Comparer 类的新实例。 |
|
|  | [Comparer(InputStream document, LoadOptions loadOptions, ComparerSettings settings)](#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-) | 使用指定的文档流、[LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) 和 [ComparerSettings](../../com.groupdocs.comparison/comparersettings) 初始化 Comparer 类的新实例。 |
|
|  | [Comparer(ComparerSettings settings)](#Comparer-com.groupdocs.comparison.ComparerSettings-) | 使用指定的 [ComparerSettings](../../com.groupdocs.comparison/comparersettings) 初始化 Comparer 类的新实例。 |
|
## 字段

| 字段 | 描述 |
| --- | --- |
| [FILE_PATH](#FILE-PATH) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getSource()](#getSource--) | 获取正在比较的源文档。 |
|
|  | [getTargets()](#getTargets--) | 与源文件进行比较的目标文档列表。 |
|
|  | [compare()](#compare--) | 使用默认选项比较指定文件与目标文档，但不保存结果。 |
|
|  | [compare(String filePath)](#compare-java.lang.String-) | 比较指定文件与目标文档并生成比较结果。 |
|
|  | [compare(Path filePath)](#compare-java.nio.file.Path-) | 比较指定文件与目标文档并生成比较结果。 |
|
|  | [compare(OutputStream outputStream)](#compare-java.io.OutputStream-) | 比较指定文件与目标文档，并将比较结果写入输出流。 |
|
|  | [compare(String filePath, CompareOptions compareOptions)](#compare-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | 比较指定文件与目标文档，并将比较结果写入提供的文件路径。 |
|
|  | [compare(Path filePath, CompareOptions compareOptions)](#compare-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | 比较指定文件与目标文档，并将比较结果写入提供的文件路径。 |
|
|  | [compare(OutputStream stream, CompareOptions compareOptions)](#compare-java.io.OutputStream-com.groupdocs.comparison.options.CompareOptions-) | 比较指定文件与目标文档，并将比较结果写入输出流。 |
|
|  | [compare(SaveOptions saveOptions, CompareOptions compareOptions)](#compare-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | 比较指定文件与目标文档，但不保存结果。 |
|
|  | [compare(String filePath, SaveOptions saveOptions)](#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-) | 比较指定文件与目标文档，并将比较结果写入提供的文件路径。 |
|
|  | [compare(Path filePath, SaveOptions saveOptions)](#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-) | 比较指定文件与目标文档，并将比较结果写入提供的文件路径。 |
|
|  | [compare(OutputStream stream, SaveOptions saveOptions)](#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-) | 比较指定文件与目标文档，并将比较结果写入提供的文件路径。 |
|
|  | [compare(CompareOptions compareOptions)](#compare-com.groupdocs.comparison.options.CompareOptions-) | 比较指定文件与目标文档，但不保存结果。 |
|
|  | [compare(OutputStream outputStream, SaveOptions saveOptions, CompareOptions compareOptions)](#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | 比较指定文件与目标文档，并将比较结果写入提供的输出流。 |
|
|  | [compare(String filePath, SaveOptions saveOptions, CompareOptions compareOptions)](#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | 比较指定文件与目标文档，并将比较结果写入提供的文件路径。 |
|
|  | [compareDirectory(String filePath, CompareOptions compareOptions)](#compareDirectory-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | 比较指定目录与目标目录，并将比较结果保存到提供的文件路径。 |
|
|  | [compareDirectory(Path filePath, CompareOptions compareOptions)](#compareDirectory-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | 比较指定目录与目标目录，并将比较结果保存到提供的文件路径。 |
|
|  | [compare(Path filePath, SaveOptions saveOptions, CompareOptions compareOptions)](#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | 比较指定文件与目标文档，并将比较结果写入提供的文件路径。 |
|
|  | [add(String filePath)](#add-java.lang.String-) | 将指定的目标文档添加到比较过程。 |
|
|  | [add(String filePath, CompareOptions compareOptions)](#add-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | 将指定的目标文档或文件夹添加到比较过程。 |
|
|  | [add(Path filePath)](#add-java.nio.file.Path-) | 将指定的目标文档添加到比较过程。 |
|
|  | [add(String[] filePaths)](#add-java.lang.String...-) | 将指定的目标文档添加到比较过程。 |
|
|  | [add(Path[] filePaths)](#add-java.nio.file.Path...-) | 将指定的目标文档添加到比较过程。 |
|
|  | [add(String filePath, LoadOptions loadOptions)](#add-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-) | 使用指定的加载选项将目标文档添加到比较过程。 |
|
|  | [add(Path filePath, LoadOptions loadOptions)](#add-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-) | 使用指定的加载选项将目标文档添加到比较过程。 |
|
|  | [add(Path filePath, CompareOptions compareOptions)](#add-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | 使用指定的加载选项将目标文档添加到比较过程。 |
|
|  | [add(InputStream document)](#add-java.io.InputStream-) | 将指定的目标文档添加到比较过程。 |
|
|  | [add(InputStream[] documents)](#add-java.io.InputStream...-) | 将指定的目标文档添加到比较过程。 |
|
|  | [add(InputStream document, LoadOptions loadOptions)](#add-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-) | 使用指定的加载选项将目标文档添加到比较过程。 |
|
|  | [getChanges()](#getChanges--) | 检索一个包含 [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) 对象的数组，这些对象表示比较过程中检测到的更改。 |
|
|  | [getChanges(GetChangeOptions getChangeOptions)](#getChanges-com.groupdocs.comparison.options.GetChangeOptions-) | 检索一个包含 [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) 对象的数组，这些对象表示比较过程中检测到的更改。 |
|
|  | [applyChanges(String filePath, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.lang.String-com.groupdocs.comparison.options.ApplyChangeOptions-) | 接受或拒绝更改并将其应用于结果文档。 |
|
|  | [applyChanges(Path filePath, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.ApplyChangeOptions-) | 接受或拒绝更改并将其应用于生成的文档。 |
|
|  | [applyChanges(OutputStream document, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.ApplyChangeOptions-) | 接受或拒绝更改并将其应用于生成的文档。 |
|
|  | [applyChanges(String filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-) | 接受或拒绝更改并将其应用于生成的文档。 |
|
|  | [applyChanges(Path filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-) | 接受或拒绝更改并将其应用于生成的文档。 |
|
|  | [applyChanges(OutputStream document, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-) | 接受或拒绝更改并将其应用于生成的文档。 |
|
|  | [getResultString()](#getResultString--) | 获取比较后的结果字符串（仅适用于文本比较）。 |
|
|  | [getSourceFolder()](#getSourceFolder--) | 返回正在比较的源文件夹。 |
|
|  | [getTargetFolder()](#getTargetFolder--) | 返回正在比较的目标文件夹。 |
|
|  | [selfComparisonCheck(Document source, Document target)](#selfComparisonCheck-com.groupdocs.comparison.Document-com.groupdocs.comparison.Document-) | 自我比较检查 (e498c23)。 |
|
|  | [close()](#close--) | 释放资源。 |
|
### Comparer(String filePath) {#Comparer-java.lang.String-}
```
public Comparer(String filePath)
```


使用指定的源文件路径初始化 Comparer 类的新实例。

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.lang.String | 源文档的路径 |
|

### Comparer(String filePath, CompareOptions compareOptions) {#Comparer-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(String filePath, CompareOptions compareOptions)
```


使用指定的文件夹路径和比较选项初始化 Comparer 类的新实例。

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.lang.String | 源文档或文件夹的路径 |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | 文件夹比较的比较选项 |
|

### Comparer(Path filePath) {#Comparer-java.nio.file.Path-}
```
public Comparer(Path filePath)
```


使用指定的源文件路径初始化 Comparer 类的新实例。

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 源文档的路径 |
|

### Comparer(String filePath, LoadOptions loadOptions) {#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Comparer(String filePath, LoadOptions loadOptions)
```


使用指定的源文件路径和 [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) 初始化 Comparer 的新实例。

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.lang.String | 源文档的路径 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | 要应用于文档的自定义加载选项 |
|

### Comparer(Path filePath, LoadOptions loadOptions) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Comparer(Path filePath, LoadOptions loadOptions)
```


使用指定的源文件路径和 [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) 初始化 Comparer 的新实例。

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 源文档的路径 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | 要应用于文档的自定义加载选项 |
|

### Comparer(Path filePath, CompareOptions compareOptions) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(Path filePath, CompareOptions compareOptions)
```


使用指定的源文件路径和 [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) 初始化 Comparer 的新实例。

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 源文档的路径 |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | 文件夹比较的比较选项 |
|

### Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings) {#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings)
```


使用指定的源文件路径、[LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) 和 [ComparerSettings](../../com.groupdocs.comparison/comparersettings) 初始化 Comparer 类的新实例。

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.lang.String | 源文档的路径 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | 要应用于文档的自定义加载选项 |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | 比较过程使用的比较器设置 |
|

### Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions) {#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)
```


使用指定的源文件路径、[LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) 和 [ComparerSettings](../../com.groupdocs.comparison/comparersettings) 初始化 Comparer 类的新实例。

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.lang.String | 要比较的源文档、文件夹或文本的路径 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | 要应用于文档的自定义加载选项 |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | 比较过程使用的比较器设置 |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | 文件夹比较的比较选项 |
|

### Comparer(String filePath, ComparerSettings settings) {#Comparer-java.lang.String-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(String filePath, ComparerSettings settings)
```


使用指定的源文件路径和 [ComparerSettings](../../com.groupdocs.comparison/comparersettings) 初始化 Comparer 类的新实例。

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.lang.String | 源文档的路径 |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | 比较过程使用的比较器设置 |
|

### Comparer(Path filePath, ComparerSettings settings) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(Path filePath, ComparerSettings settings)
```


使用指定的源文件路径和 [ComparerSettings](../../com.groupdocs.comparison/comparersettings) 初始化 Comparer 类的新实例。

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 源文档的路径 |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | 比较过程使用的比较器设置 |
|

### Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings)
```


使用指定的源文件路径、[LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) 和 [ComparerSettings](../../com.groupdocs.comparison/comparersettings) 初始化 Comparer 类的新实例。

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 源文档的路径 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | 要应用于文档的自定义加载选项 |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | 比较过程使用的比较器设置 |
|

### Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)
```


使用指定的源文件路径、[LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) 和 [ComparerSettings](../../com.groupdocs.comparison/comparersettings) 初始化 Comparer 类的新实例。

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 源文档或文件夹的路径 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | 要应用于文档的自定义加载选项 |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | 比较过程使用的比较器设置 |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | 文件夹比较的比较选项 |
|

### Comparer(InputStream document) {#Comparer-java.io.InputStream-}
```
public Comparer(InputStream document)
```


使用指定的源文档流初始化 Comparer 类的新实例。

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文档 | java.io.InputStream | 源文档的输入流 |
|

### Comparer(InputStream document, LoadOptions loadOptions) {#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Comparer(InputStream document, LoadOptions loadOptions)
```


使用指定的源文档流和 [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) 初始化 Comparer 的新实例。

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文档 | java.io.InputStream | 源文档的输入流 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | 要应用于文档的自定义加载选项 |
|

### Comparer(InputStream document, ComparerSettings settings) {#Comparer-java.io.InputStream-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(InputStream document, ComparerSettings settings)
```


使用指定的源文档流和 [ComparerSettings](../../com.groupdocs.comparison/comparersettings) 初始化 Comparer 类的新实例。

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文档 | java.io.InputStream | 源文档的输入流 |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | 比较过程使用的比较器设置 |
|

### Comparer(InputStream document, LoadOptions loadOptions, ComparerSettings settings) {#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(InputStream document, LoadOptions loadOptions, ComparerSettings settings)
```


使用指定的文档流、[LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) 和 [ComparerSettings](../../com.groupdocs.comparison/comparersettings) 初始化 Comparer 类的新实例。

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文档 | java.io.InputStream | 包含待比较文档数据的流 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | 要应用于文档的自定义加载选项 |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | 比较过程使用的比较器设置 |
|

### Comparer(ComparerSettings settings) {#Comparer-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(ComparerSettings settings)
```


使用指定的 [ComparerSettings](../../com.groupdocs.comparison/comparersettings) 初始化 Comparer 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | 设置 |
|

### FILE_PATH {#FILE-PATH}
```
public static final String FILE_PATH
```


### getSource() {#getSource--}
```
public final Document getSource()
```


获取正在比较的源文档。


**Returns:**
[Document](../../com.groupdocs.comparison/document) - the source document

### getTargets() {#getTargets--}
```
public final List<Document> getTargets()
```


与源文件进行比较的目标文档列表。


**Returns:**
java.util.List<com.groupdocs.comparison.Document> - 目标文档

### compare() {#compare--}
```
public final Path compare()
```


使用默认选项比较指定文件与目标文档，但不保存结果。

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Returns:**
java.nio.file.Path - 结果文档的路径或 null

### compare(String filePath) {#compare-java.lang.String-}
```
public final Path compare(String filePath)
```


比较指定文件与目标文档并生成比较结果。

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.lang.String | 结果文档路径 |
|

**Returns:**
java.nio.file.Path - 结果文件路径或 null。在某些情况下可以更改其扩展名

### compare(Path filePath) {#compare-java.nio.file.Path-}
```
public final Path compare(Path filePath)
```


比较指定文件与目标文档并生成比较结果。

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 结果文档路径 |
|

**Returns:**
java.nio.file.Path - 结果文件路径，在某些情况下可以更改其扩展名

### compare(OutputStream outputStream) {#compare-java.io.OutputStream-}
```
public final Path compare(OutputStream outputStream)
```


比较指定文件与目标文档，并将比较结果写入输出流。


注意：如果返回值为 null，请使用写入 outputStream 的数据

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | outputStream | java.io.OutputStream | 结果文档流 |
|

**Returns:**
java.nio.file.Path - 结果文件路径或 null（当必须使用 outputStream 中的数据时）。在某些情况下可以更改结果文件的扩展名

### compare(String filePath, CompareOptions compareOptions) {#compare-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(String filePath, CompareOptions compareOptions)
```


比较指定文件与目标文档，并将比较结果写入提供的文件路径。

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.lang.String | 结果文档文件路径 |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | 比较过程使用的比较选项 |
|

**Returns:**
java.nio.file.Path - 结果文件路径，在某些情况下可以更改其扩展名

### compare(Path filePath, CompareOptions compareOptions) {#compare-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(Path filePath, CompareOptions compareOptions)
```


比较指定文件与目标文档，并将比较结果写入提供的文件路径。

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 结果文档文件路径 |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | 比较过程使用的比较选项 |
|

**Returns:**
java.nio.file.Path - 结果文件路径，在某些情况下可以更改其扩展名

### compare(OutputStream stream, CompareOptions compareOptions) {#compare-java.io.OutputStream-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(OutputStream stream, CompareOptions compareOptions)
```


比较指定文件与目标文档，并将比较结果写入输出流。


注意：如果返回值为 null，请使用写入 outputStream 的数据。

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 流 | java.io.OutputStream | 结果文档流 |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | 比较过程使用的比较选项 |
|

**Returns:**
java.nio.file.Path - 结果文件路径或 null（当必须使用 outputStream 中的数据时）。在某些情况下可以更改结果文件的扩展名

### compare(SaveOptions saveOptions, CompareOptions compareOptions) {#compare-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(SaveOptions saveOptions, CompareOptions compareOptions)
```


比较指定文件与目标文档，但不保存结果。

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparison options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | 保存选项 |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | 比较过程使用的比较选项 |
|

**Returns:**
java.nio.file.Path - 结果文档的路径或 null

### compare(String filePath, SaveOptions saveOptions) {#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-}
```
public final Path compare(String filePath, SaveOptions saveOptions)
```


比较指定文件与目标文档，并将比较结果写入提供的文件路径。

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.lang.String | 结果文档文件路径 |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | 保存选项 |
|

**Returns:**
java.nio.file.Path - 结果文件路径，在某些情况下可以更改其扩展名

### compare(Path filePath, SaveOptions saveOptions) {#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-}
```
public final Path compare(Path filePath, SaveOptions saveOptions)
```


比较指定文件与目标文档，并将比较结果写入提供的文件路径。

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 结果文档文件路径 |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | 保存选项 |
|

**Returns:**
java.nio.file.Path - 结果文件路径，在某些情况下可以更改其扩展名

### compare(OutputStream stream, SaveOptions saveOptions) {#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-}
```
public final Path compare(OutputStream stream, SaveOptions saveOptions)
```


比较指定文件与目标文档，并将比较结果写入提供的文件路径。


注意：如果返回值为 null，请使用写入 outputStream 的数据

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 流 | java.io.OutputStream | 结果文档流 |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | 保存选项 |
|

**Returns:**
java.nio.file.Path - 结果文件路径或 null（当必须使用 outputStream 中的数据时）。在某些情况下可以更改结果文件的扩展名

### compare(CompareOptions compareOptions) {#compare-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(CompareOptions compareOptions)
```


比较指定文件与目标文档，但不保存结果。

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | 比较过程使用的比较选项 |
|

**Returns:**
java.nio.file.Path - 结果文件的路径或 null

### compare(OutputStream outputStream, SaveOptions saveOptions, CompareOptions compareOptions) {#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(OutputStream outputStream, SaveOptions saveOptions, CompareOptions compareOptions)
```


比较指定文件与目标文档，并将比较结果写入提供的输出流。


注意：如果返回值为 null，请使用写入 outputStream 的数据

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | outputStream | java.io.OutputStream | 结果文档流 |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | 用于保存结果文档的保存选项 |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | 比较过程使用的比较选项 |
|

**Returns:**
java.nio.file.Path - 结果文件路径或 null（当必须使用 outputStream 中的数据时）。在某些情况下可以更改结果文件的扩展名

### compare(String filePath, SaveOptions saveOptions, CompareOptions compareOptions) {#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(String filePath, SaveOptions saveOptions, CompareOptions compareOptions)
```


比较指定文件与目标文档，并将比较结果写入提供的文件路径。

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparison options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.lang.String | 结果文档文件路径 |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | 用于保存结果文档的保存选项 |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | 比较过程使用的比较选项 |
|

**Returns:**
java.nio.file.Path - 结果文件路径，在某些情况下可以更改其扩展名

### compareDirectory(String filePath, CompareOptions compareOptions) {#compareDirectory-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public void compareDirectory(String filePath, CompareOptions compareOptions)
```


比较指定目录与目标目录，并将比较结果保存到提供的文件路径。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.lang.String | 比较结果将被保存的文件路径。 |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | 用于目录比较过程的选项。 |
|

### compareDirectory(Path filePath, CompareOptions compareOptions) {#compareDirectory-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public void compareDirectory(Path filePath, CompareOptions compareOptions)
```


比较指定目录与目标目录，并将比较结果保存到提供的文件路径。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 比较结果将被保存的文件路径。 |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | 用于目录比较过程的选项。 |
|

### compare(Path filePath, SaveOptions saveOptions, CompareOptions compareOptions) {#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(Path filePath, SaveOptions saveOptions, CompareOptions compareOptions)
```


比较指定文件与目标文档，并将比较结果写入提供的文件路径。

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 结果文档文件路径 |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | 用于保存结果文档的保存选项 |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | 比较过程使用的比较选项 |
|

**Returns:**
java.nio.file.Path - 结果文件路径，在某些情况下可以更改其扩展名

### add(String filePath) {#add-java.lang.String-}
```
public final void add(String filePath)
```


将指定的目标文档添加到比较过程。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.lang.String | 要添加的目标文档的路径 |
|

### add(String filePath, CompareOptions compareOptions) {#add-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public void add(String filePath, CompareOptions compareOptions)
```


将指定的目标文档或文件夹添加到比较过程。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.lang.String | 要添加的目标文档或文件夹的路径 |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | 比较的选项 |
|

### add(Path filePath) {#add-java.nio.file.Path-}
```
public final void add(Path filePath)
```


将指定的目标文档添加到比较过程。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 要添加的目标文档的路径 |
|

### add(String[] filePaths) {#add-java.lang.String...-}
```
public final void add(String[] filePaths)
```


将指定的目标文档添加到比较过程。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePaths | java.lang.String[] | 要添加的目标文档的路径 |
|

### add(Path[] filePaths) {#add-java.nio.file.Path...-}
```
public final void add(Path[] filePaths)
```


将指定的目标文档添加到比较过程。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePaths | java.nio.file.Path[] | 要添加的目标文档的路径 |
|

### add(String filePath, LoadOptions loadOptions) {#add-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-}
```
public final void add(String filePath, LoadOptions loadOptions)
```


使用指定的加载选项将目标文档添加到比较过程。

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.lang.String | 要添加的目标文档的路径 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | 要应用于文档的自定义加载选项 |
|

### add(Path filePath, LoadOptions loadOptions) {#add-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-}
```
public final void add(Path filePath, LoadOptions loadOptions)
```


使用指定的加载选项将目标文档添加到比较过程。

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 要添加的目标文档的路径 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | 要应用于文档的自定义加载选项 |
|

### add(Path filePath, CompareOptions compareOptions) {#add-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public final void add(Path filePath, CompareOptions compareOptions)
```


使用指定的加载选项将目标文档添加到比较过程。

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 要添加的目标文档或文件夹的路径 |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | 比较的选项 |
|

### add(InputStream document) {#add-java.io.InputStream-}
```
public final void add(InputStream document)
```


将指定的目标文档添加到比较过程。

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文档 | java.io.InputStream | 包含待比较文档数据的流 |
|

### add(InputStream[] documents) {#add-java.io.InputStream...-}
```
public final void add(InputStream[] documents)
```


将指定的目标文档添加到比较过程。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文档 | java.io.InputStream[] | 用于比较的文档数据流 |
|

### add(InputStream document, LoadOptions loadOptions) {#add-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-}
```
public final void add(InputStream document, LoadOptions loadOptions)
```


使用指定的加载选项将目标文档添加到比较过程。

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文档 | java.io.InputStream | 包含待比较文档数据的流 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | 要应用于文档的自定义加载选项 |
|

### getChanges() {#getChanges--}
```
public final ChangeInfo[] getChanges()
```


检索一个包含 [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) 对象的数组，这些对象表示比较过程中检测到的更改。


使用此方法获取源文档与目标文档之间更改的详细信息。
每个 [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) 对象包含诸如更改类型、受影响区域等信息，
以及更改前后的内容。

* More about how to obtain collection of detected differences between compared documents in Java: [How to get list of changes between documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Get+list+of+changes)
* More about how to get changes coordinates at pages image preview when comparing documents using GroupDocs.Comparison for Java: [How to get changes coordinates programmatically](../https://docs.groupdocs.com/display/comparisonjava/Get+changes+coordinates)


**Returns:**
com.groupdocs.comparison.result.ChangeInfo[] - 一个数组，包含在比较过程中检测到的更改的 [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) 对象

### getChanges(GetChangeOptions getChangeOptions) {#getChanges-com.groupdocs.comparison.options.GetChangeOptions-}
```
public final ChangeInfo[] getChanges(GetChangeOptions getChangeOptions)
```


检索一个包含 [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) 对象的数组，这些对象表示比较过程中检测到的更改。


使用此方法获取源文档与目标文档之间更改的详细信息。
每个 [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) 对象包含诸如更改类型、受影响区域等信息，
以及更改前后的内容。


参数 [GetChangeOptions](../../com.groupdocs.comparison.options/getchangeoptions) 允许以不同方式过滤更改。

* More about how to obtain collection of detected differences between compared documents in Java: [How to get list of changes between documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Get+list+of+changes)
* More about how to get changes coordinates at pages image preview when comparing documents using GroupDocs.Comparison for Java: [How to get changes coordinates programmatically](../https://docs.groupdocs.com/display/comparisonjava/Get+changes+coordinates)


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | getChangeOptions | [GetChangeOptions](../../com.groupdocs.comparison.options/getchangeoptions) | 允许过滤更改的对象 |
|

**Returns:**
com.groupdocs.comparison.result.ChangeInfo[] - 一个数组，包含在比较过程中检测到的更改的 [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) 对象

### applyChanges(String filePath, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.lang.String-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(String filePath, ApplyChangeOptions applyChangeOptions)
```


接受或拒绝更改并将其应用于结果文档。

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.lang.String | 结果文档文件路径 |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | 自定义应用更改选项，用于配置应用更改的过程 |
|

### applyChanges(Path filePath, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(Path filePath, ApplyChangeOptions applyChangeOptions)
```


接受或拒绝更改并将其应用于生成的文档。

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 结果文档文件路径 |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | 自定义应用更改选项，用于配置应用更改的过程 |
|

### applyChanges(OutputStream document, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(OutputStream document, ApplyChangeOptions applyChangeOptions)
```


接受或拒绝更改并将其应用于生成的文档。

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文档 | java.io.OutputStream | 结果文档输出流 |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | 自定义应用更改选项，用于配置应用更改的过程 |
|

### applyChanges(String filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(String filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)
```


接受或拒绝更改并将其应用于生成的文档。

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.lang.String | 结果文档文件路径 |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | 用于配置保存结果文档的保存选项 |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | 自定义应用更改选项，用于配置应用更改的过程 |
|

### applyChanges(Path filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(Path filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)
```


接受或拒绝更改并将其应用于生成的文档。

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 结果文档文件路径 |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | 用于配置保存结果文档的保存选项 |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | 自定义应用更改选项，用于配置应用更改的过程 |
|

### applyChanges(OutputStream document, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(OutputStream document, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)
```


接受或拒绝更改并将其应用于生成的文档。

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文档 | java.io.OutputStream | 结果文档输出流 |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | 用于配置保存结果文档的保存选项 |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | 自定义应用更改选项，用于配置应用更改的过程 |
|

### getResultString() {#getResultString--}
```
public String getResultString()
```


获取比较后的结果字符串（仅适用于文本比较）。


**Returns:**
java.lang.String - 结果字符串

### getSourceFolder() {#getSourceFolder--}
```
public String getSourceFolder()
```


返回正在比较的源文件夹。


**Returns:**
java.lang.String - 源文件夹

### getTargetFolder() {#getTargetFolder--}
```
public String getTargetFolder()
```


返回正在比较的目标文件夹。


**Returns:**
java.lang.String - 目标文件夹

### selfComparisonCheck(Document source, Document target) {#selfComparisonCheck-com.groupdocs.comparison.Document-com.groupdocs.comparison.Document-}
```
public static void selfComparisonCheck(Document source, Document target)
```


自比较检查 (e498c23)。C# 7a7668c internal；保持 public，以便 core.common 测试可以调用。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [Document](../../com.groupdocs.comparison/document) |  |
| target | [Document](../../com.groupdocs.comparison/document) |  |

### close() {#close--}
```
public void close()
```


释放资源。


