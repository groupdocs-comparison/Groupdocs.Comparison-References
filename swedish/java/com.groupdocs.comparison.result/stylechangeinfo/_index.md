---
title: "StyleChangeInfo"
second_title: "GroupDocs.Comparison för Java API-referens"
description: "Klassen StyleChangeInfo representerar information om en stiländring i ett jämfört dokument."
type: docs
weight: 13
url: /sv/java/com.groupdocs.comparison.result/stylechangeinfo/
---
**Inheritance:**
java.lang.Object
```
public class StyleChangeInfo
```

Klassen StyleChangeInfo representerar information om en stiländring i ett jämfört dokument.


Den tillhandahåller detaljer såsom det ändrade egenskapsnamnet, värden före och efter ändringen, med mera.
Använd den här klassen för att hämta information om stiländringar under dokumentjämförelseprocessen.


Exempel på användning:

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


## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [StyleChangeInfo()](#StyleChangeInfo--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getPropertyName()](#getPropertyName--) | Hämtar namnet på den egenskap som ändrades. |
|
|  | [setPropertyName(String value)](#setPropertyName-java.lang.String-) | Ställer in namnet på den egenskap som ändrades. |
|
|  | [getNewValue()](#getNewValue--) | Hämtar det nya värdet på egenskapen. |
|
|  | [setNewValue(Object value)](#setNewValue-java.lang.Object-) | Ställer in det nya värdet på egenskapen. |
|
|  | [getOldValue()](#getOldValue--) | Hämtar det gamla värdet på egenskapen. |
|
|  | [setOldValue(Object value)](#setOldValue-java.lang.Object-) | Ställer in det gamla värdet på egenskapen. |
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


Hämtar namnet på den egenskap som ändrades.


**Returns:**
java.lang.String - egenskapsnamnet

### setPropertyName(String value) {#setPropertyName-java.lang.String-}
```
public final void setPropertyName(String value)
```


Ställer in namnet på den egenskap som ändrades.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | java.lang.String | Egenskapsnamnet |
|

### getNewValue() {#getNewValue--}
```
public final Object getNewValue()
```


Hämtar det nya värdet på egenskapen.


**Returns:**
java.lang.Object - det nya värdet på egenskapen

### setNewValue(Object value) {#setNewValue-java.lang.Object-}
```
public final void setNewValue(Object value)
```


Ställer in det nya värdet på egenskapen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | java.lang.Object | Det nya värdet på egenskapen |
|

### getOldValue() {#getOldValue--}
```
public final Object getOldValue()
```


Hämtar det gamla värdet på egenskapen.


**Returns:**
java.lang.Object - det gamla värdet på egenskapen

### setOldValue(Object value) {#setOldValue-java.lang.Object-}
```
public final void setOldValue(Object value)
```


Ställer in det gamla värdet på egenskapen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | java.lang.Object | Det gamla värdet på egenskapen |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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
