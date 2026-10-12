---
title: "IDocumentInfo"
second_title: "GroupDocs.Comparison voor Java API-referentie"
description: "Biedt toegang tot documenteigenschappen."
type: docs
weight: 10
url: /nl/java/com.groupdocs.comparison.interfaces/idocumentinfo/
---
**All Implemented Interfaces:**
java.io.Closeable
```
public interface IDocumentInfo extends Closeable
```

Biedt toegang tot documenteigenschappen.


Meer details over het gebruik ervan zijn te vinden in de [Document.getDocumentInfo()](../../com.groupdocs.comparison/document#getDocumentInfo--) methode of in een [documentatie](../https://docs.groupdocs.com/comparison/java/get-file-info/).


Voorbeeldgebruik:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    try (IDocumentInfo documentInfo = comparer.getSource().getDocumentInfo()) {
      for (int i = 0; i < documentInfo.getPageCount(); i++) {
          System.out.printf("File type: %s%nNumber of pages: %d", documentInfo.getFileType().getFileFormat(), documentInfo.getPageCount());
      }
    }
 }
 
````


## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getFileType()](#getFileType--) | Haalt een type van het bestand op dat wordt weergegeven door de [FileType](../../com.groupdocs.comparison.result/filetype) enum. |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.comparison.result.FileType-) | Stelt een type van het bestand in met behulp van de [FileType](../../com.groupdocs.comparison.result/filetype) enum. |
|
|  | [getPageCount()](#getPageCount--) | Haalt het aantal van het bestand op. |
|
|  | [setPageCount(int value)](#setPageCount-int-) | Stelt het aantal van het bestand in. |
|
|  | [getSize()](#getSize--) | Haalt de grootte van het bestand op. |
|
|  | [setSize(long value)](#setSize-long-) | Stelt de grootte van het bestand in. |
|
|  | [getPagesInfo()](#getPagesInfo--) | Haalt informatie op voor elke pagina van het bestand met behulp van de [PageInfo](../../com.groupdocs.comparison.result/pageinfo) klasse. |
|
|  | [setPagesInfo(List<PageInfo> pageInfos)](#setPagesInfo-java.util.List-com.groupdocs.comparison.result.PageInfo--) | Stelt informatie in voor elke pagina van het bestand met behulp van de [PageInfo](../../com.groupdocs.comparison.result/pageinfo) klasse. |
|
|  | [close()](#close--) | Vernietigt het object, waardoor het onmogelijk wordt om informatie over het document op te halen met deze instantie van het [IDocumentInfo](../../com.groupdocs.comparison.interfaces/idocumentinfo) object. |
|
### getFileType() {#getFileType--}
```
public abstract FileType getFileType()
```


Haalt een type van het bestand op dat wordt weergegeven door de [FileType](../../com.groupdocs.comparison.result/filetype) enum.


**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the type of the file

### setFileType(FileType value) {#setFileType-com.groupdocs.comparison.result.FileType-}
```
public abstract void setFileType(FileType value)
```


Stelt een type van het bestand in met behulp van de [FileType](../../com.groupdocs.comparison.result/filetype) enum.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [FileType](../../com.groupdocs.comparison.result/filetype) | Het type van het bestand |
|

### getPageCount() {#getPageCount--}
```
public abstract int getPageCount()
```


Haalt het aantal van het bestand op.


**Returns:**
int - het aantal van het bestand

### setPageCount(int value) {#setPageCount-int-}
```
public abstract void setPageCount(int value)
```


Stelt het aantal van het bestand in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | int | Het aantal van het bestand |
|

### getSize() {#getSize--}
```
public abstract long getSize()
```


Haalt de grootte van het bestand op.


**Returns:**
long - de grootte van het bestand

### setSize(long value) {#setSize-long-}
```
public abstract void setSize(long value)
```


Stelt de grootte van het bestand in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | long | De grootte van het bestand |
|

### getPagesInfo() {#getPagesInfo--}
```
public abstract List<PageInfo> getPagesInfo()
```


Haalt informatie op voor elke pagina van het bestand met behulp van de [PageInfo](../../com.groupdocs.comparison.result/pageinfo) klasse.


**Returns:**
java.util.List<com.groupdocs.comparison.result.PageInfo> - informatie voor elke pagina van het bestand

### setPagesInfo(List<PageInfo> pageInfos) {#setPagesInfo-java.util.List-com.groupdocs.comparison.result.PageInfo--}
```
public abstract void setPagesInfo(List<PageInfo> pageInfos)
```


Stelt informatie in voor elke pagina van het bestand met behulp van de [PageInfo](../../com.groupdocs.comparison.result/pageinfo) klasse.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | pageInfos | java.util.List<com.groupdocs.comparison.result.PageInfo> | Informatie voor elke pagina van het bestand |
|

### close() {#close--}
```
public abstract void close()
```


Vernietigt het object, waardoor het onmogelijk wordt om informatie over het document op te halen met deze instantie van het [IDocumentInfo](../../com.groupdocs.comparison.interfaces/idocumentinfo) object.
Verwijdert ook tijdelijke bestanden en geeft gebruikte bronnen vrij.


