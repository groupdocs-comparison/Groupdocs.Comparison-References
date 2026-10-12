---
title: "ComparisonAction"
second_title: "Riferimento API di GroupDocs.Comparison per Java"
description: "L'enum ComparisonAction rappresenta le azioni che possono essere applicate a una modifica durante il processo di confronto di documenti."
type: docs
weight: 15
url: /it/java/com.groupdocs.comparison.result/comparisonaction/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ComparisonAction extends Enum<ComparisonAction>
```

L'enum ComparisonAction rappresenta le azioni che possono essere applicate a una modifica durante il processo di confronto di documenti.


Ogni costante in questo enum rappresenta un'azione specifica e fornisce una descrizione leggibile dall'uomo e un valore numerico.


Esempio di utilizzo:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);
     comparer.compare();

     final ChangeInfo[] changes = comparer.getChanges();
     for (ChangeInfo changeInfo : changes) {
         if (changeInfo.getId() % 2 == 0) {
             changeInfo.setComparisonAction(ComparisonAction.REJECT);
         }
     }
     comparer.applyChanges(resultFile, changes);
 }
 
````


## Campi

| Campo | Descrizione |
| --- | --- |
|  | [NONE](#NONE) | Rappresenta nessuna azione. |
|
|  | [ACCEPT](#ACCEPT) | Rappresenta un'azione di accettazione. |
|
|  | [REJECT](#REJECT) | Rappresenta un'azione di rifiuto. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Analizza la rappresentazione stringa di ComparisonAction per ottenere la costante enum. |
|
|  | [fromInt(int intValue)](#fromInt-int-) | Crea una nuova costante dell'enum ComparisonAction usando il valore numerico fornito. |
|
|  | [toString()](#toString--) | Rappresentazione stringa di ComparisonAction. |
|
|  | [toInt()](#toInt--) | Rappresentazione numerica di ComparisonAction. |
|
### NONE {#NONE}
```
public static final ComparisonAction NONE
```


Rappresenta nessuna azione. La modifica non avrà alcun effetto.


### ACCEPT {#ACCEPT}
```
public static final ComparisonAction ACCEPT
```


Rappresenta un'azione di accettazione. La modifica sarà visibile nel file di risultato.


### REJECT {#REJECT}
```
public static final ComparisonAction REJECT
```


Rappresenta un'azione di rifiuto. La modifica sarà invisibile nel file di risultato.


### values() {#values--}
```
public static ComparisonAction[] values()
```




**Returns:**
com.groupdocs.comparison.result.ComparisonAction[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static ComparisonAction valueOf(String name)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String |  |

**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static ComparisonAction fromString(String toStringValue)
```


Analizza la rappresentazione stringa di ComparisonAction per ottenere la costante enum.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | toStringValue | java.lang.String | La rappresentazione stringa di ComparisonAction |
|

**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) - ComparisonAction enum constant associated with input string

### fromInt(int intValue) {#fromInt-int-}
```
public static ComparisonAction fromInt(int intValue)
```


Crea una nuova costante dell'enum ComparisonAction usando il valore numerico fornito.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | intValue | int | La rappresentazione numerica di ComparisonAction |
|

**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) - ComparisonAction enum constant associated with numeric value

### toString() {#toString--}
```
public String toString()
```


Rappresentazione stringa di ComparisonAction.


**Returns:**
java.lang.String - valore stringa della costante dell'enumerazione

### toInt() {#toInt--}
```
public int toInt()
```


Rappresentazione numerica di ComparisonAction.


**Returns:**
int - valore numerico della costante dell'enumerazione

