---
title: "IDocumentInfo"
second_title: "GroupDocs.Comparison for Java Αναφορά API"
description: "Παρέχει πρόσβαση στις ιδιότητες του εγγράφου."
type: docs
weight: 10
url: /el/java/com.groupdocs.comparison.interfaces/idocumentinfo/
---
**All Implemented Interfaces:**
java.io.Closeable
```
public interface IDocumentInfo extends Closeable
```

Παρέχει πρόσβαση στις ιδιότητες του εγγράφου.


Περισσότερες λεπτομέρειες σχετικά με τη χρήση του μπορείτε να βρείτε στη μέθοδο [Document.getDocumentInfo()](../../com.groupdocs.comparison/document#getDocumentInfo--) ή σε μια [documentation](../https://docs.groupdocs.com/comparison/java/get-file-info/).


Παράδειγμα χρήσης:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    try (IDocumentInfo documentInfo = comparer.getSource().getDocumentInfo()) {
      for (int i = 0; i < documentInfo.getPageCount(); i++) {
          System.out.printf("File type: %s%nNumber of pages: %d", documentInfo.getFileType().getFileFormat(), documentInfo.getPageCount());
      }
    }
 }
 
````


## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getFileType()](#getFileType--) | Λαμβάνει έναν τύπο του αρχείου που αναπαρίσταται από το enum [FileType](../../com.groupdocs.comparison.result/filetype). |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.comparison.result.FileType-) | Ορίζει έναν τύπο του αρχείου χρησιμοποιώντας το enum [FileType](../../com.groupdocs.comparison.result/filetype). |
|
|  | [getPageCount()](#getPageCount--) | Λαμβάνει τον αριθμό του αρχείου. |
|
|  | [setPageCount(int value)](#setPageCount-int-) | Ορίζει τον αριθμό του αρχείου. |
|
|  | [getSize()](#getSize--) | Λαμβάνει το μέγεθος του αρχείου. |
|
|  | [setSize(long value)](#setSize-long-) | Ορίζει το μέγεθος του αρχείου. |
|
|  | [getPagesInfo()](#getPagesInfo--) | Λαμβάνει πληροφορίες για κάθε σελίδα του αρχείου χρησιμοποιώντας την κλάση [PageInfo](../../com.groupdocs.comparison.result/pageinfo). |
|
|  | [setPagesInfo(List<PageInfo> pageInfos)](#setPagesInfo-java.util.List-com.groupdocs.comparison.result.PageInfo--) | Ορίζει πληροφορίες για κάθε σελίδα του αρχείου χρησιμοποιώντας την κλάση [PageInfo](../../com.groupdocs.comparison.result/pageinfo). |
|
|  | [close()](#close--) | Καταστρέφει το αντικείμενο, καθιστώντας αδύνατη τη λήψη πληροφοριών του εγγράφου χρησιμοποιώντας αυτήν την παρουσία του αντικειμένου [IDocumentInfo](../../com.groupdocs.comparison.interfaces/idocumentinfo). |
|
### getFileType() {#getFileType--}
```
public abstract FileType getFileType()
```


Λαμβάνει έναν τύπο του αρχείου που αναπαρίσταται από το enum [FileType](../../com.groupdocs.comparison.result/filetype).


**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the type of the file

### setFileType(FileType value) {#setFileType-com.groupdocs.comparison.result.FileType-}
```
public abstract void setFileType(FileType value)
```


Ορίζει έναν τύπο του αρχείου χρησιμοποιώντας το enum [FileType](../../com.groupdocs.comparison.result/filetype).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [FileType](../../com.groupdocs.comparison.result/filetype) | Ο τύπος του αρχείου |
|

### getPageCount() {#getPageCount--}
```
public abstract int getPageCount()
```


Λαμβάνει τον αριθμό του αρχείου.


**Returns:**
int - ο αριθμός του αρχείου

### setPageCount(int value) {#setPageCount-int-}
```
public abstract void setPageCount(int value)
```


Ορίζει τον αριθμό του αρχείου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | int | Ο αριθμός του αρχείου |
|

### getSize() {#getSize--}
```
public abstract long getSize()
```


Λαμβάνει το μέγεθος του αρχείου.


**Returns:**
long - το μέγεθος του αρχείου

### setSize(long value) {#setSize-long-}
```
public abstract void setSize(long value)
```


Ορίζει το μέγεθος του αρχείου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | long | Το μέγεθος του αρχείου |
|

### getPagesInfo() {#getPagesInfo--}
```
public abstract List<PageInfo> getPagesInfo()
```


Λαμβάνει πληροφορίες για κάθε σελίδα του αρχείου χρησιμοποιώντας την κλάση [PageInfo](../../com.groupdocs.comparison.result/pageinfo).


**Returns:**
java.util.List<com.groupdocs.comparison.result.PageInfo> - πληροφορίες για κάθε σελίδα του αρχείου

### setPagesInfo(List<PageInfo> pageInfos) {#setPagesInfo-java.util.List-com.groupdocs.comparison.result.PageInfo--}
```
public abstract void setPagesInfo(List<PageInfo> pageInfos)
```


Ορίζει πληροφορίες για κάθε σελίδα του αρχείου χρησιμοποιώντας την κλάση [PageInfo](../../com.groupdocs.comparison.result/pageinfo).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | pageInfos | java.util.List<com.groupdocs.comparison.result.PageInfo> | Πληροφορίες για κάθε σελίδα του αρχείου |
|

### close() {#close--}
```
public abstract void close()
```


Καταστρέφει το αντικείμενο, καθιστώντας αδύνατη τη λήψη πληροφοριών του εγγράφου χρησιμοποιώντας αυτήν την παρουσία του αντικειμένου [IDocumentInfo](../../com.groupdocs.comparison.interfaces/idocumentinfo).
Επίσης διαγράφει προσωρινά αρχεία και απελευθερώνει τους χρησιμοποιημένους πόρους.


