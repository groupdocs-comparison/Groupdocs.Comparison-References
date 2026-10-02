---
title: "ApplyRevisionOptions"
second_title: "GroupDocs.Comparison for Java API Referansı"
description: "ApplyRevisionOptions sınıfı, revizyonların son belgeye uygulanmadan önceki durumunu güncellemenizi sağlar."
type: docs
weight: 10
url: /tr/java/com.groupdocs.comparison.words.revision/applyrevisionoptions/
---
**Inheritance:**
java.lang.Object
```
public class ApplyRevisionOptions
```

ApplyRevisionOptions sınıfı, revizyonların son belgeye uygulanmadan önceki durumunu güncellemenizi sağlar.


Revizyon uygulama sürecini özelleştirmek için çeşitli yapıcılar ve özellikler sağlar.


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
|  | [ApplyRevisionOptions()](#ApplyRevisionOptions--) | ApplyRevisionOptions sınıfının yeni bir örneğini başlatır. |
|
|  | [ApplyRevisionOptions(List<RevisionInfo> changes)](#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--) | Belirtilen revizyon listesiyle yeni bir ApplyRevisionOptions nesnesi oluşturur. |
|
|  | [ApplyRevisionOptions(List<RevisionInfo> changes, RevisionAction revisionAction)](#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--com.groupdocs.comparison.words.revision.RevisionAction-) | Belirtilen revizyon listesi ve ortak bir revizyon eylemiyle yeni bir ApplyRevisionOptions nesnesi oluşturur. |
|
|  | [ApplyRevisionOptions(RevisionAction revisionAction)](#ApplyRevisionOptions-com.groupdocs.comparison.words.revision.RevisionAction-) | Ortak bir revizyon eylemiyle yeni bir ApplyRevisionOptions nesnesi oluşturur. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getChanges()](#getChanges--) | Uygulanacak revizyonların listesini alır. |
|
|  | [setChanges(List<RevisionInfo> changes)](#setChanges-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--) | Uygulanacak revizyonların listesini ayarlar. |
|
|  | [getCommonHandler()](#getCommonHandler--) | Tüm revizyonlara uygulanacak ortak revizyon eylemini alır. |
|
|  | [setCommonHandler(RevisionAction commonHandler)](#setCommonHandler-com.groupdocs.comparison.words.revision.RevisionAction-) | Tüm revizyonlara uygulanacak ortak revizyon eylemini ayarlar. |
|
### ApplyRevisionOptions() {#ApplyRevisionOptions--}
```
public ApplyRevisionOptions()
```


ApplyRevisionOptions sınıfının yeni bir örneğini başlatır.


### ApplyRevisionOptions(List<RevisionInfo> changes) {#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--}
```
public ApplyRevisionOptions(List<RevisionInfo> changes)
```


Belirtilen revizyon listesiyle yeni bir ApplyRevisionOptions nesnesi oluşturur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değişiklikler | java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> | Uygulanacak revizyonların listesi |
|

### ApplyRevisionOptions(List<RevisionInfo> changes, RevisionAction revisionAction) {#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--com.groupdocs.comparison.words.revision.RevisionAction-}
```
public ApplyRevisionOptions(List<RevisionInfo> changes, RevisionAction revisionAction)
```


Belirtilen revizyon listesi ve ortak bir revizyon eylemiyle yeni bir ApplyRevisionOptions nesnesi oluşturur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değişiklikler | java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> | Uygulanacak revizyonların listesi |
|
|  | revisionAction | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | Tüm revizyonlara uygulanacak ortak revizyon eylemi |
|

### ApplyRevisionOptions(RevisionAction revisionAction) {#ApplyRevisionOptions-com.groupdocs.comparison.words.revision.RevisionAction-}
```
public ApplyRevisionOptions(RevisionAction revisionAction)
```


Ortak bir revizyon eylemiyle yeni bir ApplyRevisionOptions nesnesi oluşturur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | revisionAction | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | Tüm revizyonlara uygulanacak ortak revizyon eylemi |
|

### getChanges() {#getChanges--}
```
public List<RevisionInfo> getChanges()
```


Uygulanacak revizyonların listesini alır.


**Returns:**
java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> - revizyonların listesi

### setChanges(List<RevisionInfo> changes) {#setChanges-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--}
```
public void setChanges(List<RevisionInfo> changes)
```


Uygulanacak revizyonların listesini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değişiklikler | java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> | Revizyonların listesi |
|

### getCommonHandler() {#getCommonHandler--}
```
public RevisionAction getCommonHandler()
```


Tüm revizyonlara uygulanacak ortak revizyon eylemini alır.


**Returns:**
[RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) - the common revision action

### setCommonHandler(RevisionAction commonHandler) {#setCommonHandler-com.groupdocs.comparison.words.revision.RevisionAction-}
```
public void setCommonHandler(RevisionAction commonHandler)
```


Tüm revizyonlara uygulanacak ortak revizyon eylemini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | commonHandler | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | Ortak revizyon eylemi |
|

