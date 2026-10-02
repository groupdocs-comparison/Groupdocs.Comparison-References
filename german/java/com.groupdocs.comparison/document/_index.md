---
title: "Document"
second_title: "GroupDocs.Comparison für Java API-Referenz"
description: "Stellt ein Dokument für den Vergleichsprozess dar."
type: docs
weight: 12
url: /de/java/com.groupdocs.comparison/document/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Document implements Closeable
```

Stellt ein Dokument für den Vergleichsprozess dar.


Die Document-Klasse stellt Methoden zum Laden, Erzeugen von Vorschaubildern und Manipulieren von Dokumenten während des Vergleichsprozesses bereit.


Beispielverwendung:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     try (IDocumentInfo info = comparer.getSource().getDocumentInfo()) {
         System.out.println("File type: " + info.getFileType());
         System.out.println("Number of pages: " + info.getPageCount());
         System.out.println("Document size: " + info.getSize());
     }
 }
 
````


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [Document(InputStream stream)](#Document-java.io.InputStream-) | Initialisiert eine neue Instanz der Document-Klasse mit dem angegebenen Dokument-Stream. |
|
|  | [Document(String filePath)](#Document-java.lang.String-) | Initialisiert eine neue Instanz der Document-Klasse mit dem angegebenen Dokumentpfad. |
|
|  | [Document(Path filePath)](#Document-java.nio.file.Path-) | Initialisiert eine neue Instanz der Document-Klasse mit dem angegebenen Dokumentpfad. |
|
|  | [Document(Path filePath, String password)](#Document-java.nio.file.Path-java.lang.String-) | Initialisiert eine neue Instanz der Document-Klasse mit dem angegebenen Dokumentpfad und einem Passwort. |
|
|  | [Document(Path filePath, LoadOptions loadOptions)](#Document-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-) | Initialisiert eine neue Instanz der Document-Klasse mit dem angegebenen Dokumentpfad und Ladeoptionen. |
|
|  | [Document(String filePath, String password)](#Document-java.lang.String-java.lang.String-) | Initialisiert eine neue Instanz der Document-Klasse mit dem angegebenen Dokumentpfad und einem Passwort. |
|
|  | [Document(String filePath, LoadOptions loadOptions)](#Document-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-) | Initialisiert eine neue Instanz der Document-Klasse mit dem angegebenen Dokumentpfad und Ladeoptionen. |
|
|  | [Document(InputStream stream, String password)](#Document-java.io.InputStream-java.lang.String-) | Initialisiert eine neue Instanz der Document-Klasse mit dem angegebenen Dokument-Stream und einem Passwort. |
|
|  | [Document(String filePathOrTextContent, boolean isLoadText)](#Document-java.lang.String-boolean-) | Initialisiert eine neue Instanz der Document-Klasse mit dem angegebenen Dokumentpfad oder Textinhalt und einem Flag, das angibt, was übergeben wurde. |
|
|  | [Document(InputStream inputStream, LoadOptions loadOptions)](#Document-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-) | Initialisiert eine neue Instanz der Document-Klasse mit dem angegebenen Dokument-Stream und Ladeoptionen. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getChanges()](#getChanges--) | Liefert eine Liste von [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo)-Objekten, die die während des Vergleichsprozesses erkannten Änderungen darstellen. |
|
|  | [setChanges(List<ChangeInfo> value)](#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--) | Setzt eine Liste von [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo)-Objekten, die die während des Vergleichsprozesses erkannten Änderungen darstellen. |
|
|  | [getName()](#getName--) | Liefert den Namen des Dokuments. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Setzt den Namen des Dokuments. |
|
|  | [getFileType()](#getFileType--) | Liefert den Typ des Dokuments. |
|
|  | [setFileType(FileType fileType)](#setFileType-com.groupdocs.comparison.result.FileType-) | Setzt den Typ des Dokuments. |
|
|  | [createStream()](#createStream--) | Erstellt einen neuen Stream mit dem Dokumentinhalt. |
|
|  | [getStreamLength()](#getStreamLength--) | Liefert die Größe des Dokuments |
|
|  | [getPassword()](#getPassword--) | Liefert das Passwort des Dokuments |
|
|  | [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.comparison.options.PreviewOptions-) | Erzeugt Dokumentvorschauen basierend auf den bereitgestellten [PreviewOptions](../../com.groupdocs.comparison.options/previewoptions). |
|
|  | [getDocumentInfo()](#getDocumentInfo--) | Liefert Informationen über das Dokument, einschließlich Dokumenttyp, Seitenzahl, Seitengrößen und mehr. |
|
| [close()](#close--) |  |
### Document(InputStream stream) {#Document-java.io.InputStream-}
```
public Document(InputStream stream)
```


Initialisiert eine neue Instanz der Document-Klasse mit dem angegebenen Dokument-Stream.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Stream | java.io.InputStream | Document-Stream |
|

### Document(String filePath) {#Document-java.lang.String-}
```
public Document(String filePath)
```


Initialisiert eine neue Instanz der Document-Klasse mit dem angegebenen Dokumentpfad.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.lang.String | Document-Pfad |
|

### Document(Path filePath) {#Document-java.nio.file.Path-}
```
public Document(Path filePath)
```


Initialisiert eine neue Instanz der Document-Klasse mit dem angegebenen Dokumentpfad.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Document-Pfad |
|

### Document(Path filePath, String password) {#Document-java.nio.file.Path-java.lang.String-}
```
public Document(Path filePath, String password)
```


Initialisiert eine neue Instanz der Document-Klasse mit dem angegebenen Dokumentpfad und einem Passwort.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Document-Pfad |
|
|  | Passwort | java.lang.String | Document-Passwort |
|

### Document(Path filePath, LoadOptions loadOptions) {#Document-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Document(Path filePath, LoadOptions loadOptions)
```


Initialisiert eine neue Instanz der Document-Klasse mit dem angegebenen Dokumentpfad und Ladeoptionen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Document-Pfad |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Ladeoptionen |
|

### Document(String filePath, String password) {#Document-java.lang.String-java.lang.String-}
```
public Document(String filePath, String password)
```


Initialisiert eine neue Instanz der Document-Klasse mit dem angegebenen Dokumentpfad und einem Passwort.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.lang.String | Document-Pfad |
|
|  | Passwort | java.lang.String | Document-Passwort |
|

### Document(String filePath, LoadOptions loadOptions) {#Document-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Document(String filePath, LoadOptions loadOptions)
```


Initialisiert eine neue Instanz der Document-Klasse mit dem angegebenen Dokumentpfad und Ladeoptionen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.lang.String | Document-Pfad |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Ladeoptionen |
|

### Document(InputStream stream, String password) {#Document-java.io.InputStream-java.lang.String-}
```
public Document(InputStream stream, String password)
```


Initialisiert eine neue Instanz der Document-Klasse mit dem angegebenen Dokument-Stream und einem Passwort.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Stream | java.io.InputStream | Document-Stream |
|
|  | Passwort | java.lang.String | Document-Passwort |
|

### Document(String filePathOrTextContent, boolean isLoadText) {#Document-java.lang.String-boolean-}
```
public Document(String filePathOrTextContent, boolean isLoadText)
```


Initialisiert eine neue Instanz der Document-Klasse mit dem angegebenen Dokumentpfad oder Textinhalt und einem Flag, das angibt, was übergeben wurde.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePathOrTextContent | java.lang.String | der Dateipfad |
|
|  | isLoadText | boolean | der ist geladener Text |
|

### Document(InputStream inputStream, LoadOptions loadOptions) {#Document-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Document(InputStream inputStream, LoadOptions loadOptions)
```


Initialisiert eine neue Instanz der Document-Klasse mit dem angegebenen Dokument-Stream und Ladeoptionen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | inputStream | java.io.InputStream | Document-Stream |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Ladeoptionen |
|

### getChanges() {#getChanges--}
```
public final List<ChangeInfo> getChanges()
```


Liefert eine Liste von [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo)-Objekten, die die während des Vergleichsprozesses erkannten Änderungen darstellen.


Verwenden Sie diese Methode, um detaillierte Informationen über die Änderungen zwischen dem Quelldokument und dem Zieldokument (en) zu erhalten.
Jedes [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo)-Objekt enthält Informationen wie den Typ der Änderung, den betroffenen Bereich,
und den Inhalt vor und nach der Änderung.


**Returns:**
java.util.List<com.groupdocs.comparison.result.ChangeInfo> - eine Liste von [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo)-Objekten, die die während des Vergleichsvorgangs erkannten Änderungen darstellen

### setChanges(List<ChangeInfo> value) {#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--}
```
public final void setChanges(List<ChangeInfo> value)
```


Setzt eine Liste von [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo)-Objekten, die die während des Vergleichsprozesses erkannten Änderungen darstellen.


Verwenden Sie diese Methode, um detaillierte Informationen über die Änderungen zwischen dem Quelldokument und dem Zieldokument (en) zu erhalten.
Jedes [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo)-Objekt enthält Informationen wie den Typ der Änderung, den betroffenen Bereich,
und den Inhalt vor und nach der Änderung.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | java.util.List<com.groupdocs.comparison.result.ChangeInfo> | eine Liste von [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo)-Objekten, die die während des Vergleichsvorgangs erkannten Änderungen darstellen |
|

### getName() {#getName--}
```
public final String getName()
```


Liefert den Namen des Dokuments.


**Returns:**
java.lang.String - der Name des Dokuments

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Setzt den Namen des Dokuments.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | java.lang.String | der Name des Dokuments |
|

### getFileType() {#getFileType--}
```
public FileType getFileType()
```


Liefert den Typ des Dokuments.


**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the type of the document

### setFileType(FileType fileType) {#setFileType-com.groupdocs.comparison.result.FileType-}
```
public void setFileType(FileType fileType)
```


Setzt den Typ des Dokuments.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.comparison.result/filetype) | der Typ des Dokuments |
|

### createStream() {#createStream--}
```
public InputStream createStream()
```


Erstellt einen neuen Stream mit dem Dokumentinhalt.


**Returns:**
java.io.InputStream - der Stream mit dem Dokumentinhalt

### getStreamLength() {#getStreamLength--}
```
public long getStreamLength()
```


Liefert die Größe des Dokuments


**Returns:**
long - die Größe des Dokuments

### getPassword() {#getPassword--}
```
public String getPassword()
```


Liefert das Passwort des Dokuments


**Returns:**
java.lang.String - das Passwort des Dokuments

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.comparison.options.PreviewOptions-}
```
public final void generatePreview(PreviewOptions previewOptions)
```


Erzeugt Dokumentvorschauen basierend auf den bereitgestellten [PreviewOptions](../../com.groupdocs.comparison.options/previewoptions).


Diese Methode erzeugt Vorschauen der Dokumentseiten gemäß den angegebenen Optionen, wie z. B. dem Vorschauformat,
Seitenzahlen und Ausgabestream-Anbieter. Die erzeugten Vorschauen können bei Bedarf gespeichert oder weiterverarbeitet werden.

* Learn more about how to generate previews for document pages: [How to generate document pages preview using GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Generate+document+pages+preview)


Beispielverwendung:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     PreviewOptions previewOptions = new PreviewOptions(
             pageNumber -> Files.newOutputStream(Paths.get("preview-image-page-" + pageNumber + ".png"))
     );
     previewOptions.setPreviewFormat(PreviewFormats.PNG);
     previewOptions.setPageNumbers(new int[]{1, 2});
     comparer.getSource().generatePreview(previewOptions);
 }
 
````



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | previewOptions | [PreviewOptions](../../com.groupdocs.comparison.options/previewoptions) | Die Vorschauoptionen, die das Format, die Seitenzahlen usw. angeben |
|

### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Liefert Informationen über das Dokument, einschließlich Dokumenttyp, Seitenzahl, Seitengrößen und mehr.

* Learn more about document file type, page count, size, and other format-specific properties: [How to get document info using GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Get+file+info)


**Returns:**
[IDocumentInfo](../../com.groupdocs.comparison.interfaces/idocumentinfo) - the document information

### close() {#close--}
```
public void close()
```




