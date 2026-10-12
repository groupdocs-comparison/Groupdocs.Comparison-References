---
title: "SaveOptions"
second_title: "Référence API de GroupDocs.Comparison for Java"
description: "Permet de spécifier des options supplémentaires lors de l'enregistrement d'un document."
type: docs
weight: 10
url: /fr/java/com.groupdocs.comparison.options.save/saveoptions/
---
**Inheritance:**
java.lang.Object
```
public class SaveOptions
```

Permet de spécifier des options supplémentaires lors de l'enregistrement d'un document.


Exemple d'utilisation :

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    final SaveOptions saveOptions = new SaveOptions();
    saveOptions.setPassword("passw");

    comparer.compare(resultFile, saveOptions);
 }
 
````


## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [SaveOptions()](#SaveOptions--) | Initialise une nouvelle instance de la classe SaveOptions. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getCloneMetadataType()](#getCloneMetadataType--) | Obtient une stratégie de traitement des métadonnées lors de l'enregistrement du document résultat. |
|
|  | [setCloneMetadataType(MetadataType value)](#setCloneMetadataType-com.groupdocs.comparison.options.enums.MetadataType-) | Définit une stragey de traitement des métadonnées lors de l'enregistrement du document résultat. |
|
|  | [getFileAuthorMetadata()](#getFileAuthorMetadata--) | Obtient un objet de métadonnées qui sera placé dans le document résultat lorsque [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) est défini sur [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR). |
|
|  | [setFileAuthorMetadata(FileAuthorMetadata value)](#setFileAuthorMetadata-com.groupdocs.comparison.options.FileAuthorMetadata-) | Définit un objet de métadonnées qui doit être placé dans le document résultat lorsque [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) est défini sur [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR). |
|
|  | [getPassword()](#getPassword--) | Obtient un mot de passe pour le document résultat. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Définit un mot de passe pour le document résultat. |
|
|  | [getFolderPath()](#getFolderPath--) | Obtient le chemin du dossier où les images résultantes seront enregistrées. |
|
|  | [setFolderPath(String value)](#setFolderPath-java.lang.String-) | Définit le chemin du dossier où les images résultantes doivent être enregistrées. |
|
|  | [setFolderPath(Path value)](#setFolderPath-java.nio.file.Path-) | Définit le chemin du dossier où les images résultantes doivent être enregistrées. |
|
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```


Initialise une nouvelle instance de la classe SaveOptions.


### getCloneMetadataType() {#getCloneMetadataType--}
```
public final MetadataType getCloneMetadataType()
```


Obtient une stratégie de traitement des métadonnées lors de l'enregistrement du document résultat.
Les valeurs possibles se trouvent dans l'énumération [MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype)


**Returns:**
[MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) - the stragegy of processing metadata

### setCloneMetadataType(MetadataType value) {#setCloneMetadataType-com.groupdocs.comparison.options.enums.MetadataType-}
```
public final void setCloneMetadataType(MetadataType value)
```


Définit une stragey de traitement des métadonnées lors de l'enregistrement du document résultat.
Les valeurs possibles se trouvent dans l'énumération [MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) | La stragegy de traitement des métadonnées |
|

### getFileAuthorMetadata() {#getFileAuthorMetadata--}
```
public final FileAuthorMetadata getFileAuthorMetadata()
```


Obtient un objet de métadonnées qui sera placé dans le document résultat lorsque [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) est défini sur [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR).


**Returns:**
[FileAuthorMetadata](../../com.groupdocs.comparison.options/fileauthormetadata) - the metadata object

### setFileAuthorMetadata(FileAuthorMetadata value) {#setFileAuthorMetadata-com.groupdocs.comparison.options.FileAuthorMetadata-}
```
public final void setFileAuthorMetadata(FileAuthorMetadata value)
```


Définit un objet de métadonnées qui doit être placé dans le document résultat lorsque [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) est défini sur [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [FileAuthorMetadata](../../com.groupdocs.comparison.options/fileauthormetadata) | L'objet de métadonnées |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Obtient un mot de passe pour le document résultat.


**Returns:**
java.lang.String - le mot de passe

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Définit un mot de passe pour le document résultat.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.lang.String | Le mot de passe |
|

### getFolderPath() {#getFolderPath--}
```
public final String getFolderPath()
```


Obtient le chemin du dossier où les images résultantes seront enregistrées.
Utilisé uniquement pour la comparaison d'images.


**Returns:**
java.lang.String - le chemin du dossier pour enregistrer les images résultantes

### setFolderPath(String value) {#setFolderPath-java.lang.String-}
```
public final void setFolderPath(String value)
```


Définit le chemin du dossier où les images résultantes doivent être enregistrées.
Utilisé uniquement pour la comparaison d'images.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.lang.String | Le chemin du dossier pour enregistrer les images résultantes |
|

### setFolderPath(Path value) {#setFolderPath-java.nio.file.Path-}
```
public final void setFolderPath(Path value)
```


Définit le chemin du dossier où les images résultantes doivent être enregistrées.
Utilisé uniquement pour la comparaison d'images.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.nio.file.Path | Le chemin du dossier pour enregistrer les images résultantes |
|

