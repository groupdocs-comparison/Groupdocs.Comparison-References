---
title: "FileAuthorMetadata"
second_title: "GroupDocs.Comparison für Java API-Referenz"
description: "Ermöglicht die Konfiguration von Informationen über die Autor-Metadaten des Dokuments."
type: docs
weight: 12
url: /de/java/com.groupdocs.comparison.options/fileauthormetadata/
---
**Inheritance:**
java.lang.Object
```
public class FileAuthorMetadata
```

Ermöglicht die Konfiguration von Informationen über die Autor-Metadaten des Dokuments.


Beispielverwendung:

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


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [FileAuthorMetadata()](#FileAuthorMetadata--) | Initialisiert eine neue Instanz der Klasse FileAuthorMetadata. |
|
## Felder

| Feld | Beschreibung |
| --- | --- |
| [GROUP_DOCS](#GROUP-DOCS) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getAuthor()](#getAuthor--) | Ermittelt den Autor eines Dokuments. |
|
|  | [setAuthor(String value)](#setAuthor-java.lang.String-) | Legt den Autor eines Dokuments fest. |
|
|  | [getLastSaveBy()](#getLastSaveBy--) | Ermittelt den Namen der Person, die das Dokument zuletzt gespeichert hat. |
|
|  | [setLastSaveBy(String value)](#setLastSaveBy-java.lang.String-) | Legt den Namen der Person fest, die das Dokument zuletzt gespeichert hat. |
|
|  | [getCompany()](#getCompany--) | Ermittelt den Namen eines Unternehmens, dessen Dokument ist. |
|
|  | [setCompany(String value)](#setCompany-java.lang.String-) | Setzt den Namen eines Unternehmens, dessen Dokument ist. |
|
### FileAuthorMetadata() {#FileAuthorMetadata--}
```
public FileAuthorMetadata()
```


Initialisiert eine neue Instanz der Klasse FileAuthorMetadata.


### GROUP_DOCS {#GROUP-DOCS}
```
public static final String GROUP_DOCS
```


### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```


Ermittelt den Autor eines Dokuments.


**Returns:**
java.lang.String - der Autor

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```


Legt den Autor eines Dokuments fest.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | java.lang.String | Der Autor |
|

### getLastSaveBy() {#getLastSaveBy--}
```
public final String getLastSaveBy()
```


Ermittelt den Namen der Person, die das Dokument zuletzt gespeichert hat.


**Returns:**
java.lang.String - der Name

### setLastSaveBy(String value) {#setLastSaveBy-java.lang.String-}
```
public final void setLastSaveBy(String value)
```


Legt den Namen der Person fest, die das Dokument zuletzt gespeichert hat.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | java.lang.String | Der Name einer Person |
|

### getCompany() {#getCompany--}
```
public final String getCompany()
```


Ermittelt den Namen eines Unternehmens, dessen Dokument ist.


**Returns:**
java.lang.String - der Name eines Unternehmens

### setCompany(String value) {#setCompany-java.lang.String-}
```
public final void setCompany(String value)
```


Setzt den Namen eines Unternehmens, dessen Dokument ist.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | java.lang.String | Der Name eines Unternehmens |
|

