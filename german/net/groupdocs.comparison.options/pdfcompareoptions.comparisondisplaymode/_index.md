---
title: "PdfCompareOptions.ComparisonDisplayMode"
second_title: "GroupDocs.Comparison für .NET API-Referenz"
description: "Steuert, wie das PDF-Vergleichsergebnisdokument angeordnet ist."
type: docs
weight: 370
url: /de/net/groupdocs.comparison.options/pdfcompareoptions.comparisondisplaymode/
---
## PdfCompareOptions.ComparisonDisplayMode enumeration

Steuert, wie das PDF-Vergleichsergebnisdokument angeordnet ist.

```csharp
public enum ComparisonDisplayMode
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Inline | `0` | Standardmodus. Erstellt ein einzelnes zusammengeführtes PDF-Dokument, bei dem gelöschter Inhalt in einer Farbe und eingefügter Inhalt in einer anderen Farbe hervorgehoben wird. Sowohl Quell- als auch Zielinhalt existieren auf denselben Seiten, was bei stark unterschiedlichen Dokumenten zu Überlappungen führen kann. |
| SideBySide | `1` | Jede Ergebnisseite zeigt eine Quellseite und die entsprechende Zielseite nebeneinander. Löschungen erscheinen links (Quellseite) und Einfügungen rechts (Zielseite). Inhalte aus den beiden Dokumenten überschneiden sich nie, wodurch dieser Modus geeignet ist, wenn die Dokumente stark voneinander abweichen. |
| Interleaved | `2` | Erstellt ein Dokument mit wechselnden Seiten: Ungerade Seiten stammen aus dem Quelldokument (zeigen Löschungen) und gerade Seiten aus dem Zieldokument (zeigen Einfügungen). Öffnen Sie das Ergebnis in einem PDF‑Betrachter mit aktivierter "Two Page View", um jedes Quell‑/Ziel‑Paar nebeneinander auf dem Bildschirm zu sehen. Wie SideBySide verhindert dieser Modus Inhaltsüberlappungen und eignet sich am besten für stark unterschiedliche Dokumente. |

### Siehe auch

* class [PdfCompareOptions](../pdfcompareoptions)
* namespace [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.Comparison.dll -->
