---
title: "RevisionAction"
second_title: "GroupDocs.Comparison for Java Αναφορά API"
description: "Αντιπροσωπεύει μια ενέργεια που μπορεί να εφαρμοστεί σε μια αναθεώρηση."
type: docs
weight: 13
url: /el/java/com.groupdocs.comparison.words.revision/revisionaction/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum RevisionAction extends Enum<RevisionAction>
```

Αντιπροσωπεύει μια ενέργεια που μπορεί να εφαρμοστεί σε μια αναθεώρηση.


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
|  | [NONE](#NONE) | Δείχνει ότι δεν απαιτείται καμία ενέργεια. |
|
|  | [ACCEPT](#ACCEPT) | Δείχνει ότι η αναθεώρηση θα εμφανιστεί εάν είναι τύπου INSERTION, ή θα αφαιρεθεί εάν ο τύπος είναι DELETION. |
|
|  | [REJECT](#REJECT) | Δείχνει ότι η αναθεώρηση θα αφαιρεθεί εάν είναι τύπου INSERTION, ή θα εμφανιστεί εάν ο τύπος είναι DELETION. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### NONE {#NONE}
```
public static final RevisionAction NONE
```


Δείχνει ότι δεν απαιτείται καμία ενέργεια.


### ACCEPT {#ACCEPT}
```
public static final RevisionAction ACCEPT
```


Δείχνει ότι η αναθεώρηση θα εμφανιστεί εάν είναι τύπου INSERTION, ή θα αφαιρεθεί εάν ο τύπος είναι DELETION.


### REJECT {#REJECT}
```
public static final RevisionAction REJECT
```


Δείχνει ότι η αναθεώρηση θα αφαιρεθεί εάν είναι τύπου INSERTION, ή θα εμφανιστεί εάν ο τύπος είναι DELETION.


### values() {#values--}
```
public static RevisionAction[] values()
```




**Returns:**
com.groupdocs.comparison.words.revision.RevisionAction[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static RevisionAction valueOf(String name)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| όνομα | java.lang.String |  |

**Returns:**
[RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction)
