---
title: "Rectangle"
second_title: "GroupDocs.Comparison for Java Αναφορά API"
description: "Η κλάση Rectangle αντιπροσωπεύει την τροποποιημένη περιοχή σε ένα έγγραφο."
type: docs
weight: 12
url: /el/java/com.groupdocs.comparison.result/rectangle/
---
**Inheritance:**
java.lang.Object
```
public final class Rectangle
```

Η κλάση Rectangle αντιπροσωπεύει την τροποποιημένη περιοχή σε ένα έγγραφο.


Παράδειγμα χρήσης:

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


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [Rectangle()](#Rectangle--) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Rectangle. |
|
|  | [Rectangle(Rectangle other)](#Rectangle-com.groupdocs.comparison.result.Rectangle-) | Δημιουργεί ένα νέο αντικείμενο Rectangle που είναι αντίγραφο του καθορισμένου ορθογωνίου. |
|
|  | [Rectangle(double x, double y, double width, double height)](#Rectangle-double-double-double-double-) | Δημιουργεί ένα νέο αντικείμενο της κλάσης Rectangle με τις καθορισμένες τιμές x, y, πλάτος και ύψος. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getHeight()](#getHeight--) | Λαμβάνει το ύψος του ορθογωνίου. |
|
|  | [setHeight(double value)](#setHeight-double-) | Ορίζει το ύψος του ορθογωνίου. |
|
|  | [getWidth()](#getWidth--) | Λαμβάνει το πλάτος του ορθογωνίου. |
|
|  | [setWidth(double value)](#setWidth-double-) | Ορίζει το πλάτος του ορθογωνίου. |
|
|  | [getX()](#getX--) | Λαμβάνει τη συντεταγμένη x της επάνω αριστερής γωνίας του ορθογωνίου. |
|
|  | [setX(double value)](#setX-double-) | Ορίζει τη συντεταγμένη x της επάνω αριστερής γωνίας του ορθογωνίου. |
|
|  | [getY()](#getY--) | Λαμβάνει τη συντεταγμένη y της επάνω αριστερής γωνίας του ορθογωνίου. |
|
|  | [setY(double value)](#setY-double-) | Ορίζει τη συντεταγμένη y της επάνω αριστερής γωνίας του ορθογωνίου. |
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


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Rectangle.


### Rectangle(Rectangle other) {#Rectangle-com.groupdocs.comparison.result.Rectangle-}
```
public Rectangle(Rectangle other)
```


Δημιουργεί ένα νέο αντικείμενο Rectangle που είναι αντίγραφο του καθορισμένου ορθογωνίου.

<br />



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | other | [Rectangle](../../com.groupdocs.comparison.result/rectangle) | Το ορθογώνιο προς αντιγραφή |
|

### Rectangle(double x, double y, double width, double height) {#Rectangle-double-double-double-double-}
```
public Rectangle(double x, double y, double width, double height)
```


Δημιουργεί ένα νέο αντικείμενο της κλάσης Rectangle με τις καθορισμένες τιμές x, y, πλάτος και ύψος.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | x | double | Η συντεταγμένη x της επάνω αριστερής γωνίας του ορθογωνίου |
|
|  | y | double | Η συντεταγμένη y της επάνω αριστερής γωνίας του ορθογωνίου |
|
|  | width | double | Το πλάτος του ορθογωνίου |
|
|  | height | double | Το ύψος του ορθογωνίου |
|

### getHeight() {#getHeight--}
```
public double getHeight()
```


Λαμβάνει το ύψος του ορθογωνίου.


**Returns:**
double - το ύψος του ορθογωνίου

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Ορίζει το ύψος του ορθογωνίου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | double | Το ύψος του ορθογωνίου |
|

### getWidth() {#getWidth--}
```
public double getWidth()
```


Λαμβάνει το πλάτος του ορθογωνίου.


**Returns:**
double - το πλάτος του ορθογωνίου

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Ορίζει το πλάτος του ορθογωνίου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | double | Το πλάτος του ορθογωνίου |
|

### getX() {#getX--}
```
public double getX()
```


Λαμβάνει τη συντεταγμένη x της επάνω αριστερής γωνίας του ορθογωνίου.


**Returns:**
double - η συντεταγμένη x της επάνω αριστερής γωνίας του ορθογωνίου

### setX(double value) {#setX-double-}
```
public void setX(double value)
```


Ορίζει τη συντεταγμένη x της επάνω αριστερής γωνίας του ορθογωνίου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | double | Η συντεταγμένη x της επάνω αριστερής γωνίας του ορθογωνίου |
|

### getY() {#getY--}
```
public double getY()
```


Λαμβάνει τη συντεταγμένη y της επάνω αριστερής γωνίας του ορθογωνίου.


**Returns:**
double - η συντεταγμένη y της επάνω αριστερής γωνίας του ορθογωνίου

### setY(double value) {#setY-double-}
```
public void setY(double value)
```


Ορίζει τη συντεταγμένη y της επάνω αριστερής γωνίας του ορθογωνίου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | double | Η συντεταγμένη y της επάνω αριστερής γωνίας του ορθογωνίου |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
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
