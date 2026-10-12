---
title: "Comparer"
second_title: "GroupDocs.Comparison for Java Αναφορά API"
description: "Η κλάση Comparer παρέχει λειτουργικότητα για τη σύγκριση εγγράφων και τη δημιουργία αποτελεσμάτων σύγκρισης."
type: docs
weight: 10
url: /el/java/com.groupdocs.comparison/comparer/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public class Comparer implements System.IDisposable, Closeable
```

Η κλάση Comparer παρέχει λειτουργικότητα για τη σύγκριση εγγράφων και τη δημιουργία αποτελεσμάτων σύγκρισης.


Σας επιτρέπει να συγκρίνετε διάφορους τύπους εγγράφων, όπως PDF, Word, Excel, PowerPoint και άλλα.


Παράδειγμα χρήσης:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     CompareOptions compareOptions = new CompareOptions();
     compareOptions.setDetectStyleChanges(true);

     comparer.compare(resultFile, compareOptions);
 }
 
````


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [Comparer(String filePath)](#Comparer-java.lang.String-) | Αρχικοποιεί νέο στιγμιότυπο της κλάσης Comparer με τη συγκεκριμένη διαδρομή του πηγαίου αρχείου. |
|
|  | [Comparer(String filePath, CompareOptions compareOptions)](#Comparer-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | Αρχικοποιεί νέο στιγμιότυπο της κλάσης Comparer με τη συγκεκριμένη διαδρομή φακέλου και τις επιλογές σύγκρισης. |
|
|  | [Comparer(Path filePath)](#Comparer-java.nio.file.Path-) | Αρχικοποιεί νέο στιγμιότυπο της κλάσης Comparer με τη συγκεκριμένη διαδρομή του πηγαίου αρχείου. |
|
|  | [Comparer(String filePath, LoadOptions loadOptions)](#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-) | Αρχικοποιεί νέο στιγμιότυπο του Comparer με τη συγκεκριμένη διαδρομή του πηγαίου αρχείου και [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions). |
|
|  | [Comparer(Path filePath, LoadOptions loadOptions)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-) | Αρχικοποιεί νέο στιγμιότυπο του Comparer με τη συγκεκριμένη διαδρομή του πηγαίου αρχείου και [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions). |
|
|  | [Comparer(Path filePath, CompareOptions compareOptions)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | Αρχικοποιεί νέο στιγμιότυπο του Comparer με τη συγκεκριμένη διαδρομή του πηγαίου αρχείου και [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions). |
|
|  | [Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings)](#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-) | Αρχικοποιεί νέο αντικείμενο της κλάσης Comparer με τη συγκεκριμένη διαδρομή αρχείου προέλευσης, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) και [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)](#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-) | Αρχικοποιεί νέο αντικείμενο της κλάσης Comparer με τη συγκεκριμένη διαδρομή αρχείου προέλευσης, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) και [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(String filePath, ComparerSettings settings)](#Comparer-java.lang.String-com.groupdocs.comparison.ComparerSettings-) | Αρχικοποιεί νέο αντικείμενο της κλάσης Comparer με τη συγκεκριμένη διαδρομή αρχείου προέλευσης και [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(Path filePath, ComparerSettings settings)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.ComparerSettings-) | Αρχικοποιεί νέο αντικείμενο της κλάσης Comparer με τη συγκεκριμένη διαδρομή αρχείου προέλευσης και [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-) | Αρχικοποιεί νέο αντικείμενο της κλάσης Comparer με τη συγκεκριμένη διαδρομή αρχείου προέλευσης, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) και [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-) | Αρχικοποιεί νέο αντικείμενο της κλάσης Comparer με τη συγκεκριμένη διαδρομή αρχείου προέλευσης, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) και [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(InputStream document)](#Comparer-java.io.InputStream-) | Αρχικοποιεί νέο αντικείμενο της κλάσης Comparer με το καθορισμένο ρεύμα εγγράφου προέλευσης. |
|
|  | [Comparer(InputStream document, LoadOptions loadOptions)](#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-) | Αρχικοποιεί νέο αντικείμενο της κλάσης Comparer με το καθορισμένο ρεύμα εγγράφου προέλευσης και [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions). |
|
|  | [Comparer(InputStream document, ComparerSettings settings)](#Comparer-java.io.InputStream-com.groupdocs.comparison.ComparerSettings-) | Αρχικοποιεί νέο αντικείμενο της κλάσης Comparer με το καθορισμένο ρεύμα εγγράφου προέλευσης και [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(InputStream document, LoadOptions loadOptions, ComparerSettings settings)](#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-) | Αρχικοποιεί νέο αντικείμενο της κλάσης Comparer με το καθορισμένο ρεύμα εγγράφου, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) και [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(ComparerSettings settings)](#Comparer-com.groupdocs.comparison.ComparerSettings-) | Αρχικοποιεί νέο αντικείμενο της κλάσης Comparer με τα καθορισμένα [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [FILE_PATH](#FILE-PATH) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getSource()](#getSource--) | Αποκτά το έγγραφο προέλευσης που συγκρίνεται. |
|
|  | [getTargets()](#getTargets--) | Λίστα εγγράφων-στόχων για σύγκριση με το αρχείο προέλευσης. |
|
|  | [compare()](#compare--) | Συγκρίνει το καθορισμένο αρχείο με τα έγγραφα-στόχους χωρίς αποθήκευση του αποτελέσματος με τις προεπιλεγμένες επιλογές. |
|
|  | [compare(String filePath)](#compare-java.lang.String-) | Συγκρίνει το καθορισμένο αρχείο με τα έγγραφα-στόχους και δημιουργεί ένα αποτέλεσμα σύγκρισης. |
|
|  | [compare(Path filePath)](#compare-java.nio.file.Path-) | Συγκρίνει το καθορισμένο αρχείο με τα έγγραφα-στόχους και δημιουργεί ένα αποτέλεσμα σύγκρισης. |
|
|  | [compare(OutputStream outputStream)](#compare-java.io.OutputStream-) | Συγκρίνει το καθορισμένο αρχείο με τα έγγραφα-στόχους και γράφει το αποτέλεσμα σύγκρισης στο ρεύμα εξόδου. |
|
|  | [compare(String filePath, CompareOptions compareOptions)](#compare-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | Συγκρίνει το καθορισμένο αρχείο με τα έγγραφα-στόχους και γράφει το αποτέλεσμα σύγκρισης στη δοθείσα διαδρομή αρχείου. |
|
|  | [compare(Path filePath, CompareOptions compareOptions)](#compare-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | Συγκρίνει το καθορισμένο αρχείο με τα έγγραφα-στόχους και γράφει το αποτέλεσμα σύγκρισης στη δοθείσα διαδρομή αρχείου. |
|
|  | [compare(OutputStream stream, CompareOptions compareOptions)](#compare-java.io.OutputStream-com.groupdocs.comparison.options.CompareOptions-) | Συγκρίνει το καθορισμένο αρχείο με τα έγγραφα-στόχους και γράφει το αποτέλεσμα σύγκρισης στο ρεύμα εξόδου. |
|
|  | [compare(SaveOptions saveOptions, CompareOptions compareOptions)](#compare-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | Συγκρίνει το καθορισμένο αρχείο με τα έγγραφα-στόχους χωρίς αποθήκευση του αποτελέσματος. |
|
|  | [compare(String filePath, SaveOptions saveOptions)](#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-) | Συγκρίνει το καθορισμένο αρχείο με τα έγγραφα-στόχους και γράφει το αποτέλεσμα σύγκρισης στη δοθείσα διαδρομή αρχείου. |
|
|  | [compare(Path filePath, SaveOptions saveOptions)](#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-) | Συγκρίνει το καθορισμένο αρχείο με τα έγγραφα-στόχους και γράφει το αποτέλεσμα σύγκρισης στη δοθείσα διαδρομή αρχείου. |
|
|  | [compare(OutputStream stream, SaveOptions saveOptions)](#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-) | Συγκρίνει το καθορισμένο αρχείο με τα έγγραφα-στόχους και γράφει το αποτέλεσμα σύγκρισης στη δοθείσα διαδρομή αρχείου. |
|
|  | [compare(CompareOptions compareOptions)](#compare-com.groupdocs.comparison.options.CompareOptions-) | Συγκρίνει το καθορισμένο αρχείο με τα έγγραφα-στόχους χωρίς αποθήκευση του αποτελέσματος. |
|
|  | [compare(OutputStream outputStream, SaveOptions saveOptions, CompareOptions compareOptions)](#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | Συγκρίνει το καθορισμένο αρχείο με τα έγγραφα-στόχους και γράφει το αποτέλεσμα σύγκρισης στο δοθέν ρεύμα εξόδου. |
|
|  | [compare(String filePath, SaveOptions saveOptions, CompareOptions compareOptions)](#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | Συγκρίνει το καθορισμένο αρχείο με τα έγγραφα-στόχους και γράφει το αποτέλεσμα σύγκρισης στη δοθείσα διαδρομή αρχείου. |
|
|  | [compareDirectory(String filePath, CompareOptions compareOptions)](#compareDirectory-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | Συγκρίνει τον καθορισμένο φάκελο με το φάκελο-στόχο και αποθηκεύει το αποτέλεσμα σύγκρισης στη δοθείσα διαδρομή αρχείου. |
|
|  | [compareDirectory(Path filePath, CompareOptions compareOptions)](#compareDirectory-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | Συγκρίνει τον καθορισμένο φάκελο με το φάκελο-στόχο και αποθηκεύει το αποτέλεσμα σύγκρισης στη δοθείσα διαδρομή αρχείου. |
|
|  | [compare(Path filePath, SaveOptions saveOptions, CompareOptions compareOptions)](#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | Συγκρίνει το καθορισμένο αρχείο με τα έγγραφα-στόχους και γράφει το αποτέλεσμα σύγκρισης στη δοθείσα διαδρομή αρχείου. |
|
|  | [add(String filePath)](#add-java.lang.String-) | Προσθέτει το καθορισμένο έγγραφο-στόχο στη διαδικασία σύγκρισης. |
|
|  | [add(String filePath, CompareOptions compareOptions)](#add-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | Προσθέτει το καθορισμένο έγγραφο-στόχο ή φάκελο στη διαδικασία σύγκρισης. |
|
|  | [add(Path filePath)](#add-java.nio.file.Path-) | Προσθέτει το καθορισμένο έγγραφο-στόχο στη διαδικασία σύγκρισης. |
|
|  | [add(String[] filePaths)](#add-java.lang.String...-) | Προσθέτει τα καθορισμένα έγγραφα-στόχους στη διαδικασία σύγκρισης. |
|
|  | [add(Path[] filePaths)](#add-java.nio.file.Path...-) | Προσθέτει τα καθορισμένα έγγραφα-στόχους στη διαδικασία σύγκρισης. |
|
|  | [add(String filePath, LoadOptions loadOptions)](#add-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-) | Προσθέτει το καθορισμένο έγγραφο-στόχο στη διαδικασία σύγκρισης με τις καθορισμένες επιλογές φόρτωσης. |
|
|  | [add(Path filePath, LoadOptions loadOptions)](#add-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-) | Προσθέτει το καθορισμένο έγγραφο-στόχο στη διαδικασία σύγκρισης με τις καθορισμένες επιλογές φόρτωσης. |
|
|  | [add(Path filePath, CompareOptions compareOptions)](#add-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | Προσθέτει το καθορισμένο έγγραφο-στόχο στη διαδικασία σύγκρισης με τις καθορισμένες επιλογές φόρτωσης. |
|
|  | [add(InputStream document)](#add-java.io.InputStream-) | Προσθέτει το καθορισμένο έγγραφο-στόχο στη διαδικασία σύγκρισης. |
|
|  | [add(InputStream[] documents)](#add-java.io.InputStream...-) | Προσθέτει τα καθορισμένα έγγραφα-στόχους στη διαδικασία σύγκρισης. |
|
|  | [add(InputStream document, LoadOptions loadOptions)](#add-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-) | Προσθέτει το καθορισμένο έγγραφο-στόχο στη διαδικασία σύγκρισης με τις καθορισμένες επιλογές φόρτωσης. |
|
|  | [getChanges()](#getChanges--) | Ανακτά έναν πίνακα αντικειμένων [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) που αντιπροσωπεύουν τις αλλαγές που εντοπίστηκαν κατά τη διαδικασία σύγκρισης. |
|
|  | [getChanges(GetChangeOptions getChangeOptions)](#getChanges-com.groupdocs.comparison.options.GetChangeOptions-) | Ανακτά έναν πίνακα αντικειμένων [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) που αντιπροσωπεύουν τις αλλαγές που εντοπίστηκαν κατά τη διαδικασία σύγκρισης. |
|
|  | [applyChanges(String filePath, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.lang.String-com.groupdocs.comparison.options.ApplyChangeOptions-) | Αποδέχεται ή απορρίπτει αλλαγές και τις εφαρμόζει στο έγγραφο αποτελέσματος. |
|
|  | [applyChanges(Path filePath, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.ApplyChangeOptions-) | Αποδέχεται ή απορρίπτει αλλαγές και τις εφαρμόζει στο τελικό έγγραφο. |
|
|  | [applyChanges(OutputStream document, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.ApplyChangeOptions-) | Αποδέχεται ή απορρίπτει αλλαγές και τις εφαρμόζει στο τελικό έγγραφο. |
|
|  | [applyChanges(String filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-) | Αποδέχεται ή απορρίπτει αλλαγές και τις εφαρμόζει στο τελικό έγγραφο. |
|
|  | [applyChanges(Path filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-) | Αποδέχεται ή απορρίπτει αλλαγές και τις εφαρμόζει στο τελικό έγγραφο. |
|
|  | [applyChanges(OutputStream document, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-) | Αποδέχεται ή απορρίπτει αλλαγές και τις εφαρμόζει στο τελικό έγγραφο. |
|
|  | [getResultString()](#getResultString--) | Αποκτά τη συμβολοσειρά αποτελέσματος μετά τη σύγκριση (μόνο για σύγκριση κειμένου). |
|
|  | [getSourceFolder()](#getSourceFolder--) | Επιστρέφει το φάκελο προέλευσης που συγκρίνεται. |
|
|  | [getTargetFolder()](#getTargetFolder--) | Επιστρέφει το φάκελο προορισμού που συγκρίνεται. |
|
|  | [selfComparisonCheck(Document source, Document target)](#selfComparisonCheck-com.groupdocs.comparison.Document-com.groupdocs.comparison.Document-) | Έλεγχος αυτοσύγκρισης (e498c23). |
|
|  | [close()](#close--) | Απελευθερώνει πόρους. |
|
### Comparer(String filePath) {#Comparer-java.lang.String-}
```
public Comparer(String filePath)
```


Αρχικοποιεί νέο στιγμιότυπο της κλάσης Comparer με τη συγκεκριμένη διαδρομή του πηγαίου αρχείου.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Η διαδρομή προς το αρχικό έγγραφο |
|

### Comparer(String filePath, CompareOptions compareOptions) {#Comparer-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(String filePath, CompareOptions compareOptions)
```


Αρχικοποιεί νέο στιγμιότυπο της κλάσης Comparer με τη συγκεκριμένη διαδρομή φακέλου και τις επιλογές σύγκρισης.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Η διαδρομή προς το αρχικό έγγραφο ή φάκελο |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Οι επιλογές σύγκρισης για τη σύγκριση φακέλων |
|

### Comparer(Path filePath) {#Comparer-java.nio.file.Path-}
```
public Comparer(Path filePath)
```


Αρχικοποιεί νέο στιγμιότυπο της κλάσης Comparer με τη συγκεκριμένη διαδρομή του πηγαίου αρχείου.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Η διαδρομή προς το αρχικό έγγραφο |
|

### Comparer(String filePath, LoadOptions loadOptions) {#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Comparer(String filePath, LoadOptions loadOptions)
```


Αρχικοποιεί νέο στιγμιότυπο του Comparer με τη συγκεκριμένη διαδρομή του πηγαίου αρχείου και [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Η διαδρομή προς το αρχικό έγγραφο |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Οι προσαρμοσμένες επιλογές φόρτωσης που θα εφαρμοστούν στο έγγραφο |
|

### Comparer(Path filePath, LoadOptions loadOptions) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Comparer(Path filePath, LoadOptions loadOptions)
```


Αρχικοποιεί νέο στιγμιότυπο του Comparer με τη συγκεκριμένη διαδρομή του πηγαίου αρχείου και [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Η διαδρομή προς το αρχικό έγγραφο |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Οι προσαρμοσμένες επιλογές φόρτωσης που θα εφαρμοστούν στο έγγραφο |
|

### Comparer(Path filePath, CompareOptions compareOptions) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(Path filePath, CompareOptions compareOptions)
```


Αρχικοποιεί νέο στιγμιότυπο του Comparer με τη συγκεκριμένη διαδρομή του πηγαίου αρχείου και [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Η διαδρομή προς το αρχικό έγγραφο |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Οι επιλογές σύγκρισης για τη σύγκριση φακέλων |
|

### Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings) {#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings)
```


Αρχικοποιεί νέο αντικείμενο της κλάσης Comparer με τη συγκεκριμένη διαδρομή αρχείου προέλευσης, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) και [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Η διαδρομή προς το αρχικό έγγραφο |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Οι προσαρμοσμένες επιλογές φόρτωσης που θα εφαρμοστούν στο έγγραφο |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Οι ρυθμίσεις συγκριτή που θα χρησιμοποιηθούν για τη διαδικασία σύγκρισης |
|

### Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions) {#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)
```


Αρχικοποιεί νέο αντικείμενο της κλάσης Comparer με τη συγκεκριμένη διαδρομή αρχείου προέλευσης, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) και [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Η διαδρομή προς το αρχικό έγγραφο ή φάκελο ή κείμενο προς σύγκριση |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Οι προσαρμοσμένες επιλογές φόρτωσης που θα εφαρμοστούν στο έγγραφο |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Οι ρυθμίσεις συγκριτή που θα χρησιμοποιηθούν για τη διαδικασία σύγκρισης |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Οι επιλογές σύγκρισης για τη σύγκριση φακέλων |
|

### Comparer(String filePath, ComparerSettings settings) {#Comparer-java.lang.String-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(String filePath, ComparerSettings settings)
```


Αρχικοποιεί νέο αντικείμενο της κλάσης Comparer με τη συγκεκριμένη διαδρομή αρχείου προέλευσης και [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Η διαδρομή προς το αρχικό έγγραφο |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Οι ρυθμίσεις συγκριτή που θα χρησιμοποιηθούν για τη διαδικασία σύγκρισης |
|

### Comparer(Path filePath, ComparerSettings settings) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(Path filePath, ComparerSettings settings)
```


Αρχικοποιεί νέο αντικείμενο της κλάσης Comparer με τη συγκεκριμένη διαδρομή αρχείου προέλευσης και [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Η διαδρομή προς το αρχικό έγγραφο |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Οι ρυθμίσεις συγκριτή που θα χρησιμοποιηθούν για τη διαδικασία σύγκρισης |
|

### Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings)
```


Αρχικοποιεί νέο αντικείμενο της κλάσης Comparer με τη συγκεκριμένη διαδρομή αρχείου προέλευσης, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) και [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Η διαδρομή προς το αρχικό έγγραφο |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Οι προσαρμοσμένες επιλογές φόρτωσης που θα εφαρμοστούν στο έγγραφο |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Οι ρυθμίσεις συγκριτή που θα χρησιμοποιηθούν για τη διαδικασία σύγκρισης |
|

### Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)
```


Αρχικοποιεί νέο αντικείμενο της κλάσης Comparer με τη συγκεκριμένη διαδρομή αρχείου προέλευσης, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) και [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Η διαδρομή προς το αρχικό έγγραφο ή φάκελο |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Οι προσαρμοσμένες επιλογές φόρτωσης που θα εφαρμοστούν στο έγγραφο |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Οι ρυθμίσεις συγκριτή που θα χρησιμοποιηθούν για τη διαδικασία σύγκρισης |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Οι επιλογές σύγκρισης για τη σύγκριση φακέλων |
|

### Comparer(InputStream document) {#Comparer-java.io.InputStream-}
```
public Comparer(InputStream document)
```


Αρχικοποιεί νέο αντικείμενο της κλάσης Comparer με το καθορισμένο ρεύμα εγγράφου προέλευσης.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | έγγραφο | java.io.InputStream | Η ροή εισόδου του αρχικού εγγράφου |
|

### Comparer(InputStream document, LoadOptions loadOptions) {#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Comparer(InputStream document, LoadOptions loadOptions)
```


Αρχικοποιεί νέο αντικείμενο της κλάσης Comparer με το καθορισμένο ρεύμα εγγράφου προέλευσης και [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | έγγραφο | java.io.InputStream | Η ροή εισόδου του αρχικού εγγράφου |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Οι προσαρμοσμένες επιλογές φόρτωσης που θα εφαρμοστούν στο έγγραφο |
|

### Comparer(InputStream document, ComparerSettings settings) {#Comparer-java.io.InputStream-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(InputStream document, ComparerSettings settings)
```


Αρχικοποιεί νέο αντικείμενο της κλάσης Comparer με το καθορισμένο ρεύμα εγγράφου προέλευσης και [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | έγγραφο | java.io.InputStream | Η ροή εισόδου του αρχικού εγγράφου |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Οι ρυθμίσεις συγκριτή που θα χρησιμοποιηθούν για τη διαδικασία σύγκρισης |
|

### Comparer(InputStream document, LoadOptions loadOptions, ComparerSettings settings) {#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(InputStream document, LoadOptions loadOptions, ComparerSettings settings)
```


Αρχικοποιεί νέο αντικείμενο της κλάσης Comparer με το καθορισμένο ρεύμα εγγράφου, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) και [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | έγγραφο | java.io.InputStream | Η ροή με δεδομένα ενός εγγράφου προς σύγκριση |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Οι προσαρμοσμένες επιλογές φόρτωσης που θα εφαρμοστούν στο έγγραφο |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Οι ρυθμίσεις συγκριτή που θα χρησιμοποιηθούν για τη διαδικασία σύγκρισης |
|

### Comparer(ComparerSettings settings) {#Comparer-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(ComparerSettings settings)
```


Αρχικοποιεί νέο αντικείμενο της κλάσης Comparer με τα καθορισμένα [ComparerSettings](../../com.groupdocs.comparison/comparersettings).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | οι ρυθμίσεις |
|

### FILE_PATH {#FILE-PATH}
```
public static final String FILE_PATH
```


### getSource() {#getSource--}
```
public final Document getSource()
```


Αποκτά το έγγραφο προέλευσης που συγκρίνεται.


**Returns:**
[Document](../../com.groupdocs.comparison/document) - the source document

### getTargets() {#getTargets--}
```
public final List<Document> getTargets()
```


Λίστα εγγράφων-στόχων για σύγκριση με το αρχείο προέλευσης.


**Returns:**
java.util.List<com.groupdocs.comparison.Document> - τα έγγραφα προορισμού

### compare() {#compare--}
```
public final Path compare()
```


Συγκρίνει το καθορισμένο αρχείο με τα έγγραφα-στόχους χωρίς αποθήκευση του αποτελέσματος με τις προεπιλεγμένες επιλογές.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Returns:**
java.nio.file.Path - η διαδρομή του τελικού εγγράφου ή null

### compare(String filePath) {#compare-java.lang.String-}
```
public final Path compare(String filePath)
```


Συγκρίνει το καθορισμένο αρχείο με τα έγγραφα-στόχους και δημιουργεί ένα αποτέλεσμα σύγκρισης.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Διαδρομή τελικού εγγράφου |
|

**Returns:**
java.nio.file.Path - διαδρομή αρχείου αποτελέσματος ή null. Σε ορισμένες περιπτώσεις η επέκτασή του μπορεί να αλλάξει

### compare(Path filePath) {#compare-java.nio.file.Path-}
```
public final Path compare(Path filePath)
```


Συγκρίνει το καθορισμένο αρχείο με τα έγγραφα-στόχους και δημιουργεί ένα αποτέλεσμα σύγκρισης.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Διαδρομή τελικού εγγράφου |
|

**Returns:**
java.nio.file.Path - διαδρομή αρχείου αποτελέσματος, σε ορισμένες περιπτώσεις η επέκτασή του μπορεί να αλλάξει

### compare(OutputStream outputStream) {#compare-java.io.OutputStream-}
```
public final Path compare(OutputStream outputStream)
```


Συγκρίνει το καθορισμένο αρχείο με τα έγγραφα-στόχους και γράφει το αποτέλεσμα σύγκρισης στο ρεύμα εξόδου.


Σημείωση: Σε περιπτώσεις που η τιμή επιστροφής είναι null, χρησιμοποιήστε τα δεδομένα που γράφτηκαν στο outputStream

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | outputStream | java.io.OutputStream | Ροή τελικού εγγράφου |
|

**Returns:**
java.nio.file.Path - διαδρομή αρχείου αποτελέσματος ή null όταν πρέπει να χρησιμοποιηθούν τα δεδομένα από το outputStream. Σε ορισμένες περιπτώσεις η επέκταση του αρχείου αποτελέσματος μπορεί να αλλάξει

### compare(String filePath, CompareOptions compareOptions) {#compare-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(String filePath, CompareOptions compareOptions)
```


Συγκρίνει το καθορισμένο αρχείο με τα έγγραφα-στόχους και γράφει το αποτέλεσμα σύγκρισης στη δοθείσα διαδρομή αρχείου.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Διαδρομή αρχείου τελικού εγγράφου |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Οι επιλογές σύγκρισης που θα χρησιμοποιηθούν για τη διαδικασία σύγκρισης |
|

**Returns:**
java.nio.file.Path - διαδρομή αρχείου αποτελέσματος, σε ορισμένες περιπτώσεις η επέκτασή του μπορεί να αλλάξει

### compare(Path filePath, CompareOptions compareOptions) {#compare-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(Path filePath, CompareOptions compareOptions)
```


Συγκρίνει το καθορισμένο αρχείο με τα έγγραφα-στόχους και γράφει το αποτέλεσμα σύγκρισης στη δοθείσα διαδρομή αρχείου.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Διαδρομή αρχείου τελικού εγγράφου |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Οι επιλογές σύγκρισης που θα χρησιμοποιηθούν για τη διαδικασία σύγκρισης |
|

**Returns:**
java.nio.file.Path - διαδρομή αρχείου αποτελέσματος, σε ορισμένες περιπτώσεις η επέκτασή του μπορεί να αλλάξει

### compare(OutputStream stream, CompareOptions compareOptions) {#compare-java.io.OutputStream-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(OutputStream stream, CompareOptions compareOptions)
```


Συγκρίνει το καθορισμένο αρχείο με τα έγγραφα-στόχους και γράφει το αποτέλεσμα σύγκρισης στο ρεύμα εξόδου.


Σημείωση: Σε περίπτωση που η τιμή επιστροφής είναι null, χρησιμοποιήστε τα δεδομένα που γράφτηκαν στο outputStream.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | ροή | java.io.OutputStream | Ροή τελικού εγγράφου |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Οι επιλογές σύγκρισης που θα χρησιμοποιηθούν για τη διαδικασία σύγκρισης |
|

**Returns:**
java.nio.file.Path - διαδρομή αρχείου αποτελέσματος ή null όταν πρέπει να χρησιμοποιηθούν τα δεδομένα από το outputStream. Σε ορισμένες περιπτώσεις η επέκταση του αρχείου αποτελέσματος μπορεί να αλλάξει

### compare(SaveOptions saveOptions, CompareOptions compareOptions) {#compare-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(SaveOptions saveOptions, CompareOptions compareOptions)
```


Συγκρίνει το καθορισμένο αρχείο με τα έγγραφα-στόχους χωρίς αποθήκευση του αποτελέσματος.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparison options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Επιλογές αποθήκευσης |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Οι επιλογές σύγκρισης που θα χρησιμοποιηθούν για τη διαδικασία σύγκρισης |
|

**Returns:**
java.nio.file.Path - η διαδρομή του τελικού εγγράφου ή null

### compare(String filePath, SaveOptions saveOptions) {#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-}
```
public final Path compare(String filePath, SaveOptions saveOptions)
```


Συγκρίνει το καθορισμένο αρχείο με τα έγγραφα-στόχους και γράφει το αποτέλεσμα σύγκρισης στη δοθείσα διαδρομή αρχείου.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Διαδρομή αρχείου τελικού εγγράφου |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Επιλογές αποθήκευσης |
|

**Returns:**
java.nio.file.Path - διαδρομή αρχείου αποτελέσματος, σε ορισμένες περιπτώσεις η επέκτασή του μπορεί να αλλάξει

### compare(Path filePath, SaveOptions saveOptions) {#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-}
```
public final Path compare(Path filePath, SaveOptions saveOptions)
```


Συγκρίνει το καθορισμένο αρχείο με τα έγγραφα-στόχους και γράφει το αποτέλεσμα σύγκρισης στη δοθείσα διαδρομή αρχείου.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Διαδρομή αρχείου τελικού εγγράφου |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Επιλογές αποθήκευσης |
|

**Returns:**
java.nio.file.Path - διαδρομή αρχείου αποτελέσματος, σε ορισμένες περιπτώσεις η επέκτασή του μπορεί να αλλάξει

### compare(OutputStream stream, SaveOptions saveOptions) {#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-}
```
public final Path compare(OutputStream stream, SaveOptions saveOptions)
```


Συγκρίνει το καθορισμένο αρχείο με τα έγγραφα-στόχους και γράφει το αποτέλεσμα σύγκρισης στη δοθείσα διαδρομή αρχείου.


Σημείωση: Σε περίπτωση που η επιστρεφόμενη τιμή είναι null, χρησιμοποιήστε τα δεδομένα που γράφτηκαν στο outputStream

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | ροή | java.io.OutputStream | Ροή τελικού εγγράφου |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Επιλογές αποθήκευσης |
|

**Returns:**
java.nio.file.Path - διαδρομή αρχείου αποτελέσματος ή null όταν πρέπει να χρησιμοποιηθούν τα δεδομένα από το outputStream. Σε ορισμένες περιπτώσεις η επέκταση του αρχείου αποτελέσματος μπορεί να αλλάξει

### compare(CompareOptions compareOptions) {#compare-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(CompareOptions compareOptions)
```


Συγκρίνει το καθορισμένο αρχείο με τα έγγραφα-στόχους χωρίς αποθήκευση του αποτελέσματος.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Οι επιλογές σύγκρισης που θα χρησιμοποιηθούν για τη διαδικασία σύγκρισης |
|

**Returns:**
java.nio.file.Path - η διαδρομή προς το αρχείο αποτελέσματος ή null

### compare(OutputStream outputStream, SaveOptions saveOptions, CompareOptions compareOptions) {#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(OutputStream outputStream, SaveOptions saveOptions, CompareOptions compareOptions)
```


Συγκρίνει το καθορισμένο αρχείο με τα έγγραφα-στόχους και γράφει το αποτέλεσμα σύγκρισης στο δοθέν ρεύμα εξόδου.


Σημείωση: Σε περίπτωση που η επιστρεφόμενη τιμή είναι null, χρησιμοποιήστε τα δεδομένα που γράφτηκαν στο outputStream

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | outputStream | java.io.OutputStream | Ροή τελικού εγγράφου |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Οι επιλογές αποθήκευσης που θα χρησιμοποιηθούν για την αποθήκευση του τελικού εγγράφου |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Οι επιλογές σύγκρισης που θα χρησιμοποιηθούν για τη διαδικασία σύγκρισης |
|

**Returns:**
java.nio.file.Path - διαδρομή αρχείου αποτελέσματος ή null όταν πρέπει να χρησιμοποιηθούν τα δεδομένα από το outputStream. Σε ορισμένες περιπτώσεις η επέκταση του αρχείου αποτελέσματος μπορεί να αλλάξει

### compare(String filePath, SaveOptions saveOptions, CompareOptions compareOptions) {#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(String filePath, SaveOptions saveOptions, CompareOptions compareOptions)
```


Συγκρίνει το καθορισμένο αρχείο με τα έγγραφα-στόχους και γράφει το αποτέλεσμα σύγκρισης στη δοθείσα διαδρομή αρχείου.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparison options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Διαδρομή αρχείου τελικού εγγράφου |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Οι επιλογές αποθήκευσης που θα χρησιμοποιηθούν για την αποθήκευση του τελικού εγγράφου |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Οι επιλογές σύγκρισης που θα χρησιμοποιηθούν για τη διαδικασία σύγκρισης |
|

**Returns:**
java.nio.file.Path - διαδρομή αρχείου αποτελέσματος, σε ορισμένες περιπτώσεις η επέκτασή του μπορεί να αλλάξει

### compareDirectory(String filePath, CompareOptions compareOptions) {#compareDirectory-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public void compareDirectory(String filePath, CompareOptions compareOptions)
```


Συγκρίνει τον καθορισμένο φάκελο με το φάκελο-στόχο και αποθηκεύει το αποτέλεσμα σύγκρισης στη δοθείσα διαδρομή αρχείου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Η διαδρομή αρχείου όπου θα αποθηκευτεί το αποτέλεσμα της σύγκρισης. |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Οι επιλογές που θα χρησιμοποιηθούν για τη διαδικασία σύγκρισης καταλόγων. |
|

### compareDirectory(Path filePath, CompareOptions compareOptions) {#compareDirectory-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public void compareDirectory(Path filePath, CompareOptions compareOptions)
```


Συγκρίνει τον καθορισμένο φάκελο με το φάκελο-στόχο και αποθηκεύει το αποτέλεσμα σύγκρισης στη δοθείσα διαδρομή αρχείου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Η διαδρομή αρχείου όπου θα αποθηκευτεί το αποτέλεσμα της σύγκρισης. |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Οι επιλογές που θα χρησιμοποιηθούν για τη διαδικασία σύγκρισης καταλόγων. |
|

### compare(Path filePath, SaveOptions saveOptions, CompareOptions compareOptions) {#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(Path filePath, SaveOptions saveOptions, CompareOptions compareOptions)
```


Συγκρίνει το καθορισμένο αρχείο με τα έγγραφα-στόχους και γράφει το αποτέλεσμα σύγκρισης στη δοθείσα διαδρομή αρχείου.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Διαδρομή αρχείου τελικού εγγράφου |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Οι επιλογές αποθήκευσης που θα χρησιμοποιηθούν για την αποθήκευση του τελικού εγγράφου |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Οι επιλογές σύγκρισης που θα χρησιμοποιηθούν για τη διαδικασία σύγκρισης |
|

**Returns:**
java.nio.file.Path - διαδρομή αρχείου αποτελέσματος, σε ορισμένες περιπτώσεις η επέκτασή του μπορεί να αλλάξει

### add(String filePath) {#add-java.lang.String-}
```
public final void add(String filePath)
```


Προσθέτει το καθορισμένο έγγραφο-στόχο στη διαδικασία σύγκρισης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Η διαδρομή προς το έγγραφο προορισμού που θα προστεθεί |
|

### add(String filePath, CompareOptions compareOptions) {#add-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public void add(String filePath, CompareOptions compareOptions)
```


Προσθέτει το καθορισμένο έγγραφο-στόχο ή φάκελο στη διαδικασία σύγκρισης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Η διαδρομή προς το έγγραφο ή φάκελο προορισμού που θα προστεθεί |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Οι επιλογές για τη σύγκριση |
|

### add(Path filePath) {#add-java.nio.file.Path-}
```
public final void add(Path filePath)
```


Προσθέτει το καθορισμένο έγγραφο-στόχο στη διαδικασία σύγκρισης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Η διαδρομή προς το έγγραφο προορισμού που θα προστεθεί |
|

### add(String[] filePaths) {#add-java.lang.String...-}
```
public final void add(String[] filePaths)
```


Προσθέτει τα καθορισμένα έγγραφα-στόχους στη διαδικασία σύγκρισης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePaths | java.lang.String[] | Διαδρομές προς τα έγγραφα προορισμού που θα προστεθούν |
|

### add(Path[] filePaths) {#add-java.nio.file.Path...-}
```
public final void add(Path[] filePaths)
```


Προσθέτει τα καθορισμένα έγγραφα-στόχους στη διαδικασία σύγκρισης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePaths | java.nio.file.Path[] | Διαδρομές προς τα έγγραφα προορισμού που θα προστεθούν |
|

### add(String filePath, LoadOptions loadOptions) {#add-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-}
```
public final void add(String filePath, LoadOptions loadOptions)
```


Προσθέτει το καθορισμένο έγγραφο-στόχο στη διαδικασία σύγκρισης με τις καθορισμένες επιλογές φόρτωσης.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Διαδρομή προς το έγγραφο προορισμού που θα προστεθεί |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Οι προσαρμοσμένες επιλογές φόρτωσης που θα εφαρμοστούν στο έγγραφο |
|

### add(Path filePath, LoadOptions loadOptions) {#add-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-}
```
public final void add(Path filePath, LoadOptions loadOptions)
```


Προσθέτει το καθορισμένο έγγραφο-στόχο στη διαδικασία σύγκρισης με τις καθορισμένες επιλογές φόρτωσης.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Διαδρομή προς το έγγραφο προορισμού που θα προστεθεί |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Οι προσαρμοσμένες επιλογές φόρτωσης που θα εφαρμοστούν στο έγγραφο |
|

### add(Path filePath, CompareOptions compareOptions) {#add-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public final void add(Path filePath, CompareOptions compareOptions)
```


Προσθέτει το καθορισμένο έγγραφο-στόχο στη διαδικασία σύγκρισης με τις καθορισμένες επιλογές φόρτωσης.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Η διαδρομή προς το έγγραφο ή φάκελο προορισμού που θα προστεθεί |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Οι επιλογές για τη σύγκριση |
|

### add(InputStream document) {#add-java.io.InputStream-}
```
public final void add(InputStream document)
```


Προσθέτει το καθορισμένο έγγραφο-στόχο στη διαδικασία σύγκρισης.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | έγγραφο | java.io.InputStream | Η ροή με δεδομένα ενός εγγράφου προς σύγκριση |
|

### add(InputStream[] documents) {#add-java.io.InputStream...-}
```
public final void add(InputStream[] documents)
```


Προσθέτει τα καθορισμένα έγγραφα-στόχους στη διαδικασία σύγκρισης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | documents | java.io.InputStream[] | Ροές με δεδομένα εγγράφων προς σύγκριση |
|

### add(InputStream document, LoadOptions loadOptions) {#add-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-}
```
public final void add(InputStream document, LoadOptions loadOptions)
```


Προσθέτει το καθορισμένο έγγραφο-στόχο στη διαδικασία σύγκρισης με τις καθορισμένες επιλογές φόρτωσης.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | έγγραφο | java.io.InputStream | Η ροή με δεδομένα ενός εγγράφου προς σύγκριση |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Οι προσαρμοσμένες επιλογές φόρτωσης που θα εφαρμοστούν στο έγγραφο |
|

### getChanges() {#getChanges--}
```
public final ChangeInfo[] getChanges()
```


Ανακτά έναν πίνακα αντικειμένων [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) που αντιπροσωπεύουν τις αλλαγές που εντοπίστηκαν κατά τη διαδικασία σύγκρισης.


Χρησιμοποιήστε αυτή τη μέθοδο για να λάβετε λεπτομερείς πληροφορίες σχετικά με τις αλλαγές μεταξύ του πηγαίου εγγράφου και του(των) στόχου(ων) εγγράφου(ων).
Κάθε αντικείμενο [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) περιέχει πληροφορίες όπως ο τύπος της αλλαγής, η επηρεαζόμενη περιοχή,
και το περιεχόμενο πριν και μετά την αλλαγή.

* More about how to obtain collection of detected differences between compared documents in Java: [How to get list of changes between documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Get+list+of+changes)
* More about how to get changes coordinates at pages image preview when comparing documents using GroupDocs.Comparison for Java: [How to get changes coordinates programmatically](../https://docs.groupdocs.com/display/comparisonjava/Get+changes+coordinates)


**Returns:**
com.groupdocs.comparison.result.ChangeInfo[] - ένας πίνακας από αντικείμενα [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) που αντιπροσωπεύουν τις αλλαγές που εντοπίστηκαν κατά τη διαδικασία σύγκρισης

### getChanges(GetChangeOptions getChangeOptions) {#getChanges-com.groupdocs.comparison.options.GetChangeOptions-}
```
public final ChangeInfo[] getChanges(GetChangeOptions getChangeOptions)
```


Ανακτά έναν πίνακα αντικειμένων [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) που αντιπροσωπεύουν τις αλλαγές που εντοπίστηκαν κατά τη διαδικασία σύγκρισης.


Χρησιμοποιήστε αυτή τη μέθοδο για να λάβετε λεπτομερείς πληροφορίες σχετικά με τις αλλαγές μεταξύ του πηγαίου εγγράφου και του(των) στόχου(ων) εγγράφου(ων).
Κάθε αντικείμενο [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) περιέχει πληροφορίες όπως ο τύπος της αλλαγής, η επηρεαζόμενη περιοχή,
και το περιεχόμενο πριν και μετά την αλλαγή.


Η παράμετρος [GetChangeOptions](../../com.groupdocs.comparison.options/getchangeoptions) επιτρέπει το φιλτράρισμα των αλλαγών με διαφορετικό τρόπο.

* More about how to obtain collection of detected differences between compared documents in Java: [How to get list of changes between documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Get+list+of+changes)
* More about how to get changes coordinates at pages image preview when comparing documents using GroupDocs.Comparison for Java: [How to get changes coordinates programmatically](../https://docs.groupdocs.com/display/comparisonjava/Get+changes+coordinates)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | getChangeOptions | [GetChangeOptions](../../com.groupdocs.comparison.options/getchangeoptions) | Το αντικείμενο που επιτρέπει το φιλτράρισμα των αλλαγών |
|

**Returns:**
com.groupdocs.comparison.result.ChangeInfo[] - ένας πίνακας από αντικείμενα [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) που αντιπροσωπεύουν τις αλλαγές που εντοπίστηκαν κατά τη διαδικασία σύγκρισης

### applyChanges(String filePath, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.lang.String-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(String filePath, ApplyChangeOptions applyChangeOptions)
```


Αποδέχεται ή απορρίπτει αλλαγές και τις εφαρμόζει στο έγγραφο αποτελέσματος.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Διαδρομή αρχείου τελικού εγγράφου |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | Οι προσαρμοσμένες επιλογές εφαρμογής αλλαγών για τη διαμόρφωση της διαδικασίας εφαρμογής των αλλαγών |
|

### applyChanges(Path filePath, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(Path filePath, ApplyChangeOptions applyChangeOptions)
```


Αποδέχεται ή απορρίπτει αλλαγές και τις εφαρμόζει στο τελικό έγγραφο.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Διαδρομή αρχείου τελικού εγγράφου |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | Οι προσαρμοσμένες επιλογές εφαρμογής αλλαγών για τη διαμόρφωση της διαδικασίας εφαρμογής των αλλαγών |
|

### applyChanges(OutputStream document, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(OutputStream document, ApplyChangeOptions applyChangeOptions)
```


Αποδέχεται ή απορρίπτει αλλαγές και τις εφαρμόζει στο τελικό έγγραφο.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | έγγραφο | java.io.OutputStream | Ροή εξόδου του εγγράφου αποτελέσματος |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | Οι προσαρμοσμένες επιλογές εφαρμογής αλλαγών για τη διαμόρφωση της διαδικασίας εφαρμογής των αλλαγών |
|

### applyChanges(String filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(String filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)
```


Αποδέχεται ή απορρίπτει αλλαγές και τις εφαρμόζει στο τελικό έγγραφο.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Διαδρομή αρχείου τελικού εγγράφου |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Οι επιλογές αποθήκευσης για τη διαμόρφωση της αποθήκευσης του εγγράφου αποτελέσματος |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | Οι προσαρμοσμένες επιλογές εφαρμογής αλλαγών για τη διαμόρφωση της διαδικασίας εφαρμογής των αλλαγών |
|

### applyChanges(Path filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(Path filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)
```


Αποδέχεται ή απορρίπτει αλλαγές και τις εφαρμόζει στο τελικό έγγραφο.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Διαδρομή αρχείου τελικού εγγράφου |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Οι επιλογές αποθήκευσης για τη διαμόρφωση της αποθήκευσης του εγγράφου αποτελέσματος |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | Οι προσαρμοσμένες επιλογές εφαρμογής αλλαγών για τη διαμόρφωση της διαδικασίας εφαρμογής των αλλαγών |
|

### applyChanges(OutputStream document, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(OutputStream document, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)
```


Αποδέχεται ή απορρίπτει αλλαγές και τις εφαρμόζει στο τελικό έγγραφο.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | έγγραφο | java.io.OutputStream | Ροή εξόδου του εγγράφου αποτελέσματος |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Οι επιλογές αποθήκευσης για τη διαμόρφωση της αποθήκευσης του εγγράφου αποτελέσματος |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | Οι προσαρμοσμένες επιλογές εφαρμογής αλλαγών για τη διαμόρφωση της διαδικασίας εφαρμογής των αλλαγών |
|

### getResultString() {#getResultString--}
```
public String getResultString()
```


Αποκτά τη συμβολοσειρά αποτελέσματος μετά τη σύγκριση (μόνο για σύγκριση κειμένου).


**Returns:**
java.lang.String - η συμβολοσειρά αποτελέσματος

### getSourceFolder() {#getSourceFolder--}
```
public String getSourceFolder()
```


Επιστρέφει το φάκελο προέλευσης που συγκρίνεται.


**Returns:**
java.lang.String - ο φάκελος προέλευσης

### getTargetFolder() {#getTargetFolder--}
```
public String getTargetFolder()
```


Επιστρέφει το φάκελο προορισμού που συγκρίνεται.


**Returns:**
java.lang.String - ο φάκελος προορισμού

### selfComparisonCheck(Document source, Document target) {#selfComparisonCheck-com.groupdocs.comparison.Document-com.groupdocs.comparison.Document-}
```
public static void selfComparisonCheck(Document source, Document target)
```


Έλεγχος αυτο-σύγκρισης (e498c23). C# 7a7668c εσωτερικό· διατηρήθηκε δημόσιο ώστε τα τεστ core.common να μπορούν να το καλέσουν.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| source | [Document](../../com.groupdocs.comparison/document) |  |
| target | [Document](../../com.groupdocs.comparison/document) |  |

### close() {#close--}
```
public void close()
```


Απελευθερώνει πόρους.


