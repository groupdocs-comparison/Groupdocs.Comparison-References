---
title: "ReleasePageStream"
second_title: "GroupDocs.Comparison 适用于 .NET 的 API 参考"
description: "委托，定义用于释放 PreviewOptions../groupdocs.comparison.options/previewoptions 使用的输出页面预览流的方法。"
type: docs
weight: 30
url: /zh/net/groupdocs.comparison.common.delegates/releasepagestream/
---
## ReleasePageStream delegate

委托，定义用于释放 [`PreviewOptions`](../../groupdocs.comparison.options/previewoptions) 使用的输出页面预览流的方法。

```csharp
public delegate void ReleasePageStream(int pageNumber, Stream pageStream);
```

| Parameter | Type | 描述 |
| --- | --- | --- |
| pageNumber | Int32 | 预览页面的数量。 |
| pageStream | Stream | 要释放的页面流。 |

### 另见

* namespace [GroupDocs.Comparison.Common.Delegates](../../groupdocs.comparison.common.delegates)
* assembly [GroupDocs.Comparison](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.Comparison.dll 生成 -->
