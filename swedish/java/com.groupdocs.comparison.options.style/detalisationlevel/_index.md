---
title: "DetalisationLevel"
second_title: "GroupDocs.Comparison för Java API-referens"
description: "Anger detaljnivån för jämförelsen."
type: docs
weight: 13
url: /sv/java/com.groupdocs.comparison.options.style/detalisationlevel/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DetalisationLevel extends Enum<DetalisationLevel>
```

Anger detaljnivån för jämförelsen.


Exempel på användning:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setDetectStyleChanges(false);
    compareOptions.setDetalisationLevel(DetalisationLevel.HIGH);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [LOW](#LOW) | Representerar den låga jämförelsesnivån. |
|
|  | [MIDDLE](#MIDDLE) | Representerar den mellana jämförelsesnivån. |
|
|  | [HIGH](#HIGH) | Representerar den höga jämförelsesnivån. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Analyserar strängrepresentationen av DetalisationLevel för att få enum‑konstanten. |
|
|  | [toString()](#toString--) | Strängrepresentation av DetalisationLevel. |
|
### LOW {#LOW}
```
public static final DetalisationLevel LOW
```


Representerar den låga jämförelsesnivån.


Nivån "Low" ger den bästa hastigheten för jämförelser men offrar jämförelsens kvalitet.
Jämförelse utförs per ord.


### MIDDLE {#MIDDLE}
```
public static final DetalisationLevel MIDDLE
```


Representerar den mellana jämförelsesnivån.


Nivån "Middle" är en rimlig kompromiss mellan jämförelsens hastighet och kvalitet.
Jämförelse utförs per tecken, men ignorerar teckenkänslighet och mellanslag.


### HIGH {#HIGH}
```
public static final DetalisationLevel HIGH
```


Representerar den höga jämförelsesnivån.


Nivån "High" har den bästa jämförelseskvaliteten, men den lägsta hastigheten.
Jämförelse utförs per tecken med hänsyn till teckenkänslighet och mellanslag.


### values() {#values--}
```
public static DetalisationLevel[] values()
```




**Returns:**
com.groupdocs.comparison.options.style.DetalisationLevel[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static DetalisationLevel valueOf(String name)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String |  |

**Returns:**
[DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static DetalisationLevel fromString(String toStringValue)
```


Analyserar strängrepresentationen av DetalisationLevel för att få enum‑konstanten.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | toStringValue | java.lang.String | Strängrepresentationen av DetalisationLevel |
|

**Returns:**
[DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) - DetalisationLevel enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


Strängrepresentation av DetalisationLevel.


**Returns:**
java.lang.String - strängvärde av enum‑konstant

