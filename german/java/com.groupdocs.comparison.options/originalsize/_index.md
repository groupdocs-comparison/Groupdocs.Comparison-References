---
title: "OriginalSize"
second_title: "GroupDocs.Comparison für Java API-Referenz"
description: "Stellt die ursprüngliche Größe eines Dokuments in einem Vergleichsergebnis dar."
type: docs
weight: 14
url: /de/java/com.groupdocs.comparison.options/originalsize/
---
**Inheritance:**
java.lang.Object
```
public class OriginalSize
```

Stellt die ursprüngliche Größe eines Dokuments in einem Vergleichsergebnis dar.


Die Originalgröße enthält die Abmessungen (Breite und Höhe) der Dokumentseiten.


Beispielverwendung:

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


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [OriginalSize()](#OriginalSize--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getWidth()](#getWidth--) | Liefert die Breite der Dokumentseiten. |
|
|  | [setWidth(int value)](#setWidth-int-) | Setzt die Breite der Dokumentseiten. |
|
|  | [getHeight()](#getHeight--) | Liefert die Höhe der Dokumentseiten. |
|
|  | [setHeight(int value)](#setHeight-int-) | Setzt die Höhe der Dokumentseiten. |
|
### OriginalSize() {#OriginalSize--}
```
public OriginalSize()
```


### getWidth() {#getWidth--}
```
public final int getWidth()
```


Liefert die Breite der Dokumentseiten.


**Returns:**
int - die Breite der Dokumentseiten.

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Setzt die Breite der Dokumentseiten.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | int | Die Breite der Dokumentseiten. |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Liefert die Höhe der Dokumentseiten.


**Returns:**
int - die Höhe der Dokumentseiten.

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Setzt die Höhe der Dokumentseiten.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | int | Die Höhe der Dokumentseiten. |
|

