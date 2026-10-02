---
title: "ComparisonType"
second_title: "Referencia de API de GroupDocs.Comparison for Java"
description: "Representa el tipo de comparación que se realizará."
type: docs
weight: 10
url: /es/java/com.groupdocs.comparison.options.enums/comparisontype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ComparisonType extends Enum<ComparisonType>
```

Representa el tipo de comparación que se realizará.


Ejemplo de uso:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setComparisonType(ComparisonType.CELLS);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## Campos

| Campo | Descripción |
| --- | --- |
|  | [TEXT](#TEXT) | Los archivos deben compararse como documentos de texto. |
|
|  | [SLIDES](#SLIDES) | Los archivos deben compararse como documentos de presentación. |
|
|  | [WORDS](#WORDS) | Los archivos deben compararse como documentos de Word. |
|
|  | [CELLS](#CELLS) | Los archivos deben compararse como documentos de Excel. |
|
|  | [PDF](#PDF) | Los archivos deben compararse como documentos PDF. |
|
|  | [IMAGING](#IMAGING) | Los archivos deben compararse como documentos de imagen. |
|
|  | [EMAIL](#EMAIL) | Los archivos deben compararse como documentos de correo electrónico. |
|
|  | [NOTE](#NOTE) | Los archivos deben compararse como documentos de notas. |
|
|  | [HTML](#HTML) | Los archivos deben compararse como documentos HTML. |
|
|  | [DIAGRAM](#DIAGRAM) | Los archivos deben compararse como documentos de diagrama. |
|
|  | [DIFFERENT](#DIFFERENT) | Los archivos deben compararse como documentos en diferentes formatos. |
|
|  | [SVG](#SVG) | Los archivos deben compararse como documentos SVG. |
|
|  | [UNDEFINED](#UNDEFINED) | Para uso interno. |
|
## Métodos

| Método | Descripción |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Analiza la representación en cadena de ComparisonType para obtener la constante del enumerado. |
|
|  | [toString()](#toString--) | Representación en cadena de ComparisonType. |
|
### TEXT {#TEXT}
```
public static final ComparisonType TEXT
```


Los archivos deben compararse como documentos de texto.


### SLIDES {#SLIDES}
```
public static final ComparisonType SLIDES
```


Los archivos deben compararse como documentos de presentación.


### WORDS {#WORDS}
```
public static final ComparisonType WORDS
```


Los archivos deben compararse como documentos de Word.


### CELLS {#CELLS}
```
public static final ComparisonType CELLS
```


Los archivos deben compararse como documentos de Excel.


### PDF {#PDF}
```
public static final ComparisonType PDF
```


Los archivos deben compararse como documentos PDF.


### IMAGING {#IMAGING}
```
public static final ComparisonType IMAGING
```


Los archivos deben compararse como documentos de imagen.


### EMAIL {#EMAIL}
```
public static final ComparisonType EMAIL
```


Los archivos deben compararse como documentos de correo electrónico.


### NOTE {#NOTE}
```
public static final ComparisonType NOTE
```


Los archivos deben compararse como documentos de notas.


### HTML {#HTML}
```
public static final ComparisonType HTML
```


Los archivos deben compararse como documentos HTML.


### DIAGRAM {#DIAGRAM}
```
public static final ComparisonType DIAGRAM
```


Los archivos deben compararse como documentos de diagrama.


### DIFFERENT {#DIFFERENT}
```
public static final ComparisonType DIFFERENT
```


Los archivos deben compararse como documentos en diferentes formatos.


### SVG {#SVG}
```
public static final ComparisonType SVG
```


Los archivos deben compararse como documentos SVG.


### UNDEFINED {#UNDEFINED}
```
public static final ComparisonType UNDEFINED
```


Para uso interno.


### values() {#values--}
```
public static ComparisonType[] values()
```




**Returns:**
com.groupdocs.comparison.options.enums.ComparisonType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static ComparisonType valueOf(String name)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String |  |

**Returns:**
[ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static ComparisonType fromString(String toStringValue)
```


Analiza la representación en cadena de ComparisonType para obtener la constante del enumerado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | toStringValue | java.lang.String | La representación en cadena de ComparisonType |
|

**Returns:**
[ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) - ComparisonType enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


Representación en cadena de ComparisonType.


**Returns:**
java.lang.String - valor en cadena de la constante del enum

