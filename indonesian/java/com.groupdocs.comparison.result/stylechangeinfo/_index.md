---
title: "StyleChangeInfo"
second_title: "Referensi API GroupDocs.Comparison untuk Java"
description: "Kelas StyleChangeInfo mewakili informasi tentang perubahan gaya dalam dokumen yang dibandingkan."
type: docs
weight: 13
url: /id/java/com.groupdocs.comparison.result/stylechangeinfo/
---
**Inheritance:**
java.lang.Object
```
public class StyleChangeInfo
```

Kelas StyleChangeInfo mewakili informasi tentang perubahan gaya dalam dokumen yang dibandingkan.


Menyediakan detail seperti nama properti yang diubah, nilai sebelum dan sesudah perubahan, dan sebagainya.
Gunakan kelas ini untuk mengambil informasi tentang perubahan gaya selama proses perbandingan dokumen.


Contoh penggunaan:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     comparer.compare();
     final ChangeInfo[] changes = comparer.getChanges();
     for (ChangeInfo change : changes) {
         // Access the style change information
         final List styleChanges = change.getStyleChanges();
         for (StyleChangeInfo styleChange : styleChanges) {
             // Print the style change information
             System.out.println("PropertyName: " + styleChange.getPropertyName());
             System.out.println("OldValue: " + styleChange.getOldValue());
             System.out.println("NewValue: " + styleChange.getNewValue());
         }
     }
 }
 
````


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [StyleChangeInfo()](#StyleChangeInfo--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getPropertyName()](#getPropertyName--) | Mendapatkan nama properti yang diubah. |
|
|  | [setPropertyName(String value)](#setPropertyName-java.lang.String-) | Menetapkan nama properti yang diubah. |
|
|  | [getNewValue()](#getNewValue--) | Mendapatkan nilai baru properti. |
|
|  | [setNewValue(Object value)](#setNewValue-java.lang.Object-) | Menetapkan nilai baru properti. |
|
|  | [getOldValue()](#getOldValue--) | Mendapatkan nilai lama properti. |
|
|  | [setOldValue(Object value)](#setOldValue-java.lang.Object-) | Menetapkan nilai lama properti. |
|
|  | [equals(Object o)](#equals-java.lang.Object-) | {@inheritDoc} |
|
|  | [hashCode()](#hashCode--) | {@inheritDoc} |
|
### StyleChangeInfo() {#StyleChangeInfo--}
```
public StyleChangeInfo()
```


### getPropertyName() {#getPropertyName--}
```
public final String getPropertyName()
```


Mendapatkan nama properti yang diubah.


**Returns:**
java.lang.String - nama properti

### setPropertyName(String value) {#setPropertyName-java.lang.String-}
```
public final void setPropertyName(String value)
```


Menetapkan nama properti yang diubah.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | java.lang.String | Nama properti |
|

### getNewValue() {#getNewValue--}
```
public final Object getNewValue()
```


Mendapatkan nilai baru properti.


**Returns:**
java.lang.Object - nilai baru properti

### setNewValue(Object value) {#setNewValue-java.lang.Object-}
```
public final void setNewValue(Object value)
```


Menetapkan nilai baru properti.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | java.lang.Object | Nilai baru properti |
|

### getOldValue() {#getOldValue--}
```
public final Object getOldValue()
```


Mendapatkan nilai lama properti.


**Returns:**
java.lang.Object - nilai lama properti

### setOldValue(Object value) {#setOldValue-java.lang.Object-}
```
public final void setOldValue(Object value)
```


Menetapkan nilai lama properti.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | java.lang.Object | Nilai lama properti |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| o | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
