---
title: "ApplyChangeOptions"
second_title: "Riferimento API di GroupDocs.Comparison per Java"
description: "Consente di aggiornare l'elenco delle modifiche prima di applicarle al documento risultante."
type: docs
weight: 10
url: /it/java/com.groupdocs.comparison.options/applychangeoptions/
---
**Inheritance:**
java.lang.Object
```
public class ApplyChangeOptions
```

Consente di aggiornare l'elenco delle modifiche prima di applicarle al documento risultante.


Esempio di utilizzo:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);
     comparer.compare();
     ChangeInfo[] changes = comparer.getChanges();
     changes[0].setComparisonAction(ComparisonAction.REJECT);

     final ApplyChangeOptions applyChangeOptions = new ApplyChangeOptions(changes);

     comparer.applyChanges(resultFile, applyChangeOptions);
 }
 
````


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [ApplyChangeOptions()](#ApplyChangeOptions--) | Inizializza una nuova istanza della classe ApplyChangeOptions. |
|
|  | [ApplyChangeOptions(List<ChangeInfo> changes)](#ApplyChangeOptions-java.util.List-com.groupdocs.comparison.result.ChangeInfo--) | Inizializza una nuova istanza della classe ApplyChangeOptions con l'elenco delle modifiche. |
|
|  | [ApplyChangeOptions(ChangeInfo[] changes)](#ApplyChangeOptions-com.groupdocs.comparison.result.ChangeInfo---) | Inizializza una nuova istanza della classe ApplyChangeOptions con l'array delle modifiche. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getChanges()](#getChanges--) | Ottiene un array di modifiche da applicare al documento risultante. |
|
|  | [setChanges(ChangeInfo[] value)](#setChanges-com.groupdocs.comparison.result.ChangeInfo---) | Imposta un array di modifiche da applicare al documento risultante. |
|
|  | [setChanges(List<ChangeInfo> value)](#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--) | Imposta un elenco di modifiche da applicare al documento risultante. |
|
|  | [isSaveOriginalState()](#isSaveOriginalState--) | Ottiene un flag che determina se lo stato originale deve essere salvato. |
|
|  | [setSaveOriginalState(boolean saveOriginalState)](#setSaveOriginalState-boolean-) | Imposta un flag che determina se lo stato originale deve essere salvato. |
|
### ApplyChangeOptions() {#ApplyChangeOptions--}
```
public ApplyChangeOptions()
```


Inizializza una nuova istanza della classe ApplyChangeOptions.


### ApplyChangeOptions(List<ChangeInfo> changes) {#ApplyChangeOptions-java.util.List-com.groupdocs.comparison.result.ChangeInfo--}
```
public ApplyChangeOptions(List<ChangeInfo> changes)
```


Inizializza una nuova istanza della classe ApplyChangeOptions con l'elenco delle modifiche.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | modifiche | java.util.List<com.groupdocs.comparison.result.ChangeInfo> | L'elenco delle modifiche da applicare |
|

### ApplyChangeOptions(ChangeInfo[] changes) {#ApplyChangeOptions-com.groupdocs.comparison.result.ChangeInfo---}
```
public ApplyChangeOptions(ChangeInfo[] changes)
```


Inizializza una nuova istanza della classe ApplyChangeOptions con l'array delle modifiche.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | changes | [ChangeInfo\[\]](../../com.groupdocs.comparison.result/changeinfo) | L'elenco delle modifiche da applicare |
|

### getChanges() {#getChanges--}
```
public final ChangeInfo[] getChanges()
```


Ottiene un array di modifiche da applicare al documento risultante.


**Returns:**
com.groupdocs.comparison.result.ChangeInfo[] - l'array delle modifiche da applicare

### setChanges(ChangeInfo[] value) {#setChanges-com.groupdocs.comparison.result.ChangeInfo---}
```
public final void setChanges(ChangeInfo[] value)
```


Imposta un array di modifiche da applicare al documento risultante.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [ChangeInfo\[\]](../../com.groupdocs.comparison.result/changeinfo) | L'array delle modifiche da applicare |
|

### setChanges(List<ChangeInfo> value) {#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--}
```
public final void setChanges(List<ChangeInfo> value)
```


Imposta un elenco di modifiche da applicare al documento risultante.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.util.List<com.groupdocs.comparison.result.ChangeInfo> | L'elenco delle modifiche da applicare |
|

### isSaveOriginalState() {#isSaveOriginalState--}
```
public boolean isSaveOriginalState()
```


Ottiene un flag che determina se lo stato originale deve essere salvato. Valore predefinito: false.


**Returns:**
boolean - true se lo stato originale deve essere salvato, altrimenti false

### setSaveOriginalState(boolean saveOriginalState) {#setSaveOriginalState-boolean-}
```
public void setSaveOriginalState(boolean saveOriginalState)
```


Imposta un flag che determina se lo stato originale deve essere salvato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | saveOriginalState | boolean | True se lo stato originale deve essere salvato, altrimenti false |
|

