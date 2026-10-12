---
title: "StyleSettings"
second_title: "Riferimento API di GroupDocs.Comparison per Java"
description: "Questa classe rappresenta le impostazioni di stile per la formattazione del testo."
type: docs
weight: 12
url: /it/java/com.groupdocs.comparison.options.style/stylesettings/
---
**Inheritance:**
java.lang.Object
```
public class StyleSettings
```

Questa classe rappresenta le impostazioni di stile per la formattazione del testo.


Usa questa classe per personalizzare il colore del carattere, il colore di evidenziazione, gli attributi di stile (grassetto, sottolineato, corsivo, barrato),
separatori di stringa, dimensioni originali e separatori di parole per il testo.


Esempio di utilizzo:

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


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [StyleSettings()](#StyleSettings--) | Inizializza una nuova istanza della classe StyleSettings. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getFontColor()](#getFontColor--) | Ottiene il colore del carattere. |
|
|  | [setFontColor(Color value)](#setFontColor-java.awt.Color-) | Imposta il colore del carattere. |
|
|  | [getShapeColor()](#getShapeColor--) | Ottiene il colore della forma. |
|
|  | [setShapeColor(Color value)](#setShapeColor-java.awt.Color-) | Imposta il colore della forma. |
|
|  | [getHighlightColor()](#getHighlightColor--) | Ottiene il colore dell'evidenziazione. |
|
|  | [setHighlightColor(Color value)](#setHighlightColor-java.awt.Color-) | Imposta il colore dell'evidenziazione. |
|
|  | [isBold()](#isBold--) | Ottiene un flag che indica se il testo sarà in grassetto o meno. |
|
|  | [setBold(boolean value)](#setBold-boolean-) | Imposta un flag che indica se il testo dovrebbe essere in grassetto o meno. |
|
|  | [isUnderline()](#isUnderline--) | Ottiene un flag che indica se il testo sarà sottolineato o meno. |
|
|  | [setUnderline(boolean value)](#setUnderline-boolean-) | Imposta un flag che indica se il testo dovrebbe essere sottolineato o meno. |
|
|  | [isItalic()](#isItalic--) | Ottiene un flag che indica se il testo sarà in corsivo o meno. |
|
|  | [setItalic(boolean value)](#setItalic-boolean-) | Imposta un flag che indica se il testo dovrebbe essere in corsivo o meno. |
|
|  | [isStrikethrough()](#isStrikethrough--) | Ottiene un flag che indica se il testo sarà barrato o meno. |
|
|  | [setStrikethrough(boolean value)](#setStrikethrough-boolean-) | Imposta un flag che indica se il testo dovrebbe essere barrato o meno. |
|
|  | [getStartStringSeparator()](#getStartStringSeparator--) | Ottiene il separatore di stringa iniziale. |
|
|  | [setStartStringSeparator(String value)](#setStartStringSeparator-java.lang.String-) | Imposta il separatore di stringa iniziale. |
|
|  | [getEndStringSeparator()](#getEndStringSeparator--) | Ottiene il separatore di stringa finale. |
|
|  | [setEndStringSeparator(String value)](#setEndStringSeparator-java.lang.String-) | Imposta il separatore di stringa finale. |
|
|  | [getOriginalSize()](#getOriginalSize--) | Ottiene la dimensione originale dei documenti da confrontare. |
|
|  | [setOriginalSize(Size value)](#setOriginalSize-com.groupdocs.comparison.options.style.Size-) | Imposta la dimensione originale dei documenti da confrontare. |
|
|  | [getWordsSeparators()](#getWordsSeparators--) | Ottiene i caratteri separatori di parole. |
|
|  | [setWordsSeparators(char[] value)](#setWordsSeparators-char---) | Imposta i caratteri separatori di parole. |
|
### StyleSettings() {#StyleSettings--}
```
public StyleSettings()
```


Inizializza una nuova istanza della classe StyleSettings.


### getFontColor() {#getFontColor--}
```
public final Color getFontColor()
```


Ottiene il colore del carattere.


**Returns:**
java.awt.Color - il colore del carattere.

### setFontColor(Color value) {#setFontColor-java.awt.Color-}
```
public final void setFontColor(Color value)
```


Imposta il colore del carattere.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.awt.Color | Il nuovo colore del carattere. |
|

### getShapeColor() {#getShapeColor--}
```
public final Color getShapeColor()
```


Ottiene il colore della forma.


**Returns:**
java.awt.Color - il colore della forma.

### setShapeColor(Color value) {#setShapeColor-java.awt.Color-}
```
public final void setShapeColor(Color value)
```


Imposta il colore della forma.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.awt.Color | Il nuovo colore della forma. |
|

### getHighlightColor() {#getHighlightColor--}
```
public final Color getHighlightColor()
```


Ottiene il colore dell'evidenziazione.


**Returns:**
java.awt.Color - il colore dell'evidenziazione.

### setHighlightColor(Color value) {#setHighlightColor-java.awt.Color-}
```
public final void setHighlightColor(Color value)
```


Imposta il colore dell'evidenziazione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.awt.Color | Il nuovo colore dell'evidenziazione. |
|

### isBold() {#isBold--}
```
public final boolean isBold()
```


Ottiene un flag che indica se il testo sarà in grassetto o meno.


**Returns:**
boolean - vero se il testo sarà in grassetto, falso altrimenti.

### setBold(boolean value) {#setBold-boolean-}
```
public final void setBold(boolean value)
```


Imposta un flag che indica se il testo dovrebbe essere in grassetto o meno.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | vero se il testo dovrebbe essere in grassetto, falso altrimenti. |
|

### isUnderline() {#isUnderline--}
```
public final boolean isUnderline()
```


Ottiene un flag che indica se il testo sarà sottolineato o meno.


**Returns:**
boolean - vero se il testo sarà sottolineato, falso altrimenti.

### setUnderline(boolean value) {#setUnderline-boolean-}
```
public final void setUnderline(boolean value)
```


Imposta un flag che indica se il testo dovrebbe essere sottolineato o meno.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | vero se il testo dovrebbe essere sottolineato, falso altrimenti. |
|

### isItalic() {#isItalic--}
```
public final boolean isItalic()
```


Ottiene un flag che indica se il testo sarà in corsivo o meno.


**Returns:**
boolean - vero se il testo sarà in corsivo, falso altrimenti.

### setItalic(boolean value) {#setItalic-boolean-}
```
public final void setItalic(boolean value)
```


Imposta un flag che indica se il testo dovrebbe essere in corsivo o meno.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | vero se il testo dovrebbe essere in corsivo, falso altrimenti. |
|

### isStrikethrough() {#isStrikethrough--}
```
public final boolean isStrikethrough()
```


Ottiene un flag che indica se il testo sarà barrato o meno.


**Returns:**
boolean - vero se il testo sarà barrato, falso altrimenti.

### setStrikethrough(boolean value) {#setStrikethrough-boolean-}
```
public final void setStrikethrough(boolean value)
```


Imposta un flag che indica se il testo dovrebbe essere barrato o meno.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | vero se il testo dovrebbe essere barrato, falso altrimenti. |
|

### getStartStringSeparator() {#getStartStringSeparator--}
```
public final String getStartStringSeparator()
```


Ottiene il separatore di stringa iniziale.


**Returns:**
java.lang.String - il separatore di stringa iniziale.

### setStartStringSeparator(String value) {#setStartStringSeparator-java.lang.String-}
```
public final void setStartStringSeparator(String value)
```


Imposta il separatore di stringa iniziale.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.lang.String | Il nuovo separatore di stringa iniziale. |
|

### getEndStringSeparator() {#getEndStringSeparator--}
```
public final String getEndStringSeparator()
```


Ottiene il separatore di stringa finale.


**Returns:**
java.lang.String - il separatore di stringa finale.

### setEndStringSeparator(String value) {#setEndStringSeparator-java.lang.String-}
```
public final void setEndStringSeparator(String value)
```


Imposta il separatore di stringa finale.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.lang.String | Il nuovo separatore di stringa finale. |
|

### getOriginalSize() {#getOriginalSize--}
```
public final Size getOriginalSize()
```


Ottiene la dimensione originale dei documenti da confrontare.


**Returns:**
[Size](../../com.groupdocs.comparison.options.style/size) - the original size of comparing documents.

### setOriginalSize(Size value) {#setOriginalSize-com.groupdocs.comparison.options.style.Size-}
```
public final void setOriginalSize(Size value)
```


Imposta la dimensione originale dei documenti da confrontare.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [Size](../../com.groupdocs.comparison.options.style/size) | La nuova dimensione originale dei documenti di confronto. |
|

### getWordsSeparators() {#getWordsSeparators--}
```
public final char[] getWordsSeparators()
```


Ottiene i caratteri separatori di parole.


**Returns:**
char[] - i separatori di parole.

### setWordsSeparators(char[] value) {#setWordsSeparators-char---}
```
public final void setWordsSeparators(char[] value)
```


Imposta i caratteri separatori di parole.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | char[] | I nuovi separatori di parole. |
|

