---
title: "LoadOptions"
second_title: "GroupDocs.Comparison 适用于 .NET 的 API 参考"
description: "允许在加载文档时指定其他选项。"
type: docs
weight: 300
url: /zh/net/groupdocs.comparison.options/loadoptions/
---
## LoadOptions class

允许在加载文档时指定其他选项。

```csharp
public class LoadOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [LoadOptions](loadoptions)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [FileType](../../groupdocs.comparison.options/loadoptions/filetype) { get; set; } | 手动设置比较的文件类型，以覆盖自动文件类型检测。 |
| [FontDirectories](../../groupdocs.comparison.options/loadoptions/fontdirectories) { get; set; } | 要加载的字体目录列表。 |
| [LoadText](../../groupdocs.comparison.options/loadoptions/loadtext) { get; set; } | 指示传入的字符串是比较文本，而不是文件路径（仅用于文本比较）。 |
| [Password](../../groupdocs.comparison.options/loadoptions/password) { get; set; } | 文档的密码。 |
| [SkipExternalResources](../../groupdocs.comparison.options/loadoptions/skipexternalresources) { get; set; } | 禁用加载所有外部资源（例如通过远程 URL 引用的图像），除非是 [`WhitelistedResources`](./whitelistedresources)。 |
| [WhitelistedResources](../../groupdocs.comparison.options/loadoptions/whitelistedresources) { get; set; } | 当 [`SkipExternalResources`](./skipexternalresources) 设置为 `true` 时，应加载的外部资源对应的 URL 片段列表。 |

### 另见

* namespace [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.Comparison.dll 生成 -->
