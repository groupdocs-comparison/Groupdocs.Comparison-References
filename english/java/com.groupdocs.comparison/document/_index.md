---
title: Document
second_title: GroupDocs.Comparison for Java API Reference
description: Represents a document for comparison process.
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

Represents a document for comparison process.

The Document class provides methods to load, generate preview images, and manipulate documents during the comparison process.

Example usage:

```

 try (Comparer comparer = new Comparer(sourceFile)) {
     try (IDocumentInfo info = comparer.getSource().getDocumentInfo()) {
         System.out.println("File type: " + info.getFileType());
         System.out.println("Number of pages: " + info.getPageCount());
         System.out.println("Document size: " + info.getSize());
     }
 }
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [Document(InputStream stream)](#Document-java.io.InputStream-) | Initializes new instance of [Document](../../com.groupdocs.comparison/document) class with the specified document stream. |
| [Document(String filePath)](#Document-java.lang.String-) | Initializes new instance of [Document](../../com.groupdocs.comparison/document) class with the specified document path. |
| [Document(Path filePath)](#Document-java.nio.file.Path-) | Initializes new instance of [Document](../../com.groupdocs.comparison/document) class with the specified document path. |
| [Document(Path filePath, String password)](#Document-java.nio.file.Path-java.lang.String-) | Initializes new instance of [Document](../../com.groupdocs.comparison/document) class with the specified document path and a password. |
| [Document(Path filePath, LoadOptions loadOptions)](#Document-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-) | Initializes new instance of [Document](../../com.groupdocs.comparison/document) class with the specified document path and load options. |
| [Document(String filePath, String password)](#Document-java.lang.String-java.lang.String-) | Initializes new instance of [Document](../../com.groupdocs.comparison/document) class with the specified document path and a password. |
| [Document(String filePath, LoadOptions loadOptions)](#Document-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-) | Initializes new instance of [Document](../../com.groupdocs.comparison/document) class with the specified document path and load options. |
| [Document(InputStream stream, String password)](#Document-java.io.InputStream-java.lang.String-) | Initializes new instance of [Document](../../com.groupdocs.comparison/document) class with the specified document stream and a password. |
| [Document(String filePathOrTextContent, boolean isLoadText)](#Document-java.lang.String-boolean-) | Initializes new instance of [Document](../../com.groupdocs.comparison/document) class with the specified document path or text content and a flag that indicates what was passed. |
| [Document(InputStream inputStream, LoadOptions loadOptions)](#Document-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-) | Initializes new instance of [Document](../../com.groupdocs.comparison/document) class with the specified document stream and load options. |
## Methods

| Method | Description |
| --- | --- |
| [getChanges()](#getChanges--) | Gets a list of [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) objects representing the changes detected during the comparison process. |
| [setChanges(List<ChangeInfo> value)](#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--) | Sets a list of [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) objects representing the changes detected during the comparison process. |
| [getName()](#getName--) | Gets the name of the document. |
| [setName(String value)](#setName-java.lang.String-) | Sets the name of the document. |
| [getFileType()](#getFileType--) | Gets the type of the document. |
| [setFileType(FileType fileType)](#setFileType-com.groupdocs.comparison.result.FileType-) | Sets the type of the document. |
| [createStream()](#createStream--) | Creates new stream with document content. |
| [getStreamLength()](#getStreamLength--) | Gets the size of the document |
| [getPassword()](#getPassword--) | Gets the password of the document |
| [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.comparison.options.PreviewOptions-) | Generates document previews based on the provided [PreviewOptions](../../com.groupdocs.comparison.options/previewoptions). |
| [getDocumentInfo()](#getDocumentInfo--) | Gets information about the document, including document type, page count, page sizes, and more. |
| [close()](#close--) |  |
### Document(InputStream stream) {#Document-java.io.InputStream-}
```
public Document(InputStream stream)
```


Initializes new instance of [Document](../../com.groupdocs.comparison/document) class with the specified document stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Document stream |

### Document(String filePath) {#Document-java.lang.String-}
```
public Document(String filePath)
```


Initializes new instance of [Document](../../com.groupdocs.comparison/document) class with the specified document path.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Document path |

### Document(Path filePath) {#Document-java.nio.file.Path-}
```
public Document(Path filePath)
```


Initializes new instance of [Document](../../com.groupdocs.comparison/document) class with the specified document path.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.nio.file.Path | Document path |

### Document(Path filePath, String password) {#Document-java.nio.file.Path-java.lang.String-}
```
public Document(Path filePath, String password)
```


Initializes new instance of [Document](../../com.groupdocs.comparison/document) class with the specified document path and a password.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.nio.file.Path | Document path |
| password | java.lang.String | Document password |

### Document(Path filePath, LoadOptions loadOptions) {#Document-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Document(Path filePath, LoadOptions loadOptions)
```


Initializes new instance of [Document](../../com.groupdocs.comparison/document) class with the specified document path and load options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.nio.file.Path | Document path |
| loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Load options |

### Document(String filePath, String password) {#Document-java.lang.String-java.lang.String-}
```
public Document(String filePath, String password)
```


Initializes new instance of [Document](../../com.groupdocs.comparison/document) class with the specified document path and a password.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Document path |
| password | java.lang.String | Document password |

### Document(String filePath, LoadOptions loadOptions) {#Document-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Document(String filePath, LoadOptions loadOptions)
```


Initializes new instance of [Document](../../com.groupdocs.comparison/document) class with the specified document path and load options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Document path |
| loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Load options |

### Document(InputStream stream, String password) {#Document-java.io.InputStream-java.lang.String-}
```
public Document(InputStream stream, String password)
```


Initializes new instance of [Document](../../com.groupdocs.comparison/document) class with the specified document stream and a password.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Document stream |
| password | java.lang.String | Document password |

### Document(String filePathOrTextContent, boolean isLoadText) {#Document-java.lang.String-boolean-}
```
public Document(String filePathOrTextContent, boolean isLoadText)
```


Initializes new instance of [Document](../../com.groupdocs.comparison/document) class with the specified document path or text content and a flag that indicates what was passed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePathOrTextContent | java.lang.String | the file path |
| isLoadText | boolean | the is load text |

### Document(InputStream inputStream, LoadOptions loadOptions) {#Document-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Document(InputStream inputStream, LoadOptions loadOptions)
```


Initializes new instance of [Document](../../com.groupdocs.comparison/document) class with the specified document stream and load options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Document stream |
| loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Load options |

### getChanges() {#getChanges--}
```
public final List<ChangeInfo> getChanges()
```


Gets a list of [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) objects representing the changes detected during the comparison process.

Use this method to get detailed information about the changes between the source document and the target document(s). Each [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) object contains information such as the type of change, the affected area, and the content before and after the change.

**Returns:**
java.util.List<com.groupdocs.comparison.result.ChangeInfo> - a list of [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) objects representing the changes detected during the comparison process
### setChanges(List<ChangeInfo> value) {#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--}
```
public final void setChanges(List<ChangeInfo> value)
```


Sets a list of [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) objects representing the changes detected during the comparison process.

Use this method to get detailed information about the changes between the source document and the target document(s). Each [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) object contains information such as the type of change, the affected area, and the content before and after the change.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.List<com.groupdocs.comparison.result.ChangeInfo> | a list of [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) objects representing the changes detected during the comparison process |

### getName() {#getName--}
```
public final String getName()
```


Gets the name of the document.

**Returns:**
java.lang.String - the name of the document
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Sets the name of the document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | the name of the document |

### getFileType() {#getFileType--}
```
public FileType getFileType()
```


Gets the type of the document.

**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the type of the document
### setFileType(FileType fileType) {#setFileType-com.groupdocs.comparison.result.FileType-}
```
public void setFileType(FileType fileType)
```


Sets the type of the document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.comparison.result/filetype) | the type of the document |

### createStream() {#createStream--}
```
public InputStream createStream()
```


Creates new stream with document content.

**Returns:**
java.io.InputStream - the stream with document content
### getStreamLength() {#getStreamLength--}
```
public long getStreamLength()
```


Gets the size of the document

**Returns:**
long - the size of the document
### getPassword() {#getPassword--}
```
public String getPassword()
```


Gets the password of the document

**Returns:**
java.lang.String - the password of the document
### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.comparison.options.PreviewOptions-}
```
public final void generatePreview(PreviewOptions previewOptions)
```


Generates document previews based on the provided [PreviewOptions](../../com.groupdocs.comparison.options/previewoptions).

This method generates previews of the document pages according to the specified options, such as preview format, page numbers, and output stream provider. The generated previews can be saved or further processed as needed.

 *  Learn more about how to generate previews for document pages: [How to generate document pages preview using GroupDocs.Comparison][]

Example usage:

```

 try (Comparer comparer = new Comparer(sourceFile)) {
     PreviewOptions previewOptions = new PreviewOptions(
             pageNumber -> Files.newOutputStream(Paths.get("preview-image-page-" + pageNumber + ".png"))
     );
     previewOptions.setPreviewFormat(PreviewFormats.PNG);
     previewOptions.setPageNumbers(new int[]{1, 2});
     comparer.getSource().generatePreview(previewOptions);
 }
 
```


[How to generate document pages preview using GroupDocs.Comparison]: https://docs.groupdocs.com/display/comparisonjava/Generate+document+pages+preview

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| previewOptions | [PreviewOptions](../../com.groupdocs.comparison.options/previewoptions) | The preview options specifying the format, page numbers and so on |

### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Gets information about the document, including document type, page count, page sizes, and more.

 *  Learn more about document file type, page count, size, and other format-specific properties: [ How to get document info using GroupDocs.Comparison][How to get document info using GroupDocs.Comparison]


[How to get document info using GroupDocs.Comparison]: https://docs.groupdocs.com/display/comparisonjava/Get+file+info

**Returns:**
[IDocumentInfo](../../com.groupdocs.comparison.interfaces/idocumentinfo) - the document information
### close() {#close--}
```
public void close()
```




