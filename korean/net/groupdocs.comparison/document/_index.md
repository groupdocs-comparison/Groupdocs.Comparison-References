---
title: "문서"
second_title: "GroupDocs.Comparison .NET용 API 참조"
description: "비교된 문서를 나타냅니다."
type: docs
weight: 120
url: /ko/net/groupdocs.comparison/document/
---
## Document class

비교된 문서를 나타냅니다.

```csharp
public class Document
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Document](document#constructor)(Stream) | `[`Document`](../document)` 클래스의 새 인스턴스를 초기화합니다. |
| [Document](document#constructor_2)(string) | `[`Document`](../document)` 클래스의 새 인스턴스를 초기화합니다. |
| [Document](document#constructor_1)(Stream, string) | `[`Document`](../document)` 클래스의 새 인스턴스를 초기화합니다. |
| [Document](document#constructor_3)(string, string) | `[`Document`](../document)` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Changes](../../groupdocs.comparison/document/changes) { get; set; } | 변경 목록. 변경 유형, 위치, 내용 등에 대한 자세한 설명을 포함합니다. |
| [FileType](../../groupdocs.comparison/document/filetype) { get; } | 문서 파일 유형. |
| [Name](../../groupdocs.comparison/document/name) { get; set; } | 문서 이름. |
| [Password](../../groupdocs.comparison/document/password) { get; } | 문서 비밀번호. |
| [Stream](../../groupdocs.comparison/document/stream) { get; } | 문서 스트림. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [GeneratePreview](../../groupdocs.comparison/document/generatepreview)(PreviewOptions) | 문서 페이지 미리보기를 생성합니다. |
| [GetDocumentInfo](../../groupdocs.comparison/document/getdocumentinfo)() | 문서에 대한 정보를 가져옵니다 - 문서 유형, 페이지 수, 페이지 크기 등. |

### 또 보기

* namespace [GroupDocs.Comparison](../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../)

<!-- 수정 금지: xmldocmd에 의해 GroupDocs.Comparison.dll용으로 생성됨 -->
