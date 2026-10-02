---
title: "GetChangeOptions"
second_title: "GroupDocs.Comparison for Java API Referansı"
description: "Karşılaştırma sonucundan belirli değişiklik türlerini almayı filtrelemeyi yapılandırmaya izin verir."
type: docs
weight: 13
url: /tr/java/com.groupdocs.comparison.options/getchangeoptions/
---
**Inheritance:**
java.lang.Object
```
public class GetChangeOptions
```

Karşılaştırma sonucundan belirli değişiklik türlerini almayı filtrelemeyi yapılandırmaya izin verir.


Örnek kullanım:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);
     comparer.compare();

     GetChangeOptions getChangeOptions = new GetChangeOptions();

     getChangeOptions.setFilter(ChangeType.DELETED);

     ChangeInfo[] changes = comparer.getChanges(getChangeOptions);
     System.out.println(Arrays.toString(changes));
 }
 
````


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [GetChangeOptions()](#GetChangeOptions--) | GetChangeOptions sınıfının yeni bir örneğini başlatır. |
|
|  | [GetChangeOptions(ChangeType filter)](#GetChangeOptions-com.groupdocs.comparison.result.ChangeType-) | Belirtilen filtre türü için GetChangeOptions sınıfının yeni bir örneğini başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getFilter()](#getFilter--) | Karşılaştırma sonucundan belirli değişiklik türlerini almak için filtreyi alır. |
|
|  | [setFilter(ChangeType value)](#setFilter-com.groupdocs.comparison.result.ChangeType-) | Karşılaştırma sonucundan belirli değişiklik türlerini almak için filtreyi ayarlar. |
|
### GetChangeOptions() {#GetChangeOptions--}
```
public GetChangeOptions()
```


GetChangeOptions sınıfının yeni bir örneğini başlatır.


### GetChangeOptions(ChangeType filter) {#GetChangeOptions-com.groupdocs.comparison.result.ChangeType-}
```
public GetChangeOptions(ChangeType filter)
```


Belirtilen filtre türü için GetChangeOptions sınıfının yeni bir örneğini başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filter | [ChangeType](../../com.groupdocs.comparison.result/changetype) |  |

### getFilter() {#getFilter--}
```
public final ChangeType getFilter()
```


Karşılaştırma sonucundan belirli değişiklik türlerini almak için filtreyi alır.


**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - the filter specifying the types of changes to be retrieved.

### setFilter(ChangeType value) {#setFilter-com.groupdocs.comparison.result.ChangeType-}
```
public final void setFilter(ChangeType value)
```


Karşılaştırma sonucundan belirli değişiklik türlerini almak için filtreyi ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [ChangeType](../../com.groupdocs.comparison.result/changetype) | Alınacak değişiklik türlerini belirten filtre. |
|

