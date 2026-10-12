---
title: "DetalisationLevel"
second_title: "GroupDocs.Comparison voor Java API-referentie"
description: "Specificeert het detailniveau van de vergelijking."
type: docs
weight: 13
url: /nl/java/com.groupdocs.comparison.options.style/detalisationlevel/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DetalisationLevel extends Enum<DetalisationLevel>
```

Specificeert het detailniveau van de vergelijking.


Voorbeeldgebruik:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setDetectStyleChanges(false);
    compareOptions.setDetalisationLevel(DetalisationLevel.HIGH);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [LOW](#LOW) | Stelt het lage vergelijkingsniveau voor. |
|
|  | [MIDDLE](#MIDDLE) | Stelt het middelmatige vergelijkingsniveau voor. |
|
|  | [HIGH](#HIGH) | Stelt het hoge vergelijkingsniveau voor. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Parseert de tekenreeksrepresentatie van DetalisationLevel om de enum-constante te verkrijgen. |
|
|  | [toString()](#toString--) | Stringrepresentatie van DetalisationLevel. |
|
### LOW {#LOW}
```
public static final DetalisationLevel LOW
```


Stelt het lage vergelijkingsniveau voor.


Het "Low"-niveau biedt de beste snelheid voor vergelijkingen, maar schaadt de vergelijkingskwaliteit.
Vergelijking wordt per woord uitgevoerd.


### MIDDLE {#MIDDLE}
```
public static final DetalisationLevel MIDDLE
```


Stelt het middelmatige vergelijkingsniveau voor.


Het "Middle"-niveau is een redelijk compromis tussen vergelijkingssnelheid en kwaliteit.
Vergelijking wordt per teken uitgevoerd, maar negeert hoofdlettergevoeligheid en spaties.


### HIGH {#HIGH}
```
public static final DetalisationLevel HIGH
```


Stelt het hoge vergelijkingsniveau voor.


Het "High"-niveau biedt de beste vergelijkingskwaliteit, maar de laagste snelheid.
Vergelijking wordt per teken uitgevoerd, rekening houdend met hoofdlettergevoeligheid en spaties.


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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String |  |

**Returns:**
[DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static DetalisationLevel fromString(String toStringValue)
```


Parseert de tekenreeksrepresentatie van DetalisationLevel om de enum-constante te verkrijgen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | toStringValue | java.lang.String | De stringrepresentatie van DetalisationLevel |
|

**Returns:**
[DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) - DetalisationLevel enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


Stringrepresentatie van DetalisationLevel.


**Returns:**
java.lang.String - tekenreekswaarde van enum-constante

