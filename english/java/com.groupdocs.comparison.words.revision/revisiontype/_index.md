---
title: RevisionType
second_title: GroupDocs.Comparison for Java API Reference
description: Represents the types of revisions in a document.
type: docs
weight: 14
url: /java/com.groupdocs.comparison.words.revision/revisiontype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum RevisionType extends Enum<RevisionType>
```

Represents the types of revisions in a document.

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
| [INSERTION](#INSERTION) | Represents a type when new content was inserted in the document. |
| [DELETION](#DELETION) | Represents a type when content was removed from the document. |
| [FORMAT_CHANGE](#FORMAT-CHANGE) | Represents a type when change of formatting was applied to the parent node. |
| [STYLE_DEFINITION_CHANGE](#STYLE-DEFINITION-CHANGE) | Represents a type when change of formatting was applied to the parent style. |
| [MOVING](#MOVING) | Represents a type when content was moved in the document. |
## Methods

| Method | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [fromInt(int toIntValue)](#fromInt-int-) | Creates new constant of enum RevisionType using provided numeric value. |
| [fromString(String toStringValue)](#fromString-java.lang.String-) | Parses string representation of RevisionType to get the enum constant. |
| [toInt()](#toInt--) | Numeric representation of RevisionType. |
| [toString()](#toString--) | String representation of RevisionType. |
### INSERTION {#INSERTION}
```
public static final RevisionType INSERTION
```


Represents a type when new content was inserted in the document.

### DELETION {#DELETION}
```
public static final RevisionType DELETION
```


Represents a type when content was removed from the document.

### FORMAT_CHANGE {#FORMAT-CHANGE}
```
public static final RevisionType FORMAT_CHANGE
```


Represents a type when change of formatting was applied to the parent node.

### STYLE_DEFINITION_CHANGE {#STYLE-DEFINITION-CHANGE}
```
public static final RevisionType STYLE_DEFINITION_CHANGE
```


Represents a type when change of formatting was applied to the parent style.

### MOVING {#MOVING}
```
public static final RevisionType MOVING
```


Represents a type when content was moved in the document.

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
### fromInt(int toIntValue) {#fromInt-int-}
```
public static RevisionType fromInt(int toIntValue)
```


Creates new constant of enum RevisionType using provided numeric value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| toIntValue | int | The numeric representation of RevisionType |

**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) - RevisionType enum constant associated with numeric value
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static RevisionType fromString(String toStringValue)
```


Parses string representation of RevisionType to get the enum constant.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| toStringValue | java.lang.String | The string representation of RevisionType |

**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) - RevisionType enum constant associated with input string
### toInt() {#toInt--}
```
public int toInt()
```


Numeric representation of RevisionType.

**Returns:**
int - numeric value of enum constant
### toString() {#toString--}
```
public String toString()
```


String representation of RevisionType.

**Returns:**
java.lang.String - string value of enum constant
