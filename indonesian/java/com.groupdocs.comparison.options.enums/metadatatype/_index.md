---
title: "MetadataType"
second_title: "Referensi API GroupDocs.Comparison untuk Java"
description: "Menentukan dari mana dokumen hasil akan mengambil informasi metadata."
type: docs
weight: 12
url: /id/java/com.groupdocs.comparison.options.enums/metadatatype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum MetadataType extends Enum<MetadataType>
```

Menentukan dari mana dokumen hasil akan mengambil informasi metadata.


Contoh penggunaan:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    SaveOptions saveOptions = new SaveOptions();
    saveOptions.setCloneMetadataType(MetadataType.FILE_AUTHOR);

    comparer.compare(resultFile, saveOptions);
 }
 
````


## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [DEFAULT](#DEFAULT) | Metadata akan dibiarkan apa adanya. |
|
|  | [SOURCE](#SOURCE) | Metedata akan diambil dari dokumen sumber. |
|
|  | [TARGET](#TARGET) | Metedata akan diambil dari dokumen target. |
|
|  | [FILE_AUTHOR](#FILE-AUTHOR) | Metedata akan diatur oleh pengguna. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Menganalisis representasi string dari MetadataType untuk mendapatkan konstanta enum. |
|
|  | [toString()](#toString--) | Representasi string dari MetadataType. |
|
### DEFAULT {#DEFAULT}
```
public static final MetadataType DEFAULT
```


Metadata akan dibiarkan apa adanya.


### SOURCE {#SOURCE}
```
public static final MetadataType SOURCE
```


Metedata akan diambil dari dokumen sumber.


### TARGET {#TARGET}
```
public static final MetadataType TARGET
```


Metedata akan diambil dari dokumen target.


### FILE_AUTHOR {#FILE-AUTHOR}
```
public static final MetadataType FILE_AUTHOR
```


Metedata akan diatur oleh pengguna.


### values() {#values--}
```
public static MetadataType[] values()
```




**Returns:**
com.groupdocs.comparison.options.enums.MetadataType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static MetadataType valueOf(String name)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static MetadataType fromString(String toStringValue)
```


Menganalisis representasi string dari MetadataType untuk mendapatkan konstanta enum.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | toStringValue | java.lang.String | Representasi string dari MetadataType |
|

**Returns:**
[MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) - MetadataType enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


Representasi string dari MetadataType.


**Returns:**
java.lang.String - nilai string dari konstanta enum

