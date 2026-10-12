---
title: "ComparisonAction"
second_title: "GroupDocs.Comparison for Java Αναφορά API"
description: "Η απαρίθμηση ComparisonAction αντιπροσωπεύει τις ενέργειες που μπορούν να εφαρμοστούν σε μια αλλαγή κατά τη διαδικασία σύγκρισης εγγράφων."
type: docs
weight: 15
url: /el/java/com.groupdocs.comparison.result/comparisonaction/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ComparisonAction extends Enum<ComparisonAction>
```

Η απαρίθμηση ComparisonAction αντιπροσωπεύει τις ενέργειες που μπορούν να εφαρμοστούν σε μια αλλαγή κατά τη διαδικασία σύγκρισης εγγράφων.


Κάθε σταθερά σε αυτό το enum αντιπροσωπεύει μια συγκεκριμένη ενέργεια και παρέχει μια ανθρώπινα αναγνώσιμη περιγραφή και μια αριθμητική τιμή.


Παράδειγμα χρήσης:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);
     comparer.compare();

     final ChangeInfo[] changes = comparer.getChanges();
     for (ChangeInfo changeInfo : changes) {
         if (changeInfo.getId() % 2 == 0) {
             changeInfo.setComparisonAction(ComparisonAction.REJECT);
         }
     }
     comparer.applyChanges(resultFile, changes);
 }
 
````


## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [NONE](#NONE) | Αντιπροσωπεύει καμία ενέργεια. |
|
|  | [ACCEPT](#ACCEPT) | Αντιπροσωπεύει μια ενέργεια αποδοχής. |
|
|  | [REJECT](#REJECT) | Αντιπροσωπεύει μια ενέργεια απόρριψης. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Αναλύει την αναπαράσταση συμβολοσειράς του ComparisonAction για να λάβει τη σταθερά του enum. |
|
|  | [fromInt(int intValue)](#fromInt-int-) | Δημιουργεί νέα σταθερά του enum ComparisonAction χρησιμοποιώντας την παρεχόμενη αριθμητική τιμή. |
|
|  | [toString()](#toString--) | Αναπαράσταση συμβολοσειράς του ComparisonAction. |
|
|  | [toInt()](#toInt--) | Αριθμητική αναπαράσταση του ComparisonAction. |
|
### NONE {#NONE}
```
public static final ComparisonAction NONE
```


Αντιπροσωπεύει καμία ενέργεια. Η αλλαγή δεν θα έχει καμία επίδραση.


### ACCEPT {#ACCEPT}
```
public static final ComparisonAction ACCEPT
```


Αντιπροσωπεύει μια ενέργεια αποδοχής. Η αλλαγή θα είναι ορατή στο αρχείο αποτελεσμάτων.


### REJECT {#REJECT}
```
public static final ComparisonAction REJECT
```


Αντιπροσωπεύει μια ενέργεια απόρριψης. Η αλλαγή θα είναι αόρατη στο αρχείο αποτελεσμάτων.


### values() {#values--}
```
public static ComparisonAction[] values()
```




**Returns:**
com.groupdocs.comparison.result.ComparisonAction[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static ComparisonAction valueOf(String name)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| όνομα | java.lang.String |  |

**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static ComparisonAction fromString(String toStringValue)
```


Αναλύει την αναπαράσταση συμβολοσειράς του ComparisonAction για να λάβει τη σταθερά του enum.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | toStringValue | java.lang.String | Η αναπαράσταση συμβολοσειράς του ComparisonAction |
|

**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) - ComparisonAction enum constant associated with input string

### fromInt(int intValue) {#fromInt-int-}
```
public static ComparisonAction fromInt(int intValue)
```


Δημιουργεί νέα σταθερά του enum ComparisonAction χρησιμοποιώντας την παρεχόμενη αριθμητική τιμή.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | intValue | int | Η αριθμητική αναπαράσταση του ComparisonAction |
|

**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) - ComparisonAction enum constant associated with numeric value

### toString() {#toString--}
```
public String toString()
```


Αναπαράσταση συμβολοσειράς του ComparisonAction.


**Returns:**
java.lang.String - τιμή συμβολοσειράς του σταθερού της enum

### toInt() {#toInt--}
```
public int toInt()
```


Αριθμητική αναπαράσταση του ComparisonAction.


**Returns:**
int - αριθμητική τιμή του σταθερού της enum

