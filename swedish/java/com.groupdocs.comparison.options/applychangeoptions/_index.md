---
title: "ApplyChangeOptions"
second_title: "GroupDocs.Comparison för Java API-referens"
description: "Tillåter att uppdatera listan över ändringar innan de tillämpas på det resulterande dokumentet."
type: docs
weight: 10
url: /sv/java/com.groupdocs.comparison.options/applychangeoptions/
---
**Inheritance:**
java.lang.Object
```
public class ApplyChangeOptions
```

Tillåter att uppdatera listan över ändringar innan de tillämpas på det resulterande dokumentet.


Exempel på användning:

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


## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [ApplyChangeOptions()](#ApplyChangeOptions--) | Initierar en ny instans av klassen ApplyChangeOptions. |
|
|  | [ApplyChangeOptions(List<ChangeInfo> changes)](#ApplyChangeOptions-java.util.List-com.groupdocs.comparison.result.ChangeInfo--) | Initierar en ny instans av klassen ApplyChangeOptions med en lista av ändringar. |
|
|  | [ApplyChangeOptions(ChangeInfo[] changes)](#ApplyChangeOptions-com.groupdocs.comparison.result.ChangeInfo---) | Initierar en ny instans av klassen ApplyChangeOptions med en array av ändringar. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getChanges()](#getChanges--) | Hämtar en array av ändringar som måste tillämpas på det resulterande dokumentet. |
|
|  | [setChanges(ChangeInfo[] value)](#setChanges-com.groupdocs.comparison.result.ChangeInfo---) | Ställer in en array av ändringar som måste tillämpas på det resulterande dokumentet. |
|
|  | [setChanges(List<ChangeInfo> value)](#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--) | Ställer in en lista av ändringar som måste tillämpas på det resulterande dokumentet. |
|
|  | [isSaveOriginalState()](#isSaveOriginalState--) | Hämtar en flagga som bestämmer om det ursprungliga tillståndet ska sparas. |
|
|  | [setSaveOriginalState(boolean saveOriginalState)](#setSaveOriginalState-boolean-) | Ställer in en flagga som bestämmer om det ursprungliga tillståndet ska sparas. |
|
### ApplyChangeOptions() {#ApplyChangeOptions--}
```
public ApplyChangeOptions()
```


Initierar en ny instans av klassen ApplyChangeOptions.


### ApplyChangeOptions(List<ChangeInfo> changes) {#ApplyChangeOptions-java.util.List-com.groupdocs.comparison.result.ChangeInfo--}
```
public ApplyChangeOptions(List<ChangeInfo> changes)
```


Initierar en ny instans av klassen ApplyChangeOptions med en lista av ändringar.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | ändringar | java.util.List<com.groupdocs.comparison.result.ChangeInfo> | Listan med ändringar som ska tillämpas |
|

### ApplyChangeOptions(ChangeInfo[] changes) {#ApplyChangeOptions-com.groupdocs.comparison.result.ChangeInfo---}
```
public ApplyChangeOptions(ChangeInfo[] changes)
```


Initierar en ny instans av klassen ApplyChangeOptions med en array av ändringar.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | changes | [ChangeInfo\[\]](../../com.groupdocs.comparison.result/changeinfo) | Listan med ändringar som ska tillämpas |
|

### getChanges() {#getChanges--}
```
public final ChangeInfo[] getChanges()
```


Hämtar en array av ändringar som måste tillämpas på det resulterande dokumentet.


**Returns:**
com.groupdocs.comparison.result.ChangeInfo[] - arrayen av ändringar som ska tillämpas

### setChanges(ChangeInfo[] value) {#setChanges-com.groupdocs.comparison.result.ChangeInfo---}
```
public final void setChanges(ChangeInfo[] value)
```


Ställer in en array av ändringar som måste tillämpas på det resulterande dokumentet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [ChangeInfo\[\]](../../com.groupdocs.comparison.result/changeinfo) | Arrayen av ändringar som ska tillämpas |
|

### setChanges(List<ChangeInfo> value) {#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--}
```
public final void setChanges(List<ChangeInfo> value)
```


Ställer in en lista av ändringar som måste tillämpas på det resulterande dokumentet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | java.util.List<com.groupdocs.comparison.result.ChangeInfo> | Listan med ändringar som ska tillämpas |
|

### isSaveOriginalState() {#isSaveOriginalState--}
```
public boolean isSaveOriginalState()
```


Hämtar en flagga som bestämmer om det ursprungliga tillståndet ska sparas. Standardvärde: false.


**Returns:**
boolean - true om det ursprungliga tillståndet ska sparas, annars false

### setSaveOriginalState(boolean saveOriginalState) {#setSaveOriginalState-boolean-}
```
public void setSaveOriginalState(boolean saveOriginalState)
```


Ställer in en flagga som bestämmer om det ursprungliga tillståndet ska sparas.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | saveOriginalState | boolean | True om det ursprungliga tillståndet ska sparas, annars false |
|

