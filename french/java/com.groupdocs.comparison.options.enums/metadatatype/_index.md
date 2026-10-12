---
title: "MetadataType"
second_title: "Référence API de GroupDocs.Comparison for Java"
description: "Détermine d'où le document résultat prendra les informations de métadonnées."
type: docs
weight: 12
url: /fr/java/com.groupdocs.comparison.options.enums/metadatatype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum MetadataType extends Enum<MetadataType>
```

Détermine d'où le document résultat prendra les informations de métadonnées.


Exemple d'utilisation :

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    SaveOptions saveOptions = new SaveOptions();
    saveOptions.setCloneMetadataType(MetadataType.FILE_AUTHOR);

    comparer.compare(resultFile, saveOptions);
 }
 
````


## Champs

| Champ | Description |
| --- | --- |
|  | [DEFAULT](#DEFAULT) | Les métadonnées seront laissées telles quelles. |
|
|  | [SOURCE](#SOURCE) | Les métadonnées seront prises du document source. |
|
|  | [TARGET](#TARGET) | Les métadonnées seront prises du document cible. |
|
|  | [FILE_AUTHOR](#FILE-AUTHOR) | Les métadonnées seront définies par l'utilisateur. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Analyse la représentation sous forme de chaîne de MetadataType pour obtenir la constante d'énumération. |
|
|  | [toString()](#toString--) | Représentation sous forme de chaîne de MetadataType. |
|
### DEFAULT {#DEFAULT}
```
public static final MetadataType DEFAULT
```


Les métadonnées seront laissées telles quelles.


### SOURCE {#SOURCE}
```
public static final MetadataType SOURCE
```


Les métadonnées seront prises du document source.


### TARGET {#TARGET}
```
public static final MetadataType TARGET
```


Les métadonnées seront prises du document cible.


### FILE_AUTHOR {#FILE-AUTHOR}
```
public static final MetadataType FILE_AUTHOR
```


Les métadonnées seront définies par l'utilisateur.


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
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String |  |

**Returns:**
[MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static MetadataType fromString(String toStringValue)
```


Analyse la représentation sous forme de chaîne de MetadataType pour obtenir la constante d'énumération.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | toStringValue | java.lang.String | La représentation sous forme de chaîne de MetadataType |
|

**Returns:**
[MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) - MetadataType enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


Représentation sous forme de chaîne de MetadataType.


**Returns:**
java.lang.String - valeur sous forme de chaîne de la constante d'énumération

