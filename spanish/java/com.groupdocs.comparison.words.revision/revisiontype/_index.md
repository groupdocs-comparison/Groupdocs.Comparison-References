---
title: "RevisionType"
second_title: "Referencia de API de GroupDocs.Comparison for Java"
description: "Representa los tipos de revisiones en un documento."
type: docs
weight: 14
url: /es/java/com.groupdocs.comparison.words.revision/revisiontype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum RevisionType extends Enum<RevisionType>
```

Representa los tipos de revisiones en un documento.


Ejemplo de uso:

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


## Campos

| Campo | Descripción |
| --- | --- |
|  | [INSERTION](#INSERTION) | Representa un tipo cuando se insertó contenido nuevo en el documento. |
|
|  | [DELETION](#DELETION) | Representa un tipo cuando se eliminó contenido del documento. |
|
|  | [FORMAT_CHANGE](#FORMAT-CHANGE) | Representa un tipo cuando se aplicó un cambio de formato al nodo padre. |
|
|  | [STYLE_DEFINITION_CHANGE](#STYLE-DEFINITION-CHANGE) | Representa un tipo cuando se aplicó un cambio de formato al estilo padre. |
|
|  | [MOVING](#MOVING) | Representa un tipo cuando se movió contenido en el documento. |
|
## Métodos

| Método | Descripción |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromInt(int toIntValue)](#fromInt-int-) | Crea una nueva constante del enum RevisionType usando el valor numérico proporcionado. |
|
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Analiza la representación en cadena de RevisionType para obtener la constante del enum. |
|
|  | [toInt()](#toInt--) | Representación numérica de RevisionType. |
|
|  | [toString()](#toString--) | Representación en cadena de RevisionType. |
|
### INSERTION {#INSERTION}
```
public static final RevisionType INSERTION
```


Representa un tipo cuando se insertó contenido nuevo en el documento.


### DELETION {#DELETION}
```
public static final RevisionType DELETION
```


Representa un tipo cuando se eliminó contenido del documento.


### FORMAT_CHANGE {#FORMAT-CHANGE}
```
public static final RevisionType FORMAT_CHANGE
```


Representa un tipo cuando se aplicó un cambio de formato al nodo padre.


### STYLE_DEFINITION_CHANGE {#STYLE-DEFINITION-CHANGE}
```
public static final RevisionType STYLE_DEFINITION_CHANGE
```


Representa un tipo cuando se aplicó un cambio de formato al estilo padre.


### MOVING {#MOVING}
```
public static final RevisionType MOVING
```


Representa un tipo cuando se movió contenido en el documento.


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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String |  |

**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype)
### fromInt(int toIntValue) {#fromInt-int-}
```
public static RevisionType fromInt(int toIntValue)
```


Crea una nueva constante del enum RevisionType usando el valor numérico proporcionado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | toIntValue | int | La representación numérica de RevisionType |
|

**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) - RevisionType enum constant associated with numeric value

### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static RevisionType fromString(String toStringValue)
```


Analiza la representación en cadena de RevisionType para obtener la constante del enum.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | toStringValue | java.lang.String | La representación en cadena de RevisionType |
|

**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) - RevisionType enum constant associated with input string

### toInt() {#toInt--}
```
public int toInt()
```


Representación numérica de RevisionType.


**Returns:**
int - valor numérico de la constante del enum

### toString() {#toString--}
```
public String toString()
```


Representación en cadena de RevisionType.


**Returns:**
java.lang.String - valor en cadena de la constante del enum

