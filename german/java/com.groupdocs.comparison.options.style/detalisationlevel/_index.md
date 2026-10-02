---
title: "DetalisationLevel"
second_title: "GroupDocs.Comparison für Java API-Referenz"
description: "Gibt das Detailniveau des Vergleichs an."
type: docs
weight: 13
url: /de/java/com.groupdocs.comparison.options.style/detalisationlevel/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DetalisationLevel extends Enum<DetalisationLevel>
```

Gibt das Detailniveau des Vergleichs an.


Beispielverwendung:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setDetectStyleChanges(false);
    compareOptions.setDetalisationLevel(DetalisationLevel.HIGH);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [LOW](#LOW) | Stellt die niedrige Vergleichsebene dar. |
|
|  | [MIDDLE](#MIDDLE) | Stellt die mittlere Vergleichsebene dar. |
|
|  | [HIGH](#HIGH) | Stellt die hohe Vergleichsebene dar. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Parst die String-Darstellung von DetalisationLevel, um die Enum-Konstante zu erhalten. |
|
|  | [toString()](#toString--) | String-Darstellung von DetalisationLevel. |
|
### LOW {#LOW}
```
public static final DetalisationLevel LOW
```


Stellt die niedrige Vergleichsebene dar.


Die "Low"-Stufe bietet die höchste Geschwindigkeit für Vergleiche, opfert jedoch die Vergleichsqualität.
Der Vergleich wird wortweise durchgeführt.


### MIDDLE {#MIDDLE}
```
public static final DetalisationLevel MIDDLE
```


Stellt die mittlere Vergleichsebene dar.


Die "Middle"-Stufe ist ein vernünftiger Kompromiss zwischen Vergleichsgeschwindigkeit und -qualität.
Der Vergleich wird zeichenweise durchgeführt, jedoch ohne Berücksichtigung von Groß-/Kleinschreibung und Leerzeichen.


### HIGH {#HIGH}
```
public static final DetalisationLevel HIGH
```


Stellt die hohe Vergleichsebene dar.


Die "High"-Stufe bietet die beste Vergleichsqualität, jedoch die niedrigste Geschwindigkeit.
Der Vergleich wird zeichenweise durchgeführt, wobei Groß-/Kleinschreibung und Leerzeichen berücksichtigt werden.


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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String |  |

**Returns:**
[DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static DetalisationLevel fromString(String toStringValue)
```


Parst die String-Darstellung von DetalisationLevel, um die Enum-Konstante zu erhalten.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | toStringValue | java.lang.String | Die String-Darstellung von DetalisationLevel |
|

**Returns:**
[DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) - DetalisationLevel enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


String-Darstellung von DetalisationLevel.


**Returns:**
java.lang.String - String-Wert der Enum-Konstante

