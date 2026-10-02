---
title: "ComparisonType"
second_title: "Java 用 GroupDocs.Comparison API リファレンス"
description: "実行される比較のタイプを表します。"
type: docs
weight: 10
url: /ja/java/com.groupdocs.comparison.options.enums/comparisontype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ComparisonType extends Enum<ComparisonType>
```

実行される比較のタイプを表します。


使用例:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setComparisonType(ComparisonType.CELLS);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [TEXT](#TEXT) | ファイルはテキスト文書として比較する必要があります。 |
|
|  | [SLIDES](#SLIDES) | ファイルはプレゼンテーション文書として比較する必要があります。 |
|
|  | [WORDS](#WORDS) | ファイルは Word 文書として比較する必要があります。 |
|
|  | [CELLS](#CELLS) | ファイルは Excel 文書として比較する必要があります。 |
|
|  | [PDF](#PDF) | ファイルは PDF 文書として比較する必要があります。 |
|
|  | [IMAGING](#IMAGING) | ファイルは画像文書として比較する必要があります。 |
|
|  | [EMAIL](#EMAIL) | ファイルはメール文書として比較する必要があります。 |
|
|  | [NOTE](#NOTE) | ファイルはノート文書として比較する必要があります。 |
|
|  | [HTML](#HTML) | ファイルは HTML 文書として比較する必要があります。 |
|
|  | [DIAGRAM](#DIAGRAM) | ファイルは図表文書として比較する必要があります。 |
|
|  | [DIFFERENT](#DIFFERENT) | ファイルは異なる形式の文書として比較する必要があります。 |
|
|  | [SVG](#SVG) | ファイルは SVG 文書として比較する必要があります。 |
|
|  | [UNDEFINED](#UNDEFINED) | 内部使用向けです。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | ComparisonType の文字列表現を解析して列挙体定数を取得します。 |
|
|  | [toString()](#toString--) | ComparisonType の文字列表現。 |
|
### TEXT {#TEXT}
```
public static final ComparisonType TEXT
```


ファイルはテキスト文書として比較する必要があります。


### SLIDES {#SLIDES}
```
public static final ComparisonType SLIDES
```


ファイルはプレゼンテーション文書として比較する必要があります。


### WORDS {#WORDS}
```
public static final ComparisonType WORDS
```


ファイルは Word 文書として比較する必要があります。


### CELLS {#CELLS}
```
public static final ComparisonType CELLS
```


ファイルは Excel 文書として比較する必要があります。


### PDF {#PDF}
```
public static final ComparisonType PDF
```


ファイルは PDF 文書として比較する必要があります。


### IMAGING {#IMAGING}
```
public static final ComparisonType IMAGING
```


ファイルは画像文書として比較する必要があります。


### EMAIL {#EMAIL}
```
public static final ComparisonType EMAIL
```


ファイルはメール文書として比較する必要があります。


### NOTE {#NOTE}
```
public static final ComparisonType NOTE
```


ファイルはノート文書として比較する必要があります。


### HTML {#HTML}
```
public static final ComparisonType HTML
```


ファイルは HTML 文書として比較する必要があります。


### DIAGRAM {#DIAGRAM}
```
public static final ComparisonType DIAGRAM
```


ファイルは図表文書として比較する必要があります。


### DIFFERENT {#DIFFERENT}
```
public static final ComparisonType DIFFERENT
```


ファイルは異なる形式の文書として比較する必要があります。


### SVG {#SVG}
```
public static final ComparisonType SVG
```


ファイルは SVG 文書として比較する必要があります。


### UNDEFINED {#UNDEFINED}
```
public static final ComparisonType UNDEFINED
```


内部使用向けです。


### values() {#values--}
```
public static ComparisonType[] values()
```




**Returns:**
com.groupdocs.comparison.options.enums.ComparisonType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static ComparisonType valueOf(String name)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static ComparisonType fromString(String toStringValue)
```


ComparisonType の文字列表現を解析して列挙体定数を取得します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | toStringValue | java.lang.String | ComparisonType の文字列表現 |
|

**Returns:**
[ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) - ComparisonType enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


ComparisonType の文字列表現。


**Returns:**
java.lang.String - 列挙定数の文字列値

