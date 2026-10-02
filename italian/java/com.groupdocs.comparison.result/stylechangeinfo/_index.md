---
title: "StyleChangeInfo"
second_title: "Riferimento API di GroupDocs.Comparison per Java"
description: "La classe StyleChangeInfo rappresenta le informazioni su una modifica di stile in un documento confrontato."
type: docs
weight: 13
url: /it/java/com.groupdocs.comparison.result/stylechangeinfo/
---
**Inheritance:**
java.lang.Object
```
public class StyleChangeInfo
```

La classe StyleChangeInfo rappresenta le informazioni su una modifica di stile in un documento confrontato.


Fornisce dettagli come il nome della proprietà modificata, i valori prima e dopo la modifica, ecc.
Utilizza questa classe per recuperare informazioni sulle modifiche di stile durante il processo di confronto dei documenti.


Esempio di utilizzo:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     comparer.compare();
     final ChangeInfo[] changes = comparer.getChanges();
     for (ChangeInfo change : changes) {
         // Access the style change information
         final List styleChanges = change.getStyleChanges();
         for (StyleChangeInfo styleChange : styleChanges) {
             // Print the style change information
             System.out.println("PropertyName: " + styleChange.getPropertyName());
             System.out.println("OldValue: " + styleChange.getOldValue());
             System.out.println("NewValue: " + styleChange.getNewValue());
         }
     }
 }
 
````


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [StyleChangeInfo()](#StyleChangeInfo--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getPropertyName()](#getPropertyName--) | Ottiene il nome della proprietà che è stata modificata. |
|
|  | [setPropertyName(String value)](#setPropertyName-java.lang.String-) | Imposta il nome della proprietà che è stata modificata. |
|
|  | [getNewValue()](#getNewValue--) | Ottiene il nuovo valore della proprietà. |
|
|  | [setNewValue(Object value)](#setNewValue-java.lang.Object-) | Imposta il nuovo valore della proprietà. |
|
|  | [getOldValue()](#getOldValue--) | Ottiene il vecchio valore della proprietà. |
|
|  | [setOldValue(Object value)](#setOldValue-java.lang.Object-) | Imposta il vecchio valore della proprietà. |
|
|  | [equals(Object o)](#equals-java.lang.Object-) | {@inheritDoc} |
|
|  | [hashCode()](#hashCode--) | {@inheritDoc} |
|
### StyleChangeInfo() {#StyleChangeInfo--}
```
public StyleChangeInfo()
```


### getPropertyName() {#getPropertyName--}
```
public final String getPropertyName()
```


Ottiene il nome della proprietà che è stata modificata.


**Returns:**
java.lang.String - il nome della proprietà

### setPropertyName(String value) {#setPropertyName-java.lang.String-}
```
public final void setPropertyName(String value)
```


Imposta il nome della proprietà che è stata modificata.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.lang.String | Il nome della proprietà |
|

### getNewValue() {#getNewValue--}
```
public final Object getNewValue()
```


Ottiene il nuovo valore della proprietà.


**Returns:**
java.lang.Object - il nuovo valore della proprietà

### setNewValue(Object value) {#setNewValue-java.lang.Object-}
```
public final void setNewValue(Object value)
```


Imposta il nuovo valore della proprietà.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.lang.Object | Il nuovo valore della proprietà |
|

### getOldValue() {#getOldValue--}
```
public final Object getOldValue()
```


Ottiene il vecchio valore della proprietà.


**Returns:**
java.lang.Object - il vecchio valore della proprietà

### setOldValue(Object value) {#setOldValue-java.lang.Object-}
```
public final void setOldValue(Object value)
```


Imposta il vecchio valore della proprietà.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.lang.Object | Il vecchio valore della proprietà |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| o | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
