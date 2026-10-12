---
title: "ApplyRevisionOptions"
second_title: "GroupDocs.Comparison för Java API-referens"
description: "Klassen ApplyRevisionOptions låter dig uppdatera statusen för revisioner innan de tillämpas på det slutgiltiga dokumentet."
type: docs
weight: 10
url: /sv/java/com.groupdocs.comparison.words.revision/applyrevisionoptions/
---
**Inheritance:**
java.lang.Object
```
public class ApplyRevisionOptions
```

Klassen ApplyRevisionOptions låter dig uppdatera statusen för revisioner innan de tillämpas på det slutgiltiga dokumentet.


Den tillhandahåller olika konstruktorer och egenskaper för att anpassa processen för att tillämpa revisioner.


Exempel på användning:

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


## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [ApplyRevisionOptions()](#ApplyRevisionOptions--) | Initierar en ny instans av klassen ApplyRevisionOptions. |
|
|  | [ApplyRevisionOptions(List<RevisionInfo> changes)](#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--) | Skapar ett nytt ApplyRevisionOptions-objekt med den angivna listan av revisioner. |
|
|  | [ApplyRevisionOptions(List<RevisionInfo> changes, RevisionAction revisionAction)](#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--com.groupdocs.comparison.words.revision.RevisionAction-) | Skapar en ny ApplyRevisionOptions-objekt med den angivna listan av revisioner och en gemensam revisionsåtgärd. |
|
|  | [ApplyRevisionOptions(RevisionAction revisionAction)](#ApplyRevisionOptions-com.groupdocs.comparison.words.revision.RevisionAction-) | Skapar en ny ApplyRevisionOptions-objekt med en gemensam revisionsåtgärd. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getChanges()](#getChanges--) | Hämtar listan över revisioner som ska tillämpas. |
|
|  | [setChanges(List<RevisionInfo> changes)](#setChanges-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--) | Ställer in listan över revisioner som ska tillämpas. |
|
|  | [getCommonHandler()](#getCommonHandler--) | Hämtar den gemensamma revisionsåtgärden som ska tillämpas på alla revisioner. |
|
|  | [setCommonHandler(RevisionAction commonHandler)](#setCommonHandler-com.groupdocs.comparison.words.revision.RevisionAction-) | Ställer in den gemensamma revisionsåtgärden som ska tillämpas på alla revisioner. |
|
### ApplyRevisionOptions() {#ApplyRevisionOptions--}
```
public ApplyRevisionOptions()
```


Initierar en ny instans av klassen ApplyRevisionOptions.


### ApplyRevisionOptions(List<RevisionInfo> changes) {#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--}
```
public ApplyRevisionOptions(List<RevisionInfo> changes)
```


Skapar ett nytt ApplyRevisionOptions-objekt med den angivna listan av revisioner.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | ändringar | java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> | Listan över revisioner som ska tillämpas |
|

### ApplyRevisionOptions(List<RevisionInfo> changes, RevisionAction revisionAction) {#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--com.groupdocs.comparison.words.revision.RevisionAction-}
```
public ApplyRevisionOptions(List<RevisionInfo> changes, RevisionAction revisionAction)
```


Skapar en ny ApplyRevisionOptions-objekt med den angivna listan av revisioner och en gemensam revisionsåtgärd.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | ändringar | java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> | Listan över revisioner som ska tillämpas |
|
|  | revisionAction | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | Den gemensamma revisionsåtgärden som ska tillämpas på alla revisioner |
|

### ApplyRevisionOptions(RevisionAction revisionAction) {#ApplyRevisionOptions-com.groupdocs.comparison.words.revision.RevisionAction-}
```
public ApplyRevisionOptions(RevisionAction revisionAction)
```


Skapar en ny ApplyRevisionOptions-objekt med en gemensam revisionsåtgärd.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | revisionAction | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | Den gemensamma revisionsåtgärden som ska tillämpas på alla revisioner |
|

### getChanges() {#getChanges--}
```
public List<RevisionInfo> getChanges()
```


Hämtar listan över revisioner som ska tillämpas.


**Returns:**
java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> - listan över revisioner

### setChanges(List<RevisionInfo> changes) {#setChanges-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--}
```
public void setChanges(List<RevisionInfo> changes)
```


Ställer in listan över revisioner som ska tillämpas.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | ändringar | java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> | Listan över revisioner |
|

### getCommonHandler() {#getCommonHandler--}
```
public RevisionAction getCommonHandler()
```


Hämtar den gemensamma revisionsåtgärden som ska tillämpas på alla revisioner.


**Returns:**
[RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) - the common revision action

### setCommonHandler(RevisionAction commonHandler) {#setCommonHandler-com.groupdocs.comparison.words.revision.RevisionAction-}
```
public void setCommonHandler(RevisionAction commonHandler)
```


Ställer in den gemensamma revisionsåtgärden som ska tillämpas på alla revisioner.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | commonHandler | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | Den gemensamma revisionsåtgärden |
|

