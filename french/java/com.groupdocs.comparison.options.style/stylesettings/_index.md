---
title: "StyleSettings"
second_title: "Référence API de GroupDocs.Comparison for Java"
description: "Cette classe représente les paramètres de style pour le formatage du texte."
type: docs
weight: 12
url: /fr/java/com.groupdocs.comparison.options.style/stylesettings/
---
**Inheritance:**
java.lang.Object
```
public class StyleSettings
```

Cette classe représente les paramètres de style pour le formatage du texte.


Utilisez cette classe pour personnaliser la couleur de la police, la couleur de surbrillance, les attributs de style (bold, underline, italic, strikethrough),
les séparateurs de chaîne, les tailles originales et les séparateurs de mots pour le texte.


Exemple d'utilisation :

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


## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [StyleSettings()](#StyleSettings--) | Initialise une nouvelle instance de la classe StyleSettings. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getFontColor()](#getFontColor--) | Obtient la couleur de la police. |
|
|  | [setFontColor(Color value)](#setFontColor-java.awt.Color-) | Définit la couleur de la police. |
|
|  | [getShapeColor()](#getShapeColor--) | Obtient la couleur de la forme. |
|
|  | [setShapeColor(Color value)](#setShapeColor-java.awt.Color-) | Définit la couleur de la forme. |
|
|  | [getHighlightColor()](#getHighlightColor--) | Obtient la couleur de surbrillance. |
|
|  | [setHighlightColor(Color value)](#setHighlightColor-java.awt.Color-) | Définit la couleur de surbrillance. |
|
|  | [isBold()](#isBold--) | Obtient un indicateur qui indique si le texte sera en gras ou non. |
|
|  | [setBold(boolean value)](#setBold-boolean-) | Définit un indicateur qui indique si le texte doit être en gras ou non. |
|
|  | [isUnderline()](#isUnderline--) | Obtient un indicateur qui indique si le texte sera souligné ou non. |
|
|  | [setUnderline(boolean value)](#setUnderline-boolean-) | Définit un indicateur qui indique si le texte doit être souligné ou non. |
|
|  | [isItalic()](#isItalic--) | Obtient un indicateur qui indique si le texte sera en italique ou non. |
|
|  | [setItalic(boolean value)](#setItalic-boolean-) | Définit un indicateur qui indique si le texte doit être en italique ou non. |
|
|  | [isStrikethrough()](#isStrikethrough--) | Obtient un indicateur qui indique si le texte sera barré ou non. |
|
|  | [setStrikethrough(boolean value)](#setStrikethrough-boolean-) | Définit un indicateur qui indique si le texte doit être barré ou non. |
|
|  | [getStartStringSeparator()](#getStartStringSeparator--) | Obtient le séparateur de chaîne de début. |
|
|  | [setStartStringSeparator(String value)](#setStartStringSeparator-java.lang.String-) | Définit le séparateur de chaîne de début. |
|
|  | [getEndStringSeparator()](#getEndStringSeparator--) | Obtient le séparateur de chaîne de fin. |
|
|  | [setEndStringSeparator(String value)](#setEndStringSeparator-java.lang.String-) | Définit le séparateur de chaîne de fin. |
|
|  | [getOriginalSize()](#getOriginalSize--) | Obtient la taille originale des documents comparés. |
|
|  | [setOriginalSize(Size value)](#setOriginalSize-com.groupdocs.comparison.options.style.Size-) | Définit la taille originale des documents comparés. |
|
|  | [getWordsSeparators()](#getWordsSeparators--) | Obtient les caractères séparateurs de mots. |
|
|  | [setWordsSeparators(char[] value)](#setWordsSeparators-char---) | Définit les caractères séparateurs de mots. |
|
### StyleSettings() {#StyleSettings--}
```
public StyleSettings()
```


Initialise une nouvelle instance de la classe StyleSettings.


### getFontColor() {#getFontColor--}
```
public final Color getFontColor()
```


Obtient la couleur de la police.


**Returns:**
java.awt.Color - la couleur de la police.

### setFontColor(Color value) {#setFontColor-java.awt.Color-}
```
public final void setFontColor(Color value)
```


Définit la couleur de la police.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.awt.Color | La nouvelle couleur de police. |
|

### getShapeColor() {#getShapeColor--}
```
public final Color getShapeColor()
```


Obtient la couleur de la forme.


**Returns:**
java.awt.Color - la couleur de la forme.

### setShapeColor(Color value) {#setShapeColor-java.awt.Color-}
```
public final void setShapeColor(Color value)
```


Définit la couleur de la forme.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.awt.Color | La nouvelle couleur de forme. |
|

### getHighlightColor() {#getHighlightColor--}
```
public final Color getHighlightColor()
```


Obtient la couleur de surbrillance.


**Returns:**
java.awt.Color - la couleur de surbrillance.

### setHighlightColor(Color value) {#setHighlightColor-java.awt.Color-}
```
public final void setHighlightColor(Color value)
```


Définit la couleur de surbrillance.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.awt.Color | La nouvelle couleur de surbrillance. |
|

### isBold() {#isBold--}
```
public final boolean isBold()
```


Obtient un indicateur qui indique si le texte sera en gras ou non.


**Returns:**
boolean - vrai si le texte sera en gras, faux sinon.

### setBold(boolean value) {#setBold-boolean-}
```
public final void setBold(boolean value)
```


Définit un indicateur qui indique si le texte doit être en gras ou non.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | boolean | vrai si le texte doit être en gras, faux sinon. |
|

### isUnderline() {#isUnderline--}
```
public final boolean isUnderline()
```


Obtient un indicateur qui indique si le texte sera souligné ou non.


**Returns:**
boolean - vrai si le texte sera souligné, faux sinon.

### setUnderline(boolean value) {#setUnderline-boolean-}
```
public final void setUnderline(boolean value)
```


Définit un indicateur qui indique si le texte doit être souligné ou non.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | boolean | vrai si le texte doit être souligné, faux sinon. |
|

### isItalic() {#isItalic--}
```
public final boolean isItalic()
```


Obtient un indicateur qui indique si le texte sera en italique ou non.


**Returns:**
boolean - vrai si le texte sera en italique, faux sinon.

### setItalic(boolean value) {#setItalic-boolean-}
```
public final void setItalic(boolean value)
```


Définit un indicateur qui indique si le texte doit être en italique ou non.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | boolean | vrai si le texte doit être en italique, faux sinon. |
|

### isStrikethrough() {#isStrikethrough--}
```
public final boolean isStrikethrough()
```


Obtient un indicateur qui indique si le texte sera barré ou non.


**Returns:**
boolean - vrai si le texte sera barré, faux sinon.

### setStrikethrough(boolean value) {#setStrikethrough-boolean-}
```
public final void setStrikethrough(boolean value)
```


Définit un indicateur qui indique si le texte doit être barré ou non.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | boolean | vrai si le texte doit être barré, faux sinon. |
|

### getStartStringSeparator() {#getStartStringSeparator--}
```
public final String getStartStringSeparator()
```


Obtient le séparateur de chaîne de début.


**Returns:**
java.lang.String - le séparateur de chaîne de début.

### setStartStringSeparator(String value) {#setStartStringSeparator-java.lang.String-}
```
public final void setStartStringSeparator(String value)
```


Définit le séparateur de chaîne de début.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.lang.String | Le nouveau séparateur de chaîne de début. |
|

### getEndStringSeparator() {#getEndStringSeparator--}
```
public final String getEndStringSeparator()
```


Obtient le séparateur de chaîne de fin.


**Returns:**
java.lang.String - le séparateur de chaîne de fin.

### setEndStringSeparator(String value) {#setEndStringSeparator-java.lang.String-}
```
public final void setEndStringSeparator(String value)
```


Définit le séparateur de chaîne de fin.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.lang.String | Le nouveau séparateur de chaîne de fin. |
|

### getOriginalSize() {#getOriginalSize--}
```
public final Size getOriginalSize()
```


Obtient la taille originale des documents comparés.


**Returns:**
[Size](../../com.groupdocs.comparison.options.style/size) - the original size of comparing documents.

### setOriginalSize(Size value) {#setOriginalSize-com.groupdocs.comparison.options.style.Size-}
```
public final void setOriginalSize(Size value)
```


Définit la taille originale des documents comparés.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [Size](../../com.groupdocs.comparison.options.style/size) | La nouvelle taille originale des documents comparés. |
|

### getWordsSeparators() {#getWordsSeparators--}
```
public final char[] getWordsSeparators()
```


Obtient les caractères séparateurs de mots.


**Returns:**
char[] - les séparateurs de mots.

### setWordsSeparators(char[] value) {#setWordsSeparators-char---}
```
public final void setWordsSeparators(char[] value)
```


Définit les caractères séparateurs de mots.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | char[] | Les nouveaux séparateurs de mots. |
|

