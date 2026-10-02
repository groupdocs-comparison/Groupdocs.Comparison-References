---
title: "PdfCompareOptions"
second_title: "GroupDocs.Comparison for .NET API-referentie"
description: "PDF-document specifieke vergelijkingsopties. Erft algemene opties van CompareOptions./compareoptions."
type: docs
weight: 360
url: /nl/net/groupdocs.comparison.options/pdfcompareoptions/
---
## PdfCompareOptions class

PDF-document specifieke vergelijkingsopties. Erft algemene opties van [`CompareOptions`](../compareoptions).

```csharp
public class PdfCompareOptions : CompareOptions
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [PdfCompareOptions](pdfcompareoptions)() | Initialiseert een nieuw exemplaar van de [`PdfCompareOptions`](../pdfcompareoptions) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AnnotationAuthorName](../../groupdocs.comparison.options/pdfcompareoptions/annotationauthorname) { get; set; } | Leest of stelt de auteursnaam in die wordt gebruikt voor annotaties wanneer [`DisplayMode`](./displaymode) is ingesteld op Interleaved. |
| [CalculateCoordinates](../../groupdocs.comparison.options/compareoptions/calculatecoordinates) { get; set; } | Geeft aan of coördinaten voor gewijzigde componenten moeten worden berekend. |
| [CalculateCoordinatesMode](../../groupdocs.comparison.options/compareoptions/calculatecoordinatesmode) { get; set; } | Specificeert de coördinatenberekening voor de modus van gewijzigde componenten. |
| [ChangedItemStyle](../../groupdocs.comparison.options/compareoptions/changeditemstyle) { get; set; } | Beschrijft de stijl voor gewijzigde componenten. |
| [CompareImagesPdf](../../groupdocs.comparison.options/pdfcompareoptions/compareimagespdf) { get; set; } | Leest of stelt een waarde in die aangeeft of afbeeldingen in PDF-documenten moeten worden vergeleken. |
| [DeletedItemStyle](../../groupdocs.comparison.options/compareoptions/deleteditemstyle) { get; set; } | Beschrijft de stijl voor verwijderde componenten. |
| [DetalisationLevel](../../groupdocs.comparison.options/compareoptions/detalisationlevel) { get; set; } | Haalt of stelt het detailniveau van de vergelijking in. |
| [DetectStyleChanges](../../groupdocs.comparison.options/compareoptions/detectstylechanges) { get; set; } | Geeft aan of stijlwijzigingen al dan niet worden gedetecteerd. |
| [DiagramMasterSetting](../../groupdocs.comparison.options/compareoptions/diagrammastersetting) { get; set; } | Haalt of stelt de padwaarde voor de master in, of gebruikt vergelijking zonder pad van de master. Deze optie geldt alleen voor Diagram. |
| [DirectoryCompare](../../groupdocs.comparison.options/compareoptions/directorycompare) { get; set; } | Besturing om vergelijking van mappen in te schakelen. |
| [DisplayMode](../../groupdocs.comparison.options/pdfcompareoptions/displaymode) { get; set; } | Leest of stelt in hoe het vergelijkingsresultaatdocument wordt opgemaakt. De standaardwaarde is Inline. |
| [ExtendedSummaryPage](../../groupdocs.comparison.options/compareoptions/extendedsummarypage) { get; set; } | Geeft aan of uitgebreide bestandsvergelijkingsinformatie aan de samenvattingspagina wordt toegevoegd of niet. |
| [FolderComparisonExtension](../../groupdocs.comparison.options/compareoptions/foldercomparisonextension) { get; set; } | Haalt of stelt het formaat in van het resulterende mapvergelijkingsbestand. |
| [GenerateSummaryPage](../../groupdocs.comparison.options/compareoptions/generatesummarypage) { get; set; } | Geeft aan of een samenvattingspagina met statistieken van gedetecteerde wijzigingen aan het resulterende document wordt toegevoegd of niet. |
| [HeaderFootersComparison](../../groupdocs.comparison.options/compareoptions/headerfooterscomparison) { get; set; } | Besturing om vergelijking van kop-/voettekstinhoud in te schakelen. |
| [IgnoreChangeSettings](../../groupdocs.comparison.options/compareoptions/ignorechangesettings) { get; set; } | Haalt of stelt instellingen in om wijzigingen op basis van gelijkenis te negeren. |
| [ImagesInheritanceMode](../../groupdocs.comparison.options/pdfcompareoptions/imagesinheritancemode) { get; set; } | Specificeert de bron van afbeeldingsovererving wanneer afbeeldingsvergelijking is uitgeschakeld. |
| [InsertedItemStyle](../../groupdocs.comparison.options/compareoptions/inserteditemstyle) { get; set; } | Beschrijft de stijl voor ingevoegde componenten. |
| [MarkChangedContent](../../groupdocs.comparison.options/compareoptions/markchangedcontent) { get; set; } | Geeft aan of frames worden gebruikt voor vormen in Word Processing en voor rechthoeken in afbeeldingsdocumenten. |
| [MarkNestedContent](../../groupdocs.comparison.options/compareoptions/marknestedcontent) { get; set; } | Haalt of stelt een waarde in die aangeeft of de onderliggende elementen van het verwijderde of ingevoegde element als verwijderd of ingevoegd gemarkeerd moeten worden. |
| [OriginalSize](../../groupdocs.comparison.options/compareoptions/originalsize) { get; set; } | Haalt of stelt de oorspronkelijke afmetingen van de te vergelijken documenten in. |
| [PagesSetup](../../groupdocs.comparison.options/pdfcompareoptions/pagessetup) { get; set; } | Leest of stelt het paginabereik in om te vergelijken. Wanneer null, worden alle pagina's vergeleken. |
| [PaperSize](../../groupdocs.comparison.options/compareoptions/papersize) { get; set; } | Haalt of stelt de papiergrootte van het resultaatsdocument in. |
| [PasswordSaveOption](../../groupdocs.comparison.options/compareoptions/passwordsaveoption) { get; set; } | Haalt of stelt de optie voor het opslaan van wachtwoord in. |
| [SensitivityOfComparison](../../groupdocs.comparison.options/compareoptions/sensitivityofcomparison) { get; set; } | Haalt of stelt de gevoeligheid van de vergelijking in. |
| [SensitivityOfComparisonForTables](../../groupdocs.comparison.options/compareoptions/sensitivityofcomparisonfortables) { get; set; } | Haalt of stelt de gevoeligheid van de vergelijking voor tabellen in. |
| [ShowDeletedContent](../../groupdocs.comparison.options/compareoptions/showdeletedcontent) { get; set; } | Geeft aan of verwijderde componenten in het resulterende document worden getoond of niet. |
| [ShowInsertedContent](../../groupdocs.comparison.options/compareoptions/showinsertedcontent) { get; set; } | Geeft aan of ingevoegde componenten in het resulterende document worden getoond of niet. |
| [ShowOnlyChanged](../../groupdocs.comparison.options/compareoptions/showonlychanged) { get; set; } | Besturingen om alleen gewijzigde items weer te geven in te schakelen. |
| [ShowOnlySummaryPage](../../groupdocs.comparison.options/compareoptions/showonlysummarypage) { get; set; } | Geeft aan of in het resulterende document alleen een pagina met statistieken van gedetecteerde wijzigingen wordt achtergelaten of niet. |
| [UserMasterPath](../../groupdocs.comparison.options/compareoptions/usermasterpath) { get; set; } | Pad naar de master-sjabloon van de gebruiker voor diagrammen. |
| [WordsSeparatorChars](../../groupdocs.comparison.options/compareoptions/wordsseparatorchars) { set; } | Geeft of stelt een array van scheidingstekens in om tekst in woorden te splitsen. |

### Zie ook

* class [CompareOptions](../compareoptions)
* namespace [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Comparison.dll -->
