---
title: ApplyChangeOptions
second_title: GroupDocs.Comparison for Java API Reference
description: Allows to update the list of changes before applying them to the resulting document.
type: docs
weight: 10
url: /java/com.groupdocs.comparison.options/applychangeoptions/
---
**Inheritance:**
java.lang.Object
```
public class ApplyChangeOptions
```

Allows to update the list of changes before applying them to the resulting document.
## Constructors

| Constructor | Description |
| --- | --- |
| [ApplyChangeOptions()](#ApplyChangeOptions--) | Initializes a new instance of the @[ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) class |
| [ApplyChangeOptions(List<ChangeInfo> changes)](#ApplyChangeOptions-java.util.List-com.groupdocs.comparison.result.ChangeInfo--) | Initializes a new instance of the @[ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) class |
| [ApplyChangeOptions(ChangeInfo[] changes)](#ApplyChangeOptions-com.groupdocs.comparison.result.ChangeInfo---) | Initializes a new instance of the @[ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) class |
## Methods

| Method | Description |
| --- | --- |
| [getChanges()](#getChanges--) | List of changes that must be applied to the resulting document. |
| [setChanges(ChangeInfo[] value)](#setChanges-com.groupdocs.comparison.result.ChangeInfo---) | List of changes that must be applied to the resulting document. |
| [setChanges(List<ChangeInfo> value)](#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--) | List of changes that must be applied to the resulting document. |
| [isSaveOriginalState()](#isSaveOriginalState--) | Is save original state boolean. |
| [setSaveOriginalState(boolean saveOriginalState)](#setSaveOriginalState-boolean-) | Sets save original state. |
### ApplyChangeOptions() {#ApplyChangeOptions--}
```
public ApplyChangeOptions()
```


Initializes a new instance of the @[ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) class

### ApplyChangeOptions(List<ChangeInfo> changes) {#ApplyChangeOptions-java.util.List-com.groupdocs.comparison.result.ChangeInfo--}
```
public ApplyChangeOptions(List<ChangeInfo> changes)
```


Initializes a new instance of the @[ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| changes | java.util.List<com.groupdocs.comparison.result.ChangeInfo> | the changes |

### ApplyChangeOptions(ChangeInfo[] changes) {#ApplyChangeOptions-com.groupdocs.comparison.result.ChangeInfo---}
```
public ApplyChangeOptions(ChangeInfo[] changes)
```


Initializes a new instance of the @[ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| changes | [ChangeInfo\[\]](../../com.groupdocs.comparison.result/changeinfo) | the changes |

### getChanges() {#getChanges--}
```
public final ChangeInfo[] getChanges()
```


List of changes that must be applied to the resulting document.

**Returns:**
com.groupdocs.comparison.result.ChangeInfo[] - changes change info [ ]
### setChanges(ChangeInfo[] value) {#setChanges-com.groupdocs.comparison.result.ChangeInfo---}
```
public final void setChanges(ChangeInfo[] value)
```


List of changes that must be applied to the resulting document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ChangeInfo\[\]](../../com.groupdocs.comparison.result/changeinfo) | changes |

### setChanges(List<ChangeInfo> value) {#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--}
```
public final void setChanges(List<ChangeInfo> value)
```


List of changes that must be applied to the resulting document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.List<com.groupdocs.comparison.result.ChangeInfo> | changes |

### isSaveOriginalState() {#isSaveOriginalState--}
```
public boolean isSaveOriginalState()
```


Is save original state boolean.

**Returns:**
boolean - the boolean
### setSaveOriginalState(boolean saveOriginalState) {#setSaveOriginalState-boolean-}
```
public void setSaveOriginalState(boolean saveOriginalState)
```


Sets save original state.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| saveOriginalState | boolean | the save original state |

