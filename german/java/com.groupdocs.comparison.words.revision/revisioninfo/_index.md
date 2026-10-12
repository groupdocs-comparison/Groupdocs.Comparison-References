---
title: "RevisionInfo"
second_title: "GroupDocs.Comparison für Java API-Referenz"
description: "Stellt eine Revision im Dokument dar."
type: docs
weight: 12
url: /de/java/com.groupdocs.comparison.words.revision/revisioninfo/
---
**Inheritance:**
java.lang.Object
```
public class RevisionInfo
```

Stellt eine Revision im Dokument dar.


Eine Revision kapselt Informationen über die am Dokument vorgenommenen Änderungen.
Diese Klasse stellt Methoden bereit, um Informationen über die Revision abzurufen, wie z. B. ihren Typ,
Inhalt, Autor und so weiter.

Beispielverwendung:

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


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [RevisionInfo()](#RevisionInfo--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getAction()](#getAction--) | Ermittelt die mit der Revision verbundene Aktion (akzeptieren oder ablehnen). |
|
|  | [setAction(RevisionAction value)](#setAction-com.groupdocs.comparison.words.revision.RevisionAction-) | Setzt den mit der Revision verbundenen Wert (akzeptieren oder ablehnen). |
|
|  | [getText()](#getText--) | Liest den Textinhalt der Revision. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Setzt den Wert des Inhalts der Revision. |
|
|  | [getAuthor()](#getAuthor--) | Liest den Autor der Revision. |
|
|  | [setAuthor(String value)](#setAuthor-java.lang.String-) | Setzt den Wert der Revision. |
|
|  | [getType()](#getType--) | Ermittelt den Typ der Revision, abhängig vom Typ ändert sich die Logik der Aktion (akzeptieren oder ablehnen). |
|
|  | [setType(RevisionType value)](#setType-com.groupdocs.comparison.words.revision.RevisionType-) | Setzt den Wert der Revision, abhängig vom Wert ändert sich die Logik der Aktion (akzeptieren oder ablehnen). |
|
### RevisionInfo() {#RevisionInfo--}
```
public RevisionInfo()
```


### getAction() {#getAction--}
```
public RevisionAction getAction()
```


Liest die mit der Revision verbundene Aktion (akzeptieren oder ablehnen). Dieses Feld ermöglicht es Ihnen, die Anzeige der Revision zu beeinflussen.


**Returns:**
[RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) - the action associated with the revision.

### setAction(RevisionAction value) {#setAction-com.groupdocs.comparison.words.revision.RevisionAction-}
```
public void setAction(RevisionAction value)
```


Setzt den mit der Revision verbundenen Wert (akzeptieren oder ablehnen). Dieses Feld ermöglicht es Ihnen, die Anzeige der Revision zu beeinflussen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | Der Wert, der mit der Revision verbunden ist. |
|

### getText() {#getText--}
```
public String getText()
```


Liest den Textinhalt der Revision.


**Returns:**
java.lang.String – der Textinhalt der Revision.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Setzt den Wert des Inhalts der Revision.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | java.lang.String | Der Wert des Inhalts der Revision. |
|

### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Liest den Autor der Revision.


**Returns:**
java.lang.String – der Autor der Revision.

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public void setAuthor(String value)
```


Setzt den Wert der Revision.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | java.lang.String | Der Wert der Revision. |
|

### getType() {#getType--}
```
public RevisionType getType()
```


Ermittelt den Typ der Revision, abhängig vom Typ ändert sich die Logik der Aktion (akzeptieren oder ablehnen).


**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) - the type of the revision.

### setType(RevisionType value) {#setType-com.groupdocs.comparison.words.revision.RevisionType-}
```
public void setType(RevisionType value)
```


Setzt den Wert der Revision, abhängig vom Wert ändert sich die Logik der Aktion (akzeptieren oder ablehnen).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) | Der Wert der Revision. |
|

