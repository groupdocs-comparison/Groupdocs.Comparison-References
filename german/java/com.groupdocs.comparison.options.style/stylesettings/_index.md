---
title: "StyleSettings"
second_title: "GroupDocs.Comparison für Java API-Referenz"
description: "Diese Klasse stellt Stileinstellungen für die Textformatierung dar."
type: docs
weight: 12
url: /de/java/com.groupdocs.comparison.options.style/stylesettings/
---
**Inheritance:**
java.lang.Object
```
public class StyleSettings
```

Diese Klasse stellt Stileinstellungen für die Textformatierung dar.


Verwenden Sie diese Klasse, um die Schriftfarbe, Hervorhebungsfarbe, Stilattribute (fett, unterstrichen, kursiv, durchgestrichen) anzupassen,
Zeichenketten-Trennzeichen, Originalgrößen und Worttrennzeichen für Text.


Beispielverwendung:

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


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [StyleSettings()](#StyleSettings--) | Initialisiert eine neue Instanz der Klasse StyleSettings. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getFontColor()](#getFontColor--) | Liest die Schriftfarbe. |
|
|  | [setFontColor(Color value)](#setFontColor-java.awt.Color-) | Setzt die Schriftfarbe. |
|
|  | [getShapeColor()](#getShapeColor--) | Liest die Formfarbe. |
|
|  | [setShapeColor(Color value)](#setShapeColor-java.awt.Color-) | Setzt die Formfarbe. |
|
|  | [getHighlightColor()](#getHighlightColor--) | Liest die Hervorhebungsfarbe. |
|
|  | [setHighlightColor(Color value)](#setHighlightColor-java.awt.Color-) | Setzt die Hervorhebungsfarbe. |
|
|  | [isBold()](#isBold--) | Liest ein Flag, das angibt, ob der Text fett dargestellt wird oder nicht. |
|
|  | [setBold(boolean value)](#setBold-boolean-) | Setzt ein Flag, das angibt, ob der Text fett dargestellt werden soll oder nicht. |
|
|  | [isUnderline()](#isUnderline--) | Liest ein Flag, das angibt, ob der Text unterstrichen wird oder nicht. |
|
|  | [setUnderline(boolean value)](#setUnderline-boolean-) | Setzt ein Flag, das angibt, ob der Text unterstrichen werden soll oder nicht. |
|
|  | [isItalic()](#isItalic--) | Liest ein Flag, das angibt, ob der Text kursiv dargestellt wird oder nicht. |
|
|  | [setItalic(boolean value)](#setItalic-boolean-) | Setzt ein Flag, das angibt, ob der Text kursiv dargestellt werden soll oder nicht. |
|
|  | [isStrikethrough()](#isStrikethrough--) | Liest ein Flag, das angibt, ob der Text durchgestrichen wird oder nicht. |
|
|  | [setStrikethrough(boolean value)](#setStrikethrough-boolean-) | Setzt ein Flag, das angibt, ob der Text durchgestrichen werden soll oder nicht. |
|
|  | [getStartStringSeparator()](#getStartStringSeparator--) | Liest den Start-String-Trenner. |
|
|  | [setStartStringSeparator(String value)](#setStartStringSeparator-java.lang.String-) | Setzt den Start-String-Trenner. |
|
|  | [getEndStringSeparator()](#getEndStringSeparator--) | Liest den End-String-Trenner. |
|
|  | [setEndStringSeparator(String value)](#setEndStringSeparator-java.lang.String-) | Setzt den End-String-Trenner. |
|
|  | [getOriginalSize()](#getOriginalSize--) | Liest die Originalgröße der zu vergleichenden Dokumente. |
|
|  | [setOriginalSize(Size value)](#setOriginalSize-com.groupdocs.comparison.options.style.Size-) | Setzt die Originalgröße der zu vergleichenden Dokumente. |
|
|  | [getWordsSeparators()](#getWordsSeparators--) | Liest die Worttrennzeichen. |
|
|  | [setWordsSeparators(char[] value)](#setWordsSeparators-char---) | Setzt die Worttrennzeichen. |
|
### StyleSettings() {#StyleSettings--}
```
public StyleSettings()
```


Initialisiert eine neue Instanz der Klasse StyleSettings.


### getFontColor() {#getFontColor--}
```
public final Color getFontColor()
```


Liest die Schriftfarbe.


**Returns:**
java.awt.Color - die Schriftfarbe.

### setFontColor(Color value) {#setFontColor-java.awt.Color-}
```
public final void setFontColor(Color value)
```


Setzt die Schriftfarbe.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | java.awt.Color | Die neue Schriftfarbe. |
|

### getShapeColor() {#getShapeColor--}
```
public final Color getShapeColor()
```


Liest die Formfarbe.


**Returns:**
java.awt.Color - die Formfarbe.

### setShapeColor(Color value) {#setShapeColor-java.awt.Color-}
```
public final void setShapeColor(Color value)
```


Setzt die Formfarbe.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | java.awt.Color | Die neue Formfarbe. |
|

### getHighlightColor() {#getHighlightColor--}
```
public final Color getHighlightColor()
```


Liest die Hervorhebungsfarbe.


**Returns:**
java.awt.Color - die Hervorhebungsfarbe.

### setHighlightColor(Color value) {#setHighlightColor-java.awt.Color-}
```
public final void setHighlightColor(Color value)
```


Setzt die Hervorhebungsfarbe.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | java.awt.Color | Die neue Hervorhebungsfarbe. |
|

### isBold() {#isBold--}
```
public final boolean isBold()
```


Liest ein Flag, das angibt, ob der Text fett dargestellt wird oder nicht.


**Returns:**
boolean - true, wenn der Text fett sein wird, sonst false.

### setBold(boolean value) {#setBold-boolean-}
```
public final void setBold(boolean value)
```


Setzt ein Flag, das angibt, ob der Text fett dargestellt werden soll oder nicht.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | boolean | true, wenn der Text fett sein soll, sonst false. |
|

### isUnderline() {#isUnderline--}
```
public final boolean isUnderline()
```


Liest ein Flag, das angibt, ob der Text unterstrichen wird oder nicht.


**Returns:**
boolean - true, wenn der Text unterstrichen sein wird, sonst false.

### setUnderline(boolean value) {#setUnderline-boolean-}
```
public final void setUnderline(boolean value)
```


Setzt ein Flag, das angibt, ob der Text unterstrichen werden soll oder nicht.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | boolean | true, wenn der Text unterstrichen sein soll, sonst false. |
|

### isItalic() {#isItalic--}
```
public final boolean isItalic()
```


Liest ein Flag, das angibt, ob der Text kursiv dargestellt wird oder nicht.


**Returns:**
boolean - true, wenn der Text kursiv sein wird, sonst false.

### setItalic(boolean value) {#setItalic-boolean-}
```
public final void setItalic(boolean value)
```


Setzt ein Flag, das angibt, ob der Text kursiv dargestellt werden soll oder nicht.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | boolean | true, wenn der Text kursiv sein soll, sonst false. |
|

### isStrikethrough() {#isStrikethrough--}
```
public final boolean isStrikethrough()
```


Liest ein Flag, das angibt, ob der Text durchgestrichen wird oder nicht.


**Returns:**
boolean - true, wenn der Text durchgestrichen sein wird, sonst false.

### setStrikethrough(boolean value) {#setStrikethrough-boolean-}
```
public final void setStrikethrough(boolean value)
```


Setzt ein Flag, das angibt, ob der Text durchgestrichen werden soll oder nicht.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | boolean | true, wenn der Text durchgestrichen sein soll, sonst false. |
|

### getStartStringSeparator() {#getStartStringSeparator--}
```
public final String getStartStringSeparator()
```


Liest den Start-String-Trenner.


**Returns:**
java.lang.String - das Trennzeichen für die Startzeichenfolge.

### setStartStringSeparator(String value) {#setStartStringSeparator-java.lang.String-}
```
public final void setStartStringSeparator(String value)
```


Setzt den Start-String-Trenner.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | java.lang.String | Das neue Trennzeichen für die Startzeichenfolge. |
|

### getEndStringSeparator() {#getEndStringSeparator--}
```
public final String getEndStringSeparator()
```


Liest den End-String-Trenner.


**Returns:**
java.lang.String - das Trennzeichen für die Endzeichenfolge.

### setEndStringSeparator(String value) {#setEndStringSeparator-java.lang.String-}
```
public final void setEndStringSeparator(String value)
```


Setzt den End-String-Trenner.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | java.lang.String | Das neue Trennzeichen für die Endzeichenfolge. |
|

### getOriginalSize() {#getOriginalSize--}
```
public final Size getOriginalSize()
```


Liest die Originalgröße der zu vergleichenden Dokumente.


**Returns:**
[Size](../../com.groupdocs.comparison.options.style/size) - the original size of comparing documents.

### setOriginalSize(Size value) {#setOriginalSize-com.groupdocs.comparison.options.style.Size-}
```
public final void setOriginalSize(Size value)
```


Setzt die Originalgröße der zu vergleichenden Dokumente.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [Size](../../com.groupdocs.comparison.options.style/size) | Die neue Originalgröße der zu vergleichenden Dokumente. |
|

### getWordsSeparators() {#getWordsSeparators--}
```
public final char[] getWordsSeparators()
```


Liest die Worttrennzeichen.


**Returns:**
char[] - die Worttrennzeichen.

### setWordsSeparators(char[] value) {#setWordsSeparators-char---}
```
public final void setWordsSeparators(char[] value)
```


Setzt die Worttrennzeichen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | char[] | Die neuen Worttrennzeichen. |
|

