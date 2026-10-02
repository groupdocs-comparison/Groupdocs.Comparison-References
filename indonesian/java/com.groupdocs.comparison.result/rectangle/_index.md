---
title: "Rectangle"
second_title: "Referensi API GroupDocs.Comparison untuk Java"
description: "Kelas Rectangle mewakili area yang berubah pada sebuah dokumen."
type: docs
weight: 12
url: /id/java/com.groupdocs.comparison.result/rectangle/
---
**Inheritance:**
java.lang.Object
```
public final class Rectangle
```

Kelas Rectangle mewakili area yang berubah pada sebuah dokumen.


Contoh penggunaan:

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


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [Rectangle()](#Rectangle--) | Menginisialisasi instance baru dari kelas Rectangle. |
|
|  | [Rectangle(Rectangle other)](#Rectangle-com.groupdocs.comparison.result.Rectangle-) | Membuat objek Rectangle baru yang merupakan salinan dari persegi panjang yang ditentukan. |
|
|  | [Rectangle(double x, double y, double width, double height)](#Rectangle-double-double-double-double-) | Membuat instance baru dari kelas Rectangle dengan x, y, lebar, dan tinggi yang ditentukan. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getHeight()](#getHeight--) | Mendapatkan tinggi persegi panjang. |
|
|  | [setHeight(double value)](#setHeight-double-) | Mengatur tinggi persegi panjang. |
|
|  | [getWidth()](#getWidth--) | Mendapatkan lebar persegi panjang. |
|
|  | [setWidth(double value)](#setWidth-double-) | Mengatur lebar persegi panjang. |
|
|  | [getX()](#getX--) | Mendapatkan koordinat x dari sudut kiri atas persegi panjang. |
|
|  | [setX(double value)](#setX-double-) | Mengatur koordinat x dari sudut kiri atas persegi panjang. |
|
|  | [getY()](#getY--) | Mendapatkan koordinat y dari sudut kiri atas persegi panjang. |
|
|  | [setY(double value)](#setY-double-) | Mengatur koordinat y dari sudut kiri atas persegi panjang. |
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


Menginisialisasi instance baru dari kelas Rectangle.


### Rectangle(Rectangle other) {#Rectangle-com.groupdocs.comparison.result.Rectangle-}
```
public Rectangle(Rectangle other)
```


Membuat objek Rectangle baru yang merupakan salinan dari persegi panjang yang ditentukan.

<br />



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | other | [Rectangle](../../com.groupdocs.comparison.result/rectangle) | Persegi panjang yang akan disalin |
|

### Rectangle(double x, double y, double width, double height) {#Rectangle-double-double-double-double-}
```
public Rectangle(double x, double y, double width, double height)
```


Membuat instance baru dari kelas Rectangle dengan x, y, lebar, dan tinggi yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | x | double | Koordinat x dari sudut kiri atas persegi panjang |
|
|  | y | double | Koordinat y dari sudut kiri atas persegi panjang |
|
|  | lebar | double | Lebar persegi panjang |
|
|  | tinggi | double | Tinggi persegi panjang |
|

### getHeight() {#getHeight--}
```
public double getHeight()
```


Mendapatkan tinggi persegi panjang.


**Returns:**
double - tinggi persegi panjang

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Mengatur tinggi persegi panjang.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | double | Tinggi persegi panjang |
|

### getWidth() {#getWidth--}
```
public double getWidth()
```


Mendapatkan lebar persegi panjang.


**Returns:**
double - lebar persegi panjang

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Mengatur lebar persegi panjang.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | double | Lebar persegi panjang |
|

### getX() {#getX--}
```
public double getX()
```


Mendapatkan koordinat x dari sudut kiri atas persegi panjang.


**Returns:**
double - koordinat x dari sudut kiri atas persegi panjang

### setX(double value) {#setX-double-}
```
public void setX(double value)
```


Mengatur koordinat x dari sudut kiri atas persegi panjang.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | double | Koordinat x dari sudut kiri atas persegi panjang |
|

### getY() {#getY--}
```
public double getY()
```


Mendapatkan koordinat y dari sudut kiri atas persegi panjang.


**Returns:**
double - koordinat y dari sudut kiri atas persegi panjang

### setY(double value) {#setY-double-}
```
public void setY(double value)
```


Mengatur koordinat y dari sudut kiri atas persegi panjang.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | double | Koordinat y dari sudut kiri atas persegi panjang |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
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
