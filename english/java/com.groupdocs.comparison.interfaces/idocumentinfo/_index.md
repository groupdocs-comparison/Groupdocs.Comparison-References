---
title: IDocumentInfo
second_title: GroupDocs.Comparison for Java API Reference
description: Defines document description properties.
type: docs
weight: 10
url: /java/com.groupdocs.comparison.interfaces/idocumentinfo/
---
**All Implemented Interfaces:**
java.io.Closeable
```
public interface IDocumentInfo extends Closeable
```

Defines document description properties.
## Methods

| Method | Description |
| --- | --- |
| [getFileType()](#getFileType--) | Document type |
| [setFileType(FileType value)](#setFileType-com.groupdocs.comparison.result.FileType-) | Document type |
| [getPageCount()](#getPageCount--) | Number of pages |
| [setPageCount(int value)](#setPageCount-int-) | Number of pages |
| [getSize()](#getSize--) | File size |
| [setSize(long value)](#setSize-long-) | File size |
| [getPagesInfo()](#getPagesInfo--) | Pages Information ( Page Number, Width, Height ) |
| [setPagesInfo(List<PageInfo> pageInfos)](#setPagesInfo-java.util.List-com.groupdocs.comparison.result.PageInfo--) | Pages Information ( Page Number, Width, Height ) |
| [close()](#close--) |  |
### getFileType() {#getFileType--}
```
public abstract FileType getFileType()
```


Document type

**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the file type
### setFileType(FileType value) {#setFileType-com.groupdocs.comparison.result.FileType-}
```
public abstract void setFileType(FileType value)
```


Document type

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.comparison.result/filetype) | the value |

### getPageCount() {#getPageCount--}
```
public abstract int getPageCount()
```


Number of pages

**Returns:**
int - the page count
### setPageCount(int value) {#setPageCount-int-}
```
public abstract void setPageCount(int value)
```


Number of pages

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | the value |

### getSize() {#getSize--}
```
public abstract long getSize()
```


File size

**Returns:**
long - the size
### setSize(long value) {#setSize-long-}
```
public abstract void setSize(long value)
```


File size

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long | the value |

### getPagesInfo() {#getPagesInfo--}
```
public abstract List<PageInfo> getPagesInfo()
```


Pages Information ( Page Number, Width, Height )

**Returns:**
java.util.List<com.groupdocs.comparison.result.PageInfo> - Pages Information
### setPagesInfo(List<PageInfo> pageInfos) {#setPagesInfo-java.util.List-com.groupdocs.comparison.result.PageInfo--}
```
public abstract void setPagesInfo(List<PageInfo> pageInfos)
```


Pages Information ( Page Number, Width, Height )

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageInfos | java.util.List<com.groupdocs.comparison.result.PageInfo> | Pages Information |

### close() {#close--}
```
public abstract void close()
```




