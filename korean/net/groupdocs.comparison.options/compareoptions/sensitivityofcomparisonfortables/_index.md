---
title: "SensitivityOfComparisonForTables"
second_title: "GroupDocs.Comparison .NET용 API 참조"
description: "표에 대한 비교 민감도를 가져오거나 설정합니다."
type: docs
weight: 220
url: /ko/net/groupdocs.comparison.options/compareoptions/sensitivityofcomparisonfortables/
---
## CompareOptions.SensitivityOfComparisonForTables property

표에 대한 비교 민감도를 가져오거나 설정합니다.

```csharp
public int? SensitivityOfComparisonForTables { get; set; }
```

### Property Value

값이 null인 경우 대신 SensitivityOfComparison이 사용됩니다. 두 비교 객체의 전체 요소에 대한 삭제 및 삽입된 요소 비율입니다. 이 비율이 초과하면 객체는 비교되지 않고 완전히 삽입 및 삭제된 것으로 간주됩니다. 최소값 - 0% => 두 비교 객체의 공통 부분 수열 길이에 관계없이 비교가 수행되지 않습니다. 기본값 - 75% => 두 비교 객체의 전체 요소에 대한 삭제 및 삽입된 요소 비율이 75% 이하인 경우에만 비교가 수행됩니다. 최대값 - 100% => 두 비교 객체의 공통 부분 수열 길이에 관계없이 비교가 수행됩니다.

### 또 보기

* class [CompareOptions](../../compareoptions)
* namespace [GroupDocs.Comparison.Options](../../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../../)

<!-- 수정 금지: xmldocmd에 의해 GroupDocs.Comparison.dll용으로 생성됨 -->
