---
title: "RevisionHandler"
second_title: "Справочник API GroupDocs.Comparison для .NET"
description: "Представляет основной класс, который управляет обработкой ревизий."
type: docs
weight: 540
url: /ru/net/groupdocs.comparison.words.revision/revisionhandler/
---
## RevisionHandler class

Представляет основной класс, который управляет обработкой ревизий.

```csharp
public sealed class RevisionHandler : IDisposable
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [RevisionHandler](revisionhandler#constructor)(Stream) | Инициализирует новый экземпляр класса [`RevisionHandler`](../revisionhandler) с файловым потоком, содержащим ревизии. |
| [RevisionHandler](revisionhandler#constructor_2)(string) | Инициализирует новый экземпляр класса [`RevisionHandler`](../revisionhandler) с путем к файлу, содержащему ревизии. |
| [RevisionHandler](revisionhandler#constructor_1)(Stream, bool) | Инициализирует новый экземпляр класса [`RevisionHandler`](../revisionhandler) с файловым потоком, содержащим ревизии, и явным контролем владения потоком. |

## Методы

| Имя | Описание |
| --- | --- |
| [ApplyRevisionChanges](../../groupdocs.comparison.words.revision/revisionhandler/applyrevisionchanges#applyrevisionchanges)(ApplyRevisionOptions) | Обрабатывает изменения в ревизиях и применяет их к тому же файлу, из которого были взяты ревизии. |
| [ApplyRevisionChanges](../../groupdocs.comparison.words.revision/revisionhandler/applyrevisionchanges#applyrevisionchanges_1)(Stream, ApplyRevisionOptions) | Обрабатывает изменения в ревизиях, и результат записывается в поток документа. |
| [ApplyRevisionChanges](../../groupdocs.comparison.words.revision/revisionhandler/applyrevisionchanges#applyrevisionchanges_2)(string, ApplyRevisionOptions) | Обрабатывает изменения в ревизиях, и результат записывается в указанный файл по пути. |
| [Dispose](../../groupdocs.comparison.words.revision/revisionhandler/dispose)() | Освобождает ресурсы. |
| [GetRevisions](../../groupdocs.comparison.words.revision/revisionhandler/getrevisions)() | Получает список всех ревизий. |

### См. также

* namespace [GroupDocs.Comparison.Words.Revision](../../groupdocs.comparison.words.revision)
* assembly [GroupDocs.Comparison](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Comparison.dll -->
