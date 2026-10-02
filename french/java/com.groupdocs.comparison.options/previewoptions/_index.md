---
title: "PreviewOptions"
second_title: "Référence API de GroupDocs.Comparison for Java"
description: "Fournit des options pour générer des aperçus de documents dans le processus de comparaison."
type: docs
weight: 15
url: /fr/java/com.groupdocs.comparison.options/previewoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewOptions
```

Fournit des options pour générer des aperçus de documents dans le processus de comparaison.


Exemple d'utilisation :

````

 try (Comparer comparer = new Comparer(sourceFile)) {

    PreviewOptions previewOptions = new PreviewOptions(
            pageNumber -> Files.newOutputStream(Paths.get(String.format("preview-page_%d.png", pageNumber)))
    );
    previewOptions.setPreviewFormat(PreviewFormats.PNG);
    previewOptions.setPageNumbers(new int[]{1, 2});

    comparer.getSource().generatePreview(previewOptions);
 }
 
````


## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [PreviewOptions(Delegates.CreatePageStream createPageStream)](#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-) | Initialise une nouvelle instance de la classe PreviewOptions en spécifiant la fonction Delegates.CreatePageStream. |
|
|  | [PreviewOptions(CreatePageStreamFunction createPageStream)](#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-) | Initialise une nouvelle instance de la classe PreviewOptions en spécifiant la fonction [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction). |
|
|  | [PreviewOptions(Delegates.CreatePageStream createPageStream, Delegates.ReleasePageStream releasePageStream)](#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-) | Initialise une nouvelle instance de la classe PreviewOptions en spécifiant les fonctions Delegates.CreatePageStream et Delegates.ReleasePageStream. |
|
|  | [PreviewOptions(CreatePageStreamFunction createPageStream, ReleasePageStreamFunction releasePageStream)](#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-) | Initialise une nouvelle instance de la classe PreviewOptions en spécifiant les fonctions [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) et [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction). |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getCreatePageStream()](#getCreatePageStream--) | Obtient une fonction pour créer le flux de prévisualisation de page de sortie. |
|
|  | [setCreatePageStream(Delegates.CreatePageStream createPageStream)](#setCreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-) | Définit une fonction pour créer le flux de prévisualisation de page de sortie. |
|
|  | [setCreatePageStream(CreatePageStreamFunction createPageStream)](#setCreatePageStream-com.groupdocs.comparison.common.function.CreatePageStreamFunction-) | Définit une fonction pour créer le flux de prévisualisation de page de sortie. |
|
|  | [getReleasePageStream()](#getReleasePageStream--) | Obtient une fonction pour libérer le flux de prévisualisation de page de sortie. |
|
|  | [setReleasePageStream(Delegates.ReleasePageStream releasePageStream)](#setReleasePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-) | Obtient une fonction pour libérer le flux de prévisualisation de page de sortie. |
|
|  | [setReleasePageStream(ReleasePageStreamFunction releasePageStream)](#setReleasePageStream-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-) | Définit une fonction pour libérer le flux de prévisualisation de page de sortie. |
|
|  | [getWidth()](#getWidth--) | Obtient la largeur des images d'aperçu. |
|
|  | [setWidth(int value)](#setWidth-int-) | Définit la largeur des images d'aperçu. |
|
|  | [getHeight()](#getHeight--) | Obtient la hauteur des images d'aperçu. |
|
|  | [setHeight(int value)](#setHeight-int-) | Définit la hauteur des images d'aperçu. |
|
|  | [getPageNumbers()](#getPageNumbers--) | Obtient un tableau de numéros de page pour lesquels des images d'aperçu seront générées. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | Définit un tableau de numéros de page pour lesquels des images d'aperçu seront générées. |
|
|  | [getPreviewFormat()](#getPreviewFormat--) | Obtient le format des images d'aperçu. |
|
|  | [setPreviewFormat(PreviewFormats value)](#setPreviewFormat-com.groupdocs.comparison.options.enums.PreviewFormats-) | Définit le format des images d'aperçu. |
|
### PreviewOptions(Delegates.CreatePageStream createPageStream) {#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-}
```
public PreviewOptions(Delegates.CreatePageStream createPageStream)
```


Initialise une nouvelle instance de la classe PreviewOptions en spécifiant la fonction Delegates.CreatePageStream.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.comparison.common.delegates/createpagestream) | La fonction pour créer le flux d'aperçu de page de sortie. |
|

### PreviewOptions(CreatePageStreamFunction createPageStream) {#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-}
```
public PreviewOptions(CreatePageStreamFunction createPageStream)
```


Initialise une nouvelle instance de la classe PreviewOptions en spécifiant la fonction [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | createPageStream | [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) | La fonction pour créer le flux d'aperçu de page de sortie. |
|

### PreviewOptions(Delegates.CreatePageStream createPageStream, Delegates.ReleasePageStream releasePageStream) {#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-}
```
public PreviewOptions(Delegates.CreatePageStream createPageStream, Delegates.ReleasePageStream releasePageStream)
```


Initialise une nouvelle instance de la classe PreviewOptions en spécifiant les fonctions Delegates.CreatePageStream et Delegates.ReleasePageStream.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.comparison.common.delegates/createpagestream) | La fonction pour créer le flux d'aperçu de page de sortie. |
|
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.comparison.common.delegates/releasepagestream) | La fonction pour libérer le flux d'aperçu de page de sortie. |
|

### PreviewOptions(CreatePageStreamFunction createPageStream, ReleasePageStreamFunction releasePageStream) {#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-}
```
public PreviewOptions(CreatePageStreamFunction createPageStream, ReleasePageStreamFunction releasePageStream)
```


Initialise une nouvelle instance de la classe PreviewOptions en spécifiant les fonctions [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) et [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | createPageStream | [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) | La fonction pour créer le flux d'aperçu de page de sortie. |
|
|  | releasePageStream | [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) | La fonction pour libérer le flux d'aperçu de page de sortie. |
|

### getCreatePageStream() {#getCreatePageStream--}
```
public CreatePageStreamFunction getCreatePageStream()
```


Obtient une fonction pour créer le flux de prévisualisation de page de sortie.


**Returns:**
[CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) - the function to create output page preview stream.

### setCreatePageStream(Delegates.CreatePageStream createPageStream) {#setCreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-}
```
public void setCreatePageStream(Delegates.CreatePageStream createPageStream)
```


Définit une fonction pour créer le flux de prévisualisation de page de sortie.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.comparison.common.delegates/createpagestream) | La fonction pour créer le flux d'aperçu de page de sortie. |
|

### setCreatePageStream(CreatePageStreamFunction createPageStream) {#setCreatePageStream-com.groupdocs.comparison.common.function.CreatePageStreamFunction-}
```
public void setCreatePageStream(CreatePageStreamFunction createPageStream)
```


Définit une fonction pour créer le flux de prévisualisation de page de sortie.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | createPageStream | [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) | La fonction pour créer le flux d'aperçu de page de sortie. |
|

### getReleasePageStream() {#getReleasePageStream--}
```
public ReleasePageStreamFunction getReleasePageStream()
```


Obtient une fonction pour libérer le flux de prévisualisation de page de sortie.


**Returns:**
[ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) - the function to release output page preview stream.

### setReleasePageStream(Delegates.ReleasePageStream releasePageStream) {#setReleasePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-}
```
public void setReleasePageStream(Delegates.ReleasePageStream releasePageStream)
```


Obtient une fonction pour libérer le flux de prévisualisation de page de sortie.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.comparison.common.delegates/releasepagestream) | La fonction pour libérer le flux d'aperçu de page de sortie. |
|

### setReleasePageStream(ReleasePageStreamFunction releasePageStream) {#setReleasePageStream-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-}
```
public void setReleasePageStream(ReleasePageStreamFunction releasePageStream)
```


Définit une fonction pour libérer le flux de prévisualisation de page de sortie.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | releasePageStream | [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) | La fonction pour libérer le flux d'aperçu de page de sortie. |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Obtient la largeur des images d'aperçu.


**Returns:**
int - la largeur des images d'aperçu.

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Définit la largeur des images d'aperçu.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | int | La largeur des images d'aperçu. |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Obtient la hauteur des images d'aperçu.


**Returns:**
int - la hauteur des images d'aperçu.

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Définit la hauteur des images d'aperçu.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | int | La hauteur des images d'aperçu. |
|

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Obtient un tableau de numéros de page pour lesquels des images d'aperçu seront générées.


**Returns:**
int[] - tableau de numéros de page

### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Définit un tableau de numéros de page pour lesquels des images d'aperçu seront générées.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | int[] | Tableau de numéros de page |
|

### getPreviewFormat() {#getPreviewFormat--}
```
public final PreviewFormats getPreviewFormat()
```


Obtient le format des images d'aperçu.


**Returns:**
[PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats) - preview images format

### setPreviewFormat(PreviewFormats value) {#setPreviewFormat-com.groupdocs.comparison.options.enums.PreviewFormats-}
```
public final void setPreviewFormat(PreviewFormats value)
```


Définit le format des images d'aperçu.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats) | Format des images d'aperçu |
|

