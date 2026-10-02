---
title: "MetadataType"
second_title: "GroupDocs.Comparison voor Java API-referentie"
description: "Bepaalt vanwaar het resultaatdocument metadata-informatie haalt."
type: docs
weight: 12
url: /nl/java/com.groupdocs.comparison.options.enums/metadatatype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum MetadataType extends Enum<MetadataType>
```

Bepaalt vanwaar het resultaatdocument metadata-informatie haalt.


Voorbeeldgebruik:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    SaveOptions saveOptions = new SaveOptions();
    saveOptions.setCloneMetadataType(MetadataType.FILE_AUTHOR);

    comparer.compare(resultFile, saveOptions);
 }
 
````


## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [DEFAULT](#DEFAULT) | Metadata blijft ongewijzigd. |
|
|  | [SOURCE](#SOURCE) | Metedata zal worden gehaald uit het brondocument. |
|
|  | [TARGET](#TARGET) | Metedata zal worden gehaald uit het doeldocument. |
|
|  | [FILE_AUTHOR](#FILE-AUTHOR) | Metedata zal door de gebruiker worden ingesteld. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Parseert de tekenreeksrepresentatie van MetadataType om de enum-constante te verkrijgen. |
|
|  | [toString()](#toString--) | Stringrepresentatie van MetadataType. |
|
### DEFAULT {#DEFAULT}
```
public static final MetadataType DEFAULT
```


Metadata blijft ongewijzigd.


### SOURCE {#SOURCE}
```
public static final MetadataType SOURCE
```


Metedata zal worden gehaald uit het brondocument.


### TARGET {#TARGET}
```
public static final MetadataType TARGET
```


Metedata zal worden gehaald uit het doeldocument.


### FILE_AUTHOR {#FILE-AUTHOR}
```
public static final MetadataType FILE_AUTHOR
```


Metedata zal door de gebruiker worden ingesteld.


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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String |  |

**Returns:**
[MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static MetadataType fromString(String toStringValue)
```


Parseert de tekenreeksrepresentatie van MetadataType om de enum-constante te verkrijgen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | toStringValue | java.lang.String | De stringrepresentatie van MetadataType |
|

**Returns:**
[MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) - MetadataType enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


Stringrepresentatie van MetadataType.


**Returns:**
java.lang.String - tekenreekswaarde van enum-constante

