---
title: "PreviewFormats"
second_title: "Referensi API GroupDocs.Comparison untuk Java"
description: "Menumerasikan format pratinjau yang didukung untuk perbandingan dokumen."
type: docs
weight: 15
url: /id/java/com.groupdocs.comparison.options.enums/previewformats/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PreviewFormats extends Enum<PreviewFormats>
```

Menumerasikan format pratinjau yang didukung untuk perbandingan dokumen.
Enum PreviewFormats menyediakan daftar format yang dapat digunakan untuk menghasilkan pratinjau dokumen yang dibandingkan.

Format yang didukung meliputi:

* #PNG.PNG - Portable Network Graphics (.png)
* #JPEG.JPEG - Joint Photographic Experts Group (.jpeg)
* #BMP.BMP - Bitmap Picture (.bmp)


Contoh penggunaan:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    PreviewOptions previewOptions = new PreviewOptions(
            pageNumber -> Files.newOutputStream(Paths.get(String.format("preview-page_%d.png", pageNumber)))
    );
    previewOptions.setPreviewFormat(PreviewFormats.PNG);

    comparer.getTargets().get(0).generatePreview(previewOptions);
 }
 
````


## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [PNG](#PNG) | PNG - dapat mengonsumsi ruang disk atau lalu lintas jaringan yang signifikan jika halaman berisi banyak grafik berwarna. |
|
|  | [JPEG](#JPEG) | Jpeg - menyediakan pemrosesan lebih cepat dengan penggunaan ruang disk dan lalu lintas jaringan yang lebih kecil, tetapi dapat menghasilkan kualitas gambar yang lebih rendah. |
|
|  | [BMP](#BMP) | BMP - menawarkan kualitas gambar terbaik tetapi memerlukan pemrosesan yang lebih lambat dengan penggunaan ruang disk dan lalu lintas jaringan yang lebih tinggi. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Menganalisis representasi string dari PreviewFormats untuk mendapatkan konstanta enum. |
|
|  | [toString()](#toString--) | Representasi string dari PreviewFormats. |
|
### PNG {#PNG}
```
public static final PreviewFormats PNG
```


PNG - dapat mengonsumsi ruang disk atau lalu lintas jaringan yang signifikan jika halaman berisi banyak grafik berwarna. Format pratinjau default.


### JPEG {#JPEG}
```
public static final PreviewFormats JPEG
```


Jpeg - menyediakan pemrosesan lebih cepat dengan penggunaan ruang disk dan lalu lintas jaringan yang lebih kecil, tetapi dapat menghasilkan kualitas gambar yang lebih rendah.


### BMP {#BMP}
```
public static final PreviewFormats BMP
```


BMP - menawarkan kualitas gambar terbaik tetapi memerlukan pemrosesan yang lebih lambat dengan penggunaan ruang disk dan lalu lintas jaringan yang lebih tinggi.


### values() {#values--}
```
public static PreviewFormats[] values()
```




**Returns:**
com.groupdocs.comparison.options.enums.PreviewFormats[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PreviewFormats valueOf(String name)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static PreviewFormats fromString(String toStringValue)
```


Menganalisis representasi string dari PreviewFormats untuk mendapatkan konstanta enum.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | toStringValue | java.lang.String | Representasi string dari PreviewFormats |
|

**Returns:**
[PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats) - PreviewFormats enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


Representasi string dari PreviewFormats.


**Returns:**
java.lang.String - nilai string dari konstanta enum

