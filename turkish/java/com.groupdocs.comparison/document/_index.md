---
title: "Belge"
second_title: "GroupDocs.Comparison for Java API Referansı"
description: "Karşılaştırma süreci için bir belgeyi temsil eder."
type: docs
weight: 12
url: /tr/java/com.groupdocs.comparison/document/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Document implements Closeable
```

Karşılaştırma süreci için bir belgeyi temsil eder.


Document sınıfı, karşılaştırma sürecinde belgeleri yüklemek, ön izleme görüntüleri oluşturmak ve belgeleri manipüle etmek için yöntemler sağlar.


Örnek kullanım:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     try (IDocumentInfo info = comparer.getSource().getDocumentInfo()) {
         System.out.println("File type: " + info.getFileType());
         System.out.println("Number of pages: " + info.getPageCount());
         System.out.println("Document size: " + info.getSize());
     }
 }
 
````


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [Document(InputStream stream)](#Document-java.io.InputStream-) | Belirtilen belge akışıyla Document sınıfının yeni bir örneğini başlatır. |
|
|  | [Document(String filePath)](#Document-java.lang.String-) | Belirtilen belge yolu ile Document sınıfının yeni bir örneğini başlatır. |
|
|  | [Document(Path filePath)](#Document-java.nio.file.Path-) | Belirtilen belge yolu ile Document sınıfının yeni bir örneğini başlatır. |
|
|  | [Document(Path filePath, String password)](#Document-java.nio.file.Path-java.lang.String-) | Belirtilen belge yolu ve bir şifre ile Document sınıfının yeni bir örneğini başlatır. |
|
|  | [Document(Path filePath, LoadOptions loadOptions)](#Document-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-) | Belirtilen belge yolu ve yükleme seçenekleri ile Document sınıfının yeni bir örneğini başlatır. |
|
|  | [Document(String filePath, String password)](#Document-java.lang.String-java.lang.String-) | Belirtilen belge yolu ve bir şifre ile Document sınıfının yeni bir örneğini başlatır. |
|
|  | [Document(String filePath, LoadOptions loadOptions)](#Document-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-) | Belirtilen belge yolu ve yükleme seçenekleri ile Document sınıfının yeni bir örneğini başlatır. |
|
|  | [Document(InputStream stream, String password)](#Document-java.io.InputStream-java.lang.String-) | Belirtilen belge akışı ve bir şifre ile Document sınıfının yeni bir örneğini başlatır. |
|
|  | [Document(String filePathOrTextContent, boolean isLoadText)](#Document-java.lang.String-boolean-) | Belirtilen belge yolu veya metin içeriği ve neyin geçirildiğini gösteren bir bayrak ile Document sınıfının yeni bir örneğini başlatır. |
|
|  | [Document(InputStream inputStream, LoadOptions loadOptions)](#Document-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-) | Belirtilen belge akışı ve yükleme seçenekleri ile Document sınıfının yeni bir örneğini başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getChanges()](#getChanges--) | Karşılaştırma sürecinde tespit edilen değişiklikleri temsil eden [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) nesnelerinin bir listesini alır. |
|
|  | [setChanges(List<ChangeInfo> value)](#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--) | Karşılaştırma sürecinde tespit edilen değişiklikleri temsil eden [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) nesnelerinin bir listesini ayarlar. |
|
|  | [getName()](#getName--) | Belgenin adını alır. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Belgenin adını ayarlar. |
|
|  | [getFileType()](#getFileType--) | Belgenin türünü alır. |
|
|  | [setFileType(FileType fileType)](#setFileType-com.groupdocs.comparison.result.FileType-) | Belgenin türünü ayarlar. |
|
|  | [createStream()](#createStream--) | Belge içeriğiyle yeni bir akış oluşturur. |
|
|  | [getStreamLength()](#getStreamLength--) | Belgenin boyutunu alır |
|
|  | [getPassword()](#getPassword--) | Belgenin şifresini alır |
|
|  | [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.comparison.options.PreviewOptions-) | Sağlanan [PreviewOptions](../../com.groupdocs.comparison.options/previewoptions) temelinde belge ön izlemeleri oluşturur. |
|
|  | [getDocumentInfo()](#getDocumentInfo--) | Belge hakkında, belge türü, sayfa sayısı, sayfa boyutları ve daha fazlası dahil olmak üzere bilgi alır. |
|
| [close()](#close--) |  |
### Document(InputStream stream) {#Document-java.io.InputStream-}
```
public Document(InputStream stream)
```


Belirtilen belge akışıyla Document sınıfının yeni bir örneğini başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | akış | java.io.InputStream | Belge akışı |
|

### Document(String filePath) {#Document-java.lang.String-}
```
public Document(String filePath)
```


Belirtilen belge yolu ile Document sınıfının yeni bir örneğini başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Belge yolu |
|

### Document(Path filePath) {#Document-java.nio.file.Path-}
```
public Document(Path filePath)
```


Belirtilen belge yolu ile Document sınıfının yeni bir örneğini başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Belge yolu |
|

### Document(Path filePath, String password) {#Document-java.nio.file.Path-java.lang.String-}
```
public Document(Path filePath, String password)
```


Belirtilen belge yolu ve bir şifre ile Document sınıfının yeni bir örneğini başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Belge yolu |
|
|  | şifre | java.lang.String | Belge şifresi |
|

### Document(Path filePath, LoadOptions loadOptions) {#Document-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Document(Path filePath, LoadOptions loadOptions)
```


Belirtilen belge yolu ve yükleme seçenekleri ile Document sınıfının yeni bir örneğini başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Belge yolu |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Yükleme seçenekleri |
|

### Document(String filePath, String password) {#Document-java.lang.String-java.lang.String-}
```
public Document(String filePath, String password)
```


Belirtilen belge yolu ve bir şifre ile Document sınıfının yeni bir örneğini başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Belge yolu |
|
|  | şifre | java.lang.String | Belge şifresi |
|

### Document(String filePath, LoadOptions loadOptions) {#Document-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Document(String filePath, LoadOptions loadOptions)
```


Belirtilen belge yolu ve yükleme seçenekleri ile Document sınıfının yeni bir örneğini başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Belge yolu |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Yükleme seçenekleri |
|

### Document(InputStream stream, String password) {#Document-java.io.InputStream-java.lang.String-}
```
public Document(InputStream stream, String password)
```


Belirtilen belge akışı ve bir şifre ile Document sınıfının yeni bir örneğini başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | akış | java.io.InputStream | Belge akışı |
|
|  | şifre | java.lang.String | Belge şifresi |
|

### Document(String filePathOrTextContent, boolean isLoadText) {#Document-java.lang.String-boolean-}
```
public Document(String filePathOrTextContent, boolean isLoadText)
```


Belirtilen belge yolu veya metin içeriği ve neyin geçirildiğini gösteren bir bayrak ile Document sınıfının yeni bir örneğini başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePathOrTextContent | java.lang.String | dosya yolu |
|
|  | isLoadText | boolean | yükleme metni |
|

### Document(InputStream inputStream, LoadOptions loadOptions) {#Document-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Document(InputStream inputStream, LoadOptions loadOptions)
```


Belirtilen belge akışı ve yükleme seçenekleri ile Document sınıfının yeni bir örneğini başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | inputStream | java.io.InputStream | Belge akışı |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Yükleme seçenekleri |
|

### getChanges() {#getChanges--}
```
public final List<ChangeInfo> getChanges()
```


Karşılaştırma sürecinde tespit edilen değişiklikleri temsil eden [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) nesnelerinin bir listesini alır.


Kaynak belge ile hedef belge(ler) arasındaki değişiklikler hakkında ayrıntılı bilgi almak için bu yöntemi kullanın.
Her bir [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) nesnesi, değişiklik türü, etkilenen alan gibi bilgileri içerir,
ve değişiklik öncesi ve sonrası içeriği.


**Returns:**
java.util.List<com.groupdocs.comparison.result.ChangeInfo> - karşılaştırma sürecinde tespit edilen değişiklikleri temsil eden [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) nesnelerinin bir listesi

### setChanges(List<ChangeInfo> value) {#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--}
```
public final void setChanges(List<ChangeInfo> value)
```


Karşılaştırma sürecinde tespit edilen değişiklikleri temsil eden [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) nesnelerinin bir listesini ayarlar.


Kaynak belge ile hedef belge(ler) arasındaki değişiklikler hakkında ayrıntılı bilgi almak için bu yöntemi kullanın.
Her bir [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) nesnesi, değişiklik türü, etkilenen alan gibi bilgileri içerir,
ve değişiklik öncesi ve sonrası içeriği.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | java.util.List<com.groupdocs.comparison.result.ChangeInfo> | karşılaştırma sürecinde tespit edilen değişiklikleri temsil eden [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) nesnelerinin bir listesi |
|

### getName() {#getName--}
```
public final String getName()
```


Belgenin adını alır.


**Returns:**
java.lang.String - belgenin adı

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Belgenin adını ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.lang.String | belgenin adı |
|

### getFileType() {#getFileType--}
```
public FileType getFileType()
```


Belgenin türünü alır.


**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the type of the document

### setFileType(FileType fileType) {#setFileType-com.groupdocs.comparison.result.FileType-}
```
public void setFileType(FileType fileType)
```


Belgenin türünü ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.comparison.result/filetype) | belgenin türü |
|

### createStream() {#createStream--}
```
public InputStream createStream()
```


Belge içeriğiyle yeni bir akış oluşturur.


**Returns:**
java.io.InputStream - belgenin içeriğini içeren akış

### getStreamLength() {#getStreamLength--}
```
public long getStreamLength()
```


Belgenin boyutunu alır


**Returns:**
long - belgenin boyutu

### getPassword() {#getPassword--}
```
public String getPassword()
```


Belgenin şifresini alır


**Returns:**
java.lang.String - belgenin şifresi

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.comparison.options.PreviewOptions-}
```
public final void generatePreview(PreviewOptions previewOptions)
```


Sağlanan [PreviewOptions](../../com.groupdocs.comparison.options/previewoptions) temelinde belge ön izlemeleri oluşturur.


Bu yöntem, belirtilen seçeneklere göre belge sayfalarının önizlemelerini oluşturur, örneğin önizleme biçimi,
sayfa numaraları ve çıktı akışı sağlayıcı. Oluşturulan önizlemeler gerektiği gibi kaydedilebilir veya daha fazla işlenebilir.

* Learn more about how to generate previews for document pages: [How to generate document pages preview using GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Generate+document+pages+preview)


Örnek kullanım:

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | previewOptions | [PreviewOptions](../../com.groupdocs.comparison.options/previewoptions) | Biçim, sayfa numaraları vb. belirten önizleme seçenekleri |
|

### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Belge hakkında, belge türü, sayfa sayısı, sayfa boyutları ve daha fazlası dahil olmak üzere bilgi alır.

* Learn more about document file type, page count, size, and other format-specific properties: [How to get document info using GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Get+file+info)


**Returns:**
[IDocumentInfo](../../com.groupdocs.comparison.interfaces/idocumentinfo) - the document information

### close() {#close--}
```
public void close()
```




