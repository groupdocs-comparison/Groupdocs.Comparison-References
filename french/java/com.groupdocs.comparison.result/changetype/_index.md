---
title: "ChangeType"
second_title: "Référence API de GroupDocs.Comparison for Java"
description: "L'énumération ChangeType représente les types de modifications pouvant survenir pendant le processus de comparaison de documents."
type: docs
weight: 14
url: /fr/java/com.groupdocs.comparison.result/changetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ChangeType extends Enum<ChangeType>
```

L'énumération ChangeType représente les types de modifications pouvant survenir pendant le processus de comparaison de documents.


Chaque constante de cette énumération représente un type de modification spécifique et fournit une description lisible par l'homme ainsi qu'une valeur numérique.


Exemple d'utilisation :

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);
     comparer.compare();
     final ChangeInfo[] changes = comparer.getChanges();
     for (ChangeInfo changeInfo : changes) {
         // Get the ChangeType for a specific change
         final ChangeType changeType = changeInfo.getType();
         // Print the ChangeType information
         System.out.println("Description: " + changeType.toString());
         System.out.println("Value: " + changeType.toInt());
     }
 }
 
````


## Champs

| Champ | Description |
| --- | --- |
|  | [NONE](#NONE) | Représente aucune modification. |
|
|  | [MODIFIED](#MODIFIED) | Représente une modification modifiée. |
|
|  | [INSERTED](#INSERTED) | Représente une modification insérée. |
|
|  | [DELETED](#DELETED) | Représente une modification supprimée. |
|
|  | [ADDED](#ADDED) | Représente une modification ajoutée. |
|
|  | [NOT_MODIFIED](#NOT-MODIFIED) | Représente une modification non modifiée. |
|
|  | [STYLE_CHANGED](#STYLE-CHANGED) | Représente une modification de style. |
|
|  | [RESIZED](#RESIZED) | Représente un changement redimensionné. |
|
|  | [MOVED](#MOVED) | Représente un changement déplacé. |
|
|  | [MOVED_AND_RESIZED](#MOVED-AND-RESIZED) | Représente un changement déplacé et redimensionné. |
|
|  | [SHIFTED_AND_RESIZED](#SHIFTED-AND-RESIZED) | Représente un changement décalé et redimensionné. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Analyse la représentation sous forme de chaîne de ChangeType pour obtenir la constante d'énumération. |
|
|  | [fromInt(int intValue)](#fromInt-int-) | Crée une nouvelle constante de l'énumération ChangeType en utilisant la valeur numérique fournie. |
|
|  | [toString()](#toString--) | Représentation sous forme de chaîne de ChangeType. |
|
|  | [toInt()](#toInt--) | Représentation numérique de ChangeType. |
|
### NONE {#NONE}
```
public static final ChangeType NONE
```


Représente aucune modification.


### MODIFIED {#MODIFIED}
```
public static final ChangeType MODIFIED
```


Représente une modification modifiée.


### INSERTED {#INSERTED}
```
public static final ChangeType INSERTED
```


Représente une modification insérée.


### DELETED {#DELETED}
```
public static final ChangeType DELETED
```


Représente une modification supprimée.


### ADDED {#ADDED}
```
public static final ChangeType ADDED
```


Représente une modification ajoutée.


### NOT_MODIFIED {#NOT-MODIFIED}
```
public static final ChangeType NOT_MODIFIED
```


Représente une modification non modifiée.


### STYLE_CHANGED {#STYLE-CHANGED}
```
public static final ChangeType STYLE_CHANGED
```


Représente une modification de style.


### RESIZED {#RESIZED}
```
public static final ChangeType RESIZED
```


Représente un changement redimensionné.


### MOVED {#MOVED}
```
public static final ChangeType MOVED
```


Représente un changement déplacé.


### MOVED_AND_RESIZED {#MOVED-AND-RESIZED}
```
public static final ChangeType MOVED_AND_RESIZED
```


Représente un changement déplacé et redimensionné.


### SHIFTED_AND_RESIZED {#SHIFTED-AND-RESIZED}
```
public static final ChangeType SHIFTED_AND_RESIZED
```


Représente un changement décalé et redimensionné.


### values() {#values--}
```
public static ChangeType[] values()
```




**Returns:**
com.groupdocs.comparison.result.ChangeType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static ChangeType valueOf(String name)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String |  |

**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static ChangeType fromString(String toStringValue)
```


Analyse la représentation sous forme de chaîne de ChangeType pour obtenir la constante d'énumération.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | toStringValue | java.lang.String | La représentation sous forme de chaîne de ChangeType |
|

**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - ChangeType enum constant associated with input string

### fromInt(int intValue) {#fromInt-int-}
```
public static ChangeType fromInt(int intValue)
```


Crée une nouvelle constante de l'énumération ChangeType en utilisant la valeur numérique fournie.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | intValue | int | La représentation numérique de ChangeType |
|

**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - ChangeType enum constant associated with numeric value

### toString() {#toString--}
```
public String toString()
```


Représentation sous forme de chaîne de ChangeType.


**Returns:**
java.lang.String - valeur sous forme de chaîne de la constante d'énumération

### toInt() {#toInt--}
```
public int toInt()
```


Représentation numérique de ChangeType.


**Returns:**
int - valeur numérique de la constante d'énumération

