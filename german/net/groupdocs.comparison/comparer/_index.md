---
title: "Vergleicher"
second_title: "GroupDocs.Comparison für .NET API-Referenz"
description: "Stellt die Hauptklasse dar, die den Vergleich von Dokumenten steuert."
type: docs
weight: 100
url: /de/net/groupdocs.comparison/comparer/
---
## Comparer class

Stellt die Hauptklasse dar, die den Vergleich von Dokumenten steuert.

```csharp
public sealed class Comparer : IDisposable
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Comparer](comparer#constructor)(Stream) | Initialisiert eine neue Instanz der Klasse [`Comparer`](../comparer) mit dem Quell-Dokument-Stream. |
| [Comparer](comparer#constructor_4)(string) | Initialisiert eine neue Instanz der Klasse [`Comparer`](../comparer) mit dem Quelldateipfad. |
| [Comparer](comparer#constructor_1)(Stream, ComparerSettings) | Initialisiert eine neue Instanz der Klasse [`Comparer`](../comparer) mit dem Quell-Dokument-Stream und [`ComparerSettings`](../comparersettings). |
| [Comparer](comparer#constructor_2)(Stream, LoadOptions) | Initialisiert eine neue Instanz von [`Comparer`](../comparer) mit dem Quell-Dokument-Stream und [`LoadOptions`](../../groupdocs.comparison.options/loadoptions). |
| [Comparer](comparer#constructor_6)(string, CompareOptions) | Initialisiert eine neue Instanz von [`Comparer`](../comparer) mit dem Quellordnerpfad und [`CompareOptions`](../../groupdocs.comparison.options/compareoptions). |
| [Comparer](comparer#constructor_5)(string, ComparerSettings) | Initialisiert eine neue Instanz der Klasse [`Comparer`](../comparer) mit dem Quelldateipfad und [`ComparerSettings`](../comparersettings). |
| [Comparer](comparer#constructor_7)(string, LoadOptions) | Initialisiert eine neue Instanz von [`Comparer`](../comparer) mit dem Quelldateipfad und [`LoadOptions`](../../groupdocs.comparison.options/loadoptions). |
| [Comparer](comparer#constructor_3)(Stream, LoadOptions, ComparerSettings) | Initialisiert eine neue Instanz der Klasse [`Comparer`](../comparer) mit Dokumenten-Stream, [`LoadOptions`](../../groupdocs.comparison.options/loadoptions) und [`ComparerSettings`](../comparersettings). |
| [Comparer](comparer#constructor_8)(string, LoadOptions, ComparerSettings) | Initialisiert eine neue Instanz der Klasse [`Comparer`](../comparer) mit dem Quelldateipfad, [`LoadOptions`](../../groupdocs.comparison.options/loadoptions) und [`ComparerSettings`](../comparersettings). |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Result](../../groupdocs.comparison/comparer/result) { get; } | Ergebnisdokument. |
| [Source](../../groupdocs.comparison/comparer/source) { get; } | Quelldatei, die verglichen wird. |
| [SourceFolder](../../groupdocs.comparison/comparer/sourcefolder) { get; } | Quellordner, der verglichen wird. |
| [TargetFolder](../../groupdocs.comparison/comparer/targetfolder) { get; set; } | Zielordner, der verglichen wird. |
| [Targets](../../groupdocs.comparison/comparer/targets) { get; } | Liste der Zieldateien, die mit der Quelldatei verglichen werden sollen. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Add](../../groupdocs.comparison/comparer/add#add)(Stream) | Fügt einen Dokumenten-Stream zum Vergleich hinzu. |
| [Add](../../groupdocs.comparison/comparer/add#add_2)(string) | Fügt eine Datei zum Vergleich hinzu. |
| [Add](../../groupdocs.comparison/comparer/add#add_1)(Stream, LoadOptions) | Fügt einen Dokumenten-Stream zum Vergleich hinzu, wobei Ladeoptionen angegeben sind. |
| [Add](../../groupdocs.comparison/comparer/add#add_3)(string, CompareOptions) | Fügt einen Ordner zum Vergleich hinzu. |
| [Add](../../groupdocs.comparison/comparer/add#add_4)(string, LoadOptions) | Fügt eine Datei zum Vergleich hinzu, wobei Ladeoptionen angegeben sind. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges)(Stream, ApplyChangeOptions) | Akzeptiert oder verwirft Änderungen und wendet sie auf das Ergebnisdokument an. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_2)(string, ApplyChangeOptions) | Akzeptiert oder verwirft Änderungen und wendet sie auf das Ergebnisdokument an. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_1)(Stream, SaveOptions, ApplyChangeOptions) | Akzeptiert oder verwirft Änderungen und wendet sie auf das Ergebnisdokument an. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_3)(string, SaveOptions, ApplyChangeOptions) | Akzeptiert oder verwirft Änderungen und wendet sie auf das Ergebnisdokument an. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare)() | Vergleicht Dokumente ohne das Ergebnis zu speichern mit den Standardoptionen |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_1)(CompareOptions) | Vergleicht Dokumente, ohne das Ergebnis zu speichern. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_3)(Stream) | Vergleicht Dokumente und speichert das Ergebnis in einen Dateistream |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_7)(string) | Vergleicht Dokumente und speichert das Ergebnis unter dem Dateipfad |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_2)(SaveOptions, CompareOptions) | Vergleicht Dokumente, ohne das Ergebnis zu speichern. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_4)(Stream, CompareOptions) | Vergleicht Dokumente und speichert das Ergebnis in einen Dateistream |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_5)(Stream, SaveOptions) | Vergleicht Dokumente und speichert das Ergebnis in einen Dateistream |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_8)(string, CompareOptions) | Vergleicht Dokumente und speichert das Ergebnis unter dem Dateipfad |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_9)(string, SaveOptions) | Vergleicht Dokumente und speichert das Ergebnis unter dem Dateipfad |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_6)(Stream, SaveOptions, CompareOptions) | Vergleicht Dokumente und speichert das Ergebnis in einen Stream. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_10)(string, SaveOptions, CompareOptions) | Vergleicht Dokumente und speichert das Ergebnis unter dem Dateipfad |
| [CompareDirectory](../../groupdocs.comparison/comparer/comparedirectory)(string, CompareOptions) | Vergleicht ein Verzeichnis und speichert das Ergebnis unter dem Dateipfad |
| [Dispose](../../groupdocs.comparison/comparer/dispose)() | Gibt Ressourcen frei. |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges)() | Ermittelt die Liste der Änderungen zwischen Quell‑ und Zieldatei(en). |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges_1)(ChangeType) | Ermittelt die Liste der Änderungen zwischen Quell‑ und Zieldatei(en). |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges_2)(GetChangeOptions) | Ermittelt die Liste der Änderungen zwischen Quell‑ und Zieldatei(en). |
| [GetResultDocumentStream](../../groupdocs.comparison/comparer/getresultdocumentstream)() | Ermittelt den Stream des Ergebnisdokuments, gibt null zurück, wenn der Stream nicht existiert |
| [GetResultString](../../groupdocs.comparison/comparer/getresultstring)() | Ergebniszeichenfolge nach dem Vergleich abrufen (nur für Textvergleich). |

### Siehe auch

* namespace [GroupDocs.Comparison](../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.Comparison.dll -->
