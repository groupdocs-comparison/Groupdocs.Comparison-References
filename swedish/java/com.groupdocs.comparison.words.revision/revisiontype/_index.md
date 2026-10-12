---
title: "RevisionType"
second_title: "GroupDocs.Comparison för Java API-referens"
description: "Representerar typerna av revisioner i ett dokument."
type: docs
weight: 14
url: /sv/java/com.groupdocs.comparison.words.revision/revisiontype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum RevisionType extends Enum<RevisionType>
```

Representerar typerna av revisioner i ett dokument.


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
|  | [INSERTION](#INSERTION) | Representerar en typ när nytt innehåll har infogats i dokumentet. |
|
|  | [DELETION](#DELETION) | Representerar en typ när innehåll har tagits bort från dokumentet. |
|
|  | [FORMAT_CHANGE](#FORMAT-CHANGE) | Representerar en typ när en formateringsändring har tillämpats på föräldraknuten. |
|
|  | [STYLE_DEFINITION_CHANGE](#STYLE-DEFINITION-CHANGE) | Representerar en typ när en formateringsändring har tillämpats på förälderstilen. |
|
|  | [MOVING](#MOVING) | Representerar en typ när innehåll har flyttats i dokumentet. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromInt(int toIntValue)](#fromInt-int-) | Skapar en ny konstant av enum RevisionType med det angivna numeriska värdet. |
|
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Analyserar strängrepresentationen av RevisionType för att få enum‑konstanten. |
|
|  | [toInt()](#toInt--) | Numerisk representation av RevisionType. |
|
|  | [toString()](#toString--) | Strängrepresentation av RevisionType. |
|
### INSERTION {#INSERTION}
```
public static final RevisionType INSERTION
```


Representerar en typ när nytt innehåll har infogats i dokumentet.


### DELETION {#DELETION}
```
public static final RevisionType DELETION
```


Representerar en typ när innehåll har tagits bort från dokumentet.


### FORMAT_CHANGE {#FORMAT-CHANGE}
```
public static final RevisionType FORMAT_CHANGE
```


Representerar en typ när en formateringsändring har tillämpats på föräldraknuten.


### STYLE_DEFINITION_CHANGE {#STYLE-DEFINITION-CHANGE}
```
public static final RevisionType STYLE_DEFINITION_CHANGE
```


Representerar en typ när en formateringsändring har tillämpats på förälderstilen.


### MOVING {#MOVING}
```
public static final RevisionType MOVING
```


Representerar en typ när innehåll har flyttats i dokumentet.


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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String |  |

**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype)
### fromInt(int toIntValue) {#fromInt-int-}
```
public static RevisionType fromInt(int toIntValue)
```


Skapar en ny konstant av enum RevisionType med det angivna numeriska värdet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | toIntValue | int | Den numeriska representationen av RevisionType |
|

**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) - RevisionType enum constant associated with numeric value

### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static RevisionType fromString(String toStringValue)
```


Analyserar strängrepresentationen av RevisionType för att få enum‑konstanten.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | toStringValue | java.lang.String | Strängrepresentationen av RevisionType |
|

**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) - RevisionType enum constant associated with input string

### toInt() {#toInt--}
```
public int toInt()
```


Numerisk representation av RevisionType.


**Returns:**
int - numeriskt värde av enum‑konstant

### toString() {#toString--}
```
public String toString()
```


Strängrepresentation av RevisionType.


**Returns:**
java.lang.String - strängvärde av enum‑konstant

