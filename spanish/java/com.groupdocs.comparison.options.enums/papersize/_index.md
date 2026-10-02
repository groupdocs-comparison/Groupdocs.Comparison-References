---
title: "PaperSize"
second_title: "Referencia de API de GroupDocs.Comparison for Java"
description: "Representa las opciones de tamaño de papel para la comparación de documentos."
type: docs
weight: 13
url: /es/java/com.groupdocs.comparison.options.enums/papersize/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PaperSize extends Enum<PaperSize>
```

Representa las opciones de tamaño de papel para la comparación de documentos.


Ejemplo de uso:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setPaperSize(PaperSize.A6);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## Campos

| Campo | Descripción |
| --- | --- |
|  | [DEFAULT](#DEFAULT) | Tamaño de papel predeterminado. |
|
|  | [A0](#A0) | Tamaño de papel estándar A0 (841 mm x 1189 mm). |
|
|  | [A1](#A1) | Tamaño de papel estándar A1 (594 mm x 841 mm). |
|
|  | [A2](#A2) | Tamaño de papel estándar A2 (420 mm x 594 mm). |
|
|  | [A3](#A3) | Tamaño de papel estándar A3 (297 mm x 420 mm). |
|
|  | [A4](#A4) | Tamaño de papel estándar A4 (210 mm x 297 mm). |
|
|  | [A5](#A5) | Tamaño de papel estándar A5 (148 mm x 210 mm). |
|
|  | [A6](#A6) | Tamaño de papel estándar A6 (105 mm x 148 mm). |
|
|  | [A7](#A7) | Tamaño de papel estándar A7 (74 mm x 105 mm). |
|
|  | [A8](#A8) | Tamaño de papel estándar A8 (52 mm x 74 mm). |
|
## Métodos

| Método | Descripción |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Analiza la representación en cadena de PaperSize para obtener la constante enum. |
|
|  | [toString()](#toString--) | Representación en cadena de PaperSize. |
|
### DEFAULT {#DEFAULT}
```
public static final PaperSize DEFAULT
```


Tamaño de papel predeterminado.


### A0 {#A0}
```
public static final PaperSize A0
```


Tamaño de papel estándar A0 (841 mm x 1189 mm).


### A1 {#A1}
```
public static final PaperSize A1
```


Tamaño de papel estándar A1 (594 mm x 841 mm).


### A2 {#A2}
```
public static final PaperSize A2
```


Tamaño de papel estándar A2 (420 mm x 594 mm).


### A3 {#A3}
```
public static final PaperSize A3
```


Tamaño de papel estándar A3 (297 mm x 420 mm).


### A4 {#A4}
```
public static final PaperSize A4
```


Tamaño de papel estándar A4 (210 mm x 297 mm).


### A5 {#A5}
```
public static final PaperSize A5
```


Tamaño de papel estándar A5 (148 mm x 210 mm).


### A6 {#A6}
```
public static final PaperSize A6
```


Tamaño de papel estándar A6 (105 mm x 148 mm).


### A7 {#A7}
```
public static final PaperSize A7
```


Tamaño de papel estándar A7 (74 mm x 105 mm).


### A8 {#A8}
```
public static final PaperSize A8
```


Tamaño de papel estándar A8 (52 mm x 74 mm).


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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String |  |

**Returns:**
[PaperSize](../../com.groupdocs.comparison.options.enums/papersize)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static PaperSize fromString(String toStringValue)
```


Analiza la representación en cadena de PaperSize para obtener la constante enum.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | toStringValue | java.lang.String | La representación en cadena de PaperSize |
|

**Returns:**
[PaperSize](../../com.groupdocs.comparison.options.enums/papersize) - PaperSize enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


Representación en cadena de PaperSize.


**Returns:**
java.lang.String - valor en cadena de la constante del enum

