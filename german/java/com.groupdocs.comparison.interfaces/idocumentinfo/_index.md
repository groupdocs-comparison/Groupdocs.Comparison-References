---
title: "IDocumentInfo"
second_title: "GroupDocs.Comparison für Java API-Referenz"
description: "Stellt Zugriff auf Dokumenteigenschaften bereit."
type: docs
weight: 10
url: /de/java/com.groupdocs.comparison.interfaces/idocumentinfo/
---
**All Implemented Interfaces:**
java.io.Closeable
```
public interface IDocumentInfo extends Closeable
```

Stellt Zugriff auf Dokumenteigenschaften bereit.


Weitere Details zu seiner Verwendung finden Sie in der Methode [Document.getDocumentInfo()](../../com.groupdocs.comparison/document#getDocumentInfo--) oder in einer [Dokumentation](../https://docs.groupdocs.com/comparison/java/get-file-info/).


Beispielverwendung:

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

| Methode | Beschreibung |
| --- | --- |
|  | [getFileType()](#getFileType--) | Ermittelt den Typ der Datei, der durch das Enum [FileType](../../com.groupdocs.comparison.result/filetype) repräsentiert wird. |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.comparison.result.FileType-) | Setzt den Typ der Datei mithilfe des Enums [FileType](../../com.groupdocs.comparison.result/filetype). |
|
|  | [getPageCount()](#getPageCount--) | Ermittelt die Anzahl der Datei. |
|
|  | [setPageCount(int value)](#setPageCount-int-) | Setzt die Anzahl der Datei. |
|
|  | [getSize()](#getSize--) | Ermittelt die Größe der Datei. |
|
|  | [setSize(long value)](#setSize-long-) | Setzt die Größe der Datei. |
|
|  | [getPagesInfo()](#getPagesInfo--) | Ermittelt Informationen für jede Seite der Datei mithilfe der Klasse [PageInfo](../../com.groupdocs.comparison.result/pageinfo). |
|
|  | [setPagesInfo(List<PageInfo> pageInfos)](#setPagesInfo-java.util.List-com.groupdocs.comparison.result.PageInfo--) | Setzt Informationen für jede Seite der Datei mithilfe der Klasse [PageInfo](../../com.groupdocs.comparison.result/pageinfo). |
|
|  | [close()](#close--) | Zerstört das Objekt, sodass es unmöglich ist, Informationen des Dokuments über diese Instanz des Objekts [IDocumentInfo](../../com.groupdocs.comparison.interfaces/idocumentinfo) abzurufen. |
|
### getFileType() {#getFileType--}
```
public abstract FileType getFileType()
```


Ermittelt den Typ der Datei, der durch das Enum [FileType](../../com.groupdocs.comparison.result/filetype) repräsentiert wird.


**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the type of the file

### setFileType(FileType value) {#setFileType-com.groupdocs.comparison.result.FileType-}
```
public abstract void setFileType(FileType value)
```


Setzt den Typ der Datei mithilfe des Enums [FileType](../../com.groupdocs.comparison.result/filetype).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [FileType](../../com.groupdocs.comparison.result/filetype) | Der Typ der Datei |
|

### getPageCount() {#getPageCount--}
```
public abstract int getPageCount()
```


Ermittelt die Anzahl der Datei.


**Returns:**
int - die Anzahl der Datei

### setPageCount(int value) {#setPageCount-int-}
```
public abstract void setPageCount(int value)
```


Setzt die Anzahl der Datei.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | int | Die Anzahl der Datei |
|

### getSize() {#getSize--}
```
public abstract long getSize()
```


Ermittelt die Größe der Datei.


**Returns:**
long - die Größe der Datei

### setSize(long value) {#setSize-long-}
```
public abstract void setSize(long value)
```


Setzt die Größe der Datei.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | long | Die Größe der Datei |
|

### getPagesInfo() {#getPagesInfo--}
```
public abstract List<PageInfo> getPagesInfo()
```


Ermittelt Informationen für jede Seite der Datei mithilfe der Klasse [PageInfo](../../com.groupdocs.comparison.result/pageinfo).


**Returns:**
java.util.List<com.groupdocs.comparison.result.PageInfo> - Informationen für jede Seite der Datei

### setPagesInfo(List<PageInfo> pageInfos) {#setPagesInfo-java.util.List-com.groupdocs.comparison.result.PageInfo--}
```
public abstract void setPagesInfo(List<PageInfo> pageInfos)
```


Setzt Informationen für jede Seite der Datei mithilfe der Klasse [PageInfo](../../com.groupdocs.comparison.result/pageinfo).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | pageInfos | java.util.List<com.groupdocs.comparison.result.PageInfo> | Informationen für jede Seite der Datei |
|

### close() {#close--}
```
public abstract void close()
```


Zerstört das Objekt, sodass es unmöglich ist, Informationen des Dokuments über diese Instanz des Objekts [IDocumentInfo](../../com.groupdocs.comparison.interfaces/idocumentinfo) abzurufen.
Löscht außerdem temporäre Dateien und gibt verwendete Ressourcen frei.


