---
title: "StyleSettings"
second_title: "GroupDocs.Comparison for Java Αναφορά API"
description: "Αυτή η κλάση αντιπροσωπεύει τις ρυθμίσεις στυλ για τη μορφοποίηση κειμένου."
type: docs
weight: 12
url: /el/java/com.groupdocs.comparison.options.style/stylesettings/
---
**Inheritance:**
java.lang.Object
```
public class StyleSettings
```

Αυτή η κλάση αντιπροσωπεύει τις ρυθμίσεις στυλ για τη μορφοποίηση κειμένου.


Χρησιμοποιήστε αυτήν την κλάση για να προσαρμόσετε το χρώμα γραμματοσειράς, το χρώμα επισήμανσης, τα χαρακτηριστικά στυλ (bold, underline, italic, strikethrough),
διαχωριστές συμβολοσειρών, αρχικά μεγέθη και διαχωριστές λέξεων για κείμενο.


Παράδειγμα χρήσης:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    StyleSettings styleSettings = new StyleSettings();
    styleSettings.setFontColor(Color.GREEN);
    styleSettings.setBold(true);
    styleSettings.setUnderline(true);

    final CompareOptions compareOptions = new CompareOptions();
    compareOptions.setInsertedItemStyle(styleSettings);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [StyleSettings()](#StyleSettings--) | Αρχικοποιεί ένα νέο παράδειγμα της κλάσης StyleSettings. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getFontColor()](#getFontColor--) | Λαμβάνει το χρώμα γραμματοσειράς. |
|
|  | [setFontColor(Color value)](#setFontColor-java.awt.Color-) | Ορίζει το χρώμα γραμματοσειράς. |
|
|  | [getShapeColor()](#getShapeColor--) | Λαμβάνει το χρώμα σχήματος. |
|
|  | [setShapeColor(Color value)](#setShapeColor-java.awt.Color-) | Ορίζει το χρώμα σχήματος. |
|
|  | [getHighlightColor()](#getHighlightColor--) | Λαμβάνει το χρώμα επισήμανσης. |
|
|  | [setHighlightColor(Color value)](#setHighlightColor-java.awt.Color-) | Ορίζει το χρώμα επισήμανσης. |
|
|  | [isBold()](#isBold--) | Λαμβάνει μια σημαία που υποδεικνύει αν το κείμενο θα είναι έντονο ή όχι. |
|
|  | [setBold(boolean value)](#setBold-boolean-) | Ορίζει μια σημαία που υποδεικνύει αν το κείμενο πρέπει να είναι έντονο ή όχι. |
|
|  | [isUnderline()](#isUnderline--) | Λαμβάνει μια σημαία που υποδεικνύει αν το κείμενο θα είναι υπογραμμισμένο ή όχι. |
|
|  | [setUnderline(boolean value)](#setUnderline-boolean-) | Ορίζει μια σημαία που υποδεικνύει αν το κείμενο πρέπει να είναι υπογραμμισμένο ή όχι. |
|
|  | [isItalic()](#isItalic--) | Λαμβάνει μια σημαία που υποδεικνύει αν το κείμενο θα είναι πλάγιο ή όχι. |
|
|  | [setItalic(boolean value)](#setItalic-boolean-) | Ορίζει μια σημαία που υποδεικνύει αν το κείμενο πρέπει να είναι πλάγιο ή όχι. |
|
|  | [isStrikethrough()](#isStrikethrough--) | Λαμβάνει μια σημαία που υποδεικνύει αν το κείμενο θα είναι διαγραμμισμένο ή όχι. |
|
|  | [setStrikethrough(boolean value)](#setStrikethrough-boolean-) | Ορίζει μια σημαία που υποδεικνύει αν το κείμενο πρέπει να είναι διαγραμμισμένο ή όχι. |
|
|  | [getStartStringSeparator()](#getStartStringSeparator--) | Λαμβάνει το διαχωριστικό έναρξης συμβολοσειράς. |
|
|  | [setStartStringSeparator(String value)](#setStartStringSeparator-java.lang.String-) | Ορίζει το διαχωριστικό έναρξης συμβολοσειράς. |
|
|  | [getEndStringSeparator()](#getEndStringSeparator--) | Λαμβάνει το διαχωριστικό λήξης συμβολοσειράς. |
|
|  | [setEndStringSeparator(String value)](#setEndStringSeparator-java.lang.String-) | Ορίζει το διαχωριστικό λήξης συμβολοσειράς. |
|
|  | [getOriginalSize()](#getOriginalSize--) | Λαμβάνει το αρχικό μέγεθος των εγγράφων σύγκρισης. |
|
|  | [setOriginalSize(Size value)](#setOriginalSize-com.groupdocs.comparison.options.style.Size-) | Ορίζει το αρχικό μέγεθος των εγγράφων σύγκρισης. |
|
|  | [getWordsSeparators()](#getWordsSeparators--) | Λαμβάνει τους χαρακτήρες διαχωρισμού λέξεων. |
|
|  | [setWordsSeparators(char[] value)](#setWordsSeparators-char---) | Ορίζει τους χαρακτήρες διαχωρισμού λέξεων. |
|
### StyleSettings() {#StyleSettings--}
```
public StyleSettings()
```


Αρχικοποιεί ένα νέο παράδειγμα της κλάσης StyleSettings.


### getFontColor() {#getFontColor--}
```
public final Color getFontColor()
```


Λαμβάνει το χρώμα γραμματοσειράς.


**Returns:**
java.awt.Color - το χρώμα γραμματοσειράς.

### setFontColor(Color value) {#setFontColor-java.awt.Color-}
```
public final void setFontColor(Color value)
```


Ορίζει το χρώμα γραμματοσειράς.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | java.awt.Color | Το νέο χρώμα γραμματοσειράς. |
|

### getShapeColor() {#getShapeColor--}
```
public final Color getShapeColor()
```


Λαμβάνει το χρώμα σχήματος.


**Returns:**
java.awt.Color - το χρώμα σχήματος.

### setShapeColor(Color value) {#setShapeColor-java.awt.Color-}
```
public final void setShapeColor(Color value)
```


Ορίζει το χρώμα σχήματος.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | java.awt.Color | Το νέο χρώμα σχήματος. |
|

### getHighlightColor() {#getHighlightColor--}
```
public final Color getHighlightColor()
```


Λαμβάνει το χρώμα επισήμανσης.


**Returns:**
java.awt.Color - το χρώμα επισήμανσης.

### setHighlightColor(Color value) {#setHighlightColor-java.awt.Color-}
```
public final void setHighlightColor(Color value)
```


Ορίζει το χρώμα επισήμανσης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | java.awt.Color | Το νέο χρώμα επισήμανσης. |
|

### isBold() {#isBold--}
```
public final boolean isBold()
```


Λαμβάνει μια σημαία που υποδεικνύει αν το κείμενο θα είναι έντονο ή όχι.


**Returns:**
boolean - true εάν το κείμενο θα είναι έντονο, false διαφορετικά.

### setBold(boolean value) {#setBold-boolean-}
```
public final void setBold(boolean value)
```


Ορίζει μια σημαία που υποδεικνύει αν το κείμενο πρέπει να είναι έντονο ή όχι.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | boolean | true εάν το κείμενο πρέπει να είναι έντονο, false διαφορετικά. |
|

### isUnderline() {#isUnderline--}
```
public final boolean isUnderline()
```


Λαμβάνει μια σημαία που υποδεικνύει αν το κείμενο θα είναι υπογραμμισμένο ή όχι.


**Returns:**
boolean - true εάν το κείμενο θα είναι υπογραμμισμένο, false διαφορετικά.

### setUnderline(boolean value) {#setUnderline-boolean-}
```
public final void setUnderline(boolean value)
```


Ορίζει μια σημαία που υποδεικνύει αν το κείμενο πρέπει να είναι υπογραμμισμένο ή όχι.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | boolean | true εάν το κείμενο πρέπει να είναι υπογραμμισμένο, false διαφορετικά. |
|

### isItalic() {#isItalic--}
```
public final boolean isItalic()
```


Λαμβάνει μια σημαία που υποδεικνύει αν το κείμενο θα είναι πλάγιο ή όχι.


**Returns:**
boolean - true εάν το κείμενο θα είναι πλάγιο, false διαφορετικά.

### setItalic(boolean value) {#setItalic-boolean-}
```
public final void setItalic(boolean value)
```


Ορίζει μια σημαία που υποδεικνύει αν το κείμενο πρέπει να είναι πλάγιο ή όχι.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | boolean | true εάν το κείμενο πρέπει να είναι πλάγιο, false διαφορετικά. |
|

### isStrikethrough() {#isStrikethrough--}
```
public final boolean isStrikethrough()
```


Λαμβάνει μια σημαία που υποδεικνύει αν το κείμενο θα είναι διαγραμμισμένο ή όχι.


**Returns:**
boolean - true εάν το κείμενο θα είναι διαγραμμισμένο, false διαφορετικά.

### setStrikethrough(boolean value) {#setStrikethrough-boolean-}
```
public final void setStrikethrough(boolean value)
```


Ορίζει μια σημαία που υποδεικνύει αν το κείμενο πρέπει να είναι διαγραμμισμένο ή όχι.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | boolean | true εάν το κείμενο πρέπει να είναι διαγραμμισμένο, false διαφορετικά. |
|

### getStartStringSeparator() {#getStartStringSeparator--}
```
public final String getStartStringSeparator()
```


Λαμβάνει το διαχωριστικό έναρξης συμβολοσειράς.


**Returns:**
java.lang.String - το διαχωριστικό αρχικού συμβολοσειράς.

### setStartStringSeparator(String value) {#setStartStringSeparator-java.lang.String-}
```
public final void setStartStringSeparator(String value)
```


Ορίζει το διαχωριστικό έναρξης συμβολοσειράς.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | java.lang.String | Το νέο διαχωριστικό αρχικού συμβολοσειράς. |
|

### getEndStringSeparator() {#getEndStringSeparator--}
```
public final String getEndStringSeparator()
```


Λαμβάνει το διαχωριστικό λήξης συμβολοσειράς.


**Returns:**
java.lang.String - το διαχωριστικό τελικού συμβολοσειράς.

### setEndStringSeparator(String value) {#setEndStringSeparator-java.lang.String-}
```
public final void setEndStringSeparator(String value)
```


Ορίζει το διαχωριστικό λήξης συμβολοσειράς.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | java.lang.String | Το νέο διαχωριστικό τελικού συμβολοσειράς. |
|

### getOriginalSize() {#getOriginalSize--}
```
public final Size getOriginalSize()
```


Λαμβάνει το αρχικό μέγεθος των εγγράφων σύγκρισης.


**Returns:**
[Size](../../com.groupdocs.comparison.options.style/size) - the original size of comparing documents.

### setOriginalSize(Size value) {#setOriginalSize-com.groupdocs.comparison.options.style.Size-}
```
public final void setOriginalSize(Size value)
```


Ορίζει το αρχικό μέγεθος των εγγράφων σύγκρισης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [Size](../../com.groupdocs.comparison.options.style/size) | Το νέο αρχικό μέγεθος των εγγράφων σύγκρισης. |
|

### getWordsSeparators() {#getWordsSeparators--}
```
public final char[] getWordsSeparators()
```


Λαμβάνει τους χαρακτήρες διαχωρισμού λέξεων.


**Returns:**
char[] - τα διαχωριστικά λέξεων.

### setWordsSeparators(char[] value) {#setWordsSeparators-char---}
```
public final void setWordsSeparators(char[] value)
```


Ορίζει τους χαρακτήρες διαχωρισμού λέξεων.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | char[] | Τα νέα διαχωριστικά λέξεων. |
|

