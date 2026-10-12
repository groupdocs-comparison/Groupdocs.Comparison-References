---
title: "ApplyChangeOptions"
second_title: "GroupDocs.Comparison voor Java API-referentie"
description: "Staat toe de lijst met wijzigingen bij te werken voordat ze op het resulterende document worden toegepast."
type: docs
weight: 10
url: /nl/java/com.groupdocs.comparison.options/applychangeoptions/
---
**Inheritance:**
java.lang.Object
```
public class ApplyChangeOptions
```

Staat toe de lijst met wijzigingen bij te werken voordat ze op het resulterende document worden toegepast.


Voorbeeldgebruik:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);
     comparer.compare();
     ChangeInfo[] changes = comparer.getChanges();
     changes[0].setComparisonAction(ComparisonAction.REJECT);

     final ApplyChangeOptions applyChangeOptions = new ApplyChangeOptions(changes);

     comparer.applyChanges(resultFile, applyChangeOptions);
 }
 
````


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [ApplyChangeOptions()](#ApplyChangeOptions--) | Initialiseert een nieuw exemplaar van de klasse ApplyChangeOptions. |
|
|  | [ApplyChangeOptions(List<ChangeInfo> changes)](#ApplyChangeOptions-java.util.List-com.groupdocs.comparison.result.ChangeInfo--) | Initialiseert een nieuw exemplaar van de klasse ApplyChangeOptions met een lijst van wijzigingen. |
|
|  | [ApplyChangeOptions(ChangeInfo[] changes)](#ApplyChangeOptions-com.groupdocs.comparison.result.ChangeInfo---) | Initialiseert een nieuw exemplaar van de klasse ApplyChangeOptions met een array van wijzigingen. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getChanges()](#getChanges--) | Haalt een array van wijzigingen op die op het resulterende document moeten worden toegepast. |
|
|  | [setChanges(ChangeInfo[] value)](#setChanges-com.groupdocs.comparison.result.ChangeInfo---) | Stelt een array van wijzigingen in die op het resulterende document moeten worden toegepast. |
|
|  | [setChanges(List<ChangeInfo> value)](#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--) | Stelt een lijst van wijzigingen in die op het resulterende document moeten worden toegepast. |
|
|  | [isSaveOriginalState()](#isSaveOriginalState--) | Haalt een vlag op die bepaalt of de oorspronkelijke staat moet worden opgeslagen. |
|
|  | [setSaveOriginalState(boolean saveOriginalState)](#setSaveOriginalState-boolean-) | Stelt een vlag in die bepaalt of de oorspronkelijke staat moet worden opgeslagen. |
|
### ApplyChangeOptions() {#ApplyChangeOptions--}
```
public ApplyChangeOptions()
```


Initialiseert een nieuw exemplaar van de klasse ApplyChangeOptions.


### ApplyChangeOptions(List<ChangeInfo> changes) {#ApplyChangeOptions-java.util.List-com.groupdocs.comparison.result.ChangeInfo--}
```
public ApplyChangeOptions(List<ChangeInfo> changes)
```


Initialiseert een nieuw exemplaar van de klasse ApplyChangeOptions met een lijst van wijzigingen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | wijzigingen | java.util.List<com.groupdocs.comparison.result.ChangeInfo> | De lijst met wijzigingen die moeten worden toegepast |
|

### ApplyChangeOptions(ChangeInfo[] changes) {#ApplyChangeOptions-com.groupdocs.comparison.result.ChangeInfo---}
```
public ApplyChangeOptions(ChangeInfo[] changes)
```


Initialiseert een nieuw exemplaar van de klasse ApplyChangeOptions met een array van wijzigingen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | changes | [ChangeInfo\[\]](../../com.groupdocs.comparison.result/changeinfo) | De lijst met wijzigingen die moeten worden toegepast |
|

### getChanges() {#getChanges--}
```
public final ChangeInfo[] getChanges()
```


Haalt een array van wijzigingen op die op het resulterende document moeten worden toegepast.


**Returns:**
com.groupdocs.comparison.result.ChangeInfo[] - de array met wijzigingen die moeten worden toegepast

### setChanges(ChangeInfo[] value) {#setChanges-com.groupdocs.comparison.result.ChangeInfo---}
```
public final void setChanges(ChangeInfo[] value)
```


Stelt een array van wijzigingen in die op het resulterende document moeten worden toegepast.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [ChangeInfo\[\]](../../com.groupdocs.comparison.result/changeinfo) | De array met wijzigingen die moeten worden toegepast |
|

### setChanges(List<ChangeInfo> value) {#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--}
```
public final void setChanges(List<ChangeInfo> value)
```


Stelt een lijst van wijzigingen in die op het resulterende document moeten worden toegepast.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.util.List<com.groupdocs.comparison.result.ChangeInfo> | De lijst met wijzigingen die moeten worden toegepast |
|

### isSaveOriginalState() {#isSaveOriginalState--}
```
public boolean isSaveOriginalState()
```


Haalt een vlag op die bepaalt of de oorspronkelijke staat moet worden opgeslagen. Standaardwaarde: false.


**Returns:**
boolean - true als de oorspronkelijke staat moet worden opgeslagen, anders false

### setSaveOriginalState(boolean saveOriginalState) {#setSaveOriginalState-boolean-}
```
public void setSaveOriginalState(boolean saveOriginalState)
```


Stelt een vlag in die bepaalt of de oorspronkelijke staat moet worden opgeslagen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | saveOriginalState | boolean | True als de oorspronkelijke staat moet worden opgeslagen, anders false |
|

