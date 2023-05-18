---
title: IDocumentInfo
second_title: GroupDocs.Comparison for Java API Reference
description: Provides access to document properties.
type: docs
weight: 10
url: /java/com.groupdocs.comparison.interfaces/idocumentinfo/
---
**All Implemented Interfaces:**
java.io.Closeable
```
public interface IDocumentInfo extends Closeable
```

Provides access to document properties.

More details about its usage can be found in [Document.getDocumentInfo()](../../com.groupdocs.comparison/document\#getDocumentInfo--) method or in a [documentation][].

Example usage:

```

 try (Comparer comparer = new Comparer(sourceFile)) {
    try (IDocumentInfo documentInfo = comparer.getSource().getDocumentInfo()) {
      for (int i = 0; i < documentInfo.getPageCount(); i++) {
          System.out.printf("File type: %s%nNumber of pages: %d", documentInfo.getFileType().getFileFormat(), documentInfo.getPageCount());
      }
    }
 }
 
```


[documentation]: https://docs.groupdocs.com/comparison/java/get-file-info/
## Methods

| Method | Description |
| --- | --- |
| [getFileType()](#getFileType--) | Gets a type of the file represented by [FileType](../../com.groupdocs.comparison.result/filetype) enum. |
| [setFileType(FileType value)](#setFileType-com.groupdocs.comparison.result.FileType-) | Sets a type of the file using [FileType](../../com.groupdocs.comparison.result/filetype) enum. |
| [getPageCount()](#getPageCount--) | Gets a count of the file. |
| [setPageCount(int value)](#setPageCount-int-) | Sets a count of the file. |
| [getSize()](#getSize--) | Gets a size of the file. |
| [setSize(long value)](#setSize-long-) | Sets a size of the file. |
| [getPagesInfo()](#getPagesInfo--) | Gets information for each page of the file using [PageInfo](../../com.groupdocs.comparison.result/pageinfo) class. |
| [setPagesInfo(List<PageInfo> pageInfos)](#setPagesInfo-java.util.List-com.groupdocs.comparison.result.PageInfo--) | Sets information for each page of the file using [PageInfo](../../com.groupdocs.comparison.result/pageinfo) class. |
| [close()](#close--) | Destroys the object making it impossible to get information of the document using this instance of [IDocumentInfo](../../com.groupdocs.comparison.interfaces/idocumentinfo) object. |
### getFileType() {#getFileType--}
```
public abstract FileType getFileType()
```


Gets a type of the file represented by [FileType](../../com.groupdocs.comparison.result/filetype) enum.

**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the type of the file
### setFileType(FileType value) {#setFileType-com.groupdocs.comparison.result.FileType-}
```
public abstract void setFileType(FileType value)
```


Sets a type of the file using [FileType](../../com.groupdocs.comparison.result/filetype) enum.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.comparison.result/filetype) | The type of the file |

### getPageCount() {#getPageCount--}
```
public abstract int getPageCount()
```


Gets a count of the file.

**Returns:**
int - the count of the file
### setPageCount(int value) {#setPageCount-int-}
```
public abstract void setPageCount(int value)
```


Sets a count of the file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The count of the file |

### getSize() {#getSize--}
```
public abstract long getSize()
```


Gets a size of the file.

**Returns:**
long - the size of the file
### setSize(long value) {#setSize-long-}
```
public abstract void setSize(long value)
```


Sets a size of the file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long | The size of the file |

### getPagesInfo() {#getPagesInfo--}
```
public abstract List<PageInfo> getPagesInfo()
```


Gets information for each page of the file using [PageInfo](../../com.groupdocs.comparison.result/pageinfo) class.

**Returns:**
java.util.List<com.groupdocs.comparison.result.PageInfo> - information for each page of the file
### setPagesInfo(List<PageInfo> pageInfos) {#setPagesInfo-java.util.List-com.groupdocs.comparison.result.PageInfo--}
```
public abstract void setPagesInfo(List<PageInfo> pageInfos)
```


Sets information for each page of the file using [PageInfo](../../com.groupdocs.comparison.result/pageinfo) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageInfos | java.util.List<com.groupdocs.comparison.result.PageInfo> | Information for each page of the file |

### close() {#close--}
```
public abstract void close()
```


Destroys the object making it impossible to get information of the document using this instance of [IDocumentInfo](../../com.groupdocs.comparison.interfaces/idocumentinfo) object.

Also deletes temporary files and releases used resources.

