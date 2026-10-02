---
title: "IDocumentInfo"
second_title: "GroupDocs.Comparison for Java API Referansı"
description: "Belge özelliklerine erişim sağlar."
type: docs
weight: 10
url: /tr/java/com.groupdocs.comparison.interfaces/idocumentinfo/
---
**All Implemented Interfaces:**
java.io.Closeable
```
public interface IDocumentInfo extends Closeable
```

Belge özelliklerine erişim sağlar.


Kullanımıyla ilgili daha fazla ayrıntı, [Document.getDocumentInfo()](../../com.groupdocs.comparison/document#getDocumentInfo--) yöntemi veya bir [belge](../https://docs.groupdocs.com/comparison/java/get-file-info/) içinde bulunabilir.


Örnek kullanım:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    try (IDocumentInfo documentInfo = comparer.getSource().getDocumentInfo()) {
      for (int i = 0; i < documentInfo.getPageCount(); i++) {
          System.out.printf("File type: %s%nNumber of pages: %d", documentInfo.getFileType().getFileFormat(), documentInfo.getPageCount());
      }
    }
 }
 
````


## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getFileType()](#getFileType--) | [FileType](../../com.groupdocs.comparison.result/filetype) enum'ı tarafından temsil edilen dosyanın tipini alır. |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.comparison.result.FileType-) | [FileType](../../com.groupdocs.comparison.result/filetype) enum'ı kullanarak dosyanın tipini ayarlar. |
|
|  | [getPageCount()](#getPageCount--) | Dosyanın sayısını alır. |
|
|  | [setPageCount(int value)](#setPageCount-int-) | Dosyanın sayısını ayarlar. |
|
|  | [getSize()](#getSize--) | Dosyanın boyutunu alır. |
|
|  | [setSize(long value)](#setSize-long-) | Dosyanın boyutunu ayarlar. |
|
|  | [getPagesInfo()](#getPagesInfo--) | [PageInfo](../../com.groupdocs.comparison.result/pageinfo) sınıfını kullanarak dosyanın her sayfası için bilgileri alır. |
|
|  | [setPagesInfo(List<PageInfo> pageInfos)](#setPagesInfo-java.util.List-com.groupdocs.comparison.result.PageInfo--) | [PageInfo](../../com.groupdocs.comparison.result/pageinfo) sınıfını kullanarak dosyanın her sayfası için bilgileri ayarlar. |
|
|  | [close()](#close--) | Bu nesneyi yok ederek, bu [IDocumentInfo](../../com.groupdocs.comparison.interfaces/idocumentinfo) nesnesi örneğiyle belgenin bilgilerini almayı imkansız hâle getirir. |
|
### getFileType() {#getFileType--}
```
public abstract FileType getFileType()
```


[FileType](../../com.groupdocs.comparison.result/filetype) enum'ı tarafından temsil edilen dosyanın tipini alır.


**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the type of the file

### setFileType(FileType value) {#setFileType-com.groupdocs.comparison.result.FileType-}
```
public abstract void setFileType(FileType value)
```


[FileType](../../com.groupdocs.comparison.result/filetype) enum'ı kullanarak dosyanın tipini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [FileType](../../com.groupdocs.comparison.result/filetype) | Dosyanın tipi |
|

### getPageCount() {#getPageCount--}
```
public abstract int getPageCount()
```


Dosyanın sayısını alır.


**Returns:**
int - dosyanın sayısı

### setPageCount(int value) {#setPageCount-int-}
```
public abstract void setPageCount(int value)
```


Dosyanın sayısını ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | int | Dosyanın sayısı |
|

### getSize() {#getSize--}
```
public abstract long getSize()
```


Dosyanın boyutunu alır.


**Returns:**
long - dosyanın boyutu

### setSize(long value) {#setSize-long-}
```
public abstract void setSize(long value)
```


Dosyanın boyutunu ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | long | Dosyanın boyutu |
|

### getPagesInfo() {#getPagesInfo--}
```
public abstract List<PageInfo> getPagesInfo()
```


[PageInfo](../../com.groupdocs.comparison.result/pageinfo) sınıfını kullanarak dosyanın her sayfası için bilgileri alır.


**Returns:**
java.util.List<com.groupdocs.comparison.result.PageInfo> - dosyanın her sayfası için bilgi

### setPagesInfo(List<PageInfo> pageInfos) {#setPagesInfo-java.util.List-com.groupdocs.comparison.result.PageInfo--}
```
public abstract void setPagesInfo(List<PageInfo> pageInfos)
```


[PageInfo](../../com.groupdocs.comparison.result/pageinfo) sınıfını kullanarak dosyanın her sayfası için bilgileri ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | pageInfos | java.util.List<com.groupdocs.comparison.result.PageInfo> | Dosyanın her sayfası için bilgi |
|

### close() {#close--}
```
public abstract void close()
```


Bu nesneyi yok ederek, bu [IDocumentInfo](../../com.groupdocs.comparison.interfaces/idocumentinfo) nesnesi örneğiyle belgenin bilgilerini almayı imkansız hâle getirir.
Ayrıca geçici dosyaları siler ve kullanılan kaynakları serbest bırakır.


