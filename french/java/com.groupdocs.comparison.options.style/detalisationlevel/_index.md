---
title: "DetalisationLevel"
second_title: "Référence API de GroupDocs.Comparison for Java"
description: "Spécifie le niveau de détail de la comparaison."
type: docs
weight: 13
url: /fr/java/com.groupdocs.comparison.options.style/detalisationlevel/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DetalisationLevel extends Enum<DetalisationLevel>
```

Spécifie le niveau de détail de la comparaison.


Exemple d'utilisation :

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setDetectStyleChanges(false);
    compareOptions.setDetalisationLevel(DetalisationLevel.HIGH);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## Champs

| Champ | Description |
| --- | --- |
|  | [LOW](#LOW) | Représente le niveau de comparaison faible. |
|
|  | [MIDDLE](#MIDDLE) | Représente le niveau de comparaison moyen. |
|
|  | [HIGH](#HIGH) | Représente le niveau de comparaison élevé. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Analyse la représentation sous forme de chaîne de DetalisationLevel pour obtenir la constante d'énumération. |
|
|  | [toString()](#toString--) | Représentation sous forme de chaîne de DetalisationLevel. |
|
### LOW {#LOW}
```
public static final DetalisationLevel LOW
```


Représente le niveau de comparaison faible.


Le niveau "Low" offre la meilleure vitesse pour les comparaisons mais sacrifie la qualité de comparaison.
La comparaison est effectuée par mot.


### MIDDLE {#MIDDLE}
```
public static final DetalisationLevel MIDDLE
```


Représente le niveau de comparaison moyen.


Le niveau "Middle" est un compromis raisonnable entre la vitesse de comparaison et la qualité.
La comparaison est effectuée caractère par caractère, mais en ignorant la casse des caractères et le comptage des espaces.


### HIGH {#HIGH}
```
public static final DetalisationLevel HIGH
```


Représente le niveau de comparaison élevé.


Le niveau "High" offre la meilleure qualité de comparaison, mais la vitesse la plus basse.
La comparaison est effectuée caractère par caractère en tenant compte de la casse des caractères et du comptage des espaces.


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
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String |  |

**Returns:**
[DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static DetalisationLevel fromString(String toStringValue)
```


Analyse la représentation sous forme de chaîne de DetalisationLevel pour obtenir la constante d'énumération.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | toStringValue | java.lang.String | La représentation sous forme de chaîne de DetalisationLevel |
|

**Returns:**
[DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) - DetalisationLevel enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


Représentation sous forme de chaîne de DetalisationLevel.


**Returns:**
java.lang.String - valeur sous forme de chaîne de la constante d'énumération

