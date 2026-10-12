---
title: "GetChangeOptions"
second_title: "GroupDocs.Comparison voor Java API-referentie"
description: "Staat toe filterinstellingen te configureren voor het ophalen van specifieke wijzigingstypen uit het vergelijkingsresultaat."
type: docs
weight: 13
url: /nl/java/com.groupdocs.comparison.options/getchangeoptions/
---
**Inheritance:**
java.lang.Object
```
public class GetChangeOptions
```

Staat toe filterinstellingen te configureren voor het ophalen van specifieke wijzigingstypen uit het vergelijkingsresultaat.


Voorbeeldgebruik:

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


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [GetChangeOptions()](#GetChangeOptions--) | Initialiseert een nieuw exemplaar van de GetChangeOptions-klasse. |
|
|  | [GetChangeOptions(ChangeType filter)](#GetChangeOptions-com.groupdocs.comparison.result.ChangeType-) | Initialiseert een nieuw exemplaar van de GetChangeOptions-klasse voor het opgegeven filtertype. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getFilter()](#getFilter--) | Haalt het filter op voor het ophalen van specifieke wijzigingstypen uit het vergelijkingsresultaat. |
|
|  | [setFilter(ChangeType value)](#setFilter-com.groupdocs.comparison.result.ChangeType-) | Stelt het filter in voor het ophalen van specifieke wijzigingstypen uit het vergelijkingsresultaat. |
|
### GetChangeOptions() {#GetChangeOptions--}
```
public GetChangeOptions()
```


Initialiseert een nieuw exemplaar van de GetChangeOptions-klasse.


### GetChangeOptions(ChangeType filter) {#GetChangeOptions-com.groupdocs.comparison.result.ChangeType-}
```
public GetChangeOptions(ChangeType filter)
```


Initialiseert een nieuw exemplaar van de GetChangeOptions-klasse voor het opgegeven filtertype.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filter | [ChangeType](../../com.groupdocs.comparison.result/changetype) |  |

### getFilter() {#getFilter--}
```
public final ChangeType getFilter()
```


Haalt het filter op voor het ophalen van specifieke wijzigingstypen uit het vergelijkingsresultaat.


**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - the filter specifying the types of changes to be retrieved.

### setFilter(ChangeType value) {#setFilter-com.groupdocs.comparison.result.ChangeType-}
```
public final void setFilter(ChangeType value)
```


Stelt het filter in voor het ophalen van specifieke wijzigingstypen uit het vergelijkingsresultaat.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [ChangeType](../../com.groupdocs.comparison.result/changetype) | Het filter dat de types wijzigingen specificeert die moeten worden opgehaald. |
|

