---
title: PageInfo
second_title: GroupDocs.Comparison for Java API Reference
description: The PageInfo class represents information about a specific page in a document.
type: docs
weight: 11
url: /java/com.groupdocs.comparison.result/pageinfo/
---
**Inheritance:**
java.lang.Object
```
public class PageInfo
```

The PageInfo class represents information about a specific page in a document.

It provides details such as the page number, width, height, and other relevant properties. Use this class to retrieve information about individual pages in a document during the comparison process.

Example usage:

```

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     comparer.compare(resultFile);
     final ChangeInfo[] changes = comparer.getChanges();
     for (ChangeInfo change : changes) {
         final PageInfo pageInfo = change.getPageInfo();
         // Print the page information
         System.out.println("Page Number: " + pageInfo.getPageNumber());
         System.out.println("Page Width: " + pageInfo.getWidth());
         System.out.println("Page Height: " + pageInfo.getHeight());
     }
 }
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [PageInfo(int pageNumber, int width, int height)](#PageInfo-int-int-int-) | Initializes a new instance of the PageInfo class with configuring pageNumber, width and height. |
## Methods

| Method | Description |
| --- | --- |
| [getWidth()](#getWidth--) | Gets the width of the page |
| [setWidth(int value)](#setWidth-int-) | Sets the width of the page |
| [getHeight()](#getHeight--) | Gets the height of the page |
| [setHeight(int value)](#setHeight-int-) | Sets the height of the page |
| [getPageNumber()](#getPageNumber--) | Gets the number of the page |
| [setPageNumber(int value)](#setPageNumber-int-) | Sets the number of the page |
| [toString()](#toString--) |  |
### PageInfo(int pageNumber, int width, int height) {#PageInfo-int-int-int-}
```
public PageInfo(int pageNumber, int width, int height)
```


Initializes a new instance of the PageInfo class with configuring pageNumber, width and height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | The number of the page |
| width | int | The width of the page |
| height | int | The height of the page |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Gets the width of the page

**Returns:**
int - the width of the page
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Sets the width of the page

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The width of the page |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Gets the height of the page

**Returns:**
int - the height of the page
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Sets the height of the page

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The height of the page |

### getPageNumber() {#getPageNumber--}
```
public final int getPageNumber()
```


Gets the number of the page

**Returns:**
int - the number of the page
### setPageNumber(int value) {#setPageNumber-int-}
```
public final void setPageNumber(int value)
```


Sets the number of the page

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The number of the page |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
