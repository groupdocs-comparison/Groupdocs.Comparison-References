---
title: "PasswordSaveOption"
second_title: "Référence API de GroupDocs.Comparison for Java"
description: "Énumère les options pour enregistrer les informations de mot de passe dans un document pendant le processus de comparaison."
type: docs
weight: 14
url: /fr/java/com.groupdocs.comparison.options.enums/passwordsaveoption/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PasswordSaveOption extends Enum<PasswordSaveOption>
```

Énumère les options pour enregistrer les informations de mot de passe dans un document pendant le processus de comparaison.


Exemple d'utilisation :

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setPasswordSaveOption(PasswordSaveOption.SOURCE);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## Champs

| Champ | Description |
| --- | --- |
|  | [NONE](#NONE) | Ne pas enregistrer le mot de passe. |
|
|  | [SOURCE](#SOURCE) | Utiliser le mot de passe du document source. |
|
|  | [TARGET](#TARGET) | Utiliser le mot de passe du document cible. |
|
|  | [USER](#USER) | \* Utiliser le mot de passe fourni par l'utilisateur. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Analyse la représentation sous forme de chaîne de PasswordSaveOption pour obtenir la constante d'énumération. |
|
|  | [toString()](#toString--) | Représentation sous forme de chaîne de PasswordSaveOption. |
|
### NONE {#NONE}
```
public static final PasswordSaveOption NONE
```


Ne pas enregistrer le mot de passe.


### SOURCE {#SOURCE}
```
public static final PasswordSaveOption SOURCE
```


Utiliser le mot de passe du document source.


### TARGET {#TARGET}
```
public static final PasswordSaveOption TARGET
```


Utiliser le mot de passe du document cible.


### USER {#USER}
```
public static final PasswordSaveOption USER
```


\* Utiliser le mot de passe fourni par l'utilisateur.


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
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String |  |

**Returns:**
[PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static PasswordSaveOption fromString(String toStringValue)
```


Analyse la représentation sous forme de chaîne de PasswordSaveOption pour obtenir la constante d'énumération.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | toStringValue | java.lang.String | La représentation sous forme de chaîne de PasswordSaveOption |
|

**Returns:**
[PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) - PasswordSaveOption enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


Représentation sous forme de chaîne de PasswordSaveOption.


**Returns:**
java.lang.String - valeur sous forme de chaîne de la constante d'énumération

