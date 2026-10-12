---
title: "ChangeInfo"
second_title: "GroupDocs.Comparison für .NET API-Referenz"
description: "Stellt Informationen über Änderungen dar."
type: docs
weight: 460
url: /de/net/groupdocs.comparison.result/changeinfo/
---
## ChangeInfo class

Stellt Informationen über Änderungen dar.

```csharp
public class ChangeInfo
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [ChangeInfo](changeinfo)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Authors](../../groupdocs.comparison.result/changeinfo/authors) { get; set; } | Liste der Autoren. |
| [Box](../../groupdocs.comparison.result/changeinfo/box) { get; set; } | Koordinaten des geänderten Elements. |
| [Column](../../groupdocs.comparison.result/changeinfo/column) { get; set; } | Nullbasierter Spaltenindex der geänderten Zelle. Wird für den Zellenvergleich (XLSX, CSV, ODS usw.) gefüllt, sonst null. |
| [ColumnHeader](../../groupdocs.comparison.result/changeinfo/columnheader) { get; set; } | Spaltenkopfzeilentext, der aus der ersten Zeile des Arbeitsblatts für die entsprechende Spalte entnommen wird. Wird für den Zellenvergleich gefüllt, wenn die erste Zeile Kopfzeilenwerte enthält, sonst null. |
| [ComparisonAction](../../groupdocs.comparison.result/changeinfo/comparisonaction) { get; set; } | Aktion (akzeptieren oder ablehnen). Dieses Feld gibt dem Vergleich an, was mit dieser Änderung zu tun ist. |
| [ComponentType](../../groupdocs.comparison.result/changeinfo/componenttype) { get; set; } | Typ der geänderten Komponente. |
| [Id](../../groupdocs.comparison.result/changeinfo/id) { get; set; } | ID der Änderung. |
| [PageInfo](../../groupdocs.comparison.result/changeinfo/pageinfo) { get; set; } | Seite, auf der die aktuelle Änderung platziert ist. |
| [Row](../../groupdocs.comparison.result/changeinfo/row) { get; set; } | Nullbasierter Zeilenindex der geänderten Zelle. Wird für den Zellenvergleich (XLSX, CSV, ODS usw.) gefüllt, sonst null. |
| [SourceText](../../groupdocs.comparison.result/changeinfo/sourcetext) { get; set; } | Geänderter Text des Quelldokuments. |
| [StyleChanges](../../groupdocs.comparison.result/changeinfo/stylechanges) { get; set; } | Array von Stiländerungen. |
| [TargetText](../../groupdocs.comparison.result/changeinfo/targettext) { get; set; } | Geänderter Text des Zieldokuments. |
| [Text](../../groupdocs.comparison.result/changeinfo/text) { get; set; } | Textwert der Änderung. |
| [Type](../../groupdocs.comparison.result/changeinfo/type) { get; } | Typ der Änderung. |

### Siehe auch

* namespace [GroupDocs.Comparison.Result](../../groupdocs.comparison.result)
* assembly [GroupDocs.Comparison](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.Comparison.dll -->
