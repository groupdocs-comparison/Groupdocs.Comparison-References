---
title: "ComparisonAction"
second_title: "GroupDocs.Comparison voor Java API-referentie"
description: "De ComparisonAction-enum vertegenwoordigt de acties die op een wijziging kunnen worden toegepast tijdens het documentvergelijkingsproces."
type: docs
weight: 15
url: /nl/java/com.groupdocs.comparison.result/comparisonaction/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ComparisonAction extends Enum<ComparisonAction>
```

De ComparisonAction-enum vertegenwoordigt de acties die op een wijziging kunnen worden toegepast tijdens het documentvergelijkingsproces.


Elke constante in deze enum vertegenwoordigt een specifieke actie en biedt een menselijk leesbare beschrijving en een numerieke waarde.


Voorbeeldgebruik:

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


## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [NONE](#NONE) | Geeft geen actie weer. |
|
|  | [ACCEPT](#ACCEPT) | Geeft een acceptactie weer. |
|
|  | [REJECT](#REJECT) | Geeft een afwijzingsactie weer. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Parseert de tekenreeksrepresentatie van ComparisonAction om de enum-constante te verkrijgen. |
|
|  | [fromInt(int intValue)](#fromInt-int-) | Maakt een nieuwe constante van enum ComparisonAction aan met behulp van de opgegeven numerieke waarde. |
|
|  | [toString()](#toString--) | Tekenreeksrepresentatie van ComparisonAction. |
|
|  | [toInt()](#toInt--) | Numerieke representatie van ComparisonAction. |
|
### NONE {#NONE}
```
public static final ComparisonAction NONE
```


Geeft geen actie weer. De wijziging heeft geen effect.


### ACCEPT {#ACCEPT}
```
public static final ComparisonAction ACCEPT
```


Geeft een acceptactie weer. De wijziging zal zichtbaar zijn in het resultaatbestand.


### REJECT {#REJECT}
```
public static final ComparisonAction REJECT
```


Geeft een afwijzingsactie weer. De wijziging zal onzichtbaar zijn in het resultaatbestand.


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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String |  |

**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static ComparisonAction fromString(String toStringValue)
```


Parseert de tekenreeksrepresentatie van ComparisonAction om de enum-constante te verkrijgen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | toStringValue | java.lang.String | De tekenreeksrepresentatie van ComparisonAction |
|

**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) - ComparisonAction enum constant associated with input string

### fromInt(int intValue) {#fromInt-int-}
```
public static ComparisonAction fromInt(int intValue)
```


Maakt een nieuwe constante van enum ComparisonAction aan met behulp van de opgegeven numerieke waarde.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | intValue | int | De numerieke representatie van ComparisonAction |
|

**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) - ComparisonAction enum constant associated with numeric value

### toString() {#toString--}
```
public String toString()
```


Tekenreeksrepresentatie van ComparisonAction.


**Returns:**
java.lang.String - tekenreekswaarde van enum-constante

### toInt() {#toInt--}
```
public int toInt()
```


Numerieke representatie van ComparisonAction.


**Returns:**
int - numerieke waarde van enum-constante

