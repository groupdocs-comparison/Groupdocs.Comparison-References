---
title: ApplyRevisionOptions
second_title: GroupDocs.Comparison for Java API Reference
description: The ApplyRevisionOptions class allows you to update the state of revisions before they are applied to the final document.
type: docs
weight: 10
url: /java/com.groupdocs.comparison.words.revision/applyrevisionoptions/
---
**Inheritance:**
java.lang.Object
```
public class ApplyRevisionOptions
```

The ApplyRevisionOptions class allows you to update the state of revisions before they are applied to the final document.

It provides various constructors and properties to customize the revision application process.

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
| [ApplyRevisionOptions()](#ApplyRevisionOptions--) | Initializes a new instance of the ApplyRevisionOptions class. |
| [ApplyRevisionOptions(List<RevisionInfo> changes)](#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--) | Instantiates a new ApplyRevisionOptions object with the specified list of revisions. |
| [ApplyRevisionOptions(List<RevisionInfo> changes, RevisionAction revisionAction)](#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--com.groupdocs.comparison.words.revision.RevisionAction-) | Instantiates a new ApplyRevisionOptions object with the specified list of revisions and a common revision action. |
| [ApplyRevisionOptions(RevisionAction revisionAction)](#ApplyRevisionOptions-com.groupdocs.comparison.words.revision.RevisionAction-) | Instantiates a new ApplyRevisionOptions object with a common revision action. |
## Methods

| Method | Description |
| --- | --- |
| [getChanges()](#getChanges--) | Gets the list of revisions to be applied. |
| [setChanges(List<RevisionInfo> changes)](#setChanges-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--) | Sets the list of revisions to be applied. |
| [getCommonHandler()](#getCommonHandler--) | Gets the common revision action to be applied to all revisions. |
| [setCommonHandler(RevisionAction commonHandler)](#setCommonHandler-com.groupdocs.comparison.words.revision.RevisionAction-) | Sets the common revision action to be applied to all revisions. |
### ApplyRevisionOptions() {#ApplyRevisionOptions--}
```
public ApplyRevisionOptions()
```


Initializes a new instance of the ApplyRevisionOptions class.

### ApplyRevisionOptions(List<RevisionInfo> changes) {#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--}
```
public ApplyRevisionOptions(List<RevisionInfo> changes)
```


Instantiates a new ApplyRevisionOptions object with the specified list of revisions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| changes | java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> | The list of revisions to be applied |

### ApplyRevisionOptions(List<RevisionInfo> changes, RevisionAction revisionAction) {#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--com.groupdocs.comparison.words.revision.RevisionAction-}
```
public ApplyRevisionOptions(List<RevisionInfo> changes, RevisionAction revisionAction)
```


Instantiates a new ApplyRevisionOptions object with the specified list of revisions and a common revision action.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| changes | java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> | The list of revisions to be applied |
| revisionAction | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | The common revision action to be applied to all revisions |

### ApplyRevisionOptions(RevisionAction revisionAction) {#ApplyRevisionOptions-com.groupdocs.comparison.words.revision.RevisionAction-}
```
public ApplyRevisionOptions(RevisionAction revisionAction)
```


Instantiates a new ApplyRevisionOptions object with a common revision action.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| revisionAction | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | The common revision action to be applied to all revisions |

### getChanges() {#getChanges--}
```
public List<RevisionInfo> getChanges()
```


Gets the list of revisions to be applied.

**Returns:**
java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> - the list of revisions
### setChanges(List<RevisionInfo> changes) {#setChanges-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--}
```
public void setChanges(List<RevisionInfo> changes)
```


Sets the list of revisions to be applied.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| changes | java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> | The list of revisions |

### getCommonHandler() {#getCommonHandler--}
```
public RevisionAction getCommonHandler()
```


Gets the common revision action to be applied to all revisions.

**Returns:**
[RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) - the common revision action
### setCommonHandler(RevisionAction commonHandler) {#setCommonHandler-com.groupdocs.comparison.words.revision.RevisionAction-}
```
public void setCommonHandler(RevisionAction commonHandler)
```


Sets the common revision action to be applied to all revisions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| commonHandler | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | The common revision action |

