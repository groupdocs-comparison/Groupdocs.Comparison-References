---
title: "OriginalSize"
second_title: "Référence API de GroupDocs.Comparison for Java"
description: "Représente la taille originale d'un document dans un résultat de comparaison."
type: docs
weight: 14
url: /fr/java/com.groupdocs.comparison.options/originalsize/
---
**Inheritance:**
java.lang.Object
```
public class OriginalSize
```

Représente la taille originale d'un document dans un résultat de comparaison.


La taille originale comprend les dimensions (largeur et hauteur) des pages du document.


Exemple d'utilisation :

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


## Constructeurs

| Constructeur | Description |
| --- | --- |
| [OriginalSize()](#OriginalSize--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getWidth()](#getWidth--) | Obtient la largeur des pages du document. |
|
|  | [setWidth(int value)](#setWidth-int-) | Définit la largeur des pages du document. |
|
|  | [getHeight()](#getHeight--) | Obtient la hauteur des pages du document. |
|
|  | [setHeight(int value)](#setHeight-int-) | Définit la hauteur des pages du document. |
|
### OriginalSize() {#OriginalSize--}
```
public OriginalSize()
```


### getWidth() {#getWidth--}
```
public final int getWidth()
```


Obtient la largeur des pages du document.


**Returns:**
int - la largeur des pages du document.

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Définit la largeur des pages du document.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | int | La largeur des pages du document. |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Obtient la hauteur des pages du document.


**Returns:**
int - la hauteur des pages du document.

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Définit la hauteur des pages du document.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | int | La hauteur des pages du document. |
|

