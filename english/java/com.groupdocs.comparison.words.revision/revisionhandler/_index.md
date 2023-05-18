---
title: RevisionHandler
second_title: GroupDocs.Comparison for Java API Reference
description: Represents a class that controls the handling of revisions.
type: docs
weight: 11
url: /java/com.groupdocs.comparison.words.revision/revisionhandler/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class RevisionHandler implements Closeable
```

Represents a class that controls the handling of revisions.

The RevisionHandler class allows you to work with revisions in documents. It provides methods to retrieve the list of revisions, apply changes to revisions, and save the modified document.

Example usage:

```

 try (RevisionHandler revisionHandler = new RevisionHandler(sourceFile)) {
     List revisionList = revisionHandler.getRevisions();

     for (RevisionInfo revisionInfo : revisionList) {
         if (revisionInfo.getType() == RevisionType.DELETION)
             // Set an action to be applied to the revision
             revisionInfo.setAction(RevisionAction.Accept);
     }
     // Create an instance of ApplyRevisionOptions
     ApplyRevisionOptions revisionChanges = new ApplyRevisionOptions();
     revisionChanges.setChanges(revisionList);
     // Apply the revisions using the options
     revisionHandler.applyRevisionChanges(resultFile, revisionChanges);
 }
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [RevisionHandler(String filePath)](#RevisionHandler-java.lang.String-) | Initializes a new instance of the [RevisionHandler](../../com.groupdocs.comparison.words.revision/revisionhandler) class with the path to the file containing revisions. |
| [RevisionHandler(Path filePath)](#RevisionHandler-java.nio.file.Path-) | Initializes a new instance of the [RevisionHandler](../../com.groupdocs.comparison.words.revision/revisionhandler) class with the path to the file containing revisions. |
| [RevisionHandler(InputStream file, FileType fileType)](#RevisionHandler-java.io.InputStream-com.groupdocs.comparison.result.FileType-) | Initializes a new instance of the [RevisionHandler](../../com.groupdocs.comparison.words.revision/revisionhandler) class with a file stream containing revisions. |
| [RevisionHandler(Document document)](#RevisionHandler-com.aspose.words.Document-) | Initializes a new instance of the [RevisionHandler](../../com.groupdocs.comparison.words.revision/revisionhandler) class with a document. |
## Methods

| Method | Description |
| --- | --- |
| [getRevisions()](#getRevisions--) | Gets the list of all revisions. |
| [applyRevisionChanges(ApplyRevisionOptions changes)](#applyRevisionChanges-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | Processes changes in revisions and applies them to the original file. |
| [applyRevisionChanges(Path filePath, ApplyRevisionOptions changes)](#applyRevisionChanges-java.nio.file.Path-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | Processes changes in revisions and writes the result to the specified file. |
| [applyRevisionChanges(String filePath, ApplyRevisionOptions changes)](#applyRevisionChanges-java.lang.String-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | Processes changes in revisions and writes the result to the specified file. |
| [applyRevisionChanges(OutputStream outputStream, ApplyRevisionOptions changes)](#applyRevisionChanges-java.io.OutputStream-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | Processes changes in revisions and writes the result to the document stream. |
| [close()](#close--) |  |
### RevisionHandler(String filePath) {#RevisionHandler-java.lang.String-}
```
public RevisionHandler(String filePath)
```


Initializes a new instance of the [RevisionHandler](../../com.groupdocs.comparison.words.revision/revisionhandler) class with the path to the file containing revisions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The path to the file. |

### RevisionHandler(Path filePath) {#RevisionHandler-java.nio.file.Path-}
```
public RevisionHandler(Path filePath)
```


Initializes a new instance of the [RevisionHandler](../../com.groupdocs.comparison.words.revision/revisionhandler) class with the path to the file containing revisions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.nio.file.Path | The path to the file. |

### RevisionHandler(InputStream file, FileType fileType) {#RevisionHandler-java.io.InputStream-com.groupdocs.comparison.result.FileType-}
```
public RevisionHandler(InputStream file, FileType fileType)
```


Initializes a new instance of the [RevisionHandler](../../com.groupdocs.comparison.words.revision/revisionhandler) class with a file stream containing revisions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.io.InputStream | The source document stream. |
| fileType | [FileType](../../com.groupdocs.comparison.result/filetype) | The type of the file. |

### RevisionHandler(Document document) {#RevisionHandler-com.aspose.words.Document-}
```
public RevisionHandler(Document document)
```


Initializes a new instance of the [RevisionHandler](../../com.groupdocs.comparison.words.revision/revisionhandler) class with a document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | com.aspose.words.Document | The document. |

### getRevisions() {#getRevisions--}
```
public List<RevisionInfo> getRevisions()
```


Gets the list of all revisions.

Due to the fact that revisions were originally sorted in a group, revisions must be taken from a List. In the List, a single revision can be split into multiple revisions with the same general text. Since the List may contain revisions with the same general text, this must be controlled when creating a list of revisions for the user. This is controlled here using List<RevisionGroup> groups.

**Returns:**
java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> - the list of revisions.
### applyRevisionChanges(ApplyRevisionOptions changes) {#applyRevisionChanges-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(ApplyRevisionOptions changes)
```


Processes changes in revisions and applies them to the original file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | The list of changed revisions. |

### applyRevisionChanges(Path filePath, ApplyRevisionOptions changes) {#applyRevisionChanges-java.nio.file.Path-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(Path filePath, ApplyRevisionOptions changes)
```


Processes changes in revisions and writes the result to the specified file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.nio.file.Path | The result file path. |
| changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | The list of changed revisions. |

### applyRevisionChanges(String filePath, ApplyRevisionOptions changes) {#applyRevisionChanges-java.lang.String-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(String filePath, ApplyRevisionOptions changes)
```


Processes changes in revisions and writes the result to the specified file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The result file path. |
| changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | The list of changed revisions. |

### applyRevisionChanges(OutputStream outputStream, ApplyRevisionOptions changes) {#applyRevisionChanges-java.io.OutputStream-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(OutputStream outputStream, ApplyRevisionOptions changes)
```


Processes changes in revisions and writes the result to the document stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | java.io.OutputStream | The result document stream. |
| changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | The list of changed revisions. |

### close() {#close--}
```
public void close()
```




