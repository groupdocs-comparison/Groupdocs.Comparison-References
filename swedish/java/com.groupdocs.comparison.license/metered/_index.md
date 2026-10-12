---
title: "Metered"
second_title: "GroupDocs.Comparison för Java API-referens"
description: "Tillhandahåller metoder för att tillämpa mätad licens på Comparison."
type: docs
weight: 11
url: /sv/java/com.groupdocs.comparison.license/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Tillhandahåller metoder för att tillämpa mätad licens på Comparison.

* More about GroupDocs.Comparison licensing: [Evaluation Limitations and Licensing](../https://docs.groupdocs.com/display/comparisonjava/Evaluation+Limitations+and+Licensing+of+GroupDocs.Comparison)


Kort exempel på användning:

````

 final Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 
````


## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [Metered()](#Metered--) | Initierar en ny instans av Metered-klassen. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getConsumptionQuantity()](#getConsumptionQuantity--) | Hämtar förbrukningsmängd. |
|
|  | [getConsumptionCredit()](#getConsumptionCredit--) | Hämtar mängden använda krediter. |
|
|  | [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Tillämpar mätlicens med offentliga och privata nycklar. |
|
### Metered() {#Metered--}
```
public Metered()
```


Initierar en ny instans av Metered-klassen.


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


Hämtar förbrukningsmängd.


**Returns:**
double - förbrukningsmängd

### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


Hämtar mängden använda krediter.


**Returns:**
double - antal redan använda krediter

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


Tillämpar mätlicens med offentliga och privata nycklar.


Exempel på användning:

````

 final Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 
````



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | publicKey | java.lang.String | Offentlig nyckel |
|
|  | privateKey | java.lang.String | Privat nyckel |
|

