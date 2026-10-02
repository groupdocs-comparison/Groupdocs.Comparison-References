---
title: "Licentie"
second_title: "GroupDocs.Comparison voor Java API-referentie"
description: "De License-klasse biedt methoden om licenties in te stellen en toe te passen voor GroupDocs.Comparison."
type: docs
weight: 10
url: /nl/java/com.groupdocs.comparison.license/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

De License-klasse biedt methoden om licenties in te stellen en toe te passen voor GroupDocs.Comparison.


Het stelt u in staat om specifieke functies van de bibliotheek in te schakelen of uit te schakelen op basis van de toegepaste licentie.

* More about GroupDocs.Comparison licensing: [Evaluation Limitations and Licensing](../https://docs.groupdocs.com/display/comparisonjava/Evaluation+Limitations+and+Licensing+of+GroupDocs.Comparison)


Voorbeeldgebruik:

````

 final License license = new License();
 license.setLicense("GroupDocs.License.lic");
 
````


## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [License()](#License--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [isValidLicense()](#isValidLicense--) | Haalt een waarde op die aangeeft of de licentie is ingesteld of niet. |
|
|  | [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | Stelt een licentie in voor Comparison met behulp van een invoerstroom. |
|
|  | [setLicense(Path licensePath)](#setLicense-java.nio.file.Path-) | Stelt een licentie in voor Comparison met behulp van het pad naar het licentiebestand. |
|
|  | [setLicense(String licensePath)](#setLicense-java.lang.String-) | Stelt een licentie in voor Comparison met behulp van het pad naar het licentiebestand. |
|
### License() {#License--}
```
public License()
```


### isValidLicense() {#isValidLicense--}
```
public static boolean isValidLicense()
```


Haalt een waarde op die aangeeft of de licentie is ingesteld of niet.


**Returns:**
boolean - true als de licentie succesvol is ingesteld, anders false

### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


Stelt een licentie in voor Comparison met behulp van een invoerstroom.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | licenseStream | java.io.InputStream | De licentiestroom, null maakt de licentie ongedaan |
|

### setLicense(Path licensePath) {#setLicense-java.nio.file.Path-}
```
public final void setLicense(Path licensePath)
```


Stelt een licentie in voor Comparison met behulp van het pad naar het licentiebestand.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | licensePath | java.nio.file.Path | Het pad naar het licentiebestand |
|

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


Stelt een licentie in voor Comparison met behulp van het pad naar het licentiebestand.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | licensePath | java.lang.String | Het pad naar het licentiebestand |
|

