---
title: "Comparer"
second_title: "GroupDocs.Comparison pour .NET API Reference"
description: "Représente la classe principale qui contrôle le processus de comparaison des documents."
type: docs
weight: 100
url: /fr/net/groupdocs.comparison/comparer/
---
## Comparer class

Représente la classe principale qui contrôle le processus de comparaison des documents.

```csharp
public sealed class Comparer : IDisposable
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Comparer](comparer#constructor)(Stream) | Initialise une nouvelle instance de la classe [`Comparer`](../comparer) avec le flux du document source. |
| [Comparer](comparer#constructor_4)(string) | Initialise une nouvelle instance de la classe [`Comparer`](../comparer) avec le chemin du fichier source. |
| [Comparer](comparer#constructor_1)(Stream, ComparerSettings) | Initialise une nouvelle instance de la classe [`Comparer`](../comparer) avec le flux du document source et [`ComparerSettings`](../comparersettings). |
| [Comparer](comparer#constructor_2)(Stream, LoadOptions) | Initialise une nouvelle instance de [`Comparer`](../comparer) avec le flux du document source et [`LoadOptions`](../../groupdocs.comparison.options/loadoptions). |
| [Comparer](comparer#constructor_6)(string, CompareOptions) | Initialise une nouvelle instance de [`Comparer`](../comparer) avec le chemin du dossier source et [`CompareOptions`](../../groupdocs.comparison.options/compareoptions). |
| [Comparer](comparer#constructor_5)(string, ComparerSettings) | Initialise une nouvelle instance de la classe [`Comparer`](../comparer) avec le chemin du fichier source et [`ComparerSettings`](../comparersettings). |
| [Comparer](comparer#constructor_7)(string, LoadOptions) | Initialise une nouvelle instance de [`Comparer`](../comparer) avec le chemin du fichier source et [`LoadOptions`](../../groupdocs.comparison.options/loadoptions). |
| [Comparer](comparer#constructor_3)(Stream, LoadOptions, ComparerSettings) | Initialise une nouvelle instance de la classe [`Comparer`](../comparer) avec le flux du document, [`LoadOptions`](../../groupdocs.comparison.options/loadoptions) et [`ComparerSettings`](../comparersettings). |
| [Comparer](comparer#constructor_8)(string, LoadOptions, ComparerSettings) | Initialise une nouvelle instance de la classe [`Comparer`](../comparer) avec le chemin du fichier source, [`LoadOptions`](../../groupdocs.comparison.options/loadoptions) et [`ComparerSettings`](../comparersettings). |

## Propriétés

| Nom | Description |
| --- | --- |
| [Result](../../groupdocs.comparison/comparer/result) { get; } | Document résultant. |
| [Source](../../groupdocs.comparison/comparer/source) { get; } | Fichier source qui est comparé. |
| [SourceFolder](../../groupdocs.comparison/comparer/sourcefolder) { get; } | Dossier source qui est comparé. |
| [TargetFolder](../../groupdocs.comparison/comparer/targetfolder) { get; set; } | Dossier cible qui est comparé. |
| [Targets](../../groupdocs.comparison/comparer/targets) { get; } | Liste des fichiers cibles à comparer avec le fichier source. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Add](../../groupdocs.comparison/comparer/add#add)(Stream) | Ajoute le flux du document à la comparaison. |
| [Add](../../groupdocs.comparison/comparer/add#add_2)(string) | Ajoute un fichier à la comparaison. |
| [Add](../../groupdocs.comparison/comparer/add#add_1)(Stream, LoadOptions) | Ajoute le flux du document à la comparaison avec les options de chargement spécifiées. |
| [Add](../../groupdocs.comparison/comparer/add#add_3)(string, CompareOptions) | Ajoute un dossier à la comparaison. |
| [Add](../../groupdocs.comparison/comparer/add#add_4)(string, LoadOptions) | Ajoute un fichier à la comparaison avec les options de chargement spécifiées. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges)(Stream, ApplyChangeOptions) | Accepte ou rejette les modifications et les applique au document résultant. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_2)(string, ApplyChangeOptions) | Accepte ou rejette les modifications et les applique au document résultant. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_1)(Stream, SaveOptions, ApplyChangeOptions) | Accepte ou rejette les modifications et les applique au document résultant. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_3)(string, SaveOptions, ApplyChangeOptions) | Accepte ou rejette les modifications et les applique au document résultant. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare)() | Compare les documents sans enregistrer le résultat avec les options par défaut |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_1)(CompareOptions) | Compare les documents sans enregistrer le résultat. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_3)(Stream) | Compare les documents et enregistre le résultat dans un flux de fichier |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_7)(string) | Compare les documents et enregistre le résultat dans le chemin du fichier |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_2)(SaveOptions, CompareOptions) | Compare les documents sans enregistrer le résultat. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_4)(Stream, CompareOptions) | Compare les documents et enregistre le résultat dans un flux de fichier |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_5)(Stream, SaveOptions) | Compare les documents et enregistre le résultat dans un flux de fichier |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_8)(string, CompareOptions) | Compare les documents et enregistre le résultat dans le chemin du fichier |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_9)(string, SaveOptions) | Compare les documents et enregistre le résultat dans le chemin du fichier |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_6)(Stream, SaveOptions, CompareOptions) | Compare les documents et enregistre le résultat dans un flux. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_10)(string, SaveOptions, CompareOptions) | Compare les documents et enregistre le résultat dans le chemin du fichier |
| [CompareDirectory](../../groupdocs.comparison/comparer/comparedirectory)(string, CompareOptions) | Compare le répertoire et enregistre le résultat dans le chemin du fichier |
| [Dispose](../../groupdocs.comparison/comparer/dispose)() | Libère les ressources. |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges)() | Obtient la liste des modifications entre le(s) fichier(s) source et cible. |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges_1)(ChangeType) | Obtient la liste des modifications entre le(s) fichier(s) source et cible. |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges_2)(GetChangeOptions) | Obtient la liste des modifications entre le(s) fichier(s) source et cible. |
| [GetResultDocumentStream](../../groupdocs.comparison/comparer/getresultdocumentstream)() | Obtient le flux du document résultant, renvoie null si le flux n'existe pas |
| [GetResultString](../../groupdocs.comparison/comparer/getresultstring)() | Obtenir la chaîne de résultat après la comparaison (pour la comparaison de texte uniquement). |

### Voir aussi

* namespace [GroupDocs.Comparison](../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Comparison.dll -->
