---
title: "PaperSize"
second_title: "GroupDocs.Comparison voor Java API-referentie"
description: "Stelt de papierformaatopties voor documentvergelijking voor."
type: docs
weight: 13
url: /nl/java/com.groupdocs.comparison.options.enums/papersize/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PaperSize extends Enum<PaperSize>
```

Stelt de papierformaatopties voor documentvergelijking voor.


Voorbeeldgebruik:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setPaperSize(PaperSize.A6);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [DEFAULT](#DEFAULT) | Standaard papierformaat. |
|
|  | [A0](#A0) | Standaard papierformaat A0 (841mm x 1189mm). |
|
|  | [A1](#A1) | Standaard papierformaat A1 (594mm x 841mm). |
|
|  | [A2](#A2) | Standaard papierformaat A2 (420mm x 594mm). |
|
|  | [A3](#A3) | Standaard papierformaat A3 (297mm x 420mm). |
|
|  | [A4](#A4) | Standaard papierformaat A4 (210mm x 297mm). |
|
|  | [A5](#A5) | Standaard papierformaat A5 (148mm x 210mm). |
|
|  | [A6](#A6) | Standaard papierformaat A6 (105mm x 148mm). |
|
|  | [A7](#A7) | Standaard papierformaat A7 (74mm x 105mm). |
|
|  | [A8](#A8) | Standaard papierformaat A8 (52mm x 74mm). |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Parseert de tekenreeksrepresentatie van PaperSize om de enum-constante te verkrijgen. |
|
|  | [toString()](#toString--) | Tekenreeksrepresentatie van PaperSize. |
|
### DEFAULT {#DEFAULT}
```
public static final PaperSize DEFAULT
```


Standaard papierformaat.


### A0 {#A0}
```
public static final PaperSize A0
```


Standaard papierformaat A0 (841mm x 1189mm).


### A1 {#A1}
```
public static final PaperSize A1
```


Standaard papierformaat A1 (594mm x 841mm).


### A2 {#A2}
```
public static final PaperSize A2
```


Standaard papierformaat A2 (420mm x 594mm).


### A3 {#A3}
```
public static final PaperSize A3
```


Standaard papierformaat A3 (297mm x 420mm).


### A4 {#A4}
```
public static final PaperSize A4
```


Standaard papierformaat A4 (210mm x 297mm).


### A5 {#A5}
```
public static final PaperSize A5
```


Standaard papierformaat A5 (148mm x 210mm).


### A6 {#A6}
```
public static final PaperSize A6
```


Standaard papierformaat A6 (105mm x 148mm).


### A7 {#A7}
```
public static final PaperSize A7
```


Standaard papierformaat A7 (74mm x 105mm).


### A8 {#A8}
```
public static final PaperSize A8
```


Standaard papierformaat A8 (52mm x 74mm).


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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String |  |

**Returns:**
[PaperSize](../../com.groupdocs.comparison.options.enums/papersize)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static PaperSize fromString(String toStringValue)
```


Parseert de tekenreeksrepresentatie van PaperSize om de enum-constante te verkrijgen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | toStringValue | java.lang.String | De tekenreeksrepresentatie van PaperSize |
|

**Returns:**
[PaperSize](../../com.groupdocs.comparison.options.enums/papersize) - PaperSize enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


Tekenreeksrepresentatie van PaperSize.


**Returns:**
java.lang.String - tekenreekswaarde van enum-constante

