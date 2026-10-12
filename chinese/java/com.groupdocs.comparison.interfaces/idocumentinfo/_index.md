---
title: "IDocumentInfo"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "提供对文档属性的访问。"
type: docs
weight: 10
url: /zh/java/com.groupdocs.comparison.interfaces/idocumentinfo/
---
**All Implemented Interfaces:**
java.io.Closeable
```
public interface IDocumentInfo extends Closeable
```

提供对文档属性的访问。


关于其用法的更多细节可在 [Document.getDocumentInfo()](../../com.groupdocs.comparison/document#getDocumentInfo--) 方法或在 [documentation](../https://docs.groupdocs.com/comparison/java/get-file-info/) 中找到。


示例用法：

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    try (IDocumentInfo documentInfo = comparer.getSource().getDocumentInfo()) {
      for (int i = 0; i < documentInfo.getPageCount(); i++) {
          System.out.printf("File type: %s%nNumber of pages: %d", documentInfo.getFileType().getFileFormat(), documentInfo.getPageCount());
      }
    }
 }
 
````


## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getFileType()](#getFileType--) | 获取文件的类型，由 [FileType](../../com.groupdocs.comparison.result/filetype) 枚举表示。 |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.comparison.result.FileType-) | 使用 [FileType](../../com.groupdocs.comparison.result/filetype) 枚举设置文件的类型。 |
|
|  | [getPageCount()](#getPageCount--) | 获取文件的计数。 |
|
|  | [setPageCount(int value)](#setPageCount-int-) | 设置文件的计数。 |
|
|  | [getSize()](#getSize--) | 获取文件的大小。 |
|
|  | [setSize(long value)](#setSize-long-) | 设置文件的大小。 |
|
|  | [getPagesInfo()](#getPagesInfo--) | 使用 [PageInfo](../../com.groupdocs.comparison.result/pageinfo) 类获取文件每页的信息。 |
|
|  | [setPagesInfo(List<PageInfo> pageInfos)](#setPagesInfo-java.util.List-com.groupdocs.comparison.result.PageInfo--) | 使用 [PageInfo](../../com.groupdocs.comparison.result/pageinfo) 类设置文件每页的信息。 |
|
|  | [close()](#close--) | 销毁对象后，使用此实例的 [IDocumentInfo](../../com.groupdocs.comparison.interfaces/idocumentinfo) 对象将无法获取文档信息。 |
|
### getFileType() {#getFileType--}
```
public abstract FileType getFileType()
```


获取文件的类型，由 [FileType](../../com.groupdocs.comparison.result/filetype) 枚举表示。


**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the type of the file

### setFileType(FileType value) {#setFileType-com.groupdocs.comparison.result.FileType-}
```
public abstract void setFileType(FileType value)
```


使用 [FileType](../../com.groupdocs.comparison.result/filetype) 枚举设置文件的类型。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [FileType](../../com.groupdocs.comparison.result/filetype) | 文件的类型 |
|

### getPageCount() {#getPageCount--}
```
public abstract int getPageCount()
```


获取文件的计数。


**Returns:**
int - 文件的计数

### setPageCount(int value) {#setPageCount-int-}
```
public abstract void setPageCount(int value)
```


设置文件的计数。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | int | 文件的计数 |
|

### getSize() {#getSize--}
```
public abstract long getSize()
```


获取文件的大小。


**Returns:**
long - 文件的大小

### setSize(long value) {#setSize-long-}
```
public abstract void setSize(long value)
```


设置文件的大小。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | long | 文件的大小 |
|

### getPagesInfo() {#getPagesInfo--}
```
public abstract List<PageInfo> getPagesInfo()
```


使用 [PageInfo](../../com.groupdocs.comparison.result/pageinfo) 类获取文件每页的信息。


**Returns:**
java.util.List<com.groupdocs.comparison.result.PageInfo> - 文件中每页的信息

### setPagesInfo(List<PageInfo> pageInfos) {#setPagesInfo-java.util.List-com.groupdocs.comparison.result.PageInfo--}
```
public abstract void setPagesInfo(List<PageInfo> pageInfos)
```


使用 [PageInfo](../../com.groupdocs.comparison.result/pageinfo) 类设置文件每页的信息。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | pageInfos | java.util.List<com.groupdocs.comparison.result.PageInfo> | 文件中每页的信息 |
|

### close() {#close--}
```
public abstract void close()
```


销毁对象后，使用此实例的 [IDocumentInfo](../../com.groupdocs.comparison.interfaces/idocumentinfo) 对象将无法获取文档信息。
同时删除临时文件并释放已使用的资源。


