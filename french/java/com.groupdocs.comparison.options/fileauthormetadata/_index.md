---
title: "FileAuthorMetadata"
second_title: "Référence API de GroupDocs.Comparison for Java"
description: "Permet de configurer les informations sur les métadonnées de l'auteur du document."
type: docs
weight: 12
url: /fr/java/com.groupdocs.comparison.options/fileauthormetadata/
---
**Inheritance:**
java.lang.Object
```
public class FileAuthorMetadata
```

Permet de configurer les informations sur les métadonnées de l'auteur du document.


Exemple d'utilisation :

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     SaveOptions saveOptions = new SaveOptions();
     saveOptions.setCloneMetadataType(MetadataType.FILE_AUTHOR);

     final FileAuthorMetadata fileAuthorMetadata = new FileAuthorMetadata();
     fileAuthorMetadata.setAuthor("Tom");
     fileAuthorMetadata.setCompany("GroupDocs");
     fileAuthorMetadata.setLastSaveBy("Jack");

     saveOptions.setFileAuthorMetadata(fileAuthorMetadata);

     comparer.compare(resultFile, saveOptions);
 }
 
````


## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [FileAuthorMetadata()](#FileAuthorMetadata--) | Initialise une nouvelle instance de la classe FileAuthorMetadata. |
|
## Champs

| Champ | Description |
| --- | --- |
| [GROUP_DOCS](#GROUP-DOCS) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getAuthor()](#getAuthor--) | Obtient l'auteur d'un document. |
|
|  | [setAuthor(String value)](#setAuthor-java.lang.String-) | Définit l'auteur d'un document. |
|
|  | [getLastSaveBy()](#getLastSaveBy--) | Obtient le nom de la personne qui a enregistré le document pour la dernière fois. |
|
|  | [setLastSaveBy(String value)](#setLastSaveBy-java.lang.String-) | Définit le nom de la personne qui a enregistré le document pour la dernière fois. |
|
|  | [getCompany()](#getCompany--) | Obtient le nom d'une entreprise dont le document est. |
|
|  | [setCompany(String value)](#setCompany-java.lang.String-) | Définit le nom d'une entreprise dont le document est. |
|
### FileAuthorMetadata() {#FileAuthorMetadata--}
```
public FileAuthorMetadata()
```


Initialise une nouvelle instance de la classe FileAuthorMetadata.


### GROUP_DOCS {#GROUP-DOCS}
```
public static final String GROUP_DOCS
```


### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```


Obtient l'auteur d'un document.


**Returns:**
java.lang.String - l'auteur

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```


Définit l'auteur d'un document.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.lang.String | L'auteur |
|

### getLastSaveBy() {#getLastSaveBy--}
```
public final String getLastSaveBy()
```


Obtient le nom de la personne qui a enregistré le document pour la dernière fois.


**Returns:**
java.lang.String - le nom

### setLastSaveBy(String value) {#setLastSaveBy-java.lang.String-}
```
public final void setLastSaveBy(String value)
```


Définit le nom de la personne qui a enregistré le document pour la dernière fois.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.lang.String | Le nom d'une personne |
|

### getCompany() {#getCompany--}
```
public final String getCompany()
```


Obtient le nom d'une entreprise dont le document est.


**Returns:**
java.lang.String - le nom d'une entreprise

### setCompany(String value) {#setCompany-java.lang.String-}
```
public final void setCompany(String value)
```


Définit le nom d'une entreprise dont le document est.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.lang.String | Le nom d'une entreprise |
|

