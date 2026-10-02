---
title: "ComparisonType"
second_title: "Référence API de GroupDocs.Comparison for Java"
description: "Représente le type de comparaison à effectuer."
type: docs
weight: 10
url: /fr/java/com.groupdocs.comparison.options.enums/comparisontype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ComparisonType extends Enum<ComparisonType>
```

Représente le type de comparaison à effectuer.


Exemple d'utilisation :

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setComparisonType(ComparisonType.CELLS);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## Champs

| Champ | Description |
| --- | --- |
|  | [TEXT](#TEXT) | Les fichiers doivent être comparés en tant que documents texte. |
|
|  | [SLIDES](#SLIDES) | Les fichiers doivent être comparés en tant que documents de présentation. |
|
|  | [WORDS](#WORDS) | Les fichiers doivent être comparés en tant que documents Word. |
|
|  | [CELLS](#CELLS) | Les fichiers doivent être comparés en tant que documents Excel. |
|
|  | [PDF](#PDF) | Les fichiers doivent être comparés en tant que documents PDF. |
|
|  | [IMAGING](#IMAGING) | Les fichiers doivent être comparés en tant que documents image. |
|
|  | [EMAIL](#EMAIL) | Les fichiers doivent être comparés en tant que documents e-mail. |
|
|  | [NOTE](#NOTE) | Les fichiers doivent être comparés en tant que documents de notes. |
|
|  | [HTML](#HTML) | Les fichiers doivent être comparés en tant que documents HTML. |
|
|  | [DIAGRAM](#DIAGRAM) | Les fichiers doivent être comparés en tant que documents de diagramme. |
|
|  | [DIFFERENT](#DIFFERENT) | Les fichiers doivent être comparés en tant que documents dans différents formats. |
|
|  | [SVG](#SVG) | Les fichiers doivent être comparés en tant que documents SVG. |
|
|  | [UNDEFINED](#UNDEFINED) | Pour usage interne. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Analyse la représentation sous forme de chaîne de ComparisonType pour obtenir la constante d'énumération. |
|
|  | [toString()](#toString--) | Représentation sous forme de chaîne de ComparisonType. |
|
### TEXT {#TEXT}
```
public static final ComparisonType TEXT
```


Les fichiers doivent être comparés en tant que documents texte.


### SLIDES {#SLIDES}
```
public static final ComparisonType SLIDES
```


Les fichiers doivent être comparés en tant que documents de présentation.


### WORDS {#WORDS}
```
public static final ComparisonType WORDS
```


Les fichiers doivent être comparés en tant que documents Word.


### CELLS {#CELLS}
```
public static final ComparisonType CELLS
```


Les fichiers doivent être comparés en tant que documents Excel.


### PDF {#PDF}
```
public static final ComparisonType PDF
```


Les fichiers doivent être comparés en tant que documents PDF.


### IMAGING {#IMAGING}
```
public static final ComparisonType IMAGING
```


Les fichiers doivent être comparés en tant que documents image.


### EMAIL {#EMAIL}
```
public static final ComparisonType EMAIL
```


Les fichiers doivent être comparés en tant que documents e-mail.


### NOTE {#NOTE}
```
public static final ComparisonType NOTE
```


Les fichiers doivent être comparés en tant que documents de notes.


### HTML {#HTML}
```
public static final ComparisonType HTML
```


Les fichiers doivent être comparés en tant que documents HTML.


### DIAGRAM {#DIAGRAM}
```
public static final ComparisonType DIAGRAM
```


Les fichiers doivent être comparés en tant que documents de diagramme.


### DIFFERENT {#DIFFERENT}
```
public static final ComparisonType DIFFERENT
```


Les fichiers doivent être comparés en tant que documents dans différents formats.


### SVG {#SVG}
```
public static final ComparisonType SVG
```


Les fichiers doivent être comparés en tant que documents SVG.


### UNDEFINED {#UNDEFINED}
```
public static final ComparisonType UNDEFINED
```


Pour usage interne.


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
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String |  |

**Returns:**
[ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static ComparisonType fromString(String toStringValue)
```


Analyse la représentation sous forme de chaîne de ComparisonType pour obtenir la constante d'énumération.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | toStringValue | java.lang.String | La représentation sous forme de chaîne de ComparisonType |
|

**Returns:**
[ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) - ComparisonType enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


Représentation sous forme de chaîne de ComparisonType.


**Returns:**
java.lang.String - valeur sous forme de chaîne de la constante d'énumération

