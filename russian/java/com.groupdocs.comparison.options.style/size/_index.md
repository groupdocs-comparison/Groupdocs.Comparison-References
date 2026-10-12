---
title: "Размер"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "Представляет размер документа при сравнении."
type: docs
weight: 11
url: /ru/java/com.groupdocs.comparison.options.style/size/
---
**Inheritance:**
java.lang.Object
```
public class Size
```

Представляет размер документа при сравнении.


Пример использования:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     final Size originalSize = new Size(100, 200);

     StyleSettings styleSettings = new StyleSettings();
     styleSettings.setOriginalSize(originalSize);

     final CompareOptions compareOptions = new CompareOptions();
     compareOptions.setInsertedItemStyle(styleSettings);

     comparer.compare(resultFile, compareOptions);
 }
 
````


## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [Size()](#Size--) | Инициализирует новый экземпляр класса Size. |
|
|  | [Size(int width, int height)](#Size-int-int-) | Инициализирует новый экземпляр класса Size с шириной и высотой документа. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getWidth()](#getWidth--) | Получает ширину оригинального документа. |
|
|  | [setWidth(int value)](#setWidth-int-) | Устанавливает ширину оригинального документа. |
|
|  | [getHeight()](#getHeight--) | Получает высоту оригинального документа. |
|
|  | [setHeight(int value)](#setHeight-int-) | Устанавливает высоту оригинального документа. |
|
### Size() {#Size--}
```
public Size()
```


Инициализирует новый экземпляр класса Size.


### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


Инициализирует новый экземпляр класса Size с шириной и высотой документа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ширина | int |  |
| высота | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Получает ширину оригинального документа.


**Returns:**
int — ширина документа

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Устанавливает ширину оригинального документа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | int | Ширина документа |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Получает высоту оригинального документа.


**Returns:**
int — высота документа

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Устанавливает высоту оригинального документа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | int | Высота документа |
|

