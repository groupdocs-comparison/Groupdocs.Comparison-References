---
title: "OriginalSize"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "Представляет исходный размер документа в результате сравнения."
type: docs
weight: 14
url: /ru/java/com.groupdocs.comparison.options/originalsize/
---
**Inheritance:**
java.lang.Object
```
public class OriginalSize
```

Представляет исходный размер документа в результате сравнения.


Исходный размер включает размеры (ширину и высоту) страниц документа.


Пример использования:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     CompareOptions compareOptions = new CompareOptions();
     final OriginalSize originalSize = compareOptions.getOriginalSize();
     originalSize.setWidth(480);
     originalSize.setHeight(640);

     comparer.compare(resultFile, compareOptions);
 }
 
````


## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [OriginalSize()](#OriginalSize--) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getWidth()](#getWidth--) | Получает ширину страниц документа. |
|
|  | [setWidth(int value)](#setWidth-int-) | Устанавливает ширину страниц документа. |
|
|  | [getHeight()](#getHeight--) | Получает высоту страниц документа. |
|
|  | [setHeight(int value)](#setHeight-int-) | Устанавливает высоту страниц документа. |
|
### OriginalSize() {#OriginalSize--}
```
public OriginalSize()
```


### getWidth() {#getWidth--}
```
public final int getWidth()
```


Получает ширину страниц документа.


**Returns:**
int — ширина страниц документа.

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Устанавливает ширину страниц документа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | int | Ширина страниц документа. |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Получает высоту страниц документа.


**Returns:**
int — высота страниц документа.

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Устанавливает высоту страниц документа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | int | Высота страниц документа. |
|

