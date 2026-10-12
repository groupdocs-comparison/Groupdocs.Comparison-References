---
title: "PaperSize"
second_title: "GroupDocs.Comparison für Java API-Referenz"
description: "Stellt die Papiergrößenoptionen für den Dokumentvergleich dar."
type: docs
weight: 13
url: /de/java/com.groupdocs.comparison.options.enums/papersize/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PaperSize extends Enum<PaperSize>
```

Stellt die Papiergrößenoptionen für den Dokumentvergleich dar.


Beispielverwendung:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setPaperSize(PaperSize.A6);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [DEFAULT](#DEFAULT) | Standardpapiergröße. |
|
|  | [A0](#A0) | Standardpapiergröße A0 (841mm x 1189mm). |
|
|  | [A1](#A1) | Standardpapiergröße A1 (594mm x 841mm). |
|
|  | [A2](#A2) | Standardpapiergröße A2 (420mm x 594mm). |
|
|  | [A3](#A3) | Standardpapiergröße A3 (297mm x 420mm). |
|
|  | [A4](#A4) | Standardpapiergröße A4 (210mm x 297mm). |
|
|  | [A5](#A5) | Standardpapiergröße A5 (148mm x 210mm). |
|
|  | [A6](#A6) | Standardpapiergröße A6 (105mm x 148mm). |
|
|  | [A7](#A7) | Standardpapiergröße A7 (74mm x 105mm). |
|
|  | [A8](#A8) | Standardpapiergröße A8 (52mm x 74mm). |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Parst die String-Darstellung von PaperSize, um die Enum-Konstante zu erhalten. |
|
|  | [toString()](#toString--) | String-Darstellung von PaperSize. |
|
### DEFAULT {#DEFAULT}
```
public static final PaperSize DEFAULT
```


Standardpapiergröße.


### A0 {#A0}
```
public static final PaperSize A0
```


Standardpapiergröße A0 (841mm x 1189mm).


### A1 {#A1}
```
public static final PaperSize A1
```


Standardpapiergröße A1 (594mm x 841mm).


### A2 {#A2}
```
public static final PaperSize A2
```


Standardpapiergröße A2 (420mm x 594mm).


### A3 {#A3}
```
public static final PaperSize A3
```


Standardpapiergröße A3 (297mm x 420mm).


### A4 {#A4}
```
public static final PaperSize A4
```


Standardpapiergröße A4 (210mm x 297mm).


### A5 {#A5}
```
public static final PaperSize A5
```


Standardpapiergröße A5 (148mm x 210mm).


### A6 {#A6}
```
public static final PaperSize A6
```


Standardpapiergröße A6 (105mm x 148mm).


### A7 {#A7}
```
public static final PaperSize A7
```


Standardpapiergröße A7 (74mm x 105mm).


### A8 {#A8}
```
public static final PaperSize A8
```


Standardpapiergröße A8 (52mm x 74mm).


### values() {#values--}
```
public static PaperSize[] values()
```




**Returns:**
com.groupdocs.comparison.options.enums.PaperSize[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PaperSize valueOf(String name)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String |  |

**Returns:**
[PaperSize](../../com.groupdocs.comparison.options.enums/papersize)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static PaperSize fromString(String toStringValue)
```


Parst die String-Darstellung von PaperSize, um die Enum-Konstante zu erhalten.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | toStringValue | java.lang.String | Die String-Darstellung von PaperSize |
|

**Returns:**
[PaperSize](../../com.groupdocs.comparison.options.enums/papersize) - PaperSize enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


String-Darstellung von PaperSize.


**Returns:**
java.lang.String - String-Wert der Enum-Konstante

