---
title: "ChangeType"
second_title: "Referensi API GroupDocs.Comparison untuk Java"
description: "Enum ChangeType mewakili jenis-jenis perubahan yang dapat terjadi selama proses perbandingan dokumen."
type: docs
weight: 14
url: /id/java/com.groupdocs.comparison.result/changetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ChangeType extends Enum<ChangeType>
```

Enum ChangeType mewakili jenis-jenis perubahan yang dapat terjadi selama proses perbandingan dokumen.


Setiap konstanta dalam enum ini mewakili tipe perubahan tertentu dan menyediakan deskripsi yang dapat dibaca manusia serta nilai numerik.


Contoh penggunaan:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);
     comparer.compare();
     final ChangeInfo[] changes = comparer.getChanges();
     for (ChangeInfo changeInfo : changes) {
         // Get the ChangeType for a specific change
         final ChangeType changeType = changeInfo.getType();
         // Print the ChangeType information
         System.out.println("Description: " + changeType.toString());
         System.out.println("Value: " + changeType.toInt());
     }
 }
 
````


## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [NONE](#NONE) | Mewakili tidak ada perubahan. |
|
|  | [MODIFIED](#MODIFIED) | Mewakili perubahan yang dimodifikasi. |
|
|  | [INSERTED](#INSERTED) | Mewakili perubahan yang disisipkan. |
|
|  | [DELETED](#DELETED) | Mewakili perubahan yang dihapus. |
|
|  | [ADDED](#ADDED) | Mewakili perubahan yang ditambahkan. |
|
|  | [NOT_MODIFIED](#NOT-MODIFIED) | Mewakili perubahan yang tidak dimodifikasi. |
|
|  | [STYLE_CHANGED](#STYLE-CHANGED) | Mewakili perubahan gaya. |
|
|  | [RESIZED](#RESIZED) | Mewakili perubahan yang diubah ukurannya. |
|
|  | [MOVED](#MOVED) | Mewakili perubahan yang dipindahkan. |
|
|  | [MOVED_AND_RESIZED](#MOVED-AND-RESIZED) | Mewakili perubahan yang dipindahkan dan diubah ukurannya. |
|
|  | [SHIFTED_AND_RESIZED](#SHIFTED-AND-RESIZED) | Mewakili perubahan yang digeser dan diubah ukurannya. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Menganalisis representasi string dari ChangeType untuk mendapatkan konstanta enum. |
|
|  | [fromInt(int intValue)](#fromInt-int-) | Membuat konstanta baru enum ChangeType menggunakan nilai numerik yang diberikan. |
|
|  | [toString()](#toString--) | Representasi string dari ChangeType. |
|
|  | [toInt()](#toInt--) | Representasi numerik dari ChangeType. |
|
### NONE {#NONE}
```
public static final ChangeType NONE
```


Mewakili tidak ada perubahan.


### MODIFIED {#MODIFIED}
```
public static final ChangeType MODIFIED
```


Mewakili perubahan yang dimodifikasi.


### INSERTED {#INSERTED}
```
public static final ChangeType INSERTED
```


Mewakili perubahan yang disisipkan.


### DELETED {#DELETED}
```
public static final ChangeType DELETED
```


Mewakili perubahan yang dihapus.


### ADDED {#ADDED}
```
public static final ChangeType ADDED
```


Mewakili perubahan yang ditambahkan.


### NOT_MODIFIED {#NOT-MODIFIED}
```
public static final ChangeType NOT_MODIFIED
```


Mewakili perubahan yang tidak dimodifikasi.


### STYLE_CHANGED {#STYLE-CHANGED}
```
public static final ChangeType STYLE_CHANGED
```


Mewakili perubahan gaya.


### RESIZED {#RESIZED}
```
public static final ChangeType RESIZED
```


Mewakili perubahan yang diubah ukurannya.


### MOVED {#MOVED}
```
public static final ChangeType MOVED
```


Mewakili perubahan yang dipindahkan.


### MOVED_AND_RESIZED {#MOVED-AND-RESIZED}
```
public static final ChangeType MOVED_AND_RESIZED
```


Mewakili perubahan yang dipindahkan dan diubah ukurannya.


### SHIFTED_AND_RESIZED {#SHIFTED-AND-RESIZED}
```
public static final ChangeType SHIFTED_AND_RESIZED
```


Mewakili perubahan yang digeser dan diubah ukurannya.


### values() {#values--}
```
public static ChangeType[] values()
```




**Returns:**
com.groupdocs.comparison.result.ChangeType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static ChangeType valueOf(String name)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static ChangeType fromString(String toStringValue)
```


Menganalisis representasi string dari ChangeType untuk mendapatkan konstanta enum.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | toStringValue | java.lang.String | Representasi string dari ChangeType |
|

**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - ChangeType enum constant associated with input string

### fromInt(int intValue) {#fromInt-int-}
```
public static ChangeType fromInt(int intValue)
```


Membuat konstanta baru enum ChangeType menggunakan nilai numerik yang diberikan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | intValue | int | Representasi numerik dari ChangeType |
|

**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - ChangeType enum constant associated with numeric value

### toString() {#toString--}
```
public String toString()
```


Representasi string dari ChangeType.


**Returns:**
java.lang.String - nilai string dari konstanta enum

### toInt() {#toInt--}
```
public int toInt()
```


Representasi numerik dari ChangeType.


**Returns:**
int - nilai numerik dari konstanta enum

