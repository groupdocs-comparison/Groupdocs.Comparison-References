---
title: "DetalisationLevel"
second_title: "GroupDocs.Comparison for Java Αναφορά API"
description: "Καθορίζει το επίπεδο λεπτομερειών της σύγκρισης."
type: docs
weight: 13
url: /el/java/com.groupdocs.comparison.options.style/detalisationlevel/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DetalisationLevel extends Enum<DetalisationLevel>
```

Καθορίζει το επίπεδο λεπτομερειών της σύγκρισης.


Παράδειγμα χρήσης:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setDetectStyleChanges(false);
    compareOptions.setDetalisationLevel(DetalisationLevel.HIGH);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [LOW](#LOW) | Αντιπροσωπεύει το χαμηλό επίπεδο σύγκρισης. |
|
|  | [MIDDLE](#MIDDLE) | Αντιπροσωπεύει το μεσαίο επίπεδο σύγκρισης. |
|
|  | [HIGH](#HIGH) | Αντιπροσωπεύει το υψηλό επίπεδο σύγκρισης. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Αναλύει την αναπαράσταση συμβολοσειράς του DetalisationLevel για να πάρει το σταθερό της enum. |
|
|  | [toString()](#toString--) | Αναπαράσταση συμβολοσειράς του DetalisationLevel. |
|
### LOW {#LOW}
```
public static final DetalisationLevel LOW
```


Αντιπροσωπεύει το χαμηλό επίπεδο σύγκρισης.


Το επίπεδο "Low" παρέχει την καλύτερη ταχύτητα για συγκρίσεις, αλλά θυσιάζει την ποιότητα σύγκρισης.
Η σύγκριση εκτελείται ανά λέξη.


### MIDDLE {#MIDDLE}
```
public static final DetalisationLevel MIDDLE
```


Αντιπροσωπεύει το μεσαίο επίπεδο σύγκρισης.


Το επίπεδο "Middle" είναι ένας λογικός συμβιβασμός μεταξύ ταχύτητας σύγκρισης και ποιότητας.
Η σύγκριση εκτελείται ανά χαρακτήρα, αλλά αγνοώντας τη διάκριση πεζών-κεφαλαίων και τον αριθμό των κενών.


### HIGH {#HIGH}
```
public static final DetalisationLevel HIGH
```


Αντιπροσωπεύει το υψηλό επίπεδο σύγκρισης.


Το επίπεδο "High" προσφέρει την καλύτερη ποιότητα σύγκρισης, αλλά τη χαμηλότερη ταχύτητα.
Η σύγκριση εκτελείται ανά χαρακτήρα λαμβάνοντας υπόψη τη διάκριση πεζών-κεφαλαίων και τον αριθμό των κενών.


### values() {#values--}
```
public static DetalisationLevel[] values()
```




**Returns:**
com.groupdocs.comparison.options.style.DetalisationLevel[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static DetalisationLevel valueOf(String name)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| όνομα | java.lang.String |  |

**Returns:**
[DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static DetalisationLevel fromString(String toStringValue)
```


Αναλύει την αναπαράσταση συμβολοσειράς του DetalisationLevel για να πάρει το σταθερό της enum.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | toStringValue | java.lang.String | Η αναπαράσταση συμβολοσειράς του DetalisationLevel |
|

**Returns:**
[DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) - DetalisationLevel enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


Αναπαράσταση συμβολοσειράς του DetalisationLevel.


**Returns:**
java.lang.String - τιμή συμβολοσειράς του σταθερού της enum

