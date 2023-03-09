---
title: Comparer
second_title: GroupDocs.Comparison für .NET-API-Referenz
description: Stellt die Hauptklasse dar die den Dokumentenvergleichsprozess steuert.
type: docs
weight: 100
url: /de/net/groupdocs.comparison/comparer/
---
## Comparer class

Stellt die Hauptklasse dar, die den Dokumentenvergleichsprozess steuert.

```csharp
public class Comparer : IDisposable
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [Comparer](comparer#constructor)(Stream) | Initialisiert eine neue Instanz von[`Comparer`](../comparer) Klasse mit Quelldokumentstream. |
| [Comparer](comparer#constructor_4)(string) | Initialisiert eine neue Instanz von[`Comparer`](../comparer) Klasse mit Quelldateipfad. |
| [Comparer](comparer#constructor_1)(Stream, ComparerSettings) | Initialisiert eine neue Instanz von[`Comparer`](../comparer)Klasse mit Quelldokumentstrom und[`ComparerSettings`](../comparersettings) . |
| [Comparer](comparer#constructor_2)(Stream, LoadOptions) | Initialisiert eine neue Instanz von[`Comparer`](../comparer) mit Quelldokumentstrom und[`LoadOptions`](../../groupdocs.comparison.options/loadoptions) . |
| [Comparer](comparer#constructor_5)(string, ComparerSettings) | Initialisiert eine neue Instanz von[`Comparer`](../comparer) Klasse mit Quelldateipfad und[`ComparerSettings`](../comparersettings) . |
| [Comparer](comparer#constructor_6)(string, LoadOptions) | Initialisiert eine neue Instanz von[`Comparer`](../comparer) mit Quelldateipfad und[`LoadOptions`](../../groupdocs.comparison.options/loadoptions) . |
| [Comparer](comparer#constructor_3)(Stream, LoadOptions, ComparerSettings) | Initialisiert eine neue Instanz von[`Comparer`](../comparer) Klasse mit Dokumentenstrom,[`LoadOptions`](../../groupdocs.comparison.options/loadoptions) Und[`ComparerSettings`](../comparersettings) . |
| [Comparer](comparer#constructor_7)(string, LoadOptions, ComparerSettings) | Initialisiert eine neue Instanz von[`Comparer`](../comparer) Klasse mit Quelldateipfad,[`LoadOptions`](../../groupdocs.comparison.options/loadoptions) Und[`ComparerSettings`](../comparersettings) . |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Source](../../groupdocs.comparison/comparer/source) { get; } | Quelldatei, die verglichen wird. |
| [Targets](../../groupdocs.comparison/comparer/targets) { get; } | Liste der Zieldateien, die mit der Quelldatei verglichen werden sollen. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Add](../../groupdocs.comparison/comparer/add#add)(Stream) | Fügt den Dokumentenstream zum Vergleich hinzu. |
| [Add](../../groupdocs.comparison/comparer/add#add_2)(string) | Fügt Datei zum Vergleich hinzu. |
| [Add](../../groupdocs.comparison/comparer/add#add_1)(Stream, LoadOptions) | Fügt den Dokumentenstrom zum Vergleich mit den angegebenen Ladeoptionen hinzu. |
| [Add](../../groupdocs.comparison/comparer/add#add_3)(string, LoadOptions) | Fügt Datei zum Vergleich mit angegebenen Ladeoptionen hinzu. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges)(Stream, ApplyChangeOptions) | Akzeptiert oder lehnt Änderungen ab und wendet sie auf das resultierende Dokument an. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_2)(string, ApplyChangeOptions) | Akzeptiert oder lehnt Änderungen ab und wendet sie auf das resultierende Dokument an. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_1)(Stream, SaveOptions, ApplyChangeOptions) | Akzeptiert oder lehnt Änderungen ab und wendet sie auf das resultierende Dokument an. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_3)(string, SaveOptions, ApplyChangeOptions) | Akzeptiert oder lehnt Änderungen ab und wendet sie auf das resultierende Dokument an. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare)() | Vergleicht Dokumente ohne Ergebnis mit Standardoptionen zu speichern |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_1)(CompareOptions) | Vergleicht Dokumente ohne Ergebnis zu speichern. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_3)(Stream) | Vergleicht Dokumente und speichert Ergebnis in Datei stream |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_7)(string) | Vergleicht Dokumente und speichert Ergebnis im Dateipfad |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_2)(SaveOptions, CompareOptions) | Vergleicht Dokumente ohne Ergebnis zu speichern. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_4)(Stream, CompareOptions) | Vergleicht Dokumente und speichert Ergebnis in Datei stream |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_5)(Stream, SaveOptions) | Vergleicht Dokumente und speichert Ergebnis in Datei stream |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_8)(string, CompareOptions) | Vergleicht Dokumente und speichert Ergebnis im Dateipfad |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_9)(string, SaveOptions) | Vergleicht Dokumente und speichert Ergebnis im Dateipfad |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_6)(Stream, SaveOptions, CompareOptions) | Vergleicht Dokumente und speichert das Ergebnis in einem Stream. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_10)(string, SaveOptions, CompareOptions) | Vergleicht Dokumente und speichert Ergebnis im Dateipfad |
| [Dispose](../../groupdocs.comparison/comparer/dispose)() | Gibt Ressourcen frei. |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges)() | Ruft eine Liste der Änderungen zwischen Quell- und Zieldatei(en) ab. |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges_1)(GetChangeOptions) | Ruft eine Liste der Änderungen zwischen Quell- und Zieldatei(en) ab. |
| [GetResultString](../../groupdocs.comparison/comparer/getresultstring)() | Ergebnisstring nach Vergleich abrufen (nur für Textvergleich). |

### Siehe auch

* namensraum [GroupDocs.Comparison](../../groupdocs.comparison)
* Montage [GroupDocs.Comparison](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Comparison.dll -->
