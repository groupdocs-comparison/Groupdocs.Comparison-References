---
title: "SupportedLocales"
second_title: "GroupDocs.Comparison for Java Αναφορά API"
description: "Η κλάση SupportedLocales παρέχει σταθερές που αντιπροσωπεύουν τις υποστηριζόμενες τοπικές ρυθμίσεις (locales) για το GroupDocs.Comparison."
type: docs
weight: 10
url: /el/java/com.groupdocs.comparison.localization/supportedlocales/
---
**Inheritance:**
java.lang.Object
```
public class SupportedLocales
```

Η κλάση SupportedLocales παρέχει σταθερές που αντιπροσωπεύουν τις υποστηριζόμενες τοπικές ρυθμίσεις (locales) για το GroupDocs.Comparison.


Σας επιτρέπει να καθορίσετε την τοπική ρύθμιση για λειτουργίες ειδικές για γλώσσα, όπως η μορφοποίηση και η προβολή μηνυμάτων.


Για περισσότερες πληροφορίες σχετικά με τις τοπικές ρυθμίσεις, ανατρέξτε στην τεκμηρίωση του Java Locale:
[Java Locale](../https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/util/Locale.html)


Παράδειγμα χρήσης:

````

 final boolean localeSupported = SupportedLocales.isLocaleSupported(Locale.CANADA);
 
````


## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [isLocaleSupported(String localeString)](#isLocaleSupported-java.lang.String-) | Καθορίζει εάν η τοπική ρύθμιση υποστηρίζεται ή όχι. |
|
|  | [isLocaleSupported(Locale locale)](#isLocaleSupported-java.util.Locale-) | Καθορίζει εάν η τοπική ρύθμιση υποστηρίζεται ή όχι. |
|
|  | [isLocaleSupported(CultureInfo culture)](#isLocaleSupported-com.groupdocs.foundation.utils.CultureInfo-) | Καθορίζει εάν η τοπική ρύθμιση, που αναπαρίσταται ως CultureInfo, υποστηρίζεται ή όχι. |
|
### isLocaleSupported(String localeString) {#isLocaleSupported-java.lang.String-}
```
public static boolean isLocaleSupported(String localeString)
```


Καθορίζει εάν η τοπική ρύθμιση υποστηρίζεται ή όχι.
Η μορφή του localeString είναι xx-YY ή xx_YY, παραδείγματα: en-US, en_US


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | localeString | java.lang.String | Η τοπική ρύθμιση που θα ελεγχθεί, μπορεί να είναι null |
|

**Returns:**
boolean - true εάν υποστηρίζεται, διαφορετικά false

### isLocaleSupported(Locale locale) {#isLocaleSupported-java.util.Locale-}
```
public static boolean isLocaleSupported(Locale locale)
```


Καθορίζει εάν η τοπική ρύθμιση υποστηρίζεται ή όχι.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | locale | java.util.Locale | Η τοπική ρύθμιση που θα ελεγχθεί, δεν είναι null |
|

**Returns:**
boolean - true εάν υποστηρίζεται, διαφορετικά false

### isLocaleSupported(CultureInfo culture) {#isLocaleSupported-com.groupdocs.foundation.utils.CultureInfo-}
```
public static boolean isLocaleSupported(CultureInfo culture)
```


Καθορίζει εάν η τοπική ρύθμιση, που αναπαρίσταται ως CultureInfo, υποστηρίζεται ή όχι.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | culture | com.groupdocs.foundation.utils.CultureInfo | Η culture που θα ελεγχθεί, δεν είναι null |
|

**Returns:**
boolean - true εάν υποστηρίζεται, διαφορετικά false

