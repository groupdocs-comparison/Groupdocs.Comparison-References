---
title: "Dokument"
second_title: "GroupDocs.Comparison för Java API-referens"
description: "Representerar ett dokument för jämförelseprocessen."
type: docs
weight: 12
url: /sv/java/com.groupdocs.comparison/document/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Document implements Closeable
```

Representerar ett dokument för jämförelseprocessen.


Document‑klassen tillhandahåller metoder för att läsa in, generera förhandsgranskningsbilder och manipulera dokument under jämförelseprocessen.


Exempel på användning:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     try (IDocumentInfo info = comparer.getSource().getDocumentInfo()) {
         System.out.println("File type: " + info.getFileType());
         System.out.println("Number of pages: " + info.getPageCount());
         System.out.println("Document size: " + info.getSize());
     }
 }
 
````


## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [Document(InputStream stream)](#Document-java.io.InputStream-) | Initierar en ny instans av Document‑klassen med den angivna dokumentströmmen. |
|
|  | [Document(String filePath)](#Document-java.lang.String-) | Initierar en ny instans av Document‑klassen med den angivna dokumentvägen. |
|
|  | [Document(Path filePath)](#Document-java.nio.file.Path-) | Initierar en ny instans av Document‑klassen med den angivna dokumentvägen. |
|
|  | [Document(Path filePath, String password)](#Document-java.nio.file.Path-java.lang.String-) | Initierar en ny instans av Document‑klassen med den angivna dokumentvägen och ett lösenord. |
|
|  | [Document(Path filePath, LoadOptions loadOptions)](#Document-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-) | Initierar en ny instans av Document‑klassen med den angivna dokumentvägen och inläsningsalternativ. |
|
|  | [Document(String filePath, String password)](#Document-java.lang.String-java.lang.String-) | Initierar en ny instans av Document‑klassen med den angivna dokumentvägen och ett lösenord. |
|
|  | [Document(String filePath, LoadOptions loadOptions)](#Document-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-) | Initierar en ny instans av Document‑klassen med den angivna dokumentvägen och inläsningsalternativ. |
|
|  | [Document(InputStream stream, String password)](#Document-java.io.InputStream-java.lang.String-) | Initierar en ny instans av Document‑klassen med den angivna dokumentströmmen och ett lösenord. |
|
|  | [Document(String filePathOrTextContent, boolean isLoadText)](#Document-java.lang.String-boolean-) | Initierar en ny instans av Document‑klassen med den angivna dokumentvägen eller textinnehållet och en flagga som indikerar vad som skickades. |
|
|  | [Document(InputStream inputStream, LoadOptions loadOptions)](#Document-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-) | Initierar en ny instans av Document‑klassen med den angivna dokumentströmmen och inläsningsalternativ. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getChanges()](#getChanges--) | Hämtar en lista med [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo)-objekt som representerar de förändringar som upptäcktes under jämförelseprocessen. |
|
|  | [setChanges(List<ChangeInfo> value)](#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--) | Ställer in en lista med [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo)-objekt som representerar de förändringar som upptäcktes under jämförelseprocessen. |
|
|  | [getName()](#getName--) | Hämtar dokumentets namn. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Ställer in dokumentets namn. |
|
|  | [getFileType()](#getFileType--) | Hämtar dokumentets typ. |
|
|  | [setFileType(FileType fileType)](#setFileType-com.groupdocs.comparison.result.FileType-) | Ställer in dokumentets typ. |
|
|  | [createStream()](#createStream--) | Skapar en ny ström med dokumentinnehåll. |
|
|  | [getStreamLength()](#getStreamLength--) | Hämtar dokumentets storlek |
|
|  | [getPassword()](#getPassword--) | Hämtar dokumentets lösenord |
|
|  | [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.comparison.options.PreviewOptions-) | Genererar dokumentförhandsgranskningar baserat på de angivna [PreviewOptions](../../com.groupdocs.comparison.options/previewoptions). |
|
|  | [getDocumentInfo()](#getDocumentInfo--) | Hämtar information om dokumentet, inklusive dokumenttyp, sidantal, sidstorlekar och mer. |
|
| [close()](#close--) |  |
### Document(InputStream stream) {#Document-java.io.InputStream-}
```
public Document(InputStream stream)
```


Initierar en ny instans av Document‑klassen med den angivna dokumentströmmen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | ström | java.io.InputStream | Dokumentström |
|

### Document(String filePath) {#Document-java.lang.String-}
```
public Document(String filePath)
```


Initierar en ny instans av Document‑klassen med den angivna dokumentvägen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.lang.String | Dokumentväg |
|

### Document(Path filePath) {#Document-java.nio.file.Path-}
```
public Document(Path filePath)
```


Initierar en ny instans av Document‑klassen med den angivna dokumentvägen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Dokumentväg |
|

### Document(Path filePath, String password) {#Document-java.nio.file.Path-java.lang.String-}
```
public Document(Path filePath, String password)
```


Initierar en ny instans av Document‑klassen med den angivna dokumentvägen och ett lösenord.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Dokumentväg |
|
|  | lösenord | java.lang.String | Dokumentlösenord |
|

### Document(Path filePath, LoadOptions loadOptions) {#Document-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Document(Path filePath, LoadOptions loadOptions)
```


Initierar en ny instans av Document‑klassen med den angivna dokumentvägen och inläsningsalternativ.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Dokumentväg |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Inläsningsalternativ |
|

### Document(String filePath, String password) {#Document-java.lang.String-java.lang.String-}
```
public Document(String filePath, String password)
```


Initierar en ny instans av Document‑klassen med den angivna dokumentvägen och ett lösenord.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.lang.String | Dokumentväg |
|
|  | lösenord | java.lang.String | Dokumentlösenord |
|

### Document(String filePath, LoadOptions loadOptions) {#Document-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Document(String filePath, LoadOptions loadOptions)
```


Initierar en ny instans av Document‑klassen med den angivna dokumentvägen och inläsningsalternativ.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.lang.String | Dokumentväg |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Inläsningsalternativ |
|

### Document(InputStream stream, String password) {#Document-java.io.InputStream-java.lang.String-}
```
public Document(InputStream stream, String password)
```


Initierar en ny instans av Document‑klassen med den angivna dokumentströmmen och ett lösenord.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | ström | java.io.InputStream | Dokumentström |
|
|  | lösenord | java.lang.String | Dokumentlösenord |
|

### Document(String filePathOrTextContent, boolean isLoadText) {#Document-java.lang.String-boolean-}
```
public Document(String filePathOrTextContent, boolean isLoadText)
```


Initierar en ny instans av Document‑klassen med den angivna dokumentvägen eller textinnehållet och en flagga som indikerar vad som skickades.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePathOrTextContent | java.lang.String | filvägen |
|
|  | isLoadText | boolean | det är laddningstexten |
|

### Document(InputStream inputStream, LoadOptions loadOptions) {#Document-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Document(InputStream inputStream, LoadOptions loadOptions)
```


Initierar en ny instans av Document‑klassen med den angivna dokumentströmmen och inläsningsalternativ.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | inputStream | java.io.InputStream | Dokumentström |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Inläsningsalternativ |
|

### getChanges() {#getChanges--}
```
public final List<ChangeInfo> getChanges()
```


Hämtar en lista med [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo)-objekt som representerar de förändringar som upptäcktes under jämförelseprocessen.


Använd den här metoden för att få detaljerad information om förändringarna mellan källdokumentet och mål(dokumentet).
Varje [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) objekt innehåller information såsom typ av förändring, det påverkade området,
och innehållet före och efter förändringen.


**Returns:**
java.util.List<com.groupdocs.comparison.result.ChangeInfo> - en lista med [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) objekt som representerar förändringarna som upptäcktes under jämförelseprocessen

### setChanges(List<ChangeInfo> value) {#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--}
```
public final void setChanges(List<ChangeInfo> value)
```


Ställer in en lista med [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo)-objekt som representerar de förändringar som upptäcktes under jämförelseprocessen.


Använd den här metoden för att få detaljerad information om förändringarna mellan källdokumentet och mål(dokumentet).
Varje [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) objekt innehåller information såsom typ av förändring, det påverkade området,
och innehållet före och efter förändringen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | java.util.List<com.groupdocs.comparison.result.ChangeInfo> | en lista med [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) objekt som representerar förändringarna som upptäcktes under jämförelseprocessen |
|

### getName() {#getName--}
```
public final String getName()
```


Hämtar dokumentets namn.


**Returns:**
java.lang.String - namnet på dokumentet

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Ställer in dokumentets namn.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | java.lang.String | namnet på dokumentet |
|

### getFileType() {#getFileType--}
```
public FileType getFileType()
```


Hämtar dokumentets typ.


**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the type of the document

### setFileType(FileType fileType) {#setFileType-com.groupdocs.comparison.result.FileType-}
```
public void setFileType(FileType fileType)
```


Ställer in dokumentets typ.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.comparison.result/filetype) | dokumentets typ |
|

### createStream() {#createStream--}
```
public InputStream createStream()
```


Skapar en ny ström med dokumentinnehåll.


**Returns:**
java.io.InputStream - strömmen med dokumentets innehåll

### getStreamLength() {#getStreamLength--}
```
public long getStreamLength()
```


Hämtar dokumentets storlek


**Returns:**
long - storleken på dokumentet

### getPassword() {#getPassword--}
```
public String getPassword()
```


Hämtar dokumentets lösenord


**Returns:**
java.lang.String - dokumentets lösenord

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.comparison.options.PreviewOptions-}
```
public final void generatePreview(PreviewOptions previewOptions)
```


Genererar dokumentförhandsgranskningar baserat på de angivna [PreviewOptions](../../com.groupdocs.comparison.options/previewoptions).


Denna metod genererar förhandsgranskningar av dokumentets sidor enligt de angivna alternativen, såsom förhandsgranskningsformat,
sidnummer och leverantör av utdataström. De genererade förhandsgranskningarna kan sparas eller vidarebehandlas vid behov.

* Learn more about how to generate previews for document pages: [How to generate document pages preview using GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Generate+document+pages+preview)


Exempel på användning:

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | previewOptions | [PreviewOptions](../../com.groupdocs.comparison.options/previewoptions) | Förhandsgranskningsalternativen som specificerar format, sidnummer med mera |
|

### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Hämtar information om dokumentet, inklusive dokumenttyp, sidantal, sidstorlekar och mer.

* Learn more about document file type, page count, size, and other format-specific properties: [How to get document info using GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Get+file+info)


**Returns:**
[IDocumentInfo](../../com.groupdocs.comparison.interfaces/idocumentinfo) - the document information

### close() {#close--}
```
public void close()
```




