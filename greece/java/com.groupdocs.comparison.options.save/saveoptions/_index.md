---
title: "SaveOptions"
second_title: "GroupDocs.Comparison for Java Αναφορά API"
description: "Επιτρέπει τον καθορισμό πρόσθετων επιλογών κατά την αποθήκευση ενός εγγράφου."
type: docs
weight: 10
url: /el/java/com.groupdocs.comparison.options.save/saveoptions/
---
**Inheritance:**
java.lang.Object
```
public class SaveOptions
```

Επιτρέπει τον καθορισμό πρόσθετων επιλογών κατά την αποθήκευση ενός εγγράφου.


Παράδειγμα χρήσης:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    final SaveOptions saveOptions = new SaveOptions();
    saveOptions.setPassword("passw");

    comparer.compare(resultFile, saveOptions);
 }
 
````


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [SaveOptions()](#SaveOptions--) | Αρχικοποιεί μια νέα παρουσία της κλάσης SaveOptions. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getCloneMetadataType()](#getCloneMetadataType--) | Λαμβάνει μια στρατηγική επεξεργασίας αποθήκευσης μεταδεδομένων του τελικού εγγράφου. |
|
|  | [setCloneMetadataType(MetadataType value)](#setCloneMetadataType-com.groupdocs.comparison.options.enums.MetadataType-) | Ορίζει μια στρατηγική επεξεργασίας αποθήκευσης μεταδεδομένων του τελικού εγγράφου. |
|
|  | [getFileAuthorMetadata()](#getFileAuthorMetadata--) | Λαμβάνει ένα αντικείμενο μεταδεδομένων που θα τοποθετηθεί στο τελικό έγγραφο όταν το [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) οριστεί σε [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR). |
|
|  | [setFileAuthorMetadata(FileAuthorMetadata value)](#setFileAuthorMetadata-com.groupdocs.comparison.options.FileAuthorMetadata-) | Ορίζει ένα αντικείμενο μεταδεδομένων που θα πρέπει να τοποθετηθεί στο τελικό έγγραφο όταν το [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) οριστεί σε [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR). |
|
|  | [getPassword()](#getPassword--) | Λαμβάνει έναν κωδικό πρόσβασης για το τελικό έγγραφο. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Ορίζει έναν κωδικό πρόσβασης για το τελικό έγγραφο. |
|
|  | [getFolderPath()](#getFolderPath--) | Λαμβάνει τη διαδρομή φακέλου στην οποία θα αποθηκευτούν οι τελικές εικόνες. |
|
|  | [setFolderPath(String value)](#setFolderPath-java.lang.String-) | Ορίζει τη διαδρομή φακέλου στην οποία θα αποθηκευτούν οι τελικές εικόνες. |
|
|  | [setFolderPath(Path value)](#setFolderPath-java.nio.file.Path-) | Ορίζει τη διαδρομή φακέλου στην οποία θα αποθηκευτούν οι τελικές εικόνες. |
|
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης SaveOptions.


### getCloneMetadataType() {#getCloneMetadataType--}
```
public final MetadataType getCloneMetadataType()
```


Λαμβάνει μια στρατηγική επεξεργασίας αποθήκευσης μεταδεδομένων του τελικού εγγράφου.
Πιθανές τιμές βρίσκονται στην enum [MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype)


**Returns:**
[MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) - the stragegy of processing metadata

### setCloneMetadataType(MetadataType value) {#setCloneMetadataType-com.groupdocs.comparison.options.enums.MetadataType-}
```
public final void setCloneMetadataType(MetadataType value)
```


Ορίζει μια στρατηγική επεξεργασίας αποθήκευσης μεταδεδομένων του τελικού εγγράφου.
Πιθανές τιμές βρίσκονται στην enum [MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) | Η στρατηγική επεξεργασίας μεταδεδομένων |
|

### getFileAuthorMetadata() {#getFileAuthorMetadata--}
```
public final FileAuthorMetadata getFileAuthorMetadata()
```


Λαμβάνει ένα αντικείμενο μεταδεδομένων που θα τοποθετηθεί στο τελικό έγγραφο όταν το [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) οριστεί σε [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR).


**Returns:**
[FileAuthorMetadata](../../com.groupdocs.comparison.options/fileauthormetadata) - the metadata object

### setFileAuthorMetadata(FileAuthorMetadata value) {#setFileAuthorMetadata-com.groupdocs.comparison.options.FileAuthorMetadata-}
```
public final void setFileAuthorMetadata(FileAuthorMetadata value)
```


Ορίζει ένα αντικείμενο μεταδεδομένων που θα πρέπει να τοποθετηθεί στο τελικό έγγραφο όταν το [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) οριστεί σε [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [FileAuthorMetadata](../../com.groupdocs.comparison.options/fileauthormetadata) | Το αντικείμενο μεταδεδομένων |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Λαμβάνει έναν κωδικό πρόσβασης για το τελικό έγγραφο.


**Returns:**
java.lang.String - ο κωδικός πρόσβασης

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Ορίζει έναν κωδικό πρόσβασης για το τελικό έγγραφο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | java.lang.String | Ο κωδικός πρόσβασης |
|

### getFolderPath() {#getFolderPath--}
```
public final String getFolderPath()
```


Λαμβάνει τη διαδρομή φακέλου στην οποία θα αποθηκευτούν οι τελικές εικόνες.
Χρησιμοποιείται μόνο για σύγκριση εικόνων.


**Returns:**
java.lang.String - η διαδρομή φακέλου για αποθήκευση τελικών εικόνων

### setFolderPath(String value) {#setFolderPath-java.lang.String-}
```
public final void setFolderPath(String value)
```


Ορίζει τη διαδρομή φακέλου στην οποία θα αποθηκευτούν οι τελικές εικόνες.
Χρησιμοποιείται μόνο για σύγκριση εικόνων.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | java.lang.String | Η διαδρομή φακέλου για αποθήκευση τελικών εικόνων |
|

### setFolderPath(Path value) {#setFolderPath-java.nio.file.Path-}
```
public final void setFolderPath(Path value)
```


Ορίζει τη διαδρομή φακέλου στην οποία θα αποθηκευτούν οι τελικές εικόνες.
Χρησιμοποιείται μόνο για σύγκριση εικόνων.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | java.nio.file.Path | Η διαδρομή φακέλου για αποθήκευση τελικών εικόνων |
|

