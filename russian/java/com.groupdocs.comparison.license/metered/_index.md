---
title: "Metered"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "Предоставляет методы для применения измеряемой лицензии к Comparison."
type: docs
weight: 11
url: /ru/java/com.groupdocs.comparison.license/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Предоставляет методы для применения измеряемой лицензии к Comparison.

* More about GroupDocs.Comparison licensing: [Evaluation Limitations and Licensing](../https://docs.groupdocs.com/display/comparisonjava/Evaluation+Limitations+and+Licensing+of+GroupDocs.Comparison)


Краткий пример использования:

````

 final Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 
````


## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [Metered()](#Metered--) | Инициализирует новый экземпляр класса Metered. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getConsumptionQuantity()](#getConsumptionQuantity--) | Получает количество потребления. |
|
|  | [getConsumptionCredit()](#getConsumptionCredit--) | Получает количество использованных кредитов. |
|
|  | [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Применяет измеряемую лицензию с использованием публичных и приватных ключей. |
|
### Metered() {#Metered--}
```
public Metered()
```


Инициализирует новый экземпляр класса Metered.


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


Получает количество потребления.


**Returns:**
double — количество потребления

### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


Получает количество использованных кредитов.


**Returns:**
double — количество уже использованных кредитов

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


Применяет измеряемую лицензию с использованием публичных и приватных ключей.


Пример использования:

````

 final Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 
````



**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | publicKey | java.lang.String | Публичный ключ |
|
|  | privateKey | java.lang.String | Закрытый ключ |
|

