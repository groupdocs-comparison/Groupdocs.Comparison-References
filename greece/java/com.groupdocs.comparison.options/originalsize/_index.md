---
title: "OriginalSize"
second_title: "GroupDocs.Comparison for Java Αναφορά API"
description: "Αντιπροσωπεύει το αρχικό μέγεθος ενός εγγράφου σε ένα αποτέλεσμα σύγκρισης."
type: docs
weight: 14
url: /el/java/com.groupdocs.comparison.options/originalsize/
---
**Inheritance:**
java.lang.Object
```
public class OriginalSize
```

Αντιπροσωπεύει το αρχικό μέγεθος ενός εγγράφου σε ένα αποτέλεσμα σύγκρισης.


Το αρχικό μέγεθος περιλαμβάνει τις διαστάσεις (πλάτος και ύψος) των σελίδων του εγγράφου.


Παράδειγμα χρήσης:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     CompareOptions compareOptions = new CompareOptions();
     final OriginalSize originalSize = compareOptions.getOriginalSize();
     originalSize.setWidth(480);
     originalSize.setHeight(640);

     comparer.compare(resultFile, compareOptions);
 }
 
````


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [OriginalSize()](#OriginalSize--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getWidth()](#getWidth--) | Λαμβάνει το πλάτος των σελίδων του εγγράφου. |
|
|  | [setWidth(int value)](#setWidth-int-) | Ορίζει το πλάτος των σελίδων του εγγράφου. |
|
|  | [getHeight()](#getHeight--) | Λαμβάνει το ύψος των σελίδων του εγγράφου. |
|
|  | [setHeight(int value)](#setHeight-int-) | Ορίζει το ύψος των σελίδων του εγγράφου. |
|
### OriginalSize() {#OriginalSize--}
```
public OriginalSize()
```


### getWidth() {#getWidth--}
```
public final int getWidth()
```


Λαμβάνει το πλάτος των σελίδων του εγγράφου.


**Returns:**
int - το πλάτος των σελίδων του εγγράφου.

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Ορίζει το πλάτος των σελίδων του εγγράφου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | int | Το πλάτος των σελίδων του εγγράφου. |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Λαμβάνει το ύψος των σελίδων του εγγράφου.


**Returns:**
int - το ύψος των σελίδων του εγγράφου.

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Ορίζει το ύψος των σελίδων του εγγράφου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | int | Το ύψος των σελίδων του εγγράφου. |
|

