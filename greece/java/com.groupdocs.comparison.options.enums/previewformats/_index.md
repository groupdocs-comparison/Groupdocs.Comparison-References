---
title: "PreviewFormats"
second_title: "GroupDocs.Comparison for Java Αναφορά API"
description: "Απαριθμεί τις υποστηριζόμενες μορφές προεπισκόπησης για τη σύγκριση εγγράφων."
type: docs
weight: 15
url: /el/java/com.groupdocs.comparison.options.enums/previewformats/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PreviewFormats extends Enum<PreviewFormats>
```

Απαριθμεί τις υποστηριζόμενες μορφές προεπισκόπησης για τη σύγκριση εγγράφων.
Το enum PreviewFormats παρέχει μια λίστα μορφών που μπορούν να χρησιμοποιηθούν για τη δημιουργία προεπισκοπήσεων των συγκρινόμενων εγγράφων.

Οι υποστηριζόμενες μορφές περιλαμβάνουν:

* #PNG.PNG - Portable Network Graphics (.png)
* #JPEG.JPEG - Joint Photographic Experts Group (.jpeg)
* #BMP.BMP - Bitmap Picture (.bmp)


Παράδειγμα χρήσης:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    PreviewOptions previewOptions = new PreviewOptions(
            pageNumber -> Files.newOutputStream(Paths.get(String.format("preview-page_%d.png", pageNumber)))
    );
    previewOptions.setPreviewFormat(PreviewFormats.PNG);

    comparer.getTargets().get(0).generatePreview(previewOptions);
 }
 
````


## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [PNG](#PNG) | PNG - μπορεί να καταναλώσει σημαντικό χώρο δίσκου ή κυκλοφορία δικτύου εάν η σελίδα περιέχει πολυάριθμα χρωματιστά γραφικά. |
|
|  | [JPEG](#JPEG) | Jpeg - παρέχει ταχύτερη επεξεργασία με μικρότερη χρήση χώρου δίσκου και κυκλοφορίας δικτύου, αλλά μπορεί να οδηγήσει σε χαμηλότερη ποιότητα εικόνας. |
|
|  | [BMP](#BMP) | BMP - προσφέρει την καλύτερη ποιότητα εικόνας αλλά απαιτεί πιο αργή επεξεργασία με μεγαλύτερη χρήση χώρου δίσκου και κυκλοφορίας δικτύου. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Αναλύει την αναπαράσταση συμβολοσειράς του PreviewFormats για να λάβει τη σταθερά enum. |
|
|  | [toString()](#toString--) | Αναπαράσταση συμβολοσειράς του PreviewFormats. |
|
### PNG {#PNG}
```
public static final PreviewFormats PNG
```


PNG - μπορεί να καταναλώσει σημαντικό χώρο δίσκου ή κυκλοφορία δικτύου εάν η σελίδα περιέχει πολυάριθμα χρωματιστά γραφικά. Προεπιλεγμένη μορφή προεπισκόπησης.


### JPEG {#JPEG}
```
public static final PreviewFormats JPEG
```


Jpeg - παρέχει ταχύτερη επεξεργασία με μικρότερη χρήση χώρου δίσκου και κυκλοφορίας δικτύου, αλλά μπορεί να οδηγήσει σε χαμηλότερη ποιότητα εικόνας.


### BMP {#BMP}
```
public static final PreviewFormats BMP
```


BMP - προσφέρει την καλύτερη ποιότητα εικόνας αλλά απαιτεί πιο αργή επεξεργασία με μεγαλύτερη χρήση χώρου δίσκου και κυκλοφορίας δικτύου.


### values() {#values--}
```
public static PreviewFormats[] values()
```




**Returns:**
com.groupdocs.comparison.options.enums.PreviewFormats[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PreviewFormats valueOf(String name)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| όνομα | java.lang.String |  |

**Returns:**
[PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static PreviewFormats fromString(String toStringValue)
```


Αναλύει την αναπαράσταση συμβολοσειράς του PreviewFormats για να λάβει τη σταθερά enum.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | toStringValue | java.lang.String | Η αναπαράσταση συμβολοσειράς του PreviewFormats |
|

**Returns:**
[PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats) - PreviewFormats enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


Αναπαράσταση συμβολοσειράς του PreviewFormats.


**Returns:**
java.lang.String - τιμή συμβολοσειράς του σταθερού της enum

