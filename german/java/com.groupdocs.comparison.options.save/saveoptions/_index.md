---
title: "SaveOptions"
second_title: "GroupDocs.Comparison für Java API-Referenz"
description: "Ermöglicht das Festlegen zusätzlicher Optionen beim Speichern eines Dokuments."
type: docs
weight: 10
url: /de/java/com.groupdocs.comparison.options.save/saveoptions/
---
**Inheritance:**
java.lang.Object
```
public class SaveOptions
```

Ermöglicht das Festlegen zusätzlicher Optionen beim Speichern eines Dokuments.


Beispielverwendung:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    final SaveOptions saveOptions = new SaveOptions();
    saveOptions.setPassword("passw");

    comparer.compare(resultFile, saveOptions);
 }
 
````


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [SaveOptions()](#SaveOptions--) | Initialisiert eine neue Instanz der Klasse SaveOptions. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getCloneMetadataType()](#getCloneMetadataType--) | Liefert eine Strategie zur Verarbeitung von Metadaten beim Speichern des Ergebnisdokuments. |
|
|  | [setCloneMetadataType(MetadataType value)](#setCloneMetadataType-com.groupdocs.comparison.options.enums.MetadataType-) | Legt eine Strategie zur Verarbeitung von Metadaten beim Speichern des Ergebnisdokuments fest. |
|
|  | [getFileAuthorMetadata()](#getFileAuthorMetadata--) | Liefert ein Metadatenobjekt, das in das Ergebnisdokument eingefügt wird, wenn [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) auf [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR) gesetzt ist. |
|
|  | [setFileAuthorMetadata(FileAuthorMetadata value)](#setFileAuthorMetadata-com.groupdocs.comparison.options.FileAuthorMetadata-) | Legt ein Metadatenobjekt fest, das in das Ergebnisdokument eingefügt werden soll, wenn [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) auf [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR) gesetzt ist. |
|
|  | [getPassword()](#getPassword--) | Liefert ein Passwort für das Ergebnisdokument. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Legt ein Passwort für das Ergebnisdokument fest. |
|
|  | [getFolderPath()](#getFolderPath--) | Liefert einen Ordnerpfad, in dem Ergebnisbilder gespeichert werden. |
|
|  | [setFolderPath(String value)](#setFolderPath-java.lang.String-) | Legt einen Ordnerpfad fest, in dem Ergebnisbilder gespeichert werden sollen. |
|
|  | [setFolderPath(Path value)](#setFolderPath-java.nio.file.Path-) | Legt einen Ordnerpfad fest, in dem Ergebnisbilder gespeichert werden sollen. |
|
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```


Initialisiert eine neue Instanz der Klasse SaveOptions.


### getCloneMetadataType() {#getCloneMetadataType--}
```
public final MetadataType getCloneMetadataType()
```


Liefert eine Strategie zur Verarbeitung von Metadaten beim Speichern des Ergebnisdokuments.
Mögliche Werte befinden sich im Enum [MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype)


**Returns:**
[MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) - the stragegy of processing metadata

### setCloneMetadataType(MetadataType value) {#setCloneMetadataType-com.groupdocs.comparison.options.enums.MetadataType-}
```
public final void setCloneMetadataType(MetadataType value)
```


Legt eine Strategie zur Verarbeitung von Metadaten beim Speichern des Ergebnisdokuments fest.
Mögliche Werte befinden sich im Enum [MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) | Die Strategie zur Verarbeitung von Metadaten |
|

### getFileAuthorMetadata() {#getFileAuthorMetadata--}
```
public final FileAuthorMetadata getFileAuthorMetadata()
```


Liefert ein Metadatenobjekt, das in das Ergebnisdokument eingefügt wird, wenn [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) auf [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR) gesetzt ist.


**Returns:**
[FileAuthorMetadata](../../com.groupdocs.comparison.options/fileauthormetadata) - the metadata object

### setFileAuthorMetadata(FileAuthorMetadata value) {#setFileAuthorMetadata-com.groupdocs.comparison.options.FileAuthorMetadata-}
```
public final void setFileAuthorMetadata(FileAuthorMetadata value)
```


Legt ein Metadatenobjekt fest, das in das Ergebnisdokument eingefügt werden soll, wenn [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) auf [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR) gesetzt ist.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [FileAuthorMetadata](../../com.groupdocs.comparison.options/fileauthormetadata) | Das Metadatenobjekt |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Liefert ein Passwort für das Ergebnisdokument.


**Returns:**
java.lang.String - das Passwort

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Legt ein Passwort für das Ergebnisdokument fest.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | java.lang.String | Das Passwort |
|

### getFolderPath() {#getFolderPath--}
```
public final String getFolderPath()
```


Liefert einen Ordnerpfad, in dem Ergebnisbilder gespeichert werden.
Nur für den Bildvergleich verwendet.


**Returns:**
java.lang.String - der Ordnerpfad zum Speichern der Ergebnisbilder

### setFolderPath(String value) {#setFolderPath-java.lang.String-}
```
public final void setFolderPath(String value)
```


Legt einen Ordnerpfad fest, in dem Ergebnisbilder gespeichert werden sollen.
Nur für den Bildvergleich verwendet.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | java.lang.String | Der Ordnerpfad zum Speichern der Ergebnisbilder |
|

### setFolderPath(Path value) {#setFolderPath-java.nio.file.Path-}
```
public final void setFolderPath(Path value)
```


Legt einen Ordnerpfad fest, in dem Ergebnisbilder gespeichert werden sollen.
Nur für den Bildvergleich verwendet.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | java.nio.file.Path | Der Ordnerpfad zum Speichern der Ergebnisbilder |
|

