---
title: "CompareOptions"
second_title: "GroupDocs.Comparison for Java Αναφορά API"
description: "Επιτρέπει τη διαμόρφωση της διαδικασίας σύγκρισης εγγράφων."
type: docs
weight: 11
url: /el/java/com.groupdocs.comparison.options/compareoptions/
---
**Inheritance:**
java.lang.Object
```
public class CompareOptions
```

Επιτρέπει τη διαμόρφωση της διαδικασίας σύγκρισης εγγράφων.


Παράδειγμα χρήσης:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     final StyleSettings styleSettings = new StyleSettings();
     styleSettings.setHighlightColor(Color.RED);
     styleSettings.setFontColor(Color.GREEN);
     styleSettings.setUnderline(true);

     CompareOptions compareOptions = new CompareOptions();
     compareOptions.setInsertedItemStyle(styleSettings);

     comparer.compare(resultFile, compareOptions);
 }
 
````


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [CompareOptions()](#CompareOptions--) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης CompareOptions. |
|
|  | [CompareOptions(StyleSettings insertedItemStyle, StyleSettings deletedItemStyle, StyleSettings changedItemStyle)](#CompareOptions-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης CompareOptions με ρυθμίσεις για διαφορετικά στυλ. |
|
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [ignoreChangeSettings](#ignoreChangeSettings) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getIgnoreChangeSettings()](#getIgnoreChangeSettings--) | Λάβετε τις ρυθμίσεις για την αγνόηση αλλαγών βάσει ομοιότητας. |
|
|  | [setIgnoreChangeSettings(IgnoreChangeSensitivitySettings ignoreChangeSettings)](#setIgnoreChangeSettings-com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings-) | Ορίζει τις ρυθμίσεις για την αγνόηση αλλαγών βάσει ομοιότητας. |
|
|  | [getUserMasterPath()](#getUserMasterPath--) | Λαμβάνει τη διαδρομή προς το πρότυπο του χρήστη για Διαγράμματα. |
|
|  | [setUserMasterPath(String userMasterPath)](#setUserMasterPath-java.lang.String-) | Ορίζει τη διαδρομή προς το πρότυπο του χρήστη για Διαγράμματα. |
|
|  | [getComparisonType()](#getComparisonType--) | Λαμβάνει έναν τύπο πηγής και στόχου εγγράφων ως αντικείμενο [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) ώστε η Comparison να γνωρίζει πώς να τα συγκρίνει. |
|
|  | [setComparisonType(ComparisonType comparisonType)](#setComparisonType-com.groupdocs.comparison.options.enums.ComparisonType-) | Ορίζει έναν τύπο πηγής και στόχου εγγράφων ως αντικείμενο [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) ώστε η Comparison να γνωρίζει πώς να τα συγκρίνει. |
|
|  | [getPaperSize()](#getPaperSize--) | Λαμβάνει το μέγεθος του χαρτιού στο τελικό έγγραφο ως αντικείμενο [PaperSize](../../com.groupdocs.comparison.options.enums/papersize) object. |
|
|  | [setPaperSize(PaperSize value)](#setPaperSize-com.groupdocs.comparison.options.enums.PaperSize-) | Ορίζει το μέγεθος του χαρτιού στο τελικό έγγραφο ως αντικείμενο [PaperSize](../../com.groupdocs.comparison.options.enums/papersize) object. |
|
|  | [getCalculateCoordinatesMode()](#getCalculateCoordinatesMode--) | Λαμβάνει τη λειτουργία υπολογισμού συντεταγμένων ως αντικείμενο [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) object. |
|
|  | [setCalculateCoordinatesMode(CalculateCoordinatesModeEnumeration calculateCoordinatesMode)](#setCalculateCoordinatesMode-com.groupdocs.comparison.options.enums.CalculateCoordinatesModeEnumeration-) | Ορίζει τη λειτουργία υπολογισμού συντεταγμένων ως αντικείμενο [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) object. |
|
|  | [isShowDeletedContent()](#isShowDeletedContent--) | Λαμβάνει μια σημαία που υποδεικνύει εάν θα εμφανίζονται διαγραμμένα στοιχεία στο τελικό έγγραφο ή όχι. |
|
|  | [setShowDeletedContent(boolean value)](#setShowDeletedContent-boolean-) | Ορίζει μια σημαία που υποδεικνύει εάν θα εμφανίζονται διαγραμμένα στοιχεία στο τελικό έγγραφο ή όχι. |
|
|  | [isShowInsertedContent()](#isShowInsertedContent--) | Λαμβάνει μια σημαία που υποδεικνύει εάν θα εμφανίζονται τα εισαχθέντα στοιχεία στο τελικό έγγραφο ή όχι. |
|
|  | [setShowInsertedContent(boolean value)](#setShowInsertedContent-boolean-) | Ορίζει μια σημαία που υποδεικνύει εάν θα εμφανίζονται τα εισαχθέντα στοιχεία στο τελικό έγγραφο ή όχι. |
|
|  | [isGenerateSummaryPage()](#isGenerateSummaryPage--) | Λαμβάνει μια σημαία που υποδεικνύει εάν θα προστεθεί σελίδα σύνοψης με στατιστικά των εντοπισμένων αλλαγών στο τελικό έγγραφο ή όχι. |
|
|  | [setGenerateSummaryPage(boolean value)](#setGenerateSummaryPage-boolean-) | Ορίζει μια σημαία που υποδεικνύει εάν θα προστεθεί σελίδα σύνοψης με στατιστικά των εντοπισμένων αλλαγών στο τελικό έγγραφο ή όχι. |
|
|  | [isExtendedSummaryPage()](#isExtendedSummaryPage--) | Λαμβάνει μια σημαία που υποδεικνύει εάν θα προστεθεί εκτεταμένη πληροφορία σύγκρισης αρχείων στη σελίδα σύνοψης ή όχι. |
|
|  | [setExtendedSummaryPage(boolean value)](#setExtendedSummaryPage-boolean-) | Ορίζει μια σημαία που υποδεικνύει εάν θα προστεθεί εκτεταμένη πληροφορία σύγκρισης αρχείων στη σελίδα σύνοψης ή όχι. |
|
|  | [isShowOnlySummaryPage()](#isShowOnlySummaryPage--) | Λαμβάνει μια σημαία που υποδεικνύει εάν θα παραμείνει στο τελικό έγγραφο μόνο μια σελίδα με στατιστικά των εντοπισμένων αλλαγών ή όχι. |
|
|  | [setShowOnlySummaryPage(boolean value)](#setShowOnlySummaryPage-boolean-) | Ορίζει μια σημαία που υποδεικνύει εάν θα παραμείνει στο τελικό έγγραφο μόνο μια σελίδα με στατιστικά των εντοπισμένων αλλαγών ή όχι. |
|
|  | [isDetectStyleChanges()](#isDetectStyleChanges--) | Λαμβάνει μια σημαία που υποδεικνύει εάν θα εντοπιστούν αλλαγές στυλ ή όχι. |
|
|  | [setDetectStyleChanges(boolean value)](#setDetectStyleChanges-boolean-) | Ορίζει μια σημαία που υποδεικνύει εάν θα εντοπιστούν αλλαγές στυλ ή όχι. |
|
|  | [isMarkNestedContent()](#isMarkNestedContent--) | Λαμβάνει μια σημαία που υποδεικνύει εάν θα σημειωθούν τα παιδιά των διαγραμμένων ή εισαχθέντων στοιχείων ως διαγραμμένα ή εισαχθέντα. |
|
|  | [setMarkNestedContent(boolean value)](#setMarkNestedContent-boolean-) | Ορίζει μια σημαία που υποδεικνύει εάν θα σημειωθούν τα παιδιά των διαγραμμένων ή εισαχθέντων στοιχείων ως διαγραμμένα ή εισαχθέντα. |
|
|  | [isCalculateCoordinates()](#isCalculateCoordinates--) | Λαμβάνει μια σημαία που υποδεικνύει εάν θα υπολογιστούν οι συντεταγμένες για τα αλλαγμένα στοιχεία. |
|
|  | [setCalculateCoordinates(boolean value)](#setCalculateCoordinates-boolean-) | Ορίζει μια σημαία που υποδεικνύει εάν θα υπολογιστούν οι συντεταγμένες για τα αλλαγμένα στοιχεία. |
|
|  | [isHeaderFootersComparison()](#isHeaderFootersComparison--) | Λαμβάνει μια σημαία που υποδεικνύει εάν θα συγκριθεί το περιεχόμενο της κεφαλίδας/υποσέλιδου. |
|
|  | [setHeaderFootersComparison(boolean value)](#setHeaderFootersComparison-boolean-) | Ορίζει μια σημαία που υποδεικνύει εάν θα συγκριθεί το περιεχόμενο της κεφαλίδας/υποσέλιδου. |
|
|  | [getDetalisationLevel()](#getDetalisationLevel--) | Λαμβάνει ένα επίπεδο λεπτομέρειας σύγκρισης που αναπαρίσταται ως [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel). |
|
|  | [setDetalisationLevel(DetalisationLevel value)](#setDetalisationLevel-com.groupdocs.comparison.options.style.DetalisationLevel-) | Ορίζει ένα επίπεδο λεπτομέρειας σύγκρισης που αναπαρίσταται ως [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel). |
|
|  | [isMarkChangedContent()](#isMarkChangedContent--) | Λαμβάνει μια σημαία που υποδεικνύει εάν θα χρησιμοποιηθούν πλαίσια για σχήματα στην Επεξεργασία Κειμένου και για ορθογώνια στα έγγραφα Εικόνας. |
|
|  | [setMarkChangedContent(boolean value)](#setMarkChangedContent-boolean-) | Ορίζει μια σημαία που υποδεικνύει εάν θα χρησιμοποιηθούν πλαίσια για σχήματα στην Επεξεργασία Κειμένου και για ορθογώνια στα έγγραφα Εικόνας. |
|
|  | [getInsertedItemStyle()](#getInsertedItemStyle--) | Λαμβάνει τις ρυθμίσεις στυλ που θα εφαρμοστούν στα εισαχθέντα στοιχεία. |
|
|  | [setInsertedItemStyle(StyleSettings value)](#setInsertedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-) | Ορίζει τις ρυθμίσεις στυλ που θα εφαρμοστούν στα εισαχθέντα στοιχεία. |
|
|  | [getDeletedItemStyle()](#getDeletedItemStyle--) | Λαμβάνει τις ρυθμίσεις στυλ που θα εφαρμοστούν στα διαγραμμένα στοιχεία. |
|
|  | [setDeletedItemStyle(StyleSettings value)](#setDeletedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-) | Ορίζει τις ρυθμίσεις στυλ που θα εφαρμοστούν στα διαγραμμένα στοιχεία. |
|
|  | [getChangedItemStyle()](#getChangedItemStyle--) | Λαμβάνει τις ρυθμίσεις στυλ που θα εφαρμοστούν στα αλλαγμένα στοιχεία. |
|
|  | [setChangedItemStyle(StyleSettings value)](#setChangedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-) | Ορίζει ρυθμίσεις στυλ που θα εφαρμοστούν στα τροποποιημένα στοιχεία. |
|
|  | [getSensitivityOfComparison()](#getSensitivityOfComparison--) | Λαμβάνει ευαισθησία σύγκρισης. |
|
|  | [setSensitivityOfComparison(int value)](#setSensitivityOfComparison-int-) | Ορίζει ευαισθησία σύγκρισης. |
|
|  | [setSensitivityOfComparisonForTables(Integer value)](#setSensitivityOfComparisonForTables-java.lang.Integer-) | Ορίζει ευαισθησία σύγκρισης για πίνακες. |
|
|  | [getSensitivityOfComparisonForTables()](#getSensitivityOfComparisonForTables--) | Λαμβάνει ευαισθησία σύγκρισης για πίνακες. |
|
|  | [setWordsSeparatorChars(char[] value)](#setWordsSeparatorChars-char---) | Ορίζει έναν πίνακα οριοθετητών που θα χρησιμοποιηθεί για το διαχωρισμό του κειμένου σε λέξεις. |
|
|  | [getPasswordSaveOption()](#getPasswordSaveOption--) | Λαμβάνει μια επιλογή αποθήκευσης κωδικού που αντιπροσωπεύεται από το αντικείμενο [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption). |
|
|  | [setPasswordSaveOption(PasswordSaveOption value)](#setPasswordSaveOption-com.groupdocs.comparison.options.enums.PasswordSaveOption-) | Ορίζει μια επιλογή αποθήκευσης κωδικού που αντιπροσωπεύεται από το αντικείμενο [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption). |
|
|  | [getOriginalSize()](#getOriginalSize--) | Λαμβάνει τα αρχικά μεγέθη των συγκρινόμενων εγγράφων που αντιπροσωπεύονται από το αντικείμενο [OriginalSize](../../com.groupdocs.comparison.options/originalsize). |
|
|  | [setOriginalSize(OriginalSize value)](#setOriginalSize-com.groupdocs.comparison.options.OriginalSize-) | Ορίζει τα αρχικά μεγέθη των συγκρινόμενων εγγράφων που αντιπροσωπεύονται από το αντικείμενο [OriginalSize](../../com.groupdocs.comparison.options/originalsize). |
|
|  | [getDiagramMasterSetting()](#getDiagramMasterSetting--) | Λαμβάνει μια ρύθμιση κύριας σελίδας για έγγραφα Diagram που αντιπροσωπεύεται από το αντικείμενο [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting). |
|
|  | [setDiagramMasterSetting(DiagramMasterSetting value)](#setDiagramMasterSetting-com.groupdocs.comparison.options.style.DiagramMasterSetting-) | Ορίζει μια ρύθμιση κύριας σελίδας για έγγραφα Diagram που αντιπροσωπεύεται από το αντικείμενο [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting). |
|
|  | [isDirectoryCompare()](#isDirectoryCompare--) | Επιστρέφει μια σημαία που υποδεικνύει εάν η σύγκριση καταλόγου είναι ενεργοποιημένη. |
|
|  | [setDirectoryCompare(boolean directoryCompare)](#setDirectoryCompare-boolean-) | Ορίζει μια σημαία που υποδεικνύει εάν η σύγκριση καταλόγου πρέπει να ενεργοποιηθεί. |
|
|  | [isShowOnlyChanged()](#isShowOnlyChanged--) | Επιστρέφει μια λογική τιμή που υποδεικνύει εάν πρέπει να εμφανίζονται μόνο τα τροποποιημένα στοιχεία. |
|
|  | [setShowOnlyChanged(boolean showOnlyChanged)](#setShowOnlyChanged-boolean-) | Ορίζει την τιμή που υποδεικνύει εάν πρέπει να εμφανίζονται μόνο τα τροποποιημένα στοιχεία. |
|
|  | [getFolderComparisonExtension()](#getFolderComparisonExtension--) | Λαμβάνει τη μορφή του τελικού αρχείου σύγκρισης φακέλου. |
|
|  | [setFolderComparisonExtension(FolderComparisonExtension folderComparisonExtension)](#setFolderComparisonExtension-com.groupdocs.comparison.options.enums.FolderComparisonExtension-) | Ορίζει τη μορφή του τελικού αρχείου σύγκρισης φακέλου. |
|
### CompareOptions() {#CompareOptions--}
```
public CompareOptions()
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης CompareOptions.


### CompareOptions(StyleSettings insertedItemStyle, StyleSettings deletedItemStyle, StyleSettings changedItemStyle) {#CompareOptions-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-}
```
public CompareOptions(StyleSettings insertedItemStyle, StyleSettings deletedItemStyle, StyleSettings changedItemStyle)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης CompareOptions με ρυθμίσεις για διαφορετικά στυλ.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | insertedItemStyle | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Ρυθμίσεις στυλ για εισαχθέντα στοιχεία |
|
|  | deletedItemStyle | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Ρυθμίσεις στυλ για διαγραμμένα στοιχεία |
|
|  | changedItemStyle | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Ρυθμίσεις στυλ για τροποποιημένα στοιχεία στυλ |
|

### ignoreChangeSettings {#ignoreChangeSettings}
```
public IgnoreChangeSensitivitySettings ignoreChangeSettings
```


### getIgnoreChangeSettings() {#getIgnoreChangeSettings--}
```
public IgnoreChangeSensitivitySettings getIgnoreChangeSettings()
```


Λάβετε τις ρυθμίσεις για την αγνόηση αλλαγών βάσει ομοιότητας.


**Returns:**
com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings - Ρυθμίσεις για την παράβλεψη αλλαγών.

### setIgnoreChangeSettings(IgnoreChangeSensitivitySettings ignoreChangeSettings) {#setIgnoreChangeSettings-com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings-}
```
public void setIgnoreChangeSettings(IgnoreChangeSensitivitySettings ignoreChangeSettings)
```


Ορίζει τις ρυθμίσεις για την αγνόηση αλλαγών βάσει ομοιότητας.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | ignoreChangeSettings | com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings | Ρυθμίσεις για την παράβλεψη αλλαγών. |
|

### getUserMasterPath() {#getUserMasterPath--}
```
public String getUserMasterPath()
```


Λαμβάνει τη διαδρομή προς το πρότυπο του χρήστη για Διαγράμματα.


**Returns:**
java.lang.String - Η διαδρομή προς το πρότυπο του master του χρήστη για τα Διαγράμματα.

### setUserMasterPath(String userMasterPath) {#setUserMasterPath-java.lang.String-}
```
public void setUserMasterPath(String userMasterPath)
```


Ορίζει τη διαδρομή προς το πρότυπο του χρήστη για Διαγράμματα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | userMasterPath | java.lang.String | Η διαδρομή προς το πρότυπο του master του χρήστη για τα Διαγράμματα. |
|

### getComparisonType() {#getComparisonType--}
```
public ComparisonType getComparisonType()
```


Λαμβάνει έναν τύπο πηγής και στόχου εγγράφων ως αντικείμενο [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) ώστε η Comparison να γνωρίζει πώς να τα συγκρίνει.
Όταν αυτή η επιλογή είναι ενεργοποιημένη, η επιλογή [LoadOptions.getFileType()](../../com.groupdocs.comparison.options.load/loadoptions#getFileType--) θα παραλειφθεί.


**Returns:**
[ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) - the type of source and target documents

### setComparisonType(ComparisonType comparisonType) {#setComparisonType-com.groupdocs.comparison.options.enums.ComparisonType-}
```
public void setComparisonType(ComparisonType comparisonType)
```


Ορίζει έναν τύπο πηγής και στόχου εγγράφων ως αντικείμενο [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) ώστε η Comparison να γνωρίζει πώς να τα συγκρίνει.
Όταν αυτή η επιλογή είναι ενεργοποιημένη, η επιλογή [LoadOptions.setFileType(FileType)](../../com.groupdocs.comparison.options.load/loadoptions#setFileType-FileType-) θα παραλειφθεί.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | comparisonType | [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) | Ο τύπος των πηγαίων και στόχων εγγράφων |
|

### getPaperSize() {#getPaperSize--}
```
public final PaperSize getPaperSize()
```


Λαμβάνει το μέγεθος του χαρτιού στο τελικό έγγραφο ως αντικείμενο [PaperSize](../../com.groupdocs.comparison.options.enums/papersize) object.


**Returns:**
[PaperSize](../../com.groupdocs.comparison.options.enums/papersize) - the size of a paper in result document

### setPaperSize(PaperSize value) {#setPaperSize-com.groupdocs.comparison.options.enums.PaperSize-}
```
public final void setPaperSize(PaperSize value)
```


Ορίζει το μέγεθος του χαρτιού στο τελικό έγγραφο ως αντικείμενο [PaperSize](../../com.groupdocs.comparison.options.enums/papersize) object.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [PaperSize](../../com.groupdocs.comparison.options.enums/papersize) | Το μέγεθος του χαρτιού στο τελικό έγγραφο. |
|

### getCalculateCoordinatesMode() {#getCalculateCoordinatesMode--}
```
public CalculateCoordinatesModeEnumeration getCalculateCoordinatesMode()
```


Λαμβάνει τη λειτουργία υπολογισμού συντεταγμένων ως αντικείμενο [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) object.


**Returns:**
[CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) - the calculate coordinates mode

### setCalculateCoordinatesMode(CalculateCoordinatesModeEnumeration calculateCoordinatesMode) {#setCalculateCoordinatesMode-com.groupdocs.comparison.options.enums.CalculateCoordinatesModeEnumeration-}
```
public void setCalculateCoordinatesMode(CalculateCoordinatesModeEnumeration calculateCoordinatesMode)
```


Ορίζει τη λειτουργία υπολογισμού συντεταγμένων ως αντικείμενο [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) object.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | calculateCoordinatesMode | [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) | Η λειτουργία υπολογισμού συντεταγμένων. |
|

### isShowDeletedContent() {#isShowDeletedContent--}
```
public final boolean isShowDeletedContent()
```


Λαμβάνει μια σημαία που υποδεικνύει εάν θα εμφανίζονται διαγραμμένα στοιχεία στο τελικό έγγραφο ή όχι.


**Returns:**
boolean - true εάν τα διαγραμμένα στοιχεία στο τελικό έγγραφο θα εμφανιστούν, διαφορετικά false

### setShowDeletedContent(boolean value) {#setShowDeletedContent-boolean-}
```
public final void setShowDeletedContent(boolean value)
```


Ορίζει μια σημαία που υποδεικνύει εάν θα εμφανίζονται διαγραμμένα στοιχεία στο τελικό έγγραφο ή όχι.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | boolean | true εάν τα διαγραμμένα στοιχεία στο τελικό έγγραφο πρέπει να εμφανιστούν, διαφορετικά false |
|

### isShowInsertedContent() {#isShowInsertedContent--}
```
public final boolean isShowInsertedContent()
```


Λαμβάνει μια σημαία που υποδεικνύει εάν θα εμφανίζονται τα εισαχθέντα στοιχεία στο τελικό έγγραφο ή όχι.


**Returns:**
boolean - true εάν τα εισαχθέντα στοιχεία στο τελικό έγγραφο πρέπει να εμφανιστούν, διαφορετικά false

### setShowInsertedContent(boolean value) {#setShowInsertedContent-boolean-}
```
public final void setShowInsertedContent(boolean value)
```


Ορίζει μια σημαία που υποδεικνύει εάν θα εμφανίζονται τα εισαχθέντα στοιχεία στο τελικό έγγραφο ή όχι.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | boolean | true εάν τα εισαχθέντα στοιχεία στο τελικό έγγραφο πρέπει να εμφανιστούν, διαφορετικά false |
|

### isGenerateSummaryPage() {#isGenerateSummaryPage--}
```
public final boolean isGenerateSummaryPage()
```


Λαμβάνει μια σημαία που υποδεικνύει εάν θα προστεθεί σελίδα σύνοψης με στατιστικά των εντοπισμένων αλλαγών στο τελικό έγγραφο ή όχι.


**Returns:**
boolean - true εάν θα προστεθεί η σελίδα περίληψης, διαφορετικά false

### setGenerateSummaryPage(boolean value) {#setGenerateSummaryPage-boolean-}
```
public final void setGenerateSummaryPage(boolean value)
```


Ορίζει μια σημαία που υποδεικνύει εάν θα προστεθεί σελίδα σύνοψης με στατιστικά των εντοπισμένων αλλαγών στο τελικό έγγραφο ή όχι.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | boolean | true εάν η σελίδα περίληψης πρέπει να προστεθεί, διαφορετικά false |
|

### isExtendedSummaryPage() {#isExtendedSummaryPage--}
```
public boolean isExtendedSummaryPage()
```


Λαμβάνει μια σημαία που υποδεικνύει εάν θα προστεθεί εκτεταμένη πληροφορία σύγκρισης αρχείων στη σελίδα σύνοψης ή όχι.


**Returns:**
boolean - true εάν θα προστεθεί εκτεταμένη πληροφορία σύγκρισης αρχείων στη σελίδα περίληψης, διαφορετικά false

### setExtendedSummaryPage(boolean value) {#setExtendedSummaryPage-boolean-}
```
public void setExtendedSummaryPage(boolean value)
```


Ορίζει μια σημαία που υποδεικνύει εάν θα προστεθεί εκτεταμένη πληροφορία σύγκρισης αρχείων στη σελίδα σύνοψης ή όχι.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | boolean | true εάν η εκτεταμένη πληροφορία σύγκρισης αρχείων πρέπει να προστεθεί στη σελίδα περίληψης, διαφορετικά false |
|

### isShowOnlySummaryPage() {#isShowOnlySummaryPage--}
```
public boolean isShowOnlySummaryPage()
```


Λαμβάνει μια σημαία που υποδεικνύει εάν θα παραμείνει στο τελικό έγγραφο μόνο μια σελίδα με στατιστικά των εντοπισμένων αλλαγών ή όχι.


**Returns:**
boolean - true εάν στο τελικό έγγραφο θα παραμείνει μόνο μια σελίδα με στατιστικά των εντοπισμένων αλλαγών, διαφορετικά false

### setShowOnlySummaryPage(boolean value) {#setShowOnlySummaryPage-boolean-}
```
public void setShowOnlySummaryPage(boolean value)
```


Ορίζει μια σημαία που υποδεικνύει εάν θα παραμείνει στο τελικό έγγραφο μόνο μια σελίδα με στατιστικά των εντοπισμένων αλλαγών ή όχι.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | boolean | true εάν στο τελικό έγγραφο πρέπει να παραμείνει μόνο μια σελίδα με στατιστικά των εντοπισμένων αλλαγών, διαφορετικά false |
|

### isDetectStyleChanges() {#isDetectStyleChanges--}
```
public final boolean isDetectStyleChanges()
```


Λαμβάνει μια σημαία που υποδεικνύει εάν θα εντοπιστούν αλλαγές στυλ ή όχι.


**Returns:**
boolean - true εάν θα εντοπιστούν αλλαγές στυλ, διαφορετικά false

### setDetectStyleChanges(boolean value) {#setDetectStyleChanges-boolean-}
```
public final void setDetectStyleChanges(boolean value)
```


Ορίζει μια σημαία που υποδεικνύει εάν θα εντοπιστούν αλλαγές στυλ ή όχι.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | boolean | true εάν πρέπει να εντοπιστούν αλλαγές στυλ, διαφορετικά false |
|

### isMarkNestedContent() {#isMarkNestedContent--}
```
public final boolean isMarkNestedContent()
```


Λαμβάνει μια σημαία που υποδεικνύει εάν θα σημειωθούν τα παιδιά των διαγραμμένων ή εισαχθέντων στοιχείων ως διαγραμμένα ή εισαχθέντα.


**Returns:**
boolean - true εάν τα υποστοιχεία των διαγραμμένων ή εισαχθέντων στοιχείων θα σημειωθούν ως διαγραμμένα ή εισαχθέντα, διαφορετικά false

### setMarkNestedContent(boolean value) {#setMarkNestedContent-boolean-}
```
public final void setMarkNestedContent(boolean value)
```


Ορίζει μια σημαία που υποδεικνύει εάν θα σημειωθούν τα παιδιά των διαγραμμένων ή εισαχθέντων στοιχείων ως διαγραμμένα ή εισαχθέντα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | boolean | true εάν τα υποστοιχεία των διαγραμμένων ή εισαχθέντων στοιχείων πρέπει να σημειωθούν ως διαγραμμένα ή εισαχθέντα, διαφορετικά false |
|

### isCalculateCoordinates() {#isCalculateCoordinates--}
```
public final boolean isCalculateCoordinates()
```


Λαμβάνει μια σημαία που υποδεικνύει εάν θα υπολογιστούν οι συντεταγμένες για τα αλλαγμένα στοιχεία.


**Returns:**
boolean - true εάν θα υπολογιστούν οι συντεταγμένες για τα τροποποιημένα στοιχεία, διαφορετικά false

### setCalculateCoordinates(boolean value) {#setCalculateCoordinates-boolean-}
```
public final void setCalculateCoordinates(boolean value)
```


Ορίζει μια σημαία που υποδεικνύει εάν θα υπολογιστούν οι συντεταγμένες για τα αλλαγμένα στοιχεία.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | boolean | true εάν πρέπει να υπολογιστούν οι συντεταγμένες για τα τροποποιημένα στοιχεία, διαφορετικά false |
|

### isHeaderFootersComparison() {#isHeaderFootersComparison--}
```
public final boolean isHeaderFootersComparison()
```


Λαμβάνει μια σημαία που υποδεικνύει εάν θα συγκριθεί το περιεχόμενο της κεφαλίδας/υποσέλιδου.


**Returns:**
boolean - true εάν τα περιεχόμενα κεφαλίδας/υποσέλιδου θα συγκριθούν, διαφορετικά false

### setHeaderFootersComparison(boolean value) {#setHeaderFootersComparison-boolean-}
```
public final void setHeaderFootersComparison(boolean value)
```


Ορίζει μια σημαία που υποδεικνύει εάν θα συγκριθεί το περιεχόμενο της κεφαλίδας/υποσέλιδου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | boolean | true εάν το περιεχόμενο κεφαλίδας/υποσέλιδου πρέπει να συγκριθεί, διαφορετικά false |
|

### getDetalisationLevel() {#getDetalisationLevel--}
```
public final DetalisationLevel getDetalisationLevel()
```


Λαμβάνει ένα επίπεδο λεπτομέρειας σύγκρισης που αναπαρίσταται ως [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel).
Η προεπιλεγμένη τιμή είναι [DetalisationLevel.LOW](../../com.groupdocs.comparison.options.style/detalisationlevel#LOW).


**Returns:**
[DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) - the level of comparison detalization

### setDetalisationLevel(DetalisationLevel value) {#setDetalisationLevel-com.groupdocs.comparison.options.style.DetalisationLevel-}
```
public final void setDetalisationLevel(DetalisationLevel value)
```


Ορίζει ένα επίπεδο λεπτομέρειας σύγκρισης που αναπαρίσταται ως [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel).
Η προεπιλεγμένη τιμή είναι [DetalisationLevel.LOW](../../com.groupdocs.comparison.options.style/detalisationlevel#LOW)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) | Το επίπεδο λεπτομέρειας σύγκρισης |
|

### isMarkChangedContent() {#isMarkChangedContent--}
```
public final boolean isMarkChangedContent()
```


Λαμβάνει μια σημαία που υποδεικνύει εάν θα χρησιμοποιηθούν πλαίσια για σχήματα στην Επεξεργασία Κειμένου και για ορθογώνια στα έγγραφα Εικόνας.


**Returns:**
boolean - true εάν θα χρησιμοποιηθούν πλαίσια, διαφορετικά false

### setMarkChangedContent(boolean value) {#setMarkChangedContent-boolean-}
```
public final void setMarkChangedContent(boolean value)
```


Ορίζει μια σημαία που υποδεικνύει εάν θα χρησιμοποιηθούν πλαίσια για σχήματα στην Επεξεργασία Κειμένου και για ορθογώνια στα έγγραφα Εικόνας.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | boolean | true εάν πρέπει να χρησιμοποιηθούν πλαίσια, διαφορετικά false |
|

### getInsertedItemStyle() {#getInsertedItemStyle--}
```
public final StyleSettings getInsertedItemStyle()
```


Λαμβάνει τις ρυθμίσεις στυλ που θα εφαρμοστούν στα εισαχθέντα στοιχεία.


**Returns:**
[StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) - style settings of inserted items

### setInsertedItemStyle(StyleSettings value) {#setInsertedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-}
```
public final void setInsertedItemStyle(StyleSettings value)
```


Ορίζει τις ρυθμίσεις στυλ που θα εφαρμοστούν στα εισαχθέντα στοιχεία.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Ρυθμίσεις στυλ των εισαχθέντων στοιχείων |
|

### getDeletedItemStyle() {#getDeletedItemStyle--}
```
public final StyleSettings getDeletedItemStyle()
```


Λαμβάνει τις ρυθμίσεις στυλ που θα εφαρμοστούν στα διαγραμμένα στοιχεία.


**Returns:**
[StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) - style settings of deleted items

### setDeletedItemStyle(StyleSettings value) {#setDeletedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-}
```
public final void setDeletedItemStyle(StyleSettings value)
```


Ορίζει τις ρυθμίσεις στυλ που θα εφαρμοστούν στα διαγραμμένα στοιχεία.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Ρυθμίσεις στυλ των διαγραμμένων στοιχείων |
|

### getChangedItemStyle() {#getChangedItemStyle--}
```
public final StyleSettings getChangedItemStyle()
```


Λαμβάνει τις ρυθμίσεις στυλ που θα εφαρμοστούν στα αλλαγμένα στοιχεία.


**Returns:**
[StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) - style settings of changed items

### setChangedItemStyle(StyleSettings value) {#setChangedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-}
```
public final void setChangedItemStyle(StyleSettings value)
```


Ορίζει ρυθμίσεις στυλ που θα εφαρμοστούν στα τροποποιημένα στοιχεία.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Ρυθμίσεις στυλ των τροποποιημένων στοιχείων |
|

### getSensitivityOfComparison() {#getSensitivityOfComparison--}
```
public final int getSensitivityOfComparison()
```


Λαμβάνει ευαισθησία σύγκρισης.
Το ποσοστό των διαγραμμένων και εισαχθέντων στοιχείων δύο συγκρινόμενων αντικειμένων σε σχέση με όλα τα στοιχεία αυτών των αντικειμένων.

* If this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Returns:**
int - η ευαισθησία της σύγκρισης

### setSensitivityOfComparison(int value) {#setSensitivityOfComparison-int-}
```
public final void setSensitivityOfComparison(int value)
```


Ορίζει ευαισθησία σύγκρισης.
Το ποσοστό των διαγραμμένων και εισαχθέντων στοιχείων δύο συγκρινόμενων αντικειμένων σε σχέση με όλα τα στοιχεία αυτών των αντικειμένων.

* If this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | int | Η ευαισθησία της σύγκρισης |
|

### setSensitivityOfComparisonForTables(Integer value) {#setSensitivityOfComparisonForTables-java.lang.Integer-}
```
public void setSensitivityOfComparisonForTables(Integer value)
```


Ορίζει ευαισθησία σύγκρισης για πίνακες.
Εάν η τιμή είναι null, χρησιμοποιείται το SensitivityOfComparison. Το ποσοστό των διαγραμμένων και εισαχθέντων στοιχείων δύο συγκρινόμενων αντικειμένων σε σχέση με όλα τα στοιχεία αυτών των αντικειμένων.

* if this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs, if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | java.lang.Integer | Η ευαισθησία της σύγκρισης για πίνακες |
|

### getSensitivityOfComparisonForTables() {#getSensitivityOfComparisonForTables--}
```
public final Integer getSensitivityOfComparisonForTables()
```


Λαμβάνει ευαισθησία σύγκρισης για πίνακες.
Εάν η τιμή είναι null, χρησιμοποιείται το SensitivityOfComparison. Το ποσοστό των διαγραμμένων και εισαχθέντων στοιχείων δύο συγκρινόμενων αντικειμένων σε σχέση με όλα τα στοιχεία αυτών των αντικειμένων.

* if this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs, if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Returns:**
java.lang.Integer - Η ευαισθησία της σύγκρισης για πίνακες

### setWordsSeparatorChars(char[] value) {#setWordsSeparatorChars-char---}
```
public final void setWordsSeparatorChars(char[] value)
```


Ορίζει έναν πίνακα οριοθετητών που θα χρησιμοποιηθεί για το διαχωρισμό του κειμένου σε λέξεις.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | char[] | Ο πίνακας των οριοθετητών για το διαχωρισμό του κειμένου σε λέξεις |
|

### getPasswordSaveOption() {#getPasswordSaveOption--}
```
public final PasswordSaveOption getPasswordSaveOption()
```


Λαμβάνει μια επιλογή αποθήκευσης κωδικού που αντιπροσωπεύεται από το αντικείμενο [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption).


**Returns:**
[PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) - the password save option

### setPasswordSaveOption(PasswordSaveOption value) {#setPasswordSaveOption-com.groupdocs.comparison.options.enums.PasswordSaveOption-}
```
public final void setPasswordSaveOption(PasswordSaveOption value)
```


Ορίζει μια επιλογή αποθήκευσης κωδικού που αντιπροσωπεύεται από το αντικείμενο [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) | Η επιλογή αποθήκευσης κωδικού πρόσβασης |
|

### getOriginalSize() {#getOriginalSize--}
```
public final OriginalSize getOriginalSize()
```


Λαμβάνει τα αρχικά μεγέθη των συγκρινόμενων εγγράφων που αντιπροσωπεύονται από το αντικείμενο [OriginalSize](../../com.groupdocs.comparison.options/originalsize).


**Returns:**
[OriginalSize](../../com.groupdocs.comparison.options/originalsize) - the original size of documents

### setOriginalSize(OriginalSize value) {#setOriginalSize-com.groupdocs.comparison.options.OriginalSize-}
```
public final void setOriginalSize(OriginalSize value)
```


Ορίζει τα αρχικά μεγέθη των συγκρινόμενων εγγράφων που αντιπροσωπεύονται από το αντικείμενο [OriginalSize](../../com.groupdocs.comparison.options/originalsize).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [OriginalSize](../../com.groupdocs.comparison.options/originalsize) | Το αρχικό μέγεθος των εγγράφων |
|

### getDiagramMasterSetting() {#getDiagramMasterSetting--}
```
public final DiagramMasterSetting getDiagramMasterSetting()
```


Λαμβάνει μια ρύθμιση κύριας σελίδας για έγγραφα Diagram που αντιπροσωπεύεται από το αντικείμενο [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting).


**Returns:**
[DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) - the diagram master page setting

### setDiagramMasterSetting(DiagramMasterSetting value) {#setDiagramMasterSetting-com.groupdocs.comparison.options.style.DiagramMasterSetting-}
```
public final void setDiagramMasterSetting(DiagramMasterSetting value)
```


Ορίζει μια ρύθμιση κύριας σελίδας για έγγραφα Diagram που αντιπροσωπεύεται από το αντικείμενο [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) | Η ρύθμιση κύριας σελίδας διαγράμματος |
|

### isDirectoryCompare() {#isDirectoryCompare--}
```
public boolean isDirectoryCompare()
```


Επιστρέφει μια σημαία που υποδεικνύει εάν η σύγκριση καταλόγου είναι ενεργοποιημένη.


**Returns:**
boolean - true εάν η σύγκριση καταλόγου είναι ενεργοποιημένη, διαφορετικά false

### setDirectoryCompare(boolean directoryCompare) {#setDirectoryCompare-boolean-}
```
public void setDirectoryCompare(boolean directoryCompare)
```


Ορίζει μια σημαία που υποδεικνύει εάν η σύγκριση καταλόγου πρέπει να ενεργοποιηθεί.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | directoryCompare | boolean | true εάν η σύγκριση καταλόγου πρέπει να ενεργοποιηθεί, διαφορετικά false |
|

### isShowOnlyChanged() {#isShowOnlyChanged--}
```
public boolean isShowOnlyChanged()
```


Επιστρέφει μια λογική τιμή που υποδεικνύει εάν πρέπει να εμφανίζονται μόνο τα τροποποιημένα στοιχεία.


**Returns:**
boolean - true εάν πρέπει να εμφανίζονται μόνο τα τροποποιημένα στοιχεία, διαφορετικά false

### setShowOnlyChanged(boolean showOnlyChanged) {#setShowOnlyChanged-boolean-}
```
public void setShowOnlyChanged(boolean showOnlyChanged)
```


Ορίζει την τιμή που υποδεικνύει εάν πρέπει να εμφανίζονται μόνο τα τροποποιημένα στοιχεία.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | showOnlyChanged | boolean | η boolean τιμή που υποδεικνύει εάν πρέπει να εμφανίζονται μόνο τα τροποποιημένα στοιχεία |
|

### getFolderComparisonExtension() {#getFolderComparisonExtension--}
```
public FolderComparisonExtension getFolderComparisonExtension()
```


Λαμβάνει τη μορφή του τελικού αρχείου σύγκρισης φακέλου.


**Returns:**
com.groupdocs.comparison.options.enums.FolderComparisonExtension - το FolderComparisonExtension που αντιπροσωπεύει τη μορφή του τελικού αρχείου σύγκρισης φακέλων

### setFolderComparisonExtension(FolderComparisonExtension folderComparisonExtension) {#setFolderComparisonExtension-com.groupdocs.comparison.options.enums.FolderComparisonExtension-}
```
public void setFolderComparisonExtension(FolderComparisonExtension folderComparisonExtension)
```


Ορίζει τη μορφή του τελικού αρχείου σύγκρισης φακέλου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | folderComparisonExtension | com.groupdocs.comparison.options.enums.FolderComparisonExtension | το FolderComparisonExtension που αντιπροσωπεύει τη μορφή του τελικού αρχείου σύγκρισης φακέλων |
|

