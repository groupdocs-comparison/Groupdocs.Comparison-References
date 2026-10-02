---
title: "MetadataType"
second_title: "Referencia de API de GroupDocs.Comparison for Java"
description: "Determina de dónde el documento resultante obtendrá la información de metadatos."
type: docs
weight: 12
url: /es/java/com.groupdocs.comparison.options.enums/metadatatype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum MetadataType extends Enum<MetadataType>
```

Determina de dónde el documento resultante obtendrá la información de metadatos.


Ejemplo de uso:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    SaveOptions saveOptions = new SaveOptions();
    saveOptions.setCloneMetadataType(MetadataType.FILE_AUTHOR);

    comparer.compare(resultFile, saveOptions);
 }
 
````


## Campos

| Campo | Descripción |
| --- | --- |
|  | [DEFAULT](#DEFAULT) | Los metadatos se dejarán tal como están. |
|
|  | [SOURCE](#SOURCE) | Metedata se tomará del documento de origen. |
|
|  | [TARGET](#TARGET) | Metedata se tomará del documento de destino. |
|
|  | [FILE_AUTHOR](#FILE-AUTHOR) | Metedata será establecido por el usuario. |
|
## Métodos

| Método | Descripción |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Analiza la representación en cadena de MetadataType para obtener la constante enum. |
|
|  | [toString()](#toString--) | Representación en cadena de MetadataType. |
|
### DEFAULT {#DEFAULT}
```
public static final MetadataType DEFAULT
```


Los metadatos se dejarán tal como están.


### SOURCE {#SOURCE}
```
public static final MetadataType SOURCE
```


Metedata se tomará del documento de origen.


### TARGET {#TARGET}
```
public static final MetadataType TARGET
```


Metedata se tomará del documento de destino.


### FILE_AUTHOR {#FILE-AUTHOR}
```
public static final MetadataType FILE_AUTHOR
```


Metedata será establecido por el usuario.


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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String |  |

**Returns:**
[MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static MetadataType fromString(String toStringValue)
```


Analiza la representación en cadena de MetadataType para obtener la constante enum.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | toStringValue | java.lang.String | La representación en cadena de MetadataType |
|

**Returns:**
[MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) - MetadataType enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


Representación en cadena de MetadataType.


**Returns:**
java.lang.String - valor en cadena de la constante del enum

