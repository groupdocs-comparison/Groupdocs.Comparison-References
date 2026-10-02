---
title: "RevisionHandler"
second_title: "GroupDocs.Comparison för Java API-referens"
description: "Representerar en klass som styr hanteringen av revisioner."
type: docs
weight: 11
url: /sv/java/com.groupdocs.comparison.words.revision/revisionhandler/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class RevisionHandler implements Closeable
```

Representerar en klass som styr hanteringen av revisioner.


Klassen RevisionHandler låter dig arbeta med revisioner i dokument.
Den tillhandahåller metoder för att hämta listan över revisioner, tillämpa ändringar på revisioner och spara det modifierade dokumentet.


Exempel på användning:

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


## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [RevisionHandler(String filePath)](#RevisionHandler-java.lang.String-) | Initierar en ny instans av RevisionHandler-klassen med sökvägen till filen som innehåller revisioner. |
|
|  | [RevisionHandler(Path filePath)](#RevisionHandler-java.nio.file.Path-) | Initierar en ny instans av RevisionHandler-klassen med sökvägen till filen som innehåller revisioner. |
|
|  | [RevisionHandler(InputStream file, FileType fileType)](#RevisionHandler-java.io.InputStream-com.groupdocs.comparison.result.FileType-) | Initierar en ny instans av RevisionHandler-klassen med ett filström som innehåller revisioner. |
|
|  | [RevisionHandler(Document document)](#RevisionHandler-com.aspose.words.Document-) | Initierar en ny instans av RevisionHandler-klassen med ett dokument. |
|
## Fält

| Fält | Beskrivning |
| --- | --- |
| [SOURCE_PATH_IS_NULL](#SOURCE-PATH-IS-NULL) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getRevisions()](#getRevisions--) | Hämtar listan över alla revisioner. |
|
|  | [applyRevisionChanges(ApplyRevisionOptions changes)](#applyRevisionChanges-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | Bearbetar ändringar i revisioner och tillämpar dem på den ursprungliga filen. |
|
|  | [applyRevisionChanges(Path filePath, ApplyRevisionOptions changes)](#applyRevisionChanges-java.nio.file.Path-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | Bearbetar ändringar i revisioner och skriver resultatet till den angivna filen. |
|
|  | [applyRevisionChanges(String filePath, ApplyRevisionOptions changes)](#applyRevisionChanges-java.lang.String-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | Bearbetar ändringar i revisioner och skriver resultatet till den angivna filen. |
|
|  | [applyRevisionChanges(OutputStream outputStream, ApplyRevisionOptions changes)](#applyRevisionChanges-java.io.OutputStream-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | Bearbetar ändringar i revisioner och skriver resultatet till dokumentströmmen. |
|
| [close()](#close--) |  |
### RevisionHandler(String filePath) {#RevisionHandler-java.lang.String-}
```
public RevisionHandler(String filePath)
```


Initierar en ny instans av RevisionHandler-klassen med sökvägen till filen som innehåller revisioner.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.lang.String | Sökvägen till filen. |
|

### RevisionHandler(Path filePath) {#RevisionHandler-java.nio.file.Path-}
```
public RevisionHandler(Path filePath)
```


Initierar en ny instans av RevisionHandler-klassen med sökvägen till filen som innehåller revisioner.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Sökvägen till filen. |
|

### RevisionHandler(InputStream file, FileType fileType) {#RevisionHandler-java.io.InputStream-com.groupdocs.comparison.result.FileType-}
```
public RevisionHandler(InputStream file, FileType fileType)
```


Initierar en ny instans av RevisionHandler-klassen med ett filström som innehåller revisioner.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fil | java.io.InputStream | Källans dokumentström. |
|
|  | fileType | [FileType](../../com.groupdocs.comparison.result/filetype) | Typen av filen. |
|

### RevisionHandler(Document document) {#RevisionHandler-com.aspose.words.Document-}
```
public RevisionHandler(Document document)
```


Initierar en ny instans av RevisionHandler-klassen med ett dokument.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | dokument | com.aspose.words.Document | Dokumentet. |
|

### SOURCE_PATH_IS_NULL {#SOURCE-PATH-IS-NULL}
```
public static final String SOURCE_PATH_IS_NULL
```


### getRevisions() {#getRevisions--}
```
public List<RevisionInfo> getRevisions()
```


Hämtar listan över alla revisioner.


På grund av att revisioner ursprungligen sorterades i en grupp, måste revisioner tas från en List.
I List kan en enskild revision delas upp i flera revisioner med samma allmänna text.
Eftersom List kan innehålla revisioner med samma allmänna text måste detta kontrolleras när en lista med revisioner skapas för användaren.
Detta kontrolleras här med List\<RevisionGroup\> grupper.


**Returns:**
java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> - listan med revisioner.

### applyRevisionChanges(ApplyRevisionOptions changes) {#applyRevisionChanges-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(ApplyRevisionOptions changes)
```


Bearbetar ändringar i revisioner och tillämpar dem på den ursprungliga filen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | Listan med ändrade revisioner. |
|

### applyRevisionChanges(Path filePath, ApplyRevisionOptions changes) {#applyRevisionChanges-java.nio.file.Path-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(Path filePath, ApplyRevisionOptions changes)
```


Bearbetar ändringar i revisioner och skriver resultatet till den angivna filen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Resultatfilens sökväg. |
|
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | Listan med ändrade revisioner. |
|

### applyRevisionChanges(String filePath, ApplyRevisionOptions changes) {#applyRevisionChanges-java.lang.String-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(String filePath, ApplyRevisionOptions changes)
```


Bearbetar ändringar i revisioner och skriver resultatet till den angivna filen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.lang.String | Resultatfilens sökväg. |
|
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | Listan med ändrade revisioner. |
|

### applyRevisionChanges(OutputStream outputStream, ApplyRevisionOptions changes) {#applyRevisionChanges-java.io.OutputStream-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(OutputStream outputStream, ApplyRevisionOptions changes)
```


Bearbetar ändringar i revisioner och skriver resultatet till dokumentströmmen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | outputStream | java.io.OutputStream | Resultatdokumentets ström. |
|
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | Listan med ändrade revisioner. |
|

### close() {#close--}
```
public void close()
```




