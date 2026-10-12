---
title: "RevisionInfo"
second_title: "Referensi API GroupDocs.Comparison untuk Java"
description: "Mewakili sebuah revisi dalam dokumen."
type: docs
weight: 12
url: /id/java/com.groupdocs.comparison.words.revision/revisioninfo/
---
**Inheritance:**
java.lang.Object
```
public class RevisionInfo
```

Mewakili sebuah revisi dalam dokumen.


Sebuah revisi mengenkapsulasi informasi tentang perubahan revisi yang dibuat pada dokumen.
Kelas ini menyediakan metode untuk mengambil informasi tentang revisi, seperti tipenya,
konten, penulis, dan sebagainya.

Contoh penggunaan:

````

 try (RevisionHandler revisionHandler = new RevisionHandler(sourceFile)) {
     List revisionList = revisionHandler.getRevisions();

     for (RevisionInfo revisionInfo : revisionList) {
         System.out.println("Revision Type: " + revisionInfo.getType());
         System.out.println("Text: " + revisionInfo.getText());
         System.out.println("Author: " + revisionInfo.getAuthor());
     }
 }
 
````


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [RevisionInfo()](#RevisionInfo--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getAction()](#getAction--) | Mendapatkan aksi yang terkait dengan revisi (terima atau tolak). |
|
|  | [setAction(RevisionAction value)](#setAction-com.groupdocs.comparison.words.revision.RevisionAction-) | Mengatur nilai yang terkait dengan revisi (terima atau tolak). |
|
|  | [getText()](#getText--) | Mendapatkan konten teks dari revisi. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Mengatur nilai konten revisi. |
|
|  | [getAuthor()](#getAuthor--) | Mendapatkan penulis revisi. |
|
|  | [setAuthor(String value)](#setAuthor-java.lang.String-) | Mengatur nilai revisi. |
|
|  | [getType()](#getType--) | Mendapatkan tipe revisi, tergantung pada tipe tersebut logika Aksi (terima atau tolak) berubah. |
|
|  | [setType(RevisionType value)](#setType-com.groupdocs.comparison.words.revision.RevisionType-) | Mengatur nilai revisi, tergantung pada nilai tersebut logika Aksi (terima atau tolak) berubah. |
|
### RevisionInfo() {#RevisionInfo--}
```
public RevisionInfo()
```


### getAction() {#getAction--}
```
public RevisionAction getAction()
```


Mendapatkan aksi yang terkait dengan revisi (terima atau tolak). Bidang ini memungkinkan Anda memengaruhi tampilan revisi.


**Returns:**
[RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) - the action associated with the revision.

### setAction(RevisionAction value) {#setAction-com.groupdocs.comparison.words.revision.RevisionAction-}
```
public void setAction(RevisionAction value)
```


Mengatur nilai yang terkait dengan revisi (terima atau tolak). Bidang ini memungkinkan Anda memengaruhi tampilan revisi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | Nilai yang terkait dengan revisi. |
|

### getText() {#getText--}
```
public String getText()
```


Mendapatkan konten teks dari revisi.


**Returns:**
java.lang.String - konten teks dari revisi.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Mengatur nilai konten revisi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | java.lang.String | Konten nilai revisi. |
|

### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Mendapatkan penulis revisi.


**Returns:**
java.lang.String - penulis revisi.

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public void setAuthor(String value)
```


Mengatur nilai revisi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | java.lang.String | Nilai revisi. |
|

### getType() {#getType--}
```
public RevisionType getType()
```


Mendapatkan tipe revisi, tergantung pada tipe tersebut logika Aksi (terima atau tolak) berubah.


**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) - the type of the revision.

### setType(RevisionType value) {#setType-com.groupdocs.comparison.words.revision.RevisionType-}
```
public void setType(RevisionType value)
```


Mengatur nilai revisi, tergantung pada nilai tersebut logika Aksi (terima atau tolak) berubah.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) | Nilai revisi. |
|

