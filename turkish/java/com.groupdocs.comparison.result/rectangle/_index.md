---
title: "Rectangle"
second_title: "GroupDocs.Comparison for Java API Referansı"
description: "Rectangle sınıfı, bir belgede değiştirilen alanı temsil eder."
type: docs
weight: 12
url: /tr/java/com.groupdocs.comparison.result/rectangle/
---
**Inheritance:**
java.lang.Object
```
public final class Rectangle
```

Rectangle sınıfı, bir belgede değiştirilen alanı temsil eder.


Örnek kullanım:

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


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [Rectangle()](#Rectangle--) | Rectangle sınıfının yeni bir örneğini başlatır. |
|
|  | [Rectangle(Rectangle other)](#Rectangle-com.groupdocs.comparison.result.Rectangle-) | Belirtilen dikdörtgenin bir kopyası olan yeni bir Rectangle nesnesi oluşturur. |
|
|  | [Rectangle(double x, double y, double width, double height)](#Rectangle-double-double-double-double-) | Belirtilen x, y, genişlik ve yükseklik değerleriyle Rectangle sınıfının yeni bir örneğini oluşturur. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getHeight()](#getHeight--) | Rectangle nesnesinin yüksekliğini alır. |
|
|  | [setHeight(double value)](#setHeight-double-) | Rectangle nesnesinin yüksekliğini ayarlar. |
|
|  | [getWidth()](#getWidth--) | Rectangle nesnesinin genişliğini alır. |
|
|  | [setWidth(double value)](#setWidth-double-) | Rectangle nesnesinin genişliğini ayarlar. |
|
|  | [getX()](#getX--) | Rectangle nesnesinin sol üst köşesinin x koordinatını alır. |
|
|  | [setX(double value)](#setX-double-) | Rectangle nesnesinin sol üst köşesinin x koordinatını ayarlar. |
|
|  | [getY()](#getY--) | Rectangle nesnesinin sol üst köşesinin y koordinatını alır. |
|
|  | [setY(double value)](#setY-double-) | Rectangle nesnesinin sol üst köşesinin y koordinatını ayarlar. |
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


Rectangle sınıfının yeni bir örneğini başlatır.


### Rectangle(Rectangle other) {#Rectangle-com.groupdocs.comparison.result.Rectangle-}
```
public Rectangle(Rectangle other)
```


Belirtilen dikdörtgenin bir kopyası olan yeni bir Rectangle nesnesi oluşturur.

<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | other | [Rectangle](../../com.groupdocs.comparison.result/rectangle) | Kopyalanacak Rectangle |
|

### Rectangle(double x, double y, double width, double height) {#Rectangle-double-double-double-double-}
```
public Rectangle(double x, double y, double width, double height)
```


Belirtilen x, y, genişlik ve yükseklik değerleriyle Rectangle sınıfının yeni bir örneğini oluşturur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | x | double | Rectangle nesnesinin sol üst köşesinin x koordinatı |
|
|  | y | double | Rectangle nesnesinin sol üst köşesinin y koordinatı |
|
|  | genişlik | double | Rectangle nesnesinin genişliği |
|
|  | yükseklik | double | Rectangle nesnesinin yüksekliği |
|

### getHeight() {#getHeight--}
```
public double getHeight()
```


Rectangle nesnesinin yüksekliğini alır.


**Returns:**
double - Rectangle nesnesinin yüksekliği

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Rectangle nesnesinin yüksekliğini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | double | Rectangle nesnesinin yüksekliği |
|

### getWidth() {#getWidth--}
```
public double getWidth()
```


Rectangle nesnesinin genişliğini alır.


**Returns:**
double - Rectangle nesnesinin genişliği

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Rectangle nesnesinin genişliğini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | double | Rectangle nesnesinin genişliği |
|

### getX() {#getX--}
```
public double getX()
```


Rectangle nesnesinin sol üst köşesinin x koordinatını alır.


**Returns:**
double - Rectangle nesnesinin sol üst köşesinin x koordinatı

### setX(double value) {#setX-double-}
```
public void setX(double value)
```


Rectangle nesnesinin sol üst köşesinin x koordinatını ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | double | Rectangle nesnesinin sol üst köşesinin x koordinatı |
|

### getY() {#getY--}
```
public double getY()
```


Rectangle nesnesinin sol üst köşesinin y koordinatını alır.


**Returns:**
double - dikdörtgenin sol üst köşesinin y koordinatı

### setY(double value) {#setY-double-}
```
public void setY(double value)
```


Rectangle nesnesinin sol üst köşesinin y koordinatını ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | double | Rectangle nesnesinin sol üst köşesinin y koordinatı |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```




**Parameters:**
| Parametre | Tür | Açıklama |
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
