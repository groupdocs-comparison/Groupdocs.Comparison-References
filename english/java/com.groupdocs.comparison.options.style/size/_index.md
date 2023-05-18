---
title: Size
second_title: GroupDocs.Comparison for Java API Reference
description: Represents the size of document in comparison.
type: docs
weight: 11
url: /java/com.groupdocs.comparison.options.style/size/
---
**Inheritance:**
java.lang.Object
```
public class Size
```

Represents the size of document in comparison.

Example usage:

```

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     final Size originalSize = new Size(100, 200);

     StyleSettings styleSettings = new StyleSettings();
     styleSettings.setOriginalSize(originalSize);

     final CompareOptions compareOptions = new CompareOptions();
     compareOptions.setInsertedItemStyle(styleSettings);

     comparer.compare(resultFile, compareOptions);
 }
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [Size()](#Size--) | Initializes a new instance of the Size class. |
| [Size(int width, int height)](#Size-int-int-) | Initializes a new instance of the Size class with width and height of a document. |
## Methods

| Method | Description |
| --- | --- |
| [getWidth()](#getWidth--) | Gets the width of an original document. |
| [setWidth(int value)](#setWidth-int-) | Sets the width of an original document. |
| [getHeight()](#getHeight--) | Gets the height of an original document. |
| [setHeight(int value)](#setHeight-int-) | Sets the height of an original document. |
### Size() {#Size--}
```
public Size()
```


Initializes a new instance of the Size class.

### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


Initializes a new instance of the Size class with width and height of a document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int |  |
| height | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Gets the width of an original document.

**Returns:**
int - the width of the document
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Sets the width of an original document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The width of the document |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Gets the height of an original document.

**Returns:**
int - the height of the document
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Sets the height of an original document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The height of the document |

