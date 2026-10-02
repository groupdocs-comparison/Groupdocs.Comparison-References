---
title: "ドキュメント"
second_title: "GroupDocs.Comparison for .NET API リファレンス"
description: "比較対象のドキュメントを表します。"
type: docs
weight: 120
url: /ja/net/groupdocs.comparison/document/
---
## Document class

比較対象のドキュメントを表します。

```csharp
public class Document
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Document](document#constructor)(Stream) | 新しい[`Document`](../document)クラスのインスタンスを初期化します。 |
| [Document](document#constructor_2)(string) | 新しい[`Document`](../document)クラスのインスタンスを初期化します。 |
| [Document](document#constructor_1)(Stream, string) | 新しい[`Document`](../document)クラスのインスタンスを初期化します。 |
| [Document](document#constructor_3)(string, string) | 新しい[`Document`](../document)クラスのインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Changes](../../groupdocs.comparison/document/changes) { get; set; } | 変更のリスト。変更タイプ、位置、内容などに関する詳細な説明が含まれます。 |
| [FileType](../../groupdocs.comparison/document/filetype) { get; } | ドキュメントのファイルタイプ。 |
| [Name](../../groupdocs.comparison/document/name) { get; set; } | ドキュメント名。 |
| [Password](../../groupdocs.comparison/document/password) { get; } | ドキュメントのパスワード。 |
| [Stream](../../groupdocs.comparison/document/stream) { get; } | ドキュメントストリーム。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GeneratePreview](../../groupdocs.comparison/document/generatepreview)(PreviewOptions) | ドキュメントページのプレビューを生成します。 |
| [GetDocumentInfo](../../groupdocs.comparison/document/getdocumentinfo)() | ドキュメントに関する情報を取得します - ドキュメントタイプ、ページ数、ページサイズなど。 |

### 関連項目

* namespace [GroupDocs.Comparison](../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Comparison.dll 用に生成されました -->
