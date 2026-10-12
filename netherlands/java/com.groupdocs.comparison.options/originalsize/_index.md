---
title: "OriginalSize"
second_title: "GroupDocs.Comparison voor Java API-referentie"
description: "Stelt de oorspronkelijke grootte van een document in een vergelijkingsresultaat voor."
type: docs
weight: 14
url: /nl/java/com.groupdocs.comparison.options/originalsize/
---
**Inheritance:**
java.lang.Object
```
public class OriginalSize
```

Stelt de oorspronkelijke grootte van een document in een vergelijkingsresultaat voor.


De oorspronkelijke grootte omvat de afmetingen (breedte en hoogte) van de pagina's van het document.


Voorbeeldgebruik:

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


## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [OriginalSize()](#OriginalSize--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getWidth()](#getWidth--) | Haalt de breedte van de pagina's van het document op. |
|
|  | [setWidth(int value)](#setWidth-int-) | Stelt de breedte van de pagina's van het document in. |
|
|  | [getHeight()](#getHeight--) | Haalt de hoogte van de pagina's van het document op. |
|
|  | [setHeight(int value)](#setHeight-int-) | Stelt de hoogte van de pagina's van het document in. |
|
### OriginalSize() {#OriginalSize--}
```
public OriginalSize()
```


### getWidth() {#getWidth--}
```
public final int getWidth()
```


Haalt de breedte van de pagina's van het document op.


**Returns:**
int - de breedte van de pagina's van het document.

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Stelt de breedte van de pagina's van het document in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | int | De breedte van de pagina's van het document. |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Haalt de hoogte van de pagina's van het document op.


**Returns:**
int - de hoogte van de pagina's van het document.

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Stelt de hoogte van de pagina's van het document in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | int | De hoogte van de pagina's van het document. |
|

