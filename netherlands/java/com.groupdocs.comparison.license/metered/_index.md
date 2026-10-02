---
title: "Metered"
second_title: "GroupDocs.Comparison voor Java API-referentie"
description: "Biedt methoden om een meterlicentie toe te passen op Comparison."
type: docs
weight: 11
url: /nl/java/com.groupdocs.comparison.license/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Biedt methoden om een meterlicentie toe te passen op Comparison.

* More about GroupDocs.Comparison licensing: [Evaluation Limitations and Licensing](../https://docs.groupdocs.com/display/comparisonjava/Evaluation+Limitations+and+Licensing+of+GroupDocs.Comparison)


Kort voorbeeldgebruik:

````

 final Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 
````


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [Metered()](#Metered--) | Initialiseert een nieuw exemplaar van de Metered-klasse. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getConsumptionQuantity()](#getConsumptionQuantity--) | Haalt de consumptiehoeveelheid op. |
|
|  | [getConsumptionCredit()](#getConsumptionCredit--) | Haal het aantal gebruikte credits op. |
|
|  | [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Past een meterlicentie toe met behulp van publieke en private sleutels. |
|
### Metered() {#Metered--}
```
public Metered()
```


Initialiseert een nieuw exemplaar van de Metered-klasse.


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


Haalt de consumptiehoeveelheid op.


**Returns:**
double - consumptiehoeveelheid

### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


Haal het aantal gebruikte credits op.


**Returns:**
double - aantal reeds gebruikte credits

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


Past een meterlicentie toe met behulp van publieke en private sleutels.


Voorbeeldgebruik:

````

 final Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 
````



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | publicKey | java.lang.String | Publieke sleutel |
|
|  | privateKey | java.lang.String | Privésleutel |
|

