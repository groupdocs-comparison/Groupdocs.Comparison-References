---
title: "IDocumentInfo"
second_title: "GroupDocs.Comparison för Java API-referens"
description: "Tillhandahåller åtkomst till dokumentegenskaper."
type: docs
weight: 10
url: /sv/java/com.groupdocs.comparison.interfaces/idocumentinfo/
---
**All Implemented Interfaces:**
java.io.Closeable
```
public interface IDocumentInfo extends Closeable
```

Tillhandahåller åtkomst till dokumentegenskaper.


Mer detaljer om dess användning finns i metoden [Document.getDocumentInfo()](../../com.groupdocs.comparison/document#getDocumentInfo--) eller i en [documentation](../https://docs.groupdocs.com/comparison/java/get-file-info/).


Exempel på användning:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    try (IDocumentInfo documentInfo = comparer.getSource().getDocumentInfo()) {
      for (int i = 0; i < documentInfo.getPageCount(); i++) {
          System.out.printf("File type: %s%nNumber of pages: %d", documentInfo.getFileType().getFileFormat(), documentInfo.getPageCount());
      }
    }
 }
 
````


## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getFileType()](#getFileType--) | Hämtar filens typ som representeras av enumen [FileType](../../com.groupdocs.comparison.result/filetype). |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.comparison.result.FileType-) | Ställer in filens typ med hjälp av enumen [FileType](../../com.groupdocs.comparison.result/filetype). |
|
|  | [getPageCount()](#getPageCount--) | Hämtar antalet i filen. |
|
|  | [setPageCount(int value)](#setPageCount-int-) | Ställer in antalet i filen. |
|
|  | [getSize()](#getSize--) | Hämtar filens storlek. |
|
|  | [setSize(long value)](#setSize-long-) | Ställer in filens storlek. |
|
|  | [getPagesInfo()](#getPagesInfo--) | Hämtar information för varje sida i filen med klassen [PageInfo](../../com.groupdocs.comparison.result/pageinfo). |
|
|  | [setPagesInfo(List<PageInfo> pageInfos)](#setPagesInfo-java.util.List-com.groupdocs.comparison.result.PageInfo--) | Ställer in information för varje sida i filen med klassen [PageInfo](../../com.groupdocs.comparison.result/pageinfo). |
|
|  | [close()](#close--) | Förstör objektet så att det blir omöjligt att hämta information om dokumentet med denna instans av objektet [IDocumentInfo](../../com.groupdocs.comparison.interfaces/idocumentinfo). |
|
### getFileType() {#getFileType--}
```
public abstract FileType getFileType()
```


Hämtar filens typ som representeras av enumen [FileType](../../com.groupdocs.comparison.result/filetype).


**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the type of the file

### setFileType(FileType value) {#setFileType-com.groupdocs.comparison.result.FileType-}
```
public abstract void setFileType(FileType value)
```


Ställer in filens typ med hjälp av enumen [FileType](../../com.groupdocs.comparison.result/filetype).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [FileType](../../com.groupdocs.comparison.result/filetype) | Typen av filen |
|

### getPageCount() {#getPageCount--}
```
public abstract int getPageCount()
```


Hämtar antalet i filen.


**Returns:**
int - antalet i filen

### setPageCount(int value) {#setPageCount-int-}
```
public abstract void setPageCount(int value)
```


Ställer in antalet i filen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | int | Antalet i filen |
|

### getSize() {#getSize--}
```
public abstract long getSize()
```


Hämtar filens storlek.


**Returns:**
long - storleken på filen

### setSize(long value) {#setSize-long-}
```
public abstract void setSize(long value)
```


Ställer in filens storlek.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | long | Storleken på filen |
|

### getPagesInfo() {#getPagesInfo--}
```
public abstract List<PageInfo> getPagesInfo()
```


Hämtar information för varje sida i filen med klassen [PageInfo](../../com.groupdocs.comparison.result/pageinfo).


**Returns:**
java.util.List<com.groupdocs.comparison.result.PageInfo> - information för varje sida i filen

### setPagesInfo(List<PageInfo> pageInfos) {#setPagesInfo-java.util.List-com.groupdocs.comparison.result.PageInfo--}
```
public abstract void setPagesInfo(List<PageInfo> pageInfos)
```


Ställer in information för varje sida i filen med klassen [PageInfo](../../com.groupdocs.comparison.result/pageinfo).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | pageInfos | java.util.List<com.groupdocs.comparison.result.PageInfo> | Information för varje sida i filen |
|

### close() {#close--}
```
public abstract void close()
```


Förstör objektet så att det blir omöjligt att hämta information om dokumentet med denna instans av objektet [IDocumentInfo](../../com.groupdocs.comparison.interfaces/idocumentinfo).
Tar också bort temporära filer och frigör använda resurser.


