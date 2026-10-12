---
title: "PdfCompareOptions.ComparisonDisplayMode"
second_title: "GroupDocs.Comparison pour .NET API Reference"
description: "Contrôle la disposition du document résultat de la comparaison PDF."
type: docs
weight: 370
url: /fr/net/groupdocs.comparison.options/pdfcompareoptions.comparisondisplaymode/
---
## PdfCompareOptions.ComparisonDisplayMode enumeration

Contrôle la disposition du document résultat de la comparaison PDF.

```csharp
public enum ComparisonDisplayMode
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Inline | `0` | Mode par défaut. Produit un seul document PDF fusionné où le contenu supprimé est mis en évidence dans une couleur et le contenu inséré dans une autre. Le contenu source et cible coexistent sur les mêmes pages, ce qui peut entraîner un chevauchement lorsque les documents diffèrent de manière significative. |
| SideBySide | `1` | Chaque page de résultat affiche une page source et sa page cible correspondante côte à côte. Les suppressions apparaissent à gauche (côté source) et les insertions à droite (côté cible). Le contenu des deux documents ne se chevauche jamais, ce qui rend ce mode adapté lorsque les documents diffèrent fortement. |
| Interleaved | `2` | Produit un document avec des pages alternées : les pages impaires proviennent du document source (affichant les suppressions) et les pages paires proviennent du document cible (affichant les insertions). Ouvrez le résultat dans un visualiseur PDF avec la vue "Two Page View" activée pour voir chaque paire source/cible côte à côte à l’écran. Comme SideBySide, ce mode empêche le chevauchement du contenu et convient le mieux aux documents très différents. |

### Voir aussi

* class [PdfCompareOptions](../pdfcompareoptions)
* namespace [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Comparison.dll -->
