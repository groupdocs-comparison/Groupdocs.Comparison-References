---
title: "PdfCompareOptions"
second_title: "GroupDocs.Comparison 适用于 .NET 的 API 参考"
description: "PDF 文档特定的比较选项。继承自 CompareOptions./compareoptions。"
type: docs
weight: 360
url: /zh/net/groupdocs.comparison.options/pdfcompareoptions/
---
## PdfCompareOptions class

PDF 文档特定的比较选项。继承自 [`CompareOptions`](../compareoptions)。

```csharp
public class PdfCompareOptions : CompareOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PdfCompareOptions](pdfcompareoptions)() | 初始化 [`PdfCompareOptions`](../pdfcompareoptions) 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AnnotationAuthorName](../../groupdocs.comparison.options/pdfcompareoptions/annotationauthorname) { get; set; } | 获取或设置在 [`DisplayMode`](./displaymode) 设置为 Interleaved 时用于注释的作者名称。 |
| [CalculateCoordinates](../../groupdocs.comparison.options/compareoptions/calculatecoordinates) { get; set; } | 指示是否计算已更改组件的坐标。 |
| [CalculateCoordinatesMode](../../groupdocs.comparison.options/compareoptions/calculatecoordinatesmode) { get; set; } | 指定已更改组件模式的坐标计算方式。 |
| [ChangedItemStyle](../../groupdocs.comparison.options/compareoptions/changeditemstyle) { get; set; } | 描述已更改组件的样式。 |
| [CompareImagesPdf](../../groupdocs.comparison.options/pdfcompareoptions/compareimagespdf) { get; set; } | 获取或设置指示是否在 PDF 文档中比较图像的值。 |
| [DeletedItemStyle](../../groupdocs.comparison.options/compareoptions/deleteditemstyle) { get; set; } | 描述已删除组件的样式。 |
| [DetalisationLevel](../../groupdocs.comparison.options/compareoptions/detalisationlevel) { get; set; } | 获取或设置比较详细级别。 |
| [DetectStyleChanges](../../groupdocs.comparison.options/compareoptions/detectstylechanges) { get; set; } | 指示是否检测样式更改。 |
| [DiagramMasterSetting](../../groupdocs.comparison.options/compareoptions/diagrammastersetting) { get; set; } | 获取或设置主文件的路径值，或在没有主文件路径的情况下进行比较。此选项仅适用于 Diagram。 |
| [DirectoryCompare](../../groupdocs.comparison.options/compareoptions/directorycompare) { get; set; } | 用于开启文件夹比较的控制。 |
| [DisplayMode](../../groupdocs.comparison.options/pdfcompareoptions/displaymode) { get; set; } | 获取或设置比较结果文档的布局方式。默认值为 Inline。 |
| [ExtendedSummaryPage](../../groupdocs.comparison.options/compareoptions/extendedsummarypage) { get; set; } | 指示是否将扩展的文件比较信息添加到摘要页。 |
| [FolderComparisonExtension](../../groupdocs.comparison.options/compareoptions/foldercomparisonextension) { get; set; } | 获取或设置生成的文件夹比较文件的格式。 |
| [GenerateSummaryPage](../../groupdocs.comparison.options/compareoptions/generatesummarypage) { get; set; } | 指示是否在结果文档中添加包含检测到的更改统计信息的摘要页。 |
| [HeaderFootersComparison](../../groupdocs.comparison.options/compareoptions/headerfooterscomparison) { get; set; } | 用于开启页眉/页脚内容比较的控制。 |
| [IgnoreChangeSettings](../../groupdocs.comparison.options/compareoptions/ignorechangesettings) { get; set; } | 获取或设置基于相似性忽略更改的设置。 |
| [ImagesInheritanceMode](../../groupdocs.comparison.options/pdfcompareoptions/imagesinheritancemode) { get; set; } | 指定在禁用图像比较时图像继承的来源。 |
| [InsertedItemStyle](../../groupdocs.comparison.options/compareoptions/inserteditemstyle) { get; set; } | 描述插入组件的样式。 |
| [MarkChangedContent](../../groupdocs.comparison.options/compareoptions/markchangedcontent) { get; set; } | 指示是否在文字处理文档中对形状使用框架，以及在图像文档中对矩形使用框架。 |
| [MarkNestedContent](../../groupdocs.comparison.options/compareoptions/marknestedcontent) { get; set; } | 获取或设置一个值，指示是否将已删除或已插入元素的子项标记为已删除或已插入。 |
| [OriginalSize](../../groupdocs.comparison.options/compareoptions/originalsize) { get; set; } | 获取或设置被比较文档的原始尺寸。 |
| [PagesSetup](../../groupdocs.comparison.options/pdfcompareoptions/pagessetup) { get; set; } | 获取或设置要比较的页码范围。为 null 时，将比较所有页。 |
| [PaperSize](../../groupdocs.comparison.options/compareoptions/papersize) { get; set; } | 获取或设置结果文档的纸张尺寸。 |
| [PasswordSaveOption](../../groupdocs.comparison.options/compareoptions/passwordsaveoption) { get; set; } | 获取或设置密码保存选项。 |
| [SensitivityOfComparison](../../groupdocs.comparison.options/compareoptions/sensitivityofcomparison) { get; set; } | 获取或设置比较的灵敏度。 |
| [SensitivityOfComparisonForTables](../../groupdocs.comparison.options/compareoptions/sensitivityofcomparisonfortables) { get; set; } | 获取或设置表格比较的灵敏度。 |
| [ShowDeletedContent](../../groupdocs.comparison.options/compareoptions/showdeletedcontent) { get; set; } | 指示是否在结果文档中显示已删除的组件。 |
| [ShowInsertedContent](../../groupdocs.comparison.options/compareoptions/showinsertedcontent) { get; set; } | 指示是否在结果文档中显示已插入的组件。 |
| [ShowOnlyChanged](../../groupdocs.comparison.options/compareoptions/showonlychanged) { get; set; } | 用于启用仅显示更改项的控制。 |
| [ShowOnlySummaryPage](../../groupdocs.comparison.options/compareoptions/showonlysummarypage) { get; set; } | 指示是否在结果文档中仅留下包含检测到的更改统计信息的页面。 |
| [UserMasterPath](../../groupdocs.comparison.options/compareoptions/usermasterpath) { get; set; } | 用于图表的用户主模板的路径。 |
| [WordsSeparatorChars](../../groupdocs.comparison.options/compareoptions/wordsseparatorchars) { set; } | 获取或设置用于将文本拆分为单词的分隔符数组。 |

### 另见

* class [CompareOptions](../compareoptions)
* namespace [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.Comparison.dll 生成 -->
