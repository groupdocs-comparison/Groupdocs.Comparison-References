---
title: "StyleSettings"
second_title: "GroupDocs.Comparison voor Java API-referentie"
description: "Deze klasse stelt stijlinstellingen voor tekstopmaak voor."
type: docs
weight: 12
url: /nl/java/com.groupdocs.comparison.options.style/stylesettings/
---
**Inheritance:**
java.lang.Object
```
public class StyleSettings
```

Deze klasse stelt stijlinstellingen voor tekstopmaak voor.


Gebruik deze klasse om de letterkleur, markeerkleur, stijlkenmerken (vet, onderstrepen, cursief, doorhalen) aan te passen,
string-scheidingstekens, oorspronkelijke groottes en woord-scheidingstekens voor tekst.


Voorbeeldgebruik:

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


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [StyleSettings()](#StyleSettings--) | Initialiseert een nieuw exemplaar van de klasse StyleSettings. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getFontColor()](#getFontColor--) | Haalt de letterkleur op. |
|
|  | [setFontColor(Color value)](#setFontColor-java.awt.Color-) | Stelt de letterkleur in. |
|
|  | [getShapeColor()](#getShapeColor--) | Haalt de vormkleur op. |
|
|  | [setShapeColor(Color value)](#setShapeColor-java.awt.Color-) | Stelt de vormkleur in. |
|
|  | [getHighlightColor()](#getHighlightColor--) | Haalt de markeerkleur op. |
|
|  | [setHighlightColor(Color value)](#setHighlightColor-java.awt.Color-) | Stelt de markeerkleur in. |
|
|  | [isBold()](#isBold--) | Haalt een vlag op die aangeeft of de tekst vetgedrukt zal zijn of niet. |
|
|  | [setBold(boolean value)](#setBold-boolean-) | Stelt een vlag in die aangeeft of de tekst vetgedrukt moet zijn of niet. |
|
|  | [isUnderline()](#isUnderline--) | Haalt een vlag op die aangeeft of de tekst onderstreept zal zijn of niet. |
|
|  | [setUnderline(boolean value)](#setUnderline-boolean-) | Stelt een vlag in die aangeeft of de tekst onderstreept moet zijn of niet. |
|
|  | [isItalic()](#isItalic--) | Haalt een vlag op die aangeeft of de tekst cursief zal zijn of niet. |
|
|  | [setItalic(boolean value)](#setItalic-boolean-) | Stelt een vlag in die aangeeft of de tekst cursief moet zijn of niet. |
|
|  | [isStrikethrough()](#isStrikethrough--) | Haalt een vlag op die aangeeft of de tekst doorgestreept zal zijn of niet. |
|
|  | [setStrikethrough(boolean value)](#setStrikethrough-boolean-) | Stelt een vlag in die aangeeft of de tekst doorgestreept moet zijn of niet. |
|
|  | [getStartStringSeparator()](#getStartStringSeparator--) | Haalt het scheidingsteken voor de startreeks op. |
|
|  | [setStartStringSeparator(String value)](#setStartStringSeparator-java.lang.String-) | Stelt het scheidingsteken voor de startreeks in. |
|
|  | [getEndStringSeparator()](#getEndStringSeparator--) | Haalt het scheidingsteken voor de eindreeks op. |
|
|  | [setEndStringSeparator(String value)](#setEndStringSeparator-java.lang.String-) | Stelt het scheidingsteken voor de eindreeks in. |
|
|  | [getOriginalSize()](#getOriginalSize--) | Haalt de oorspronkelijke grootte van te vergelijken documenten op. |
|
|  | [setOriginalSize(Size value)](#setOriginalSize-com.groupdocs.comparison.options.style.Size-) | Stelt de oorspronkelijke grootte van te vergelijken documenten in. |
|
|  | [getWordsSeparators()](#getWordsSeparators--) | Haalt de woord scheidingsteken tekens op. |
|
|  | [setWordsSeparators(char[] value)](#setWordsSeparators-char---) | Stelt de woord scheidingsteken tekens in. |
|
### StyleSettings() {#StyleSettings--}
```
public StyleSettings()
```


Initialiseert een nieuw exemplaar van de klasse StyleSettings.


### getFontColor() {#getFontColor--}
```
public final Color getFontColor()
```


Haalt de letterkleur op.


**Returns:**
java.awt.Color - de letterkleur.

### setFontColor(Color value) {#setFontColor-java.awt.Color-}
```
public final void setFontColor(Color value)
```


Stelt de letterkleur in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.awt.Color | De nieuwe letterkleur. |
|

### getShapeColor() {#getShapeColor--}
```
public final Color getShapeColor()
```


Haalt de vormkleur op.


**Returns:**
java.awt.Color - de vormkleur.

### setShapeColor(Color value) {#setShapeColor-java.awt.Color-}
```
public final void setShapeColor(Color value)
```


Stelt de vormkleur in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.awt.Color | De nieuwe vormkleur. |
|

### getHighlightColor() {#getHighlightColor--}
```
public final Color getHighlightColor()
```


Haalt de markeerkleur op.


**Returns:**
java.awt.Color - de markeerkleur.

### setHighlightColor(Color value) {#setHighlightColor-java.awt.Color-}
```
public final void setHighlightColor(Color value)
```


Stelt de markeerkleur in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.awt.Color | De nieuwe markeerkleur. |
|

### isBold() {#isBold--}
```
public final boolean isBold()
```


Haalt een vlag op die aangeeft of de tekst vetgedrukt zal zijn of niet.


**Returns:**
boolean - true als de tekst vet wordt, false anders.

### setBold(boolean value) {#setBold-boolean-}
```
public final void setBold(boolean value)
```


Stelt een vlag in die aangeeft of de tekst vetgedrukt moet zijn of niet.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | boolean | true als de tekst vet moet zijn, false anders. |
|

### isUnderline() {#isUnderline--}
```
public final boolean isUnderline()
```


Haalt een vlag op die aangeeft of de tekst onderstreept zal zijn of niet.


**Returns:**
boolean - true als de tekst onderstreept wordt, false anders.

### setUnderline(boolean value) {#setUnderline-boolean-}
```
public final void setUnderline(boolean value)
```


Stelt een vlag in die aangeeft of de tekst onderstreept moet zijn of niet.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | boolean | true als de tekst onderstreept moet zijn, false anders. |
|

### isItalic() {#isItalic--}
```
public final boolean isItalic()
```


Haalt een vlag op die aangeeft of de tekst cursief zal zijn of niet.


**Returns:**
boolean - true als de tekst cursief wordt, false anders.

### setItalic(boolean value) {#setItalic-boolean-}
```
public final void setItalic(boolean value)
```


Stelt een vlag in die aangeeft of de tekst cursief moet zijn of niet.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | boolean | true als de tekst cursief moet zijn, false anders. |
|

### isStrikethrough() {#isStrikethrough--}
```
public final boolean isStrikethrough()
```


Haalt een vlag op die aangeeft of de tekst doorgestreept zal zijn of niet.


**Returns:**
boolean - true als de tekst doorgestreept wordt, false anders.

### setStrikethrough(boolean value) {#setStrikethrough-boolean-}
```
public final void setStrikethrough(boolean value)
```


Stelt een vlag in die aangeeft of de tekst doorgestreept moet zijn of niet.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | boolean | true als de tekst doorgestreept moet zijn, false anders. |
|

### getStartStringSeparator() {#getStartStringSeparator--}
```
public final String getStartStringSeparator()
```


Haalt het scheidingsteken voor de startreeks op.


**Returns:**
java.lang.String - het scheidingsteken voor de startreeks.

### setStartStringSeparator(String value) {#setStartStringSeparator-java.lang.String-}
```
public final void setStartStringSeparator(String value)
```


Stelt het scheidingsteken voor de startreeks in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.lang.String | Het nieuwe scheidingsteken voor de startreeks. |
|

### getEndStringSeparator() {#getEndStringSeparator--}
```
public final String getEndStringSeparator()
```


Haalt het scheidingsteken voor de eindreeks op.


**Returns:**
java.lang.String - het scheidingsteken voor de eindreeks.

### setEndStringSeparator(String value) {#setEndStringSeparator-java.lang.String-}
```
public final void setEndStringSeparator(String value)
```


Stelt het scheidingsteken voor de eindreeks in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.lang.String | Het nieuwe scheidingsteken voor de eindreeks. |
|

### getOriginalSize() {#getOriginalSize--}
```
public final Size getOriginalSize()
```


Haalt de oorspronkelijke grootte van te vergelijken documenten op.


**Returns:**
[Size](../../com.groupdocs.comparison.options.style/size) - the original size of comparing documents.

### setOriginalSize(Size value) {#setOriginalSize-com.groupdocs.comparison.options.style.Size-}
```
public final void setOriginalSize(Size value)
```


Stelt de oorspronkelijke grootte van te vergelijken documenten in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [Size](../../com.groupdocs.comparison.options.style/size) | De nieuwe originele grootte van te vergelijken documenten. |
|

### getWordsSeparators() {#getWordsSeparators--}
```
public final char[] getWordsSeparators()
```


Haalt de woord scheidingsteken tekens op.


**Returns:**
char[] - de woordseparatoren.

### setWordsSeparators(char[] value) {#setWordsSeparators-char---}
```
public final void setWordsSeparators(char[] value)
```


Stelt de woord scheidingsteken tekens in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | char[] | De nieuwe woordseparatoren. |
|

