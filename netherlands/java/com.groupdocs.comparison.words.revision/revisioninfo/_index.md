---
title: "RevisionInfo"
second_title: "GroupDocs.Comparison voor Java API-referentie"
description: "Stelt een revisie in het document voor."
type: docs
weight: 12
url: /nl/java/com.groupdocs.comparison.words.revision/revisioninfo/
---
**Inheritance:**
java.lang.Object
```
public class RevisionInfo
```

Stelt een revisie in het document voor.


Een revisie bevat informatie over de revisieverandering die in het document is aangebracht.
Deze klasse biedt methoden om informatie over de revisie op te halen, zoals het type,
inhoud, auteur, enzovoort.

Voorbeeldgebruik:

````

 try (RevisionHandler revisionHandler = new RevisionHandler(sourceFile)) {
     List revisionList = revisionHandler.getRevisions();

     for (RevisionInfo revisionInfo : revisionList) {
         System.out.println("Revision Type: " + revisionInfo.getType());
         System.out.println("Text: " + revisionInfo.getText());
         System.out.println("Author: " + revisionInfo.getAuthor());
     }
 }
 
````


## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [RevisionInfo()](#RevisionInfo--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getAction()](#getAction--) | Haalt de actie op die aan de revisie is gekoppeld (accepteren of afwijzen). |
|
|  | [setAction(RevisionAction value)](#setAction-com.groupdocs.comparison.words.revision.RevisionAction-) | Stelt de waarde in die aan de revisie is gekoppeld (accepteren of afwijzen). |
|
|  | [getText()](#getText--) | Haalt de tekstinhoud van de revisie op. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Stelt de inhoud van de waarde van de revisie in. |
|
|  | [getAuthor()](#getAuthor--) | Haalt de auteur van de revisie op. |
|
|  | [setAuthor(String value)](#setAuthor-java.lang.String-) | Stelt de waarde van de revisie in. |
|
|  | [getType()](#getType--) | Haalt het type van de revisie op; afhankelijk van het type verandert de logica van de Actie (accepteren of afwijzen). |
|
|  | [setType(RevisionType value)](#setType-com.groupdocs.comparison.words.revision.RevisionType-) | Stelt de waarde van de revisie in; afhankelijk van de waarde verandert de logica van de Actie (accepteren of afwijzen). |
|
### RevisionInfo() {#RevisionInfo--}
```
public RevisionInfo()
```


### getAction() {#getAction--}
```
public RevisionAction getAction()
```


Haalt de actie op die aan de revisie is gekoppeld (accepteren of afwijzen). Dit veld stelt u in staat de weergave van de revisie te beïnvloeden.


**Returns:**
[RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) - the action associated with the revision.

### setAction(RevisionAction value) {#setAction-com.groupdocs.comparison.words.revision.RevisionAction-}
```
public void setAction(RevisionAction value)
```


Stelt de waarde in die aan de revisie is gekoppeld (accepteren of afwijzen). Dit veld stelt u in staat de weergave van de revisie te beïnvloeden.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | De waarde die aan de revisie is gekoppeld. |
|

### getText() {#getText--}
```
public String getText()
```


Haalt de tekstinhoud van de revisie op.


**Returns:**
java.lang.String - de tekstinhoud van de revisie.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Stelt de inhoud van de waarde van de revisie in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.lang.String | De inhoud van de waarde van de revisie. |
|

### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Haalt de auteur van de revisie op.


**Returns:**
java.lang.String - de auteur van de revisie.

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public void setAuthor(String value)
```


Stelt de waarde van de revisie in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.lang.String | De waarde van de revisie. |
|

### getType() {#getType--}
```
public RevisionType getType()
```


Haalt het type van de revisie op; afhankelijk van het type verandert de logica van de Actie (accepteren of afwijzen).


**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) - the type of the revision.

### setType(RevisionType value) {#setType-com.groupdocs.comparison.words.revision.RevisionType-}
```
public void setType(RevisionType value)
```


Stelt de waarde van de revisie in; afhankelijk van de waarde verandert de logica van de Actie (accepteren of afwijzen).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) | De waarde van de revisie. |
|

