---
title: "ドキュメント"
second_title: "Java 用 GroupDocs.Comparison API リファレンス"
description: "比較プロセス用のドキュメントを表します。"
type: docs
weight: 12
url: /ja/java/com.groupdocs.comparison/document/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Document implements Closeable
```

比較プロセス用のドキュメントを表します。


Document クラスは、比較プロセス中にドキュメントをロードし、プレビュー画像を生成し、操作するためのメソッドを提供します。


使用例:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     try (IDocumentInfo info = comparer.getSource().getDocumentInfo()) {
         System.out.println("File type: " + info.getFileType());
         System.out.println("Number of pages: " + info.getPageCount());
         System.out.println("Document size: " + info.getSize());
     }
 }
 
````


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [Document(InputStream stream)](#Document-java.io.InputStream-) | 指定されたドキュメント ストリームで Document クラスの新しいインスタンスを初期化します。 |
|
|  | [Document(String filePath)](#Document-java.lang.String-) | 指定されたドキュメント パスで Document クラスの新しいインスタンスを初期化します。 |
|
|  | [Document(Path filePath)](#Document-java.nio.file.Path-) | 指定されたドキュメント パスで Document クラスの新しいインスタンスを初期化します。 |
|
|  | [Document(Path filePath, String password)](#Document-java.nio.file.Path-java.lang.String-) | 指定されたドキュメント パスとパスワードで Document クラスの新しいインスタンスを初期化します。 |
|
|  | [Document(Path filePath, LoadOptions loadOptions)](#Document-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-) | 指定されたドキュメント パスとロード オプションで Document クラスの新しいインスタンスを初期化します。 |
|
|  | [Document(String filePath, String password)](#Document-java.lang.String-java.lang.String-) | 指定されたドキュメント パスとパスワードで Document クラスの新しいインスタンスを初期化します。 |
|
|  | [Document(String filePath, LoadOptions loadOptions)](#Document-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-) | 指定されたドキュメント パスとロード オプションで Document クラスの新しいインスタンスを初期化します。 |
|
|  | [Document(InputStream stream, String password)](#Document-java.io.InputStream-java.lang.String-) | 指定されたドキュメント ストリームとパスワードで Document クラスの新しいインスタンスを初期化します。 |
|
|  | [Document(String filePathOrTextContent, boolean isLoadText)](#Document-java.lang.String-boolean-) | 指定されたドキュメント パスまたはテキスト コンテンツと、何が渡されたかを示すフラグで Document クラスの新しいインスタンスを初期化します。 |
|
|  | [Document(InputStream inputStream, LoadOptions loadOptions)](#Document-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-) | 指定されたドキュメント ストリームとロード オプションで Document クラスの新しいインスタンスを初期化します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getChanges()](#getChanges--) | 比較プロセス中に検出された変更を表す [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) オブジェクトのリストを取得します。 |
|
|  | [setChanges(List<ChangeInfo> value)](#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--) | 比較プロセス中に検出された変更を表す [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) オブジェクトのリストを設定します。 |
|
|  | [getName()](#getName--) | ドキュメントの名前を取得します。 |
|
|  | [setName(String value)](#setName-java.lang.String-) | ドキュメントの名前を設定します。 |
|
|  | [getFileType()](#getFileType--) | ドキュメントの種類を取得します。 |
|
|  | [setFileType(FileType fileType)](#setFileType-com.groupdocs.comparison.result.FileType-) | ドキュメントの種類を設定します。 |
|
|  | [createStream()](#createStream--) | ドキュメントの内容で新しいストリームを作成します。 |
|
|  | [getStreamLength()](#getStreamLength--) | ドキュメントのサイズを取得します |
|
|  | [getPassword()](#getPassword--) | ドキュメントのパスワードを取得します |
|
|  | [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.comparison.options.PreviewOptions-) | 提供された[PreviewOptions](../../com.groupdocs.comparison.options/previewoptions)に基づいてドキュメントのプレビューを生成します。 |
|
|  | [getDocumentInfo()](#getDocumentInfo--) | ドキュメントの種類、ページ数、ページサイズなどを含む情報を取得します。 |
|
| [close()](#close--) |  |
### Document(InputStream stream) {#Document-java.io.InputStream-}
```
public Document(InputStream stream)
```


指定されたドキュメント ストリームで Document クラスの新しいインスタンスを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | ストリーム | java.io.InputStream | ドキュメントストリーム |
|

### Document(String filePath) {#Document-java.lang.String-}
```
public Document(String filePath)
```


指定されたドキュメント パスで Document クラスの新しいインスタンスを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.lang.String | ドキュメントパス |
|

### Document(Path filePath) {#Document-java.nio.file.Path-}
```
public Document(Path filePath)
```


指定されたドキュメント パスで Document クラスの新しいインスタンスを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | ドキュメントパス |
|

### Document(Path filePath, String password) {#Document-java.nio.file.Path-java.lang.String-}
```
public Document(Path filePath, String password)
```


指定されたドキュメント パスとパスワードで Document クラスの新しいインスタンスを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | ドキュメントパス |
|
|  | パスワード | java.lang.String | ドキュメントパスワード |
|

### Document(Path filePath, LoadOptions loadOptions) {#Document-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Document(Path filePath, LoadOptions loadOptions)
```


指定されたドキュメント パスとロード オプションで Document クラスの新しいインスタンスを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | ドキュメントパス |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | ロードオプション |
|

### Document(String filePath, String password) {#Document-java.lang.String-java.lang.String-}
```
public Document(String filePath, String password)
```


指定されたドキュメント パスとパスワードで Document クラスの新しいインスタンスを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.lang.String | ドキュメントパス |
|
|  | パスワード | java.lang.String | ドキュメントパスワード |
|

### Document(String filePath, LoadOptions loadOptions) {#Document-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Document(String filePath, LoadOptions loadOptions)
```


指定されたドキュメント パスとロード オプションで Document クラスの新しいインスタンスを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.lang.String | ドキュメントパス |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | ロードオプション |
|

### Document(InputStream stream, String password) {#Document-java.io.InputStream-java.lang.String-}
```
public Document(InputStream stream, String password)
```


指定されたドキュメント ストリームとパスワードで Document クラスの新しいインスタンスを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | ストリーム | java.io.InputStream | ドキュメントストリーム |
|
|  | パスワード | java.lang.String | ドキュメントパスワード |
|

### Document(String filePathOrTextContent, boolean isLoadText) {#Document-java.lang.String-boolean-}
```
public Document(String filePathOrTextContent, boolean isLoadText)
```


指定されたドキュメント パスまたはテキスト コンテンツと、何が渡されたかを示すフラグで Document クラスの新しいインスタンスを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePathOrTextContent | java.lang.String | ファイルパス |
|
|  | isLoadText | boolean | ロードテキストかどうか |
|

### Document(InputStream inputStream, LoadOptions loadOptions) {#Document-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Document(InputStream inputStream, LoadOptions loadOptions)
```


指定されたドキュメント ストリームとロード オプションで Document クラスの新しいインスタンスを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | inputStream | java.io.InputStream | ドキュメントストリーム |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | ロードオプション |
|

### getChanges() {#getChanges--}
```
public final List<ChangeInfo> getChanges()
```


比較プロセス中に検出された変更を表す [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) オブジェクトのリストを取得します。


このメソッドを使用して、ソースドキュメントとターゲットドキュメント間の変更に関する詳細情報を取得します。
各[ChangeInfo](../../com.groupdocs.comparison.result/changeinfo)オブジェクトは、変更の種類や影響を受けた領域などの情報を含みます、
そして変更前後のコンテンツです。


**Returns:**
java.util.List<com.groupdocs.comparison.result.ChangeInfo> - 比較プロセス中に検出された変更を表す[ChangeInfo](../../com.groupdocs.comparison.result/changeinfo)オブジェクトのリスト

### setChanges(List<ChangeInfo> value) {#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--}
```
public final void setChanges(List<ChangeInfo> value)
```


比較プロセス中に検出された変更を表す [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) オブジェクトのリストを設定します。


このメソッドを使用して、ソースドキュメントとターゲットドキュメント間の変更に関する詳細情報を取得します。
各[ChangeInfo](../../com.groupdocs.comparison.result/changeinfo)オブジェクトは、変更の種類や影響を受けた領域などの情報を含みます、
そして変更前後のコンテンツです。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | value | java.util.List<com.groupdocs.comparison.result.ChangeInfo> | 比較プロセス中に検出された変更を表す[ChangeInfo](../../com.groupdocs.comparison.result/changeinfo)オブジェクトのリスト |
|

### getName() {#getName--}
```
public final String getName()
```


ドキュメントの名前を取得します。


**Returns:**
java.lang.String - ドキュメントの名前

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


ドキュメントの名前を設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | java.lang.String | ドキュメントの名前 |
|

### getFileType() {#getFileType--}
```
public FileType getFileType()
```


ドキュメントの種類を取得します。


**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the type of the document

### setFileType(FileType fileType) {#setFileType-com.groupdocs.comparison.result.FileType-}
```
public void setFileType(FileType fileType)
```


ドキュメントの種類を設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.comparison.result/filetype) | ドキュメントのタイプ |
|

### createStream() {#createStream--}
```
public InputStream createStream()
```


ドキュメントの内容で新しいストリームを作成します。


**Returns:**
java.io.InputStream - ドキュメント内容のストリーム

### getStreamLength() {#getStreamLength--}
```
public long getStreamLength()
```


ドキュメントのサイズを取得します


**Returns:**
long - ドキュメントのサイズ

### getPassword() {#getPassword--}
```
public String getPassword()
```


ドキュメントのパスワードを取得します


**Returns:**
java.lang.String - ドキュメントのパスワード

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.comparison.options.PreviewOptions-}
```
public final void generatePreview(PreviewOptions previewOptions)
```


提供された[PreviewOptions](../../com.groupdocs.comparison.options/previewoptions)に基づいてドキュメントのプレビューを生成します。


このメソッドは、指定されたオプション（プレビュー形式など）に従ってドキュメントページのプレビューを生成します、
ページ番号、および出力ストリームプロバイダー。生成されたプレビューは、必要に応じて保存またはさらに処理できます。

* Learn more about how to generate previews for document pages: [How to generate document pages preview using GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Generate+document+pages+preview)


使用例:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     PreviewOptions previewOptions = new PreviewOptions(
             pageNumber -> Files.newOutputStream(Paths.get("preview-image-page-" + pageNumber + ".png"))
     );
     previewOptions.setPreviewFormat(PreviewFormats.PNG);
     previewOptions.setPageNumbers(new int[]{1, 2});
     comparer.getSource().generatePreview(previewOptions);
 }
 
````



**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | previewOptions | [PreviewOptions](../../com.groupdocs.comparison.options/previewoptions) | 形式、ページ番号などを指定するプレビューオプション |
|

### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


ドキュメントの種類、ページ数、ページサイズなどを含む情報を取得します。

* Learn more about document file type, page count, size, and other format-specific properties: [How to get document info using GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Get+file+info)


**Returns:**
[IDocumentInfo](../../com.groupdocs.comparison.interfaces/idocumentinfo) - the document information

### close() {#close--}
```
public void close()
```




