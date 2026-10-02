---
title: "LoadOptions"
second_title: "Справочник API GroupDocs.Comparison для .NET"
description: "Позволяет указать дополнительные параметры при загрузке документа."
type: docs
weight: 300
url: /ru/net/groupdocs.comparison.options/loadoptions/
---
## LoadOptions class

Позволяет указать дополнительные параметры при загрузке документа.

```csharp
public class LoadOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [LoadOptions](loadoptions)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [FileType](../../groupdocs.comparison.options/loadoptions/filetype) { get; set; } | Вручную задаёт тип файла для сравнения, переопределяя автоматическое определение типа файла. |
| [FontDirectories](../../groupdocs.comparison.options/loadoptions/fontdirectories) { get; set; } | Список каталогов шрифтов для загрузки. |
| [LoadText](../../groupdocs.comparison.options/loadoptions/loadtext) { get; set; } | Указывает, что переданные строки являются текстом сравнения, а не путями к файлам (только для сравнения текста). |
| [Password](../../groupdocs.comparison.options/loadoptions/password) { get; set; } | Пароль документа. |
| [SkipExternalResources](../../groupdocs.comparison.options/loadoptions/skipexternalresources) { get; set; } | Отключает загрузку всех внешних ресурсов (например, изображений, указанных удалённым URL), за исключением [`WhitelistedResources`](./whitelistedresources). |
| [WhitelistedResources](../../groupdocs.comparison.options/loadoptions/whitelistedresources) { get; set; } | Список фрагментов URL, соответствующих внешним ресурсам, которые должны быть загружены, когда [`SkipExternalResources`](./skipexternalresources) установлен в `true`. |

### См. также

* namespace [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Comparison.dll -->
