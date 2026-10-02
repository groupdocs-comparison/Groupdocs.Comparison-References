---
title: "Metered"
second_title: "GroupDocs.Comparison لـ Java API Reference"
description: "توفر طرقًا لتطبيق الترخيص القائم على القياس على Comparison."
type: docs
weight: 11
url: /ar/java/com.groupdocs.comparison.license/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

توفر طرقًا لتطبيق الترخيص القائم على القياس على Comparison.

* More about GroupDocs.Comparison licensing: [Evaluation Limitations and Licensing](../https://docs.groupdocs.com/display/comparisonjava/Evaluation+Limitations+and+Licensing+of+GroupDocs.Comparison)


مثال قصير للاستخدام:

````

 final Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 
````


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [Metered()](#Metered--) | يُنشئ مثيلاً جديدًا من فئة Metered. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getConsumptionQuantity()](#getConsumptionQuantity--) | يحصل على كمية الاستهلاك. |
|
|  | [getConsumptionCredit()](#getConsumptionCredit--) | يسترجع مقدار الرصيد المستخدم. |
|
|  | [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | يطبق ترخيصًا مقاسًا باستخدام المفاتيح العامة والخاصة. |
|
### Metered() {#Metered--}
```
public Metered()
```


يُنشئ مثيلاً جديدًا من فئة Metered.


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


يحصل على كمية الاستهلاك.


**Returns:**
double - كمية الاستهلاك

### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


يسترجع مقدار الرصيد المستخدم.


**Returns:**
double - عدد الأرصدة المستخدمة بالفعل

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


يطبق ترخيصًا مقاسًا باستخدام المفاتيح العامة والخاصة.


مثال على الاستخدام:

````

 final Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 
````



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | publicKey | java.lang.String | المفتاح العام |
|
|  | privateKey | java.lang.String | المفتاح الخاص |
|

