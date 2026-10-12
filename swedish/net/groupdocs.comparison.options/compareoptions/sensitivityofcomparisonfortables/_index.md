---
title: "SensitivityOfComparisonForTables"
second_title: "GroupDocs.Comparison för .NET API-referens"
description: "Hämtar eller anger en känslighet för jämförelse av tabeller."
type: docs
weight: 220
url: /sv/net/groupdocs.comparison.options/compareoptions/sensitivityofcomparisonfortables/
---
## CompareOptions.SensitivityOfComparisonForTables property

Hämtar eller anger en känslighet för jämförelse av tabeller.

```csharp
public int? SensitivityOfComparisonForTables { get; set; }
```

### Property Value

Om värdet är null används SensitivityOfComparison istället. Procentandelen av borttagna och infogade element i två jämförda objekt i förhållande till alla element i dessa objekt. Om denna procentandel överskrids jämförs inte objektet utan det betraktas som helt infogat och borttaget. Minvärde - 0% => Jämförelsen sker inte för någon längd av den gemensamma delsekvensen för två jämförda objekt. Standardvärde - 75% => Jämförelsen sker om procentandelen av borttagna och infogade element i två jämförda objekt i förhållande till alla element i dessa objekt inte är mer än 75. Maxvärde - 100% => Jämförelsen sker för vilken längd som helst av den gemensamma delsekvensen för två jämförda objekt.

### Se även

* class [CompareOptions](../../compareoptions)
* namespace [GroupDocs.Comparison.Options](../../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../../)

<!-- DO NOT EDIT: genererad av xmldocmd för GroupDocs.Comparison.dll -->
