---
title: "PasswordSaveOption"
second_title: "GroupDocs.Comparison voor Java API-referentie"
description: "Somt de opties op voor het opslaan van wachtwoordinformatie in een document tijdens het vergelijkingsproces."
type: docs
weight: 14
url: /nl/java/com.groupdocs.comparison.options.enums/passwordsaveoption/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PasswordSaveOption extends Enum<PasswordSaveOption>
```

Somt de opties op voor het opslaan van wachtwoordinformatie in een document tijdens het vergelijkingsproces.


Voorbeeldgebruik:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setPasswordSaveOption(PasswordSaveOption.SOURCE);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [NONE](#NONE) | Sla het wachtwoord niet op. |
|
|  | [SOURCE](#SOURCE) | Gebruik het wachtwoord van het brondocument. |
|
|  | [TARGET](#TARGET) | Gebruik het wachtwoord van het doeldocument. |
|
|  | [USER](#USER) | * Gebruik wachtwoord opgegeven door de gebruiker. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Parseert de tekenreeksrepresentatie van PasswordSaveOption om de enum-constante te verkrijgen. |
|
|  | [toString()](#toString--) | Tekenreeksrepresentatie van PasswordSaveOption. |
|
### NONE {#NONE}
```
public static final PasswordSaveOption NONE
```


Sla het wachtwoord niet op.


### SOURCE {#SOURCE}
```
public static final PasswordSaveOption SOURCE
```


Gebruik het wachtwoord van het brondocument.


### TARGET {#TARGET}
```
public static final PasswordSaveOption TARGET
```


Gebruik het wachtwoord van het doeldocument.


### USER {#USER}
```
public static final PasswordSaveOption USER
```


* Gebruik wachtwoord opgegeven door de gebruiker.


### values() {#values--}
```
public static PasswordSaveOption[] values()
```




**Returns:**
com.groupdocs.comparison.options.enums.PasswordSaveOption[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PasswordSaveOption valueOf(String name)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String |  |

**Returns:**
[PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static PasswordSaveOption fromString(String toStringValue)
```


Parseert de tekenreeksrepresentatie van PasswordSaveOption om de enum-constante te verkrijgen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | toStringValue | java.lang.String | De tekenreeksrepresentatie van PasswordSaveOption |
|

**Returns:**
[PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) - PasswordSaveOption enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


Tekenreeksrepresentatie van PasswordSaveOption.


**Returns:**
java.lang.String - tekenreekswaarde van enum-constante

