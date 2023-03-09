---
title: SensitivityOfComparison
second_title: .NET API 참조용 GroupDocs.Comparison
description: 비교 감도를 가져오거나 설정합니다.
type: docs
weight: 210
url: /ko/net/groupdocs.comparison.options/compareoptions/sensitivityofcomparison/
---
## CompareOptions.SensitivityOfComparison property

비교 감도를 가져오거나 설정합니다.

```csharp
public int SensitivityOfComparison { get; set; }
```

### 자산 가치

이러한 개체의 모든 요소와 관련하여 두 비교 개체의 삭제 및 삽입된 요소의 백분율입니다. 이 백분율을 초과하면 개체는 비교되지 않지만 완전히 삽입 및 삭제된 것으로 간주됩니다. 최소값 - 0% = &gt; 두 비교 객체의 공통 서브시퀀스 길이에 대해서는 비교하지 않습니다. 기본값 - 75% =&gt; 비교 발생 두 비교 객체의 모든 요소에 대한 삭제 및 삽입 요소의 비율 75보다 크지 않음. 최대값 - 100% =&gt; 비교 대상 두 개체의 공통 하위 시퀀스 길이에 관계없이 비교가 발생합니다.

### 또한보십시오

* class [CompareOptions](../../compareoptions)
* 네임스페이스 [GroupDocs.Comparison.Options](../../compareoptions)
* 집회 [GroupDocs.Comparison](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Comparison.dll -->