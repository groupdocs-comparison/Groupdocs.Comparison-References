---
title: "RevisionAction"
second_title: "GroupDocs.Comparison voor Java API-referentie"
description: "Stelt een actie voor die op een revisie kan worden toegepast."
type: docs
weight: 13
url: /nl/java/com.groupdocs.comparison.words.revision/revisionaction/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum RevisionAction extends Enum<RevisionAction>
```

Stelt een actie voor die op een revisie kan worden toegepast.


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


## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [NONE](#NONE) | Geeft aan dat er geen actie ondernomen moet worden. |
|
|  | [ACCEPT](#ACCEPT) | Geeft aan dat de revisie wordt weergegeven als deze van het type INSERTION is, of wordt verwijderd als het type DELETION is. |
|
|  | [REJECT](#REJECT) | Geeft aan dat de revisie wordt verwijderd als deze van het type INSERTION is, of wordt weergegeven als het type DELETION is. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### NONE {#NONE}
```
public static final RevisionAction NONE
```


Geeft aan dat er geen actie ondernomen moet worden.


### ACCEPT {#ACCEPT}
```
public static final RevisionAction ACCEPT
```


Geeft aan dat de revisie wordt weergegeven als deze van het type INSERTION is, of wordt verwijderd als het type DELETION is.


### REJECT {#REJECT}
```
public static final RevisionAction REJECT
```


Geeft aan dat de revisie wordt verwijderd als deze van het type INSERTION is, of wordt weergegeven als het type DELETION is.


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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String |  |

**Returns:**
[RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction)
