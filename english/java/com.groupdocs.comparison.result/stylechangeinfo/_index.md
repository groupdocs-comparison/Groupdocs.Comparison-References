---
title: StyleChangeInfo
second_title: GroupDocs.Comparison for Java API Reference
description: The StyleChangeInfo class represents information about a style change in a compared document.
type: docs
weight: 13
url: /java/com.groupdocs.comparison.result/stylechangeinfo/
---
**Inheritance:**
java.lang.Object
```
public class StyleChangeInfo
```

The StyleChangeInfo class represents information about a style change in a compared document.

It provides details such as the changed property name, values before and after the change, and so on. Use this class to retrieve information about style changes during the document comparison process.

Example usage:

```

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     comparer.compare();
     final ChangeInfo[] changes = comparer.getChanges();
     for (ChangeInfo change : changes) {
         // Access the style change information
         final List styleChanges = change.getStyleChanges();
         for (StyleChangeInfo styleChange : styleChanges) {
             // Print the style change information
             System.out.println("PropertyName: " + styleChange.getPropertyName());
             System.out.println("OldValue: " + styleChange.getOldValue());
             System.out.println("NewValue: " + styleChange.getNewValue());
         }
     }
 }
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [StyleChangeInfo()](#StyleChangeInfo--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getPropertyName()](#getPropertyName--) | Gets the name of the property that was changed. |
| [setPropertyName(String value)](#setPropertyName-java.lang.String-) | Sets the name of the property that was changed. |
| [getNewValue()](#getNewValue--) | Gets the new value of the property. |
| [setNewValue(Object value)](#setNewValue-java.lang.Object-) | Sets the new value of the property. |
| [getOldValue()](#getOldValue--) | Gets the old value of the property. |
| [setOldValue(Object value)](#setOldValue-java.lang.Object-) | Sets the old value of the property. |
| [equals(Object o)](#equals-java.lang.Object-) | \{@inheritDoc\} |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
### StyleChangeInfo() {#StyleChangeInfo--}
```
public StyleChangeInfo()
```


### getPropertyName() {#getPropertyName--}
```
public final String getPropertyName()
```


Gets the name of the property that was changed.

**Returns:**
java.lang.String - the property name
### setPropertyName(String value) {#setPropertyName-java.lang.String-}
```
public final void setPropertyName(String value)
```


Sets the name of the property that was changed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The property name |

### getNewValue() {#getNewValue--}
```
public final Object getNewValue()
```


Gets the new value of the property.

**Returns:**
java.lang.Object - the new value of the property
### setNewValue(Object value) {#setNewValue-java.lang.Object-}
```
public final void setNewValue(Object value)
```


Sets the new value of the property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object | The new value of the property |

### getOldValue() {#getOldValue--}
```
public final Object getOldValue()
```


Gets the old value of the property.

**Returns:**
java.lang.Object - the old value of the property
### setOldValue(Object value) {#setOldValue-java.lang.Object-}
```
public final void setOldValue(Object value)
```


Sets the old value of the property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object | The old value of the property |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| o | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
