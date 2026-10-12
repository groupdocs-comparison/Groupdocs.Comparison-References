---
title: "RevisionType"
second_title: "GroupDocs.Comparison for Java Αναφορά API"
description: "Αντιπροσωπεύει τους τύπους των αναθεωρήσεων σε ένα έγγραφο."
type: docs
weight: 14
url: /el/java/com.groupdocs.comparison.words.revision/revisiontype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum RevisionType extends Enum<RevisionType>
```

Αντιπροσωπεύει τους τύπους των αναθεωρήσεων σε ένα έγγραφο.


Παράδειγμα χρήσης:

````

 try (RevisionHandler revisionHandler = new RevisionHandler(sourceFile)) {
     List revisionList = revisionHandler.getRevisions();

     for (RevisionInfo revisionInfo : revisionList) {
         if (revisionInfo.getType() == RevisionType.DELETION)
             // Set an action to be applied to the revision
             revisionInfo.setAction(RevisionAction.Accept);
     }
     // Create an instance of ApplyRevisionOptions
     ApplyRevisionOptions revisionChanges = new ApplyRevisionOptions();
     revisionChanges.setChanges(revisionList);
     // Apply the revisions using the options
     revisionHandler.applyRevisionChanges(resultFile, revisionChanges);
 }
 
````


## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [INSERTION](#INSERTION) | Αντιπροσωπεύει έναν τύπο όταν νέο περιεχόμενο εισήχθη στο έγγραφο. |
|
|  | [DELETION](#DELETION) | Αντιπροσωπεύει έναν τύπο όταν περιεχόμενο αφαιρέθηκε από το έγγραφο. |
|
|  | [FORMAT_CHANGE](#FORMAT-CHANGE) | Αντιπροσωπεύει έναν τύπο όταν εφαρμοστέα αλλαγή μορφοποίησης στον γονικό κόμβο. |
|
|  | [STYLE_DEFINITION_CHANGE](#STYLE-DEFINITION-CHANGE) | Αντιπροσωπεύει έναν τύπο όταν εφαρμοστέα αλλαγή μορφοποίησης στο γονικό στυλ. |
|
|  | [MOVING](#MOVING) | Αντιπροσωπεύει έναν τύπο όταν περιεχόμενο μετακινήθηκε στο έγγραφο. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromInt(int toIntValue)](#fromInt-int-) | Δημιουργεί νέο σταθερό της enum RevisionType χρησιμοποιώντας την παρεχόμενη αριθμητική τιμή. |
|
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Αναλύει την αναπαράσταση συμβολοσειράς της enum RevisionType για να πάρει το σταθερό της enum. |
|
|  | [toInt()](#toInt--) | Αριθμητική αναπαράσταση της enum RevisionType. |
|
|  | [toString()](#toString--) | Αναπαράσταση συμβολοσειράς της enum RevisionType. |
|
### INSERTION {#INSERTION}
```
public static final RevisionType INSERTION
```


Αντιπροσωπεύει έναν τύπο όταν νέο περιεχόμενο εισήχθη στο έγγραφο.


### DELETION {#DELETION}
```
public static final RevisionType DELETION
```


Αντιπροσωπεύει έναν τύπο όταν περιεχόμενο αφαιρέθηκε από το έγγραφο.


### FORMAT_CHANGE {#FORMAT-CHANGE}
```
public static final RevisionType FORMAT_CHANGE
```


Αντιπροσωπεύει έναν τύπο όταν εφαρμοστέα αλλαγή μορφοποίησης στον γονικό κόμβο.


### STYLE_DEFINITION_CHANGE {#STYLE-DEFINITION-CHANGE}
```
public static final RevisionType STYLE_DEFINITION_CHANGE
```


Αντιπροσωπεύει έναν τύπο όταν εφαρμοστέα αλλαγή μορφοποίησης στο γονικό στυλ.


### MOVING {#MOVING}
```
public static final RevisionType MOVING
```


Αντιπροσωπεύει έναν τύπο όταν περιεχόμενο μετακινήθηκε στο έγγραφο.


### values() {#values--}
```
public static RevisionType[] values()
```




**Returns:**
com.groupdocs.comparison.words.revision.RevisionType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static RevisionType valueOf(String name)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| όνομα | java.lang.String |  |

**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype)
### fromInt(int toIntValue) {#fromInt-int-}
```
public static RevisionType fromInt(int toIntValue)
```


Δημιουργεί νέο σταθερό της enum RevisionType χρησιμοποιώντας την παρεχόμενη αριθμητική τιμή.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | toIntValue | int | Η αριθμητική αναπαράσταση της enum RevisionType |
|

**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) - RevisionType enum constant associated with numeric value

### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static RevisionType fromString(String toStringValue)
```


Αναλύει την αναπαράσταση συμβολοσειράς της enum RevisionType για να πάρει το σταθερό της enum.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | toStringValue | java.lang.String | Η αναπαράσταση συμβολοσειράς της enum RevisionType |
|

**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) - RevisionType enum constant associated with input string

### toInt() {#toInt--}
```
public int toInt()
```


Αριθμητική αναπαράσταση της enum RevisionType.


**Returns:**
int - αριθμητική τιμή του σταθερού της enum

### toString() {#toString--}
```
public String toString()
```


Αναπαράσταση συμβολοσειράς της enum RevisionType.


**Returns:**
java.lang.String - τιμή συμβολοσειράς του σταθερού της enum

