---
title: "WordCompareOptions"
second_title: "GroupDocs.Comparison for .NET API-referentie"
description: "Specifieke vergelijkingsopties voor Word-documenten. Erft algemene opties van CompareOptions./compareoptions."
type: docs
weight: 440
url: /nl/net/groupdocs.comparison.options/wordcompareoptions/
---
## WordCompareOptions class

Specifieke vergelijkingsopties voor Word-documenten. Erft algemene opties van [`CompareOptions`](../compareoptions).

```csharp
public class WordCompareOptions : CompareOptions
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [WordCompareOptions](wordcompareoptions)() | Initialiseert een nieuw exemplaar van de [`WordCompareOptions`](../wordcompareoptions) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [CalculateCoordinates](../../groupdocs.comparison.options/compareoptions/calculatecoordinates) { get; set; } | Geeft aan of coördinaten voor gewijzigde componenten moeten worden berekend. |
| [CalculateCoordinatesMode](../../groupdocs.comparison.options/compareoptions/calculatecoordinatesmode) { get; set; } | Specificeert de coördinatenberekening voor de modus van gewijzigde componenten. |
| [ChangedItemStyle](../../groupdocs.comparison.options/compareoptions/changeditemstyle) { get; set; } | Beschrijft de stijl voor gewijzigde componenten. |
| [CompareBookmarks](../../groupdocs.comparison.options/wordcompareoptions/comparebookmarks) { get; set; } | Haalt op of stelt in of bladwijzers in de bron- en doel-documenten worden vergeleken en verschillen in het resultaat worden opgenomen. |
| [CompareDocumentProperty](../../groupdocs.comparison.options/wordcompareoptions/comparedocumentproperty) { get; set; } | Haalt op of stelt in of ingebouwde en aangepaste documenteigenschappen worden vergeleken en verschillen in het resultaat worden opgenomen (bijv. op de samenvattingspagina van eigenschappen). |
| [CompareVariableProperty](../../groupdocs.comparison.options/wordcompareoptions/comparevariableproperty) { get; set; } | Haalt op of stelt in of documentvariabele-eigenschappen (bijv. DOCVARIABLE-velden) worden vergeleken en verschillen in het resultaat worden opgenomen. |
| [DeletedItemStyle](../../groupdocs.comparison.options/compareoptions/deleteditemstyle) { get; set; } | Beschrijft de stijl voor verwijderde componenten. |
| [DetalisationLevel](../../groupdocs.comparison.options/compareoptions/detalisationlevel) { get; set; } | Haalt of stelt het detailniveau van de vergelijking in. |
| [DetectStyleChanges](../../groupdocs.comparison.options/compareoptions/detectstylechanges) { get; set; } | Geeft aan of stijlwijzigingen al dan niet worden gedetecteerd. |
| [DiagramMasterSetting](../../groupdocs.comparison.options/compareoptions/diagrammastersetting) { get; set; } | Haalt of stelt de padwaarde voor de master in, of gebruikt vergelijking zonder pad van de master. Deze optie geldt alleen voor Diagram. |
| [DirectoryCompare](../../groupdocs.comparison.options/compareoptions/directorycompare) { get; set; } | Besturing om vergelijking van mappen in te schakelen. |
| [DisplayMode](../../groupdocs.comparison.options/wordcompareoptions/displaymode) { get; set; } | Haalt of stelt in hoe vergelijkingsresultaten worden weergegeven: als Word-revisies in de modus Track Changes (Revisions) of als gemarkeerde wijzigingen die direct in het document worden gerenderd (Highlight). |
| [ExtendedSummaryPage](../../groupdocs.comparison.options/compareoptions/extendedsummarypage) { get; set; } | Geeft aan of uitgebreide bestandsvergelijkingsinformatie aan de samenvattingspagina wordt toegevoegd of niet. |
| [FolderComparisonExtension](../../groupdocs.comparison.options/compareoptions/foldercomparisonextension) { get; set; } | Haalt of stelt het formaat in van het resulterende mapvergelijkingsbestand. |
| [GenerateSummaryPage](../../groupdocs.comparison.options/compareoptions/generatesummarypage) { get; set; } | Geeft aan of een samenvattingspagina met statistieken van gedetecteerde wijzigingen aan het resulterende document wordt toegevoegd of niet. |
| [HeaderFootersComparison](../../groupdocs.comparison.options/compareoptions/headerfooterscomparison) { get; set; } | Besturing om vergelijking van kop-/voettekstinhoud in te schakelen. |
| [IgnoreChangeSettings](../../groupdocs.comparison.options/compareoptions/ignorechangesettings) { get; set; } | Haalt of stelt instellingen in om wijzigingen op basis van gelijkenis te negeren. |
| [InsertedItemStyle](../../groupdocs.comparison.options/compareoptions/inserteditemstyle) { get; set; } | Beschrijft de stijl voor ingevoegde componenten. |
| [LeaveGaps](../../groupdocs.comparison.options/wordcompareoptions/leavegaps) { get; set; } | Haalt of stelt in of lege regels op de plaats van ingevoegde of verwijderde inhoud worden gelaten om de lay-out en het aantal regels te behouden; gebruikt met [`ShowInsertedContent`](../compareoptions/showinsertedcontent) en [`ShowDeletedContent`](../compareoptions/showdeletedcontent). |
| [MarkChangedContent](../../groupdocs.comparison.options/compareoptions/markchangedcontent) { get; set; } | Geeft aan of frames worden gebruikt voor vormen in Word Processing en voor rechthoeken in afbeeldingsdocumenten. |
| [MarkLineBreaks](../../groupdocs.comparison.options/wordcompareoptions/marklinebreaks) { get; set; } | Haalt of stelt in of alinea‑ (regelformaat) onderbrekingen die verschillen tussen documenten visueel worden gemarkeerd in het resultaat. |
| [MarkNestedContent](../../groupdocs.comparison.options/compareoptions/marknestedcontent) { get; set; } | Haalt of stelt een waarde in die aangeeft of de onderliggende elementen van het verwijderde of ingevoegde element als verwijderd of ingevoegd gemarkeerd moeten worden. |
| [OriginalSize](../../groupdocs.comparison.options/compareoptions/originalsize) { get; set; } | Haalt of stelt de oorspronkelijke afmetingen van de te vergelijken documenten in. |
| [PaperSize](../../groupdocs.comparison.options/compareoptions/papersize) { get; set; } | Haalt of stelt de papiergrootte van het resultaatsdocument in. |
| [PasswordSaveOption](../../groupdocs.comparison.options/compareoptions/passwordsaveoption) { get; set; } | Haalt of stelt de optie voor het opslaan van wachtwoord in. |
| [RevisionAuthorName](../../groupdocs.comparison.options/wordcompareoptions/revisionauthorname) { get; set; } | Haalt of stelt de auteursnaam in die wordt gebruikt voor revisies wanneer !:WordTrackChanges is ingeschakeld. Indien ingesteld, wordt deze naam toegepast op de revisiemarkeringen in het resultaatsdocument. |
| [SensitivityOfComparison](../../groupdocs.comparison.options/compareoptions/sensitivityofcomparison) { get; set; } | Haalt of stelt de gevoeligheid van de vergelijking in. |
| [SensitivityOfComparisonForTables](../../groupdocs.comparison.options/compareoptions/sensitivityofcomparisonfortables) { get; set; } | Haalt of stelt de gevoeligheid van de vergelijking voor tabellen in. |
| [ShowDeletedContent](../../groupdocs.comparison.options/compareoptions/showdeletedcontent) { get; set; } | Geeft aan of verwijderde componenten in het resulterende document worden getoond of niet. |
| [ShowInsertedContent](../../groupdocs.comparison.options/compareoptions/showinsertedcontent) { get; set; } | Geeft aan of ingevoegde componenten in het resulterende document worden getoond of niet. |
| [ShowOnlyChanged](../../groupdocs.comparison.options/compareoptions/showonlychanged) { get; set; } | Besturingen om alleen gewijzigde items weer te geven in te schakelen. |
| [ShowOnlySummaryPage](../../groupdocs.comparison.options/compareoptions/showonlysummarypage) { get; set; } | Geeft aan of in het resulterende document alleen een pagina met statistieken van gedetecteerde wijzigingen wordt achtergelaten of niet. |
| [ShowRevisions](../../groupdocs.comparison.options/wordcompareoptions/showrevisions) { get; set; } | Geeft of stelt in of de resulterende document de revisiemarkeringen zichtbaar houdt. Indien onwaar, worden alle revisies geaccepteerd en verschijnt het resultaat als definitieve tekst. Deze instelling is alleen van betekenis wanneer [`DisplayMode`](./displaymode) is ingesteld op Highlight. De standaardwaarde is true. |
| [UserMasterPath](../../groupdocs.comparison.options/compareoptions/usermasterpath) { get; set; } | Pad naar de master-sjabloon van de gebruiker voor diagrammen. |
| [WordsSeparatorChars](../../groupdocs.comparison.options/compareoptions/wordsseparatorchars) { set; } | Geeft of stelt een array van scheidingstekens in om tekst in woorden te splitsen. |

### Zie ook

* class [CompareOptions](../compareoptions)
* namespace [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Comparison.dll -->
