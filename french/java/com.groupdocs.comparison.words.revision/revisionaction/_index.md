---
title: "RevisionAction"
second_title: "Référence API de GroupDocs.Comparison for Java"
description: "Représente une action qui peut être appliquée à une révision."
type: docs
weight: 13
url: /fr/java/com.groupdocs.comparison.words.revision/revisionaction/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum RevisionAction extends Enum<RevisionAction>
```

Représente une action qui peut être appliquée à une révision.


Exemple d'utilisation :

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


## Champs

| Champ | Description |
| --- | --- |
|  | [NONE](#NONE) | Indique qu'aucune action ne doit être effectuée. |
|
|  | [ACCEPT](#ACCEPT) | Indique que la révision sera affichée si elle est de type INSERTION, ou qu'elle sera supprimée si le type est DELETION. |
|
|  | [REJECT](#REJECT) | Indique que la révision sera supprimée si elle est de type INSERTION, ou qu'elle sera affichée si le type est DELETION. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### NONE {#NONE}
```
public static final RevisionAction NONE
```


Indique qu'aucune action ne doit être effectuée.


### ACCEPT {#ACCEPT}
```
public static final RevisionAction ACCEPT
```


Indique que la révision sera affichée si elle est de type INSERTION, ou qu'elle sera supprimée si le type est DELETION.


### REJECT {#REJECT}
```
public static final RevisionAction REJECT
```


Indique que la révision sera supprimée si elle est de type INSERTION, ou qu'elle sera affichée si le type est DELETION.


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
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String |  |

**Returns:**
[RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction)
