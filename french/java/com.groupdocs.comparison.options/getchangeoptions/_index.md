---
title: "GetChangeOptions"
second_title: "Référence API de GroupDocs.Comparison for Java"
description: "Permet de configurer le filtrage pour récupérer des types de modifications spécifiques à partir du résultat de la comparaison."
type: docs
weight: 13
url: /fr/java/com.groupdocs.comparison.options/getchangeoptions/
---
**Inheritance:**
java.lang.Object
```
public class GetChangeOptions
```

Permet de configurer le filtrage pour récupérer des types de modifications spécifiques à partir du résultat de la comparaison.


Exemple d'utilisation :

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);
     comparer.compare();

     GetChangeOptions getChangeOptions = new GetChangeOptions();

     getChangeOptions.setFilter(ChangeType.DELETED);

     ChangeInfo[] changes = comparer.getChanges(getChangeOptions);
     System.out.println(Arrays.toString(changes));
 }
 
````


## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [GetChangeOptions()](#GetChangeOptions--) | Initialise une nouvelle instance de la classe GetChangeOptions. |
|
|  | [GetChangeOptions(ChangeType filter)](#GetChangeOptions-com.groupdocs.comparison.result.ChangeType-) | Initialise une nouvelle instance de la classe GetChangeOptions pour le type de filtre spécifié. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getFilter()](#getFilter--) | Obtient le filtre permettant de récupérer des types de modifications spécifiques à partir du résultat de comparaison. |
|
|  | [setFilter(ChangeType value)](#setFilter-com.groupdocs.comparison.result.ChangeType-) | Définit le filtre permettant de récupérer des types de modifications spécifiques à partir du résultat de comparaison. |
|
### GetChangeOptions() {#GetChangeOptions--}
```
public GetChangeOptions()
```


Initialise une nouvelle instance de la classe GetChangeOptions.


### GetChangeOptions(ChangeType filter) {#GetChangeOptions-com.groupdocs.comparison.result.ChangeType-}
```
public GetChangeOptions(ChangeType filter)
```


Initialise une nouvelle instance de la classe GetChangeOptions pour le type de filtre spécifié.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filter | [ChangeType](../../com.groupdocs.comparison.result/changetype) |  |

### getFilter() {#getFilter--}
```
public final ChangeType getFilter()
```


Obtient le filtre permettant de récupérer des types de modifications spécifiques à partir du résultat de comparaison.


**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - the filter specifying the types of changes to be retrieved.

### setFilter(ChangeType value) {#setFilter-com.groupdocs.comparison.result.ChangeType-}
```
public final void setFilter(ChangeType value)
```


Définit le filtre permettant de récupérer des types de modifications spécifiques à partir du résultat de comparaison.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [ChangeType](../../com.groupdocs.comparison.result/changetype) | Le filtre spécifiant les types de modifications à récupérer. |
|

