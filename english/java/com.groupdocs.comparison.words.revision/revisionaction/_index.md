---
title: RevisionAction
second_title: GroupDocs.Comparison for Java API Reference
description: Action that can be applied to a revision.
type: docs
weight: 13
url: /java/com.groupdocs.comparison.words.revision/revisionaction/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum RevisionAction extends Enum<RevisionAction>
```

Action that can be applied to a revision.
## Fields

| Field | Description |
| --- | --- |
| [None](#None) | Nothing to do. |
| [Accept](#Accept) | The revision will be displayed if it is of type INSERTION or will be removed if the type is DELETION. |
| [Reject](#Reject) | The revision will be removed if it is of type INSERTION or will be displayed if the type is DELETION. |
## Methods

| Method | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### None {#None}
```
public static final RevisionAction None
```


Nothing to do.

### Accept {#Accept}
```
public static final RevisionAction Accept
```


The revision will be displayed if it is of type INSERTION or will be removed if the type is DELETION.

### Reject {#Reject}
```
public static final RevisionAction Reject
```


The revision will be removed if it is of type INSERTION or will be displayed if the type is DELETION.

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
