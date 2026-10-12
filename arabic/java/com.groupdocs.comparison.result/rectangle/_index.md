---
title: "Rectangle"
second_title: "GroupDocs.Comparison لـ Java API Reference"
description: "تمثل فئة Rectangle المنطقة المتغيرة في المستند."
type: docs
weight: 12
url: /ar/java/com.groupdocs.comparison.result/rectangle/
---
**Inheritance:**
java.lang.Object
```
public final class Rectangle
```

تمثل فئة Rectangle المنطقة المتغيرة في المستند.


مثال على الاستخدام:

````

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
 
````


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [Rectangle()](#Rectangle--) | يُهيئ نسخة جديدة من فئة Rectangle. |
|
|  | [Rectangle(Rectangle other)](#Rectangle-com.groupdocs.comparison.result.Rectangle-) | ينشئ كائن Rectangle جديد يكون نسخة من المستطيل المحدد. |
|
|  | [Rectangle(double x, double y, double width, double height)](#Rectangle-double-double-double-double-) | ينشئ نسخة جديدة من فئة Rectangle باستخدام القيم المحددة لـ x و y والعرض والارتفاع. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getHeight()](#getHeight--) | يحصل على ارتفاع المستطيل. |
|
|  | [setHeight(double value)](#setHeight-double-) | يضبط ارتفاع المستطيل. |
|
|  | [getWidth()](#getWidth--) | يحصل على عرض المستطيل. |
|
|  | [setWidth(double value)](#setWidth-double-) | يضبط عرض المستطيل. |
|
|  | [getX()](#getX--) | يحصل على إحداثي x للزاوية العلوية اليسرى للمستطيل. |
|
|  | [setX(double value)](#setX-double-) | يضبط إحداثي x للزاوية العلوية اليسرى للمستطيل. |
|
|  | [getY()](#getY--) | يحصل على إحداثي y للزاوية العلوية اليسرى للمستطيل. |
|
|  | [setY(double value)](#setY-double-) | يضبط إحداثي y للزاوية العلوية اليسرى للمستطيل. |
|
|  | [equals(Object o)](#equals-java.lang.Object-) | {@inheritDoc} |
|
|  | [hashCode()](#hashCode--) | {@inheritDoc} |
|
|  | [toString()](#toString--) | {@inheritDoc} |
|
### Rectangle() {#Rectangle--}
```
public Rectangle()
```


يُهيئ نسخة جديدة من فئة Rectangle.


### Rectangle(Rectangle other) {#Rectangle-com.groupdocs.comparison.result.Rectangle-}
```
public Rectangle(Rectangle other)
```


ينشئ كائن Rectangle جديد يكون نسخة من المستطيل المحدد.

<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | other | [Rectangle](../../com.groupdocs.comparison.result/rectangle) | المستطيل المراد نسخه |
|

### Rectangle(double x, double y, double width, double height) {#Rectangle-double-double-double-double-}
```
public Rectangle(double x, double y, double width, double height)
```


ينشئ نسخة جديدة من فئة Rectangle باستخدام القيم المحددة لـ x و y والعرض والارتفاع.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | x | double | الإحداثي السيني للزاوية العليا اليسرى للمستطيل |
|
|  | y | double | الإحداثي الصادي للزاوية العليا اليسرى للمستطيل |
|
|  | العرض | double | عرض المستطيل |
|
|  | الارتفاع | double | ارتفاع المستطيل |
|

### getHeight() {#getHeight--}
```
public double getHeight()
```


يحصل على ارتفاع المستطيل.


**Returns:**
double - ارتفاع المستطيل

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


يضبط ارتفاع المستطيل.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | double | ارتفاع المستطيل |
|

### getWidth() {#getWidth--}
```
public double getWidth()
```


يحصل على عرض المستطيل.


**Returns:**
double - عرض المستطيل

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


يضبط عرض المستطيل.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | double | عرض المستطيل |
|

### getX() {#getX--}
```
public double getX()
```


يحصل على إحداثي x للزاوية العلوية اليسرى للمستطيل.


**Returns:**
double - الإحداثي السيني للزاوية العليا اليسرى للمستطيل

### setX(double value) {#setX-double-}
```
public void setX(double value)
```


يضبط إحداثي x للزاوية العلوية اليسرى للمستطيل.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | double | الإحداثي السيني للزاوية العليا اليسرى للمستطيل |
|

### getY() {#getY--}
```
public double getY()
```


يحصل على إحداثي y للزاوية العلوية اليسرى للمستطيل.


**Returns:**
double - الإحداثي الصادي للزاوية العليا اليسرى للمستطيل

### setY(double value) {#setY-double-}
```
public void setY(double value)
```


يضبط إحداثي y للزاوية العلوية اليسرى للمستطيل.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | double | الإحداثي الصادي للزاوية العليا اليسرى للمستطيل |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```




**Parameters:**
| معامل | نوع | الوصف |
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
