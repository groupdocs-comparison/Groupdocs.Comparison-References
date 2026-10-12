---
title: "PasswordSaveOption"
second_title: "Riferimento API di GroupDocs.Comparison per Java"
description: "Elenca le opzioni per salvare le informazioni della password in un documento durante il processo di confronto."
type: docs
weight: 14
url: /it/java/com.groupdocs.comparison.options.enums/passwordsaveoption/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PasswordSaveOption extends Enum<PasswordSaveOption>
```

Elenca le opzioni per salvare le informazioni della password in un documento durante il processo di confronto.


Esempio di utilizzo:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setPasswordSaveOption(PasswordSaveOption.SOURCE);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## Campi

| Campo | Descrizione |
| --- | --- |
|  | [NONE](#NONE) | Non salvare la password. |
|
|  | [SOURCE](#SOURCE) | Usa la password dal documento di origine. |
|
|  | [TARGET](#TARGET) | Usa la password dal documento di destinazione. |
|
|  | [USER](#USER) | \* Usa la password fornita dall'utente. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Analizza la rappresentazione stringa di PasswordSaveOption per ottenere la costante enum. |
|
|  | [toString()](#toString--) | Rappresentazione stringa di PasswordSaveOption. |
|
### NONE {#NONE}
```
public static final PasswordSaveOption NONE
```


Non salvare la password.


### SOURCE {#SOURCE}
```
public static final PasswordSaveOption SOURCE
```


Usa la password dal documento di origine.


### TARGET {#TARGET}
```
public static final PasswordSaveOption TARGET
```


Usa la password dal documento di destinazione.


### USER {#USER}
```
public static final PasswordSaveOption USER
```


\* Usa la password fornita dall'utente.


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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String |  |

**Returns:**
[PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static PasswordSaveOption fromString(String toStringValue)
```


Analizza la rappresentazione stringa di PasswordSaveOption per ottenere la costante enum.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | toStringValue | java.lang.String | La rappresentazione stringa di PasswordSaveOption |
|

**Returns:**
[PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) - PasswordSaveOption enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


Rappresentazione stringa di PasswordSaveOption.


**Returns:**
java.lang.String - valore stringa della costante dell'enumerazione

