---
title: "PreviewOptions"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "Предоставляет параметры для создания предварительных просмотров документов в процессе сравнения."
type: docs
weight: 15
url: /ru/java/com.groupdocs.comparison.options/previewoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewOptions
```

Предоставляет параметры для создания предварительных просмотров документов в процессе сравнения.


Пример использования:

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


## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [PreviewOptions(Delegates.CreatePageStream createPageStream)](#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-) | Инициализирует новый экземпляр класса PreviewOptions, указывая функцию Delegates.CreatePageStream. |
|
|  | [PreviewOptions(CreatePageStreamFunction createPageStream)](#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-) | Инициализирует новый экземпляр класса PreviewOptions, указывая функцию [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction). |
|
|  | [PreviewOptions(Delegates.CreatePageStream createPageStream, Delegates.ReleasePageStream releasePageStream)](#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-) | Инициализирует новый экземпляр класса PreviewOptions, указывая функции Delegates.CreatePageStream и Delegates.ReleasePageStream. |
|
|  | [PreviewOptions(CreatePageStreamFunction createPageStream, ReleasePageStreamFunction releasePageStream)](#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-) | Инициализирует новый экземпляр класса PreviewOptions, указывая функции [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) и [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction). |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getCreatePageStream()](#getCreatePageStream--) | Получает функцию для создания потока предварительного просмотра выходной страницы. |
|
|  | [setCreatePageStream(Delegates.CreatePageStream createPageStream)](#setCreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-) | Устанавливает функцию для создания потока предварительного просмотра выходной страницы. |
|
|  | [setCreatePageStream(CreatePageStreamFunction createPageStream)](#setCreatePageStream-com.groupdocs.comparison.common.function.CreatePageStreamFunction-) | Устанавливает функцию для создания потока предварительного просмотра выходной страницы. |
|
|  | [getReleasePageStream()](#getReleasePageStream--) | Получает функцию для освобождения потока предварительного просмотра выходной страницы. |
|
|  | [setReleasePageStream(Delegates.ReleasePageStream releasePageStream)](#setReleasePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-) | Получает функцию для освобождения потока предварительного просмотра выходной страницы. |
|
|  | [setReleasePageStream(ReleasePageStreamFunction releasePageStream)](#setReleasePageStream-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-) | Устанавливает функцию для освобождения потока предварительного просмотра выходной страницы. |
|
|  | [getWidth()](#getWidth--) | Получает ширину предварительных изображений. |
|
|  | [setWidth(int value)](#setWidth-int-) | Устанавливает ширину предварительных изображений. |
|
|  | [getHeight()](#getHeight--) | Получает высоту предварительных изображений. |
|
|  | [setHeight(int value)](#setHeight-int-) | Устанавливает высоту предварительных изображений. |
|
|  | [getPageNumbers()](#getPageNumbers--) | Получает массив номеров страниц, для которых будут создаваться предварительные изображения. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | Устанавливает массив номеров страниц, для которых будут создаваться предварительные изображения. |
|
|  | [getPreviewFormat()](#getPreviewFormat--) | Получает формат предварительных изображений. |
|
|  | [setPreviewFormat(PreviewFormats value)](#setPreviewFormat-com.groupdocs.comparison.options.enums.PreviewFormats-) | Устанавливает формат предварительных изображений. |
|
### PreviewOptions(Delegates.CreatePageStream createPageStream) {#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-}
```
public PreviewOptions(Delegates.CreatePageStream createPageStream)
```


Инициализирует новый экземпляр класса PreviewOptions, указывая функцию Delegates.CreatePageStream.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.comparison.common.delegates/createpagestream) | Функция для создания потока предварительного просмотра выходных страниц. |
|

### PreviewOptions(CreatePageStreamFunction createPageStream) {#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-}
```
public PreviewOptions(CreatePageStreamFunction createPageStream)
```


Инициализирует новый экземпляр класса PreviewOptions, указывая функцию [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | createPageStream | [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) | Функция для создания потока предварительного просмотра выходных страниц. |
|

### PreviewOptions(Delegates.CreatePageStream createPageStream, Delegates.ReleasePageStream releasePageStream) {#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-}
```
public PreviewOptions(Delegates.CreatePageStream createPageStream, Delegates.ReleasePageStream releasePageStream)
```


Инициализирует новый экземпляр класса PreviewOptions, указывая функции Delegates.CreatePageStream и Delegates.ReleasePageStream.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.comparison.common.delegates/createpagestream) | Функция для создания потока предварительного просмотра выходных страниц. |
|
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.comparison.common.delegates/releasepagestream) | Функция для освобождения потока предварительного просмотра выходных страниц. |
|

### PreviewOptions(CreatePageStreamFunction createPageStream, ReleasePageStreamFunction releasePageStream) {#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-}
```
public PreviewOptions(CreatePageStreamFunction createPageStream, ReleasePageStreamFunction releasePageStream)
```


Инициализирует новый экземпляр класса PreviewOptions, указывая функции [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) и [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | createPageStream | [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) | Функция для создания потока предварительного просмотра выходных страниц. |
|
|  | releasePageStream | [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) | Функция для освобождения потока предварительного просмотра выходных страниц. |
|

### getCreatePageStream() {#getCreatePageStream--}
```
public CreatePageStreamFunction getCreatePageStream()
```


Получает функцию для создания потока предварительного просмотра выходной страницы.


**Returns:**
[CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) - the function to create output page preview stream.

### setCreatePageStream(Delegates.CreatePageStream createPageStream) {#setCreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-}
```
public void setCreatePageStream(Delegates.CreatePageStream createPageStream)
```


Устанавливает функцию для создания потока предварительного просмотра выходной страницы.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.comparison.common.delegates/createpagestream) | Функция для создания потока предварительного просмотра выходных страниц. |
|

### setCreatePageStream(CreatePageStreamFunction createPageStream) {#setCreatePageStream-com.groupdocs.comparison.common.function.CreatePageStreamFunction-}
```
public void setCreatePageStream(CreatePageStreamFunction createPageStream)
```


Устанавливает функцию для создания потока предварительного просмотра выходной страницы.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | createPageStream | [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) | Функция для создания потока предварительного просмотра выходных страниц. |
|

### getReleasePageStream() {#getReleasePageStream--}
```
public ReleasePageStreamFunction getReleasePageStream()
```


Получает функцию для освобождения потока предварительного просмотра выходной страницы.


**Returns:**
[ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) - the function to release output page preview stream.

### setReleasePageStream(Delegates.ReleasePageStream releasePageStream) {#setReleasePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-}
```
public void setReleasePageStream(Delegates.ReleasePageStream releasePageStream)
```


Получает функцию для освобождения потока предварительного просмотра выходной страницы.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.comparison.common.delegates/releasepagestream) | Функция для освобождения потока предварительного просмотра выходных страниц. |
|

### setReleasePageStream(ReleasePageStreamFunction releasePageStream) {#setReleasePageStream-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-}
```
public void setReleasePageStream(ReleasePageStreamFunction releasePageStream)
```


Устанавливает функцию для освобождения потока предварительного просмотра выходной страницы.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | releasePageStream | [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) | Функция для освобождения потока предварительного просмотра выходных страниц. |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Получает ширину предварительных изображений.


**Returns:**
int — ширина предварительных изображений.

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Устанавливает ширину предварительных изображений.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | int | Ширина предварительных изображений. |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Получает высоту предварительных изображений.


**Returns:**
int — высота предварительных изображений.

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Устанавливает высоту предварительных изображений.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | int | Высота предварительных изображений. |
|

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Получает массив номеров страниц, для которых будут создаваться предварительные изображения.


**Returns:**
int[] — массив номеров страниц

### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Устанавливает массив номеров страниц, для которых будут создаваться предварительные изображения.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | int[] | Массив номеров страниц |
|

### getPreviewFormat() {#getPreviewFormat--}
```
public final PreviewFormats getPreviewFormat()
```


Получает формат предварительных изображений.


**Returns:**
[PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats) - preview images format

### setPreviewFormat(PreviewFormats value) {#setPreviewFormat-com.groupdocs.comparison.options.enums.PreviewFormats-}
```
public final void setPreviewFormat(PreviewFormats value)
```


Устанавливает формат предварительных изображений.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | [PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats) | Формат предварительных изображений |
|

