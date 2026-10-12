---
title: "Size"
second_title: "GroupDocs.Comparison voor Java API-referentie"
description: "Stelt de grootte van het document in de vergelijking voor."
type: docs
weight: 11
url: /nl/java/com.groupdocs.comparison.options.style/size/
---
**Inheritance:**
java.lang.Object
```
public class Size
```

Stelt de grootte van het document in de vergelijking voor.


Voorbeeldgebruik:

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


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [Size()](#Size--) | Initialiseert een nieuw exemplaar van de Size-klasse. |
|
|  | [Size(int width, int height)](#Size-int-int-) | Initialiseert een nieuw exemplaar van de Size-klasse met de breedte en hoogte van een document. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getWidth()](#getWidth--) | Haalt de breedte op van een origineel document. |
|
|  | [setWidth(int value)](#setWidth-int-) | Stelt de breedte in van een origineel document. |
|
|  | [getHeight()](#getHeight--) | Haalt de hoogte op van een origineel document. |
|
|  | [setHeight(int value)](#setHeight-int-) | Stelt de hoogte in van een origineel document. |
|
### Size() {#Size--}
```
public Size()
```


Initialiseert een nieuw exemplaar van de Size-klasse.


### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


Initialiseert een nieuw exemplaar van de Size-klasse met de breedte en hoogte van een document.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| width | int |  |
| height | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Haalt de breedte op van een origineel document.


**Returns:**
int - de breedte van het document

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Stelt de breedte in van een origineel document.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | int | De breedte van het document |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Haalt de hoogte op van een origineel document.


**Returns:**
int - de hoogte van het document

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Stelt de hoogte in van een origineel document.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | int | De hoogte van het document |
|

