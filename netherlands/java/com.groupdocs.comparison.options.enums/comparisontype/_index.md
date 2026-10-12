---
title: "ComparisonType"
second_title: "GroupDocs.Comparison voor Java API-referentie"
description: "Stelt het type vergelijking voor dat moet worden uitgevoerd."
type: docs
weight: 10
url: /nl/java/com.groupdocs.comparison.options.enums/comparisontype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ComparisonType extends Enum<ComparisonType>
```

Stelt het type vergelijking voor dat moet worden uitgevoerd.


Voorbeeldgebruik:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setComparisonType(ComparisonType.CELLS);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [TEXT](#TEXT) | Bestanden moeten worden vergeleken als tekstdocumenten. |
|
|  | [SLIDES](#SLIDES) | Bestanden moeten worden vergeleken als presentatiedocumenten. |
|
|  | [WORDS](#WORDS) | Bestanden moeten worden vergeleken als Word-documenten. |
|
|  | [CELLS](#CELLS) | Bestanden moeten worden vergeleken als Excel-documenten. |
|
|  | [PDF](#PDF) | Bestanden moeten worden vergeleken als PDF-documenten. |
|
|  | [IMAGING](#IMAGING) | Bestanden moeten worden vergeleken als afbeeldingsdocumenten. |
|
|  | [EMAIL](#EMAIL) | Bestanden moeten worden vergeleken als e-maildocumenten. |
|
|  | [NOTE](#NOTE) | Bestanden moeten worden vergeleken als notitiedocumenten. |
|
|  | [HTML](#HTML) | Bestanden moeten worden vergeleken als HTML-documenten. |
|
|  | [DIAGRAM](#DIAGRAM) | Bestanden moeten worden vergeleken als diagramdocumenten. |
|
|  | [DIFFERENT](#DIFFERENT) | Bestanden moeten worden vergeleken als documenten in verschillende formaten. |
|
|  | [SVG](#SVG) | Bestanden moeten worden vergeleken als SVG-documenten. |
|
|  | [UNDEFINED](#UNDEFINED) | Alleen voor intern gebruik. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Parseert de tekenreeksrepresentatie van ComparisonType om de enum-constante te verkrijgen. |
|
|  | [toString()](#toString--) | Tekenreeksrepresentatie van ComparisonType. |
|
### TEXT {#TEXT}
```
public static final ComparisonType TEXT
```


Bestanden moeten worden vergeleken als tekstdocumenten.


### SLIDES {#SLIDES}
```
public static final ComparisonType SLIDES
```


Bestanden moeten worden vergeleken als presentatiedocumenten.


### WORDS {#WORDS}
```
public static final ComparisonType WORDS
```


Bestanden moeten worden vergeleken als Word-documenten.


### CELLS {#CELLS}
```
public static final ComparisonType CELLS
```


Bestanden moeten worden vergeleken als Excel-documenten.


### PDF {#PDF}
```
public static final ComparisonType PDF
```


Bestanden moeten worden vergeleken als PDF-documenten.


### IMAGING {#IMAGING}
```
public static final ComparisonType IMAGING
```


Bestanden moeten worden vergeleken als afbeeldingsdocumenten.


### EMAIL {#EMAIL}
```
public static final ComparisonType EMAIL
```


Bestanden moeten worden vergeleken als e-maildocumenten.


### NOTE {#NOTE}
```
public static final ComparisonType NOTE
```


Bestanden moeten worden vergeleken als notitiedocumenten.


### HTML {#HTML}
```
public static final ComparisonType HTML
```


Bestanden moeten worden vergeleken als HTML-documenten.


### DIAGRAM {#DIAGRAM}
```
public static final ComparisonType DIAGRAM
```


Bestanden moeten worden vergeleken als diagramdocumenten.


### DIFFERENT {#DIFFERENT}
```
public static final ComparisonType DIFFERENT
```


Bestanden moeten worden vergeleken als documenten in verschillende formaten.


### SVG {#SVG}
```
public static final ComparisonType SVG
```


Bestanden moeten worden vergeleken als SVG-documenten.


### UNDEFINED {#UNDEFINED}
```
public static final ComparisonType UNDEFINED
```


Alleen voor intern gebruik.


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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String |  |

**Returns:**
[ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static ComparisonType fromString(String toStringValue)
```


Parseert de tekenreeksrepresentatie van ComparisonType om de enum-constante te verkrijgen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | toStringValue | java.lang.String | De tekenreeksrepresentatie van ComparisonType |
|

**Returns:**
[ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) - ComparisonType enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


Tekenreeksrepresentatie van ComparisonType.


**Returns:**
java.lang.String - tekenreekswaarde van enum-constante

