---
title: "ChangeType"
second_title: "GroupDocs.Comparison för Java API-referens"
description: "Enumen ChangeType representerar de typer av ändringar som kan uppstå under dokumentjämförelseprocessen."
type: docs
weight: 14
url: /sv/java/com.groupdocs.comparison.result/changetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ChangeType extends Enum<ChangeType>
```

Enumen ChangeType representerar de typer av ändringar som kan uppstå under dokumentjämförelseprocessen.


Varje konstant i den här enumen representerar en specifik typ av förändring och ger en människoläsbar beskrivning samt ett numeriskt värde.


Exempel på användning:

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


## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [NONE](#NONE) | Representerar ingen förändring. |
|
|  | [MODIFIED](#MODIFIED) | Representerar en modifierad förändring. |
|
|  | [INSERTED](#INSERTED) | Representerar en insatt förändring. |
|
|  | [DELETED](#DELETED) | Representerar en borttagen förändring. |
|
|  | [ADDED](#ADDED) | Representerar en tillagd förändring. |
|
|  | [NOT_MODIFIED](#NOT-MODIFIED) | Representerar en oförändrad förändring. |
|
|  | [STYLE_CHANGED](#STYLE-CHANGED) | Representerar en stiländrad förändring. |
|
|  | [RESIZED](#RESIZED) | Representerar en storleksändrad förändring. |
|
|  | [MOVED](#MOVED) | Representerar en flyttad förändring. |
|
|  | [MOVED_AND_RESIZED](#MOVED-AND-RESIZED) | Representerar en flyttad och storleksändrad förändring. |
|
|  | [SHIFTED_AND_RESIZED](#SHIFTED-AND-RESIZED) | Representerar en förskjuten och storleksändrad förändring. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Analyserar strängrepresentationen av ChangeType för att få enum‑konstanten. |
|
|  | [fromInt(int intValue)](#fromInt-int-) | Skapar en ny konstant av enum ChangeType med det angivna numeriska värdet. |
|
|  | [toString()](#toString--) | Strängrepresentation av ChangeType. |
|
|  | [toInt()](#toInt--) | Numerisk representation av ChangeType. |
|
### NONE {#NONE}
```
public static final ChangeType NONE
```


Representerar ingen förändring.


### MODIFIED {#MODIFIED}
```
public static final ChangeType MODIFIED
```


Representerar en modifierad förändring.


### INSERTED {#INSERTED}
```
public static final ChangeType INSERTED
```


Representerar en insatt förändring.


### DELETED {#DELETED}
```
public static final ChangeType DELETED
```


Representerar en borttagen förändring.


### ADDED {#ADDED}
```
public static final ChangeType ADDED
```


Representerar en tillagd förändring.


### NOT_MODIFIED {#NOT-MODIFIED}
```
public static final ChangeType NOT_MODIFIED
```


Representerar en oförändrad förändring.


### STYLE_CHANGED {#STYLE-CHANGED}
```
public static final ChangeType STYLE_CHANGED
```


Representerar en stiländrad förändring.


### RESIZED {#RESIZED}
```
public static final ChangeType RESIZED
```


Representerar en storleksändrad förändring.


### MOVED {#MOVED}
```
public static final ChangeType MOVED
```


Representerar en flyttad förändring.


### MOVED_AND_RESIZED {#MOVED-AND-RESIZED}
```
public static final ChangeType MOVED_AND_RESIZED
```


Representerar en flyttad och storleksändrad förändring.


### SHIFTED_AND_RESIZED {#SHIFTED-AND-RESIZED}
```
public static final ChangeType SHIFTED_AND_RESIZED
```


Representerar en förskjuten och storleksändrad förändring.


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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String |  |

**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static ChangeType fromString(String toStringValue)
```


Analyserar strängrepresentationen av ChangeType för att få enum‑konstanten.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | toStringValue | java.lang.String | Strängrepresentationen av ChangeType |
|

**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - ChangeType enum constant associated with input string

### fromInt(int intValue) {#fromInt-int-}
```
public static ChangeType fromInt(int intValue)
```


Skapar en ny konstant av enum ChangeType med det angivna numeriska värdet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | intValue | int | Den numeriska representationen av ChangeType |
|

**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - ChangeType enum constant associated with numeric value

### toString() {#toString--}
```
public String toString()
```


Strängrepresentation av ChangeType.


**Returns:**
java.lang.String - strängvärde av enum‑konstant

### toInt() {#toInt--}
```
public int toInt()
```


Numerisk representation av ChangeType.


**Returns:**
int - numeriskt värde av enum‑konstant

