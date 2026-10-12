---
title: "ApplyChangeOptions"
second_title: "GroupDocs.Comparison for Java Αναφορά API"
description: "Επιτρέπει την ενημέρωση της λίστας αλλαγών πριν την εφαρμογή τους στο τελικό έγγραφο."
type: docs
weight: 10
url: /el/java/com.groupdocs.comparison.options/applychangeoptions/
---
**Inheritance:**
java.lang.Object
```
public class ApplyChangeOptions
```

Επιτρέπει την ενημέρωση της λίστας αλλαγών πριν την εφαρμογή τους στο τελικό έγγραφο.


Παράδειγμα χρήσης:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);
     comparer.compare();
     ChangeInfo[] changes = comparer.getChanges();
     changes[0].setComparisonAction(ComparisonAction.REJECT);

     final ApplyChangeOptions applyChangeOptions = new ApplyChangeOptions(changes);

     comparer.applyChanges(resultFile, applyChangeOptions);
 }
 
````


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [ApplyChangeOptions()](#ApplyChangeOptions--) | Αρχικοποιεί μια νέα παρουσία της κλάσης ApplyChangeOptions. |
|
|  | [ApplyChangeOptions(List<ChangeInfo> changes)](#ApplyChangeOptions-java.util.List-com.groupdocs.comparison.result.ChangeInfo--) | Αρχικοποιεί μια νέα παρουσία της κλάσης ApplyChangeOptions με λίστα αλλαγών. |
|
|  | [ApplyChangeOptions(ChangeInfo[] changes)](#ApplyChangeOptions-com.groupdocs.comparison.result.ChangeInfo---) | Αρχικοποιεί μια νέα παρουσία της κλάσης ApplyChangeOptions με πίνακα αλλαγών. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getChanges()](#getChanges--) | Λαμβάνει έναν πίνακα αλλαγών που πρέπει να εφαρμοστούν στο τελικό έγγραφο. |
|
|  | [setChanges(ChangeInfo[] value)](#setChanges-com.groupdocs.comparison.result.ChangeInfo---) | Ορίζει έναν πίνακα αλλαγών που πρέπει να εφαρμοστούν στο τελικό έγγραφο. |
|
|  | [setChanges(List<ChangeInfo> value)](#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--) | Ορίζει μια λίστα αλλαγών που πρέπει να εφαρμοστούν στο τελικό έγγραφο. |
|
|  | [isSaveOriginalState()](#isSaveOriginalState--) | Λαμβάνει μια σημαία που καθορίζει αν η αρχική κατάσταση πρέπει να αποθηκευτεί. |
|
|  | [setSaveOriginalState(boolean saveOriginalState)](#setSaveOriginalState-boolean-) | Ορίζει μια σημαία που καθορίζει αν η αρχική κατάσταση πρέπει να αποθηκευτεί. |
|
### ApplyChangeOptions() {#ApplyChangeOptions--}
```
public ApplyChangeOptions()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης ApplyChangeOptions.


### ApplyChangeOptions(List<ChangeInfo> changes) {#ApplyChangeOptions-java.util.List-com.groupdocs.comparison.result.ChangeInfo--}
```
public ApplyChangeOptions(List<ChangeInfo> changes)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης ApplyChangeOptions με λίστα αλλαγών.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | αλλαγές | java.util.List<com.groupdocs.comparison.result.ChangeInfo> | Η λίστα των αλλαγών που θα εφαρμοστούν |
|

### ApplyChangeOptions(ChangeInfo[] changes) {#ApplyChangeOptions-com.groupdocs.comparison.result.ChangeInfo---}
```
public ApplyChangeOptions(ChangeInfo[] changes)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης ApplyChangeOptions με πίνακα αλλαγών.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | changes | [ChangeInfo\[\]](../../com.groupdocs.comparison.result/changeinfo) | Η λίστα των αλλαγών που θα εφαρμοστούν |
|

### getChanges() {#getChanges--}
```
public final ChangeInfo[] getChanges()
```


Λαμβάνει έναν πίνακα αλλαγών που πρέπει να εφαρμοστούν στο τελικό έγγραφο.


**Returns:**
com.groupdocs.comparison.result.ChangeInfo[] - ο πίνακας των αλλαγών που θα εφαρμοστούν

### setChanges(ChangeInfo[] value) {#setChanges-com.groupdocs.comparison.result.ChangeInfo---}
```
public final void setChanges(ChangeInfo[] value)
```


Ορίζει έναν πίνακα αλλαγών που πρέπει να εφαρμοστούν στο τελικό έγγραφο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [ChangeInfo\[\]](../../com.groupdocs.comparison.result/changeinfo) | Ο πίνακας των αλλαγών που θα εφαρμοστούν |
|

### setChanges(List<ChangeInfo> value) {#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--}
```
public final void setChanges(List<ChangeInfo> value)
```


Ορίζει μια λίστα αλλαγών που πρέπει να εφαρμοστούν στο τελικό έγγραφο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | java.util.List<com.groupdocs.comparison.result.ChangeInfo> | Η λίστα των αλλαγών που θα εφαρμοστούν |
|

### isSaveOriginalState() {#isSaveOriginalState--}
```
public boolean isSaveOriginalState()
```


Λαμβάνει μια σημαία που καθορίζει αν η αρχική κατάσταση πρέπει να αποθηκευτεί. Προεπιλεγμένη τιμή: false.


**Returns:**
boolean - true αν η αρχική κατάσταση πρέπει να αποθηκευτεί, αλλιώς false

### setSaveOriginalState(boolean saveOriginalState) {#setSaveOriginalState-boolean-}
```
public void setSaveOriginalState(boolean saveOriginalState)
```


Ορίζει μια σημαία που καθορίζει αν η αρχική κατάσταση πρέπει να αποθηκευτεί.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | saveOriginalState | boolean | True αν η αρχική κατάσταση πρέπει να αποθηκευτεί, αλλιώς false |
|

