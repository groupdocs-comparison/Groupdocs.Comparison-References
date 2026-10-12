---
title: "PageInfo"
second_title: "GroupDocs.Comparison für Java API-Referenz"
description: "Die Klasse PageInfo stellt Informationen über eine bestimmte Seite in einem Dokument dar."
type: docs
weight: 11
url: /de/java/com.groupdocs.comparison.result/pageinfo/
---
**Inheritance:**
java.lang.Object
```
public class PageInfo
```

Die Klasse PageInfo stellt Informationen über eine bestimmte Seite in einem Dokument dar.


Sie liefert Details wie die Seitenzahl, Breite, Höhe und andere relevante Eigenschaften.
Verwenden Sie diese Klasse, um Informationen über einzelne Seiten in einem Dokument während des Vergleichsprozesses abzurufen.


Beispielverwendung:

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


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [PageInfo(int pageNumber, int width, int height)](#PageInfo-int-int-int-) | Initialisiert eine neue Instanz der PageInfo-Klasse mit den Parametern pageNumber, Breite und Höhe. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getWidth()](#getWidth--) | Liest die Breite der Seite |
|
|  | [setWidth(int value)](#setWidth-int-) | Setzt die Breite der Seite |
|
|  | [getHeight()](#getHeight--) | Liest die Höhe der Seite |
|
|  | [setHeight(int value)](#setHeight-int-) | Setzt die Höhe der Seite |
|
|  | [getPageNumber()](#getPageNumber--) | Liest die Nummer der Seite |
|
|  | [setPageNumber(int value)](#setPageNumber-int-) | Setzt die Nummer der Seite |
|
| [toString()](#toString--) |  |
### PageInfo(int pageNumber, int width, int height) {#PageInfo-int-int-int-}
```
public PageInfo(int pageNumber, int width, int height)
```


Initialisiert eine neue Instanz der PageInfo-Klasse mit den Parametern pageNumber, Breite und Höhe.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | pageNumber | int | Die Nummer der Seite |
|
|  | width | int | Die Breite der Seite |
|
|  | height | int | Die Höhe der Seite |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Liest die Breite der Seite


**Returns:**
int - die Breite der Seite

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Setzt die Breite der Seite


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | int | Die Breite der Seite |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Liest die Höhe der Seite


**Returns:**
int - die Höhe der Seite

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Setzt die Höhe der Seite


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | int | Die Höhe der Seite |
|

### getPageNumber() {#getPageNumber--}
```
public final int getPageNumber()
```


Liest die Nummer der Seite


**Returns:**
int - die Seitennummer

### setPageNumber(int value) {#setPageNumber-int-}
```
public final void setPageNumber(int value)
```


Setzt die Nummer der Seite


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | int | Die Nummer der Seite |
|

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
