---
title: "ApplyChangeOptions"
second_title: "Référence API de GroupDocs.Comparison for Java"
description: "Permet de mettre à jour la liste des modifications avant de les appliquer au document résultant."
type: docs
weight: 10
url: /fr/java/com.groupdocs.comparison.options/applychangeoptions/
---
**Inheritance:**
java.lang.Object
```
public class ApplyChangeOptions
```

Permet de mettre à jour la liste des modifications avant de les appliquer au document résultant.


Exemple d'utilisation :

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);
     comparer.compare();
     ChangeInfo[] changes = comparer.getChanges();
     changes[0].setComparisonAction(ComparisonAction.REJECT);

     final ApplyChangeOptions applyChangeOptions = new ApplyChangeOptions(changes);

     comparer.applyChanges(resultFile, applyChangeOptions);
 }
 
````


## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [ApplyChangeOptions()](#ApplyChangeOptions--) | Initialise une nouvelle instance de la classe ApplyChangeOptions. |
|
|  | [ApplyChangeOptions(List<ChangeInfo> changes)](#ApplyChangeOptions-java.util.List-com.groupdocs.comparison.result.ChangeInfo--) | Initialise une nouvelle instance de la classe ApplyChangeOptions avec une liste de modifications. |
|
|  | [ApplyChangeOptions(ChangeInfo[] changes)](#ApplyChangeOptions-com.groupdocs.comparison.result.ChangeInfo---) | Initialise une nouvelle instance de la classe ApplyChangeOptions avec un tableau de modifications. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getChanges()](#getChanges--) | Obtient un tableau de modifications qui doivent être appliquées au document résultant. |
|
|  | [setChanges(ChangeInfo[] value)](#setChanges-com.groupdocs.comparison.result.ChangeInfo---) | Définit un tableau de modifications qui doivent être appliquées au document résultant. |
|
|  | [setChanges(List<ChangeInfo> value)](#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--) | Définit une liste de modifications qui doivent être appliquées au document résultant. |
|
|  | [isSaveOriginalState()](#isSaveOriginalState--) | Obtient un indicateur qui détermine si l'état original doit être enregistré. |
|
|  | [setSaveOriginalState(boolean saveOriginalState)](#setSaveOriginalState-boolean-) | Définit un indicateur qui détermine si l'état original doit être enregistré. |
|
### ApplyChangeOptions() {#ApplyChangeOptions--}
```
public ApplyChangeOptions()
```


Initialise une nouvelle instance de la classe ApplyChangeOptions.


### ApplyChangeOptions(List<ChangeInfo> changes) {#ApplyChangeOptions-java.util.List-com.groupdocs.comparison.result.ChangeInfo--}
```
public ApplyChangeOptions(List<ChangeInfo> changes)
```


Initialise une nouvelle instance de la classe ApplyChangeOptions avec une liste de modifications.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | modifications | java.util.List<com.groupdocs.comparison.result.ChangeInfo> | La liste des modifications à appliquer |
|

### ApplyChangeOptions(ChangeInfo[] changes) {#ApplyChangeOptions-com.groupdocs.comparison.result.ChangeInfo---}
```
public ApplyChangeOptions(ChangeInfo[] changes)
```


Initialise une nouvelle instance de la classe ApplyChangeOptions avec un tableau de modifications.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | changes | [ChangeInfo\[\]](../../com.groupdocs.comparison.result/changeinfo) | La liste des modifications à appliquer |
|

### getChanges() {#getChanges--}
```
public final ChangeInfo[] getChanges()
```


Obtient un tableau de modifications qui doivent être appliquées au document résultant.


**Returns:**
com.groupdocs.comparison.result.ChangeInfo[] - le tableau des modifications à appliquer

### setChanges(ChangeInfo[] value) {#setChanges-com.groupdocs.comparison.result.ChangeInfo---}
```
public final void setChanges(ChangeInfo[] value)
```


Définit un tableau de modifications qui doivent être appliquées au document résultant.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [ChangeInfo\[\]](../../com.groupdocs.comparison.result/changeinfo) | Le tableau des modifications à appliquer |
|

### setChanges(List<ChangeInfo> value) {#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--}
```
public final void setChanges(List<ChangeInfo> value)
```


Définit une liste de modifications qui doivent être appliquées au document résultant.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.util.List<com.groupdocs.comparison.result.ChangeInfo> | La liste des modifications à appliquer |
|

### isSaveOriginalState() {#isSaveOriginalState--}
```
public boolean isSaveOriginalState()
```


Obtient un indicateur qui détermine si l'état original doit être enregistré. Valeur par défaut : false.


**Returns:**
boolean - true si l'état original doit être enregistré, sinon false

### setSaveOriginalState(boolean saveOriginalState) {#setSaveOriginalState-boolean-}
```
public void setSaveOriginalState(boolean saveOriginalState)
```


Définit un indicateur qui détermine si l'état original doit être enregistré.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | saveOriginalState | boolean | True si l'état original doit être enregistré, sinon false |
|

