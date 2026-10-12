---
title: "RevisionHandler"
second_title: "GroupDocs.Comparison voor Java API-referentie"
description: "Stelt een klasse voor die de verwerking van revisies regelt."
type: docs
weight: 11
url: /nl/java/com.groupdocs.comparison.words.revision/revisionhandler/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class RevisionHandler implements Closeable
```

Stelt een klasse voor die de verwerking van revisies regelt.


De RevisionHandler-klasse stelt u in staat om met revisies in documenten te werken.
Het biedt methoden om de lijst met revisies op te halen, wijzigingen op revisies toe te passen en het gewijzigde document op te slaan.


Voorbeeldgebruik:

````

 try (RevisionHandler revisionHandler = new RevisionHandler(sourceFile)) {
     List revisionList = revisionHandler.getRevisions();

     for (RevisionInfo revisionInfo : revisionList) {
         if (revisionInfo.getType() == RevisionType.DELETION)
             // Set an action to be applied to the revision
             revisionInfo.setAction(RevisionAction.Accept);
     }
     // Create an instance of ApplyRevisionOptions
     ApplyRevisionOptions revisionChanges = new ApplyRevisionOptions();
     revisionChanges.setChanges(revisionList);
     // Apply the revisions using the options
     revisionHandler.applyRevisionChanges(resultFile, revisionChanges);
 }
 
````


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [RevisionHandler(String filePath)](#RevisionHandler-java.lang.String-) | Initialiseert een nieuw exemplaar van de RevisionHandler-klasse met het pad naar het bestand dat revisies bevat. |
|
|  | [RevisionHandler(Path filePath)](#RevisionHandler-java.nio.file.Path-) | Initialiseert een nieuw exemplaar van de RevisionHandler-klasse met het pad naar het bestand dat revisies bevat. |
|
|  | [RevisionHandler(InputStream file, FileType fileType)](#RevisionHandler-java.io.InputStream-com.groupdocs.comparison.result.FileType-) | Initialiseert een nieuw exemplaar van de RevisionHandler-klasse met een bestandsstroom die revisies bevat. |
|
|  | [RevisionHandler(Document document)](#RevisionHandler-com.aspose.words.Document-) | Initialiseert een nieuw exemplaar van de RevisionHandler-klasse met een document. |
|
## Velden

| Veld | Beschrijving |
| --- | --- |
| [SOURCE_PATH_IS_NULL](#SOURCE-PATH-IS-NULL) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getRevisions()](#getRevisions--) | Haalt de lijst met alle revisies op. |
|
|  | [applyRevisionChanges(ApplyRevisionOptions changes)](#applyRevisionChanges-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | Verwerkt wijzigingen in revisies en past ze toe op het originele bestand. |
|
|  | [applyRevisionChanges(Path filePath, ApplyRevisionOptions changes)](#applyRevisionChanges-java.nio.file.Path-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | Verwerkt wijzigingen in revisies en schrijft het resultaat naar het opgegeven bestand. |
|
|  | [applyRevisionChanges(String filePath, ApplyRevisionOptions changes)](#applyRevisionChanges-java.lang.String-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | Verwerkt wijzigingen in revisies en schrijft het resultaat naar het opgegeven bestand. |
|
|  | [applyRevisionChanges(OutputStream outputStream, ApplyRevisionOptions changes)](#applyRevisionChanges-java.io.OutputStream-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | Verwerkt wijzigingen in revisies en schrijft het resultaat naar de documentstroom. |
|
| [close()](#close--) |  |
### RevisionHandler(String filePath) {#RevisionHandler-java.lang.String-}
```
public RevisionHandler(String filePath)
```


Initialiseert een nieuw exemplaar van de RevisionHandler-klasse met het pad naar het bestand dat revisies bevat.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Het pad naar het bestand. |
|

### RevisionHandler(Path filePath) {#RevisionHandler-java.nio.file.Path-}
```
public RevisionHandler(Path filePath)
```


Initialiseert een nieuw exemplaar van de RevisionHandler-klasse met het pad naar het bestand dat revisies bevat.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Het pad naar het bestand. |
|

### RevisionHandler(InputStream file, FileType fileType) {#RevisionHandler-java.io.InputStream-com.groupdocs.comparison.result.FileType-}
```
public RevisionHandler(InputStream file, FileType fileType)
```


Initialiseert een nieuw exemplaar van de RevisionHandler-klasse met een bestandsstroom die revisies bevat.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | bestand | java.io.InputStream | De bron documentstroom. |
|
|  | fileType | [FileType](../../com.groupdocs.comparison.result/filetype) | Het type van het bestand. |
|

### RevisionHandler(Document document) {#RevisionHandler-com.aspose.words.Document-}
```
public RevisionHandler(Document document)
```


Initialiseert een nieuw exemplaar van de RevisionHandler-klasse met een document.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | document | com.aspose.words.Document | Het document. |
|

### SOURCE_PATH_IS_NULL {#SOURCE-PATH-IS-NULL}
```
public static final String SOURCE_PATH_IS_NULL
```


### getRevisions() {#getRevisions--}
```
public List<RevisionInfo> getRevisions()
```


Haalt de lijst met alle revisies op.


Omdat revisies oorspronkelijk in een groep werden gesorteerd, moeten revisies uit een lijst worden gehaald.
In de lijst kan een enkele revisie worden opgesplitst in meerdere revisies met dezelfde algemene tekst.
Aangezien de lijst revisies met dezelfde algemene tekst kan bevatten, moet dit worden gecontroleerd bij het maken van een lijst met revisies voor de gebruiker.
Dit wordt hier gecontroleerd met behulp van List\\<RevisionGroup\\> groepen.


**Returns:**
java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> - de lijst met revisies.

### applyRevisionChanges(ApplyRevisionOptions changes) {#applyRevisionChanges-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(ApplyRevisionOptions changes)
```


Verwerkt wijzigingen in revisies en past ze toe op het originele bestand.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | De lijst met gewijzigde revisies. |
|

### applyRevisionChanges(Path filePath, ApplyRevisionOptions changes) {#applyRevisionChanges-java.nio.file.Path-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(Path filePath, ApplyRevisionOptions changes)
```


Verwerkt wijzigingen in revisies en schrijft het resultaat naar het opgegeven bestand.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Het pad van het resultaatbestand. |
|
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | De lijst met gewijzigde revisies. |
|

### applyRevisionChanges(String filePath, ApplyRevisionOptions changes) {#applyRevisionChanges-java.lang.String-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(String filePath, ApplyRevisionOptions changes)
```


Verwerkt wijzigingen in revisies en schrijft het resultaat naar het opgegeven bestand.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Het pad van het resultaatbestand. |
|
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | De lijst met gewijzigde revisies. |
|

### applyRevisionChanges(OutputStream outputStream, ApplyRevisionOptions changes) {#applyRevisionChanges-java.io.OutputStream-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(OutputStream outputStream, ApplyRevisionOptions changes)
```


Verwerkt wijzigingen in revisies en schrijft het resultaat naar de documentstroom.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | outputStream | java.io.OutputStream | De resultaatdocumentstroom. |
|
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | De lijst met gewijzigde revisies. |
|

### close() {#close--}
```
public void close()
```




