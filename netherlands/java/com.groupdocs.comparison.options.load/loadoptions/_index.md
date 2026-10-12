---
title: "LoadOptions"
second_title: "GroupDocs.Comparison voor Java API-referentie"
description: "Staat toe extra opties op te geven bij het laden van een document."
type: docs
weight: 10
url: /nl/java/com.groupdocs.comparison.options.load/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

Staat toe extra opties op te geven bij het laden van een document.


Voorbeeldgebruik:

````

 final LoadOptions loadOptions = new LoadOptions();
 loadOptions.setPassword("passw");
 loadOptions.setFileType(FileType.PDF);

 try (Comparer comparer = new Comparer(sourceFile, loadOptions)) {
    comparer.add(targetFile);

    comparer.compare(resultFile);
 }
 
````


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [LoadOptions()](#LoadOptions--) | Initialiseert een nieuw exemplaar van de LoadOptions-klasse. |
|
|  | [LoadOptions(boolean isLoadText)](#LoadOptions-boolean-) | Initialiseert een nieuw exemplaar van de LoadOptions-klasse met een vlag die aangeeft dat de invoertekst een te vergelijken tekst is, geen pad. |
|
|  | [LoadOptions(String password)](#LoadOptions-java.lang.String-) | Initialiseert een nieuw exemplaar van de LoadOptions-klasse met een wachtwoord om een document te laden. |
|
|  | [LoadOptions(boolean isLoadText, String password)](#LoadOptions-boolean-java.lang.String-) | Initialiseert een nieuw exemplaar van de LoadOptions-klasse met een vlag die aangeeft dat de invoertekst een te vergelijken tekst is en een wachtwoord om een document te laden. |
|
|  | [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.comparison.result.FileType-) | Initialiseert een nieuw exemplaar van de LoadOptions-klasse met een type bestand. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [isLoadText()](#isLoadText--) | Haalt een vlag op die aangeeft dat de string die aan de constructor van [Comparer](../../com.groupdocs.comparison/comparer) of aan de methode [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) wordt doorgegeven, vergelijkingstekst is, geen bestandspaden (alleen voor tekstvergelijking). |
|
|  | [setLoadText(boolean value)](#setLoadText-boolean-) | Stelt een vlag in die aangeeft dat de string die aan de constructor van [Comparer](../../com.groupdocs.comparison/comparer) of aan de methode [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) wordt doorgegeven, vergelijkingstekst is, geen bestandspaden (alleen voor tekstvergelijking). |
|
|  | [getPassword()](#getPassword--) | Haalt een wachtwoord op dat wordt gebruikt om een document te laden. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Stelt een wachtwoord in dat moet worden gebruikt om een document te laden. |
|
|  | [getFontDirectories()](#getFontDirectories--) | Haalt een lijst op van mappen waarin lettertypebestanden staan die nodig zijn om een document te laden. |
|
|  | [setFontDirectories(List<String> value)](#setFontDirectories-java.util.List-java.lang.String--) | Stelt een lijst in van mappen waarin lettertypebestanden staan die nodig zijn om een document te laden. |
|
|  | [getFileType()](#getFileType--) | Haalt een type van een bestand op dat wordt geladen. |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.comparison.result.FileType-) | Stelt een type van een bestand in dat wordt geladen. |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


Initialiseert een nieuw exemplaar van de LoadOptions-klasse.


### LoadOptions(boolean isLoadText) {#LoadOptions-boolean-}
```
public LoadOptions(boolean isLoadText)
```


Initialiseert een nieuw exemplaar van de LoadOptions-klasse met een vlag die aangeeft dat de invoertekst een te vergelijken tekst is, geen pad.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | isLoadText | boolean | De vlag die aangeeft dat de invoerreeks een te vergelijken tekst is, geen pad |
|

### LoadOptions(String password) {#LoadOptions-java.lang.String-}
```
public LoadOptions(String password)
```


Initialiseert een nieuw exemplaar van de LoadOptions-klasse met een wachtwoord om een document te laden.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | wachtwoord | java.lang.String | Het wachtwoord om het document te laden |
|

### LoadOptions(boolean isLoadText, String password) {#LoadOptions-boolean-java.lang.String-}
```
public LoadOptions(boolean isLoadText, String password)
```


Initialiseert een nieuw exemplaar van de LoadOptions-klasse met een vlag die aangeeft dat de invoertekst een te vergelijken tekst is en een wachtwoord om een document te laden.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | isLoadText | boolean | De vlag die aangeeft dat de invoerreeks een te vergelijken tekst is, geen pad |
|
|  | wachtwoord | java.lang.String | Het wachtwoord om het document te laden |
|

### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.comparison.result.FileType-}
```
public LoadOptions(FileType fileType)
```


Initialiseert een nieuw exemplaar van de LoadOptions-klasse met een type bestand.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.comparison.result/filetype) | Het type van het bestand |
|

### isLoadText() {#isLoadText--}
```
public boolean isLoadText()
```


Haalt een vlag op die aangeeft dat de string die aan de constructor van [Comparer](../../com.groupdocs.comparison/comparer) of aan de methode [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) wordt doorgegeven, vergelijkingstekst is, geen bestandspaden (alleen voor tekstvergelijking).


**Returns:**
boolean - true als de invoerreeks een te vergelijken tekst is, anders false

### setLoadText(boolean value) {#setLoadText-boolean-}
```
public void setLoadText(boolean value)
```


Stelt een vlag in die aangeeft dat de string die aan de constructor van [Comparer](../../com.groupdocs.comparison/comparer) of aan de methode [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) wordt doorgegeven, vergelijkingstekst is, geen bestandspaden (alleen voor tekstvergelijking).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | boolean | true als de invoerreeks een te vergelijken tekst is, anders false |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Haalt een wachtwoord op dat wordt gebruikt om een document te laden.


**Returns:**
java.lang.String - het wachtwoord om het document te laden

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Stelt een wachtwoord in dat moet worden gebruikt om een document te laden.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.lang.String | Het wachtwoord om het document te laden |
|

### getFontDirectories() {#getFontDirectories--}
```
public List<String> getFontDirectories()
```


Haalt een lijst op van mappen waarin lettertypebestanden staan die nodig zijn om een document te laden.


**Returns:**
java.util.List<java.lang.String> - de lijst met mappen met lettertypebestanden

### setFontDirectories(List<String> value) {#setFontDirectories-java.util.List-java.lang.String--}
```
public void setFontDirectories(List<String> value)
```


Stelt een lijst in van mappen waarin lettertypebestanden staan die nodig zijn om een document te laden.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.util.List<java.lang.String> | De lijst met mappen met lettertypebestanden |
|

### getFileType() {#getFileType--}
```
public FileType getFileType()
```


Haalt een type van een bestand op dat wordt geladen.


**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the type of the file

### setFileType(FileType value) {#setFileType-com.groupdocs.comparison.result.FileType-}
```
public void setFileType(FileType value)
```


Stelt een type van een bestand in dat wordt geladen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [FileType](../../com.groupdocs.comparison.result/filetype) | Het type van het bestand |
|

