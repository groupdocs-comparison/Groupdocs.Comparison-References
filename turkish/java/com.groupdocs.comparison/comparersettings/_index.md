---
title: "ComparerSettings"
second_title: "GroupDocs.Comparison for Java API Referansı"
description: "Sınıfın davranışını özelleştirmek için ayarları tanımlar."
type: docs
weight: 11
url: /tr/java/com.groupdocs.comparison/comparersettings/
---
**Inheritance:**
java.lang.Object
```
public class ComparerSettings
```

Sınıfın davranışını özelleştirmek için [Comparer](../../com.groupdocs.comparison/comparer) sınıfının ayarlarını tanımlar.


Örnek kullanım:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     final ComparerSettings comparerSettings = new ComparerSettings();
     comparerSettings.setLogger(new ConsoleLogger(false, false, true, true));

     comparer.compare(resultFile, comparerSettings);
 }
 
````


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [ComparerSettings()](#ComparerSettings--) | ComparerSettings sınıfının yeni bir örneğini oluşturur. |
|
|  | [ComparerSettings(ILogger logger)](#ComparerSettings-com.groupdocs.foundation.logging.ILogger-) | ComparerSettings sınıfının yeni bir örneğini oluşturur. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getLogger()](#getLogger--) | Günlükleme için kullanılan logger uygulamasını alır. |
|
|  | [setLogger(ILogger value)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | Günlükleme için logger uygulamasını ayarlar. |
|
### ComparerSettings() {#ComparerSettings--}
```
public ComparerSettings()
```


ComparerSettings sınıfının yeni bir örneğini oluşturur.


### ComparerSettings(ILogger logger) {#ComparerSettings-com.groupdocs.foundation.logging.ILogger-}
```
public ComparerSettings(ILogger logger)
```


ComparerSettings sınıfının yeni bir örneğini oluşturur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | logger | com.groupdocs.foundation.logging.ILogger | kullanılacak logger |
|

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


Günlükleme için kullanılan logger uygulamasını alır.


**Returns:**
com.groupdocs.foundation.logging.ILogger - logger

### setLogger(ILogger value) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public final void setLogger(ILogger value)
```


Günlükleme için logger uygulamasını ayarlar.


Günlüklemeyi devre dışı bırakmak için com.groupdocs.foundation.logging.NullLogger#NULL_LOGGER.NULL_LOGGER kullanın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | com.groupdocs.foundation.logging.ILogger | ayar yapılacak logger uygulaması |
|

