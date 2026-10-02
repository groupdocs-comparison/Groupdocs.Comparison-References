---
title: "ApplyRevisionChanges"
second_title: "Справочник API GroupDocs.Comparison для .NET"
description: "Обрабатывает изменения в ревизиях и применяет их к тому же файлу, из которого были взяты ревизии."
type: docs
weight: 20
url: /ru/net/groupdocs.comparison.words.revision/revisionhandler/applyrevisionchanges/
---
## ApplyRevisionChanges(ApplyRevisionOptions) {#applyrevisionchanges}

Обрабатывает изменения в ревизиях и применяет их к тому же файлу, из которого были взяты ревизии.

```csharp
public void ApplyRevisionChanges(ApplyRevisionOptions changes)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| изменения | ApplyRevisionOptions | Список изменённых ревизий |

### См. также

* class [ApplyRevisionOptions](../../applyrevisionoptions)
* class [RevisionHandler](../../revisionhandler)
* namespace [GroupDocs.Comparison.Words.Revision](../../../groupdocs.comparison.words.revision)
* assembly [GroupDocs.Comparison](../../../)

---

## ApplyRevisionChanges(string, ApplyRevisionOptions) {#applyrevisionchanges_2}

Обрабатывает изменения в ревизиях, и результат записывается в указанный файл по пути.

```csharp
public void ApplyRevisionChanges(string filePath, ApplyRevisionOptions changes)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к результирующему файлу |
| изменения | ApplyRevisionOptions | Список изменённых ревизий |

### См. также

* class [ApplyRevisionOptions](../../applyrevisionoptions)
* class [RevisionHandler](../../revisionhandler)
* namespace [GroupDocs.Comparison.Words.Revision](../../../groupdocs.comparison.words.revision)
* assembly [GroupDocs.Comparison](../../../)

---

## ApplyRevisionChanges(Stream, ApplyRevisionOptions) {#applyrevisionchanges_1}

Обрабатывает изменения в ревизиях, и результат записывается в поток документа.

```csharp
public void ApplyRevisionChanges(Stream document, ApplyRevisionOptions changes)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| документ | Stream | Результирующий документ |
| изменения | ApplyRevisionOptions | Список изменённых ревизий |

### См. также

* class [ApplyRevisionOptions](../../applyrevisionoptions)
* class [RevisionHandler](../../revisionhandler)
* namespace [GroupDocs.Comparison.Words.Revision](../../../groupdocs.comparison.words.revision)
* assembly [GroupDocs.Comparison](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Comparison.dll -->
