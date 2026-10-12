---
title: "StyleChangeInfo"
second_title: "GroupDocs.Comparison voor Java API-referentie"
description: "De StyleChangeInfo-klasse vertegenwoordigt informatie over een stijlwijziging in een vergeleken document."
type: docs
weight: 13
url: /nl/java/com.groupdocs.comparison.result/stylechangeinfo/
---
**Inheritance:**
java.lang.Object
```
public class StyleChangeInfo
```

De StyleChangeInfo-klasse vertegenwoordigt informatie over een stijlwijziging in een vergeleken document.


Het biedt details zoals de naam van de gewijzigde eigenschap, waarden vóór en na de wijziging, enzovoort.
Gebruik deze klasse om informatie op te halen over stijlwijzigingen tijdens het documentvergelijkingsproces.


Voorbeeldgebruik:

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


## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [StyleChangeInfo()](#StyleChangeInfo--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getPropertyName()](#getPropertyName--) | Haalt de naam op van de eigenschap die is gewijzigd. |
|
|  | [setPropertyName(String value)](#setPropertyName-java.lang.String-) | Stelt de naam in van de eigenschap die is gewijzigd. |
|
|  | [getNewValue()](#getNewValue--) | Haalt de nieuwe waarde van de eigenschap op. |
|
|  | [setNewValue(Object value)](#setNewValue-java.lang.Object-) | Stelt de nieuwe waarde van de eigenschap in. |
|
|  | [getOldValue()](#getOldValue--) | Haalt de oude waarde van de eigenschap op. |
|
|  | [setOldValue(Object value)](#setOldValue-java.lang.Object-) | Stelt de oude waarde van de eigenschap in. |
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


Haalt de naam op van de eigenschap die is gewijzigd.


**Returns:**
java.lang.String - de eigenschapsnaam

### setPropertyName(String value) {#setPropertyName-java.lang.String-}
```
public final void setPropertyName(String value)
```


Stelt de naam in van de eigenschap die is gewijzigd.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.lang.String | De eigenschapsnaam |
|

### getNewValue() {#getNewValue--}
```
public final Object getNewValue()
```


Haalt de nieuwe waarde van de eigenschap op.


**Returns:**
java.lang.Object - de nieuwe waarde van de eigenschap

### setNewValue(Object value) {#setNewValue-java.lang.Object-}
```
public final void setNewValue(Object value)
```


Stelt de nieuwe waarde van de eigenschap in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.lang.Object | De nieuwe waarde van de eigenschap |
|

### getOldValue() {#getOldValue--}
```
public final Object getOldValue()
```


Haalt de oude waarde van de eigenschap op.


**Returns:**
java.lang.Object - de oude waarde van de eigenschap

### setOldValue(Object value) {#setOldValue-java.lang.Object-}
```
public final void setOldValue(Object value)
```


Stelt de oude waarde van de eigenschap in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.lang.Object | De oude waarde van de eigenschap |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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
