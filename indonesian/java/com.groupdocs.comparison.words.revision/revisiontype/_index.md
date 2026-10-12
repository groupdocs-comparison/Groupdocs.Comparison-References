---
title: "RevisionType"
second_title: "Referensi API GroupDocs.Comparison untuk Java"
description: "Mewakili jenis-jenis revisi dalam sebuah dokumen."
type: docs
weight: 14
url: /id/java/com.groupdocs.comparison.words.revision/revisiontype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum RevisionType extends Enum<RevisionType>
```

Mewakili jenis-jenis revisi dalam sebuah dokumen.


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


## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [INSERTION](#INSERTION) | Mewakili tipe ketika konten baru disisipkan ke dalam dokumen. |
|
|  | [DELETION](#DELETION) | Mewakili tipe ketika konten dihapus dari dokumen. |
|
|  | [FORMAT_CHANGE](#FORMAT-CHANGE) | Mewakili tipe ketika perubahan format diterapkan pada node induk. |
|
|  | [STYLE_DEFINITION_CHANGE](#STYLE-DEFINITION-CHANGE) | Mewakili tipe ketika perubahan format diterapkan pada gaya induk. |
|
|  | [MOVING](#MOVING) | Mewakili tipe ketika konten dipindahkan dalam dokumen. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromInt(int toIntValue)](#fromInt-int-) | Membuat konstanta baru dari enum RevisionType menggunakan nilai numerik yang diberikan. |
|
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Mengurai representasi string dari RevisionType untuk mendapatkan konstanta enum. |
|
|  | [toInt()](#toInt--) | Representasi numerik dari RevisionType. |
|
|  | [toString()](#toString--) | Representasi string dari RevisionType. |
|
### INSERTION {#INSERTION}
```
public static final RevisionType INSERTION
```


Mewakili tipe ketika konten baru disisipkan ke dalam dokumen.


### DELETION {#DELETION}
```
public static final RevisionType DELETION
```


Mewakili tipe ketika konten dihapus dari dokumen.


### FORMAT_CHANGE {#FORMAT-CHANGE}
```
public static final RevisionType FORMAT_CHANGE
```


Mewakili tipe ketika perubahan format diterapkan pada node induk.


### STYLE_DEFINITION_CHANGE {#STYLE-DEFINITION-CHANGE}
```
public static final RevisionType STYLE_DEFINITION_CHANGE
```


Mewakili tipe ketika perubahan format diterapkan pada gaya induk.


### MOVING {#MOVING}
```
public static final RevisionType MOVING
```


Mewakili tipe ketika konten dipindahkan dalam dokumen.


### values() {#values--}
```
public static RevisionType[] values()
```




**Returns:**
com.groupdocs.comparison.words.revision.RevisionType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static RevisionType valueOf(String name)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype)
### fromInt(int toIntValue) {#fromInt-int-}
```
public static RevisionType fromInt(int toIntValue)
```


Membuat konstanta baru dari enum RevisionType menggunakan nilai numerik yang diberikan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | toIntValue | int | Representasi numerik dari RevisionType |
|

**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) - RevisionType enum constant associated with numeric value

### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static RevisionType fromString(String toStringValue)
```


Mengurai representasi string dari RevisionType untuk mendapatkan konstanta enum.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | toStringValue | java.lang.String | Representasi string dari RevisionType |
|

**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) - RevisionType enum constant associated with input string

### toInt() {#toInt--}
```
public int toInt()
```


Representasi numerik dari RevisionType.


**Returns:**
int - nilai numerik dari konstanta enum

### toString() {#toString--}
```
public String toString()
```


Representasi string dari RevisionType.


**Returns:**
java.lang.String - nilai string dari konstanta enum

