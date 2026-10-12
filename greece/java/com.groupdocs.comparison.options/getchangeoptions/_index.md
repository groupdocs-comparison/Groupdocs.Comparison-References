---
title: "GetChangeOptions"
second_title: "GroupDocs.Comparison for Java Αναφορά API"
description: "Επιτρέπει τη διαμόρφωση φιλτραρίσματος για την ανάκτηση συγκεκριμένων τύπων αλλαγών από το αποτέλεσμα της σύγκρισης."
type: docs
weight: 13
url: /el/java/com.groupdocs.comparison.options/getchangeoptions/
---
**Inheritance:**
java.lang.Object
```
public class GetChangeOptions
```

Επιτρέπει τη διαμόρφωση φιλτραρίσματος για την ανάκτηση συγκεκριμένων τύπων αλλαγών από το αποτέλεσμα της σύγκρισης.


Παράδειγμα χρήσης:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);
     comparer.compare();

     GetChangeOptions getChangeOptions = new GetChangeOptions();

     getChangeOptions.setFilter(ChangeType.DELETED);

     ChangeInfo[] changes = comparer.getChanges(getChangeOptions);
     System.out.println(Arrays.toString(changes));
 }
 
````


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [GetChangeOptions()](#GetChangeOptions--) | Αρχικοποιεί μια νέα παρουσία της κλάσης GetChangeOptions. |
|
|  | [GetChangeOptions(ChangeType filter)](#GetChangeOptions-com.groupdocs.comparison.result.ChangeType-) | Αρχικοποιεί μια νέα παρουσία της κλάσης GetChangeOptions για τον καθορισμένο τύπο φίλτρου. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getFilter()](#getFilter--) | Λαμβάνει το φίλτρο για την ανάκτηση συγκεκριμένων τύπων αλλαγών από το αποτέλεσμα σύγκρισης. |
|
|  | [setFilter(ChangeType value)](#setFilter-com.groupdocs.comparison.result.ChangeType-) | Ορίζει το φίλτρο για την ανάκτηση συγκεκριμένων τύπων αλλαγών από το αποτέλεσμα σύγκρισης. |
|
### GetChangeOptions() {#GetChangeOptions--}
```
public GetChangeOptions()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης GetChangeOptions.


### GetChangeOptions(ChangeType filter) {#GetChangeOptions-com.groupdocs.comparison.result.ChangeType-}
```
public GetChangeOptions(ChangeType filter)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης GetChangeOptions για τον καθορισμένο τύπο φίλτρου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filter | [ChangeType](../../com.groupdocs.comparison.result/changetype) |  |

### getFilter() {#getFilter--}
```
public final ChangeType getFilter()
```


Λαμβάνει το φίλτρο για την ανάκτηση συγκεκριμένων τύπων αλλαγών από το αποτέλεσμα σύγκρισης.


**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - the filter specifying the types of changes to be retrieved.

### setFilter(ChangeType value) {#setFilter-com.groupdocs.comparison.result.ChangeType-}
```
public final void setFilter(ChangeType value)
```


Ορίζει το φίλτρο για την ανάκτηση συγκεκριμένων τύπων αλλαγών από το αποτέλεσμα σύγκρισης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [ChangeType](../../com.groupdocs.comparison.result/changetype) | Το φίλτρο που καθορίζει τους τύπους αλλαγών που θα ανακτηθούν. |
|

