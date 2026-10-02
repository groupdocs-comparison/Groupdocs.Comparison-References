---
title: "RevisionHandler"
second_title: "GroupDocs.Comparison .NET용 API 참조"
description: "수정 처리를 제어하는 주요 클래스를 나타냅니다."
type: docs
weight: 540
url: /ko/net/groupdocs.comparison.words.revision/revisionhandler/
---
## RevisionHandler class

수정 처리를 제어하는 주요 클래스를 나타냅니다.

```csharp
public sealed class RevisionHandler : IDisposable
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [RevisionHandler](revisionhandler#constructor)(Stream) | 리비전이 포함된 파일 스트림으로 [`RevisionHandler`](../revisionhandler) 클래스의 새 인스턴스를 초기화합니다. |
| [RevisionHandler](revisionhandler#constructor_2)(string) | 리비전이 포함된 파일 경로를 사용하여 [`RevisionHandler`](../revisionhandler) 클래스의 새 인스턴스를 초기화합니다. |
| [RevisionHandler](revisionhandler#constructor_1)(Stream, bool) | 리비전이 포함된 파일 스트림과 명시적인 스트림 소유권 제어를 사용하여 [`RevisionHandler`](../revisionhandler) 클래스의 새 인스턴스를 초기화합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [ApplyRevisionChanges](../../groupdocs.comparison.words.revision/revisionhandler/applyrevisionchanges#applyrevisionchanges)(ApplyRevisionOptions) | 리비전의 변경 사항을 처리하고 해당 리비전이 추출된 동일한 파일에 적용합니다. |
| [ApplyRevisionChanges](../../groupdocs.comparison.words.revision/revisionhandler/applyrevisionchanges#applyrevisionchanges_1)(Stream, ApplyRevisionOptions) | 리비전의 변경 사항을 처리하고 결과를 문서 스트림에 씁니다. |
| [ApplyRevisionChanges](../../groupdocs.comparison.words.revision/revisionhandler/applyrevisionchanges#applyrevisionchanges_2)(string, ApplyRevisionOptions) | 리비전의 변경 사항을 처리하고 결과를 지정된 경로의 파일에 씁니다. |
| [Dispose](../../groupdocs.comparison.words.revision/revisionhandler/dispose)() | 리소스를 해제합니다. |
| [GetRevisions](../../groupdocs.comparison.words.revision/revisionhandler/getrevisions)() | 모든 리비전의 목록을 가져옵니다. |

### 또 보기

* namespace [GroupDocs.Comparison.Words.Revision](../../groupdocs.comparison.words.revision)
* assembly [GroupDocs.Comparison](../../)

<!-- 수정 금지: xmldocmd에 의해 GroupDocs.Comparison.dll용으로 생성됨 -->
