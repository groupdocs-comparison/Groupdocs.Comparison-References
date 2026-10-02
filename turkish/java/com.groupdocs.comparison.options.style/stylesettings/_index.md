---
title: "StyleSettings"
second_title: "GroupDocs.Comparison for Java API Referansı"
description: "Bu sınıf, metin biçimlendirme için stil ayarlarını temsil eder."
type: docs
weight: 12
url: /tr/java/com.groupdocs.comparison.options.style/stylesettings/
---
**Inheritance:**
java.lang.Object
```
public class StyleSettings
```

Bu sınıf, metin biçimlendirme için stil ayarlarını temsil eder.


Bu sınıfı, yazı tipi rengini, vurgulama rengini, stil özelliklerini (kalın, altı çizili, italik, üstü çizili) özelleştirmek için kullanın,
dize ayırıcıları, orijinal boyutlar ve metin için kelime ayırıcıları.


Örnek kullanım:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    StyleSettings styleSettings = new StyleSettings();
    styleSettings.setFontColor(Color.GREEN);
    styleSettings.setBold(true);
    styleSettings.setUnderline(true);

    final CompareOptions compareOptions = new CompareOptions();
    compareOptions.setInsertedItemStyle(styleSettings);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [StyleSettings()](#StyleSettings--) | StyleSettings sınıfının yeni bir örneğini başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getFontColor()](#getFontColor--) | Yazı tipi rengini alır. |
|
|  | [setFontColor(Color value)](#setFontColor-java.awt.Color-) | Yazı tipi rengini ayarlar. |
|
|  | [getShapeColor()](#getShapeColor--) | Şekil rengini alır. |
|
|  | [setShapeColor(Color value)](#setShapeColor-java.awt.Color-) | Şekil rengini ayarlar. |
|
|  | [getHighlightColor()](#getHighlightColor--) | Vurgulama rengini alır. |
|
|  | [setHighlightColor(Color value)](#setHighlightColor-java.awt.Color-) | Vurgulama rengini ayarlar. |
|
|  | [isBold()](#isBold--) | Metnin kalın olup olmayacağını gösteren bir bayrağı alır. |
|
|  | [setBold(boolean value)](#setBold-boolean-) | Metnin kalın olup olmayacağını gösteren bir bayrağı ayarlar. |
|
|  | [isUnderline()](#isUnderline--) | Metnin altı çizili olup olmayacağını gösteren bir bayrağı alır. |
|
|  | [setUnderline(boolean value)](#setUnderline-boolean-) | Metnin altı çizili olup olmadığını gösteren bir bayrak ayarlar. |
|
|  | [isItalic()](#isItalic--) | Metnin italik olup olmayacağını gösteren bir bayrağı alır. |
|
|  | [setItalic(boolean value)](#setItalic-boolean-) | Metnin italik olup olmadığını gösteren bir bayrak ayarlar. |
|
|  | [isStrikethrough()](#isStrikethrough--) | Metnin üstü çizili olup olmayacağını gösteren bir bayrağı alır. |
|
|  | [setStrikethrough(boolean value)](#setStrikethrough-boolean-) | Metnin üstü çizili olup olmadığını gösteren bir bayrak ayarlar. |
|
|  | [getStartStringSeparator()](#getStartStringSeparator--) | Başlangıç dize ayıracısını alır. |
|
|  | [setStartStringSeparator(String value)](#setStartStringSeparator-java.lang.String-) | Başlangıç dize ayıracısını ayarlar. |
|
|  | [getEndStringSeparator()](#getEndStringSeparator--) | Bitiş dize ayıracısını alır. |
|
|  | [setEndStringSeparator(String value)](#setEndStringSeparator-java.lang.String-) | Bitiş dize ayıracısını ayarlar. |
|
|  | [getOriginalSize()](#getOriginalSize--) | Karşılaştırılan belgelerin orijinal boyutunu alır. |
|
|  | [setOriginalSize(Size value)](#setOriginalSize-com.groupdocs.comparison.options.style.Size-) | Karşılaştırılan belgelerin orijinal boyutunu ayarlar. |
|
|  | [getWordsSeparators()](#getWordsSeparators--) | Kelime ayırıcı karakterleri alır. |
|
|  | [setWordsSeparators(char[] value)](#setWordsSeparators-char---) | Kelime ayırıcı karakterleri ayarlar. |
|
### StyleSettings() {#StyleSettings--}
```
public StyleSettings()
```


StyleSettings sınıfının yeni bir örneğini başlatır.


### getFontColor() {#getFontColor--}
```
public final Color getFontColor()
```


Yazı tipi rengini alır.


**Returns:**
java.awt.Color - yazı tipi rengi.

### setFontColor(Color value) {#setFontColor-java.awt.Color-}
```
public final void setFontColor(Color value)
```


Yazı tipi rengini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.awt.Color | Yeni yazı tipi rengi. |
|

### getShapeColor() {#getShapeColor--}
```
public final Color getShapeColor()
```


Şekil rengini alır.


**Returns:**
java.awt.Color - şekil rengi.

### setShapeColor(Color value) {#setShapeColor-java.awt.Color-}
```
public final void setShapeColor(Color value)
```


Şekil rengini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.awt.Color | Yeni şekil rengi. |
|

### getHighlightColor() {#getHighlightColor--}
```
public final Color getHighlightColor()
```


Vurgulama rengini alır.


**Returns:**
java.awt.Color - vurgulama rengi.

### setHighlightColor(Color value) {#setHighlightColor-java.awt.Color-}
```
public final void setHighlightColor(Color value)
```


Vurgulama rengini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.awt.Color | Yeni vurgulama rengi. |
|

### isBold() {#isBold--}
```
public final boolean isBold()
```


Metnin kalın olup olmayacağını gösteren bir bayrağı alır.


**Returns:**
boolean - metin kalın olacaksa true, aksi takdirde false.

### setBold(boolean value) {#setBold-boolean-}
```
public final void setBold(boolean value)
```


Metnin kalın olup olmayacağını gösteren bir bayrağı ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | boolean | Metin kalın olmalıysa true, aksi takdirde false. |
|

### isUnderline() {#isUnderline--}
```
public final boolean isUnderline()
```


Metnin altı çizili olup olmayacağını gösteren bir bayrağı alır.


**Returns:**
boolean - metin altı çizili olacaksa true, aksi takdirde false.

### setUnderline(boolean value) {#setUnderline-boolean-}
```
public final void setUnderline(boolean value)
```


Metnin altı çizili olup olmadığını gösteren bir bayrak ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | boolean | Metin altı çizili olmalıysa true, aksi takdirde false. |
|

### isItalic() {#isItalic--}
```
public final boolean isItalic()
```


Metnin italik olup olmayacağını gösteren bir bayrağı alır.


**Returns:**
boolean - metin italik olacaksa true, aksi takdirde false.

### setItalic(boolean value) {#setItalic-boolean-}
```
public final void setItalic(boolean value)
```


Metnin italik olup olmadığını gösteren bir bayrak ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | boolean | true ise metin italik olmalı, false aksi takdirde. |
|

### isStrikethrough() {#isStrikethrough--}
```
public final boolean isStrikethrough()
```


Metnin üstü çizili olup olmayacağını gösteren bir bayrağı alır.


**Returns:**
boolean - true ise metin üstü çizili olacak, false aksi takdirde.

### setStrikethrough(boolean value) {#setStrikethrough-boolean-}
```
public final void setStrikethrough(boolean value)
```


Metnin üstü çizili olup olmadığını gösteren bir bayrak ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | boolean | true ise metin üstü çizili olmalı, false aksi takdirde. |
|

### getStartStringSeparator() {#getStartStringSeparator--}
```
public final String getStartStringSeparator()
```


Başlangıç dize ayıracısını alır.


**Returns:**
java.lang.String - başlangıç dize ayırıcı.

### setStartStringSeparator(String value) {#setStartStringSeparator-java.lang.String-}
```
public final void setStartStringSeparator(String value)
```


Başlangıç dize ayıracısını ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.lang.String | Yeni başlangıç dize ayırıcı. |
|

### getEndStringSeparator() {#getEndStringSeparator--}
```
public final String getEndStringSeparator()
```


Bitiş dize ayıracısını alır.


**Returns:**
java.lang.String - bitiş dize ayırıcı.

### setEndStringSeparator(String value) {#setEndStringSeparator-java.lang.String-}
```
public final void setEndStringSeparator(String value)
```


Bitiş dize ayıracısını ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.lang.String | Yeni bitiş dize ayırıcı. |
|

### getOriginalSize() {#getOriginalSize--}
```
public final Size getOriginalSize()
```


Karşılaştırılan belgelerin orijinal boyutunu alır.


**Returns:**
[Size](../../com.groupdocs.comparison.options.style/size) - the original size of comparing documents.

### setOriginalSize(Size value) {#setOriginalSize-com.groupdocs.comparison.options.style.Size-}
```
public final void setOriginalSize(Size value)
```


Karşılaştırılan belgelerin orijinal boyutunu ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [Size](../../com.groupdocs.comparison.options.style/size) | Karşılaştırılan belgelerin yeni orijinal boyutu. |
|

### getWordsSeparators() {#getWordsSeparators--}
```
public final char[] getWordsSeparators()
```


Kelime ayırıcı karakterleri alır.


**Returns:**
char[] - kelime ayırıcıları.

### setWordsSeparators(char[] value) {#setWordsSeparators-char---}
```
public final void setWordsSeparators(char[] value)
```


Kelime ayırıcı karakterleri ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | char[] | Yeni kelime ayırıcıları. |
|

