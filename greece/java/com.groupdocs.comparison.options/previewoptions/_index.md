---
title: "PreviewOptions"
second_title: "GroupDocs.Comparison for Java Αναφορά API"
description: "Παρέχει επιλογές για τη δημιουργία προεπισκοπήσεων εγγράφων στη διαδικασία σύγκρισης."
type: docs
weight: 15
url: /el/java/com.groupdocs.comparison.options/previewoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewOptions
```

Παρέχει επιλογές για τη δημιουργία προεπισκοπήσεων εγγράφων στη διαδικασία σύγκρισης.


Παράδειγμα χρήσης:

````

 try (Comparer comparer = new Comparer(sourceFile)) {

    PreviewOptions previewOptions = new PreviewOptions(
            pageNumber -> Files.newOutputStream(Paths.get(String.format("preview-page_%d.png", pageNumber)))
    );
    previewOptions.setPreviewFormat(PreviewFormats.PNG);
    previewOptions.setPageNumbers(new int[]{1, 2});

    comparer.getSource().generatePreview(previewOptions);
 }
 
````


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [PreviewOptions(Delegates.CreatePageStream createPageStream)](#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-) | Αρχικοποιεί μια νέα παρουσία της κλάσης PreviewOptions καθορίζοντας τη λειτουργία Delegates.CreatePageStream. |
|
|  | [PreviewOptions(CreatePageStreamFunction createPageStream)](#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-) | Αρχικοποιεί μια νέα παρουσία της κλάσης PreviewOptions καθορίζοντας τη λειτουργία [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction). |
|
|  | [PreviewOptions(Delegates.CreatePageStream createPageStream, Delegates.ReleasePageStream releasePageStream)](#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-) | Αρχικοποιεί μια νέα παρουσία της κλάσης PreviewOptions καθορίζοντας τις λειτουργίες Delegates.CreatePageStream και Delegates.ReleasePageStream. |
|
|  | [PreviewOptions(CreatePageStreamFunction createPageStream, ReleasePageStreamFunction releasePageStream)](#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-) | Αρχικοποιεί μια νέα παρουσία της κλάσης PreviewOptions καθορίζοντας τις λειτουργίες [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) και [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction). |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getCreatePageStream()](#getCreatePageStream--) | Λαμβάνει μια λειτουργία για τη δημιουργία ροής προεπισκόπησης εξόδου σελίδας. |
|
|  | [setCreatePageStream(Delegates.CreatePageStream createPageStream)](#setCreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-) | Ορίζει μια λειτουργία για τη δημιουργία ροής προεπισκόπησης εξόδου σελίδας. |
|
|  | [setCreatePageStream(CreatePageStreamFunction createPageStream)](#setCreatePageStream-com.groupdocs.comparison.common.function.CreatePageStreamFunction-) | Ορίζει μια λειτουργία για τη δημιουργία ροής προεπισκόπησης εξόδου σελίδας. |
|
|  | [getReleasePageStream()](#getReleasePageStream--) | Λαμβάνει μια λειτουργία για την απελευθέρωση της ροής προεπισκόπησης εξόδου σελίδας. |
|
|  | [setReleasePageStream(Delegates.ReleasePageStream releasePageStream)](#setReleasePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-) | Λαμβάνει μια λειτουργία για την απελευθέρωση της ροής προεπισκόπησης εξόδου σελίδας. |
|
|  | [setReleasePageStream(ReleasePageStreamFunction releasePageStream)](#setReleasePageStream-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-) | Ορίζει μια λειτουργία για την απελευθέρωση της ροής προεπισκόπησης εξόδου σελίδας. |
|
|  | [getWidth()](#getWidth--) | Λαμβάνει το πλάτος των εικόνων προεπισκόπησης. |
|
|  | [setWidth(int value)](#setWidth-int-) | Ορίζει το πλάτος των εικόνων προεπισκόπησης. |
|
|  | [getHeight()](#getHeight--) | Λαμβάνει το ύψος των εικόνων προεπισκόπησης. |
|
|  | [setHeight(int value)](#setHeight-int-) | Ορίζει το ύψος των εικόνων προεπισκόπησης. |
|
|  | [getPageNumbers()](#getPageNumbers--) | Λαμβάνει έναν πίνακα αριθμών σελίδων για τις οποίες θα δημιουργηθούν εικόνες προεπισκόπησης. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | Ορίζει έναν πίνακα αριθμών σελίδων για τις οποίες θα δημιουργηθούν εικόνες προεπισκόπησης. |
|
|  | [getPreviewFormat()](#getPreviewFormat--) | Λαμβάνει μια μορφή των εικόνων προεπισκόπησης. |
|
|  | [setPreviewFormat(PreviewFormats value)](#setPreviewFormat-com.groupdocs.comparison.options.enums.PreviewFormats-) | Ορίζει μια μορφή των εικόνων προεπισκόπησης. |
|
### PreviewOptions(Delegates.CreatePageStream createPageStream) {#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-}
```
public PreviewOptions(Delegates.CreatePageStream createPageStream)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης PreviewOptions καθορίζοντας τη λειτουργία Delegates.CreatePageStream.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.comparison.common.delegates/createpagestream) | Η λειτουργία για δημιουργία ροής προεπισκόπησης εξόδου σελίδας. |
|

### PreviewOptions(CreatePageStreamFunction createPageStream) {#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-}
```
public PreviewOptions(CreatePageStreamFunction createPageStream)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης PreviewOptions καθορίζοντας τη λειτουργία [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | createPageStream | [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) | Η λειτουργία για δημιουργία ροής προεπισκόπησης εξόδου σελίδας. |
|

### PreviewOptions(Delegates.CreatePageStream createPageStream, Delegates.ReleasePageStream releasePageStream) {#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-}
```
public PreviewOptions(Delegates.CreatePageStream createPageStream, Delegates.ReleasePageStream releasePageStream)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης PreviewOptions καθορίζοντας τις λειτουργίες Delegates.CreatePageStream και Delegates.ReleasePageStream.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.comparison.common.delegates/createpagestream) | Η λειτουργία για δημιουργία ροής προεπισκόπησης εξόδου σελίδας. |
|
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.comparison.common.delegates/releasepagestream) | Η λειτουργία για απελευθέρωση ροής προεπισκόπησης εξόδου σελίδας. |
|

### PreviewOptions(CreatePageStreamFunction createPageStream, ReleasePageStreamFunction releasePageStream) {#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-}
```
public PreviewOptions(CreatePageStreamFunction createPageStream, ReleasePageStreamFunction releasePageStream)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης PreviewOptions καθορίζοντας τις λειτουργίες [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) και [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | createPageStream | [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) | Η λειτουργία για δημιουργία ροής προεπισκόπησης εξόδου σελίδας. |
|
|  | releasePageStream | [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) | Η λειτουργία για απελευθέρωση ροής προεπισκόπησης εξόδου σελίδας. |
|

### getCreatePageStream() {#getCreatePageStream--}
```
public CreatePageStreamFunction getCreatePageStream()
```


Λαμβάνει μια λειτουργία για τη δημιουργία ροής προεπισκόπησης εξόδου σελίδας.


**Returns:**
[CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) - the function to create output page preview stream.

### setCreatePageStream(Delegates.CreatePageStream createPageStream) {#setCreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-}
```
public void setCreatePageStream(Delegates.CreatePageStream createPageStream)
```


Ορίζει μια λειτουργία για τη δημιουργία ροής προεπισκόπησης εξόδου σελίδας.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.comparison.common.delegates/createpagestream) | Η λειτουργία για δημιουργία ροής προεπισκόπησης εξόδου σελίδας. |
|

### setCreatePageStream(CreatePageStreamFunction createPageStream) {#setCreatePageStream-com.groupdocs.comparison.common.function.CreatePageStreamFunction-}
```
public void setCreatePageStream(CreatePageStreamFunction createPageStream)
```


Ορίζει μια λειτουργία για τη δημιουργία ροής προεπισκόπησης εξόδου σελίδας.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | createPageStream | [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) | Η λειτουργία για δημιουργία ροής προεπισκόπησης εξόδου σελίδας. |
|

### getReleasePageStream() {#getReleasePageStream--}
```
public ReleasePageStreamFunction getReleasePageStream()
```


Λαμβάνει μια λειτουργία για την απελευθέρωση της ροής προεπισκόπησης εξόδου σελίδας.


**Returns:**
[ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) - the function to release output page preview stream.

### setReleasePageStream(Delegates.ReleasePageStream releasePageStream) {#setReleasePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-}
```
public void setReleasePageStream(Delegates.ReleasePageStream releasePageStream)
```


Λαμβάνει μια λειτουργία για την απελευθέρωση της ροής προεπισκόπησης εξόδου σελίδας.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.comparison.common.delegates/releasepagestream) | Η λειτουργία για απελευθέρωση ροής προεπισκόπησης εξόδου σελίδας. |
|

### setReleasePageStream(ReleasePageStreamFunction releasePageStream) {#setReleasePageStream-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-}
```
public void setReleasePageStream(ReleasePageStreamFunction releasePageStream)
```


Ορίζει μια λειτουργία για την απελευθέρωση της ροής προεπισκόπησης εξόδου σελίδας.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | releasePageStream | [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) | Η λειτουργία για απελευθέρωση ροής προεπισκόπησης εξόδου σελίδας. |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Λαμβάνει το πλάτος των εικόνων προεπισκόπησης.


**Returns:**
int - το πλάτος των εικόνων προεπισκόπησης.

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Ορίζει το πλάτος των εικόνων προεπισκόπησης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | int | Το πλάτος των εικόνων προεπισκόπησης. |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Λαμβάνει το ύψος των εικόνων προεπισκόπησης.


**Returns:**
int - το ύψος των εικόνων προεπισκόπησης.

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Ορίζει το ύψος των εικόνων προεπισκόπησης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | int | Το ύψος των εικόνων προεπισκόπησης. |
|

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Λαμβάνει έναν πίνακα αριθμών σελίδων για τις οποίες θα δημιουργηθούν εικόνες προεπισκόπησης.


**Returns:**
int[] - πίνακας αριθμών σελίδων

### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Ορίζει έναν πίνακα αριθμών σελίδων για τις οποίες θα δημιουργηθούν εικόνες προεπισκόπησης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | int[] | Πίνακας αριθμών σελίδων |
|

### getPreviewFormat() {#getPreviewFormat--}
```
public final PreviewFormats getPreviewFormat()
```


Λαμβάνει μια μορφή των εικόνων προεπισκόπησης.


**Returns:**
[PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats) - preview images format

### setPreviewFormat(PreviewFormats value) {#setPreviewFormat-com.groupdocs.comparison.options.enums.PreviewFormats-}
```
public final void setPreviewFormat(PreviewFormats value)
```


Ορίζει μια μορφή των εικόνων προεπισκόπησης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats) | Μορφή εικόνων προεπισκόπησης |
|

