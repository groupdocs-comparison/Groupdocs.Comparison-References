---
title: "StyleSettings"
second_title: "Referensi API GroupDocs.Comparison untuk Java"
description: "Kelas ini mewakili pengaturan gaya untuk pemformatan teks."
type: docs
weight: 12
url: /id/java/com.groupdocs.comparison.options.style/stylesettings/
---
**Inheritance:**
java.lang.Object
```
public class StyleSettings
```

Kelas ini mewakili pengaturan gaya untuk pemformatan teks.


Gunakan kelas ini untuk menyesuaikan warna font, warna sorotan, atribut gaya (bold, underline, italic, strikethrough),
pemisah string, ukuran asli, dan pemisah kata untuk teks.


Contoh penggunaan:

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


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [StyleSettings()](#StyleSettings--) | Menginisialisasi instance baru dari kelas StyleSettings. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getFontColor()](#getFontColor--) | Mendapatkan warna font. |
|
|  | [setFontColor(Color value)](#setFontColor-java.awt.Color-) | Mengatur warna font. |
|
|  | [getShapeColor()](#getShapeColor--) | Mendapatkan warna bentuk. |
|
|  | [setShapeColor(Color value)](#setShapeColor-java.awt.Color-) | Mengatur warna bentuk. |
|
|  | [getHighlightColor()](#getHighlightColor--) | Mendapatkan warna sorotan. |
|
|  | [setHighlightColor(Color value)](#setHighlightColor-java.awt.Color-) | Mengatur warna sorotan. |
|
|  | [isBold()](#isBold--) | Mendapatkan flag yang menunjukkan apakah teks akan tebal atau tidak. |
|
|  | [setBold(boolean value)](#setBold-boolean-) | Mengatur flag yang menunjukkan apakah teks harus tebal atau tidak. |
|
|  | [isUnderline()](#isUnderline--) | Mendapatkan flag yang menunjukkan apakah teks akan digarisbawahi atau tidak. |
|
|  | [setUnderline(boolean value)](#setUnderline-boolean-) | Mengatur flag yang menunjukkan apakah teks harus digarisbawahi atau tidak. |
|
|  | [isItalic()](#isItalic--) | Mendapatkan flag yang menunjukkan apakah teks akan miring atau tidak. |
|
|  | [setItalic(boolean value)](#setItalic-boolean-) | Mengatur flag yang menunjukkan apakah teks harus miring atau tidak. |
|
|  | [isStrikethrough()](#isStrikethrough--) | Mendapatkan flag yang menunjukkan apakah teks akan dicoret atau tidak. |
|
|  | [setStrikethrough(boolean value)](#setStrikethrough-boolean-) | Mengatur flag yang menunjukkan apakah teks harus dicoret atau tidak. |
|
|  | [getStartStringSeparator()](#getStartStringSeparator--) | Mendapatkan pemisah string awal. |
|
|  | [setStartStringSeparator(String value)](#setStartStringSeparator-java.lang.String-) | Mengatur pemisah string awal. |
|
|  | [getEndStringSeparator()](#getEndStringSeparator--) | Mendapatkan pemisah string akhir. |
|
|  | [setEndStringSeparator(String value)](#setEndStringSeparator-java.lang.String-) | Mengatur pemisah string akhir. |
|
|  | [getOriginalSize()](#getOriginalSize--) | Mendapatkan ukuran asli dokumen yang dibandingkan. |
|
|  | [setOriginalSize(Size value)](#setOriginalSize-com.groupdocs.comparison.options.style.Size-) | Mengatur ukuran asli dokumen yang dibandingkan. |
|
|  | [getWordsSeparators()](#getWordsSeparators--) | Mendapatkan karakter pemisah kata. |
|
|  | [setWordsSeparators(char[] value)](#setWordsSeparators-char---) | Mengatur karakter pemisah kata. |
|
### StyleSettings() {#StyleSettings--}
```
public StyleSettings()
```


Menginisialisasi instance baru dari kelas StyleSettings.


### getFontColor() {#getFontColor--}
```
public final Color getFontColor()
```


Mendapatkan warna font.


**Returns:**
java.awt.Color - warna font.

### setFontColor(Color value) {#setFontColor-java.awt.Color-}
```
public final void setFontColor(Color value)
```


Mengatur warna font.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | java.awt.Color | Warna font baru. |
|

### getShapeColor() {#getShapeColor--}
```
public final Color getShapeColor()
```


Mendapatkan warna bentuk.


**Returns:**
java.awt.Color - warna bentuk.

### setShapeColor(Color value) {#setShapeColor-java.awt.Color-}
```
public final void setShapeColor(Color value)
```


Mengatur warna bentuk.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | java.awt.Color | Warna bentuk baru. |
|

### getHighlightColor() {#getHighlightColor--}
```
public final Color getHighlightColor()
```


Mendapatkan warna sorotan.


**Returns:**
java.awt.Color - warna sorotan.

### setHighlightColor(Color value) {#setHighlightColor-java.awt.Color-}
```
public final void setHighlightColor(Color value)
```


Mengatur warna sorotan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | java.awt.Color | Warna sorotan baru. |
|

### isBold() {#isBold--}
```
public final boolean isBold()
```


Mendapatkan flag yang menunjukkan apakah teks akan tebal atau tidak.


**Returns:**
boolean - true jika teks akan tebal, false jika tidak.

### setBold(boolean value) {#setBold-boolean-}
```
public final void setBold(boolean value)
```


Mengatur flag yang menunjukkan apakah teks harus tebal atau tidak.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | boolean | true jika teks harus tebal, false jika tidak. |
|

### isUnderline() {#isUnderline--}
```
public final boolean isUnderline()
```


Mendapatkan flag yang menunjukkan apakah teks akan digarisbawahi atau tidak.


**Returns:**
boolean - true jika teks akan digarisbawahi, false jika tidak.

### setUnderline(boolean value) {#setUnderline-boolean-}
```
public final void setUnderline(boolean value)
```


Mengatur flag yang menunjukkan apakah teks harus digarisbawahi atau tidak.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | boolean | true jika teks harus digarisbawahi, false jika tidak. |
|

### isItalic() {#isItalic--}
```
public final boolean isItalic()
```


Mendapatkan flag yang menunjukkan apakah teks akan miring atau tidak.


**Returns:**
boolean - true jika teks akan miring, false jika tidak.

### setItalic(boolean value) {#setItalic-boolean-}
```
public final void setItalic(boolean value)
```


Mengatur flag yang menunjukkan apakah teks harus miring atau tidak.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | boolean | true jika teks harus miring, false jika tidak. |
|

### isStrikethrough() {#isStrikethrough--}
```
public final boolean isStrikethrough()
```


Mendapatkan flag yang menunjukkan apakah teks akan dicoret atau tidak.


**Returns:**
boolean - true jika teks akan dicoret, false jika tidak.

### setStrikethrough(boolean value) {#setStrikethrough-boolean-}
```
public final void setStrikethrough(boolean value)
```


Mengatur flag yang menunjukkan apakah teks harus dicoret atau tidak.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | boolean | true jika teks harus dicoret, false jika tidak. |
|

### getStartStringSeparator() {#getStartStringSeparator--}
```
public final String getStartStringSeparator()
```


Mendapatkan pemisah string awal.


**Returns:**
java.lang.String - pemisah string awal.

### setStartStringSeparator(String value) {#setStartStringSeparator-java.lang.String-}
```
public final void setStartStringSeparator(String value)
```


Mengatur pemisah string awal.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | java.lang.String | Pemisah string awal baru. |
|

### getEndStringSeparator() {#getEndStringSeparator--}
```
public final String getEndStringSeparator()
```


Mendapatkan pemisah string akhir.


**Returns:**
java.lang.String - pemisah string akhir.

### setEndStringSeparator(String value) {#setEndStringSeparator-java.lang.String-}
```
public final void setEndStringSeparator(String value)
```


Mengatur pemisah string akhir.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | java.lang.String | Pemisah string akhir baru. |
|

### getOriginalSize() {#getOriginalSize--}
```
public final Size getOriginalSize()
```


Mendapatkan ukuran asli dokumen yang dibandingkan.


**Returns:**
[Size](../../com.groupdocs.comparison.options.style/size) - the original size of comparing documents.

### setOriginalSize(Size value) {#setOriginalSize-com.groupdocs.comparison.options.style.Size-}
```
public final void setOriginalSize(Size value)
```


Mengatur ukuran asli dokumen yang dibandingkan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [Size](../../com.groupdocs.comparison.options.style/size) | Ukuran asli baru dari dokumen perbandingan. |
|

### getWordsSeparators() {#getWordsSeparators--}
```
public final char[] getWordsSeparators()
```


Mendapatkan karakter pemisah kata.


**Returns:**
char[] - pemisah kata.

### setWordsSeparators(char[] value) {#setWordsSeparators-char---}
```
public final void setWordsSeparators(char[] value)
```


Mengatur karakter pemisah kata.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | char[] | Pemisah kata baru. |
|

