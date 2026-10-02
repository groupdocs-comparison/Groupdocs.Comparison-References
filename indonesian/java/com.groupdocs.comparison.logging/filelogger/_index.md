---
title: "FileLogger"
second_title: "Referensi API GroupDocs.Comparison untuk Java"
description: "Logger yang menulis log ke file."
type: docs
weight: 11
url: /id/java/com.groupdocs.comparison.logging/filelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.foundation.logging.ILogger
```
public class FileLogger implements ILogger
```

Logger yang menulis log ke file.


Harus digunakan bersama dengan [ComparisonLogger](../../com.groupdocs.comparison.logging/comparisonlogger).


Contoh penggunaan:

````

 ComparisonLogger.setLogger(new FileLogger("/path/to/file.log.txt", false, true, true, true));
 
````


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [FileLogger(String filePath)](#FileLogger-java.lang.String-) | Menginisialisasi sebuah instance baru dari kelas FileLogger dengan jalur file. |
|
|  | [FileLogger(String filePath, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)](#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-) | Menginisialisasi sebuah instance baru dari kelas FileLogger dengan jalur file dan konfigurasi tingkat log. |
|
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [MESSAGE](#MESSAGE) |  |
| [EXCEPTION](#EXCEPTION) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | Menulis pesan jejak ke file. |
|
|  | [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Menulis pesan jejak ke file. |
|
|  | [isTraceEnabled()](#isTraceEnabled--) | Memeriksa apakah pencatatan jejak diaktifkan. |
|
|  | [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | Menulis pesan debug ke file. |
|
|  | [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Menulis pesan debug ke file. |
|
|  | [isDebugEnabled()](#isDebugEnabled--) | Memeriksa apakah pencatatan debug diaktifkan. |
|
|  | [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | Menulis pesan peringatan ke file. |
|
|  | [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Menulis pesan peringatan ke file. |
|
|  | [isWarningEnabled()](#isWarningEnabled--) | Memeriksa apakah pencatatan peringatan diaktifkan. |
|
|  | [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | Menulis pesan kesalahan ke file. |
|
|  | [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Menulis pesan kesalahan ke file. |
|
|  | [isErrorEnabled()](#isErrorEnabled--) | Memeriksa apakah pencatatan error diaktifkan. |
|
### FileLogger(String filePath) {#FileLogger-java.lang.String-}
```
public FileLogger(String filePath)
```


Menginisialisasi sebuah instance baru dari kelas FileLogger dengan jalur file.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.lang.String | Jalur ke file yang akan digunakan untuk menulis log |
|

### FileLogger(String filePath, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled) {#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-}
```
public FileLogger(String filePath, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)
```


Menginisialisasi sebuah instance baru dari kelas FileLogger dengan jalur file dan konfigurasi tingkat log.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.lang.String | Jalur ke file yang akan digunakan untuk menulis log |
|
|  | isTraceEnabled | boolean | True untuk mengaktifkan pencatatan jejak, false jika tidak |
|
|  | isDebugEnabled | boolean | True untuk mengaktifkan pencatatan debug, false jika tidak |
|
|  | isWarningEnabled | boolean | True untuk mengaktifkan pencatatan peringatan, false jika tidak |
|
|  | isErrorEnabled | boolean | True untuk mengaktifkan pencatatan error, false jika tidak |
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


Menulis pesan jejak ke file.


Pesan log jejak menyediakan informasi terperinci maksimal tentang alur aplikasi.
Pesan dapat berisi satu atau beberapa {} yang akan diganti dengan argumen yang sesuai.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | message | java.lang.String | Pesan. |
|
|  | arguments | java.lang.Object[] | Argumen, menggantikan {} dalam pesan sesuai urutan penerusan, null akan ditulis sebagai 'null' |
|

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void trace(Throwable throwable, String message, Object[] arguments)
```


Menulis pesan jejak ke file.


Pesan log jejak menyediakan informasi terperinci maksimal tentang alur aplikasi.
Pesan dapat berisi satu atau beberapa {} yang akan diganti dengan argumen yang sesuai.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Objek throwable yang akan digunakan untuk mendapatkan stacktrace |
|
|  | message | java.lang.String | Pesan. |
|
|  | arguments | java.lang.Object[] | Argumen, menggantikan {} dalam pesan sesuai urutan penerusan, null akan ditulis sebagai 'null' |
|

### isTraceEnabled() {#isTraceEnabled--}
```
public boolean isTraceEnabled()
```


Memeriksa apakah pencatatan jejak diaktifkan.


**Returns:**
boolean - true jika diaktifkan, false jika tidak

### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public void debug(String message, Object[] arguments)
```


Menulis pesan debug ke file.


Pesan log debug menyediakan informasi tentang proses berbeda dalam alur aplikasi.
Pesan dapat berisi satu atau beberapa {} yang akan diganti dengan argumen yang sesuai.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | message | java.lang.String | Pesan. |
|
|  | arguments | java.lang.Object[] | Argumen, menggantikan {} dalam pesan sesuai urutan penerusan, null akan ditulis sebagai 'null' |
|

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void debug(Throwable throwable, String message, Object[] arguments)
```


Menulis pesan debug ke file.


Pesan log debug menyediakan informasi tentang proses berbeda dalam alur aplikasi.
Pesan dapat berisi satu atau beberapa {} yang akan diganti dengan argumen yang sesuai.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Objek throwable yang akan digunakan untuk mendapatkan stacktrace |
|
|  | message | java.lang.String | Pesan. |
|
|  | arguments | java.lang.Object[] | Argumen, menggantikan {} dalam pesan sesuai urutan penerusan, null akan ditulis sebagai 'null' |
|

### isDebugEnabled() {#isDebugEnabled--}
```
public boolean isDebugEnabled()
```


Memeriksa apakah pencatatan debug diaktifkan.


**Returns:**
boolean - true jika diaktifkan, false jika tidak

### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public void warning(String message, Object[] arguments)
```


Menulis pesan peringatan ke file.


Pesan log peringatan menyediakan informasi tentang kejadian tak terduga dan dapat dipulihkan dalam alur aplikasi.
Pesan dapat berisi satu atau beberapa {} yang akan diganti dengan argumen yang sesuai.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | message | java.lang.String | Pesan. |
|
|  | arguments | java.lang.Object[] | Argumen, menggantikan {} dalam pesan sesuai urutan penerusan, null akan ditulis sebagai 'null' |
|

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void warning(Throwable throwable, String message, Object[] arguments)
```


Menulis pesan peringatan ke file.


Pesan log peringatan menyediakan informasi tentang kejadian tak terduga dan dapat dipulihkan dalam alur aplikasi.
Pesan dapat berisi satu atau beberapa {} yang akan diganti dengan argumen yang sesuai.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Objek throwable yang akan digunakan untuk mendapatkan stacktrace |
|
|  | message | java.lang.String | Pesan. |
|
|  | arguments | java.lang.Object[] | Argumen, menggantikan {} dalam pesan sesuai urutan penerusan, null akan ditulis sebagai 'null' |
|

### isWarningEnabled() {#isWarningEnabled--}
```
public boolean isWarningEnabled()
```


Memeriksa apakah pencatatan peringatan diaktifkan.


**Returns:**
boolean - true jika diaktifkan, false jika tidak

### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public void error(String message, Object[] arguments)
```


Menulis pesan kesalahan ke file.


Pesan log error menyediakan informasi tentang kejadian yang tidak dapat dipulihkan dalam alur aplikasi.
Pesan dapat berisi satu atau beberapa {} yang akan diganti dengan argumen yang sesuai.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | message | java.lang.String | Pesan. |
|
|  | arguments | java.lang.Object[] | Argumen, menggantikan {} dalam pesan sesuai urutan penerusan, null akan ditulis sebagai 'null' |
|

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void error(Throwable throwable, String message, Object[] arguments)
```


Menulis pesan kesalahan ke file.


Pesan log error menyediakan informasi tentang kejadian yang tidak dapat dipulihkan dalam alur aplikasi.
Pesan dapat berisi satu atau beberapa {} yang akan diganti dengan argumen yang sesuai.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Objek throwable yang akan digunakan untuk mendapatkan stacktrace |
|
|  | message | java.lang.String | Pesan. |
|
|  | arguments | java.lang.Object[] | Argumen, menggantikan {} dalam pesan sesuai urutan penerusan, null akan ditulis sebagai 'null' |
|

### isErrorEnabled() {#isErrorEnabled--}
```
public boolean isErrorEnabled()
```


Memeriksa apakah pencatatan error diaktifkan.


**Returns:**
boolean - true jika diaktifkan, false jika tidak

