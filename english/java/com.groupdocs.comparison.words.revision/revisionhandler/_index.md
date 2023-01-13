---
title: RevisionHandler
second_title: GroupDocs.Comparison for Java API Reference
description: Represents the main class that controls revision handling.
type: docs
weight: 11
url: /java/com.groupdocs.comparison.words.revision/revisionhandler/
---
**Inheritance:**
java.lang.Object
```
public class RevisionHandler
```

Represents the main class that controls revision handling.
## Constructors

| Constructor | Description |
| --- | --- |
| [RevisionHandler(String filePath)](#RevisionHandler-java.lang.String-) | Initializes new instance of [RevisionHandler](../../com.groupdocs.comparison.words.revision/revisionhandler) class with the path to the file with revisions. |
| [RevisionHandler(Path filePath)](#RevisionHandler-java.nio.file.Path-) | Initializes new instance of [RevisionHandler](../../com.groupdocs.comparison.words.revision/revisionhandler) class with the path to the file with revisions. |
| [RevisionHandler(InputStream file, FileType fileType)](#RevisionHandler-java.io.InputStream-com.groupdocs.comparison.result.FileType-) | Initializes new instance of [RevisionHandler](../../com.groupdocs.comparison.words.revision/revisionhandler) class with a file stream with revisions. |
| [RevisionHandler(Document document)](#RevisionHandler-com.aspose.words.Document-) | Instantiates a new Revision handler. |
## Methods

| Method | Description |
| --- | --- |
| [getRevisions()](#getRevisions--) | Gets list of all revisions. |
| [applyRevisionChanges(ApplyRevisionOptions changes)](#applyRevisionChanges-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | Processes changes in revisions and applies them to the same file from which the revisions were taken. |
| [applyRevisionChanges(Path filePath, ApplyRevisionOptions changes)](#applyRevisionChanges-java.nio.file.Path-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | Processes changes in revisions, and the result is written to the specified file by path. |
| [applyRevisionChanges(String filePath, ApplyRevisionOptions changes)](#applyRevisionChanges-java.lang.String-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | Processes changes in revisions, and the result is written to the specified file by path. |
| [applyRevisionChanges(OutputStream outputStream, ApplyRevisionOptions changes)](#applyRevisionChanges-java.io.OutputStream-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | Processes changes in revisions and the result is written to the document stream. |
### RevisionHandler(String filePath) {#RevisionHandler-java.lang.String-}
```
public RevisionHandler(String filePath)
```


Initializes new instance of [RevisionHandler](../../com.groupdocs.comparison.words.revision/revisionhandler) class with the path to the file with revisions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | File path |

### RevisionHandler(Path filePath) {#RevisionHandler-java.nio.file.Path-}
```
public RevisionHandler(Path filePath)
```


Initializes new instance of [RevisionHandler](../../com.groupdocs.comparison.words.revision/revisionhandler) class with the path to the file with revisions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.nio.file.Path | File path |

### RevisionHandler(InputStream file, FileType fileType) {#RevisionHandler-java.io.InputStream-com.groupdocs.comparison.result.FileType-}
```
public RevisionHandler(InputStream file, FileType fileType)
```


Initializes new instance of [RevisionHandler](../../com.groupdocs.comparison.words.revision/revisionhandler) class with a file stream with revisions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.io.InputStream | Source document stream |
| fileType | [FileType](../../com.groupdocs.comparison.result/filetype) |  |

### RevisionHandler(Document document) {#RevisionHandler-com.aspose.words.Document-}
```
public RevisionHandler(Document document)
```


Instantiates a new Revision handler.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | com.aspose.words.Document | the document |

### getRevisions() {#getRevisions--}
```
public List<RevisionInfo> getRevisions()
```


Gets list of all revisions.

Due to the fact that revisions were originally sorted in a group, revisions must be taken from RevisionCollections. In RevisionCollections, a single revision can be split into multiple revisions with the same general text. Since RevisionCollections may contain revisions with the same general text, this must be controlled when creating a list of revisions for the user. This is controlled here using List<RevisionGroup> groups.

**Returns:**
java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> - the revisions
### applyRevisionChanges(ApplyRevisionOptions changes) {#applyRevisionChanges-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(ApplyRevisionOptions changes)
```


Processes changes in revisions and applies them to the same file from which the revisions were taken.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | List of changed revisions |

### applyRevisionChanges(Path filePath, ApplyRevisionOptions changes) {#applyRevisionChanges-java.nio.file.Path-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(Path filePath, ApplyRevisionOptions changes)
```


Processes changes in revisions, and the result is written to the specified file by path.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.nio.file.Path | Result file path |
| changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | List of changed revisions |

### applyRevisionChanges(String filePath, ApplyRevisionOptions changes) {#applyRevisionChanges-java.lang.String-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(String filePath, ApplyRevisionOptions changes)
```


Processes changes in revisions, and the result is written to the specified file by path.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Result file path |
| changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | List of changed revisions |

### applyRevisionChanges(OutputStream outputStream, ApplyRevisionOptions changes) {#applyRevisionChanges-java.io.OutputStream-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(OutputStream outputStream, ApplyRevisionOptions changes)
```


Processes changes in revisions and the result is written to the document stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | java.io.OutputStream | Result document |
| changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | List of changed revisions |

