---
title: "PageInfo"
second_title: "GroupDocs.Comparison for Java Αναφορά API"
description: "Η κλάση PageInfo αντιπροσωπεύει πληροφορίες σχετικά με μια συγκεκριμένη σελίδα σε ένα έγγραφο."
type: docs
weight: 11
url: /el/java/com.groupdocs.comparison.result/pageinfo/
---
**Inheritance:**
java.lang.Object
```
public class PageInfo
```

Η κλάση PageInfo αντιπροσωπεύει πληροφορίες σχετικά με μια συγκεκριμένη σελίδα σε ένα έγγραφο.


Παρέχει λεπτομέρειες όπως ο αριθμός σελίδας, το πλάτος, το ύψος και άλλες σχετικές ιδιότητες.
Χρησιμοποιήστε αυτήν την κλάση για να ανακτήσετε πληροφορίες σχετικά με μεμονωμένες σελίδες σε ένα έγγραφο κατά τη διαδικασία σύγκρισης.


Παράδειγμα χρήσης:

````

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
 
````


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [PageInfo(int pageNumber, int width, int height)](#PageInfo-int-int-int-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης PageInfo με ρύθμιση του pageNumber, του πλάτους και του ύψους. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getWidth()](#getWidth--) | Ανακτά το πλάτος της σελίδας |
|
|  | [setWidth(int value)](#setWidth-int-) | Ορίζει το πλάτος της σελίδας |
|
|  | [getHeight()](#getHeight--) | Ανακτά το ύψος της σελίδας |
|
|  | [setHeight(int value)](#setHeight-int-) | Ορίζει το ύψος της σελίδας |
|
|  | [getPageNumber()](#getPageNumber--) | Ανακτά τον αριθμό της σελίδας |
|
|  | [setPageNumber(int value)](#setPageNumber-int-) | Ορίζει τον αριθμό της σελίδας |
|
| [toString()](#toString--) |  |
### PageInfo(int pageNumber, int width, int height) {#PageInfo-int-int-int-}
```
public PageInfo(int pageNumber, int width, int height)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης PageInfo με ρύθμιση του pageNumber, του πλάτους και του ύψους.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | pageNumber | int | Ο αριθμός της σελίδας |
|
|  | width | int | Το πλάτος της σελίδας |
|
|  | height | int | Το ύψος της σελίδας |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Ανακτά το πλάτος της σελίδας


**Returns:**
int - το πλάτος της σελίδας

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Ορίζει το πλάτος της σελίδας


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | int | Το πλάτος της σελίδας |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Ανακτά το ύψος της σελίδας


**Returns:**
int - το ύψος της σελίδας

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Ορίζει το ύψος της σελίδας


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | int | Το ύψος της σελίδας |
|

### getPageNumber() {#getPageNumber--}
```
public final int getPageNumber()
```


Ανακτά τον αριθμό της σελίδας


**Returns:**
int - ο αριθμός της σελίδας

### setPageNumber(int value) {#setPageNumber-int-}
```
public final void setPageNumber(int value)
```


Ορίζει τον αριθμό της σελίδας


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | int | Ο αριθμός της σελίδας |
|

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
