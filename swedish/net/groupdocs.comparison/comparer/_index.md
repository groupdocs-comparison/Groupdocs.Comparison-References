---
title: "Jämförare"
second_title: "GroupDocs.Comparison för .NET API-referens"
description: "Representerar huvudklassen som styr dokumentjämförelseprocessen."
type: docs
weight: 100
url: /sv/net/groupdocs.comparison/comparer/
---
## Comparer class

Representerar huvudklassen som styr dokumentjämförelseprocessen.

```csharp
public sealed class Comparer : IDisposable
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Comparer](comparer#constructor)(Stream) | Initierar en ny instans av klassen [`Comparer`](../comparer) med källdokumentström. |
| [Comparer](comparer#constructor_4)(string) | Initierar en ny instans av klassen [`Comparer`](../comparer) med källfilens sökväg. |
| [Comparer](comparer#constructor_1)(Stream, ComparerSettings) | Initierar en ny instans av klassen [`Comparer`](../comparer) med källdokumentström och [`ComparerSettings`](../comparersettings). |
| [Comparer](comparer#constructor_2)(Stream, LoadOptions) | Initierar en ny instans av [`Comparer`](../comparer) med källdokumentström och [`LoadOptions`](../../groupdocs.comparison.options/loadoptions). |
| [Comparer](comparer#constructor_6)(string, CompareOptions) | Initierar en ny instans av [`Comparer`](../comparer) med källmappens sökväg och [`CompareOptions`](../../groupdocs.comparison.options/compareoptions). |
| [Comparer](comparer#constructor_5)(string, ComparerSettings) | Initierar en ny instans av klassen [`Comparer`](../comparer) med källfilens sökväg och [`ComparerSettings`](../comparersettings). |
| [Comparer](comparer#constructor_7)(string, LoadOptions) | Initierar en ny instans av [`Comparer`](../comparer) med sökväg till källfil och [`LoadOptions`](../../groupdocs.comparison.options/loadoptions). |
| [Comparer](comparer#constructor_3)(Stream, LoadOptions, ComparerSettings) | Initierar en ny instans av [`Comparer`](../comparer)-klassen med dokumentström, [`LoadOptions`](../../groupdocs.comparison.options/loadoptions) och [`ComparerSettings`](../comparersettings). |
| [Comparer](comparer#constructor_8)(string, LoadOptions, ComparerSettings) | Initierar en ny instans av [`Comparer`](../comparer)-klassen med sökväg till källfil, [`LoadOptions`](../../groupdocs.comparison.options/loadoptions) och [`ComparerSettings`](../comparersettings). |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Result](../../groupdocs.comparison/comparer/result) { get; } | Resultatdokument. |
| [Source](../../groupdocs.comparison/comparer/source) { get; } | Källfil som jämförs. |
| [SourceFolder](../../groupdocs.comparison/comparer/sourcefolder) { get; } | Källmapp som jämförs. |
| [TargetFolder](../../groupdocs.comparison/comparer/targetfolder) { get; set; } | Målmapp som jämförs. |
| [Targets](../../groupdocs.comparison/comparer/targets) { get; } | Lista över målfil(er) att jämföra med källfilen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Add](../../groupdocs.comparison/comparer/add#add)(Stream) | Lägger till dokumentström i jämförelsen. |
| [Add](../../groupdocs.comparison/comparer/add#add_2)(string) | Lägger till fil i jämförelsen. |
| [Add](../../groupdocs.comparison/comparer/add#add_1)(Stream, LoadOptions) | Lägger till dokumentström i jämförelsen med angivna laddningsalternativ. |
| [Add](../../groupdocs.comparison/comparer/add#add_3)(string, CompareOptions) | Lägger till mapp i jämförelsen. |
| [Add](../../groupdocs.comparison/comparer/add#add_4)(string, LoadOptions) | Lägger till fil i jämförelsen med angivna laddningsalternativ. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges)(Stream, ApplyChangeOptions) | Accepterar eller avvisar ändringar och tillämpar dem på det resulterande dokumentet. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_2)(string, ApplyChangeOptions) | Accepterar eller avvisar ändringar och tillämpar dem på det resulterande dokumentet. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_1)(Stream, SaveOptions, ApplyChangeOptions) | Accepterar eller avvisar ändringar och tillämpar dem på det resulterande dokumentet. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_3)(string, SaveOptions, ApplyChangeOptions) | Accepterar eller avvisar ändringar och tillämpar dem på det resulterande dokumentet. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare)() | Jämför dokument utan att spara resultatet med standardalternativ |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_1)(CompareOptions) | Jämför dokument utan att spara resultatet. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_3)(Stream) | Jämför dokument och sparar resultatet till filström |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_7)(string) | Jämför dokument och sparar resultatet till filsökväg |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_2)(SaveOptions, CompareOptions) | Jämför dokument utan att spara resultatet. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_4)(Stream, CompareOptions) | Jämför dokument och sparar resultatet till filström |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_5)(Stream, SaveOptions) | Jämför dokument och sparar resultatet till filström |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_8)(string, CompareOptions) | Jämför dokument och sparar resultatet till filsökväg |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_9)(string, SaveOptions) | Jämför dokument och sparar resultatet till filsökväg |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_6)(Stream, SaveOptions, CompareOptions) | Jämför dokument och sparar resultatet till en ström. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_10)(string, SaveOptions, CompareOptions) | Jämför dokument och sparar resultatet till filsökväg |
| [CompareDirectory](../../groupdocs.comparison/comparer/comparedirectory)(string, CompareOptions) | Jämför katalog och sparar resultatet till filsökväg |
| [Dispose](../../groupdocs.comparison/comparer/dispose)() | Frigör resurser. |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges)() | Hämtar lista över ändringar mellan källa och målfil(er). |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges_1)(ChangeType) | Hämtar lista över ändringar mellan källa och målfil(er). |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges_2)(GetChangeOptions) | Hämtar lista över ändringar mellan källa och målfil(er). |
| [GetResultDocumentStream](../../groupdocs.comparison/comparer/getresultdocumentstream)() | Hämtar strömmen för resultatdokumentet, returnerar null om strömmen inte finns |
| [GetResultString](../../groupdocs.comparison/comparer/getresultstring)() | Hämta resultatssträng efter jämförelse (Endast för textjämförelse). |

### Se även

* namespace [GroupDocs.Comparison](../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../)

<!-- DO NOT EDIT: genererad av xmldocmd för GroupDocs.Comparison.dll -->
