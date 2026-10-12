---
title: "StyleSettings"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "यह क्लास टेक्स्ट फ़ॉर्मेटिंग के लिए स्टाइल सेटिंग्स को दर्शाती है।"
type: docs
weight: 12
url: /hi/java/com.groupdocs.comparison.options.style/stylesettings/
---
**Inheritance:**
java.lang.Object
```
public class StyleSettings
```

यह क्लास टेक्स्ट फ़ॉर्मेटिंग के लिए स्टाइल सेटिंग्स को दर्शाती है।


इस क्लास का उपयोग फ़ॉन्ट रंग, हाइलाइट रंग, शैली गुण (bold, underline, italic, strikethrough), को अनुकूलित करने के लिए करें,
स्ट्रिंग विभाजक, मूल आकार, और टेक्स्ट के लिए शब्द विभाजक।


उदाहरण उपयोग:

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


## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [StyleSettings()](#StyleSettings--) | StyleSettings क्लास का एक नया इंस्टेंस प्रारंभ करता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getFontColor()](#getFontColor--) | फ़ॉन्ट रंग प्राप्त करता है। |
|
|  | [setFontColor(Color value)](#setFontColor-java.awt.Color-) | फ़ॉन्ट रंग सेट करता है। |
|
|  | [getShapeColor()](#getShapeColor--) | आकार का रंग प्राप्त करता है। |
|
|  | [setShapeColor(Color value)](#setShapeColor-java.awt.Color-) | आकार का रंग सेट करता है। |
|
|  | [getHighlightColor()](#getHighlightColor--) | हाइलाइट रंग प्राप्त करता है। |
|
|  | [setHighlightColor(Color value)](#setHighlightColor-java.awt.Color-) | हाइलाइट रंग सेट करता है। |
|
|  | [isBold()](#isBold--) | एक फ़्लैग प्राप्त करता है जो दर्शाता है कि टेक्स्ट बोल्ड होगा या नहीं। |
|
|  | [setBold(boolean value)](#setBold-boolean-) | एक फ़्लैग सेट करता है जो दर्शाता है कि टेक्स्ट बोल्ड होना चाहिए या नहीं। |
|
|  | [isUnderline()](#isUnderline--) | एक फ़्लैग प्राप्त करता है जो दर्शाता है कि टेक्स्ट अंडरलाइन होगा या नहीं। |
|
|  | [setUnderline(boolean value)](#setUnderline-boolean-) | एक फ़्लैग सेट करता है जो दर्शाता है कि टेक्स्ट अंडरलाइन होना चाहिए या नहीं। |
|
|  | [isItalic()](#isItalic--) | एक फ़्लैग प्राप्त करता है जो दर्शाता है कि टेक्स्ट इटैलिक होगा या नहीं। |
|
|  | [setItalic(boolean value)](#setItalic-boolean-) | एक फ़्लैग सेट करता है जो दर्शाता है कि टेक्स्ट इटैलिक होना चाहिए या नहीं। |
|
|  | [isStrikethrough()](#isStrikethrough--) | एक फ़्लैग प्राप्त करता है जो दर्शाता है कि टेक्स्ट स्ट्राइक थ्रू होगा या नहीं। |
|
|  | [setStrikethrough(boolean value)](#setStrikethrough-boolean-) | एक फ़्लैग सेट करता है जो दर्शाता है कि टेक्स्ट स्ट्राइक थ्रू होना चाहिए या नहीं। |
|
|  | [getStartStringSeparator()](#getStartStringSeparator--) | स्टार्ट स्ट्रिंग सेपरेटर प्राप्त करता है। |
|
|  | [setStartStringSeparator(String value)](#setStartStringSeparator-java.lang.String-) | स्टार्ट स्ट्रिंग सेपरेटर सेट करता है। |
|
|  | [getEndStringSeparator()](#getEndStringSeparator--) | एंड स्ट्रिंग सेपरेटर प्राप्त करता है। |
|
|  | [setEndStringSeparator(String value)](#setEndStringSeparator-java.lang.String-) | एंड स्ट्रिंग सेपरेटर सेट करता है। |
|
|  | [getOriginalSize()](#getOriginalSize--) | तुलना दस्तावेज़ों का मूल आकार प्राप्त करता है। |
|
|  | [setOriginalSize(Size value)](#setOriginalSize-com.groupdocs.comparison.options.style.Size-) | तुलना दस्तावेज़ों का मूल आकार सेट करता है। |
|
|  | [getWordsSeparators()](#getWordsSeparators--) | शब्द सेपरेटर अक्षर प्राप्त करता है। |
|
|  | [setWordsSeparators(char[] value)](#setWordsSeparators-char---) | शब्द सेपरेटर अक्षर सेट करता है। |
|
### StyleSettings() {#StyleSettings--}
```
public StyleSettings()
```


StyleSettings क्लास का एक नया इंस्टेंस प्रारंभ करता है।


### getFontColor() {#getFontColor--}
```
public final Color getFontColor()
```


फ़ॉन्ट रंग प्राप्त करता है।


**Returns:**
java.awt.Color - फ़ॉन्ट रंग।

### setFontColor(Color value) {#setFontColor-java.awt.Color-}
```
public final void setFontColor(Color value)
```


फ़ॉन्ट रंग सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | java.awt.Color | नया फ़ॉन्ट रंग। |
|

### getShapeColor() {#getShapeColor--}
```
public final Color getShapeColor()
```


आकार का रंग प्राप्त करता है।


**Returns:**
java.awt.Color - आकार का रंग।

### setShapeColor(Color value) {#setShapeColor-java.awt.Color-}
```
public final void setShapeColor(Color value)
```


आकार का रंग सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | java.awt.Color | नया आकार का रंग। |
|

### getHighlightColor() {#getHighlightColor--}
```
public final Color getHighlightColor()
```


हाइलाइट रंग प्राप्त करता है।


**Returns:**
java.awt.Color - हाइलाइट रंग।

### setHighlightColor(Color value) {#setHighlightColor-java.awt.Color-}
```
public final void setHighlightColor(Color value)
```


हाइलाइट रंग सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | java.awt.Color | नया हाइलाइट रंग। |
|

### isBold() {#isBold--}
```
public final boolean isBold()
```


एक फ़्लैग प्राप्त करता है जो दर्शाता है कि टेक्स्ट बोल्ड होगा या नहीं।


**Returns:**
boolean - यदि टेक्स्ट बोल्ड होगा तो true, अन्यथा false।

### setBold(boolean value) {#setBold-boolean-}
```
public final void setBold(boolean value)
```


एक फ़्लैग सेट करता है जो दर्शाता है कि टेक्स्ट बोल्ड होना चाहिए या नहीं।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | boolean | यदि टेक्स्ट बोल्ड होना चाहिए तो true, अन्यथा false। |
|

### isUnderline() {#isUnderline--}
```
public final boolean isUnderline()
```


एक फ़्लैग प्राप्त करता है जो दर्शाता है कि टेक्स्ट अंडरलाइन होगा या नहीं।


**Returns:**
boolean - यदि टेक्स्ट अंडरलाइन होगा तो true, अन्यथा false।

### setUnderline(boolean value) {#setUnderline-boolean-}
```
public final void setUnderline(boolean value)
```


एक फ़्लैग सेट करता है जो दर्शाता है कि टेक्स्ट अंडरलाइन होना चाहिए या नहीं।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | boolean | यदि टेक्स्ट अंडरलाइन होना चाहिए तो true, अन्यथा false। |
|

### isItalic() {#isItalic--}
```
public final boolean isItalic()
```


एक फ़्लैग प्राप्त करता है जो दर्शाता है कि टेक्स्ट इटैलिक होगा या नहीं।


**Returns:**
boolean - यदि टेक्स्ट इटैलिक होगा तो true, अन्यथा false।

### setItalic(boolean value) {#setItalic-boolean-}
```
public final void setItalic(boolean value)
```


एक फ़्लैग सेट करता है जो दर्शाता है कि टेक्स्ट इटैलिक होना चाहिए या नहीं।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | boolean | यदि टेक्स्ट इटैलिक होना चाहिए तो true, अन्यथा false। |
|

### isStrikethrough() {#isStrikethrough--}
```
public final boolean isStrikethrough()
```


एक फ़्लैग प्राप्त करता है जो दर्शाता है कि टेक्स्ट स्ट्राइक थ्रू होगा या नहीं।


**Returns:**
boolean - यदि टेक्स्ट स्ट्राइक थ्रू होगा तो true, अन्यथा false।

### setStrikethrough(boolean value) {#setStrikethrough-boolean-}
```
public final void setStrikethrough(boolean value)
```


एक फ़्लैग सेट करता है जो दर्शाता है कि टेक्स्ट स्ट्राइक थ्रू होना चाहिए या नहीं।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | boolean | यदि टेक्स्ट स्ट्राइक थ्रू होना चाहिए तो true, अन्यथा false। |
|

### getStartStringSeparator() {#getStartStringSeparator--}
```
public final String getStartStringSeparator()
```


स्टार्ट स्ट्रिंग सेपरेटर प्राप्त करता है।


**Returns:**
java.lang.String - प्रारंभ स्ट्रिंग विभाजक।

### setStartStringSeparator(String value) {#setStartStringSeparator-java.lang.String-}
```
public final void setStartStringSeparator(String value)
```


स्टार्ट स्ट्रिंग सेपरेटर सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | java.lang.String | नया प्रारंभ स्ट्रिंग विभाजक। |
|

### getEndStringSeparator() {#getEndStringSeparator--}
```
public final String getEndStringSeparator()
```


एंड स्ट्रिंग सेपरेटर प्राप्त करता है।


**Returns:**
java.lang.String - अंत स्ट्रिंग विभाजक।

### setEndStringSeparator(String value) {#setEndStringSeparator-java.lang.String-}
```
public final void setEndStringSeparator(String value)
```


एंड स्ट्रिंग सेपरेटर सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | java.lang.String | नया अंत स्ट्रिंग विभाजक। |
|

### getOriginalSize() {#getOriginalSize--}
```
public final Size getOriginalSize()
```


तुलना दस्तावेज़ों का मूल आकार प्राप्त करता है।


**Returns:**
[Size](../../com.groupdocs.comparison.options.style/size) - the original size of comparing documents.

### setOriginalSize(Size value) {#setOriginalSize-com.groupdocs.comparison.options.style.Size-}
```
public final void setOriginalSize(Size value)
```


तुलना दस्तावेज़ों का मूल आकार सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | [Size](../../com.groupdocs.comparison.options.style/size) | तुलना दस्तावेज़ों का नया मूल आकार। |
|

### getWordsSeparators() {#getWordsSeparators--}
```
public final char[] getWordsSeparators()
```


शब्द सेपरेटर अक्षर प्राप्त करता है।


**Returns:**
char[] - शब्द विभाजक।

### setWordsSeparators(char[] value) {#setWordsSeparators-char---}
```
public final void setWordsSeparators(char[] value)
```


शब्द सेपरेटर अक्षर सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | char[] | नए शब्द विभाजक। |
|

