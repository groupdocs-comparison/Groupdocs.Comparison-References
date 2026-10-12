---
title: "WordCompareOptions"
second_title: "GroupDocs.Comparison 适用于 .NET 的 API 参考"
description: "Word 文档特定的比较选项。继承自 CompareOptions./compareoptions 的通用选项。"
type: docs
weight: 440
url: /zh/net/groupdocs.comparison.options/wordcompareoptions/
---
## WordCompareOptions class

Word 文档特定的比较选项。继承自 [`CompareOptions`](../compareoptions) 的通用选项。

```csharp
public class WordCompareOptions : CompareOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [WordCompareOptions](wordcompareoptions)() | 初始化一个 [`WordCompareOptions`](../wordcompareoptions) 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CalculateCoordinates](../../groupdocs.comparison.options/compareoptions/calculatecoordinates) { get; set; } | 指示是否计算已更改组件的坐标。 |
| [CalculateCoordinatesMode](../../groupdocs.comparison.options/compareoptions/calculatecoordinatesmode) { get; set; } | 指定已更改组件模式的坐标计算方式。 |
| [ChangedItemStyle](../../groupdocs.comparison.options/compareoptions/changeditemstyle) { get; set; } | 描述已更改组件的样式。 |
| [CompareBookmarks](../../groupdocs.comparison.options/wordcompareoptions/comparebookmarks) { get; set; } | 获取或设置是否比较源文档和目标文档中的书签并在结果中包含差异。 |
| [CompareDocumentProperty](../../groupdocs.comparison.options/wordcompareoptions/comparedocumentproperty) { get; set; } | 获取或设置是否比较内置和自定义文档属性并在结果中包含差异（例如在属性摘要页上）。 |
| [CompareVariableProperty](../../groupdocs.comparison.options/wordcompareoptions/comparevariableproperty) { get; set; } | 获取或设置是否比较文档变量属性（例如 DOCVARIABLE 字段）并在结果中包含差异。 |
| [DeletedItemStyle](../../groupdocs.comparison.options/compareoptions/deleteditemstyle) { get; set; } | 描述已删除组件的样式。 |
| [DetalisationLevel](../../groupdocs.comparison.options/compareoptions/detalisationlevel) { get; set; } | 获取或设置比较详细级别。 |
| [DetectStyleChanges](../../groupdocs.comparison.options/compareoptions/detectstylechanges) { get; set; } | 指示是否检测样式更改。 |
| [DiagramMasterSetting](../../groupdocs.comparison.options/compareoptions/diagrammastersetting) { get; set; } | 获取或设置主文件的路径值，或在没有主文件路径的情况下进行比较。此选项仅适用于 Diagram。 |
| [DirectoryCompare](../../groupdocs.comparison.options/compareoptions/directorycompare) { get; set; } | 用于开启文件夹比较的控制。 |
| [DisplayMode](../../groupdocs.comparison.options/wordcompareoptions/displaymode) { get; set; } | 获取或设置比较结果的显示方式：作为在“Track Changes”模式下的 Word 修订（Revisions），或作为直接渲染到文档中的高亮更改（Highlight）。 |
| [ExtendedSummaryPage](../../groupdocs.comparison.options/compareoptions/extendedsummarypage) { get; set; } | 指示是否将扩展的文件比较信息添加到摘要页。 |
| [FolderComparisonExtension](../../groupdocs.comparison.options/compareoptions/foldercomparisonextension) { get; set; } | 获取或设置生成的文件夹比较文件的格式。 |
| [GenerateSummaryPage](../../groupdocs.comparison.options/compareoptions/generatesummarypage) { get; set; } | 指示是否在结果文档中添加包含检测到的更改统计信息的摘要页。 |
| [HeaderFootersComparison](../../groupdocs.comparison.options/compareoptions/headerfooterscomparison) { get; set; } | 用于开启页眉/页脚内容比较的控制。 |
| [IgnoreChangeSettings](../../groupdocs.comparison.options/compareoptions/ignorechangesettings) { get; set; } | 获取或设置基于相似性忽略更改的设置。 |
| [InsertedItemStyle](../../groupdocs.comparison.options/compareoptions/inserteditemstyle) { get; set; } | 描述插入组件的样式。 |
| [LeaveGaps](../../groupdocs.comparison.options/wordcompareoptions/leavegaps) { get; set; } | 获取或设置是否在插入或删除的内容位置保留空行以保持布局和行数；与 [`ShowInsertedContent`](../compareoptions/showinsertedcontent) 和 [`ShowDeletedContent`](../compareoptions/showdeletedcontent) 一起使用。 |
| [MarkChangedContent](../../groupdocs.comparison.options/compareoptions/markchangedcontent) { get; set; } | 指示是否在文字处理文档中对形状使用框架，以及在图像文档中对矩形使用框架。 |
| [MarkLineBreaks](../../groupdocs.comparison.options/wordcompareoptions/marklinebreaks) { get; set; } | 获取或设置是否在结果中对文档之间不同的段落（行）换行进行可视标记。 |
| [MarkNestedContent](../../groupdocs.comparison.options/compareoptions/marknestedcontent) { get; set; } | 获取或设置一个值，指示是否将已删除或已插入元素的子项标记为已删除或已插入。 |
| [OriginalSize](../../groupdocs.comparison.options/compareoptions/originalsize) { get; set; } | 获取或设置被比较文档的原始尺寸。 |
| [PaperSize](../../groupdocs.comparison.options/compareoptions/papersize) { get; set; } | 获取或设置结果文档的纸张尺寸。 |
| [PasswordSaveOption](../../groupdocs.comparison.options/compareoptions/passwordsaveoption) { get; set; } | 获取或设置密码保存选项。 |
| [RevisionAuthorName](../../groupdocs.comparison.options/wordcompareoptions/revisionauthorname) { get; set; } | 获取或设置在启用 !:WordTrackChanges 时用于修订的作者名称。如果设置，该名称将应用于结果文档中的修订标记。 |
| [SensitivityOfComparison](../../groupdocs.comparison.options/compareoptions/sensitivityofcomparison) { get; set; } | 获取或设置比较的灵敏度。 |
| [SensitivityOfComparisonForTables](../../groupdocs.comparison.options/compareoptions/sensitivityofcomparisonfortables) { get; set; } | 获取或设置表格比较的灵敏度。 |
| [ShowDeletedContent](../../groupdocs.comparison.options/compareoptions/showdeletedcontent) { get; set; } | 指示是否在结果文档中显示已删除的组件。 |
| [ShowInsertedContent](../../groupdocs.comparison.options/compareoptions/showinsertedcontent) { get; set; } | 指示是否在结果文档中显示已插入的组件。 |
| [ShowOnlyChanged](../../groupdocs.comparison.options/compareoptions/showonlychanged) { get; set; } | 用于启用仅显示更改项的控制。 |
| [ShowOnlySummaryPage](../../groupdocs.comparison.options/compareoptions/showonlysummarypage) { get; set; } | 指示是否在结果文档中仅留下包含检测到的更改统计信息的页面。 |
| [ShowRevisions](../../groupdocs.comparison.options/wordcompareoptions/showrevisions) { get; set; } | 获取或设置结果文档是否保持修订标记可见。如果为 false，则所有修订都被接受，结果显示为最终文本。仅当 [`DisplayMode`](./displaymode) 设置为 Highlight 时此设置才有意义。默认值为 true。 |
| [UserMasterPath](../../groupdocs.comparison.options/compareoptions/usermasterpath) { get; set; } | 用于图表的用户主模板的路径。 |
| [WordsSeparatorChars](../../groupdocs.comparison.options/compareoptions/wordsseparatorchars) { set; } | 获取或设置用于将文本拆分为单词的分隔符数组。 |

### 另见

* class [CompareOptions](../compareoptions)
* namespace [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.Comparison.dll 生成 -->
