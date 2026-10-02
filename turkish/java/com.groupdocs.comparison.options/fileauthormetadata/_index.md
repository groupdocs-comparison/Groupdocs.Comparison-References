---
title: "FileAuthorMetadata"
second_title: "GroupDocs.Comparison for Java API Referansı"
description: "Belgelerin yazar meta verileri hakkında bilgi yapılandırılmasına izin verir."
type: docs
weight: 12
url: /tr/java/com.groupdocs.comparison.options/fileauthormetadata/
---
**Inheritance:**
java.lang.Object
```
public class FileAuthorMetadata
```

Belgenin yazar meta verileri hakkında bilgileri yapılandırmaya izin verir.


Örnek kullanım:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     SaveOptions saveOptions = new SaveOptions();
     saveOptions.setCloneMetadataType(MetadataType.FILE_AUTHOR);

     final FileAuthorMetadata fileAuthorMetadata = new FileAuthorMetadata();
     fileAuthorMetadata.setAuthor("Tom");
     fileAuthorMetadata.setCompany("GroupDocs");
     fileAuthorMetadata.setLastSaveBy("Jack");

     saveOptions.setFileAuthorMetadata(fileAuthorMetadata);

     comparer.compare(resultFile, saveOptions);
 }
 
````


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [FileAuthorMetadata()](#FileAuthorMetadata--) | FileAuthorMetadata sınıfının yeni bir örneğini başlatır. |
|
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [GROUP_DOCS](#GROUP-DOCS) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getAuthor()](#getAuthor--) | Bir belgenin yazarını alır. |
|
|  | [setAuthor(String value)](#setAuthor-java.lang.String-) | Bir belgenin yazarını ayarlar. |
|
|  | [getLastSaveBy()](#getLastSaveBy--) | Belgeyi en son kaydeden kişinin adını alır. |
|
|  | [setLastSaveBy(String value)](#setLastSaveBy-java.lang.String-) | Belgeyi en son kaydeden kişinin adını ayarlar. |
|
|  | [getCompany()](#getCompany--) | Belgenin ait olduğu şirketin adını alır. |
|
|  | [setCompany(String value)](#setCompany-java.lang.String-) | Belgenin ait olduğu şirketin adını ayarlar. |
|
### FileAuthorMetadata() {#FileAuthorMetadata--}
```
public FileAuthorMetadata()
```


FileAuthorMetadata sınıfının yeni bir örneğini başlatır.


### GROUP_DOCS {#GROUP-DOCS}
```
public static final String GROUP_DOCS
```


### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```


Bir belgenin yazarını alır.


**Returns:**
java.lang.String - yazar

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```


Bir belgenin yazarını ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.lang.String | Yazar |
|

### getLastSaveBy() {#getLastSaveBy--}
```
public final String getLastSaveBy()
```


Belgeyi en son kaydeden kişinin adını alır.


**Returns:**
java.lang.String - ad

### setLastSaveBy(String value) {#setLastSaveBy-java.lang.String-}
```
public final void setLastSaveBy(String value)
```


Belgeyi en son kaydeden kişinin adını ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.lang.String | Bir kişinin adı |
|

### getCompany() {#getCompany--}
```
public final String getCompany()
```


Belgenin ait olduğu şirketin adını alır.


**Returns:**
java.lang.String - bir şirketin adı

### setCompany(String value) {#setCompany-java.lang.String-}
```
public final void setCompany(String value)
```


Belgenin ait olduğu şirketin adını ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.lang.String | Bir şirketin adı |
|

