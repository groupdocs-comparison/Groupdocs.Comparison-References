---
title: "DetalisationLevel"
second_title: "GroupDocs.Comparison .NET용 API 참조"
description: "비교 세부 수준을 지정합니다."
type: docs
weight: 230
url: /ko/net/groupdocs.comparison.options/detalisationlevel/
---
## DetalisationLevel enumeration

비교 세부 수준을 지정합니다.

```csharp
public enum DetalisationLevel
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Low | `0` | 낮은 수준. 비교 품질을 희생하고 최고의 속도 비교를 제공합니다. 비교는 단어 단위로 수행됩니다. |
| Middle | `1` | 중간 수준. 비교 속도와 품질 사이의 합리적인 타협을 제공합니다. 비교는 문자 단위로 수행되지만 대소문자와 공백 수는 무시합니다. |
| High | `2` | 높은 수준. 최고의 비교 품질을 제공하지만 속도는 가장 낮습니다. 비교는 대소문자와 공백 수를 고려하여 문자 단위로 수행됩니다. |

### 또 보기

* namespace [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../)

<!-- 수정 금지: xmldocmd에 의해 GroupDocs.Comparison.dll용으로 생성됨 -->
