---
title: "Size"
second_title: "GroupDocs.Comparison för Java API-referens"
description: "Representerar dokumentets storlek i jämförelsen."
type: docs
weight: 11
url: /sv/java/com.groupdocs.comparison.options.style/size/
---
**Inheritance:**
java.lang.Object
```
public class Size
```

Representerar dokumentets storlek i jämförelsen.


Exempel på användning:

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


## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [Size()](#Size--) | Initierar en ny instans av Size-klassen. |
|
|  | [Size(int width, int height)](#Size-int-int-) | Initierar en ny instans av Size-klassen med bredd och höjd för ett dokument. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getWidth()](#getWidth--) | Hämtar bredden på ett originaldokument. |
|
|  | [setWidth(int value)](#setWidth-int-) | Ställer in bredden på ett originaldokument. |
|
|  | [getHeight()](#getHeight--) | Hämtar höjden på ett originaldokument. |
|
|  | [setHeight(int value)](#setHeight-int-) | Ställer in höjden på ett originaldokument. |
|
### Size() {#Size--}
```
public Size()
```


Initierar en ny instans av Size-klassen.


### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


Initierar en ny instans av Size-klassen med bredd och höjd för ett dokument.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| width | int |  |
| height | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Hämtar bredden på ett originaldokument.


**Returns:**
int - dokumentets bredd

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Ställer in bredden på ett originaldokument.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | int | Dokumentets bredd |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Hämtar höjden på ett originaldokument.


**Returns:**
int - dokumentets höjd

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Ställer in höjden på ett originaldokument.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | int | Dokumentets höjd |
|

