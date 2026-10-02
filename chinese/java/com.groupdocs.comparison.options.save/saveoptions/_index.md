---
title: "SaveOptions"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "允许在保存文档时指定其他选项。"
type: docs
weight: 10
url: /zh/java/com.groupdocs.comparison.options.save/saveoptions/
---
**Inheritance:**
java.lang.Object
```
public class SaveOptions
```

允许在保存文档时指定其他选项。


示例用法：

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    final SaveOptions saveOptions = new SaveOptions();
    saveOptions.setPassword("passw");

    comparer.compare(resultFile, saveOptions);
 }
 
````


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [SaveOptions()](#SaveOptions--) | 初始化 SaveOptions 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getCloneMetadataType()](#getCloneMetadataType--) | 获取处理元数据保存结果文档的策略。 |
|
|  | [setCloneMetadataType(MetadataType value)](#setCloneMetadataType-com.groupdocs.comparison.options.enums.MetadataType-) | 设置处理元数据保存结果文档的策略。 |
|
|  | [getFileAuthorMetadata()](#getFileAuthorMetadata--) | 获取当 [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) 设置为 [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR) 时将被设置到结果文档中的元数据对象。 |
|
|  | [setFileAuthorMetadata(FileAuthorMetadata value)](#setFileAuthorMetadata-com.groupdocs.comparison.options.FileAuthorMetadata-) | 设置当 [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) 设置为 [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR) 时应当被设置到结果文档中的元数据对象。 |
|
|  | [getPassword()](#getPassword--) | 获取结果文档的密码。 |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 设置结果文档的密码。 |
|
|  | [getFolderPath()](#getFolderPath--) | 获取将保存结果图像的文件夹路径。 |
|
|  | [setFolderPath(String value)](#setFolderPath-java.lang.String-) | 设置应保存结果图像的文件夹路径。 |
|
|  | [setFolderPath(Path value)](#setFolderPath-java.nio.file.Path-) | 设置应保存结果图像的文件夹路径。 |
|
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```


初始化 SaveOptions 类的新实例。


### getCloneMetadataType() {#getCloneMetadataType--}
```
public final MetadataType getCloneMetadataType()
```


获取处理元数据保存结果文档的策略。
可能的值位于枚举 [MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) 中


**Returns:**
[MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) - the stragegy of processing metadata

### setCloneMetadataType(MetadataType value) {#setCloneMetadataType-com.groupdocs.comparison.options.enums.MetadataType-}
```
public final void setCloneMetadataType(MetadataType value)
```


设置处理元数据保存结果文档的策略。
可能的值位于枚举 [MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) 中


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) | 处理元数据的策略 |
|

### getFileAuthorMetadata() {#getFileAuthorMetadata--}
```
public final FileAuthorMetadata getFileAuthorMetadata()
```


获取当 [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) 设置为 [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR) 时将被设置到结果文档中的元数据对象。


**Returns:**
[FileAuthorMetadata](../../com.groupdocs.comparison.options/fileauthormetadata) - the metadata object

### setFileAuthorMetadata(FileAuthorMetadata value) {#setFileAuthorMetadata-com.groupdocs.comparison.options.FileAuthorMetadata-}
```
public final void setFileAuthorMetadata(FileAuthorMetadata value)
```


设置当 [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) 设置为 [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR) 时应当被设置到结果文档中的元数据对象。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [FileAuthorMetadata](../../com.groupdocs.comparison.options/fileauthormetadata) | 元数据对象 |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


获取结果文档的密码。


**Returns:**
java.lang.String - 密码

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


设置结果文档的密码。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.lang.String | 密码 |
|

### getFolderPath() {#getFolderPath--}
```
public final String getFolderPath()
```


获取将保存结果图像的文件夹路径。
仅用于图像比较。


**Returns:**
java.lang.String - 保存结果图像的文件夹路径

### setFolderPath(String value) {#setFolderPath-java.lang.String-}
```
public final void setFolderPath(String value)
```


设置应保存结果图像的文件夹路径。
仅用于图像比较。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.lang.String | 保存结果图像的文件夹路径 |
|

### setFolderPath(Path value) {#setFolderPath-java.nio.file.Path-}
```
public final void setFolderPath(Path value)
```


设置应保存结果图像的文件夹路径。
仅用于图像比较。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.nio.file.Path | 保存结果图像的文件夹路径 |
|

