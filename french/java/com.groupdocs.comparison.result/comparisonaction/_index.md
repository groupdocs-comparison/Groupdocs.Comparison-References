---
title: "ComparisonAction"
second_title: "Référence API de GroupDocs.Comparison for Java"
description: "L'énumération ComparisonAction représente les actions pouvant être appliquées à une modification pendant le processus de comparaison de documents."
type: docs
weight: 15
url: /fr/java/com.groupdocs.comparison.result/comparisonaction/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ComparisonAction extends Enum<ComparisonAction>
```

L'énumération ComparisonAction représente les actions pouvant être appliquées à une modification pendant le processus de comparaison de documents.


Chaque constante de cette énumération représente une action spécifique et fournit une description lisible par l'homme ainsi qu'une valeur numérique.


Exemple d'utilisation :

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);
     comparer.compare();

     final ChangeInfo[] changes = comparer.getChanges();
     for (ChangeInfo changeInfo : changes) {
         if (changeInfo.getId() % 2 == 0) {
             changeInfo.setComparisonAction(ComparisonAction.REJECT);
         }
     }
     comparer.applyChanges(resultFile, changes);
 }
 
````


## Champs

| Champ | Description |
| --- | --- |
|  | [NONE](#NONE) | Représente aucune action. |
|
|  | [ACCEPT](#ACCEPT) | Représente une action d'acceptation. |
|
|  | [REJECT](#REJECT) | Représente une action de rejet. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Analyse la représentation sous forme de chaîne de ComparisonAction pour obtenir la constante d'énumération. |
|
|  | [fromInt(int intValue)](#fromInt-int-) | Crée une nouvelle constante de l'énumération ComparisonAction en utilisant la valeur numérique fournie. |
|
|  | [toString()](#toString--) | Représentation sous forme de chaîne de ComparisonAction. |
|
|  | [toInt()](#toInt--) | Représentation numérique de ComparisonAction. |
|
### NONE {#NONE}
```
public static final ComparisonAction NONE
```


Représente aucune action. Le changement n'aura aucun effet.


### ACCEPT {#ACCEPT}
```
public static final ComparisonAction ACCEPT
```


Représente une action d'acceptation. Le changement sera visible dans le fichier de résultat.


### REJECT {#REJECT}
```
public static final ComparisonAction REJECT
```


Représente une action de rejet. Le changement sera invisible dans le fichier de résultat.


### values() {#values--}
```
public static ComparisonAction[] values()
```




**Returns:**
com.groupdocs.comparison.result.ComparisonAction[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static ComparisonAction valueOf(String name)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String |  |

**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static ComparisonAction fromString(String toStringValue)
```


Analyse la représentation sous forme de chaîne de ComparisonAction pour obtenir la constante d'énumération.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | toStringValue | java.lang.String | La représentation sous forme de chaîne de ComparisonAction |
|

**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) - ComparisonAction enum constant associated with input string

### fromInt(int intValue) {#fromInt-int-}
```
public static ComparisonAction fromInt(int intValue)
```


Crée une nouvelle constante de l'énumération ComparisonAction en utilisant la valeur numérique fournie.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | intValue | int | La représentation numérique de ComparisonAction |
|

**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) - ComparisonAction enum constant associated with numeric value

### toString() {#toString--}
```
public String toString()
```


Représentation sous forme de chaîne de ComparisonAction.


**Returns:**
java.lang.String - valeur sous forme de chaîne de la constante d'énumération

### toInt() {#toInt--}
```
public int toInt()
```


Représentation numérique de ComparisonAction.


**Returns:**
int - valeur numérique de la constante d'énumération

