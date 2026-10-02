---
title: "ComparisonType"
second_title: "GroupDocs.Comparison für Java API-Referenz"
description: "Stellt den Typ des durchzuführenden Vergleichs dar."
type: docs
weight: 10
url: /de/java/com.groupdocs.comparison.options.enums/comparisontype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ComparisonType extends Enum<ComparisonType>
```

Stellt den Typ des durchzuführenden Vergleichs dar.


Beispielverwendung:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setComparisonType(ComparisonType.CELLS);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [TEXT](#TEXT) | Dateien müssen als Textdokumente verglichen werden. |
|
|  | [SLIDES](#SLIDES) | Dateien müssen als Präsentationsdokumente verglichen werden. |
|
|  | [WORDS](#WORDS) | Dateien müssen als Word-Dokumente verglichen werden. |
|
|  | [CELLS](#CELLS) | Dateien müssen als Excel-Dokumente verglichen werden. |
|
|  | [PDF](#PDF) | Dateien müssen als PDF-Dokumente verglichen werden. |
|
|  | [IMAGING](#IMAGING) | Dateien müssen als Bilddokumente verglichen werden. |
|
|  | [EMAIL](#EMAIL) | Dateien müssen als E-Mail-Dokumente verglichen werden. |
|
|  | [NOTE](#NOTE) | Dateien müssen als Notizdokumente verglichen werden. |
|
|  | [HTML](#HTML) | Dateien müssen als HTML-Dokumente verglichen werden. |
|
|  | [DIAGRAM](#DIAGRAM) | Dateien müssen als Diagrammdokumente verglichen werden. |
|
|  | [DIFFERENT](#DIFFERENT) | Dateien müssen als Dokumente in verschiedenen Formaten verglichen werden. |
|
|  | [SVG](#SVG) | Dateien müssen als SVG-Dokumente verglichen werden. |
|
|  | [UNDEFINED](#UNDEFINED) | Zur internen Verwendung. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Parst die Zeichenkettenrepräsentation von ComparisonType, um die Enum-Konstante zu erhalten. |
|
|  | [toString()](#toString--) | Zeichenkettenrepräsentation von ComparisonType. |
|
### TEXT {#TEXT}
```
public static final ComparisonType TEXT
```


Dateien müssen als Textdokumente verglichen werden.


### SLIDES {#SLIDES}
```
public static final ComparisonType SLIDES
```


Dateien müssen als Präsentationsdokumente verglichen werden.


### WORDS {#WORDS}
```
public static final ComparisonType WORDS
```


Dateien müssen als Word-Dokumente verglichen werden.


### CELLS {#CELLS}
```
public static final ComparisonType CELLS
```


Dateien müssen als Excel-Dokumente verglichen werden.


### PDF {#PDF}
```
public static final ComparisonType PDF
```


Dateien müssen als PDF-Dokumente verglichen werden.


### IMAGING {#IMAGING}
```
public static final ComparisonType IMAGING
```


Dateien müssen als Bilddokumente verglichen werden.


### EMAIL {#EMAIL}
```
public static final ComparisonType EMAIL
```


Dateien müssen als E-Mail-Dokumente verglichen werden.


### NOTE {#NOTE}
```
public static final ComparisonType NOTE
```


Dateien müssen als Notizdokumente verglichen werden.


### HTML {#HTML}
```
public static final ComparisonType HTML
```


Dateien müssen als HTML-Dokumente verglichen werden.


### DIAGRAM {#DIAGRAM}
```
public static final ComparisonType DIAGRAM
```


Dateien müssen als Diagrammdokumente verglichen werden.


### DIFFERENT {#DIFFERENT}
```
public static final ComparisonType DIFFERENT
```


Dateien müssen als Dokumente in verschiedenen Formaten verglichen werden.


### SVG {#SVG}
```
public static final ComparisonType SVG
```


Dateien müssen als SVG-Dokumente verglichen werden.


### UNDEFINED {#UNDEFINED}
```
public static final ComparisonType UNDEFINED
```


Zur internen Verwendung.


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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String |  |

**Returns:**
[ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static ComparisonType fromString(String toStringValue)
```


Parst die Zeichenkettenrepräsentation von ComparisonType, um die Enum-Konstante zu erhalten.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | toStringValue | java.lang.String | Die Zeichenkettenrepräsentation von ComparisonType |
|

**Returns:**
[ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) - ComparisonType enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


Zeichenkettenrepräsentation von ComparisonType.


**Returns:**
java.lang.String - String-Wert der Enum-Konstante

