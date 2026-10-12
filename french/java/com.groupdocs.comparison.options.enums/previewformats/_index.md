---
title: "PreviewFormats"
second_title: "Référence API de GroupDocs.Comparison for Java"
description: "Énumère les formats d'aperçu pris en charge pour la comparaison de documents."
type: docs
weight: 15
url: /fr/java/com.groupdocs.comparison.options.enums/previewformats/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PreviewFormats extends Enum<PreviewFormats>
```

Énumère les formats d'aperçu pris en charge pour la comparaison de documents.
L'énumération PreviewFormats fournit une liste de formats pouvant être utilisés pour générer des aperçus des documents comparés.

Les formats pris en charge incluent :

* #PNG.PNG - Portable Network Graphics (.png)
* #JPEG.JPEG - Joint Photographic Experts Group (.jpeg)
* #BMP.BMP - Bitmap Picture (.bmp)


Exemple d'utilisation :

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    PreviewOptions previewOptions = new PreviewOptions(
            pageNumber -> Files.newOutputStream(Paths.get(String.format("preview-page_%d.png", pageNumber)))
    );
    previewOptions.setPreviewFormat(PreviewFormats.PNG);

    comparer.getTargets().get(0).generatePreview(previewOptions);
 }
 
````


## Champs

| Champ | Description |
| --- | --- |
|  | [PNG](#PNG) | PNG - peut consommer un espace disque ou un trafic réseau important si la page contient de nombreux graphiques en couleur. |
|
|  | [JPEG](#JPEG) | Jpeg - offre un traitement plus rapide avec une utilisation d'espace disque et un trafic réseau plus faibles, mais peut entraîner une qualité d'image inférieure. |
|
|  | [BMP](#BMP) | BMP - offre la meilleure qualité d'image mais nécessite un traitement plus lent avec une utilisation d'espace disque et un trafic réseau plus élevés. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Analyse la représentation sous forme de chaîne de PreviewFormats pour obtenir la constante d'énumération. |
|
|  | [toString()](#toString--) | Représentation sous forme de chaîne de PreviewFormats. |
|
### PNG {#PNG}
```
public static final PreviewFormats PNG
```


PNG - peut consommer un espace disque ou un trafic réseau important si la page contient de nombreux graphiques en couleur. Format d'aperçu par défaut.


### JPEG {#JPEG}
```
public static final PreviewFormats JPEG
```


Jpeg - offre un traitement plus rapide avec une utilisation d'espace disque et un trafic réseau plus faibles, mais peut entraîner une qualité d'image inférieure.


### BMP {#BMP}
```
public static final PreviewFormats BMP
```


BMP - offre la meilleure qualité d'image mais nécessite un traitement plus lent avec une utilisation d'espace disque et un trafic réseau plus élevés.


### values() {#values--}
```
public static PreviewFormats[] values()
```




**Returns:**
com.groupdocs.comparison.options.enums.PreviewFormats[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PreviewFormats valueOf(String name)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String |  |

**Returns:**
[PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static PreviewFormats fromString(String toStringValue)
```


Analyse la représentation sous forme de chaîne de PreviewFormats pour obtenir la constante d'énumération.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | toStringValue | java.lang.String | La représentation sous forme de chaîne de PreviewFormats |
|

**Returns:**
[PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats) - PreviewFormats enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


Représentation sous forme de chaîne de PreviewFormats.


**Returns:**
java.lang.String - valeur sous forme de chaîne de la constante d'énumération

