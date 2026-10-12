---
title: "RevisionType"
second_title: "GroupDocs.Comparison voor Java API-referentie"
description: "Stelt de typen revisies in een document voor."
type: docs
weight: 14
url: /nl/java/com.groupdocs.comparison.words.revision/revisiontype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum RevisionType extends Enum<RevisionType>
```

Stelt de typen revisies in een document voor.


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
|  | [INSERTION](#INSERTION) | Stelt een type voor wanneer nieuwe inhoud in het document is ingevoegd. |
|
|  | [DELETION](#DELETION) | Stelt een type voor wanneer inhoud uit het document is verwijderd. |
|
|  | [FORMAT_CHANGE](#FORMAT-CHANGE) | Stelt een type voor wanneer een wijziging van opmaak is toegepast op het bovenliggende knooppunt. |
|
|  | [STYLE_DEFINITION_CHANGE](#STYLE-DEFINITION-CHANGE) | Stelt een type voor wanneer een wijziging van opmaak is toegepast op de bovenliggende stijl. |
|
|  | [MOVING](#MOVING) | Stelt een type voor wanneer inhoud in het document is verplaatst. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromInt(int toIntValue)](#fromInt-int-) | Maakt een nieuwe constante van enum RevisionType met de opgegeven numerieke waarde. |
|
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Parseert de tekenreeksrepresentatie van RevisionType om de enum-constante te verkrijgen. |
|
|  | [toInt()](#toInt--) | Numerieke representatie van RevisionType. |
|
|  | [toString()](#toString--) | Tekenreeksrepresentatie van RevisionType. |
|
### INSERTION {#INSERTION}
```
public static final RevisionType INSERTION
```


Stelt een type voor wanneer nieuwe inhoud in het document is ingevoegd.


### DELETION {#DELETION}
```
public static final RevisionType DELETION
```


Stelt een type voor wanneer inhoud uit het document is verwijderd.


### FORMAT_CHANGE {#FORMAT-CHANGE}
```
public static final RevisionType FORMAT_CHANGE
```


Stelt een type voor wanneer een wijziging van opmaak is toegepast op het bovenliggende knooppunt.


### STYLE_DEFINITION_CHANGE {#STYLE-DEFINITION-CHANGE}
```
public static final RevisionType STYLE_DEFINITION_CHANGE
```


Stelt een type voor wanneer een wijziging van opmaak is toegepast op de bovenliggende stijl.


### MOVING {#MOVING}
```
public static final RevisionType MOVING
```


Stelt een type voor wanneer inhoud in het document is verplaatst.


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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String |  |

**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype)
### fromInt(int toIntValue) {#fromInt-int-}
```
public static RevisionType fromInt(int toIntValue)
```


Maakt een nieuwe constante van enum RevisionType met de opgegeven numerieke waarde.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | toIntValue | int | De numerieke representatie van RevisionType |
|

**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) - RevisionType enum constant associated with numeric value

### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static RevisionType fromString(String toStringValue)
```


Parseert de tekenreeksrepresentatie van RevisionType om de enum-constante te verkrijgen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | toStringValue | java.lang.String | De tekenreeksrepresentatie van RevisionType |
|

**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) - RevisionType enum constant associated with input string

### toInt() {#toInt--}
```
public int toInt()
```


Numerieke representatie van RevisionType.


**Returns:**
int - numerieke waarde van enum-constante

### toString() {#toString--}
```
public String toString()
```


Tekenreeksrepresentatie van RevisionType.


**Returns:**
java.lang.String - tekenreekswaarde van enum-constante

