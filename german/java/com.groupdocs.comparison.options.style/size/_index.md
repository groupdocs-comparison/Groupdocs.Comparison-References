---
title: "Size"
second_title: "GroupDocs.Comparison für Java API-Referenz"
description: "Stellt die Größe des Dokuments im Vergleich dar."
type: docs
weight: 11
url: /de/java/com.groupdocs.comparison.options.style/size/
---
**Inheritance:**
java.lang.Object
```
public class Size
```

Stellt die Größe des Dokuments im Vergleich dar.


Beispielverwendung:

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


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [Size()](#Size--) | Initialisiert eine neue Instanz der Size-Klasse. |
|
|  | [Size(int width, int height)](#Size-int-int-) | Initialisiert eine neue Instanz der Size-Klasse mit Breite und Höhe eines Dokuments. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getWidth()](#getWidth--) | Liest die Breite eines Originaldokuments. |
|
|  | [setWidth(int value)](#setWidth-int-) | Setzt die Breite eines Originaldokuments. |
|
|  | [getHeight()](#getHeight--) | Liest die Höhe eines Originaldokuments. |
|
|  | [setHeight(int value)](#setHeight-int-) | Setzt die Höhe eines Originaldokuments. |
|
### Size() {#Size--}
```
public Size()
```


Initialisiert eine neue Instanz der Size-Klasse.


### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


Initialisiert eine neue Instanz der Size-Klasse mit Breite und Höhe eines Dokuments.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| width | int |  |
| height | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Liest die Breite eines Originaldokuments.


**Returns:**
int - die Breite des Dokuments

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Setzt die Breite eines Originaldokuments.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | int | Die Breite des Dokuments |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Liest die Höhe eines Originaldokuments.


**Returns:**
int - die Höhe des Dokuments

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Setzt die Höhe eines Originaldokuments.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | int | Die Höhe des Dokuments |
|

