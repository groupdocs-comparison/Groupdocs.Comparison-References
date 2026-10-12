---
title: "Metered"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "提供将计量许可证应用于 Comparison 的方法。"
type: docs
weight: 11
url: /zh/java/com.groupdocs.comparison.license/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

提供将计量许可证应用于 Comparison 的方法。

* More about GroupDocs.Comparison licensing: [Evaluation Limitations and Licensing](../https://docs.groupdocs.com/display/comparisonjava/Evaluation+Limitations+and+Licensing+of+GroupDocs.Comparison)


简短的示例用法：

````

 final Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 
````


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [Metered()](#Metered--) | 初始化 Metered 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getConsumptionQuantity()](#getConsumptionQuantity--) | 获取消耗数量。 |
|
|  | [getConsumptionCredit()](#getConsumptionCredit--) | 检索已使用积分的数量。 |
|
|  | [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | 使用公钥和私钥应用计量许可证。 |
|
### Metered() {#Metered--}
```
public Metered()
```


初始化 Metered 类的新实例。


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


获取消耗数量。


**Returns:**
double - 消耗数量

### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


检索已使用积分的数量。


**Returns:**
double - 已使用积分的数量

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


使用公钥和私钥应用计量许可证。


示例用法：

````

 final Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 
````



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | publicKey | java.lang.String | 公钥 |
|
|  | privateKey | java.lang.String | 私钥 |
|

