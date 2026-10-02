---
title: "PaperSize"
second_title: "Java 用 GroupDocs.Comparison API リファレンス"
description: "文書比較の用紙サイズオプションを表します。"
type: docs
weight: 13
url: /ja/java/com.groupdocs.comparison.options.enums/papersize/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PaperSize extends Enum<PaperSize>
```

文書比較の用紙サイズオプションを表します。


使用例:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setPaperSize(PaperSize.A6);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [DEFAULT](#DEFAULT) | デフォルトの用紙サイズです。 |
|
|  | [A0](#A0) | 標準用紙サイズ A0 (841mm x 1189mm)。 |
|
|  | [A1](#A1) | 標準用紙サイズ A1 (594mm x 841mm)。 |
|
|  | [A2](#A2) | 標準用紙サイズ A2 (420mm x 594mm)。 |
|
|  | [A3](#A3) | 標準用紙サイズ A3 (297mm x 420mm)。 |
|
|  | [A4](#A4) | 標準用紙サイズ A4 (210mm x 297mm)。 |
|
|  | [A5](#A5) | 標準用紙サイズ A5 (148mm x 210mm)。 |
|
|  | [A6](#A6) | 標準用紙サイズ A6 (105mm x 148mm)。 |
|
|  | [A7](#A7) | 標準用紙サイズ A7 (74mm x 105mm)。 |
|
|  | [A8](#A8) | 標準用紙サイズ A8 (52mm x 74mm)。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | PaperSize の文字列表現を解析して列挙体定数を取得します。 |
|
|  | [toString()](#toString--) | PaperSize の文字列表現。 |
|
### DEFAULT {#DEFAULT}
```
public static final PaperSize DEFAULT
```


デフォルトの用紙サイズです。


### A0 {#A0}
```
public static final PaperSize A0
```


標準用紙サイズ A0 (841mm x 1189mm)。


### A1 {#A1}
```
public static final PaperSize A1
```


標準用紙サイズ A1 (594mm x 841mm)。


### A2 {#A2}
```
public static final PaperSize A2
```


標準用紙サイズ A2 (420mm x 594mm)。


### A3 {#A3}
```
public static final PaperSize A3
```


標準用紙サイズ A3 (297mm x 420mm)。


### A4 {#A4}
```
public static final PaperSize A4
```


標準用紙サイズ A4 (210mm x 297mm)。


### A5 {#A5}
```
public static final PaperSize A5
```


標準用紙サイズ A5 (148mm x 210mm)。


### A6 {#A6}
```
public static final PaperSize A6
```


標準用紙サイズ A6 (105mm x 148mm)。


### A7 {#A7}
```
public static final PaperSize A7
```


標準用紙サイズ A7 (74mm x 105mm)。


### A8 {#A8}
```
public static final PaperSize A8
```


標準用紙サイズ A8 (52mm x 74mm)。


### values() {#values--}
```
public static PaperSize[] values()
```




**Returns:**
com.groupdocs.comparison.options.enums.PaperSize[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PaperSize valueOf(String name)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[PaperSize](../../com.groupdocs.comparison.options.enums/papersize)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static PaperSize fromString(String toStringValue)
```


PaperSize の文字列表現を解析して列挙体定数を取得します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | toStringValue | java.lang.String | PaperSize の文字列表現 |
|

**Returns:**
[PaperSize](../../com.groupdocs.comparison.options.enums/papersize) - PaperSize enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


PaperSize の文字列表現。


**Returns:**
java.lang.String - 列挙定数の文字列値

