---
title: "GetChangeOptions"
second_title: "GroupDocs.Comparison för Java API-referens"
description: "Tillåter att konfigurera filtrering för att hämta specifika ändringstyper från jämförelsresultatet."
type: docs
weight: 13
url: /sv/java/com.groupdocs.comparison.options/getchangeoptions/
---
**Inheritance:**
java.lang.Object
```
public class GetChangeOptions
```

Tillåter att konfigurera filtrering för att hämta specifika ändringstyper från jämförelsresultatet.


Exempel på användning:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);
     comparer.compare();

     GetChangeOptions getChangeOptions = new GetChangeOptions();

     getChangeOptions.setFilter(ChangeType.DELETED);

     ChangeInfo[] changes = comparer.getChanges(getChangeOptions);
     System.out.println(Arrays.toString(changes));
 }
 
````


## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [GetChangeOptions()](#GetChangeOptions--) | Initierar en ny instans av klassen GetChangeOptions. |
|
|  | [GetChangeOptions(ChangeType filter)](#GetChangeOptions-com.groupdocs.comparison.result.ChangeType-) | Initierar en ny instans av klassen GetChangeOptions för angiven filtertyp. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getFilter()](#getFilter--) | Hämtar filtret för att hämta specifika ändringstyper från jämförelsresultatet. |
|
|  | [setFilter(ChangeType value)](#setFilter-com.groupdocs.comparison.result.ChangeType-) | Ställer in filtret för att hämta specifika ändringstyper från jämförelsresultatet. |
|
### GetChangeOptions() {#GetChangeOptions--}
```
public GetChangeOptions()
```


Initierar en ny instans av klassen GetChangeOptions.


### GetChangeOptions(ChangeType filter) {#GetChangeOptions-com.groupdocs.comparison.result.ChangeType-}
```
public GetChangeOptions(ChangeType filter)
```


Initierar en ny instans av klassen GetChangeOptions för angiven filtertyp.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filter | [ChangeType](../../com.groupdocs.comparison.result/changetype) |  |

### getFilter() {#getFilter--}
```
public final ChangeType getFilter()
```


Hämtar filtret för att hämta specifika ändringstyper från jämförelsresultatet.


**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - the filter specifying the types of changes to be retrieved.

### setFilter(ChangeType value) {#setFilter-com.groupdocs.comparison.result.ChangeType-}
```
public final void setFilter(ChangeType value)
```


Ställer in filtret för att hämta specifika ändringstyper från jämförelsresultatet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [ChangeType](../../com.groupdocs.comparison.result/changetype) | Filtret som specificerar vilka ändringstyper som ska hämtas. |
|

