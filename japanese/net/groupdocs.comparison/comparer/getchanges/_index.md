---
title: "GetChanges"
second_title: "GroupDocs.Comparison for .NET API リファレンス"
description: "ソースファイルとターゲットファイル間の変更リストを取得します。"
type: docs
weight: 120
url: /ja/net/groupdocs.comparison/comparer/getchanges/
---
## GetChanges() {#getchanges}

ソースとターゲットファイル間の変更一覧を取得します。

```csharp
public ChangeInfo[] GetChanges()
```

### 備考

**Learn more**

* More about how to obtain collection of detected differences between compared documents in C#: [How to get list of changes between documents in C#](https://docs.groupdocs.com/display/comparisonnet/Get+list+of+changes)
* More about how to get changes coordinates at pages image preview when comparing documents using GroupDocs.Comparison for .NET: [How to get changes coordinates programmatically](https://docs.groupdocs.com/display/comparisonnet/Get+changes+coordinates)

### 関連項目

* class [ChangeInfo](../../../groupdocs.comparison.result/changeinfo)
* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

---

## GetChanges(GetChangeOptions) {#getchanges_2}

ソースとターゲットファイル間の変更一覧を取得します。

```csharp
public ChangeInfo[] GetChanges(GetChangeOptions getChangeOptions)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| getChangeOptions | GetChangeOptions | 変更オプションを取得 |

### 備考

**Learn more**

* More about how to obtain collection of detected differences between compared documents in C#: [How to get list of changes between documents in C#](https://docs.groupdocs.com/display/comparisonnet/Get+list+of+changes)
* More about how to get changes coordinates at pages image preview when comparing documents using GroupDocs.Comparison for .NET: [How to get changes coordinates programmatically](https://docs.groupdocs.com/display/comparisonnet/Get+changes+coordinates)

### 関連項目

* class [ChangeInfo](../../../groupdocs.comparison.result/changeinfo)
* class [GetChangeOptions](../../../groupdocs.comparison.options/getchangeoptions)
* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

---

## GetChanges(ChangeType) {#getchanges_1}

ソースとターゲットファイル間の変更一覧を取得します。

```csharp
public ChangeInfo[] GetChanges(ChangeType filter)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| フィルタ | ChangeType | 変更タイプを指定 |

### 関連項目

* class [ChangeInfo](../../../groupdocs.comparison.result/changeinfo)
* enum [ChangeType](../../../groupdocs.comparison.options/changetype)
* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Comparison.dll 用に生成されました -->
