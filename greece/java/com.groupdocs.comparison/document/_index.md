---
title: "Έγγραφο"
second_title: "GroupDocs.Comparison for Java Αναφορά API"
description: "Αντιπροσωπεύει ένα έγγραφο για τη διαδικασία σύγκρισης."
type: docs
weight: 12
url: /el/java/com.groupdocs.comparison/document/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Document implements Closeable
```

Αντιπροσωπεύει ένα έγγραφο για τη διαδικασία σύγκρισης.


Η κλάση Document παρέχει μεθόδους για φόρτωση, δημιουργία εικόνων προεπισκόπησης και διαχείριση εγγράφων κατά τη διαδικασία σύγκρισης.


Παράδειγμα χρήσης:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     try (IDocumentInfo info = comparer.getSource().getDocumentInfo()) {
         System.out.println("File type: " + info.getFileType());
         System.out.println("Number of pages: " + info.getPageCount());
         System.out.println("Document size: " + info.getSize());
     }
 }
 
````


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [Document(InputStream stream)](#Document-java.io.InputStream-) | Αρχικοποιεί νέο αντικείμενο της κλάσης Document με τη συγκεκριμένη ροή εγγράφου. |
|
|  | [Document(String filePath)](#Document-java.lang.String-) | Αρχικοποιεί νέο αντικείμενο της κλάσης Document με τη συγκεκριμένη διαδρομή εγγράφου. |
|
|  | [Document(Path filePath)](#Document-java.nio.file.Path-) | Αρχικοποιεί νέο αντικείμενο της κλάσης Document με τη συγκεκριμένη διαδρομή εγγράφου. |
|
|  | [Document(Path filePath, String password)](#Document-java.nio.file.Path-java.lang.String-) | Αρχικοποιεί νέο αντικείμενο της κλάσης Document με τη συγκεκριμένη διαδρομή εγγράφου και έναν κωδικό πρόσβασης. |
|
|  | [Document(Path filePath, LoadOptions loadOptions)](#Document-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-) | Αρχικοποιεί νέο αντικείμενο της κλάσης Document με τη συγκεκριμένη διαδρομή εγγράφου και επιλογές φόρτωσης. |
|
|  | [Document(String filePath, String password)](#Document-java.lang.String-java.lang.String-) | Αρχικοποιεί νέο αντικείμενο της κλάσης Document με τη συγκεκριμένη διαδρομή εγγράφου και έναν κωδικό πρόσβασης. |
|
|  | [Document(String filePath, LoadOptions loadOptions)](#Document-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-) | Αρχικοποιεί νέο αντικείμενο της κλάσης Document με τη συγκεκριμένη διαδρομή εγγράφου και επιλογές φόρτωσης. |
|
|  | [Document(InputStream stream, String password)](#Document-java.io.InputStream-java.lang.String-) | Αρχικοποιεί νέο αντικείμενο της κλάσης Document με τη συγκεκριμένη ροή εγγράφου και έναν κωδικό πρόσβασης. |
|
|  | [Document(String filePathOrTextContent, boolean isLoadText)](#Document-java.lang.String-boolean-) | Αρχικοποιεί νέο αντικείμενο της κλάσης Document με τη συγκεκριμένη διαδρομή εγγράφου ή το κείμενο περιεχομένου και μια σημαία που υποδεικνύει τι παραδόθηκε. |
|
|  | [Document(InputStream inputStream, LoadOptions loadOptions)](#Document-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-) | Αρχικοποιεί νέο αντικείμενο της κλάσης Document με τη συγκεκριμένη ροή εγγράφου και επιλογές φόρτωσης. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getChanges()](#getChanges--) | Λαμβάνει μια λίστα αντικειμένων [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) που αντιπροσωπεύουν τις αλλαγές που εντοπίστηκαν κατά τη διαδικασία σύγκρισης. |
|
|  | [setChanges(List<ChangeInfo> value)](#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--) | Ορίζει μια λίστα αντικειμένων [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) που αντιπροσωπεύουν τις αλλαγές που εντοπίστηκαν κατά τη διαδικασία σύγκρισης. |
|
|  | [getName()](#getName--) | Λαμβάνει το όνομα του εγγράφου. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Ορίζει το όνομα του εγγράφου. |
|
|  | [getFileType()](#getFileType--) | Λαμβάνει τον τύπο του εγγράφου. |
|
|  | [setFileType(FileType fileType)](#setFileType-com.groupdocs.comparison.result.FileType-) | Ορίζει τον τύπο του εγγράφου. |
|
|  | [createStream()](#createStream--) | Δημιουργεί νέα ροή με το περιεχόμενο του εγγράφου. |
|
|  | [getStreamLength()](#getStreamLength--) | Λαμβάνει το μέγεθος του εγγράφου |
|
|  | [getPassword()](#getPassword--) | Λαμβάνει τον κωδικό πρόσβασης του εγγράφου |
|
|  | [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.comparison.options.PreviewOptions-) | Δημιουργεί προεπισκοπήσεις εγγράφου με βάση τις παρεχόμενες [PreviewOptions](../../com.groupdocs.comparison.options/previewoptions). |
|
|  | [getDocumentInfo()](#getDocumentInfo--) | Λαμβάνει πληροφορίες για το έγγραφο, συμπεριλαμβανομένου του τύπου εγγράφου, του αριθμού σελίδων, των μεγεθών σελίδων και άλλων. |
|
| [close()](#close--) |  |
### Document(InputStream stream) {#Document-java.io.InputStream-}
```
public Document(InputStream stream)
```


Αρχικοποιεί νέο αντικείμενο της κλάσης Document με τη συγκεκριμένη ροή εγγράφου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | ροή | java.io.InputStream | Ροή εγγράφου |
|

### Document(String filePath) {#Document-java.lang.String-}
```
public Document(String filePath)
```


Αρχικοποιεί νέο αντικείμενο της κλάσης Document με τη συγκεκριμένη διαδρομή εγγράφου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Διαδρομή εγγράφου |
|

### Document(Path filePath) {#Document-java.nio.file.Path-}
```
public Document(Path filePath)
```


Αρχικοποιεί νέο αντικείμενο της κλάσης Document με τη συγκεκριμένη διαδρομή εγγράφου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Διαδρομή εγγράφου |
|

### Document(Path filePath, String password) {#Document-java.nio.file.Path-java.lang.String-}
```
public Document(Path filePath, String password)
```


Αρχικοποιεί νέο αντικείμενο της κλάσης Document με τη συγκεκριμένη διαδρομή εγγράφου και έναν κωδικό πρόσβασης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Διαδρομή εγγράφου |
|
|  | κωδικός πρόσβασης | java.lang.String | Κωδικός πρόσβασης εγγράφου |
|

### Document(Path filePath, LoadOptions loadOptions) {#Document-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Document(Path filePath, LoadOptions loadOptions)
```


Αρχικοποιεί νέο αντικείμενο της κλάσης Document με τη συγκεκριμένη διαδρομή εγγράφου και επιλογές φόρτωσης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Διαδρομή εγγράφου |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Επιλογές φόρτωσης |
|

### Document(String filePath, String password) {#Document-java.lang.String-java.lang.String-}
```
public Document(String filePath, String password)
```


Αρχικοποιεί νέο αντικείμενο της κλάσης Document με τη συγκεκριμένη διαδρομή εγγράφου και έναν κωδικό πρόσβασης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Διαδρομή εγγράφου |
|
|  | κωδικός πρόσβασης | java.lang.String | Κωδικός πρόσβασης εγγράφου |
|

### Document(String filePath, LoadOptions loadOptions) {#Document-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Document(String filePath, LoadOptions loadOptions)
```


Αρχικοποιεί νέο αντικείμενο της κλάσης Document με τη συγκεκριμένη διαδρομή εγγράφου και επιλογές φόρτωσης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Διαδρομή εγγράφου |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Επιλογές φόρτωσης |
|

### Document(InputStream stream, String password) {#Document-java.io.InputStream-java.lang.String-}
```
public Document(InputStream stream, String password)
```


Αρχικοποιεί νέο αντικείμενο της κλάσης Document με τη συγκεκριμένη ροή εγγράφου και έναν κωδικό πρόσβασης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | ροή | java.io.InputStream | Ροή εγγράφου |
|
|  | κωδικός πρόσβασης | java.lang.String | Κωδικός πρόσβασης εγγράφου |
|

### Document(String filePathOrTextContent, boolean isLoadText) {#Document-java.lang.String-boolean-}
```
public Document(String filePathOrTextContent, boolean isLoadText)
```


Αρχικοποιεί νέο αντικείμενο της κλάσης Document με τη συγκεκριμένη διαδρομή εγγράφου ή το κείμενο περιεχομένου και μια σημαία που υποδεικνύει τι παραδόθηκε.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePathOrTextContent | java.lang.String | η διαδρομή του αρχείου |
|
|  | isLoadText | boolean | το is load text |
|

### Document(InputStream inputStream, LoadOptions loadOptions) {#Document-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Document(InputStream inputStream, LoadOptions loadOptions)
```


Αρχικοποιεί νέο αντικείμενο της κλάσης Document με τη συγκεκριμένη ροή εγγράφου και επιλογές φόρτωσης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | inputStream | java.io.InputStream | Ροή εγγράφου |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Επιλογές φόρτωσης |
|

### getChanges() {#getChanges--}
```
public final List<ChangeInfo> getChanges()
```


Λαμβάνει μια λίστα αντικειμένων [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) που αντιπροσωπεύουν τις αλλαγές που εντοπίστηκαν κατά τη διαδικασία σύγκρισης.


Χρησιμοποιήστε αυτή τη μέθοδο για να λάβετε λεπτομερείς πληροφορίες σχετικά με τις αλλαγές μεταξύ του πηγαίου εγγράφου και του(των) στόχου(ων) εγγράφου(ων).
Κάθε αντικείμενο [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) περιέχει πληροφορίες όπως ο τύπος της αλλαγής, η επηρεαζόμενη περιοχή,
και το περιεχόμενο πριν και μετά την αλλαγή.


**Returns:**
java.util.List<com.groupdocs.comparison.result.ChangeInfo> - μια λίστα από αντικείμενα [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) που αντιπροσωπεύουν τις αλλαγές που εντοπίστηκαν κατά τη διαδικασία σύγκρισης

### setChanges(List<ChangeInfo> value) {#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--}
```
public final void setChanges(List<ChangeInfo> value)
```


Ορίζει μια λίστα αντικειμένων [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) που αντιπροσωπεύουν τις αλλαγές που εντοπίστηκαν κατά τη διαδικασία σύγκρισης.


Χρησιμοποιήστε αυτή τη μέθοδο για να λάβετε λεπτομερείς πληροφορίες σχετικά με τις αλλαγές μεταξύ του πηγαίου εγγράφου και του(των) στόχου(ων) εγγράφου(ων).
Κάθε αντικείμενο [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) περιέχει πληροφορίες όπως ο τύπος της αλλαγής, η επηρεαζόμενη περιοχή,
και το περιεχόμενο πριν και μετά την αλλαγή.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | java.util.List<com.groupdocs.comparison.result.ChangeInfo> | μια λίστα από αντικείμενα [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) που αντιπροσωπεύουν τις αλλαγές που εντοπίστηκαν κατά τη διαδικασία σύγκρισης |
|

### getName() {#getName--}
```
public final String getName()
```


Λαμβάνει το όνομα του εγγράφου.


**Returns:**
java.lang.String - το όνομα του εγγράφου

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Ορίζει το όνομα του εγγράφου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | java.lang.String | το όνομα του εγγράφου |
|

### getFileType() {#getFileType--}
```
public FileType getFileType()
```


Λαμβάνει τον τύπο του εγγράφου.


**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the type of the document

### setFileType(FileType fileType) {#setFileType-com.groupdocs.comparison.result.FileType-}
```
public void setFileType(FileType fileType)
```


Ορίζει τον τύπο του εγγράφου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.comparison.result/filetype) | ο τύπος του εγγράφου |
|

### createStream() {#createStream--}
```
public InputStream createStream()
```


Δημιουργεί νέα ροή με το περιεχόμενο του εγγράφου.


**Returns:**
java.io.InputStream - η ροή με το περιεχόμενο του εγγράφου

### getStreamLength() {#getStreamLength--}
```
public long getStreamLength()
```


Λαμβάνει το μέγεθος του εγγράφου


**Returns:**
long - το μέγεθος του εγγράφου

### getPassword() {#getPassword--}
```
public String getPassword()
```


Λαμβάνει τον κωδικό πρόσβασης του εγγράφου


**Returns:**
java.lang.String - ο κωδικός πρόσβασης του εγγράφου

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.comparison.options.PreviewOptions-}
```
public final void generatePreview(PreviewOptions previewOptions)
```


Δημιουργεί προεπισκοπήσεις εγγράφου με βάση τις παρεχόμενες [PreviewOptions](../../com.groupdocs.comparison.options/previewoptions).


Αυτή η μέθοδος δημιουργεί προεπισκοπήσεις των σελίδων του εγγράφου σύμφωνα με τις καθορισμένες επιλογές, όπως η μορφή προεπισκόπησης,
αριθμοί σελίδων και παροχέας ροής εξόδου. Οι δημιουργημένες προεπισκοπήσεις μπορούν να αποθηκευτούν ή να υποβληθούν σε περαιτέρω επεξεργασία όπως απαιτείται.

* Learn more about how to generate previews for document pages: [How to generate document pages preview using GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Generate+document+pages+preview)


Παράδειγμα χρήσης:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     PreviewOptions previewOptions = new PreviewOptions(
             pageNumber -> Files.newOutputStream(Paths.get("preview-image-page-" + pageNumber + ".png"))
     );
     previewOptions.setPreviewFormat(PreviewFormats.PNG);
     previewOptions.setPageNumbers(new int[]{1, 2});
     comparer.getSource().generatePreview(previewOptions);
 }
 
````



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | previewOptions | [PreviewOptions](../../com.groupdocs.comparison.options/previewoptions) | Οι επιλογές προεπισκόπησης που καθορίζουν τη μορφή, τους αριθμούς σελίδων κ.λπ. |
|

### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Λαμβάνει πληροφορίες για το έγγραφο, συμπεριλαμβανομένου του τύπου εγγράφου, του αριθμού σελίδων, των μεγεθών σελίδων και άλλων.

* Learn more about document file type, page count, size, and other format-specific properties: [How to get document info using GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Get+file+info)


**Returns:**
[IDocumentInfo](../../com.groupdocs.comparison.interfaces/idocumentinfo) - the document information

### close() {#close--}
```
public void close()
```




