---
title: "PageInfo"
second_title: "Référence API de GroupDocs.Comparison for Java"
description: "La classe PageInfo représente les informations concernant une page spécifique d'un document."
type: docs
weight: 11
url: /fr/java/com.groupdocs.comparison.result/pageinfo/
---
**Inheritance:**
java.lang.Object
```
public class PageInfo
```

La classe PageInfo représente les informations concernant une page spécifique d'un document.


Il fournit des détails tels que le numéro de page, la largeur, la hauteur et d'autres propriétés pertinentes.
Utilisez cette classe pour récupérer des informations sur les pages individuelles d'un document pendant le processus de comparaison.


Exemple d'utilisation :

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


## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [PageInfo(int pageNumber, int width, int height)](#PageInfo-int-int-int-) | Initialise une nouvelle instance de la classe PageInfo en configurant pageNumber, la largeur et la hauteur. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getWidth()](#getWidth--) | Obtient la largeur de la page |
|
|  | [setWidth(int value)](#setWidth-int-) | Définit la largeur de la page |
|
|  | [getHeight()](#getHeight--) | Obtient la hauteur de la page |
|
|  | [setHeight(int value)](#setHeight-int-) | Définit la hauteur de la page |
|
|  | [getPageNumber()](#getPageNumber--) | Obtient le numéro de la page |
|
|  | [setPageNumber(int value)](#setPageNumber-int-) | Définit le numéro de la page |
|
| [toString()](#toString--) |  |
### PageInfo(int pageNumber, int width, int height) {#PageInfo-int-int-int-}
```
public PageInfo(int pageNumber, int width, int height)
```


Initialise une nouvelle instance de la classe PageInfo en configurant pageNumber, la largeur et la hauteur.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | pageNumber | int | Le numéro de la page |
|
|  | largeur | int | La largeur de la page |
|
|  | hauteur | int | La hauteur de la page |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Obtient la largeur de la page


**Returns:**
int - la largeur de la page

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Définit la largeur de la page


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | int | La largeur de la page |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Obtient la hauteur de la page


**Returns:**
int - la hauteur de la page

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Définit la hauteur de la page


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | int | La hauteur de la page |
|

### getPageNumber() {#getPageNumber--}
```
public final int getPageNumber()
```


Obtient le numéro de la page


**Returns:**
int - le numéro de la page

### setPageNumber(int value) {#setPageNumber-int-}
```
public final void setPageNumber(int value)
```


Définit le numéro de la page


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | int | Le numéro de la page |
|

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
