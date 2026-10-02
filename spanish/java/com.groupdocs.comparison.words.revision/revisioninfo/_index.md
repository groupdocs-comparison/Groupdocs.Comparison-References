---
title: "RevisionInfo"
second_title: "Referencia de API de GroupDocs.Comparison for Java"
description: "Representa una revisión en el documento."
type: docs
weight: 12
url: /es/java/com.groupdocs.comparison.words.revision/revisioninfo/
---
**Inheritance:**
java.lang.Object
```
public class RevisionInfo
```

Representa una revisión en el documento.


Una revisión encapsula información sobre el cambio de revisión realizado en el documento.
Esta clase proporciona métodos para obtener información sobre la revisión, como su tipo,
contenido, autor y demás.

Ejemplo de uso:

````

 try (RevisionHandler revisionHandler = new RevisionHandler(sourceFile)) {
     List revisionList = revisionHandler.getRevisions();

     for (RevisionInfo revisionInfo : revisionList) {
         System.out.println("Revision Type: " + revisionInfo.getType());
         System.out.println("Text: " + revisionInfo.getText());
         System.out.println("Author: " + revisionInfo.getAuthor());
     }
 }
 
````


## Constructores

| Constructor | Descripción |
| --- | --- |
| [RevisionInfo()](#RevisionInfo--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getAction()](#getAction--) | Obtiene la acción asociada a la revisión (aceptar o rechazar). |
|
|  | [setAction(RevisionAction value)](#setAction-com.groupdocs.comparison.words.revision.RevisionAction-) | Establece el valor asociado a la revisión (aceptar o rechazar). |
|
|  | [getText()](#getText--) | Obtiene el contenido de texto de la revisión. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Establece el contenido del valor de la revisión. |
|
|  | [getAuthor()](#getAuthor--) | Obtiene el autor de la revisión. |
|
|  | [setAuthor(String value)](#setAuthor-java.lang.String-) | Establece el valor de la revisión. |
|
|  | [getType()](#getType--) | Obtiene el tipo de la revisión; dependiendo del tipo, la lógica de Acción (aceptar o rechazar) cambia. |
|
|  | [setType(RevisionType value)](#setType-com.groupdocs.comparison.words.revision.RevisionType-) | Establece el valor de la revisión; dependiendo del valor, la lógica de Acción (aceptar o rechazar) cambia. |
|
### RevisionInfo() {#RevisionInfo--}
```
public RevisionInfo()
```


### getAction() {#getAction--}
```
public RevisionAction getAction()
```


Obtiene la acción asociada a la revisión (aceptar o rechazar). Este campo le permite influir en la visualización de la revisión.


**Returns:**
[RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) - the action associated with the revision.

### setAction(RevisionAction value) {#setAction-com.groupdocs.comparison.words.revision.RevisionAction-}
```
public void setAction(RevisionAction value)
```


Establece el valor asociado a la revisión (aceptar o rechazar). Este campo le permite influir en la visualización de la revisión.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | El valor asociado a la revisión. |
|

### getText() {#getText--}
```
public String getText()
```


Obtiene el contenido de texto de la revisión.


**Returns:**
java.lang.String - el contenido de texto de la revisión.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Establece el contenido del valor de la revisión.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.String | El contenido del valor de la revisión. |
|

### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Obtiene el autor de la revisión.


**Returns:**
java.lang.String - el autor de la revisión.

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public void setAuthor(String value)
```


Establece el valor de la revisión.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.String | El valor de la revisión. |
|

### getType() {#getType--}
```
public RevisionType getType()
```


Obtiene el tipo de la revisión; dependiendo del tipo, la lógica de Acción (aceptar o rechazar) cambia.


**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) - the type of the revision.

### setType(RevisionType value) {#setType-com.groupdocs.comparison.words.revision.RevisionType-}
```
public void setType(RevisionType value)
```


Establece el valor de la revisión; dependiendo del valor, la lógica de Acción (aceptar o rechazar) cambia.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) | El valor de la revisión. |
|

