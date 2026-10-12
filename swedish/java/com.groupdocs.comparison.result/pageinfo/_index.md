---
title: "PageInfo"
second_title: "GroupDocs.Comparison för Java API-referens"
description: "Klassen PageInfo representerar information om en specifik sida i ett dokument."
type: docs
weight: 11
url: /sv/java/com.groupdocs.comparison.result/pageinfo/
---
**Inheritance:**
java.lang.Object
```
public class PageInfo
```

Klassen PageInfo representerar information om en specifik sida i ett dokument.


Den tillhandahåller detaljer såsom sidnummer, bredd, höjd och andra relevanta egenskaper.
Använd den här klassen för att hämta information om enskilda sidor i ett dokument under jämförelseprocessen.


Exempel på användning:

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


## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [PageInfo(int pageNumber, int width, int height)](#PageInfo-int-int-int-) | Initierar en ny instans av PageInfo-klassen med konfiguration av sidnummer, bredd och höjd. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getWidth()](#getWidth--) | Hämtar sidans bredd |
|
|  | [setWidth(int value)](#setWidth-int-) | Ställer in sidans bredd |
|
|  | [getHeight()](#getHeight--) | Hämtar sidans höjd |
|
|  | [setHeight(int value)](#setHeight-int-) | Ställer in sidans höjd |
|
|  | [getPageNumber()](#getPageNumber--) | Hämtar sidnumret |
|
|  | [setPageNumber(int value)](#setPageNumber-int-) | Ställer in sidnumret |
|
| [toString()](#toString--) |  |
### PageInfo(int pageNumber, int width, int height) {#PageInfo-int-int-int-}
```
public PageInfo(int pageNumber, int width, int height)
```


Initierar en ny instans av PageInfo-klassen med konfiguration av sidnummer, bredd och höjd.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | pageNumber | int | Sidnumret |
|
|  | width | int | Sidans bredd |
|
|  | height | int | Sidans höjd |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Hämtar sidans bredd


**Returns:**
int - sidans bredd

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Ställer in sidans bredd


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | int | Sidans bredd |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Hämtar sidans höjd


**Returns:**
int - sidans höjd

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Ställer in sidans höjd


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | int | Sidans höjd |
|

### getPageNumber() {#getPageNumber--}
```
public final int getPageNumber()
```


Hämtar sidnumret


**Returns:**
int - sidans nummer

### setPageNumber(int value) {#setPageNumber-int-}
```
public final void setPageNumber(int value)
```


Ställer in sidnumret


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | int | Sidnumret |
|

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
