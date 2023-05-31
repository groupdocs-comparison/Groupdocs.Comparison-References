---
title: Rectangle
second_title: GroupDocs.Comparison for Java API Reference
description: The Rectangle class represents changed area on a document.
type: docs
weight: 12
url: /java/com.groupdocs.comparison.result/rectangle/
---
**Inheritance:**
java.lang.Object
```
public final class Rectangle
```

The Rectangle class represents changed area on a document.

Example usage:

```

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     comparer.compare(resultFile);
     final ChangeInfo[] changes = comparer.getChanges();
     for (ChangeInfo change : changes) {
         final Rectangle box = change.getBox();
         // Print the changed area on page
         System.out.println("Changed area on a page: "
                 + box.getX() + ", " + box.getY() + ", " + box.getWidth() + ", " + box.getHeight());
     }
 }
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [Rectangle()](#Rectangle--) | Initializes a new instance of the Rectangle class. |
| [Rectangle(Rectangle other)](#Rectangle-com.groupdocs.comparison.result.Rectangle-) | Creates a new Rectangle object that is a copy of the specified rectangle. |
| [Rectangle(double x, double y, double width, double height)](#Rectangle-double-double-double-double-) | Creates a new instance of the Rectangle class with the specified x, y, width, and height. |
## Methods

| Method | Description |
| --- | --- |
| [getHeight()](#getHeight--) | Gets the height of the rectangle. |
| [setHeight(double value)](#setHeight-double-) | Sets the height of the rectangle. |
| [getWidth()](#getWidth--) | Gets the width of the rectangle. |
| [setWidth(double value)](#setWidth-double-) | Sets the width of the rectangle. |
| [getX()](#getX--) | Gets the x-coordinate of the top-left corner of the rectangle. |
| [setX(double value)](#setX-double-) | Sets the x-coordinate of the top-left corner of the rectangle. |
| [getY()](#getY--) | Gets the y-coordinate of the top-left corner of the rectangle. |
| [setY(double value)](#setY-double-) | Sets the y-coordinate of the top-left corner of the rectangle. |
| [equals(Object o)](#equals-java.lang.Object-) | \{@inheritDoc\} |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | \{@inheritDoc\} |
### Rectangle() {#Rectangle--}
```
public Rectangle()
```


Initializes a new instance of the Rectangle class.

### Rectangle(Rectangle other) {#Rectangle-com.groupdocs.comparison.result.Rectangle-}
```
public Rectangle(Rectangle other)
```


Creates a new Rectangle object that is a copy of the specified rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [Rectangle](../../com.groupdocs.comparison.result/rectangle) | The rectangle to be copied |

### Rectangle(double x, double y, double width, double height) {#Rectangle-double-double-double-double-}
```
public Rectangle(double x, double y, double width, double height)
```


Creates a new instance of the Rectangle class with the specified x, y, width, and height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | double | The x-coordinate of the top-left corner of the rectangle |
| y | double | The y-coordinate of the top-left corner of the rectangle |
| width | double | The width of the rectangle |
| height | double | The height of the rectangle |

### getHeight() {#getHeight--}
```
public double getHeight()
```


Gets the height of the rectangle.

**Returns:**
double - the height of the rectangle
### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Sets the height of the rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The height of the rectangle |

### getWidth() {#getWidth--}
```
public double getWidth()
```


Gets the width of the rectangle.

**Returns:**
double - the width of the rectangle
### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Sets the width of the rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The width of the rectangle |

### getX() {#getX--}
```
public double getX()
```


Gets the x-coordinate of the top-left corner of the rectangle.

**Returns:**
double - the x-coordinate of the top-left corner of the rectangle
### setX(double value) {#setX-double-}
```
public void setX(double value)
```


Sets the x-coordinate of the top-left corner of the rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The x-coordinate of the top-left corner of the rectangle |

### getY() {#getY--}
```
public double getY()
```


Gets the y-coordinate of the top-left corner of the rectangle.

**Returns:**
double - the y-coordinate of the top-left corner of the rectangle
### setY(double value) {#setY-double-}
```
public void setY(double value)
```


Sets the y-coordinate of the top-left corner of the rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The y-coordinate of the top-left corner of the rectangle |

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
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
