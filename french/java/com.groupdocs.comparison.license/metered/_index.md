---
title: "Metered"
second_title: "Référence API de GroupDocs.Comparison for Java"
description: "Fournit des méthodes pour appliquer une licence à la consommation à Comparison."
type: docs
weight: 11
url: /fr/java/com.groupdocs.comparison.license/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Fournit des méthodes pour appliquer une licence à la consommation à Comparison.

* More about GroupDocs.Comparison licensing: [Evaluation Limitations and Licensing](../https://docs.groupdocs.com/display/comparisonjava/Evaluation+Limitations+and+Licensing+of+GroupDocs.Comparison)


Exemple d'utilisation court :

````

 final Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 
````


## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [Metered()](#Metered--) | Initialise une nouvelle instance de la classe Metered. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getConsumptionQuantity()](#getConsumptionQuantity--) | Obtient la quantité de consommation. |
|
|  | [getConsumptionCredit()](#getConsumptionCredit--) | Récupère le montant des crédits utilisés. |
|
|  | [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Applique une licence mesurée en utilisant les clés publiques et privées. |
|
### Metered() {#Metered--}
```
public Metered()
```


Initialise une nouvelle instance de la classe Metered.


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


Obtient la quantité de consommation.


**Returns:**
double - quantité de consommation

### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


Récupère le montant des crédits utilisés.


**Returns:**
double - nombre de crédits déjà utilisés

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


Applique une licence mesurée en utilisant les clés publiques et privées.


Exemple d'utilisation :

````

 final Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 
````



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | publicKey | java.lang.String | Clé publique |
|
|  | privateKey | java.lang.String | Clé privée |
|

