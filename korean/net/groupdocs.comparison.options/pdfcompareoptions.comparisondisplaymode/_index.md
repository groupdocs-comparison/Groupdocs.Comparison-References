---
title: "PdfCompareOptions.ComparisonDisplayMode"
second_title: "GroupDocs.Comparison .NET용 API 참조"
description: "Pdf 비교 결과 문서의 레이아웃 방식을 제어합니다."
type: docs
weight: 370
url: /ko/net/groupdocs.comparison.options/pdfcompareoptions.comparisondisplaymode/
---
## PdfCompareOptions.ComparisonDisplayMode enumeration

Pdf 비교 결과 문서의 레이아웃 방식을 제어합니다.

```csharp
public enum ComparisonDisplayMode
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Inline | `0` | 기본 모드. 삭제된 내용은 한 색으로, 삽입된 내용은 다른 색으로 강조 표시된 단일 병합 PDF 문서를 생성합니다. 소스와 대상 내용이 동일 페이지에 함께 존재하므로 문서가 크게 다를 경우 겹침이 발생할 수 있습니다. |
| SideBySide | `1` | 각 결과 페이지는 원본 페이지와 해당 대상 페이지를 나란히 보여줍니다. 삭제는 왼쪽(원본 쪽)에, 삽입은 오른쪽(대상 쪽)에 표시됩니다. 두 문서의 내용이 겹치지 않아, 문서가 크게 다를 때 이 모드에 적합합니다. |
| Interleaved | `2` | 문서를 교대로 페이지를 배치하여 생성합니다: 홀수 페이지는 원본 문서(삭제 표시)에서 가져오고 짝수 페이지는 대상 문서(삽입 표시)에서 가져옵니다. "Two Page View"가 활성화된 PDF 뷰어에서 결과를 열어 화면에 원본/대상 쌍을 나란히 볼 수 있습니다. SideBySide와 마찬가지로 이 모드는 내용 겹침을 방지하며, 크게 다른 문서에 가장 적합합니다. |

### 또 보기

* class [PdfCompareOptions](../pdfcompareoptions)
* namespace [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../)

<!-- 수정 금지: xmldocmd에 의해 GroupDocs.Comparison.dll용으로 생성됨 -->
