---
title: "MetadataType"
second_title: "GroupDocs.Comparison für Java API-Referenz"
description: "Bestimmt, von wo das Ergebnisdokument Metadateninformationen übernimmt."
type: docs
weight: 12
url: /de/java/com.groupdocs.comparison.options.enums/metadatatype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum MetadataType extends Enum<MetadataType>
```

Bestimmt, von wo das Ergebnisdokument Metadateninformationen übernimmt.


Beispielverwendung:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    SaveOptions saveOptions = new SaveOptions();
    saveOptions.setCloneMetadataType(MetadataType.FILE_AUTHOR);

    comparer.compare(resultFile, saveOptions);
 }
 
````


## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [DEFAULT](#DEFAULT) | Metadaten bleiben unverändert. |
|
|  | [SOURCE](#SOURCE) | Metadaten werden aus dem Quelldokument übernommen. |
|
|  | [TARGET](#TARGET) | Metadaten werden aus dem Zieldokument übernommen. |
|
|  | [FILE_AUTHOR](#FILE-AUTHOR) | Metadaten werden vom Benutzer festgelegt. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Parst die String-Darstellung von MetadataType, um die Enum-Konstante zu erhalten. |
|
|  | [toString()](#toString--) | String-Darstellung von MetadataType. |
|
### DEFAULT {#DEFAULT}
```
public static final MetadataType DEFAULT
```


Metadaten bleiben unverändert.


### SOURCE {#SOURCE}
```
public static final MetadataType SOURCE
```


Metadaten werden aus dem Quelldokument übernommen.


### TARGET {#TARGET}
```
public static final MetadataType TARGET
```


Metadaten werden aus dem Zieldokument übernommen.


### FILE_AUTHOR {#FILE-AUTHOR}
```
public static final MetadataType FILE_AUTHOR
```


Metadaten werden vom Benutzer festgelegt.


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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String |  |

**Returns:**
[MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static MetadataType fromString(String toStringValue)
```


Parst die String-Darstellung von MetadataType, um die Enum-Konstante zu erhalten.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | toStringValue | java.lang.String | Die String-Darstellung von MetadataType |
|

**Returns:**
[MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) - MetadataType enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


String-Darstellung von MetadataType.


**Returns:**
java.lang.String - String-Wert der Enum-Konstante

