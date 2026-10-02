---
title: "StyleSettings"
second_title: "Java 用 GroupDocs.Comparison API リファレンス"
description: "このクラスはテキスト書式設定のスタイル設定を表します。"
type: docs
weight: 12
url: /ja/java/com.groupdocs.comparison.options.style/stylesettings/
---
**Inheritance:**
java.lang.Object
```
public class StyleSettings
```

このクラスはテキスト書式設定のスタイル設定を表します。


このクラスを使用して、フォントカラー、ハイライトカラー、スタイル属性（太字、下線、斜体、取り消し線）をカスタマイズします。
文字列の区切り文字、元のサイズ、およびテキストの単語区切り文字。


使用例:

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


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [StyleSettings()](#StyleSettings--) | StyleSettings クラスの新しいインスタンスを初期化します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getFontColor()](#getFontColor--) | フォントカラーを取得します。 |
|
|  | [setFontColor(Color value)](#setFontColor-java.awt.Color-) | フォントカラーを設定します。 |
|
|  | [getShapeColor()](#getShapeColor--) | シェイプカラーを取得します。 |
|
|  | [setShapeColor(Color value)](#setShapeColor-java.awt.Color-) | シェイプカラーを設定します。 |
|
|  | [getHighlightColor()](#getHighlightColor--) | ハイライトカラーを取得します。 |
|
|  | [setHighlightColor(Color value)](#setHighlightColor-java.awt.Color-) | ハイライトカラーを設定します。 |
|
|  | [isBold()](#isBold--) | テキストが太字になるかどうかを示すフラグを取得します。 |
|
|  | [setBold(boolean value)](#setBold-boolean-) | テキストを太字にするかどうかを示すフラグを設定します。 |
|
|  | [isUnderline()](#isUnderline--) | テキストが下線になるかどうかを示すフラグを取得します。 |
|
|  | [setUnderline(boolean value)](#setUnderline-boolean-) | テキストに下線を付けるかどうかを示すフラグを設定します。 |
|
|  | [isItalic()](#isItalic--) | テキストが斜体になるかどうかを示すフラグを取得します。 |
|
|  | [setItalic(boolean value)](#setItalic-boolean-) | テキストが斜体になるかどうかを示すフラグを設定します。 |
|
|  | [isStrikethrough()](#isStrikethrough--) | テキストに取り消し線が付くかどうかを示すフラグを取得します。 |
|
|  | [setStrikethrough(boolean value)](#setStrikethrough-boolean-) | テキストに取り消し線が付くかどうかを示すフラグを設定します。 |
|
|  | [getStartStringSeparator()](#getStartStringSeparator--) | 開始文字列の区切り文字を取得します。 |
|
|  | [setStartStringSeparator(String value)](#setStartStringSeparator-java.lang.String-) | 開始文字列の区切り文字を設定します。 |
|
|  | [getEndStringSeparator()](#getEndStringSeparator--) | 終了文字列の区切り文字を取得します。 |
|
|  | [setEndStringSeparator(String value)](#setEndStringSeparator-java.lang.String-) | 終了文字列の区切り文字を設定します。 |
|
|  | [getOriginalSize()](#getOriginalSize--) | 比較対象文書の元のサイズを取得します。 |
|
|  | [setOriginalSize(Size value)](#setOriginalSize-com.groupdocs.comparison.options.style.Size-) | 比較対象文書の元のサイズを設定します。 |
|
|  | [getWordsSeparators()](#getWordsSeparators--) | 単語の区切り文字を取得します。 |
|
|  | [setWordsSeparators(char[] value)](#setWordsSeparators-char---) | 単語の区切り文字を設定します。 |
|
### StyleSettings() {#StyleSettings--}
```
public StyleSettings()
```


StyleSettings クラスの新しいインスタンスを初期化します。


### getFontColor() {#getFontColor--}
```
public final Color getFontColor()
```


フォントカラーを取得します。


**Returns:**
java.awt.Color - フォントの色です。

### setFontColor(Color value) {#setFontColor-java.awt.Color-}
```
public final void setFontColor(Color value)
```


フォントカラーを設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | java.awt.Color | 新しいフォントの色です。 |
|

### getShapeColor() {#getShapeColor--}
```
public final Color getShapeColor()
```


シェイプカラーを取得します。


**Returns:**
java.awt.Color - シェイプの色です。

### setShapeColor(Color value) {#setShapeColor-java.awt.Color-}
```
public final void setShapeColor(Color value)
```


シェイプカラーを設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | java.awt.Color | 新しいシェイプの色です。 |
|

### getHighlightColor() {#getHighlightColor--}
```
public final Color getHighlightColor()
```


ハイライトカラーを取得します。


**Returns:**
java.awt.Color - ハイライトの色です。

### setHighlightColor(Color value) {#setHighlightColor-java.awt.Color-}
```
public final void setHighlightColor(Color value)
```


ハイライトカラーを設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | java.awt.Color | 新しいハイライトの色です。 |
|

### isBold() {#isBold--}
```
public final boolean isBold()
```


テキストが太字になるかどうかを示すフラグを取得します。


**Returns:**
boolean - テキストが太字になる場合は true、そうでない場合は false。

### setBold(boolean value) {#setBold-boolean-}
```
public final void setBold(boolean value)
```


テキストを太字にするかどうかを示すフラグを設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | boolean | テキストが太字であるべき場合は true、そうでない場合は false。 |
|

### isUnderline() {#isUnderline--}
```
public final boolean isUnderline()
```


テキストが下線になるかどうかを示すフラグを取得します。


**Returns:**
boolean - テキストに下線が付く場合は true、そうでない場合は false。

### setUnderline(boolean value) {#setUnderline-boolean-}
```
public final void setUnderline(boolean value)
```


テキストに下線を付けるかどうかを示すフラグを設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | boolean | テキストに下線が付くべき場合は true、そうでない場合は false。 |
|

### isItalic() {#isItalic--}
```
public final boolean isItalic()
```


テキストが斜体になるかどうかを示すフラグを取得します。


**Returns:**
boolean - テキストが斜体になる場合は true、そうでない場合は false。

### setItalic(boolean value) {#setItalic-boolean-}
```
public final void setItalic(boolean value)
```


テキストが斜体になるかどうかを示すフラグを設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | boolean | テキストを斜体にすべき場合は true、そうでなければ false。 |
|

### isStrikethrough() {#isStrikethrough--}
```
public final boolean isStrikethrough()
```


テキストに取り消し線が付くかどうかを示すフラグを取得します。


**Returns:**
boolean - テキストが取り消し線になる場合は true、そうでなければ false。

### setStrikethrough(boolean value) {#setStrikethrough-boolean-}
```
public final void setStrikethrough(boolean value)
```


テキストに取り消し線が付くかどうかを示すフラグを設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | boolean | テキストを取り消し線にすべき場合は true、そうでなければ false。 |
|

### getStartStringSeparator() {#getStartStringSeparator--}
```
public final String getStartStringSeparator()
```


開始文字列の区切り文字を取得します。


**Returns:**
java.lang.String - 開始文字列の区切り文字。

### setStartStringSeparator(String value) {#setStartStringSeparator-java.lang.String-}
```
public final void setStartStringSeparator(String value)
```


開始文字列の区切り文字を設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | java.lang.String | 新しい開始文字列の区切り文字。 |
|

### getEndStringSeparator() {#getEndStringSeparator--}
```
public final String getEndStringSeparator()
```


終了文字列の区切り文字を取得します。


**Returns:**
java.lang.String - 終了文字列の区切り文字。

### setEndStringSeparator(String value) {#setEndStringSeparator-java.lang.String-}
```
public final void setEndStringSeparator(String value)
```


終了文字列の区切り文字を設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | java.lang.String | 新しい終了文字列の区切り文字。 |
|

### getOriginalSize() {#getOriginalSize--}
```
public final Size getOriginalSize()
```


比較対象文書の元のサイズを取得します。


**Returns:**
[Size](../../com.groupdocs.comparison.options.style/size) - the original size of comparing documents.

### setOriginalSize(Size value) {#setOriginalSize-com.groupdocs.comparison.options.style.Size-}
```
public final void setOriginalSize(Size value)
```


比較対象文書の元のサイズを設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | value | [Size](../../com.groupdocs.comparison.options.style/size) | 比較文書の新しい元サイズ。 |
|

### getWordsSeparators() {#getWordsSeparators--}
```
public final char[] getWordsSeparators()
```


単語の区切り文字を取得します。


**Returns:**
char[] - 単語の区切り文字。

### setWordsSeparators(char[] value) {#setWordsSeparators-char---}
```
public final void setWordsSeparators(char[] value)
```


単語の区切り文字を設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | char[] | 新しい単語の区切り文字。 |
|

