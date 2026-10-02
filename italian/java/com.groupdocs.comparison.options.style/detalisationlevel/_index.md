---
title: "DetalisationLevel"
second_title: "Riferimento API di GroupDocs.Comparison per Java"
description: "Specifica il livello di dettaglio del confronto."
type: docs
weight: 13
url: /it/java/com.groupdocs.comparison.options.style/detalisationlevel/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DetalisationLevel extends Enum<DetalisationLevel>
```

Specifica il livello di dettaglio del confronto.


Esempio di utilizzo:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setDetectStyleChanges(false);
    compareOptions.setDetalisationLevel(DetalisationLevel.HIGH);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## Campi

| Campo | Descrizione |
| --- | --- |
|  | [LOW](#LOW) | Rappresenta il livello di confronto Basso. |
|
|  | [MIDDLE](#MIDDLE) | Rappresenta il livello di confronto Medio. |
|
|  | [HIGH](#HIGH) | Rappresenta il livello di confronto Alto. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Analizza la rappresentazione stringa di DetalisationLevel per ottenere la costante dell'enumerazione. |
|
|  | [toString()](#toString--) | Rappresentazione stringa di DetalisationLevel. |
|
### LOW {#LOW}
```
public static final DetalisationLevel LOW
```


Rappresenta il livello di confronto Basso.


Il livello "Low" offre la massima velocità per i confronti ma sacrifica la qualità del confronto.
Il confronto viene eseguito parola per parola.


### MIDDLE {#MIDDLE}
```
public static final DetalisationLevel MIDDLE
```


Rappresenta il livello di confronto Medio.


Il livello "Middle" è un compromesso ragionevole tra velocità e qualità del confronto.
Il confronto viene eseguito carattere per carattere, ma ignorando il caso dei caratteri e il conteggio degli spazi.


### HIGH {#HIGH}
```
public static final DetalisationLevel HIGH
```


Rappresenta il livello di confronto Alto.


Il livello "High" offre la migliore qualità di confronto, ma la velocità più bassa.
Il confronto viene eseguito carattere per carattere considerando il caso dei caratteri e il conteggio degli spazi.


### values() {#values--}
```
public static DetalisationLevel[] values()
```




**Returns:**
com.groupdocs.comparison.options.style.DetalisationLevel[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static DetalisationLevel valueOf(String name)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String |  |

**Returns:**
[DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static DetalisationLevel fromString(String toStringValue)
```


Analizza la rappresentazione stringa di DetalisationLevel per ottenere la costante dell'enumerazione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | toStringValue | java.lang.String | La rappresentazione stringa di DetalisationLevel |
|

**Returns:**
[DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) - DetalisationLevel enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


Rappresentazione stringa di DetalisationLevel.


**Returns:**
java.lang.String - valore stringa della costante dell'enumerazione

