---
title: "Metered"
second_title: "GroupDocs.Comparison for Java Αναφορά API"
description: "Παρέχει μεθόδους για την εφαρμογή μετρημένης άδειας στο Comparison."
type: docs
weight: 11
url: /el/java/com.groupdocs.comparison.license/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Παρέχει μεθόδους για την εφαρμογή μετρημένης άδειας στο Comparison.

* More about GroupDocs.Comparison licensing: [Evaluation Limitations and Licensing](../https://docs.groupdocs.com/display/comparisonjava/Evaluation+Limitations+and+Licensing+of+GroupDocs.Comparison)


Σύντομο παράδειγμα χρήσης:

````

 final Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 
````


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [Metered()](#Metered--) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Metered. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getConsumptionQuantity()](#getConsumptionQuantity--) | Λαμβάνει την ποσότητα κατανάλωσης. |
|
|  | [getConsumptionCredit()](#getConsumptionCredit--) | Ανακτά το ποσό των χρησιμοποιημένων πιστώσεων. |
|
|  | [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Εφαρμόζει μετρημένη άδεια χρησιμοποιώντας δημόσια και ιδιωτικά κλειδιά. |
|
### Metered() {#Metered--}
```
public Metered()
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Metered.


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


Λαμβάνει την ποσότητα κατανάλωσης.


**Returns:**
double - ποσότητα κατανάλωσης

### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


Ανακτά το ποσό των χρησιμοποιημένων πιστώσεων.


**Returns:**
double - αριθμός ήδη χρησιμοποιημένων πιστώσεων

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


Εφαρμόζει μετρημένη άδεια χρησιμοποιώντας δημόσια και ιδιωτικά κλειδιά.


Παράδειγμα χρήσης:

````

 final Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 
````



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | publicKey | java.lang.String | Δημόσιο κλειδί |
|
|  | privateKey | java.lang.String | Ιδιωτικό κλειδί |
|

