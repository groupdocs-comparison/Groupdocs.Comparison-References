---
title: "FileAuthorMetadata"
second_title: "GroupDocs.Comparison for Java Αναφορά API"
description: "Επιτρέπει τη διαμόρφωση πληροφοριών σχετικά με τα μεταδεδομένα του συγγραφέα του εγγράφου."
type: docs
weight: 12
url: /el/java/com.groupdocs.comparison.options/fileauthormetadata/
---
**Inheritance:**
java.lang.Object
```
public class FileAuthorMetadata
```

Επιτρέπει τη διαμόρφωση πληροφοριών σχετικά με τα μεταδεδομένα του συγγραφέα του εγγράφου.


Παράδειγμα χρήσης:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     SaveOptions saveOptions = new SaveOptions();
     saveOptions.setCloneMetadataType(MetadataType.FILE_AUTHOR);

     final FileAuthorMetadata fileAuthorMetadata = new FileAuthorMetadata();
     fileAuthorMetadata.setAuthor("Tom");
     fileAuthorMetadata.setCompany("GroupDocs");
     fileAuthorMetadata.setLastSaveBy("Jack");

     saveOptions.setFileAuthorMetadata(fileAuthorMetadata);

     comparer.compare(resultFile, saveOptions);
 }
 
````


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [FileAuthorMetadata()](#FileAuthorMetadata--) | Αρχικοποιεί μια νέα παρουσία της κλάσης FileAuthorMetadata. |
|
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [GROUP_DOCS](#GROUP-DOCS) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getAuthor()](#getAuthor--) | Λαμβάνει τον συγγραφέα ενός εγγράφου. |
|
|  | [setAuthor(String value)](#setAuthor-java.lang.String-) | Ορίζει τον συγγραφέα ενός εγγράφου. |
|
|  | [getLastSaveBy()](#getLastSaveBy--) | Λαμβάνει το όνομα του ατόμου που αποθήκευσε το έγγραφο για τελευταία φορά. |
|
|  | [setLastSaveBy(String value)](#setLastSaveBy-java.lang.String-) | Ορίζει το όνομα του ατόμου που αποθήκευσε το έγγραφο για τελευταία φορά. |
|
|  | [getCompany()](#getCompany--) | Λαμβάνει το όνομα μιας εταιρείας του οποίου το έγγραφο είναι. |
|
|  | [setCompany(String value)](#setCompany-java.lang.String-) | Ορίζει το όνομα μιας εταιρείας του οποίου το έγγραφο είναι. |
|
### FileAuthorMetadata() {#FileAuthorMetadata--}
```
public FileAuthorMetadata()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης FileAuthorMetadata.


### GROUP_DOCS {#GROUP-DOCS}
```
public static final String GROUP_DOCS
```


### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```


Λαμβάνει τον συγγραφέα ενός εγγράφου.


**Returns:**
java.lang.String - ο συγγραφέας

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```


Ορίζει τον συγγραφέα ενός εγγράφου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | java.lang.String | Ο συγγραφέας |
|

### getLastSaveBy() {#getLastSaveBy--}
```
public final String getLastSaveBy()
```


Λαμβάνει το όνομα του ατόμου που αποθήκευσε το έγγραφο για τελευταία φορά.


**Returns:**
java.lang.String - το όνομα

### setLastSaveBy(String value) {#setLastSaveBy-java.lang.String-}
```
public final void setLastSaveBy(String value)
```


Ορίζει το όνομα του ατόμου που αποθήκευσε το έγγραφο για τελευταία φορά.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | java.lang.String | Το όνομα ενός ατόμου |
|

### getCompany() {#getCompany--}
```
public final String getCompany()
```


Λαμβάνει το όνομα μιας εταιρείας του οποίου το έγγραφο είναι.


**Returns:**
java.lang.String - το όνομα μιας εταιρείας

### setCompany(String value) {#setCompany-java.lang.String-}
```
public final void setCompany(String value)
```


Ορίζει το όνομα μιας εταιρείας του οποίου το έγγραφο είναι.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | java.lang.String | Το όνομα μιας εταιρείας |
|

