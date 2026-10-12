---
title: "SensitivityOfComparison"
second_title: "GroupDocs.Comparison for .NET API リファレンス"
description: "比較の感度を取得または設定します。"
type: docs
weight: 210
url: /ja/net/groupdocs.comparison.options/compareoptions/sensitivityofcomparison/
---
## CompareOptions.SensitivityOfComparison property

比較の感度を取得または設定します。

```csharp
public int SensitivityOfComparison { get; set; }
```

### Property Value

2 つの比較対象オブジェクトのすべての要素に対する、削除および挿入された要素の割合です。この割合が超過した場合、オブジェクトは比較されず、完全に挿入および削除されたものとみなされます。Min value - 0% => 2 つの比較対象オブジェクトの共通部分列の長さにかかわらず比較は行われません。Default value - 75% => 削除および挿入された要素の割合が 75% 以下であれば比較が行われます。Max value - 100% => 2 つの比較対象オブジェクトの共通部分列の長さに関係なく比較が行われます。

### 関連項目

* class [CompareOptions](../../compareoptions)
* namespace [GroupDocs.Comparison.Options](../../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Comparison.dll 用に生成されました -->
