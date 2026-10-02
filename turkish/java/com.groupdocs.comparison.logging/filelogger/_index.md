---
title: "FileLogger"
second_title: "GroupDocs.Comparison for Java API Referansı"
description: "Dosyaya günlük yazan logger."
type: docs
weight: 11
url: /tr/java/com.groupdocs.comparison.logging/filelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.foundation.logging.ILogger
```
public class FileLogger implements ILogger
```

Dosyaya günlük yazan logger.


[ComparisonLogger](../../com.groupdocs.comparison.logging/comparisonlogger) ile birlikte kullanılmalıdır.


Örnek kullanım:

````

 ComparisonLogger.setLogger(new FileLogger("/path/to/file.log.txt", false, true, true, true));
 
````


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [FileLogger(String filePath)](#FileLogger-java.lang.String-) | FileLogger sınıfının dosya yolu ile yeni bir örneğini başlatır. |
|
|  | [FileLogger(String filePath, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)](#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-) | FileLogger sınıfının dosya yolu ve günlük seviyeleri yapılandırması ile yeni bir örneğini başlatır. |
|
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [MESSAGE](#MESSAGE) |  |
| [EXCEPTION](#EXCEPTION) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | İzleme mesajını dosyaya yazar. |
|
|  | [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | İzleme mesajını dosyaya yazar. |
|
|  | [isTraceEnabled()](#isTraceEnabled--) | İzleme kaydı etkin olup olmadığını kontrol eder. |
|
|  | [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | Hata ayıklama mesajını dosyaya yazar. |
|
|  | [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Hata ayıklama mesajını dosyaya yazar. |
|
|  | [isDebugEnabled()](#isDebugEnabled--) | Hata ayıklama kaydı etkin olup olmadığını kontrol eder. |
|
|  | [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | Uyarı mesajını dosyaya yazar. |
|
|  | [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Uyarı mesajını dosyaya yazar. |
|
|  | [isWarningEnabled()](#isWarningEnabled--) | Uyarı kaydı etkin olup olmadığını kontrol eder. |
|
|  | [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | Hata mesajını dosyaya yazar. |
|
|  | [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Hata mesajını dosyaya yazar. |
|
|  | [isErrorEnabled()](#isErrorEnabled--) | Hata kaydı etkin olup olmadığını kontrol eder. |
|
### FileLogger(String filePath) {#FileLogger-java.lang.String-}
```
public FileLogger(String filePath)
```


FileLogger sınıfının dosya yolu ile yeni bir örneğini başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Günlüklerin yazılacağı dosyanın yolu |
|

### FileLogger(String filePath, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled) {#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-}
```
public FileLogger(String filePath, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)
```


FileLogger sınıfının dosya yolu ve günlük seviyeleri yapılandırması ile yeni bir örneğini başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Günlüklerin yazılacağı dosyanın yolu |
|
|  | isTraceEnabled | boolean | İzleme kaydını etkinleştirmek için true, aksi takdirde false |
|
|  | isDebugEnabled | boolean | Hata ayıklama kaydını etkinleştirmek için true, aksi takdirde false |
|
|  | isWarningEnabled | boolean | Uyarı kaydını etkinleştirmek için true, aksi takdirde false |
|
|  | isErrorEnabled | boolean | Hata kaydını etkinleştirmek için true, aksi takdirde false |
|

### MESSAGE {#MESSAGE}
```
public static final String MESSAGE
```


### EXCEPTION {#EXCEPTION}
```
public static final String EXCEPTION
```


### trace(String message, Object[] arguments) {#trace-java.lang.String-java.lang.Object...-}
```
public void trace(String message, Object[] arguments)
```


İzleme mesajını dosyaya yazar.


Trace günlük mesajları, uygulama akışı hakkında en ayrıntılı bilgileri sağlar.
Mesaj, bir veya birkaç {} içerebilir ve bunlar ilgili argümanlarla değiştirilecektir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | mesaj | java.lang.String | Mesaj. |
|
|  | argümanlar | java.lang.Object[] | Argümanlar, mesajdaki {} yer tutucularını geçiş sırasına göre değiştirir, null 'null' olarak yazılacaktır. |
|

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void trace(Throwable throwable, String message, Object[] arguments)
```


İzleme mesajını dosyaya yazar.


Trace günlük mesajları, uygulama akışı hakkında en ayrıntılı bilgileri sağlar.
Mesaj, bir veya birkaç {} içerebilir ve bunlar ilgili argümanlarla değiştirilecektir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Stacktrace almak için kullanılacak throwable nesnesi |
|
|  | mesaj | java.lang.String | Mesaj. |
|
|  | argümanlar | java.lang.Object[] | Argümanlar, mesajdaki {} yer tutucularını geçiş sırasına göre değiştirir, null 'null' olarak yazılacaktır. |
|

### isTraceEnabled() {#isTraceEnabled--}
```
public boolean isTraceEnabled()
```


İzleme kaydı etkin olup olmadığını kontrol eder.


**Returns:**
boolean - etkinse true, aksi takdirde false

### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public void debug(String message, Object[] arguments)
```


Hata ayıklama mesajını dosyaya yazar.


Debug günlük mesajları, uygulama akışındaki farklı süreçler hakkında bilgi sağlar.
Mesaj, bir veya birkaç {} içerebilir ve bunlar ilgili argümanlarla değiştirilecektir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | mesaj | java.lang.String | Mesaj. |
|
|  | argümanlar | java.lang.Object[] | Argümanlar, mesajdaki {} yer tutucularını geçiş sırasına göre değiştirir, null 'null' olarak yazılacaktır. |
|

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void debug(Throwable throwable, String message, Object[] arguments)
```


Hata ayıklama mesajını dosyaya yazar.


Debug günlük mesajları, uygulama akışındaki farklı süreçler hakkında bilgi sağlar.
Mesaj, bir veya birkaç {} içerebilir ve bunlar ilgili argümanlarla değiştirilecektir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Stacktrace almak için kullanılacak throwable nesnesi |
|
|  | mesaj | java.lang.String | Mesaj. |
|
|  | argümanlar | java.lang.Object[] | Argümanlar, mesajdaki {} yer tutucularını geçiş sırasına göre değiştirir, null 'null' olarak yazılacaktır. |
|

### isDebugEnabled() {#isDebugEnabled--}
```
public boolean isDebugEnabled()
```


Hata ayıklama kaydı etkin olup olmadığını kontrol eder.


**Returns:**
boolean - etkinse true, aksi takdirde false

### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public void warning(String message, Object[] arguments)
```


Uyarı mesajını dosyaya yazar.


Uyarı günlük mesajları, uygulama akışındaki beklenmeyen ve kurtarılabilir olaylar hakkında bilgi sağlar.
Mesaj, bir veya birkaç {} içerebilir ve bunlar ilgili argümanlarla değiştirilecektir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | mesaj | java.lang.String | Mesaj. |
|
|  | argümanlar | java.lang.Object[] | Argümanlar, mesajdaki {} yer tutucularını geçiş sırasına göre değiştirir, null 'null' olarak yazılacaktır. |
|

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void warning(Throwable throwable, String message, Object[] arguments)
```


Uyarı mesajını dosyaya yazar.


Uyarı günlük mesajları, uygulama akışındaki beklenmeyen ve kurtarılabilir olaylar hakkında bilgi sağlar.
Mesaj, bir veya birkaç {} içerebilir ve bunlar ilgili argümanlarla değiştirilecektir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Stacktrace almak için kullanılacak throwable nesnesi |
|
|  | mesaj | java.lang.String | Mesaj. |
|
|  | argümanlar | java.lang.Object[] | Argümanlar, mesajdaki {} yer tutucularını geçiş sırasına göre değiştirir, null 'null' olarak yazılacaktır. |
|

### isWarningEnabled() {#isWarningEnabled--}
```
public boolean isWarningEnabled()
```


Uyarı kaydı etkin olup olmadığını kontrol eder.


**Returns:**
boolean - etkinse true, aksi takdirde false

### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public void error(String message, Object[] arguments)
```


Hata mesajını dosyaya yazar.


Hata günlük mesajları, uygulama akışındaki kurtarılamaz olaylar hakkında bilgi sağlar.
Mesaj, bir veya birkaç {} içerebilir ve bunlar ilgili argümanlarla değiştirilecektir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | mesaj | java.lang.String | Mesaj. |
|
|  | argümanlar | java.lang.Object[] | Argümanlar, mesajdaki {} yer tutucularını geçiş sırasına göre değiştirir, null 'null' olarak yazılacaktır. |
|

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void error(Throwable throwable, String message, Object[] arguments)
```


Hata mesajını dosyaya yazar.


Hata günlük mesajları, uygulama akışındaki kurtarılamaz olaylar hakkında bilgi sağlar.
Mesaj, bir veya birkaç {} içerebilir ve bunlar ilgili argümanlarla değiştirilecektir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Stacktrace almak için kullanılacak throwable nesnesi |
|
|  | mesaj | java.lang.String | Mesaj. |
|
|  | argümanlar | java.lang.Object[] | Argümanlar, mesajdaki {} yer tutucularını geçiş sırasına göre değiştirir, null 'null' olarak yazılacaktır. |
|

### isErrorEnabled() {#isErrorEnabled--}
```
public boolean isErrorEnabled()
```


Hata kaydı etkin olup olmadığını kontrol eder.


**Returns:**
boolean - etkinse true, aksi takdirde false

