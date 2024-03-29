---
title: RevisionHandler
second_title: GroupDocs.Comparison for .NET API 参考
description: 表示控制修订处理的主类
type: docs
weight: 460
url: /zh/net/groupdocs.comparison.words.revision/revisionhandler/
---
## RevisionHandler class

表示控制修订处理的主类。

```csharp
public class RevisionHandler : IDisposable
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [RevisionHandler](revisionhandler#constructor)(Stream) | 初始化新实例[`RevisionHandler`](../revisionhandler)带有修订的文件流的类. |
| [RevisionHandler](revisionhandler#constructor_1)(string) | 初始化新实例[`RevisionHandler`](../revisionhandler)带有修订文件路径的类. |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [ApplyRevisionChanges](../../groupdocs.comparison.words.revision/revisionhandler/applyrevisionchanges#applyrevisionchanges)(ApplyRevisionOptions) | 处理修订中的更改并将它们应用于从中获取修订的同一文件。 |
| [ApplyRevisionChanges](../../groupdocs.comparison.words.revision/revisionhandler/applyrevisionchanges#applyrevisionchanges_1)(Stream, ApplyRevisionOptions) | 处理修订中的更改并将结果写入文档流。 |
| [ApplyRevisionChanges](../../groupdocs.comparison.words.revision/revisionhandler/applyrevisionchanges#applyrevisionchanges_2)(string, ApplyRevisionOptions) | 处理revisions中的变化，结果按路径写入指定文件。 |
| [Dispose](../../groupdocs.comparison.words.revision/revisionhandler/dispose)() | 释放资源。 |
| [GetRevisions](../../groupdocs.comparison.words.revision/revisionhandler/getrevisions)() | 获取所有修订的列表。 |

### 也可以看看

* 命名空间 [GroupDocs.Comparison.Words.Revision](../../groupdocs.comparison.words.revision)
* 部件 [GroupDocs.Comparison](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Comparison.dll -->
