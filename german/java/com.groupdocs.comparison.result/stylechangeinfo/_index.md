---
title: "StyleChangeInfo"
second_title: "GroupDocs.Comparison für Java API-Referenz"
description: "Die Klasse StyleChangeInfo stellt Informationen über eine Stiländerung in einem verglichenen Dokument dar."
type: docs
weight: 13
url: /de/java/com.groupdocs.comparison.result/stylechangeinfo/
---
**Inheritance:**
java.lang.Object
```
public class StyleChangeInfo
```

Die Klasse StyleChangeInfo stellt Informationen über eine Stiländerung in einem verglichenen Dokument dar.


Sie liefert Details wie den Namen der geänderten Eigenschaft, Werte vor und nach der Änderung usw.
Verwenden Sie diese Klasse, um Informationen über Stiländerungen während des Dokumentvergleichsprozesses abzurufen.


Beispielverwendung:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     comparer.compare();
     final ChangeInfo[] changes = comparer.getChanges();
     for (ChangeInfo change : changes) {
         // Access the style change information
         final List styleChanges = change.getStyleChanges();
         for (StyleChangeInfo styleChange : styleChanges) {
             // Print the style change information
             System.out.println("PropertyName: " + styleChange.getPropertyName());
             System.out.println("OldValue: " + styleChange.getOldValue());
             System.out.println("NewValue: " + styleChange.getNewValue());
         }
     }
 }
 
````


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [StyleChangeInfo()](#StyleChangeInfo--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getPropertyName()](#getPropertyName--) | Liefert den Namen der geänderten Eigenschaft. |
|
|  | [setPropertyName(String value)](#setPropertyName-java.lang.String-) | Setzt den Namen der geänderten Eigenschaft. |
|
|  | [getNewValue()](#getNewValue--) | Liefert den neuen Wert der Eigenschaft. |
|
|  | [setNewValue(Object value)](#setNewValue-java.lang.Object-) | Setzt den neuen Wert der Eigenschaft. |
|
|  | [getOldValue()](#getOldValue--) | Liefert den alten Wert der Eigenschaft. |
|
|  | [setOldValue(Object value)](#setOldValue-java.lang.Object-) | Setzt den alten Wert der Eigenschaft. |
|
|  | [equals(Object o)](#equals-java.lang.Object-) | {@inheritDoc} |
|
|  | [hashCode()](#hashCode--) | {@inheritDoc} |
|
### StyleChangeInfo() {#StyleChangeInfo--}
```
public StyleChangeInfo()
```


### getPropertyName() {#getPropertyName--}
```
public final String getPropertyName()
```


Liefert den Namen der geänderten Eigenschaft.


**Returns:**
java.lang.String - der Eigenschaftsname

### setPropertyName(String value) {#setPropertyName-java.lang.String-}
```
public final void setPropertyName(String value)
```


Setzt den Namen der geänderten Eigenschaft.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | java.lang.String | Der Eigenschaftsname |
|

### getNewValue() {#getNewValue--}
```
public final Object getNewValue()
```


Liefert den neuen Wert der Eigenschaft.


**Returns:**
java.lang.Object - der neue Wert der Eigenschaft

### setNewValue(Object value) {#setNewValue-java.lang.Object-}
```
public final void setNewValue(Object value)
```


Setzt den neuen Wert der Eigenschaft.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | java.lang.Object | Der neue Wert der Eigenschaft |
|

### getOldValue() {#getOldValue--}
```
public final Object getOldValue()
```


Liefert den alten Wert der Eigenschaft.


**Returns:**
java.lang.Object - der alte Wert der Eigenschaft

### setOldValue(Object value) {#setOldValue-java.lang.Object-}
```
public final void setOldValue(Object value)
```


Setzt den alten Wert der Eigenschaft.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | java.lang.Object | Der alte Wert der Eigenschaft |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| o | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
