---
title: LoadOptions
second_title: GroupDocs.Comparison for Java API Reference
description: Allows specifying additional options when loading a document.
type: docs
weight: 10
url: /java/com.groupdocs.comparison.options.load/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

Allows specifying additional options when loading a document.


Example usage:

````

 final LoadOptions loadOptions = new LoadOptions();
 loadOptions.setPassword("passw");
 loadOptions.setFileType(FileType.PDF);

 try (Comparer comparer = new Comparer(sourceFile, loadOptions)) {
    comparer.add(targetFile);

    comparer.compare(resultFile);
 }
 
````


## Constructors

| Constructor | Description |
| --- | --- |
| [LoadOptions()](#LoadOptions--) | Initializes a new instance of the LoadOptions class.
 |
| [LoadOptions(boolean isLoadText)](#LoadOptions-boolean-) | Initializes a new instance of the LoadOptions class with a flag which means that input string is a text to compare, not path.
 |
| [LoadOptions(String password)](#LoadOptions-java.lang.String-) | Initializes a new instance of the LoadOptions class with a password to load document.
 |
| [LoadOptions(boolean isLoadText, String password)](#LoadOptions-boolean-java.lang.String-) | Initializes a new instance of the LoadOptions class with a flag which means that input string is a text to compare and a password to load document.
 |
| [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.comparison.result.FileType-) | Initializes a new instance of the LoadOptions class with a type of a file.
 |
## Methods

| Method | Description |
| --- | --- |
| [isLoadText()](#isLoadText--) | Gets a flag that indicates that the string passed to [Comparer](../../com.groupdocs.comparison/comparer) constructor or to [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) method is comparison text, not file paths (For Text Comparison only).
 |
| [setLoadText(boolean value)](#setLoadText-boolean-) | Sets a flag that indicates that the string passed to [Comparer](../../com.groupdocs.comparison/comparer) constructor or to [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) method is comparison text, not file paths (For Text Comparison only).
 |
| [getPassword()](#getPassword--) | Gets a password that will be used to load a document.
 |
| [setPassword(String value)](#setPassword-java.lang.String-) | Sets a password that should be used to load a document.
 |
| [getFontDirectories()](#getFontDirectories--) | Gets a list of directories where font files to load a document are placed.
 |
| [setFontDirectories(List<String> value)](#setFontDirectories-java.util.List-java.lang.String--) | Sets a list of directories where font files to load a document are placed.
 |
| [getFileType()](#getFileType--) | Gets a type of a file that is loading.
 |
| [setFileType(FileType value)](#setFileType-com.groupdocs.comparison.result.FileType-) | Sets a type of a file that is loading.
 |
| [isSkipExternalResources()](#isSkipExternalResources--) | Gets whether loading of external resources referenced by a document is disabled.
 |
| [setSkipExternalResources(boolean value)](#setSkipExternalResources-boolean-) | Sets whether loading of external resources referenced by a document is disabled.
 |
| [getWhitelistedResources()](#getWhitelistedResources--) | Gets the resources that are still loaded while #isSkipExternalResources().isSkipExternalResources() is on.
 |
| [setWhitelistedResources(List<String> value)](#setWhitelistedResources-java.util.List-java.lang.String--) | Sets the resources that are still loaded while #isSkipExternalResources().isSkipExternalResources() is on.
 |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


Initializes a new instance of the LoadOptions class.


### LoadOptions(boolean isLoadText) {#LoadOptions-boolean-}
```
public LoadOptions(boolean isLoadText)
```


Initializes a new instance of the LoadOptions class with a flag which means that input string is a text to compare, not path.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isLoadText | boolean | The flag which means that input string is a text to compare, not path
 |

### LoadOptions(String password) {#LoadOptions-java.lang.String-}
```
public LoadOptions(String password)
```


Initializes a new instance of the LoadOptions class with a password to load document.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| password | java.lang.String | The password to load document
 |

### LoadOptions(boolean isLoadText, String password) {#LoadOptions-boolean-java.lang.String-}
```
public LoadOptions(boolean isLoadText, String password)
```


Initializes a new instance of the LoadOptions class with a flag which means that input string is a text to compare and a password to load document.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isLoadText | boolean | The flag which means that input string is a text to compare, not path
 |
| password | java.lang.String | The password to load document
 |

### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.comparison.result.FileType-}
```
public LoadOptions(FileType fileType)
```


Initializes a new instance of the LoadOptions class with a type of a file.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.comparison.result/filetype) | The type of the file
 |

### isLoadText() {#isLoadText--}
```
public boolean isLoadText()
```


Gets a flag that indicates that the string passed to [Comparer](../../com.groupdocs.comparison/comparer) constructor or to [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) method is comparison text, not file paths (For Text Comparison only).


**Returns:**
boolean - true if input string is a text to compare, otherwise false

### setLoadText(boolean value) {#setLoadText-boolean-}
```
public void setLoadText(boolean value)
```


Sets a flag that indicates that the string passed to [Comparer](../../com.groupdocs.comparison/comparer) constructor or to [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) method is comparison text, not file paths (For Text Comparison only).


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | true if input string is a text to compare, otherwise false
 |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Gets a password that will be used to load a document.


**Returns:**
java.lang.String - the password to load the document

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Sets a password that should be used to load a document.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The password to load the document
 |

### getFontDirectories() {#getFontDirectories--}
```
public List<String> getFontDirectories()
```


Gets a list of directories where font files to load a document are placed.


**Returns:**
java.util.List<java.lang.String> - the list of directories with font files

### setFontDirectories(List<String> value) {#setFontDirectories-java.util.List-java.lang.String--}
```
public void setFontDirectories(List<String> value)
```


Sets a list of directories where font files to load a document are placed.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.List<java.lang.String> | The list of directories with font files
 |

### getFileType() {#getFileType--}
```
public FileType getFileType()
```


Gets a type of a file that is loading.


**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the type of the file

### setFileType(FileType value) {#setFileType-com.groupdocs.comparison.result.FileType-}
```
public void setFileType(FileType value)
```


Sets a type of a file that is loading.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.comparison.result/filetype) | The type of the file
 |

### isSkipExternalResources() {#isSkipExternalResources--}
```
public boolean isSkipExternalResources()
```


Gets whether loading of external resources referenced by a document is disabled.


A document can point at resources outside itself, for example an image given by a remote
URL. Loading those means the comparison reaches out to whatever address the document
names, so it is off by default; #getWhitelistedResources().getWhitelistedResources() lets named resources
through while it is on.


**Returns:**
boolean - true when external resources are not loaded, which is the default

### setSkipExternalResources(boolean value) {#setSkipExternalResources-boolean-}
```
public void setSkipExternalResources(boolean value)
```


Sets whether loading of external resources referenced by a document is disabled.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | true to leave external resources unloaded, false to allow them
 |

### getWhitelistedResources() {#getWhitelistedResources--}
```
public List<String> getWhitelistedResources()
```


Gets the resources that are still loaded while #isSkipExternalResources().isSkipExternalResources() is on.


**Returns:**
java.util.List<java.lang.String> - the URL fragments of the allowed resources

### setWhitelistedResources(List<String> value) {#setWhitelistedResources-java.util.List-java.lang.String--}
```
public void setWhitelistedResources(List<String> value)
```


Sets the resources that are still loaded while #isSkipExternalResources().isSkipExternalResources() is on.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.List<java.lang.String> | The URL fragments of the allowed resources
 |

