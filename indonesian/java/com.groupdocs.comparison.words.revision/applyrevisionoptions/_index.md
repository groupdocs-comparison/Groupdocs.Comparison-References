---
title: "ApplyRevisionOptions"
second_title: "Referensi API GroupDocs.Comparison untuk Java"
description: "Kelas ApplyRevisionOptions memungkinkan Anda memperbarui status revisi sebelum diterapkan ke dokumen akhir."
type: docs
weight: 10
url: /id/java/com.groupdocs.comparison.words.revision/applyrevisionoptions/
---
**Inheritance:**
java.lang.Object
```
public class ApplyRevisionOptions
```

Kelas ApplyRevisionOptions memungkinkan Anda memperbarui status revisi sebelum diterapkan ke dokumen akhir.


Ini menyediakan berbagai konstruktor dan properti untuk menyesuaikan proses penerapan revisi.


Contoh penggunaan:

````

 try (RevisionHandler revisionHandler = new RevisionHandler(sourceFile)) {
     List revisionList = revisionHandler.getRevisions();

     for (RevisionInfo revisionInfo : revisionList) {
         if (revisionInfo.getType() == RevisionType.DELETION)
             // Set an action to be applied to the revision
             revisionInfo.setAction(RevisionAction.Accept);
     }
     // Create an instance of ApplyRevisionOptions
     ApplyRevisionOptions revisionChanges = new ApplyRevisionOptions();
     revisionChanges.setChanges(revisionList);
     // Apply the revisions using the options
     revisionHandler.applyRevisionChanges(resultFile, revisionChanges);
 }
 
````


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [ApplyRevisionOptions()](#ApplyRevisionOptions--) | Menginisialisasi instance baru dari kelas ApplyRevisionOptions. |
|
|  | [ApplyRevisionOptions(List<RevisionInfo> changes)](#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--) | Membuat objek ApplyRevisionOptions baru dengan daftar revisi yang ditentukan. |
|
|  | [ApplyRevisionOptions(List<RevisionInfo> changes, RevisionAction revisionAction)](#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--com.groupdocs.comparison.words.revision.RevisionAction-) | Membuat instance baru dari objek ApplyRevisionOptions dengan daftar revisi yang ditentukan dan aksi revisi umum. |
|
|  | [ApplyRevisionOptions(RevisionAction revisionAction)](#ApplyRevisionOptions-com.groupdocs.comparison.words.revision.RevisionAction-) | Membuat instance baru dari objek ApplyRevisionOptions dengan aksi revisi umum. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getChanges()](#getChanges--) | Mendapatkan daftar revisi yang akan diterapkan. |
|
|  | [setChanges(List<RevisionInfo> changes)](#setChanges-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--) | Menetapkan daftar revisi yang akan diterapkan. |
|
|  | [getCommonHandler()](#getCommonHandler--) | Mendapatkan aksi revisi umum yang akan diterapkan pada semua revisi. |
|
|  | [setCommonHandler(RevisionAction commonHandler)](#setCommonHandler-com.groupdocs.comparison.words.revision.RevisionAction-) | Menetapkan aksi revisi umum yang akan diterapkan pada semua revisi. |
|
### ApplyRevisionOptions() {#ApplyRevisionOptions--}
```
public ApplyRevisionOptions()
```


Menginisialisasi instance baru dari kelas ApplyRevisionOptions.


### ApplyRevisionOptions(List<RevisionInfo> changes) {#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--}
```
public ApplyRevisionOptions(List<RevisionInfo> changes)
```


Membuat objek ApplyRevisionOptions baru dengan daftar revisi yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | perubahan | java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> | Daftar revisi yang akan diterapkan |
|

### ApplyRevisionOptions(List<RevisionInfo> changes, RevisionAction revisionAction) {#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--com.groupdocs.comparison.words.revision.RevisionAction-}
```
public ApplyRevisionOptions(List<RevisionInfo> changes, RevisionAction revisionAction)
```


Membuat instance baru dari objek ApplyRevisionOptions dengan daftar revisi yang ditentukan dan aksi revisi umum.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | perubahan | java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> | Daftar revisi yang akan diterapkan |
|
|  | revisionAction | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | Aksi revisi umum yang akan diterapkan pada semua revisi |
|

### ApplyRevisionOptions(RevisionAction revisionAction) {#ApplyRevisionOptions-com.groupdocs.comparison.words.revision.RevisionAction-}
```
public ApplyRevisionOptions(RevisionAction revisionAction)
```


Membuat instance baru dari objek ApplyRevisionOptions dengan aksi revisi umum.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | revisionAction | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | Aksi revisi umum yang akan diterapkan pada semua revisi |
|

### getChanges() {#getChanges--}
```
public List<RevisionInfo> getChanges()
```


Mendapatkan daftar revisi yang akan diterapkan.


**Returns:**
java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> - daftar revisi

### setChanges(List<RevisionInfo> changes) {#setChanges-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--}
```
public void setChanges(List<RevisionInfo> changes)
```


Menetapkan daftar revisi yang akan diterapkan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | perubahan | java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> | Daftar revisi |
|

### getCommonHandler() {#getCommonHandler--}
```
public RevisionAction getCommonHandler()
```


Mendapatkan aksi revisi umum yang akan diterapkan pada semua revisi.


**Returns:**
[RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) - the common revision action

### setCommonHandler(RevisionAction commonHandler) {#setCommonHandler-com.groupdocs.comparison.words.revision.RevisionAction-}
```
public void setCommonHandler(RevisionAction commonHandler)
```


Menetapkan aksi revisi umum yang akan diterapkan pada semua revisi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | commonHandler | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | Aksi revisi umum |
|

