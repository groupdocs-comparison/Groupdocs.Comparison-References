---
title: "ChangeInfo"
second_title: "GroupDocs.Comparison for .NET API リファレンス"
description: "変更に関する情報を表します。"
type: docs
weight: 460
url: /ja/net/groupdocs.comparison.result/changeinfo/
---
## ChangeInfo class

変更に関する情報を表します。

```csharp
public class ChangeInfo
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [ChangeInfo](changeinfo)() | デフォルトコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Authors](../../groupdocs.comparison.result/changeinfo/authors) { get; set; } | 著者の一覧。 |
| [Box](../../groupdocs.comparison.result/changeinfo/box) { get; set; } | 変更された要素の座標。 |
| [Column](../../groupdocs.comparison.result/changeinfo/column) { get; set; } | 変更されたセルのゼロベース列インデックス。Cells 比較ツール (XLSX、CSV、ODS など) で設定され、その他の場合は null です。 |
| [ColumnHeader](../../groupdocs.comparison.result/changeinfo/columnheader) { get; set; } | 対応する列の列ヘッダー テキストは、ワークシートの最初の行から取得されます。最初の行にヘッダー値がある場合に Cells 比較ツールで設定され、その他の場合は null です。 |
| [ComparisonAction](../../groupdocs.comparison.result/changeinfo/comparisonaction) { get; set; } | アクション (受諾または拒否)。このフィールドは比較に対してこの変更をどう処理するかを指示します。 |
| [ComponentType](../../groupdocs.comparison.result/changeinfo/componenttype) { get; set; } | 変更されたコンポーネントのタイプ。 |
| [Id](../../groupdocs.comparison.result/changeinfo/id) { get; set; } | 変更の ID。 |
| [PageInfo](../../groupdocs.comparison.result/changeinfo/pageinfo) { get; set; } | 現在の変更が配置されているページ。 |
| [Row](../../groupdocs.comparison.result/changeinfo/row) { get; set; } | 変更されたセルのゼロベース行インデックス。Cells 比較ツール (XLSX、CSV、ODS など) で設定され、その他の場合は null です。 |
| [SourceText](../../groupdocs.comparison.result/changeinfo/sourcetext) { get; set; } | ソース文書の変更されたテキスト。 |
| [StyleChanges](../../groupdocs.comparison.result/changeinfo/stylechanges) { get; set; } | スタイル変更の配列。 |
| [TargetText](../../groupdocs.comparison.result/changeinfo/targettext) { get; set; } | ターゲット文書の変更されたテキスト。 |
| [Text](../../groupdocs.comparison.result/changeinfo/text) { get; set; } | 変更のテキスト値。 |
| [Type](../../groupdocs.comparison.result/changeinfo/type) { get; } | 変更のタイプ。 |

### 関連項目

* namespace [GroupDocs.Comparison.Result](../../groupdocs.comparison.result)
* assembly [GroupDocs.Comparison](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Comparison.dll 用に生成されました -->
