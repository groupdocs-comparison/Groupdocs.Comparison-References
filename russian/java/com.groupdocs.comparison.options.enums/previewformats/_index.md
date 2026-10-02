---
title: "PreviewFormats"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "Перечисляет поддерживаемые форматы предварительного просмотра для сравнения документов."
type: docs
weight: 15
url: /ru/java/com.groupdocs.comparison.options.enums/previewformats/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PreviewFormats extends Enum<PreviewFormats>
```

Перечисляет поддерживаемые форматы предварительного просмотра для сравнения документов.
Перечисление PreviewFormats предоставляет список форматов, которые можно использовать для создания предварительных просмотров сравниваемых документов.

Поддерживаемые форматы включают:

* #PNG.PNG - Portable Network Graphics (.png)
* #JPEG.JPEG - Joint Photographic Experts Group (.jpeg)
* #BMP.BMP - Bitmap Picture (.bmp)


Пример использования:

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


## Поля

| Поле | Описание |
| --- | --- |
|  | [PNG](#PNG) | PNG — может занимать значительный объём диска или сетевой трафик, если страница содержит множество цветных графических элементов. |
|
|  | [JPEG](#JPEG) | Jpeg — обеспечивает более быструю обработку при меньшем использовании дискового пространства и сетевого трафика, но может привести к более низкому качеству изображения. |
|
|  | [BMP](#BMP) | BMP — предлагает наилучшее качество изображения, но требует более медленной обработки с большим использованием дискового пространства и сетевого трафика. |
|
## Методы

| Метод | Описание |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Разбирает строковое представление PreviewFormats, чтобы получить константу перечисления. |
|
|  | [toString()](#toString--) | Строковое представление PreviewFormats. |
|
### PNG {#PNG}
```
public static final PreviewFormats PNG
```


PNG — может занимать значительный объём диска или сетевой трафик, если страница содержит множество цветных графических элементов. Формат предварительного просмотра по умолчанию.


### JPEG {#JPEG}
```
public static final PreviewFormats JPEG
```


Jpeg — обеспечивает более быструю обработку при меньшем использовании дискового пространства и сетевого трафика, но может привести к более низкому качеству изображения.


### BMP {#BMP}
```
public static final PreviewFormats BMP
```


BMP — предлагает наилучшее качество изображения, но требует более медленной обработки с большим использованием дискового пространства и сетевого трафика.


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
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String |  |

**Returns:**
[PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static PreviewFormats fromString(String toStringValue)
```


Разбирает строковое представление PreviewFormats, чтобы получить константу перечисления.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | toStringValue | java.lang.String | Строковое представление PreviewFormats |
|

**Returns:**
[PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats) - PreviewFormats enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


Строковое представление PreviewFormats.


**Returns:**
java.lang.String — строковое значение константы перечисления

