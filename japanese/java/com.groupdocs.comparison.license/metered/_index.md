---
title: "Metered"
second_title: "Java 用 GroupDocs.Comparison API リファレンス"
description: "Comparison に対して従量課金ライセンスを適用するメソッドを提供します。"
type: docs
weight: 11
url: /ja/java/com.groupdocs.comparison.license/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Comparison に対して従量課金ライセンスを適用するメソッドを提供します。

* More about GroupDocs.Comparison licensing: [Evaluation Limitations and Licensing](../https://docs.groupdocs.com/display/comparisonjava/Evaluation+Limitations+and+Licensing+of+GroupDocs.Comparison)


簡単な使用例:

````

 final Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 
````


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [Metered()](#Metered--) | Metered クラスの新しいインスタンスを初期化します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getConsumptionQuantity()](#getConsumptionQuantity--) | 消費量を取得します。 |
|
|  | [getConsumptionCredit()](#getConsumptionCredit--) | 使用済みクレジットの量を取得します。 |
|
|  | [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | 公開鍵と秘密鍵を使用して従量課金ライセンスを適用します。 |
|
### Metered() {#Metered--}
```
public Metered()
```


Metered クラスの新しいインスタンスを初期化します。


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


消費量を取得します。


**Returns:**
double - 消費量

### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


使用済みクレジットの量を取得します。


**Returns:**
double - 既に使用されたクレジットの数

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


公開鍵と秘密鍵を使用して従量課金ライセンスを適用します。


使用例:

````

 final Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 
````



**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | publicKey | java.lang.String | 公開鍵 |
|
|  | privateKey | java.lang.String | 秘密鍵 |
|

