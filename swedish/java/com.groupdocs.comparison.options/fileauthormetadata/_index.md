---
title: "FileAuthorMetadata"
second_title: "GroupDocs.Comparison för Java API-referens"
description: "Tillåter konfiguration av information om dokumentets författarmetadata."
type: docs
weight: 12
url: /sv/java/com.groupdocs.comparison.options/fileauthormetadata/
---
**Inheritance:**
java.lang.Object
```
public class FileAuthorMetadata
```

Tillåter att konfigurera information om dokumentets författarmetadata.


Exempel på användning:

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


## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [FileAuthorMetadata()](#FileAuthorMetadata--) | Initierar en ny instans av klassen FileAuthorMetadata. |
|
## Fält

| Fält | Beskrivning |
| --- | --- |
| [GROUP_DOCS](#GROUP-DOCS) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getAuthor()](#getAuthor--) | Hämtar författaren till ett dokument. |
|
|  | [setAuthor(String value)](#setAuthor-java.lang.String-) | Ställer in författaren till ett dokument. |
|
|  | [getLastSaveBy()](#getLastSaveBy--) | Hämtar namnet på personen som senast sparade dokumentet. |
|
|  | [setLastSaveBy(String value)](#setLastSaveBy-java.lang.String-) | Ställer in namnet på personen som senast sparade dokumentet. |
|
|  | [getCompany()](#getCompany--) | Hämtar namn på ett företag vars dokument är. |
|
|  | [setCompany(String value)](#setCompany-java.lang.String-) | Ställer in namn på ett företag vars dokument är. |
|
### FileAuthorMetadata() {#FileAuthorMetadata--}
```
public FileAuthorMetadata()
```


Initierar en ny instans av klassen FileAuthorMetadata.


### GROUP_DOCS {#GROUP-DOCS}
```
public static final String GROUP_DOCS
```


### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```


Hämtar författaren till ett dokument.


**Returns:**
java.lang.String - författaren

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```


Ställer in författaren till ett dokument.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | java.lang.String | Författaren |
|

### getLastSaveBy() {#getLastSaveBy--}
```
public final String getLastSaveBy()
```


Hämtar namnet på personen som senast sparade dokumentet.


**Returns:**
java.lang.String - namnet

### setLastSaveBy(String value) {#setLastSaveBy-java.lang.String-}
```
public final void setLastSaveBy(String value)
```


Ställer in namnet på personen som senast sparade dokumentet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | java.lang.String | Namnet på en person |
|

### getCompany() {#getCompany--}
```
public final String getCompany()
```


Hämtar namn på ett företag vars dokument är.


**Returns:**
java.lang.String - namnet på ett företag

### setCompany(String value) {#setCompany-java.lang.String-}
```
public final void setCompany(String value)
```


Ställer in namn på ett företag vars dokument är.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | java.lang.String | Namnet på ett företag |
|

