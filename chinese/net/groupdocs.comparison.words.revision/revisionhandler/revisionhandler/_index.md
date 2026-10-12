---
title: "RevisionHandler"
second_title: "GroupDocs.Comparison 适用于 .NET 的 API 参考"
description: "使用修订文件的路径初始化 RevisionHandlergroupdocs.comparison.words.revision/revisionhandler 类的新实例。"
type: docs
weight: 10
url: /zh/net/groupdocs.comparison.words.revision/revisionhandler/revisionhandler/
---
## RevisionHandler(string) {#constructor_2}

使用修订文件的路径初始化 [`RevisionHandler`](../../revisionhandler) 类的新实例。

```csharp
public RevisionHandler(string filePath)
```

| Parameter | Type | 描述 |
| --- | --- | --- |
| filePath | String | 文件路径 |

### 另见

* class [RevisionHandler](../../revisionhandler)
* namespace [GroupDocs.Comparison.Words.Revision](../../../groupdocs.comparison.words.revision)
* assembly [GroupDocs.Comparison](../../../)

---

## RevisionHandler(Stream) {#constructor}

使用包含修订的文件流初始化 [`RevisionHandler`](../../revisionhandler) 类的新实例。

```csharp
public RevisionHandler(Stream file)
```

| Parameter | Type | 描述 |
| --- | --- | --- |
| 文件 | Stream | 源文档流 |

### 另见

* class [RevisionHandler](../../revisionhandler)
* namespace [GroupDocs.Comparison.Words.Revision](../../../groupdocs.comparison.words.revision)
* assembly [GroupDocs.Comparison](../../../)

---

## RevisionHandler(Stream, bool) {#constructor_1}

使用包含修订的文件流以及显式的流所有权控制初始化 [`RevisionHandler`](../../revisionhandler) 类的新实例。

```csharp
public RevisionHandler(Stream file, bool leaveOpen)
```

| Parameter | Type | 描述 |
| --- | --- | --- |
| 文件 | Stream | 源文档流 |
| leaveOpen | Boolean | 当为 true 时，调用方保留 *file* 的所有权并负责释放它。当为 false（默认）时，[`Dispose`](../dispose) 关闭流。 |

### 另见

* class [RevisionHandler](../../revisionhandler)
* namespace [GroupDocs.Comparison.Words.Revision](../../../groupdocs.comparison.words.revision)
* assembly [GroupDocs.Comparison](../../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.Comparison.dll 生成 -->
