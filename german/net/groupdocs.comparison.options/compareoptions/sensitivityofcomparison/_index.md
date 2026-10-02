---
title: "SensitivityOfComparison"
second_title: "GroupDocs.Comparison für .NET API-Referenz"
description: "Liest oder setzt die Empfindlichkeit des Vergleichs."
type: docs
weight: 210
url: /de/net/groupdocs.comparison.options/compareoptions/sensitivityofcomparison/
---
## CompareOptions.SensitivityOfComparison property

Liest oder setzt die Empfindlichkeit des Vergleichs.

```csharp
public int SensitivityOfComparison { get; set; }
```

### Property Value

Der Prozentsatz gelöschter und eingefügter Elemente zweier verglichener Objekte in Relation zu allen Elementen dieser Objekte. Wenn dieser Prozentsatz überschritten wird, werden die Objekte nicht verglichen, sondern als vollständig eingefügt und gelöscht betrachtet. Minimalwert - 0% => Der Vergleich findet für keine Länge der gemeinsamen Teilsequenz von zwei verglichenen Objekten statt. Standardwert - 75% => Der Vergleich erfolgt, wenn der Prozentsatz gelöschter und eingefügter Elemente von zwei verglichenen Objekten in Bezug auf alle Elemente dieser Objekte nicht mehr als 75 beträgt. Maximalwert - 100% => Der Vergleich findet bei jeder Länge der gemeinsamen Teilsequenz von zwei verglichenen Objekten statt.

### Siehe auch

* class [CompareOptions](../../compareoptions)
* namespace [GroupDocs.Comparison.Options](../../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.Comparison.dll -->
