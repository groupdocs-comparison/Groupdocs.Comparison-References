---
title: ChangeInfo
second_title: GroupDocs.Comparison for Java API Reference
description: Represents information about change.
type: docs
weight: 11
url: /java/com.groupdocs.comparison.result/changeinfo/
---
**Inheritance:**
java.lang.Object
```
public class ChangeInfo
```

Represents information about change.
## Constructors

| Constructor | Description |
| --- | --- |
| [ChangeInfo()](#ChangeInfo--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getId()](#getId--) | Id of change. |
| [setId(int value)](#setId-int-) | Id of change. |
| [getComparisonAction()](#getComparisonAction--) | Action (accept or reject). |
| [setComparisonAction(ComparisonAction value)](#setComparisonAction-com.groupdocs.comparison.result.ComparisonAction-) | Action (accept or reject). |
| [getPageInfo()](#getPageInfo--) | Page where current change is placed. |
| [setPageInfo(PageInfo value)](#setPageInfo-com.groupdocs.comparison.result.PageInfo-) | Page where current change is placed. |
| [getBox()](#getBox--) | Coordinates of changed element. |
| [setBox(Rectangle value)](#setBox-com.groupdocs.comparison.result.Rectangle-) | Coordinates of changed element. |
| [getText()](#getText--) | Text value of change. |
| [setText(String value)](#setText-java.lang.String-) | Text value of change. |
| [getStyleChanges()](#getStyleChanges--) | Style changes. |
| [setStyleChanges(List<StyleChangeInfo> value)](#setStyleChanges-java.util.List-com.groupdocs.comparison.result.StyleChangeInfo--) | Style changes. |
| [getAuthors()](#getAuthors--) | Authors. |
| [setAuthors(List<String> value)](#setAuthors-java.util.List-java.lang.String--) | Authors. |
| [getType()](#getType--) | Type of change. |
| [getTargetText()](#getTargetText--) | Changed text of target doc. |
| [setTargetText(String mTargetText)](#setTargetText-java.lang.String-) | Changed text of target doc. |
| [getSourceText()](#getSourceText--) | Changed text of source doc. |
| [setSourceText(String sourceText)](#setSourceText-java.lang.String-) | Changed text of source doc. |
| [getComponentType()](#getComponentType--) | Type of changed component |
| [setComponentType(String componentType)](#setComponentType-java.lang.String-) | Type of changed component |
| [toString()](#toString--) |  |
### ChangeInfo() {#ChangeInfo--}
```
public ChangeInfo()
```


### getId() {#getId--}
```
public final int getId()
```


Id of change.

**Returns:**
int - the id
### setId(int value) {#setId-int-}
```
public final void setId(int value)
```


Id of change.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | the value |

### getComparisonAction() {#getComparisonAction--}
```
public final ComparisonAction getComparisonAction()
```


Action (accept or reject). This field tells comparison what to do with this change.

**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) - the comparison action
### setComparisonAction(ComparisonAction value) {#setComparisonAction-com.groupdocs.comparison.result.ComparisonAction-}
```
public final void setComparisonAction(ComparisonAction value)
```


Action (accept or reject). This field tells comparison what to do with this change.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) | the value |

### getPageInfo() {#getPageInfo--}
```
public final PageInfo getPageInfo()
```


Page where current change is placed.

**Returns:**
[PageInfo](../../com.groupdocs.comparison.result/pageinfo) - the page info
### setPageInfo(PageInfo value) {#setPageInfo-com.groupdocs.comparison.result.PageInfo-}
```
public final void setPageInfo(PageInfo value)
```


Page where current change is placed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PageInfo](../../com.groupdocs.comparison.result/pageinfo) | the value |

### getBox() {#getBox--}
```
public final Rectangle getBox()
```


Coordinates of changed element.

**Returns:**
[Rectangle](../../com.groupdocs.comparison.result/rectangle) - the box
### setBox(Rectangle value) {#setBox-com.groupdocs.comparison.result.Rectangle-}
```
public final void setBox(Rectangle value)
```


Coordinates of changed element.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.groupdocs.comparison.result/rectangle) | the value |

### getText() {#getText--}
```
public final String getText()
```


Text value of change.

**Returns:**
java.lang.String - the text
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Text value of change.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | the value |

### getStyleChanges() {#getStyleChanges--}
```
public final List<StyleChangeInfo> getStyleChanges()
```


Style changes.

**Returns:**
java.util.List<com.groupdocs.comparison.result.StyleChangeInfo> - the style changes
### setStyleChanges(List<StyleChangeInfo> value) {#setStyleChanges-java.util.List-com.groupdocs.comparison.result.StyleChangeInfo--}
```
public final void setStyleChanges(List<StyleChangeInfo> value)
```


Style changes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.List<com.groupdocs.comparison.result.StyleChangeInfo> | the value |

### getAuthors() {#getAuthors--}
```
public final List<String> getAuthors()
```


Authors.

**Returns:**
java.util.List<java.lang.String> - the authors
### setAuthors(List<String> value) {#setAuthors-java.util.List-java.lang.String--}
```
public final void setAuthors(List<String> value)
```


Authors.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.List<java.lang.String> | the value |

### getType() {#getType--}
```
public final ChangeType getType()
```


Type of change.

**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - the type
### getTargetText() {#getTargetText--}
```
public String getTargetText()
```


Changed text of target doc.

**Returns:**
java.lang.String - Changed text of target doc.
### setTargetText(String mTargetText) {#setTargetText-java.lang.String-}
```
public void setTargetText(String mTargetText)
```


Changed text of target doc.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mTargetText | java.lang.String | Changed text of target doc. |

### getSourceText() {#getSourceText--}
```
public String getSourceText()
```


Changed text of source doc.

**Returns:**
java.lang.String - text of source doc.
### setSourceText(String sourceText) {#setSourceText-java.lang.String-}
```
public void setSourceText(String sourceText)
```


Changed text of source doc.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceText | java.lang.String | text of source doc. |

### getComponentType() {#getComponentType--}
```
public String getComponentType()
```


Type of changed component

**Returns:**
java.lang.String - the component type
### setComponentType(String componentType) {#setComponentType-java.lang.String-}
```
public void setComponentType(String componentType)
```


Type of changed component

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| componentType | java.lang.String | the component type |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
