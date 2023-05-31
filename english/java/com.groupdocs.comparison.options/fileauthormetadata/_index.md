---
title: FileAuthorMetadata
second_title: GroupDocs.Comparison for Java API Reference
description: Allows configuring information about the documents author metadata.
type: docs
weight: 12
url: /java/com.groupdocs.comparison.options/fileauthormetadata/
---
**Inheritance:**
java.lang.Object
```
public class FileAuthorMetadata
```

Allows configuring information about the document's author metadata.

Example usage:

```

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
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [FileAuthorMetadata()](#FileAuthorMetadata--) | Initializes a new instance of the FileAuthorMetadata class. |
## Fields

| Field | Description |
| --- | --- |
| [GROUP_DOCS](#GROUP-DOCS) |  |
## Methods

| Method | Description |
| --- | --- |
| [getAuthor()](#getAuthor--) | Gets the author of a document. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | Sets the author of a document. |
| [getLastSaveBy()](#getLastSaveBy--) | Gets name of a person who saved the document for the last time. |
| [setLastSaveBy(String value)](#setLastSaveBy-java.lang.String-) | Sets name of a person who saved the document for the last time. |
| [getCompany()](#getCompany--) | Gets name of a company whose document is. |
| [setCompany(String value)](#setCompany-java.lang.String-) | Sets name of a company whose document is. |
### FileAuthorMetadata() {#FileAuthorMetadata--}
```
public FileAuthorMetadata()
```


Initializes a new instance of the FileAuthorMetadata class.

### GROUP_DOCS {#GROUP-DOCS}
```
public static final String GROUP_DOCS
```


### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```


Gets the author of a document.

**Returns:**
java.lang.String - the author
### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```


Sets the author of a document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The author |

### getLastSaveBy() {#getLastSaveBy--}
```
public final String getLastSaveBy()
```


Gets name of a person who saved the document for the last time.

**Returns:**
java.lang.String - the name
### setLastSaveBy(String value) {#setLastSaveBy-java.lang.String-}
```
public final void setLastSaveBy(String value)
```


Sets name of a person who saved the document for the last time.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The name of a person |

### getCompany() {#getCompany--}
```
public final String getCompany()
```


Gets name of a company whose document is.

**Returns:**
java.lang.String - the name of a company
### setCompany(String value) {#setCompany-java.lang.String-}
```
public final void setCompany(String value)
```


Sets name of a company whose document is.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The name of a company |

