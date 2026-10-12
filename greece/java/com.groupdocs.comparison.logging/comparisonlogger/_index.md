---
title: "ComparisonLogger"
second_title: "GroupDocs.Comparison for Java Αναφορά API"
description: "Υλοποιεί μεθόδους καταγραφής και έναν τρόπο για να διαμορφώσετε ενσωματωμένο ή προσαρμοσμένο από τον χρήστη καταγραφέα."
type: docs
weight: 10
url: /el/java/com.groupdocs.comparison.logging/comparisonlogger/
---
**Inheritance:**
java.lang.Object
```
public class ComparisonLogger
```

Υλοποιεί μεθόδους καταγραφής και έναν τρόπο για να διαμορφώσετε ενσωματωμένο ή προσαρμοσμένο από τον χρήστη καταγραφέα.


Η κλάση επιτρέπει τη ρύθμιση ενσωματωμένου ή προσαρμοσμένου logger και την εγγραφή μηνυμάτων καταγραφής.


Παράδειγμα χρήσης:

````

 ComparisonLogger.setLogger(new com.groupdocs.comparison.logging.ConsoleLogger(false, true, true, true));
 ComparisonLogger.warning(exceptionObject, "Warning message with parameters: {}, {}", "parameter1", 2);
 
````


## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | Γράφει μήνυμα trace στον προρυθμισμένο logger. |
|
|  | [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Γράφει μήνυμα trace, stacktrace και μήνυμα από εξαίρεση στον προρυθμισμένο logger. |
|
|  | [isTraceEnabled()](#isTraceEnabled--) | Ελέγχει εάν η καταγραφή trace είναι ενεργοποιημένη στον προρυθμισμένο logger. |
|
|  | [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | Γράφει μήνυμα debug στον προρυθμισμένο logger. |
|
|  | [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Γράφει μήνυμα debug, stacktrace και μήνυμα από εξαίρεση στον προρυθμισμένο logger. |
|
|  | [isDebugEnabled()](#isDebugEnabled--) | Ελέγχει εάν η καταγραφή debug είναι ενεργοποιημένη στον προρυθμισμένο logger. |
|
|  | [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | Γράφει μήνυμα προειδοποίησης στον προρυθμισμένο logger. |
|
|  | [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Γράφει μήνυμα προειδοποίησης, stacktrace και μήνυμα από εξαίρεση στον προρυθμισμένο logger. |
|
|  | [isWarningEnabled()](#isWarningEnabled--) | Ελέγχει εάν η καταγραφή προειδοποίησης είναι ενεργοποιημένη στον προρυθμισμένο logger. |
|
|  | [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | Γράφει μήνυμα σφάλματος στον προρυθμισμένο logger. |
|
|  | [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Γράφει μήνυμα σφάλματος, stacktrace και μήνυμα από εξαίρεση στον προρυθμισμένο logger. |
|
|  | [isErrorEnabled()](#isErrorEnabled--) | Ελέγχει εάν η καταγραφή σφάλματος είναι ενεργοποιημένη στον προρυθμισμένο logger. |
|
|  | [getLogger()](#getLogger--) | Αποκτά τον προρυθμισμένο logger που θα χρησιμοποιηθεί για την εγγραφή όλων των τύπων καταγραφών. |
|
|  | [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | Ορίζει τον logger που θα χρησιμοποιηθεί για την εγγραφή όλων των τύπων καταγραφών. |
|
### trace(String message, Object[] arguments) {#trace-java.lang.String-java.lang.Object...-}
```
public static void trace(String message, Object[] arguments)
```


Γράφει μήνυμα trace στον προρυθμισμένο logger.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | message | java.lang.String | Το μήνυμα, εάν είναι null, η συμπεριφορά εξαρτάται από τον logger |
|
|  | ορίσματα | java.lang.Object[] | Τα επιχειρήματα που θα ενσωματωθούν στο μήνυμα, εάν είναι null, η συμπεριφορά εξαρτάται από τον logger |
|

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void trace(Throwable throwable, String message, Object[] arguments)
```


Γράφει μήνυμα trace, stacktrace και μήνυμα από εξαίρεση στον προρυθμισμένο logger.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Το αντικείμενο throwable που θα χρησιμοποιηθεί για την λήψη του stacktrace, εάν είναι null, η συμπεριφορά εξαρτάται από τον logger |
|
|  | message | java.lang.String | Το μήνυμα, εάν είναι null, η συμπεριφορά εξαρτάται από τον logger |
|
|  | ορίσματα | java.lang.Object[] | Τα επιχειρήματα που θα ενσωματωθούν στο μήνυμα, εάν είναι null, η συμπεριφορά εξαρτάται από τον logger |
|

### isTraceEnabled() {#isTraceEnabled--}
```
public static boolean isTraceEnabled()
```


Ελέγχει εάν η καταγραφή trace είναι ενεργοποιημένη στον προρυθμισμένο logger.


**Returns:**
boolean - true εάν είναι ενεργοποιημένο στον προρυθμισμένο logger, αλλιώς false

### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public static void debug(String message, Object[] arguments)
```


Γράφει μήνυμα debug στον προρυθμισμένο logger.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | message | java.lang.String | Το μήνυμα, εάν είναι null, η συμπεριφορά εξαρτάται από τον logger |
|
|  | ορίσματα | java.lang.Object[] | Τα επιχειρήματα που θα ενσωματωθούν στο μήνυμα, εάν είναι null, η συμπεριφορά εξαρτάται από τον logger |
|

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void debug(Throwable throwable, String message, Object[] arguments)
```


Γράφει μήνυμα debug, stacktrace και μήνυμα από εξαίρεση στον προρυθμισμένο logger.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Το αντικείμενο throwable που θα χρησιμοποιηθεί για την λήψη του stacktrace, εάν είναι null, η συμπεριφορά εξαρτάται από τον logger |
|
|  | message | java.lang.String | Το μήνυμα, εάν είναι null, η συμπεριφορά εξαρτάται από τον logger |
|
|  | ορίσματα | java.lang.Object[] | Τα επιχειρήματα που θα ενσωματωθούν στο μήνυμα, εάν είναι null, η συμπεριφορά εξαρτάται από τον logger |
|

### isDebugEnabled() {#isDebugEnabled--}
```
public static boolean isDebugEnabled()
```


Ελέγχει εάν η καταγραφή debug είναι ενεργοποιημένη στον προρυθμισμένο logger.


**Returns:**
boolean - true εάν είναι ενεργοποιημένο στον προρυθμισμένο logger, αλλιώς false

### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public static void warning(String message, Object[] arguments)
```


Γράφει μήνυμα προειδοποίησης στον προρυθμισμένο logger.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | message | java.lang.String | Το μήνυμα, εάν είναι null, η συμπεριφορά εξαρτάται από τον logger |
|
|  | ορίσματα | java.lang.Object[] | Τα επιχειρήματα που θα ενσωματωθούν στο μήνυμα, εάν είναι null, η συμπεριφορά εξαρτάται από τον logger |
|

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void warning(Throwable throwable, String message, Object[] arguments)
```


Γράφει μήνυμα προειδοποίησης, stacktrace και μήνυμα από εξαίρεση στον προρυθμισμένο logger.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Το αντικείμενο throwable που θα χρησιμοποιηθεί για την λήψη του stacktrace, εάν είναι null, η συμπεριφορά εξαρτάται από τον logger |
|
|  | message | java.lang.String | Το μήνυμα, εάν είναι null, η συμπεριφορά εξαρτάται από τον logger |
|
|  | ορίσματα | java.lang.Object[] | Τα επιχειρήματα που θα ενσωματωθούν στο μήνυμα, εάν είναι null, η συμπεριφορά εξαρτάται από τον logger |
|

### isWarningEnabled() {#isWarningEnabled--}
```
public static boolean isWarningEnabled()
```


Ελέγχει εάν η καταγραφή προειδοποίησης είναι ενεργοποιημένη στον προρυθμισμένο logger.


**Returns:**
boolean - true εάν είναι ενεργοποιημένο στον προρυθμισμένο logger, αλλιώς false

### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public static void error(String message, Object[] arguments)
```


Γράφει μήνυμα σφάλματος στον προρυθμισμένο logger.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | message | java.lang.String | Το μήνυμα, εάν είναι null, η συμπεριφορά εξαρτάται από τον logger |
|
|  | ορίσματα | java.lang.Object[] | Τα επιχειρήματα που θα ενσωματωθούν στο μήνυμα, εάν είναι null, η συμπεριφορά εξαρτάται από τον logger |
|

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void error(Throwable throwable, String message, Object[] arguments)
```


Γράφει μήνυμα σφάλματος, stacktrace και μήνυμα από εξαίρεση στον προρυθμισμένο logger.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Το αντικείμενο throwable που θα χρησιμοποιηθεί για την λήψη του stacktrace, εάν είναι null, η συμπεριφορά εξαρτάται από τον logger |
|
|  | message | java.lang.String | Το μήνυμα, εάν είναι null, η συμπεριφορά εξαρτάται από τον logger |
|
|  | ορίσματα | java.lang.Object[] | Τα επιχειρήματα που θα ενσωματωθούν στο μήνυμα, εάν είναι null, η συμπεριφορά εξαρτάται από τον logger |
|

### isErrorEnabled() {#isErrorEnabled--}
```
public static boolean isErrorEnabled()
```


Ελέγχει εάν η καταγραφή σφάλματος είναι ενεργοποιημένη στον προρυθμισμένο logger.


**Returns:**
boolean - true εάν είναι ενεργοποιημένο στον προρυθμισμένο logger, αλλιώς false

### getLogger() {#getLogger--}
```
public static synchronized ILogger getLogger()
```


Αποκτά τον προρυθμισμένο logger που θα χρησιμοποιηθεί για την εγγραφή όλων των τύπων καταγραφών.


**Returns:**
com.groupdocs.foundation.logging.ILogger - ο logger

### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public static synchronized void setLogger(ILogger logger)
```


Ορίζει τον logger που θα χρησιμοποιηθεί για την εγγραφή όλων των τύπων καταγραφών.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | logger | com.groupdocs.foundation.logging.ILogger | Ο logger |
|

