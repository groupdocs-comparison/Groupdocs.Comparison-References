---
title: "SensitivityOfComparison"
second_title: "GroupDocs.Comparison pour .NET API Reference"
description: "Obtient ou définit une sensibilité de la comparaison."
type: docs
weight: 210
url: /fr/net/groupdocs.comparison.options/compareoptions/sensitivityofcomparison/
---
## CompareOptions.SensitivityOfComparison property

Obtient ou définit une sensibilité de la comparaison.

```csharp
public int SensitivityOfComparison { get; set; }
```

### Property Value

Le pourcentage d'éléments supprimés et insérés de deux objets comparés par rapport à l'ensemble des éléments de ces objets. si ce pourcentage est dépassé, l'objet n'est pas comparé mais est considéré comme entièrement inséré et supprimé. Valeur minimale - 0% => La comparaison ne se produit pas pour aucune longueur de la sous‑séquence commune de deux objets comparés. Valeur par défaut - 75% => La comparaison se produit si le pourcentage d'éléments supprimés et insérés de deux objets comparés par rapport à l'ensemble des éléments de ces objets n'est pas supérieur à 75. Valeur maximale - 100% => La comparaison se produit pour n'importe quelle longueur de la sous‑séquence commune de deux objets comparés.

### Voir aussi

* class [CompareOptions](../../compareoptions)
* namespace [GroupDocs.Comparison.Options](../../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Comparison.dll -->
