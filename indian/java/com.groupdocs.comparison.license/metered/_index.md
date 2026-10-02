---
title: "Metered"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "Comparison में मीटरड लाइसेंस लागू करने के मेथड प्रदान करता है।"
type: docs
weight: 11
url: /hi/java/com.groupdocs.comparison.license/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Comparison में मीटरड लाइसेंस लागू करने के मेथड प्रदान करता है।

* More about GroupDocs.Comparison licensing: [Evaluation Limitations and Licensing](../https://docs.groupdocs.com/display/comparisonjava/Evaluation+Limitations+and+Licensing+of+GroupDocs.Comparison)


संक्षिप्त उदाहरण उपयोग:

````

 final Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 
````


## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [Metered()](#Metered--) | Metered वर्ग की नई इंस्टेंस को इनिशियलाइज़ करता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getConsumptionQuantity()](#getConsumptionQuantity--) | उपभोग मात्रा प्राप्त करता है। |
|
|  | [getConsumptionCredit()](#getConsumptionCredit--) | उपयोग किए गए क्रेडिट की राशि प्राप्त करता है। |
|
|  | [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | सार्वजनिक और निजी कुंजियों का उपयोग करके मीटर लाइसेंस लागू करता है। |
|
### Metered() {#Metered--}
```
public Metered()
```


Metered वर्ग की नई इंस्टेंस को इनिशियलाइज़ करता है।


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


उपभोग मात्रा प्राप्त करता है।


**Returns:**
double - उपभोग मात्रा

### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


उपयोग किए गए क्रेडिट की राशि प्राप्त करता है।


**Returns:**
double - पहले से उपयोग किए गए क्रेडिट की संख्या

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


सार्वजनिक और निजी कुंजियों का उपयोग करके मीटर लाइसेंस लागू करता है।


उदाहरण उपयोग:

````

 final Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 
````



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | publicKey | java.lang.String | सार्वजनिक कुंजी |
|
|  | privateKey | java.lang.String | निजी कुंजी |
|

