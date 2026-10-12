---
title: "ApplyRevisionChanges"
second_title: "GroupDocs.Comparison 适用于 .NET 的 API 参考"
description: "处理修订中的更改并将其应用于获取修订的同一文件。"
type: docs
weight: 20
url: /zh/net/groupdocs.comparison.words.revision/revisionhandler/applyrevisionchanges/
---
## ApplyRevisionChanges(ApplyRevisionOptions) {#applyrevisionchanges}

处理修订中的更改并将其应用于获取修订的同一文件。

```csharp
public void ApplyRevisionChanges(ApplyRevisionOptions changes)
```

| Parameter | Type | 描述 |
| --- | --- | --- |
| 更改 | ApplyRevisionOptions | 已更改修订的列表 |

### 另见

* class [ApplyRevisionOptions](../../applyrevisionoptions)
* class [RevisionHandler](../../revisionhandler)
* namespace [GroupDocs.Comparison.Words.Revision](../../../groupdocs.comparison.words.revision)
* assembly [GroupDocs.Comparison](../../../)

---

## ApplyRevisionChanges(string, ApplyRevisionOptions) {#applyrevisionchanges_2}

处理修订中的更改，结果写入指定路径的文件。

```csharp
public void ApplyRevisionChanges(string filePath, ApplyRevisionOptions changes)
```

| Parameter | Type | 描述 |
| --- | --- | --- |
| filePath | String | 结果文件路径 |
| 更改 | ApplyRevisionOptions | 已更改修订的列表 |

### 另见

* class [ApplyRevisionOptions](../../applyrevisionoptions)
* class [RevisionHandler](../../revisionhandler)
* namespace [GroupDocs.Comparison.Words.Revision](../../../groupdocs.comparison.words.revision)
* assembly [GroupDocs.Comparison](../../../)

---

## ApplyRevisionChanges(Stream, ApplyRevisionOptions) {#applyrevisionchanges_1}

处理修订中的更改，结果写入文档流。

```csharp
public void ApplyRevisionChanges(Stream document, ApplyRevisionOptions changes)
```

| Parameter | Type | 描述 |
| --- | --- | --- |
| 文档 | Stream | 结果文档 |
| 更改 | ApplyRevisionOptions | 已更改修订的列表 |

### 另见

* class [ApplyRevisionOptions](../../applyrevisionoptions)
* class [RevisionHandler](../../revisionhandler)
* namespace [GroupDocs.Comparison.Words.Revision](../../../groupdocs.comparison.words.revision)
* assembly [GroupDocs.Comparison](../../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.Comparison.dll 生成 -->
