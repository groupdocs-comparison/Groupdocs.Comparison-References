---
title: "ComparisonLogger"
second_title: "GroupDocs.Comparison for Java API Referansı"
description: "Günlükleme yöntemlerini uygular ve bütünleşik ya da kullanıcı tanımlı logger'ı yapılandırmanın bir yolunu sağlar."
type: docs
weight: 10
url: /tr/java/com.groupdocs.comparison.logging/comparisonlogger/
---
**Inheritance:**
java.lang.Object
```
public class ComparisonLogger
```

Günlükleme yöntemlerini uygular ve bütünleşik ya da kullanıcı tanımlı logger'ı yapılandırmanın bir yolunu sağlar.


Bu sınıf, entegre veya özel bir logger ayarlamayı ve günlük mesajları yazmayı sağlar.


Örnek kullanım:

````

 ComparisonLogger.setLogger(new com.groupdocs.comparison.logging.ConsoleLogger(false, true, true, true));
 ComparisonLogger.warning(exceptionObject, "Warning message with parameters: {}, {}", "parameter1", 2);
 
````


## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | Trace mesajını önceden yapılandırılmış logger'a yazar. |
|
|  | [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Trace mesajını, stacktrace'i ve bir istisnanın mesajını önceden yapılandırılmış logger'a yazar. |
|
|  | [isTraceEnabled()](#isTraceEnabled--) | Önceden yapılandırılmış logger'da trace kaydı etkin olup olmadığını kontrol eder. |
|
|  | [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | Debug mesajını önceden yapılandırılmış logger'a yazar. |
|
|  | [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Debug mesajını, stacktrace'i ve bir istisnanın mesajını önceden yapılandırılmış logger'a yazar. |
|
|  | [isDebugEnabled()](#isDebugEnabled--) | Önceden yapılandırılmış logger'da debug kaydı etkin olup olmadığını kontrol eder. |
|
|  | [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | Uyarı mesajını önceden yapılandırılmış logger'a yazar. |
|
|  | [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Uyarı mesajını, stacktrace'i ve bir istisnanın mesajını önceden yapılandırılmış logger'a yazar. |
|
|  | [isWarningEnabled()](#isWarningEnabled--) | Önceden yapılandırılmış logger'da uyarı kaydı etkin olup olmadığını kontrol eder. |
|
|  | [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | Hata mesajını önceden yapılandırılmış logger'a yazar. |
|
|  | [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Hata mesajını, yığın izini ve bir istisnanın mesajını önceden yapılandırılmış logger'a yazar. |
|
|  | [isErrorEnabled()](#isErrorEnabled--) | Hata kaydının önceden yapılandırılmış logger'da etkin olup olmadığını kontrol eder. |
|
|  | [getLogger()](#getLogger--) | Tüm log türlerini yazmak için kullanılacak önceden yapılandırılmış logger'ı alır. |
|
|  | [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | Tüm log türlerini yazmak için kullanılacak logger'ı ayarlar. |
|
### trace(String message, Object[] arguments) {#trace-java.lang.String-java.lang.Object...-}
```
public static void trace(String message, Object[] arguments)
```


Trace mesajını önceden yapılandırılmış logger'a yazar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | mesaj | java.lang.String | Mesaj, null ise davranış logger'a bağlıdır |
|
|  | argümanlar | java.lang.Object[] | Mesaja yerleştirilecek argümanlar, null ise davranış logger'a bağlıdır |
|

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void trace(Throwable throwable, String message, Object[] arguments)
```


Trace mesajını, stacktrace'i ve bir istisnanın mesajını önceden yapılandırılmış logger'a yazar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Yığın izini almak için kullanılacak throwable nesnesi, null ise davranış logger'a bağlıdır |
|
|  | mesaj | java.lang.String | Mesaj, null ise davranış logger'a bağlıdır |
|
|  | argümanlar | java.lang.Object[] | Mesaja yerleştirilecek argümanlar, null ise davranış logger'a bağlıdır |
|

### isTraceEnabled() {#isTraceEnabled--}
```
public static boolean isTraceEnabled()
```


Önceden yapılandırılmış logger'da trace kaydı etkin olup olmadığını kontrol eder.


**Returns:**
boolean - önceden yapılandırılmış logger'da etkinse true, aksi takdirde false

### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public static void debug(String message, Object[] arguments)
```


Debug mesajını önceden yapılandırılmış logger'a yazar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | mesaj | java.lang.String | Mesaj, null ise davranış logger'a bağlıdır |
|
|  | argümanlar | java.lang.Object[] | Mesaja yerleştirilecek argümanlar, null ise davranış logger'a bağlıdır |
|

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void debug(Throwable throwable, String message, Object[] arguments)
```


Debug mesajını, stacktrace'i ve bir istisnanın mesajını önceden yapılandırılmış logger'a yazar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Yığın izini almak için kullanılacak throwable nesnesi, null ise davranış logger'a bağlıdır |
|
|  | mesaj | java.lang.String | Mesaj, null ise davranış logger'a bağlıdır |
|
|  | argümanlar | java.lang.Object[] | Mesaja yerleştirilecek argümanlar, null ise davranış logger'a bağlıdır |
|

### isDebugEnabled() {#isDebugEnabled--}
```
public static boolean isDebugEnabled()
```


Önceden yapılandırılmış logger'da debug kaydı etkin olup olmadığını kontrol eder.


**Returns:**
boolean - önceden yapılandırılmış logger'da etkinse true, aksi takdirde false

### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public static void warning(String message, Object[] arguments)
```


Uyarı mesajını önceden yapılandırılmış logger'a yazar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | mesaj | java.lang.String | Mesaj, null ise davranış logger'a bağlıdır |
|
|  | argümanlar | java.lang.Object[] | Mesaja yerleştirilecek argümanlar, null ise davranış logger'a bağlıdır |
|

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void warning(Throwable throwable, String message, Object[] arguments)
```


Uyarı mesajını, stacktrace'i ve bir istisnanın mesajını önceden yapılandırılmış logger'a yazar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Yığın izini almak için kullanılacak throwable nesnesi, null ise davranış logger'a bağlıdır |
|
|  | mesaj | java.lang.String | Mesaj, null ise davranış logger'a bağlıdır |
|
|  | argümanlar | java.lang.Object[] | Mesaja yerleştirilecek argümanlar, null ise davranış logger'a bağlıdır |
|

### isWarningEnabled() {#isWarningEnabled--}
```
public static boolean isWarningEnabled()
```


Önceden yapılandırılmış logger'da uyarı kaydı etkin olup olmadığını kontrol eder.


**Returns:**
boolean - önceden yapılandırılmış logger'da etkinse true, aksi takdirde false

### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public static void error(String message, Object[] arguments)
```


Hata mesajını önceden yapılandırılmış logger'a yazar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | mesaj | java.lang.String | Mesaj, null ise davranış logger'a bağlıdır |
|
|  | argümanlar | java.lang.Object[] | Mesaja yerleştirilecek argümanlar, null ise davranış logger'a bağlıdır |
|

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void error(Throwable throwable, String message, Object[] arguments)
```


Hata mesajını, yığın izini ve bir istisnanın mesajını önceden yapılandırılmış logger'a yazar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Yığın izini almak için kullanılacak throwable nesnesi, null ise davranış logger'a bağlıdır |
|
|  | mesaj | java.lang.String | Mesaj, null ise davranış logger'a bağlıdır |
|
|  | argümanlar | java.lang.Object[] | Mesaja yerleştirilecek argümanlar, null ise davranış logger'a bağlıdır |
|

### isErrorEnabled() {#isErrorEnabled--}
```
public static boolean isErrorEnabled()
```


Hata kaydının önceden yapılandırılmış logger'da etkin olup olmadığını kontrol eder.


**Returns:**
boolean - önceden yapılandırılmış logger'da etkinse true, aksi takdirde false

### getLogger() {#getLogger--}
```
public static synchronized ILogger getLogger()
```


Tüm log türlerini yazmak için kullanılacak önceden yapılandırılmış logger'ı alır.


**Returns:**
com.groupdocs.foundation.logging.ILogger - logger

### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public static synchronized void setLogger(ILogger logger)
```


Tüm log türlerini yazmak için kullanılacak logger'ı ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | logger | com.groupdocs.foundation.logging.ILogger | Logger |
|

