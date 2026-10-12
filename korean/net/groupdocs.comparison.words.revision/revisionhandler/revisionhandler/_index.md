---
title: "RevisionHandler"
second_title: "GroupDocs.Comparison .NET용 API 참조"
description: "수정이 포함된 파일 경로를 사용하여 RevisionHandlergroupdocs.comparison.words.revision/revisionhandler 클래스의 새 인스턴스를 초기화합니다."
type: docs
weight: 10
url: /ko/net/groupdocs.comparison.words.revision/revisionhandler/revisionhandler/
---
## RevisionHandler(string) {#constructor_2}

수정이 포함된 파일 경로를 사용하여 [`RevisionHandler`](../../revisionhandler) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public RevisionHandler(string filePath)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| filePath | String | 파일 경로 |

### 또 보기

* class [RevisionHandler](../../revisionhandler)
* namespace [GroupDocs.Comparison.Words.Revision](../../../groupdocs.comparison.words.revision)
* assembly [GroupDocs.Comparison](../../../)

---

## RevisionHandler(Stream) {#constructor}

수정이 포함된 파일 스트림을 사용하여 [`RevisionHandler`](../../revisionhandler) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public RevisionHandler(Stream file)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| file | Stream | 소스 문서 스트림 |

### 또 보기

* class [RevisionHandler](../../revisionhandler)
* namespace [GroupDocs.Comparison.Words.Revision](../../../groupdocs.comparison.words.revision)
* assembly [GroupDocs.Comparison](../../../)

---

## RevisionHandler(Stream, bool) {#constructor_1}

수정이 포함된 파일 스트림과 명시적인 스트림 소유권 제어를 사용하여 [`RevisionHandler`](../../revisionhandler) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public RevisionHandler(Stream file, bool leaveOpen)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| file | Stream | 소스 문서 스트림 |
| leaveOpen | Boolean | true인 경우, 호출자는 *file*에 대한 소유권을 유지하며 이를 해제할 책임이 있습니다. false(기본값)인 경우, [`Dispose`](../dispose) 가 스트림을 닫습니다. |

### 또 보기

* class [RevisionHandler](../../revisionhandler)
* namespace [GroupDocs.Comparison.Words.Revision](../../../groupdocs.comparison.words.revision)
* assembly [GroupDocs.Comparison](../../../)

<!-- 수정 금지: xmldocmd에 의해 GroupDocs.Comparison.dll용으로 생성됨 -->
