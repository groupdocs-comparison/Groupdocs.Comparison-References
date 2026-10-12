---
title: "RevisionAction"
second_title: "GroupDocs.Comparison för Java API-referens"
description: "Representerar en åtgärd som kan tillämpas på en revision."
type: docs
weight: 13
url: /sv/java/com.groupdocs.comparison.words.revision/revisionaction/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum RevisionAction extends Enum<RevisionAction>
```

Representerar en åtgärd som kan tillämpas på en revision.


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


## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [NONE](#NONE) | Indikerar att ingen åtgärd ska vidtas. |
|
|  | [ACCEPT](#ACCEPT) | Indikerar att revisionen kommer att visas om den är av typen INSERTION, eller att den tas bort om typen är DELETION. |
|
|  | [REJECT](#REJECT) | Indikerar att revisionen tas bort om den är av typen INSERTION, eller att den visas om typen är DELETION. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### NONE {#NONE}
```
public static final RevisionAction NONE
```


Indikerar att ingen åtgärd ska vidtas.


### ACCEPT {#ACCEPT}
```
public static final RevisionAction ACCEPT
```


Indikerar att revisionen kommer att visas om den är av typen INSERTION, eller att den tas bort om typen är DELETION.


### REJECT {#REJECT}
```
public static final RevisionAction REJECT
```


Indikerar att revisionen tas bort om den är av typen INSERTION, eller att den visas om typen är DELETION.


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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String |  |

**Returns:**
[RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction)
