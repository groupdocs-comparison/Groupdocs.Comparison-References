---
title: "StyleSettings"
second_title: "Referencia de API de GroupDocs.Comparison for Java"
description: "Esta clase representa los ajustes de estilo para el formato de texto."
type: docs
weight: 12
url: /es/java/com.groupdocs.comparison.options.style/stylesettings/
---
**Inheritance:**
java.lang.Object
```
public class StyleSettings
```

Esta clase representa los ajustes de estilo para el formato de texto.


Utilice esta clase para personalizar el color de fuente, el color de resaltado, los atributos de estilo (negrita, subrayado, cursiva, tachado),
separadores de cadena, tamaños originales y separadores de palabras para texto.


Ejemplo de uso:

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


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [StyleSettings()](#StyleSettings--) | Inicializa una nueva instancia de la clase StyleSettings. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getFontColor()](#getFontColor--) | Obtiene el color de la fuente. |
|
|  | [setFontColor(Color value)](#setFontColor-java.awt.Color-) | Establece el color de la fuente. |
|
|  | [getShapeColor()](#getShapeColor--) | Obtiene el color de la forma. |
|
|  | [setShapeColor(Color value)](#setShapeColor-java.awt.Color-) | Establece el color de la forma. |
|
|  | [getHighlightColor()](#getHighlightColor--) | Obtiene el color de resaltado. |
|
|  | [setHighlightColor(Color value)](#setHighlightColor-java.awt.Color-) | Establece el color de resaltado. |
|
|  | [isBold()](#isBold--) | Obtiene una bandera que indica si el texto será negrita o no. |
|
|  | [setBold(boolean value)](#setBold-boolean-) | Establece una bandera que indica si el texto debe ser negrita o no. |
|
|  | [isUnderline()](#isUnderline--) | Obtiene una bandera que indica si el texto estará subrayado o no. |
|
|  | [setUnderline(boolean value)](#setUnderline-boolean-) | Establece una bandera que indica si el texto debe estar subrayado o no. |
|
|  | [isItalic()](#isItalic--) | Obtiene una bandera que indica si el texto será cursiva o no. |
|
|  | [setItalic(boolean value)](#setItalic-boolean-) | Establece una bandera que indica si el texto debe ser cursiva o no. |
|
|  | [isStrikethrough()](#isStrikethrough--) | Obtiene una bandera que indica si el texto tendrá tachado o no. |
|
|  | [setStrikethrough(boolean value)](#setStrikethrough-boolean-) | Establece una bandera que indica si el texto debe estar tachado o no. |
|
|  | [getStartStringSeparator()](#getStartStringSeparator--) | Obtiene el separador de cadena de inicio. |
|
|  | [setStartStringSeparator(String value)](#setStartStringSeparator-java.lang.String-) | Establece el separador de cadena de inicio. |
|
|  | [getEndStringSeparator()](#getEndStringSeparator--) | Obtiene el separador de cadena final. |
|
|  | [setEndStringSeparator(String value)](#setEndStringSeparator-java.lang.String-) | Establece el separador de cadena final. |
|
|  | [getOriginalSize()](#getOriginalSize--) | Obtiene el tamaño original de los documentos comparados. |
|
|  | [setOriginalSize(Size value)](#setOriginalSize-com.groupdocs.comparison.options.style.Size-) | Establece el tamaño original de los documentos comparados. |
|
|  | [getWordsSeparators()](#getWordsSeparators--) | Obtiene los caracteres separadores de palabras. |
|
|  | [setWordsSeparators(char[] value)](#setWordsSeparators-char---) | Establece los caracteres separadores de palabras. |
|
### StyleSettings() {#StyleSettings--}
```
public StyleSettings()
```


Inicializa una nueva instancia de la clase StyleSettings.


### getFontColor() {#getFontColor--}
```
public final Color getFontColor()
```


Obtiene el color de la fuente.


**Returns:**
java.awt.Color - el color de la fuente.

### setFontColor(Color value) {#setFontColor-java.awt.Color-}
```
public final void setFontColor(Color value)
```


Establece el color de la fuente.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.awt.Color | El nuevo color de fuente. |
|

### getShapeColor() {#getShapeColor--}
```
public final Color getShapeColor()
```


Obtiene el color de la forma.


**Returns:**
java.awt.Color - el color de la forma.

### setShapeColor(Color value) {#setShapeColor-java.awt.Color-}
```
public final void setShapeColor(Color value)
```


Establece el color de la forma.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.awt.Color | El nuevo color de la forma. |
|

### getHighlightColor() {#getHighlightColor--}
```
public final Color getHighlightColor()
```


Obtiene el color de resaltado.


**Returns:**
java.awt.Color - el color de resaltado.

### setHighlightColor(Color value) {#setHighlightColor-java.awt.Color-}
```
public final void setHighlightColor(Color value)
```


Establece el color de resaltado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.awt.Color | El nuevo color de resaltado. |
|

### isBold() {#isBold--}
```
public final boolean isBold()
```


Obtiene una bandera que indica si el texto será negrita o no.


**Returns:**
boolean - true si el texto será negrita, false de lo contrario.

### setBold(boolean value) {#setBold-boolean-}
```
public final void setBold(boolean value)
```


Establece una bandera que indica si el texto debe ser negrita o no.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | true si el texto debe ser negrita, false de lo contrario. |
|

### isUnderline() {#isUnderline--}
```
public final boolean isUnderline()
```


Obtiene una bandera que indica si el texto estará subrayado o no.


**Returns:**
boolean - true si el texto será subrayado, false de lo contrario.

### setUnderline(boolean value) {#setUnderline-boolean-}
```
public final void setUnderline(boolean value)
```


Establece una bandera que indica si el texto debe estar subrayado o no.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | true si el texto debe ser subrayado, false de lo contrario. |
|

### isItalic() {#isItalic--}
```
public final boolean isItalic()
```


Obtiene una bandera que indica si el texto será cursiva o no.


**Returns:**
boolean - true si el texto será cursiva, false de lo contrario.

### setItalic(boolean value) {#setItalic-boolean-}
```
public final void setItalic(boolean value)
```


Establece una bandera que indica si el texto debe ser cursiva o no.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | true si el texto debe ser cursiva, false de lo contrario. |
|

### isStrikethrough() {#isStrikethrough--}
```
public final boolean isStrikethrough()
```


Obtiene una bandera que indica si el texto tendrá tachado o no.


**Returns:**
boolean - true si el texto tendrá tachado, false de lo contrario.

### setStrikethrough(boolean value) {#setStrikethrough-boolean-}
```
public final void setStrikethrough(boolean value)
```


Establece una bandera que indica si el texto debe estar tachado o no.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | true si el texto debe tener tachado, false de lo contrario. |
|

### getStartStringSeparator() {#getStartStringSeparator--}
```
public final String getStartStringSeparator()
```


Obtiene el separador de cadena de inicio.


**Returns:**
java.lang.String - el separador de cadena inicial.

### setStartStringSeparator(String value) {#setStartStringSeparator-java.lang.String-}
```
public final void setStartStringSeparator(String value)
```


Establece el separador de cadena de inicio.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.String | El nuevo separador de cadena inicial. |
|

### getEndStringSeparator() {#getEndStringSeparator--}
```
public final String getEndStringSeparator()
```


Obtiene el separador de cadena final.


**Returns:**
java.lang.String - el separador de cadena final.

### setEndStringSeparator(String value) {#setEndStringSeparator-java.lang.String-}
```
public final void setEndStringSeparator(String value)
```


Establece el separador de cadena final.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.String | El nuevo separador de cadena final. |
|

### getOriginalSize() {#getOriginalSize--}
```
public final Size getOriginalSize()
```


Obtiene el tamaño original de los documentos comparados.


**Returns:**
[Size](../../com.groupdocs.comparison.options.style/size) - the original size of comparing documents.

### setOriginalSize(Size value) {#setOriginalSize-com.groupdocs.comparison.options.style.Size-}
```
public final void setOriginalSize(Size value)
```


Establece el tamaño original de los documentos comparados.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [Size](../../com.groupdocs.comparison.options.style/size) | El nuevo tamaño original de los documentos comparados. |
|

### getWordsSeparators() {#getWordsSeparators--}
```
public final char[] getWordsSeparators()
```


Obtiene los caracteres separadores de palabras.


**Returns:**
char[] - los separadores de palabras.

### setWordsSeparators(char[] value) {#setWordsSeparators-char---}
```
public final void setWordsSeparators(char[] value)
```


Establece los caracteres separadores de palabras.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | char[] | Los nuevos separadores de palabras. |
|

