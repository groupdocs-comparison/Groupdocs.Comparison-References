---
title: "Metered"
second_title: "GroupDocs.Comparison for Java API 참조"
description: "계량 라이선스를 Comparison에 적용하는 메서드를 제공합니다."
type: docs
weight: 11
url: /ko/java/com.groupdocs.comparison.license/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

계량 라이선스를 Comparison에 적용하는 메서드를 제공합니다.

* More about GroupDocs.Comparison licensing: [Evaluation Limitations and Licensing](../https://docs.groupdocs.com/display/comparisonjava/Evaluation+Limitations+and+Licensing+of+GroupDocs.Comparison)


짧은 사용 예시:

````

 final Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 
````


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [Metered()](#Metered--) | Metered 클래스의 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getConsumptionQuantity()](#getConsumptionQuantity--) | 소비량을 가져옵니다. |
|
|  | [getConsumptionCredit()](#getConsumptionCredit--) | 사용된 크레딧 양을 검색합니다. |
|
|  | [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | 공개 키와 개인 키를 사용하여 계량식 라이선스를 적용합니다. |
|
### Metered() {#Metered--}
```
public Metered()
```


Metered 클래스의 새 인스턴스를 초기화합니다.


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


소비량을 가져옵니다.


**Returns:**
double - 소비량

### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


사용된 크레딧 양을 검색합니다.


**Returns:**
double - 이미 사용된 크레딧 수

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


공개 키와 개인 키를 사용하여 계량식 라이선스를 적용합니다.


사용 예시:

````

 final Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 
````



**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | publicKey | java.lang.String | 공개 키 |
|
|  | privateKey | java.lang.String | 개인 키 |
|

