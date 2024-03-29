---
title: CompareOptions
second_title: .NET API 참조용 GroupDocs.Comparison
description: 다른 비교 옵션을 설정할 수 있습니다.
type: docs
weight: 210
url: /ko/net/groupdocs.comparison.options/compareoptions/
---
## CompareOptions class

다른 비교 옵션을 설정할 수 있습니다.

```csharp
public class CompareOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [CompareOptions](compareoptions)() | 의 새 인스턴스를 초기화합니다.[`CompareOptions`](../compareoptions) 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [CalculateCoordinates](../../groupdocs.comparison.options/compareoptions/calculatecoordinates) { get; set; } | 변경된 구성 요소에 대한 좌표 계산 여부를 나타냅니다. |
| [ChangedItemStyle](../../groupdocs.comparison.options/compareoptions/changeditemstyle) { get; set; } | 변경된 구성 요소의 스타일을 설명합니다. |
| [CompareBookmarks](../../groupdocs.comparison.options/compareoptions/comparebookmarks) { get; set; } | Word 형식의 책갈피 비교를 켜도록 제어합니다. |
| [CompareDocumentProperty](../../groupdocs.comparison.options/compareoptions/comparedocumentproperty) { get; set; } | Word 형식의 빌드 속성과 사용자 정의 속성 비교를 켜도록 제어합니다. |
| [CompareVariableProperty](../../groupdocs.comparison.options/compareoptions/comparevariableproperty) { get; set; } | Word 형식의 변수 속성 비교를 켜도록 제어합니다. |
| [DeletedItemStyle](../../groupdocs.comparison.options/compareoptions/deleteditemstyle) { get; set; } | 삭제된 구성 요소의 스타일을 설명합니다. |
| [DetalisationLevel](../../groupdocs.comparison.options/compareoptions/detalisationlevel) { get; set; } | 비교 세부 수준을 가져오거나 설정합니다. |
| [DetectStyleChanges](../../groupdocs.comparison.options/compareoptions/detectstylechanges) { get; set; } | 스타일 변경 감지 여부를 나타냅니다. |
| [DiagramMasterSetting](../../groupdocs.comparison.options/compareoptions/diagrammastersetting) { get; set; } | 마스터의 경로 값을 가져오거나 설정하거나 마스터의 경로 없이 비교를 사용합니다. 이 옵션은 Diagram. 에만 해당됩니다. |
| [ExtendedSummaryPage](../../groupdocs.comparison.options/compareoptions/extendedsummarypage) { get; set; } | 확장 파일 비교 정보를 요약 페이지에 추가할지 여부를 나타냅니다. |
| [GenerateSummaryPage](../../groupdocs.comparison.options/compareoptions/generatesummarypage) { get; set; } | 검색된 변경 통계가 있는 요약 페이지를 결과 문서에 추가할지 여부를 나타냅니다. |
| [HeaderFootersComparison](../../groupdocs.comparison.options/compareoptions/headerfooterscomparison) { get; set; } | 머리글/바닥글 내용 비교를 켜도록 제어합니다. |
| [InsertedItemStyle](../../groupdocs.comparison.options/compareoptions/inserteditemstyle) { get; set; } | 삽입된 구성 요소의 스타일을 설명합니다. |
| [LeaveGaps](../../groupdocs.comparison.options/compareoptions/leavegaps) { get; set; } | 최종 문서에서 삽입/삭제된 구성 요소 대신 빈 줄을 표시할지 여부를 나타냅니다(ShowInsertedContent 또는 ShowDeletedContent 속성과 함께 사용). |
| [MarkChangedContent](../../groupdocs.comparison.options/compareoptions/markchangedcontent) { get; set; } | 워드 프로세싱의 모양과 이미지 문서의 사각형에 프레임을 사용할지 여부를 나타냅니다. |
| [MarkNestedContent](../../groupdocs.comparison.options/compareoptions/marknestedcontent) { get; set; } | 삭제 또는 삽입된 요소의 자식을 삭제 또는 삽입으로 표시할지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [OriginalSize](../../groupdocs.comparison.options/compareoptions/originalsize) { get; set; } | 비교 문서의 원래 크기를 가져오거나 설정합니다. |
| [PaperSize](../../groupdocs.comparison.options/compareoptions/papersize) { get; set; } | 결과 문서 용지 크기를 가져오거나 설정합니다. |
| [PasswordSaveOption](../../groupdocs.comparison.options/compareoptions/passwordsaveoption) { get; set; } | 암호 저장 옵션을 가져오거나 설정합니다. |
| [SensitivityOfComparison](../../groupdocs.comparison.options/compareoptions/sensitivityofcomparison) { get; set; } | 비교 감도를 가져오거나 설정합니다. |
| [ShowDeletedContent](../../groupdocs.comparison.options/compareoptions/showdeletedcontent) { get; set; } | 삭제된 구성 요소를 결과 문서에 표시할지 여부를 나타냅니다. |
| [ShowInsertedContent](../../groupdocs.comparison.options/compareoptions/showinsertedcontent) { get; set; } | 결과 문서에 삽입된 구성 요소를 표시할지 여부를 나타냅니다. |
| [ShowOnlySummaryPage](../../groupdocs.comparison.options/compareoptions/showonlysummarypage) { get; set; } | 결과 문서에서 감지된 변경 사항의 통계가 있는 페이지만 결과 문서에 남길지 여부를 나타냅니다. |
| [ShowRevisions](../../groupdocs.comparison.options/compareoptions/showrevisions) { get; set; } | 결과 문서에 다른 개정판을 표시할지 여부를 나타냅니다. |
| [WordsSeparatorChars](../../groupdocs.comparison.options/compareoptions/wordsseparatorchars) { set; } | 텍스트를 단어로 분할하는 구분 기호 배열을 가져오거나 설정합니다. |
| [WordTrackChanges](../../groupdocs.comparison.options/compareoptions/wordtrackchanges) { get; set; } | Words Track Revisions. 의 비교를 켜도록 제어합니다. |

### 또한보십시오

* 네임스페이스 [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* 집회 [GroupDocs.Comparison](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Comparison.dll -->
