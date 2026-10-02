---
title: "RevisionHandler"
second_title: "GroupDocs.Comparison for Java API Referansı"
description: "Revizyonların işlenmesini kontrol eden bir sınıfı temsil eder."
type: docs
weight: 11
url: /tr/java/com.groupdocs.comparison.words.revision/revisionhandler/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class RevisionHandler implements Closeable
```

Revizyonların işlenmesini kontrol eden bir sınıfı temsil eder.


RevisionHandler sınıfı, belgelerdeki revizyonlarla çalışmanıza olanak tanır.
Revizyonların listesini almak, revizyonlara değişiklik uygulamak ve değiştirilmiş belgeyi kaydetmek için yöntemler sağlar.


Örnek kullanım:

````

 try (RevisionHandler revisionHandler = new RevisionHandler(sourceFile)) {
     List revisionList = revisionHandler.getRevisions();

     for (RevisionInfo revisionInfo : revisionList) {
         if (revisionInfo.getType() == RevisionType.DELETION)
             // Set an action to be applied to the revision
             revisionInfo.setAction(RevisionAction.Accept);
     }
     // Create an instance of ApplyRevisionOptions
     ApplyRevisionOptions revisionChanges = new ApplyRevisionOptions();
     revisionChanges.setChanges(revisionList);
     // Apply the revisions using the options
     revisionHandler.applyRevisionChanges(resultFile, revisionChanges);
 }
 
````


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [RevisionHandler(String filePath)](#RevisionHandler-java.lang.String-) | Revizyonları içeren dosyanın yoluyla RevisionHandler sınıfının yeni bir örneğini başlatır. |
|
|  | [RevisionHandler(Path filePath)](#RevisionHandler-java.nio.file.Path-) | Revizyonları içeren dosyanın yoluyla RevisionHandler sınıfının yeni bir örneğini başlatır. |
|
|  | [RevisionHandler(InputStream file, FileType fileType)](#RevisionHandler-java.io.InputStream-com.groupdocs.comparison.result.FileType-) | Revizyonları içeren bir dosya akışıyla RevisionHandler sınıfının yeni bir örneğini başlatır. |
|
|  | [RevisionHandler(Document document)](#RevisionHandler-com.aspose.words.Document-) | Bir belgeyle RevisionHandler sınıfının yeni bir örneğini başlatır. |
|
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [SOURCE_PATH_IS_NULL](#SOURCE-PATH-IS-NULL) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getRevisions()](#getRevisions--) | Tüm revizyonların listesini alır. |
|
|  | [applyRevisionChanges(ApplyRevisionOptions changes)](#applyRevisionChanges-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | Revizyonlardaki değişiklikleri işler ve orijinal dosyaya uygular. |
|
|  | [applyRevisionChanges(Path filePath, ApplyRevisionOptions changes)](#applyRevisionChanges-java.nio.file.Path-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | Revizyonlardaki değişiklikleri işler ve sonucu belirtilen dosyaya yazar. |
|
|  | [applyRevisionChanges(String filePath, ApplyRevisionOptions changes)](#applyRevisionChanges-java.lang.String-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | Revizyonlardaki değişiklikleri işler ve sonucu belirtilen dosyaya yazar. |
|
|  | [applyRevisionChanges(OutputStream outputStream, ApplyRevisionOptions changes)](#applyRevisionChanges-java.io.OutputStream-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | Revizyonlardaki değişiklikleri işler ve sonucu belge akışına yazar. |
|
| [close()](#close--) |  |
### RevisionHandler(String filePath) {#RevisionHandler-java.lang.String-}
```
public RevisionHandler(String filePath)
```


Revizyonları içeren dosyanın yoluyla RevisionHandler sınıfının yeni bir örneğini başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Dosyanın yolu. |
|

### RevisionHandler(Path filePath) {#RevisionHandler-java.nio.file.Path-}
```
public RevisionHandler(Path filePath)
```


Revizyonları içeren dosyanın yoluyla RevisionHandler sınıfının yeni bir örneğini başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Dosyanın yolu. |
|

### RevisionHandler(InputStream file, FileType fileType) {#RevisionHandler-java.io.InputStream-com.groupdocs.comparison.result.FileType-}
```
public RevisionHandler(InputStream file, FileType fileType)
```


Revizyonları içeren bir dosya akışıyla RevisionHandler sınıfının yeni bir örneğini başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | dosya | java.io.InputStream | Kaynak belge akışı. |
|
|  | fileType | [FileType](../../com.groupdocs.comparison.result/filetype) | Dosyanın türü. |
|

### RevisionHandler(Document document) {#RevisionHandler-com.aspose.words.Document-}
```
public RevisionHandler(Document document)
```


Bir belgeyle RevisionHandler sınıfının yeni bir örneğini başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | belge | com.aspose.words.Document | Belge. |
|

### SOURCE_PATH_IS_NULL {#SOURCE-PATH-IS-NULL}
```
public static final String SOURCE_PATH_IS_NULL
```


### getRevisions() {#getRevisions--}
```
public List<RevisionInfo> getRevisions()
```


Tüm revizyonların listesini alır.


Revizyonların başlangıçta bir grup içinde sıralanmış olması nedeniyle, revizyonlar bir Listeden alınmalıdır.
Listede, tek bir revizyon aynı genel metne sahip birden fazla revizyona bölünebilir.
Liste aynı genel metne sahip revizyonlar içerebileceği için, bu kullanıcı için bir revizyon listesi oluşturulurken kontrol edilmelidir.
Bu, burada List\<RevisionGroup\> grupları kullanılarak kontrol edilir.


**Returns:**
java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> - revizyonların listesi.

### applyRevisionChanges(ApplyRevisionOptions changes) {#applyRevisionChanges-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(ApplyRevisionOptions changes)
```


Revizyonlardaki değişiklikleri işler ve orijinal dosyaya uygular.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | Değiştirilen revizyonların listesi. |
|

### applyRevisionChanges(Path filePath, ApplyRevisionOptions changes) {#applyRevisionChanges-java.nio.file.Path-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(Path filePath, ApplyRevisionOptions changes)
```


Revizyonlardaki değişiklikleri işler ve sonucu belirtilen dosyaya yazar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Sonuç dosya yolu. |
|
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | Değiştirilen revizyonların listesi. |
|

### applyRevisionChanges(String filePath, ApplyRevisionOptions changes) {#applyRevisionChanges-java.lang.String-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(String filePath, ApplyRevisionOptions changes)
```


Revizyonlardaki değişiklikleri işler ve sonucu belirtilen dosyaya yazar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Sonuç dosya yolu. |
|
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | Değiştirilen revizyonların listesi. |
|

### applyRevisionChanges(OutputStream outputStream, ApplyRevisionOptions changes) {#applyRevisionChanges-java.io.OutputStream-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(OutputStream outputStream, ApplyRevisionOptions changes)
```


Revizyonlardaki değişiklikleri işler ve sonucu belge akışına yazar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | outputStream | java.io.OutputStream | Sonuç belge akışı. |
|
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | Değiştirilen revizyonların listesi. |
|

### close() {#close--}
```
public void close()
```




