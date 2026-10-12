---
title: "RevisionHandler"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "表示控制修订处理的类。"
type: docs
weight: 11
url: /zh/java/com.groupdocs.comparison.words.revision/revisionhandler/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class RevisionHandler implements Closeable
```

表示控制修订处理的类。


RevisionHandler 类允许您在文档中处理修订。
它提供了检索修订列表、对修订应用更改以及保存修改后文档的方法。


示例用法：

````

 try (RevisionHandler revisionHandler = new RevisionHandler(sourceFile)) {
     List revisionList = revisionHandler.getRevisions();

     for (RevisionInfo revisionInfo : revisionList) {
         if (revisionInfo.getType() == RevisionType.DELETION)
             // Set an action to be applied to the revision
             revisionInfo.setAction(RevisionAction.Accept);
     }
     // Create an instance of ApplyRevisionOptions
     ApplyRevisionOptions revisionChanges = new ApplyRevisionOptions();
     revisionChanges.setChanges(revisionList);
     // Apply the revisions using the options
     revisionHandler.applyRevisionChanges(resultFile, revisionChanges);
 }
 
````


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [RevisionHandler(String filePath)](#RevisionHandler-java.lang.String-) | 使用包含修订的文件路径初始化 RevisionHandler 类的新实例。 |
|
|  | [RevisionHandler(Path filePath)](#RevisionHandler-java.nio.file.Path-) | 使用包含修订的文件路径初始化 RevisionHandler 类的新实例。 |
|
|  | [RevisionHandler(InputStream file, FileType fileType)](#RevisionHandler-java.io.InputStream-com.groupdocs.comparison.result.FileType-) | 使用包含修订的文件流初始化 RevisionHandler 类的新实例。 |
|
|  | [RevisionHandler(Document document)](#RevisionHandler-com.aspose.words.Document-) | 使用文档初始化 RevisionHandler 类的新实例。 |
|
## 字段

| 字段 | 描述 |
| --- | --- |
| [SOURCE_PATH_IS_NULL](#SOURCE-PATH-IS-NULL) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getRevisions()](#getRevisions--) | 获取所有修订的列表。 |
|
|  | [applyRevisionChanges(ApplyRevisionOptions changes)](#applyRevisionChanges-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | 处理修订中的更改并将其应用于原始文件。 |
|
|  | [applyRevisionChanges(Path filePath, ApplyRevisionOptions changes)](#applyRevisionChanges-java.nio.file.Path-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | 处理修订中的更改并将结果写入指定文件。 |
|
|  | [applyRevisionChanges(String filePath, ApplyRevisionOptions changes)](#applyRevisionChanges-java.lang.String-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | 处理修订中的更改并将结果写入指定文件。 |
|
|  | [applyRevisionChanges(OutputStream outputStream, ApplyRevisionOptions changes)](#applyRevisionChanges-java.io.OutputStream-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | 处理修订中的更改并将结果写入文档流。 |
|
| [close()](#close--) |  |
### RevisionHandler(String filePath) {#RevisionHandler-java.lang.String-}
```
public RevisionHandler(String filePath)
```


使用包含修订的文件路径初始化 RevisionHandler 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.lang.String | 文件的路径。 |
|

### RevisionHandler(Path filePath) {#RevisionHandler-java.nio.file.Path-}
```
public RevisionHandler(Path filePath)
```


使用包含修订的文件路径初始化 RevisionHandler 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 文件的路径。 |
|

### RevisionHandler(InputStream file, FileType fileType) {#RevisionHandler-java.io.InputStream-com.groupdocs.comparison.result.FileType-}
```
public RevisionHandler(InputStream file, FileType fileType)
```


使用包含修订的文件流初始化 RevisionHandler 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文件 | java.io.InputStream | 源文档流。 |
|
|  | fileType | [FileType](../../com.groupdocs.comparison.result/filetype) | 文件的类型。 |
|

### RevisionHandler(Document document) {#RevisionHandler-com.aspose.words.Document-}
```
public RevisionHandler(Document document)
```


使用文档初始化 RevisionHandler 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文档 | com.aspose.words.Document | 文档。 |
|

### SOURCE_PATH_IS_NULL {#SOURCE-PATH-IS-NULL}
```
public static final String SOURCE_PATH_IS_NULL
```


### getRevisions() {#getRevisions--}
```
public List<RevisionInfo> getRevisions()
```


获取所有修订的列表。


由于修订最初是按组排序的，必须从 List 中获取修订。
在 List 中，单个修订可以拆分为具有相同通用文本的多个修订。
由于 List 可能包含具有相同通用文本的修订，在为用户创建修订列表时必须进行控制。
这里使用 List\<RevisionGroup\> 组进行控制。


**Returns:**
java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> - 修订列表。

### applyRevisionChanges(ApplyRevisionOptions changes) {#applyRevisionChanges-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(ApplyRevisionOptions changes)
```


处理修订中的更改并将其应用于原始文件。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | 已更改修订的列表。 |
|

### applyRevisionChanges(Path filePath, ApplyRevisionOptions changes) {#applyRevisionChanges-java.nio.file.Path-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(Path filePath, ApplyRevisionOptions changes)
```


处理修订中的更改并将结果写入指定文件。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 结果文件路径。 |
|
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | 已更改修订的列表。 |
|

### applyRevisionChanges(String filePath, ApplyRevisionOptions changes) {#applyRevisionChanges-java.lang.String-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(String filePath, ApplyRevisionOptions changes)
```


处理修订中的更改并将结果写入指定文件。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.lang.String | 结果文件路径。 |
|
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | 已更改修订的列表。 |
|

### applyRevisionChanges(OutputStream outputStream, ApplyRevisionOptions changes) {#applyRevisionChanges-java.io.OutputStream-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(OutputStream outputStream, ApplyRevisionOptions changes)
```


处理修订中的更改并将结果写入文档流。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | outputStream | java.io.OutputStream | 结果文档流。 |
|
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | 已更改修订的列表。 |
|

### close() {#close--}
```
public void close()
```




