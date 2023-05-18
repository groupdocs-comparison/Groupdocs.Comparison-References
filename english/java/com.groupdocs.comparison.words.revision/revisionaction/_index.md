---
title: RevisionAction
second_title: GroupDocs.Comparison for Java API Reference
description: Represents an action that can be applied to a revision.
type: docs
weight: 13
url: /java/com.groupdocs.comparison.words.revision/revisionaction/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum RevisionAction extends Enum<RevisionAction>
```

Represents an action that can be applied to a revision.

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
## Fields

| Field | Description |
| --- | --- |
| [None](#None) | Indicates that no action is to be taken. |
| [Accept](#Accept) | Indicates that the revision will be displayed if it is of type INSERTION, or it will be removed if the type is DELETION. |
| [Reject](#Reject) | Indicates that the revision will be removed if it is of type INSERTION, or it will be displayed if the type is DELETION. |
## Methods

| Method | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### None {#None}
```
public static final RevisionAction None
```


Indicates that no action is to be taken.

### Accept {#Accept}
```
public static final RevisionAction Accept
```


Indicates that the revision will be displayed if it is of type INSERTION, or it will be removed if the type is DELETION.

### Reject {#Reject}
```
public static final RevisionAction Reject
```


Indicates that the revision will be removed if it is of type INSERTION, or it will be displayed if the type is DELETION.

### values() {#values--}
```
public static RevisionAction[] values()
```




**Returns:**
com.groupdocs.comparison.words.revision.RevisionAction[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static RevisionAction valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction)
