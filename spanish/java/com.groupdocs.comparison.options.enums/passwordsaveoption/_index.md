---
title: "PasswordSaveOption"
second_title: "Referencia de API de GroupDocs.Comparison for Java"
description: "Enumera las opciones para guardar la información de contraseña en un documento durante el proceso de comparación."
type: docs
weight: 14
url: /es/java/com.groupdocs.comparison.options.enums/passwordsaveoption/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PasswordSaveOption extends Enum<PasswordSaveOption>
```

Enumera las opciones para guardar la información de contraseña en un documento durante el proceso de comparación.


Ejemplo de uso:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setPasswordSaveOption(PasswordSaveOption.SOURCE);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## Campos

| Campo | Descripción |
| --- | --- |
|  | [NONE](#NONE) | No guardar la contraseña. |
|
|  | [SOURCE](#SOURCE) | Usar la contraseña del documento de origen. |
|
|  | [TARGET](#TARGET) | Usar la contraseña del documento de destino. |
|
|  | [USER](#USER) | \* Usar la contraseña proporcionada por el usuario. |
|
## Métodos

| Método | Descripción |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Analiza la representación en cadena de PasswordSaveOption para obtener la constante del enumerado. |
|
|  | [toString()](#toString--) | Representación en cadena de PasswordSaveOption. |
|
### NONE {#NONE}
```
public static final PasswordSaveOption NONE
```


No guardar la contraseña.


### SOURCE {#SOURCE}
```
public static final PasswordSaveOption SOURCE
```


Usar la contraseña del documento de origen.


### TARGET {#TARGET}
```
public static final PasswordSaveOption TARGET
```


Usar la contraseña del documento de destino.


### USER {#USER}
```
public static final PasswordSaveOption USER
```


\* Usar la contraseña proporcionada por el usuario.


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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String |  |

**Returns:**
[PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static PasswordSaveOption fromString(String toStringValue)
```


Analiza la representación en cadena de PasswordSaveOption para obtener la constante del enumerado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | toStringValue | java.lang.String | La representación en cadena de PasswordSaveOption |
|

**Returns:**
[PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) - PasswordSaveOption enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


Representación en cadena de PasswordSaveOption.


**Returns:**
java.lang.String - valor en cadena de la constante del enum

