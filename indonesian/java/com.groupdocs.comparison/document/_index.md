---
title: "Dokumen"
second_title: "Referensi API GroupDocs.Comparison untuk Java"
description: "Mewakili dokumen untuk proses perbandingan."
type: docs
weight: 12
url: /id/java/com.groupdocs.comparison/document/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Document implements Closeable
```

Mewakili dokumen untuk proses perbandingan.


Kelas Document menyediakan metode untuk memuat, menghasilkan gambar pratinjau, dan memanipulasi dokumen selama proses perbandingan.


Contoh penggunaan:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     try (IDocumentInfo info = comparer.getSource().getDocumentInfo()) {
         System.out.println("File type: " + info.getFileType());
         System.out.println("Number of pages: " + info.getPageCount());
         System.out.println("Document size: " + info.getSize());
     }
 }
 
````


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [Document(InputStream stream)](#Document-java.io.InputStream-) | Menginisialisasi instance baru dari kelas Document dengan aliran dokumen yang ditentukan. |
|
|  | [Document(String filePath)](#Document-java.lang.String-) | Menginisialisasi instance baru dari kelas Document dengan jalur dokumen yang ditentukan. |
|
|  | [Document(Path filePath)](#Document-java.nio.file.Path-) | Menginisialisasi instance baru dari kelas Document dengan jalur dokumen yang ditentukan. |
|
|  | [Document(Path filePath, String password)](#Document-java.nio.file.Path-java.lang.String-) | Menginisialisasi instance baru dari kelas Document dengan jalur dokumen yang ditentukan dan kata sandi. |
|
|  | [Document(Path filePath, LoadOptions loadOptions)](#Document-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-) | Menginisialisasi instance baru dari kelas Document dengan jalur dokumen yang ditentukan dan opsi pemuatan. |
|
|  | [Document(String filePath, String password)](#Document-java.lang.String-java.lang.String-) | Menginisialisasi instance baru dari kelas Document dengan jalur dokumen yang ditentukan dan kata sandi. |
|
|  | [Document(String filePath, LoadOptions loadOptions)](#Document-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-) | Menginisialisasi instance baru dari kelas Document dengan jalur dokumen yang ditentukan dan opsi pemuatan. |
|
|  | [Document(InputStream stream, String password)](#Document-java.io.InputStream-java.lang.String-) | Menginisialisasi instance baru dari kelas Document dengan aliran dokumen yang ditentukan dan kata sandi. |
|
|  | [Document(String filePathOrTextContent, boolean isLoadText)](#Document-java.lang.String-boolean-) | Menginisialisasi instance baru dari kelas Document dengan jalur dokumen atau konten teks yang ditentukan dan sebuah flag yang menunjukkan apa yang diberikan. |
|
|  | [Document(InputStream inputStream, LoadOptions loadOptions)](#Document-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-) | Menginisialisasi instance baru dari kelas Document dengan aliran dokumen yang ditentukan dan opsi pemuatan. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getChanges()](#getChanges--) | Mendapatkan daftar objek [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) yang mewakili perubahan yang terdeteksi selama proses perbandingan. |
|
|  | [setChanges(List<ChangeInfo> value)](#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--) | Menetapkan daftar objek [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) yang mewakili perubahan yang terdeteksi selama proses perbandingan. |
|
|  | [getName()](#getName--) | Mendapatkan nama dokumen. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Menetapkan nama dokumen. |
|
|  | [getFileType()](#getFileType--) | Mendapatkan tipe dokumen. |
|
|  | [setFileType(FileType fileType)](#setFileType-com.groupdocs.comparison.result.FileType-) | Menetapkan tipe dokumen. |
|
|  | [createStream()](#createStream--) | Membuat aliran baru dengan konten dokumen. |
|
|  | [getStreamLength()](#getStreamLength--) | Mendapatkan ukuran dokumen |
|
|  | [getPassword()](#getPassword--) | Mendapatkan kata sandi dokumen |
|
|  | [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.comparison.options.PreviewOptions-) | Menghasilkan pratinjau dokumen berdasarkan [PreviewOptions](../../com.groupdocs.comparison.options/previewoptions) yang disediakan. |
|
|  | [getDocumentInfo()](#getDocumentInfo--) | Mendapatkan informasi tentang dokumen, termasuk tipe dokumen, jumlah halaman, ukuran halaman, dan lainnya. |
|
| [close()](#close--) |  |
### Document(InputStream stream) {#Document-java.io.InputStream-}
```
public Document(InputStream stream)
```


Menginisialisasi instance baru dari kelas Document dengan aliran dokumen yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | aliran | java.io.InputStream | Aliran dokumen |
|

### Document(String filePath) {#Document-java.lang.String-}
```
public Document(String filePath)
```


Menginisialisasi instance baru dari kelas Document dengan jalur dokumen yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.lang.String | Jalur dokumen |
|

### Document(Path filePath) {#Document-java.nio.file.Path-}
```
public Document(Path filePath)
```


Menginisialisasi instance baru dari kelas Document dengan jalur dokumen yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Jalur dokumen |
|

### Document(Path filePath, String password) {#Document-java.nio.file.Path-java.lang.String-}
```
public Document(Path filePath, String password)
```


Menginisialisasi instance baru dari kelas Document dengan jalur dokumen yang ditentukan dan kata sandi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Jalur dokumen |
|
|  | kata sandi | java.lang.String | Kata sandi dokumen |
|

### Document(Path filePath, LoadOptions loadOptions) {#Document-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Document(Path filePath, LoadOptions loadOptions)
```


Menginisialisasi instance baru dari kelas Document dengan jalur dokumen yang ditentukan dan opsi pemuatan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Jalur dokumen |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Opsi pemuatan |
|

### Document(String filePath, String password) {#Document-java.lang.String-java.lang.String-}
```
public Document(String filePath, String password)
```


Menginisialisasi instance baru dari kelas Document dengan jalur dokumen yang ditentukan dan kata sandi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.lang.String | Jalur dokumen |
|
|  | kata sandi | java.lang.String | Kata sandi dokumen |
|

### Document(String filePath, LoadOptions loadOptions) {#Document-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Document(String filePath, LoadOptions loadOptions)
```


Menginisialisasi instance baru dari kelas Document dengan jalur dokumen yang ditentukan dan opsi pemuatan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.lang.String | Jalur dokumen |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Opsi pemuatan |
|

### Document(InputStream stream, String password) {#Document-java.io.InputStream-java.lang.String-}
```
public Document(InputStream stream, String password)
```


Menginisialisasi instance baru dari kelas Document dengan aliran dokumen yang ditentukan dan kata sandi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | aliran | java.io.InputStream | Aliran dokumen |
|
|  | kata sandi | java.lang.String | Kata sandi dokumen |
|

### Document(String filePathOrTextContent, boolean isLoadText) {#Document-java.lang.String-boolean-}
```
public Document(String filePathOrTextContent, boolean isLoadText)
```


Menginisialisasi instance baru dari kelas Document dengan jalur dokumen atau konten teks yang ditentukan dan sebuah flag yang menunjukkan apa yang diberikan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePathOrTextContent | java.lang.String | jalur file |
|
|  | isLoadText | boolean | teks muat is |
|

### Document(InputStream inputStream, LoadOptions loadOptions) {#Document-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Document(InputStream inputStream, LoadOptions loadOptions)
```


Menginisialisasi instance baru dari kelas Document dengan aliran dokumen yang ditentukan dan opsi pemuatan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | inputStream | java.io.InputStream | Aliran dokumen |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Opsi pemuatan |
|

### getChanges() {#getChanges--}
```
public final List<ChangeInfo> getChanges()
```


Mendapatkan daftar objek [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) yang mewakili perubahan yang terdeteksi selama proses perbandingan.


Gunakan metode ini untuk mendapatkan informasi terperinci tentang perubahan antara dokumen sumber dan dokumen target.
Setiap objek [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) berisi informasi seperti jenis perubahan, area yang terpengaruh,
dan konten sebelum serta sesudah perubahan.


**Returns:**
java.util.List<com.groupdocs.comparison.result.ChangeInfo> - daftar objek [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) yang mewakili perubahan yang terdeteksi selama proses perbandingan

### setChanges(List<ChangeInfo> value) {#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--}
```
public final void setChanges(List<ChangeInfo> value)
```


Menetapkan daftar objek [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) yang mewakili perubahan yang terdeteksi selama proses perbandingan.


Gunakan metode ini untuk mendapatkan informasi terperinci tentang perubahan antara dokumen sumber dan dokumen target.
Setiap objek [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) berisi informasi seperti jenis perubahan, area yang terpengaruh,
dan konten sebelum serta sesudah perubahan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | java.util.List<com.groupdocs.comparison.result.ChangeInfo> | daftar objek [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) yang mewakili perubahan yang terdeteksi selama proses perbandingan |
|

### getName() {#getName--}
```
public final String getName()
```


Mendapatkan nama dokumen.


**Returns:**
java.lang.String - nama dokumen

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Menetapkan nama dokumen.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | java.lang.String | nama dokumen |
|

### getFileType() {#getFileType--}
```
public FileType getFileType()
```


Mendapatkan tipe dokumen.


**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the type of the document

### setFileType(FileType fileType) {#setFileType-com.groupdocs.comparison.result.FileType-}
```
public void setFileType(FileType fileType)
```


Menetapkan tipe dokumen.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.comparison.result/filetype) | tipe dokumen |
|

### createStream() {#createStream--}
```
public InputStream createStream()
```


Membuat aliran baru dengan konten dokumen.


**Returns:**
java.io.InputStream - aliran dengan konten dokumen

### getStreamLength() {#getStreamLength--}
```
public long getStreamLength()
```


Mendapatkan ukuran dokumen


**Returns:**
long - ukuran dokumen

### getPassword() {#getPassword--}
```
public String getPassword()
```


Mendapatkan kata sandi dokumen


**Returns:**
java.lang.String - kata sandi dokumen

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.comparison.options.PreviewOptions-}
```
public final void generatePreview(PreviewOptions previewOptions)
```


Menghasilkan pratinjau dokumen berdasarkan [PreviewOptions](../../com.groupdocs.comparison.options/previewoptions) yang disediakan.


Metode ini menghasilkan pratinjau halaman dokumen sesuai dengan opsi yang ditentukan, seperti format pratinjau,
nomor halaman, dan penyedia aliran output. Pratinjau yang dihasilkan dapat disimpan atau diproses lebih lanjut sesuai kebutuhan.

* Learn more about how to generate previews for document pages: [How to generate document pages preview using GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Generate+document+pages+preview)


Contoh penggunaan:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     PreviewOptions previewOptions = new PreviewOptions(
             pageNumber -> Files.newOutputStream(Paths.get("preview-image-page-" + pageNumber + ".png"))
     );
     previewOptions.setPreviewFormat(PreviewFormats.PNG);
     previewOptions.setPageNumbers(new int[]{1, 2});
     comparer.getSource().generatePreview(previewOptions);
 }
 
````



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | previewOptions | [PreviewOptions](../../com.groupdocs.comparison.options/previewoptions) | Opsi pratinjau yang menentukan format, nomor halaman, dan sebagainya |
|

### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Mendapatkan informasi tentang dokumen, termasuk tipe dokumen, jumlah halaman, ukuran halaman, dan lainnya.

* Learn more about document file type, page count, size, and other format-specific properties: [How to get document info using GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Get+file+info)


**Returns:**
[IDocumentInfo](../../com.groupdocs.comparison.interfaces/idocumentinfo) - the document information

### close() {#close--}
```
public void close()
```




