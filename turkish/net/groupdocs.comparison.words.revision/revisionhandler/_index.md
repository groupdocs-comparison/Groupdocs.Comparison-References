---
title: "RevisionHandler"
second_title: "GroupDocs.Comparison .NET için API Referansı"
description: "Revizyon işleme kontrol eden ana sınıfı temsil eder."
type: docs
weight: 540
url: /tr/net/groupdocs.comparison.words.revision/revisionhandler/
---
## RevisionHandler class

Revizyon işleme kontrol eden ana sınıfı temsil eder.

```csharp
public sealed class RevisionHandler : IDisposable
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [RevisionHandler](revisionhandler#constructor)(Stream) | Revizyon içeren bir dosya akışıyla [`RevisionHandler`](../revisionhandler) sınıfının yeni bir örneğini başlatır. |
| [RevisionHandler](revisionhandler#constructor_2)(string) | Revizyon içeren dosyanın yolu ile [`RevisionHandler`](../revisionhandler) sınıfının yeni bir örneğini başlatır. |
| [RevisionHandler](revisionhandler#constructor_1)(Stream, bool) | Revizyon içeren bir dosya akışı ve açık akış sahipliği kontrolüyle [`RevisionHandler`](../revisionhandler) sınıfının yeni bir örneğini başlatır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [ApplyRevisionChanges](../../groupdocs.comparison.words.revision/revisionhandler/applyrevisionchanges#applyrevisionchanges)(ApplyRevisionOptions) | Revizyonlardaki değişiklikleri işler ve revizyonların alındığı aynı dosyaya uygular. |
| [ApplyRevisionChanges](../../groupdocs.comparison.words.revision/revisionhandler/applyrevisionchanges#applyrevisionchanges_1)(Stream, ApplyRevisionOptions) | Revizyonlardaki değişiklikleri işler ve sonuç belge akışına yazılır. |
| [ApplyRevisionChanges](../../groupdocs.comparison.words.revision/revisionhandler/applyrevisionchanges#applyrevisionchanges_2)(string, ApplyRevisionOptions) | Revizyonlardaki değişiklikleri işler ve sonuç belirtilen dosya yoluna yazılır. |
| [Dispose](../../groupdocs.comparison.words.revision/revisionhandler/dispose)() | Kaynakları serbest bırakır. |
| [GetRevisions](../../groupdocs.comparison.words.revision/revisionhandler/getrevisions)() | Tüm revizyonların listesini alır. |

### Ayrıca Bakınız

* namespace [GroupDocs.Comparison.Words.Revision](../../groupdocs.comparison.words.revision)
* assembly [GroupDocs.Comparison](../../)

<!-- DÜZENLEMEYİN: GroupDocs.Comparison.dll için xmldocmd tarafından oluşturuldu -->
