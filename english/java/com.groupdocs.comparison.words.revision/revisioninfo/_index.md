---
title: RevisionInfo
second_title: GroupDocs.Comparison for Java API Reference
description: Provides information about one revision.
type: docs
weight: 12
url: /java/com.groupdocs.comparison.words.revision/revisioninfo/
---
**Inheritance:**
java.lang.Object
```
public class RevisionInfo
```

Provides information about one revision.
## Constructors

| Constructor | Description |
| --- | --- |
| [RevisionInfo()](#RevisionInfo--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getAction()](#getAction--) | Action (accept or reject). |
| [setAction(RevisionAction action)](#setAction-com.groupdocs.comparison.words.revision.RevisionAction-) | Action (accept or reject). |
| [getText()](#getText--) | The text that is in revision. |
| [setText(String text)](#setText-java.lang.String-) | The text that is in revision. |
| [getAuthor()](#getAuthor--) | Author. |
| [setAuthor(String author)](#setAuthor-java.lang.String-) | Author. |
| [getType()](#getType--) | RevisionHandler type, depending on the type the Action (accept or reject) logic changes. |
| [setType(RevisionType type)](#setType-com.groupdocs.comparison.words.revision.RevisionType-) | RevisionHandler type, depending on the type the Action (accept or reject) logic changes. |
### RevisionInfo() {#RevisionInfo--}
```
public RevisionInfo()
```


### getAction() {#getAction--}
```
public RevisionAction getAction()
```


Action (accept or reject). This field allows you to influence the display of the revision.

**Returns:**
[RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) - the action
### setAction(RevisionAction action) {#setAction-com.groupdocs.comparison.words.revision.RevisionAction-}
```
public void setAction(RevisionAction action)
```


Action (accept or reject). This field allows you to influence the display of the revision.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| action | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | the action |

### getText() {#getText--}
```
public String getText()
```


The text that is in revision.

**Returns:**
java.lang.String - the text
### setText(String text) {#setText-java.lang.String-}
```
public void setText(String text)
```


The text that is in revision.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | the text |

### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Author.

**Returns:**
java.lang.String - the author
### setAuthor(String author) {#setAuthor-java.lang.String-}
```
public void setAuthor(String author)
```


Author.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| author | java.lang.String | the author |

### getType() {#getType--}
```
public RevisionType getType()
```


RevisionHandler type, depending on the type the Action (accept or reject) logic changes.

**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) - the type
### setType(RevisionType type) {#setType-com.groupdocs.comparison.words.revision.RevisionType-}
```
public void setType(RevisionType type)
```


RevisionHandler type, depending on the type the Action (accept or reject) logic changes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | [RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) | the type |

