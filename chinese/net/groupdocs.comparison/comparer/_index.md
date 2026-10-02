---
title: "比较器"
second_title: "GroupDocs.Comparison 适用于 .NET 的 API 参考"
description: "表示控制文档比较过程的主类。"
type: docs
weight: 100
url: /zh/net/groupdocs.comparison/comparer/
---
## Comparer class

表示控制文档比较过程的主类。

```csharp
public sealed class Comparer : IDisposable
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Comparer](comparer#constructor)(Stream) | 使用源文档流初始化 [`Comparer`](../comparer) 类的新实例。 |
| [Comparer](comparer#constructor_4)(string) | 使用源文件路径初始化 [`Comparer`](../comparer) 类的新实例。 |
| [Comparer](comparer#constructor_1)(Stream, ComparerSettings) | 使用源文档流和 [`ComparerSettings`](../comparersettings) 初始化 [`Comparer`](../comparer) 类的新实例。 |
| [Comparer](comparer#constructor_2)(Stream, LoadOptions) | 使用源文档流和 [`LoadOptions`](../../groupdocs.comparison.options/loadoptions) 初始化 [`Comparer`](../comparer) 的新实例。 |
| [Comparer](comparer#constructor_6)(string, CompareOptions) | 使用源文件夹路径和 [`CompareOptions`](../../groupdocs.comparison.options/compareoptions) 初始化 [`Comparer`](../comparer) 的新实例。 |
| [Comparer](comparer#constructor_5)(string, ComparerSettings) | 使用源文件路径和 [`ComparerSettings`](../comparersettings) 初始化 [`Comparer`](../comparer) 类的新实例。 |
| [Comparer](comparer#constructor_7)(string, LoadOptions) | 使用源文件路径和[`LoadOptions`](../../groupdocs.comparison.options/loadoptions)初始化[`Comparer`](../comparer)的新实例。 |
| [Comparer](comparer#constructor_3)(Stream, LoadOptions, ComparerSettings) | 使用文档流、[`LoadOptions`](../../groupdocs.comparison.options/loadoptions)和[`ComparerSettings`](../comparersettings)初始化[`Comparer`](../comparer)类的新实例。 |
| [Comparer](comparer#constructor_8)(string, LoadOptions, ComparerSettings) | 使用源文件路径、[`LoadOptions`](../../groupdocs.comparison.options/loadoptions)和[`ComparerSettings`](../comparersettings)初始化[`Comparer`](../comparer)类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Result](../../groupdocs.comparison/comparer/result) { get; } | 结果文档。 |
| [Source](../../groupdocs.comparison/comparer/source) { get; } | 正在比较的源文件。 |
| [SourceFolder](../../groupdocs.comparison/comparer/sourcefolder) { get; } | 正在比较的源文件夹。 |
| [TargetFolder](../../groupdocs.comparison/comparer/targetfolder) { get; set; } | 正在比较的目标文件夹。 |
| [Targets](../../groupdocs.comparison/comparer/targets) { get; } | 用于与源文件比较的目标文件列表。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Add](../../groupdocs.comparison/comparer/add#add)(Stream) | 向比较中添加文档流。 |
| [Add](../../groupdocs.comparison/comparer/add#add_2)(string) | 向比较中添加文件。 |
| [Add](../../groupdocs.comparison/comparer/add#add_1)(Stream, LoadOptions) | 使用指定的加载选项向比较中添加文档流。 |
| [Add](../../groupdocs.comparison/comparer/add#add_3)(string, CompareOptions) | 向比较中添加文件夹。 |
| [Add](../../groupdocs.comparison/comparer/add#add_4)(string, LoadOptions) | 使用指定的加载选项向比较中添加文件。 |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges)(Stream, ApplyChangeOptions) | 接受或拒绝更改并将其应用于结果文档。 |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_2)(string, ApplyChangeOptions) | 接受或拒绝更改并将其应用于结果文档。 |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_1)(Stream, SaveOptions, ApplyChangeOptions) | 接受或拒绝更改并将其应用于结果文档。 |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_3)(string, SaveOptions, ApplyChangeOptions) | 接受或拒绝更改并将其应用于结果文档。 |
| [Compare](../../groupdocs.comparison/comparer/compare#compare)() | 使用默认选项比较文档而不保存结果 |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_1)(CompareOptions) | 比较文档而不保存结果。 |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_3)(Stream) | 比较文档并将结果保存到文件流 |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_7)(string) | 比较文档并将结果保存到文件路径 |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_2)(SaveOptions, CompareOptions) | 比较文档而不保存结果。 |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_4)(Stream, CompareOptions) | 比较文档并将结果保存到文件流 |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_5)(Stream, SaveOptions) | 比较文档并将结果保存到文件流 |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_8)(string, CompareOptions) | 比较文档并将结果保存到文件路径 |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_9)(string, SaveOptions) | 比较文档并将结果保存到文件路径 |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_6)(Stream, SaveOptions, CompareOptions) | 比较文档并将结果保存到流。 |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_10)(string, SaveOptions, CompareOptions) | 比较文档并将结果保存到文件路径 |
| [CompareDirectory](../../groupdocs.comparison/comparer/comparedirectory)(string, CompareOptions) | 比较目录并将结果保存到文件路径 |
| [Dispose](../../groupdocs.comparison/comparer/dispose)() | 释放资源。 |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges)() | 获取源文件和目标文件之间的更改列表。 |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges_1)(ChangeType) | 获取源文件和目标文件之间的更改列表。 |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges_2)(GetChangeOptions) | 获取源文件和目标文件之间的更改列表。 |
| [GetResultDocumentStream](../../groupdocs.comparison/comparer/getresultdocumentstream)() | 获取结果文档的流，如果流不存在则返回 null |
| [GetResultString](../../groupdocs.comparison/comparer/getresultstring)() | 获取比较后的结果字符串（仅适用于文本比较）。 |

### 另见

* namespace [GroupDocs.Comparison](../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.Comparison.dll 生成 -->
