---
title: "ApplyChangeOptions"
second_title: "GroupDocs.Comparison für Java API-Referenz"
description: "Ermöglicht das Aktualisieren der Liste von Änderungen, bevor sie auf das resultierende Dokument angewendet werden."
type: docs
weight: 10
url: /de/java/com.groupdocs.comparison.options/applychangeoptions/
---
**Inheritance:**
java.lang.Object
```
public class ApplyChangeOptions
```

Ermöglicht das Aktualisieren der Liste von Änderungen, bevor sie auf das resultierende Dokument angewendet werden.


Beispielverwendung:

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


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [ApplyChangeOptions()](#ApplyChangeOptions--) | Initialisiert eine neue Instanz der Klasse ApplyChangeOptions. |
|
|  | [ApplyChangeOptions(List<ChangeInfo> changes)](#ApplyChangeOptions-java.util.List-com.groupdocs.comparison.result.ChangeInfo--) | Initialisiert eine neue Instanz der Klasse ApplyChangeOptions mit einer Liste von Änderungen. |
|
|  | [ApplyChangeOptions(ChangeInfo[] changes)](#ApplyChangeOptions-com.groupdocs.comparison.result.ChangeInfo---) | Initialisiert eine neue Instanz der Klasse ApplyChangeOptions mit einem Array von Änderungen. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getChanges()](#getChanges--) | Liest ein Array von Änderungen, die auf das resultierende Dokument angewendet werden müssen. |
|
|  | [setChanges(ChangeInfo[] value)](#setChanges-com.groupdocs.comparison.result.ChangeInfo---) | Setzt ein Array von Änderungen, die auf das resultierende Dokument angewendet werden müssen. |
|
|  | [setChanges(List<ChangeInfo> value)](#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--) | Setzt eine Liste von Änderungen, die auf das resultierende Dokument angewendet werden müssen. |
|
|  | [isSaveOriginalState()](#isSaveOriginalState--) | Liest ein Flag, das bestimmt, ob der Originalzustand gespeichert werden soll. |
|
|  | [setSaveOriginalState(boolean saveOriginalState)](#setSaveOriginalState-boolean-) | Setzt ein Flag, das bestimmt, ob der Originalzustand gespeichert werden soll. |
|
### ApplyChangeOptions() {#ApplyChangeOptions--}
```
public ApplyChangeOptions()
```


Initialisiert eine neue Instanz der Klasse ApplyChangeOptions.


### ApplyChangeOptions(List<ChangeInfo> changes) {#ApplyChangeOptions-java.util.List-com.groupdocs.comparison.result.ChangeInfo--}
```
public ApplyChangeOptions(List<ChangeInfo> changes)
```


Initialisiert eine neue Instanz der Klasse ApplyChangeOptions mit einer Liste von Änderungen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Änderungen | java.util.List<com.groupdocs.comparison.result.ChangeInfo> | Die Liste der anzuwendenden Änderungen |
|

### ApplyChangeOptions(ChangeInfo[] changes) {#ApplyChangeOptions-com.groupdocs.comparison.result.ChangeInfo---}
```
public ApplyChangeOptions(ChangeInfo[] changes)
```


Initialisiert eine neue Instanz der Klasse ApplyChangeOptions mit einem Array von Änderungen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | changes | [ChangeInfo\[\]](../../com.groupdocs.comparison.result/changeinfo) | Die Liste der anzuwendenden Änderungen |
|

### getChanges() {#getChanges--}
```
public final ChangeInfo[] getChanges()
```


Liest ein Array von Änderungen, die auf das resultierende Dokument angewendet werden müssen.


**Returns:**
com.groupdocs.comparison.result.ChangeInfo[] - das Array der anzuwendenden Änderungen

### setChanges(ChangeInfo[] value) {#setChanges-com.groupdocs.comparison.result.ChangeInfo---}
```
public final void setChanges(ChangeInfo[] value)
```


Setzt ein Array von Änderungen, die auf das resultierende Dokument angewendet werden müssen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [ChangeInfo\[\]](../../com.groupdocs.comparison.result/changeinfo) | Das Array der anzuwendenden Änderungen |
|

### setChanges(List<ChangeInfo> value) {#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--}
```
public final void setChanges(List<ChangeInfo> value)
```


Setzt eine Liste von Änderungen, die auf das resultierende Dokument angewendet werden müssen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | java.util.List<com.groupdocs.comparison.result.ChangeInfo> | Die Liste der anzuwendenden Änderungen |
|

### isSaveOriginalState() {#isSaveOriginalState--}
```
public boolean isSaveOriginalState()
```


Liest ein Flag, das bestimmt, ob der Originalzustand gespeichert werden soll. Standardwert: false.


**Returns:**
boolean - true, wenn der Originalzustand gespeichert werden soll, sonst false

### setSaveOriginalState(boolean saveOriginalState) {#setSaveOriginalState-boolean-}
```
public void setSaveOriginalState(boolean saveOriginalState)
```


Setzt ein Flag, das bestimmt, ob der Originalzustand gespeichert werden soll.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | saveOriginalState | boolean | True, wenn der Originalzustand gespeichert werden soll, sonst false |
|

