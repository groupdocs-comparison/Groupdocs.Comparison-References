---
title: "LoadOptions"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "允许在加载文档时指定其他选项。"
type: docs
weight: 10
url: /zh/java/com.groupdocs.comparison.options.load/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

允许在加载文档时指定其他选项。


示例用法：

````

 final LoadOptions loadOptions = new LoadOptions();
 loadOptions.setPassword("passw");
 loadOptions.setFileType(FileType.PDF);

 try (Comparer comparer = new Comparer(sourceFile, loadOptions)) {
    comparer.add(targetFile);

    comparer.compare(resultFile);
 }
 
````


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [LoadOptions()](#LoadOptions--) | 初始化 LoadOptions 类的新实例。 |
|
|  | [LoadOptions(boolean isLoadText)](#LoadOptions-boolean-) | 使用一个标志初始化 LoadOptions 类的新实例，该标志表示输入字符串是要比较的文本，而不是路径。 |
|
|  | [LoadOptions(String password)](#LoadOptions-java.lang.String-) | 使用密码初始化 LoadOptions 类的新实例，以加载文档。 |
|
|  | [LoadOptions(boolean isLoadText, String password)](#LoadOptions-boolean-java.lang.String-) | 使用一个标志初始化 LoadOptions 类的新实例，该标志表示输入字符串是要比较的文本并且提供用于加载文档的密码。 |
|
|  | [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.comparison.result.FileType-) | 使用文件类型初始化 LoadOptions 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [isLoadText()](#isLoadText--) | 获取一个标志，指示传递给 [Comparer](../../com.groupdocs.comparison/comparer) 构造函数或 [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) 方法的字符串是比较文本，而不是文件路径（仅用于文本比较）。 |
|
|  | [setLoadText(boolean value)](#setLoadText-boolean-) | 设置一个标志，指示传递给 [Comparer](../../com.groupdocs.comparison/comparer) 构造函数或 [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) 方法的字符串是比较文本，而不是文件路径（仅用于文本比较）。 |
|
|  | [getPassword()](#getPassword--) | 获取用于加载文档的密码。 |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 设置用于加载文档的密码。 |
|
|  | [getFontDirectories()](#getFontDirectories--) | 获取放置用于加载文档的字体文件的目录列表。 |
|
|  | [setFontDirectories(List<String> value)](#setFontDirectories-java.util.List-java.lang.String--) | 设置放置用于加载文档的字体文件的目录列表。 |
|
|  | [getFileType()](#getFileType--) | 获取正在加载的文件类型。 |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.comparison.result.FileType-) | 设置正在加载的文件类型。 |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


初始化 LoadOptions 类的新实例。


### LoadOptions(boolean isLoadText) {#LoadOptions-boolean-}
```
public LoadOptions(boolean isLoadText)
```


使用一个标志初始化 LoadOptions 类的新实例，该标志表示输入字符串是要比较的文本，而不是路径。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | isLoadText | boolean | 该标志表示输入字符串是要比较的文本，而不是路径 |
|

### LoadOptions(String password) {#LoadOptions-java.lang.String-}
```
public LoadOptions(String password)
```


使用密码初始化 LoadOptions 类的新实例，以加载文档。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 密码 | java.lang.String | 加载文档的密码 |
|

### LoadOptions(boolean isLoadText, String password) {#LoadOptions-boolean-java.lang.String-}
```
public LoadOptions(boolean isLoadText, String password)
```


使用一个标志初始化 LoadOptions 类的新实例，该标志表示输入字符串是要比较的文本并且提供用于加载文档的密码。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | isLoadText | boolean | 该标志表示输入字符串是要比较的文本，而不是路径 |
|
|  | 密码 | java.lang.String | 加载文档的密码 |
|

### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.comparison.result.FileType-}
```
public LoadOptions(FileType fileType)
```


使用文件类型初始化 LoadOptions 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.comparison.result/filetype) | 文件的类型 |
|

### isLoadText() {#isLoadText--}
```
public boolean isLoadText()
```


获取一个标志，指示传递给 [Comparer](../../com.groupdocs.comparison/comparer) 构造函数或 [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) 方法的字符串是比较文本，而不是文件路径（仅用于文本比较）。


**Returns:**
boolean - 如果输入字符串是要比较的文本，则为 true；否则为 false

### setLoadText(boolean value) {#setLoadText-boolean-}
```
public void setLoadText(boolean value)
```


设置一个标志，指示传递给 [Comparer](../../com.groupdocs.comparison/comparer) 构造函数或 [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) 方法的字符串是比较文本，而不是文件路径（仅用于文本比较）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | 如果输入字符串是要比较的文本，则为 true；否则为 false |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


获取用于加载文档的密码。


**Returns:**
java.lang.String - 加载文档的密码

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


设置用于加载文档的密码。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.lang.String | 加载文档的密码 |
|

### getFontDirectories() {#getFontDirectories--}
```
public List<String> getFontDirectories()
```


获取放置用于加载文档的字体文件的目录列表。


**Returns:**
java.util.List<java.lang.String> - 包含字体文件的目录列表

### setFontDirectories(List<String> value) {#setFontDirectories-java.util.List-java.lang.String--}
```
public void setFontDirectories(List<String> value)
```


设置放置用于加载文档的字体文件的目录列表。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.util.List<java.lang.String> | 包含字体文件的目录列表 |
|

### getFileType() {#getFileType--}
```
public FileType getFileType()
```


获取正在加载的文件类型。


**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the type of the file

### setFileType(FileType value) {#setFileType-com.groupdocs.comparison.result.FileType-}
```
public void setFileType(FileType value)
```


设置正在加载的文件类型。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [FileType](../../com.groupdocs.comparison.result/filetype) | 文件的类型 |
|

