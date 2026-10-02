---
title: "SaveOptions"
second_title: "GroupDocs.Comparison for Java API Referansı"
description: "Bir belgeyi kaydederken ek seçenekler belirtmenize olanak tanır."
type: docs
weight: 10
url: /tr/java/com.groupdocs.comparison.options.save/saveoptions/
---
**Inheritance:**
java.lang.Object
```
public class SaveOptions
```

Bir belgeyi kaydederken ek seçenekler belirtmenize olanak tanır.


Örnek kullanım:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    final SaveOptions saveOptions = new SaveOptions();
    saveOptions.setPassword("passw");

    comparer.compare(resultFile, saveOptions);
 }
 
````


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [SaveOptions()](#SaveOptions--) | SaveOptions sınıfının yeni bir örneğini başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getCloneMetadataType()](#getCloneMetadataType--) | Meta veri kaydetme sonuç belgesini işleme stratejisini alır. |
|
|  | [setCloneMetadataType(MetadataType value)](#setCloneMetadataType-com.groupdocs.comparison.options.enums.MetadataType-) | Meta veri kaydetme sonuç belgesini işleme stratejisini ayarlar. |
|
|  | [getFileAuthorMetadata()](#getFileAuthorMetadata--) | Sonuç belgesine, [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR) olarak ayarlandığında yerleştirilecek bir metadata nesnesi alır. |
|
|  | [setFileAuthorMetadata(FileAuthorMetadata value)](#setFileAuthorMetadata-com.groupdocs.comparison.options.FileAuthorMetadata-) | Sonuç belgesine, [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR) olarak ayarlandığında yerleştirilmesi gereken bir metadata nesnesi ayarlar. |
|
|  | [getPassword()](#getPassword--) | Sonuç belgesi için bir şifre alır. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Sonuç belgesi için bir şifre ayarlar. |
|
|  | [getFolderPath()](#getFolderPath--) | Sonuç görüntülerinin kaydedileceği klasör yolunu alır. |
|
|  | [setFolderPath(String value)](#setFolderPath-java.lang.String-) | Sonuç görüntülerinin kaydedilmesi gereken klasör yolunu ayarlar. |
|
|  | [setFolderPath(Path value)](#setFolderPath-java.nio.file.Path-) | Sonuç görüntülerinin kaydedilmesi gereken klasör yolunu ayarlar. |
|
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```


SaveOptions sınıfının yeni bir örneğini başlatır.


### getCloneMetadataType() {#getCloneMetadataType--}
```
public final MetadataType getCloneMetadataType()
```


Meta veri kaydetme sonuç belgesini işleme stratejisini alır.
Olası değerler [MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) enumunda bulunur.


**Returns:**
[MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) - the stragegy of processing metadata

### setCloneMetadataType(MetadataType value) {#setCloneMetadataType-com.groupdocs.comparison.options.enums.MetadataType-}
```
public final void setCloneMetadataType(MetadataType value)
```


Meta veri kaydetme sonuç belgesini işleme stratejisini ayarlar.
Olası değerler [MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) enumunda bulunur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) | Metadata işleme stratejisi |
|

### getFileAuthorMetadata() {#getFileAuthorMetadata--}
```
public final FileAuthorMetadata getFileAuthorMetadata()
```


Sonuç belgesine, [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR) olarak ayarlandığında yerleştirilecek bir metadata nesnesi alır.


**Returns:**
[FileAuthorMetadata](../../com.groupdocs.comparison.options/fileauthormetadata) - the metadata object

### setFileAuthorMetadata(FileAuthorMetadata value) {#setFileAuthorMetadata-com.groupdocs.comparison.options.FileAuthorMetadata-}
```
public final void setFileAuthorMetadata(FileAuthorMetadata value)
```


Sonuç belgesine, [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR) olarak ayarlandığında yerleştirilmesi gereken bir metadata nesnesi ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [FileAuthorMetadata](../../com.groupdocs.comparison.options/fileauthormetadata) | Metadata nesnesi |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Sonuç belgesi için bir şifre alır.


**Returns:**
java.lang.String - şifre

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Sonuç belgesi için bir şifre ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.lang.String | Şifre |
|

### getFolderPath() {#getFolderPath--}
```
public final String getFolderPath()
```


Sonuç görüntülerinin kaydedileceği klasör yolunu alır.
Yalnızca Görüntü Karşılaştırması için kullanılır.


**Returns:**
java.lang.String - sonuç görüntülerini kaydetmek için klasör yolu

### setFolderPath(String value) {#setFolderPath-java.lang.String-}
```
public final void setFolderPath(String value)
```


Sonuç görüntülerinin kaydedilmesi gereken klasör yolunu ayarlar.
Yalnızca Görüntü Karşılaştırması için kullanılır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.lang.String | Sonuç görüntülerini kaydetmek için klasör yolu |
|

### setFolderPath(Path value) {#setFolderPath-java.nio.file.Path-}
```
public final void setFolderPath(Path value)
```


Sonuç görüntülerinin kaydedilmesi gereken klasör yolunu ayarlar.
Yalnızca Görüntü Karşılaştırması için kullanılır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.nio.file.Path | Sonuç görüntülerini kaydetmek için klasör yolu |
|

