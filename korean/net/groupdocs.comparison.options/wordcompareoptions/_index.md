---
title: "WordCompareOptions"
second_title: "GroupDocs.Comparison .NET용 API 참조"
description: "Word 문서 전용 비교 옵션. CompareOptions./compareoptions에서 공통 옵션을 상속합니다."
type: docs
weight: 440
url: /ko/net/groupdocs.comparison.options/wordcompareoptions/
---
## WordCompareOptions class

Word 문서 전용 비교 옵션. [`CompareOptions`](../compareoptions)에서 공통 옵션을 상속합니다.

```csharp
public class WordCompareOptions : CompareOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [WordCompareOptions](wordcompareoptions)() | [`WordCompareOptions`](../wordcompareoptions) 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [CalculateCoordinates](../../groupdocs.comparison.options/compareoptions/calculatecoordinates) { get; set; } | 변경된 구성 요소에 대한 좌표를 계산할지 여부를 나타냅니다. |
| [CalculateCoordinatesMode](../../groupdocs.comparison.options/compareoptions/calculatecoordinatesmode) { get; set; } | 변경된 구성 요소 모드에 대한 좌표 계산을 지정합니다. |
| [ChangedItemStyle](../../groupdocs.comparison.options/compareoptions/changeditemstyle) { get; set; } | 변경된 구성 요소의 스타일을 설명합니다. |
| [CompareBookmarks](../../groupdocs.comparison.options/wordcompareoptions/comparebookmarks) { get; set; } | 소스 및 대상 문서의 북마크를 비교하고 차이를 결과에 포함할지 여부를 가져오거나 설정합니다. |
| [CompareDocumentProperty](../../groupdocs.comparison.options/wordcompareoptions/comparedocumentproperty) { get; set; } | 내장 및 사용자 정의 문서 속성을 비교하고 차이를 결과에 포함할지 여부를 가져오거나 설정합니다(예: 속성 요약 페이지). |
| [CompareVariableProperty](../../groupdocs.comparison.options/wordcompareoptions/comparevariableproperty) { get; set; } | 문서 변수 속성(예: DOCVARIABLE 필드)을 비교하고 차이를 결과에 포함할지 여부를 가져오거나 설정합니다. |
| [DeletedItemStyle](../../groupdocs.comparison.options/compareoptions/deleteditemstyle) { get; set; } | 삭제된 구성 요소의 스타일을 설명합니다. |
| [DetalisationLevel](../../groupdocs.comparison.options/compareoptions/detalisationlevel) { get; set; } | 비교 상세 수준을 가져오거나 설정합니다. |
| [DetectStyleChanges](../../groupdocs.comparison.options/compareoptions/detectstylechanges) { get; set; } | 스타일 변경을 감지할지 여부를 나타냅니다. |
| [DiagramMasterSetting](../../groupdocs.comparison.options/compareoptions/diagrammastersetting) { get; set; } | 마스터의 경로 값을 가져오거나 설정하거나, 마스터 경로 없이 비교를 사용합니다. 이 옵션은 Diagram에만 적용됩니다. |
| [DirectoryCompare](../../groupdocs.comparison.options/compareoptions/directorycompare) { get; set; } | 폴더 비교를 활성화하는 제어입니다. |
| [DisplayMode](../../groupdocs.comparison.options/wordcompareoptions/displaymode) { get; set; } | 비교 결과 표시 방식을 설정합니다: 변경 추적 모드의 Word 수정본(Revisions)으로 표시하거나, 문서에 직접 강조된 변경 사항(Highlight)으로 표시합니다. |
| [ExtendedSummaryPage](../../groupdocs.comparison.options/compareoptions/extendedsummarypage) { get; set; } | 요약 페이지에 확장 파일 비교 정보를 추가할지 여부를 나타냅니다. |
| [FolderComparisonExtension](../../groupdocs.comparison.options/compareoptions/foldercomparisonextension) { get; set; } | 결과 폴더 비교 파일의 형식을 가져오거나 설정합니다. |
| [GenerateSummaryPage](../../groupdocs.comparison.options/compareoptions/generatesummarypage) { get; set; } | 감지된 변경 통계가 포함된 요약 페이지를 결과 문서에 추가할지 여부를 나타냅니다. |
| [HeaderFootersComparison](../../groupdocs.comparison.options/compareoptions/headerfooterscomparison) { get; set; } | 머리글/바닥글 내용 비교를 활성화하는 제어입니다. |
| [IgnoreChangeSettings](../../groupdocs.comparison.options/compareoptions/ignorechangesettings) { get; set; } | 유사성을 기반으로 변경을 무시하는 설정을 가져오거나 설정합니다. |
| [InsertedItemStyle](../../groupdocs.comparison.options/compareoptions/inserteditemstyle) { get; set; } | 삽입된 구성 요소의 스타일을 설명합니다. |
| [LeaveGaps](../../groupdocs.comparison.options/wordcompareoptions/leavegaps) { get; set; } | 삽입되거나 삭제된 내용 대신 빈 줄을 남겨 레이아웃과 줄 수를 유지할지 여부를 가져오거나 설정합니다; [`ShowInsertedContent`](../compareoptions/showinsertedcontent) 및 [`ShowDeletedContent`](../compareoptions/showdeletedcontent)와 함께 사용됩니다. |
| [MarkChangedContent](../../groupdocs.comparison.options/compareoptions/markchangedcontent) { get; set; } | 워드 프로세싱에서 도형에 프레임을 사용하고 이미지 문서에서 사각형에 프레임을 사용할지 여부를 나타냅니다. |
| [MarkLineBreaks](../../groupdocs.comparison.options/wordcompareoptions/marklinebreaks) { get; set; } | 문서 간에 차이가 있는 단락(줄) 구분이 결과에 시각적으로 표시될지 여부를 가져오거나 설정합니다. |
| [MarkNestedContent](../../groupdocs.comparison.options/compareoptions/marknestedcontent) { get; set; } | 삭제되거나 삽입된 요소의 자식들을 삭제되었거나 삽입된 것으로 표시할지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [OriginalSize](../../groupdocs.comparison.options/compareoptions/originalsize) { get; set; } | 비교된 문서의 원래 크기를 가져오거나 설정합니다. |
| [PaperSize](../../groupdocs.comparison.options/compareoptions/papersize) { get; set; } | 결과 문서의 용지 크기를 가져오거나 설정합니다. |
| [PasswordSaveOption](../../groupdocs.comparison.options/compareoptions/passwordsaveoption) { get; set; } | 비밀번호 저장 옵션을 가져오거나 설정합니다. |
| [RevisionAuthorName](../../groupdocs.comparison.options/wordcompareoptions/revisionauthorname) { get; set; } | !:WordTrackChanges가 활성화될 때 수정에 사용되는 작성자 이름을 가져오거나 설정합니다. 설정하면 이 이름이 결과 문서의 수정 표시(markup)에 적용됩니다. |
| [SensitivityOfComparison](../../groupdocs.comparison.options/compareoptions/sensitivityofcomparison) { get; set; } | 비교 민감도를 가져오거나 설정합니다. |
| [SensitivityOfComparisonForTables](../../groupdocs.comparison.options/compareoptions/sensitivityofcomparisonfortables) { get; set; } | 표에 대한 비교 민감도를 가져오거나 설정합니다. |
| [ShowDeletedContent](../../groupdocs.comparison.options/compareoptions/showdeletedcontent) { get; set; } | 결과 문서에 삭제된 구성 요소를 표시할지 여부를 나타냅니다. |
| [ShowInsertedContent](../../groupdocs.comparison.options/compareoptions/showinsertedcontent) { get; set; } | 결과 문서에 삽입된 구성 요소를 표시할지 여부를 나타냅니다. |
| [ShowOnlyChanged](../../groupdocs.comparison.options/compareoptions/showonlychanged) { get; set; } | 변경된 항목만 표시하도록 제어합니다. |
| [ShowOnlySummaryPage](../../groupdocs.comparison.options/compareoptions/showonlysummarypage) { get; set; } | 결과 문서에 감지된 변경 통계가 포함된 페이지만 남길지 여부를 나타냅니다. |
| [ShowRevisions](../../groupdocs.comparison.options/wordcompareoptions/showrevisions) { get; set; } | 결과 문서가 수정 표시를 표시하도록 유지할지 여부를 가져오거나 설정합니다. false인 경우 모든 수정이 수락되어 결과가 최종 텍스트로 표시됩니다. 이 설정은 [`DisplayMode`](./displaymode)가 Highlight로 설정된 경우에만 의미가 있습니다. 기본값은 true입니다. |
| [UserMasterPath](../../groupdocs.comparison.options/compareoptions/usermasterpath) { get; set; } | 다이어그램용 사용자 마스터 템플릿 경로. |
| [WordsSeparatorChars](../../groupdocs.comparison.options/compareoptions/wordsseparatorchars) { set; } | 텍스트를 단어로 분할하기 위한 구분자 배열을 가져오거나 설정합니다. |

### 또 보기

* class [CompareOptions](../compareoptions)
* namespace [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../)

<!-- 수정 금지: xmldocmd에 의해 GroupDocs.Comparison.dll용으로 생성됨 -->
