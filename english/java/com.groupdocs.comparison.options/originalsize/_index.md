---
title: OriginalSize
second_title: GroupDocs.Comparison for Java API Reference
description: Represents the original size of a document in a comparison result.
type: docs
weight: 14
url: /java/com.groupdocs.comparison.options/originalsize/
---
**Inheritance:**
java.lang.Object
```
public class OriginalSize
```

Represents the original size of a document in a comparison result.

The original size includes the dimensions (width and height) of the document's pages.

Example usage:

```

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     CompareOptions compareOptions = new CompareOptions();
     final OriginalSize originalSize = compareOptions.getOriginalSize();
     originalSize.setWidth(480);
     originalSize.setHeight(640);

     comparer.compare(resultFile, compareOptions);
 }
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [OriginalSize()](#OriginalSize--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getWidth()](#getWidth--) | Gets the width of the document's pages. |
| [setWidth(int value)](#setWidth-int-) | Sets the width of the document's pages. |
| [getHeight()](#getHeight--) | Gets the height of the document's pages. |
| [setHeight(int value)](#setHeight-int-) | Sets the height of the document's pages. |
### OriginalSize() {#OriginalSize--}
```
public OriginalSize()
```


### getWidth() {#getWidth--}
```
public final int getWidth()
```


Gets the width of the document's pages.

**Returns:**
int - the width of the document's pages.
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Sets the width of the document's pages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The width of the document's pages. |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Gets the height of the document's pages.

**Returns:**
int - the height of the document's pages.
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Sets the height of the document's pages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The height of the document's pages. |

