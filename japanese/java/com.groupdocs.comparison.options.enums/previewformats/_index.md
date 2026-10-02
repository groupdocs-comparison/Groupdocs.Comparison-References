---
title: "PreviewFormats"
second_title: "Java 用 GroupDocs.Comparison API リファレンス"
description: "文書比較でサポートされているプレビュー形式を列挙します。"
type: docs
weight: 15
url: /ja/java/com.groupdocs.comparison.options.enums/previewformats/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PreviewFormats extends Enum<PreviewFormats>
```

文書比較でサポートされているプレビュー形式を列挙します。
PreviewFormats 列挙体は、比較された文書のプレビューを生成するために使用できるフォーマットの一覧を提供します。

サポートされているフォーマットは次のとおりです：

* #PNG.PNG - Portable Network Graphics (.png)
* #JPEG.JPEG - Joint Photographic Experts Group (.jpeg)
* #BMP.BMP - Bitmap Picture (.bmp)


使用例:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    PreviewOptions previewOptions = new PreviewOptions(
            pageNumber -> Files.newOutputStream(Paths.get(String.format("preview-page_%d.png", pageNumber)))
    );
    previewOptions.setPreviewFormat(PreviewFormats.PNG);

    comparer.getTargets().get(0).generatePreview(previewOptions);
 }
 
````


## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [PNG](#PNG) | PNG - ページに多数のカラーグラフィックが含まれる場合、かなりのディスク容量やネットワークトラフィックを消費する可能性があります。 |
|
|  | [JPEG](#JPEG) | Jpeg - ディスク容量とネットワークトラフィックが少なく、処理が高速ですが、画像品質が低下する可能性があります。 |
|
|  | [BMP](#BMP) | BMP - 最高の画像品質を提供しますが、処理が遅く、ディスク容量とネットワークトラフィックが多く必要です。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | PreviewFormats の文字列表現を解析して列挙体定数を取得します。 |
|
|  | [toString()](#toString--) | PreviewFormats の文字列表現。 |
|
### PNG {#PNG}
```
public static final PreviewFormats PNG
```


PNG - ページに多数のカラーグラフィックが含まれる場合、ディスク容量やネットワークトラフィックを大量に消費する可能性があります。デフォルトのプレビュー形式です。


### JPEG {#JPEG}
```
public static final PreviewFormats JPEG
```


Jpeg - ディスク容量とネットワークトラフィックが少なく、処理が高速ですが、画像品質が低下する可能性があります。


### BMP {#BMP}
```
public static final PreviewFormats BMP
```


BMP - 最高の画像品質を提供しますが、処理が遅く、ディスク容量とネットワークトラフィックが多く必要です。


### values() {#values--}
```
public static PreviewFormats[] values()
```




**Returns:**
com.groupdocs.comparison.options.enums.PreviewFormats[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PreviewFormats valueOf(String name)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static PreviewFormats fromString(String toStringValue)
```


PreviewFormats の文字列表現を解析して列挙体定数を取得します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | toStringValue | java.lang.String | PreviewFormats の文字列表現 |
|

**Returns:**
[PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats) - PreviewFormats enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


PreviewFormats の文字列表現。


**Returns:**
java.lang.String - 列挙定数の文字列値

