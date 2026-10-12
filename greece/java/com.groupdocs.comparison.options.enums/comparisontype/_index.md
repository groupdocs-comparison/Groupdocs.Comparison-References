---
title: "ComparisonType"
second_title: "GroupDocs.Comparison for Java Αναφορά API"
description: "Αναπαριστά τον τύπο σύγκρισης που θα εκτελεστεί."
type: docs
weight: 10
url: /el/java/com.groupdocs.comparison.options.enums/comparisontype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ComparisonType extends Enum<ComparisonType>
```

Αναπαριστά τον τύπο σύγκρισης που θα εκτελεστεί.


Παράδειγμα χρήσης:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setComparisonType(ComparisonType.CELLS);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [TEXT](#TEXT) | Τα αρχεία πρέπει να συγκρίνονται ως έγγραφα κειμένου. |
|
|  | [SLIDES](#SLIDES) | Τα αρχεία πρέπει να συγκρίνονται ως έγγραφα παρουσίασης. |
|
|  | [WORDS](#WORDS) | Τα αρχεία πρέπει να συγκρίνονται ως έγγραφα Word. |
|
|  | [CELLS](#CELLS) | Τα αρχεία πρέπει να συγκρίνονται ως έγγραφα Excel. |
|
|  | [PDF](#PDF) | Τα αρχεία πρέπει να συγκρίνονται ως έγγραφα PDF. |
|
|  | [IMAGING](#IMAGING) | Τα αρχεία πρέπει να συγκρίνονται ως έγγραφα εικόνας. |
|
|  | [EMAIL](#EMAIL) | Τα αρχεία πρέπει να συγκρίνονται ως έγγραφα email. |
|
|  | [NOTE](#NOTE) | Τα αρχεία πρέπει να συγκρίνονται ως έγγραφα σημειώσεων. |
|
|  | [HTML](#HTML) | Τα αρχεία πρέπει να συγκρίνονται ως έγγραφα HTML. |
|
|  | [DIAGRAM](#DIAGRAM) | Τα αρχεία πρέπει να συγκρίνονται ως έγγραφα διαγράμματος. |
|
|  | [DIFFERENT](#DIFFERENT) | Τα αρχεία πρέπει να συγκρίνονται ως έγγραφα σε διαφορετικές μορφές. |
|
|  | [SVG](#SVG) | Τα αρχεία πρέπει να συγκρίνονται ως έγγραφα SVG. |
|
|  | [UNDEFINED](#UNDEFINED) | Για εσωτερική χρήση. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Αναλύει την αναπαράσταση συμβολοσειράς του ComparisonType για να λάβει τη σταθερά enum. |
|
|  | [toString()](#toString--) | Αναπαράσταση συμβολοσειράς του ComparisonType. |
|
### TEXT {#TEXT}
```
public static final ComparisonType TEXT
```


Τα αρχεία πρέπει να συγκρίνονται ως έγγραφα κειμένου.


### SLIDES {#SLIDES}
```
public static final ComparisonType SLIDES
```


Τα αρχεία πρέπει να συγκρίνονται ως έγγραφα παρουσίασης.


### WORDS {#WORDS}
```
public static final ComparisonType WORDS
```


Τα αρχεία πρέπει να συγκρίνονται ως έγγραφα Word.


### CELLS {#CELLS}
```
public static final ComparisonType CELLS
```


Τα αρχεία πρέπει να συγκρίνονται ως έγγραφα Excel.


### PDF {#PDF}
```
public static final ComparisonType PDF
```


Τα αρχεία πρέπει να συγκρίνονται ως έγγραφα PDF.


### IMAGING {#IMAGING}
```
public static final ComparisonType IMAGING
```


Τα αρχεία πρέπει να συγκρίνονται ως έγγραφα εικόνας.


### EMAIL {#EMAIL}
```
public static final ComparisonType EMAIL
```


Τα αρχεία πρέπει να συγκρίνονται ως έγγραφα email.


### NOTE {#NOTE}
```
public static final ComparisonType NOTE
```


Τα αρχεία πρέπει να συγκρίνονται ως έγγραφα σημειώσεων.


### HTML {#HTML}
```
public static final ComparisonType HTML
```


Τα αρχεία πρέπει να συγκρίνονται ως έγγραφα HTML.


### DIAGRAM {#DIAGRAM}
```
public static final ComparisonType DIAGRAM
```


Τα αρχεία πρέπει να συγκρίνονται ως έγγραφα διαγράμματος.


### DIFFERENT {#DIFFERENT}
```
public static final ComparisonType DIFFERENT
```


Τα αρχεία πρέπει να συγκρίνονται ως έγγραφα σε διαφορετικές μορφές.


### SVG {#SVG}
```
public static final ComparisonType SVG
```


Τα αρχεία πρέπει να συγκρίνονται ως έγγραφα SVG.


### UNDEFINED {#UNDEFINED}
```
public static final ComparisonType UNDEFINED
```


Για εσωτερική χρήση.


### values() {#values--}
```
public static ComparisonType[] values()
```




**Returns:**
com.groupdocs.comparison.options.enums.ComparisonType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static ComparisonType valueOf(String name)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| όνομα | java.lang.String |  |

**Returns:**
[ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static ComparisonType fromString(String toStringValue)
```


Αναλύει την αναπαράσταση συμβολοσειράς του ComparisonType για να λάβει τη σταθερά enum.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | toStringValue | java.lang.String | Η αναπαράσταση συμβολοσειράς του ComparisonType |
|

**Returns:**
[ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) - ComparisonType enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


Αναπαράσταση συμβολοσειράς του ComparisonType.


**Returns:**
java.lang.String - τιμή συμβολοσειράς του σταθερού της enum

