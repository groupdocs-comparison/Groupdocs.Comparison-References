---
title: "StyleSettings"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "Этот класс представляет параметры стиля для форматирования текста."
type: docs
weight: 12
url: /ru/java/com.groupdocs.comparison.options.style/stylesettings/
---
**Inheritance:**
java.lang.Object
```
public class StyleSettings
```

Этот класс представляет параметры стиля для форматирования текста.


Используйте этот класс для настройки цвета шрифта, цвета выделения, атрибутов стиля (жирный, подчёркнутый, курсив, зачёркнутый),
строковых разделителей, оригинальных размеров и разделителей слов для текста.


Пример использования:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    StyleSettings styleSettings = new StyleSettings();
    styleSettings.setFontColor(Color.GREEN);
    styleSettings.setBold(true);
    styleSettings.setUnderline(true);

    final CompareOptions compareOptions = new CompareOptions();
    compareOptions.setInsertedItemStyle(styleSettings);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [StyleSettings()](#StyleSettings--) | Инициализирует новый экземпляр класса StyleSettings. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getFontColor()](#getFontColor--) | Получает цвет шрифта. |
|
|  | [setFontColor(Color value)](#setFontColor-java.awt.Color-) | Устанавливает цвет шрифта. |
|
|  | [getShapeColor()](#getShapeColor--) | Получает цвет фигуры. |
|
|  | [setShapeColor(Color value)](#setShapeColor-java.awt.Color-) | Устанавливает цвет фигуры. |
|
|  | [getHighlightColor()](#getHighlightColor--) | Получает цвет выделения. |
|
|  | [setHighlightColor(Color value)](#setHighlightColor-java.awt.Color-) | Устанавливает цвет выделения. |
|
|  | [isBold()](#isBold--) | Получает флаг, указывающий, будет ли текст полужирным или нет. |
|
|  | [setBold(boolean value)](#setBold-boolean-) | Устанавливает флаг, указывающий, должен ли текст быть полужирным или нет. |
|
|  | [isUnderline()](#isUnderline--) | Получает флаг, указывающий, будет ли текст подчёркнутым или нет. |
|
|  | [setUnderline(boolean value)](#setUnderline-boolean-) | Устанавливает флаг, указывающий, должен ли текст быть подчёркнутым или нет. |
|
|  | [isItalic()](#isItalic--) | Получает флаг, указывающий, будет ли текст курсивом или нет. |
|
|  | [setItalic(boolean value)](#setItalic-boolean-) | Устанавливает флаг, указывающий, должен ли текст быть курсивом или нет. |
|
|  | [isStrikethrough()](#isStrikethrough--) | Получает флаг, указывающий, будет ли текст зачёркнутым или нет. |
|
|  | [setStrikethrough(boolean value)](#setStrikethrough-boolean-) | Устанавливает флаг, указывающий, должен ли текст быть зачёркнутым или нет. |
|
|  | [getStartStringSeparator()](#getStartStringSeparator--) | Получает разделитель начальной строки. |
|
|  | [setStartStringSeparator(String value)](#setStartStringSeparator-java.lang.String-) | Устанавливает разделитель начальной строки. |
|
|  | [getEndStringSeparator()](#getEndStringSeparator--) | Получает разделитель конечной строки. |
|
|  | [setEndStringSeparator(String value)](#setEndStringSeparator-java.lang.String-) | Устанавливает разделитель конечной строки. |
|
|  | [getOriginalSize()](#getOriginalSize--) | Получает оригинальный размер сравниваемых документов. |
|
|  | [setOriginalSize(Size value)](#setOriginalSize-com.groupdocs.comparison.options.style.Size-) | Устанавливает оригинальный размер сравниваемых документов. |
|
|  | [getWordsSeparators()](#getWordsSeparators--) | Получает символы-разделители слов. |
|
|  | [setWordsSeparators(char[] value)](#setWordsSeparators-char---) | Устанавливает символы-разделители слов. |
|
### StyleSettings() {#StyleSettings--}
```
public StyleSettings()
```


Инициализирует новый экземпляр класса StyleSettings.


### getFontColor() {#getFontColor--}
```
public final Color getFontColor()
```


Получает цвет шрифта.


**Returns:**
java.awt.Color - цвет шрифта.

### setFontColor(Color value) {#setFontColor-java.awt.Color-}
```
public final void setFontColor(Color value)
```


Устанавливает цвет шрифта.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | java.awt.Color | Новый цвет шрифта. |
|

### getShapeColor() {#getShapeColor--}
```
public final Color getShapeColor()
```


Получает цвет фигуры.


**Returns:**
java.awt.Color - цвет формы.

### setShapeColor(Color value) {#setShapeColor-java.awt.Color-}
```
public final void setShapeColor(Color value)
```


Устанавливает цвет фигуры.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | java.awt.Color | Новый цвет формы. |
|

### getHighlightColor() {#getHighlightColor--}
```
public final Color getHighlightColor()
```


Получает цвет выделения.


**Returns:**
java.awt.Color - цвет выделения.

### setHighlightColor(Color value) {#setHighlightColor-java.awt.Color-}
```
public final void setHighlightColor(Color value)
```


Устанавливает цвет выделения.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | java.awt.Color | Новый цвет выделения. |
|

### isBold() {#isBold--}
```
public final boolean isBold()
```


Получает флаг, указывающий, будет ли текст полужирным или нет.


**Returns:**
boolean - true, если текст будет полужирным, иначе false.

### setBold(boolean value) {#setBold-boolean-}
```
public final void setBold(boolean value)
```


Устанавливает флаг, указывающий, должен ли текст быть полужирным или нет.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | boolean | true, если текст должен быть полужирным, иначе false. |
|

### isUnderline() {#isUnderline--}
```
public final boolean isUnderline()
```


Получает флаг, указывающий, будет ли текст подчёркнутым или нет.


**Returns:**
boolean - true, если текст будет подчёркнут, иначе false.

### setUnderline(boolean value) {#setUnderline-boolean-}
```
public final void setUnderline(boolean value)
```


Устанавливает флаг, указывающий, должен ли текст быть подчёркнутым или нет.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | boolean | true, если текст должен быть подчёркнут, иначе false. |
|

### isItalic() {#isItalic--}
```
public final boolean isItalic()
```


Получает флаг, указывающий, будет ли текст курсивом или нет.


**Returns:**
boolean - true, если текст будет курсивом, иначе false.

### setItalic(boolean value) {#setItalic-boolean-}
```
public final void setItalic(boolean value)
```


Устанавливает флаг, указывающий, должен ли текст быть курсивом или нет.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | boolean | true, если текст должен быть курсивом, иначе false. |
|

### isStrikethrough() {#isStrikethrough--}
```
public final boolean isStrikethrough()
```


Получает флаг, указывающий, будет ли текст зачёркнутым или нет.


**Returns:**
boolean - true, если текст будет зачёркнут, иначе false.

### setStrikethrough(boolean value) {#setStrikethrough-boolean-}
```
public final void setStrikethrough(boolean value)
```


Устанавливает флаг, указывающий, должен ли текст быть зачёркнутым или нет.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | boolean | true, если текст должен быть зачёркнут, иначе false. |
|

### getStartStringSeparator() {#getStartStringSeparator--}
```
public final String getStartStringSeparator()
```


Получает разделитель начальной строки.


**Returns:**
java.lang.String - разделитель начальной строки.

### setStartStringSeparator(String value) {#setStartStringSeparator-java.lang.String-}
```
public final void setStartStringSeparator(String value)
```


Устанавливает разделитель начальной строки.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | java.lang.String | Новый разделитель начальной строки. |
|

### getEndStringSeparator() {#getEndStringSeparator--}
```
public final String getEndStringSeparator()
```


Получает разделитель конечной строки.


**Returns:**
java.lang.String - разделитель конечной строки.

### setEndStringSeparator(String value) {#setEndStringSeparator-java.lang.String-}
```
public final void setEndStringSeparator(String value)
```


Устанавливает разделитель конечной строки.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | java.lang.String | Новый разделитель конечной строки. |
|

### getOriginalSize() {#getOriginalSize--}
```
public final Size getOriginalSize()
```


Получает оригинальный размер сравниваемых документов.


**Returns:**
[Size](../../com.groupdocs.comparison.options.style/size) - the original size of comparing documents.

### setOriginalSize(Size value) {#setOriginalSize-com.groupdocs.comparison.options.style.Size-}
```
public final void setOriginalSize(Size value)
```


Устанавливает оригинальный размер сравниваемых документов.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | [Size](../../com.groupdocs.comparison.options.style/size) | Новый оригинальный размер сравниваемых документов. |
|

### getWordsSeparators() {#getWordsSeparators--}
```
public final char[] getWordsSeparators()
```


Получает символы-разделители слов.


**Returns:**
char[] - разделители слов.

### setWordsSeparators(char[] value) {#setWordsSeparators-char---}
```
public final void setWordsSeparators(char[] value)
```


Устанавливает символы-разделители слов.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | char[] | Новые разделители слов. |
|

