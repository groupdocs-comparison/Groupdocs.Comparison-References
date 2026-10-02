---
title: "PreviewOptions"
second_title: "Java 用 GroupDocs.Comparison API リファレンス"
description: "比較プロセスでドキュメントプレビューを生成するためのオプションを提供します。"
type: docs
weight: 15
url: /ja/java/com.groupdocs.comparison.options/previewoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewOptions
```

比較プロセスでドキュメントプレビューを生成するためのオプションを提供します。


使用例:

````

 try (Comparer comparer = new Comparer(sourceFile)) {

    PreviewOptions previewOptions = new PreviewOptions(
            pageNumber -> Files.newOutputStream(Paths.get(String.format("preview-page_%d.png", pageNumber)))
    );
    previewOptions.setPreviewFormat(PreviewFormats.PNG);
    previewOptions.setPageNumbers(new int[]{1, 2});

    comparer.getSource().generatePreview(previewOptions);
 }
 
````


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [PreviewOptions(Delegates.CreatePageStream createPageStream)](#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-) | Delegates.CreatePageStream 関数を指定して PreviewOptions クラスの新しいインスタンスを初期化します。 |
|
|  | [PreviewOptions(CreatePageStreamFunction createPageStream)](#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-) | PreviewOptions クラスの新しいインスタンスを初期化し、[CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) 関数を指定します。 |
|
|  | [PreviewOptions(Delegates.CreatePageStream createPageStream, Delegates.ReleasePageStream releasePageStream)](#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-) | Delegates.CreatePageStream と Delegates.ReleasePageStream 関数を指定して PreviewOptions クラスの新しいインスタンスを初期化します。 |
|
|  | [PreviewOptions(CreatePageStreamFunction createPageStream, ReleasePageStreamFunction releasePageStream)](#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-) | PreviewOptions クラスの新しいインスタンスを初期化し、[CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) と [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) 関数を指定します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getCreatePageStream()](#getCreatePageStream--) | 出力ページプレビュー ストリームを作成する関数を取得します。 |
|
|  | [setCreatePageStream(Delegates.CreatePageStream createPageStream)](#setCreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-) | 出力ページプレビュー ストリームを作成する関数を設定します。 |
|
|  | [setCreatePageStream(CreatePageStreamFunction createPageStream)](#setCreatePageStream-com.groupdocs.comparison.common.function.CreatePageStreamFunction-) | 出力ページプレビュー ストリームを作成する関数を設定します。 |
|
|  | [getReleasePageStream()](#getReleasePageStream--) | 出力ページプレビュー ストリームを解放する関数を取得します。 |
|
|  | [setReleasePageStream(Delegates.ReleasePageStream releasePageStream)](#setReleasePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-) | 出力ページプレビュー ストリームを解放する関数を取得します。 |
|
|  | [setReleasePageStream(ReleasePageStreamFunction releasePageStream)](#setReleasePageStream-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-) | 出力ページプレビュー ストリームを解放する関数を設定します。 |
|
|  | [getWidth()](#getWidth--) | プレビュー画像の幅を取得します。 |
|
|  | [setWidth(int value)](#setWidth-int-) | プレビュー画像の幅を設定します。 |
|
|  | [getHeight()](#getHeight--) | プレビュー画像の高さを取得します。 |
|
|  | [setHeight(int value)](#setHeight-int-) | プレビュー画像の高さを設定します。 |
|
|  | [getPageNumbers()](#getPageNumbers--) | プレビュー画像が生成されるページ番号の配列を取得します。 |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | プレビュー画像が生成されるページ番号の配列を設定します。 |
|
|  | [getPreviewFormat()](#getPreviewFormat--) | プレビュー画像の形式を取得します。 |
|
|  | [setPreviewFormat(PreviewFormats value)](#setPreviewFormat-com.groupdocs.comparison.options.enums.PreviewFormats-) | プレビュー画像の形式を設定します。 |
|
### PreviewOptions(Delegates.CreatePageStream createPageStream) {#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-}
```
public PreviewOptions(Delegates.CreatePageStream createPageStream)
```


Delegates.CreatePageStream 関数を指定して PreviewOptions クラスの新しいインスタンスを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.comparison.common.delegates/createpagestream) | 出力ページプレビュー ストリームを作成する関数です。 |
|

### PreviewOptions(CreatePageStreamFunction createPageStream) {#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-}
```
public PreviewOptions(CreatePageStreamFunction createPageStream)
```


PreviewOptions クラスの新しいインスタンスを初期化し、[CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) 関数を指定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | createPageStream | [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) | 出力ページプレビュー ストリームを作成する関数です。 |
|

### PreviewOptions(Delegates.CreatePageStream createPageStream, Delegates.ReleasePageStream releasePageStream) {#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-}
```
public PreviewOptions(Delegates.CreatePageStream createPageStream, Delegates.ReleasePageStream releasePageStream)
```


Delegates.CreatePageStream と Delegates.ReleasePageStream 関数を指定して PreviewOptions クラスの新しいインスタンスを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.comparison.common.delegates/createpagestream) | 出力ページプレビュー ストリームを作成する関数です。 |
|
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.comparison.common.delegates/releasepagestream) | 出力ページプレビュー ストリームを解放する関数です。 |
|

### PreviewOptions(CreatePageStreamFunction createPageStream, ReleasePageStreamFunction releasePageStream) {#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-}
```
public PreviewOptions(CreatePageStreamFunction createPageStream, ReleasePageStreamFunction releasePageStream)
```


PreviewOptions クラスの新しいインスタンスを初期化し、[CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) と [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) 関数を指定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | createPageStream | [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) | 出力ページプレビュー ストリームを作成する関数です。 |
|
|  | releasePageStream | [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) | 出力ページプレビュー ストリームを解放する関数です。 |
|

### getCreatePageStream() {#getCreatePageStream--}
```
public CreatePageStreamFunction getCreatePageStream()
```


出力ページプレビュー ストリームを作成する関数を取得します。


**Returns:**
[CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) - the function to create output page preview stream.

### setCreatePageStream(Delegates.CreatePageStream createPageStream) {#setCreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-}
```
public void setCreatePageStream(Delegates.CreatePageStream createPageStream)
```


出力ページプレビュー ストリームを作成する関数を設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.comparison.common.delegates/createpagestream) | 出力ページプレビュー ストリームを作成する関数です。 |
|

### setCreatePageStream(CreatePageStreamFunction createPageStream) {#setCreatePageStream-com.groupdocs.comparison.common.function.CreatePageStreamFunction-}
```
public void setCreatePageStream(CreatePageStreamFunction createPageStream)
```


出力ページプレビュー ストリームを作成する関数を設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | createPageStream | [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) | 出力ページプレビュー ストリームを作成する関数です。 |
|

### getReleasePageStream() {#getReleasePageStream--}
```
public ReleasePageStreamFunction getReleasePageStream()
```


出力ページプレビュー ストリームを解放する関数を取得します。


**Returns:**
[ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) - the function to release output page preview stream.

### setReleasePageStream(Delegates.ReleasePageStream releasePageStream) {#setReleasePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-}
```
public void setReleasePageStream(Delegates.ReleasePageStream releasePageStream)
```


出力ページプレビュー ストリームを解放する関数を取得します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.comparison.common.delegates/releasepagestream) | 出力ページプレビュー ストリームを解放する関数です。 |
|

### setReleasePageStream(ReleasePageStreamFunction releasePageStream) {#setReleasePageStream-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-}
```
public void setReleasePageStream(ReleasePageStreamFunction releasePageStream)
```


出力ページプレビュー ストリームを解放する関数を設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | releasePageStream | [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) | 出力ページプレビュー ストリームを解放する関数です。 |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


プレビュー画像の幅を取得します。


**Returns:**
int - プレビュー画像の幅。

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


プレビュー画像の幅を設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | int | プレビュー画像の幅。 |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


プレビュー画像の高さを取得します。


**Returns:**
int - プレビュー画像の高さ。

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


プレビュー画像の高さを設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | int | プレビュー画像の高さ。 |
|

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


プレビュー画像が生成されるページ番号の配列を取得します。


**Returns:**
int[] - ページ番号配列

### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


プレビュー画像が生成されるページ番号の配列を設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | int[] | ページ番号配列 |
|

### getPreviewFormat() {#getPreviewFormat--}
```
public final PreviewFormats getPreviewFormat()
```


プレビュー画像の形式を取得します。


**Returns:**
[PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats) - preview images format

### setPreviewFormat(PreviewFormats value) {#setPreviewFormat-com.groupdocs.comparison.options.enums.PreviewFormats-}
```
public final void setPreviewFormat(PreviewFormats value)
```


プレビュー画像の形式を設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | value | [PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats) | プレビュー画像の形式 |
|

