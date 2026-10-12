---
title: "RevisionAction"
second_title: "Referencia de API de GroupDocs.Comparison for Java"
description: "Representa una acción que puede aplicarse a una revisión."
type: docs
weight: 13
url: /es/java/com.groupdocs.comparison.words.revision/revisionaction/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum RevisionAction extends Enum<RevisionAction>
```

Representa una acción que puede aplicarse a una revisión.


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
|  | [NONE](#NONE) | Indica que no se debe realizar ninguna acción. |
|
|  | [ACCEPT](#ACCEPT) | Indica que la revisión se mostrará si es de tipo INSERTION, o se eliminará si el tipo es DELETION. |
|
|  | [REJECT](#REJECT) | Indica que la revisión se eliminará si es de tipo INSERTION, o se mostrará si el tipo es DELETION. |
|
## Métodos

| Método | Descripción |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### NONE {#NONE}
```
public static final RevisionAction NONE
```


Indica que no se debe realizar ninguna acción.


### ACCEPT {#ACCEPT}
```
public static final RevisionAction ACCEPT
```


Indica que la revisión se mostrará si es de tipo INSERTION, o se eliminará si el tipo es DELETION.


### REJECT {#REJECT}
```
public static final RevisionAction REJECT
```


Indica que la revisión se eliminará si es de tipo INSERTION, o se mostrará si el tipo es DELETION.


### values() {#values--}
```
public static RevisionAction[] values()
```




**Returns:**
com.groupdocs.comparison.words.revision.RevisionAction[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static RevisionAction valueOf(String name)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String |  |

**Returns:**
[RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction)
