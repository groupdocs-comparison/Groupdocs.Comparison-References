---
title: LoadOptions
second_title: GroupDocs.Comparison for Java API Reference
description: Allows to specify additional options when loading a document.
type: docs
weight: 10
url: /java/com.groupdocs.comparison.options.load/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

Allows to specify additional options when loading a document.
## Constructors

| Constructor | Description |
| --- | --- |
| [LoadOptions()](#LoadOptions--) |  |
| [LoadOptions(boolean isLoadText)](#LoadOptions-boolean-) |  |
| [LoadOptions(String password)](#LoadOptions-java.lang.String-) |  |
| [LoadOptions(boolean isLoadText, String password)](#LoadOptions-boolean-java.lang.String-) |  |
| [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.comparison.result.FileType-) |  |
## Methods

| Method | Description |
| --- | --- |
| [isLoadText()](#isLoadText--) | Indicates that the strings passed are comparison text, not file paths (For Text Comparison only). |
| [setLoadText(boolean loadText)](#setLoadText-boolean-) | Indicates that the strings passed are comparison text, not file paths (For Text Comparison only). |
| [getPassword()](#getPassword--) | Password of document. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Password of document. |
| [getFontDirectories()](#getFontDirectories--) | List of font directories to load. |
| [setFontDirectories(List<String> fontDirectories)](#setFontDirectories-java.util.List-java.lang.String--) | List of font directories to load. |
| [getFileType()](#getFileType--) | File type of the document |
| [setFileType(FileType fileType)](#setFileType-com.groupdocs.comparison.result.FileType-) | File type of the document |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


### LoadOptions(boolean isLoadText) {#LoadOptions-boolean-}
```
public LoadOptions(boolean isLoadText)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isLoadText | boolean |  |

### LoadOptions(String password) {#LoadOptions-java.lang.String-}
```
public LoadOptions(String password)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| password | java.lang.String |  |

### LoadOptions(boolean isLoadText, String password) {#LoadOptions-boolean-java.lang.String-}
```
public LoadOptions(boolean isLoadText, String password)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isLoadText | boolean |  |
| password | java.lang.String |  |

### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.comparison.result.FileType-}
```
public LoadOptions(FileType fileType)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.comparison.result/filetype) |  |

### isLoadText() {#isLoadText--}
```
public boolean isLoadText()
```


Indicates that the strings passed are comparison text, not file paths (For Text Comparison only).

**Returns:**
boolean - is enabled or not
### setLoadText(boolean loadText) {#setLoadText-boolean-}
```
public void setLoadText(boolean loadText)
```


Indicates that the strings passed are comparison text, not file paths (For Text Comparison only).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| loadText | boolean | is enabled or not |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Password of document.

**Returns:**
java.lang.String - password
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Password of document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | password |

### getFontDirectories() {#getFontDirectories--}
```
public List<String> getFontDirectories()
```


List of font directories to load.

**Returns:**
java.util.List<java.lang.String> - font directories
### setFontDirectories(List<String> fontDirectories) {#setFontDirectories-java.util.List-java.lang.String--}
```
public void setFontDirectories(List<String> fontDirectories)
```


List of font directories to load.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontDirectories | java.util.List<java.lang.String> | font directories |

### getFileType() {#getFileType--}
```
public FileType getFileType()
```


File type of the document

**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - file type of the document
### setFileType(FileType fileType) {#setFileType-com.groupdocs.comparison.result.FileType-}
```
public void setFileType(FileType fileType)
```


File type of the document

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.comparison.result/filetype) | file type of the document |

