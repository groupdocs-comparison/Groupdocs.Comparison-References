---
title: "MetadataType"
second_title: "GroupDocs.Comparison for Java API Referansı"
description: "Sonuç belgesinin meta veri bilgisini nereden alacağını belirler."
type: docs
weight: 12
url: /tr/java/com.groupdocs.comparison.options.enums/metadatatype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum MetadataType extends Enum<MetadataType>
```

Sonuç belgesinin meta veri bilgisini nereden alacağını belirler.


Örnek kullanım:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    SaveOptions saveOptions = new SaveOptions();
    saveOptions.setCloneMetadataType(MetadataType.FILE_AUTHOR);

    comparer.compare(resultFile, saveOptions);
 }
 
````


## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [DEFAULT](#DEFAULT) | Meta veri olduğu gibi bırakılacak. |
|
|  | [SOURCE](#SOURCE) | Metedata kaynak belgeden alınacak. |
|
|  | [TARGET](#TARGET) | Metedata hedef belgeden alınacak. |
|
|  | [FILE_AUTHOR](#FILE-AUTHOR) | Metedata kullanıcı tarafından ayarlanacak. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | MetadataType'ın dize temsilini ayrıştırarak enum sabitini alır. |
|
|  | [toString()](#toString--) | MetadataType'ın dize temsili. |
|
### DEFAULT {#DEFAULT}
```
public static final MetadataType DEFAULT
```


Meta veri olduğu gibi bırakılacak.


### SOURCE {#SOURCE}
```
public static final MetadataType SOURCE
```


Metedata kaynak belgeden alınacak.


### TARGET {#TARGET}
```
public static final MetadataType TARGET
```


Metedata hedef belgeden alınacak.


### FILE_AUTHOR {#FILE-AUTHOR}
```
public static final MetadataType FILE_AUTHOR
```


Metedata kullanıcı tarafından ayarlanacak.


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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static MetadataType fromString(String toStringValue)
```


MetadataType'ın dize temsilini ayrıştırarak enum sabitini alır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | toStringValue | java.lang.String | MetadataType'ın dize temsili |
|

**Returns:**
[MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) - MetadataType enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


MetadataType'ın dize temsili.


**Returns:**
java.lang.String - enum sabitinin dize değeri

