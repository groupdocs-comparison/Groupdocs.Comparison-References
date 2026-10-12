---
title: "SaveOptions"
second_title: "GroupDocs.Comparison för Java API-referens"
description: "Tillåter att specificera ytterligare alternativ när ett dokument sparas."
type: docs
weight: 10
url: /sv/java/com.groupdocs.comparison.options.save/saveoptions/
---
**Inheritance:**
java.lang.Object
```
public class SaveOptions
```

Tillåter att specificera ytterligare alternativ när ett dokument sparas.


Exempel på användning:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    final SaveOptions saveOptions = new SaveOptions();
    saveOptions.setPassword("passw");

    comparer.compare(resultFile, saveOptions);
 }
 
````


## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [SaveOptions()](#SaveOptions--) | Initierar en ny instans av klassen SaveOptions. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getCloneMetadataType()](#getCloneMetadataType--) | Hämtar en strategi för bearbetning av metadata vid sparande av resultatsdokumentet. |
|
|  | [setCloneMetadataType(MetadataType value)](#setCloneMetadataType-com.groupdocs.comparison.options.enums.MetadataType-) | Ställer in en strategi för bearbetning av metadata vid sparande av resultatsdokumentet. |
|
|  | [getFileAuthorMetadata()](#getFileAuthorMetadata--) | Hämtar ett metadataobjekt som kommer att sättas in i resultatsdokumentet när [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) är satt till [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR). |
|
|  | [setFileAuthorMetadata(FileAuthorMetadata value)](#setFileAuthorMetadata-com.groupdocs.comparison.options.FileAuthorMetadata-) | Ställer in ett metadataobjekt som ska sättas in i resultatsdokumentet när [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) är satt till [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR). |
|
|  | [getPassword()](#getPassword--) | Hämtar ett lösenord för resultatsdokumentet. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Ställer in ett lösenord för resultatsdokumentet. |
|
|  | [getFolderPath()](#getFolderPath--) | Hämtar en mappväg dit resultatsbilderna kommer att sparas. |
|
|  | [setFolderPath(String value)](#setFolderPath-java.lang.String-) | Ställer in en mappväg dit resultatsbilderna ska sparas. |
|
|  | [setFolderPath(Path value)](#setFolderPath-java.nio.file.Path-) | Ställer in en mappväg dit resultatsbilderna ska sparas. |
|
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```


Initierar en ny instans av klassen SaveOptions.


### getCloneMetadataType() {#getCloneMetadataType--}
```
public final MetadataType getCloneMetadataType()
```


Hämtar en strategi för bearbetning av metadata vid sparande av resultatsdokumentet.
Möjliga värden finns i enum [MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype)


**Returns:**
[MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) - the stragegy of processing metadata

### setCloneMetadataType(MetadataType value) {#setCloneMetadataType-com.groupdocs.comparison.options.enums.MetadataType-}
```
public final void setCloneMetadataType(MetadataType value)
```


Ställer in en strategi för bearbetning av metadata vid sparande av resultatsdokumentet.
Möjliga värden finns i enum [MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) | Strategin för bearbetning av metadata |
|

### getFileAuthorMetadata() {#getFileAuthorMetadata--}
```
public final FileAuthorMetadata getFileAuthorMetadata()
```


Hämtar ett metadataobjekt som kommer att sättas in i resultatsdokumentet när [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) är satt till [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR).


**Returns:**
[FileAuthorMetadata](../../com.groupdocs.comparison.options/fileauthormetadata) - the metadata object

### setFileAuthorMetadata(FileAuthorMetadata value) {#setFileAuthorMetadata-com.groupdocs.comparison.options.FileAuthorMetadata-}
```
public final void setFileAuthorMetadata(FileAuthorMetadata value)
```


Ställer in ett metadataobjekt som ska sättas in i resultatsdokumentet när [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) är satt till [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [FileAuthorMetadata](../../com.groupdocs.comparison.options/fileauthormetadata) | Metadataobjektet |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Hämtar ett lösenord för resultatsdokumentet.


**Returns:**
java.lang.String - lösenordet

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Ställer in ett lösenord för resultatsdokumentet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | java.lang.String | Lösenordet |
|

### getFolderPath() {#getFolderPath--}
```
public final String getFolderPath()
```


Hämtar en mappväg dit resultatsbilderna kommer att sparas.
Används endast för bildjämförelse.


**Returns:**
java.lang.String - mappvägen för att spara resultatsbilder

### setFolderPath(String value) {#setFolderPath-java.lang.String-}
```
public final void setFolderPath(String value)
```


Ställer in en mappväg dit resultatsbilderna ska sparas.
Används endast för bildjämförelse.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | java.lang.String | Mappvägen för att spara resultatsbilder |
|

### setFolderPath(Path value) {#setFolderPath-java.nio.file.Path-}
```
public final void setFolderPath(Path value)
```


Ställer in en mappväg dit resultatsbilderna ska sparas.
Används endast för bildjämförelse.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | java.nio.file.Path | Mappvägen för att spara resultatsbilder |
|

