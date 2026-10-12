---
title: "PasswordSaveOption"
second_title: "Referensi API GroupDocs.Comparison untuk Java"
description: "Menumerasikan opsi untuk menyimpan informasi kata sandi dalam dokumen selama proses perbandingan."
type: docs
weight: 14
url: /id/java/com.groupdocs.comparison.options.enums/passwordsaveoption/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PasswordSaveOption extends Enum<PasswordSaveOption>
```

Menumerasikan opsi untuk menyimpan informasi kata sandi dalam dokumen selama proses perbandingan.


Contoh penggunaan:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setPasswordSaveOption(PasswordSaveOption.SOURCE);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [NONE](#NONE) | Jangan simpan kata sandi. |
|
|  | [SOURCE](#SOURCE) | Gunakan kata sandi dari dokumen sumber. |
|
|  | [TARGET](#TARGET) | Gunakan kata sandi dari dokumen target. |
|
|  | [USER](#USER) | * Gunakan kata sandi yang diberikan oleh pengguna. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Menganalisis representasi string dari PasswordSaveOption untuk mendapatkan konstanta enum. |
|
|  | [toString()](#toString--) | Representasi string dari PasswordSaveOption. |
|
### NONE {#NONE}
```
public static final PasswordSaveOption NONE
```


Jangan simpan kata sandi.


### SOURCE {#SOURCE}
```
public static final PasswordSaveOption SOURCE
```


Gunakan kata sandi dari dokumen sumber.


### TARGET {#TARGET}
```
public static final PasswordSaveOption TARGET
```


Gunakan kata sandi dari dokumen target.


### USER {#USER}
```
public static final PasswordSaveOption USER
```


* Gunakan kata sandi yang diberikan oleh pengguna.


### values() {#values--}
```
public static PasswordSaveOption[] values()
```




**Returns:**
com.groupdocs.comparison.options.enums.PasswordSaveOption[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PasswordSaveOption valueOf(String name)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static PasswordSaveOption fromString(String toStringValue)
```


Menganalisis representasi string dari PasswordSaveOption untuk mendapatkan konstanta enum.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | toStringValue | java.lang.String | Representasi string dari PasswordSaveOption |
|

**Returns:**
[PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) - PasswordSaveOption enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


Representasi string dari PasswordSaveOption.


**Returns:**
java.lang.String - nilai string dari konstanta enum

