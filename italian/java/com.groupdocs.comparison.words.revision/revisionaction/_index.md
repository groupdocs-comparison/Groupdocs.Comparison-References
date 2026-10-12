---
title: "RevisionAction"
second_title: "Riferimento API di GroupDocs.Comparison per Java"
description: "Rappresenta un'azione che può essere applicata a una revisione."
type: docs
weight: 13
url: /it/java/com.groupdocs.comparison.words.revision/revisionaction/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum RevisionAction extends Enum<RevisionAction>
```

Rappresenta un'azione che può essere applicata a una revisione.


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
|  | [NONE](#NONE) | Indica che non è necessario eseguire alcuna azione. |
|
|  | [ACCEPT](#ACCEPT) | Indica che la revisione verrà visualizzata se è di tipo INSERTION, oppure verrà rimossa se il tipo è DELETION. |
|
|  | [REJECT](#REJECT) | Indica che la revisione verrà rimossa se è di tipo INSERTION, oppure verrà visualizzata se il tipo è DELETION. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### NONE {#NONE}
```
public static final RevisionAction NONE
```


Indica che non è necessario eseguire alcuna azione.


### ACCEPT {#ACCEPT}
```
public static final RevisionAction ACCEPT
```


Indica che la revisione verrà visualizzata se è di tipo INSERTION, oppure verrà rimossa se il tipo è DELETION.


### REJECT {#REJECT}
```
public static final RevisionAction REJECT
```


Indica che la revisione verrà rimossa se è di tipo INSERTION, oppure verrà visualizzata se il tipo è DELETION.


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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String |  |

**Returns:**
[RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction)
