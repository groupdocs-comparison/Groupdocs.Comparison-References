---
title: "PaperSize"
second_title: "GroupDocs.Comparison for Java Αναφορά API"
description: "Αναπαριστά τις επιλογές μεγέθους χαρτιού για τη σύγκριση εγγράφων."
type: docs
weight: 13
url: /el/java/com.groupdocs.comparison.options.enums/papersize/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PaperSize extends Enum<PaperSize>
```

Αναπαριστά τις επιλογές μεγέθους χαρτιού για τη σύγκριση εγγράφων.


Παράδειγμα χρήσης:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setPaperSize(PaperSize.A6);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [DEFAULT](#DEFAULT) | Προεπιλεγμένο μέγεθος χαρτιού. |
|
|  | [A0](#A0) | Τυπικό μέγεθος χαρτιού A0 (841mm x 1189mm). |
|
|  | [A1](#A1) | Τυπικό μέγεθος χαρτιού A1 (594mm x 841mm). |
|
|  | [A2](#A2) | Τυπικό μέγεθος χαρτιού A2 (420mm x 594mm). |
|
|  | [A3](#A3) | Τυπικό μέγεθος χαρτιού A3 (297mm x 420mm). |
|
|  | [A4](#A4) | Τυπικό μέγεθος χαρτιού A4 (210mm x 297mm). |
|
|  | [A5](#A5) | Τυπικό μέγεθος χαρτιού A5 (148mm x 210mm). |
|
|  | [A6](#A6) | Τυπικό μέγεθος χαρτιού A6 (105mm x 148mm). |
|
|  | [A7](#A7) | Τυπικό μέγεθος χαρτιού A7 (74mm x 105mm). |
|
|  | [A8](#A8) | Τυπικό μέγεθος χαρτιού A8 (52mm x 74mm). |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Αναλύει τη συμβολοσειρά αναπαράστασης του PaperSize για να λάβει τη σταθερά enum. |
|
|  | [toString()](#toString--) | Συμβολοσειρά αναπαράστασης του PaperSize. |
|
### DEFAULT {#DEFAULT}
```
public static final PaperSize DEFAULT
```


Προεπιλεγμένο μέγεθος χαρτιού.


### A0 {#A0}
```
public static final PaperSize A0
```


Τυπικό μέγεθος χαρτιού A0 (841mm x 1189mm).


### A1 {#A1}
```
public static final PaperSize A1
```


Τυπικό μέγεθος χαρτιού A1 (594mm x 841mm).


### A2 {#A2}
```
public static final PaperSize A2
```


Τυπικό μέγεθος χαρτιού A2 (420mm x 594mm).


### A3 {#A3}
```
public static final PaperSize A3
```


Τυπικό μέγεθος χαρτιού A3 (297mm x 420mm).


### A4 {#A4}
```
public static final PaperSize A4
```


Τυπικό μέγεθος χαρτιού A4 (210mm x 297mm).


### A5 {#A5}
```
public static final PaperSize A5
```


Τυπικό μέγεθος χαρτιού A5 (148mm x 210mm).


### A6 {#A6}
```
public static final PaperSize A6
```


Τυπικό μέγεθος χαρτιού A6 (105mm x 148mm).


### A7 {#A7}
```
public static final PaperSize A7
```


Τυπικό μέγεθος χαρτιού A7 (74mm x 105mm).


### A8 {#A8}
```
public static final PaperSize A8
```


Τυπικό μέγεθος χαρτιού A8 (52mm x 74mm).


### values() {#values--}
```
public static PaperSize[] values()
```




**Returns:**
com.groupdocs.comparison.options.enums.PaperSize[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PaperSize valueOf(String name)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| όνομα | java.lang.String |  |

**Returns:**
[PaperSize](../../com.groupdocs.comparison.options.enums/papersize)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static PaperSize fromString(String toStringValue)
```


Αναλύει τη συμβολοσειρά αναπαράστασης του PaperSize για να λάβει τη σταθερά enum.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | toStringValue | java.lang.String | Η συμβολοσειρά αναπαράστασης του PaperSize |
|

**Returns:**
[PaperSize](../../com.groupdocs.comparison.options.enums/papersize) - PaperSize enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


Συμβολοσειρά αναπαράστασης του PaperSize.


**Returns:**
java.lang.String - τιμή συμβολοσειράς του σταθερού της enum

