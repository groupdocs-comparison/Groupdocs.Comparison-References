---
title: "PasswordSaveOption"
second_title: "GroupDocs.Comparison for Java API Referansı"
description: "Karşılaştırma sürecinde bir belgede şifre bilgisinin kaydedilmesi seçeneklerini listeler."
type: docs
weight: 14
url: /tr/java/com.groupdocs.comparison.options.enums/passwordsaveoption/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PasswordSaveOption extends Enum<PasswordSaveOption>
```

Karşılaştırma sürecinde bir belgede şifre bilgisinin kaydedilmesi seçeneklerini listeler.


Örnek kullanım:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setPasswordSaveOption(PasswordSaveOption.SOURCE);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [NONE](#NONE) | Şifreyi kaydetme. |
|
|  | [SOURCE](#SOURCE) | Kaynak belgeden şifreyi kullan. |
|
|  | [TARGET](#TARGET) | Hedef belgeden şifreyi kullan. |
|
|  | [USER](#USER) | \* Kullanıcı tarafından sağlanan şifreyi kullan. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | PasswordSaveOption'in dize temsilini ayrıştırarak enum sabitini alır. |
|
|  | [toString()](#toString--) | PasswordSaveOption'in dize temsili. |
|
### NONE {#NONE}
```
public static final PasswordSaveOption NONE
```


Şifreyi kaydetme.


### SOURCE {#SOURCE}
```
public static final PasswordSaveOption SOURCE
```


Kaynak belgeden şifreyi kullan.


### TARGET {#TARGET}
```
public static final PasswordSaveOption TARGET
```


Hedef belgeden şifreyi kullan.


### USER {#USER}
```
public static final PasswordSaveOption USER
```


\* Kullanıcı tarafından sağlanan şifreyi kullan.


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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static PasswordSaveOption fromString(String toStringValue)
```


PasswordSaveOption'in dize temsilini ayrıştırarak enum sabitini alır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | toStringValue | java.lang.String | PasswordSaveOption'in dize temsili |
|

**Returns:**
[PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) - PasswordSaveOption enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


PasswordSaveOption'in dize temsili.


**Returns:**
java.lang.String - enum sabitinin dize değeri

