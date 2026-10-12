---
title: "Utils"
second_title: "GroupDocs.Comparison for Java Αναφορά API"
description: "Βοηθητική κλάση που παρέχει κοινές μεθόδους βοηθητικού χαρακτήρα, οι οποίες μπορούν να είναι χρήσιμες κατά τη χρήση του Comparison API."
type: docs
weight: 11
url: /el/java/com.groupdocs.comparison.common/utils/
---
**Inheritance:**
java.lang.Object
```
public class Utils
```

Βοηθητική κλάση που παρέχει κοινές μεθόδους βοηθητικού χαρακτήρα, οι οποίες μπορούν να είναι χρήσιμες κατά τη χρήση του Comparison API.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Utils()](#Utils--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getMethodByTag(Class<?> clazz, String methodTag, boolean isGetter)](#getMethodByTag-java.lang.Class----java.lang.String-boolean-) |  |
|  | [closeStreams(Closeable[] closeables)](#closeStreams-java.io.Closeable...-) | Κλείνει ήσυχα όλα τα παρεχόμενα αντικείμενα, συλλαμβάνοντας και καταγράφοντας όλα τα IOException. |
|
|  | [closeStreams(BiConsumer<Closeable,IOException> consumer, Closeable[] closeables)](#closeStreams-java.util.function.BiConsumer-java.io.Closeable-java.io.IOException--java.io.Closeable...-) | Κλείνει τα καθορισμένα ρεύματα, καταστέλλοντας τυχόν εξαιρέσεις που προκύπτουν κατά την καταγραφή ή επεξεργασία του IOException |
|
|  | [isText(String data)](#isText-java.lang.String-) | Ελέγχει ότι η είσοδος συμβολοσειρά περιέχει μόνο χαρακτήρες που επιτρέπονται σε συνηθισμένη συμβολοσειρά οποιασδήποτε γλώσσας |
|
| [containsOnlyLatinCharsAndPunctuation(String data)](#containsOnlyLatinCharsAndPunctuation-java.lang.String-) |  |
| [toString(TextStyle textStyle)](#toString-com.aspose.note.TextStyle-) |  |
### Utils() {#Utils--}
```
public Utils()
```


### getMethodByTag(Class<?> clazz, String methodTag, boolean isGetter) {#getMethodByTag-java.lang.Class----java.lang.String-boolean-}
```
public static Optional<Method> getMethodByTag(Class<?> clazz, String methodTag, boolean isGetter)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| clazz | java.lang.Class<?> |  |
| methodTag | java.lang.String |  |
| isGetter | boolean |  |

**Returns:**
java.util.Optional<java.lang.reflect.Method>
### closeStreams(Closeable[] closeables) {#closeStreams-java.io.Closeable...-}
```
public static boolean closeStreams(Closeable[] closeables)
```


Κλείνει ήσυχα όλα τα παρεχόμενα αντικείμενα, συλλαμβάνοντας και καταγράφοντας όλα τα IOException.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | closeables | java.io.Closeable[] | Οποιοδήποτε αντικείμενο που υλοποιεί τη διεπαφή Closeable, μπορεί να είναι null |
|

**Returns:**
boolean - true εάν όλα τα αντικείμενα closeable κλείστηκαν χωρίς εξαίρεση, διαφορετικά false

### closeStreams(BiConsumer<Closeable,IOException> consumer, Closeable[] closeables) {#closeStreams-java.util.function.BiConsumer-java.io.Closeable-java.io.IOException--java.io.Closeable...-}
```
public static boolean closeStreams(BiConsumer<Closeable,IOException> consumer, Closeable[] closeables)
```


Κλείνει τα καθορισμένα ρεύματα, καταστέλλοντας τυχόν εξαιρέσεις που προκύπτουν κατά την καταγραφή ή επεξεργασία του IOException
Εάν οποιοδήποτε από τα ρεύματα είναι null ή αντιμετωπίσει εξαίρεση κατά το κλείσιμο, αγνοείται.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | consumer | java.util.function.BiConsumer<java.io.Closeable,java.io.IOException> | Θα κληθεί για κάθε ζεύγος closeable και IOException όταν το κλείσιμο προκαλεί την εξαίρεση, μπορεί να είναι null |
|
|  | closeables | java.io.Closeable[] | Οποιοδήποτε αντικείμενο που υλοποιεί τη διεπαφή Closeable, μπορεί να είναι null |
|

**Returns:**
boolean - true εάν όλα τα αντικείμενα closeable κλείστηκαν χωρίς εξαίρεση, διαφορετικά false

### isText(String data) {#isText-java.lang.String-}
```
public static boolean isText(String data)
```


Ελέγχει ότι η είσοδος συμβολοσειρά περιέχει μόνο χαρακτήρες που επιτρέπονται σε συνηθισμένη συμβολοσειρά οποιασδήποτε γλώσσας


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| data | java.lang.String |  |

**Returns:**
boolean
### containsOnlyLatinCharsAndPunctuation(String data) {#containsOnlyLatinCharsAndPunctuation-java.lang.String-}
```
public static boolean containsOnlyLatinCharsAndPunctuation(String data)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| data | java.lang.String |  |

**Returns:**
boolean
### toString(TextStyle textStyle) {#toString-com.aspose.note.TextStyle-}
```
public static void toString(TextStyle textStyle)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| textStyle | com.aspose.note.TextStyle |  |

