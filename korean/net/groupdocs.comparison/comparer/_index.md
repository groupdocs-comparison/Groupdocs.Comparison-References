---
title: "비교기"
second_title: "GroupDocs.Comparison .NET용 API 참조"
description: "문서 비교 프로세스를 제어하는 주요 클래스를 나타냅니다."
type: docs
weight: 100
url: /ko/net/groupdocs.comparison/comparer/
---
## Comparer class

문서 비교 프로세스를 제어하는 주요 클래스를 나타냅니다.

```csharp
public sealed class Comparer : IDisposable
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Comparer](comparer#constructor)(Stream) | `[`Comparer`](../comparer)` 클래스의 새 인스턴스를 소스 문서 스트림과 함께 초기화합니다. |
| [Comparer](comparer#constructor_4)(string) | `[`Comparer`](../comparer)` 클래스의 새 인스턴스를 소스 파일 경로와 함께 초기화합니다. |
| [Comparer](comparer#constructor_1)(Stream, ComparerSettings) | `[`Comparer`](../comparer)` 클래스의 새 인스턴스를 소스 문서 스트림 및 [`ComparerSettings`](../comparersettings)와 함께 초기화합니다. |
| [Comparer](comparer#constructor_2)(Stream, LoadOptions) | `[`Comparer`](../comparer)`를 소스 문서 스트림 및 [`LoadOptions`](../../groupdocs.comparison.options/loadoptions)와 함께 초기화합니다. |
| [Comparer](comparer#constructor_6)(string, CompareOptions) | `[`Comparer`](../comparer)`를 소스 폴더 경로 및 [`CompareOptions`](../../groupdocs.comparison.options/compareoptions)와 함께 초기화합니다. |
| [Comparer](comparer#constructor_5)(string, ComparerSettings) | `[`Comparer`](../comparer)` 클래스의 새 인스턴스를 소스 파일 경로 및 [`ComparerSettings`](../comparersettings)와 함께 초기화합니다. |
| [Comparer](comparer#constructor_7)(string, LoadOptions) | 소스 파일 경로와 [`LoadOptions`](../../groupdocs.comparison.options/loadoptions)를 사용하여 [`Comparer`](../comparer)의 새 인스턴스를 초기화합니다. |
| [Comparer](comparer#constructor_3)(Stream, LoadOptions, ComparerSettings) | [`Comparer`](../comparer) 클래스의 새 인스턴스를 문서 스트림, [`LoadOptions`](../../groupdocs.comparison.options/loadoptions) 및 [`ComparerSettings`](../comparersettings)와 함께 초기화합니다. |
| [Comparer](comparer#constructor_8)(string, LoadOptions, ComparerSettings) | [`Comparer`](../comparer) 클래스의 새 인스턴스를 소스 파일 경로, [`LoadOptions`](../../groupdocs.comparison.options/loadoptions) 및 [`ComparerSettings`](../comparersettings)와 함께 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Result](../../groupdocs.comparison/comparer/result) { get; } | 결과 문서. |
| [Source](../../groupdocs.comparison/comparer/source) { get; } | 비교되는 소스 파일. |
| [SourceFolder](../../groupdocs.comparison/comparer/sourcefolder) { get; } | 비교되는 소스 폴더. |
| [TargetFolder](../../groupdocs.comparison/comparer/targetfolder) { get; set; } | 비교되는 대상 폴더. |
| [Targets](../../groupdocs.comparison/comparer/targets) { get; } | 소스 파일과 비교할 대상 파일 목록. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Add](../../groupdocs.comparison/comparer/add#add)(Stream) | 문서 스트림을 비교에 추가합니다. |
| [Add](../../groupdocs.comparison/comparer/add#add_2)(string) | 파일을 비교에 추가합니다. |
| [Add](../../groupdocs.comparison/comparer/add#add_1)(Stream, LoadOptions) | 지정된 로드 옵션과 함께 문서 스트림을 비교에 추가합니다. |
| [Add](../../groupdocs.comparison/comparer/add#add_3)(string, CompareOptions) | 폴더를 비교에 추가합니다. |
| [Add](../../groupdocs.comparison/comparer/add#add_4)(string, LoadOptions) | 지정된 로드 옵션과 함께 파일을 비교에 추가합니다. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges)(Stream, ApplyChangeOptions) | 변경 사항을 수락하거나 거부하고 결과 문서에 적용합니다. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_2)(string, ApplyChangeOptions) | 변경 사항을 수락하거나 거부하고 결과 문서에 적용합니다. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_1)(Stream, SaveOptions, ApplyChangeOptions) | 변경 사항을 수락하거나 거부하고 결과 문서에 적용합니다. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_3)(string, SaveOptions, ApplyChangeOptions) | 변경 사항을 수락하거나 거부하고 결과 문서에 적용합니다. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare)() | 기본 옵션으로 결과를 저장하지 않고 문서를 비교합니다. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_1)(CompareOptions) | 결과를 저장하지 않고 문서를 비교합니다. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_3)(Stream) | 문서를 비교하고 결과를 파일 스트림에 저장합니다. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_7)(string) | 문서를 비교하고 결과를 파일 경로에 저장합니다. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_2)(SaveOptions, CompareOptions) | 결과를 저장하지 않고 문서를 비교합니다. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_4)(Stream, CompareOptions) | 문서를 비교하고 결과를 파일 스트림에 저장합니다. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_5)(Stream, SaveOptions) | 문서를 비교하고 결과를 파일 스트림에 저장합니다. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_8)(string, CompareOptions) | 문서를 비교하고 결과를 파일 경로에 저장합니다. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_9)(string, SaveOptions) | 문서를 비교하고 결과를 파일 경로에 저장합니다. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_6)(Stream, SaveOptions, CompareOptions) | 문서를 비교하고 결과를 스트림에 저장합니다. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_10)(string, SaveOptions, CompareOptions) | 문서를 비교하고 결과를 파일 경로에 저장합니다. |
| [CompareDirectory](../../groupdocs.comparison/comparer/comparedirectory)(string, CompareOptions) | 디렉터리를 비교하고 결과를 파일 경로에 저장합니다. |
| [Dispose](../../groupdocs.comparison/comparer/dispose)() | 리소스를 해제합니다. |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges)() | 소스와 대상 파일 간의 변경 목록을 가져옵니다. |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges_1)(ChangeType) | 소스와 대상 파일 간의 변경 목록을 가져옵니다. |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges_2)(GetChangeOptions) | 소스와 대상 파일 간의 변경 목록을 가져옵니다. |
| [GetResultDocumentStream](../../groupdocs.comparison/comparer/getresultdocumentstream)() | 결과 문서의 스트림을 가져오며, 스트림이 존재하지 않으면 null을 반환합니다 |
| [GetResultString](../../groupdocs.comparison/comparer/getresultstring)() | 비교 후 결과 문자열을 가져옵니다 (텍스트 비교 전용). |

### 또 보기

* namespace [GroupDocs.Comparison](../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../)

<!-- 수정 금지: xmldocmd에 의해 GroupDocs.Comparison.dll용으로 생성됨 -->
