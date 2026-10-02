---
title: "PreviewOptions"
second_title: "GroupDocs.Comparison for Java API Referansı"
description: "Karşılaştırma sürecinde belge ön izlemeleri oluşturmak için seçenekler sağlar."
type: docs
weight: 15
url: /tr/java/com.groupdocs.comparison.options/previewoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewOptions
```

Karşılaştırma sürecinde belge ön izlemeleri oluşturmak için seçenekler sağlar.


Örnek kullanım:

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


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [PreviewOptions(Delegates.CreatePageStream createPageStream)](#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-) | Delegates.CreatePageStream işlevini belirten PreviewOptions sınıfının yeni bir örneğini başlatır. |
|
|  | [PreviewOptions(CreatePageStreamFunction createPageStream)](#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-) | PreviewOptions sınıfının yeni bir örneğini, [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) işlevini belirterek başlatır. |
|
|  | [PreviewOptions(Delegates.CreatePageStream createPageStream, Delegates.ReleasePageStream releasePageStream)](#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-) | Delegates.CreatePageStream ve Delegates.ReleasePageStream işlevlerini belirten PreviewOptions sınıfının yeni bir örneğini başlatır. |
|
|  | [PreviewOptions(CreatePageStreamFunction createPageStream, ReleasePageStreamFunction releasePageStream)](#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-) | PreviewOptions sınıfının yeni bir örneğini, [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) ve [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) işlevlerini belirterek başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getCreatePageStream()](#getCreatePageStream--) | Çıktı sayfa önizleme akışı oluşturmak için bir işlev alır. |
|
|  | [setCreatePageStream(Delegates.CreatePageStream createPageStream)](#setCreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-) | Çıktı sayfa önizleme akışı oluşturmak için bir işlev ayarlar. |
|
|  | [setCreatePageStream(CreatePageStreamFunction createPageStream)](#setCreatePageStream-com.groupdocs.comparison.common.function.CreatePageStreamFunction-) | Çıktı sayfa önizleme akışı oluşturmak için bir işlev ayarlar. |
|
|  | [getReleasePageStream()](#getReleasePageStream--) | Çıktı sayfa önizleme akışını serbest bırakmak için bir işlev alır. |
|
|  | [setReleasePageStream(Delegates.ReleasePageStream releasePageStream)](#setReleasePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-) | Çıktı sayfa önizleme akışını serbest bırakmak için bir işlev alır. |
|
|  | [setReleasePageStream(ReleasePageStreamFunction releasePageStream)](#setReleasePageStream-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-) | Çıktı sayfa önizleme akışını serbest bırakmak için bir işlev ayarlar. |
|
|  | [getWidth()](#getWidth--) | Önizleme görüntülerinin genişliğini alır. |
|
|  | [setWidth(int value)](#setWidth-int-) | Önizleme görüntülerinin genişliğini ayarlar. |
|
|  | [getHeight()](#getHeight--) | Önizleme görüntülerinin yüksekliğini alır. |
|
|  | [setHeight(int value)](#setHeight-int-) | Önizleme görüntülerinin yüksekliğini ayarlar. |
|
|  | [getPageNumbers()](#getPageNumbers--) | Önizleme görüntülerinin oluşturulacağı sayfa numaralarının bir dizisini alır. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | Önizleme görüntülerinin oluşturulacağı sayfa numaralarının bir dizisini ayarlar. |
|
|  | [getPreviewFormat()](#getPreviewFormat--) | Önizleme görüntülerinin formatını alır. |
|
|  | [setPreviewFormat(PreviewFormats value)](#setPreviewFormat-com.groupdocs.comparison.options.enums.PreviewFormats-) | Önizleme görüntülerinin formatını ayarlar. |
|
### PreviewOptions(Delegates.CreatePageStream createPageStream) {#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-}
```
public PreviewOptions(Delegates.CreatePageStream createPageStream)
```


Delegates.CreatePageStream işlevini belirten PreviewOptions sınıfının yeni bir örneğini başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.comparison.common.delegates/createpagestream) | Çıktı sayfa önizleme akışı oluşturmak için işlev. |
|

### PreviewOptions(CreatePageStreamFunction createPageStream) {#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-}
```
public PreviewOptions(CreatePageStreamFunction createPageStream)
```


PreviewOptions sınıfının yeni bir örneğini, [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) işlevini belirterek başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | createPageStream | [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) | Çıktı sayfa önizleme akışı oluşturmak için işlev. |
|

### PreviewOptions(Delegates.CreatePageStream createPageStream, Delegates.ReleasePageStream releasePageStream) {#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-}
```
public PreviewOptions(Delegates.CreatePageStream createPageStream, Delegates.ReleasePageStream releasePageStream)
```


Delegates.CreatePageStream ve Delegates.ReleasePageStream işlevlerini belirten PreviewOptions sınıfının yeni bir örneğini başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.comparison.common.delegates/createpagestream) | Çıktı sayfa önizleme akışı oluşturmak için işlev. |
|
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.comparison.common.delegates/releasepagestream) | Çıktı sayfa önizleme akışını serbest bırakmak için işlev. |
|

### PreviewOptions(CreatePageStreamFunction createPageStream, ReleasePageStreamFunction releasePageStream) {#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-}
```
public PreviewOptions(CreatePageStreamFunction createPageStream, ReleasePageStreamFunction releasePageStream)
```


PreviewOptions sınıfının yeni bir örneğini, [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) ve [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) işlevlerini belirterek başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | createPageStream | [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) | Çıktı sayfa önizleme akışı oluşturmak için işlev. |
|
|  | releasePageStream | [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) | Çıktı sayfa önizleme akışını serbest bırakmak için işlev. |
|

### getCreatePageStream() {#getCreatePageStream--}
```
public CreatePageStreamFunction getCreatePageStream()
```


Çıktı sayfa önizleme akışı oluşturmak için bir işlev alır.


**Returns:**
[CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) - the function to create output page preview stream.

### setCreatePageStream(Delegates.CreatePageStream createPageStream) {#setCreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-}
```
public void setCreatePageStream(Delegates.CreatePageStream createPageStream)
```


Çıktı sayfa önizleme akışı oluşturmak için bir işlev ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.comparison.common.delegates/createpagestream) | Çıktı sayfa önizleme akışı oluşturmak için işlev. |
|

### setCreatePageStream(CreatePageStreamFunction createPageStream) {#setCreatePageStream-com.groupdocs.comparison.common.function.CreatePageStreamFunction-}
```
public void setCreatePageStream(CreatePageStreamFunction createPageStream)
```


Çıktı sayfa önizleme akışı oluşturmak için bir işlev ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | createPageStream | [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) | Çıktı sayfa önizleme akışı oluşturmak için işlev. |
|

### getReleasePageStream() {#getReleasePageStream--}
```
public ReleasePageStreamFunction getReleasePageStream()
```


Çıktı sayfa önizleme akışını serbest bırakmak için bir işlev alır.


**Returns:**
[ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) - the function to release output page preview stream.

### setReleasePageStream(Delegates.ReleasePageStream releasePageStream) {#setReleasePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-}
```
public void setReleasePageStream(Delegates.ReleasePageStream releasePageStream)
```


Çıktı sayfa önizleme akışını serbest bırakmak için bir işlev alır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.comparison.common.delegates/releasepagestream) | Çıktı sayfa önizleme akışını serbest bırakmak için işlev. |
|

### setReleasePageStream(ReleasePageStreamFunction releasePageStream) {#setReleasePageStream-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-}
```
public void setReleasePageStream(ReleasePageStreamFunction releasePageStream)
```


Çıktı sayfa önizleme akışını serbest bırakmak için bir işlev ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | releasePageStream | [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) | Çıktı sayfa önizleme akışını serbest bırakmak için işlev. |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Önizleme görüntülerinin genişliğini alır.


**Returns:**
int - ön izleme görüntülerinin genişliği.

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Önizleme görüntülerinin genişliğini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | int | Ön izleme görüntülerinin genişliği. |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Önizleme görüntülerinin yüksekliğini alır.


**Returns:**
int - ön izleme görüntülerinin yüksekliği.

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Önizleme görüntülerinin yüksekliğini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | int | Ön izleme görüntülerinin yüksekliği. |
|

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Önizleme görüntülerinin oluşturulacağı sayfa numaralarının bir dizisini alır.


**Returns:**
int[] - sayfa numaraları dizisi

### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Önizleme görüntülerinin oluşturulacağı sayfa numaralarının bir dizisini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | int[] | Sayfa numaraları dizisi |
|

### getPreviewFormat() {#getPreviewFormat--}
```
public final PreviewFormats getPreviewFormat()
```


Önizleme görüntülerinin formatını alır.


**Returns:**
[PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats) - preview images format

### setPreviewFormat(PreviewFormats value) {#setPreviewFormat-com.groupdocs.comparison.options.enums.PreviewFormats-}
```
public final void setPreviewFormat(PreviewFormats value)
```


Önizleme görüntülerinin formatını ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats) | Ön izleme görüntüleri biçimi |
|

