---
title: ChangeType
second_title: GroupDocs.Comparison for Java API Reference
description: The ChangeType enum represents the types of changes that can occur during the document comparison process.
type: docs
weight: 14
url: /java/com.groupdocs.comparison.result/changetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ChangeType extends Enum<ChangeType>
```

The ChangeType enum represents the types of changes that can occur during the document comparison process.

Each constant in this enum represents a specific type of change and provides a human-readable description and a numeric value.

Example usage:

```

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);
     comparer.compare();
     final ChangeInfo[] changes = comparer.getChanges();
     for (ChangeInfo changeInfo : changes) {
         // Get the ChangeType for a specific change
         final ChangeType changeType = changeInfo.getType();
         // Print the ChangeType information
         System.out.println("Description: " + changeType.toString());
         System.out.println("Value: " + changeType.toInt());
     }
 }
 
```
## Fields

| Field | Description |
| --- | --- |
| [NONE](#NONE) | Represents no change. |
| [MODIFIED](#MODIFIED) | Represents a modified change. |
| [INSERTED](#INSERTED) | Represents an inserted change. |
| [DELETED](#DELETED) | Represents a deleted change. |
| [ADDED](#ADDED) | Represents an added change. |
| [NOT_MODIFIED](#NOT-MODIFIED) | Represents a not modified change. |
| [STYLE_CHANGED](#STYLE-CHANGED) | Represents a style changed change. |
| [RESIZED](#RESIZED) | Represents a resized change. |
| [MOVED](#MOVED) | Represents a moved change. |
| [MOVED_AND_RESIZED](#MOVED-AND-RESIZED) | Represents a moved and resized change. |
| [SHIFTED_AND_RESIZED](#SHIFTED-AND-RESIZED) | Represents a shifted and resized change. |
## Methods

| Method | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [fromString(String toStringValue)](#fromString-java.lang.String-) | Parses string representation of ChangeType to get the enum constant. |
| [fromInt(int intValue)](#fromInt-int-) | Creates new constant of enum ChangeType using provided numeric value. |
| [toString()](#toString--) | String representation of ChangeType. |
| [toInt()](#toInt--) | Numeric representation of ChangeType. |
### NONE {#NONE}
```
public static final ChangeType NONE
```


Represents no change.

### MODIFIED {#MODIFIED}
```
public static final ChangeType MODIFIED
```


Represents a modified change.

### INSERTED {#INSERTED}
```
public static final ChangeType INSERTED
```


Represents an inserted change.

### DELETED {#DELETED}
```
public static final ChangeType DELETED
```


Represents a deleted change.

### ADDED {#ADDED}
```
public static final ChangeType ADDED
```


Represents an added change.

### NOT_MODIFIED {#NOT-MODIFIED}
```
public static final ChangeType NOT_MODIFIED
```


Represents a not modified change.

### STYLE_CHANGED {#STYLE-CHANGED}
```
public static final ChangeType STYLE_CHANGED
```


Represents a style changed change.

### RESIZED {#RESIZED}
```
public static final ChangeType RESIZED
```


Represents a resized change.

### MOVED {#MOVED}
```
public static final ChangeType MOVED
```


Represents a moved change.

### MOVED_AND_RESIZED {#MOVED-AND-RESIZED}
```
public static final ChangeType MOVED_AND_RESIZED
```


Represents a moved and resized change.

### SHIFTED_AND_RESIZED {#SHIFTED-AND-RESIZED}
```
public static final ChangeType SHIFTED_AND_RESIZED
```


Represents a shifted and resized change.

### values() {#values--}
```
public static ChangeType[] values()
```




**Returns:**
com.groupdocs.comparison.result.ChangeType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static ChangeType valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static ChangeType fromString(String toStringValue)
```


Parses string representation of ChangeType to get the enum constant.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| toStringValue | java.lang.String | The string representation of ChangeType |

**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - ChangeType enum constant associated with input string
### fromInt(int intValue) {#fromInt-int-}
```
public static ChangeType fromInt(int intValue)
```


Creates new constant of enum ChangeType using provided numeric value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| intValue | int | The numeric representation of ChangeType |

**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - ChangeType enum constant associated with numeric value
### toString() {#toString--}
```
public String toString()
```


String representation of ChangeType.

**Returns:**
java.lang.String - string value of enum constant
### toInt() {#toInt--}
```
public int toInt()
```


Numeric representation of ChangeType.

**Returns:**
int - numeric value of enum constant
