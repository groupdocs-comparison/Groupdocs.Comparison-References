---
title: "ChangeInfo"
second_title: "Справочник API GroupDocs.Comparison для .NET"
description: "Представляет информацию об изменении."
type: docs
weight: 460
url: /ru/net/groupdocs.comparison.result/changeinfo/
---
## ChangeInfo class

Представляет информацию об изменении.

```csharp
public class ChangeInfo
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ChangeInfo](changeinfo)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Authors](../../groupdocs.comparison.result/changeinfo/authors) { get; set; } | Список авторов. |
| [Box](../../groupdocs.comparison.result/changeinfo/box) { get; set; } | Координаты изменённого элемента. |
| [Column](../../groupdocs.comparison.result/changeinfo/column) { get; set; } | Нулевой индекс столбца изменённой ячейки. Заполняется для сравнения ячеек (XLSX, CSV, ODS и др.), иначе null. |
| [ColumnHeader](../../groupdocs.comparison.result/changeinfo/columnheader) { get; set; } | Текст заголовка столбца, взятый из первой строки листа для соответствующего столбца. Заполняется для сравнения ячеек, когда первая строка содержит значения заголовков, иначе null. |
| [ComparisonAction](../../groupdocs.comparison.result/changeinfo/comparisonaction) { get; set; } | Действие (принять или отклонить). Это поле указывает сравнивателю, что делать с этим изменением. |
| [ComponentType](../../groupdocs.comparison.result/changeinfo/componenttype) { get; set; } | Тип изменённого компонента. |
| [Id](../../groupdocs.comparison.result/changeinfo/id) { get; set; } | Идентификатор изменения. |
| [PageInfo](../../groupdocs.comparison.result/changeinfo/pageinfo) { get; set; } | Страница, на которой размещено текущее изменение. |
| [Row](../../groupdocs.comparison.result/changeinfo/row) { get; set; } | Нулевой индекс строки изменённой ячейки. Заполняется для сравнения ячеек (XLSX, CSV, ODS и др.), иначе null. |
| [SourceText](../../groupdocs.comparison.result/changeinfo/sourcetext) { get; set; } | Изменённый текст исходного документа. |
| [StyleChanges](../../groupdocs.comparison.result/changeinfo/stylechanges) { get; set; } | Массив изменений стилей. |
| [TargetText](../../groupdocs.comparison.result/changeinfo/targettext) { get; set; } | Изменённый текст целевого документа. |
| [Text](../../groupdocs.comparison.result/changeinfo/text) { get; set; } | Текстовое значение изменения. |
| [Type](../../groupdocs.comparison.result/changeinfo/type) { get; } | Тип изменения. |

### См. также

* namespace [GroupDocs.Comparison.Result](../../groupdocs.comparison.result)
* assembly [GroupDocs.Comparison](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Comparison.dll -->
