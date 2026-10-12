---
title: "OriginalSize"
second_title: "Riferimento API di GroupDocs.Comparison per Java"
description: "Rappresenta le dimensioni originali di un documento in un risultato di confronto."
type: docs
weight: 14
url: /it/java/com.groupdocs.comparison.options/originalsize/
---
**Inheritance:**
java.lang.Object
```
public class OriginalSize
```

Rappresenta le dimensioni originali di un documento in un risultato di confronto.


La dimensione originale include le dimensioni (larghezza e altezza) delle pagine del documento.


Esempio di utilizzo:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     CompareOptions compareOptions = new CompareOptions();
     final OriginalSize originalSize = compareOptions.getOriginalSize();
     originalSize.setWidth(480);
     originalSize.setHeight(640);

     comparer.compare(resultFile, compareOptions);
 }
 
````


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [OriginalSize()](#OriginalSize--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getWidth()](#getWidth--) | Ottiene la larghezza delle pagine del documento. |
|
|  | [setWidth(int value)](#setWidth-int-) | Imposta la larghezza delle pagine del documento. |
|
|  | [getHeight()](#getHeight--) | Ottiene l'altezza delle pagine del documento. |
|
|  | [setHeight(int value)](#setHeight-int-) | Imposta l'altezza delle pagine del documento. |
|
### OriginalSize() {#OriginalSize--}
```
public OriginalSize()
```


### getWidth() {#getWidth--}
```
public final int getWidth()
```


Ottiene la larghezza delle pagine del documento.


**Returns:**
int - la larghezza delle pagine del documento.

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Imposta la larghezza delle pagine del documento.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | int | La larghezza delle pagine del documento. |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Ottiene l'altezza delle pagine del documento.


**Returns:**
int - l'altezza delle pagine del documento.

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Imposta l'altezza delle pagine del documento.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | int | L'altezza delle pagine del documento. |
|

