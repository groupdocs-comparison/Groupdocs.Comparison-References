---
title: "WordCompareOptions"
second_title: "GroupDocs.Comparison für .NET API-Referenz"
description: "Word-Dokument-spezifische Vergleichsoptionen. Erbt gemeinsame Optionen von CompareOptions./compareoptions."
type: docs
weight: 440
url: /de/net/groupdocs.comparison.options/wordcompareoptions/
---
## WordCompareOptions class

Word-Dokument-spezifische Vergleichsoptionen. Erbt gemeinsame Optionen von [`CompareOptions`](../compareoptions).

```csharp
public class WordCompareOptions : CompareOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [WordCompareOptions](wordcompareoptions)() | Initialisiert eine neue Instanz der [`WordCompareOptions`](../wordcompareoptions)-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CalculateCoordinates](../../groupdocs.comparison.options/compareoptions/calculatecoordinates) { get; set; } | Gibt an, ob Koordinaten für geänderte Komponenten berechnet werden sollen. |
| [CalculateCoordinatesMode](../../groupdocs.comparison.options/compareoptions/calculatecoordinatesmode) { get; set; } | Legt den Modus zur Koordinatenberechnung für geänderte Komponenten fest. |
| [ChangedItemStyle](../../groupdocs.comparison.options/compareoptions/changeditemstyle) { get; set; } | Beschreibt den Stil für geänderte Komponenten. |
| [CompareBookmarks](../../groupdocs.comparison.options/wordcompareoptions/comparebookmarks) { get; set; } | Liest oder setzt, ob Lesezeichen in den Quell- und Zieldokumenten verglichen und Unterschiede im Ergebnis enthalten werden. |
| [CompareDocumentProperty](../../groupdocs.comparison.options/wordcompareoptions/comparedocumentproperty) { get; set; } | Liest oder setzt, ob integrierte und benutzerdefinierte Dokumenteigenschaften verglichen und Unterschiede im Ergebnis enthalten werden (z. B. auf der Zusammenfassungsseite der Eigenschaften). |
| [CompareVariableProperty](../../groupdocs.comparison.options/wordcompareoptions/comparevariableproperty) { get; set; } | Liest oder setzt, ob Dokumentvariableneigenschaften (z. B. DOCVARIABLE-Felder) verglichen und Unterschiede im Ergebnis enthalten werden. |
| [DeletedItemStyle](../../groupdocs.comparison.options/compareoptions/deleteditemstyle) { get; set; } | Beschreibt den Stil für gelöschte Komponenten. |
| [DetalisationLevel](../../groupdocs.comparison.options/compareoptions/detalisationlevel) { get; set; } | Liest oder setzt die Detailstufe des Vergleichs. |
| [DetectStyleChanges](../../groupdocs.comparison.options/compareoptions/detectstylechanges) { get; set; } | Gibt an, ob Stiländerungen erkannt werden sollen oder nicht. |
| [DiagramMasterSetting](../../groupdocs.comparison.options/compareoptions/diagrammastersetting) { get; set; } | Liest oder setzt den Pfadwert für das Master‑Element oder verwendet den Vergleich ohne Pfad des Masters. Diese Option gilt nur für Diagramme. |
| [DirectoryCompare](../../groupdocs.comparison.options/compareoptions/directorycompare) { get; set; } | Steuerung zum Aktivieren des Ordnervergleichs. |
| [DisplayMode](../../groupdocs.comparison.options/wordcompareoptions/displaymode) { get; set; } | Liest oder setzt, wie Vergleichsergebnisse angezeigt werden: als Word‑Revisionen im Änderungsnachverfolgungs‑Modus (Revisions) oder als hervorgehobene Änderungen, die direkt in das Dokument eingefügt werden (Highlight). |
| [ExtendedSummaryPage](../../groupdocs.comparison.options/compareoptions/extendedsummarypage) { get; set; } | Gibt an, ob erweiterte Dateivergleichsinformationen zur Übersichtsseite hinzugefügt werden sollen oder nicht. |
| [FolderComparisonExtension](../../groupdocs.comparison.options/compareoptions/foldercomparisonextension) { get; set; } | Liest oder setzt das Format der resultierenden Ordnervergleichsdatei. |
| [GenerateSummaryPage](../../groupdocs.comparison.options/compareoptions/generatesummarypage) { get; set; } | Gibt an, ob eine Übersichtsseite mit Statistiken zu erkannten Änderungen zum Ergebnisdokument hinzugefügt werden soll oder nicht. |
| [HeaderFootersComparison](../../groupdocs.comparison.options/compareoptions/headerfooterscomparison) { get; set; } | Steuerung zum Aktivieren des Vergleichs von Kopf‑/Fußzeileninhalten. |
| [IgnoreChangeSettings](../../groupdocs.comparison.options/compareoptions/ignorechangesettings) { get; set; } | Liest oder setzt Einstellungen, um Änderungen basierend auf Ähnlichkeit zu ignorieren. |
| [InsertedItemStyle](../../groupdocs.comparison.options/compareoptions/inserteditemstyle) { get; set; } | Beschreibt den Stil für eingefügte Komponenten. |
| [LeaveGaps](../../groupdocs.comparison.options/wordcompareoptions/leavegaps) { get; set; } | Liest oder setzt, ob leere Zeilen anstelle von eingefügtem oder gelöschtem Inhalt belassen werden, um Layout und Zeilenzahl beizubehalten; verwendet mit [`ShowInsertedContent`](../compareoptions/showinsertedcontent) und [`ShowDeletedContent`](../compareoptions/showdeletedcontent). |
| [MarkChangedContent](../../groupdocs.comparison.options/compareoptions/markchangedcontent) { get; set; } | Gibt an, ob Rahmen für Formen in der Textverarbeitung und für Rechtecke in Bilddokumenten verwendet werden sollen. |
| [MarkLineBreaks](../../groupdocs.comparison.options/wordcompareoptions/marklinebreaks) { get; set; } | Liest oder setzt, ob Absatz‑ (Zeilen‑)Umbrüche, die zwischen Dokumenten unterschiedlich sind, im Ergebnis optisch markiert werden. |
| [MarkNestedContent](../../groupdocs.comparison.options/compareoptions/marknestedcontent) { get; set; } | Liest oder setzt einen Wert, der angibt, ob die untergeordneten Elemente des gelöschten oder eingefügten Elements als gelöscht oder eingefügt markiert werden sollen. |
| [OriginalSize](../../groupdocs.comparison.options/compareoptions/originalsize) { get; set; } | Liest oder setzt die Originalgrößen der verglichenen Dokumente. |
| [PaperSize](../../groupdocs.comparison.options/compareoptions/papersize) { get; set; } | Liest oder setzt die Papiergröße des Ergebnisdokuments. |
| [PasswordSaveOption](../../groupdocs.comparison.options/compareoptions/passwordsaveoption) { get; set; } | Liest oder setzt die Option zum Speichern des Passworts. |
| [RevisionAuthorName](../../groupdocs.comparison.options/wordcompareoptions/revisionauthorname) { get; set; } | Liest oder setzt den Autorennamen, der für Revisionen verwendet wird, wenn !:WordTrackChanges aktiviert ist. Wenn festgelegt, wird dieser Name auf die Revisionsmarkierungen im Ergebnisdokument angewendet. |
| [SensitivityOfComparison](../../groupdocs.comparison.options/compareoptions/sensitivityofcomparison) { get; set; } | Liest oder setzt die Empfindlichkeit des Vergleichs. |
| [SensitivityOfComparisonForTables](../../groupdocs.comparison.options/compareoptions/sensitivityofcomparisonfortables) { get; set; } | Liest oder setzt die Empfindlichkeit des Vergleichs für Tabellen. |
| [ShowDeletedContent](../../groupdocs.comparison.options/compareoptions/showdeletedcontent) { get; set; } | Gibt an, ob gelöschte Komponenten im Ergebnisdokument angezeigt werden sollen oder nicht. |
| [ShowInsertedContent](../../groupdocs.comparison.options/compareoptions/showinsertedcontent) { get; set; } | Gibt an, ob eingefügte Komponenten im Ergebnisdokument angezeigt werden sollen oder nicht. |
| [ShowOnlyChanged](../../groupdocs.comparison.options/compareoptions/showonlychanged) { get; set; } | Steuerungen, um die Anzeige nur geänderter Elemente zu aktivieren. |
| [ShowOnlySummaryPage](../../groupdocs.comparison.options/compareoptions/showonlysummarypage) { get; set; } | Gibt an, ob im Ergebnisdokument nur eine Seite mit Statistiken zu den erkannten Änderungen belassen werden soll oder nicht. |
| [ShowRevisions](../../groupdocs.comparison.options/wordcompareoptions/showrevisions) { get; set; } | Liest oder setzt, ob das Ergebnisdokument die Revisionsmarkierung sichtbar hält. Wenn false, werden alle Revisionen akzeptiert und das Ergebnis erscheint als endgültiger Text. Diese Einstellung ist nur sinnvoll, wenn [`DisplayMode`](./displaymode) auf Highlight gesetzt ist. Der Standardwert ist true. |
| [UserMasterPath](../../groupdocs.comparison.options/compareoptions/usermasterpath) { get; set; } | Pfad zur Mastervorlage des Benutzers für Diagramme. |
| [WordsSeparatorChars](../../groupdocs.comparison.options/compareoptions/wordsseparatorchars) { set; } | Liest oder setzt ein Array von Trennzeichen, um Text in Wörter zu splitten. |

### Siehe auch

* class [CompareOptions](../compareoptions)
* namespace [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.Comparison.dll -->
