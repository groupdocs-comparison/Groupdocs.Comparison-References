---
title: ApplyChangeOptions
second_title: GroupDocs.Comparison for Java API Reference
description: Allows updating the list of changes before applying them to the resulting document.
type: docs
weight: 10
url: /java/com.groupdocs.comparison.options/applychangeoptions/
---
**Inheritance:**
java.lang.Object
```
public class ApplyChangeOptions
```

Allows updating the list of changes before applying them to the resulting document.

Example usage:

```

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);
     comparer.compare();
     ChangeInfo[] changes = comparer.getChanges();
     changes[0].setComparisonAction(ComparisonAction.REJECT);

     final ApplyChangeOptions applyChangeOptions = new ApplyChangeOptions(changes);

     comparer.applyChanges(resultFile, applyChangeOptions);
 }
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [ApplyChangeOptions()](#ApplyChangeOptions--) | Initializes a new instance of the ApplyChangeOptions class. |
| [ApplyChangeOptions(List<ChangeInfo> changes)](#ApplyChangeOptions-java.util.List-com.groupdocs.comparison.result.ChangeInfo--) | Initializes a new instance of the ApplyChangeOptions class with list of changes. |
| [ApplyChangeOptions(ChangeInfo[] changes)](#ApplyChangeOptions-com.groupdocs.comparison.result.ChangeInfo---) | Initializes a new instance of the ApplyChangeOptions class with array of changes. |
## Methods

| Method | Description |
| --- | --- |
| [getChanges()](#getChanges--) | Gets an array of changes that must be applied to the resulting document. |
| [setChanges(ChangeInfo[] value)](#setChanges-com.groupdocs.comparison.result.ChangeInfo---) | Sets an array of changes that must be applied to the resulting document. |
| [setChanges(List<ChangeInfo> value)](#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--) | Sets a list of changes that must be applied to the resulting document. |
| [isSaveOriginalState()](#isSaveOriginalState--) | Gets a flag that determines is original state should be saved. |
| [setSaveOriginalState(boolean saveOriginalState)](#setSaveOriginalState-boolean-) | Sets a flag that determines is original state should be saved. |
### ApplyChangeOptions() {#ApplyChangeOptions--}
```
public ApplyChangeOptions()
```


Initializes a new instance of the ApplyChangeOptions class.

### ApplyChangeOptions(List<ChangeInfo> changes) {#ApplyChangeOptions-java.util.List-com.groupdocs.comparison.result.ChangeInfo--}
```
public ApplyChangeOptions(List<ChangeInfo> changes)
```


Initializes a new instance of the ApplyChangeOptions class with list of changes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| changes | java.util.List<com.groupdocs.comparison.result.ChangeInfo> | The list of changes to be applied |

### ApplyChangeOptions(ChangeInfo[] changes) {#ApplyChangeOptions-com.groupdocs.comparison.result.ChangeInfo---}
```
public ApplyChangeOptions(ChangeInfo[] changes)
```


Initializes a new instance of the ApplyChangeOptions class with array of changes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| changes | [ChangeInfo\[\]](../../com.groupdocs.comparison.result/changeinfo) | The list of changes to be applied |

### getChanges() {#getChanges--}
```
public final ChangeInfo[] getChanges()
```


Gets an array of changes that must be applied to the resulting document.

**Returns:**
com.groupdocs.comparison.result.ChangeInfo[] - the array of changes to be applied
### setChanges(ChangeInfo[] value) {#setChanges-com.groupdocs.comparison.result.ChangeInfo---}
```
public final void setChanges(ChangeInfo[] value)
```


Sets an array of changes that must be applied to the resulting document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ChangeInfo\[\]](../../com.groupdocs.comparison.result/changeinfo) | The array of changes to be applied |

### setChanges(List<ChangeInfo> value) {#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--}
```
public final void setChanges(List<ChangeInfo> value)
```


Sets a list of changes that must be applied to the resulting document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.List<com.groupdocs.comparison.result.ChangeInfo> | The list of changes to be applied |

### isSaveOriginalState() {#isSaveOriginalState--}
```
public boolean isSaveOriginalState()
```


Gets a flag that determines is original state should be saved. Default value: false.

**Returns:**
boolean - true if original state should be saved, otherwise false
### setSaveOriginalState(boolean saveOriginalState) {#setSaveOriginalState-boolean-}
```
public void setSaveOriginalState(boolean saveOriginalState)
```


Sets a flag that determines is original state should be saved.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| saveOriginalState | boolean | True if original state should be saved, otherwise false |

