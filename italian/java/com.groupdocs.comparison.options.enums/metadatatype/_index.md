---
title: "MetadataType"
second_title: "Riferimento API di GroupDocs.Comparison per Java"
description: "Determina da dove il documento risultato prenderà le informazioni dei metadati."
type: docs
weight: 12
url: /it/java/com.groupdocs.comparison.options.enums/metadatatype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum MetadataType extends Enum<MetadataType>
```

Determina da dove il documento risultato prenderà le informazioni dei metadati.


Esempio di utilizzo:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    SaveOptions saveOptions = new SaveOptions();
    saveOptions.setCloneMetadataType(MetadataType.FILE_AUTHOR);

    comparer.compare(resultFile, saveOptions);
 }
 
````


## Campi

| Campo | Descrizione |
| --- | --- |
|  | [DEFAULT](#DEFAULT) | I metadati verranno lasciati così come sono. |
|
|  | [SOURCE](#SOURCE) | I metadati verranno presi dal documento di origine. |
|
|  | [TARGET](#TARGET) | I metadati verranno presi dal documento di destinazione. |
|
|  | [FILE_AUTHOR](#FILE-AUTHOR) | I metadati verranno impostati dall'utente. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Analizza la rappresentazione stringa di MetadataType per ottenere la costante enum. |
|
|  | [toString()](#toString--) | Rappresentazione stringa di MetadataType. |
|
### DEFAULT {#DEFAULT}
```
public static final MetadataType DEFAULT
```


I metadati verranno lasciati così come sono.


### SOURCE {#SOURCE}
```
public static final MetadataType SOURCE
```


I metadati verranno presi dal documento di origine.


### TARGET {#TARGET}
```
public static final MetadataType TARGET
```


I metadati verranno presi dal documento di destinazione.


### FILE_AUTHOR {#FILE-AUTHOR}
```
public static final MetadataType FILE_AUTHOR
```


I metadati verranno impostati dall'utente.


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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String |  |

**Returns:**
[MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static MetadataType fromString(String toStringValue)
```


Analizza la rappresentazione stringa di MetadataType per ottenere la costante enum.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | toStringValue | java.lang.String | La rappresentazione stringa di MetadataType |
|

**Returns:**
[MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) - MetadataType enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


Rappresentazione stringa di MetadataType.


**Returns:**
java.lang.String - valore stringa della costante dell'enumerazione

