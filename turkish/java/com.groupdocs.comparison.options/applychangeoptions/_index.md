---
title: "ApplyChangeOptions"
second_title: "GroupDocs.Comparison for Java API Referansı"
description: "Değişikliklerin sonuç belgesine uygulanmadan önce değişiklik listesini güncellemeye izin verir."
type: docs
weight: 10
url: /tr/java/com.groupdocs.comparison.options/applychangeoptions/
---
**Inheritance:**
java.lang.Object
```
public class ApplyChangeOptions
```

Değişikliklerin sonuç belgesine uygulanmadan önce değişiklik listesini güncellemeye izin verir.


Örnek kullanım:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);
     comparer.compare();
     ChangeInfo[] changes = comparer.getChanges();
     changes[0].setComparisonAction(ComparisonAction.REJECT);

     final ApplyChangeOptions applyChangeOptions = new ApplyChangeOptions(changes);

     comparer.applyChanges(resultFile, applyChangeOptions);
 }
 
````


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [ApplyChangeOptions()](#ApplyChangeOptions--) | ApplyChangeOptions sınıfının yeni bir örneğini başlatır. |
|
|  | [ApplyChangeOptions(List<ChangeInfo> changes)](#ApplyChangeOptions-java.util.List-com.groupdocs.comparison.result.ChangeInfo--) | ApplyChangeOptions sınıfının yeni bir örneğini değişiklik listesiyle başlatır. |
|
|  | [ApplyChangeOptions(ChangeInfo[] changes)](#ApplyChangeOptions-com.groupdocs.comparison.result.ChangeInfo---) | ApplyChangeOptions sınıfının yeni bir örneğini değişiklik dizisiyle başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getChanges()](#getChanges--) | Sonuç belgesine uygulanması gereken değişikliklerin bir dizisini alır. |
|
|  | [setChanges(ChangeInfo[] value)](#setChanges-com.groupdocs.comparison.result.ChangeInfo---) | Sonuç belgesine uygulanması gereken değişikliklerin bir dizisini ayarlar. |
|
|  | [setChanges(List<ChangeInfo> value)](#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--) | Sonuç belgesine uygulanması gereken değişikliklerin bir listesini ayarlar. |
|
|  | [isSaveOriginalState()](#isSaveOriginalState--) | Orijinal durumun kaydedilip kaydedilmeyeceğini belirleyen bir bayrağı alır. |
|
|  | [setSaveOriginalState(boolean saveOriginalState)](#setSaveOriginalState-boolean-) | Orijinal durumun kaydedilip kaydedilmeyeceğini belirleyen bir bayrağı ayarlar. |
|
### ApplyChangeOptions() {#ApplyChangeOptions--}
```
public ApplyChangeOptions()
```


ApplyChangeOptions sınıfının yeni bir örneğini başlatır.


### ApplyChangeOptions(List<ChangeInfo> changes) {#ApplyChangeOptions-java.util.List-com.groupdocs.comparison.result.ChangeInfo--}
```
public ApplyChangeOptions(List<ChangeInfo> changes)
```


ApplyChangeOptions sınıfının yeni bir örneğini değişiklik listesiyle başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değişiklikler | java.util.List<com.groupdocs.comparison.result.ChangeInfo> | Uygulanacak değişikliklerin listesi |
|

### ApplyChangeOptions(ChangeInfo[] changes) {#ApplyChangeOptions-com.groupdocs.comparison.result.ChangeInfo---}
```
public ApplyChangeOptions(ChangeInfo[] changes)
```


ApplyChangeOptions sınıfının yeni bir örneğini değişiklik dizisiyle başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | changes | [ChangeInfo\[\]](../../com.groupdocs.comparison.result/changeinfo) | Uygulanacak değişikliklerin listesi |
|

### getChanges() {#getChanges--}
```
public final ChangeInfo[] getChanges()
```


Sonuç belgesine uygulanması gereken değişikliklerin bir dizisini alır.


**Returns:**
com.groupdocs.comparison.result.ChangeInfo[] - uygulanacak değişikliklerin dizisi

### setChanges(ChangeInfo[] value) {#setChanges-com.groupdocs.comparison.result.ChangeInfo---}
```
public final void setChanges(ChangeInfo[] value)
```


Sonuç belgesine uygulanması gereken değişikliklerin bir dizisini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [ChangeInfo\[\]](../../com.groupdocs.comparison.result/changeinfo) | Uygulanacak değişikliklerin dizisi |
|

### setChanges(List<ChangeInfo> value) {#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--}
```
public final void setChanges(List<ChangeInfo> value)
```


Sonuç belgesine uygulanması gereken değişikliklerin bir listesini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.util.List<com.groupdocs.comparison.result.ChangeInfo> | Uygulanacak değişikliklerin listesi |
|

### isSaveOriginalState() {#isSaveOriginalState--}
```
public boolean isSaveOriginalState()
```


Orijinal durumun kaydedilip kaydedilmeyeceğini belirleyen bir bayrağı alır. Varsayılan değer: false.


**Returns:**
boolean - orijinal durum kaydedilecekse true, aksi takdirde false

### setSaveOriginalState(boolean saveOriginalState) {#setSaveOriginalState-boolean-}
```
public void setSaveOriginalState(boolean saveOriginalState)
```


Orijinal durumun kaydedilip kaydedilmeyeceğini belirleyen bir bayrağı ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | saveOriginalState | boolean | Orijinal durum kaydedilecekse true, aksi takdirde false |
|

