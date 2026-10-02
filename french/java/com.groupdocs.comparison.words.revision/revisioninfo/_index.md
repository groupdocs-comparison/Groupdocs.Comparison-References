---
title: "RevisionInfo"
second_title: "Référence API de GroupDocs.Comparison for Java"
description: "Représente une révision dans le document."
type: docs
weight: 12
url: /fr/java/com.groupdocs.comparison.words.revision/revisioninfo/
---
**Inheritance:**
java.lang.Object
```
public class RevisionInfo
```

Représente une révision dans le document.


Une révision encapsule les informations sur la modification de révision apportée au document.
Cette classe fournit des méthodes pour récupérer les informations sur la révision, telles que son type,
contenu, auteur, etc.

Exemple d'utilisation :

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


## Constructeurs

| Constructeur | Description |
| --- | --- |
| [RevisionInfo()](#RevisionInfo--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getAction()](#getAction--) | Obtient l'action associée à la révision (accepter ou rejeter). |
|
|  | [setAction(RevisionAction value)](#setAction-com.groupdocs.comparison.words.revision.RevisionAction-) | Définit la valeur associée à la révision (accepter ou rejeter). |
|
|  | [getText()](#getText--) | Obtient le contenu texte de la révision. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Définit le contenu de la valeur de la révision. |
|
|  | [getAuthor()](#getAuthor--) | Obtient l'auteur de la révision. |
|
|  | [setAuthor(String value)](#setAuthor-java.lang.String-) | Définit la valeur de la révision. |
|
|  | [getType()](#getType--) | Obtient le type de la révision, selon le type la logique d'Action (accepter ou rejeter) change. |
|
|  | [setType(RevisionType value)](#setType-com.groupdocs.comparison.words.revision.RevisionType-) | Définit la valeur de la révision, selon la valeur la logique d'Action (accepter ou rejeter) change. |
|
### RevisionInfo() {#RevisionInfo--}
```
public RevisionInfo()
```


### getAction() {#getAction--}
```
public RevisionAction getAction()
```


Obtient l'action associée à la révision (accepter ou rejeter). Ce champ vous permet d'influencer l'affichage de la révision.


**Returns:**
[RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) - the action associated with the revision.

### setAction(RevisionAction value) {#setAction-com.groupdocs.comparison.words.revision.RevisionAction-}
```
public void setAction(RevisionAction value)
```


Définit la valeur associée à la révision (accepter ou rejeter). Ce champ vous permet d'influencer l'affichage de la révision.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | La valeur associée à la révision. |
|

### getText() {#getText--}
```
public String getText()
```


Obtient le contenu texte de la révision.


**Returns:**
java.lang.String - le contenu texte de la révision.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Définit le contenu de la valeur de la révision.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.lang.String | Le contenu de la valeur de la révision. |
|

### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Obtient l'auteur de la révision.


**Returns:**
java.lang.String - l'auteur de la révision.

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public void setAuthor(String value)
```


Définit la valeur de la révision.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.lang.String | La valeur de la révision. |
|

### getType() {#getType--}
```
public RevisionType getType()
```


Obtient le type de la révision, selon le type la logique d'Action (accepter ou rejeter) change.


**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) - the type of the revision.

### setType(RevisionType value) {#setType-com.groupdocs.comparison.words.revision.RevisionType-}
```
public void setType(RevisionType value)
```


Définit la valeur de la révision, selon la valeur la logique d'Action (accepter ou rejeter) change.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) | La valeur de la révision. |
|

