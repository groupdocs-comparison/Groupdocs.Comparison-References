---
title: "StyleChangeInfo"
second_title: "GroupDocs.Comparison for Java Αναφορά API"
description: "Η κλάση StyleChangeInfo αντιπροσωπεύει πληροφορίες σχετικά με μια αλλαγή στυλ σε ένα συγκριόμενο έγγραφο."
type: docs
weight: 13
url: /el/java/com.groupdocs.comparison.result/stylechangeinfo/
---
**Inheritance:**
java.lang.Object
```
public class StyleChangeInfo
```

Η κλάση StyleChangeInfo αντιπροσωπεύει πληροφορίες σχετικά με μια αλλαγή στυλ σε ένα συγκριόμενο έγγραφο.


Παρέχει λεπτομέρειες όπως το όνομα της τροποποιημένης ιδιότητας, τις τιμές πριν και μετά την αλλαγή, κ.λπ.
Χρησιμοποιήστε αυτή την κλάση για να ανακτήσετε πληροφορίες σχετικά με τις αλλαγές στυλ κατά τη διαδικασία σύγκρισης εγγράφων.


Παράδειγμα χρήσης:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     comparer.compare();
     final ChangeInfo[] changes = comparer.getChanges();
     for (ChangeInfo change : changes) {
         // Access the style change information
         final List styleChanges = change.getStyleChanges();
         for (StyleChangeInfo styleChange : styleChanges) {
             // Print the style change information
             System.out.println("PropertyName: " + styleChange.getPropertyName());
             System.out.println("OldValue: " + styleChange.getOldValue());
             System.out.println("NewValue: " + styleChange.getNewValue());
         }
     }
 }
 
````


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [StyleChangeInfo()](#StyleChangeInfo--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getPropertyName()](#getPropertyName--) | Λαμβάνει το όνομα της ιδιότητας που τροποποιήθηκε. |
|
|  | [setPropertyName(String value)](#setPropertyName-java.lang.String-) | Ορίζει το όνομα της ιδιότητας που τροποποιήθηκε. |
|
|  | [getNewValue()](#getNewValue--) | Λαμβάνει τη νέα τιμή της ιδιότητας. |
|
|  | [setNewValue(Object value)](#setNewValue-java.lang.Object-) | Ορίζει τη νέα τιμή της ιδιότητας. |
|
|  | [getOldValue()](#getOldValue--) | Λαμβάνει την παλιά τιμή της ιδιότητας. |
|
|  | [setOldValue(Object value)](#setOldValue-java.lang.Object-) | Ορίζει την παλιά τιμή της ιδιότητας. |
|
|  | [equals(Object o)](#equals-java.lang.Object-) | {@inheritDoc} |
|
|  | [hashCode()](#hashCode--) | {@inheritDoc} |
|
### StyleChangeInfo() {#StyleChangeInfo--}
```
public StyleChangeInfo()
```


### getPropertyName() {#getPropertyName--}
```
public final String getPropertyName()
```


Λαμβάνει το όνομα της ιδιότητας που τροποποιήθηκε.


**Returns:**
java.lang.String - το όνομα της ιδιότητας

### setPropertyName(String value) {#setPropertyName-java.lang.String-}
```
public final void setPropertyName(String value)
```


Ορίζει το όνομα της ιδιότητας που τροποποιήθηκε.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | java.lang.String | Το όνομα της ιδιότητας |
|

### getNewValue() {#getNewValue--}
```
public final Object getNewValue()
```


Λαμβάνει τη νέα τιμή της ιδιότητας.


**Returns:**
java.lang.Object - η νέα τιμή της ιδιότητας

### setNewValue(Object value) {#setNewValue-java.lang.Object-}
```
public final void setNewValue(Object value)
```


Ορίζει τη νέα τιμή της ιδιότητας.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | java.lang.Object | Η νέα τιμή της ιδιότητας |
|

### getOldValue() {#getOldValue--}
```
public final Object getOldValue()
```


Λαμβάνει την παλιά τιμή της ιδιότητας.


**Returns:**
java.lang.Object - η παλιά τιμή της ιδιότητας

### setOldValue(Object value) {#setOldValue-java.lang.Object-}
```
public final void setOldValue(Object value)
```


Ορίζει την παλιά τιμή της ιδιότητας.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | java.lang.Object | Η παλιά τιμή της ιδιότητας |
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
