---
title: "Ölçümlü"
second_title: "GroupDocs.Comparison for Java API Referansı"
description: "Comparison için ölçülen lisansı uygulama yöntemleri sağlar."
type: docs
weight: 11
url: /tr/java/com.groupdocs.comparison.license/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Comparison için ölçülen lisansı uygulama yöntemleri sağlar.

* More about GroupDocs.Comparison licensing: [Evaluation Limitations and Licensing](../https://docs.groupdocs.com/display/comparisonjava/Evaluation+Limitations+and+Licensing+of+GroupDocs.Comparison)


Kısa örnek kullanımı:

````

 final Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 
````


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [Metered()](#Metered--) | Metered sınıfının yeni bir örneğini başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getConsumptionQuantity()](#getConsumptionQuantity--) | Tüketim miktarını alır. |
|
|  | [getConsumptionCredit()](#getConsumptionCredit--) | Kullanılan kredi miktarını alır. |
|
|  | [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Ölçümlü lisansı, genel ve özel anahtarlar kullanarak uygular. |
|
### Metered() {#Metered--}
```
public Metered()
```


Metered sınıfının yeni bir örneğini başlatır.


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


Tüketim miktarını alır.


**Returns:**
double - tüketim miktarı

### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


Kullanılan kredi miktarını alır.


**Returns:**
double - zaten kullanılan kredi sayısı

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


Ölçümlü lisansı, genel ve özel anahtarlar kullanarak uygular.


Örnek kullanım:

````

 final Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 
````



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | publicKey | java.lang.String | Genel anahtar |
|
|  | privateKey | java.lang.String | Özel anahtar |
|

