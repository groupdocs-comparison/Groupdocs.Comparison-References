---
title: "Size"
second_title: "Riferimento API di GroupDocs.Comparison per Java"
description: "Rappresenta le dimensioni del documento nel confronto."
type: docs
weight: 11
url: /it/java/com.groupdocs.comparison.options.style/size/
---
**Inheritance:**
java.lang.Object
```
public class Size
```

Rappresenta le dimensioni del documento nel confronto.


Esempio di utilizzo:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     final Size originalSize = new Size(100, 200);

     StyleSettings styleSettings = new StyleSettings();
     styleSettings.setOriginalSize(originalSize);

     final CompareOptions compareOptions = new CompareOptions();
     compareOptions.setInsertedItemStyle(styleSettings);

     comparer.compare(resultFile, compareOptions);
 }
 
````


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [Size()](#Size--) | Inizializza una nuova istanza della classe Size. |
|
|  | [Size(int width, int height)](#Size-int-int-) | Inizializza una nuova istanza della classe Size con larghezza e altezza di un documento. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getWidth()](#getWidth--) | Ottiene la larghezza di un documento originale. |
|
|  | [setWidth(int value)](#setWidth-int-) | Imposta la larghezza di un documento originale. |
|
|  | [getHeight()](#getHeight--) | Ottiene l'altezza di un documento originale. |
|
|  | [setHeight(int value)](#setHeight-int-) | Imposta l'altezza di un documento originale. |
|
### Size() {#Size--}
```
public Size()
```


Inizializza una nuova istanza della classe Size.


### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


Inizializza una nuova istanza della classe Size con larghezza e altezza di un documento.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | int |  |
| height | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Ottiene la larghezza di un documento originale.


**Returns:**
int - la larghezza del documento

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Imposta la larghezza di un documento originale.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | int | La larghezza del documento |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Ottiene l'altezza di un documento originale.


**Returns:**
int - l'altezza del documento

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Imposta l'altezza di un documento originale.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | int | L'altezza del documento |
|

