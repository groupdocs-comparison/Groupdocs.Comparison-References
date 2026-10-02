---
title: "PdfCompareOptions.ComparisonDisplayMode"
second_title: "GroupDocs.Comparison 适用于 .NET 的 API 参考"
description: "控制 Pdf 比较结果文档的布局方式。"
type: docs
weight: 370
url: /zh/net/groupdocs.comparison.options/pdfcompareoptions.comparisondisplaymode/
---
## PdfCompareOptions.ComparisonDisplayMode enumeration

控制 Pdf 比较结果文档的布局方式。

```csharp
public enum ComparisonDisplayMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Inline | `0` | 默认模式。生成一个合并的 PDF 文档，其中已删除的内容以一种颜色高亮显示，已插入的内容以另一种颜色高亮显示。源内容和目标内容在同一页面共存，当文档差异显著时可能导致重叠。 |
| SideBySide | `1` | 每个结果页都会并排显示源页面及其对应的目标页面。删除内容显示在左侧（源侧），插入内容显示在右侧（目标侧）。两个文档的内容永不重叠，使此模式适用于文档差异很大的情况。 |
| Interleaved | `2` | 生成一个交替页的文档：奇数页来自源文档（显示删除），偶数页来自目标文档（显示插入）。在启用了"Two Page View"的 PDF 查看器中打开结果，可在屏幕上并排查看每个源/目标对。与 SideBySide 类似，此模式防止内容重叠，最适合差异巨大的文档。 |

### 另见

* class [PdfCompareOptions](../pdfcompareoptions)
* namespace [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.Comparison.dll 生成 -->
