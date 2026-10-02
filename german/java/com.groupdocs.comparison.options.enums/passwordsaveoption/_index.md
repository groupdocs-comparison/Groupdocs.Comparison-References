---
title: "PasswordSaveOption"
second_title: "GroupDocs.Comparison für Java API-Referenz"
description: "Enumeriert die Optionen zum Speichern von Passwortinformationen in einem Dokument während des Vergleichsvorgangs."
type: docs
weight: 14
url: /de/java/com.groupdocs.comparison.options.enums/passwordsaveoption/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PasswordSaveOption extends Enum<PasswordSaveOption>
```

Enumeriert die Optionen zum Speichern von Passwortinformationen in einem Dokument während des Vergleichsvorgangs.


Beispielverwendung:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setPasswordSaveOption(PasswordSaveOption.SOURCE);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [NONE](#NONE) | Passwort nicht speichern. |
|
|  | [SOURCE](#SOURCE) | Passwort aus dem Quelldokument verwenden. |
|
|  | [TARGET](#TARGET) | Passwort aus dem Zieldokument verwenden. |
|
|  | [USER](#USER) | \* Vom Benutzer bereitgestelltes Passwort verwenden. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Parst die Zeichenkettenrepräsentation von PasswordSaveOption, um die Enum-Konstante zu erhalten. |
|
|  | [toString()](#toString--) | Zeichenkettenrepräsentation von PasswordSaveOption. |
|
### NONE {#NONE}
```
public static final PasswordSaveOption NONE
```


Passwort nicht speichern.


### SOURCE {#SOURCE}
```
public static final PasswordSaveOption SOURCE
```


Passwort aus dem Quelldokument verwenden.


### TARGET {#TARGET}
```
public static final PasswordSaveOption TARGET
```


Passwort aus dem Zieldokument verwenden.


### USER {#USER}
```
public static final PasswordSaveOption USER
```


\* Vom Benutzer bereitgestelltes Passwort verwenden.


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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String |  |

**Returns:**
[PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static PasswordSaveOption fromString(String toStringValue)
```


Parst die Zeichenkettenrepräsentation von PasswordSaveOption, um die Enum-Konstante zu erhalten.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | toStringValue | java.lang.String | Die Zeichenkettenrepräsentation von PasswordSaveOption |
|

**Returns:**
[PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) - PasswordSaveOption enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


Zeichenkettenrepräsentation von PasswordSaveOption.


**Returns:**
java.lang.String - String-Wert der Enum-Konstante

