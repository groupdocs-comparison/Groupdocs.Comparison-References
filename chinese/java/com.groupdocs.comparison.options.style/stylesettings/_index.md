---
title: "StyleSettings"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "此类表示文本格式的样式设置。"
type: docs
weight: 12
url: /zh/java/com.groupdocs.comparison.options.style/stylesettings/
---
**Inheritance:**
java.lang.Object
```
public class StyleSettings
```

此类表示文本格式的样式设置。


使用此类来自定义字体颜色、突出显示颜色、样式属性（粗体、下划线、斜体、删除线），
字符串分隔符、原始尺寸以及文本的单词分隔符。


示例用法：

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


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [StyleSettings()](#StyleSettings--) | 初始化 StyleSettings 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getFontColor()](#getFontColor--) | 获取字体颜色。 |
|
|  | [setFontColor(Color value)](#setFontColor-java.awt.Color-) | 设置字体颜色。 |
|
|  | [getShapeColor()](#getShapeColor--) | 获取形状颜色。 |
|
|  | [setShapeColor(Color value)](#setShapeColor-java.awt.Color-) | 设置形状颜色。 |
|
|  | [getHighlightColor()](#getHighlightColor--) | 获取突出显示颜色。 |
|
|  | [setHighlightColor(Color value)](#setHighlightColor-java.awt.Color-) | 设置突出显示颜色。 |
|
|  | [isBold()](#isBold--) | 获取指示文本是否加粗的标志。 |
|
|  | [setBold(boolean value)](#setBold-boolean-) | 设置指示文本是否加粗的标志。 |
|
|  | [isUnderline()](#isUnderline--) | 获取指示文本是否带下划线的标志。 |
|
|  | [setUnderline(boolean value)](#setUnderline-boolean-) | 设置指示文本是否带下划线的标志。 |
|
|  | [isItalic()](#isItalic--) | 获取指示文本是否斜体的标志。 |
|
|  | [setItalic(boolean value)](#setItalic-boolean-) | 设置指示文本是否斜体的标志。 |
|
|  | [isStrikethrough()](#isStrikethrough--) | 获取指示文本是否删除线的标志。 |
|
|  | [setStrikethrough(boolean value)](#setStrikethrough-boolean-) | 设置指示文本是否删除线的标志。 |
|
|  | [getStartStringSeparator()](#getStartStringSeparator--) | 获取起始字符串分隔符。 |
|
|  | [setStartStringSeparator(String value)](#setStartStringSeparator-java.lang.String-) | 设置起始字符串分隔符。 |
|
|  | [getEndStringSeparator()](#getEndStringSeparator--) | 获取结束字符串分隔符。 |
|
|  | [setEndStringSeparator(String value)](#setEndStringSeparator-java.lang.String-) | 设置结束字符串分隔符。 |
|
|  | [getOriginalSize()](#getOriginalSize--) | 获取比较文档的原始大小。 |
|
|  | [setOriginalSize(Size value)](#setOriginalSize-com.groupdocs.comparison.options.style.Size-) | 设置比较文档的原始大小。 |
|
|  | [getWordsSeparators()](#getWordsSeparators--) | 获取单词分隔字符。 |
|
|  | [setWordsSeparators(char[] value)](#setWordsSeparators-char---) | 设置单词分隔字符。 |
|
### StyleSettings() {#StyleSettings--}
```
public StyleSettings()
```


初始化 StyleSettings 类的新实例。


### getFontColor() {#getFontColor--}
```
public final Color getFontColor()
```


获取字体颜色。


**Returns:**
java.awt.Color - 字体颜色。

### setFontColor(Color value) {#setFontColor-java.awt.Color-}
```
public final void setFontColor(Color value)
```


设置字体颜色。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.awt.Color | 新的字体颜色。 |
|

### getShapeColor() {#getShapeColor--}
```
public final Color getShapeColor()
```


获取形状颜色。


**Returns:**
java.awt.Color - 形状颜色。

### setShapeColor(Color value) {#setShapeColor-java.awt.Color-}
```
public final void setShapeColor(Color value)
```


设置形状颜色。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.awt.Color | 新的形状颜色。 |
|

### getHighlightColor() {#getHighlightColor--}
```
public final Color getHighlightColor()
```


获取突出显示颜色。


**Returns:**
java.awt.Color - 高亮颜色。

### setHighlightColor(Color value) {#setHighlightColor-java.awt.Color-}
```
public final void setHighlightColor(Color value)
```


设置突出显示颜色。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.awt.Color | 新的高亮颜色。 |
|

### isBold() {#isBold--}
```
public final boolean isBold()
```


获取指示文本是否加粗的标志。


**Returns:**
boolean - 如果文本将加粗，则为 true；否则为 false。

### setBold(boolean value) {#setBold-boolean-}
```
public final void setBold(boolean value)
```


设置指示文本是否加粗的标志。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | 如果文本应加粗，则为 true；否则为 false。 |
|

### isUnderline() {#isUnderline--}
```
public final boolean isUnderline()
```


获取指示文本是否带下划线的标志。


**Returns:**
boolean - 如果文本将加下划线，则为 true；否则为 false。

### setUnderline(boolean value) {#setUnderline-boolean-}
```
public final void setUnderline(boolean value)
```


设置指示文本是否带下划线的标志。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | 如果文本应加下划线，则为 true；否则为 false。 |
|

### isItalic() {#isItalic--}
```
public final boolean isItalic()
```


获取指示文本是否斜体的标志。


**Returns:**
boolean - 如果文本将斜体，则为 true；否则为 false。

### setItalic(boolean value) {#setItalic-boolean-}
```
public final void setItalic(boolean value)
```


设置指示文本是否斜体的标志。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | 如果文本应斜体，则为 true；否则为 false。 |
|

### isStrikethrough() {#isStrikethrough--}
```
public final boolean isStrikethrough()
```


获取指示文本是否删除线的标志。


**Returns:**
boolean - 如果文本将删除线，则为 true；否则为 false。

### setStrikethrough(boolean value) {#setStrikethrough-boolean-}
```
public final void setStrikethrough(boolean value)
```


设置指示文本是否删除线的标志。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | 如果文本应删除线，则为 true；否则为 false。 |
|

### getStartStringSeparator() {#getStartStringSeparator--}
```
public final String getStartStringSeparator()
```


获取起始字符串分隔符。


**Returns:**
java.lang.String - 起始字符串分隔符。

### setStartStringSeparator(String value) {#setStartStringSeparator-java.lang.String-}
```
public final void setStartStringSeparator(String value)
```


设置起始字符串分隔符。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.lang.String | 新的起始字符串分隔符。 |
|

### getEndStringSeparator() {#getEndStringSeparator--}
```
public final String getEndStringSeparator()
```


获取结束字符串分隔符。


**Returns:**
java.lang.String - 结束字符串分隔符。

### setEndStringSeparator(String value) {#setEndStringSeparator-java.lang.String-}
```
public final void setEndStringSeparator(String value)
```


设置结束字符串分隔符。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.lang.String | 新的结束字符串分隔符。 |
|

### getOriginalSize() {#getOriginalSize--}
```
public final Size getOriginalSize()
```


获取比较文档的原始大小。


**Returns:**
[Size](../../com.groupdocs.comparison.options.style/size) - the original size of comparing documents.

### setOriginalSize(Size value) {#setOriginalSize-com.groupdocs.comparison.options.style.Size-}
```
public final void setOriginalSize(Size value)
```


设置比较文档的原始大小。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [Size](../../com.groupdocs.comparison.options.style/size) | 新的比较文档的原始大小。 |
|

### getWordsSeparators() {#getWordsSeparators--}
```
public final char[] getWordsSeparators()
```


获取单词分隔字符。


**Returns:**
char[] - 单词分隔符。

### setWordsSeparators(char[] value) {#setWordsSeparators-char---}
```
public final void setWordsSeparators(char[] value)
```


设置单词分隔字符。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | char[] | 新的单词分隔符。 |
|

