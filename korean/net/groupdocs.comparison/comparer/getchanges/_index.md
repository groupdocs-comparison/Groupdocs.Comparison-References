---
title: "GetChanges"
second_title: "GroupDocs.Comparison .NET용 API 참조"
description: "소스 파일과 대상 파일 사이의 변경 목록을 가져옵니다."
type: docs
weight: 120
url: /ko/net/groupdocs.comparison/comparer/getchanges/
---
## GetChanges() {#getchanges}

소스와 대상 파일 간의 변경 목록을 가져옵니다.

```csharp
public ChangeInfo[] GetChanges()
```

### 비고

**Learn more**

* More about how to obtain collection of detected differences between compared documents in C#: [How to get list of changes between documents in C#](https://docs.groupdocs.com/display/comparisonnet/Get+list+of+changes)
* More about how to get changes coordinates at pages image preview when comparing documents using GroupDocs.Comparison for .NET: [How to get changes coordinates programmatically](https://docs.groupdocs.com/display/comparisonnet/Get+changes+coordinates)

### 또 보기

* class [ChangeInfo](../../../groupdocs.comparison.result/changeinfo)
* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

---

## GetChanges(GetChangeOptions) {#getchanges_2}

소스와 대상 파일 간의 변경 목록을 가져옵니다.

```csharp
public ChangeInfo[] GetChanges(GetChangeOptions getChangeOptions)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| getChangeOptions | GetChangeOptions | 변경 옵션을 가져옵니다 |

### 비고

**Learn more**

* More about how to obtain collection of detected differences between compared documents in C#: [How to get list of changes between documents in C#](https://docs.groupdocs.com/display/comparisonnet/Get+list+of+changes)
* More about how to get changes coordinates at pages image preview when comparing documents using GroupDocs.Comparison for .NET: [How to get changes coordinates programmatically](https://docs.groupdocs.com/display/comparisonnet/Get+changes+coordinates)

### 또 보기

* class [ChangeInfo](../../../groupdocs.comparison.result/changeinfo)
* class [GetChangeOptions](../../../groupdocs.comparison.options/getchangeoptions)
* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

---

## GetChanges(ChangeType) {#getchanges_1}

소스와 대상 파일 간의 변경 목록을 가져옵니다.

```csharp
public ChangeInfo[] GetChanges(ChangeType filter)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 필터 | ChangeType | 변경 유형을 지정합니다 |

### 또 보기

* class [ChangeInfo](../../../groupdocs.comparison.result/changeinfo)
* enum [ChangeType](../../../groupdocs.comparison.options/changetype)
* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

<!-- 수정 금지: xmldocmd에 의해 GroupDocs.Comparison.dll용으로 생성됨 -->
