---
title: "Comparer"
second_title: "GroupDocs.Comparison for .NET API-referentie"
description: "Stelt de hoofdklasse voor die het documentvergelijkingsproces beheert."
type: docs
weight: 100
url: /nl/net/groupdocs.comparison/comparer/
---
## Comparer class

Stelt de hoofdklasse voor die het documentvergelijkingsproces beheert.

```csharp
public sealed class Comparer : IDisposable
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [Comparer](comparer#constructor)(Stream) | Initialiseert een nieuw exemplaar van de [`Comparer`](../comparer) klasse met bron-documentstroom. |
| [Comparer](comparer#constructor_4)(string) | Initialiseert een nieuw exemplaar van de [`Comparer`](../comparer) klasse met bron-bestandspad. |
| [Comparer](comparer#constructor_1)(Stream, ComparerSettings) | Initialiseert een nieuw exemplaar van de [`Comparer`](../comparer) klasse met bron-documentstroom en [`ComparerSettings`](../comparersettings). |
| [Comparer](comparer#constructor_2)(Stream, LoadOptions) | Initialiseert een nieuw exemplaar van de [`Comparer`](../comparer) met bron-documentstroom en [`LoadOptions`](../../groupdocs.comparison.options/loadoptions). |
| [Comparer](comparer#constructor_6)(string, CompareOptions) | Initialiseert een nieuw exemplaar van de [`Comparer`](../comparer) met bron-mappad en [`CompareOptions`](../../groupdocs.comparison.options/compareoptions). |
| [Comparer](comparer#constructor_5)(string, ComparerSettings) | Initialiseert een nieuw exemplaar van de [`Comparer`](../comparer) klasse met bron-bestandspad en [`ComparerSettings`](../comparersettings). |
| [Comparer](comparer#constructor_7)(string, LoadOptions) | Initialiseert een nieuw exemplaar van [`Comparer`](../comparer) met het bronbestandspad en [`LoadOptions`](../../groupdocs.comparison.options/loadoptions). |
| [Comparer](comparer#constructor_3)(Stream, LoadOptions, ComparerSettings) | Initialiseert een nieuw exemplaar van de [`Comparer`](../comparer) klasse met een documentstroom, [`LoadOptions`](../../groupdocs.comparison.options/loadoptions) en [`ComparerSettings`](../comparersettings). |
| [Comparer](comparer#constructor_8)(string, LoadOptions, ComparerSettings) | Initialiseert een nieuw exemplaar van de [`Comparer`](../comparer) klasse met het bronbestandspad, [`LoadOptions`](../../groupdocs.comparison.options/loadoptions) en [`ComparerSettings`](../comparersettings). |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Result](../../groupdocs.comparison/comparer/result) { get; } | Resultaatdocument. |
| [Source](../../groupdocs.comparison/comparer/source) { get; } | Bronbestand dat wordt vergeleken. |
| [SourceFolder](../../groupdocs.comparison/comparer/sourcefolder) { get; } | Bronmap die wordt vergeleken. |
| [TargetFolder](../../groupdocs.comparison/comparer/targetfolder) { get; set; } | Doelmap die wordt vergeleken. |
| [Targets](../../groupdocs.comparison/comparer/targets) { get; } | Lijst van doelbestanden om te vergelijken met het bronbestand. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Add](../../groupdocs.comparison/comparer/add#add)(Stream) | Voegt een documentstroom toe aan de vergelijking. |
| [Add](../../groupdocs.comparison/comparer/add#add_2)(string) | Voegt een bestand toe aan de vergelijking. |
| [Add](../../groupdocs.comparison/comparer/add#add_1)(Stream, LoadOptions) | Voegt een documentstroom toe aan de vergelijking met opgegeven laadopties. |
| [Add](../../groupdocs.comparison/comparer/add#add_3)(string, CompareOptions) | Voegt een map toe aan de vergelijking. |
| [Add](../../groupdocs.comparison/comparer/add#add_4)(string, LoadOptions) | Voegt een bestand toe aan de vergelijking met opgegeven laadopties. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges)(Stream, ApplyChangeOptions) | Accepteert of wijst wijzigingen af en past ze toe op het resulterende document. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_2)(string, ApplyChangeOptions) | Accepteert of wijst wijzigingen af en past ze toe op het resulterende document. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_1)(Stream, SaveOptions, ApplyChangeOptions) | Accepteert of wijst wijzigingen af en past ze toe op het resulterende document. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_3)(string, SaveOptions, ApplyChangeOptions) | Accepteert of wijst wijzigingen af en past ze toe op het resulterende document. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare)() | Vergelijkt documenten zonder het resultaat op te slaan met standaardopties |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_1)(CompareOptions) | Vergelijkt documenten zonder het resultaat op te slaan. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_3)(Stream) | Vergelijkt documenten en slaat het resultaat op naar een bestandsstroom |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_7)(string) | Vergelijkt documenten en slaat het resultaat op naar een bestandspad |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_2)(SaveOptions, CompareOptions) | Vergelijkt documenten zonder het resultaat op te slaan. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_4)(Stream, CompareOptions) | Vergelijkt documenten en slaat het resultaat op naar een bestandsstroom |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_5)(Stream, SaveOptions) | Vergelijkt documenten en slaat het resultaat op naar een bestandsstroom |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_8)(string, CompareOptions) | Vergelijkt documenten en slaat het resultaat op naar een bestandspad |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_9)(string, SaveOptions) | Vergelijkt documenten en slaat het resultaat op naar een bestandspad |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_6)(Stream, SaveOptions, CompareOptions) | Vergelijkt documenten en slaat het resultaat op naar een stroom. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_10)(string, SaveOptions, CompareOptions) | Vergelijkt documenten en slaat het resultaat op naar een bestandspad |
| [CompareDirectory](../../groupdocs.comparison/comparer/comparedirectory)(string, CompareOptions) | Vergelijkt een map en slaat het resultaat op naar een bestandspad |
| [Dispose](../../groupdocs.comparison/comparer/dispose)() | Geeft bronnen vrij. |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges)() | Haalt de lijst met wijzigingen op tussen bron- en doelbestand(en). |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges_1)(ChangeType) | Haalt de lijst met wijzigingen op tussen bron- en doelbestand(en). |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges_2)(GetChangeOptions) | Haalt de lijst met wijzigingen op tussen bron- en doelbestand(en). |
| [GetResultDocumentStream](../../groupdocs.comparison/comparer/getresultdocumentstream)() | Haalt de stroom van het resultaatdocument op, retourneert null als de stroom niet bestaat |
| [GetResultString](../../groupdocs.comparison/comparer/getresultstring)() | Resultaatstring ophalen na vergelijking (alleen voor tekstvergelijking). |

### Zie ook

* namespace [GroupDocs.Comparison](../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Comparison.dll -->
