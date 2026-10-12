---
title: "LoadOptions"
second_title: "GroupDocs.Comparison for Java Αναφορά API"
description: "Επιτρέπει τον καθορισμό πρόσθετων επιλογών κατά τη φόρτωση ενός εγγράφου."
type: docs
weight: 10
url: /el/java/com.groupdocs.comparison.options.load/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

Επιτρέπει τον καθορισμό πρόσθετων επιλογών κατά τη φόρτωση ενός εγγράφου.


Παράδειγμα χρήσης:

````

 final LoadOptions loadOptions = new LoadOptions();
 loadOptions.setPassword("passw");
 loadOptions.setFileType(FileType.PDF);

 try (Comparer comparer = new Comparer(sourceFile, loadOptions)) {
    comparer.add(targetFile);

    comparer.compare(resultFile);
 }
 
````


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [LoadOptions()](#LoadOptions--) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης LoadOptions. |
|
|  | [LoadOptions(boolean isLoadText)](#LoadOptions-boolean-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης LoadOptions με μια σημαία που σημαίνει ότι η συμβολοσειρά εισόδου είναι κείμενο προς σύγκριση, όχι διαδρομή. |
|
|  | [LoadOptions(String password)](#LoadOptions-java.lang.String-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης LoadOptions με κωδικό πρόσβασης για τη φόρτωση του εγγράφου. |
|
|  | [LoadOptions(boolean isLoadText, String password)](#LoadOptions-boolean-java.lang.String-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης LoadOptions με μια σημαία που σημαίνει ότι η συμβολοσειρά εισόδου είναι κείμενο προς σύγκριση και κωδικός πρόσβασης για τη φόρτωση του εγγράφου. |
|
|  | [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.comparison.result.FileType-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης LoadOptions με τύπο αρχείου. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [isLoadText()](#isLoadText--) | Λαμβάνει μια σημαία που υποδεικνύει ότι η συμβολοσειρά που περνά στο κατασκευαστή του [Comparer](../../com.groupdocs.comparison/comparer) ή στη μέθοδο [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) είναι κείμενο σύγκρισης, όχι διαδρομές αρχείων (Μόνο για σύγκριση κειμένου). |
|
|  | [setLoadText(boolean value)](#setLoadText-boolean-) | Ορίζει μια σημαία που υποδεικνύει ότι η συμβολοσειρά που περνά στο κατασκευαστή του [Comparer](../../com.groupdocs.comparison/comparer) ή στη μέθοδο [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) είναι κείμενο σύγκρισης, όχι διαδρομές αρχείων (Μόνο για σύγκριση κειμένου). |
|
|  | [getPassword()](#getPassword--) | Λαμβάνει έναν κωδικό πρόσβασης που θα χρησιμοποιηθεί για τη φόρτωση ενός εγγράφου. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Ορίζει έναν κωδικό πρόσβασης που πρέπει να χρησιμοποιηθεί για τη φόρτωση ενός εγγράφου. |
|
|  | [getFontDirectories()](#getFontDirectories--) | Λαμβάνει μια λίστα καταλόγων όπου τοποθετούνται τα αρχεία γραμματοσειρών για τη φόρτωση ενός εγγράφου. |
|
|  | [setFontDirectories(List<String> value)](#setFontDirectories-java.util.List-java.lang.String--) | Ορίζει μια λίστα καταλόγων όπου τοποθετούνται τα αρχεία γραμματοσειρών για τη φόρτωση ενός εγγράφου. |
|
|  | [getFileType()](#getFileType--) | Λαμβάνει τον τύπο ενός αρχείου που φορτώνεται. |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.comparison.result.FileType-) | Ορίζει έναν τύπο αρχείου που φορτώνεται. |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης LoadOptions.


### LoadOptions(boolean isLoadText) {#LoadOptions-boolean-}
```
public LoadOptions(boolean isLoadText)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης LoadOptions με μια σημαία που σημαίνει ότι η συμβολοσειρά εισόδου είναι κείμενο προς σύγκριση, όχι διαδρομή.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | isLoadText | boolean | Η σημαία που σημαίνει ότι η συμβολοσειρά εισόδου είναι κείμενο προς σύγκριση, όχι διαδρομή |
|

### LoadOptions(String password) {#LoadOptions-java.lang.String-}
```
public LoadOptions(String password)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης LoadOptions με κωδικό πρόσβασης για τη φόρτωση του εγγράφου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | κωδικός πρόσβασης | java.lang.String | Ο κωδικός πρόσβασης για τη φόρτωση του εγγράφου |
|

### LoadOptions(boolean isLoadText, String password) {#LoadOptions-boolean-java.lang.String-}
```
public LoadOptions(boolean isLoadText, String password)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης LoadOptions με μια σημαία που σημαίνει ότι η συμβολοσειρά εισόδου είναι κείμενο προς σύγκριση και κωδικός πρόσβασης για τη φόρτωση του εγγράφου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | isLoadText | boolean | Η σημαία που σημαίνει ότι η συμβολοσειρά εισόδου είναι κείμενο προς σύγκριση, όχι διαδρομή |
|
|  | κωδικός πρόσβασης | java.lang.String | Ο κωδικός πρόσβασης για τη φόρτωση του εγγράφου |
|

### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.comparison.result.FileType-}
```
public LoadOptions(FileType fileType)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης LoadOptions με τύπο αρχείου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.comparison.result/filetype) | Ο τύπος του αρχείου |
|

### isLoadText() {#isLoadText--}
```
public boolean isLoadText()
```


Λαμβάνει μια σημαία που υποδεικνύει ότι η συμβολοσειρά που περνά στο κατασκευαστή του [Comparer](../../com.groupdocs.comparison/comparer) ή στη μέθοδο [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) είναι κείμενο σύγκρισης, όχι διαδρομές αρχείων (Μόνο για σύγκριση κειμένου).


**Returns:**
boolean - true αν η συμβολοσειρά εισόδου είναι κείμενο προς σύγκριση, διαφορετικά false

### setLoadText(boolean value) {#setLoadText-boolean-}
```
public void setLoadText(boolean value)
```


Ορίζει μια σημαία που υποδεικνύει ότι η συμβολοσειρά που περνά στο κατασκευαστή του [Comparer](../../com.groupdocs.comparison/comparer) ή στη μέθοδο [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) είναι κείμενο σύγκρισης, όχι διαδρομές αρχείων (Μόνο για σύγκριση κειμένου).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | boolean | true αν η συμβολοσειρά εισόδου είναι κείμενο προς σύγκριση, διαφορετικά false |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Λαμβάνει έναν κωδικό πρόσβασης που θα χρησιμοποιηθεί για τη φόρτωση ενός εγγράφου.


**Returns:**
java.lang.String - ο κωδικός πρόσβασης για τη φόρτωση του εγγράφου

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Ορίζει έναν κωδικό πρόσβασης που πρέπει να χρησιμοποιηθεί για τη φόρτωση ενός εγγράφου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | java.lang.String | Ο κωδικός πρόσβασης για τη φόρτωση του εγγράφου |
|

### getFontDirectories() {#getFontDirectories--}
```
public List<String> getFontDirectories()
```


Λαμβάνει μια λίστα καταλόγων όπου τοποθετούνται τα αρχεία γραμματοσειρών για τη φόρτωση ενός εγγράφου.


**Returns:**
java.util.List<java.lang.String> - η λίστα των καταλόγων με αρχεία γραμματοσειρών

### setFontDirectories(List<String> value) {#setFontDirectories-java.util.List-java.lang.String--}
```
public void setFontDirectories(List<String> value)
```


Ορίζει μια λίστα καταλόγων όπου τοποθετούνται τα αρχεία γραμματοσειρών για τη φόρτωση ενός εγγράφου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | java.util.List<java.lang.String> | Η λίστα των καταλόγων με αρχεία γραμματοσειρών |
|

### getFileType() {#getFileType--}
```
public FileType getFileType()
```


Λαμβάνει τον τύπο ενός αρχείου που φορτώνεται.


**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the type of the file

### setFileType(FileType value) {#setFileType-com.groupdocs.comparison.result.FileType-}
```
public void setFileType(FileType value)
```


Ορίζει έναν τύπο αρχείου που φορτώνεται.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [FileType](../../com.groupdocs.comparison.result/filetype) | Ο τύπος του αρχείου |
|

