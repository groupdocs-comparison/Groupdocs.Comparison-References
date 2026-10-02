---
title: "LoadOptions"
second_title: "GroupDocs.Comparison for Java API Referansı"
description: "Bir belgeyi yüklerken ek seçenekler belirtmenizi sağlar."
type: docs
weight: 10
url: /tr/java/com.groupdocs.comparison.options.load/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

Bir belgeyi yüklerken ek seçenekler belirtmenizi sağlar.


Örnek kullanım:

````

 final LoadOptions loadOptions = new LoadOptions();
 loadOptions.setPassword("passw");
 loadOptions.setFileType(FileType.PDF);

 try (Comparer comparer = new Comparer(sourceFile, loadOptions)) {
    comparer.add(targetFile);

    comparer.compare(resultFile);
 }
 
````


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [LoadOptions()](#LoadOptions--) | LoadOptions sınıfının yeni bir örneğini başlatır. |
|
|  | [LoadOptions(boolean isLoadText)](#LoadOptions-boolean-) | LoadOptions sınıfının yeni bir örneğini, giriş dizesinin karşılaştırma metni olduğunu ve yol olmadığını belirten bir bayrakla başlatır. |
|
|  | [LoadOptions(String password)](#LoadOptions-java.lang.String-) | LoadOptions sınıfının yeni bir örneğini, belgeyi yüklemek için bir parola ile başlatır. |
|
|  | [LoadOptions(boolean isLoadText, String password)](#LoadOptions-boolean-java.lang.String-) | LoadOptions sınıfının yeni bir örneğini, giriş dizesinin karşılaştırma metni olduğunu belirten bir bayrak ve belgeyi yüklemek için bir parola ile başlatır. |
|
|  | [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.comparison.result.FileType-) | LoadOptions sınıfının yeni bir örneğini, bir dosya türü ile başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [isLoadText()](#isLoadText--) | Karşılaştırma metni olduğunu ve dosya yolu olmadığını gösteren bir bayrağı, [Comparer](../../com.groupdocs.comparison/comparer) yapıcısına veya [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) metoduna geçirilen dize için alır (Yalnızca Metin Karşılaştırması için). |
|
|  | [setLoadText(boolean value)](#setLoadText-boolean-) | Karşılaştırma metni olduğunu ve dosya yolu olmadığını gösteren bir bayrağı, [Comparer](../../com.groupdocs.comparison/comparer) yapıcısına veya [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) metoduna geçirilen dize için ayarlar (Yalnızca Metin Karşılaştırması için). |
|
|  | [getPassword()](#getPassword--) | Bir belgeyi yüklemek için kullanılacak bir parolayı alır. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Bir belgeyi yüklemek için kullanılacak bir parolayı ayarlar. |
|
|  | [getFontDirectories()](#getFontDirectories--) | Bir belgeyi yüklemek için kullanılan yazı tipi dosyalarının bulunduğu dizinlerin bir listesini alır. |
|
|  | [setFontDirectories(List<String> value)](#setFontDirectories-java.util.List-java.lang.String--) | Bir belgeyi yüklemek için kullanılan yazı tipi dosyalarının bulunduğu dizinlerin bir listesini ayarlar. |
|
|  | [getFileType()](#getFileType--) | Yüklenen dosyanın türünü alır. |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.comparison.result.FileType-) | Yüklenen dosyanın türünü ayarlar. |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


LoadOptions sınıfının yeni bir örneğini başlatır.


### LoadOptions(boolean isLoadText) {#LoadOptions-boolean-}
```
public LoadOptions(boolean isLoadText)
```


LoadOptions sınıfının yeni bir örneğini, giriş dizesinin karşılaştırma metni olduğunu ve yol olmadığını belirten bir bayrakla başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | isLoadText | boolean | Giriş dizesinin karşılaştırma metni olduğunu ve yol olmadığını belirten bayrak |
|

### LoadOptions(String password) {#LoadOptions-java.lang.String-}
```
public LoadOptions(String password)
```


LoadOptions sınıfının yeni bir örneğini, belgeyi yüklemek için bir parola ile başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | şifre | java.lang.String | Belgeyi yüklemek için parola |
|

### LoadOptions(boolean isLoadText, String password) {#LoadOptions-boolean-java.lang.String-}
```
public LoadOptions(boolean isLoadText, String password)
```


LoadOptions sınıfının yeni bir örneğini, giriş dizesinin karşılaştırma metni olduğunu belirten bir bayrak ve belgeyi yüklemek için bir parola ile başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | isLoadText | boolean | Giriş dizesinin karşılaştırma metni olduğunu ve yol olmadığını belirten bayrak |
|
|  | şifre | java.lang.String | Belgeyi yüklemek için parola |
|

### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.comparison.result.FileType-}
```
public LoadOptions(FileType fileType)
```


LoadOptions sınıfının yeni bir örneğini, bir dosya türü ile başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.comparison.result/filetype) | Dosyanın tipi |
|

### isLoadText() {#isLoadText--}
```
public boolean isLoadText()
```


Karşılaştırma metni olduğunu ve dosya yolu olmadığını gösteren bir bayrağı, [Comparer](../../com.groupdocs.comparison/comparer) yapıcısına veya [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) metoduna geçirilen dize için alır (Yalnızca Metin Karşılaştırması için).


**Returns:**
boolean - giriş dizesi karşılaştırma metni ise true, aksi takdirde false

### setLoadText(boolean value) {#setLoadText-boolean-}
```
public void setLoadText(boolean value)
```


Karşılaştırma metni olduğunu ve dosya yolu olmadığını gösteren bir bayrağı, [Comparer](../../com.groupdocs.comparison/comparer) yapıcısına veya [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) metoduna geçirilen dize için ayarlar (Yalnızca Metin Karşılaştırması için).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | boolean | giriş dizesi karşılaştırma metni ise true, aksi takdirde false |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Bir belgeyi yüklemek için kullanılacak bir parolayı alır.


**Returns:**
java.lang.String - belgeyi yüklemek için parola

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Bir belgeyi yüklemek için kullanılacak bir parolayı ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.lang.String | Belgeyi yüklemek için parola |
|

### getFontDirectories() {#getFontDirectories--}
```
public List<String> getFontDirectories()
```


Bir belgeyi yüklemek için kullanılan yazı tipi dosyalarının bulunduğu dizinlerin bir listesini alır.


**Returns:**
java.util.List<java.lang.String> - yazı tipi dosyaları içeren dizinlerin listesi

### setFontDirectories(List<String> value) {#setFontDirectories-java.util.List-java.lang.String--}
```
public void setFontDirectories(List<String> value)
```


Bir belgeyi yüklemek için kullanılan yazı tipi dosyalarının bulunduğu dizinlerin bir listesini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.util.List<java.lang.String> | Yazı tipi dosyaları içeren dizinlerin listesi |
|

### getFileType() {#getFileType--}
```
public FileType getFileType()
```


Yüklenen dosyanın türünü alır.


**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the type of the file

### setFileType(FileType value) {#setFileType-com.groupdocs.comparison.result.FileType-}
```
public void setFileType(FileType value)
```


Yüklenen dosyanın türünü ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [FileType](../../com.groupdocs.comparison.result/filetype) | Dosyanın tipi |
|

