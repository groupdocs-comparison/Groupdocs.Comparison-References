---
title: RevisionHandler
second_title: GroupDocs.Comparison for .NET API リファレンス
description: リビジョンの処理を制御するメイン クラスを表します
type: docs
weight: 460
url: /ja/net/groupdocs.comparison.words.revision/revisionhandler/
---
## RevisionHandler class

リビジョンの処理を制御するメイン クラスを表します。

```csharp
public class RevisionHandler : IDisposable
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [RevisionHandler](revisionhandler#constructor)(Stream) | の新しいインスタンスを初期化します[`RevisionHandler`](../revisionhandler)リビジョンを持つファイル ストリームを持つクラス. |
| [RevisionHandler](revisionhandler#constructor_1)(string) | の新しいインスタンスを初期化します[`RevisionHandler`](../revisionhandler)リビジョンを持つファイルへのパスを持つクラス. |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [ApplyRevisionChanges](../../groupdocs.comparison.words.revision/revisionhandler/applyrevisionchanges#applyrevisionchanges)(ApplyRevisionOptions) | リビジョンの変更を処理し、リビジョンが取得された同じファイルに適用します。 |
| [ApplyRevisionChanges](../../groupdocs.comparison.words.revision/revisionhandler/applyrevisionchanges#applyrevisionchanges_1)(Stream, ApplyRevisionOptions) | リビジョンの変更を処理し、結果がドキュメント ストリームに書き込まれます。 |
| [ApplyRevisionChanges](../../groupdocs.comparison.words.revision/revisionhandler/applyrevisionchanges#applyrevisionchanges_2)(string, ApplyRevisionOptions) | リビジョンの変更を処理し、結果がパスで指定されたファイルに書き込まれます。 |
| [Dispose](../../groupdocs.comparison.words.revision/revisionhandler/dispose)() | リソースを解放します。 |
| [GetRevisions](../../groupdocs.comparison.words.revision/revisionhandler/getrevisions)() | すべてのリビジョンのリストを取得します。 |

### 関連項目

* 名前空間 [GroupDocs.Comparison.Words.Revision](../../groupdocs.comparison.words.revision)
* 組み立て [GroupDocs.Comparison](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Comparison.dll -->