---
title: "Taille"
second_title: "Référence API de GroupDocs.Comparison for Java"
description: "Représente la taille du document dans la comparaison."
type: docs
weight: 11
url: /fr/java/com.groupdocs.comparison.options.style/size/
---
**Inheritance:**
java.lang.Object
```
public class Size
```

Représente la taille du document dans la comparaison.


Exemple d'utilisation :

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


## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [Size()](#Size--) | Initialise une nouvelle instance de la classe Taille. |
|
|  | [Size(int width, int height)](#Size-int-int-) | Initialise une nouvelle instance de la classe Taille avec la largeur et la hauteur d'un document. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getWidth()](#getWidth--) | Obtient la largeur d'un document original. |
|
|  | [setWidth(int value)](#setWidth-int-) | Définit la largeur d'un document original. |
|
|  | [getHeight()](#getHeight--) | Obtient la hauteur d'un document original. |
|
|  | [setHeight(int value)](#setHeight-int-) | Définit la hauteur d'un document original. |
|
### Size() {#Size--}
```
public Size()
```


Initialise une nouvelle instance de la classe Taille.


### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


Initialise une nouvelle instance de la classe Taille avec la largeur et la hauteur d'un document.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| largeur | int |  |
| hauteur | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Obtient la largeur d'un document original.


**Returns:**
int - la largeur du document

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Définit la largeur d'un document original.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | int | La largeur du document |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Obtient la hauteur d'un document original.


**Returns:**
int - la hauteur du document

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Définit la hauteur d'un document original.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | int | La hauteur du document |
|

