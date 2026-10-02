---
title: "ComparisonAction"
second_title: "Referensi API GroupDocs.Comparison untuk Java"
description: "Enum ComparisonAction mewakili tindakan yang dapat diterapkan pada perubahan selama proses perbandingan dokumen."
type: docs
weight: 15
url: /id/java/com.groupdocs.comparison.result/comparisonaction/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ComparisonAction extends Enum<ComparisonAction>
```

Enum ComparisonAction mewakili tindakan yang dapat diterapkan pada perubahan selama proses perbandingan dokumen.


Setiap konstanta dalam enum ini mewakili aksi tertentu dan menyediakan deskripsi yang dapat dibaca manusia serta nilai numerik.


Contoh penggunaan:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);
     comparer.compare();

     final ChangeInfo[] changes = comparer.getChanges();
     for (ChangeInfo changeInfo : changes) {
         if (changeInfo.getId() % 2 == 0) {
             changeInfo.setComparisonAction(ComparisonAction.REJECT);
         }
     }
     comparer.applyChanges(resultFile, changes);
 }
 
````


## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [NONE](#NONE) | Mewakili tidak ada aksi. |
|
|  | [ACCEPT](#ACCEPT) | Mewakili aksi menerima. |
|
|  | [REJECT](#REJECT) | Mewakili aksi menolak. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Menganalisis representasi string dari ComparisonAction untuk mendapatkan konstanta enum. |
|
|  | [fromInt(int intValue)](#fromInt-int-) | Membuat konstanta baru dari enum ComparisonAction menggunakan nilai numerik yang diberikan. |
|
|  | [toString()](#toString--) | Representasi string dari ComparisonAction. |
|
|  | [toInt()](#toInt--) | Representasi numerik dari ComparisonAction. |
|
### NONE {#NONE}
```
public static final ComparisonAction NONE
```


Mewakili tidak ada aksi. Perubahan tidak akan berpengaruh.


### ACCEPT {#ACCEPT}
```
public static final ComparisonAction ACCEPT
```


Mewakili aksi menerima. Perubahan akan terlihat di file hasil.


### REJECT {#REJECT}
```
public static final ComparisonAction REJECT
```


Mewakili aksi menolak. Perubahan tidak akan terlihat di file hasil.


### values() {#values--}
```
public static ComparisonAction[] values()
```




**Returns:**
com.groupdocs.comparison.result.ComparisonAction[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static ComparisonAction valueOf(String name)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static ComparisonAction fromString(String toStringValue)
```


Menganalisis representasi string dari ComparisonAction untuk mendapatkan konstanta enum.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | toStringValue | java.lang.String | Representasi string dari ComparisonAction |
|

**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) - ComparisonAction enum constant associated with input string

### fromInt(int intValue) {#fromInt-int-}
```
public static ComparisonAction fromInt(int intValue)
```


Membuat konstanta baru dari enum ComparisonAction menggunakan nilai numerik yang diberikan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | intValue | int | Representasi numerik dari ComparisonAction |
|

**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) - ComparisonAction enum constant associated with numeric value

### toString() {#toString--}
```
public String toString()
```


Representasi string dari ComparisonAction.


**Returns:**
java.lang.String - nilai string dari konstanta enum

### toInt() {#toInt--}
```
public int toInt()
```


Representasi numerik dari ComparisonAction.


**Returns:**
int - nilai numerik dari konstanta enum

