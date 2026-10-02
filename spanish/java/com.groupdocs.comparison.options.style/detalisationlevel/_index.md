---
title: "DetalisationLevel"
second_title: "Referencia de API de GroupDocs.Comparison for Java"
description: "Especifica el nivel de detalle de la comparación."
type: docs
weight: 13
url: /es/java/com.groupdocs.comparison.options.style/detalisationlevel/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DetalisationLevel extends Enum<DetalisationLevel>
```

Especifica el nivel de detalle de la comparación.


Ejemplo de uso:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setDetectStyleChanges(false);
    compareOptions.setDetalisationLevel(DetalisationLevel.HIGH);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## Campos

| Campo | Descripción |
| --- | --- |
|  | [LOW](#LOW) | Representa el nivel bajo de comparación. |
|
|  | [MIDDLE](#MIDDLE) | Representa el nivel medio de comparación. |
|
|  | [HIGH](#HIGH) | Representa el nivel alto de comparación. |
|
## Métodos

| Método | Descripción |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Analiza la representación en cadena de DetalisationLevel para obtener la constante del enum. |
|
|  | [toString()](#toString--) | Representación en cadena de DetalisationLevel. |
|
### LOW {#LOW}
```
public static final DetalisationLevel LOW
```


Representa el nivel bajo de comparación.


El nivel "Low" ofrece la mejor velocidad para comparaciones pero sacrifica la calidad de la comparación.
La comparación se realiza por palabra.


### MIDDLE {#MIDDLE}
```
public static final DetalisationLevel MIDDLE
```


Representa el nivel medio de comparación.


El nivel "Middle" es un compromiso razonable entre la velocidad y la calidad de la comparación.
La comparación se realiza por carácter, pero ignorando mayúsculas y minúsculas y el recuento de espacios.


### HIGH {#HIGH}
```
public static final DetalisationLevel HIGH
```


Representa el nivel alto de comparación.


El nivel "High" ofrece la mejor calidad de comparación, pero la velocidad más baja.
La comparación se realiza por carácter considerando mayúsculas y minúsculas y el recuento de espacios.


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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String |  |

**Returns:**
[DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static DetalisationLevel fromString(String toStringValue)
```


Analiza la representación en cadena de DetalisationLevel para obtener la constante del enum.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | toStringValue | java.lang.String | La representación en cadena de DetalisationLevel |
|

**Returns:**
[DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) - DetalisationLevel enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


Representación en cadena de DetalisationLevel.


**Returns:**
java.lang.String - valor en cadena de la constante del enum

