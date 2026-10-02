---
title: "比較ツール"
second_title: "GroupDocs.Comparison for .NET API リファレンス"
description: "ドキュメント比較プロセスを制御する主要クラスを表します。"
type: docs
weight: 100
url: /ja/net/groupdocs.comparison/comparer/
---
## Comparer class

ドキュメント比較プロセスを制御する主要クラスを表します。

```csharp
public sealed class Comparer : IDisposable
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Comparer](comparer#constructor)(Stream) | ソースドキュメントストリームを使用して、[`Comparer`](../comparer)クラスの新しいインスタンスを初期化します。 |
| [Comparer](comparer#constructor_4)(string) | ソースファイルパスを使用して、[`Comparer`](../comparer)クラスの新しいインスタンスを初期化します。 |
| [Comparer](comparer#constructor_1)(Stream, ComparerSettings) | ソースドキュメントストリームと[`ComparerSettings`](../comparersettings)を使用して、[`Comparer`](../comparer)クラスの新しいインスタンスを初期化します。 |
| [Comparer](comparer#constructor_2)(Stream, LoadOptions) | ソースドキュメントストリームと[`LoadOptions`](../../groupdocs.comparison.options/loadoptions)を使用して、[`Comparer`](../comparer)の新しいインスタンスを初期化します。 |
| [Comparer](comparer#constructor_6)(string, CompareOptions) | ソースフォルダーパスと[`CompareOptions`](../../groupdocs.comparison.options/compareoptions)を使用して、[`Comparer`](../comparer)の新しいインスタンスを初期化します。 |
| [Comparer](comparer#constructor_5)(string, ComparerSettings) | ソースファイルパスと[`ComparerSettings`](../comparersettings)を使用して、[`Comparer`](../comparer)クラスの新しいインスタンスを初期化します。 |
| [Comparer](comparer#constructor_7)(string, LoadOptions) | ソースファイルパスと[`LoadOptions`](../../groupdocs.comparison.options/loadoptions)を使用して、[`Comparer`](../comparer)の新しいインスタンスを初期化します。 |
| [Comparer](comparer#constructor_3)(Stream, LoadOptions, ComparerSettings) | ドキュメントストリーム、[`LoadOptions`](../../groupdocs.comparison.options/loadoptions)、および[`ComparerSettings`](../comparersettings)を使用して、[`Comparer`](../comparer)クラスの新しいインスタンスを初期化します。 |
| [Comparer](comparer#constructor_8)(string, LoadOptions, ComparerSettings) | ソースファイルパス、[`LoadOptions`](../../groupdocs.comparison.options/loadoptions)、および[`ComparerSettings`](../comparersettings)を使用して、[`Comparer`](../comparer)クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Result](../../groupdocs.comparison/comparer/result) { get; } | 結果ドキュメント。 |
| [Source](../../groupdocs.comparison/comparer/source) { get; } | 比較対象のソースファイル。 |
| [SourceFolder](../../groupdocs.comparison/comparer/sourcefolder) { get; } | 比較対象のソースフォルダー。 |
| [TargetFolder](../../groupdocs.comparison/comparer/targetfolder) { get; set; } | 比較対象のターゲットフォルダー。 |
| [Targets](../../groupdocs.comparison/comparer/targets) { get; } | ソースファイルと比較するターゲットファイルの一覧。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Add](../../groupdocs.comparison/comparer/add#add)(Stream) | 比較にドキュメントストリームを追加します。 |
| [Add](../../groupdocs.comparison/comparer/add#add_2)(string) | 比較にファイルを追加します。 |
| [Add](../../groupdocs.comparison/comparer/add#add_1)(Stream, LoadOptions) | 指定されたロードオプションで比較にドキュメントストリームを追加します。 |
| [Add](../../groupdocs.comparison/comparer/add#add_3)(string, CompareOptions) | 比較にフォルダーを追加します。 |
| [Add](../../groupdocs.comparison/comparer/add#add_4)(string, LoadOptions) | 指定されたロードオプションで比較にファイルを追加します。 |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges)(Stream, ApplyChangeOptions) | 変更を受け入れるか拒否し、結果ドキュメントに適用します。 |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_2)(string, ApplyChangeOptions) | 変更を受け入れるか拒否し、結果ドキュメントに適用します。 |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_1)(Stream, SaveOptions, ApplyChangeOptions) | 変更を受け入れるか拒否し、結果ドキュメントに適用します。 |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_3)(string, SaveOptions, ApplyChangeOptions) | 変更を受け入れるか拒否し、結果ドキュメントに適用します。 |
| [Compare](../../groupdocs.comparison/comparer/compare#compare)() | デフォルトオプションで結果を保存せずにドキュメントを比較します。 |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_1)(CompareOptions) | 結果を保存せずにドキュメントを比較します。 |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_3)(Stream) | ドキュメントを比較し、結果をファイルストリームに保存します。 |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_7)(string) | ドキュメントを比較し、結果をファイルパスに保存します。 |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_2)(SaveOptions, CompareOptions) | 結果を保存せずにドキュメントを比較します。 |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_4)(Stream, CompareOptions) | ドキュメントを比較し、結果をファイルストリームに保存します。 |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_5)(Stream, SaveOptions) | ドキュメントを比較し、結果をファイルストリームに保存します。 |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_8)(string, CompareOptions) | ドキュメントを比較し、結果をファイルパスに保存します。 |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_9)(string, SaveOptions) | ドキュメントを比較し、結果をファイルパスに保存します。 |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_6)(Stream, SaveOptions, CompareOptions) | ドキュメントを比較し、結果をストリームに保存します。 |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_10)(string, SaveOptions, CompareOptions) | ドキュメントを比較し、結果をファイルパスに保存します。 |
| [CompareDirectory](../../groupdocs.comparison/comparer/comparedirectory)(string, CompareOptions) | ディレクトリを比較し、結果をファイルパスに保存します。 |
| [Dispose](../../groupdocs.comparison/comparer/dispose)() | リソースを解放します。 |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges)() | ソースとターゲットファイル間の変更一覧を取得します。 |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges_1)(ChangeType) | ソースとターゲットファイル間の変更一覧を取得します。 |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges_2)(GetChangeOptions) | ソースとターゲットファイル間の変更一覧を取得します。 |
| [GetResultDocumentStream](../../groupdocs.comparison/comparer/getresultdocumentstream)() | 結果ドキュメントのストリームを取得します。ストリームが存在しない場合は null を返します。 |
| [GetResultString](../../groupdocs.comparison/comparer/getresultstring)() | 比較後に結果文字列を取得します（テキスト比較の場合のみ）。 |

### 関連項目

* namespace [GroupDocs.Comparison](../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Comparison.dll 用に生成されました -->
