---
title: "RevisionInfo"
second_title: "GroupDocs.Comparison for Java Αναφορά API"
description: "Αντιπροσωπεύει μια αναθεώρηση στο έγγραφο."
type: docs
weight: 12
url: /el/java/com.groupdocs.comparison.words.revision/revisioninfo/
---
**Inheritance:**
java.lang.Object
```
public class RevisionInfo
```

Αντιπροσωπεύει μια αναθεώρηση στο έγγραφο.


Μια αναθεώρηση περιλαμβάνει πληροφορίες σχετικά με την αλλαγή αναθεώρησης που έγινε στο έγγραφο.
Αυτή η κλάση παρέχει μεθόδους για την ανάκτηση πληροφοριών σχετικά με την αναθεώρηση, όπως ο τύπος της,
περιεχόμενο, συγγραφέας, κ.λπ.

Παράδειγμα χρήσης:

````

 try (RevisionHandler revisionHandler = new RevisionHandler(sourceFile)) {
     List revisionList = revisionHandler.getRevisions();

     for (RevisionInfo revisionInfo : revisionList) {
         System.out.println("Revision Type: " + revisionInfo.getType());
         System.out.println("Text: " + revisionInfo.getText());
         System.out.println("Author: " + revisionInfo.getAuthor());
     }
 }
 
````


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [RevisionInfo()](#RevisionInfo--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getAction()](#getAction--) | Λαμβάνει τη δράση που σχετίζεται με την αναθεώρηση (αποδοχή ή απόρριψη). |
|
|  | [setAction(RevisionAction value)](#setAction-com.groupdocs.comparison.words.revision.RevisionAction-) | Ορίζει την τιμή που σχετίζεται με την αναθεώρηση (αποδοχή ή απόρριψη). |
|
|  | [getText()](#getText--) | Λαμβάνει το κείμενο της αναθεώρησης. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Ορίζει το περιεχόμενο τιμής της αναθεώρησης. |
|
|  | [getAuthor()](#getAuthor--) | Λαμβάνει τον συγγραφέα της αναθεώρησης. |
|
|  | [setAuthor(String value)](#setAuthor-java.lang.String-) | Ορίζει την τιμή της αναθεώρησης. |
|
|  | [getType()](#getType--) | Λαμβάνει τον τύπο της αναθεώρησης, ανάλογα με τον τύπο η λογική της Δράσης (αποδοχή ή απόρριψη) αλλάζει. |
|
|  | [setType(RevisionType value)](#setType-com.groupdocs.comparison.words.revision.RevisionType-) | Ορίζει την τιμή της αναθεώρησης, ανάλογα με την τιμή η λογική της Δράσης (αποδοχή ή απόρριψη) αλλάζει. |
|
### RevisionInfo() {#RevisionInfo--}
```
public RevisionInfo()
```


### getAction() {#getAction--}
```
public RevisionAction getAction()
```


Λαμβάνει τη δράση που σχετίζεται με την αναθεώρηση (αποδοχή ή απόρριψη). Αυτό το πεδίο σας επιτρέπει να επηρεάσετε την εμφάνιση της αναθεώρησης.


**Returns:**
[RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) - the action associated with the revision.

### setAction(RevisionAction value) {#setAction-com.groupdocs.comparison.words.revision.RevisionAction-}
```
public void setAction(RevisionAction value)
```


Ορίζει την τιμή που σχετίζεται με την αναθεώρηση (αποδοχή ή απόρριψη). Αυτό το πεδίο σας επιτρέπει να επηρεάσετε την εμφάνιση της αναθεώρησης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | Η τιμή που σχετίζεται με την αναθεώρηση. |
|

### getText() {#getText--}
```
public String getText()
```


Λαμβάνει το κείμενο της αναθεώρησης.


**Returns:**
java.lang.String - το κείμενο της αναθεώρησης.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Ορίζει το περιεχόμενο τιμής της αναθεώρησης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | java.lang.String | Το περιεχόμενο τιμής της αναθεώρησης. |
|

### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Λαμβάνει τον συγγραφέα της αναθεώρησης.


**Returns:**
java.lang.String - ο συγγραφέας της αναθεώρησης.

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public void setAuthor(String value)
```


Ορίζει την τιμή της αναθεώρησης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | java.lang.String | Η τιμή της αναθεώρησης. |
|

### getType() {#getType--}
```
public RevisionType getType()
```


Λαμβάνει τον τύπο της αναθεώρησης, ανάλογα με τον τύπο η λογική της Δράσης (αποδοχή ή απόρριψη) αλλάζει.


**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) - the type of the revision.

### setType(RevisionType value) {#setType-com.groupdocs.comparison.words.revision.RevisionType-}
```
public void setType(RevisionType value)
```


Ορίζει την τιμή της αναθεώρησης, ανάλογα με την τιμή η λογική της Δράσης (αποδοχή ή απόρριψη) αλλάζει.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) | Η τιμή της αναθεώρησης. |
|

