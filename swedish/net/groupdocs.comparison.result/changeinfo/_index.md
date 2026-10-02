---
title: "ChangeInfo"
second_title: "GroupDocs.Comparison för .NET API-referens"
description: "Representerar information om ändring."
type: docs
weight: 460
url: /sv/net/groupdocs.comparison.result/changeinfo/
---
## ChangeInfo class

Representerar information om ändring.

```csharp
public class ChangeInfo
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ChangeInfo](changeinfo)() | Standardkonstruktören. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Authors](../../groupdocs.comparison.result/changeinfo/authors) { get; set; } | Lista över författare. |
| [Box](../../groupdocs.comparison.result/changeinfo/box) { get; set; } | Koordinater för ändrat element. |
| [Column](../../groupdocs.comparison.result/changeinfo/column) { get; set; } | Nollbaserat kolumnindex för den ändrade cellen. Fylls i för Cells-jämförare (XLSX, CSV, ODS, etc.), annars null. |
| [ColumnHeader](../../groupdocs.comparison.result/changeinfo/columnheader) { get; set; } | Kolumnrubriktext hämtad från det första raden i kalkylbladet för motsvarande kolumn. Fylls i för Cells-jämförare när den första raden innehåller rubrikvärden, annars null. |
| [ComparisonAction](../../groupdocs.comparison.result/changeinfo/comparisonaction) { get; set; } | Åtgärd (acceptera eller avvisa). Detta fält talar om för jämförelsen vad som ska göras med denna ändring. |
| [ComponentType](../../groupdocs.comparison.result/changeinfo/componenttype) { get; set; } | Typ av ändrad komponent. |
| [Id](../../groupdocs.comparison.result/changeinfo/id) { get; set; } | Id för ändring. |
| [PageInfo](../../groupdocs.comparison.result/changeinfo/pageinfo) { get; set; } | Sida där den aktuella ändringen är placerad. |
| [Row](../../groupdocs.comparison.result/changeinfo/row) { get; set; } | Nollbaserat radindex för den ändrade cellen. Fylls i för Cells-jämförare (XLSX, CSV, ODS, etc.), annars null. |
| [SourceText](../../groupdocs.comparison.result/changeinfo/sourcetext) { get; set; } | Ändrad text i källdokumentet. |
| [StyleChanges](../../groupdocs.comparison.result/changeinfo/stylechanges) { get; set; } | Array av stiländringar. |
| [TargetText](../../groupdocs.comparison.result/changeinfo/targettext) { get; set; } | Ändrad text i måldokumentet. |
| [Text](../../groupdocs.comparison.result/changeinfo/text) { get; set; } | Textvärde för ändring. |
| [Type](../../groupdocs.comparison.result/changeinfo/type) { get; } | Typ av ändring. |

### Se även

* namespace [GroupDocs.Comparison.Result](../../groupdocs.comparison.result)
* assembly [GroupDocs.Comparison](../../)

<!-- DO NOT EDIT: genererad av xmldocmd för GroupDocs.Comparison.dll -->
