---
title: "DetalisationLevel"
second_title: "GroupDocs.Comparison 适用于 .NET 的 API 参考"
description: "指定比较细节的级别。"
type: docs
weight: 230
url: /zh/net/groupdocs.comparison.options/detalisationlevel/
---
## DetalisationLevel enumeration

指定比较细节的级别。

```csharp
public enum DetalisationLevel
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Low | `0` | 低级。提供最快的比较速度，牺牲比较质量。比较按单词进行。 |
| Middle | `1` | 中级。在比较速度和质量之间取得合理的折中。比较按字符进行，但忽略字符大小写和空格计数。 |
| High | `2` | 高级。提供最佳的比较质量，但速度最低。比较按字符进行，考虑字符大小写和空格计数。 |

### 另见

* namespace [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.Comparison.dll 生成 -->
