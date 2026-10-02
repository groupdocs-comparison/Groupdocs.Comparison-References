---
title: "RevisionInfo"
second_title: "GroupDocs.Comparison för Java API-referens"
description: "Representerar en revision i dokumentet."
type: docs
weight: 12
url: /sv/java/com.groupdocs.comparison.words.revision/revisioninfo/
---
**Inheritance:**
java.lang.Object
```
public class RevisionInfo
```

Representerar en revision i dokumentet.


En revision kapslar in information om revisionsändringen som gjorts i dokumentet.
Denna klass tillhandahåller metoder för att hämta information om revisionen, såsom dess typ,
innehåll, författare och så vidare.

Exempel på användning:

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


## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [RevisionInfo()](#RevisionInfo--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getAction()](#getAction--) | Hämtar åtgärden som är associerad med revisionen (acceptera eller avvisa). |
|
|  | [setAction(RevisionAction value)](#setAction-com.groupdocs.comparison.words.revision.RevisionAction-) | Ställer in värdet som är associerat med revisionen (acceptera eller avvisa). |
|
|  | [getText()](#getText--) | Hämtar textinnehållet i revisionen. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Ställer in värdeinnehållet i revisionen. |
|
|  | [getAuthor()](#getAuthor--) | Hämtar författaren till revisionen. |
|
|  | [setAuthor(String value)](#setAuthor-java.lang.String-) | Ställer in värdet för revisionen. |
|
|  | [getType()](#getType--) | Hämtar typen av revisionen, beroende på typen ändras logiken för Åtgärd (acceptera eller avvisa). |
|
|  | [setType(RevisionType value)](#setType-com.groupdocs.comparison.words.revision.RevisionType-) | Ställer in värdet för revisionen, beroende på värdet ändras logiken för Åtgärd (acceptera eller avvisa). |
|
### RevisionInfo() {#RevisionInfo--}
```
public RevisionInfo()
```


### getAction() {#getAction--}
```
public RevisionAction getAction()
```


Hämtar åtgärden som är associerad med revisionen (acceptera eller avvisa). Detta fält låter dig påverka visningen av revisionen.


**Returns:**
[RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) - the action associated with the revision.

### setAction(RevisionAction value) {#setAction-com.groupdocs.comparison.words.revision.RevisionAction-}
```
public void setAction(RevisionAction value)
```


Ställer in värdet som är associerat med revisionen (acceptera eller avvisa). Detta fält låter dig påverka visningen av revisionen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | Värdet som är associerat med revisionen. |
|

### getText() {#getText--}
```
public String getText()
```


Hämtar textinnehållet i revisionen.


**Returns:**
java.lang.String - textinnehållet i revisionen.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Ställer in värdeinnehållet i revisionen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | java.lang.String | Värdeinnehållet i revisionen. |
|

### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Hämtar författaren till revisionen.


**Returns:**
java.lang.String - författaren till revisionen.

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public void setAuthor(String value)
```


Ställer in värdet för revisionen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | java.lang.String | Värdet för revisionen. |
|

### getType() {#getType--}
```
public RevisionType getType()
```


Hämtar typen av revisionen, beroende på typen ändras logiken för Åtgärd (acceptera eller avvisa).


**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) - the type of the revision.

### setType(RevisionType value) {#setType-com.groupdocs.comparison.words.revision.RevisionType-}
```
public void setType(RevisionType value)
```


Ställer in värdet för revisionen, beroende på värdet ändras logiken för Åtgärd (acceptera eller avvisa).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) | Värdet för revisionen. |
|

