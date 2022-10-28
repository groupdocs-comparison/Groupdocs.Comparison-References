---
title: ApplyRevisionOptions
second_title: GroupDocs.Comparison for Java API Reference
description: Allows you to update the state of revisions before they are applied to the final document.
type: docs
weight: 10
url: /java/com.groupdocs.comparison.words.revision/applyrevisionoptions/
---
**Inheritance:**
java.lang.Object
```
public class ApplyRevisionOptions
```

Allows you to update the state of revisions before they are applied to the final document.
## Constructors

| Constructor | Description |
| --- | --- |
| [ApplyRevisionOptions()](#ApplyRevisionOptions--) | Instantiates a new Apply revision options. |
| [ApplyRevisionOptions(List<RevisionInfo> changes)](#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--) | Instantiates a new Apply revision options. |
| [ApplyRevisionOptions(List<RevisionInfo> changes, RevisionAction commonHandler)](#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--com.groupdocs.comparison.words.revision.RevisionAction-) | Instantiates a new Apply revision options. |
| [ApplyRevisionOptions(RevisionAction mCommonHandler)](#ApplyRevisionOptions-com.groupdocs.comparison.words.revision.RevisionAction-) | Instantiates a new Apply revision options. |
## Methods

| Method | Description |
| --- | --- |
| [getChanges()](#getChanges--) | The list of revisions processed, which will be applied to the resulting document. |
| [setChanges(List<RevisionInfo> changes)](#setChanges-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--) | The list of revisions processed, which will be applied to the resulting document. |
| [getCommonHandler()](#getCommonHandler--) | Indicates whether to apply one action for all revisions |
| [setCommonHandler(RevisionAction commonHandler)](#setCommonHandler-com.groupdocs.comparison.words.revision.RevisionAction-) | Indicates whether to apply one action for all revisions |
### ApplyRevisionOptions() {#ApplyRevisionOptions--}
```
public ApplyRevisionOptions()
```


Instantiates a new Apply revision options.

### ApplyRevisionOptions(List<RevisionInfo> changes) {#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--}
```
public ApplyRevisionOptions(List<RevisionInfo> changes)
```


Instantiates a new Apply revision options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| changes | java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> | the changes |

### ApplyRevisionOptions(List<RevisionInfo> changes, RevisionAction commonHandler) {#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--com.groupdocs.comparison.words.revision.RevisionAction-}
```
public ApplyRevisionOptions(List<RevisionInfo> changes, RevisionAction commonHandler)
```


Instantiates a new Apply revision options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| changes | java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> | the changes |
| commonHandler | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | the common handler |

### ApplyRevisionOptions(RevisionAction mCommonHandler) {#ApplyRevisionOptions-com.groupdocs.comparison.words.revision.RevisionAction-}
```
public ApplyRevisionOptions(RevisionAction mCommonHandler)
```


Instantiates a new Apply revision options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mCommonHandler | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | the m common handler |

### getChanges() {#getChanges--}
```
public List<RevisionInfo> getChanges()
```


The list of revisions processed, which will be applied to the resulting document.

**Returns:**
java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> - the changes
### setChanges(List<RevisionInfo> changes) {#setChanges-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--}
```
public void setChanges(List<RevisionInfo> changes)
```


The list of revisions processed, which will be applied to the resulting document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| changes | java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> | the changes |

### getCommonHandler() {#getCommonHandler--}
```
public RevisionAction getCommonHandler()
```


Indicates whether to apply one action for all revisions

**Returns:**
[RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) - the common handler
### setCommonHandler(RevisionAction commonHandler) {#setCommonHandler-com.groupdocs.comparison.words.revision.RevisionAction-}
```
public void setCommonHandler(RevisionAction commonHandler)
```


Indicates whether to apply one action for all revisions

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| commonHandler | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | the common handler |

