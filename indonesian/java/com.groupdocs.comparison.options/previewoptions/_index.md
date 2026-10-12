---
title: "PreviewOptions"
second_title: "Referensi API GroupDocs.Comparison untuk Java"
description: "Menyediakan opsi untuk menghasilkan pratinjau dokumen dalam proses perbandingan."
type: docs
weight: 15
url: /id/java/com.groupdocs.comparison.options/previewoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewOptions
```

Menyediakan opsi untuk menghasilkan pratinjau dokumen dalam proses perbandingan.


Contoh penggunaan:

````

 try (Comparer comparer = new Comparer(sourceFile)) {

    PreviewOptions previewOptions = new PreviewOptions(
            pageNumber -> Files.newOutputStream(Paths.get(String.format("preview-page_%d.png", pageNumber)))
    );
    previewOptions.setPreviewFormat(PreviewFormats.PNG);
    previewOptions.setPageNumbers(new int[]{1, 2});

    comparer.getSource().generatePreview(previewOptions);
 }
 
````


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [PreviewOptions(Delegates.CreatePageStream createPageStream)](#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-) | Menginisialisasi instance baru dari kelas PreviewOptions dengan menentukan fungsi Delegates.CreatePageStream. |
|
|  | [PreviewOptions(CreatePageStreamFunction createPageStream)](#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-) | Menginisialisasi instance baru dari kelas PreviewOptions dengan menentukan fungsi [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction). |
|
|  | [PreviewOptions(Delegates.CreatePageStream createPageStream, Delegates.ReleasePageStream releasePageStream)](#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-) | Menginisialisasi instance baru dari kelas PreviewOptions dengan menentukan fungsi Delegates.CreatePageStream dan Delegates.ReleasePageStream. |
|
|  | [PreviewOptions(CreatePageStreamFunction createPageStream, ReleasePageStreamFunction releasePageStream)](#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-) | Menginisialisasi instance baru dari kelas PreviewOptions dengan menentukan fungsi [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) dan [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction). |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getCreatePageStream()](#getCreatePageStream--) | Mendapatkan fungsi untuk membuat aliran pratinjau halaman output. |
|
|  | [setCreatePageStream(Delegates.CreatePageStream createPageStream)](#setCreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-) | Mengatur fungsi untuk membuat aliran pratinjau halaman output. |
|
|  | [setCreatePageStream(CreatePageStreamFunction createPageStream)](#setCreatePageStream-com.groupdocs.comparison.common.function.CreatePageStreamFunction-) | Mengatur fungsi untuk membuat aliran pratinjau halaman output. |
|
|  | [getReleasePageStream()](#getReleasePageStream--) | Mendapatkan fungsi untuk melepaskan aliran pratinjau halaman output. |
|
|  | [setReleasePageStream(Delegates.ReleasePageStream releasePageStream)](#setReleasePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-) | Mendapatkan fungsi untuk melepaskan aliran pratinjau halaman output. |
|
|  | [setReleasePageStream(ReleasePageStreamFunction releasePageStream)](#setReleasePageStream-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-) | Mengatur fungsi untuk melepaskan aliran pratinjau halaman output. |
|
|  | [getWidth()](#getWidth--) | Mendapatkan lebar gambar pratinjau. |
|
|  | [setWidth(int value)](#setWidth-int-) | Mengatur lebar gambar pratinjau. |
|
|  | [getHeight()](#getHeight--) | Mendapatkan tinggi gambar pratinjau. |
|
|  | [setHeight(int value)](#setHeight-int-) | Mengatur tinggi gambar pratinjau. |
|
|  | [getPageNumbers()](#getPageNumbers--) | Mendapatkan array nomor halaman yang akan dibuat gambar pratinjau. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | Mengatur array nomor halaman yang akan dibuat gambar pratinjau. |
|
|  | [getPreviewFormat()](#getPreviewFormat--) | Mendapatkan format gambar pratinjau. |
|
|  | [setPreviewFormat(PreviewFormats value)](#setPreviewFormat-com.groupdocs.comparison.options.enums.PreviewFormats-) | Mengatur format gambar pratinjau. |
|
### PreviewOptions(Delegates.CreatePageStream createPageStream) {#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-}
```
public PreviewOptions(Delegates.CreatePageStream createPageStream)
```


Menginisialisasi instance baru dari kelas PreviewOptions dengan menentukan fungsi Delegates.CreatePageStream.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.comparison.common.delegates/createpagestream) | Fungsi untuk membuat aliran pratinjau halaman output. |
|

### PreviewOptions(CreatePageStreamFunction createPageStream) {#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-}
```
public PreviewOptions(CreatePageStreamFunction createPageStream)
```


Menginisialisasi instance baru dari kelas PreviewOptions dengan menentukan fungsi [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | createPageStream | [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) | Fungsi untuk membuat aliran pratinjau halaman output. |
|

### PreviewOptions(Delegates.CreatePageStream createPageStream, Delegates.ReleasePageStream releasePageStream) {#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-}
```
public PreviewOptions(Delegates.CreatePageStream createPageStream, Delegates.ReleasePageStream releasePageStream)
```


Menginisialisasi instance baru dari kelas PreviewOptions dengan menentukan fungsi Delegates.CreatePageStream dan Delegates.ReleasePageStream.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.comparison.common.delegates/createpagestream) | Fungsi untuk membuat aliran pratinjau halaman output. |
|
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.comparison.common.delegates/releasepagestream) | Fungsi untuk melepaskan aliran pratinjau halaman output. |
|

### PreviewOptions(CreatePageStreamFunction createPageStream, ReleasePageStreamFunction releasePageStream) {#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-}
```
public PreviewOptions(CreatePageStreamFunction createPageStream, ReleasePageStreamFunction releasePageStream)
```


Menginisialisasi instance baru dari kelas PreviewOptions dengan menentukan fungsi [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) dan [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | createPageStream | [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) | Fungsi untuk membuat aliran pratinjau halaman output. |
|
|  | releasePageStream | [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) | Fungsi untuk melepaskan aliran pratinjau halaman output. |
|

### getCreatePageStream() {#getCreatePageStream--}
```
public CreatePageStreamFunction getCreatePageStream()
```


Mendapatkan fungsi untuk membuat aliran pratinjau halaman output.


**Returns:**
[CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) - the function to create output page preview stream.

### setCreatePageStream(Delegates.CreatePageStream createPageStream) {#setCreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-}
```
public void setCreatePageStream(Delegates.CreatePageStream createPageStream)
```


Mengatur fungsi untuk membuat aliran pratinjau halaman output.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.comparison.common.delegates/createpagestream) | Fungsi untuk membuat aliran pratinjau halaman output. |
|

### setCreatePageStream(CreatePageStreamFunction createPageStream) {#setCreatePageStream-com.groupdocs.comparison.common.function.CreatePageStreamFunction-}
```
public void setCreatePageStream(CreatePageStreamFunction createPageStream)
```


Mengatur fungsi untuk membuat aliran pratinjau halaman output.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | createPageStream | [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) | Fungsi untuk membuat aliran pratinjau halaman output. |
|

### getReleasePageStream() {#getReleasePageStream--}
```
public ReleasePageStreamFunction getReleasePageStream()
```


Mendapatkan fungsi untuk melepaskan aliran pratinjau halaman output.


**Returns:**
[ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) - the function to release output page preview stream.

### setReleasePageStream(Delegates.ReleasePageStream releasePageStream) {#setReleasePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-}
```
public void setReleasePageStream(Delegates.ReleasePageStream releasePageStream)
```


Mendapatkan fungsi untuk melepaskan aliran pratinjau halaman output.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.comparison.common.delegates/releasepagestream) | Fungsi untuk melepaskan aliran pratinjau halaman output. |
|

### setReleasePageStream(ReleasePageStreamFunction releasePageStream) {#setReleasePageStream-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-}
```
public void setReleasePageStream(ReleasePageStreamFunction releasePageStream)
```


Mengatur fungsi untuk melepaskan aliran pratinjau halaman output.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | releasePageStream | [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) | Fungsi untuk melepaskan aliran pratinjau halaman output. |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Mendapatkan lebar gambar pratinjau.


**Returns:**
int - lebar gambar pratinjau.

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Mengatur lebar gambar pratinjau.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | int | Lebar gambar pratinjau. |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Mendapatkan tinggi gambar pratinjau.


**Returns:**
int - tinggi gambar pratinjau.

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Mengatur tinggi gambar pratinjau.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | int | Tinggi gambar pratinjau. |
|

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Mendapatkan array nomor halaman yang akan dibuat gambar pratinjau.


**Returns:**
int[] - array nomor halaman

### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Mengatur array nomor halaman yang akan dibuat gambar pratinjau.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | int[] | Array nomor halaman |
|

### getPreviewFormat() {#getPreviewFormat--}
```
public final PreviewFormats getPreviewFormat()
```


Mendapatkan format gambar pratinjau.


**Returns:**
[PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats) - preview images format

### setPreviewFormat(PreviewFormats value) {#setPreviewFormat-com.groupdocs.comparison.options.enums.PreviewFormats-}
```
public final void setPreviewFormat(PreviewFormats value)
```


Mengatur format gambar pratinjau.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats) | Format gambar pratinjau |
|

