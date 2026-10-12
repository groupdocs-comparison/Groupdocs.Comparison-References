---
title: "PaperSize"
second_title: "Riferimento API di GroupDocs.Comparison per Java"
description: "Rappresenta le opzioni di formato carta per il confronto dei documenti."
type: docs
weight: 13
url: /it/java/com.groupdocs.comparison.options.enums/papersize/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PaperSize extends Enum<PaperSize>
```

Rappresenta le opzioni di formato carta per il confronto dei documenti.


Esempio di utilizzo:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setPaperSize(PaperSize.A6);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## Campi

| Campo | Descrizione |
| --- | --- |
|  | [DEFAULT](#DEFAULT) | Formato carta predefinito. |
|
|  | [A0](#A0) | Formato carta standard A0 (841 mm x 1189 mm). |
|
|  | [A1](#A1) | Formato carta standard A1 (594 mm x 841 mm). |
|
|  | [A2](#A2) | Formato carta standard A2 (420 mm x 594 mm). |
|
|  | [A3](#A3) | Formato carta standard A3 (297 mm x 420 mm). |
|
|  | [A4](#A4) | Formato carta standard A4 (210 mm x 297 mm). |
|
|  | [A5](#A5) | Formato carta standard A5 (148 mm x 210 mm). |
|
|  | [A6](#A6) | Formato carta standard A6 (105 mm x 148 mm). |
|
|  | [A7](#A7) | Formato carta standard A7 (74 mm x 105 mm). |
|
|  | [A8](#A8) | Formato carta standard A8 (52 mm x 74 mm). |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Analizza la rappresentazione stringa di PaperSize per ottenere la costante enum. |
|
|  | [toString()](#toString--) | Rappresentazione stringa di PaperSize. |
|
### DEFAULT {#DEFAULT}
```
public static final PaperSize DEFAULT
```


Formato carta predefinito.


### A0 {#A0}
```
public static final PaperSize A0
```


Formato carta standard A0 (841 mm x 1189 mm).


### A1 {#A1}
```
public static final PaperSize A1
```


Formato carta standard A1 (594 mm x 841 mm).


### A2 {#A2}
```
public static final PaperSize A2
```


Formato carta standard A2 (420 mm x 594 mm).


### A3 {#A3}
```
public static final PaperSize A3
```


Formato carta standard A3 (297 mm x 420 mm).


### A4 {#A4}
```
public static final PaperSize A4
```


Formato carta standard A4 (210 mm x 297 mm).


### A5 {#A5}
```
public static final PaperSize A5
```


Formato carta standard A5 (148 mm x 210 mm).


### A6 {#A6}
```
public static final PaperSize A6
```


Formato carta standard A6 (105 mm x 148 mm).


### A7 {#A7}
```
public static final PaperSize A7
```


Formato carta standard A7 (74 mm x 105 mm).


### A8 {#A8}
```
public static final PaperSize A8
```


Formato carta standard A8 (52 mm x 74 mm).


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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String |  |

**Returns:**
[PaperSize](../../com.groupdocs.comparison.options.enums/papersize)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static PaperSize fromString(String toStringValue)
```


Analizza la rappresentazione stringa di PaperSize per ottenere la costante enum.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | toStringValue | java.lang.String | La rappresentazione stringa di PaperSize |
|

**Returns:**
[PaperSize](../../com.groupdocs.comparison.options.enums/papersize) - PaperSize enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


Rappresentazione stringa di PaperSize.


**Returns:**
java.lang.String - valore stringa della costante dell'enumerazione

