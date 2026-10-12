---
title: "LoadOptions"
second_title: "GroupDocs.Comparison pour .NET API Reference"
description: "Permet de spécifier des options supplémentaires lors du chargement d'un document."
type: docs
weight: 300
url: /fr/net/groupdocs.comparison.options/loadoptions/
---
## LoadOptions class

Permet de spécifier des options supplémentaires lors du chargement d'un document.

```csharp
public class LoadOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [LoadOptions](loadoptions)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [FileType](../../groupdocs.comparison.options/loadoptions/filetype) { get; set; } | Définissez manuellement le type de fichier pour la comparaison afin de remplacer la détection automatique du type de fichier. |
| [FontDirectories](../../groupdocs.comparison.options/loadoptions/fontdirectories) { get; set; } | Liste des répertoires de polices à charger. |
| [LoadText](../../groupdocs.comparison.options/loadoptions/loadtext) { get; set; } | Indique que les chaînes fournies sont du texte de comparaison, et non des chemins de fichiers (pour la comparaison de texte uniquement). |
| [Password](../../groupdocs.comparison.options/loadoptions/password) { get; set; } | Mot de passe du document. |
| [SkipExternalResources](../../groupdocs.comparison.options/loadoptions/skipexternalresources) { get; set; } | Désactive le chargement de toutes les ressources externes (par ex. les images référencées par une URL distante) sauf [`WhitelistedResources`](./whitelistedresources). |
| [WhitelistedResources](../../groupdocs.comparison.options/loadoptions/whitelistedresources) { get; set; } | La liste des fragments d’URL correspondant aux ressources externes qui doivent être chargées lorsque [`SkipExternalResources`](./skipexternalresources) est réglé sur `true`. |

### Voir aussi

* namespace [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Comparison.dll -->
