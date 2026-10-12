---
title: "ChangeType"
second_title: "GroupDocs.Comparison for Java Αναφορά API"
description: "Η απαρίθμηση ChangeType αντιπροσωπεύει τους τύπους αλλαγών που μπορούν να συμβούν κατά τη διαδικασία σύγκρισης εγγράφων."
type: docs
weight: 14
url: /el/java/com.groupdocs.comparison.result/changetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ChangeType extends Enum<ChangeType>
```

Η απαρίθμηση ChangeType αντιπροσωπεύει τους τύπους αλλαγών που μπορούν να συμβούν κατά τη διαδικασία σύγκρισης εγγράφων.


Κάθε σταθερά σε αυτό το enum αντιπροσωπεύει έναν συγκεκριμένο τύπο αλλαγής και παρέχει μια ανθρώπινα αναγνώσιμη περιγραφή και μια αριθμητική τιμή.


Παράδειγμα χρήσης:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);
     comparer.compare();
     final ChangeInfo[] changes = comparer.getChanges();
     for (ChangeInfo changeInfo : changes) {
         // Get the ChangeType for a specific change
         final ChangeType changeType = changeInfo.getType();
         // Print the ChangeType information
         System.out.println("Description: " + changeType.toString());
         System.out.println("Value: " + changeType.toInt());
     }
 }
 
````


## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [NONE](#NONE) | Αντιπροσωπεύει καμία αλλαγή. |
|
|  | [MODIFIED](#MODIFIED) | Αντιπροσωπεύει μια τροποποιημένη αλλαγή. |
|
|  | [INSERTED](#INSERTED) | Αντιπροσωπεύει μια εισαχθείσα αλλαγή. |
|
|  | [DELETED](#DELETED) | Αντιπροσωπεύει μια διαγραμμένη αλλαγή. |
|
|  | [ADDED](#ADDED) | Αντιπροσωπεύει μια προστιθέμενη αλλαγή. |
|
|  | [NOT_MODIFIED](#NOT-MODIFIED) | Αντιπροσωπεύει μια αμετάβλητη αλλαγή. |
|
|  | [STYLE_CHANGED](#STYLE-CHANGED) | Αντιπροσωπεύει μια αλλαγή στυλ. |
|
|  | [RESIZED](#RESIZED) | Αντιπροσωπεύει μια αλλαγή με αλλαγή μεγέθους. |
|
|  | [MOVED](#MOVED) | Αντιπροσωπεύει μια μετακινημένη αλλαγή. |
|
|  | [MOVED_AND_RESIZED](#MOVED-AND-RESIZED) | Αντιπροσωπεύει μια μετακινημένη και με αλλαγή μεγέθους αλλαγή. |
|
|  | [SHIFTED_AND_RESIZED](#SHIFTED-AND-RESIZED) | Αντιπροσωπεύει μια μετατοπισμένη και με αλλαγή μεγέθους αλλαγή. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Αναλύει την αναπαράσταση σε συμβολοσειρά του ChangeType για να λάβει τη σταθερά enum. |
|
|  | [fromInt(int intValue)](#fromInt-int-) | Δημιουργεί νέα σταθερά του enum ChangeType χρησιμοποιώντας την παρεχόμενη αριθμητική τιμή. |
|
|  | [toString()](#toString--) | Αναπαράσταση σε συμβολοσειρά του ChangeType. |
|
|  | [toInt()](#toInt--) | Αριθμητική αναπαράσταση του ChangeType. |
|
### NONE {#NONE}
```
public static final ChangeType NONE
```


Αντιπροσωπεύει καμία αλλαγή.


### MODIFIED {#MODIFIED}
```
public static final ChangeType MODIFIED
```


Αντιπροσωπεύει μια τροποποιημένη αλλαγή.


### INSERTED {#INSERTED}
```
public static final ChangeType INSERTED
```


Αντιπροσωπεύει μια εισαχθείσα αλλαγή.


### DELETED {#DELETED}
```
public static final ChangeType DELETED
```


Αντιπροσωπεύει μια διαγραμμένη αλλαγή.


### ADDED {#ADDED}
```
public static final ChangeType ADDED
```


Αντιπροσωπεύει μια προστιθέμενη αλλαγή.


### NOT_MODIFIED {#NOT-MODIFIED}
```
public static final ChangeType NOT_MODIFIED
```


Αντιπροσωπεύει μια αμετάβλητη αλλαγή.


### STYLE_CHANGED {#STYLE-CHANGED}
```
public static final ChangeType STYLE_CHANGED
```


Αντιπροσωπεύει μια αλλαγή στυλ.


### RESIZED {#RESIZED}
```
public static final ChangeType RESIZED
```


Αντιπροσωπεύει μια αλλαγή με αλλαγή μεγέθους.


### MOVED {#MOVED}
```
public static final ChangeType MOVED
```


Αντιπροσωπεύει μια μετακινημένη αλλαγή.


### MOVED_AND_RESIZED {#MOVED-AND-RESIZED}
```
public static final ChangeType MOVED_AND_RESIZED
```


Αντιπροσωπεύει μια μετακινημένη και με αλλαγή μεγέθους αλλαγή.


### SHIFTED_AND_RESIZED {#SHIFTED-AND-RESIZED}
```
public static final ChangeType SHIFTED_AND_RESIZED
```


Αντιπροσωπεύει μια μετατοπισμένη και με αλλαγή μεγέθους αλλαγή.


### values() {#values--}
```
public static ChangeType[] values()
```




**Returns:**
com.groupdocs.comparison.result.ChangeType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static ChangeType valueOf(String name)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| όνομα | java.lang.String |  |

**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static ChangeType fromString(String toStringValue)
```


Αναλύει την αναπαράσταση σε συμβολοσειρά του ChangeType για να λάβει τη σταθερά enum.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | toStringValue | java.lang.String | Η αναπαράσταση σε συμβολοσειρά του ChangeType |
|

**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - ChangeType enum constant associated with input string

### fromInt(int intValue) {#fromInt-int-}
```
public static ChangeType fromInt(int intValue)
```


Δημιουργεί νέα σταθερά του enum ChangeType χρησιμοποιώντας την παρεχόμενη αριθμητική τιμή.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | intValue | int | Η αριθμητική αναπαράσταση του ChangeType |
|

**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - ChangeType enum constant associated with numeric value

### toString() {#toString--}
```
public String toString()
```


Αναπαράσταση σε συμβολοσειρά του ChangeType.


**Returns:**
java.lang.String - τιμή συμβολοσειράς του σταθερού της enum

### toInt() {#toInt--}
```
public int toInt()
```


Αριθμητική αναπαράσταση του ChangeType.


**Returns:**
int - αριθμητική τιμή του σταθερού της enum

