---
title: "PasswordSaveOption"
second_title: "GroupDocs.Comparison for Java Αναφορά API"
description: "Απαριθμεί τις επιλογές αποθήκευσης πληροφοριών κωδικού σε ένα έγγραφο κατά τη διαδικασία σύγκρισης."
type: docs
weight: 14
url: /el/java/com.groupdocs.comparison.options.enums/passwordsaveoption/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PasswordSaveOption extends Enum<PasswordSaveOption>
```

Απαριθμεί τις επιλογές αποθήκευσης πληροφοριών κωδικού σε ένα έγγραφο κατά τη διαδικασία σύγκρισης.


Παράδειγμα χρήσης:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setPasswordSaveOption(PasswordSaveOption.SOURCE);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [NONE](#NONE) | Μην αποθηκεύετε τον κωδικό πρόσβασης. |
|
|  | [SOURCE](#SOURCE) | Χρησιμοποιήστε τον κωδικό πρόσβασης από το πηγαίο έγγραφο. |
|
|  | [TARGET](#TARGET) | Χρησιμοποιήστε τον κωδικό πρόσβασης από το έγγραφο-στόχο. |
|
|  | [USER](#USER) | \* Χρησιμοποιήστε τον κωδικό πρόσβασης που παρέχεται από τον χρήστη. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Αναλύει την αναπαράσταση συμβολοσειράς του PasswordSaveOption για να λάβει τη σταθερά enum. |
|
|  | [toString()](#toString--) | Αναπαράσταση συμβολοσειράς του PasswordSaveOption. |
|
### NONE {#NONE}
```
public static final PasswordSaveOption NONE
```


Μην αποθηκεύετε τον κωδικό πρόσβασης.


### SOURCE {#SOURCE}
```
public static final PasswordSaveOption SOURCE
```


Χρησιμοποιήστε τον κωδικό πρόσβασης από το πηγαίο έγγραφο.


### TARGET {#TARGET}
```
public static final PasswordSaveOption TARGET
```


Χρησιμοποιήστε τον κωδικό πρόσβασης από το έγγραφο-στόχο.


### USER {#USER}
```
public static final PasswordSaveOption USER
```


\* Χρησιμοποιήστε τον κωδικό πρόσβασης που παρέχεται από τον χρήστη.


### values() {#values--}
```
public static PasswordSaveOption[] values()
```




**Returns:**
com.groupdocs.comparison.options.enums.PasswordSaveOption[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PasswordSaveOption valueOf(String name)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| όνομα | java.lang.String |  |

**Returns:**
[PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static PasswordSaveOption fromString(String toStringValue)
```


Αναλύει την αναπαράσταση συμβολοσειράς του PasswordSaveOption για να λάβει τη σταθερά enum.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | toStringValue | java.lang.String | Η αναπαράσταση συμβολοσειράς του PasswordSaveOption |
|

**Returns:**
[PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) - PasswordSaveOption enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


Αναπαράσταση συμβολοσειράς του PasswordSaveOption.


**Returns:**
java.lang.String - τιμή συμβολοσειράς του σταθερού της enum

