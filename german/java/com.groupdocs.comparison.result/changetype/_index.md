---
title: "ChangeType"
second_title: "GroupDocs.Comparison für Java API-Referenz"
description: "Das Enum ChangeType repräsentiert die Arten von Änderungen, die während des Dokumentenvergleichsprozesses auftreten können."
type: docs
weight: 14
url: /de/java/com.groupdocs.comparison.result/changetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ChangeType extends Enum<ChangeType>
```

Das Enum ChangeType repräsentiert die Arten von Änderungen, die während des Dokumentenvergleichsprozesses auftreten können.


Jede Konstante in diesem Enum repräsentiert einen bestimmten Änderungstyp und liefert eine menschenlesbare Beschreibung sowie einen numerischen Wert.


Beispielverwendung:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);
     comparer.compare();
     final ChangeInfo[] changes = comparer.getChanges();
     for (ChangeInfo changeInfo : changes) {
         // Get the ChangeType for a specific change
         final ChangeType changeType = changeInfo.getType();
         // Print the ChangeType information
         System.out.println("Description: " + changeType.toString());
         System.out.println("Value: " + changeType.toInt());
     }
 }
 
````


## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [NONE](#NONE) | Stellt keine Änderung dar. |
|
|  | [MODIFIED](#MODIFIED) | Stellt eine modifizierte Änderung dar. |
|
|  | [INSERTED](#INSERTED) | Stellt eine eingefügte Änderung dar. |
|
|  | [DELETED](#DELETED) | Stellt eine gelöschte Änderung dar. |
|
|  | [ADDED](#ADDED) | Stellt eine hinzugefügte Änderung dar. |
|
|  | [NOT_MODIFIED](#NOT-MODIFIED) | Stellt eine nicht modifizierte Änderung dar. |
|
|  | [STYLE_CHANGED](#STYLE-CHANGED) | Stellt eine stilgeänderte Änderung dar. |
|
|  | [RESIZED](#RESIZED) | Stellt eine Größenänderung dar. |
|
|  | [MOVED](#MOVED) | Stellt eine verschobene Änderung dar. |
|
|  | [MOVED_AND_RESIZED](#MOVED-AND-RESIZED) | Stellt eine verschobene und skalierte Änderung dar. |
|
|  | [SHIFTED_AND_RESIZED](#SHIFTED-AND-RESIZED) | Stellt eine verschobene und skalierte Änderung dar. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Parst die String-Darstellung von ChangeType, um die Enum-Konstante zu erhalten. |
|
|  | [fromInt(int intValue)](#fromInt-int-) | Erstellt eine neue Konstante des Enums ChangeType mit dem angegebenen numerischen Wert. |
|
|  | [toString()](#toString--) | String-Darstellung von ChangeType. |
|
|  | [toInt()](#toInt--) | Numerische Darstellung von ChangeType. |
|
### NONE {#NONE}
```
public static final ChangeType NONE
```


Stellt keine Änderung dar.


### MODIFIED {#MODIFIED}
```
public static final ChangeType MODIFIED
```


Stellt eine modifizierte Änderung dar.


### INSERTED {#INSERTED}
```
public static final ChangeType INSERTED
```


Stellt eine eingefügte Änderung dar.


### DELETED {#DELETED}
```
public static final ChangeType DELETED
```


Stellt eine gelöschte Änderung dar.


### ADDED {#ADDED}
```
public static final ChangeType ADDED
```


Stellt eine hinzugefügte Änderung dar.


### NOT_MODIFIED {#NOT-MODIFIED}
```
public static final ChangeType NOT_MODIFIED
```


Stellt eine nicht modifizierte Änderung dar.


### STYLE_CHANGED {#STYLE-CHANGED}
```
public static final ChangeType STYLE_CHANGED
```


Stellt eine stilgeänderte Änderung dar.


### RESIZED {#RESIZED}
```
public static final ChangeType RESIZED
```


Stellt eine Größenänderung dar.


### MOVED {#MOVED}
```
public static final ChangeType MOVED
```


Stellt eine verschobene Änderung dar.


### MOVED_AND_RESIZED {#MOVED-AND-RESIZED}
```
public static final ChangeType MOVED_AND_RESIZED
```


Stellt eine verschobene und skalierte Änderung dar.


### SHIFTED_AND_RESIZED {#SHIFTED-AND-RESIZED}
```
public static final ChangeType SHIFTED_AND_RESIZED
```


Stellt eine verschobene und skalierte Änderung dar.


### values() {#values--}
```
public static ChangeType[] values()
```




**Returns:**
com.groupdocs.comparison.result.ChangeType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static ChangeType valueOf(String name)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String |  |

**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static ChangeType fromString(String toStringValue)
```


Parst die String-Darstellung von ChangeType, um die Enum-Konstante zu erhalten.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | toStringValue | java.lang.String | Die String-Darstellung von ChangeType |
|

**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - ChangeType enum constant associated with input string

### fromInt(int intValue) {#fromInt-int-}
```
public static ChangeType fromInt(int intValue)
```


Erstellt eine neue Konstante des Enums ChangeType mit dem angegebenen numerischen Wert.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | intValue | int | Die numerische Darstellung von ChangeType |
|

**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - ChangeType enum constant associated with numeric value

### toString() {#toString--}
```
public String toString()
```


String-Darstellung von ChangeType.


**Returns:**
java.lang.String - String-Wert der Enum-Konstante

### toInt() {#toInt--}
```
public int toInt()
```


Numerische Darstellung von ChangeType.


**Returns:**
int - numerischer Wert der Enum-Konstante

