---
title: "FileAuthorMetadata"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "允许配置有关文档作者元数据的信息。"
type: docs
weight: 12
url: /zh/java/com.groupdocs.comparison.options/fileauthormetadata/
---
**Inheritance:**
java.lang.Object
```
public class FileAuthorMetadata
```

允许配置文档作者元数据的信息。


示例用法：

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     SaveOptions saveOptions = new SaveOptions();
     saveOptions.setCloneMetadataType(MetadataType.FILE_AUTHOR);

     final FileAuthorMetadata fileAuthorMetadata = new FileAuthorMetadata();
     fileAuthorMetadata.setAuthor("Tom");
     fileAuthorMetadata.setCompany("GroupDocs");
     fileAuthorMetadata.setLastSaveBy("Jack");

     saveOptions.setFileAuthorMetadata(fileAuthorMetadata);

     comparer.compare(resultFile, saveOptions);
 }
 
````


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [FileAuthorMetadata()](#FileAuthorMetadata--) | 初始化 FileAuthorMetadata 类的新实例。 |
|
## 字段

| 字段 | 描述 |
| --- | --- |
| [GROUP_DOCS](#GROUP-DOCS) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getAuthor()](#getAuthor--) | 获取文档的作者。 |
|
|  | [setAuthor(String value)](#setAuthor-java.lang.String-) | 设置文档的作者。 |
|
|  | [getLastSaveBy()](#getLastSaveBy--) | 获取上次保存文档的人的姓名。 |
|
|  | [setLastSaveBy(String value)](#setLastSaveBy-java.lang.String-) | 设置上次保存文档的人的姓名。 |
|
|  | [getCompany()](#getCompany--) | 获取文档所属公司的名称。 |
|
|  | [setCompany(String value)](#setCompany-java.lang.String-) | 设置文档所属公司的名称。 |
|
### FileAuthorMetadata() {#FileAuthorMetadata--}
```
public FileAuthorMetadata()
```


初始化 FileAuthorMetadata 类的新实例。


### GROUP_DOCS {#GROUP-DOCS}
```
public static final String GROUP_DOCS
```


### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```


获取文档的作者。


**Returns:**
java.lang.String - 作者

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```


设置文档的作者。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.lang.String | 作者 |
|

### getLastSaveBy() {#getLastSaveBy--}
```
public final String getLastSaveBy()
```


获取上次保存文档的人的姓名。


**Returns:**
java.lang.String - 名称

### setLastSaveBy(String value) {#setLastSaveBy-java.lang.String-}
```
public final void setLastSaveBy(String value)
```


设置上次保存文档的人的姓名。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.lang.String | 个人的姓名 |
|

### getCompany() {#getCompany--}
```
public final String getCompany()
```


获取文档所属公司的名称。


**Returns:**
java.lang.String - 公司的名称

### setCompany(String value) {#setCompany-java.lang.String-}
```
public final void setCompany(String value)
```


设置文档所属公司的名称。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.lang.String | 公司的名称 |
|

