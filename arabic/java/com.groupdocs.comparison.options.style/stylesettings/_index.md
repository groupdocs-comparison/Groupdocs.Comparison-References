---
title: "StyleSettings"
second_title: "GroupDocs.Comparison لـ Java API Reference"
description: "تمثل هذه الفئة إعدادات النمط لتنسيق النص."
type: docs
weight: 12
url: /ar/java/com.groupdocs.comparison.options.style/stylesettings/
---
**Inheritance:**
java.lang.Object
```
public class StyleSettings
```

تمثل هذه الفئة إعدادات النمط لتنسيق النص.


استخدم هذه الفئة لتخصيص لون الخط، لون التظليل، سمات النمط (عريض، تحته خط، مائل، شطب)،
فواصل السلسلة، الأحجام الأصلية، وفواصل الكلمات للنص.


مثال على الاستخدام:

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


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [StyleSettings()](#StyleSettings--) | يقوم بتهيئة نسخة جديدة من الفئة StyleSettings. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getFontColor()](#getFontColor--) | يحصل على لون الخط. |
|
|  | [setFontColor(Color value)](#setFontColor-java.awt.Color-) | يضبط لون الخط. |
|
|  | [getShapeColor()](#getShapeColor--) | يحصل على لون الشكل. |
|
|  | [setShapeColor(Color value)](#setShapeColor-java.awt.Color-) | يضبط لون الشكل. |
|
|  | [getHighlightColor()](#getHighlightColor--) | يحصل على لون التظليل. |
|
|  | [setHighlightColor(Color value)](#setHighlightColor-java.awt.Color-) | يضبط لون التظليل. |
|
|  | [isBold()](#isBold--) | يحصل على علم يوضح ما إذا كان النص سيكون عريضًا أم لا. |
|
|  | [setBold(boolean value)](#setBold-boolean-) | يضبط علمًا يوضح ما إذا كان النص يجب أن يكون عريضًا أم لا. |
|
|  | [isUnderline()](#isUnderline--) | يحصل على علم يوضح ما إذا كان النص سيكون تحته خط أم لا. |
|
|  | [setUnderline(boolean value)](#setUnderline-boolean-) | يضبط علمًا يوضح ما إذا كان النص يجب أن يكون تحته خط أم لا. |
|
|  | [isItalic()](#isItalic--) | يحصل على علم يوضح ما إذا كان النص سيكون مائلًا أم لا. |
|
|  | [setItalic(boolean value)](#setItalic-boolean-) | يضبط علمًا يوضح ما إذا كان النص يجب أن يكون مائلًا أم لا. |
|
|  | [isStrikethrough()](#isStrikethrough--) | يحصل على علم يوضح ما إذا كان النص سيكون مشطوبًا أم لا. |
|
|  | [setStrikethrough(boolean value)](#setStrikethrough-boolean-) | يضبط علمًا يوضح ما إذا كان النص يجب أن يكون مشطوبًا أم لا. |
|
|  | [getStartStringSeparator()](#getStartStringSeparator--) | يحصل على فاصل سلسلة البداية. |
|
|  | [setStartStringSeparator(String value)](#setStartStringSeparator-java.lang.String-) | يضبط فاصل سلسلة البداية. |
|
|  | [getEndStringSeparator()](#getEndStringSeparator--) | يحصل على فاصل سلسلة النهاية. |
|
|  | [setEndStringSeparator(String value)](#setEndStringSeparator-java.lang.String-) | يضبط فاصل سلسلة النهاية. |
|
|  | [getOriginalSize()](#getOriginalSize--) | يحصل على الحجم الأصلي للمستندات المقارنة. |
|
|  | [setOriginalSize(Size value)](#setOriginalSize-com.groupdocs.comparison.options.style.Size-) | يضبط الحجم الأصلي للمستندات المقارنة. |
|
|  | [getWordsSeparators()](#getWordsSeparators--) | يحصل على أحرف فاصل الكلمات. |
|
|  | [setWordsSeparators(char[] value)](#setWordsSeparators-char---) | يضبط أحرف فاصل الكلمات. |
|
### StyleSettings() {#StyleSettings--}
```
public StyleSettings()
```


يقوم بتهيئة نسخة جديدة من الفئة StyleSettings.


### getFontColor() {#getFontColor--}
```
public final Color getFontColor()
```


يحصل على لون الخط.


**Returns:**
java.awt.Color - لون الخط.

### setFontColor(Color value) {#setFontColor-java.awt.Color-}
```
public final void setFontColor(Color value)
```


يضبط لون الخط.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | java.awt.Color | لون الخط الجديد. |
|

### getShapeColor() {#getShapeColor--}
```
public final Color getShapeColor()
```


يحصل على لون الشكل.


**Returns:**
java.awt.Color - لون الشكل.

### setShapeColor(Color value) {#setShapeColor-java.awt.Color-}
```
public final void setShapeColor(Color value)
```


يضبط لون الشكل.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | java.awt.Color | لون الشكل الجديد. |
|

### getHighlightColor() {#getHighlightColor--}
```
public final Color getHighlightColor()
```


يحصل على لون التظليل.


**Returns:**
java.awt.Color - لون التمييز.

### setHighlightColor(Color value) {#setHighlightColor-java.awt.Color-}
```
public final void setHighlightColor(Color value)
```


يضبط لون التظليل.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | java.awt.Color | لون التمييز الجديد. |
|

### isBold() {#isBold--}
```
public final boolean isBold()
```


يحصل على علم يوضح ما إذا كان النص سيكون عريضًا أم لا.


**Returns:**
boolean - true إذا كان النص سيكون عريضًا، false خلاف ذلك.

### setBold(boolean value) {#setBold-boolean-}
```
public final void setBold(boolean value)
```


يضبط علمًا يوضح ما إذا كان النص يجب أن يكون عريضًا أم لا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | boolean | true إذا كان النص يجب أن يكون عريضًا، false خلاف ذلك. |
|

### isUnderline() {#isUnderline--}
```
public final boolean isUnderline()
```


يحصل على علم يوضح ما إذا كان النص سيكون تحته خط أم لا.


**Returns:**
boolean - true إذا كان النص سيكون مسطرًا، false خلاف ذلك.

### setUnderline(boolean value) {#setUnderline-boolean-}
```
public final void setUnderline(boolean value)
```


يضبط علمًا يوضح ما إذا كان النص يجب أن يكون تحته خط أم لا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | boolean | true إذا كان النص يجب أن يكون مسطرًا، false خلاف ذلك. |
|

### isItalic() {#isItalic--}
```
public final boolean isItalic()
```


يحصل على علم يوضح ما إذا كان النص سيكون مائلًا أم لا.


**Returns:**
boolean - true إذا كان النص سيكون مائلًا، false خلاف ذلك.

### setItalic(boolean value) {#setItalic-boolean-}
```
public final void setItalic(boolean value)
```


يضبط علمًا يوضح ما إذا كان النص يجب أن يكون مائلًا أم لا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | boolean | true إذا كان النص يجب أن يكون مائلًا، false خلاف ذلك. |
|

### isStrikethrough() {#isStrikethrough--}
```
public final boolean isStrikethrough()
```


يحصل على علم يوضح ما إذا كان النص سيكون مشطوبًا أم لا.


**Returns:**
boolean - true إذا كان النص سيكون مشطوبًا، false خلاف ذلك.

### setStrikethrough(boolean value) {#setStrikethrough-boolean-}
```
public final void setStrikethrough(boolean value)
```


يضبط علمًا يوضح ما إذا كان النص يجب أن يكون مشطوبًا أم لا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | boolean | true إذا كان النص يجب أن يكون مشطوبًا، false خلاف ذلك. |
|

### getStartStringSeparator() {#getStartStringSeparator--}
```
public final String getStartStringSeparator()
```


يحصل على فاصل سلسلة البداية.


**Returns:**
java.lang.String - فاصل سلسلة البداية.

### setStartStringSeparator(String value) {#setStartStringSeparator-java.lang.String-}
```
public final void setStartStringSeparator(String value)
```


يضبط فاصل سلسلة البداية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | java.lang.String | فاصل سلسلة البداية الجديد. |
|

### getEndStringSeparator() {#getEndStringSeparator--}
```
public final String getEndStringSeparator()
```


يحصل على فاصل سلسلة النهاية.


**Returns:**
java.lang.String - فاصل سلسلة النهاية.

### setEndStringSeparator(String value) {#setEndStringSeparator-java.lang.String-}
```
public final void setEndStringSeparator(String value)
```


يضبط فاصل سلسلة النهاية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | java.lang.String | فاصل سلسلة النهاية الجديد. |
|

### getOriginalSize() {#getOriginalSize--}
```
public final Size getOriginalSize()
```


يحصل على الحجم الأصلي للمستندات المقارنة.


**Returns:**
[Size](../../com.groupdocs.comparison.options.style/size) - the original size of comparing documents.

### setOriginalSize(Size value) {#setOriginalSize-com.groupdocs.comparison.options.style.Size-}
```
public final void setOriginalSize(Size value)
```


يضبط الحجم الأصلي للمستندات المقارنة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [Size](../../com.groupdocs.comparison.options.style/size) | الحجم الأصلي الجديد للمستندات المقارنة. |
|

### getWordsSeparators() {#getWordsSeparators--}
```
public final char[] getWordsSeparators()
```


يحصل على أحرف فاصل الكلمات.


**Returns:**
char[] - فواصل الكلمات.

### setWordsSeparators(char[] value) {#setWordsSeparators-char---}
```
public final void setWordsSeparators(char[] value)
```


يضبط أحرف فاصل الكلمات.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | char[] | فواصل الكلمات الجديدة. |
|

