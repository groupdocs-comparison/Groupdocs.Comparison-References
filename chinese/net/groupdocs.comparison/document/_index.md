---
title: "文档"
second_title: "GroupDocs.Comparison 适用于 .NET 的 API 参考"
description: "表示已比较的文档。"
type: docs
weight: 120
url: /zh/net/groupdocs.comparison/document/
---
## Document class

表示已比较的文档。

```csharp
public class Document
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Document](document#constructor)(Stream) | 初始化 [`Document`](../document) 类的新实例。 |
| [Document](document#constructor_2)(string) | 初始化 [`Document`](../document) 类的新实例。 |
| [Document](document#constructor_1)(Stream, string) | 初始化 [`Document`](../document) 类的新实例。 |
| [Document](document#constructor_3)(string, string) | 初始化 [`Document`](../document) 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Changes](../../groupdocs.comparison/document/changes) { get; set; } | 更改列表。包含关于更改类型、位置、内容等的详细描述。 |
| [FileType](../../groupdocs.comparison/document/filetype) { get; } | 文档文件类型。 |
| [Name](../../groupdocs.comparison/document/name) { get; set; } | 文档名称。 |
| [Password](../../groupdocs.comparison/document/password) { get; } | 文档密码。 |
| [Stream](../../groupdocs.comparison/document/stream) { get; } | 文档流。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GeneratePreview](../../groupdocs.comparison/document/generatepreview)(PreviewOptions) | 生成文档页面预览。 |
| [GetDocumentInfo](../../groupdocs.comparison/document/getdocumentinfo)() | 获取关于文档的信息 - 文档类型、页数、页面尺寸等。 |

### 另见

* namespace [GroupDocs.Comparison](../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.Comparison.dll 生成 -->
