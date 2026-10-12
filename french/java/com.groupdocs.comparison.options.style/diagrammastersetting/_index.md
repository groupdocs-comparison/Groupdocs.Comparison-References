---
title: "DiagramMasterSetting"
second_title: "Référence API de GroupDocs.Comparison for Java"
description: "Représente les paramètres de comparaison du diagramme maître."
type: docs
weight: 10
url: /fr/java/com.groupdocs.comparison.options.style/diagrammastersetting/
---
**Inheritance:**
java.lang.Object
```
public class DiagramMasterSetting
```

Représente les paramètres de comparaison du diagramme maître.


Exemple d'utilisation :

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    final DiagramMasterSetting diagramMasterSetting = new DiagramMasterSetting();
    diagramMasterSetting.setMasterPath(masterFilePath);

    final CompareOptions compareOptions = new CompareOptions();
    compareOptions.setDiagramMasterSetting(diagramMasterSetting);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [DiagramMasterSetting()](#DiagramMasterSetting--) | Initialise une nouvelle instance de la classe DiagramMasterSetting. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [isUseSourceMaster()](#isUseSourceMaster--) | Obtient un indicateur qui indique si le chemin maître source sera utilisé. |
|
|  | [setUseSourceMaster(boolean value)](#setUseSourceMaster-boolean-) | Obtient un indicateur qui indique si le chemin maître source doit être utilisé. |
|
|  | [getMasterPath()](#getMasterPath--) | Obtient un chemin maître qui sera utilisé pour rendre les documents. |
|
|  | [setMasterPath(String value)](#setMasterPath-java.lang.String-) | Définit un chemin maître qui doit être utilisé pour rendre les documents. |
|
### DiagramMasterSetting() {#DiagramMasterSetting--}
```
public DiagramMasterSetting()
```


Initialise une nouvelle instance de la classe DiagramMasterSetting.


### isUseSourceMaster() {#isUseSourceMaster--}
```
public final boolean isUseSourceMaster()
```


Obtient un indicateur qui indique si le chemin maître source sera utilisé.


**Returns:**
boolean - vrai si le chemin maître source sera affiché, sinon faux

### setUseSourceMaster(boolean value) {#setUseSourceMaster-boolean-}
```
public final void setUseSourceMaster(boolean value)
```


Obtient un indicateur qui indique si le chemin maître source doit être utilisé.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | boolean | vrai si le chemin maître source doit être affiché, sinon faux |
|

### getMasterPath() {#getMasterPath--}
```
public final String getMasterPath()
```


Obtient un chemin maître qui sera utilisé pour rendre les documents. MasterPath est nécessaire pour créer un document résultat à partir d'un ensemble de formes par défaut.


**Returns:**
java.lang.String - chemin du document maître s'il est défini, sinon le chemin maître par défaut

### setMasterPath(String value) {#setMasterPath-java.lang.String-}
```
public final void setMasterPath(String value)
```


Définit un chemin maître qui doit être utilisé pour rendre les documents. MasterPath est nécessaire pour créer un document résultat à partir d'un ensemble de formes par défaut.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.lang.String | Chemin du document maître s'il est défini, sinon le chemin maître par défaut |
|

