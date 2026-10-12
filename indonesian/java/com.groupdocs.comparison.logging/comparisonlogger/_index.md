---
title: "ComparisonLogger"
second_title: "Referensi API GroupDocs.Comparison untuk Java"
description: "Mengimplementasikan metode pencatatan dan cara untuk mengkonfigurasi logger terintegrasi atau menetapkan logger yang didefinisikan pengguna."
type: docs
weight: 10
url: /id/java/com.groupdocs.comparison.logging/comparisonlogger/
---
**Inheritance:**
java.lang.Object
```
public class ComparisonLogger
```

Mengimplementasikan metode pencatatan dan cara untuk mengkonfigurasi logger terintegrasi atau menetapkan logger yang didefinisikan pengguna.


Kelas ini memungkinkan pengaturan logger terintegrasi atau kustom dan menulis pesan log.


Contoh penggunaan:

````

 ComparisonLogger.setLogger(new com.groupdocs.comparison.logging.ConsoleLogger(false, true, true, true));
 ComparisonLogger.warning(exceptionObject, "Warning message with parameters: {}, {}", "parameter1", 2);
 
````


## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | Menulis pesan jejak ke logger yang telah dikonfigurasi sebelumnya. |
|
|  | [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Menulis pesan jejak, jejak tumpukan, dan pesan dari pengecualian ke logger yang telah dikonfigurasi sebelumnya. |
|
|  | [isTraceEnabled()](#isTraceEnabled--) | Memeriksa apakah pencatatan jejak diaktifkan dalam logger yang telah dikonfigurasi sebelumnya. |
|
|  | [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | Menulis pesan debug ke logger yang telah dikonfigurasi sebelumnya. |
|
|  | [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Menulis pesan debug, jejak tumpukan, dan pesan dari pengecualian ke logger yang telah dikonfigurasi sebelumnya. |
|
|  | [isDebugEnabled()](#isDebugEnabled--) | Memeriksa apakah pencatatan debug diaktifkan dalam logger yang telah dikonfigurasi sebelumnya. |
|
|  | [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | Menulis pesan peringatan ke logger yang telah dikonfigurasi sebelumnya. |
|
|  | [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Menulis pesan peringatan, jejak tumpukan, dan pesan dari pengecualian ke logger yang telah dikonfigurasi sebelumnya. |
|
|  | [isWarningEnabled()](#isWarningEnabled--) | Memeriksa apakah pencatatan peringatan diaktifkan dalam logger yang telah dikonfigurasi sebelumnya. |
|
|  | [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | Menulis pesan error ke logger yang telah dikonfigurasi sebelumnya. |
|
|  | [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Menulis pesan error, jejak tumpukan, dan pesan dari pengecualian ke logger yang telah dikonfigurasi sebelumnya. |
|
|  | [isErrorEnabled()](#isErrorEnabled--) | Memeriksa apakah pencatatan error diaktifkan dalam logger yang telah dikonfigurasi sebelumnya. |
|
|  | [getLogger()](#getLogger--) | Mengambil logger yang telah dikonfigurasi sebelumnya yang akan digunakan untuk menulis semua jenis log. |
|
|  | [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | Mengatur logger yang akan digunakan untuk menulis semua jenis log. |
|
### trace(String message, Object[] arguments) {#trace-java.lang.String-java.lang.Object...-}
```
public static void trace(String message, Object[] arguments)
```


Menulis pesan jejak ke logger yang telah dikonfigurasi sebelumnya.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | message | java.lang.String | Pesan, jika null perilakunya tergantung pada logger |
|
|  | arguments | java.lang.Object[] | Argumen yang akan disisipkan ke dalam pesan, jika null perilakunya tergantung pada logger |
|

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void trace(Throwable throwable, String message, Object[] arguments)
```


Menulis pesan jejak, jejak tumpukan, dan pesan dari pengecualian ke logger yang telah dikonfigurasi sebelumnya.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Objek throwable yang akan digunakan untuk mendapatkan jejak tumpukan, jika null perilakunya tergantung pada logger |
|
|  | message | java.lang.String | Pesan, jika null perilakunya tergantung pada logger |
|
|  | arguments | java.lang.Object[] | Argumen yang akan disisipkan ke dalam pesan, jika null perilakunya tergantung pada logger |
|

### isTraceEnabled() {#isTraceEnabled--}
```
public static boolean isTraceEnabled()
```


Memeriksa apakah pencatatan jejak diaktifkan dalam logger yang telah dikonfigurasi sebelumnya.


**Returns:**
boolean - true jika diaktifkan dalam logger yang telah dikonfigurasi sebelumnya, jika tidak false

### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public static void debug(String message, Object[] arguments)
```


Menulis pesan debug ke logger yang telah dikonfigurasi sebelumnya.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | message | java.lang.String | Pesan, jika null perilakunya tergantung pada logger |
|
|  | arguments | java.lang.Object[] | Argumen yang akan disisipkan ke dalam pesan, jika null perilakunya tergantung pada logger |
|

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void debug(Throwable throwable, String message, Object[] arguments)
```


Menulis pesan debug, jejak tumpukan, dan pesan dari pengecualian ke logger yang telah dikonfigurasi sebelumnya.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Objek throwable yang akan digunakan untuk mendapatkan jejak tumpukan, jika null perilakunya tergantung pada logger |
|
|  | message | java.lang.String | Pesan, jika null perilakunya tergantung pada logger |
|
|  | arguments | java.lang.Object[] | Argumen yang akan disisipkan ke dalam pesan, jika null perilakunya tergantung pada logger |
|

### isDebugEnabled() {#isDebugEnabled--}
```
public static boolean isDebugEnabled()
```


Memeriksa apakah pencatatan debug diaktifkan dalam logger yang telah dikonfigurasi sebelumnya.


**Returns:**
boolean - true jika diaktifkan dalam logger yang telah dikonfigurasi sebelumnya, jika tidak false

### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public static void warning(String message, Object[] arguments)
```


Menulis pesan peringatan ke logger yang telah dikonfigurasi sebelumnya.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | message | java.lang.String | Pesan, jika null perilakunya tergantung pada logger |
|
|  | arguments | java.lang.Object[] | Argumen yang akan disisipkan ke dalam pesan, jika null perilakunya tergantung pada logger |
|

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void warning(Throwable throwable, String message, Object[] arguments)
```


Menulis pesan peringatan, jejak tumpukan, dan pesan dari pengecualian ke logger yang telah dikonfigurasi sebelumnya.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Objek throwable yang akan digunakan untuk mendapatkan jejak tumpukan, jika null perilakunya tergantung pada logger |
|
|  | message | java.lang.String | Pesan, jika null perilakunya tergantung pada logger |
|
|  | arguments | java.lang.Object[] | Argumen yang akan disisipkan ke dalam pesan, jika null perilakunya tergantung pada logger |
|

### isWarningEnabled() {#isWarningEnabled--}
```
public static boolean isWarningEnabled()
```


Memeriksa apakah pencatatan peringatan diaktifkan dalam logger yang telah dikonfigurasi sebelumnya.


**Returns:**
boolean - true jika diaktifkan dalam logger yang telah dikonfigurasi sebelumnya, jika tidak false

### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public static void error(String message, Object[] arguments)
```


Menulis pesan error ke logger yang telah dikonfigurasi sebelumnya.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | message | java.lang.String | Pesan, jika null perilakunya tergantung pada logger |
|
|  | arguments | java.lang.Object[] | Argumen yang akan disisipkan ke dalam pesan, jika null perilakunya tergantung pada logger |
|

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void error(Throwable throwable, String message, Object[] arguments)
```


Menulis pesan error, jejak tumpukan, dan pesan dari pengecualian ke logger yang telah dikonfigurasi sebelumnya.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Objek throwable yang akan digunakan untuk mendapatkan jejak tumpukan, jika null perilakunya tergantung pada logger |
|
|  | message | java.lang.String | Pesan, jika null perilakunya tergantung pada logger |
|
|  | arguments | java.lang.Object[] | Argumen yang akan disisipkan ke dalam pesan, jika null perilakunya tergantung pada logger |
|

### isErrorEnabled() {#isErrorEnabled--}
```
public static boolean isErrorEnabled()
```


Memeriksa apakah pencatatan error diaktifkan dalam logger yang telah dikonfigurasi sebelumnya.


**Returns:**
boolean - true jika diaktifkan dalam logger yang telah dikonfigurasi sebelumnya, jika tidak false

### getLogger() {#getLogger--}
```
public static synchronized ILogger getLogger()
```


Mengambil logger yang telah dikonfigurasi sebelumnya yang akan digunakan untuk menulis semua jenis log.


**Returns:**
com.groupdocs.foundation.logging.ILogger - logger

### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public static synchronized void setLogger(ILogger logger)
```


Mengatur logger yang akan digunakan untuk menulis semua jenis log.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | logger | com.groupdocs.foundation.logging.ILogger | Logger |
|

