---
title: "MetadataType"
second_title: "GroupDocs.Comparison for Java Αναφορά API"
description: "Καθορίζει από πού το τελικό έγγραφο θα λάβει τις μεταδεδομένες πληροφορίες."
type: docs
weight: 12
url: /el/java/com.groupdocs.comparison.options.enums/metadatatype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum MetadataType extends Enum<MetadataType>
```

Καθορίζει από πού το τελικό έγγραφο θα λάβει τις μεταδεδομένες πληροφορίες.


Παράδειγμα χρήσης:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    SaveOptions saveOptions = new SaveOptions();
    saveOptions.setCloneMetadataType(MetadataType.FILE_AUTHOR);

    comparer.compare(resultFile, saveOptions);
 }
 
````


## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [DEFAULT](#DEFAULT) | Τα μεταδεδομένα θα παραμείνουν όπως είναι. |
|
|  | [SOURCE](#SOURCE) | Metedata θα ληφθεί από το έγγραφο προέλευσης. |
|
|  | [TARGET](#TARGET) | Metedata θα ληφθεί από το έγγραφο προορισμού. |
|
|  | [FILE_AUTHOR](#FILE-AUTHOR) | Metedata θα οριστεί από τον χρήστη. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Αναλύει την αναπαράσταση συμβολοσειράς του MetadataType για να λάβει τη σταθερά enum. |
|
|  | [toString()](#toString--) | Αναπαράσταση συμβολοσειράς του MetadataType. |
|
### DEFAULT {#DEFAULT}
```
public static final MetadataType DEFAULT
```


Τα μεταδεδομένα θα παραμείνουν όπως είναι.


### SOURCE {#SOURCE}
```
public static final MetadataType SOURCE
```


Metedata θα ληφθεί από το έγγραφο προέλευσης.


### TARGET {#TARGET}
```
public static final MetadataType TARGET
```


Metedata θα ληφθεί από το έγγραφο προορισμού.


### FILE_AUTHOR {#FILE-AUTHOR}
```
public static final MetadataType FILE_AUTHOR
```


Metedata θα οριστεί από τον χρήστη.


### values() {#values--}
```
public static MetadataType[] values()
```




**Returns:**
com.groupdocs.comparison.options.enums.MetadataType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static MetadataType valueOf(String name)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| όνομα | java.lang.String |  |

**Returns:**
[MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static MetadataType fromString(String toStringValue)
```


Αναλύει την αναπαράσταση συμβολοσειράς του MetadataType για να λάβει τη σταθερά enum.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | toStringValue | java.lang.String | Η αναπαράσταση συμβολοσειράς του MetadataType |
|

**Returns:**
[MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) - MetadataType enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


Αναπαράσταση συμβολοσειράς του MetadataType.


**Returns:**
java.lang.String - τιμή συμβολοσειράς του σταθερού της enum

