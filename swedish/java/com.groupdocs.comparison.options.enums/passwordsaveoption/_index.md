---
title: "PasswordSaveOption"
second_title: "GroupDocs.Comparison för Java API-referens"
description: "Uppräkning av alternativen för att spara lösenordsinformation i ett dokument under jämförelseprocessen."
type: docs
weight: 14
url: /sv/java/com.groupdocs.comparison.options.enums/passwordsaveoption/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PasswordSaveOption extends Enum<PasswordSaveOption>
```

Uppräkning av alternativen för att spara lösenordsinformation i ett dokument under jämförelseprocessen.


Exempel på användning:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setPasswordSaveOption(PasswordSaveOption.SOURCE);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [NONE](#NONE) | Spara inte lösenordet. |
|
|  | [SOURCE](#SOURCE) | Använd lösenord från källdokumentet. |
|
|  | [TARGET](#TARGET) | Använd lösenord från måldokumentet. |
|
|  | [USER](#USER) | \* Använd lösenord som tillhandahålls av användaren. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Analyserar strängrepresentationen av PasswordSaveOption för att få enum-konstanten. |
|
|  | [toString()](#toString--) | Strängrepresentation av PasswordSaveOption. |
|
### NONE {#NONE}
```
public static final PasswordSaveOption NONE
```


Spara inte lösenordet.


### SOURCE {#SOURCE}
```
public static final PasswordSaveOption SOURCE
```


Använd lösenord från källdokumentet.


### TARGET {#TARGET}
```
public static final PasswordSaveOption TARGET
```


Använd lösenord från måldokumentet.


### USER {#USER}
```
public static final PasswordSaveOption USER
```


\* Använd lösenord som tillhandahålls av användaren.


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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String |  |

**Returns:**
[PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static PasswordSaveOption fromString(String toStringValue)
```


Analyserar strängrepresentationen av PasswordSaveOption för att få enum-konstanten.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | toStringValue | java.lang.String | Strängrepresentationen av PasswordSaveOption |
|

**Returns:**
[PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) - PasswordSaveOption enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


Strängrepresentation av PasswordSaveOption.


**Returns:**
java.lang.String - strängvärde av enum‑konstant

