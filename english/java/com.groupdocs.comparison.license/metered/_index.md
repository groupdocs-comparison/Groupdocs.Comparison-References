---
title: Metered
second_title: GroupDocs.Comparison for Java API Reference
description: Provides methods to apply metered license to Comparison.
type: docs
weight: 11
url: /java/com.groupdocs.comparison.license/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Provides methods to apply metered license to Comparison.

 *  More about Metered licensing: [Metered Licensing FAQ][]
 *  More about GroupDocs.Comparison licensing: [Evaluation Limitations and Licensing][]

Short example usage:

```

 final Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 
```


[Metered Licensing FAQ]: https://purchase.groupdocs.com/faqs/licensing/metered
[Evaluation Limitations and Licensing]: https://docs.groupdocs.com/display/comparisonjava/Evaluation+Limitations+and+Licensing+of+GroupDocs.Comparison
## Constructors

| Constructor | Description |
| --- | --- |
| [Metered()](#Metered--) | Initializes a new instance of the Metered class. |
## Methods

| Method | Description |
| --- | --- |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Gets consumption quantity. |
| [getConsumptionCredit()](#getConsumptionCredit--) | Retrieves amount of used credits. |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Applies metered license using public and private keys. |
### Metered() {#Metered--}
```
public Metered()
```


Initializes a new instance of the Metered class.

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


Gets consumption quantity.

**Returns:**
double - consumption quantity
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


Retrieves amount of used credits.

**Returns:**
double - number of already used credits
### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


Applies metered license using public and private keys.

Example usage:

```

 final Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| publicKey | java.lang.String | Public key |
| privateKey | java.lang.String | Private key |

