---
title: "ComparisonAction"
second_title: "GroupDocs.Comparison für Java API-Referenz"
description: "Das Enum ComparisonAction stellt die Aktionen dar, die auf eine Änderung während des Dokumentenvergleichsprozesses angewendet werden können."
type: docs
weight: 15
url: /de/java/com.groupdocs.comparison.result/comparisonaction/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ComparisonAction extends Enum<ComparisonAction>
```

Das Enum ComparisonAction stellt die Aktionen dar, die auf eine Änderung während des Dokumentenvergleichsprozesses angewendet werden können.


Jede Konstante in diesem Enum repräsentiert eine bestimmte Aktion und liefert eine menschenlesbare Beschreibung sowie einen numerischen Wert.


Beispielverwendung:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);
     comparer.compare();

     final ChangeInfo[] changes = comparer.getChanges();
     for (ChangeInfo changeInfo : changes) {
         if (changeInfo.getId() % 2 == 0) {
             changeInfo.setComparisonAction(ComparisonAction.REJECT);
         }
     }
     comparer.applyChanges(resultFile, changes);
 }
 
````


## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [NONE](#NONE) | Stellt keine Aktion dar. |
|
|  | [ACCEPT](#ACCEPT) | Stellt eine Annahmeaktion dar. |
|
|  | [REJECT](#REJECT) | Stellt eine Ablehnungsaktion dar. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Parst die String-Darstellung von ComparisonAction, um die Enum-Konstante zu erhalten. |
|
|  | [fromInt(int intValue)](#fromInt-int-) | Erstellt eine neue Konstante des Enums ComparisonAction mit dem angegebenen numerischen Wert. |
|
|  | [toString()](#toString--) | String-Darstellung von ComparisonAction. |
|
|  | [toInt()](#toInt--) | Numerische Darstellung von ComparisonAction. |
|
### NONE {#NONE}
```
public static final ComparisonAction NONE
```


Stellt keine Aktion dar. Die Änderung hat keine Auswirkung.


### ACCEPT {#ACCEPT}
```
public static final ComparisonAction ACCEPT
```


Stellt eine Annahmeaktion dar. Die Änderung wird in der Ergebnisdatei sichtbar sein.


### REJECT {#REJECT}
```
public static final ComparisonAction REJECT
```


Stellt eine Ablehnungsaktion dar. Die Änderung wird in der Ergebnisdatei unsichtbar sein.


### values() {#values--}
```
public static ComparisonAction[] values()
```




**Returns:**
com.groupdocs.comparison.result.ComparisonAction[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static ComparisonAction valueOf(String name)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String |  |

**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static ComparisonAction fromString(String toStringValue)
```


Parst die String-Darstellung von ComparisonAction, um die Enum-Konstante zu erhalten.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | toStringValue | java.lang.String | Die String-Darstellung von ComparisonAction |
|

**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) - ComparisonAction enum constant associated with input string

### fromInt(int intValue) {#fromInt-int-}
```
public static ComparisonAction fromInt(int intValue)
```


Erstellt eine neue Konstante des Enums ComparisonAction mit dem angegebenen numerischen Wert.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | intValue | int | Die numerische Darstellung von ComparisonAction |
|

**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) - ComparisonAction enum constant associated with numeric value

### toString() {#toString--}
```
public String toString()
```


String-Darstellung von ComparisonAction.


**Returns:**
java.lang.String - String-Wert der Enum-Konstante

### toInt() {#toInt--}
```
public int toInt()
```


Numerische Darstellung von ComparisonAction.


**Returns:**
int - numerischer Wert der Enum-Konstante

