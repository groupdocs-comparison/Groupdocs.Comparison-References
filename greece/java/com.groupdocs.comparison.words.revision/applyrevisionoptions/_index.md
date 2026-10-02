---
title: "ApplyRevisionOptions"
second_title: "GroupDocs.Comparison for Java Αναφορά API"
description: "Η κλάση ApplyRevisionOptions σας επιτρέπει να ενημερώσετε την κατάσταση των αναθεωρήσεων πριν εφαρμοστούν στο τελικό έγγραφο."
type: docs
weight: 10
url: /el/java/com.groupdocs.comparison.words.revision/applyrevisionoptions/
---
**Inheritance:**
java.lang.Object
```
public class ApplyRevisionOptions
```

Η κλάση ApplyRevisionOptions σας επιτρέπει να ενημερώσετε την κατάσταση των αναθεωρήσεων πριν εφαρμοστούν στο τελικό έγγραφο.


Παρέχει διάφορους κατασκευαστές και ιδιότητες για την προσαρμογή της διαδικασίας εφαρμογής της αναθεώρησης.


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


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [ApplyRevisionOptions()](#ApplyRevisionOptions--) | Αρχικοποιεί μια νέα παρουσία της κλάσης ApplyRevisionOptions. |
|
|  | [ApplyRevisionOptions(List<RevisionInfo> changes)](#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--) | Δημιουργεί ένα νέο αντικείμενο ApplyRevisionOptions με τη συγκεκριμένη λίστα αναθεωρήσεων. |
|
|  | [ApplyRevisionOptions(List<RevisionInfo> changes, RevisionAction revisionAction)](#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--com.groupdocs.comparison.words.revision.RevisionAction-) | Δημιουργεί ένα νέο αντικείμενο ApplyRevisionOptions με τη συγκεκριμένη λίστα αναθεωρήσεων και μια κοινή ενέργεια αναθεώρησης. |
|
|  | [ApplyRevisionOptions(RevisionAction revisionAction)](#ApplyRevisionOptions-com.groupdocs.comparison.words.revision.RevisionAction-) | Δημιουργεί ένα νέο αντικείμενο ApplyRevisionOptions με μια κοινή ενέργεια αναθεώρησης. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getChanges()](#getChanges--) | Αποκτά τη λίστα των αναθεωρήσεων που θα εφαρμοστούν. |
|
|  | [setChanges(List<RevisionInfo> changes)](#setChanges-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--) | Ορίζει τη λίστα των αναθεωρήσεων που θα εφαρμοστούν. |
|
|  | [getCommonHandler()](#getCommonHandler--) | Αποκτά την κοινή ενέργεια αναθεώρησης που θα εφαρμοστεί σε όλες τις αναθεωρήσεις. |
|
|  | [setCommonHandler(RevisionAction commonHandler)](#setCommonHandler-com.groupdocs.comparison.words.revision.RevisionAction-) | Ορίζει την κοινή ενέργεια αναθεώρησης που θα εφαρμοστεί σε όλες τις αναθεωρήσεις. |
|
### ApplyRevisionOptions() {#ApplyRevisionOptions--}
```
public ApplyRevisionOptions()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης ApplyRevisionOptions.


### ApplyRevisionOptions(List<RevisionInfo> changes) {#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--}
```
public ApplyRevisionOptions(List<RevisionInfo> changes)
```


Δημιουργεί ένα νέο αντικείμενο ApplyRevisionOptions με τη συγκεκριμένη λίστα αναθεωρήσεων.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | αλλαγές | java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> | Η λίστα των αναθεωρήσεων που θα εφαρμοστούν |
|

### ApplyRevisionOptions(List<RevisionInfo> changes, RevisionAction revisionAction) {#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--com.groupdocs.comparison.words.revision.RevisionAction-}
```
public ApplyRevisionOptions(List<RevisionInfo> changes, RevisionAction revisionAction)
```


Δημιουργεί ένα νέο αντικείμενο ApplyRevisionOptions με τη συγκεκριμένη λίστα αναθεωρήσεων και μια κοινή ενέργεια αναθεώρησης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | αλλαγές | java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> | Η λίστα των αναθεωρήσεων που θα εφαρμοστούν |
|
|  | revisionAction | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | Η κοινή ενέργεια αναθεώρησης που θα εφαρμοστεί σε όλες τις αναθεωρήσεις |
|

### ApplyRevisionOptions(RevisionAction revisionAction) {#ApplyRevisionOptions-com.groupdocs.comparison.words.revision.RevisionAction-}
```
public ApplyRevisionOptions(RevisionAction revisionAction)
```


Δημιουργεί ένα νέο αντικείμενο ApplyRevisionOptions με μια κοινή ενέργεια αναθεώρησης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | revisionAction | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | Η κοινή ενέργεια αναθεώρησης που θα εφαρμοστεί σε όλες τις αναθεωρήσεις |
|

### getChanges() {#getChanges--}
```
public List<RevisionInfo> getChanges()
```


Αποκτά τη λίστα των αναθεωρήσεων που θα εφαρμοστούν.


**Returns:**
java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> - η λίστα των αναθεωρήσεων

### setChanges(List<RevisionInfo> changes) {#setChanges-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--}
```
public void setChanges(List<RevisionInfo> changes)
```


Ορίζει τη λίστα των αναθεωρήσεων που θα εφαρμοστούν.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | αλλαγές | java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> | Η λίστα των αναθεωρήσεων |
|

### getCommonHandler() {#getCommonHandler--}
```
public RevisionAction getCommonHandler()
```


Αποκτά την κοινή ενέργεια αναθεώρησης που θα εφαρμοστεί σε όλες τις αναθεωρήσεις.


**Returns:**
[RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) - the common revision action

### setCommonHandler(RevisionAction commonHandler) {#setCommonHandler-com.groupdocs.comparison.words.revision.RevisionAction-}
```
public void setCommonHandler(RevisionAction commonHandler)
```


Ορίζει την κοινή ενέργεια αναθεώρησης που θα εφαρμοστεί σε όλες τις αναθεωρήσεις.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | commonHandler | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | Η κοινή ενέργεια αναθεώρησης |
|

