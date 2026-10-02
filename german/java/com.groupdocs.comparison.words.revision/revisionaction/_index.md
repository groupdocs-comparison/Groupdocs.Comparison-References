---
title: "RevisionAction"
second_title: "GroupDocs.Comparison für Java API-Referenz"
description: "Stellt eine Aktion dar, die auf eine Revision angewendet werden kann."
type: docs
weight: 13
url: /de/java/com.groupdocs.comparison.words.revision/revisionaction/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum RevisionAction extends Enum<RevisionAction>
```

Stellt eine Aktion dar, die auf eine Revision angewendet werden kann.


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


## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [NONE](#NONE) | Gibt an, dass keine Aktion durchgeführt werden soll. |
|
|  | [ACCEPT](#ACCEPT) | Gibt an, dass die Revision angezeigt wird, wenn sie vom Typ INSERTION ist, oder entfernt wird, wenn sie vom Typ DELETION ist. |
|
|  | [REJECT](#REJECT) | Gibt an, dass die Revision entfernt wird, wenn sie vom Typ INSERTION ist, oder angezeigt wird, wenn sie vom Typ DELETION ist. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### NONE {#NONE}
```
public static final RevisionAction NONE
```


Gibt an, dass keine Aktion durchgeführt werden soll.


### ACCEPT {#ACCEPT}
```
public static final RevisionAction ACCEPT
```


Gibt an, dass die Revision angezeigt wird, wenn sie vom Typ INSERTION ist, oder entfernt wird, wenn sie vom Typ DELETION ist.


### REJECT {#REJECT}
```
public static final RevisionAction REJECT
```


Gibt an, dass die Revision entfernt wird, wenn sie vom Typ INSERTION ist, oder angezeigt wird, wenn sie vom Typ DELETION ist.


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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String |  |

**Returns:**
[RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction)
