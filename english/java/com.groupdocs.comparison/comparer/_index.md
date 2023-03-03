---
title: Comparer
second_title: GroupDocs.Comparison for Java API Reference
description: Represents main class that controls the documents comparison process.
type: docs
weight: 10
url: /java/com.groupdocs.comparison/comparer/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public class Comparer implements System.IDisposable, Closeable
```

Represents main class that controls the documents comparison process.
## Constructors

| Constructor | Description |
| --- | --- |
| [Comparer(String filePath)](#Comparer-java.lang.String-) | Initializes new instance of [Comparer](../../com.groupdocs.comparison/comparer) class with source file path. |
| [Comparer(Path filePath)](#Comparer-java.nio.file.Path-) | Initializes new instance of [Comparer](../../com.groupdocs.comparison/comparer) class with source file path. |
| [Comparer(String filePath, LoadOptions loadOptions)](#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-) | Initializes new instance of [Comparer](../../com.groupdocs.comparison/comparer) with source file path and [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions). |
| [Comparer(Path filePath, LoadOptions loadOptions)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-) | Initializes new instance of [Comparer](../../com.groupdocs.comparison/comparer) with source file path and [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions). |
| [Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings)](#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-) | Initializes new instance of [Comparer](../../com.groupdocs.comparison/comparer) class with source file path, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) and [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
| [Comparer(String filePath, ComparerSettings settings)](#Comparer-java.lang.String-com.groupdocs.comparison.ComparerSettings-) | Initializes new instance of [Comparer](../../com.groupdocs.comparison/comparer) class with source file path and [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
| [Comparer(Path filePath, ComparerSettings settings)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.ComparerSettings-) | Initializes new instance of [Comparer](../../com.groupdocs.comparison/comparer) class with source file path and [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
| [Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-) | Initializes new instance of [Comparer](../../com.groupdocs.comparison/comparer) class with source file path, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) and [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
| [Comparer(InputStream document)](#Comparer-java.io.InputStream-) | Initializes new instance of [Comparer](../../com.groupdocs.comparison/comparer) class with source document stream. |
| [Comparer(InputStream document, LoadOptions loadOptions)](#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-) | Initializes new instance of [Comparer](../../com.groupdocs.comparison/comparer) with source document stream and [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions). |
| [Comparer(InputStream document, ComparerSettings settings)](#Comparer-java.io.InputStream-com.groupdocs.comparison.ComparerSettings-) | Initializes new instance of [Comparer](../../com.groupdocs.comparison/comparer) class with source document stream and [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
| [Comparer(InputStream document, LoadOptions loadOptions, ComparerSettings settings)](#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-) | Initializes new instance of [Comparer](../../com.groupdocs.comparison/comparer) class with document stream, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) and [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
| [Comparer(ComparerSettings settings)](#Comparer-com.groupdocs.comparison.ComparerSettings-) | Instantiates a new Comparer. |
## Fields

| Field | Description |
| --- | --- |
| [FILE_PATH](#FILE-PATH) |  |
## Methods

| Method | Description |
| --- | --- |
| [getSource()](#getSource--) | Source file that is being compared. |
| [getTargets()](#getTargets--) | List of target files to compare with source file. |
| [compare()](#compare--) | Compares documents without saving result with default options |
| [compare(String filePath)](#compare-java.lang.String-) | Compares documents and saves result to file path |
| [compare(Path filePath)](#compare-java.nio.file.Path-) | Compares documents and saves result to file path |
| [compare(OutputStream outputStream)](#compare-java.io.OutputStream-) | Compares documents and saves result to file stream |
| [compare(String filePath, CompareOptions compareOptions)](#compare-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | Compares documents and saves result to file path |
| [compare(Path filePath, CompareOptions compareOptions)](#compare-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | Compares documents and saves result to file path |
| [compare(OutputStream document, CompareOptions compareOptions)](#compare-java.io.OutputStream-com.groupdocs.comparison.options.CompareOptions-) | Compares documents and saves result to file stream |
| [compare(SaveOptions saveOptions, CompareOptions compareOptions)](#compare-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | Compares documents without saving result. |
| [compare(String filePath, SaveOptions saveOptions)](#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-) | Compares documents and save result to file path |
| [compare(Path filePath, SaveOptions saveOptions)](#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-) | Compares documents and save result to file path |
| [compare(OutputStream document, SaveOptions saveOptions)](#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-) | Compares documents and save result to file stream |
| [compare(CompareOptions compareOptions)](#compare-com.groupdocs.comparison.options.CompareOptions-) | Compares documents without saving result. |
| [compare(OutputStream outputStream, SaveOptions saveOptions, CompareOptions compareOptions)](#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | Compares documents and saves result to a stream. |
| [compare(String filePath, SaveOptions saveOptions, CompareOptions compareOptions)](#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | Compares documents and saves result to file path |
| [compare(Path filePath, SaveOptions saveOptions, CompareOptions compareOptions)](#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | Compares documents and saves result to file path |
| [add(String filePath)](#add-java.lang.String-) | Adds file to comparison. |
| [add(Path filePath)](#add-java.nio.file.Path-) | Adds file to comparison. |
| [add(String[] filePaths)](#add-java.lang.String...-) | Adds file to comparison. |
| [add(Path[] filePaths)](#add-java.nio.file.Path...-) | Adds file to comparison. |
| [add(String filePath, LoadOptions loadOptions)](#add-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-) | Adds file to comparison with loading options specified. |
| [add(Path filePath, LoadOptions loadOptions)](#add-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-) | Adds file to comparison with loading options specified. |
| [add(InputStream document)](#add-java.io.InputStream-) | Adds document stream to comparison. |
| [add(InputStream[] documents)](#add-java.io.InputStream...-) | Adds document stream to comparison. |
| [add(InputStream document, LoadOptions loadOptions)](#add-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-) | Adds document stream to comparison with loading options specified. |
| [getChanges()](#getChanges--) | Gets list of changes between source and target file(s). |
| [getChanges(GetChangeOptions getChangeOptions)](#getChanges-com.groupdocs.comparison.options.GetChangeOptions-) | Gets list of changes between source and target file(s). |
| [applyChanges(String filePath, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.lang.String-com.groupdocs.comparison.options.ApplyChangeOptions-) | Accepts or rejects changes and applies them to resultant document. |
| [applyChanges(Path filePath, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.ApplyChangeOptions-) | Accepts or rejects changes and applies them to resultant document. |
| [applyChanges(OutputStream document, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.ApplyChangeOptions-) | Accepts or rejects changes and applies them to resultant document. |
| [applyChanges(String filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-) | Accepts or rejects changes and applies them to resultant document. |
| [applyChanges(Path filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-) | Accepts or rejects changes and applies them to resultant document. |
| [applyChanges(OutputStream document, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-) | Accepts or rejects changes and applies them to resultant document. |
| [getResultString()](#getResultString--) | Get result string after comparison (For Text Comparison only). |
| [close()](#close--) |  |
| [dispose()](#dispose--) | Releases resources. |
### Comparer(String filePath) {#Comparer-java.lang.String-}
```
public Comparer(String filePath)
```


Initializes new instance of [Comparer](../../com.groupdocs.comparison/comparer) class with source file path.

 *  More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison][]
 *  More about GroupDocs.Comparison for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Comparison]: https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/comparisonjava/Developer+Guide

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | File path |

### Comparer(Path filePath) {#Comparer-java.nio.file.Path-}
```
public Comparer(Path filePath)
```


Initializes new instance of [Comparer](../../com.groupdocs.comparison/comparer) class with source file path.

 *  More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison][]
 *  More about GroupDocs.Comparison for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Comparison]: https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/comparisonjava/Developer+Guide

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.nio.file.Path | File path |

### Comparer(String filePath, LoadOptions loadOptions) {#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Comparer(String filePath, LoadOptions loadOptions)
```


Initializes new instance of [Comparer](../../com.groupdocs.comparison/comparer) with source file path and [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions).

 *  More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison][]
 *  More about GroupDocs.Comparison for Java features: [Developer Guide][]
 *  More about how to open and compare password-protected documents: [Open and compare password-protected documents][]
 *  More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages][]


[Document formats supported by GroupDocs.Comparison]: https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/comparisonjava/Developer+Guide
[Open and compare password-protected documents]: https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents
[Open and compare documents from third-party storages]: https://docs.groupdocs.com/display/comparisonjava/Loading

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | File path |
| loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Load options |

### Comparer(Path filePath, LoadOptions loadOptions) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Comparer(Path filePath, LoadOptions loadOptions)
```


Initializes new instance of [Comparer](../../com.groupdocs.comparison/comparer) with source file path and [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions).

 *  More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison][]
 *  More about GroupDocs.Comparison for Java features: [Developer Guide][]
 *  More about how to open and compare password-protected documents: [Open and compare password-protected documents][]
 *  More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages][]


[Document formats supported by GroupDocs.Comparison]: https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/comparisonjava/Developer+Guide
[Open and compare password-protected documents]: https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents
[Open and compare documents from third-party storages]: https://docs.groupdocs.com/display/comparisonjava/Loading

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.nio.file.Path | File path |
| loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Load options |

### Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings) {#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings)
```


Initializes new instance of [Comparer](../../com.groupdocs.comparison/comparer) class with source file path, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) and [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

 *  More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison][]
 *  More about GroupDocs.Comparison for Java features: [Developer Guide][]
 *  More about how to open and compare password-protected documents: [Open and compare password-protected documents][]
 *  More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages][]


[Document formats supported by GroupDocs.Comparison]: https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/comparisonjava/Developer+Guide
[Open and compare password-protected documents]: https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents
[Open and compare documents from third-party storages]: https://docs.groupdocs.com/display/comparisonjava/Loading

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | File path |
| loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Load options |
| settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Settings for comparison |

### Comparer(String filePath, ComparerSettings settings) {#Comparer-java.lang.String-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(String filePath, ComparerSettings settings)
```


Initializes new instance of [Comparer](../../com.groupdocs.comparison/comparer) class with source file path and [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

 *  More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison][]
 *  More about GroupDocs.Comparison for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Comparison]: https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/comparisonjava/Developer+Guide

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | File pats |
| settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Settings for comparison |

### Comparer(Path filePath, ComparerSettings settings) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(Path filePath, ComparerSettings settings)
```


Initializes new instance of [Comparer](../../com.groupdocs.comparison/comparer) class with source file path and [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

 *  More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison][]
 *  More about GroupDocs.Comparison for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Comparison]: https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/comparisonjava/Developer+Guide

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.nio.file.Path | File pats |
| settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Settings for comparison |

### Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings)
```


Initializes new instance of [Comparer](../../com.groupdocs.comparison/comparer) class with source file path, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) and [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

 *  More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison][]
 *  More about GroupDocs.Comparison for Java features: [Developer Guide][]
 *  More about how to open and compare password-protected documents: [Open and compare password-protected documents][]
 *  More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages][]


[Document formats supported by GroupDocs.Comparison]: https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/comparisonjava/Developer+Guide
[Open and compare password-protected documents]: https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents
[Open and compare documents from third-party storages]: https://docs.groupdocs.com/display/comparisonjava/Loading

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.nio.file.Path | File path |
| loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Load options |
| settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Settings for comparison |

### Comparer(InputStream document) {#Comparer-java.io.InputStream-}
```
public Comparer(InputStream document)
```


Initializes new instance of [Comparer](../../com.groupdocs.comparison/comparer) class with source document stream.

 *  More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison][]
 *  More about GroupDocs.Comparison for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Comparison]: https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/comparisonjava/Developer+Guide

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | java.io.InputStream | Source document stream |

### Comparer(InputStream document, LoadOptions loadOptions) {#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Comparer(InputStream document, LoadOptions loadOptions)
```


Initializes new instance of [Comparer](../../com.groupdocs.comparison/comparer) with source document stream and [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions).

 *  More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison][]
 *  More about GroupDocs.Comparison for Java features: [Developer Guide][]
 *  More about how to open and compare password-protected documents: [Open and compare password-protected documents][]
 *  More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages][]


[Document formats supported by GroupDocs.Comparison]: https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/comparisonjava/Developer+Guide
[Open and compare password-protected documents]: https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents
[Open and compare documents from third-party storages]: https://docs.groupdocs.com/display/comparisonjava/Loading

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | java.io.InputStream | Source document stream |
| loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Load options |

### Comparer(InputStream document, ComparerSettings settings) {#Comparer-java.io.InputStream-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(InputStream document, ComparerSettings settings)
```


Initializes new instance of [Comparer](../../com.groupdocs.comparison/comparer) class with source document stream and [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

 *  More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison][]
 *  More about GroupDocs.Comparison for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Comparison]: https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/comparisonjava/Developer+Guide

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | java.io.InputStream | Source document stream |
| settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Settings for comparison |

### Comparer(InputStream document, LoadOptions loadOptions, ComparerSettings settings) {#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(InputStream document, LoadOptions loadOptions, ComparerSettings settings)
```


Initializes new instance of [Comparer](../../com.groupdocs.comparison/comparer) class with document stream, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) and [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

 *  More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison][]
 *  More about GroupDocs.Comparison for Java features: [Developer Guide][]
 *  More about how to open and compare password-protected documents: [Open and compare password-protected documents][]
 *  More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages][]


[Document formats supported by GroupDocs.Comparison]: https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/comparisonjava/Developer+Guide
[Open and compare password-protected documents]: https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents
[Open and compare documents from third-party storages]: https://docs.groupdocs.com/display/comparisonjava/Loading

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | java.io.InputStream | Source document stream |
| loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Load options |
| settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Settings for comparison |

### Comparer(ComparerSettings settings) {#Comparer-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(ComparerSettings settings)
```


Instantiates a new Comparer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | the settings |

### FILE_PATH {#FILE-PATH}
```
public static final String FILE_PATH
```


### getSource() {#getSource--}
```
public final Document getSource()
```


Source file that is being compared.

**Returns:**
[Document](../../com.groupdocs.comparison/document) - the source
### getTargets() {#getTargets--}
```
public final List<Document> getTargets()
```


List of target files to compare with source file.

**Returns:**
java.util.List<com.groupdocs.comparison.Document> - the targets
### compare() {#compare--}
```
public final Path compare()
```


Compares documents without saving result with default options

 *  More about how to compare documents: [How to compare documents in Java][]
 *  More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents][How to compare contracts_ drafts and legal documents]


[How to compare documents in Java]: https://docs.groupdocs.com/display/comparisonjava/Compare+documents
[How to compare contracts_ drafts and legal documents]: https://docs.groupdocs.com/comparison/java/comparison-use-cases/

**Returns:**
java.nio.file.Path - the path
### compare(String filePath) {#compare-java.lang.String-}
```
public final Path compare(String filePath)
```


Compares documents and saves result to file path

 *  More about how to compare documents: [How to compare documents in Java][]
 *  More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents][How to compare contracts_ drafts and legal documents]


[How to compare documents in Java]: https://docs.groupdocs.com/display/comparisonjava/Compare+documents
[How to compare contracts_ drafts and legal documents]: https://docs.groupdocs.com/comparison/java/comparison-use-cases/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Result document path |

**Returns:**
java.nio.file.Path - result file path or null. In some situations it's extension can be changed
### compare(Path filePath) {#compare-java.nio.file.Path-}
```
public final Path compare(Path filePath)
```


Compares documents and saves result to file path

 *  More about how to compare documents: [How to compare documents in Java][]
 *  More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents][How to compare contracts_ drafts and legal documents]


[How to compare documents in Java]: https://docs.groupdocs.com/display/comparisonjava/Compare+documents
[How to compare contracts_ drafts and legal documents]: https://docs.groupdocs.com/comparison/java/comparison-use-cases/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.nio.file.Path | Result document path |

**Returns:**
java.nio.file.Path - result file path, in some situations it's extension can be changed
### compare(OutputStream outputStream) {#compare-java.io.OutputStream-}
```
public final Path compare(OutputStream outputStream)
```


Compares documents and saves result to file stream

Note: In case return value is null, use data that was written into outputStream

 *  More about how to compare documents: [How to compare documents in Java][]
 *  More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents][How to compare contracts_ drafts and legal documents]


[How to compare documents in Java]: https://docs.groupdocs.com/display/comparisonjava/Compare+documents
[How to compare contracts_ drafts and legal documents]: https://docs.groupdocs.com/comparison/java/comparison-use-cases/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | java.io.OutputStream | Result document stream |

**Returns:**
java.nio.file.Path - result file path or null when data from  outputStream  must be used. In some situations result file's extension can be changed
### compare(String filePath, CompareOptions compareOptions) {#compare-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(String filePath, CompareOptions compareOptions)
```


Compares documents and saves result to file path

 *  More about how to compare documents: [How to compare documents in Java][]
 *  More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents][How to compare contracts_ drafts and legal documents]
 *  More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide][]


[How to compare documents in Java]: https://docs.groupdocs.com/display/comparisonjava/Compare+documents
[How to compare contracts_ drafts and legal documents]: https://docs.groupdocs.com/comparison/java/comparison-use-cases/
[Advanced comparison options guide]: https://docs.groupdocs.com/comparison/java/comparison/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Result document file path |
| compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Compare options |

**Returns:**
java.nio.file.Path - result file path, in some situations it's extension can be changed
### compare(Path filePath, CompareOptions compareOptions) {#compare-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(Path filePath, CompareOptions compareOptions)
```


Compares documents and saves result to file path

 *  More about how to compare documents: [How to compare documents in Java][]
 *  More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents][How to compare contracts_ drafts and legal documents]
 *  More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide][]


[How to compare documents in Java]: https://docs.groupdocs.com/display/comparisonjava/Compare+documents
[How to compare contracts_ drafts and legal documents]: https://docs.groupdocs.com/comparison/java/comparison-use-cases/
[Advanced comparison options guide]: https://docs.groupdocs.com/comparison/java/comparison/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.nio.file.Path | Result document file path |
| compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Compare options |

**Returns:**
java.nio.file.Path - result file path, in some situations it's extension can be changed
### compare(OutputStream document, CompareOptions compareOptions) {#compare-java.io.OutputStream-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(OutputStream document, CompareOptions compareOptions)
```


Compares documents and saves result to file stream

Note: In case return value is null, use data that was written into outputStream

 *  More about how to compare documents: [How to compare documents in Java][]
 *  More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents][How to compare contracts_ drafts and legal documents]
 *  More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide][]


[How to compare documents in Java]: https://docs.groupdocs.com/display/comparisonjava/Compare+documents
[How to compare contracts_ drafts and legal documents]: https://docs.groupdocs.com/comparison/java/comparison-use-cases/
[Advanced comparison options guide]: https://docs.groupdocs.com/comparison/java/comparison/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | java.io.OutputStream | Result document stream |
| compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Compare options |

**Returns:**
java.nio.file.Path - result file path or null when data from  outputStream  must be used. In some situations result file's extension can be changed
### compare(SaveOptions saveOptions, CompareOptions compareOptions) {#compare-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(SaveOptions saveOptions, CompareOptions compareOptions)
```


Compares documents without saving result.

 *  More about how to compare documents: [How to compare documents in Java][]
 *  More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents][How to compare contracts_ drafts and legal documents]
 *  More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide][]


[How to compare documents in Java]: https://docs.groupdocs.com/display/comparisonjava/Compare+documents
[How to compare contracts_ drafts and legal documents]: https://docs.groupdocs.com/comparison/java/comparison-use-cases/
[Advanced comparison options guide]: https://docs.groupdocs.com/comparison/java/comparison/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Save options |
| compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Compare options |

**Returns:**
java.nio.file.Path - the path
### compare(String filePath, SaveOptions saveOptions) {#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-}
```
public final Path compare(String filePath, SaveOptions saveOptions)
```


Compares documents and save result to file path

 *  More about how to compare documents: [How to compare documents in Java][]
 *  More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents][How to compare contracts_ drafts and legal documents]


[How to compare documents in Java]: https://docs.groupdocs.com/display/comparisonjava/Compare+documents
[How to compare contracts_ drafts and legal documents]: https://docs.groupdocs.com/comparison/java/comparison-use-cases/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Result document file path |
| saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Save options |

**Returns:**
java.nio.file.Path - result file path, in some situations it's extension can be changed
### compare(Path filePath, SaveOptions saveOptions) {#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-}
```
public final Path compare(Path filePath, SaveOptions saveOptions)
```


Compares documents and save result to file path

 *  More about how to compare documents: [How to compare documents in Java][]
 *  More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents][How to compare contracts_ drafts and legal documents]


[How to compare documents in Java]: https://docs.groupdocs.com/display/comparisonjava/Compare+documents
[How to compare contracts_ drafts and legal documents]: https://docs.groupdocs.com/comparison/java/comparison-use-cases/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.nio.file.Path | Result document file path |
| saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Save options |

**Returns:**
java.nio.file.Path - result file path, in some situations it's extension can be changed
### compare(OutputStream document, SaveOptions saveOptions) {#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-}
```
public final Path compare(OutputStream document, SaveOptions saveOptions)
```


Compares documents and save result to file stream

Note: In case return value is null, use data that was written into outputStream

 *  More about how to compare documents: [How to compare documents in Java][]
 *  More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents][How to compare contracts_ drafts and legal documents]


[How to compare documents in Java]: https://docs.groupdocs.com/display/comparisonjava/Compare+documents
[How to compare contracts_ drafts and legal documents]: https://docs.groupdocs.com/comparison/java/comparison-use-cases/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | java.io.OutputStream | Result document stream |
| saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Save options |

**Returns:**
java.nio.file.Path - result file path or null when data from  outputStream  must be used. In some situations result file's extension can be changed
### compare(CompareOptions compareOptions) {#compare-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(CompareOptions compareOptions)
```


Compares documents without saving result.

 *  More about how to compare documents: [How to compare documents in Java][]
 *  More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents][How to compare contracts_ drafts and legal documents]


[How to compare documents in Java]: https://docs.groupdocs.com/display/comparisonjava/Compare+documents
[How to compare contracts_ drafts and legal documents]: https://docs.groupdocs.com/comparison/java/comparison-use-cases/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Compare options |

**Returns:**
java.nio.file.Path - the path
### compare(OutputStream outputStream, SaveOptions saveOptions, CompareOptions compareOptions) {#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(OutputStream outputStream, SaveOptions saveOptions, CompareOptions compareOptions)
```


Compares documents and saves result to a stream.

Note: In case return value is null, use data that was written into outputStream

 *  More about how to compare documents: [How to compare documents in Java][]
 *  More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents][How to compare contracts_ drafts and legal documents]
 *  More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide][]


[How to compare documents in Java]: https://docs.groupdocs.com/display/comparisonjava/Compare+documents
[How to compare contracts_ drafts and legal documents]: https://docs.groupdocs.com/comparison/java/comparison-use-cases/
[Advanced comparison options guide]: https://docs.groupdocs.com/comparison/java/comparison/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | java.io.OutputStream | Result document stream |
| saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Save options |
| compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Compare options |

**Returns:**
java.nio.file.Path - result file path or null when data from  outputStream  must be used. In some situations result file's extension can be changed
### compare(String filePath, SaveOptions saveOptions, CompareOptions compareOptions) {#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(String filePath, SaveOptions saveOptions, CompareOptions compareOptions)
```


Compares documents and saves result to file path

 *  More about how to compare documents: [How to compare documents in Java][]
 *  More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents][How to compare contracts_ drafts and legal documents]
 *  More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide][]


[How to compare documents in Java]: https://docs.groupdocs.com/display/comparisonjava/Compare+documents
[How to compare contracts_ drafts and legal documents]: https://docs.groupdocs.com/comparison/java/comparison-use-cases/
[Advanced comparison options guide]: https://docs.groupdocs.com/comparison/java/comparison/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Result document file path |
| saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Save options |
| compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Compare options |

**Returns:**
java.nio.file.Path - result file path, in some situations it's extension can be changed
### compare(Path filePath, SaveOptions saveOptions, CompareOptions compareOptions) {#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(Path filePath, SaveOptions saveOptions, CompareOptions compareOptions)
```


Compares documents and saves result to file path

 *  More about how to compare documents: [How to compare documents in Java][]
 *  More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents][How to compare contracts_ drafts and legal documents]
 *  More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide][]


[How to compare documents in Java]: https://docs.groupdocs.com/display/comparisonjava/Compare+documents
[How to compare contracts_ drafts and legal documents]: https://docs.groupdocs.com/comparison/java/comparison-use-cases/
[Advanced comparison options guide]: https://docs.groupdocs.com/comparison/java/comparison/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.nio.file.Path | Result document file path |
| saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Save options |
| compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Compare options |

**Returns:**
java.nio.file.Path - result file path, in some situations it's extension can be changed
### add(String filePath) {#add-java.lang.String-}
```
public final void add(String filePath)
```


Adds file to comparison.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Compared file path |

### add(Path filePath) {#add-java.nio.file.Path-}
```
public final void add(Path filePath)
```


Adds file to comparison.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.nio.file.Path | Compared file path |

### add(String[] filePaths) {#add-java.lang.String...-}
```
public final void add(String[] filePaths)
```


Adds file to comparison.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePaths | java.lang.String[] | Compared files paths |

### add(Path[] filePaths) {#add-java.nio.file.Path...-}
```
public final void add(Path[] filePaths)
```


Adds file to comparison.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePaths | java.nio.file.Path[] | Compared files paths |

### add(String filePath, LoadOptions loadOptions) {#add-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-}
```
public final void add(String filePath, LoadOptions loadOptions)
```


Adds file to comparison with loading options specified.

 *  More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents][]
 *  More about how to open and compare documents stored at local disk: [How to open and compare files by file path][]
 *  More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages][]


[How to open and compare password-protected documents]: https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents
[How to open and compare files by file path]: https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk
[How to open and compare files from third-party storages]: https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Compared file path |
| loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Load options |

### add(Path filePath, LoadOptions loadOptions) {#add-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-}
```
public final void add(Path filePath, LoadOptions loadOptions)
```


Adds file to comparison with loading options specified.

 *  More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents][]
 *  More about how to open and compare documents stored at local disk: [How to open and compare files by file path][]
 *  More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages][]


[How to open and compare password-protected documents]: https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents
[How to open and compare files by file path]: https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk
[How to open and compare files from third-party storages]: https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.nio.file.Path | Compared file path |
| loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Load options |

### add(InputStream document) {#add-java.io.InputStream-}
```
public final void add(InputStream document)
```


Adds document stream to comparison.

 *  More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents][]
 *  More about how to open and compare documents stored at local disk: [How to open and compare files by file path][]
 *  More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages][]


[How to open and compare password-protected documents]: https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents
[How to open and compare files by file path]: https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk
[How to open and compare files from third-party storages]: https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | java.io.InputStream | Compared document stream |

### add(InputStream[] documents) {#add-java.io.InputStream...-}
```
public final void add(InputStream[] documents)
```


Adds document stream to comparison.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| documents | java.io.InputStream[] | Compared documents streams |

### add(InputStream document, LoadOptions loadOptions) {#add-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-}
```
public final void add(InputStream document, LoadOptions loadOptions)
```


Adds document stream to comparison with loading options specified.

 *  More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents][]
 *  More about how to open and compare documents stored at local disk: [How to open and compare files by file path][]
 *  More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages][]


[How to open and compare password-protected documents]: https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents
[How to open and compare files by file path]: https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk
[How to open and compare files from third-party storages]: https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | java.io.InputStream | Compared document stream |
| loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Load options |

### getChanges() {#getChanges--}
```
public final ChangeInfo[] getChanges()
```


Gets list of changes between source and target file(s).

 *  More about how to obtain collection of detected differences between compared documents in Java: [How to get list of changes between documents in Java][]
 *  More about how to get changes coordinates at pages image preview when comparing documents using GroupDocs.Comparison for Java: [How to get changes coordinates programmatically][]


[How to get list of changes between documents in Java]: https://docs.groupdocs.com/display/comparisonjava/Get+list+of+changes
[How to get changes coordinates programmatically]: https://docs.groupdocs.com/display/comparisonjava/Get+changes+coordinates

**Returns:**
com.groupdocs.comparison.result.ChangeInfo[] - array of changes
### getChanges(GetChangeOptions getChangeOptions) {#getChanges-com.groupdocs.comparison.options.GetChangeOptions-}
```
public final ChangeInfo[] getChanges(GetChangeOptions getChangeOptions)
```


Gets list of changes between source and target file(s).

 *  More about how to obtain collection of detected differences between compared documents in Java: [How to get list of changes between documents in Java][]
 *  More about how to get changes coordinates at pages image preview when comparing documents using GroupDocs.Comparison for Java: [How to get changes coordinates programmatically][]


[How to get list of changes between documents in Java]: https://docs.groupdocs.com/display/comparisonjava/Get+list+of+changes
[How to get changes coordinates programmatically]: https://docs.groupdocs.com/display/comparisonjava/Get+changes+coordinates

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| getChangeOptions | [GetChangeOptions](../../com.groupdocs.comparison.options/getchangeoptions) | Get change options |

**Returns:**
com.groupdocs.comparison.result.ChangeInfo[] - array of changes
### applyChanges(String filePath, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.lang.String-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(String filePath, ApplyChangeOptions applyChangeOptions)
```


Accepts or rejects changes and applies them to resultant document.

 *  More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java][]


[How to apply or reject changes detected during document comparison in Java]: https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Result file path |
| applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | Apply change options |

### applyChanges(Path filePath, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(Path filePath, ApplyChangeOptions applyChangeOptions)
```


Accepts or rejects changes and applies them to resultant document.

 *  More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java][]


[How to apply or reject changes detected during document comparison in Java]: https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.nio.file.Path | Result file path |
| applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | Apply change options |

### applyChanges(OutputStream document, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(OutputStream document, ApplyChangeOptions applyChangeOptions)
```


Accepts or rejects changes and applies them to resultant document.

 *  More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java][]


[How to apply or reject changes detected during document comparison in Java]: https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | java.io.OutputStream | Result document |
| applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | Apply change options |

### applyChanges(String filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(String filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)
```


Accepts or rejects changes and applies them to resultant document.

 *  More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java][]


[How to apply or reject changes detected during document comparison in Java]: https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Result file path |
| saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Save options |
| applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | Apply change options |

### applyChanges(Path filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(Path filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)
```


Accepts or rejects changes and applies them to resultant document.

 *  More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java][]


[How to apply or reject changes detected during document comparison in Java]: https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.nio.file.Path | Result file path |
| saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Save options |
| applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | Apply change options |

### applyChanges(OutputStream document, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(OutputStream document, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)
```


Accepts or rejects changes and applies them to resultant document.

 *  More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java][]


[How to apply or reject changes detected during document comparison in Java]: https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | java.io.OutputStream | Result document |
| saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Save options |
| applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | Apply change options |

### getResultString() {#getResultString--}
```
public String getResultString()
```


Get result string after comparison (For Text Comparison only).

**Returns:**
java.lang.String - the result string
### close() {#close--}
```
public void close()
```




### dispose() {#dispose--}
```
public final void dispose()
```


Releases resources.

