---
title: "RevisionHandler"
second_title: "GroupDocs.Comparison for .NET API リファレンス"
description: "リビジョンが含まれるファイルへのパスで、RevisionHandlergroupdocs.comparison.words.revision/revisionhandler クラスの新しいインスタンスを初期化します。"
type: docs
weight: 10
url: /ja/net/groupdocs.comparison.words.revision/revisionhandler/revisionhandler/
---
## RevisionHandler(string) {#constructor_2}

リビジョンが含まれるファイルへのパスで、[`RevisionHandler`](../../revisionhandler) クラスの新しいインスタンスを初期化します。

```csharp
public RevisionHandler(string filePath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| filePath | String | ファイルパス |

### 関連項目

* class [RevisionHandler](../../revisionhandler)
* namespace [GroupDocs.Comparison.Words.Revision](../../../groupdocs.comparison.words.revision)
* assembly [GroupDocs.Comparison](../../../)

---

## RevisionHandler(Stream) {#constructor}

リビジョンが含まれるファイルストリームで、[`RevisionHandler`](../../revisionhandler) クラスの新しいインスタンスを初期化します。

```csharp
public RevisionHandler(Stream file)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| ファイル | Stream | ソースドキュメントストリーム |

### 関連項目

* class [RevisionHandler](../../revisionhandler)
* namespace [GroupDocs.Comparison.Words.Revision](../../../groupdocs.comparison.words.revision)
* assembly [GroupDocs.Comparison](../../../)

---

## RevisionHandler(Stream, bool) {#constructor_1}

リビジョンが含まれるファイルストリームと明示的なストリーム所有権制御で、[`RevisionHandler`](../../revisionhandler) クラスの新しいインスタンスを初期化します。

```csharp
public RevisionHandler(Stream file, bool leaveOpen)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| ファイル | Stream | ソースドキュメントストリーム |
| leaveOpen | Boolean | true の場合、呼び出し元は *file* の所有権を保持し、破棄する責任があります。false（デフォルト）の場合、[`Dispose`](../dispose) がストリームを閉じます。 |

### 関連項目

* class [RevisionHandler](../../revisionhandler)
* namespace [GroupDocs.Comparison.Words.Revision](../../../groupdocs.comparison.words.revision)
* assembly [GroupDocs.Comparison](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Comparison.dll 用に生成されました -->
