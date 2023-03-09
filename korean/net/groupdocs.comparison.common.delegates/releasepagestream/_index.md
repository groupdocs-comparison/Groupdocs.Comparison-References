---
title: ReleasePageStream
second_title: .NET API 참조용 GroupDocs.Comparison
description: 에서 사용하는 출력 페이지 미리 보기 스트림을 해제하는 방법을 정의하는 대리자PreviewOptions../groupdocs.comparison.options/previewoptions .
type: docs
weight: 30
url: /ko/net/groupdocs.comparison.common.delegates/releasepagestream/
---
## ReleasePageStream delegate

에서 사용하는 출력 페이지 미리 보기 스트림을 해제하는 방법을 정의하는 대리자[`PreviewOptions`](../../groupdocs.comparison.options/previewoptions) .

```csharp
public delegate void ReleasePageStream(int pageNumber, Stream pageStream);
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| pageNumber | Int32 | 미리 본 페이지 수입니다. |
| pageStream | Stream | 해제할 페이지 스트림입니다. |

### 또한보십시오

* 네임스페이스 [GroupDocs.Comparison.Common.Delegates](../../groupdocs.comparison.common.delegates)
* 집회 [GroupDocs.Comparison](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Comparison.dll -->