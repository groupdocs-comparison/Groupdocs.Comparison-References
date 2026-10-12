---
title: "PageInfo"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "Класс PageInfo представляет информацию о конкретной странице в документе."
type: docs
weight: 11
url: /ru/java/com.groupdocs.comparison.result/pageinfo/
---
**Inheritance:**
java.lang.Object
```
public class PageInfo
```

Класс PageInfo представляет информацию о конкретной странице в документе.


Он предоставляет детали, такие как номер страницы, ширина, высота и другие соответствующие свойства.
Используйте этот класс для получения информации о отдельных страницах документа во время процесса сравнения.


Пример использования:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     comparer.compare(resultFile);
     final ChangeInfo[] changes = comparer.getChanges();
     for (ChangeInfo change : changes) {
         final PageInfo pageInfo = change.getPageInfo();
         // Print the page information
         System.out.println("Page Number: " + pageInfo.getPageNumber());
         System.out.println("Page Width: " + pageInfo.getWidth());
         System.out.println("Page Height: " + pageInfo.getHeight());
     }
 }
 
````


## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [PageInfo(int pageNumber, int width, int height)](#PageInfo-int-int-int-) | Инициализирует новый экземпляр класса PageInfo, задавая pageNumber, ширину и высоту. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getWidth()](#getWidth--) | Получает ширину страницы |
|
|  | [setWidth(int value)](#setWidth-int-) | Устанавливает ширину страницы |
|
|  | [getHeight()](#getHeight--) | Получает высоту страницы |
|
|  | [setHeight(int value)](#setHeight-int-) | Устанавливает высоту страницы |
|
|  | [getPageNumber()](#getPageNumber--) | Получает номер страницы |
|
|  | [setPageNumber(int value)](#setPageNumber-int-) | Устанавливает номер страницы |
|
| [toString()](#toString--) |  |
### PageInfo(int pageNumber, int width, int height) {#PageInfo-int-int-int-}
```
public PageInfo(int pageNumber, int width, int height)
```


Инициализирует новый экземпляр класса PageInfo, задавая pageNumber, ширину и высоту.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | pageNumber | int | Номер страницы |
|
|  | ширина | int | Ширина страницы |
|
|  | высота | int | Высота страницы |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Получает ширину страницы


**Returns:**
int - ширина страницы

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Устанавливает ширину страницы


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | int | Ширина страницы |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Получает высоту страницы


**Returns:**
int - высота страницы

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Устанавливает высоту страницы


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | int | Высота страницы |
|

### getPageNumber() {#getPageNumber--}
```
public final int getPageNumber()
```


Получает номер страницы


**Returns:**
int - номер страницы

### setPageNumber(int value) {#setPageNumber-int-}
```
public final void setPageNumber(int value)
```


Устанавливает номер страницы


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | int | Номер страницы |
|

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
