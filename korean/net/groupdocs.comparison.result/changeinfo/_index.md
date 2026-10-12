---
title: "ChangeInfo"
second_title: "GroupDocs.Comparison .NET용 API 참조"
description: "변경에 대한 정보를 나타냅니다."
type: docs
weight: 460
url: /ko/net/groupdocs.comparison.result/changeinfo/
---
## ChangeInfo class

변경에 대한 정보를 나타냅니다.

```csharp
public class ChangeInfo
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [ChangeInfo](changeinfo)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Authors](../../groupdocs.comparison.result/changeinfo/authors) { get; set; } | 작성자 목록. |
| [Box](../../groupdocs.comparison.result/changeinfo/box) { get; set; } | 변경된 요소의 좌표. |
| [Column](../../groupdocs.comparison.result/changeinfo/column) { get; set; } | 변경된 셀의 0부터 시작하는 열 인덱스. Cells comparer (XLSX, CSV, ODS 등)에서 채워지며, 그렇지 않으면 null입니다. |
| [ColumnHeader](../../groupdocs.comparison.result/changeinfo/columnheader) { get; set; } | 해당 열에 대해 워크시트 첫 번째 행에서 가져온 열 머리글 텍스트. 첫 번째 행에 머리글 값이 있는 경우 Cells comparer에서 채워지며, 그렇지 않으면 null입니다. |
| [ComparisonAction](../../groupdocs.comparison.result/changeinfo/comparisonaction) { get; set; } | 동작(수락 또는 거부). 이 필드는 비교에 이 변경을 어떻게 처리할지 알려줍니다. |
| [ComponentType](../../groupdocs.comparison.result/changeinfo/componenttype) { get; set; } | 변경된 구성 요소의 유형. |
| [Id](../../groupdocs.comparison.result/changeinfo/id) { get; set; } | 변경의 ID. |
| [PageInfo](../../groupdocs.comparison.result/changeinfo/pageinfo) { get; set; } | 현재 변경이 배치된 페이지. |
| [Row](../../groupdocs.comparison.result/changeinfo/row) { get; set; } | 변경된 셀의 0부터 시작하는 행 인덱스. Cells comparer (XLSX, CSV, ODS 등)에서 채워지며, 그렇지 않으면 null입니다. |
| [SourceText](../../groupdocs.comparison.result/changeinfo/sourcetext) { get; set; } | 원본 문서의 변경된 텍스트. |
| [StyleChanges](../../groupdocs.comparison.result/changeinfo/stylechanges) { get; set; } | 스타일 변경 배열. |
| [TargetText](../../groupdocs.comparison.result/changeinfo/targettext) { get; set; } | 대상 문서의 변경된 텍스트. |
| [Text](../../groupdocs.comparison.result/changeinfo/text) { get; set; } | 변경의 텍스트 값. |
| [Type](../../groupdocs.comparison.result/changeinfo/type) { get; } | 변경 유형. |

### 또 보기

* namespace [GroupDocs.Comparison.Result](../../groupdocs.comparison.result)
* assembly [GroupDocs.Comparison](../../)

<!-- 수정 금지: xmldocmd에 의해 GroupDocs.Comparison.dll용으로 생성됨 -->
