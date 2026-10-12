---
title: "MemoryCleaner"
second_title: "GroupDocs.Comparison for Java Αναφορά API"
description: "Καθαρίζει διάφορους πόρους για να ελευθερώσει μνήμη."
type: docs
weight: 10
url: /el/java/com.groupdocs.comparison.common/memorycleaner/
---
**Inheritance:**
java.lang.Object
```
public final class MemoryCleaner
```

Καθαρίζει διάφορους πόρους για να ελευθερώσει μνήμη.


Αυτή η κλάση παρέχει μεθόδους για εκκαθάριση της μνήμης heap, διαγραφή προσωρινών αρχείων και εκκαθάριση πληροφοριών καταχώρησης γραμματοσειρών.
Περιλαμβάνει επίσης μια μέθοδο για ασφαλή εκκαθάριση των thread-local αντικειμένων για το τρέχον νήμα.


Παράδειγμα χρήσης:

````

 // Clean heap memory, keeping font settings
 MemoryCleaner.clearKeepingFontSettings();

 // Clean heap memory and delete temp files
 MemoryCleaner.clear();

 // Clean heap memory from static PDF instances
 MemoryCleaner.clearStaticInstances();

 // Delete all temp files created by PDF in the system temp directory
 MemoryCleaner.clearAllTempFiles();

 // Clear font registry information from heap memory
 MemoryCleaner.clearFontRegistry();

 // Safely clear thread-local instances for the current thread
 MemoryCleaner.clearCurrentThreadLocals();
 
````


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [MemoryCleaner()](#MemoryCleaner--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [clearKeepingFontSettings()](#clearKeepingFontSettings--) | Καθαρίζει τη μνήμη heap από στατικές PDF περιπτώσεις (static και threadLocal) και διαγράφει όλα τα προσωρινά αρχεία. |
|
|  | [clear()](#clear--) | Καθαρίζει τη μνήμη heap από στατικές PDF περιπτώσεις (static και threadLocal) και διαγράφει όλα τα προσωρινά αρχεία. |
|
|  | [clearStaticInstances()](#clearStaticInstances--) | Καθαρίζει τη μνήμη heap από στατικές PDF περιπτώσεις. |
|
|  | [clearAllTempFiles()](#clearAllTempFiles--) | Καθαρίζει τα προσωρινά αρχεία που δημιουργήθηκαν από το GroupDocs.Comparison στον φάκελο προσωρινών αρχείων του συστήματος. |
|
|  | [clearFontRegistry()](#clearFontRegistry--) | Καθαρίζει τις πληροφορίες καταχώρησης γραμματοσειρών από τη μνήμη heap. |
|
|  | [clearCurrentThreadLocals()](#clearCurrentThreadLocals--) | Ασφαλώς καθαρίζει τη μνήμη heap από thread-local αντικείμενα για το τρέχον νήμα. |
|
### MemoryCleaner() {#MemoryCleaner--}
```
public MemoryCleaner()
```


### clearKeepingFontSettings() {#clearKeepingFontSettings--}
```
public static void clearKeepingFontSettings()
```


Καθαρίζει τη μνήμη heap από στατικές PDF περιπτώσεις (static και threadLocal) και διαγράφει όλα τα προσωρινά αρχεία.
Αυτή η μέθοδος δεν επηρεάζει τις ρυθμίσεις γραμματοσειράς.


### clear() {#clear--}
```
public static void clear()
```


Καθαρίζει τη μνήμη heap από στατικές PDF περιπτώσεις (static και threadLocal) και διαγράφει όλα τα προσωρινά αρχεία.


### clearStaticInstances() {#clearStaticInstances--}
```
public static void clearStaticInstances()
```


Καθαρίζει τη μνήμη heap από στατικές PDF περιπτώσεις.


### clearAllTempFiles() {#clearAllTempFiles--}
```
public static void clearAllTempFiles()
```


Καθαρίζει τα προσωρινά αρχεία που δημιουργήθηκαν από το GroupDocs.Comparison στον φάκελο προσωρινών αρχείων του συστήματος.


### clearFontRegistry() {#clearFontRegistry--}
```
public static void clearFontRegistry()
```


Καθαρίζει τις πληροφορίες καταχώρησης γραμματοσειρών από τη μνήμη heap.


### clearCurrentThreadLocals() {#clearCurrentThreadLocals--}
```
public static void clearCurrentThreadLocals()
```


Ασφαλώς καθαρίζει τη μνήμη heap από thread-local αντικείμενα για το τρέχον νήμα.


