---
title: "PreviewOptions"
second_title: "GroupDocs.Comparison 适用于 .NET 的 API 参考"
description: "初始化 PreviewOptionsgroupdocs.comparison.options/previewoptions 类的新实例。"
type: docs
weight: 10
url: /zh/net/groupdocs.comparison.options/previewoptions/previewoptions/
---
## PreviewOptions(CreatePageStream) {#constructor}

初始化 [`PreviewOptions`](../../previewoptions) 类的新实例。

```csharp
public PreviewOptions(CreatePageStream createPageStream)
```

| Parameter | Type | 描述 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 定义用于创建输出页面预览流的方法的委托。 |

### 另见

* delegate [CreatePageStream](../../../groupdocs.comparison.common.delegates/createpagestream)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Comparison.Options](../../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

初始化 [`PreviewOptions`](../../previewoptions) 类的新实例。

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```

| Parameter | Type | 描述 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 定义用于创建输出页面预览流的方法的委托。 |
| releasePageStream | ReleasePageStream | 委托，定义用于释放输出页面预览流的方法。 |

### 另见

* delegate [CreatePageStream](../../../groupdocs.comparison.common.delegates/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.comparison.common.delegates/releasepagestream)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Comparison.Options](../../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.Comparison.dll 生成 -->
