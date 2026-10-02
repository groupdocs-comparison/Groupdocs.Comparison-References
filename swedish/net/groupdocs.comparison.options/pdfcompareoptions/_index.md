---
title: "PdfCompareOptions"
second_title: "GroupDocs.Comparison för .NET API-referens"
description: "PDF-dokumentspecifika jämförelsealternativ. Ärver vanliga alternativ från CompareOptions./compareoptions."
type: docs
weight: 360
url: /sv/net/groupdocs.comparison.options/pdfcompareoptions/
---
## PdfCompareOptions class

PDF-dokumentspecifika jämförelsealternativ. Ärver vanliga alternativ från [`CompareOptions`](../compareoptions).

```csharp
public class PdfCompareOptions : CompareOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PdfCompareOptions](pdfcompareoptions)() | Initierar en ny instans av klassen [`PdfCompareOptions`](../pdfcompareoptions). |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AnnotationAuthorName](../../groupdocs.comparison.options/pdfcompareoptions/annotationauthorname) { get; set; } | Hämtar eller anger författarnamnet som används för anteckningar när [`DisplayMode`](./displaymode) är inställt på Interleaved. |
| [CalculateCoordinates](../../groupdocs.comparison.options/compareoptions/calculatecoordinates) { get; set; } | Anger om koordinater för ändrade komponenter ska beräknas. |
| [CalculateCoordinatesMode](../../groupdocs.comparison.options/compareoptions/calculatecoordinatesmode) { get; set; } | Specificerar koordinatberäkning för läge med ändrade komponenter. |
| [ChangedItemStyle](../../groupdocs.comparison.options/compareoptions/changeditemstyle) { get; set; } | Beskriver stil för ändrade komponenter. |
| [CompareImagesPdf](../../groupdocs.comparison.options/pdfcompareoptions/compareimagespdf) { get; set; } | Hämtar eller anger ett värde som indikerar om bilder i PDF-dokument ska jämföras. |
| [DeletedItemStyle](../../groupdocs.comparison.options/compareoptions/deleteditemstyle) { get; set; } | Beskriver stil för borttagna komponenter. |
| [DetalisationLevel](../../groupdocs.comparison.options/compareoptions/detalisationlevel) { get; set; } | Hämtar eller anger jämförelsens detaljnivå. |
| [DetectStyleChanges](../../groupdocs.comparison.options/compareoptions/detectstylechanges) { get; set; } | Anger om stiländringar ska upptäckas eller inte. |
| [DiagramMasterSetting](../../groupdocs.comparison.options/compareoptions/diagrammastersetting) { get; set; } | Hämtar eller anger sökvägsvärdet för master eller använder jämförelse utan master-sökväg. Detta alternativ gäller endast för Diagram. |
| [DirectoryCompare](../../groupdocs.comparison.options/compareoptions/directorycompare) { get; set; } | Kontroll för att aktivera jämförelse av mappar. |
| [DisplayMode](../../groupdocs.comparison.options/pdfcompareoptions/displaymode) { get; set; } | Hämtar eller anger hur jämförelsens resultatsdokument är upplagt. Standardvärdet är Inline. |
| [ExtendedSummaryPage](../../groupdocs.comparison.options/compareoptions/extendedsummarypage) { get; set; } | Anger om utökad filjämförelsinformation ska läggas till sammanfattningssidan eller inte. |
| [FolderComparisonExtension](../../groupdocs.comparison.options/compareoptions/foldercomparisonextension) { get; set; } | Hämtar eller anger formatet för den resulterande mappjämförelsfilen. |
| [GenerateSummaryPage](../../groupdocs.comparison.options/compareoptions/generatesummarypage) { get; set; } | Anger om en sammanfattningssida med statistik över upptäckta ändringar ska läggas till det resulterande dokumentet eller inte. |
| [HeaderFootersComparison](../../groupdocs.comparison.options/compareoptions/headerfooterscomparison) { get; set; } | Kontroll för att aktivera jämförelse av sidhuvud/sidfot-innehåll. |
| [IgnoreChangeSettings](../../groupdocs.comparison.options/compareoptions/ignorechangesettings) { get; set; } | Hämtar eller anger inställningar för att ignorera ändringar baserade på likhet. |
| [ImagesInheritanceMode](../../groupdocs.comparison.options/pdfcompareoptions/imagesinheritancemode) { get; set; } | Anger källan för bildarv när bildjämförelse är inaktiverad. |
| [InsertedItemStyle](../../groupdocs.comparison.options/compareoptions/inserteditemstyle) { get; set; } | Beskriver stil för infogade komponenter. |
| [MarkChangedContent](../../groupdocs.comparison.options/compareoptions/markchangedcontent) { get; set; } | Anger om ramar ska användas för former i ordbehandling och för rektanglar i bilddokument. |
| [MarkNestedContent](../../groupdocs.comparison.options/compareoptions/marknestedcontent) { get; set; } | Hämtar eller anger ett värde som indikerar om barnen till det raderade eller infogade elementet ska markeras som raderade eller infogade. |
| [OriginalSize](../../groupdocs.comparison.options/compareoptions/originalsize) { get; set; } | Hämtar eller anger de ursprungliga storlekarna på jämförda dokument. |
| [PagesSetup](../../groupdocs.comparison.options/pdfcompareoptions/pagessetup) { get; set; } | Hämtar eller anger sidintervallet som ska jämföras. När null jämförs alla sidor. |
| [PaperSize](../../groupdocs.comparison.options/compareoptions/papersize) { get; set; } | Hämtar eller anger pappersstorleken för resultatsdokumentet. |
| [PasswordSaveOption](../../groupdocs.comparison.options/compareoptions/passwordsaveoption) { get; set; } | Hämtar eller anger alternativet för att spara lösenord. |
| [SensitivityOfComparison](../../groupdocs.comparison.options/compareoptions/sensitivityofcomparison) { get; set; } | Hämtar eller anger en känslighet för jämförelsen. |
| [SensitivityOfComparisonForTables](../../groupdocs.comparison.options/compareoptions/sensitivityofcomparisonfortables) { get; set; } | Hämtar eller anger en känslighet för jämförelse av tabeller. |
| [ShowDeletedContent](../../groupdocs.comparison.options/compareoptions/showdeletedcontent) { get; set; } | Anger om raderade komponenter ska visas i det resulterande dokumentet eller inte. |
| [ShowInsertedContent](../../groupdocs.comparison.options/compareoptions/showinsertedcontent) { get; set; } | Anger om infogade komponenter ska visas i det resulterande dokumentet eller inte. |
| [ShowOnlyChanged](../../groupdocs.comparison.options/compareoptions/showonlychanged) { get; set; } | Kontroller för att möjliggöra visning av endast ändrade objekt. |
| [ShowOnlySummaryPage](../../groupdocs.comparison.options/compareoptions/showonlysummarypage) { get; set; } | Anger om endast en sida med statistik över upptäckta ändringar ska lämnas i det resulterande dokumentet eller inte. |
| [UserMasterPath](../../groupdocs.comparison.options/compareoptions/usermasterpath) { get; set; } | Sökväg till användarens mastermall för diagram. |
| [WordsSeparatorChars](../../groupdocs.comparison.options/compareoptions/wordsseparatorchars) { set; } | Hämtar eller anger en array av avgränsare för att dela upp text i ord. |

### Se även

* class [CompareOptions](../compareoptions)
* namespace [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../)

<!-- DO NOT EDIT: genererad av xmldocmd för GroupDocs.Comparison.dll -->
