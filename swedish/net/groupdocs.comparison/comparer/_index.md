---
title: Comparer
second_title: GroupDocs.Comparison för .NET API-referens
description: Representerar huvudklass som styr dokumentjämförelseprocessen.
type: docs
weight: 100
url: /sv/net/groupdocs.comparison/comparer/
---
## Comparer class

Representerar huvudklass som styr dokumentjämförelseprocessen.

```csharp
public class Comparer : IDisposable
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [Comparer](comparer#constructor)(Stream) | Initierar ny instans av[`Comparer`](../comparer) klass med källdokumentström. |
| [Comparer](comparer#constructor_4)(string) | Initierar ny instans av[`Comparer`](../comparer) klass med källfilens sökväg. |
| [Comparer](comparer#constructor_1)(Stream, ComparerSettings) | Initierar ny instans av[`Comparer`](../comparer)klass med källdokumentström och[`ComparerSettings`](../comparersettings) . |
| [Comparer](comparer#constructor_2)(Stream, LoadOptions) | Initierar ny instans av[`Comparer`](../comparer) med källdokumentström och[`LoadOptions`](../../groupdocs.comparison.options/loadoptions) . |
| [Comparer](comparer#constructor_5)(string, ComparerSettings) | Initierar ny instans av[`Comparer`](../comparer) klass med källfilens sökväg och[`ComparerSettings`](../comparersettings) . |
| [Comparer](comparer#constructor_6)(string, LoadOptions) | Initierar ny instans av[`Comparer`](../comparer) med källfilens sökväg och[`LoadOptions`](../../groupdocs.comparison.options/loadoptions) . |
| [Comparer](comparer#constructor_3)(Stream, LoadOptions, ComparerSettings) | Initierar ny instans av[`Comparer`](../comparer) klass med dokumentström,[`LoadOptions`](../../groupdocs.comparison.options/loadoptions) och[`ComparerSettings`](../comparersettings) . |
| [Comparer](comparer#constructor_7)(string, LoadOptions, ComparerSettings) | Initierar ny instans av[`Comparer`](../comparer) klass med källfilssökväg,[`LoadOptions`](../../groupdocs.comparison.options/loadoptions) och[`ComparerSettings`](../comparersettings) . |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Source](../../groupdocs.comparison/comparer/source) { get; } | Källfil som jämförs. |
| [Targets](../../groupdocs.comparison/comparer/targets) { get; } | Lista över målfiler att jämföra med källfilen. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [Add](../../groupdocs.comparison/comparer/add#add)(Stream) | Lägger till dokumentström för jämförelse. |
| [Add](../../groupdocs.comparison/comparer/add#add_2)(string) | Lägger till fil för jämförelse. |
| [Add](../../groupdocs.comparison/comparer/add#add_1)(Stream, LoadOptions) | Lägger till dokumentström för jämförelse med angivna laddningsalternativ. |
| [Add](../../groupdocs.comparison/comparer/add#add_3)(string, LoadOptions) | Lägger till fil för jämförelse med angivna laddningsalternativ. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges)(Stream, ApplyChangeOptions) | Accepterar eller avvisar ändringar och tillämpar dem på resulterande dokument. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_2)(string, ApplyChangeOptions) | Accepterar eller avvisar ändringar och tillämpar dem på resulterande dokument. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_1)(Stream, SaveOptions, ApplyChangeOptions) | Accepterar eller avvisar ändringar och tillämpar dem på resulterande dokument. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_3)(string, SaveOptions, ApplyChangeOptions) | Accepterar eller avvisar ändringar och tillämpar dem på resulterande dokument. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare)() | Jämför dokument utan att spara resultatet med standardalternativ |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_1)(CompareOptions) | Jämför dokument utan att spara resultatet. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_3)(Stream) | Jämför dokument och sparar resultat till filen stream |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_7)(string) | Jämför dokument och sparar resultatet till filen path |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_2)(SaveOptions, CompareOptions) | Jämför dokument utan att spara resultatet. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_4)(Stream, CompareOptions) | Jämför dokument och sparar resultat till filen stream |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_5)(Stream, SaveOptions) | Jämför dokument och spara resultatet till filen stream |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_8)(string, CompareOptions) | Jämför dokument och sparar resultatet till filen path |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_9)(string, SaveOptions) | Jämför dokument och spara resultatet till filen path |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_6)(Stream, SaveOptions, CompareOptions) | Jämför dokument och sparar resultat i en ström. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_10)(string, SaveOptions, CompareOptions) | Jämför dokument och sparar resultatet till filen path |
| [Dispose](../../groupdocs.comparison/comparer/dispose)() | Frigör resurser. |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges)() | Hämtar lista över ändringar mellan käll- och målfil(er). |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges_1)(GetChangeOptions) | Hämtar lista över ändringar mellan käll- och målfil(er). |
| [GetResultString](../../groupdocs.comparison/comparer/getresultstring)() | Få resultatsträng efter jämförelse (endast för textjämförelse). |

### Se även

* namnutrymme [GroupDocs.Comparison](../../groupdocs.comparison)
* hopsättning [GroupDocs.Comparison](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Comparison.dll -->
