---
title: "StyleSettings"
second_title: "GroupDocs.Comparison för Java API-referens"
description: "Denna klass representerar stilinställningar för textformatering."
type: docs
weight: 12
url: /sv/java/com.groupdocs.comparison.options.style/stylesettings/
---
**Inheritance:**
java.lang.Object
```
public class StyleSettings
```

Denna klass representerar stilinställningar för textformatering.


Använd den här klassen för att anpassa teckensnittsfärg, markeringsfärg, stilattribut (fet, understruken, kursiv, genomstruken),
strängseparatorer, originalstorlekar och ordseparatorer för text.


Exempel på användning:

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


## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [StyleSettings()](#StyleSettings--) | Initierar en ny instans av klassen StyleSettings. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getFontColor()](#getFontColor--) | Hämtar teckensnittets färg. |
|
|  | [setFontColor(Color value)](#setFontColor-java.awt.Color-) | Ställer in teckensnittets färg. |
|
|  | [getShapeColor()](#getShapeColor--) | Hämtar formens färg. |
|
|  | [setShapeColor(Color value)](#setShapeColor-java.awt.Color-) | Ställer in formens färg. |
|
|  | [getHighlightColor()](#getHighlightColor--) | Hämtar markeringsfärgen. |
|
|  | [setHighlightColor(Color value)](#setHighlightColor-java.awt.Color-) | Ställer in markeringsfärgen. |
|
|  | [isBold()](#isBold--) | Hämtar en flagga som indikerar om texten kommer att vara fet eller inte. |
|
|  | [setBold(boolean value)](#setBold-boolean-) | Ställer in en flagga som indikerar om texten ska vara fet eller inte. |
|
|  | [isUnderline()](#isUnderline--) | Hämtar en flagga som indikerar om texten kommer att vara understruken eller inte. |
|
|  | [setUnderline(boolean value)](#setUnderline-boolean-) | Ställer in en flagga som indikerar om texten ska vara understruken eller inte. |
|
|  | [isItalic()](#isItalic--) | Hämtar en flagga som indikerar om texten kommer att vara kursiv eller inte. |
|
|  | [setItalic(boolean value)](#setItalic-boolean-) | Ställer in en flagga som indikerar om texten ska vara kursiv eller inte. |
|
|  | [isStrikethrough()](#isStrikethrough--) | Hämtar en flagga som indikerar om texten kommer att vara genomstruken eller inte. |
|
|  | [setStrikethrough(boolean value)](#setStrikethrough-boolean-) | Ställer in en flagga som indikerar om texten ska vara genomstruken eller inte. |
|
|  | [getStartStringSeparator()](#getStartStringSeparator--) | Hämtar startsträngseparatorn. |
|
|  | [setStartStringSeparator(String value)](#setStartStringSeparator-java.lang.String-) | Ställer in startsträngseparatorn. |
|
|  | [getEndStringSeparator()](#getEndStringSeparator--) | Hämtar slutsträngseparatorn. |
|
|  | [setEndStringSeparator(String value)](#setEndStringSeparator-java.lang.String-) | Ställer in slutsträngseparatorn. |
|
|  | [getOriginalSize()](#getOriginalSize--) | Hämtar den ursprungliga storleken på jämförda dokument. |
|
|  | [setOriginalSize(Size value)](#setOriginalSize-com.groupdocs.comparison.options.style.Size-) | Ställer in den ursprungliga storleken på jämförda dokument. |
|
|  | [getWordsSeparators()](#getWordsSeparators--) | Hämtar tecknen för ordseparatorer. |
|
|  | [setWordsSeparators(char[] value)](#setWordsSeparators-char---) | Ställer in tecknen för ordseparatorer. |
|
### StyleSettings() {#StyleSettings--}
```
public StyleSettings()
```


Initierar en ny instans av klassen StyleSettings.


### getFontColor() {#getFontColor--}
```
public final Color getFontColor()
```


Hämtar teckensnittets färg.


**Returns:**
java.awt.Color - teckensnittets färg.

### setFontColor(Color value) {#setFontColor-java.awt.Color-}
```
public final void setFontColor(Color value)
```


Ställer in teckensnittets färg.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | java.awt.Color | Den nya teckensnittsfärgen. |
|

### getShapeColor() {#getShapeColor--}
```
public final Color getShapeColor()
```


Hämtar formens färg.


**Returns:**
java.awt.Color - formens färg.

### setShapeColor(Color value) {#setShapeColor-java.awt.Color-}
```
public final void setShapeColor(Color value)
```


Ställer in formens färg.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | java.awt.Color | Den nya formfärgen. |
|

### getHighlightColor() {#getHighlightColor--}
```
public final Color getHighlightColor()
```


Hämtar markeringsfärgen.


**Returns:**
java.awt.Color - markeringsfärgen.

### setHighlightColor(Color value) {#setHighlightColor-java.awt.Color-}
```
public final void setHighlightColor(Color value)
```


Ställer in markeringsfärgen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | java.awt.Color | Den nya markeringsfärgen. |
|

### isBold() {#isBold--}
```
public final boolean isBold()
```


Hämtar en flagga som indikerar om texten kommer att vara fet eller inte.


**Returns:**
boolean - true om texten kommer att vara fet, false annars.

### setBold(boolean value) {#setBold-boolean-}
```
public final void setBold(boolean value)
```


Ställer in en flagga som indikerar om texten ska vara fet eller inte.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | boolean | true om texten ska vara fet, false annars. |
|

### isUnderline() {#isUnderline--}
```
public final boolean isUnderline()
```


Hämtar en flagga som indikerar om texten kommer att vara understruken eller inte.


**Returns:**
boolean - true om texten kommer att vara understruken, false annars.

### setUnderline(boolean value) {#setUnderline-boolean-}
```
public final void setUnderline(boolean value)
```


Ställer in en flagga som indikerar om texten ska vara understruken eller inte.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | boolean | true om texten ska vara understruken, false annars. |
|

### isItalic() {#isItalic--}
```
public final boolean isItalic()
```


Hämtar en flagga som indikerar om texten kommer att vara kursiv eller inte.


**Returns:**
boolean - true om texten kommer att vara kursiv, false annars.

### setItalic(boolean value) {#setItalic-boolean-}
```
public final void setItalic(boolean value)
```


Ställer in en flagga som indikerar om texten ska vara kursiv eller inte.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | boolean | true om texten ska vara kursiv, false annars. |
|

### isStrikethrough() {#isStrikethrough--}
```
public final boolean isStrikethrough()
```


Hämtar en flagga som indikerar om texten kommer att vara genomstruken eller inte.


**Returns:**
boolean - true om texten kommer att vara genomstruken, false annars.

### setStrikethrough(boolean value) {#setStrikethrough-boolean-}
```
public final void setStrikethrough(boolean value)
```


Ställer in en flagga som indikerar om texten ska vara genomstruken eller inte.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | boolean | true om texten ska vara genomstruken, false annars. |
|

### getStartStringSeparator() {#getStartStringSeparator--}
```
public final String getStartStringSeparator()
```


Hämtar startsträngseparatorn.


**Returns:**
java.lang.String - startsträngseparatorn.

### setStartStringSeparator(String value) {#setStartStringSeparator-java.lang.String-}
```
public final void setStartStringSeparator(String value)
```


Ställer in startsträngseparatorn.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | java.lang.String | Den nya startsträngseparatorn. |
|

### getEndStringSeparator() {#getEndStringSeparator--}
```
public final String getEndStringSeparator()
```


Hämtar slutsträngseparatorn.


**Returns:**
java.lang.String - slutsträngseparatorn.

### setEndStringSeparator(String value) {#setEndStringSeparator-java.lang.String-}
```
public final void setEndStringSeparator(String value)
```


Ställer in slutsträngseparatorn.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | java.lang.String | Den nya slutsträngseparatorn. |
|

### getOriginalSize() {#getOriginalSize--}
```
public final Size getOriginalSize()
```


Hämtar den ursprungliga storleken på jämförda dokument.


**Returns:**
[Size](../../com.groupdocs.comparison.options.style/size) - the original size of comparing documents.

### setOriginalSize(Size value) {#setOriginalSize-com.groupdocs.comparison.options.style.Size-}
```
public final void setOriginalSize(Size value)
```


Ställer in den ursprungliga storleken på jämförda dokument.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [Size](../../com.groupdocs.comparison.options.style/size) | Den nya ursprungliga storleken på jämförelsedokumenten. |
|

### getWordsSeparators() {#getWordsSeparators--}
```
public final char[] getWordsSeparators()
```


Hämtar tecknen för ordseparatorer.


**Returns:**
char[] - ordseparatorerna.

### setWordsSeparators(char[] value) {#setWordsSeparators-char---}
```
public final void setWordsSeparators(char[] value)
```


Ställer in tecknen för ordseparatorer.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | char[] | De nya ordseparatorerna. |
|

