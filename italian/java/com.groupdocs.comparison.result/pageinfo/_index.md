---
title: "PageInfo"
second_title: "Riferimento API di GroupDocs.Comparison per Java"
description: "La classe PageInfo rappresenta le informazioni su una specifica pagina in un documento."
type: docs
weight: 11
url: /it/java/com.groupdocs.comparison.result/pageinfo/
---
**Inheritance:**
java.lang.Object
```
public class PageInfo
```

La classe PageInfo rappresenta le informazioni su una specifica pagina in un documento.


Fornisce dettagli come il numero di pagina, la larghezza, l'altezza e altre proprietà rilevanti.
Utilizza questa classe per recuperare informazioni sulle singole pagine di un documento durante il processo di confronto.


Esempio di utilizzo:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     comparer.compare(resultFile);
     final ChangeInfo[] changes = comparer.getChanges();
     for (ChangeInfo change : changes) {
         final PageInfo pageInfo = change.getPageInfo();
         // Print the page information
         System.out.println("Page Number: " + pageInfo.getPageNumber());
         System.out.println("Page Width: " + pageInfo.getWidth());
         System.out.println("Page Height: " + pageInfo.getHeight());
     }
 }
 
````


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [PageInfo(int pageNumber, int width, int height)](#PageInfo-int-int-int-) | Inizializza una nuova istanza della classe PageInfo configurando pageNumber, larghezza e altezza. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getWidth()](#getWidth--) | Ottiene la larghezza della pagina |
|
|  | [setWidth(int value)](#setWidth-int-) | Imposta la larghezza della pagina |
|
|  | [getHeight()](#getHeight--) | Ottiene l'altezza della pagina |
|
|  | [setHeight(int value)](#setHeight-int-) | Imposta l'altezza della pagina |
|
|  | [getPageNumber()](#getPageNumber--) | Ottiene il numero della pagina |
|
|  | [setPageNumber(int value)](#setPageNumber-int-) | Imposta il numero della pagina |
|
| [toString()](#toString--) |  |
### PageInfo(int pageNumber, int width, int height) {#PageInfo-int-int-int-}
```
public PageInfo(int pageNumber, int width, int height)
```


Inizializza una nuova istanza della classe PageInfo configurando pageNumber, larghezza e altezza.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | pageNumber | int | Il numero della pagina |
|
|  | width | int | La larghezza della pagina |
|
|  | height | int | L'altezza della pagina |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Ottiene la larghezza della pagina


**Returns:**
int - la larghezza della pagina

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Imposta la larghezza della pagina


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | int | La larghezza della pagina |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Ottiene l'altezza della pagina


**Returns:**
int - l'altezza della pagina

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Imposta l'altezza della pagina


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | int | L'altezza della pagina |
|

### getPageNumber() {#getPageNumber--}
```
public final int getPageNumber()
```


Ottiene il numero della pagina


**Returns:**
int - il numero della pagina

### setPageNumber(int value) {#setPageNumber-int-}
```
public final void setPageNumber(int value)
```


Imposta il numero della pagina


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | int | Il numero della pagina |
|

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
