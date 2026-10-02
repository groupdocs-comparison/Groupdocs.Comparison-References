---
title: "ChangeInfo"
second_title: "GroupDocs.Comparison pour .NET API Reference"
description: "Représente des informations sur le changement."
type: docs
weight: 460
url: /fr/net/groupdocs.comparison.result/changeinfo/
---
## ChangeInfo class

Représente des informations sur le changement.

```csharp
public class ChangeInfo
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ChangeInfo](changeinfo)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Authors](../../groupdocs.comparison.result/changeinfo/authors) { get; set; } | Liste des auteurs. |
| [Box](../../groupdocs.comparison.result/changeinfo/box) { get; set; } | Coordonnées de l'élément modifié. |
| [Column](../../groupdocs.comparison.result/changeinfo/column) { get; set; } | Indice de colonne basé sur zéro de la cellule modifiée. Rempli pour le comparateur de cellules (XLSX, CSV, ODS, etc.), sinon nul. |
| [ColumnHeader](../../groupdocs.comparison.result/changeinfo/columnheader) { get; set; } | Texte d'en-tête de colonne extrait de la première ligne de la feuille de calcul pour la colonne correspondante. Rempli pour le comparateur de cellules lorsque la première ligne contient des valeurs d'en-tête, sinon nul. |
| [ComparisonAction](../../groupdocs.comparison.result/changeinfo/comparisonaction) { get; set; } | Action (accepter ou rejeter). Ce champ indique à la comparaison quoi faire avec cette modification. |
| [ComponentType](../../groupdocs.comparison.result/changeinfo/componenttype) { get; set; } | Type du composant modifié. |
| [Id](../../groupdocs.comparison.result/changeinfo/id) { get; set; } | Identifiant de la modification. |
| [PageInfo](../../groupdocs.comparison.result/changeinfo/pageinfo) { get; set; } | Page où la modification actuelle est placée. |
| [Row](../../groupdocs.comparison.result/changeinfo/row) { get; set; } | Indice de ligne basé sur zéro de la cellule modifiée. Rempli pour le comparateur de cellules (XLSX, CSV, ODS, etc.), sinon nul. |
| [SourceText](../../groupdocs.comparison.result/changeinfo/sourcetext) { get; set; } | Texte modifié du document source. |
| [StyleChanges](../../groupdocs.comparison.result/changeinfo/stylechanges) { get; set; } | Tableau des modifications de style. |
| [TargetText](../../groupdocs.comparison.result/changeinfo/targettext) { get; set; } | Texte modifié du document cible. |
| [Text](../../groupdocs.comparison.result/changeinfo/text) { get; set; } | Valeur texte de la modification. |
| [Type](../../groupdocs.comparison.result/changeinfo/type) { get; } | Type de la modification. |

### Voir aussi

* namespace [GroupDocs.Comparison.Result](../../groupdocs.comparison.result)
* assembly [GroupDocs.Comparison](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Comparison.dll -->
