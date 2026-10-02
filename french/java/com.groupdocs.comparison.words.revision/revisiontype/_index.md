---
title: "RevisionType"
second_title: "Référence API de GroupDocs.Comparison for Java"
description: "Représente les types de révisions dans un document."
type: docs
weight: 14
url: /fr/java/com.groupdocs.comparison.words.revision/revisiontype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum RevisionType extends Enum<RevisionType>
```

Représente les types de révisions dans un document.


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
|  | [INSERTION](#INSERTION) | Représente un type lorsqu'un nouveau contenu a été inséré dans le document. |
|
|  | [DELETION](#DELETION) | Représente un type lorsque le contenu a été supprimé du document. |
|
|  | [FORMAT_CHANGE](#FORMAT-CHANGE) | Représente un type lorsqu'un changement de formatage a été appliqué au nœud parent. |
|
|  | [STYLE_DEFINITION_CHANGE](#STYLE-DEFINITION-CHANGE) | Représente un type lorsqu'un changement de formatage a été appliqué au style parent. |
|
|  | [MOVING](#MOVING) | Représente un type lorsque le contenu a été déplacé dans le document. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromInt(int toIntValue)](#fromInt-int-) | Crée une nouvelle constante de l'énumération RevisionType en utilisant la valeur numérique fournie. |
|
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Analyse la représentation sous forme de chaîne de RevisionType pour obtenir la constante d'énumération. |
|
|  | [toInt()](#toInt--) | Représentation numérique de RevisionType. |
|
|  | [toString()](#toString--) | Représentation sous forme de chaîne de RevisionType. |
|
### INSERTION {#INSERTION}
```
public static final RevisionType INSERTION
```


Représente un type lorsqu'un nouveau contenu a été inséré dans le document.


### DELETION {#DELETION}
```
public static final RevisionType DELETION
```


Représente un type lorsque le contenu a été supprimé du document.


### FORMAT_CHANGE {#FORMAT-CHANGE}
```
public static final RevisionType FORMAT_CHANGE
```


Représente un type lorsqu'un changement de formatage a été appliqué au nœud parent.


### STYLE_DEFINITION_CHANGE {#STYLE-DEFINITION-CHANGE}
```
public static final RevisionType STYLE_DEFINITION_CHANGE
```


Représente un type lorsqu'un changement de formatage a été appliqué au style parent.


### MOVING {#MOVING}
```
public static final RevisionType MOVING
```


Représente un type lorsque le contenu a été déplacé dans le document.


### values() {#values--}
```
public static RevisionType[] values()
```




**Returns:**
com.groupdocs.comparison.words.revision.RevisionType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static RevisionType valueOf(String name)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String |  |

**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype)
### fromInt(int toIntValue) {#fromInt-int-}
```
public static RevisionType fromInt(int toIntValue)
```


Crée une nouvelle constante de l'énumération RevisionType en utilisant la valeur numérique fournie.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | toIntValue | int | La représentation numérique de RevisionType |
|

**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) - RevisionType enum constant associated with numeric value

### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static RevisionType fromString(String toStringValue)
```


Analyse la représentation sous forme de chaîne de RevisionType pour obtenir la constante d'énumération.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | toStringValue | java.lang.String | La représentation sous forme de chaîne de RevisionType |
|

**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) - RevisionType enum constant associated with input string

### toInt() {#toInt--}
```
public int toInt()
```


Représentation numérique de RevisionType.


**Returns:**
int - valeur numérique de la constante d'énumération

### toString() {#toString--}
```
public String toString()
```


Représentation sous forme de chaîne de RevisionType.


**Returns:**
java.lang.String - valeur sous forme de chaîne de la constante d'énumération

