---
title: SaveOptions
second_title: GroupDocs.Comparison for Java API Reference
description: Allows specifying additional options when saving a document.
type: docs
weight: 10
url: /java/com.groupdocs.comparison.options.save/saveoptions/
---
**Inheritance:**
java.lang.Object
```
public class SaveOptions
```

Allows specifying additional options when saving a document.

Example usage:

```

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    final SaveOptions saveOptions = new SaveOptions();
    saveOptions.setPassword("passw");

    comparer.compare(resultFile, saveOptions);
 }
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [SaveOptions()](#SaveOptions--) | Initializes a new instance of the SaveOptions class. |
## Methods

| Method | Description |
| --- | --- |
| [getCloneMetadataType()](#getCloneMetadataType--) | Gets a strategy of processing metadata saving result document. |
| [setCloneMetadataType(MetadataType value)](#setCloneMetadataType-com.groupdocs.comparison.options.enums.MetadataType-) | Sets a stragegy of processing metadata saving result document. |
| [getFileAuthorMetadata()](#getFileAuthorMetadata--) | Gets a metadata object that will be set into result document when \#setCloneMetadataType(MetadataType).setCloneMetadataType(MetadataType) is set to [MetadataType.FILE\_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype\#FILE-AUTHOR). |
| [setFileAuthorMetadata(FileAuthorMetadata value)](#setFileAuthorMetadata-com.groupdocs.comparison.options.FileAuthorMetadata-) | Sets a metadata object that should be set into result document when \#setCloneMetadataType(MetadataType).setCloneMetadataType(MetadataType) is set to [MetadataType.FILE\_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype\#FILE-AUTHOR). |
| [getPassword()](#getPassword--) | Gets a password for result document. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Sets a password for result document. |
| [getFolderPath()](#getFolderPath--) | Gets a folder path to which result images will be saved. |
| [setFolderPath(String value)](#setFolderPath-java.lang.String-) | Sets a folder path to which result images should be saved. |
| [setFolderPath(Path value)](#setFolderPath-java.nio.file.Path-) | Sets a folder path to which result images should be saved. |
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```


Initializes a new instance of the SaveOptions class.

### getCloneMetadataType() {#getCloneMetadataType--}
```
public final MetadataType getCloneMetadataType()
```


Gets a strategy of processing metadata saving result document.

Possible values are in enum [MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype)

**Returns:**
[MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) - the stragegy of processing metadata
### setCloneMetadataType(MetadataType value) {#setCloneMetadataType-com.groupdocs.comparison.options.enums.MetadataType-}
```
public final void setCloneMetadataType(MetadataType value)
```


Sets a stragegy of processing metadata saving result document.

Possible values are in enum [MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) | The stragegy of processing metadata |

### getFileAuthorMetadata() {#getFileAuthorMetadata--}
```
public final FileAuthorMetadata getFileAuthorMetadata()
```


Gets a metadata object that will be set into result document when \#setCloneMetadataType(MetadataType).setCloneMetadataType(MetadataType) is set to [MetadataType.FILE\_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype\#FILE-AUTHOR).

**Returns:**
[FileAuthorMetadata](../../com.groupdocs.comparison.options/fileauthormetadata) - the metadata object
### setFileAuthorMetadata(FileAuthorMetadata value) {#setFileAuthorMetadata-com.groupdocs.comparison.options.FileAuthorMetadata-}
```
public final void setFileAuthorMetadata(FileAuthorMetadata value)
```


Sets a metadata object that should be set into result document when \#setCloneMetadataType(MetadataType).setCloneMetadataType(MetadataType) is set to [MetadataType.FILE\_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype\#FILE-AUTHOR).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [FileAuthorMetadata](../../com.groupdocs.comparison.options/fileauthormetadata) | The metadata object |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Gets a password for result document.

**Returns:**
java.lang.String - the password
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Sets a password for result document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The password |

### getFolderPath() {#getFolderPath--}
```
public final String getFolderPath()
```


Gets a folder path to which result images will be saved.

Used for Imaging Comparison only.

**Returns:**
java.lang.String - the folder path to save result images
### setFolderPath(String value) {#setFolderPath-java.lang.String-}
```
public final void setFolderPath(String value)
```


Sets a folder path to which result images should be saved.

Used for Imaging Comparison only.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The folder path to save result images |

### setFolderPath(Path value) {#setFolderPath-java.nio.file.Path-}
```
public final void setFolderPath(Path value)
```


Sets a folder path to which result images should be saved.

Used for Imaging Comparison only.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.nio.file.Path | The folder path to save result images |

