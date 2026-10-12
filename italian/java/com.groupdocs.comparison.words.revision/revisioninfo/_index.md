---
title: "RevisionInfo"
second_title: "Riferimento API di GroupDocs.Comparison per Java"
description: "Rappresenta una revisione nel documento."
type: docs
weight: 12
url: /it/java/com.groupdocs.comparison.words.revision/revisioninfo/
---
**Inheritance:**
java.lang.Object
```
public class RevisionInfo
```

Rappresenta una revisione nel documento.


Una revisione incapsula informazioni sulla modifica della revisione apportata al documento.
Questa classe fornisce metodi per recuperare informazioni sulla revisione, come il suo tipo,
contenuto, autore e così via.

Esempio di utilizzo:

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


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [RevisionInfo()](#RevisionInfo--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getAction()](#getAction--) | Ottiene l'azione associata alla revisione (accetta o rifiuta). |
|
|  | [setAction(RevisionAction value)](#setAction-com.groupdocs.comparison.words.revision.RevisionAction-) | Imposta il valore associato alla revisione (accetta o rifiuta). |
|
|  | [getText()](#getText--) | Ottiene il contenuto testuale della revisione. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Imposta il valore del contenuto della revisione. |
|
|  | [getAuthor()](#getAuthor--) | Ottiene l'autore della revisione. |
|
|  | [setAuthor(String value)](#setAuthor-java.lang.String-) | Imposta il valore della revisione. |
|
|  | [getType()](#getType--) | Ottiene il tipo della revisione; a seconda del tipo, la logica dell'Azione (accetta o rifiuta) cambia. |
|
|  | [setType(RevisionType value)](#setType-com.groupdocs.comparison.words.revision.RevisionType-) | Imposta il valore della revisione; a seconda del valore, la logica dell'Azione (accetta o rifiuta) cambia. |
|
### RevisionInfo() {#RevisionInfo--}
```
public RevisionInfo()
```


### getAction() {#getAction--}
```
public RevisionAction getAction()
```


Ottiene l'azione associata alla revisione (accetta o rifiuta). Questo campo consente di influenzare la visualizzazione della revisione.


**Returns:**
[RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) - the action associated with the revision.

### setAction(RevisionAction value) {#setAction-com.groupdocs.comparison.words.revision.RevisionAction-}
```
public void setAction(RevisionAction value)
```


Imposta il valore associato alla revisione (accetta o rifiuta). Questo campo consente di influenzare la visualizzazione della revisione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | Il valore associato alla revisione. |
|

### getText() {#getText--}
```
public String getText()
```


Ottiene il contenuto testuale della revisione.


**Returns:**
java.lang.String - il contenuto testuale della revisione.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Imposta il valore del contenuto della revisione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.lang.String | Il contenuto del valore della revisione. |
|

### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Ottiene l'autore della revisione.


**Returns:**
java.lang.String - l'autore della revisione.

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public void setAuthor(String value)
```


Imposta il valore della revisione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.lang.String | Il valore della revisione. |
|

### getType() {#getType--}
```
public RevisionType getType()
```


Ottiene il tipo della revisione; a seconda del tipo, la logica dell'Azione (accetta o rifiuta) cambia.


**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) - the type of the revision.

### setType(RevisionType value) {#setType-com.groupdocs.comparison.words.revision.RevisionType-}
```
public void setType(RevisionType value)
```


Imposta il valore della revisione; a seconda del valore, la logica dell'Azione (accetta o rifiuta) cambia.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) | Il valore della revisione. |
|

