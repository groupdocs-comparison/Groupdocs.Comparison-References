---
title: "StyleChangeInfo"
second_title: "Référence API de GroupDocs.Comparison for Java"
description: "La classe StyleChangeInfo représente les informations concernant une modification de style dans un document comparé."
type: docs
weight: 13
url: /fr/java/com.groupdocs.comparison.result/stylechangeinfo/
---
**Inheritance:**
java.lang.Object
```
public class StyleChangeInfo
```

La classe StyleChangeInfo représente les informations concernant une modification de style dans un document comparé.


Il fournit des détails tels que le nom de la propriété modifiée, les valeurs avant et après la modification, etc.
Utilisez cette classe pour récupérer des informations sur les changements de style pendant le processus de comparaison de documents.


Exemple d'utilisation :

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     comparer.compare();
     final ChangeInfo[] changes = comparer.getChanges();
     for (ChangeInfo change : changes) {
         // Access the style change information
         final List styleChanges = change.getStyleChanges();
         for (StyleChangeInfo styleChange : styleChanges) {
             // Print the style change information
             System.out.println("PropertyName: " + styleChange.getPropertyName());
             System.out.println("OldValue: " + styleChange.getOldValue());
             System.out.println("NewValue: " + styleChange.getNewValue());
         }
     }
 }
 
````


## Constructeurs

| Constructeur | Description |
| --- | --- |
| [StyleChangeInfo()](#StyleChangeInfo--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getPropertyName()](#getPropertyName--) | Obtient le nom de la propriété qui a été modifiée. |
|
|  | [setPropertyName(String value)](#setPropertyName-java.lang.String-) | Définit le nom de la propriété qui a été modifiée. |
|
|  | [getNewValue()](#getNewValue--) | Obtient la nouvelle valeur de la propriété. |
|
|  | [setNewValue(Object value)](#setNewValue-java.lang.Object-) | Définit la nouvelle valeur de la propriété. |
|
|  | [getOldValue()](#getOldValue--) | Obtient l'ancienne valeur de la propriété. |
|
|  | [setOldValue(Object value)](#setOldValue-java.lang.Object-) | Définit l'ancienne valeur de la propriété. |
|
|  | [equals(Object o)](#equals-java.lang.Object-) | {@inheritDoc} |
|
|  | [hashCode()](#hashCode--) | {@inheritDoc} |
|
### StyleChangeInfo() {#StyleChangeInfo--}
```
public StyleChangeInfo()
```


### getPropertyName() {#getPropertyName--}
```
public final String getPropertyName()
```


Obtient le nom de la propriété qui a été modifiée.


**Returns:**
java.lang.String - le nom de la propriété

### setPropertyName(String value) {#setPropertyName-java.lang.String-}
```
public final void setPropertyName(String value)
```


Définit le nom de la propriété qui a été modifiée.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.lang.String | Le nom de la propriété |
|

### getNewValue() {#getNewValue--}
```
public final Object getNewValue()
```


Obtient la nouvelle valeur de la propriété.


**Returns:**
java.lang.Object - la nouvelle valeur de la propriété

### setNewValue(Object value) {#setNewValue-java.lang.Object-}
```
public final void setNewValue(Object value)
```


Définit la nouvelle valeur de la propriété.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.lang.Object | La nouvelle valeur de la propriété |
|

### getOldValue() {#getOldValue--}
```
public final Object getOldValue()
```


Obtient l'ancienne valeur de la propriété.


**Returns:**
java.lang.Object - l'ancienne valeur de la propriété

### setOldValue(Object value) {#setOldValue-java.lang.Object-}
```
public final void setOldValue(Object value)
```


Définit l'ancienne valeur de la propriété.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.lang.Object | L'ancienne valeur de la propriété |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| o | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
