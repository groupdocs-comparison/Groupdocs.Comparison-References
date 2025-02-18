---
title: StyleSettings
second_title: GroupDocs.Comparison for Java API Reference
description: This class represents style settings for text formatting.
type: docs
weight: 12
url: /java/com.groupdocs.comparison.options.style/stylesettings/
---
**Inheritance:**
java.lang.Object
```
public class StyleSettings
```

This class represents style settings for text formatting.

Use this class to customize the font color, highlight color, style attributes (bold, underline, italic, strikethrough), string separators, original sizes, and word separators for text.

Example usage:

```

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
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [StyleSettings()](#StyleSettings--) | Initializes a new instance of the StyleSettings class. |
## Methods

| Method | Description |
| --- | --- |
| [getFontColor()](#getFontColor--) | Gets the font color. |
| [setFontColor(Color value)](#setFontColor-java.awt.Color-) | Sets the font color. |
| [getShapeColor()](#getShapeColor--) | Gets the shape color. |
| [setShapeColor(Color value)](#setShapeColor-java.awt.Color-) | Sets the shape color. |
| [getHighlightColor()](#getHighlightColor--) | Gets the highlight color. |
| [setHighlightColor(Color value)](#setHighlightColor-java.awt.Color-) | Sets the highlight color. |
| [isBold()](#isBold--) | Gets a flag that indicates whether the text will be bold or not. |
| [setBold(boolean value)](#setBold-boolean-) | Sets a flag that indicates whether the text should be bold or not. |
| [isUnderline()](#isUnderline--) | Gets a flag that indicates whether the text will be underlined or not. |
| [setUnderline(boolean value)](#setUnderline-boolean-) | Sets a flag that indicates whether the text should be underlined or not. |
| [isItalic()](#isItalic--) | Gets a flag that indicates whether the text will be italic or not. |
| [setItalic(boolean value)](#setItalic-boolean-) | Sets a flag that indicates whether the text should be italic or not. |
| [isStrikethrough()](#isStrikethrough--) | Gets a flag that indicates whether the text will be strike through or not. |
| [setStrikethrough(boolean value)](#setStrikethrough-boolean-) | Sets a flag that indicates whether the text should be strike through or not. |
| [getStartStringSeparator()](#getStartStringSeparator--) | Gets the start string separator. |
| [setStartStringSeparator(String value)](#setStartStringSeparator-java.lang.String-) | Sets the start string separator. |
| [getEndStringSeparator()](#getEndStringSeparator--) | Gets the end string separator. |
| [setEndStringSeparator(String value)](#setEndStringSeparator-java.lang.String-) | Sets the end string separator. |
| [getOriginalSize()](#getOriginalSize--) | Gets the original size of comparing documents. |
| [setOriginalSize(Size value)](#setOriginalSize-com.groupdocs.comparison.options.style.Size-) | Sets the original size of comparing documents. |
| [getWordsSeparators()](#getWordsSeparators--) | Gets the word separator chars. |
| [setWordsSeparators(char[] value)](#setWordsSeparators-char---) | Sets the word separator chars. |
### StyleSettings() {#StyleSettings--}
```
public StyleSettings()
```


Initializes a new instance of the StyleSettings class.

### getFontColor() {#getFontColor--}
```
public final Color getFontColor()
```


Gets the font color.

**Returns:**
java.awt.Color - the font color.
### setFontColor(Color value) {#setFontColor-java.awt.Color-}
```
public final void setFontColor(Color value)
```


Sets the font color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.Color | The new font color. |

### getShapeColor() {#getShapeColor--}
```
public final Color getShapeColor()
```


Gets the shape color.

**Returns:**
java.awt.Color - the shape color.
### setShapeColor(Color value) {#setShapeColor-java.awt.Color-}
```
public final void setShapeColor(Color value)
```


Sets the shape color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.Color | The new shape color. |

### getHighlightColor() {#getHighlightColor--}
```
public final Color getHighlightColor()
```


Gets the highlight color.

**Returns:**
java.awt.Color - the highlight color.
### setHighlightColor(Color value) {#setHighlightColor-java.awt.Color-}
```
public final void setHighlightColor(Color value)
```


Sets the highlight color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.Color | The new highlight color. |

### isBold() {#isBold--}
```
public final boolean isBold()
```


Gets a flag that indicates whether the text will be bold or not.

**Returns:**
boolean - true if the text will be bold, false otherwise.
### setBold(boolean value) {#setBold-boolean-}
```
public final void setBold(boolean value)
```


Sets a flag that indicates whether the text should be bold or not.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | true if the text should be bold, false otherwise. |

### isUnderline() {#isUnderline--}
```
public final boolean isUnderline()
```


Gets a flag that indicates whether the text will be underlined or not.

**Returns:**
boolean - true if the text will be underlined, false otherwise.
### setUnderline(boolean value) {#setUnderline-boolean-}
```
public final void setUnderline(boolean value)
```


Sets a flag that indicates whether the text should be underlined or not.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | true if the text should be underlined, false otherwise. |

### isItalic() {#isItalic--}
```
public final boolean isItalic()
```


Gets a flag that indicates whether the text will be italic or not.

**Returns:**
boolean - true if the text will be italic, false otherwise.
### setItalic(boolean value) {#setItalic-boolean-}
```
public final void setItalic(boolean value)
```


Sets a flag that indicates whether the text should be italic or not.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | true if the text should be italic, false otherwise. |

### isStrikethrough() {#isStrikethrough--}
```
public final boolean isStrikethrough()
```


Gets a flag that indicates whether the text will be strike through or not.

**Returns:**
boolean - true if the text will be strike through, false otherwise.
### setStrikethrough(boolean value) {#setStrikethrough-boolean-}
```
public final void setStrikethrough(boolean value)
```


Sets a flag that indicates whether the text should be strike through or not.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | true if the text should be strike through, false otherwise. |

### getStartStringSeparator() {#getStartStringSeparator--}
```
public final String getStartStringSeparator()
```


Gets the start string separator.

**Returns:**
java.lang.String - the start string separator.
### setStartStringSeparator(String value) {#setStartStringSeparator-java.lang.String-}
```
public final void setStartStringSeparator(String value)
```


Sets the start string separator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The new start string separator. |

### getEndStringSeparator() {#getEndStringSeparator--}
```
public final String getEndStringSeparator()
```


Gets the end string separator.

**Returns:**
java.lang.String - the end string separator.
### setEndStringSeparator(String value) {#setEndStringSeparator-java.lang.String-}
```
public final void setEndStringSeparator(String value)
```


Sets the end string separator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The new end string separator. |

### getOriginalSize() {#getOriginalSize--}
```
public final Size getOriginalSize()
```


Gets the original size of comparing documents.

**Returns:**
[Size](../../com.groupdocs.comparison.options.style/size) - the original size of comparing documents.
### setOriginalSize(Size value) {#setOriginalSize-com.groupdocs.comparison.options.style.Size-}
```
public final void setOriginalSize(Size value)
```


Sets the original size of comparing documents.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Size](../../com.groupdocs.comparison.options.style/size) | The new original size of comparing documents. |

### getWordsSeparators() {#getWordsSeparators--}
```
public final char[] getWordsSeparators()
```


Gets the word separator chars.

**Returns:**
char[] - the word separators.
### setWordsSeparators(char[] value) {#setWordsSeparators-char---}
```
public final void setWordsSeparators(char[] value)
```


Sets the word separator chars.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char[] | The new word separators. |

