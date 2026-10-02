---
title: "RevisionHandler"
second_title: "GroupDocs.Comparison for .NET API リファレンス"
description: "リビジョン処理を制御する主要クラスを表します。"
type: docs
weight: 540
url: /ja/net/groupdocs.comparison.words.revision/revisionhandler/
---
## RevisionHandler class

リビジョン処理を制御する主要クラスを表します。

```csharp
public sealed class RevisionHandler : IDisposable
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [RevisionHandler](revisionhandler#constructor)(Stream) | リビジョンを含むファイルストリームで、[`RevisionHandler`](../revisionhandler) クラスの新しいインスタンスを初期化します。 |
| [RevisionHandler](revisionhandler#constructor_2)(string) | リビジョンを含むファイルへのパスで、[`RevisionHandler`](../revisionhandler) クラスの新しいインスタンスを初期化します。 |
| [RevisionHandler](revisionhandler#constructor_1)(Stream, bool) | リビジョンを含むファイルストリームと明示的なストリーム所有権制御で、[`RevisionHandler`](../revisionhandler) クラスの新しいインスタンスを初期化します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [ApplyRevisionChanges](../../groupdocs.comparison.words.revision/revisionhandler/applyrevisionchanges#applyrevisionchanges)(ApplyRevisionOptions) | リビジョンの変更を処理し、リビジョンが取得された同じファイルに適用します。 |
| [ApplyRevisionChanges](../../groupdocs.comparison.words.revision/revisionhandler/applyrevisionchanges#applyrevisionchanges_1)(Stream, ApplyRevisionOptions) | リビジョンの変更を処理し、結果をドキュメントストリームに書き込みます。 |
| [ApplyRevisionChanges](../../groupdocs.comparison.words.revision/revisionhandler/applyrevisionchanges#applyrevisionchanges_2)(string, ApplyRevisionOptions) | リビジョンの変更を処理し、結果を指定されたパスのファイルに書き込みます。 |
| [Dispose](../../groupdocs.comparison.words.revision/revisionhandler/dispose)() | リソースを解放します。 |
| [GetRevisions](../../groupdocs.comparison.words.revision/revisionhandler/getrevisions)() | すべてのリビジョンのリストを取得します。 |

### 関連項目

* namespace [GroupDocs.Comparison.Words.Revision](../../groupdocs.comparison.words.revision)
* assembly [GroupDocs.Comparison](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Comparison.dll 用に生成されました -->
