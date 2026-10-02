---
title: "文档"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "表示用于比较过程的文档。"
type: docs
weight: 12
url: /zh/java/com.groupdocs.comparison/document/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Document implements Closeable
```

表示用于比较过程的文档。


Document 类提供加载、生成预览图像以及在比较过程中操作文档的方法。


示例用法：

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     try (IDocumentInfo info = comparer.getSource().getDocumentInfo()) {
         System.out.println("File type: " + info.getFileType());
         System.out.println("Number of pages: " + info.getPageCount());
         System.out.println("Document size: " + info.getSize());
     }
 }
 
````


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [Document(InputStream stream)](#Document-java.io.InputStream-) | 使用指定的文档流初始化 Document 类的新实例。 |
|
|  | [Document(String filePath)](#Document-java.lang.String-) | 使用指定的文档路径初始化 Document 类的新实例。 |
|
|  | [Document(Path filePath)](#Document-java.nio.file.Path-) | 使用指定的文档路径初始化 Document 类的新实例。 |
|
|  | [Document(Path filePath, String password)](#Document-java.nio.file.Path-java.lang.String-) | 使用指定的文档路径和密码初始化 Document 类的新实例。 |
|
|  | [Document(Path filePath, LoadOptions loadOptions)](#Document-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-) | 使用指定的文档路径和加载选项初始化 Document 类的新实例。 |
|
|  | [Document(String filePath, String password)](#Document-java.lang.String-java.lang.String-) | 使用指定的文档路径和密码初始化 Document 类的新实例。 |
|
|  | [Document(String filePath, LoadOptions loadOptions)](#Document-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-) | 使用指定的文档路径和加载选项初始化 Document 类的新实例。 |
|
|  | [Document(InputStream stream, String password)](#Document-java.io.InputStream-java.lang.String-) | 使用指定的文档流和密码初始化 Document 类的新实例。 |
|
|  | [Document(String filePathOrTextContent, boolean isLoadText)](#Document-java.lang.String-boolean-) | 使用指定的文档路径或文本内容以及指示所传递内容的标志初始化 Document 类的新实例。 |
|
|  | [Document(InputStream inputStream, LoadOptions loadOptions)](#Document-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-) | 使用指定的文档流和加载选项初始化 Document 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getChanges()](#getChanges--) | 获取一个 [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) 对象列表，表示在比较过程中检测到的更改。 |
|
|  | [setChanges(List<ChangeInfo> value)](#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--) | 设置一个 [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) 对象列表，表示在比较过程中检测到的更改。 |
|
|  | [getName()](#getName--) | 获取文档的名称。 |
|
|  | [setName(String value)](#setName-java.lang.String-) | 设置文档的名称。 |
|
|  | [getFileType()](#getFileType--) | 获取文档的类型。 |
|
|  | [setFileType(FileType fileType)](#setFileType-com.groupdocs.comparison.result.FileType-) | 设置文档的类型。 |
|
|  | [createStream()](#createStream--) | 创建包含文档内容的新流。 |
|
|  | [getStreamLength()](#getStreamLength--) | 获取文档的大小 |
|
|  | [getPassword()](#getPassword--) | 获取文档的密码 |
|
|  | [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.comparison.options.PreviewOptions-) | 根据提供的 [PreviewOptions](../../com.groupdocs.comparison.options/previewoptions) 生成文档预览。 |
|
|  | [getDocumentInfo()](#getDocumentInfo--) | 获取有关文档的信息，包括文档类型、页数、页面尺寸等。 |
|
| [close()](#close--) |  |
### Document(InputStream stream) {#Document-java.io.InputStream-}
```
public Document(InputStream stream)
```


使用指定的文档流初始化 Document 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 流 | java.io.InputStream | 文档流 |
|

### Document(String filePath) {#Document-java.lang.String-}
```
public Document(String filePath)
```


使用指定的文档路径初始化 Document 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.lang.String | 文档路径 |
|

### Document(Path filePath) {#Document-java.nio.file.Path-}
```
public Document(Path filePath)
```


使用指定的文档路径初始化 Document 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 文档路径 |
|

### Document(Path filePath, String password) {#Document-java.nio.file.Path-java.lang.String-}
```
public Document(Path filePath, String password)
```


使用指定的文档路径和密码初始化 Document 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 文档路径 |
|
|  | 密码 | java.lang.String | 文档密码 |
|

### Document(Path filePath, LoadOptions loadOptions) {#Document-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Document(Path filePath, LoadOptions loadOptions)
```


使用指定的文档路径和加载选项初始化 Document 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 文档路径 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | 加载选项 |
|

### Document(String filePath, String password) {#Document-java.lang.String-java.lang.String-}
```
public Document(String filePath, String password)
```


使用指定的文档路径和密码初始化 Document 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.lang.String | 文档路径 |
|
|  | 密码 | java.lang.String | 文档密码 |
|

### Document(String filePath, LoadOptions loadOptions) {#Document-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Document(String filePath, LoadOptions loadOptions)
```


使用指定的文档路径和加载选项初始化 Document 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.lang.String | 文档路径 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | 加载选项 |
|

### Document(InputStream stream, String password) {#Document-java.io.InputStream-java.lang.String-}
```
public Document(InputStream stream, String password)
```


使用指定的文档流和密码初始化 Document 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 流 | java.io.InputStream | 文档流 |
|
|  | 密码 | java.lang.String | 文档密码 |
|

### Document(String filePathOrTextContent, boolean isLoadText) {#Document-java.lang.String-boolean-}
```
public Document(String filePathOrTextContent, boolean isLoadText)
```


使用指定的文档路径或文本内容以及指示所传递内容的标志初始化 Document 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePathOrTextContent | java.lang.String | 文件路径 |
|
|  | isLoadText | boolean | 是否加载文本 |
|

### Document(InputStream inputStream, LoadOptions loadOptions) {#Document-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Document(InputStream inputStream, LoadOptions loadOptions)
```


使用指定的文档流和加载选项初始化 Document 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | inputStream | java.io.InputStream | 文档流 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | 加载选项 |
|

### getChanges() {#getChanges--}
```
public final List<ChangeInfo> getChanges()
```


获取一个 [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) 对象列表，表示在比较过程中检测到的更改。


使用此方法获取源文档与目标文档之间更改的详细信息。
每个 [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) 对象包含诸如更改类型、受影响区域等信息，
以及更改前后的内容。


**Returns:**
java.util.List<com.groupdocs.comparison.result.ChangeInfo> - 一个包含在比较过程中检测到的更改的 [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) 对象的列表

### setChanges(List<ChangeInfo> value) {#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--}
```
public final void setChanges(List<ChangeInfo> value)
```


设置一个 [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) 对象列表，表示在比较过程中检测到的更改。


使用此方法获取源文档与目标文档之间更改的详细信息。
每个 [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) 对象包含诸如更改类型、受影响区域等信息，
以及更改前后的内容。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | java.util.List<com.groupdocs.comparison.result.ChangeInfo> | 一个包含在比较过程中检测到的更改的 [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) 对象的列表 |
|

### getName() {#getName--}
```
public final String getName()
```


获取文档的名称。


**Returns:**
java.lang.String - 文档的名称

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


设置文档的名称。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.lang.String | 文档的名称 |
|

### getFileType() {#getFileType--}
```
public FileType getFileType()
```


获取文档的类型。


**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the type of the document

### setFileType(FileType fileType) {#setFileType-com.groupdocs.comparison.result.FileType-}
```
public void setFileType(FileType fileType)
```


设置文档的类型。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.comparison.result/filetype) | 文档的类型 |
|

### createStream() {#createStream--}
```
public InputStream createStream()
```


创建包含文档内容的新流。


**Returns:**
java.io.InputStream - 包含文档内容的流

### getStreamLength() {#getStreamLength--}
```
public long getStreamLength()
```


获取文档的大小


**Returns:**
long - 文档的大小

### getPassword() {#getPassword--}
```
public String getPassword()
```


获取文档的密码


**Returns:**
java.lang.String - 文档的密码

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.comparison.options.PreviewOptions-}
```
public final void generatePreview(PreviewOptions previewOptions)
```


根据提供的 [PreviewOptions](../../com.groupdocs.comparison.options/previewoptions) 生成文档预览。


此方法根据指定的选项（例如预览格式）生成文档页面的预览，
页码和输出流提供程序。生成的预览可以根据需要保存或进一步处理。

* Learn more about how to generate previews for document pages: [How to generate document pages preview using GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Generate+document+pages+preview)


示例用法：

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | previewOptions | [PreviewOptions](../../com.groupdocs.comparison.options/previewoptions) | 指定格式、页码等的预览选项 |
|

### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


获取有关文档的信息，包括文档类型、页数、页面尺寸等。

* Learn more about document file type, page count, size, and other format-specific properties: [How to get document info using GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Get+file+info)


**Returns:**
[IDocumentInfo](../../com.groupdocs.comparison.interfaces/idocumentinfo) - the document information

### close() {#close--}
```
public void close()
```




