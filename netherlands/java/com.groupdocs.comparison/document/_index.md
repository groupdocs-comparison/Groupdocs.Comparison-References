---
title: "Document"
second_title: "GroupDocs.Comparison voor Java API-referentie"
description: "Stelt een document voor het vergelijkingsproces voor."
type: docs
weight: 12
url: /nl/java/com.groupdocs.comparison/document/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Document implements Closeable
```

Stelt een document voor het vergelijkingsproces voor.


De Document-klasse biedt methoden om te laden, voorbeeldafbeeldingen te genereren en documenten te manipuleren tijdens het vergelijkingsproces.


Voorbeeldgebruik:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     try (IDocumentInfo info = comparer.getSource().getDocumentInfo()) {
         System.out.println("File type: " + info.getFileType());
         System.out.println("Number of pages: " + info.getPageCount());
         System.out.println("Document size: " + info.getSize());
     }
 }
 
````


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [Document(InputStream stream)](#Document-java.io.InputStream-) | Initialiseert een nieuw exemplaar van de Document-klasse met de opgegeven documentstroom. |
|
|  | [Document(String filePath)](#Document-java.lang.String-) | Initialiseert een nieuw exemplaar van de Document-klasse met het opgegeven documentpad. |
|
|  | [Document(Path filePath)](#Document-java.nio.file.Path-) | Initialiseert een nieuw exemplaar van de Document-klasse met het opgegeven documentpad. |
|
|  | [Document(Path filePath, String password)](#Document-java.nio.file.Path-java.lang.String-) | Initialiseert een nieuw exemplaar van de Document-klasse met het opgegeven documentpad en een wachtwoord. |
|
|  | [Document(Path filePath, LoadOptions loadOptions)](#Document-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-) | Initialiseert een nieuw exemplaar van de Document-klasse met het opgegeven documentpad en laadopties. |
|
|  | [Document(String filePath, String password)](#Document-java.lang.String-java.lang.String-) | Initialiseert een nieuw exemplaar van de Document-klasse met het opgegeven documentpad en een wachtwoord. |
|
|  | [Document(String filePath, LoadOptions loadOptions)](#Document-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-) | Initialiseert een nieuw exemplaar van de Document-klasse met het opgegeven documentpad en laadopties. |
|
|  | [Document(InputStream stream, String password)](#Document-java.io.InputStream-java.lang.String-) | Initialiseert een nieuw exemplaar van de Document-klasse met de opgegeven documentstroom en een wachtwoord. |
|
|  | [Document(String filePathOrTextContent, boolean isLoadText)](#Document-java.lang.String-boolean-) | Initialiseert een nieuw exemplaar van de Document-klasse met het opgegeven documentpad of tekstinhoud en een vlag die aangeeft wat is doorgegeven. |
|
|  | [Document(InputStream inputStream, LoadOptions loadOptions)](#Document-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-) | Initialiseert een nieuw exemplaar van de Document-klasse met de opgegeven documentstroom en laadopties. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getChanges()](#getChanges--) | Haalt een lijst op van [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo)-objecten die de tijdens het vergelijkingsproces gedetecteerde wijzigingen weergeven. |
|
|  | [setChanges(List<ChangeInfo> value)](#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--) | Stelt een lijst in van [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo)-objecten die de tijdens het vergelijkingsproces gedetecteerde wijzigingen weergeven. |
|
|  | [getName()](#getName--) | Haalt de naam van het document op. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Stelt de naam van het document in. |
|
|  | [getFileType()](#getFileType--) | Haalt het type van het document op. |
|
|  | [setFileType(FileType fileType)](#setFileType-com.groupdocs.comparison.result.FileType-) | Stelt het type van het document in. |
|
|  | [createStream()](#createStream--) | Maakt een nieuwe stroom met documentinhoud. |
|
|  | [getStreamLength()](#getStreamLength--) | Haalt de grootte van het document op |
|
|  | [getPassword()](#getPassword--) | Haalt het wachtwoord van het document op |
|
|  | [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.comparison.options.PreviewOptions-) | Genereert documentvoorbeelden op basis van de opgegeven [PreviewOptions](../../com.groupdocs.comparison.options/previewoptions). |
|
|  | [getDocumentInfo()](#getDocumentInfo--) | Haalt informatie over het document op, inclusief documenttype, paginatelling, paginagroottes en meer. |
|
| [close()](#close--) |  |
### Document(InputStream stream) {#Document-java.io.InputStream-}
```
public Document(InputStream stream)
```


Initialiseert een nieuw exemplaar van de Document-klasse met de opgegeven documentstroom.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | stroom | java.io.InputStream | Documentstroom |
|

### Document(String filePath) {#Document-java.lang.String-}
```
public Document(String filePath)
```


Initialiseert een nieuw exemplaar van de Document-klasse met het opgegeven documentpad.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Documentpad |
|

### Document(Path filePath) {#Document-java.nio.file.Path-}
```
public Document(Path filePath)
```


Initialiseert een nieuw exemplaar van de Document-klasse met het opgegeven documentpad.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Documentpad |
|

### Document(Path filePath, String password) {#Document-java.nio.file.Path-java.lang.String-}
```
public Document(Path filePath, String password)
```


Initialiseert een nieuw exemplaar van de Document-klasse met het opgegeven documentpad en een wachtwoord.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Documentpad |
|
|  | wachtwoord | java.lang.String | Documentwachtwoord |
|

### Document(Path filePath, LoadOptions loadOptions) {#Document-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Document(Path filePath, LoadOptions loadOptions)
```


Initialiseert een nieuw exemplaar van de Document-klasse met het opgegeven documentpad en laadopties.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Documentpad |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Laadopties |
|

### Document(String filePath, String password) {#Document-java.lang.String-java.lang.String-}
```
public Document(String filePath, String password)
```


Initialiseert een nieuw exemplaar van de Document-klasse met het opgegeven documentpad en een wachtwoord.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Documentpad |
|
|  | wachtwoord | java.lang.String | Documentwachtwoord |
|

### Document(String filePath, LoadOptions loadOptions) {#Document-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Document(String filePath, LoadOptions loadOptions)
```


Initialiseert een nieuw exemplaar van de Document-klasse met het opgegeven documentpad en laadopties.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Documentpad |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Laadopties |
|

### Document(InputStream stream, String password) {#Document-java.io.InputStream-java.lang.String-}
```
public Document(InputStream stream, String password)
```


Initialiseert een nieuw exemplaar van de Document-klasse met de opgegeven documentstroom en een wachtwoord.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | stroom | java.io.InputStream | Documentstroom |
|
|  | wachtwoord | java.lang.String | Documentwachtwoord |
|

### Document(String filePathOrTextContent, boolean isLoadText) {#Document-java.lang.String-boolean-}
```
public Document(String filePathOrTextContent, boolean isLoadText)
```


Initialiseert een nieuw exemplaar van de Document-klasse met het opgegeven documentpad of tekstinhoud en een vlag die aangeeft wat is doorgegeven.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePathOrTextContent | java.lang.String | het bestandspad |
|
|  | isLoadText | boolean | de is load text |
|

### Document(InputStream inputStream, LoadOptions loadOptions) {#Document-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Document(InputStream inputStream, LoadOptions loadOptions)
```


Initialiseert een nieuw exemplaar van de Document-klasse met de opgegeven documentstroom en laadopties.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | inputStream | java.io.InputStream | Documentstroom |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Laadopties |
|

### getChanges() {#getChanges--}
```
public final List<ChangeInfo> getChanges()
```


Haalt een lijst op van [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo)-objecten die de tijdens het vergelijkingsproces gedetecteerde wijzigingen weergeven.


Gebruik deze methode om gedetailleerde informatie te krijgen over de wijzigingen tussen het brondocument en het doeldocument(en).
Elk [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) object bevat informatie zoals het type wijziging, het getroffen gebied,
en de inhoud vóór en na de wijziging.


**Returns:**
java.util.List<com.groupdocs.comparison.result.ChangeInfo> - een lijst van [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) objecten die de wijzigingen weergeven die tijdens het vergelijkingsproces zijn gedetecteerd

### setChanges(List<ChangeInfo> value) {#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--}
```
public final void setChanges(List<ChangeInfo> value)
```


Stelt een lijst in van [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo)-objecten die de tijdens het vergelijkingsproces gedetecteerde wijzigingen weergeven.


Gebruik deze methode om gedetailleerde informatie te krijgen over de wijzigingen tussen het brondocument en het doeldocument(en).
Elk [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) object bevat informatie zoals het type wijziging, het getroffen gebied,
en de inhoud vóór en na de wijziging.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | java.util.List<com.groupdocs.comparison.result.ChangeInfo> | een lijst van [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) objecten die de wijzigingen weergeven die tijdens het vergelijkingsproces zijn gedetecteerd |
|

### getName() {#getName--}
```
public final String getName()
```


Haalt de naam van het document op.


**Returns:**
java.lang.String - de naam van het document

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Stelt de naam van het document in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.lang.String | de naam van het document |
|

### getFileType() {#getFileType--}
```
public FileType getFileType()
```


Haalt het type van het document op.


**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the type of the document

### setFileType(FileType fileType) {#setFileType-com.groupdocs.comparison.result.FileType-}
```
public void setFileType(FileType fileType)
```


Stelt het type van het document in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.comparison.result/filetype) | het type van het document |
|

### createStream() {#createStream--}
```
public InputStream createStream()
```


Maakt een nieuwe stroom met documentinhoud.


**Returns:**
java.io.InputStream - de stream met documentinhoud

### getStreamLength() {#getStreamLength--}
```
public long getStreamLength()
```


Haalt de grootte van het document op


**Returns:**
long - de grootte van het document

### getPassword() {#getPassword--}
```
public String getPassword()
```


Haalt het wachtwoord van het document op


**Returns:**
java.lang.String - het wachtwoord van het document

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.comparison.options.PreviewOptions-}
```
public final void generatePreview(PreviewOptions previewOptions)
```


Genereert documentvoorbeelden op basis van de opgegeven [PreviewOptions](../../com.groupdocs.comparison.options/previewoptions).


Deze methode genereert voorbeeldweergaven van de documentpagina's volgens de opgegeven opties, zoals voorbeeldformaat,
paginanummers, en outputstreamprovider. De gegenereerde voorbeeldweergaven kunnen worden opgeslagen of verder verwerkt indien nodig.

* Learn more about how to generate previews for document pages: [How to generate document pages preview using GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Generate+document+pages+preview)


Voorbeeldgebruik:

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | previewOptions | [PreviewOptions](../../com.groupdocs.comparison.options/previewoptions) | De voorbeeldopties die het formaat, paginanummers en dergelijke specificeren |
|

### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Haalt informatie over het document op, inclusief documenttype, paginatelling, paginagroottes en meer.

* Learn more about document file type, page count, size, and other format-specific properties: [How to get document info using GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Get+file+info)


**Returns:**
[IDocumentInfo](../../com.groupdocs.comparison.interfaces/idocumentinfo) - the document information

### close() {#close--}
```
public void close()
```




