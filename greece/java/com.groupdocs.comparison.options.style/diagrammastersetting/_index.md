---
title: "DiagramMasterSetting"
second_title: "GroupDocs.Comparison for Java Αναφορά API"
description: "Αντιπροσωπεύει τις ρυθμίσεις για τη σύγκριση κυρίως διαγράμματος."
type: docs
weight: 10
url: /el/java/com.groupdocs.comparison.options.style/diagrammastersetting/
---
**Inheritance:**
java.lang.Object
```
public class DiagramMasterSetting
```

Αντιπροσωπεύει τις ρυθμίσεις για τη σύγκριση κυρίως διαγράμματος.


Παράδειγμα χρήσης:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    final DiagramMasterSetting diagramMasterSetting = new DiagramMasterSetting();
    diagramMasterSetting.setMasterPath(masterFilePath);

    final CompareOptions compareOptions = new CompareOptions();
    compareOptions.setDiagramMasterSetting(diagramMasterSetting);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [DiagramMasterSetting()](#DiagramMasterSetting--) | Αρχικοποιεί μια νέα παρουσία της κλάσης DiagramMasterSetting. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [isUseSourceMaster()](#isUseSourceMaster--) | Λαμβάνει μια σημαία που υποδεικνύει εάν θα χρησιμοποιηθεί η διαδρομή source master path. |
|
|  | [setUseSourceMaster(boolean value)](#setUseSourceMaster-boolean-) | Λαμβάνει μια σημαία που υποδεικνύει εάν θα πρέπει να χρησιμοποιηθεί η διαδρομή source master path. |
|
|  | [getMasterPath()](#getMasterPath--) | Λαμβάνει μια κύρια διαδρομή που θα χρησιμοποιηθεί για την απόδοση εγγράφων. |
|
|  | [setMasterPath(String value)](#setMasterPath-java.lang.String-) | Ορίζει μια κύρια διαδρομή που θα πρέπει να χρησιμοποιηθεί για την απόδοση εγγράφων. |
|
### DiagramMasterSetting() {#DiagramMasterSetting--}
```
public DiagramMasterSetting()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης DiagramMasterSetting.


### isUseSourceMaster() {#isUseSourceMaster--}
```
public final boolean isUseSourceMaster()
```


Λαμβάνει μια σημαία που υποδεικνύει εάν θα χρησιμοποιηθεί η διαδρομή source master path.


**Returns:**
boolean - true εάν η πηγή κύριας διαδρομής θα εμφανιστεί, διαφορετικά false

### setUseSourceMaster(boolean value) {#setUseSourceMaster-boolean-}
```
public final void setUseSourceMaster(boolean value)
```


Λαμβάνει μια σημαία που υποδεικνύει εάν θα πρέπει να χρησιμοποιηθεί η διαδρομή source master path.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | boolean | true εάν η πηγή κύριας διαδρομής πρέπει να εμφανιστεί, διαφορετικά false |
|

### getMasterPath() {#getMasterPath--}
```
public final String getMasterPath()
```


Λαμβάνει μια κύρια διαδρομή που θα χρησιμοποιηθεί για την απόδοση εγγράφων. Το MasterPath απαιτείται για τη δημιουργία ενός τελικού εγγράφου από ένα σύνολο προεπιλεγμένων σχημάτων.


**Returns:**
java.lang.String - διαδρομή του κύριου εγγράφου εάν έχει οριστεί, διαφορετικά προεπιλεγμένη κύρια διαδρομή.

### setMasterPath(String value) {#setMasterPath-java.lang.String-}
```
public final void setMasterPath(String value)
```


Ορίζει μια κύρια διαδρομή που πρέπει να χρησιμοποιηθεί για την απόδοση εγγράφων. Το MasterPath απαιτείται για τη δημιουργία ενός τελικού εγγράφου από ένα σύνολο προεπιλεγμένων σχημάτων.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | java.lang.String | Διαδρομή του κύριου εγγράφου εάν έχει οριστεί, διαφορετικά προεπιλεγμένη κύρια διαδρομή. |
|

