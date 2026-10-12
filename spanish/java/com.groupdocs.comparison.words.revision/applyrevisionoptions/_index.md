---
title: "ApplyRevisionOptions"
second_title: "Referencia de API de GroupDocs.Comparison for Java"
description: "La clase ApplyRevisionOptions te permite actualizar el estado de las revisiones antes de que se apliquen al documento final."
type: docs
weight: 10
url: /es/java/com.groupdocs.comparison.words.revision/applyrevisionoptions/
---
**Inheritance:**
java.lang.Object
```
public class ApplyRevisionOptions
```

La clase ApplyRevisionOptions te permite actualizar el estado de las revisiones antes de que se apliquen al documento final.


Proporciona varios constructores y propiedades para personalizar el proceso de aplicación de revisiones.


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


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [ApplyRevisionOptions()](#ApplyRevisionOptions--) | Inicializa una nueva instancia de la clase ApplyRevisionOptions. |
|
|  | [ApplyRevisionOptions(List<RevisionInfo> changes)](#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--) | Instancia un nuevo objeto ApplyRevisionOptions con la lista especificada de revisiones. |
|
|  | [ApplyRevisionOptions(List<RevisionInfo> changes, RevisionAction revisionAction)](#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--com.groupdocs.comparison.words.revision.RevisionAction-) | Instancia un nuevo objeto ApplyRevisionOptions con la lista especificada de revisiones y una acción de revisión común. |
|
|  | [ApplyRevisionOptions(RevisionAction revisionAction)](#ApplyRevisionOptions-com.groupdocs.comparison.words.revision.RevisionAction-) | Instancia un nuevo objeto ApplyRevisionOptions con una acción de revisión común. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getChanges()](#getChanges--) | Obtiene la lista de revisiones que se aplicarán. |
|
|  | [setChanges(List<RevisionInfo> changes)](#setChanges-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--) | Establece la lista de revisiones que se aplicarán. |
|
|  | [getCommonHandler()](#getCommonHandler--) | Obtiene la acción de revisión común que se aplicará a todas las revisiones. |
|
|  | [setCommonHandler(RevisionAction commonHandler)](#setCommonHandler-com.groupdocs.comparison.words.revision.RevisionAction-) | Establece la acción de revisión común que se aplicará a todas las revisiones. |
|
### ApplyRevisionOptions() {#ApplyRevisionOptions--}
```
public ApplyRevisionOptions()
```


Inicializa una nueva instancia de la clase ApplyRevisionOptions.


### ApplyRevisionOptions(List<RevisionInfo> changes) {#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--}
```
public ApplyRevisionOptions(List<RevisionInfo> changes)
```


Instancia un nuevo objeto ApplyRevisionOptions con la lista especificada de revisiones.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | cambios | java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> | La lista de revisiones que se aplicarán |
|

### ApplyRevisionOptions(List<RevisionInfo> changes, RevisionAction revisionAction) {#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--com.groupdocs.comparison.words.revision.RevisionAction-}
```
public ApplyRevisionOptions(List<RevisionInfo> changes, RevisionAction revisionAction)
```


Instancia un nuevo objeto ApplyRevisionOptions con la lista especificada de revisiones y una acción de revisión común.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | cambios | java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> | La lista de revisiones que se aplicarán |
|
|  | revisionAction | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | La acción de revisión común que se aplicará a todas las revisiones |
|

### ApplyRevisionOptions(RevisionAction revisionAction) {#ApplyRevisionOptions-com.groupdocs.comparison.words.revision.RevisionAction-}
```
public ApplyRevisionOptions(RevisionAction revisionAction)
```


Instancia un nuevo objeto ApplyRevisionOptions con una acción de revisión común.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | revisionAction | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | La acción de revisión común que se aplicará a todas las revisiones |
|

### getChanges() {#getChanges--}
```
public List<RevisionInfo> getChanges()
```


Obtiene la lista de revisiones que se aplicarán.


**Returns:**
java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> - la lista de revisiones

### setChanges(List<RevisionInfo> changes) {#setChanges-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--}
```
public void setChanges(List<RevisionInfo> changes)
```


Establece la lista de revisiones que se aplicarán.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | cambios | java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> | La lista de revisiones |
|

### getCommonHandler() {#getCommonHandler--}
```
public RevisionAction getCommonHandler()
```


Obtiene la acción de revisión común que se aplicará a todas las revisiones.


**Returns:**
[RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) - the common revision action

### setCommonHandler(RevisionAction commonHandler) {#setCommonHandler-com.groupdocs.comparison.words.revision.RevisionAction-}
```
public void setCommonHandler(RevisionAction commonHandler)
```


Establece la acción de revisión común que se aplicará a todas las revisiones.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | commonHandler | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | La acción de revisión común |
|

