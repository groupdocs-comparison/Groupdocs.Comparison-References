---
title: "LoadOptions"
second_title: "GroupDocs.Comparison .NET용 API 참조"
description: "문서를 로드할 때 추가 옵션을 지정할 수 있습니다."
type: docs
weight: 300
url: /ko/net/groupdocs.comparison.options/loadoptions/
---
## LoadOptions class

문서를 로드할 때 추가 옵션을 지정할 수 있습니다.

```csharp
public class LoadOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [LoadOptions](loadoptions)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [FileType](../../groupdocs.comparison.options/loadoptions/filetype) { get; set; } | 비교를 위해 파일 유형을 수동으로 설정하여 자동 파일 유형 감지를 재정의합니다. |
| [FontDirectories](../../groupdocs.comparison.options/loadoptions/fontdirectories) { get; set; } | 로드할 폰트 디렉터리 목록. |
| [LoadText](../../groupdocs.comparison.options/loadoptions/loadtext) { get; set; } | 전달된 문자열이 파일 경로가 아니라 비교 텍스트임을 나타냅니다(텍스트 비교 전용). |
| [Password](../../groupdocs.comparison.options/loadoptions/password) { get; set; } | 문서 비밀번호. |
| [SkipExternalResources](../../groupdocs.comparison.options/loadoptions/skipexternalresources) { get; set; } | 원격 URL에서 참조된 이미지와 같은 모든 외부 리소스 로드를 비활성화합니다. 단, [`WhitelistedResources`](./whitelistedresources)는 제외합니다. |
| [WhitelistedResources](../../groupdocs.comparison.options/loadoptions/whitelistedresources) { get; set; } | [`SkipExternalResources`](./skipexternalresources)가 `true`로 설정된 경우 로드해야 하는 외부 리소스에 해당하는 URL 조각 목록입니다. |

### 또 보기

* namespace [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../)

<!-- 수정 금지: xmldocmd에 의해 GroupDocs.Comparison.dll용으로 생성됨 -->
