---
title: "MetadataType"
second_title: "GroupDocs.Comparison för Java API-referens"
description: "Bestämmer varifrån resultatsdokumentet hämtar metadata."
type: docs
weight: 12
url: /sv/java/com.groupdocs.comparison.options.enums/metadatatype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum MetadataType extends Enum<MetadataType>
```

Bestämmer varifrån resultatsdokumentet hämtar metadata.


Exempel på användning:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    SaveOptions saveOptions = new SaveOptions();
    saveOptions.setCloneMetadataType(MetadataType.FILE_AUTHOR);

    comparer.compare(resultFile, saveOptions);
 }
 
````


## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [DEFAULT](#DEFAULT) | Metadata kommer att lämnas oförändrade. |
|
|  | [SOURCE](#SOURCE) | Metedata kommer att tas från källdokumentet. |
|
|  | [TARGET](#TARGET) | Metedata kommer att tas från måldokumentet. |
|
|  | [FILE_AUTHOR](#FILE-AUTHOR) | Metedata kommer att sättas av användaren. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Analyserar strängrepresentationen av MetadataType för att få enum‑konstanten. |
|
|  | [toString()](#toString--) | Strängrepresentation av MetadataType. |
|
### DEFAULT {#DEFAULT}
```
public static final MetadataType DEFAULT
```


Metadata kommer att lämnas oförändrade.


### SOURCE {#SOURCE}
```
public static final MetadataType SOURCE
```


Metedata kommer att tas från källdokumentet.


### TARGET {#TARGET}
```
public static final MetadataType TARGET
```


Metedata kommer att tas från måldokumentet.


### FILE_AUTHOR {#FILE-AUTHOR}
```
public static final MetadataType FILE_AUTHOR
```


Metedata kommer att sättas av användaren.


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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String |  |

**Returns:**
[MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static MetadataType fromString(String toStringValue)
```


Analyserar strängrepresentationen av MetadataType för att få enum‑konstanten.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | toStringValue | java.lang.String | Strängrepresentationen av MetadataType |
|

**Returns:**
[MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) - MetadataType enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


Strängrepresentation av MetadataType.


**Returns:**
java.lang.String - strängvärde av enum‑konstant

