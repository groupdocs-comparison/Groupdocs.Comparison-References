---
title: "RevisionType"
second_title: "Riferimento API di GroupDocs.Comparison per Java"
description: "Rappresenta i tipi di revisioni in un documento."
type: docs
weight: 14
url: /it/java/com.groupdocs.comparison.words.revision/revisiontype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum RevisionType extends Enum<RevisionType>
```

Rappresenta i tipi di revisioni in un documento.


Esempio di utilizzo:

````

 try (RevisionHandler revisionHandler = new RevisionHandler(sourceFile)) {
     List revisionList = revisionHandler.getRevisions();

     for (RevisionInfo revisionInfo : revisionList) {
         if (revisionInfo.getType() == RevisionType.DELETION)
             // Set an action to be applied to the revision
             revisionInfo.setAction(RevisionAction.Accept);
     }
     // Create an instance of ApplyRevisionOptions
     ApplyRevisionOptions revisionChanges = new ApplyRevisionOptions();
     revisionChanges.setChanges(revisionList);
     // Apply the revisions using the options
     revisionHandler.applyRevisionChanges(resultFile, revisionChanges);
 }
 
````


## Campi

| Campo | Descrizione |
| --- | --- |
|  | [INSERTION](#INSERTION) | Rappresenta un tipo quando nuovo contenuto è stato inserito nel documento. |
|
|  | [DELETION](#DELETION) | Rappresenta un tipo quando il contenuto è stato rimosso dal documento. |
|
|  | [FORMAT_CHANGE](#FORMAT-CHANGE) | Rappresenta un tipo quando è stata applicata una modifica di formattazione al nodo genitore. |
|
|  | [STYLE_DEFINITION_CHANGE](#STYLE-DEFINITION-CHANGE) | Rappresenta un tipo quando è stata applicata una modifica di formattazione allo stile genitore. |
|
|  | [MOVING](#MOVING) | Rappresenta un tipo quando il contenuto è stato spostato nel documento. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromInt(int toIntValue)](#fromInt-int-) | Crea una nuova costante dell'enumerazione RevisionType usando il valore numerico fornito. |
|
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Analizza la rappresentazione stringa di RevisionType per ottenere la costante dell'enumerazione. |
|
|  | [toInt()](#toInt--) | Rappresentazione numerica di RevisionType. |
|
|  | [toString()](#toString--) | Rappresentazione stringa di RevisionType. |
|
### INSERTION {#INSERTION}
```
public static final RevisionType INSERTION
```


Rappresenta un tipo quando nuovo contenuto è stato inserito nel documento.


### DELETION {#DELETION}
```
public static final RevisionType DELETION
```


Rappresenta un tipo quando il contenuto è stato rimosso dal documento.


### FORMAT_CHANGE {#FORMAT-CHANGE}
```
public static final RevisionType FORMAT_CHANGE
```


Rappresenta un tipo quando è stata applicata una modifica di formattazione al nodo genitore.


### STYLE_DEFINITION_CHANGE {#STYLE-DEFINITION-CHANGE}
```
public static final RevisionType STYLE_DEFINITION_CHANGE
```


Rappresenta un tipo quando è stata applicata una modifica di formattazione allo stile genitore.


### MOVING {#MOVING}
```
public static final RevisionType MOVING
```


Rappresenta un tipo quando il contenuto è stato spostato nel documento.


### values() {#values--}
```
public static RevisionType[] values()
```




**Returns:**
com.groupdocs.comparison.words.revision.RevisionType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static RevisionType valueOf(String name)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String |  |

**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype)
### fromInt(int toIntValue) {#fromInt-int-}
```
public static RevisionType fromInt(int toIntValue)
```


Crea una nuova costante dell'enumerazione RevisionType usando il valore numerico fornito.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | toIntValue | int | La rappresentazione numerica di RevisionType |
|

**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) - RevisionType enum constant associated with numeric value

### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static RevisionType fromString(String toStringValue)
```


Analizza la rappresentazione stringa di RevisionType per ottenere la costante dell'enumerazione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | toStringValue | java.lang.String | La rappresentazione stringa di RevisionType |
|

**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) - RevisionType enum constant associated with input string

### toInt() {#toInt--}
```
public int toInt()
```


Rappresentazione numerica di RevisionType.


**Returns:**
int - valore numerico della costante dell'enumerazione

### toString() {#toString--}
```
public String toString()
```


Rappresentazione stringa di RevisionType.


**Returns:**
java.lang.String - valore stringa della costante dell'enumerazione

