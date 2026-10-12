---
title: "LoadOptions"
second_title: "Référence API de GroupDocs.Comparison for Java"
description: "Permet de spécifier des options supplémentaires lors du chargement d'un document."
type: docs
weight: 10
url: /fr/java/com.groupdocs.comparison.options.load/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

Permet de spécifier des options supplémentaires lors du chargement d'un document.


Exemple d'utilisation :

````

 final LoadOptions loadOptions = new LoadOptions();
 loadOptions.setPassword("passw");
 loadOptions.setFileType(FileType.PDF);

 try (Comparer comparer = new Comparer(sourceFile, loadOptions)) {
    comparer.add(targetFile);

    comparer.compare(resultFile);
 }
 
````


## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [LoadOptions()](#LoadOptions--) | Initialise une nouvelle instance de la classe LoadOptions. |
|
|  | [LoadOptions(boolean isLoadText)](#LoadOptions-boolean-) | Initialise une nouvelle instance de la classe LoadOptions avec un indicateur signifiant que la chaîne d'entrée est un texte à comparer, pas un chemin. |
|
|  | [LoadOptions(String password)](#LoadOptions-java.lang.String-) | Initialise une nouvelle instance de la classe LoadOptions avec un mot de passe pour charger le document. |
|
|  | [LoadOptions(boolean isLoadText, String password)](#LoadOptions-boolean-java.lang.String-) | Initialise une nouvelle instance de la classe LoadOptions avec un indicateur signifiant que la chaîne d'entrée est un texte à comparer et un mot de passe pour charger le document. |
|
|  | [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.comparison.result.FileType-) | Initialise une nouvelle instance de la classe LoadOptions avec un type de fichier. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [isLoadText()](#isLoadText--) | Obtient un indicateur qui indique que la chaîne passée au constructeur [Comparer](../../com.groupdocs.comparison/comparer) ou à la méthode [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) est du texte de comparaison, pas des chemins de fichiers (pour la comparaison de texte uniquement). |
|
|  | [setLoadText(boolean value)](#setLoadText-boolean-) | Définit un indicateur qui indique que la chaîne passée au constructeur [Comparer](../../com.groupdocs.comparison/comparer) ou à la méthode [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) est du texte de comparaison, pas des chemins de fichiers (pour la comparaison de texte uniquement). |
|
|  | [getPassword()](#getPassword--) | Obtient un mot de passe qui sera utilisé pour charger un document. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Définit un mot de passe qui doit être utilisé pour charger un document. |
|
|  | [getFontDirectories()](#getFontDirectories--) | Obtient une liste de répertoires où les fichiers de police pour charger un document sont placés. |
|
|  | [setFontDirectories(List<String> value)](#setFontDirectories-java.util.List-java.lang.String--) | Définit une liste de répertoires où les fichiers de police pour charger un document sont placés. |
|
|  | [getFileType()](#getFileType--) | Obtient le type d'un fichier qui est en cours de chargement. |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.comparison.result.FileType-) | Définit le type d'un fichier qui se charge. |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


Initialise une nouvelle instance de la classe LoadOptions.


### LoadOptions(boolean isLoadText) {#LoadOptions-boolean-}
```
public LoadOptions(boolean isLoadText)
```


Initialise une nouvelle instance de la classe LoadOptions avec un indicateur signifiant que la chaîne d'entrée est un texte à comparer, pas un chemin.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | isLoadText | boolean | Le drapeau qui indique que la chaîne d'entrée est un texte à comparer, pas un chemin |
|

### LoadOptions(String password) {#LoadOptions-java.lang.String-}
```
public LoadOptions(String password)
```


Initialise une nouvelle instance de la classe LoadOptions avec un mot de passe pour charger le document.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | mot de passe | java.lang.String | Le mot de passe pour charger le document |
|

### LoadOptions(boolean isLoadText, String password) {#LoadOptions-boolean-java.lang.String-}
```
public LoadOptions(boolean isLoadText, String password)
```


Initialise une nouvelle instance de la classe LoadOptions avec un indicateur signifiant que la chaîne d'entrée est un texte à comparer et un mot de passe pour charger le document.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | isLoadText | boolean | Le drapeau qui indique que la chaîne d'entrée est un texte à comparer, pas un chemin |
|
|  | mot de passe | java.lang.String | Le mot de passe pour charger le document |
|

### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.comparison.result.FileType-}
```
public LoadOptions(FileType fileType)
```


Initialise une nouvelle instance de la classe LoadOptions avec un type de fichier.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.comparison.result/filetype) | Le type du fichier |
|

### isLoadText() {#isLoadText--}
```
public boolean isLoadText()
```


Obtient un indicateur qui indique que la chaîne passée au constructeur [Comparer](../../com.groupdocs.comparison/comparer) ou à la méthode [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) est du texte de comparaison, pas des chemins de fichiers (pour la comparaison de texte uniquement).


**Returns:**
boolean - true si la chaîne d'entrée est un texte à comparer, sinon false

### setLoadText(boolean value) {#setLoadText-boolean-}
```
public void setLoadText(boolean value)
```


Définit un indicateur qui indique que la chaîne passée au constructeur [Comparer](../../com.groupdocs.comparison/comparer) ou à la méthode [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) est du texte de comparaison, pas des chemins de fichiers (pour la comparaison de texte uniquement).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | boolean | true si la chaîne d'entrée est un texte à comparer, sinon false |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Obtient un mot de passe qui sera utilisé pour charger un document.


**Returns:**
java.lang.String - le mot de passe pour charger le document

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Définit un mot de passe qui doit être utilisé pour charger un document.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.lang.String | Le mot de passe pour charger le document |
|

### getFontDirectories() {#getFontDirectories--}
```
public List<String> getFontDirectories()
```


Obtient une liste de répertoires où les fichiers de police pour charger un document sont placés.


**Returns:**
java.util.List<java.lang.String> - la liste des répertoires contenant des fichiers de police

### setFontDirectories(List<String> value) {#setFontDirectories-java.util.List-java.lang.String--}
```
public void setFontDirectories(List<String> value)
```


Définit une liste de répertoires où les fichiers de police pour charger un document sont placés.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.util.List<java.lang.String> | La liste des répertoires contenant des fichiers de police |
|

### getFileType() {#getFileType--}
```
public FileType getFileType()
```


Obtient le type d'un fichier qui est en cours de chargement.


**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the type of the file

### setFileType(FileType value) {#setFileType-com.groupdocs.comparison.result.FileType-}
```
public void setFileType(FileType value)
```


Définit le type d'un fichier qui se charge.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [FileType](../../com.groupdocs.comparison.result/filetype) | Le type du fichier |
|

