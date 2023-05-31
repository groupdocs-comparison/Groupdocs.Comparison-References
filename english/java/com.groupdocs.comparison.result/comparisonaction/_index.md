---
title: ComparisonAction
second_title: GroupDocs.Comparison for Java API Reference
description: The ComparisonAction enum represents the actions that can be applied to a change during the document comparison process.
type: docs
weight: 15
url: /java/com.groupdocs.comparison.result/comparisonaction/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ComparisonAction extends Enum<ComparisonAction>
```

The ComparisonAction enum represents the actions that can be applied to a change during the document comparison process.

Each constant in this enum represents a specific action and provides a human-readable description and a numeric value.

Example usage:

```

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);
     comparer.compare();

     final ChangeInfo[] changes = comparer.getChanges();
     for (ChangeInfo changeInfo : changes) {
         if (changeInfo.getId() % 2 == 0) {
             changeInfo.setComparisonAction(ComparisonAction.REJECT);
         }
     }
     comparer.applyChanges(resultFile, changes);
 }
 
```
## Fields

| Field | Description |
| --- | --- |
| [NONE](#NONE) | Represents no action. |
| [ACCEPT](#ACCEPT) | Represents an accept action. |
| [REJECT](#REJECT) | Represents a reject action. |
## Methods

| Method | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [fromString(String toStringValue)](#fromString-java.lang.String-) | Parses string representation of ComparisonAction to get the enum constant. |
| [fromInt(int intValue)](#fromInt-int-) | Creates new constant of enum ComparisonAction using provided numeric value. |
| [toString()](#toString--) | String representation of ComparisonAction. |
| [toInt()](#toInt--) | Numeric representation of ComparisonAction. |
### NONE {#NONE}
```
public static final ComparisonAction NONE
```


Represents no action. The change will have no effect.

### ACCEPT {#ACCEPT}
```
public static final ComparisonAction ACCEPT
```


Represents an accept action. The change will be visible in the result file.

### REJECT {#REJECT}
```
public static final ComparisonAction REJECT
```


Represents a reject action. The change will be invisible in the result file.

### values() {#values--}
```
public static ComparisonAction[] values()
```




**Returns:**
com.groupdocs.comparison.result.ComparisonAction[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static ComparisonAction valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static ComparisonAction fromString(String toStringValue)
```


Parses string representation of ComparisonAction to get the enum constant.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| toStringValue | java.lang.String | The string representation of ComparisonAction |

**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) - ComparisonAction enum constant associated with input string
### fromInt(int intValue) {#fromInt-int-}
```
public static ComparisonAction fromInt(int intValue)
```


Creates new constant of enum ComparisonAction using provided numeric value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| intValue | int | The numeric representation of ComparisonAction |

**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) - ComparisonAction enum constant associated with numeric value
### toString() {#toString--}
```
public String toString()
```


String representation of ComparisonAction.

**Returns:**
java.lang.String - string value of enum constant
### toInt() {#toInt--}
```
public int toInt()
```


Numeric representation of ComparisonAction.

**Returns:**
int - numeric value of enum constant
