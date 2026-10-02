---
title: "Boyut"
second_title: "GroupDocs.Comparison for Java API Referansı"
description: "Karşılaştırmadaki belgenin boyutunu temsil eder."
type: docs
weight: 11
url: /tr/java/com.groupdocs.comparison.options.style/size/
---
**Inheritance:**
java.lang.Object
```
public class Size
```

Karşılaştırmadaki belgenin boyutunu temsil eder.


Örnek kullanım:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     final Size originalSize = new Size(100, 200);

     StyleSettings styleSettings = new StyleSettings();
     styleSettings.setOriginalSize(originalSize);

     final CompareOptions compareOptions = new CompareOptions();
     compareOptions.setInsertedItemStyle(styleSettings);

     comparer.compare(resultFile, compareOptions);
 }
 
````


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [Size()](#Size--) | Size class'ın yeni bir örneğini başlatır. |
|
|  | [Size(int width, int height)](#Size-int-int-) | Size class'ın, bir belgenin genişlik ve yüksekliğiyle yeni bir örneğini başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getWidth()](#getWidth--) | Orijinal bir belgenin genişliğini alır. |
|
|  | [setWidth(int value)](#setWidth-int-) | Orijinal bir belgenin genişliğini ayarlar. |
|
|  | [getHeight()](#getHeight--) | Orijinal bir belgenin yüksekliğini alır. |
|
|  | [setHeight(int value)](#setHeight-int-) | Orijinal bir belgenin yüksekliğini ayarlar. |
|
### Size() {#Size--}
```
public Size()
```


Size class'ın yeni bir örneğini başlatır.


### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


Size class'ın, bir belgenin genişlik ve yüksekliğiyle yeni bir örneğini başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| genişlik | int |  |
| yükseklik | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Orijinal bir belgenin genişliğini alır.


**Returns:**
int - belgenin genişliği

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Orijinal bir belgenin genişliğini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | int | Belgenin genişliği |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Orijinal bir belgenin yüksekliğini alır.


**Returns:**
int - belgenin yüksekliği

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Orijinal bir belgenin yüksekliğini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | int | Belgenin yüksekliği |
|

