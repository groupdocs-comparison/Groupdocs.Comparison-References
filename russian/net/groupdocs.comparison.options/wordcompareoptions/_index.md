---
title: "WordCompareOptions"
second_title: "Справочник API GroupDocs.Comparison для .NET"
description: "Опции сравнения, специфичные для документа Word. Наследует общие опции от CompareOptions./compareoptions."
type: docs
weight: 440
url: /ru/net/groupdocs.comparison.options/wordcompareoptions/
---
## WordCompareOptions class

Опции сравнения, специфичные для документа Word. Наследует общие опции от [`CompareOptions`](../compareoptions).

```csharp
public class WordCompareOptions : CompareOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [WordCompareOptions](wordcompareoptions)() | Инициализирует новый экземпляр класса [`WordCompareOptions`](../wordcompareoptions). |

## Свойства

| Имя | Описание |
| --- | --- |
| [CalculateCoordinates](../../groupdocs.comparison.options/compareoptions/calculatecoordinates) { get; set; } | Указывает, следует ли вычислять координаты изменённых компонентов. |
| [CalculateCoordinatesMode](../../groupdocs.comparison.options/compareoptions/calculatecoordinatesmode) { get; set; } | Указывает режим вычисления координат для изменённых компонентов. |
| [ChangedItemStyle](../../groupdocs.comparison.options/compareoptions/changeditemstyle) { get; set; } | Описывает стиль для изменённых компонентов. |
| [CompareBookmarks](../../groupdocs.comparison.options/wordcompareoptions/comparebookmarks) { get; set; } | Получает или задает, сравниваются ли закладки в исходных и целевых документах и включаются ли различия в результат. |
| [CompareDocumentProperty](../../groupdocs.comparison.options/wordcompareoptions/comparedocumentproperty) { get; set; } | Получает или задает, сравниваются ли встроенные и пользовательские свойства документа и включаются ли различия в результат (например, на странице сводки свойств). |
| [CompareVariableProperty](../../groupdocs.comparison.options/wordcompareoptions/comparevariableproperty) { get; set; } | Получает или задает, сравниваются ли переменные свойства документа (например, поля DOCVARIABLE) и включаются ли различия в результат. |
| [DeletedItemStyle](../../groupdocs.comparison.options/compareoptions/deleteditemstyle) { get; set; } | Описывает стиль для удалённых компонентов. |
| [DetalisationLevel](../../groupdocs.comparison.options/compareoptions/detalisationlevel) { get; set; } | Получает или задает уровень детализации сравнения. |
| [DetectStyleChanges](../../groupdocs.comparison.options/compareoptions/detectstylechanges) { get; set; } | Указывает, следует ли обнаруживать изменения стилей или нет. |
| [DiagramMasterSetting](../../groupdocs.comparison.options/compareoptions/diagrammastersetting) { get; set; } | Получает или задает значение пути к мастер‑файлу или использовать сравнение без пути к мастеру. Этот параметр только для Diagram. |
| [DirectoryCompare](../../groupdocs.comparison.options/compareoptions/directorycompare) { get; set; } | Элемент управления для включения сравнения папок. |
| [DisplayMode](../../groupdocs.comparison.options/wordcompareoptions/displaymode) { get; set; } | Получает или задает способ отображения результатов сравнения: как исправления Word в режиме отслеживания изменений (Revisions) или как подсвеченные изменения, внедрённые непосредственно в документ (Highlight). |
| [ExtendedSummaryPage](../../groupdocs.comparison.options/compareoptions/extendedsummarypage) { get; set; } | Указывает, следует ли добавлять расширенную информацию о сравнении файлов на страницу сводки, или нет. |
| [FolderComparisonExtension](../../groupdocs.comparison.options/compareoptions/foldercomparisonextension) { get; set; } | Получает или задает формат получаемого файла сравнения папок. |
| [GenerateSummaryPage](../../groupdocs.comparison.options/compareoptions/generatesummarypage) { get; set; } | Указывает, следует ли добавлять страницу сводки со статистикой обнаруженных изменений в результирующий документ, или нет. |
| [HeaderFootersComparison](../../groupdocs.comparison.options/compareoptions/headerfooterscomparison) { get; set; } | Элемент управления для включения сравнения содержимого верхнего/нижнего колонтитула. |
| [IgnoreChangeSettings](../../groupdocs.comparison.options/compareoptions/ignorechangesettings) { get; set; } | Получает или задает настройки игнорирования изменений на основе схожести. |
| [InsertedItemStyle](../../groupdocs.comparison.options/compareoptions/inserteditemstyle) { get; set; } | Описывает стиль для вставленных компонентов. |
| [LeaveGaps](../../groupdocs.comparison.options/wordcompareoptions/leavegaps) { get; set; } | Получает или задает, оставлять ли пустые строки вместо вставленного или удалённого содержимого для сохранения разметки и количества строк; используется с [`ShowInsertedContent`](../compareoptions/showinsertedcontent) и [`ShowDeletedContent`](../compareoptions/showdeletedcontent). |
| [MarkChangedContent](../../groupdocs.comparison.options/compareoptions/markchangedcontent) { get; set; } | Указывает, следует ли использовать рамки для фигур в обработке Word и для прямоугольников в документах Image. |
| [MarkLineBreaks](../../groupdocs.comparison.options/wordcompareoptions/marklinebreaks) { get; set; } | Получает или задает, отмечать ли визуально разрывы абзацев (строк), различающиеся между документами, в результате. |
| [MarkNestedContent](../../groupdocs.comparison.options/compareoptions/marknestedcontent) { get; set; } | Получает или задает значение, указывающее, помечать ли дочерние элементы удалённого или вставленного элемента как удалённые или вставленные. |
| [OriginalSize](../../groupdocs.comparison.options/compareoptions/originalsize) { get; set; } | Получает или задает исходные размеры сравниваемых документов. |
| [PaperSize](../../groupdocs.comparison.options/compareoptions/papersize) { get; set; } | Получает или задает размер бумаги результирующего документа. |
| [PasswordSaveOption](../../groupdocs.comparison.options/compareoptions/passwordsaveoption) { get; set; } | Получает или задает параметр сохранения пароля. |
| [RevisionAuthorName](../../groupdocs.comparison.options/wordcompareoptions/revisionauthorname) { get; set; } | Получает или задает имя автора, используемое для исправлений, когда включён !:WordTrackChanges. Если задано, это имя применяется к разметке исправлений в результирующем документе. |
| [SensitivityOfComparison](../../groupdocs.comparison.options/compareoptions/sensitivityofcomparison) { get; set; } | Получает или задает чувствительность сравнения. |
| [SensitivityOfComparisonForTables](../../groupdocs.comparison.options/compareoptions/sensitivityofcomparisonfortables) { get; set; } | Получает или задает чувствительность сравнения для таблиц. |
| [ShowDeletedContent](../../groupdocs.comparison.options/compareoptions/showdeletedcontent) { get; set; } | Указывает, показывать ли удалённые компоненты в результирующем документе, или нет. |
| [ShowInsertedContent](../../groupdocs.comparison.options/compareoptions/showinsertedcontent) { get; set; } | Указывает, показывать ли вставленные компоненты в результирующем документе, или нет. |
| [ShowOnlyChanged](../../groupdocs.comparison.options/compareoptions/showonlychanged) { get; set; } | Элементы управления для включения отображения только изменённых элементов. |
| [ShowOnlySummaryPage](../../groupdocs.comparison.options/compareoptions/showonlysummarypage) { get; set; } | Указывает, оставлять ли в результирующем документе только страницу со статистикой обнаруженных изменений, или нет. |
| [ShowRevisions](../../groupdocs.comparison.options/wordcompareoptions/showrevisions) { get; set; } | Получает или задает, отображается ли разметка правок в результирующем документе. Если false, все правки принимаются, и результат выглядит как окончательный текст. Этот параметр имеет смысл только когда [`DisplayMode`](./displaymode) установлен в Highlight. Значение по умолчанию — true. |
| [UserMasterPath](../../groupdocs.comparison.options/compareoptions/usermasterpath) { get; set; } | Путь к пользовательскому шаблону мастера для Диаграмм. |
| [WordsSeparatorChars](../../groupdocs.comparison.options/compareoptions/wordsseparatorchars) { set; } | Получает или задает массив разделителей для разбиения текста на слова. |

### См. также

* class [CompareOptions](../compareoptions)
* namespace [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Comparison.dll -->
