---
title: "ApplyChangeOptions"
second_title: "Referensi API GroupDocs.Comparison untuk Java"
description: "Memungkinkan pembaruan daftar perubahan sebelum menerapkannya ke dokumen hasil."
type: docs
weight: 10
url: /id/java/com.groupdocs.comparison.options/applychangeoptions/
---
**Inheritance:**
java.lang.Object
```
public class ApplyChangeOptions
```

Memungkinkan pembaruan daftar perubahan sebelum menerapkannya ke dokumen hasil.


Contoh penggunaan:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);
     comparer.compare();
     ChangeInfo[] changes = comparer.getChanges();
     changes[0].setComparisonAction(ComparisonAction.REJECT);

     final ApplyChangeOptions applyChangeOptions = new ApplyChangeOptions(changes);

     comparer.applyChanges(resultFile, applyChangeOptions);
 }
 
````


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [ApplyChangeOptions()](#ApplyChangeOptions--) | Menginisialisasi instance baru dari kelas ApplyChangeOptions. |
|
|  | [ApplyChangeOptions(List<ChangeInfo> changes)](#ApplyChangeOptions-java.util.List-com.groupdocs.comparison.result.ChangeInfo--) | Menginisialisasi instance baru dari kelas ApplyChangeOptions dengan daftar perubahan. |
|
|  | [ApplyChangeOptions(ChangeInfo[] changes)](#ApplyChangeOptions-com.groupdocs.comparison.result.ChangeInfo---) | Menginisialisasi instance baru dari kelas ApplyChangeOptions dengan array perubahan. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getChanges()](#getChanges--) | Mendapatkan array perubahan yang harus diterapkan pada dokumen hasil. |
|
|  | [setChanges(ChangeInfo[] value)](#setChanges-com.groupdocs.comparison.result.ChangeInfo---) | Mengatur array perubahan yang harus diterapkan pada dokumen hasil. |
|
|  | [setChanges(List<ChangeInfo> value)](#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--) | Mengatur daftar perubahan yang harus diterapkan pada dokumen hasil. |
|
|  | [isSaveOriginalState()](#isSaveOriginalState--) | Mendapatkan flag yang menentukan apakah keadaan asli harus disimpan. |
|
|  | [setSaveOriginalState(boolean saveOriginalState)](#setSaveOriginalState-boolean-) | Mengatur flag yang menentukan apakah keadaan asli harus disimpan. |
|
### ApplyChangeOptions() {#ApplyChangeOptions--}
```
public ApplyChangeOptions()
```


Menginisialisasi instance baru dari kelas ApplyChangeOptions.


### ApplyChangeOptions(List<ChangeInfo> changes) {#ApplyChangeOptions-java.util.List-com.groupdocs.comparison.result.ChangeInfo--}
```
public ApplyChangeOptions(List<ChangeInfo> changes)
```


Menginisialisasi instance baru dari kelas ApplyChangeOptions dengan daftar perubahan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | perubahan | java.util.List<com.groupdocs.comparison.result.ChangeInfo> | Daftar perubahan yang akan diterapkan |
|

### ApplyChangeOptions(ChangeInfo[] changes) {#ApplyChangeOptions-com.groupdocs.comparison.result.ChangeInfo---}
```
public ApplyChangeOptions(ChangeInfo[] changes)
```


Menginisialisasi instance baru dari kelas ApplyChangeOptions dengan array perubahan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | changes | [ChangeInfo\[\]](../../com.groupdocs.comparison.result/changeinfo) | Daftar perubahan yang akan diterapkan |
|

### getChanges() {#getChanges--}
```
public final ChangeInfo[] getChanges()
```


Mendapatkan array perubahan yang harus diterapkan pada dokumen hasil.


**Returns:**
com.groupdocs.comparison.result.ChangeInfo[] - array perubahan yang akan diterapkan

### setChanges(ChangeInfo[] value) {#setChanges-com.groupdocs.comparison.result.ChangeInfo---}
```
public final void setChanges(ChangeInfo[] value)
```


Mengatur array perubahan yang harus diterapkan pada dokumen hasil.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [ChangeInfo\[\]](../../com.groupdocs.comparison.result/changeinfo) | Array perubahan yang akan diterapkan |
|

### setChanges(List<ChangeInfo> value) {#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--}
```
public final void setChanges(List<ChangeInfo> value)
```


Mengatur daftar perubahan yang harus diterapkan pada dokumen hasil.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | java.util.List<com.groupdocs.comparison.result.ChangeInfo> | Daftar perubahan yang akan diterapkan |
|

### isSaveOriginalState() {#isSaveOriginalState--}
```
public boolean isSaveOriginalState()
```


Mendapatkan flag yang menentukan apakah keadaan asli harus disimpan. Nilai default: false.


**Returns:**
boolean - true jika keadaan asli harus disimpan, jika tidak false

### setSaveOriginalState(boolean saveOriginalState) {#setSaveOriginalState-boolean-}
```
public void setSaveOriginalState(boolean saveOriginalState)
```


Mengatur flag yang menentukan apakah keadaan asli harus disimpan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | saveOriginalState | boolean | True jika keadaan asli harus disimpan, jika tidak false |
|

