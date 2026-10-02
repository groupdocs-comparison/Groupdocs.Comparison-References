---
title: "Сравнитель"
second_title: "Справочник API GroupDocs.Comparison для .NET"
description: "Представляет основной класс, который управляет процессом сравнения документов."
type: docs
weight: 100
url: /ru/net/groupdocs.comparison/comparer/
---
## Comparer class

Представляет основной класс, который управляет процессом сравнения документов.

```csharp
public sealed class Comparer : IDisposable
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Comparer](comparer#constructor)(Stream) | Инициализирует новый экземпляр класса [`Comparer`](../comparer) с потоком исходного документа. |
| [Comparer](comparer#constructor_4)(string) | Инициализирует новый экземпляр класса [`Comparer`](../comparer) с путем к исходному файлу. |
| [Comparer](comparer#constructor_1)(Stream, ComparerSettings) | Инициализирует новый экземпляр класса [`Comparer`](../comparer) с потоком исходного документа и [`ComparerSettings`](../comparersettings). |
| [Comparer](comparer#constructor_2)(Stream, LoadOptions) | Инициализирует новый экземпляр [`Comparer`](../comparer) с потоком исходного документа и [`LoadOptions`](../../groupdocs.comparison.options/loadoptions). |
| [Comparer](comparer#constructor_6)(string, CompareOptions) | Инициализирует новый экземпляр [`Comparer`](../comparer) с путем к исходной папке и [`CompareOptions`](../../groupdocs.comparison.options/compareoptions). |
| [Comparer](comparer#constructor_5)(string, ComparerSettings) | Инициализирует новый экземпляр класса [`Comparer`](../comparer) с путем к исходному файлу и [`ComparerSettings`](../comparersettings). |
| [Comparer](comparer#constructor_7)(string, LoadOptions) | Инициализирует новый экземпляр [`Comparer`](../comparer) с путем к исходному файлу и [`LoadOptions`](../../groupdocs.comparison.options/loadoptions). |
| [Comparer](comparer#constructor_3)(Stream, LoadOptions, ComparerSettings) | Инициализирует новый экземпляр класса [`Comparer`](../comparer) с потоком документа, [`LoadOptions`](../../groupdocs.comparison.options/loadoptions) и [`ComparerSettings`](../comparersettings). |
| [Comparer](comparer#constructor_8)(string, LoadOptions, ComparerSettings) | Инициализирует новый экземпляр класса [`Comparer`](../comparer) с путем к исходному файлу, [`LoadOptions`](../../groupdocs.comparison.options/loadoptions) и [`ComparerSettings`](../comparersettings). |

## Свойства

| Имя | Описание |
| --- | --- |
| [Result](../../groupdocs.comparison/comparer/result) { get; } | Документ результата. |
| [Source](../../groupdocs.comparison/comparer/source) { get; } | Исходный файл, который сравнивается. |
| [SourceFolder](../../groupdocs.comparison/comparer/sourcefolder) { get; } | Исходная папка, которая сравнивается. |
| [TargetFolder](../../groupdocs.comparison/comparer/targetfolder) { get; set; } | Целевая папка, которая сравнивается. |
| [Targets](../../groupdocs.comparison/comparer/targets) { get; } | Список целевых файлов для сравнения с исходным файлом. |

## Методы

| Имя | Описание |
| --- | --- |
| [Add](../../groupdocs.comparison/comparer/add#add)(Stream) | Добавляет поток документа к сравнению. |
| [Add](../../groupdocs.comparison/comparer/add#add_2)(string) | Добавляет файл к сравнению. |
| [Add](../../groupdocs.comparison/comparer/add#add_1)(Stream, LoadOptions) | Добавляет поток документа к сравнению с указанными параметрами загрузки. |
| [Add](../../groupdocs.comparison/comparer/add#add_3)(string, CompareOptions) | Добавляет папку к сравнению. |
| [Add](../../groupdocs.comparison/comparer/add#add_4)(string, LoadOptions) | Добавляет файл к сравнению с указанными параметрами загрузки. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges)(Stream, ApplyChangeOptions) | Принимает или отклоняет изменения и применяет их к результирующему документу. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_2)(string, ApplyChangeOptions) | Принимает или отклоняет изменения и применяет их к результирующему документу. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_1)(Stream, SaveOptions, ApplyChangeOptions) | Принимает или отклоняет изменения и применяет их к результирующему документу. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_3)(string, SaveOptions, ApplyChangeOptions) | Принимает или отклоняет изменения и применяет их к результирующему документу. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare)() | Сравнивает документы без сохранения результата с параметрами по умолчанию |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_1)(CompareOptions) | Сравнивает документы без сохранения результата. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_3)(Stream) | Сравнивает документы и сохраняет результат в поток файла |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_7)(string) | Сравнивает документы и сохраняет результат по пути к файлу |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_2)(SaveOptions, CompareOptions) | Сравнивает документы без сохранения результата. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_4)(Stream, CompareOptions) | Сравнивает документы и сохраняет результат в поток файла |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_5)(Stream, SaveOptions) | Сравнивает документы и сохраняет результат в поток файла |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_8)(string, CompareOptions) | Сравнивает документы и сохраняет результат по пути к файлу |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_9)(string, SaveOptions) | Сравнивает документы и сохраняет результат по пути к файлу |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_6)(Stream, SaveOptions, CompareOptions) | Сравнивает документы и сохраняет результат в поток. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_10)(string, SaveOptions, CompareOptions) | Сравнивает документы и сохраняет результат по пути к файлу |
| [CompareDirectory](../../groupdocs.comparison/comparer/comparedirectory)(string, CompareOptions) | Сравнивает каталог и сохраняет результат по пути к файлу |
| [Dispose](../../groupdocs.comparison/comparer/dispose)() | Освобождает ресурсы. |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges)() | Получает список изменений между исходным и целевыми файлом(ами). |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges_1)(ChangeType) | Получает список изменений между исходным и целевыми файлом(ами). |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges_2)(GetChangeOptions) | Получает список изменений между исходным и целевыми файлом(ами). |
| [GetResultDocumentStream](../../groupdocs.comparison/comparer/getresultdocumentstream)() | Получает поток результирующего документа, возвращает null, если поток не существует |
| [GetResultString](../../groupdocs.comparison/comparer/getresultstring)() | Получить строку результата после сравнения (только для сравнения текста). |

### См. также

* namespace [GroupDocs.Comparison](../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Comparison.dll -->
