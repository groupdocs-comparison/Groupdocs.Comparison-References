---
title: "SensitivityOfComparisonForTables"
second_title: "GroupDocs.Comparison 适用于 .NET 的 API 参考"
description: "获取或设置表格比较的灵敏度。"
type: docs
weight: 220
url: /zh/net/groupdocs.comparison.options/compareoptions/sensitivityofcomparisonfortables/
---
## CompareOptions.SensitivityOfComparisonForTables property

获取或设置表格比较的灵敏度。

```csharp
public int? SensitivityOfComparisonForTables { get; set; }
```

### Property Value

如果该值为 null，则使用 SensitivityOfComparison。两个被比较对象中已删除和已插入元素相对于这些对象全部元素的百分比。如果超过此百分比，则对象不进行比较，而被视为完全插入和删除。最小值 - 0% => 当两个被比较对象的公共子序列长度为任意时，比较不进行。默认值 - 75% => 当两个被比较对象中已删除和已插入元素相对于全部元素的百分比不超过 75% 时，进行比较。最大值 - 100% => 在两个被比较对象的任何公共子序列长度下都进行比较。

### 另见

* class [CompareOptions](../../compareoptions)
* namespace [GroupDocs.Comparison.Options](../../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.Comparison.dll 生成 -->
