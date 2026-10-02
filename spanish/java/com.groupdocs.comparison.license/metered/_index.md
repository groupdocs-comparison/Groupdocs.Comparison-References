---
title: "Metered"
second_title: "Referencia de API de GroupDocs.Comparison for Java"
description: "Proporciona métodos para aplicar una licencia medida a Comparison."
type: docs
weight: 11
url: /es/java/com.groupdocs.comparison.license/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Proporciona métodos para aplicar una licencia medida a Comparison.

* More about GroupDocs.Comparison licensing: [Evaluation Limitations and Licensing](../https://docs.groupdocs.com/display/comparisonjava/Evaluation+Limitations+and+Licensing+of+GroupDocs.Comparison)


Ejemplo corto de uso:

````

 final Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 
````


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [Metered()](#Metered--) | Inicializa una nueva instancia de la clase Metered. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getConsumptionQuantity()](#getConsumptionQuantity--) | Obtiene la cantidad de consumo. |
|
|  | [getConsumptionCredit()](#getConsumptionCredit--) | Recupera la cantidad de créditos usados. |
|
|  | [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Aplica la licencia medida usando claves públicas y privadas. |
|
### Metered() {#Metered--}
```
public Metered()
```


Inicializa una nueva instancia de la clase Metered.


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


Obtiene la cantidad de consumo.


**Returns:**
double - cantidad de consumo

### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


Recupera la cantidad de créditos usados.


**Returns:**
double - número de créditos ya usados

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


Aplica la licencia medida usando claves públicas y privadas.


Ejemplo de uso:

````

 final Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 
````



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | publicKey | java.lang.String | Clave pública |
|
|  | privateKey | java.lang.String | Clave privada |
|

