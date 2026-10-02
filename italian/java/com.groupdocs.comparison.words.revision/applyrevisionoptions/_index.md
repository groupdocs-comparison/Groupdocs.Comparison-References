---
title: "ApplyRevisionOptions"
second_title: "Riferimento API di GroupDocs.Comparison per Java"
description: "La classe ApplyRevisionOptions consente di aggiornare lo stato delle revisioni prima che vengano applicate al documento finale."
type: docs
weight: 10
url: /it/java/com.groupdocs.comparison.words.revision/applyrevisionoptions/
---
**Inheritance:**
java.lang.Object
```
public class ApplyRevisionOptions
```

La classe ApplyRevisionOptions consente di aggiornare lo stato delle revisioni prima che vengano applicate al documento finale.


Fornisce vari costruttori e proprietà per personalizzare il processo di applicazione della revisione.


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


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [ApplyRevisionOptions()](#ApplyRevisionOptions--) | Inizializza una nuova istanza della classe ApplyRevisionOptions. |
|
|  | [ApplyRevisionOptions(List<RevisionInfo> changes)](#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--) | Istanzia un nuovo oggetto ApplyRevisionOptions con l'elenco specificato di revisioni. |
|
|  | [ApplyRevisionOptions(List<RevisionInfo> changes, RevisionAction revisionAction)](#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--com.groupdocs.comparison.words.revision.RevisionAction-) | Istanzia un nuovo oggetto ApplyRevisionOptions con l'elenco specificato di revisioni e un'azione di revisione comune. |
|
|  | [ApplyRevisionOptions(RevisionAction revisionAction)](#ApplyRevisionOptions-com.groupdocs.comparison.words.revision.RevisionAction-) | Istanzia un nuovo oggetto ApplyRevisionOptions con un'azione di revisione comune. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getChanges()](#getChanges--) | Ottiene l'elenco delle revisioni da applicare. |
|
|  | [setChanges(List<RevisionInfo> changes)](#setChanges-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--) | Imposta l'elenco delle revisioni da applicare. |
|
|  | [getCommonHandler()](#getCommonHandler--) | Ottiene l'azione di revisione comune da applicare a tutte le revisioni. |
|
|  | [setCommonHandler(RevisionAction commonHandler)](#setCommonHandler-com.groupdocs.comparison.words.revision.RevisionAction-) | Imposta l'azione di revisione comune da applicare a tutte le revisioni. |
|
### ApplyRevisionOptions() {#ApplyRevisionOptions--}
```
public ApplyRevisionOptions()
```


Inizializza una nuova istanza della classe ApplyRevisionOptions.


### ApplyRevisionOptions(List<RevisionInfo> changes) {#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--}
```
public ApplyRevisionOptions(List<RevisionInfo> changes)
```


Istanzia un nuovo oggetto ApplyRevisionOptions con l'elenco specificato di revisioni.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | modifiche | java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> | L'elenco delle revisioni da applicare |
|

### ApplyRevisionOptions(List<RevisionInfo> changes, RevisionAction revisionAction) {#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--com.groupdocs.comparison.words.revision.RevisionAction-}
```
public ApplyRevisionOptions(List<RevisionInfo> changes, RevisionAction revisionAction)
```


Istanzia un nuovo oggetto ApplyRevisionOptions con l'elenco specificato di revisioni e un'azione di revisione comune.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | modifiche | java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> | L'elenco delle revisioni da applicare |
|
|  | revisionAction | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | L'azione di revisione comune da applicare a tutte le revisioni |
|

### ApplyRevisionOptions(RevisionAction revisionAction) {#ApplyRevisionOptions-com.groupdocs.comparison.words.revision.RevisionAction-}
```
public ApplyRevisionOptions(RevisionAction revisionAction)
```


Istanzia un nuovo oggetto ApplyRevisionOptions con un'azione di revisione comune.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | revisionAction | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | L'azione di revisione comune da applicare a tutte le revisioni |
|

### getChanges() {#getChanges--}
```
public List<RevisionInfo> getChanges()
```


Ottiene l'elenco delle revisioni da applicare.


**Returns:**
java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> - l'elenco delle revisioni

### setChanges(List<RevisionInfo> changes) {#setChanges-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--}
```
public void setChanges(List<RevisionInfo> changes)
```


Imposta l'elenco delle revisioni da applicare.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | modifiche | java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> | L'elenco delle revisioni |
|

### getCommonHandler() {#getCommonHandler--}
```
public RevisionAction getCommonHandler()
```


Ottiene l'azione di revisione comune da applicare a tutte le revisioni.


**Returns:**
[RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) - the common revision action

### setCommonHandler(RevisionAction commonHandler) {#setCommonHandler-com.groupdocs.comparison.words.revision.RevisionAction-}
```
public void setCommonHandler(RevisionAction commonHandler)
```


Imposta l'azione di revisione comune da applicare a tutte le revisioni.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | commonHandler | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | L'azione di revisione comune |
|

