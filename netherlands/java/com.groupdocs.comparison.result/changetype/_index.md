---
title: "ChangeType"
second_title: "GroupDocs.Comparison voor Java API-referentie"
description: "De ChangeType-enum vertegenwoordigt de soorten wijzigingen die kunnen optreden tijdens het documentvergelijkingsproces."
type: docs
weight: 14
url: /nl/java/com.groupdocs.comparison.result/changetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ChangeType extends Enum<ChangeType>
```

De ChangeType-enum vertegenwoordigt de soorten wijzigingen die kunnen optreden tijdens het documentvergelijkingsproces.


Elke constante in deze enum vertegenwoordigt een specifiek type wijziging en biedt een menselijk leesbare beschrijving en een numerieke waarde.


Voorbeeldgebruik:

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


## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [NONE](#NONE) | Geeft geen wijziging weer. |
|
|  | [MODIFIED](#MODIFIED) | Geeft een gewijzigde wijziging weer. |
|
|  | [INSERTED](#INSERTED) | Geeft een ingevoegde wijziging weer. |
|
|  | [DELETED](#DELETED) | Geeft een verwijderde wijziging weer. |
|
|  | [ADDED](#ADDED) | Geeft een toegevoegde wijziging weer. |
|
|  | [NOT_MODIFIED](#NOT-MODIFIED) | Geeft een niet-gewijzigde wijziging weer. |
|
|  | [STYLE_CHANGED](#STYLE-CHANGED) | Geeft een stijlgewijzigde wijziging weer. |
|
|  | [RESIZED](#RESIZED) | Stelt een wijziging voor die van grootte is veranderd. |
|
|  | [MOVED](#MOVED) | Stelt een verplaatste wijziging voor. |
|
|  | [MOVED_AND_RESIZED](#MOVED-AND-RESIZED) | Stelt een verplaatste en van grootte veranderde wijziging voor. |
|
|  | [SHIFTED_AND_RESIZED](#SHIFTED-AND-RESIZED) | Stelt een verschoven en van grootte veranderde wijziging voor. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Parseert de tekenreeksrepresentatie van ChangeType om de enum-constante te verkrijgen. |
|
|  | [fromInt(int intValue)](#fromInt-int-) | Maakt een nieuwe constante van de enum ChangeType met behulp van de opgegeven numerieke waarde. |
|
|  | [toString()](#toString--) | Tekenreeksrepresentatie van ChangeType. |
|
|  | [toInt()](#toInt--) | Numerieke representatie van ChangeType. |
|
### NONE {#NONE}
```
public static final ChangeType NONE
```


Geeft geen wijziging weer.


### MODIFIED {#MODIFIED}
```
public static final ChangeType MODIFIED
```


Geeft een gewijzigde wijziging weer.


### INSERTED {#INSERTED}
```
public static final ChangeType INSERTED
```


Geeft een ingevoegde wijziging weer.


### DELETED {#DELETED}
```
public static final ChangeType DELETED
```


Geeft een verwijderde wijziging weer.


### ADDED {#ADDED}
```
public static final ChangeType ADDED
```


Geeft een toegevoegde wijziging weer.


### NOT_MODIFIED {#NOT-MODIFIED}
```
public static final ChangeType NOT_MODIFIED
```


Geeft een niet-gewijzigde wijziging weer.


### STYLE_CHANGED {#STYLE-CHANGED}
```
public static final ChangeType STYLE_CHANGED
```


Geeft een stijlgewijzigde wijziging weer.


### RESIZED {#RESIZED}
```
public static final ChangeType RESIZED
```


Stelt een wijziging voor die van grootte is veranderd.


### MOVED {#MOVED}
```
public static final ChangeType MOVED
```


Stelt een verplaatste wijziging voor.


### MOVED_AND_RESIZED {#MOVED-AND-RESIZED}
```
public static final ChangeType MOVED_AND_RESIZED
```


Stelt een verplaatste en van grootte veranderde wijziging voor.


### SHIFTED_AND_RESIZED {#SHIFTED-AND-RESIZED}
```
public static final ChangeType SHIFTED_AND_RESIZED
```


Stelt een verschoven en van grootte veranderde wijziging voor.


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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String |  |

**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static ChangeType fromString(String toStringValue)
```


Parseert de tekenreeksrepresentatie van ChangeType om de enum-constante te verkrijgen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | toStringValue | java.lang.String | De tekenreeksrepresentatie van ChangeType |
|

**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - ChangeType enum constant associated with input string

### fromInt(int intValue) {#fromInt-int-}
```
public static ChangeType fromInt(int intValue)
```


Maakt een nieuwe constante van de enum ChangeType met behulp van de opgegeven numerieke waarde.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | intValue | int | De numerieke representatie van ChangeType |
|

**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - ChangeType enum constant associated with numeric value

### toString() {#toString--}
```
public String toString()
```


Tekenreeksrepresentatie van ChangeType.


**Returns:**
java.lang.String - tekenreekswaarde van enum-constante

### toInt() {#toInt--}
```
public int toInt()
```


Numerieke representatie van ChangeType.


**Returns:**
int - numerieke waarde van enum-constante

