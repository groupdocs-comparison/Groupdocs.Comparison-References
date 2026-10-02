---
title: "FileLogger"
second_title: "GroupDocs.Comparison for Java Αναφορά API"
description: "Καταγραφέας που γράφει τα αρχεία καταγραφής σε αρχείο."
type: docs
weight: 11
url: /el/java/com.groupdocs.comparison.logging/filelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.foundation.logging.ILogger
```
public class FileLogger implements ILogger
```

Καταγραφέας που γράφει τα αρχεία καταγραφής σε αρχείο.


Πρέπει να χρησιμοποιείται μαζί με [ComparisonLogger](../../com.groupdocs.comparison.logging/comparisonlogger).


Παράδειγμα χρήσης:

````

 ComparisonLogger.setLogger(new FileLogger("/path/to/file.log.txt", false, true, true, true));
 
````


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [FileLogger(String filePath)](#FileLogger-java.lang.String-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης FileLogger με τη διαδρομή αρχείου. |
|
|  | [FileLogger(String filePath, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)](#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης FileLogger με τη διαδρομή αρχείου και τη διαμόρφωση επιπέδων καταγραφής. |
|
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [MESSAGE](#MESSAGE) |  |
| [EXCEPTION](#EXCEPTION) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | Γράφει ένα μήνυμα trace στο αρχείο. |
|
|  | [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Γράφει ένα μήνυμα trace στο αρχείο. |
|
|  | [isTraceEnabled()](#isTraceEnabled--) | Ελέγχει αν η καταγραφή trace είναι ενεργοποιημένη. |
|
|  | [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | Γράφει ένα μήνυμα debug στο αρχείο. |
|
|  | [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Γράφει ένα μήνυμα debug στο αρχείο. |
|
|  | [isDebugEnabled()](#isDebugEnabled--) | Ελέγχει αν η καταγραφή debug είναι ενεργοποιημένη. |
|
|  | [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | Γράφει ένα μήνυμα προειδοποίησης στο αρχείο. |
|
|  | [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Γράφει ένα μήνυμα προειδοποίησης στο αρχείο. |
|
|  | [isWarningEnabled()](#isWarningEnabled--) | Ελέγχει αν η καταγραφή προειδοποίησης είναι ενεργοποιημένη. |
|
|  | [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | Γράφει ένα μήνυμα σφάλματος στο αρχείο. |
|
|  | [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Γράφει ένα μήνυμα σφάλματος στο αρχείο. |
|
|  | [isErrorEnabled()](#isErrorEnabled--) | Ελέγχει αν η καταγραφή σφάλματος είναι ενεργοποιημένη. |
|
### FileLogger(String filePath) {#FileLogger-java.lang.String-}
```
public FileLogger(String filePath)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης FileLogger με τη διαδρομή αρχείου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Η διαδρομή προς το αρχείο που θα χρησιμοποιηθεί για την εγγραφή των καταγραφών |
|

### FileLogger(String filePath, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled) {#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-}
```
public FileLogger(String filePath, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης FileLogger με τη διαδρομή αρχείου και τη διαμόρφωση επιπέδων καταγραφής.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Η διαδρομή προς το αρχείο που θα χρησιμοποιηθεί για την εγγραφή των καταγραφών |
|
|  | isTraceEnabled | boolean | Αληθές για ενεργοποίηση της καταγραφής εντοπισμού, ψευδές διαφορετικά |
|
|  | isDebugEnabled | boolean | Αληθές για ενεργοποίηση της καταγραφής αποσφαλμάτωσης, ψευδές διαφορετικά |
|
|  | isWarningEnabled | boolean | Αληθές για ενεργοποίηση της καταγραφής προειδοποιήσεων, ψευδές διαφορετικά |
|
|  | isErrorEnabled | boolean | Αληθές για ενεργοποίηση της καταγραφής σφαλμάτων, ψευδές διαφορετικά |
|

### MESSAGE {#MESSAGE}
```
public static final String MESSAGE
```


### EXCEPTION {#EXCEPTION}
```
public static final String EXCEPTION
```


### trace(String message, Object[] arguments) {#trace-java.lang.String-java.lang.Object...-}
```
public void trace(String message, Object[] arguments)
```


Γράφει ένα μήνυμα trace στο αρχείο.


Τα μηνύματα καταγραφής εντοπισμού παρέχουν μέγιστες λεπτομερείς πληροφορίες σχετικά με τη ροή της εφαρμογής.
Το μήνυμα μπορεί να περιέχει ένα ή λίγα {} που θα αντικατασταθούν από τα αντίστοιχα επιχειρήματα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | message | java.lang.String | Το μήνυμα. |
|
|  | ορίσματα | java.lang.Object[] | Τα ορίσματα, αντικαθιστούν τα {} στο μήνυμα με τη σειρά που περνιούνται, το null θα γραφτεί ως 'null' |
|

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void trace(Throwable throwable, String message, Object[] arguments)
```


Γράφει ένα μήνυμα trace στο αρχείο.


Τα μηνύματα καταγραφής εντοπισμού παρέχουν μέγιστες λεπτομερείς πληροφορίες σχετικά με τη ροή της εφαρμογής.
Το μήνυμα μπορεί να περιέχει ένα ή λίγα {} που θα αντικατασταθούν από τα αντίστοιχα επιχειρήματα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Το αντικείμενο throwable που θα χρησιμοποιηθεί για την απόκτηση του stacktrace |
|
|  | message | java.lang.String | Το μήνυμα. |
|
|  | ορίσματα | java.lang.Object[] | Τα ορίσματα, αντικαθιστούν τα {} στο μήνυμα με τη σειρά που περνιούνται, το null θα γραφτεί ως 'null' |
|

### isTraceEnabled() {#isTraceEnabled--}
```
public boolean isTraceEnabled()
```


Ελέγχει αν η καταγραφή trace είναι ενεργοποιημένη.


**Returns:**
boolean - αληθές αν είναι ενεργοποιημένο, διαφορετικά ψευδές

### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public void debug(String message, Object[] arguments)
```


Γράφει ένα μήνυμα debug στο αρχείο.


Τα μηνύματα καταγραφής αποσφαλμάτωσης παρέχουν πληροφορίες σχετικά με διαφορετικές διαδικασίες στη ροή της εφαρμογής.
Το μήνυμα μπορεί να περιέχει ένα ή λίγα {} που θα αντικατασταθούν από τα αντίστοιχα επιχειρήματα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | message | java.lang.String | Το μήνυμα. |
|
|  | ορίσματα | java.lang.Object[] | Τα ορίσματα, αντικαθιστούν τα {} στο μήνυμα με τη σειρά που περνιούνται, το null θα γραφτεί ως 'null' |
|

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void debug(Throwable throwable, String message, Object[] arguments)
```


Γράφει ένα μήνυμα debug στο αρχείο.


Τα μηνύματα καταγραφής αποσφαλμάτωσης παρέχουν πληροφορίες σχετικά με διαφορετικές διαδικασίες στη ροή της εφαρμογής.
Το μήνυμα μπορεί να περιέχει ένα ή λίγα {} που θα αντικατασταθούν από τα αντίστοιχα επιχειρήματα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Το αντικείμενο throwable που θα χρησιμοποιηθεί για την απόκτηση του stacktrace |
|
|  | message | java.lang.String | Το μήνυμα. |
|
|  | ορίσματα | java.lang.Object[] | Τα ορίσματα, αντικαθιστούν τα {} στο μήνυμα με τη σειρά που περνιούνται, το null θα γραφτεί ως 'null' |
|

### isDebugEnabled() {#isDebugEnabled--}
```
public boolean isDebugEnabled()
```


Ελέγχει αν η καταγραφή debug είναι ενεργοποιημένη.


**Returns:**
boolean - αληθές αν είναι ενεργοποιημένο, διαφορετικά ψευδές

### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public void warning(String message, Object[] arguments)
```


Γράφει ένα μήνυμα προειδοποίησης στο αρχείο.


Τα μηνύματα καταγραφής προειδοποιήσεων παρέχουν πληροφορίες σχετικά με απρόσμενα και ανακτήσιμα γεγονότα στη ροή της εφαρμογής.
Το μήνυμα μπορεί να περιέχει ένα ή λίγα {} που θα αντικατασταθούν από τα αντίστοιχα επιχειρήματα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | message | java.lang.String | Το μήνυμα. |
|
|  | ορίσματα | java.lang.Object[] | Τα ορίσματα, αντικαθιστούν τα {} στο μήνυμα με τη σειρά που περνιούνται, το null θα γραφτεί ως 'null' |
|

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void warning(Throwable throwable, String message, Object[] arguments)
```


Γράφει ένα μήνυμα προειδοποίησης στο αρχείο.


Τα μηνύματα καταγραφής προειδοποιήσεων παρέχουν πληροφορίες σχετικά με απρόσμενα και ανακτήσιμα γεγονότα στη ροή της εφαρμογής.
Το μήνυμα μπορεί να περιέχει ένα ή λίγα {} που θα αντικατασταθούν από τα αντίστοιχα επιχειρήματα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Το αντικείμενο throwable που θα χρησιμοποιηθεί για την απόκτηση του stacktrace |
|
|  | message | java.lang.String | Το μήνυμα. |
|
|  | ορίσματα | java.lang.Object[] | Τα ορίσματα, αντικαθιστούν τα {} στο μήνυμα με τη σειρά που περνιούνται, το null θα γραφτεί ως 'null' |
|

### isWarningEnabled() {#isWarningEnabled--}
```
public boolean isWarningEnabled()
```


Ελέγχει αν η καταγραφή προειδοποίησης είναι ενεργοποιημένη.


**Returns:**
boolean - αληθές αν είναι ενεργοποιημένο, διαφορετικά ψευδές

### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public void error(String message, Object[] arguments)
```


Γράφει ένα μήνυμα σφάλματος στο αρχείο.


Τα μηνύματα καταγραφής σφαλμάτων παρέχουν πληροφορίες σχετικά με μη ανακτήσιμα γεγονότα στη ροή της εφαρμογής.
Το μήνυμα μπορεί να περιέχει ένα ή λίγα {} που θα αντικατασταθούν από τα αντίστοιχα επιχειρήματα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | message | java.lang.String | Το μήνυμα. |
|
|  | ορίσματα | java.lang.Object[] | Τα ορίσματα, αντικαθιστούν τα {} στο μήνυμα με τη σειρά που περνιούνται, το null θα γραφτεί ως 'null' |
|

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void error(Throwable throwable, String message, Object[] arguments)
```


Γράφει ένα μήνυμα σφάλματος στο αρχείο.


Τα μηνύματα καταγραφής σφαλμάτων παρέχουν πληροφορίες σχετικά με μη ανακτήσιμα γεγονότα στη ροή της εφαρμογής.
Το μήνυμα μπορεί να περιέχει ένα ή λίγα {} που θα αντικατασταθούν από τα αντίστοιχα επιχειρήματα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Το αντικείμενο throwable που θα χρησιμοποιηθεί για την απόκτηση του stacktrace |
|
|  | message | java.lang.String | Το μήνυμα. |
|
|  | ορίσματα | java.lang.Object[] | Τα ορίσματα, αντικαθιστούν τα {} στο μήνυμα με τη σειρά που περνιούνται, το null θα γραφτεί ως 'null' |
|

### isErrorEnabled() {#isErrorEnabled--}
```
public boolean isErrorEnabled()
```


Ελέγχει αν η καταγραφή σφάλματος είναι ενεργοποιημένη.


**Returns:**
boolean - αληθές αν είναι ενεργοποιημένο, διαφορετικά ψευδές

