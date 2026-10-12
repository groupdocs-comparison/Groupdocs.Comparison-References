---
title: "PdfCompareOptions.ComparisonDisplayMode"
second_title: "GroupDocs.Comparison for .NET API リファレンス"
description: "PDF比較結果ドキュメントのレイアウト方法を制御します。"
type: docs
weight: 370
url: /ja/net/groupdocs.comparison.options/pdfcompareoptions.comparisondisplaymode/
---
## PdfCompareOptions.ComparisonDisplayMode enumeration

PDF比較結果ドキュメントのレイアウト方法を制御します。

```csharp
public enum ComparisonDisplayMode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Inline | `0` | デフォルトモード。削除されたコンテンツが1つの色で、挿入されたコンテンツが別の色でハイライトされる単一の結合PDFドキュメントを生成します。ソースとターゲットのコンテンツが同じページに共存するため、文書が大きく異なる場合、重なりが生じる可能性があります。 |
| SideBySide | `1` | 各結果ページは、ソースページと対応するターゲットページを並べて表示します。削除は左側（ソース側）に、挿入は右側（ターゲット側）に表示されます。2つのドキュメントの内容は決して重ならないため、ドキュメントの差異が大きい場合にこのモードが適しています。 |
| Interleaved | `2` | 奇数ページはソースドキュメント（削除を表示）から、偶数ページはターゲットドキュメント（挿入を表示）から取得する、交互ページのドキュメントを生成します。結果を PDF ビューアで「Two Page View」モードを有効にして開くと、画面上で各ソース/ターゲットのペアを並べて確認できます。SideBySide と同様に、このモードはコンテンツの重なりを防ぎ、差異が大きいドキュメントに最適です。 |

### 関連項目

* class [PdfCompareOptions](../pdfcompareoptions)
* namespace [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Comparison.dll 用に生成されました -->
