---
title: "ChangeType"
second_title: "Riferimento API di GroupDocs.Comparison per Java"
description: "L'enum ChangeType rappresenta i tipi di modifiche che possono verificarsi durante il processo di confronto di documenti."
type: docs
weight: 14
url: /it/java/com.groupdocs.comparison.result/changetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ChangeType extends Enum<ChangeType>
```

L'enum ChangeType rappresenta i tipi di modifiche che possono verificarsi durante il processo di confronto di documenti.


Ogni costante in questo enum rappresenta un tipo specifico di modifica e fornisce una descrizione leggibile dall'uomo e un valore numerico.


Esempio di utilizzo:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);
     comparer.compare();
     final ChangeInfo[] changes = comparer.getChanges();
     for (ChangeInfo changeInfo : changes) {
         // Get the ChangeType for a specific change
         final ChangeType changeType = changeInfo.getType();
         // Print the ChangeType information
         System.out.println("Description: " + changeType.toString());
         System.out.println("Value: " + changeType.toInt());
     }
 }
 
````


## Campi

| Campo | Descrizione |
| --- | --- |
|  | [NONE](#NONE) | Rappresenta nessuna modifica. |
|
|  | [MODIFIED](#MODIFIED) | Rappresenta una modifica modificata. |
|
|  | [INSERTED](#INSERTED) | Rappresenta una modifica inserita. |
|
|  | [DELETED](#DELETED) | Rappresenta una modifica eliminata. |
|
|  | [ADDED](#ADDED) | Rappresenta una modifica aggiunta. |
|
|  | [NOT_MODIFIED](#NOT-MODIFIED) | Rappresenta una modifica non modificata. |
|
|  | [STYLE_CHANGED](#STYLE-CHANGED) | Rappresenta una modifica di stile. |
|
|  | [RESIZED](#RESIZED) | Rappresenta una modifica ridimensionata. |
|
|  | [MOVED](#MOVED) | Rappresenta una modifica spostata. |
|
|  | [MOVED_AND_RESIZED](#MOVED-AND-RESIZED) | Rappresenta una modifica spostata e ridimensionata. |
|
|  | [SHIFTED_AND_RESIZED](#SHIFTED-AND-RESIZED) | Rappresenta una modifica traslata e ridimensionata. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Analizza la rappresentazione stringa di ChangeType per ottenere la costante enum. |
|
|  | [fromInt(int intValue)](#fromInt-int-) | Crea una nuova costante dell'enum ChangeType usando il valore numerico fornito. |
|
|  | [toString()](#toString--) | Rappresentazione stringa di ChangeType. |
|
|  | [toInt()](#toInt--) | Rappresentazione numerica di ChangeType. |
|
### NONE {#NONE}
```
public static final ChangeType NONE
```


Rappresenta nessuna modifica.


### MODIFIED {#MODIFIED}
```
public static final ChangeType MODIFIED
```


Rappresenta una modifica modificata.


### INSERTED {#INSERTED}
```
public static final ChangeType INSERTED
```


Rappresenta una modifica inserita.


### DELETED {#DELETED}
```
public static final ChangeType DELETED
```


Rappresenta una modifica eliminata.


### ADDED {#ADDED}
```
public static final ChangeType ADDED
```


Rappresenta una modifica aggiunta.


### NOT_MODIFIED {#NOT-MODIFIED}
```
public static final ChangeType NOT_MODIFIED
```


Rappresenta una modifica non modificata.


### STYLE_CHANGED {#STYLE-CHANGED}
```
public static final ChangeType STYLE_CHANGED
```


Rappresenta una modifica di stile.


### RESIZED {#RESIZED}
```
public static final ChangeType RESIZED
```


Rappresenta una modifica ridimensionata.


### MOVED {#MOVED}
```
public static final ChangeType MOVED
```


Rappresenta una modifica spostata.


### MOVED_AND_RESIZED {#MOVED-AND-RESIZED}
```
public static final ChangeType MOVED_AND_RESIZED
```


Rappresenta una modifica spostata e ridimensionata.


### SHIFTED_AND_RESIZED {#SHIFTED-AND-RESIZED}
```
public static final ChangeType SHIFTED_AND_RESIZED
```


Rappresenta una modifica traslata e ridimensionata.


### values() {#values--}
```
public static ChangeType[] values()
```




**Returns:**
com.groupdocs.comparison.result.ChangeType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static ChangeType valueOf(String name)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String |  |

**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static ChangeType fromString(String toStringValue)
```


Analizza la rappresentazione stringa di ChangeType per ottenere la costante enum.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | toStringValue | java.lang.String | La rappresentazione stringa di ChangeType |
|

**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - ChangeType enum constant associated with input string

### fromInt(int intValue) {#fromInt-int-}
```
public static ChangeType fromInt(int intValue)
```


Crea una nuova costante dell'enum ChangeType usando il valore numerico fornito.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | intValue | int | La rappresentazione numerica di ChangeType |
|

**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - ChangeType enum constant associated with numeric value

### toString() {#toString--}
```
public String toString()
```


Rappresentazione stringa di ChangeType.


**Returns:**
java.lang.String - valore stringa della costante dell'enumerazione

### toInt() {#toInt--}
```
public int toInt()
```


Rappresentazione numerica di ChangeType.


**Returns:**
int - valore numerico della costante dell'enumerazione

