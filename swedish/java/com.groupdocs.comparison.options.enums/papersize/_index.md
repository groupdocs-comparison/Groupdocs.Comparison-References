---
title: "PaperSize"
second_title: "GroupDocs.Comparison för Java API-referens"
description: "Representerar pappersstorleksalternativen för dokumentjämförelse."
type: docs
weight: 13
url: /sv/java/com.groupdocs.comparison.options.enums/papersize/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PaperSize extends Enum<PaperSize>
```

Representerar pappersstorleksalternativen för dokumentjämförelse.


Exempel på användning:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setPaperSize(PaperSize.A6);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [DEFAULT](#DEFAULT) | Standard pappersstorlek. |
|
|  | [A0](#A0) | Standard pappersstorlek A0 (841 mm x 1189 mm). |
|
|  | [A1](#A1) | Standard pappersstorlek A1 (594 mm x 841 mm). |
|
|  | [A2](#A2) | Standard pappersstorlek A2 (420 mm x 594 mm). |
|
|  | [A3](#A3) | Standard pappersstorlek A3 (297 mm x 420 mm). |
|
|  | [A4](#A4) | Standard pappersstorlek A4 (210 mm x 297 mm). |
|
|  | [A5](#A5) | Standard pappersstorlek A5 (148 mm x 210 mm). |
|
|  | [A6](#A6) | Standard pappersstorlek A6 (105 mm x 148 mm). |
|
|  | [A7](#A7) | Standard pappersstorlek A7 (74 mm x 105 mm). |
|
|  | [A8](#A8) | Standard pappersstorlek A8 (52 mm x 74 mm). |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Analyserar strängrepresentationen av PaperSize för att få enum‑konstanten. |
|
|  | [toString()](#toString--) | Strängrepresentation av PaperSize. |
|
### DEFAULT {#DEFAULT}
```
public static final PaperSize DEFAULT
```


Standard pappersstorlek.


### A0 {#A0}
```
public static final PaperSize A0
```


Standard pappersstorlek A0 (841 mm x 1189 mm).


### A1 {#A1}
```
public static final PaperSize A1
```


Standard pappersstorlek A1 (594 mm x 841 mm).


### A2 {#A2}
```
public static final PaperSize A2
```


Standard pappersstorlek A2 (420 mm x 594 mm).


### A3 {#A3}
```
public static final PaperSize A3
```


Standard pappersstorlek A3 (297 mm x 420 mm).


### A4 {#A4}
```
public static final PaperSize A4
```


Standard pappersstorlek A4 (210 mm x 297 mm).


### A5 {#A5}
```
public static final PaperSize A5
```


Standard pappersstorlek A5 (148 mm x 210 mm).


### A6 {#A6}
```
public static final PaperSize A6
```


Standard pappersstorlek A6 (105 mm x 148 mm).


### A7 {#A7}
```
public static final PaperSize A7
```


Standard pappersstorlek A7 (74 mm x 105 mm).


### A8 {#A8}
```
public static final PaperSize A8
```


Standard pappersstorlek A8 (52 mm x 74 mm).


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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String |  |

**Returns:**
[PaperSize](../../com.groupdocs.comparison.options.enums/papersize)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static PaperSize fromString(String toStringValue)
```


Analyserar strängrepresentationen av PaperSize för att få enum‑konstanten.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | toStringValue | java.lang.String | Strängrepresentationen av PaperSize |
|

**Returns:**
[PaperSize](../../com.groupdocs.comparison.options.enums/papersize) - PaperSize enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


Strängrepresentation av PaperSize.


**Returns:**
java.lang.String - strängvärde av enum‑konstant

