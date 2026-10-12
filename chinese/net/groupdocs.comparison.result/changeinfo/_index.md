---
title: "ChangeInfo"
second_title: "GroupDocs.Comparison 适用于 .NET 的 API 参考"
description: "表示有关更改的信息。"
type: docs
weight: 460
url: /zh/net/groupdocs.comparison.result/changeinfo/
---
## ChangeInfo class

表示有关更改的信息。

```csharp
public class ChangeInfo
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ChangeInfo](changeinfo)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Authors](../../groupdocs.comparison.result/changeinfo/authors) { get; set; } | 作者列表。 |
| [Box](../../groupdocs.comparison.result/changeinfo/box) { get; set; } | 已更改元素的坐标。 |
| [Column](../../groupdocs.comparison.result/changeinfo/column) { get; set; } | 已更改单元格的零基列索引。对 Cells 比较器（XLSX、CSV、ODS 等）填充，否则为 null。 |
| [ColumnHeader](../../groupdocs.comparison.result/changeinfo/columnheader) { get; set; } | 对应列的列标题文本取自工作表的第一行。若第一行包含标题值，则在 Cells 比较器中填充，否则为 null。 |
| [ComparisonAction](../../groupdocs.comparison.result/changeinfo/comparisonaction) { get; set; } | 操作（接受或拒绝）。此字段告诉比较在此更改上应执行的操作。 |
| [ComponentType](../../groupdocs.comparison.result/changeinfo/componenttype) { get; set; } | 已更改组件的类型。 |
| [Id](../../groupdocs.comparison.result/changeinfo/id) { get; set; } | 更改的 ID。 |
| [PageInfo](../../groupdocs.comparison.result/changeinfo/pageinfo) { get; set; } | 当前更改所在的页面。 |
| [Row](../../groupdocs.comparison.result/changeinfo/row) { get; set; } | 已更改单元格的零基行索引。对 Cells 比较器（XLSX、CSV、ODS 等）填充，否则为 null。 |
| [SourceText](../../groupdocs.comparison.result/changeinfo/sourcetext) { get; set; } | 源文档的更改文本。 |
| [StyleChanges](../../groupdocs.comparison.result/changeinfo/stylechanges) { get; set; } | 样式更改数组。 |
| [TargetText](../../groupdocs.comparison.result/changeinfo/targettext) { get; set; } | 目标文档的更改文本。 |
| [Text](../../groupdocs.comparison.result/changeinfo/text) { get; set; } | 更改的文本值。 |
| [Type](../../groupdocs.comparison.result/changeinfo/type) { get; } | 更改的类型。 |

### 另见

* namespace [GroupDocs.Comparison.Result](../../groupdocs.comparison.result)
* assembly [GroupDocs.Comparison](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.Comparison.dll 生成 -->
