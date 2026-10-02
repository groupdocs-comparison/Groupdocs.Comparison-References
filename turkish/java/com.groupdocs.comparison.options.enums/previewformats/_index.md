---
title: "PreviewFormats"
second_title: "GroupDocs.Comparison for Java API Referansı"
description: "Belge karşılaştırması için desteklenen önizleme formatlarını listeler."
type: docs
weight: 15
url: /tr/java/com.groupdocs.comparison.options.enums/previewformats/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PreviewFormats extends Enum<PreviewFormats>
```

Belge karşılaştırması için desteklenen önizleme formatlarını listeler.
PreviewFormats enum'u, karşılaştırılan belgelerin önizlemelerini oluşturmak için kullanılabilecek formatların bir listesini sağlar.

Desteklenen formatlar şunlardır:

* #PNG.PNG - Portable Network Graphics (.png)
* #JPEG.JPEG - Joint Photographic Experts Group (.jpeg)
* #BMP.BMP - Bitmap Picture (.bmp)


Örnek kullanım:

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


## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [PNG](#PNG) | PNG - sayfa çok sayıda renkli grafik içeriyorsa önemli miktarda disk alanı veya ağ trafiği tüketebilir. |
|
|  | [JPEG](#JPEG) | Jpeg - daha küçük disk alanı kullanımı ve ağ trafiği ile daha hızlı işlem sağlar, ancak daha düşük görüntü kalitesine yol açabilir. |
|
|  | [BMP](#BMP) | BMP - en iyi görüntü kalitesini sunar ancak daha yüksek disk alanı kullanımı ve ağ trafiği ile daha yavaş işlem gerektirir. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | PreviewFormats'in dize temsilini ayrıştırarak enum sabitini alır. |
|
|  | [toString()](#toString--) | PreviewFormats'in dize temsili. |
|
### PNG {#PNG}
```
public static final PreviewFormats PNG
```


PNG - sayfa çok sayıda renkli grafik içeriyorsa önemli miktarda disk alanı veya ağ trafiği tüketebilir. Varsayılan ön izleme formatı.


### JPEG {#JPEG}
```
public static final PreviewFormats JPEG
```


Jpeg - daha küçük disk alanı kullanımı ve ağ trafiği ile daha hızlı işlem sağlar, ancak daha düşük görüntü kalitesine yol açabilir.


### BMP {#BMP}
```
public static final PreviewFormats BMP
```


BMP - en iyi görüntü kalitesini sunar ancak daha yüksek disk alanı kullanımı ve ağ trafiği ile daha yavaş işlem gerektirir.


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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static PreviewFormats fromString(String toStringValue)
```


PreviewFormats'in dize temsilini ayrıştırarak enum sabitini alır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | toStringValue | java.lang.String | PreviewFormats'in dize temsili |
|

**Returns:**
[PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats) - PreviewFormats enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


PreviewFormats'in dize temsili.


**Returns:**
java.lang.String - enum sabitinin dize değeri

