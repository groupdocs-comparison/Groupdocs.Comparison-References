---
title: "RevisionAction"
second_title: "GroupDocs.Comparison 适用于 .NET 的 API 参考"
description: "可应用于修订的操作。"
type: docs
weight: 530
url: /zh/net/groupdocs.comparison.words.revision/revisionaction/
---
## RevisionAction enumeration

可应用于修订的操作。

```csharp
public enum RevisionAction
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| None | `0` | 无事可做。 |
| Accept | `1` | 如果修订的类型为 INSERTION，则会显示该修订；如果类型为 DELETION，则会将其删除。 |
| Reject | `2` | 如果修订的类型为 INSERTION，则会将其删除；如果类型为 DELETION，则会显示该修订。 |

### 另见

* namespace [GroupDocs.Comparison.Words.Revision](../../groupdocs.comparison.words.revision)
* assembly [GroupDocs.Comparison](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.Comparison.dll 生成 -->
