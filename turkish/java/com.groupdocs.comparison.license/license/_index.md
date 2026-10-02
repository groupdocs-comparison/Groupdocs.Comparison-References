---
title: "Lisans"
second_title: "GroupDocs.Comparison for Java API Referansı"
description: "License sınıfı, GroupDocs.Comparison için lisansları ayarlama ve uygulama yöntemleri sağlar."
type: docs
weight: 10
url: /tr/java/com.groupdocs.comparison.license/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

License sınıfı, GroupDocs.Comparison için lisansları ayarlama ve uygulama yöntemleri sağlar.


Uygulanan lisansa göre kütüphanenin belirli özelliklerini etkinleştirmenize veya devre dışı bırakmanıza olanak tanır.

* More about GroupDocs.Comparison licensing: [Evaluation Limitations and Licensing](../https://docs.groupdocs.com/display/comparisonjava/Evaluation+Limitations+and+Licensing+of+GroupDocs.Comparison)


Örnek kullanım:

````

 final License license = new License();
 license.setLicense("GroupDocs.License.lic");
 
````


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [License()](#License--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [isValidLicense()](#isValidLicense--) | Lisansın ayarlanıp ayarlanmadığını gösteren bir değeri alır. |
|
|  | [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | Giriş akışı kullanarak Comparison için bir lisans ayarlar. |
|
|  | [setLicense(Path licensePath)](#setLicense-java.nio.file.Path-) | Lisans dosyası yolu kullanarak Comparison için bir lisans ayarlar. |
|
|  | [setLicense(String licensePath)](#setLicense-java.lang.String-) | Lisans dosyası yolu kullanarak Comparison için bir lisans ayarlar. |
|
### License() {#License--}
```
public License()
```


### isValidLicense() {#isValidLicense--}
```
public static boolean isValidLicense()
```


Lisansın ayarlanıp ayarlanmadığını gösteren bir değeri alır.


**Returns:**
boolean - lisans başarılı bir şekilde ayarlandıysa true, aksi takdirde false

### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


Giriş akışı kullanarak Comparison için bir lisans ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | licenseStream | java.io.InputStream | Lisans akışı, null lisansı kaldırır |
|

### setLicense(Path licensePath) {#setLicense-java.nio.file.Path-}
```
public final void setLicense(Path licensePath)
```


Lisans dosyası yolu kullanarak Comparison için bir lisans ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | licensePath | java.nio.file.Path | Lisans dosya yolu |
|

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


Lisans dosyası yolu kullanarak Comparison için bir lisans ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | licensePath | java.lang.String | Lisans dosya yolu |
|

