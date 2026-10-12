---
title: "FileAuthorMetadata"
second_title: "GroupDocs.Comparison voor Java API-referentie"
description: "Staat toe om informatie over de auteursmetadata van documenten te configureren."
type: docs
weight: 12
url: /nl/java/com.groupdocs.comparison.options/fileauthormetadata/
---
**Inheritance:**
java.lang.Object
```
public class FileAuthorMetadata
```

Staat toe informatie over de auteurmetadata van het document te configureren.


Voorbeeldgebruik:

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


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [FileAuthorMetadata()](#FileAuthorMetadata--) | Initialiseert een nieuw exemplaar van de FileAuthorMetadata-klasse. |
|
## Velden

| Veld | Beschrijving |
| --- | --- |
| [GROUP_DOCS](#GROUP-DOCS) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getAuthor()](#getAuthor--) | Haalt de auteur van een document op. |
|
|  | [setAuthor(String value)](#setAuthor-java.lang.String-) | Stelt de auteur van een document in. |
|
|  | [getLastSaveBy()](#getLastSaveBy--) | Haalt de naam op van de persoon die het document voor het laatst heeft opgeslagen. |
|
|  | [setLastSaveBy(String value)](#setLastSaveBy-java.lang.String-) | Stelt de naam in van de persoon die het document voor het laatst heeft opgeslagen. |
|
|  | [getCompany()](#getCompany--) | Haalt de naam van een bedrijf op waarvan het document is. |
|
|  | [setCompany(String value)](#setCompany-java.lang.String-) | Stelt de naam van een bedrijf in waarvan het document is. |
|
### FileAuthorMetadata() {#FileAuthorMetadata--}
```
public FileAuthorMetadata()
```


Initialiseert een nieuw exemplaar van de FileAuthorMetadata-klasse.


### GROUP_DOCS {#GROUP-DOCS}
```
public static final String GROUP_DOCS
```


### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```


Haalt de auteur van een document op.


**Returns:**
java.lang.String - de auteur

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```


Stelt de auteur van een document in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.lang.String | De auteur |
|

### getLastSaveBy() {#getLastSaveBy--}
```
public final String getLastSaveBy()
```


Haalt de naam op van de persoon die het document voor het laatst heeft opgeslagen.


**Returns:**
java.lang.String - de naam

### setLastSaveBy(String value) {#setLastSaveBy-java.lang.String-}
```
public final void setLastSaveBy(String value)
```


Stelt de naam in van de persoon die het document voor het laatst heeft opgeslagen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.lang.String | De naam van een persoon |
|

### getCompany() {#getCompany--}
```
public final String getCompany()
```


Haalt de naam van een bedrijf op waarvan het document is.


**Returns:**
java.lang.String - de naam van een bedrijf

### setCompany(String value) {#setCompany-java.lang.String-}
```
public final void setCompany(String value)
```


Stelt de naam van een bedrijf in waarvan het document is.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.lang.String | De naam van een bedrijf |
|

