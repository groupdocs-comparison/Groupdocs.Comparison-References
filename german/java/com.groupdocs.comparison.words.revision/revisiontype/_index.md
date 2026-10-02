---
title: "RevisionType"
second_title: "GroupDocs.Comparison für Java API-Referenz"
description: "Stellt die Arten von Revisionen in einem Dokument dar."
type: docs
weight: 14
url: /de/java/com.groupdocs.comparison.words.revision/revisiontype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum RevisionType extends Enum<RevisionType>
```

Stellt die Arten von Revisionen in einem Dokument dar.


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
|  | [INSERTION](#INSERTION) | Stellt einen Typ dar, wenn neuer Inhalt im Dokument eingefügt wurde. |
|
|  | [DELETION](#DELETION) | Stellt einen Typ dar, wenn Inhalt aus dem Dokument entfernt wurde. |
|
|  | [FORMAT_CHANGE](#FORMAT-CHANGE) | Stellt einen Typ dar, wenn eine Formatierungsänderung am übergeordneten Knoten angewendet wurde. |
|
|  | [STYLE_DEFINITION_CHANGE](#STYLE-DEFINITION-CHANGE) | Stellt einen Typ dar, wenn eine Formatierungsänderung am übergeordneten Stil angewendet wurde. |
|
|  | [MOVING](#MOVING) | Stellt einen Typ dar, wenn Inhalt im Dokument verschoben wurde. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromInt(int toIntValue)](#fromInt-int-) | Erstellt eine neue Konstante des Enums RevisionType mit dem bereitgestellten numerischen Wert. |
|
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Parst die String-Darstellung von RevisionType, um die Enum-Konstante zu erhalten. |
|
|  | [toInt()](#toInt--) | Numerische Darstellung von RevisionType. |
|
|  | [toString()](#toString--) | String-Darstellung von RevisionType. |
|
### INSERTION {#INSERTION}
```
public static final RevisionType INSERTION
```


Stellt einen Typ dar, wenn neuer Inhalt im Dokument eingefügt wurde.


### DELETION {#DELETION}
```
public static final RevisionType DELETION
```


Stellt einen Typ dar, wenn Inhalt aus dem Dokument entfernt wurde.


### FORMAT_CHANGE {#FORMAT-CHANGE}
```
public static final RevisionType FORMAT_CHANGE
```


Stellt einen Typ dar, wenn eine Formatierungsänderung am übergeordneten Knoten angewendet wurde.


### STYLE_DEFINITION_CHANGE {#STYLE-DEFINITION-CHANGE}
```
public static final RevisionType STYLE_DEFINITION_CHANGE
```


Stellt einen Typ dar, wenn eine Formatierungsänderung am übergeordneten Stil angewendet wurde.


### MOVING {#MOVING}
```
public static final RevisionType MOVING
```


Stellt einen Typ dar, wenn Inhalt im Dokument verschoben wurde.


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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String |  |

**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype)
### fromInt(int toIntValue) {#fromInt-int-}
```
public static RevisionType fromInt(int toIntValue)
```


Erstellt eine neue Konstante des Enums RevisionType mit dem bereitgestellten numerischen Wert.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | toIntValue | int | Die numerische Darstellung von RevisionType |
|

**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) - RevisionType enum constant associated with numeric value

### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static RevisionType fromString(String toStringValue)
```


Parst die String-Darstellung von RevisionType, um die Enum-Konstante zu erhalten.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | toStringValue | java.lang.String | Die String-Darstellung von RevisionType |
|

**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) - RevisionType enum constant associated with input string

### toInt() {#toInt--}
```
public int toInt()
```


Numerische Darstellung von RevisionType.


**Returns:**
int - numerischer Wert der Enum-Konstante

### toString() {#toString--}
```
public String toString()
```


String-Darstellung von RevisionType.


**Returns:**
java.lang.String - String-Wert der Enum-Konstante

