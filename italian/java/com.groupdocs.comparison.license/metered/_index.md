---
title: "Metered"
second_title: "Riferimento API di GroupDocs.Comparison per Java"
description: "Fornisce metodi per applicare una licenza a consumo a Comparison."
type: docs
weight: 11
url: /it/java/com.groupdocs.comparison.license/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Fornisce metodi per applicare una licenza a consumo a Comparison.

* More about GroupDocs.Comparison licensing: [Evaluation Limitations and Licensing](../https://docs.groupdocs.com/display/comparisonjava/Evaluation+Limitations+and+Licensing+of+GroupDocs.Comparison)


Esempio breve di utilizzo:

````

 final Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 
````


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [Metered()](#Metered--) | Inizializza una nuova istanza della classe Metered. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getConsumptionQuantity()](#getConsumptionQuantity--) | Ottiene la quantità di consumo. |
|
|  | [getConsumptionCredit()](#getConsumptionCredit--) | Recupera l'importo dei crediti utilizzati. |
|
|  | [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Applica la licenza a consumo usando le chiavi pubblica e privata. |
|
### Metered() {#Metered--}
```
public Metered()
```


Inizializza una nuova istanza della classe Metered.


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


Ottiene la quantità di consumo.


**Returns:**
double - quantità di consumo

### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


Recupera l'importo dei crediti utilizzati.


**Returns:**
double - numero di crediti già utilizzati

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


Applica la licenza a consumo usando le chiavi pubblica e privata.


Esempio di utilizzo:

````

 final Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 
````



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | publicKey | java.lang.String | Chiave pubblica |
|
|  | privateKey | java.lang.String | Chiave privata |
|

