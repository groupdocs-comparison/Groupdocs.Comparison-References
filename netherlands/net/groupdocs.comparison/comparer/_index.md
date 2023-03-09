---
title: Comparer
second_title: GroupDocs.Comparison voor .NET API-referentie
description: Vertegenwoordigt de hoofdklasse die het documentvergelijkingsproces regelt.
type: docs
weight: 100
url: /nl/net/groupdocs.comparison/comparer/
---
## Comparer class

Vertegenwoordigt de hoofdklasse die het documentvergelijkingsproces regelt.

```csharp
public class Comparer : IDisposable
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [Comparer](comparer#constructor)(Stream) | Initialiseert nieuw exemplaar van[`Comparer`](../comparer) klasse met brondocumentstroom. |
| [Comparer](comparer#constructor_4)(string) | Initialiseert nieuw exemplaar van[`Comparer`](../comparer) klasse met pad naar bronbestand. |
| [Comparer](comparer#constructor_1)(Stream, ComparerSettings) | Initialiseert nieuw exemplaar van[`Comparer`](../comparer)klasse met brondocumentstroom en[`ComparerSettings`](../comparersettings) . |
| [Comparer](comparer#constructor_2)(Stream, LoadOptions) | Initialiseert nieuw exemplaar van[`Comparer`](../comparer) met brondocumentstroom en[`LoadOptions`](../../groupdocs.comparison.options/loadoptions) . |
| [Comparer](comparer#constructor_5)(string, ComparerSettings) | Initialiseert nieuw exemplaar van[`Comparer`](../comparer) class met bronbestandspad en[`ComparerSettings`](../comparersettings) . |
| [Comparer](comparer#constructor_6)(string, LoadOptions) | Initialiseert nieuw exemplaar van[`Comparer`](../comparer) met bronbestandspad en[`LoadOptions`](../../groupdocs.comparison.options/loadoptions) . |
| [Comparer](comparer#constructor_3)(Stream, LoadOptions, ComparerSettings) | Initialiseert nieuw exemplaar van[`Comparer`](../comparer) klas met documentstroom,[`LoadOptions`](../../groupdocs.comparison.options/loadoptions) En[`ComparerSettings`](../comparersettings) . |
| [Comparer](comparer#constructor_7)(string, LoadOptions, ComparerSettings) | Initialiseert nieuw exemplaar van[`Comparer`](../comparer) klasse met bronbestandspad,[`LoadOptions`](../../groupdocs.comparison.options/loadoptions) En[`ComparerSettings`](../comparersettings) . |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Source](../../groupdocs.comparison/comparer/source) { get; } | Bronbestand dat wordt vergeleken. |
| [Targets](../../groupdocs.comparison/comparer/targets) { get; } | Lijst met doelbestanden om te vergelijken met bronbestand. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [Add](../../groupdocs.comparison/comparer/add#add)(Stream) | Voegt documentstroom toe aan vergelijking. |
| [Add](../../groupdocs.comparison/comparer/add#add_2)(string) | Voegt bestand toe aan vergelijking. |
| [Add](../../groupdocs.comparison/comparer/add#add_1)(Stream, LoadOptions) | Voegt documentstroom toe aan vergelijking met gespecificeerde laadopties. |
| [Add](../../groupdocs.comparison/comparer/add#add_3)(string, LoadOptions) | Voegt bestand toe aan vergelijking met opgegeven laadopties. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges)(Stream, ApplyChangeOptions) | Accepteert of verwerpt wijzigingen en past ze toe op het resulterende document. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_2)(string, ApplyChangeOptions) | Accepteert of verwerpt wijzigingen en past ze toe op het resulterende document. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_1)(Stream, SaveOptions, ApplyChangeOptions) | Accepteert of verwerpt wijzigingen en past ze toe op het resulterende document. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_3)(string, SaveOptions, ApplyChangeOptions) | Accepteert of verwerpt wijzigingen en past ze toe op het resulterende document. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare)() | Vergelijkt documenten zonder resultaat op te slaan met standaardopties |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_1)(CompareOptions) | Vergelijkt documenten zonder resultaat op te slaan. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_3)(Stream) | Vergelijkt documenten en slaat resultaat op in bestandsstroom |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_7)(string) | Vergelijkt documenten en slaat resultaat op in bestandspad |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_2)(SaveOptions, CompareOptions) | Vergelijkt documenten zonder resultaat op te slaan. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_4)(Stream, CompareOptions) | Vergelijkt documenten en slaat resultaat op in bestandsstroom |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_5)(Stream, SaveOptions) | Vergelijkt documenten en slaat resultaat op in bestandsstroom |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_8)(string, CompareOptions) | Vergelijkt documenten en slaat resultaat op in bestandspad |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_9)(string, SaveOptions) | Vergelijkt documenten en slaat resultaat op in bestandspad |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_6)(Stream, SaveOptions, CompareOptions) | Vergelijkt documenten en slaat resultaat op in een stream. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_10)(string, SaveOptions, CompareOptions) | Vergelijkt documenten en slaat resultaat op in bestandspad |
| [Dispose](../../groupdocs.comparison/comparer/dispose)() | Geeft bronnen vrij. |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges)() | Krijgt een lijst met wijzigingen tussen bron- en doelbestand(en). |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges_1)(GetChangeOptions) | Krijgt een lijst met wijzigingen tussen bron- en doelbestand(en). |
| [GetResultString](../../groupdocs.comparison/comparer/getresultstring)() | Krijg resultaatreeks na vergelijking (alleen voor tekstvergelijking). |

### Zie ook

* naamruimte [GroupDocs.Comparison](../../groupdocs.comparison)
* montage [GroupDocs.Comparison](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Comparison.dll -->
