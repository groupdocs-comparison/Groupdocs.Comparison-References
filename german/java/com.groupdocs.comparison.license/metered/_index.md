---
title: "Metered"
second_title: "GroupDocs.Comparison für Java API-Referenz"
description: "Stellt Methoden zum Anwenden einer nutzungsbasierten Lizenz auf Comparison bereit."
type: docs
weight: 11
url: /de/java/com.groupdocs.comparison.license/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Stellt Methoden zum Anwenden einer nutzungsbasierten Lizenz auf Comparison bereit.

* More about GroupDocs.Comparison licensing: [Evaluation Limitations and Licensing](../https://docs.groupdocs.com/display/comparisonjava/Evaluation+Limitations+and+Licensing+of+GroupDocs.Comparison)


Kurzes Beispiel für die Verwendung:

````

 final Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 
````


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [Metered()](#Metered--) | Initialisiert eine neue Instanz der Metered-Klasse. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getConsumptionQuantity()](#getConsumptionQuantity--) | Ruft die Verbrauchsmenge ab. |
|
|  | [getConsumptionCredit()](#getConsumptionCredit--) | Ruft die Menge der verwendeten Credits ab. |
|
|  | [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Wendet eine nutzungsbasierte Lizenz mit öffentlichen und privaten Schlüsseln an. |
|
### Metered() {#Metered--}
```
public Metered()
```


Initialisiert eine neue Instanz der Metered-Klasse.


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


Ruft die Verbrauchsmenge ab.


**Returns:**
double - Verbrauchsmenge

### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


Ruft die Menge der verwendeten Credits ab.


**Returns:**
double - Anzahl bereits verwendeter Credits

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


Wendet eine nutzungsbasierte Lizenz mit öffentlichen und privaten Schlüsseln an.


Beispielverwendung:

````

 final Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 
````



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | publicKey | java.lang.String | Öffentlicher Schlüssel |
|
|  | privateKey | java.lang.String | Privater Schlüssel |
|

