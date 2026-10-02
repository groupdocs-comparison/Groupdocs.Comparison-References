---
title: "OriginalSize"
second_title: "GroupDocs.Comparison for Java API Referansı"
description: "Karşılaştırma sonucundaki bir belgenin orijinal boyutunu temsil eder."
type: docs
weight: 14
url: /tr/java/com.groupdocs.comparison.options/originalsize/
---
**Inheritance:**
java.lang.Object
```
public class OriginalSize
```

Karşılaştırma sonucundaki bir belgenin orijinal boyutunu temsil eder.


Orijinal boyut, belgenin sayfalarının boyutlarını (genişlik ve yükseklik) içerir.


Örnek kullanım:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     CompareOptions compareOptions = new CompareOptions();
     final OriginalSize originalSize = compareOptions.getOriginalSize();
     originalSize.setWidth(480);
     originalSize.setHeight(640);

     comparer.compare(resultFile, compareOptions);
 }
 
````


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [OriginalSize()](#OriginalSize--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getWidth()](#getWidth--) | Belgenin sayfalarının genişliğini alır. |
|
|  | [setWidth(int value)](#setWidth-int-) | Belgenin sayfalarının genişliğini ayarlar. |
|
|  | [getHeight()](#getHeight--) | Belgenin sayfalarının yüksekliğini alır. |
|
|  | [setHeight(int value)](#setHeight-int-) | Belgenin sayfalarının yüksekliğini ayarlar. |
|
### OriginalSize() {#OriginalSize--}
```
public OriginalSize()
```


### getWidth() {#getWidth--}
```
public final int getWidth()
```


Belgenin sayfalarının genişliğini alır.


**Returns:**
int - belgenin sayfalarının genişliği.

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Belgenin sayfalarının genişliğini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | int | Belgenin sayfalarının genişliği. |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Belgenin sayfalarının yüksekliğini alır.


**Returns:**
int - belgenin sayfalarının yüksekliği.

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Belgenin sayfalarının yüksekliğini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | int | Belgenin sayfalarının yüksekliği. |
|

