---
title: "PageInfo"
second_title: "GroupDocs.Comparison voor Java API-referentie"
description: "De PageInfo-klasse vertegenwoordigt informatie over een specifieke pagina in een document."
type: docs
weight: 11
url: /nl/java/com.groupdocs.comparison.result/pageinfo/
---
**Inheritance:**
java.lang.Object
```
public class PageInfo
```

De PageInfo-klasse vertegenwoordigt informatie over een specifieke pagina in een document.


Het biedt details zoals het paginanummer, de breedte, de hoogte en andere relevante eigenschappen.
Gebruik deze klasse om informatie over individuele pagina's in een document op te halen tijdens het vergelijkingsproces.


Voorbeeldgebruik:

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


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [PageInfo(int pageNumber, int width, int height)](#PageInfo-int-int-int-) | Initialiseert een nieuw exemplaar van de PageInfo-klasse met het configureren van paginanummer, breedte en hoogte. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getWidth()](#getWidth--) | Haalt de breedte van de pagina op |
|
|  | [setWidth(int value)](#setWidth-int-) | Stelt de breedte van de pagina in |
|
|  | [getHeight()](#getHeight--) | Haalt de hoogte van de pagina op |
|
|  | [setHeight(int value)](#setHeight-int-) | Stelt de hoogte van de pagina in |
|
|  | [getPageNumber()](#getPageNumber--) | Haalt het paginanummer op |
|
|  | [setPageNumber(int value)](#setPageNumber-int-) | Stelt het paginanummer in |
|
| [toString()](#toString--) |  |
### PageInfo(int pageNumber, int width, int height) {#PageInfo-int-int-int-}
```
public PageInfo(int pageNumber, int width, int height)
```


Initialiseert een nieuw exemplaar van de PageInfo-klasse met het configureren van paginanummer, breedte en hoogte.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | pageNumber | int | Het paginanummer |
|
|  | width | int | De breedte van de pagina |
|
|  | height | int | De hoogte van de pagina |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Haalt de breedte van de pagina op


**Returns:**
int - de breedte van de pagina

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Stelt de breedte van de pagina in


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | int | De breedte van de pagina |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Haalt de hoogte van de pagina op


**Returns:**
int - de hoogte van de pagina

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Stelt de hoogte van de pagina in


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | int | De hoogte van de pagina |
|

### getPageNumber() {#getPageNumber--}
```
public final int getPageNumber()
```


Haalt het paginanummer op


**Returns:**
int - het paginanummer

### setPageNumber(int value) {#setPageNumber-int-}
```
public final void setPageNumber(int value)
```


Stelt het paginanummer in


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | int | Het paginanummer |
|

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
