---
title: "RevisionHandler"
second_title: "GroupDocs.Comparison for Java Αναφορά API"
description: "Αντιπροσωπεύει μια κλάση που ελέγχει τη διαχείριση των αναθεωρήσεων."
type: docs
weight: 11
url: /el/java/com.groupdocs.comparison.words.revision/revisionhandler/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class RevisionHandler implements Closeable
```

Αντιπροσωπεύει μια κλάση που ελέγχει τη διαχείριση των αναθεωρήσεων.


Η κλάση RevisionHandler σας επιτρέπει να εργάζεστε με αναθεωρήσεις σε έγγραφα.
Παρέχει μεθόδους για την ανάκτηση της λίστας των αναθεωρήσεων, την εφαρμογή αλλαγών στις αναθεωρήσεις και την αποθήκευση του τροποποιημένου εγγράφου.


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
|  | [RevisionHandler(String filePath)](#RevisionHandler-java.lang.String-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης RevisionHandler με τη διαδρομή προς το αρχείο που περιέχει αναθεωρήσεις. |
|
|  | [RevisionHandler(Path filePath)](#RevisionHandler-java.nio.file.Path-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης RevisionHandler με τη διαδρομή προς το αρχείο που περιέχει αναθεωρήσεις. |
|
|  | [RevisionHandler(InputStream file, FileType fileType)](#RevisionHandler-java.io.InputStream-com.groupdocs.comparison.result.FileType-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης RevisionHandler με μια ροή αρχείου που περιέχει αναθεωρήσεις. |
|
|  | [RevisionHandler(Document document)](#RevisionHandler-com.aspose.words.Document-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης RevisionHandler με ένα έγγραφο. |
|
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [SOURCE_PATH_IS_NULL](#SOURCE-PATH-IS-NULL) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getRevisions()](#getRevisions--) | Αποκτά τη λίστα όλων των αναθεωρήσεων. |
|
|  | [applyRevisionChanges(ApplyRevisionOptions changes)](#applyRevisionChanges-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | Επεξεργάζεται τις αλλαγές στις αναθεωρήσεις και τις εφαρμόζει στο αρχικό αρχείο. |
|
|  | [applyRevisionChanges(Path filePath, ApplyRevisionOptions changes)](#applyRevisionChanges-java.nio.file.Path-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | Επεξεργάζεται τις αλλαγές στις αναθεωρήσεις και γράφει το αποτέλεσμα στο καθορισμένο αρχείο. |
|
|  | [applyRevisionChanges(String filePath, ApplyRevisionOptions changes)](#applyRevisionChanges-java.lang.String-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | Επεξεργάζεται τις αλλαγές στις αναθεωρήσεις και γράφει το αποτέλεσμα στο καθορισμένο αρχείο. |
|
|  | [applyRevisionChanges(OutputStream outputStream, ApplyRevisionOptions changes)](#applyRevisionChanges-java.io.OutputStream-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | Επεξεργάζεται τις αλλαγές στις αναθεωρήσεις και γράφει το αποτέλεσμα στη ροή εγγράφου. |
|
| [close()](#close--) |  |
### RevisionHandler(String filePath) {#RevisionHandler-java.lang.String-}
```
public RevisionHandler(String filePath)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης RevisionHandler με τη διαδρομή προς το αρχείο που περιέχει αναθεωρήσεις.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Η διαδρομή προς το αρχείο. |
|

### RevisionHandler(Path filePath) {#RevisionHandler-java.nio.file.Path-}
```
public RevisionHandler(Path filePath)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης RevisionHandler με τη διαδρομή προς το αρχείο που περιέχει αναθεωρήσεις.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Η διαδρομή προς το αρχείο. |
|

### RevisionHandler(InputStream file, FileType fileType) {#RevisionHandler-java.io.InputStream-com.groupdocs.comparison.result.FileType-}
```
public RevisionHandler(InputStream file, FileType fileType)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης RevisionHandler με μια ροή αρχείου που περιέχει αναθεωρήσεις.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | αρχείο | java.io.InputStream | Η ροή του πηγαίου εγγράφου. |
|
|  | fileType | [FileType](../../com.groupdocs.comparison.result/filetype) | Ο τύπος του αρχείου. |
|

### RevisionHandler(Document document) {#RevisionHandler-com.aspose.words.Document-}
```
public RevisionHandler(Document document)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης RevisionHandler με ένα έγγραφο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | έγγραφο | com.aspose.words.Document | Το έγγραφο. |
|

### SOURCE_PATH_IS_NULL {#SOURCE-PATH-IS-NULL}
```
public static final String SOURCE_PATH_IS_NULL
```


### getRevisions() {#getRevisions--}
```
public List<RevisionInfo> getRevisions()
```


Αποκτά τη λίστα όλων των αναθεωρήσεων.


Λόγω του ότι οι αναθεωρήσεις αρχικά ταξινομήθηκαν σε μια ομάδα, οι αναθεωρήσεις πρέπει να ληφθούν από μια Λίστα.
Σε μια Λίστα, μια μεμονωμένη αναθεώρηση μπορεί να χωριστεί σε πολλαπλές αναθεωρήσεις με το ίδιο γενικό κείμενο.
Δεδομένου ότι η Λίστα μπορεί να περιέχει αναθεωρήσεις με το ίδιο γενικό κείμενο, αυτό πρέπει να ελέγχεται κατά τη δημιουργία λίστας αναθεωρήσεων για τον χρήστη.
Αυτό ελέγχεται εδώ χρησιμοποιώντας ομάδες List\<RevisionGroup\>.


**Returns:**
java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> - η λίστα των αναθεωρήσεων.

### applyRevisionChanges(ApplyRevisionOptions changes) {#applyRevisionChanges-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(ApplyRevisionOptions changes)
```


Επεξεργάζεται τις αλλαγές στις αναθεωρήσεις και τις εφαρμόζει στο αρχικό αρχείο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | Η λίστα των τροποποιημένων αναθεωρήσεων. |
|

### applyRevisionChanges(Path filePath, ApplyRevisionOptions changes) {#applyRevisionChanges-java.nio.file.Path-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(Path filePath, ApplyRevisionOptions changes)
```


Επεξεργάζεται τις αλλαγές στις αναθεωρήσεις και γράφει το αποτέλεσμα στο καθορισμένο αρχείο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Η διαδρομή του αρχείου αποτελέσματος. |
|
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | Η λίστα των τροποποιημένων αναθεωρήσεων. |
|

### applyRevisionChanges(String filePath, ApplyRevisionOptions changes) {#applyRevisionChanges-java.lang.String-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(String filePath, ApplyRevisionOptions changes)
```


Επεξεργάζεται τις αλλαγές στις αναθεωρήσεις και γράφει το αποτέλεσμα στο καθορισμένο αρχείο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Η διαδρομή του αρχείου αποτελέσματος. |
|
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | Η λίστα των τροποποιημένων αναθεωρήσεων. |
|

### applyRevisionChanges(OutputStream outputStream, ApplyRevisionOptions changes) {#applyRevisionChanges-java.io.OutputStream-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(OutputStream outputStream, ApplyRevisionOptions changes)
```


Επεξεργάζεται τις αλλαγές στις αναθεωρήσεις και γράφει το αποτέλεσμα στη ροή εγγράφου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | outputStream | java.io.OutputStream | Η ροή του εγγράφου αποτελέσματος. |
|
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | Η λίστα των τροποποιημένων αναθεωρήσεων. |
|

### close() {#close--}
```
public void close()
```




