---
title: "RevisionInfo"
second_title: "GroupDocs.Comparison for Java API Referansı"
description: "Belgedeki bir revizyonu temsil eder."
type: docs
weight: 12
url: /tr/java/com.groupdocs.comparison.words.revision/revisioninfo/
---
**Inheritance:**
java.lang.Object
```
public class RevisionInfo
```

Belgedeki bir revizyonu temsil eder.


Bir revizyon, belgeye yapılan revizyon değişikliği hakkında bilgileri kapsüller.
Bu sınıf, revizyon hakkında, türü gibi bilgileri almak için yöntemler sağlar,
içerik, yazar ve benzeri.

Örnek kullanım:

````

 try (RevisionHandler revisionHandler = new RevisionHandler(sourceFile)) {
     List revisionList = revisionHandler.getRevisions();

     for (RevisionInfo revisionInfo : revisionList) {
         System.out.println("Revision Type: " + revisionInfo.getType());
         System.out.println("Text: " + revisionInfo.getText());
         System.out.println("Author: " + revisionInfo.getAuthor());
     }
 }
 
````


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [RevisionInfo()](#RevisionInfo--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getAction()](#getAction--) | Revizyonla ilişkili eylemi alır (kabul et veya reddet). |
|
|  | [setAction(RevisionAction value)](#setAction-com.groupdocs.comparison.words.revision.RevisionAction-) | Revizyonla ilişkili değeri ayarlar (kabul et veya reddet). |
|
|  | [getText()](#getText--) | Revizyonun metin içeriğini alır. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Revizyonun değer içeriğini ayarlar. |
|
|  | [getAuthor()](#getAuthor--) | Revizyonun yazarını alır. |
|
|  | [setAuthor(String value)](#setAuthor-java.lang.String-) | Revizyonun değerini ayarlar. |
|
|  | [getType()](#getType--) | Revizyonun tipini alır, tipine bağlı olarak Action (kabul veya reddet) mantığı değişir. |
|
|  | [setType(RevisionType value)](#setType-com.groupdocs.comparison.words.revision.RevisionType-) | Revizyonun değerini ayarlar, değere bağlı olarak Action (kabul veya reddet) mantığı değişir. |
|
### RevisionInfo() {#RevisionInfo--}
```
public RevisionInfo()
```


### getAction() {#getAction--}
```
public RevisionAction getAction()
```


Revizyonla ilişkili eylemi alır (kabul veya reddet). Bu alan, revizyonun görüntülenmesini etkilemenizi sağlar.


**Returns:**
[RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) - the action associated with the revision.

### setAction(RevisionAction value) {#setAction-com.groupdocs.comparison.words.revision.RevisionAction-}
```
public void setAction(RevisionAction value)
```


Revizyonla ilişkili değeri ayarlar (kabul veya reddet). Bu alan, revizyonun görüntülenmesini etkilemenizi sağlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | Revizyonla ilişkili değer. |
|

### getText() {#getText--}
```
public String getText()
```


Revizyonun metin içeriğini alır.


**Returns:**
java.lang.String - revizyonun metin içeriği.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Revizyonun değer içeriğini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.lang.String | Revizyonun değer içeriği. |
|

### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Revizyonun yazarını alır.


**Returns:**
java.lang.String - revizyonun yazarı.

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public void setAuthor(String value)
```


Revizyonun değerini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.lang.String | Revizyonun değeri. |
|

### getType() {#getType--}
```
public RevisionType getType()
```


Revizyonun tipini alır, tipine bağlı olarak Action (kabul veya reddet) mantığı değişir.


**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) - the type of the revision.

### setType(RevisionType value) {#setType-com.groupdocs.comparison.words.revision.RevisionType-}
```
public void setType(RevisionType value)
```


Revizyonun değerini ayarlar, değere bağlı olarak Action (kabul veya reddet) mantığı değişir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) | Revizyonun değeri. |
|

