---
title: "ApplyRevisionOptions"
second_title: "GroupDocs.Comparison voor Java API-referentie"
description: "De ApplyRevisionOptions-klasse stelt je in staat de status van revisies bij te werken voordat ze op het uiteindelijke document worden toegepast."
type: docs
weight: 10
url: /nl/java/com.groupdocs.comparison.words.revision/applyrevisionoptions/
---
**Inheritance:**
java.lang.Object
```
public class ApplyRevisionOptions
```

De ApplyRevisionOptions-klasse stelt je in staat de status van revisies bij te werken voordat ze op het uiteindelijke document worden toegepast.


Het biedt verschillende constructors en eigenschappen om het revisietoepassingsproces aan te passen.


Voorbeeldgebruik:

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


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [ApplyRevisionOptions()](#ApplyRevisionOptions--) | Initialiseert een nieuw exemplaar van de ApplyRevisionOptions-klasse. |
|
|  | [ApplyRevisionOptions(List<RevisionInfo> changes)](#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--) | Instantieert een nieuw ApplyRevisionOptions-object met de opgegeven lijst van revisies. |
|
|  | [ApplyRevisionOptions(List<RevisionInfo> changes, RevisionAction revisionAction)](#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--com.groupdocs.comparison.words.revision.RevisionAction-) | Instantieert een nieuw ApplyRevisionOptions-object met de opgegeven lijst van revisies en een gemeenschappelijke revisie‑actie. |
|
|  | [ApplyRevisionOptions(RevisionAction revisionAction)](#ApplyRevisionOptions-com.groupdocs.comparison.words.revision.RevisionAction-) | Instantieert een nieuw ApplyRevisionOptions-object met een gemeenschappelijke revisie‑actie. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getChanges()](#getChanges--) | Haalt de lijst met revisies op die moeten worden toegepast. |
|
|  | [setChanges(List<RevisionInfo> changes)](#setChanges-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--) | Stelt de lijst met revisies in die moeten worden toegepast. |
|
|  | [getCommonHandler()](#getCommonHandler--) | Haalt de gemeenschappelijke revisie‑actie op die op alle revisies moet worden toegepast. |
|
|  | [setCommonHandler(RevisionAction commonHandler)](#setCommonHandler-com.groupdocs.comparison.words.revision.RevisionAction-) | Stelt de gemeenschappelijke revisie‑actie in die op alle revisies moet worden toegepast. |
|
### ApplyRevisionOptions() {#ApplyRevisionOptions--}
```
public ApplyRevisionOptions()
```


Initialiseert een nieuw exemplaar van de ApplyRevisionOptions-klasse.


### ApplyRevisionOptions(List<RevisionInfo> changes) {#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--}
```
public ApplyRevisionOptions(List<RevisionInfo> changes)
```


Instantieert een nieuw ApplyRevisionOptions-object met de opgegeven lijst van revisies.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | wijzigingen | java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> | De lijst met revisies die moeten worden toegepast |
|

### ApplyRevisionOptions(List<RevisionInfo> changes, RevisionAction revisionAction) {#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--com.groupdocs.comparison.words.revision.RevisionAction-}
```
public ApplyRevisionOptions(List<RevisionInfo> changes, RevisionAction revisionAction)
```


Instantieert een nieuw ApplyRevisionOptions-object met de opgegeven lijst van revisies en een gemeenschappelijke revisie‑actie.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | wijzigingen | java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> | De lijst met revisies die moeten worden toegepast |
|
|  | revisionAction | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | De gemeenschappelijke revisie‑actie die op alle revisies moet worden toegepast |
|

### ApplyRevisionOptions(RevisionAction revisionAction) {#ApplyRevisionOptions-com.groupdocs.comparison.words.revision.RevisionAction-}
```
public ApplyRevisionOptions(RevisionAction revisionAction)
```


Instantieert een nieuw ApplyRevisionOptions-object met een gemeenschappelijke revisie‑actie.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | revisionAction | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | De gemeenschappelijke revisie‑actie die op alle revisies moet worden toegepast |
|

### getChanges() {#getChanges--}
```
public List<RevisionInfo> getChanges()
```


Haalt de lijst met revisies op die moeten worden toegepast.


**Returns:**
java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> - de lijst met revisies

### setChanges(List<RevisionInfo> changes) {#setChanges-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--}
```
public void setChanges(List<RevisionInfo> changes)
```


Stelt de lijst met revisies in die moeten worden toegepast.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | wijzigingen | java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> | De lijst met revisies |
|

### getCommonHandler() {#getCommonHandler--}
```
public RevisionAction getCommonHandler()
```


Haalt de gemeenschappelijke revisie‑actie op die op alle revisies moet worden toegepast.


**Returns:**
[RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) - the common revision action

### setCommonHandler(RevisionAction commonHandler) {#setCommonHandler-com.groupdocs.comparison.words.revision.RevisionAction-}
```
public void setCommonHandler(RevisionAction commonHandler)
```


Stelt de gemeenschappelijke revisie‑actie in die op alle revisies moet worden toegepast.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | commonHandler | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | De gemeenschappelijke revisie‑actie |
|

