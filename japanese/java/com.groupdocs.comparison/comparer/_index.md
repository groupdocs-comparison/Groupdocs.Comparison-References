---
title: "Comparer"
second_title: "Java 用 GroupDocs.Comparison API リファレンス"
description: "Comparer クラスは、ドキュメントの比較と比較結果の生成機能を提供します。"
type: docs
weight: 10
url: /ja/java/com.groupdocs.comparison/comparer/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public class Comparer implements System.IDisposable, Closeable
```

Comparer クラスは、ドキュメントの比較と比較結果の生成機能を提供します。


PDF、Word、Excel、PowerPointなど、さまざまな種類のドキュメントを比較できるようにします。


使用例:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     CompareOptions compareOptions = new CompareOptions();
     compareOptions.setDetectStyleChanges(true);

     comparer.compare(resultFile, compareOptions);
 }
 
````


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [Comparer(String filePath)](#Comparer-java.lang.String-) | 指定されたソースファイルパスで Comparer クラスの新しいインスタンスを初期化します。 |
|
|  | [Comparer(String filePath, CompareOptions compareOptions)](#Comparer-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | 指定されたフォルダーパスと比較オプションで Comparer クラスの新しいインスタンスを初期化します。 |
|
|  | [Comparer(Path filePath)](#Comparer-java.nio.file.Path-) | 指定されたソースファイルパスで Comparer クラスの新しいインスタンスを初期化します。 |
|
|  | [Comparer(String filePath, LoadOptions loadOptions)](#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-) | 指定されたソースファイルパスと [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) で Comparer の新しいインスタンスを初期化します。 |
|
|  | [Comparer(Path filePath, LoadOptions loadOptions)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-) | 指定されたソースファイルパスと [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) で Comparer の新しいインスタンスを初期化します。 |
|
|  | [Comparer(Path filePath, CompareOptions compareOptions)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | 指定されたソースファイルパスと [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) で Comparer の新しいインスタンスを初期化します。 |
|
|  | [Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings)](#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-) | 指定されたソースファイルパス、[LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) および [ComparerSettings](../../com.groupdocs.comparison/comparersettings) で Comparer クラスの新しいインスタンスを初期化します。 |
|
|  | [Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)](#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-) | 指定されたソースファイルパス、[LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) および [ComparerSettings](../../com.groupdocs.comparison/comparersettings) で Comparer クラスの新しいインスタンスを初期化します。 |
|
|  | [Comparer(String filePath, ComparerSettings settings)](#Comparer-java.lang.String-com.groupdocs.comparison.ComparerSettings-) | 指定されたソースファイルパスと [ComparerSettings](../../com.groupdocs.comparison/comparersettings) で Comparer クラスの新しいインスタンスを初期化します。 |
|
|  | [Comparer(Path filePath, ComparerSettings settings)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.ComparerSettings-) | 指定されたソースファイルパスと [ComparerSettings](../../com.groupdocs.comparison/comparersettings) で Comparer クラスの新しいインスタンスを初期化します。 |
|
|  | [Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-) | 指定されたソースファイルパス、[LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) および [ComparerSettings](../../com.groupdocs.comparison/comparersettings) で Comparer クラスの新しいインスタンスを初期化します。 |
|
|  | [Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-) | 指定されたソースファイルパス、[LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) および [ComparerSettings](../../com.groupdocs.comparison/comparersettings) で Comparer クラスの新しいインスタンスを初期化します。 |
|
|  | [Comparer(InputStream document)](#Comparer-java.io.InputStream-) | 指定されたソースドキュメントストリームで Comparer クラスの新しいインスタンスを初期化します。 |
|
|  | [Comparer(InputStream document, LoadOptions loadOptions)](#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-) | 指定されたソースドキュメントストリームと [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) で Comparer の新しいインスタンスを初期化します。 |
|
|  | [Comparer(InputStream document, ComparerSettings settings)](#Comparer-java.io.InputStream-com.groupdocs.comparison.ComparerSettings-) | 指定されたソースドキュメントストリームと [ComparerSettings](../../com.groupdocs.comparison/comparersettings) で Comparer クラスの新しいインスタンスを初期化します。 |
|
|  | [Comparer(InputStream document, LoadOptions loadOptions, ComparerSettings settings)](#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-) | 指定されたドキュメントストリーム、[LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) および [ComparerSettings](../../com.groupdocs.comparison/comparersettings) で Comparer クラスの新しいインスタンスを初期化します。 |
|
|  | [Comparer(ComparerSettings settings)](#Comparer-com.groupdocs.comparison.ComparerSettings-) | 指定された [ComparerSettings](../../com.groupdocs.comparison/comparersettings) で Comparer クラスの新しいインスタンスを初期化します。 |
|
## フィールド

| フィールド | 説明 |
| --- | --- |
| [FILE_PATH](#FILE-PATH) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getSource()](#getSource--) | 比較対象となっているソースドキュメントを取得します。 |
|
|  | [getTargets()](#getTargets--) | ソースファイルと比較する対象ドキュメントのリスト。 |
|
|  | [compare()](#compare--) | デフォルトオプションで結果を保存せずに、指定されたファイルを対象ドキュメントと比較します。 |
|
|  | [compare(String filePath)](#compare-java.lang.String-) | 指定されたファイルを対象ドキュメントと比較し、比較結果を生成します。 |
|
|  | [compare(Path filePath)](#compare-java.nio.file.Path-) | 指定されたファイルを対象ドキュメントと比較し、比較結果を生成します。 |
|
|  | [compare(OutputStream outputStream)](#compare-java.io.OutputStream-) | 指定されたファイルを対象ドキュメントと比較し、比較結果を出力ストリームに書き込みます。 |
|
|  | [compare(String filePath, CompareOptions compareOptions)](#compare-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | 指定されたファイルを対象ドキュメントと比較し、比較結果を指定されたファイルパスに書き込みます。 |
|
|  | [compare(Path filePath, CompareOptions compareOptions)](#compare-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | 指定されたファイルを対象ドキュメントと比較し、比較結果を指定されたファイルパスに書き込みます。 |
|
|  | [compare(OutputStream stream, CompareOptions compareOptions)](#compare-java.io.OutputStream-com.groupdocs.comparison.options.CompareOptions-) | 指定されたファイルを対象ドキュメントと比較し、比較結果を出力ストリームに書き込みます。 |
|
|  | [compare(SaveOptions saveOptions, CompareOptions compareOptions)](#compare-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | 指定されたファイルを対象ドキュメントと比較し、結果を保存せずに行います。 |
|
|  | [compare(String filePath, SaveOptions saveOptions)](#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-) | 指定されたファイルを対象ドキュメントと比較し、比較結果を指定されたファイルパスに書き込みます。 |
|
|  | [compare(Path filePath, SaveOptions saveOptions)](#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-) | 指定されたファイルを対象ドキュメントと比較し、比較結果を指定されたファイルパスに書き込みます。 |
|
|  | [compare(OutputStream stream, SaveOptions saveOptions)](#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-) | 指定されたファイルを対象ドキュメントと比較し、比較結果を指定されたファイルパスに書き込みます。 |
|
|  | [compare(CompareOptions compareOptions)](#compare-com.groupdocs.comparison.options.CompareOptions-) | 指定されたファイルを対象ドキュメントと比較し、結果を保存せずに行います。 |
|
|  | [compare(OutputStream outputStream, SaveOptions saveOptions, CompareOptions compareOptions)](#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | 指定されたファイルを対象ドキュメントと比較し、比較結果を指定された出力ストリームに書き込みます。 |
|
|  | [compare(String filePath, SaveOptions saveOptions, CompareOptions compareOptions)](#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | 指定されたファイルを対象ドキュメントと比較し、比較結果を指定されたファイルパスに書き込みます。 |
|
|  | [compareDirectory(String filePath, CompareOptions compareOptions)](#compareDirectory-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | 指定されたディレクトリを対象ディレクトリと比較し、比較結果を指定されたファイルパスに保存します。 |
|
|  | [compareDirectory(Path filePath, CompareOptions compareOptions)](#compareDirectory-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | 指定されたディレクトリを対象ディレクトリと比較し、比較結果を指定されたファイルパスに保存します。 |
|
|  | [compare(Path filePath, SaveOptions saveOptions, CompareOptions compareOptions)](#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | 指定されたファイルを対象ドキュメントと比較し、比較結果を指定されたファイルパスに書き込みます。 |
|
|  | [add(String filePath)](#add-java.lang.String-) | 指定された対象ドキュメントを比較プロセスに追加します。 |
|
|  | [add(String filePath, CompareOptions compareOptions)](#add-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | 指定された対象ドキュメントまたはフォルダーを比較プロセスに追加します。 |
|
|  | [add(Path filePath)](#add-java.nio.file.Path-) | 指定された対象ドキュメントを比較プロセスに追加します。 |
|
|  | [add(String[] filePaths)](#add-java.lang.String...-) | 指定された対象ドキュメントを比較プロセスに追加します。 |
|
|  | [add(Path[] filePaths)](#add-java.nio.file.Path...-) | 指定された対象ドキュメントを比較プロセスに追加します。 |
|
|  | [add(String filePath, LoadOptions loadOptions)](#add-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-) | 指定された対象ドキュメントを、指定されたロードオプションとともに比較プロセスに追加します。 |
|
|  | [add(Path filePath, LoadOptions loadOptions)](#add-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-) | 指定された対象ドキュメントを、指定されたロードオプションとともに比較プロセスに追加します。 |
|
|  | [add(Path filePath, CompareOptions compareOptions)](#add-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | 指定された対象ドキュメントを、指定されたロードオプションとともに比較プロセスに追加します。 |
|
|  | [add(InputStream document)](#add-java.io.InputStream-) | 指定された対象ドキュメントを比較プロセスに追加します。 |
|
|  | [add(InputStream[] documents)](#add-java.io.InputStream...-) | 指定された対象ドキュメントを比較プロセスに追加します。 |
|
|  | [add(InputStream document, LoadOptions loadOptions)](#add-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-) | 指定された対象ドキュメントを、指定されたロードオプションとともに比較プロセスに追加します。 |
|
|  | [getChanges()](#getChanges--) | 比較プロセス中に検出された変更を表す [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) オブジェクトの配列を取得します。 |
|
|  | [getChanges(GetChangeOptions getChangeOptions)](#getChanges-com.groupdocs.comparison.options.GetChangeOptions-) | 比較プロセス中に検出された変更を表す [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) オブジェクトの配列を取得します。 |
|
|  | [applyChanges(String filePath, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.lang.String-com.groupdocs.comparison.options.ApplyChangeOptions-) | 変更を受け入れるか拒否し、結果ドキュメントに適用します。 |
|
|  | [applyChanges(Path filePath, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.ApplyChangeOptions-) | 変更を受け入れるか拒否し、生成されたドキュメントに適用します。 |
|
|  | [applyChanges(OutputStream document, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.ApplyChangeOptions-) | 変更を受け入れるか拒否し、生成されたドキュメントに適用します。 |
|
|  | [applyChanges(String filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-) | 変更を受け入れるか拒否し、生成されたドキュメントに適用します。 |
|
|  | [applyChanges(Path filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-) | 変更を受け入れるか拒否し、生成されたドキュメントに適用します。 |
|
|  | [applyChanges(OutputStream document, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-) | 変更を受け入れるか拒否し、生成されたドキュメントに適用します。 |
|
|  | [getResultString()](#getResultString--) | 比較後の結果文字列を取得します（テキスト比較のみ）。 |
|
|  | [getSourceFolder()](#getSourceFolder--) | 比較対象となっているソースフォルダーを返します。 |
|
|  | [getTargetFolder()](#getTargetFolder--) | 比較対象となっているターゲットフォルダーを返します。 |
|
|  | [selfComparisonCheck(Document source, Document target)](#selfComparisonCheck-com.groupdocs.comparison.Document-com.groupdocs.comparison.Document-) | 自己比較チェック（e498c23）。 |
|
|  | [close()](#close--) | リソースを解放します。 |
|
### Comparer(String filePath) {#Comparer-java.lang.String-}
```
public Comparer(String filePath)
```


指定されたソースファイルパスで Comparer クラスの新しいインスタンスを初期化します。

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.lang.String | ソースドキュメントへのパス |
|

### Comparer(String filePath, CompareOptions compareOptions) {#Comparer-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(String filePath, CompareOptions compareOptions)
```


指定されたフォルダーパスと比較オプションで Comparer クラスの新しいインスタンスを初期化します。

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.lang.String | ソースドキュメントまたはフォルダーへのパス |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | フォルダー比較のための比較オプション |
|

### Comparer(Path filePath) {#Comparer-java.nio.file.Path-}
```
public Comparer(Path filePath)
```


指定されたソースファイルパスで Comparer クラスの新しいインスタンスを初期化します。

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | ソースドキュメントへのパス |
|

### Comparer(String filePath, LoadOptions loadOptions) {#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Comparer(String filePath, LoadOptions loadOptions)
```


指定されたソースファイルパスと [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) で Comparer の新しいインスタンスを初期化します。

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.lang.String | ソースドキュメントへのパス |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | ドキュメントに適用されるカスタムロードオプション |
|

### Comparer(Path filePath, LoadOptions loadOptions) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Comparer(Path filePath, LoadOptions loadOptions)
```


指定されたソースファイルパスと [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) で Comparer の新しいインスタンスを初期化します。

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | ソースドキュメントへのパス |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | ドキュメントに適用されるカスタムロードオプション |
|

### Comparer(Path filePath, CompareOptions compareOptions) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(Path filePath, CompareOptions compareOptions)
```


指定されたソースファイルパスと [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) で Comparer の新しいインスタンスを初期化します。

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | ソースドキュメントへのパス |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | フォルダー比較のための比較オプション |
|

### Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings) {#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings)
```


指定されたソースファイルパス、[LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) および [ComparerSettings](../../com.groupdocs.comparison/comparersettings) で Comparer クラスの新しいインスタンスを初期化します。

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.lang.String | ソースドキュメントへのパス |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | ドキュメントに適用されるカスタムロードオプション |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | 比較プロセスで使用される比較設定 |
|

### Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions) {#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)
```


指定されたソースファイルパス、[LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) および [ComparerSettings](../../com.groupdocs.comparison/comparersettings) で Comparer クラスの新しいインスタンスを初期化します。

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.lang.String | 比較対象となるソースドキュメント、フォルダー、またはテキストへのパス |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | ドキュメントに適用されるカスタムロードオプション |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | 比較プロセスで使用される比較設定 |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | フォルダー比較のための比較オプション |
|

### Comparer(String filePath, ComparerSettings settings) {#Comparer-java.lang.String-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(String filePath, ComparerSettings settings)
```


指定されたソースファイルパスと [ComparerSettings](../../com.groupdocs.comparison/comparersettings) で Comparer クラスの新しいインスタンスを初期化します。

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.lang.String | ソースドキュメントへのパス |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | 比較プロセスで使用される比較設定 |
|

### Comparer(Path filePath, ComparerSettings settings) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(Path filePath, ComparerSettings settings)
```


指定されたソースファイルパスと [ComparerSettings](../../com.groupdocs.comparison/comparersettings) で Comparer クラスの新しいインスタンスを初期化します。

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | ソースドキュメントへのパス |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | 比較プロセスで使用される比較設定 |
|

### Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings)
```


指定されたソースファイルパス、[LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) および [ComparerSettings](../../com.groupdocs.comparison/comparersettings) で Comparer クラスの新しいインスタンスを初期化します。

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | ソースドキュメントへのパス |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | ドキュメントに適用されるカスタムロードオプション |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | 比較プロセスで使用される比較設定 |
|

### Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)
```


指定されたソースファイルパス、[LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) および [ComparerSettings](../../com.groupdocs.comparison/comparersettings) で Comparer クラスの新しいインスタンスを初期化します。

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | ソースドキュメントまたはフォルダーへのパス |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | ドキュメントに適用されるカスタムロードオプション |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | 比較プロセスで使用される比較設定 |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | フォルダー比較のための比較オプション |
|

### Comparer(InputStream document) {#Comparer-java.io.InputStream-}
```
public Comparer(InputStream document)
```


指定されたソースドキュメントストリームで Comparer クラスの新しいインスタンスを初期化します。

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | ドキュメント | java.io.InputStream | ソースドキュメントの入力ストリーム |
|

### Comparer(InputStream document, LoadOptions loadOptions) {#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Comparer(InputStream document, LoadOptions loadOptions)
```


指定されたソースドキュメントストリームと [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) で Comparer の新しいインスタンスを初期化します。

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | ドキュメント | java.io.InputStream | ソースドキュメントの入力ストリーム |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | ドキュメントに適用されるカスタムロードオプション |
|

### Comparer(InputStream document, ComparerSettings settings) {#Comparer-java.io.InputStream-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(InputStream document, ComparerSettings settings)
```


指定されたソースドキュメントストリームと [ComparerSettings](../../com.groupdocs.comparison/comparersettings) で Comparer クラスの新しいインスタンスを初期化します。

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | ドキュメント | java.io.InputStream | ソースドキュメントの入力ストリーム |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | 比較プロセスで使用される比較設定 |
|

### Comparer(InputStream document, LoadOptions loadOptions, ComparerSettings settings) {#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(InputStream document, LoadOptions loadOptions, ComparerSettings settings)
```


指定されたドキュメントストリーム、[LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) および [ComparerSettings](../../com.groupdocs.comparison/comparersettings) で Comparer クラスの新しいインスタンスを初期化します。

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | ドキュメント | java.io.InputStream | 比較対象となるドキュメントのデータが含まれるストリーム |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | ドキュメントに適用されるカスタムロードオプション |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | 比較プロセスで使用される比較設定 |
|

### Comparer(ComparerSettings settings) {#Comparer-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(ComparerSettings settings)
```


指定された [ComparerSettings](../../com.groupdocs.comparison/comparersettings) で Comparer クラスの新しいインスタンスを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | 設定 |
|

### FILE_PATH {#FILE-PATH}
```
public static final String FILE_PATH
```


### getSource() {#getSource--}
```
public final Document getSource()
```


比較対象となっているソースドキュメントを取得します。


**Returns:**
[Document](../../com.groupdocs.comparison/document) - the source document

### getTargets() {#getTargets--}
```
public final List<Document> getTargets()
```


ソースファイルと比較する対象ドキュメントのリスト。


**Returns:**
java.util.List<com.groupdocs.comparison.Document> - 対象ドキュメント

### compare() {#compare--}
```
public final Path compare()
```


デフォルトオプションで結果を保存せずに、指定されたファイルを対象ドキュメントと比較します。

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Returns:**
java.nio.file.Path - 結果ドキュメントのパスまたは null

### compare(String filePath) {#compare-java.lang.String-}
```
public final Path compare(String filePath)
```


指定されたファイルを対象ドキュメントと比較し、比較結果を生成します。

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.lang.String | 結果ドキュメントのパス |
|

**Returns:**
java.nio.file.Path - 結果ファイルのパスまたは null。状況によっては拡張子を変更できる場合があります

### compare(Path filePath) {#compare-java.nio.file.Path-}
```
public final Path compare(Path filePath)
```


指定されたファイルを対象ドキュメントと比較し、比較結果を生成します。

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 結果ドキュメントのパス |
|

**Returns:**
java.nio.file.Path - 結果ファイルのパス、状況によっては拡張子を変更できる場合があります

### compare(OutputStream outputStream) {#compare-java.io.OutputStream-}
```
public final Path compare(OutputStream outputStream)
```


指定されたファイルを対象ドキュメントと比較し、比較結果を出力ストリームに書き込みます。


注: 戻り値が null の場合は、outputStream に書き込まれたデータを使用してください

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | outputStream | java.io.OutputStream | 結果ドキュメントのストリーム |
|

**Returns:**
java.nio.file.Path - データが outputStream から使用される必要がある場合は null になる結果ファイルのパス。状況によっては結果ファイルの拡張子を変更できる場合があります

### compare(String filePath, CompareOptions compareOptions) {#compare-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(String filePath, CompareOptions compareOptions)
```


指定されたファイルを対象ドキュメントと比較し、比較結果を指定されたファイルパスに書き込みます。

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.lang.String | 結果ドキュメントのファイルパス |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | 比較プロセスで使用される比較オプション |
|

**Returns:**
java.nio.file.Path - 結果ファイルのパス、状況によっては拡張子を変更できる場合があります

### compare(Path filePath, CompareOptions compareOptions) {#compare-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(Path filePath, CompareOptions compareOptions)
```


指定されたファイルを対象ドキュメントと比較し、比較結果を指定されたファイルパスに書き込みます。

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 結果ドキュメントのファイルパス |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | 比較プロセスで使用される比較オプション |
|

**Returns:**
java.nio.file.Path - 結果ファイルのパス、状況によっては拡張子を変更できる場合があります

### compare(OutputStream stream, CompareOptions compareOptions) {#compare-java.io.OutputStream-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(OutputStream stream, CompareOptions compareOptions)
```


指定されたファイルを対象ドキュメントと比較し、比較結果を出力ストリームに書き込みます。


注: 戻り値が null の場合は、outputStream に書き込まれたデータを使用してください。

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | ストリーム | java.io.OutputStream | 結果ドキュメントのストリーム |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | 比較プロセスで使用される比較オプション |
|

**Returns:**
java.nio.file.Path - データが outputStream から使用される必要がある場合は null になる結果ファイルのパス。状況によっては結果ファイルの拡張子を変更できる場合があります

### compare(SaveOptions saveOptions, CompareOptions compareOptions) {#compare-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(SaveOptions saveOptions, CompareOptions compareOptions)
```


指定されたファイルを対象ドキュメントと比較し、結果を保存せずに行います。

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparison options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | 保存オプション |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | 比較プロセスで使用される比較オプション |
|

**Returns:**
java.nio.file.Path - 結果ドキュメントのパスまたは null

### compare(String filePath, SaveOptions saveOptions) {#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-}
```
public final Path compare(String filePath, SaveOptions saveOptions)
```


指定されたファイルを対象ドキュメントと比較し、比較結果を指定されたファイルパスに書き込みます。

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.lang.String | 結果ドキュメントのファイルパス |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | 保存オプション |
|

**Returns:**
java.nio.file.Path - 結果ファイルのパス、状況によっては拡張子を変更できる場合があります

### compare(Path filePath, SaveOptions saveOptions) {#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-}
```
public final Path compare(Path filePath, SaveOptions saveOptions)
```


指定されたファイルを対象ドキュメントと比較し、比較結果を指定されたファイルパスに書き込みます。

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 結果ドキュメントのファイルパス |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | 保存オプション |
|

**Returns:**
java.nio.file.Path - 結果ファイルのパス、状況によっては拡張子を変更できる場合があります

### compare(OutputStream stream, SaveOptions saveOptions) {#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-}
```
public final Path compare(OutputStream stream, SaveOptions saveOptions)
```


指定されたファイルを対象ドキュメントと比較し、比較結果を指定されたファイルパスに書き込みます。


注: 戻り値が null の場合は、outputStream に書き込まれたデータを使用してください

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | ストリーム | java.io.OutputStream | 結果ドキュメントのストリーム |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | 保存オプション |
|

**Returns:**
java.nio.file.Path - データが outputStream から使用される必要がある場合は null になる結果ファイルのパス。状況によっては結果ファイルの拡張子を変更できる場合があります

### compare(CompareOptions compareOptions) {#compare-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(CompareOptions compareOptions)
```


指定されたファイルを対象ドキュメントと比較し、結果を保存せずに行います。

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | 比較プロセスで使用される比較オプション |
|

**Returns:**
java.nio.file.Path - 結果ファイルへのパスまたは null

### compare(OutputStream outputStream, SaveOptions saveOptions, CompareOptions compareOptions) {#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(OutputStream outputStream, SaveOptions saveOptions, CompareOptions compareOptions)
```


指定されたファイルを対象ドキュメントと比較し、比較結果を指定された出力ストリームに書き込みます。


注: 戻り値が null の場合は、outputStream に書き込まれたデータを使用してください

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | outputStream | java.io.OutputStream | 結果ドキュメントのストリーム |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | 結果ドキュメントの保存に使用される保存オプション |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | 比較プロセスで使用される比較オプション |
|

**Returns:**
java.nio.file.Path - データが outputStream から使用される必要がある場合は null になる結果ファイルのパス。状況によっては結果ファイルの拡張子を変更できる場合があります

### compare(String filePath, SaveOptions saveOptions, CompareOptions compareOptions) {#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(String filePath, SaveOptions saveOptions, CompareOptions compareOptions)
```


指定されたファイルを対象ドキュメントと比較し、比較結果を指定されたファイルパスに書き込みます。

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparison options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.lang.String | 結果ドキュメントのファイルパス |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | 結果ドキュメントの保存に使用される保存オプション |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | 比較プロセスで使用される比較オプション |
|

**Returns:**
java.nio.file.Path - 結果ファイルのパス、状況によっては拡張子を変更できる場合があります

### compareDirectory(String filePath, CompareOptions compareOptions) {#compareDirectory-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public void compareDirectory(String filePath, CompareOptions compareOptions)
```


指定されたディレクトリを対象ディレクトリと比較し、比較結果を指定されたファイルパスに保存します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.lang.String | 比較結果が保存されるファイルパス。 |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | ディレクトリ比較プロセスで使用されるオプション。 |
|

### compareDirectory(Path filePath, CompareOptions compareOptions) {#compareDirectory-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public void compareDirectory(Path filePath, CompareOptions compareOptions)
```


指定されたディレクトリを対象ディレクトリと比較し、比較結果を指定されたファイルパスに保存します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 比較結果が保存されるファイルパス。 |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | ディレクトリ比較プロセスで使用されるオプション。 |
|

### compare(Path filePath, SaveOptions saveOptions, CompareOptions compareOptions) {#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(Path filePath, SaveOptions saveOptions, CompareOptions compareOptions)
```


指定されたファイルを対象ドキュメントと比較し、比較結果を指定されたファイルパスに書き込みます。

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 結果ドキュメントのファイルパス |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | 結果ドキュメントの保存に使用される保存オプション |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | 比較プロセスで使用される比較オプション |
|

**Returns:**
java.nio.file.Path - 結果ファイルのパス、状況によっては拡張子を変更できる場合があります

### add(String filePath) {#add-java.lang.String-}
```
public final void add(String filePath)
```


指定された対象ドキュメントを比較プロセスに追加します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.lang.String | 追加される対象ドキュメントへのパス |
|

### add(String filePath, CompareOptions compareOptions) {#add-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public void add(String filePath, CompareOptions compareOptions)
```


指定された対象ドキュメントまたはフォルダーを比較プロセスに追加します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.lang.String | 追加される対象ドキュメントまたはフォルダーへのパス |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | 比較のオプション |
|

### add(Path filePath) {#add-java.nio.file.Path-}
```
public final void add(Path filePath)
```


指定された対象ドキュメントを比較プロセスに追加します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 追加される対象ドキュメントへのパス |
|

### add(String[] filePaths) {#add-java.lang.String...-}
```
public final void add(String[] filePaths)
```


指定された対象ドキュメントを比較プロセスに追加します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePaths | java.lang.String[] | 追加される対象ドキュメントへのパス |
|

### add(Path[] filePaths) {#add-java.nio.file.Path...-}
```
public final void add(Path[] filePaths)
```


指定された対象ドキュメントを比較プロセスに追加します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePaths | java.nio.file.Path[] | 追加される対象ドキュメントへのパス |
|

### add(String filePath, LoadOptions loadOptions) {#add-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-}
```
public final void add(String filePath, LoadOptions loadOptions)
```


指定された対象ドキュメントを、指定されたロードオプションとともに比較プロセスに追加します。

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.lang.String | 追加される対象ドキュメントへのパス |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | ドキュメントに適用されるカスタムロードオプション |
|

### add(Path filePath, LoadOptions loadOptions) {#add-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-}
```
public final void add(Path filePath, LoadOptions loadOptions)
```


指定された対象ドキュメントを、指定されたロードオプションとともに比較プロセスに追加します。

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 追加される対象ドキュメントへのパス |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | ドキュメントに適用されるカスタムロードオプション |
|

### add(Path filePath, CompareOptions compareOptions) {#add-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public final void add(Path filePath, CompareOptions compareOptions)
```


指定された対象ドキュメントを、指定されたロードオプションとともに比較プロセスに追加します。

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 追加される対象ドキュメントまたはフォルダーへのパス |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | 比較のオプション |
|

### add(InputStream document) {#add-java.io.InputStream-}
```
public final void add(InputStream document)
```


指定された対象ドキュメントを比較プロセスに追加します。

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | ドキュメント | java.io.InputStream | 比較対象となるドキュメントのデータが含まれるストリーム |
|

### add(InputStream[] documents) {#add-java.io.InputStream...-}
```
public final void add(InputStream[] documents)
```


指定された対象ドキュメントを比較プロセスに追加します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | ドキュメント | java.io.InputStream[] | 比較されるドキュメントのデータを含むストリーム |
|

### add(InputStream document, LoadOptions loadOptions) {#add-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-}
```
public final void add(InputStream document, LoadOptions loadOptions)
```


指定された対象ドキュメントを、指定されたロードオプションとともに比較プロセスに追加します。

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | ドキュメント | java.io.InputStream | 比較対象となるドキュメントのデータが含まれるストリーム |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | ドキュメントに適用されるカスタムロードオプション |
|

### getChanges() {#getChanges--}
```
public final ChangeInfo[] getChanges()
```


比較プロセス中に検出された変更を表す [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) オブジェクトの配列を取得します。


このメソッドを使用して、ソースドキュメントとターゲットドキュメント間の変更に関する詳細情報を取得します。
各[ChangeInfo](../../com.groupdocs.comparison.result/changeinfo)オブジェクトは、変更の種類や影響を受けた領域などの情報を含みます、
そして変更前後のコンテンツです。

* More about how to obtain collection of detected differences between compared documents in Java: [How to get list of changes between documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Get+list+of+changes)
* More about how to get changes coordinates at pages image preview when comparing documents using GroupDocs.Comparison for Java: [How to get changes coordinates programmatically](../https://docs.groupdocs.com/display/comparisonjava/Get+changes+coordinates)


**Returns:**
com.groupdocs.comparison.result.ChangeInfo[] - 比較プロセス中に検出された変更を表す [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) オブジェクトの配列

### getChanges(GetChangeOptions getChangeOptions) {#getChanges-com.groupdocs.comparison.options.GetChangeOptions-}
```
public final ChangeInfo[] getChanges(GetChangeOptions getChangeOptions)
```


比較プロセス中に検出された変更を表す [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) オブジェクトの配列を取得します。


このメソッドを使用して、ソースドキュメントとターゲットドキュメント間の変更に関する詳細情報を取得します。
各[ChangeInfo](../../com.groupdocs.comparison.result/changeinfo)オブジェクトは、変更の種類や影響を受けた領域などの情報を含みます、
そして変更前後のコンテンツです。


パラメータ [GetChangeOptions](../../com.groupdocs.comparison.options/getchangeoptions) は、変更を異なる方法でフィルタリングできるようにします。

* More about how to obtain collection of detected differences between compared documents in Java: [How to get list of changes between documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Get+list+of+changes)
* More about how to get changes coordinates at pages image preview when comparing documents using GroupDocs.Comparison for Java: [How to get changes coordinates programmatically](../https://docs.groupdocs.com/display/comparisonjava/Get+changes+coordinates)


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | getChangeOptions | [GetChangeOptions](../../com.groupdocs.comparison.options/getchangeoptions) | 変更をフィルタリングできるオブジェクト |
|

**Returns:**
com.groupdocs.comparison.result.ChangeInfo[] - 比較プロセス中に検出された変更を表す [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) オブジェクトの配列

### applyChanges(String filePath, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.lang.String-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(String filePath, ApplyChangeOptions applyChangeOptions)
```


変更を受け入れるか拒否し、結果ドキュメントに適用します。

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.lang.String | 結果ドキュメントのファイルパス |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | 変更適用プロセスを構成するためのカスタム適用変更オプション |
|

### applyChanges(Path filePath, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(Path filePath, ApplyChangeOptions applyChangeOptions)
```


変更を受け入れるか拒否し、生成されたドキュメントに適用します。

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 結果ドキュメントのファイルパス |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | 変更適用プロセスを構成するためのカスタム適用変更オプション |
|

### applyChanges(OutputStream document, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(OutputStream document, ApplyChangeOptions applyChangeOptions)
```


変更を受け入れるか拒否し、生成されたドキュメントに適用します。

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | ドキュメント | java.io.OutputStream | 結果ドキュメントの出力ストリーム |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | 変更適用プロセスを構成するためのカスタム適用変更オプション |
|

### applyChanges(String filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(String filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)
```


変更を受け入れるか拒否し、生成されたドキュメントに適用します。

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.lang.String | 結果ドキュメントのファイルパス |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | 結果ドキュメントの保存を構成するための保存オプション |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | 変更適用プロセスを構成するためのカスタム適用変更オプション |
|

### applyChanges(Path filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(Path filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)
```


変更を受け入れるか拒否し、生成されたドキュメントに適用します。

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 結果ドキュメントのファイルパス |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | 結果ドキュメントの保存を構成するための保存オプション |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | 変更適用プロセスを構成するためのカスタム適用変更オプション |
|

### applyChanges(OutputStream document, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(OutputStream document, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)
```


変更を受け入れるか拒否し、生成されたドキュメントに適用します。

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | ドキュメント | java.io.OutputStream | 結果ドキュメントの出力ストリーム |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | 結果ドキュメントの保存を構成するための保存オプション |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | 変更適用プロセスを構成するためのカスタム適用変更オプション |
|

### getResultString() {#getResultString--}
```
public String getResultString()
```


比較後の結果文字列を取得します（テキスト比較のみ）。


**Returns:**
java.lang.String - 結果文字列

### getSourceFolder() {#getSourceFolder--}
```
public String getSourceFolder()
```


比較対象となっているソースフォルダーを返します。


**Returns:**
java.lang.String - ソースフォルダー

### getTargetFolder() {#getTargetFolder--}
```
public String getTargetFolder()
```


比較対象となっているターゲットフォルダーを返します。


**Returns:**
java.lang.String - ターゲットフォルダー

### selfComparisonCheck(Document source, Document target) {#selfComparisonCheck-com.groupdocs.comparison.Document-com.groupdocs.comparison.Document-}
```
public static void selfComparisonCheck(Document source, Document target)
```


自己比較チェック (e498c23)。C# 7a7668c internal; core.common テストが呼び出せるように public のままにしています。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| source | [Document](../../com.groupdocs.comparison/document) |  |
| target | [Document](../../com.groupdocs.comparison/document) |  |

### close() {#close--}
```
public void close()
```


リソースを解放します。


