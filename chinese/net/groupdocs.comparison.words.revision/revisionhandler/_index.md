---
title: "RevisionHandler"
second_title: "GroupDocs.Comparison 适用于 .NET 的 API 参考"
description: "表示控制修订处理的主类。"
type: docs
weight: 540
url: /zh/net/groupdocs.comparison.words.revision/revisionhandler/
---
## RevisionHandler class

表示控制修订处理的主类。

```csharp
public sealed class RevisionHandler : IDisposable
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [RevisionHandler](revisionhandler#constructor)(Stream) | 使用包含修订的文件流初始化 [`RevisionHandler`](../revisionhandler) 类的新实例。 |
| [RevisionHandler](revisionhandler#constructor_2)(string) | 使用指向包含修订的文件的路径初始化 [`RevisionHandler`](../revisionhandler) 类的新实例。 |
| [RevisionHandler](revisionhandler#constructor_1)(Stream, bool) | 使用包含修订的文件流以及显式的流所有权控制初始化 [`RevisionHandler`](../revisionhandler) 类的新实例。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [ApplyRevisionChanges](../../groupdocs.comparison.words.revision/revisionhandler/applyrevisionchanges#applyrevisionchanges)(ApplyRevisionOptions) | 处理修订中的更改并将其应用于获取修订的同一文件。 |
| [ApplyRevisionChanges](../../groupdocs.comparison.words.revision/revisionhandler/applyrevisionchanges#applyrevisionchanges_1)(Stream, ApplyRevisionOptions) | 处理修订中的更改，结果写入文档流。 |
| [ApplyRevisionChanges](../../groupdocs.comparison.words.revision/revisionhandler/applyrevisionchanges#applyrevisionchanges_2)(string, ApplyRevisionOptions) | 处理修订中的更改，结果写入指定路径的文件。 |
| [Dispose](../../groupdocs.comparison.words.revision/revisionhandler/dispose)() | 释放资源。 |
| [GetRevisions](../../groupdocs.comparison.words.revision/revisionhandler/getrevisions)() | 获取所有修订的列表。 |

### 另见

* namespace [GroupDocs.Comparison.Words.Revision](../../groupdocs.comparison.words.revision)
* assembly [GroupDocs.Comparison](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.Comparison.dll 生成 -->
