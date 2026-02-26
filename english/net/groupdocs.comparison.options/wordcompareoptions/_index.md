---
title: WordCompareOptions
second_title: GroupDocs.Comparison for .NET API Reference
description: Word document specific compare options. Inherits common options from CompareOptions./compareoptions.
type: docs
weight: 410
url: /net/groupdocs.comparison.options/wordcompareoptions/
---
## WordCompareOptions class

Word document specific compare options. Inherits common options from [`CompareOptions`](../compareoptions).

```csharp
public class WordCompareOptions : CompareOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [WordCompareOptions](wordcompareoptions)() | Initializes a new instance of the [`WordCompareOptions`](../wordcompareoptions) class. |

## Properties

| Name | Description |
| --- | --- |
| [CalculateCoordinates](../../groupdocs.comparison.options/compareoptions/calculatecoordinates) { get; set; } | Indicates whether to calculate coordinates for changed components. |
| [CalculateCoordinatesMode](../../groupdocs.comparison.options/compareoptions/calculatecoordinatesmode) { get; set; } | Specifies the coordinate calculation for changed components mode. |
| [ChangedItemStyle](../../groupdocs.comparison.options/compareoptions/changeditemstyle) { get; set; } | Describes style for changed components. |
| [CompareBookmarks](../../groupdocs.comparison.options/wordcompareoptions/comparebookmarks) { get; set; } | Gets or sets whether bookmarks in the source and target documents are compared and differences included in the result. |
| [CompareDocumentProperty](../../groupdocs.comparison.options/wordcompareoptions/comparedocumentproperty) { get; set; } | Gets or sets whether built-in and custom document properties are compared and differences included in the result (e.g. on the properties summary page). |
| [CompareImagesPdf](../../groupdocs.comparison.options/compareoptions/compareimagespdf) { get; set; } | Control to turn on comparison of images in PDF format. |
| [CompareVariableProperty](../../groupdocs.comparison.options/wordcompareoptions/comparevariableproperty) { get; set; } | Gets or sets whether document variable properties (e.g. DOCVARIABLE fields) are compared and differences included in the result. |
| [DeletedItemStyle](../../groupdocs.comparison.options/compareoptions/deleteditemstyle) { get; set; } | Describes style for deleted components. |
| [DetalisationLevel](../../groupdocs.comparison.options/compareoptions/detalisationlevel) { get; set; } | Gets or sets the comparison detail level. |
| [DetectStyleChanges](../../groupdocs.comparison.options/compareoptions/detectstylechanges) { get; set; } | Indicates whether to detect style changes or not. |
| [DiagramMasterSetting](../../groupdocs.comparison.options/compareoptions/diagrammastersetting) { get; set; } | Gets or sets the path value for master or use compare without path of master. This option only for Diagram. |
| [DirectoryCompare](../../groupdocs.comparison.options/compareoptions/directorycompare) { get; set; } | Control to turn on comparison of folders. |
| [DisplayMode](../../groupdocs.comparison.options/wordcompareoptions/displaymode) { get; set; } | Gets or sets how comparison results are displayed: as Word revisions in Track Changes mode (Revisions) or as highlighted changes rendered directly into the document (Highlight). |
| [ExtendedSummaryPage](../../groupdocs.comparison.options/compareoptions/extendedsummarypage) { get; set; } | Indicates whether to add extended file comparison information to the summary page or not. |
| [FolderComparisonExtension](../../groupdocs.comparison.options/compareoptions/foldercomparisonextension) { get; set; } | Gets or sets the format of the resulting folder comparison file. |
| [GenerateSummaryPage](../../groupdocs.comparison.options/compareoptions/generatesummarypage) { get; set; } | Indicates whether to add summary page with detected changes statistics to resultant document or not. |
| [HeaderFootersComparison](../../groupdocs.comparison.options/compareoptions/headerfooterscomparison) { get; set; } | Control to turn on comparison of header/footer contents. |
| [IgnoreChangeSettings](../../groupdocs.comparison.options/compareoptions/ignorechangesettings) { get; set; } | Gets or sets settings to ignore changes based on similarity. |
| [ImagesInheritanceMode](../../groupdocs.comparison.options/compareoptions/imagesinheritancemode) { get; set; } | Specifies the source of images inheritance when image comparison is disabled. |
| [InsertedItemStyle](../../groupdocs.comparison.options/compareoptions/inserteditemstyle) { get; set; } | Describes style for inserted components. |
| [LeaveGaps](../../groupdocs.comparison.options/wordcompareoptions/leavegaps) { get; set; } | Gets or sets whether empty lines are left in place of inserted or deleted content to preserve layout and line count; used with [`ShowInsertedContent`](../compareoptions/showinsertedcontent) and [`ShowDeletedContent`](../compareoptions/showdeletedcontent). |
| [MarkChangedContent](../../groupdocs.comparison.options/compareoptions/markchangedcontent) { get; set; } | Indicates whether to use frames for shapes in Word Processing and for rectangles in Image documents. |
| [MarkLineBreaks](../../groupdocs.comparison.options/wordcompareoptions/marklinebreaks) { get; set; } | Gets or sets whether paragraph (line) breaks that differ between documents are visually marked in the result. |
| [MarkNestedContent](../../groupdocs.comparison.options/compareoptions/marknestedcontent) { get; set; } | Gets or sets a value indicating whether to mark the children of the deleted or inserted element as deleted or inserted. |
| [OriginalSize](../../groupdocs.comparison.options/compareoptions/originalsize) { get; set; } | Get or sets the original sizes of compared documents. |
| [PaperSize](../../groupdocs.comparison.options/compareoptions/papersize) { get; set; } | Gets or sets the result document paper size. |
| [PasswordSaveOption](../../groupdocs.comparison.options/compareoptions/passwordsaveoption) { get; set; } | Gets or sets the password save option. |
| [RevisionAuthorName](../../groupdocs.comparison.options/wordcompareoptions/revisionauthorname) { get; set; } | Gets or sets the author name used for revisions when !:WordTrackChanges is enabled. If set, this name is applied to revision markup in the result document. |
| [SensitivityOfComparison](../../groupdocs.comparison.options/compareoptions/sensitivityofcomparison) { get; set; } | Gets or sets a sensitivity of comparison. |
| [SensitivityOfComparisonForTables](../../groupdocs.comparison.options/compareoptions/sensitivityofcomparisonfortables) { get; set; } | Gets or sets a sensitivity of comparison for tables. |
| [ShowDeletedContent](../../groupdocs.comparison.options/compareoptions/showdeletedcontent) { get; set; } | Indicates whether to show deleted components in resultant document or not. |
| [ShowInsertedContent](../../groupdocs.comparison.options/compareoptions/showinsertedcontent) { get; set; } | Indicates whether to show inserted components in resultant document or not. |
| [ShowOnlyChanged](../../groupdocs.comparison.options/compareoptions/showonlychanged) { get; set; } | Controls to enable the display of only changed items. |
| [ShowOnlySummaryPage](../../groupdocs.comparison.options/compareoptions/showonlysummarypage) { get; set; } | Indicates whether to leave in the resulting document only a page with statistics of detected changes in the resulting document or not. |
| [ShowRevisions](../../groupdocs.comparison.options/wordcompareoptions/showrevisions) { get; set; } | Gets or sets whether the result document keeps revision markup visible. If false, all revisions are accepted and the result appears as final text. This setting is meaningful only when [`DisplayMode`](./displaymode) is set to Highlight. The default value is true. |
| [UserMasterPath](../../groupdocs.comparison.options/compareoptions/usermasterpath) { get; set; } | Path to user master's template for Diagrams. |
| [WordsSeparatorChars](../../groupdocs.comparison.options/compareoptions/wordsseparatorchars) { set; } | Gets or sets an array of delimiters to split text into words. |

### See Also

* class [CompareOptions](../compareoptions)
* namespace [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Comparison.dll -->
