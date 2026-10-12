---
title: "DetalisationLevel"
second_title: "GroupDocs.Comparison für .NET API-Referenz"
description: "Gibt das Detailniveau des Vergleichs an."
type: docs
weight: 230
url: /de/net/groupdocs.comparison.options/detalisationlevel/
---
## DetalisationLevel enumeration

Gibt das Detailniveau des Vergleichs an.

```csharp
public enum DetalisationLevel
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Low | `0` | Niedriges Niveau. Bietet den besten Geschwindigkeitsvergleich, opfert jedoch die Vergleichsqualität. Der Vergleich wird pro Wort durchgeführt. |
| Middle | `1` | Mittleres Niveau. Ein vernünftiger Kompromiss zwischen Vergleichsgeschwindigkeit und -qualität. Der Vergleich wird pro Zeichen durchgeführt, wobei Groß-/Kleinschreibung und Leerzeichen ignoriert werden. |
| High | `2` | Hohes Niveau. Die beste Vergleichsqualität, aber die niedrigste Geschwindigkeit. Der Vergleich wird pro Zeichen durchgeführt und berücksichtigt Groß-/Kleinschreibung sowie Leerzeichen. |

### Siehe auch

* namespace [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.Comparison.dll -->
