---
title: "WordCompareOptions"
second_title: "GroupDocs.Comparison för .NET API-referens"
description: "Specifika jämförelsealternativ för Word-dokument. Ärver vanliga alternativ från CompareOptions./compareoptions."
type: docs
weight: 440
url: /sv/net/groupdocs.comparison.options/wordcompareoptions/
---
## WordCompareOptions class

Specifika jämförelsealternativ för Word-dokument. Ärver vanliga alternativ från [`CompareOptions`](../compareoptions).

```csharp
public class WordCompareOptions : CompareOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [WordCompareOptions](wordcompareoptions)() | Initierar en ny instans av klassen [`WordCompareOptions`](../wordcompareoptions). |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [CalculateCoordinates](../../groupdocs.comparison.options/compareoptions/calculatecoordinates) { get; set; } | Anger om koordinater för ändrade komponenter ska beräknas. |
| [CalculateCoordinatesMode](../../groupdocs.comparison.options/compareoptions/calculatecoordinatesmode) { get; set; } | Specificerar koordinatberäkning för läge med ändrade komponenter. |
| [ChangedItemStyle](../../groupdocs.comparison.options/compareoptions/changeditemstyle) { get; set; } | Beskriver stil för ändrade komponenter. |
| [CompareBookmarks](../../groupdocs.comparison.options/wordcompareoptions/comparebookmarks) { get; set; } | Hämtar eller anger om bokmärken i käll- och mål dokument jämförs och skillnader inkluderas i resultatet. |
| [CompareDocumentProperty](../../groupdocs.comparison.options/wordcompareoptions/comparedocumentproperty) { get; set; } | Hämtar eller anger om inbyggda och anpassade dokumentegenskaper jämförs och skillnader inkluderas i resultatet (t.ex. på sammanfattningssidan för egenskaper). |
| [CompareVariableProperty](../../groupdocs.comparison.options/wordcompareoptions/comparevariableproperty) { get; set; } | Hämtar eller anger om dokumentvariabelegenskaper (t.ex. DOCVARIABLE-fält) jämförs och skillnader inkluderas i resultatet. |
| [DeletedItemStyle](../../groupdocs.comparison.options/compareoptions/deleteditemstyle) { get; set; } | Beskriver stil för borttagna komponenter. |
| [DetalisationLevel](../../groupdocs.comparison.options/compareoptions/detalisationlevel) { get; set; } | Hämtar eller anger jämförelsens detaljnivå. |
| [DetectStyleChanges](../../groupdocs.comparison.options/compareoptions/detectstylechanges) { get; set; } | Anger om stiländringar ska upptäckas eller inte. |
| [DiagramMasterSetting](../../groupdocs.comparison.options/compareoptions/diagrammastersetting) { get; set; } | Hämtar eller anger sökvägsvärdet för master eller använder jämförelse utan master-sökväg. Detta alternativ gäller endast för Diagram. |
| [DirectoryCompare](../../groupdocs.comparison.options/compareoptions/directorycompare) { get; set; } | Kontroll för att aktivera jämförelse av mappar. |
| [DisplayMode](../../groupdocs.comparison.options/wordcompareoptions/displaymode) { get; set; } | Hämtar eller anger hur jämförelsens resultat visas: som Word-revisioner i Spåra ändringar-läge (Revisions) eller som markerade ändringar som renderas direkt i dokumentet (Highlight). |
| [ExtendedSummaryPage](../../groupdocs.comparison.options/compareoptions/extendedsummarypage) { get; set; } | Anger om utökad filjämförelsinformation ska läggas till sammanfattningssidan eller inte. |
| [FolderComparisonExtension](../../groupdocs.comparison.options/compareoptions/foldercomparisonextension) { get; set; } | Hämtar eller anger formatet för den resulterande mappjämförelsfilen. |
| [GenerateSummaryPage](../../groupdocs.comparison.options/compareoptions/generatesummarypage) { get; set; } | Anger om en sammanfattningssida med statistik över upptäckta ändringar ska läggas till det resulterande dokumentet eller inte. |
| [HeaderFootersComparison](../../groupdocs.comparison.options/compareoptions/headerfooterscomparison) { get; set; } | Kontroll för att aktivera jämförelse av sidhuvud/sidfot-innehåll. |
| [IgnoreChangeSettings](../../groupdocs.comparison.options/compareoptions/ignorechangesettings) { get; set; } | Hämtar eller anger inställningar för att ignorera ändringar baserade på likhet. |
| [InsertedItemStyle](../../groupdocs.comparison.options/compareoptions/inserteditemstyle) { get; set; } | Beskriver stil för infogade komponenter. |
| [LeaveGaps](../../groupdocs.comparison.options/wordcompareoptions/leavegaps) { get; set; } | Hämtar eller anger om tomma rader lämnas i stället för infogat eller raderat innehåll för att bevara layout och radantal; används med [`ShowInsertedContent`](../compareoptions/showinsertedcontent) och [`ShowDeletedContent`](../compareoptions/showdeletedcontent). |
| [MarkChangedContent](../../groupdocs.comparison.options/compareoptions/markchangedcontent) { get; set; } | Anger om ramar ska användas för former i ordbehandling och för rektanglar i bilddokument. |
| [MarkLineBreaks](../../groupdocs.comparison.options/wordcompareoptions/marklinebreaks) { get; set; } | Hämtar eller anger om stycke- (rad-)brytningar som skiljer sig mellan dokument ska markeras visuellt i resultatet. |
| [MarkNestedContent](../../groupdocs.comparison.options/compareoptions/marknestedcontent) { get; set; } | Hämtar eller anger ett värde som indikerar om barnen till det raderade eller infogade elementet ska markeras som raderade eller infogade. |
| [OriginalSize](../../groupdocs.comparison.options/compareoptions/originalsize) { get; set; } | Hämtar eller anger de ursprungliga storlekarna på jämförda dokument. |
| [PaperSize](../../groupdocs.comparison.options/compareoptions/papersize) { get; set; } | Hämtar eller anger pappersstorleken för resultatsdokumentet. |
| [PasswordSaveOption](../../groupdocs.comparison.options/compareoptions/passwordsaveoption) { get; set; } | Hämtar eller anger alternativet för att spara lösenord. |
| [RevisionAuthorName](../../groupdocs.comparison.options/wordcompareoptions/revisionauthorname) { get; set; } | Hämtar eller anger författarnamnet som används för revisioner när !:WordTrackChanges är aktiverat. Om angivet tillämpas detta namn på revisionsmarkeringar i resultatsdokumentet. |
| [SensitivityOfComparison](../../groupdocs.comparison.options/compareoptions/sensitivityofcomparison) { get; set; } | Hämtar eller anger en känslighet för jämförelsen. |
| [SensitivityOfComparisonForTables](../../groupdocs.comparison.options/compareoptions/sensitivityofcomparisonfortables) { get; set; } | Hämtar eller anger en känslighet för jämförelse av tabeller. |
| [ShowDeletedContent](../../groupdocs.comparison.options/compareoptions/showdeletedcontent) { get; set; } | Anger om raderade komponenter ska visas i det resulterande dokumentet eller inte. |
| [ShowInsertedContent](../../groupdocs.comparison.options/compareoptions/showinsertedcontent) { get; set; } | Anger om infogade komponenter ska visas i det resulterande dokumentet eller inte. |
| [ShowOnlyChanged](../../groupdocs.comparison.options/compareoptions/showonlychanged) { get; set; } | Kontroller för att möjliggöra visning av endast ändrade objekt. |
| [ShowOnlySummaryPage](../../groupdocs.comparison.options/compareoptions/showonlysummarypage) { get; set; } | Anger om endast en sida med statistik över upptäckta ändringar ska lämnas i det resulterande dokumentet eller inte. |
| [ShowRevisions](../../groupdocs.comparison.options/wordcompareoptions/showrevisions) { get; set; } | Hämtar eller anger om resultatdokumentet behåller revisionsmarkering synlig. Om falskt accepteras alla revisioner och resultatet visas som slutgiltig text. Denna inställning är meningsfull endast när [`DisplayMode`](./displaymode) är satt till Highlight. Standardvärdet är true. |
| [UserMasterPath](../../groupdocs.comparison.options/compareoptions/usermasterpath) { get; set; } | Sökväg till användarens mastermall för diagram. |
| [WordsSeparatorChars](../../groupdocs.comparison.options/compareoptions/wordsseparatorchars) { set; } | Hämtar eller anger en array av avgränsare för att dela upp text i ord. |

### Se även

* class [CompareOptions](../compareoptions)
* namespace [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../)

<!-- DO NOT EDIT: genererad av xmldocmd för GroupDocs.Comparison.dll -->
