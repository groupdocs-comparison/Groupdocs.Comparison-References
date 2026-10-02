---
title: "ComparisonType"
second_title: "GroupDocs.Comparison för Java API-referens"
description: "Representerar typen av jämförelse som ska utföras."
type: docs
weight: 10
url: /sv/java/com.groupdocs.comparison.options.enums/comparisontype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ComparisonType extends Enum<ComparisonType>
```

Representerar typen av jämförelse som ska utföras.


Exempel på användning:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setComparisonType(ComparisonType.CELLS);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [TEXT](#TEXT) | Filer måste jämföras som textdokument. |
|
|  | [SLIDES](#SLIDES) | Filer måste jämföras som presentationsdokument. |
|
|  | [WORDS](#WORDS) | Filer måste jämföras som Word-dokument. |
|
|  | [CELLS](#CELLS) | Filer måste jämföras som Excel-dokument. |
|
|  | [PDF](#PDF) | Filer måste jämföras som PDF-dokument. |
|
|  | [IMAGING](#IMAGING) | Filer måste jämföras som bilddokument. |
|
|  | [EMAIL](#EMAIL) | Filer måste jämföras som e‑postdokument. |
|
|  | [NOTE](#NOTE) | Filer måste jämföras som anteckningsdokument. |
|
|  | [HTML](#HTML) | Filer måste jämföras som HTML-dokument. |
|
|  | [DIAGRAM](#DIAGRAM) | Filer måste jämföras som diagramdokument. |
|
|  | [DIFFERENT](#DIFFERENT) | Filer måste jämföras som dokument i olika format. |
|
|  | [SVG](#SVG) | Filer måste jämföras som SVG-dokument. |
|
|  | [UNDEFINED](#UNDEFINED) | Endast för internt bruk. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Analyserar strängrepresentationen av ComparisonType för att få enum-konstanten. |
|
|  | [toString()](#toString--) | Strängrepresentation av ComparisonType. |
|
### TEXT {#TEXT}
```
public static final ComparisonType TEXT
```


Filer måste jämföras som textdokument.


### SLIDES {#SLIDES}
```
public static final ComparisonType SLIDES
```


Filer måste jämföras som presentationsdokument.


### WORDS {#WORDS}
```
public static final ComparisonType WORDS
```


Filer måste jämföras som Word-dokument.


### CELLS {#CELLS}
```
public static final ComparisonType CELLS
```


Filer måste jämföras som Excel-dokument.


### PDF {#PDF}
```
public static final ComparisonType PDF
```


Filer måste jämföras som PDF-dokument.


### IMAGING {#IMAGING}
```
public static final ComparisonType IMAGING
```


Filer måste jämföras som bilddokument.


### EMAIL {#EMAIL}
```
public static final ComparisonType EMAIL
```


Filer måste jämföras som e‑postdokument.


### NOTE {#NOTE}
```
public static final ComparisonType NOTE
```


Filer måste jämföras som anteckningsdokument.


### HTML {#HTML}
```
public static final ComparisonType HTML
```


Filer måste jämföras som HTML-dokument.


### DIAGRAM {#DIAGRAM}
```
public static final ComparisonType DIAGRAM
```


Filer måste jämföras som diagramdokument.


### DIFFERENT {#DIFFERENT}
```
public static final ComparisonType DIFFERENT
```


Filer måste jämföras som dokument i olika format.


### SVG {#SVG}
```
public static final ComparisonType SVG
```


Filer måste jämföras som SVG-dokument.


### UNDEFINED {#UNDEFINED}
```
public static final ComparisonType UNDEFINED
```


Endast för internt bruk.


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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String |  |

**Returns:**
[ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static ComparisonType fromString(String toStringValue)
```


Analyserar strängrepresentationen av ComparisonType för att få enum-konstanten.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | toStringValue | java.lang.String | Strängrepresentationen av ComparisonType |
|

**Returns:**
[ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) - ComparisonType enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


Strängrepresentation av ComparisonType.


**Returns:**
java.lang.String - strängvärde av enum‑konstant

