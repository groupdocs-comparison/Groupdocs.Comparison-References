---
title: "ApplyRevisionOptions"
second_title: "Référence API de GroupDocs.Comparison for Java"
description: "La classe ApplyRevisionOptions vous permet de mettre à jour l'état des révisions avant qu'elles ne soient appliquées au document final."
type: docs
weight: 10
url: /fr/java/com.groupdocs.comparison.words.revision/applyrevisionoptions/
---
**Inheritance:**
java.lang.Object
```
public class ApplyRevisionOptions
```

La classe ApplyRevisionOptions vous permet de mettre à jour l'état des révisions avant qu'elles ne soient appliquées au document final.


Il fournit divers constructeurs et propriétés pour personnaliser le processus d'application de la révision.


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


## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [ApplyRevisionOptions()](#ApplyRevisionOptions--) | Initialise une nouvelle instance de la classe ApplyRevisionOptions. |
|
|  | [ApplyRevisionOptions(List<RevisionInfo> changes)](#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--) | Instancie un nouvel objet ApplyRevisionOptions avec la liste de révisions spécifiée. |
|
|  | [ApplyRevisionOptions(List<RevisionInfo> changes, RevisionAction revisionAction)](#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--com.groupdocs.comparison.words.revision.RevisionAction-) | Instancie un nouvel objet ApplyRevisionOptions avec la liste spécifiée de révisions et une action de révision commune. |
|
|  | [ApplyRevisionOptions(RevisionAction revisionAction)](#ApplyRevisionOptions-com.groupdocs.comparison.words.revision.RevisionAction-) | Instancie un nouvel objet ApplyRevisionOptions avec une action de révision commune. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getChanges()](#getChanges--) | Obtient la liste des révisions à appliquer. |
|
|  | [setChanges(List<RevisionInfo> changes)](#setChanges-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--) | Définit la liste des révisions à appliquer. |
|
|  | [getCommonHandler()](#getCommonHandler--) | Obtient l'action de révision commune à appliquer à toutes les révisions. |
|
|  | [setCommonHandler(RevisionAction commonHandler)](#setCommonHandler-com.groupdocs.comparison.words.revision.RevisionAction-) | Définit l'action de révision commune à appliquer à toutes les révisions. |
|
### ApplyRevisionOptions() {#ApplyRevisionOptions--}
```
public ApplyRevisionOptions()
```


Initialise une nouvelle instance de la classe ApplyRevisionOptions.


### ApplyRevisionOptions(List<RevisionInfo> changes) {#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--}
```
public ApplyRevisionOptions(List<RevisionInfo> changes)
```


Instancie un nouvel objet ApplyRevisionOptions avec la liste de révisions spécifiée.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | modifications | java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> | La liste des révisions à appliquer |
|

### ApplyRevisionOptions(List<RevisionInfo> changes, RevisionAction revisionAction) {#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--com.groupdocs.comparison.words.revision.RevisionAction-}
```
public ApplyRevisionOptions(List<RevisionInfo> changes, RevisionAction revisionAction)
```


Instancie un nouvel objet ApplyRevisionOptions avec la liste spécifiée de révisions et une action de révision commune.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | modifications | java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> | La liste des révisions à appliquer |
|
|  | revisionAction | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | L'action de révision commune à appliquer à toutes les révisions |
|

### ApplyRevisionOptions(RevisionAction revisionAction) {#ApplyRevisionOptions-com.groupdocs.comparison.words.revision.RevisionAction-}
```
public ApplyRevisionOptions(RevisionAction revisionAction)
```


Instancie un nouvel objet ApplyRevisionOptions avec une action de révision commune.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | revisionAction | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | L'action de révision commune à appliquer à toutes les révisions |
|

### getChanges() {#getChanges--}
```
public List<RevisionInfo> getChanges()
```


Obtient la liste des révisions à appliquer.


**Returns:**
java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> - la liste des révisions

### setChanges(List<RevisionInfo> changes) {#setChanges-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--}
```
public void setChanges(List<RevisionInfo> changes)
```


Définit la liste des révisions à appliquer.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | modifications | java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> | La liste des révisions |
|

### getCommonHandler() {#getCommonHandler--}
```
public RevisionAction getCommonHandler()
```


Obtient l'action de révision commune à appliquer à toutes les révisions.


**Returns:**
[RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) - the common revision action

### setCommonHandler(RevisionAction commonHandler) {#setCommonHandler-com.groupdocs.comparison.words.revision.RevisionAction-}
```
public void setCommonHandler(RevisionAction commonHandler)
```


Définit l'action de révision commune à appliquer à toutes les révisions.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | commonHandler | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | L'action de révision commune |
|

