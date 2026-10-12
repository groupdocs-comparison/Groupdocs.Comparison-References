---
title: "SaveOptions"
second_title: "GroupDocs.Comparison voor Java API-referentie"
description: "Staat toe om extra opties op te geven bij het opslaan van een document."
type: docs
weight: 10
url: /nl/java/com.groupdocs.comparison.options.save/saveoptions/
---
**Inheritance:**
java.lang.Object
```
public class SaveOptions
```

Staat toe om extra opties op te geven bij het opslaan van een document.


Voorbeeldgebruik:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    final SaveOptions saveOptions = new SaveOptions();
    saveOptions.setPassword("passw");

    comparer.compare(resultFile, saveOptions);
 }
 
````


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [SaveOptions()](#SaveOptions--) | Initialiseert een nieuw exemplaar van de SaveOptions-klasse. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getCloneMetadataType()](#getCloneMetadataType--) | Haalt een strategie op voor het verwerken van metadata bij het opslaan van het resultaatdocument. |
|
|  | [setCloneMetadataType(MetadataType value)](#setCloneMetadataType-com.groupdocs.comparison.options.enums.MetadataType-) | Stelt een strategie in voor het verwerken van metadata bij het opslaan van het resultaatdocument. |
|
|  | [getFileAuthorMetadata()](#getFileAuthorMetadata--) | Haalt een metadata-object op dat in het resultaatdocument wordt geplaatst wanneer [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) is ingesteld op [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR). |
|
|  | [setFileAuthorMetadata(FileAuthorMetadata value)](#setFileAuthorMetadata-com.groupdocs.comparison.options.FileAuthorMetadata-) | Stelt een metadata-object in dat in het resultaatdocument moet worden geplaatst wanneer [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) is ingesteld op [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR). |
|
|  | [getPassword()](#getPassword--) | Haalt een wachtwoord op voor het resultaatdocument. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Stelt een wachtwoord in voor het resultaatdocument. |
|
|  | [getFolderPath()](#getFolderPath--) | Haalt een mappad op waar de resultaatafbeeldingen worden opgeslagen. |
|
|  | [setFolderPath(String value)](#setFolderPath-java.lang.String-) | Stelt een mappad in waar de resultaatafbeeldingen moeten worden opgeslagen. |
|
|  | [setFolderPath(Path value)](#setFolderPath-java.nio.file.Path-) | Stelt een mappad in waar de resultaatafbeeldingen moeten worden opgeslagen. |
|
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```


Initialiseert een nieuw exemplaar van de SaveOptions-klasse.


### getCloneMetadataType() {#getCloneMetadataType--}
```
public final MetadataType getCloneMetadataType()
```


Haalt een strategie op voor het verwerken van metadata bij het opslaan van het resultaatdocument.
Mogelijke waarden staan in de enum [MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype)


**Returns:**
[MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) - the stragegy of processing metadata

### setCloneMetadataType(MetadataType value) {#setCloneMetadataType-com.groupdocs.comparison.options.enums.MetadataType-}
```
public final void setCloneMetadataType(MetadataType value)
```


Stelt een strategie in voor het verwerken van metadata bij het opslaan van het resultaatdocument.
Mogelijke waarden staan in de enum [MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) | De strategie voor het verwerken van metadata |
|

### getFileAuthorMetadata() {#getFileAuthorMetadata--}
```
public final FileAuthorMetadata getFileAuthorMetadata()
```


Haalt een metadata-object op dat in het resultaatdocument wordt geplaatst wanneer [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) is ingesteld op [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR).


**Returns:**
[FileAuthorMetadata](../../com.groupdocs.comparison.options/fileauthormetadata) - the metadata object

### setFileAuthorMetadata(FileAuthorMetadata value) {#setFileAuthorMetadata-com.groupdocs.comparison.options.FileAuthorMetadata-}
```
public final void setFileAuthorMetadata(FileAuthorMetadata value)
```


Stelt een metadata-object in dat in het resultaatdocument moet worden geplaatst wanneer [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) is ingesteld op [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [FileAuthorMetadata](../../com.groupdocs.comparison.options/fileauthormetadata) | Het metadata-object |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Haalt een wachtwoord op voor het resultaatdocument.


**Returns:**
java.lang.String - het wachtwoord

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Stelt een wachtwoord in voor het resultaatdocument.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.lang.String | Het wachtwoord |
|

### getFolderPath() {#getFolderPath--}
```
public final String getFolderPath()
```


Haalt een mappad op waar de resultaatafbeeldingen worden opgeslagen.
Alleen gebruikt voor beeldvergelijking.


**Returns:**
java.lang.String - het mappad om resultaatafbeeldingen op te slaan

### setFolderPath(String value) {#setFolderPath-java.lang.String-}
```
public final void setFolderPath(String value)
```


Stelt een mappad in waar de resultaatafbeeldingen moeten worden opgeslagen.
Alleen gebruikt voor beeldvergelijking.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.lang.String | Het mappad om resultaatafbeeldingen op te slaan |
|

### setFolderPath(Path value) {#setFolderPath-java.nio.file.Path-}
```
public final void setFolderPath(Path value)
```


Stelt een mappad in waar de resultaatafbeeldingen moeten worden opgeslagen.
Alleen gebruikt voor beeldvergelijking.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.nio.file.Path | Het mappad om resultaatafbeeldingen op te slaan |
|

