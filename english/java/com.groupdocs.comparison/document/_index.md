---
title: Document
second_title: GroupDocs.Comparison for Java API Reference
description: Represents compared document.
type: docs
weight: 12
url: /java/com.groupdocs.comparison/document/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Document implements Closeable
```

Represents compared document.
## Constructors

| Constructor | Description |
| --- | --- |
| [Document(InputStream stream)](#Document-java.io.InputStream-) | Initializes new instance of [Document](../../com.groupdocs.comparison/document) class. |
| [Document(String filePath)](#Document-java.lang.String-) | Initializes new instance of [Document](../../com.groupdocs.comparison/document) class. |
| [Document(Path filePath)](#Document-java.nio.file.Path-) | Initializes new instance of [Document](../../com.groupdocs.comparison/document) class. |
| [Document(Path filePath, String password)](#Document-java.nio.file.Path-java.lang.String-) | Initializes new instance of [Document](../../com.groupdocs.comparison/document) class. |
| [Document(Path filePath, LoadOptions loadOptions)](#Document-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-) | Initializes new instance of [Document](../../com.groupdocs.comparison/document) class. |
| [Document(String filePath, String password)](#Document-java.lang.String-java.lang.String-) | Initializes new instance of [Document](../../com.groupdocs.comparison/document) class. |
| [Document(String filePath, LoadOptions loadOptions)](#Document-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-) | Initializes new instance of [Document](../../com.groupdocs.comparison/document) class. |
| [Document(InputStream stream, String password)](#Document-java.io.InputStream-java.lang.String-) | Initializes new instance of [Document](../../com.groupdocs.comparison/document) class. |
| [Document(String filePath, boolean isLoadText)](#Document-java.lang.String-boolean-) | Initializes new instance of [Document](../../com.groupdocs.comparison/document) class. |
| [Document(InputStream inputStream, LoadOptions loadOptions)](#Document-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getChanges()](#getChanges--) | List of changes. |
| [setChanges(List<ChangeInfo> value)](#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--) | List of changes. |
| [getName()](#getName--) | Document name. |
| [setName(String value)](#setName-java.lang.String-) | Document name. |
| [getFileType()](#getFileType--) |  |
| [setFileType(FileType fileType)](#setFileType-com.groupdocs.comparison.result.FileType-) |  |
| [createStream()](#createStream--) | Document stream. |
| [getStreamLength()](#getStreamLength--) |  |
| [getPassword()](#getPassword--) | Document password. |
| [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.comparison.options.PreviewOptions-) | Generates document pages preview. |
| [getDocumentInfo()](#getDocumentInfo--) | Gets information about document - document type, pages count, page sizes etc. |
| [close()](#close--) |  |
### Document(InputStream stream) {#Document-java.io.InputStream-}
```
public Document(InputStream stream)
```


Initializes new instance of [Document](../../com.groupdocs.comparison/document) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Document stream |

### Document(String filePath) {#Document-java.lang.String-}
```
public Document(String filePath)
```


Initializes new instance of [Document](../../com.groupdocs.comparison/document) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Document path |

### Document(Path filePath) {#Document-java.nio.file.Path-}
```
public Document(Path filePath)
```


Initializes new instance of [Document](../../com.groupdocs.comparison/document) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.nio.file.Path | Document path |

### Document(Path filePath, String password) {#Document-java.nio.file.Path-java.lang.String-}
```
public Document(Path filePath, String password)
```


Initializes new instance of [Document](../../com.groupdocs.comparison/document) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.nio.file.Path | Document path |
| password | java.lang.String | Document password |

### Document(Path filePath, LoadOptions loadOptions) {#Document-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Document(Path filePath, LoadOptions loadOptions)
```


Initializes new instance of [Document](../../com.groupdocs.comparison/document) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.nio.file.Path | Document path |
| loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Load options |

### Document(String filePath, String password) {#Document-java.lang.String-java.lang.String-}
```
public Document(String filePath, String password)
```


Initializes new instance of [Document](../../com.groupdocs.comparison/document) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Document path |
| password | java.lang.String | Document password |

### Document(String filePath, LoadOptions loadOptions) {#Document-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Document(String filePath, LoadOptions loadOptions)
```


Initializes new instance of [Document](../../com.groupdocs.comparison/document) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Document path |
| loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Load options |

### Document(InputStream stream, String password) {#Document-java.io.InputStream-java.lang.String-}
```
public Document(InputStream stream, String password)
```


Initializes new instance of [Document](../../com.groupdocs.comparison/document) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Document stream |
| password | java.lang.String | Document password |

### Document(String filePath, boolean isLoadText) {#Document-java.lang.String-boolean-}
```
public Document(String filePath, boolean isLoadText)
```


Initializes new instance of [Document](../../com.groupdocs.comparison/document) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | the file path |
| isLoadText | boolean | the is load text |

### Document(InputStream inputStream, LoadOptions loadOptions) {#Document-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Document(InputStream inputStream, LoadOptions loadOptions)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream |  |
| loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) |  |

### getChanges() {#getChanges--}
```
public final List<ChangeInfo> getChanges()
```


List of changes.

**Returns:**
java.util.List<com.groupdocs.comparison.result.ChangeInfo> - the changes
### setChanges(List<ChangeInfo> value) {#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--}
```
public final void setChanges(List<ChangeInfo> value)
```


List of changes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.List<com.groupdocs.comparison.result.ChangeInfo> | the value |

### getName() {#getName--}
```
public final String getName()
```


Document name.

**Returns:**
java.lang.String - the name
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Document name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | the value |

### getFileType() {#getFileType--}
```
public FileType getFileType()
```




**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype)
### setFileType(FileType fileType) {#setFileType-com.groupdocs.comparison.result.FileType-}
```
public void setFileType(FileType fileType)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.comparison.result/filetype) |  |

### createStream() {#createStream--}
```
public InputStream createStream()
```


Document stream.

**Returns:**
java.io.InputStream - the stream
### getStreamLength() {#getStreamLength--}
```
public long getStreamLength()
```




**Returns:**
long
### getPassword() {#getPassword--}
```
public String getPassword()
```


Document password.

**Returns:**
java.lang.String - the password
### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.comparison.options.PreviewOptions-}
```
public final void generatePreview(PreviewOptions previewOptions)
```


Generates document pages preview.

 *  Learn more about how to generate previews for document pages: [How to generate document pages preview using GroupDocs.Comparison][]


[How to generate document pages preview using GroupDocs.Comparison]: https://docs.groupdocs.com/display/comparisonjava/Generate+document+pages+preview

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| previewOptions | [PreviewOptions](../../com.groupdocs.comparison.options/previewoptions) | The document preview options |

### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Gets information about document - document type, pages count, page sizes etc.

 *  Learn more about document file type, pages count, size and many other format specific properties: [How to get document info using GroupDocs.Comparison][]


[How to get document info using GroupDocs.Comparison]: https://docs.groupdocs.com/display/comparisonjava/Get+file+info

**Returns:**
[IDocumentInfo](../../com.groupdocs.comparison.interfaces/idocumentinfo) - document info
### close() {#close--}
```
public void close()
```




