---
title: RevisionType
second_title: GroupDocs.Comparison for Java API Reference
description: Specifies the type of change being tracked
type: docs
weight: 14
url: /java/com.groupdocs.comparison.words.revision/revisiontype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum RevisionType extends Enum<RevisionType>
```

Specifies the type of change being tracked
## Fields

| Field | Description |
| --- | --- |
| [Insertion](#Insertion) | New content was inserted in the document. |
| [Deletion](#Deletion) | Content was removed from the document. |
| [FormatChange](#FormatChange) | Change of formatting was applied to the parent node. |
| [StyleDefinitionChange](#StyleDefinitionChange) | Change of formatting was applied to the parent style. |
| [Moving](#Moving) | Content was moved in the document. |
## Methods

| Method | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### Insertion {#Insertion}
```
public static final RevisionType Insertion
```


New content was inserted in the document.

### Deletion {#Deletion}
```
public static final RevisionType Deletion
```


Content was removed from the document.

### FormatChange {#FormatChange}
```
public static final RevisionType FormatChange
```


Change of formatting was applied to the parent node.

### StyleDefinitionChange {#StyleDefinitionChange}
```
public static final RevisionType StyleDefinitionChange
```


Change of formatting was applied to the parent style.

### Moving {#Moving}
```
public static final RevisionType Moving
```


Content was moved in the document.

### values() {#values--}
```
public static RevisionType[] values()
```




**Returns:**
com.groupdocs.comparison.words.revision.RevisionType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static RevisionType valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype)
