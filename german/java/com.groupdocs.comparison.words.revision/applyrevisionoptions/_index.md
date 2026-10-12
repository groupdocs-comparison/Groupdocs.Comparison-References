---
title: "ApplyRevisionOptions"
second_title: "GroupDocs.Comparison für Java API-Referenz"
description: "Die Klasse ApplyRevisionOptions ermöglicht es Ihnen, den Zustand von Revisionen zu aktualisieren, bevor sie auf das endgültige Dokument angewendet werden."
type: docs
weight: 10
url: /de/java/com.groupdocs.comparison.words.revision/applyrevisionoptions/
---
**Inheritance:**
java.lang.Object
```
public class ApplyRevisionOptions
```

Die Klasse ApplyRevisionOptions ermöglicht es Ihnen, den Zustand von Revisionen zu aktualisieren, bevor sie auf das endgültige Dokument angewendet werden.


Sie bietet verschiedene Konstruktoren und Eigenschaften, um den Anwendungsprozess der Revision anzupassen.


Beispielverwendung:

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


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [ApplyRevisionOptions()](#ApplyRevisionOptions--) | Initialisiert eine neue Instanz der Klasse ApplyRevisionOptions. |
|
|  | [ApplyRevisionOptions(List<RevisionInfo> changes)](#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--) | Instanziiert ein neues ApplyRevisionOptions-Objekt mit der angegebenen Liste von Revisionen. |
|
|  | [ApplyRevisionOptions(List<RevisionInfo> changes, RevisionAction revisionAction)](#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--com.groupdocs.comparison.words.revision.RevisionAction-) | Instanziiert ein neues ApplyRevisionOptions-Objekt mit der angegebenen Liste von Revisionen und einer gemeinsamen Revisionsaktion. |
|
|  | [ApplyRevisionOptions(RevisionAction revisionAction)](#ApplyRevisionOptions-com.groupdocs.comparison.words.revision.RevisionAction-) | Instanziiert ein neues ApplyRevisionOptions-Objekt mit einer gemeinsamen Revisionsaktion. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getChanges()](#getChanges--) | Ruft die Liste der anzuwendenden Revisionen ab. |
|
|  | [setChanges(List<RevisionInfo> changes)](#setChanges-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--) | Setzt die Liste der anzuwendenden Revisionen. |
|
|  | [getCommonHandler()](#getCommonHandler--) | Ruft die gemeinsame Revisionsaktion ab, die auf alle Revisionen angewendet wird. |
|
|  | [setCommonHandler(RevisionAction commonHandler)](#setCommonHandler-com.groupdocs.comparison.words.revision.RevisionAction-) | Setzt die gemeinsame Revisionsaktion, die auf alle Revisionen angewendet wird. |
|
### ApplyRevisionOptions() {#ApplyRevisionOptions--}
```
public ApplyRevisionOptions()
```


Initialisiert eine neue Instanz der Klasse ApplyRevisionOptions.


### ApplyRevisionOptions(List<RevisionInfo> changes) {#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--}
```
public ApplyRevisionOptions(List<RevisionInfo> changes)
```


Instanziiert ein neues ApplyRevisionOptions-Objekt mit der angegebenen Liste von Revisionen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Änderungen | java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> | Die Liste der anzuwendenden Revisionen |
|

### ApplyRevisionOptions(List<RevisionInfo> changes, RevisionAction revisionAction) {#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--com.groupdocs.comparison.words.revision.RevisionAction-}
```
public ApplyRevisionOptions(List<RevisionInfo> changes, RevisionAction revisionAction)
```


Instanziiert ein neues ApplyRevisionOptions-Objekt mit der angegebenen Liste von Revisionen und einer gemeinsamen Revisionsaktion.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Änderungen | java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> | Die Liste der anzuwendenden Revisionen |
|
|  | revisionAction | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | Die gemeinsame Revisionsaktion, die auf alle Revisionen angewendet wird |
|

### ApplyRevisionOptions(RevisionAction revisionAction) {#ApplyRevisionOptions-com.groupdocs.comparison.words.revision.RevisionAction-}
```
public ApplyRevisionOptions(RevisionAction revisionAction)
```


Instanziiert ein neues ApplyRevisionOptions-Objekt mit einer gemeinsamen Revisionsaktion.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | revisionAction | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | Die gemeinsame Revisionsaktion, die auf alle Revisionen angewendet wird |
|

### getChanges() {#getChanges--}
```
public List<RevisionInfo> getChanges()
```


Ruft die Liste der anzuwendenden Revisionen ab.


**Returns:**
java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> - die Liste der Revisionen

### setChanges(List<RevisionInfo> changes) {#setChanges-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--}
```
public void setChanges(List<RevisionInfo> changes)
```


Setzt die Liste der anzuwendenden Revisionen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Änderungen | java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> | Die Liste der Revisionen |
|

### getCommonHandler() {#getCommonHandler--}
```
public RevisionAction getCommonHandler()
```


Ruft die gemeinsame Revisionsaktion ab, die auf alle Revisionen angewendet wird.


**Returns:**
[RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) - the common revision action

### setCommonHandler(RevisionAction commonHandler) {#setCommonHandler-com.groupdocs.comparison.words.revision.RevisionAction-}
```
public void setCommonHandler(RevisionAction commonHandler)
```


Setzt die gemeinsame Revisionsaktion, die auf alle Revisionen angewendet wird.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | commonHandler | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | Die gemeinsame Revisionsaktion |
|

