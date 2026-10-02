---
title: "DetalisationLevel"
second_title: "GroupDocs.Comparison for .NET API リファレンス"
description: "比較詳細のレベルを指定します。"
type: docs
weight: 230
url: /ja/net/groupdocs.comparison.options/detalisationlevel/
---
## DetalisationLevel enumeration

比較詳細のレベルを指定します。

```csharp
public enum DetalisationLevel
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Low | `0` | 低レベル。比較品質を犠牲にして最高の速度比較を提供します。比較は単語単位で実行されます。 |
| Middle | `1` | 中レベル。比較速度と品質の間の妥当な妥協点です。比較は文字単位で実行され、文字の大文字小文字とスペースは無視されます。 |
| High | `2` | 高レベル。最高の比較品質を提供しますが、速度は最も遅くなります。比較は文字単位で実行され、文字の大文字小文字とスペース数を考慮します。 |

### 関連項目

* namespace [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Comparison.dll 用に生成されました -->
