---
title: "ComparisonType"
second_title: "Riferimento API di GroupDocs.Comparison per Java"
description: "Rappresenta il tipo di confronto da eseguire."
type: docs
weight: 10
url: /it/java/com.groupdocs.comparison.options.enums/comparisontype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ComparisonType extends Enum<ComparisonType>
```

Rappresenta il tipo di confronto da eseguire.


Esempio di utilizzo:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setComparisonType(ComparisonType.CELLS);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## Campi

| Campo | Descrizione |
| --- | --- |
|  | [TEXT](#TEXT) | I file devono essere confrontati come documenti di testo. |
|
|  | [SLIDES](#SLIDES) | I file devono essere confrontati come documenti di presentazione. |
|
|  | [WORDS](#WORDS) | I file devono essere confrontati come documenti Word. |
|
|  | [CELLS](#CELLS) | I file devono essere confrontati come documenti Excel. |
|
|  | [PDF](#PDF) | I file devono essere confrontati come documenti PDF. |
|
|  | [IMAGING](#IMAGING) | I file devono essere confrontati come documenti immagine. |
|
|  | [EMAIL](#EMAIL) | I file devono essere confrontati come documenti email. |
|
|  | [NOTE](#NOTE) | I file devono essere confrontati come documenti di note. |
|
|  | [HTML](#HTML) | I file devono essere confrontati come documenti HTML. |
|
|  | [DIAGRAM](#DIAGRAM) | I file devono essere confrontati come documenti diagramma. |
|
|  | [DIFFERENT](#DIFFERENT) | I file devono essere confrontati come documenti in formati diversi. |
|
|  | [SVG](#SVG) | I file devono essere confrontati come documenti SVG. |
|
|  | [UNDEFINED](#UNDEFINED) | Per uso interno. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Analizza la rappresentazione stringa di ComparisonType per ottenere la costante enum. |
|
|  | [toString()](#toString--) | Rappresentazione stringa di ComparisonType. |
|
### TEXT {#TEXT}
```
public static final ComparisonType TEXT
```


I file devono essere confrontati come documenti di testo.


### SLIDES {#SLIDES}
```
public static final ComparisonType SLIDES
```


I file devono essere confrontati come documenti di presentazione.


### WORDS {#WORDS}
```
public static final ComparisonType WORDS
```


I file devono essere confrontati come documenti Word.


### CELLS {#CELLS}
```
public static final ComparisonType CELLS
```


I file devono essere confrontati come documenti Excel.


### PDF {#PDF}
```
public static final ComparisonType PDF
```


I file devono essere confrontati come documenti PDF.


### IMAGING {#IMAGING}
```
public static final ComparisonType IMAGING
```


I file devono essere confrontati come documenti immagine.


### EMAIL {#EMAIL}
```
public static final ComparisonType EMAIL
```


I file devono essere confrontati come documenti email.


### NOTE {#NOTE}
```
public static final ComparisonType NOTE
```


I file devono essere confrontati come documenti di note.


### HTML {#HTML}
```
public static final ComparisonType HTML
```


I file devono essere confrontati come documenti HTML.


### DIAGRAM {#DIAGRAM}
```
public static final ComparisonType DIAGRAM
```


I file devono essere confrontati come documenti diagramma.


### DIFFERENT {#DIFFERENT}
```
public static final ComparisonType DIFFERENT
```


I file devono essere confrontati come documenti in formati diversi.


### SVG {#SVG}
```
public static final ComparisonType SVG
```


I file devono essere confrontati come documenti SVG.


### UNDEFINED {#UNDEFINED}
```
public static final ComparisonType UNDEFINED
```


Per uso interno.


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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String |  |

**Returns:**
[ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static ComparisonType fromString(String toStringValue)
```


Analizza la rappresentazione stringa di ComparisonType per ottenere la costante enum.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | toStringValue | java.lang.String | La rappresentazione stringa di ComparisonType |
|

**Returns:**
[ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) - ComparisonType enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


Rappresentazione stringa di ComparisonType.


**Returns:**
java.lang.String - valore stringa della costante dell'enumerazione

