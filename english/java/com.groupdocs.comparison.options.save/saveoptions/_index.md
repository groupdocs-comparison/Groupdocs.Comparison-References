---
title: SaveOptions
second_title: GroupDocs.Comparison for Java API Reference
description: Allows to specify additional options such as password when saving a document.
type: docs
weight: 10
url: /java/com.groupdocs.comparison.options.save/saveoptions/
---
**Inheritance:**
java.lang.Object
```
public class SaveOptions
```

Allows to specify additional options (such as password) when saving a document.
## Constructors

| Constructor | Description |
| --- | --- |
| [SaveOptions()](#SaveOptions--) | Initializes a new instance of the [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [getCloneMetadataType()](#getCloneMetadataType--) | Gets or sets a value indicating whether to clone metadata to target document or not. |
| [setCloneMetadataType(MetadataType value)](#setCloneMetadataType-com.groupdocs.comparison.options.enums.MetadataType-) | Gets or sets a value indicating whether to clone metadata to target document or not. |
| [getFileAuthorMetadata()](#getFileAuthorMetadata--) | Used when MetadataType is set to FileAuthor. |
| [setFileAuthorMetadata(FileAuthorMetadata value)](#setFileAuthorMetadata-com.groupdocs.comparison.options.FileAuthorMetadata-) | Used when MetadataType is set to FileAuthor. |
| [getPassword()](#getPassword--) | Gets or sets the password for result document. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Gets or sets the password for result document. |
| [getFolderPath()](#getFolderPath--) | Gets or sets the folder path for saving result images(For Imaging Comparison only). |
| [setFolderPath(String value)](#setFolderPath-java.lang.String-) | Gets or sets the folder path for saving result images(For Imaging Comparison only). |
| [setFolderPath(Path value)](#setFolderPath-java.nio.file.Path-) | Gets or sets the folder path for saving result images(For Imaging Comparison only). |
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```


Initializes a new instance of the [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) class.

### getCloneMetadataType() {#getCloneMetadataType--}
```
public final MetadataType getCloneMetadataType()
```


Gets or sets a value indicating whether to clone metadata to target document or not.

**Returns:**
[MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) - the clone metadata type
### setCloneMetadataType(MetadataType value) {#setCloneMetadataType-com.groupdocs.comparison.options.enums.MetadataType-}
```
public final void setCloneMetadataType(MetadataType value)
```


Gets or sets a value indicating whether to clone metadata to target document or not.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) | the value |

### getFileAuthorMetadata() {#getFileAuthorMetadata--}
```
public final FileAuthorMetadata getFileAuthorMetadata()
```


Used when MetadataType is set to FileAuthor.

**Returns:**
[FileAuthorMetadata](../../com.groupdocs.comparison.options/fileauthormetadata) - the file author metadata
### setFileAuthorMetadata(FileAuthorMetadata value) {#setFileAuthorMetadata-com.groupdocs.comparison.options.FileAuthorMetadata-}
```
public final void setFileAuthorMetadata(FileAuthorMetadata value)
```


Used when MetadataType is set to FileAuthor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [FileAuthorMetadata](../../com.groupdocs.comparison.options/fileauthormetadata) | the value |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Gets or sets the password for result document.

**Returns:**
java.lang.String - the password
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Gets or sets the password for result document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | the value |

### getFolderPath() {#getFolderPath--}
```
public final String getFolderPath()
```


Gets or sets the folder path for saving result images(For Imaging Comparison only).

**Returns:**
java.lang.String - the folder path
### setFolderPath(String value) {#setFolderPath-java.lang.String-}
```
public final void setFolderPath(String value)
```


Gets or sets the folder path for saving result images(For Imaging Comparison only).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | the value |

### setFolderPath(Path value) {#setFolderPath-java.nio.file.Path-}
```
public final void setFolderPath(Path value)
```


Gets or sets the folder path for saving result images(For Imaging Comparison only).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.nio.file.Path | the value |

