---
title: "ComparerSettings"
second_title: "GroupDocs.Comparison for Java Αναφορά API"
description: "Ορίζει ρυθμίσεις για την προσαρμογή της συμπεριφοράς της κλάσης."
type: docs
weight: 11
url: /el/java/com.groupdocs.comparison/comparersettings/
---
**Inheritance:**
java.lang.Object
```
public class ComparerSettings
```

Ορίζει ρυθμίσεις για την προσαρμογή της συμπεριφοράς της κλάσης [Comparer](../../com.groupdocs.comparison/comparer).


Παράδειγμα χρήσης:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     final ComparerSettings comparerSettings = new ComparerSettings();
     comparerSettings.setLogger(new ConsoleLogger(false, false, true, true));

     comparer.compare(resultFile, comparerSettings);
 }
 
````


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [ComparerSettings()](#ComparerSettings--) | Δημιουργεί μια νέα παρουσία της κλάσης ComparerSettings. |
|
|  | [ComparerSettings(ILogger logger)](#ComparerSettings-com.groupdocs.foundation.logging.ILogger-) | Δημιουργεί μια νέα παρουσία της κλάσης ComparerSettings. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getLogger()](#getLogger--) | Λαμβάνει την υλοποίηση του logger που χρησιμοποιείται για την καταγραφή. |
|
|  | [setLogger(ILogger value)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | Ορίζει την υλοποίηση του logger για την καταγραφή. |
|
### ComparerSettings() {#ComparerSettings--}
```
public ComparerSettings()
```


Δημιουργεί μια νέα παρουσία της κλάσης ComparerSettings.


### ComparerSettings(ILogger logger) {#ComparerSettings-com.groupdocs.foundation.logging.ILogger-}
```
public ComparerSettings(ILogger logger)
```


Δημιουργεί μια νέα παρουσία της κλάσης ComparerSettings.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | logger | com.groupdocs.foundation.logging.ILogger | logger προς χρήση |
|

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


Λαμβάνει την υλοποίηση του logger που χρησιμοποιείται για την καταγραφή.


**Returns:**
com.groupdocs.foundation.logging.ILogger - ο logger

### setLogger(ILogger value) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public final void setLogger(ILogger value)
```


Ορίζει την υλοποίηση του logger για την καταγραφή.


Χρησιμοποιήστε com.groupdocs.foundation.logging.NullLogger#NULL_LOGGER.NULL_LOGGER για να απενεργοποιήσετε την καταγραφή.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | com.groupdocs.foundation.logging.ILogger | η υλοποίηση του logger προς ορισμό |
|

