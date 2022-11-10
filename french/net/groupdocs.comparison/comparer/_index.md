---
title: Comparer
second_title: Référence de l'API GroupDocs.Comparison pour .NET
description: Représente la classe principale qui contrôle le processus de comparaison de documents.
type: docs
weight: 100
url: /fr/net/groupdocs.comparison/comparer/
---
## Comparer class

Représente la classe principale qui contrôle le processus de comparaison de documents.

```csharp
public class Comparer : IDisposable
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [Comparer](comparer#constructor)(Stream) | Initialise la nouvelle instance de[`Comparer`](../comparer) classe avec flux de documents source. |
| [Comparer](comparer#constructor_4)(string) | Initialise la nouvelle instance de[`Comparer`](../comparer) classe avec le chemin du fichier source. |
| [Comparer](comparer#constructor_1)(Stream, ComparerSettings) | Initialise la nouvelle instance de[`Comparer`](../comparer)classe avec flux de documents source et[`ComparerSettings`](../comparersettings) . |
| [Comparer](comparer#constructor_2)(Stream, LoadOptions) | Initialise la nouvelle instance de[`Comparer`](../comparer) avec flux de documents source et[`LoadOptions`](../../groupdocs.comparison.options/loadoptions) . |
| [Comparer](comparer#constructor_5)(string, ComparerSettings) | Initialise la nouvelle instance de[`Comparer`](../comparer) classe avec le chemin du fichier source et[`ComparerSettings`](../comparersettings) . |
| [Comparer](comparer#constructor_6)(string, LoadOptions) | Initialise la nouvelle instance de[`Comparer`](../comparer) avec le chemin du fichier source et[`LoadOptions`](../../groupdocs.comparison.options/loadoptions) . |
| [Comparer](comparer#constructor_3)(Stream, LoadOptions, ComparerSettings) | Initialise la nouvelle instance de[`Comparer`](../comparer) classe avec flux de documents,[`LoadOptions`](../../groupdocs.comparison.options/loadoptions) et[`ComparerSettings`](../comparersettings) . |
| [Comparer](comparer#constructor_7)(string, LoadOptions, ComparerSettings) | Initialise la nouvelle instance de[`Comparer`](../comparer) classe avec le chemin du fichier source,[`LoadOptions`](../../groupdocs.comparison.options/loadoptions) et[`ComparerSettings`](../comparersettings) . |

## Propriétés

| Nom | La description |
| --- | --- |
| [Source](../../groupdocs.comparison/comparer/source) { get; } | Fichier source en cours de comparaison. |
| [Targets](../../groupdocs.comparison/comparer/targets) { get; } | Liste des fichiers cibles à comparer avec le fichier source. |

## Méthodes

| Nom | La description |
| --- | --- |
| [Add](../../groupdocs.comparison/comparer/add#add)(Stream) | Ajoute le flux de documents à la comparaison. |
| [Add](../../groupdocs.comparison/comparer/add#add_2)(string) | Ajoute le fichier à la comparaison. |
| [Add](../../groupdocs.comparison/comparer/add#add_1)(Stream, LoadOptions) | Ajoute le flux de documents à la comparaison avec les options de chargement spécifiées. |
| [Add](../../groupdocs.comparison/comparer/add#add_3)(string, LoadOptions) | Ajoute le fichier à comparer avec les options de chargement spécifiées. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges)(Stream, ApplyChangeOptions) | Accepte ou rejette les modifications et les applique au document résultant. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_2)(string, ApplyChangeOptions) | Accepte ou rejette les modifications et les applique au document résultant. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_1)(Stream, SaveOptions, ApplyChangeOptions) | Accepte ou rejette les modifications et les applique au document résultant. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_3)(string, SaveOptions, ApplyChangeOptions) | Accepte ou rejette les modifications et les applique au document résultant. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare)() | Compare les documents sans enregistrer le résultat avec les options par défaut |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_1)(CompareOptions) | Compare les documents sans enregistrer le résultat. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_3)(Stream) | Compare les documents et enregistre le résultat dans le fichier stream |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_7)(string) | Compare les documents et enregistre le résultat dans le chemin du fichier |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_2)(SaveOptions, CompareOptions) | Compare les documents sans enregistrer le résultat. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_4)(Stream, CompareOptions) | Compare les documents et enregistre le résultat dans le fichier stream |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_5)(Stream, SaveOptions) | Compare les documents et enregistre le résultat dans le fichier stream |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_8)(string, CompareOptions) | Compare les documents et enregistre le résultat dans le chemin du fichier |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_9)(string, SaveOptions) | Compare les documents et enregistre le résultat dans le chemin du fichier |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_6)(Stream, SaveOptions, CompareOptions) | Compare les documents et enregistre le résultat dans un flux. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_10)(string, SaveOptions, CompareOptions) | Compare les documents et enregistre le résultat dans le chemin du fichier |
| [Dispose](../../groupdocs.comparison/comparer/dispose)() | Libère des ressources. |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges)() | Obtient la liste des modifications entre les fichiers source et cible. |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges_1)(GetChangeOptions) | Obtient la liste des modifications entre les fichiers source et cible. |
| [GetResultString](../../groupdocs.comparison/comparer/getresultstring)() | Obtenir la chaîne de résultat après comparaison (pour la comparaison de texte uniquement). |

### Voir également

* espace de noms [GroupDocs.Comparison](../../groupdocs.comparison)
* Assemblée [GroupDocs.Comparison](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Comparison.dll -->
