---
title: "ComparisonAction"
second_title: "GroupDocs.Comparison för Java API-referens"
description: "Enumen ComparisonAction representerar de åtgärder som kan tillämpas på en ändring under dokumentjämförelseprocessen."
type: docs
weight: 15
url: /sv/java/com.groupdocs.comparison.result/comparisonaction/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ComparisonAction extends Enum<ComparisonAction>
```

Enumen ComparisonAction representerar de åtgärder som kan tillämpas på en ändring under dokumentjämförelseprocessen.


Varje konstant i den här enumen representerar en specifik åtgärd och ger en människoläsbar beskrivning samt ett numeriskt värde.


Exempel på användning:

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


## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [NONE](#NONE) | Representerar ingen åtgärd. |
|
|  | [ACCEPT](#ACCEPT) | Representerar en accepteringsåtgärd. |
|
|  | [REJECT](#REJECT) | Representerar en avvisningsåtgärd. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Analyserar strängrepresentationen av ComparisonAction för att få enum‑konstanten. |
|
|  | [fromInt(int intValue)](#fromInt-int-) | Skapar en ny konstant av enum ComparisonAction med hjälp av det angivna numeriska värdet. |
|
|  | [toString()](#toString--) | Strängrepresentation av ComparisonAction. |
|
|  | [toInt()](#toInt--) | Numerisk representation av ComparisonAction. |
|
### NONE {#NONE}
```
public static final ComparisonAction NONE
```


Representerar ingen åtgärd. Ändringen kommer inte att ha någon effekt.


### ACCEPT {#ACCEPT}
```
public static final ComparisonAction ACCEPT
```


Representerar en accepteringsåtgärd. Ändringen kommer att vara synlig i resultatfilen.


### REJECT {#REJECT}
```
public static final ComparisonAction REJECT
```


Representerar en avvisningsåtgärd. Ändringen kommer att vara osynlig i resultatfilen.


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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String |  |

**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static ComparisonAction fromString(String toStringValue)
```


Analyserar strängrepresentationen av ComparisonAction för att få enum‑konstanten.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | toStringValue | java.lang.String | Strängrepresentationen av ComparisonAction |
|

**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) - ComparisonAction enum constant associated with input string

### fromInt(int intValue) {#fromInt-int-}
```
public static ComparisonAction fromInt(int intValue)
```


Skapar en ny konstant av enum ComparisonAction med hjälp av det angivna numeriska värdet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | intValue | int | Den numeriska representationen av ComparisonAction |
|

**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) - ComparisonAction enum constant associated with numeric value

### toString() {#toString--}
```
public String toString()
```


Strängrepresentation av ComparisonAction.


**Returns:**
java.lang.String - strängvärde av enum‑konstant

### toInt() {#toInt--}
```
public int toInt()
```


Numerisk representation av ComparisonAction.


**Returns:**
int - numeriskt värde av enum‑konstant

