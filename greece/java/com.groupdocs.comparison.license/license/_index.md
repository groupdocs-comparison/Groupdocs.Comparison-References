---
title: "Άδεια"
second_title: "GroupDocs.Comparison for Java Αναφορά API"
description: "Η κλάση License παρέχει μεθόδους για τον ορισμό και την εφαρμογή αδειών για το GroupDocs.Comparison."
type: docs
weight: 10
url: /el/java/com.groupdocs.comparison.license/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

Η κλάση License παρέχει μεθόδους για τον ορισμό και την εφαρμογή αδειών για το GroupDocs.Comparison.


Σας επιτρέπει να ενεργοποιήσετε ή να απενεργοποιήσετε συγκεκριμένες λειτουργίες της βιβλιοθήκης βάσει της εφαρμοσμένης άδειας.

* More about GroupDocs.Comparison licensing: [Evaluation Limitations and Licensing](../https://docs.groupdocs.com/display/comparisonjava/Evaluation+Limitations+and+Licensing+of+GroupDocs.Comparison)


Παράδειγμα χρήσης:

````

 final License license = new License();
 license.setLicense("GroupDocs.License.lic");
 
````


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [License()](#License--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [isValidLicense()](#isValidLicense--) | Λαμβάνει μια τιμή που υποδεικνύει αν η άδεια έχει οριστεί ή όχι. |
|
|  | [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | Ορίζει μια άδεια για το Comparison χρησιμοποιώντας ροή εισόδου. |
|
|  | [setLicense(Path licensePath)](#setLicense-java.nio.file.Path-) | Ορίζει μια άδεια για το Comparison χρησιμοποιώντας τη διαδρομή του αρχείου άδειας. |
|
|  | [setLicense(String licensePath)](#setLicense-java.lang.String-) | Ορίζει μια άδεια για το Comparison χρησιμοποιώντας τη διαδρομή του αρχείου άδειας. |
|
### License() {#License--}
```
public License()
```


### isValidLicense() {#isValidLicense--}
```
public static boolean isValidLicense()
```


Λαμβάνει μια τιμή που υποδεικνύει αν η άδεια έχει οριστεί ή όχι.


**Returns:**
boolean - true εάν η άδεια ορίστηκε επιτυχώς, διαφορετικά false

### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


Ορίζει μια άδεια για το Comparison χρησιμοποιώντας ροή εισόδου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | licenseStream | java.io.InputStream | Η ροή άδειας, null ακυρώνει την άδεια |
|

### setLicense(Path licensePath) {#setLicense-java.nio.file.Path-}
```
public final void setLicense(Path licensePath)
```


Ορίζει μια άδεια για το Comparison χρησιμοποιώντας τη διαδρομή του αρχείου άδειας.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | licensePath | java.nio.file.Path | Η διαδρομή του αρχείου άδειας |
|

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


Ορίζει μια άδεια για το Comparison χρησιμοποιώντας τη διαδρομή του αρχείου άδειας.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | licensePath | java.lang.String | Η διαδρομή του αρχείου άδειας |
|

