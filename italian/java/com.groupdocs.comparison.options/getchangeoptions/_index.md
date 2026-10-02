---
title: "GetChangeOptions"
second_title: "Riferimento API di GroupDocs.Comparison per Java"
description: "Consente di configurare il filtraggio per recuperare tipi di modifica specifici dal risultato del confronto."
type: docs
weight: 13
url: /it/java/com.groupdocs.comparison.options/getchangeoptions/
---
**Inheritance:**
java.lang.Object
```
public class GetChangeOptions
```

Consente di configurare il filtraggio per recuperare tipi di modifica specifici dal risultato del confronto.


Esempio di utilizzo:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);
     comparer.compare();

     GetChangeOptions getChangeOptions = new GetChangeOptions();

     getChangeOptions.setFilter(ChangeType.DELETED);

     ChangeInfo[] changes = comparer.getChanges(getChangeOptions);
     System.out.println(Arrays.toString(changes));
 }
 
````


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [GetChangeOptions()](#GetChangeOptions--) | Inizializza una nuova istanza della classe GetChangeOptions. |
|
|  | [GetChangeOptions(ChangeType filter)](#GetChangeOptions-com.groupdocs.comparison.result.ChangeType-) | Inizializza una nuova istanza della classe GetChangeOptions per il tipo di filtro specificato. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getFilter()](#getFilter--) | Ottiene il filtro per recuperare tipi di modifica specifici dal risultato del confronto. |
|
|  | [setFilter(ChangeType value)](#setFilter-com.groupdocs.comparison.result.ChangeType-) | Imposta il filtro per recuperare tipi di modifica specifici dal risultato del confronto. |
|
### GetChangeOptions() {#GetChangeOptions--}
```
public GetChangeOptions()
```


Inizializza una nuova istanza della classe GetChangeOptions.


### GetChangeOptions(ChangeType filter) {#GetChangeOptions-com.groupdocs.comparison.result.ChangeType-}
```
public GetChangeOptions(ChangeType filter)
```


Inizializza una nuova istanza della classe GetChangeOptions per il tipo di filtro specificato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filter | [ChangeType](../../com.groupdocs.comparison.result/changetype) |  |

### getFilter() {#getFilter--}
```
public final ChangeType getFilter()
```


Ottiene il filtro per recuperare tipi di modifica specifici dal risultato del confronto.


**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - the filter specifying the types of changes to be retrieved.

### setFilter(ChangeType value) {#setFilter-com.groupdocs.comparison.result.ChangeType-}
```
public final void setFilter(ChangeType value)
```


Imposta il filtro per recuperare tipi di modifica specifici dal risultato del confronto.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [ChangeType](../../com.groupdocs.comparison.result/changetype) | Il filtro che specifica i tipi di modifiche da recuperare. |
|

