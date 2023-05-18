---
title: RevisionInfo
second_title: GroupDocs.Comparison for Java API Reference
description: Represents a revision in the document.
type: docs
weight: 12
url: /java/com.groupdocs.comparison.words.revision/revisioninfo/
---
**Inheritance:**
java.lang.Object
```
public class RevisionInfo
```

Represents a revision in the document.

A revision encapsulates information about revision change made to the document. This class provides methods to retrieve information about the revision, such as its type, content, author, and so on.

Example usage:

```

 try (RevisionHandler revisionHandler = new RevisionHandler(sourceFile)) {
     List revisionList = revisionHandler.getRevisions();

     for (RevisionInfo revisionInfo : revisionList) {
         System.out.println("Revision Type: " + revisionInfo.getType());
         System.out.println("Text: " + revisionInfo.getText());
         System.out.println("Author: " + revisionInfo.getAuthor());
     }
 }
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [RevisionInfo()](#RevisionInfo--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getAction()](#getAction--) | Gets the action associated with the revision (accept or reject). |
| [setAction(RevisionAction value)](#setAction-com.groupdocs.comparison.words.revision.RevisionAction-) | Sets the value associated with the revision (accept or reject). |
| [getText()](#getText--) | Gets the text content of the revision. |
| [setText(String value)](#setText-java.lang.String-) | Sets the value content of the revision. |
| [getAuthor()](#getAuthor--) | Gets the author of the revision. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | Sets the value of the revision. |
| [getType()](#getType--) | Gets the type of the revision, depending on the type the Action (accept or reject) logic changes. |
| [setType(RevisionType value)](#setType-com.groupdocs.comparison.words.revision.RevisionType-) | Sets the value of the revision, depending on the value the Action (accept or reject) logic changes. |
### RevisionInfo() {#RevisionInfo--}
```
public RevisionInfo()
```


### getAction() {#getAction--}
```
public RevisionAction getAction()
```


Gets the action associated with the revision (accept or reject). This field allows you to influence the display of the revision.

**Returns:**
[RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) - the action associated with the revision.
### setAction(RevisionAction value) {#setAction-com.groupdocs.comparison.words.revision.RevisionAction-}
```
public void setAction(RevisionAction value)
```


Sets the value associated with the revision (accept or reject). This field allows you to influence the display of the revision.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | The value associated with the revision. |

### getText() {#getText--}
```
public String getText()
```


Gets the text content of the revision.

**Returns:**
java.lang.String - the text content of the revision.
### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Sets the value content of the revision.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The value content of the revision. |

### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Gets the author of the revision.

**Returns:**
java.lang.String - the author of the revision.
### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public void setAuthor(String value)
```


Sets the value of the revision.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The value of the revision. |

### getType() {#getType--}
```
public RevisionType getType()
```


Gets the type of the revision, depending on the type the Action (accept or reject) logic changes.

**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) - the type of the revision.
### setType(RevisionType value) {#setType-com.groupdocs.comparison.words.revision.RevisionType-}
```
public void setType(RevisionType value)
```


Sets the value of the revision, depending on the value the Action (accept or reject) logic changes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) | The value of the revision. |

