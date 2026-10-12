---
title: "ComparerSettings"
second_title: "Referensi API GroupDocs.Comparison untuk Java"
description: "Mendefinisikan pengaturan untuk menyesuaikan perilaku kelas."
type: docs
weight: 11
url: /id/java/com.groupdocs.comparison/comparersettings/
---
**Inheritance:**
java.lang.Object
```
public class ComparerSettings
```

Mendefinisikan pengaturan untuk menyesuaikan perilaku kelas [Comparer](../../com.groupdocs.comparison/comparer).


Contoh penggunaan:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     final ComparerSettings comparerSettings = new ComparerSettings();
     comparerSettings.setLogger(new ConsoleLogger(false, false, true, true));

     comparer.compare(resultFile, comparerSettings);
 }
 
````


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [ComparerSettings()](#ComparerSettings--) | Membuat instance baru dari kelas ComparerSettings. |
|
|  | [ComparerSettings(ILogger logger)](#ComparerSettings-com.groupdocs.foundation.logging.ILogger-) | Membuat instance baru dari kelas ComparerSettings. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getLogger()](#getLogger--) | Mendapatkan implementasi logger yang digunakan untuk pencatatan. |
|
|  | [setLogger(ILogger value)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | Mengatur implementasi logger untuk pencatatan. |
|
### ComparerSettings() {#ComparerSettings--}
```
public ComparerSettings()
```


Membuat instance baru dari kelas ComparerSettings.


### ComparerSettings(ILogger logger) {#ComparerSettings-com.groupdocs.foundation.logging.ILogger-}
```
public ComparerSettings(ILogger logger)
```


Membuat instance baru dari kelas ComparerSettings.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | logger | com.groupdocs.foundation.logging.ILogger | logger yang akan digunakan |
|

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


Mendapatkan implementasi logger yang digunakan untuk pencatatan.


**Returns:**
com.groupdocs.foundation.logging.ILogger - logger

### setLogger(ILogger value) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public final void setLogger(ILogger value)
```


Mengatur implementasi logger untuk pencatatan.


Gunakan com.groupdocs.foundation.logging.NullLogger#NULL_LOGGER.NULL_LOGGER untuk menonaktifkan pencatatan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | com.groupdocs.foundation.logging.ILogger | implementasi logger yang akan diatur |
|

