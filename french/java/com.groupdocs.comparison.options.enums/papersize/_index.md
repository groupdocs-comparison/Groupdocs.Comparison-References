---
title: "PaperSize"
second_title: "Référence API de GroupDocs.Comparison for Java"
description: "Représente les options de format de papier pour la comparaison de documents."
type: docs
weight: 13
url: /fr/java/com.groupdocs.comparison.options.enums/papersize/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PaperSize extends Enum<PaperSize>
```

Représente les options de format de papier pour la comparaison de documents.


Exemple d'utilisation :

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setPaperSize(PaperSize.A6);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## Champs

| Champ | Description |
| --- | --- |
|  | [DEFAULT](#DEFAULT) | Taille de papier par défaut. |
|
|  | [A0](#A0) | Taille de papier standard A0 (841mm x 1189mm). |
|
|  | [A1](#A1) | Taille de papier standard A1 (594mm x 841mm). |
|
|  | [A2](#A2) | Taille de papier standard A2 (420mm x 594mm). |
|
|  | [A3](#A3) | Taille de papier standard A3 (297mm x 420mm). |
|
|  | [A4](#A4) | Taille de papier standard A4 (210mm x 297mm). |
|
|  | [A5](#A5) | Taille de papier standard A5 (148mm x 210mm). |
|
|  | [A6](#A6) | Taille de papier standard A6 (105mm x 148mm). |
|
|  | [A7](#A7) | Taille de papier standard A7 (74mm x 105mm). |
|
|  | [A8](#A8) | Taille de papier standard A8 (52mm x 74mm). |
|
## Méthodes

| Méthode | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Analyse la représentation sous forme de chaîne de PaperSize pour obtenir la constante d'énumération. |
|
|  | [toString()](#toString--) | Représentation sous forme de chaîne de PaperSize. |
|
### DEFAULT {#DEFAULT}
```
public static final PaperSize DEFAULT
```


Taille de papier par défaut.


### A0 {#A0}
```
public static final PaperSize A0
```


Taille de papier standard A0 (841mm x 1189mm).


### A1 {#A1}
```
public static final PaperSize A1
```


Taille de papier standard A1 (594mm x 841mm).


### A2 {#A2}
```
public static final PaperSize A2
```


Taille de papier standard A2 (420mm x 594mm).


### A3 {#A3}
```
public static final PaperSize A3
```


Taille de papier standard A3 (297mm x 420mm).


### A4 {#A4}
```
public static final PaperSize A4
```


Taille de papier standard A4 (210mm x 297mm).


### A5 {#A5}
```
public static final PaperSize A5
```


Taille de papier standard A5 (148mm x 210mm).


### A6 {#A6}
```
public static final PaperSize A6
```


Taille de papier standard A6 (105mm x 148mm).


### A7 {#A7}
```
public static final PaperSize A7
```


Taille de papier standard A7 (74mm x 105mm).


### A8 {#A8}
```
public static final PaperSize A8
```


Taille de papier standard A8 (52mm x 74mm).


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
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String |  |

**Returns:**
[PaperSize](../../com.groupdocs.comparison.options.enums/papersize)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static PaperSize fromString(String toStringValue)
```


Analyse la représentation sous forme de chaîne de PaperSize pour obtenir la constante d'énumération.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | toStringValue | java.lang.String | La représentation sous forme de chaîne de PaperSize |
|

**Returns:**
[PaperSize](../../com.groupdocs.comparison.options.enums/papersize) - PaperSize enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


Représentation sous forme de chaîne de PaperSize.


**Returns:**
java.lang.String - valeur sous forme de chaîne de la constante d'énumération

