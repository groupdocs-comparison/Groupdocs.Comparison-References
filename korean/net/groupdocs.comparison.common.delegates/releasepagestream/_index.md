---
title: "ReleasePageStream"
second_title: "GroupDocs.Comparison .NET용 API 참조"
description: "PreviewOptions../groupdocs.comparison.options/previewoptions에서 사용되는 출력 페이지 미리보기 스트림을 해제하는 메서드를 정의하는 대리자."
type: docs
weight: 30
url: /ko/net/groupdocs.comparison.common.delegates/releasepagestream/
---
## ReleasePageStream delegate

[`PreviewOptions`](../../groupdocs.comparison.options/previewoptions)에서 사용되는 출력 페이지 미리보기 스트림을 해제하는 메서드를 정의하는 대리자.

```csharp
public delegate void ReleasePageStream(int pageNumber, Stream pageStream);
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| pageNumber | Int32 | 미리보기된 페이지의 수. |
| pageStream | Stream | 해제할 페이지 스트림. |

### 또 보기

* namespace [GroupDocs.Comparison.Common.Delegates](../../groupdocs.comparison.common.delegates)
* assembly [GroupDocs.Comparison](../../)

<!-- 수정 금지: xmldocmd에 의해 GroupDocs.Comparison.dll용으로 생성됨 -->
