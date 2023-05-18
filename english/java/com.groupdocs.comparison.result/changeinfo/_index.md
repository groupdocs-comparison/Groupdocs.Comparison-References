---
title: ChangeInfo
second_title: GroupDocs.Comparison for Java API Reference
description: The ChangeInfo class represents information about a specific change in a document comparison.
type: docs
weight: 10
url: /java/com.groupdocs.comparison.result/changeinfo/
---
**Inheritance:**
java.lang.Object
```
public class ChangeInfo
```

The ChangeInfo class represents information about a specific change in a document comparison.

It provides details such as the type of change, the affected area, and the content before and after the change. Use this class to retrieve information about individual changes within a comparison result.

Example usage:

```

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     comparer.compare(resultFile);
     // Get a list of changes from the comparison result
     ChangeInfo[] changes = comparer.getChanges();
     // Iterate through the changes and retrieve information
     for (ChangeInfo change : changes) {
         ChangeType changeType = change.getType();
         String componentType = change.getComponentType();
         PageInfo pageInfo = change.getPageInfo();
         // Process the change information as needed
         // ...
     }
 }
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [ChangeInfo()](#ChangeInfo--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getId()](#getId--) | Gets unique id of the change. |
| [setId(int value)](#setId-int-) | Sets unique id of the change. |
| [getComparisonAction()](#getComparisonAction--) | Gets the action that will be applied to the change. |
| [setComparisonAction(ComparisonAction value)](#setComparisonAction-com.groupdocs.comparison.result.ComparisonAction-) | Sets the action that should be applied to the change. |
| [getPageInfo()](#getPageInfo--) | Gets information about the page, on which current change was found. |
| [setPageInfo(PageInfo value)](#setPageInfo-com.groupdocs.comparison.result.PageInfo-) | Sets information about the page, on which current change was found. |
| [getBox()](#getBox--) | Gets coordinates of changed element on the page. |
| [setBox(Rectangle value)](#setBox-com.groupdocs.comparison.result.Rectangle-) | Sets coordinates of changed element on the page. |
| [getText()](#getText--) | Gets text value of the change. |
| [setText(String value)](#setText-java.lang.String-) | Sets text value of the change. |
| [getStyleChanges()](#getStyleChanges--) | Gets the list of style changes. |
| [setStyleChanges(List<StyleChangeInfo> value)](#setStyleChanges-java.util.List-com.groupdocs.comparison.result.StyleChangeInfo--) | Sets the list of style changes. |
| [getAuthors()](#getAuthors--) | Gets the list of authors. |
| [setAuthors(List<String> value)](#setAuthors-java.util.List-java.lang.String--) | Sets the list of authors. |
| [getType()](#getType--) | Gets the type of the change represented by enum [ChangeType](../../com.groupdocs.comparison.result/changetype). |
| [getTargetText()](#getTargetText--) | Gets changed text from target document. |
| [setTargetText(String value)](#setTargetText-java.lang.String-) | Sets changed text from target document. |
| [getSourceText()](#getSourceText--) | Gets changed text from source document. |
| [setSourceText(String value)](#setSourceText-java.lang.String-) | Sets changed text from source document. |
| [getComponentType()](#getComponentType--) | Gets the type of the changed component. |
| [setComponentType(String value)](#setComponentType-java.lang.String-) | Sets the type of the changed component. |
| [toString()](#toString--) |  |
### ChangeInfo() {#ChangeInfo--}
```
public ChangeInfo()
```


### getId() {#getId--}
```
public final int getId()
```


Gets unique id of the change.

**Returns:**
int - the id of the change
### setId(int value) {#setId-int-}
```
public final void setId(int value)
```


Sets unique id of the change.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The id of the change |

### getComparisonAction() {#getComparisonAction--}
```
public final ComparisonAction getComparisonAction()
```


Gets the action that will be applied to the change.

Action ([ComparisonAction.ACCEPT](../../com.groupdocs.comparison.result/comparisonaction\#ACCEPT) or [ComparisonAction.REJECT](../../com.groupdocs.comparison.result/comparisonaction\#REJECT)) tells comparison what to do with this change.

**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) - the action that will be applied to the change
### setComparisonAction(ComparisonAction value) {#setComparisonAction-com.groupdocs.comparison.result.ComparisonAction-}
```
public final void setComparisonAction(ComparisonAction value)
```


Sets the action that should be applied to the change.

Action ([ComparisonAction.ACCEPT](../../com.groupdocs.comparison.result/comparisonaction\#ACCEPT) or [ComparisonAction.REJECT](../../com.groupdocs.comparison.result/comparisonaction\#REJECT)) tells comparison what to do with this change.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) | The action that should be applied to the change |

### getPageInfo() {#getPageInfo--}
```
public final PageInfo getPageInfo()
```


Gets information about the page, on which current change was found.

**Returns:**
[PageInfo](../../com.groupdocs.comparison.result/pageinfo) - information about the page
### setPageInfo(PageInfo value) {#setPageInfo-com.groupdocs.comparison.result.PageInfo-}
```
public final void setPageInfo(PageInfo value)
```


Sets information about the page, on which current change was found.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PageInfo](../../com.groupdocs.comparison.result/pageinfo) | Information about the page |

### getBox() {#getBox--}
```
public final Rectangle getBox()
```


Gets coordinates of changed element on the page.

**Returns:**
[Rectangle](../../com.groupdocs.comparison.result/rectangle) - coordinates of changed element
### setBox(Rectangle value) {#setBox-com.groupdocs.comparison.result.Rectangle-}
```
public final void setBox(Rectangle value)
```


Sets coordinates of changed element on the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.groupdocs.comparison.result/rectangle) | Coordinates of changed element, not null |

### getText() {#getText--}
```
public final String getText()
```


Gets text value of the change.

**Returns:**
java.lang.String - text value of the change
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Sets text value of the change.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Text value of the change |

### getStyleChanges() {#getStyleChanges--}
```
public final List<StyleChangeInfo> getStyleChanges()
```


Gets the list of style changes.

**Returns:**
java.util.List<com.groupdocs.comparison.result.StyleChangeInfo> - the list of style changes
### setStyleChanges(List<StyleChangeInfo> value) {#setStyleChanges-java.util.List-com.groupdocs.comparison.result.StyleChangeInfo--}
```
public final void setStyleChanges(List<StyleChangeInfo> value)
```


Sets the list of style changes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.List<com.groupdocs.comparison.result.StyleChangeInfo> | The list of style changes |

### getAuthors() {#getAuthors--}
```
public final List<String> getAuthors()
```


Gets the list of authors.

**Returns:**
java.util.List<java.lang.String> - the list of authors
### setAuthors(List<String> value) {#setAuthors-java.util.List-java.lang.String--}
```
public final void setAuthors(List<String> value)
```


Sets the list of authors.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.List<java.lang.String> | The list of authors |

### getType() {#getType--}
```
public final ChangeType getType()
```


Gets the type of the change represented by enum [ChangeType](../../com.groupdocs.comparison.result/changetype).

**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - the type of the change
### getTargetText() {#getTargetText--}
```
public String getTargetText()
```


Gets changed text from target document.

**Returns:**
java.lang.String - the changed text
### setTargetText(String value) {#setTargetText-java.lang.String-}
```
public void setTargetText(String value)
```


Sets changed text from target document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The changed text |

### getSourceText() {#getSourceText--}
```
public String getSourceText()
```


Gets changed text from source document.

**Returns:**
java.lang.String - the changed text
### setSourceText(String value) {#setSourceText-java.lang.String-}
```
public void setSourceText(String value)
```


Sets changed text from source document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The changed text |

### getComponentType() {#getComponentType--}
```
public String getComponentType()
```


Gets the type of the changed component.

**Returns:**
java.lang.String - the type of the changed component
### setComponentType(String value) {#setComponentType-java.lang.String-}
```
public void setComponentType(String value)
```


Sets the type of the changed component.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The type of the changed component |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
