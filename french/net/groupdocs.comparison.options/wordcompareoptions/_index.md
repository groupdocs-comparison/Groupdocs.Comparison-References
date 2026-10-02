---
title: "WordCompareOptions"
second_title: "GroupDocs.Comparison pour .NET API Reference"
description: "Options de comparaison spécifiques aux documents Word. Hérite des options communes de CompareOptions./compareoptions."
type: docs
weight: 440
url: /fr/net/groupdocs.comparison.options/wordcompareoptions/
---
## WordCompareOptions class

Options de comparaison spécifiques aux documents Word. Hérite des options communes de [`CompareOptions`](../compareoptions).

```csharp
public class WordCompareOptions : CompareOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [WordCompareOptions](wordcompareoptions)() | Initialise une nouvelle instance de la classe [`WordCompareOptions`](../wordcompareoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [CalculateCoordinates](../../groupdocs.comparison.options/compareoptions/calculatecoordinates) { get; set; } | Indique si les coordonnées des composants modifiés doivent être calculées. |
| [CalculateCoordinatesMode](../../groupdocs.comparison.options/compareoptions/calculatecoordinatesmode) { get; set; } | Spécifie le mode de calcul des coordonnées pour les composants modifiés. |
| [ChangedItemStyle](../../groupdocs.comparison.options/compareoptions/changeditemstyle) { get; set; } | Décrit le style des composants modifiés. |
| [CompareBookmarks](../../groupdocs.comparison.options/wordcompareoptions/comparebookmarks) { get; set; } | Obtient ou définit si les signets dans les documents source et cible sont comparés et si les différences sont incluses dans le résultat. |
| [CompareDocumentProperty](../../groupdocs.comparison.options/wordcompareoptions/comparedocumentproperty) { get; set; } | Obtient ou définit si les propriétés de document intégrées et personnalisées sont comparées et si les différences sont incluses dans le résultat (p. ex. sur la page de résumé des propriétés). |
| [CompareVariableProperty](../../groupdocs.comparison.options/wordcompareoptions/comparevariableproperty) { get; set; } | Obtient ou définit si les propriétés de variables de document (p. ex. champs DOCVARIABLE) sont comparées et si les différences sont incluses dans le résultat. |
| [DeletedItemStyle](../../groupdocs.comparison.options/compareoptions/deleteditemstyle) { get; set; } | Décrit le style des composants supprimés. |
| [DetalisationLevel](../../groupdocs.comparison.options/compareoptions/detalisationlevel) { get; set; } | Obtient ou définit le niveau de détail de la comparaison. |
| [DetectStyleChanges](../../groupdocs.comparison.options/compareoptions/detectstylechanges) { get; set; } | Indique s'il faut détecter les changements de style ou non. |
| [DiagramMasterSetting](../../groupdocs.comparison.options/compareoptions/diagrammastersetting) { get; set; } | Obtient ou définit la valeur du chemin pour le master ou utilise la comparaison sans chemin du master. Cette option est uniquement pour Diagram. |
| [DirectoryCompare](../../groupdocs.comparison.options/compareoptions/directorycompare) { get; set; } | Contrôle pour activer la comparaison de dossiers. |
| [DisplayMode](../../groupdocs.comparison.options/wordcompareoptions/displaymode) { get; set; } | Obtient ou définit comment les résultats de comparaison sont affichés : comme des révisions Word en mode Suivi des modifications (Revisions) ou comme des changements mis en évidence rendus directement dans le document (Highlight). |
| [ExtendedSummaryPage](../../groupdocs.comparison.options/compareoptions/extendedsummarypage) { get; set; } | Indique s'il faut ajouter des informations de comparaison de fichiers étendues à la page de résumé ou non. |
| [FolderComparisonExtension](../../groupdocs.comparison.options/compareoptions/foldercomparisonextension) { get; set; } | Obtient ou définit le format du fichier de comparaison de dossiers résultant. |
| [GenerateSummaryPage](../../groupdocs.comparison.options/compareoptions/generatesummarypage) { get; set; } | Indique s'il faut ajouter une page de résumé avec les statistiques des changements détectés au document résultant ou non. |
| [HeaderFootersComparison](../../groupdocs.comparison.options/compareoptions/headerfooterscomparison) { get; set; } | Contrôle pour activer la comparaison du contenu des en-têtes/pieds de page. |
| [IgnoreChangeSettings](../../groupdocs.comparison.options/compareoptions/ignorechangesettings) { get; set; } | Obtient ou définit les paramètres pour ignorer les changements basés sur la similarité. |
| [InsertedItemStyle](../../groupdocs.comparison.options/compareoptions/inserteditemstyle) { get; set; } | Décrit le style des composants insérés. |
| [LeaveGaps](../../groupdocs.comparison.options/wordcompareoptions/leavegaps) { get; set; } | Obtient ou définit si des lignes vides sont laissées à la place du contenu inséré ou supprimé pour préserver la mise en page et le nombre de lignes ; utilisé avec [`ShowInsertedContent`](../compareoptions/showinsertedcontent) et [`ShowDeletedContent`](../compareoptions/showdeletedcontent). |
| [MarkChangedContent](../../groupdocs.comparison.options/compareoptions/markchangedcontent) { get; set; } | Indique s'il faut utiliser des cadres pour les formes dans le traitement de texte et des rectangles dans les documents Image. |
| [MarkLineBreaks](../../groupdocs.comparison.options/wordcompareoptions/marklinebreaks) { get; set; } | Obtient ou définit si les sauts de paragraphe (ligne) qui diffèrent entre les documents sont visuellement marqués dans le résultat. |
| [MarkNestedContent](../../groupdocs.comparison.options/compareoptions/marknestedcontent) { get; set; } | Obtient ou définit une valeur indiquant s'il faut marquer les enfants de l'élément supprimé ou inséré comme supprimés ou insérés. |
| [OriginalSize](../../groupdocs.comparison.options/compareoptions/originalsize) { get; set; } | Obtient ou définit les tailles originales des documents comparés. |
| [PaperSize](../../groupdocs.comparison.options/compareoptions/papersize) { get; set; } | Obtient ou définit la taille du papier du document résultat. |
| [PasswordSaveOption](../../groupdocs.comparison.options/compareoptions/passwordsaveoption) { get; set; } | Obtient ou définit l'option d'enregistrement du mot de passe. |
| [RevisionAuthorName](../../groupdocs.comparison.options/wordcompareoptions/revisionauthorname) { get; set; } | Obtient ou définit le nom de l'auteur utilisé pour les révisions lorsque !:WordTrackChanges est activé. Si défini, ce nom est appliqué au balisage des révisions dans le document résultat. |
| [SensitivityOfComparison](../../groupdocs.comparison.options/compareoptions/sensitivityofcomparison) { get; set; } | Obtient ou définit une sensibilité de la comparaison. |
| [SensitivityOfComparisonForTables](../../groupdocs.comparison.options/compareoptions/sensitivityofcomparisonfortables) { get; set; } | Obtient ou définit une sensibilité de la comparaison pour les tableaux. |
| [ShowDeletedContent](../../groupdocs.comparison.options/compareoptions/showdeletedcontent) { get; set; } | Indique s'il faut afficher les composants supprimés dans le document résultant ou non. |
| [ShowInsertedContent](../../groupdocs.comparison.options/compareoptions/showinsertedcontent) { get; set; } | Indique s'il faut afficher les composants insérés dans le document résultant ou non. |
| [ShowOnlyChanged](../../groupdocs.comparison.options/compareoptions/showonlychanged) { get; set; } | Contrôles pour activer l'affichage uniquement des éléments modifiés. |
| [ShowOnlySummaryPage](../../groupdocs.comparison.options/compareoptions/showonlysummarypage) { get; set; } | Indique s'il faut laisser dans le document résultant uniquement une page avec les statistiques des changements détectés dans le document résultant ou non. |
| [ShowRevisions](../../groupdocs.comparison.options/wordcompareoptions/showrevisions) { get; set; } | Obtient ou définit si le document résultant conserve le balisage des révisions visible. Si false, toutes les révisions sont acceptées et le résultat apparaît comme du texte final. Ce paramètre n’est significatif que lorsque [`DisplayMode`](./displaymode) est défini sur Highlight. La valeur par défaut est true. |
| [UserMasterPath](../../groupdocs.comparison.options/compareoptions/usermasterpath) { get; set; } | Chemin vers le modèle maître de l'utilisateur pour les Diagrammes. |
| [WordsSeparatorChars](../../groupdocs.comparison.options/compareoptions/wordsseparatorchars) { set; } | Obtient ou définit un tableau de délimiteurs pour diviser le texte en mots. |

### Voir aussi

* class [CompareOptions](../compareoptions)
* namespace [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Comparison.dll -->
