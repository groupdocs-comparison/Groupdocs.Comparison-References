---
title: "ChangeInfo"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "Класс ChangeInfo представляет информацию о конкретном изменении в сравнении документов."
type: docs
weight: 10
url: /ru/java/com.groupdocs.comparison.result/changeinfo/
---
**Inheritance:**
java.lang.Object
```
public class ChangeInfo
```

Класс ChangeInfo представляет информацию о конкретном изменении в сравнении документов.


Он предоставляет детали, такие как тип изменения, затронутая область и содержимое до и после изменения.
Используйте этот класс для получения информации о отдельных изменениях в результате сравнения.


Пример использования:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     comparer.compare(resultFile);
     // Get a list of changes from the comparison result
     ChangeInfo[] changes = comparer.getChanges();
     // Iterate through the changes and retrieve information
     for (ChangeInfo change : changes) {
         ChangeType changeType = change.getType();
         String componentType = change.getComponentType();
         PageInfo pageInfo = change.getPageInfo();
         // Process the change information as needed
         // ...
     }
 }
 
````


## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ChangeInfo()](#ChangeInfo--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getRow()](#getRow--) |  |
| [setRow(Integer row)](#setRow-java.lang.Integer-) |  |
| [getColumn()](#getColumn--) |  |
| [setColumn(Integer column)](#setColumn-java.lang.Integer-) |  |
| [getColumnHeader()](#getColumnHeader--) |  |
| [setColumnHeader(String columnHeader)](#setColumnHeader-java.lang.String-) |  |
|  | [getId()](#getId--) | Получает уникальный идентификатор изменения. |
|
|  | [setId(int value)](#setId-int-) | Устанавливает уникальный идентификатор изменения. |
|
|  | [getComparisonAction()](#getComparisonAction--) | Получает действие, которое будет применено к изменению. |
|
|  | [setComparisonAction(ComparisonAction value)](#setComparisonAction-com.groupdocs.comparison.result.ComparisonAction-) | Устанавливает действие, которое должно быть применено к изменению. |
|
|  | [getPageInfo()](#getPageInfo--) | Получает информацию о странице, на которой найдено текущее изменение. |
|
|  | [setPageInfo(PageInfo value)](#setPageInfo-com.groupdocs.comparison.result.PageInfo-) | Устанавливает информацию о странице, на которой найдено текущее изменение. |
|
|  | [getBox()](#getBox--) | Получает координаты изменённого элемента на странице. |
|
|  | [setBox(Rectangle value)](#setBox-com.groupdocs.comparison.result.Rectangle-) | Устанавливает координаты изменённого элемента на странице. |
|
|  | [getText()](#getText--) | Получает текстовое значение изменения. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Устанавливает текстовое значение изменения. |
|
|  | [getStyleChanges()](#getStyleChanges--) | Получает список изменений стиля. |
|
|  | [setStyleChanges(List<StyleChangeInfo> value)](#setStyleChanges-java.util.List-com.groupdocs.comparison.result.StyleChangeInfo--) | Устанавливает список изменений стиля. |
|
|  | [getAuthors()](#getAuthors--) | Получает список авторов. |
|
|  | [setAuthors(List<String> value)](#setAuthors-java.util.List-java.lang.String--) | Устанавливает список авторов. |
|
|  | [getType()](#getType--) | Получает тип изменения, представленный перечислением [ChangeType](../../com.groupdocs.comparison.result/changetype). |
|
|  | [getTargetText()](#getTargetText--) | Получает изменённый текст из целевого документа. |
|
|  | [setTargetText(String value)](#setTargetText-java.lang.String-) | Устанавливает изменённый текст из целевого документа. |
|
|  | [getSourceText()](#getSourceText--) | Получает изменённый текст из исходного документа. |
|
|  | [setSourceText(String value)](#setSourceText-java.lang.String-) | Устанавливает изменённый текст из исходного документа. |
|
|  | [getComponentType()](#getComponentType--) | Получает тип изменённого компонента. |
|
|  | [setComponentType(String value)](#setComponentType-java.lang.String-) | Устанавливает тип изменённого компонента. |
|
| [toString()](#toString--) |  |
### ChangeInfo() {#ChangeInfo--}
```
public ChangeInfo()
```


### getRow() {#getRow--}
```
public Integer getRow()
```




**Returns:**
java.lang.Integer
### setRow(Integer row) {#setRow-java.lang.Integer-}
```
public void setRow(Integer row)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| строка | java.lang.Integer |  |

### getColumn() {#getColumn--}
```
public Integer getColumn()
```




**Returns:**
java.lang.Integer
### setColumn(Integer column) {#setColumn-java.lang.Integer-}
```
public void setColumn(Integer column)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| столбец | java.lang.Integer |  |

### getColumnHeader() {#getColumnHeader--}
```
public String getColumnHeader()
```




**Returns:**
java.lang.String
### setColumnHeader(String columnHeader) {#setColumnHeader-java.lang.String-}
```
public void setColumnHeader(String columnHeader)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| columnHeader | java.lang.String |  |

### getId() {#getId--}
```
public final int getId()
```


Получает уникальный идентификатор изменения.


**Returns:**
int - идентификатор изменения

### setId(int value) {#setId-int-}
```
public final void setId(int value)
```


Устанавливает уникальный идентификатор изменения.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | int | Идентификатор изменения |
|

### getComparisonAction() {#getComparisonAction--}
```
public final ComparisonAction getComparisonAction()
```


Получает действие, которое будет применено к изменению.
Действие ([ComparisonAction.ACCEPT](../../com.groupdocs.comparison.result/comparisonaction#ACCEPT) или [ComparisonAction.REJECT](../../com.groupdocs.comparison.result/comparisonaction#REJECT)) сообщает сравниванию, что делать с этим изменением.


**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) - the action that will be applied to the change

### setComparisonAction(ComparisonAction value) {#setComparisonAction-com.groupdocs.comparison.result.ComparisonAction-}
```
public final void setComparisonAction(ComparisonAction value)
```


Устанавливает действие, которое должно быть применено к изменению.
Действие ([ComparisonAction.ACCEPT](../../com.groupdocs.comparison.result/comparisonaction#ACCEPT) или [ComparisonAction.REJECT](../../com.groupdocs.comparison.result/comparisonaction#REJECT)) сообщает сравниванию, что делать с этим изменением.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | [ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) | Действие, которое следует применить к изменению |
|

### getPageInfo() {#getPageInfo--}
```
public final PageInfo getPageInfo()
```


Получает информацию о странице, на которой найдено текущее изменение.


**Returns:**
[PageInfo](../../com.groupdocs.comparison.result/pageinfo) - information about the page

### setPageInfo(PageInfo value) {#setPageInfo-com.groupdocs.comparison.result.PageInfo-}
```
public final void setPageInfo(PageInfo value)
```


Устанавливает информацию о странице, на которой найдено текущее изменение.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | [PageInfo](../../com.groupdocs.comparison.result/pageinfo) | Информация о странице |
|

### getBox() {#getBox--}
```
public final Rectangle getBox()
```


Получает координаты изменённого элемента на странице.


**Returns:**
[Rectangle](../../com.groupdocs.comparison.result/rectangle) - coordinates of changed element

### setBox(Rectangle value) {#setBox-com.groupdocs.comparison.result.Rectangle-}
```
public final void setBox(Rectangle value)
```


Устанавливает координаты изменённого элемента на странице.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | [Rectangle](../../com.groupdocs.comparison.result/rectangle) | Координаты изменённого элемента, не null |
|

### getText() {#getText--}
```
public final String getText()
```


Получает текстовое значение изменения.


**Returns:**
java.lang.String - текстовое значение изменения

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Устанавливает текстовое значение изменения.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | java.lang.String | Текстовое значение изменения |
|

### getStyleChanges() {#getStyleChanges--}
```
public final List<StyleChangeInfo> getStyleChanges()
```


Получает список изменений стиля.


**Returns:**
java.util.List<com.groupdocs.comparison.result.StyleChangeInfo> - список изменений стилей

### setStyleChanges(List<StyleChangeInfo> value) {#setStyleChanges-java.util.List-com.groupdocs.comparison.result.StyleChangeInfo--}
```
public final void setStyleChanges(List<StyleChangeInfo> value)
```


Устанавливает список изменений стиля.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | java.util.List<com.groupdocs.comparison.result.StyleChangeInfo> | Список изменений стилей |
|

### getAuthors() {#getAuthors--}
```
public final List<String> getAuthors()
```


Получает список авторов.


**Returns:**
java.util.List<java.lang.String> - список авторов

### setAuthors(List<String> value) {#setAuthors-java.util.List-java.lang.String--}
```
public final void setAuthors(List<String> value)
```


Устанавливает список авторов.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | java.util.List<java.lang.String> | Список авторов |
|

### getType() {#getType--}
```
public final ChangeType getType()
```


Получает тип изменения, представленный перечислением [ChangeType](../../com.groupdocs.comparison.result/changetype).


**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - the type of the change

### getTargetText() {#getTargetText--}
```
public String getTargetText()
```


Получает изменённый текст из целевого документа.


**Returns:**
java.lang.String - изменённый текст

### setTargetText(String value) {#setTargetText-java.lang.String-}
```
public void setTargetText(String value)
```


Устанавливает изменённый текст из целевого документа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | java.lang.String | Изменённый текст |
|

### getSourceText() {#getSourceText--}
```
public String getSourceText()
```


Получает изменённый текст из исходного документа.


**Returns:**
java.lang.String - изменённый текст

### setSourceText(String value) {#setSourceText-java.lang.String-}
```
public void setSourceText(String value)
```


Устанавливает изменённый текст из исходного документа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | java.lang.String | Изменённый текст |
|

### getComponentType() {#getComponentType--}
```
public String getComponentType()
```


Получает тип изменённого компонента.


**Returns:**
java.lang.String - тип изменённого компонента

### setComponentType(String value) {#setComponentType-java.lang.String-}
```
public void setComponentType(String value)
```


Устанавливает тип изменённого компонента.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | java.lang.String | Тип изменённого компонента |
|

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
