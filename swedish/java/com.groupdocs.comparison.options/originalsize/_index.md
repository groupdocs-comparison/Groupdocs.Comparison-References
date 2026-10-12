---
title: "OriginalSize"
second_title: "GroupDocs.Comparison för Java API-referens"
description: "Representerar den ursprungliga storleken på ett dokument i ett jämförelsresultat."
type: docs
weight: 14
url: /sv/java/com.groupdocs.comparison.options/originalsize/
---
**Inheritance:**
java.lang.Object
```
public class OriginalSize
```

Representerar den ursprungliga storleken på ett dokument i ett jämförelsresultat.


Den ursprungliga storleken inkluderar dimensionerna (bredd och höjd) på dokumentets sidor.


Exempel på användning:

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


## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [OriginalSize()](#OriginalSize--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getWidth()](#getWidth--) | Hämtar bredden på dokumentets sidor. |
|
|  | [setWidth(int value)](#setWidth-int-) | Ställer in bredden på dokumentets sidor. |
|
|  | [getHeight()](#getHeight--) | Hämtar höjden på dokumentets sidor. |
|
|  | [setHeight(int value)](#setHeight-int-) | Ställer in höjden på dokumentets sidor. |
|
### OriginalSize() {#OriginalSize--}
```
public OriginalSize()
```


### getWidth() {#getWidth--}
```
public final int getWidth()
```


Hämtar bredden på dokumentets sidor.


**Returns:**
int - bredden på dokumentets sidor.

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Ställer in bredden på dokumentets sidor.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | int | Bredden på dokumentets sidor. |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Hämtar höjden på dokumentets sidor.


**Returns:**
int - höjden på dokumentets sidor.

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Ställer in höjden på dokumentets sidor.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | int | Höjden på dokumentets sidor. |
|

