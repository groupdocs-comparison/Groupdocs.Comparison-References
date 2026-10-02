---
title: "RevisionHandler"
second_title: "GroupDocs.Comparison für Java API-Referenz"
description: "Stellt eine Klasse dar, die die Handhabung von Revisionen steuert."
type: docs
weight: 11
url: /de/java/com.groupdocs.comparison.words.revision/revisionhandler/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class RevisionHandler implements Closeable
```

Stellt eine Klasse dar, die die Handhabung von Revisionen steuert.


Die RevisionHandler-Klasse ermöglicht es Ihnen, mit Revisionen in Dokumenten zu arbeiten.
Sie bietet Methoden zum Abrufen der Revisionsliste, zum Anwenden von Änderungen auf Revisionen und zum Speichern des modifizierten Dokuments.


Beispielverwendung:

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


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [RevisionHandler(String filePath)](#RevisionHandler-java.lang.String-) | Initialisiert eine neue Instanz der RevisionHandler-Klasse mit dem Pfad zur Datei, die Revisionen enthält. |
|
|  | [RevisionHandler(Path filePath)](#RevisionHandler-java.nio.file.Path-) | Initialisiert eine neue Instanz der RevisionHandler-Klasse mit dem Pfad zur Datei, die Revisionen enthält. |
|
|  | [RevisionHandler(InputStream file, FileType fileType)](#RevisionHandler-java.io.InputStream-com.groupdocs.comparison.result.FileType-) | Initialisiert eine neue Instanz der RevisionHandler-Klasse mit einem Dateistream, der Revisionen enthält. |
|
|  | [RevisionHandler(Document document)](#RevisionHandler-com.aspose.words.Document-) | Initialisiert eine neue Instanz der RevisionHandler-Klasse mit einem Dokument. |
|
## Felder

| Feld | Beschreibung |
| --- | --- |
| [SOURCE_PATH_IS_NULL](#SOURCE-PATH-IS-NULL) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getRevisions()](#getRevisions--) | Ruft die Liste aller Revisionen ab. |
|
|  | [applyRevisionChanges(ApplyRevisionOptions changes)](#applyRevisionChanges-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | Verarbeitet Änderungen in Revisionen und wendet sie auf die Originaldatei an. |
|
|  | [applyRevisionChanges(Path filePath, ApplyRevisionOptions changes)](#applyRevisionChanges-java.nio.file.Path-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | Verarbeitet Änderungen in Revisionen und schreibt das Ergebnis in die angegebene Datei. |
|
|  | [applyRevisionChanges(String filePath, ApplyRevisionOptions changes)](#applyRevisionChanges-java.lang.String-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | Verarbeitet Änderungen in Revisionen und schreibt das Ergebnis in die angegebene Datei. |
|
|  | [applyRevisionChanges(OutputStream outputStream, ApplyRevisionOptions changes)](#applyRevisionChanges-java.io.OutputStream-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | Verarbeitet Änderungen in Revisionen und schreibt das Ergebnis in den Dokumentenstream. |
|
| [close()](#close--) |  |
### RevisionHandler(String filePath) {#RevisionHandler-java.lang.String-}
```
public RevisionHandler(String filePath)
```


Initialisiert eine neue Instanz der RevisionHandler-Klasse mit dem Pfad zur Datei, die Revisionen enthält.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.lang.String | Der Pfad zur Datei. |
|

### RevisionHandler(Path filePath) {#RevisionHandler-java.nio.file.Path-}
```
public RevisionHandler(Path filePath)
```


Initialisiert eine neue Instanz der RevisionHandler-Klasse mit dem Pfad zur Datei, die Revisionen enthält.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Der Pfad zur Datei. |
|

### RevisionHandler(InputStream file, FileType fileType) {#RevisionHandler-java.io.InputStream-com.groupdocs.comparison.result.FileType-}
```
public RevisionHandler(InputStream file, FileType fileType)
```


Initialisiert eine neue Instanz der RevisionHandler-Klasse mit einem Dateistream, der Revisionen enthält.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Datei | java.io.InputStream | Der Quell-Dokumenten-Stream. |
|
|  | fileType | [FileType](../../com.groupdocs.comparison.result/filetype) | Der Typ der Datei. |
|

### RevisionHandler(Document document) {#RevisionHandler-com.aspose.words.Document-}
```
public RevisionHandler(Document document)
```


Initialisiert eine neue Instanz der RevisionHandler-Klasse mit einem Dokument.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dokument | com.aspose.words.Document | Das Dokument. |
|

### SOURCE_PATH_IS_NULL {#SOURCE-PATH-IS-NULL}
```
public static final String SOURCE_PATH_IS_NULL
```


### getRevisions() {#getRevisions--}
```
public List<RevisionInfo> getRevisions()
```


Ruft die Liste aller Revisionen ab.


Da Revisionen ursprünglich in einer Gruppe sortiert wurden, müssen Revisionen aus einer Liste entnommen werden.
In der Liste kann eine einzelne Revision in mehrere Revisionen mit demselben allgemeinen Text aufgeteilt werden.
Da die Liste Revisionen mit demselben allgemeinen Text enthalten kann, muss dies beim Erstellen einer Revisionsliste für den Benutzer kontrolliert werden.
Dies wird hier mit List\<RevisionGroup\> Gruppen gesteuert.


**Returns:**
java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> - die Liste der Revisionen.

### applyRevisionChanges(ApplyRevisionOptions changes) {#applyRevisionChanges-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(ApplyRevisionOptions changes)
```


Verarbeitet Änderungen in Revisionen und wendet sie auf die Originaldatei an.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | Die Liste der geänderten Revisionen. |
|

### applyRevisionChanges(Path filePath, ApplyRevisionOptions changes) {#applyRevisionChanges-java.nio.file.Path-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(Path filePath, ApplyRevisionOptions changes)
```


Verarbeitet Änderungen in Revisionen und schreibt das Ergebnis in die angegebene Datei.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Der Pfad der Ergebnisdatei. |
|
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | Die Liste der geänderten Revisionen. |
|

### applyRevisionChanges(String filePath, ApplyRevisionOptions changes) {#applyRevisionChanges-java.lang.String-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(String filePath, ApplyRevisionOptions changes)
```


Verarbeitet Änderungen in Revisionen und schreibt das Ergebnis in die angegebene Datei.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.lang.String | Der Pfad der Ergebnisdatei. |
|
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | Die Liste der geänderten Revisionen. |
|

### applyRevisionChanges(OutputStream outputStream, ApplyRevisionOptions changes) {#applyRevisionChanges-java.io.OutputStream-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(OutputStream outputStream, ApplyRevisionOptions changes)
```


Verarbeitet Änderungen in Revisionen und schreibt das Ergebnis in den Dokumentenstream.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | outputStream | java.io.OutputStream | Der Ergebnis-Dokumenten-Stream. |
|
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | Die Liste der geänderten Revisionen. |
|

### close() {#close--}
```
public void close()
```




