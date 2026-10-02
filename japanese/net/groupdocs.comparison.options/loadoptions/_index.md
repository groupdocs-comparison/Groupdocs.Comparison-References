---
title: "LoadOptions"
second_title: "GroupDocs.Comparison for .NET API リファレンス"
description: "ドキュメントを読み込む際に追加オプションを指定できます。"
type: docs
weight: 300
url: /ja/net/groupdocs.comparison.options/loadoptions/
---
## LoadOptions class

ドキュメントを読み込む際に追加オプションを指定できます。

```csharp
public class LoadOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [LoadOptions](loadoptions)() | デフォルトコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [FileType](../../groupdocs.comparison.options/loadoptions/filetype) { get; set; } | 比較のファイルタイプを手動で設定し、自動ファイルタイプ検出を上書きします。 |
| [FontDirectories](../../groupdocs.comparison.options/loadoptions/fontdirectories) { get; set; } | ロードするフォントディレクトリの一覧です。 |
| [LoadText](../../groupdocs.comparison.options/loadoptions/loadtext) { get; set; } | 渡された文字列が比較テキストであり、ファイルパスではないことを示します（テキスト比較専用）。 |
| [Password](../../groupdocs.comparison.options/loadoptions/password) { get; set; } | ドキュメントのパスワードです。 |
| [SkipExternalResources](../../groupdocs.comparison.options/loadoptions/skipexternalresources) { get; set; } | [`WhitelistedResources`](./whitelistedresources) を除くすべての外部リソース（例: リモート URL で参照される画像）の読み込みを無効にします。 |
| [WhitelistedResources](../../groupdocs.comparison.options/loadoptions/whitelistedresources) { get; set; } | [`SkipExternalResources`](./skipexternalresources) が `true` に設定されているときに読み込むべき外部リソースに対応する URL フラグメントの一覧です。 |

### 関連項目

* namespace [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Comparison.dll 用に生成されました -->
