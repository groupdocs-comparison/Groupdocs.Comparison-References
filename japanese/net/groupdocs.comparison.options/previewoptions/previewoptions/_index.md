---
title: "PreviewOptions"
second_title: "GroupDocs.Comparison for .NET API リファレンス"
description: "PreviewOptionsgroupdocs.comparison.options/previewoptions クラスの新しいインスタンスを初期化します。"
type: docs
weight: 10
url: /ja/net/groupdocs.comparison.options/previewoptions/previewoptions/
---
## PreviewOptions(CreatePageStream) {#constructor}

[`PreviewOptions`](../../previewoptions) クラスの新しいインスタンスを初期化します。

```csharp
public PreviewOptions(CreatePageStream createPageStream)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 出力ページプレビュー ストリームを作成するメソッドを定義するデリゲート。 |

### 関連項目

* delegate [CreatePageStream](../../../groupdocs.comparison.common.delegates/createpagestream)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Comparison.Options](../../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

[`PreviewOptions`](../../previewoptions) クラスの新しいインスタンスを初期化します。

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 出力ページプレビュー ストリームを作成するメソッドを定義するデリゲート。 |
| releasePageStream | ReleasePageStream | 出力ページプレビュー ストリームを解放するメソッドを定義するデリゲート。 |

### 関連項目

* delegate [CreatePageStream](../../../groupdocs.comparison.common.delegates/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.comparison.common.delegates/releasepagestream)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Comparison.Options](../../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Comparison.dll 用に生成されました -->
