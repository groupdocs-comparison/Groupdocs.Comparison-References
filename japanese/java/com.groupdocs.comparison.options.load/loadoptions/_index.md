---
title: "LoadOptions"
second_title: "Java 用 GroupDocs.Comparison API リファレンス"
description: "文書をロードする際に追加オプションを指定できます。"
type: docs
weight: 10
url: /ja/java/com.groupdocs.comparison.options.load/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

文書をロードする際に追加オプションを指定できます。


使用例:

````

 final LoadOptions loadOptions = new LoadOptions();
 loadOptions.setPassword("passw");
 loadOptions.setFileType(FileType.PDF);

 try (Comparer comparer = new Comparer(sourceFile, loadOptions)) {
    comparer.add(targetFile);

    comparer.compare(resultFile);
 }
 
````


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [LoadOptions()](#LoadOptions--) | LoadOptions クラスの新しいインスタンスを初期化します。 |
|
|  | [LoadOptions(boolean isLoadText)](#LoadOptions-boolean-) | 入力文字列が比較用テキストであり、パスではないことを示すフラグを使用して、LoadOptions クラスの新しいインスタンスを初期化します。 |
|
|  | [LoadOptions(String password)](#LoadOptions-java.lang.String-) | ドキュメントをロードするためのパスワードを指定して、LoadOptions クラスの新しいインスタンスを初期化します。 |
|
|  | [LoadOptions(boolean isLoadText, String password)](#LoadOptions-boolean-java.lang.String-) | 入力文字列が比較用テキストであり、ドキュメントをロードするためのパスワードを含むフラグを使用して、LoadOptions クラスの新しいインスタンスを初期化します。 |
|
|  | [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.comparison.result.FileType-) | ファイルのタイプを指定して、LoadOptions クラスの新しいインスタンスを初期化します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [isLoadText()](#isLoadText--) | 文字列が比較テキストであり、ファイルパスではないことを示すフラグを取得します（テキスト比較のみ）。文字列は [Comparer](../../com.groupdocs.comparison/comparer) コンストラクタまたは [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) メソッドに渡されます。 |
|
|  | [setLoadText(boolean value)](#setLoadText-boolean-) | 文字列が比較テキストであり、ファイルパスではないことを示すフラグを設定します（テキスト比較のみ）。文字列は [Comparer](../../com.groupdocs.comparison/comparer) コンストラクタまたは [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) メソッドに渡されます。 |
|
|  | [getPassword()](#getPassword--) | ドキュメントのロードに使用されるパスワードを取得します。 |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | ドキュメントのロードに使用すべきパスワードを設定します。 |
|
|  | [getFontDirectories()](#getFontDirectories--) | ドキュメントのロードに使用するフォントファイルが配置されているディレクトリのリストを取得します。 |
|
|  | [setFontDirectories(List<String> value)](#setFontDirectories-java.util.List-java.lang.String--) | ドキュメントのロードに使用するフォントファイルが配置されているディレクトリのリストを設定します。 |
|
|  | [getFileType()](#getFileType--) | ロード中のファイルのタイプを取得します。 |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.comparison.result.FileType-) | ロード中のファイルのタイプを設定します。 |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


LoadOptions クラスの新しいインスタンスを初期化します。


### LoadOptions(boolean isLoadText) {#LoadOptions-boolean-}
```
public LoadOptions(boolean isLoadText)
```


入力文字列が比較用テキストであり、パスではないことを示すフラグを使用して、LoadOptions クラスの新しいインスタンスを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | isLoadText | boolean | 入力文字列が比較用テキストであり、パスではないことを示すフラグ |
|

### LoadOptions(String password) {#LoadOptions-java.lang.String-}
```
public LoadOptions(String password)
```


ドキュメントをロードするためのパスワードを指定して、LoadOptions クラスの新しいインスタンスを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | パスワード | java.lang.String | ドキュメントをロードするためのパスワード |
|

### LoadOptions(boolean isLoadText, String password) {#LoadOptions-boolean-java.lang.String-}
```
public LoadOptions(boolean isLoadText, String password)
```


入力文字列が比較用テキストであり、ドキュメントをロードするためのパスワードを含むフラグを使用して、LoadOptions クラスの新しいインスタンスを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | isLoadText | boolean | 入力文字列が比較用テキストであり、パスではないことを示すフラグ |
|
|  | パスワード | java.lang.String | ドキュメントをロードするためのパスワード |
|

### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.comparison.result.FileType-}
```
public LoadOptions(FileType fileType)
```


ファイルのタイプを指定して、LoadOptions クラスの新しいインスタンスを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.comparison.result/filetype) | ファイルの種類 |
|

### isLoadText() {#isLoadText--}
```
public boolean isLoadText()
```


文字列が比較テキストであり、ファイルパスではないことを示すフラグを取得します（テキスト比較のみ）。文字列は [Comparer](../../com.groupdocs.comparison/comparer) コンストラクタまたは [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) メソッドに渡されます。


**Returns:**
boolean - 入力文字列が比較用テキストの場合は true、そうでない場合は false

### setLoadText(boolean value) {#setLoadText-boolean-}
```
public void setLoadText(boolean value)
```


文字列が比較テキストであり、ファイルパスではないことを示すフラグを設定します（テキスト比較のみ）。文字列は [Comparer](../../com.groupdocs.comparison/comparer) コンストラクタまたは [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) メソッドに渡されます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | boolean | 入力文字列が比較用テキストの場合は true、そうでない場合は false |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


ドキュメントのロードに使用されるパスワードを取得します。


**Returns:**
java.lang.String - ドキュメントをロードするためのパスワード

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


ドキュメントのロードに使用すべきパスワードを設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | java.lang.String | ドキュメントをロードするためのパスワード |
|

### getFontDirectories() {#getFontDirectories--}
```
public List<String> getFontDirectories()
```


ドキュメントのロードに使用するフォントファイルが配置されているディレクトリのリストを取得します。


**Returns:**
java.util.List<java.lang.String> - フォントファイルがあるディレクトリのリスト

### setFontDirectories(List<String> value) {#setFontDirectories-java.util.List-java.lang.String--}
```
public void setFontDirectories(List<String> value)
```


ドキュメントのロードに使用するフォントファイルが配置されているディレクトリのリストを設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | java.util.List<java.lang.String> | フォントファイルがあるディレクトリのリスト |
|

### getFileType() {#getFileType--}
```
public FileType getFileType()
```


ロード中のファイルのタイプを取得します。


**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the type of the file

### setFileType(FileType value) {#setFileType-com.groupdocs.comparison.result.FileType-}
```
public void setFileType(FileType value)
```


ロード中のファイルのタイプを設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | value | [FileType](../../com.groupdocs.comparison.result/filetype) | ファイルの種類 |
|

