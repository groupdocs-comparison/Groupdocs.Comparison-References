---
title: "ChangeInfo"
second_title: "GroupDocs.Comparison for Java Αναφορά API"
description: "Η κλάση ChangeInfo αντιπροσωπεύει πληροφορίες σχετικά με μια συγκεκριμένη αλλαγή σε σύγκριση εγγράφων."
type: docs
weight: 10
url: /el/java/com.groupdocs.comparison.result/changeinfo/
---
**Inheritance:**
java.lang.Object
```
public class ChangeInfo
```

Η κλάση ChangeInfo αντιπροσωπεύει πληροφορίες σχετικά με μια συγκεκριμένη αλλαγή σε σύγκριση εγγράφων.


Παρέχει λεπτομέρειες όπως ο τύπος της αλλαγής, η επηρεαζόμενη περιοχή, και το περιεχόμενο πριν και μετά την αλλαγή.
Χρησιμοποιήστε αυτήν την κλάση για να ανακτήσετε πληροφορίες σχετικά με μεμονωμένες αλλαγές μέσα σε ένα αποτέλεσμα σύγκρισης.


Παράδειγμα χρήσης:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     comparer.compare(resultFile);
     // Get a list of changes from the comparison result
     ChangeInfo[] changes = comparer.getChanges();
     // Iterate through the changes and retrieve information
     for (ChangeInfo change : changes) {
         ChangeType changeType = change.getType();
         String componentType = change.getComponentType();
         PageInfo pageInfo = change.getPageInfo();
         // Process the change information as needed
         // ...
     }
 }
 
````


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [ChangeInfo()](#ChangeInfo--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getRow()](#getRow--) |  |
| [setRow(Integer row)](#setRow-java.lang.Integer-) |  |
| [getColumn()](#getColumn--) |  |
| [setColumn(Integer column)](#setColumn-java.lang.Integer-) |  |
| [getColumnHeader()](#getColumnHeader--) |  |
| [setColumnHeader(String columnHeader)](#setColumnHeader-java.lang.String-) |  |
|  | [getId()](#getId--) | Λαμβάνει το μοναδικό αναγνωριστικό της αλλαγής. |
|
|  | [setId(int value)](#setId-int-) | Ορίζει το μοναδικό αναγνωριστικό της αλλαγής. |
|
|  | [getComparisonAction()](#getComparisonAction--) | Λαμβάνει τη δράση που θα εφαρμοστεί στην αλλαγή. |
|
|  | [setComparisonAction(ComparisonAction value)](#setComparisonAction-com.groupdocs.comparison.result.ComparisonAction-) | Ορίζει τη δράση που πρέπει να εφαρμοστεί στην αλλαγή. |
|
|  | [getPageInfo()](#getPageInfo--) | Λαμβάνει πληροφορίες σχετικά με τη σελίδα, στην οποία βρέθηκε η τρέχουσα αλλαγή. |
|
|  | [setPageInfo(PageInfo value)](#setPageInfo-com.groupdocs.comparison.result.PageInfo-) | Ορίζει πληροφορίες σχετικά με τη σελίδα, στην οποία βρέθηκε η τρέχουσα αλλαγή. |
|
|  | [getBox()](#getBox--) | Λαμβάνει τις συντεταγμένες του τροποποιημένου στοιχείου στη σελίδα. |
|
|  | [setBox(Rectangle value)](#setBox-com.groupdocs.comparison.result.Rectangle-) | Ορίζει τις συντεταγμένες του τροποποιημένου στοιχείου στη σελίδα. |
|
|  | [getText()](#getText--) | Λαμβάνει την τιμή κειμένου της αλλαγής. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Ορίζει την τιμή κειμένου της αλλαγής. |
|
|  | [getStyleChanges()](#getStyleChanges--) | Λαμβάνει τη λίστα των αλλαγών στυλ. |
|
|  | [setStyleChanges(List<StyleChangeInfo> value)](#setStyleChanges-java.util.List-com.groupdocs.comparison.result.StyleChangeInfo--) | Ορίζει τη λίστα των αλλαγών στυλ. |
|
|  | [getAuthors()](#getAuthors--) | Λαμβάνει τη λίστα των συγγραφέων. |
|
|  | [setAuthors(List<String> value)](#setAuthors-java.util.List-java.lang.String--) | Ορίζει τη λίστα των συγγραφέων. |
|
|  | [getType()](#getType--) | Λαμβάνει τον τύπο της αλλαγής που αντιπροσωπεύεται από το enum [ChangeType](../../com.groupdocs.comparison.result/changetype). |
|
|  | [getTargetText()](#getTargetText--) | Λαμβάνει το τροποποιημένο κείμενο από το έγγραφο-στόχο. |
|
|  | [setTargetText(String value)](#setTargetText-java.lang.String-) | Ορίζει το τροποποιημένο κείμενο από το έγγραφο-στόχο. |
|
|  | [getSourceText()](#getSourceText--) | Λαμβάνει το τροποποιημένο κείμενο από το έγγραφο-πηγή. |
|
|  | [setSourceText(String value)](#setSourceText-java.lang.String-) | Ορίζει το τροποποιημένο κείμενο από το έγγραφο προέλευσης. |
|
|  | [getComponentType()](#getComponentType--) | Λαμβάνει τον τύπο του τροποποιημένου στοιχείου. |
|
|  | [setComponentType(String value)](#setComponentType-java.lang.String-) | Ορίζει τον τύπο του τροποποιημένου στοιχείου. |
|
| [toString()](#toString--) |  |
### ChangeInfo() {#ChangeInfo--}
```
public ChangeInfo()
```


### getRow() {#getRow--}
```
public Integer getRow()
```




**Returns:**
java.lang.Integer
### setRow(Integer row) {#setRow-java.lang.Integer-}
```
public void setRow(Integer row)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| γραμμή | java.lang.Integer |  |

### getColumn() {#getColumn--}
```
public Integer getColumn()
```




**Returns:**
java.lang.Integer
### setColumn(Integer column) {#setColumn-java.lang.Integer-}
```
public void setColumn(Integer column)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| στήλη | java.lang.Integer |  |

### getColumnHeader() {#getColumnHeader--}
```
public String getColumnHeader()
```




**Returns:**
java.lang.String
### setColumnHeader(String columnHeader) {#setColumnHeader-java.lang.String-}
```
public void setColumnHeader(String columnHeader)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| columnHeader | java.lang.String |  |

### getId() {#getId--}
```
public final int getId()
```


Λαμβάνει το μοναδικό αναγνωριστικό της αλλαγής.


**Returns:**
int - το αναγνωριστικό της αλλαγής

### setId(int value) {#setId-int-}
```
public final void setId(int value)
```


Ορίζει το μοναδικό αναγνωριστικό της αλλαγής.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | int | Το αναγνωριστικό της αλλαγής |
|

### getComparisonAction() {#getComparisonAction--}
```
public final ComparisonAction getComparisonAction()
```


Λαμβάνει τη δράση που θα εφαρμοστεί στην αλλαγή.
Η ενέργεια ([ComparisonAction.ACCEPT](../../com.groupdocs.comparison.result/comparisonaction#ACCEPT) ή [ComparisonAction.REJECT](../../com.groupdocs.comparison.result/comparisonaction#REJECT)) καθορίζει στην σύγκριση τι πρέπει να κάνει με αυτήν την αλλαγή.


**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) - the action that will be applied to the change

### setComparisonAction(ComparisonAction value) {#setComparisonAction-com.groupdocs.comparison.result.ComparisonAction-}
```
public final void setComparisonAction(ComparisonAction value)
```


Ορίζει τη δράση που πρέπει να εφαρμοστεί στην αλλαγή.
Η ενέργεια ([ComparisonAction.ACCEPT](../../com.groupdocs.comparison.result/comparisonaction#ACCEPT) ή [ComparisonAction.REJECT](../../com.groupdocs.comparison.result/comparisonaction#REJECT)) καθορίζει στην σύγκριση τι πρέπει να κάνει με αυτήν την αλλαγή.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) | Η ενέργεια που πρέπει να εφαρμοστεί στην αλλαγή |
|

### getPageInfo() {#getPageInfo--}
```
public final PageInfo getPageInfo()
```


Λαμβάνει πληροφορίες σχετικά με τη σελίδα, στην οποία βρέθηκε η τρέχουσα αλλαγή.


**Returns:**
[PageInfo](../../com.groupdocs.comparison.result/pageinfo) - information about the page

### setPageInfo(PageInfo value) {#setPageInfo-com.groupdocs.comparison.result.PageInfo-}
```
public final void setPageInfo(PageInfo value)
```


Ορίζει πληροφορίες σχετικά με τη σελίδα, στην οποία βρέθηκε η τρέχουσα αλλαγή.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [PageInfo](../../com.groupdocs.comparison.result/pageinfo) | Πληροφορίες για τη σελίδα |
|

### getBox() {#getBox--}
```
public final Rectangle getBox()
```


Λαμβάνει τις συντεταγμένες του τροποποιημένου στοιχείου στη σελίδα.


**Returns:**
[Rectangle](../../com.groupdocs.comparison.result/rectangle) - coordinates of changed element

### setBox(Rectangle value) {#setBox-com.groupdocs.comparison.result.Rectangle-}
```
public final void setBox(Rectangle value)
```


Ορίζει τις συντεταγμένες του τροποποιημένου στοιχείου στη σελίδα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [Rectangle](../../com.groupdocs.comparison.result/rectangle) | Συντεταγμένες του τροποποιημένου στοιχείου, μη μηδενικές |
|

### getText() {#getText--}
```
public final String getText()
```


Λαμβάνει την τιμή κειμένου της αλλαγής.


**Returns:**
java.lang.String - τιμή κειμένου της αλλαγής

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Ορίζει την τιμή κειμένου της αλλαγής.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | java.lang.String | Τιμή κειμένου της αλλαγής |
|

### getStyleChanges() {#getStyleChanges--}
```
public final List<StyleChangeInfo> getStyleChanges()
```


Λαμβάνει τη λίστα των αλλαγών στυλ.


**Returns:**
java.util.List<com.groupdocs.comparison.result.StyleChangeInfo> - η λίστα των αλλαγών στυλ

### setStyleChanges(List<StyleChangeInfo> value) {#setStyleChanges-java.util.List-com.groupdocs.comparison.result.StyleChangeInfo--}
```
public final void setStyleChanges(List<StyleChangeInfo> value)
```


Ορίζει τη λίστα των αλλαγών στυλ.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | java.util.List<com.groupdocs.comparison.result.StyleChangeInfo> | Η λίστα των αλλαγών στυλ |
|

### getAuthors() {#getAuthors--}
```
public final List<String> getAuthors()
```


Λαμβάνει τη λίστα των συγγραφέων.


**Returns:**
java.util.List<java.lang.String> - η λίστα των συγγραφέων

### setAuthors(List<String> value) {#setAuthors-java.util.List-java.lang.String--}
```
public final void setAuthors(List<String> value)
```


Ορίζει τη λίστα των συγγραφέων.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | java.util.List<java.lang.String> | Η λίστα των συγγραφέων |
|

### getType() {#getType--}
```
public final ChangeType getType()
```


Λαμβάνει τον τύπο της αλλαγής που αντιπροσωπεύεται από το enum [ChangeType](../../com.groupdocs.comparison.result/changetype).


**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - the type of the change

### getTargetText() {#getTargetText--}
```
public String getTargetText()
```


Λαμβάνει το τροποποιημένο κείμενο από το έγγραφο-στόχο.


**Returns:**
java.lang.String - το τροποποιημένο κείμενο

### setTargetText(String value) {#setTargetText-java.lang.String-}
```
public void setTargetText(String value)
```


Ορίζει το τροποποιημένο κείμενο από το έγγραφο-στόχο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | java.lang.String | Το τροποποιημένο κείμενο |
|

### getSourceText() {#getSourceText--}
```
public String getSourceText()
```


Λαμβάνει το τροποποιημένο κείμενο από το έγγραφο-πηγή.


**Returns:**
java.lang.String - το τροποποιημένο κείμενο

### setSourceText(String value) {#setSourceText-java.lang.String-}
```
public void setSourceText(String value)
```


Ορίζει το τροποποιημένο κείμενο από το έγγραφο προέλευσης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | java.lang.String | Το τροποποιημένο κείμενο |
|

### getComponentType() {#getComponentType--}
```
public String getComponentType()
```


Λαμβάνει τον τύπο του τροποποιημένου στοιχείου.


**Returns:**
java.lang.String - ο τύπος του τροποποιημένου στοιχείου

### setComponentType(String value) {#setComponentType-java.lang.String-}
```
public void setComponentType(String value)
```


Ορίζει τον τύπο του τροποποιημένου στοιχείου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | java.lang.String | Ο τύπος του τροποποιημένου στοιχείου |
|

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
