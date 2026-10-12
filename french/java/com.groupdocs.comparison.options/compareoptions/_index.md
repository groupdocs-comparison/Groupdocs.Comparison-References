---
title: "CompareOptions"
second_title: "Référence API de GroupDocs.Comparison for Java"
description: "Permet de configurer le processus de comparaison de documents."
type: docs
weight: 11
url: /fr/java/com.groupdocs.comparison.options/compareoptions/
---
**Inheritance:**
java.lang.Object
```
public class CompareOptions
```

Permet de configurer le processus de comparaison de documents.


Exemple d'utilisation :

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     final StyleSettings styleSettings = new StyleSettings();
     styleSettings.setHighlightColor(Color.RED);
     styleSettings.setFontColor(Color.GREEN);
     styleSettings.setUnderline(true);

     CompareOptions compareOptions = new CompareOptions();
     compareOptions.setInsertedItemStyle(styleSettings);

     comparer.compare(resultFile, compareOptions);
 }
 
````


## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [CompareOptions()](#CompareOptions--) | Initialise une nouvelle instance de la classe CompareOptions. |
|
|  | [CompareOptions(StyleSettings insertedItemStyle, StyleSettings deletedItemStyle, StyleSettings changedItemStyle)](#CompareOptions-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-) | Initialise une nouvelle instance de la classe CompareOptions avec des paramètres pour différents styles. |
|
## Champs

| Champ | Description |
| --- | --- |
| [ignoreChangeSettings](#ignoreChangeSettings) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getIgnoreChangeSettings()](#getIgnoreChangeSettings--) | Récupère les paramètres pour ignorer les modifications basées sur la similarité. |
|
|  | [setIgnoreChangeSettings(IgnoreChangeSensitivitySettings ignoreChangeSettings)](#setIgnoreChangeSettings-com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings-) | Définit les paramètres pour ignorer les modifications basées sur la similarité. |
|
|  | [getUserMasterPath()](#getUserMasterPath--) | Obtient le chemin du modèle maître de l'utilisateur pour les Diagrammes. |
|
|  | [setUserMasterPath(String userMasterPath)](#setUserMasterPath-java.lang.String-) | Définit le chemin du modèle maître de l'utilisateur pour les Diagrammes. |
|
|  | [getComparisonType()](#getComparisonType--) | Obtient un type de documents source et cible en tant qu'objet [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) afin que Comparison sache comment les comparer. |
|
|  | [setComparisonType(ComparisonType comparisonType)](#setComparisonType-com.groupdocs.comparison.options.enums.ComparisonType-) | Définit un type de documents source et cible en tant qu'objet [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) afin que Comparison sache comment les comparer. |
|
|  | [getPaperSize()](#getPaperSize--) | Obtient une taille de papier dans le document résultat en tant qu'objet [PaperSize](../../com.groupdocs.comparison.options.enums/papersize). |
|
|  | [setPaperSize(PaperSize value)](#setPaperSize-com.groupdocs.comparison.options.enums.PaperSize-) | Définit une taille de papier dans le document résultat en tant qu'objet [PaperSize](../../com.groupdocs.comparison.options.enums/papersize). |
|
|  | [getCalculateCoordinatesMode()](#getCalculateCoordinatesMode--) | Obtient un mode de calcul des coordonnées en tant qu'objet [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration). |
|
|  | [setCalculateCoordinatesMode(CalculateCoordinatesModeEnumeration calculateCoordinatesMode)](#setCalculateCoordinatesMode-com.groupdocs.comparison.options.enums.CalculateCoordinatesModeEnumeration-) | Définit un mode de calcul des coordonnées en tant qu'objet [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration). |
|
|  | [isShowDeletedContent()](#isShowDeletedContent--) | Obtient un indicateur qui indique s'il faut afficher les composants supprimés dans le document résultant ou non. |
|
|  | [setShowDeletedContent(boolean value)](#setShowDeletedContent-boolean-) | Définit un indicateur qui indique s'il faut afficher les composants supprimés dans le document résultant ou non. |
|
|  | [isShowInsertedContent()](#isShowInsertedContent--) | Obtient un indicateur qui indique s'il faut afficher les composants insérés dans le document résultant ou non. |
|
|  | [setShowInsertedContent(boolean value)](#setShowInsertedContent-boolean-) | Définit un indicateur qui indique s'il faut afficher les composants insérés dans le document résultant ou non. |
|
|  | [isGenerateSummaryPage()](#isGenerateSummaryPage--) | Obtient un indicateur qui indique s'il faut ajouter une page de résumé avec les statistiques des modifications détectées au document résultant ou non. |
|
|  | [setGenerateSummaryPage(boolean value)](#setGenerateSummaryPage-boolean-) | Définit un indicateur qui indique s'il faut ajouter une page de résumé avec les statistiques des modifications détectées au document résultant ou non. |
|
|  | [isExtendedSummaryPage()](#isExtendedSummaryPage--) | Obtient un indicateur qui indique s'il faut ajouter des informations de comparaison de fichiers étendues à la page de résumé ou non. |
|
|  | [setExtendedSummaryPage(boolean value)](#setExtendedSummaryPage-boolean-) | Définit un indicateur qui indique s'il faut ajouter des informations de comparaison de fichiers étendues à la page de résumé ou non. |
|
|  | [isShowOnlySummaryPage()](#isShowOnlySummaryPage--) | Obtient un indicateur qui indique s'il faut ne laisser dans le document résultant qu'une page avec les statistiques des modifications détectées ou non. |
|
|  | [setShowOnlySummaryPage(boolean value)](#setShowOnlySummaryPage-boolean-) | Définit un indicateur qui indique s'il faut ne laisser dans le document résultant qu'une page avec les statistiques des modifications détectées ou non. |
|
|  | [isDetectStyleChanges()](#isDetectStyleChanges--) | Obtient un indicateur qui indique s'il faut détecter les changements de style ou non. |
|
|  | [setDetectStyleChanges(boolean value)](#setDetectStyleChanges-boolean-) | Définit un indicateur qui indique s'il faut détecter les changements de style ou non. |
|
|  | [isMarkNestedContent()](#isMarkNestedContent--) | Obtient un indicateur qui indique s'il faut marquer les enfants des éléments supprimés ou insérés comme supprimés ou insérés. |
|
|  | [setMarkNestedContent(boolean value)](#setMarkNestedContent-boolean-) | Définit un indicateur qui indique s'il faut marquer les enfants des éléments supprimés ou insérés comme supprimés ou insérés. |
|
|  | [isCalculateCoordinates()](#isCalculateCoordinates--) | Obtient un indicateur qui indique s'il faut calculer les coordonnées des composants modifiés. |
|
|  | [setCalculateCoordinates(boolean value)](#setCalculateCoordinates-boolean-) | Définit un indicateur qui indique s'il faut calculer les coordonnées des composants modifiés. |
|
|  | [isHeaderFootersComparison()](#isHeaderFootersComparison--) | Obtient un indicateur qui indique s'il faut comparer le contenu des en-têtes/pieds de page. |
|
|  | [setHeaderFootersComparison(boolean value)](#setHeaderFootersComparison-boolean-) | Définit un indicateur qui indique s'il faut comparer le contenu des en-têtes/pieds de page. |
|
|  | [getDetalisationLevel()](#getDetalisationLevel--) | Obtient un niveau de détaillage de comparaison représenté par [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel). |
|
|  | [setDetalisationLevel(DetalisationLevel value)](#setDetalisationLevel-com.groupdocs.comparison.options.style.DetalisationLevel-) | Définit un niveau de détaillage de comparaison représenté par [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel). |
|
|  | [isMarkChangedContent()](#isMarkChangedContent--) | Obtient un indicateur qui indique si les cadres pour les formes dans le traitement de texte et pour les rectangles dans les documents image seront utilisés. |
|
|  | [setMarkChangedContent(boolean value)](#setMarkChangedContent-boolean-) | Définit un indicateur qui indique si les cadres pour les formes dans le traitement de texte et pour les rectangles dans les documents image seront utilisés. |
|
|  | [getInsertedItemStyle()](#getInsertedItemStyle--) | Obtient les paramètres de style qui seront appliqués aux éléments insérés. |
|
|  | [setInsertedItemStyle(StyleSettings value)](#setInsertedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-) | Définit les paramètres de style qui seront appliqués aux éléments insérés. |
|
|  | [getDeletedItemStyle()](#getDeletedItemStyle--) | Obtient les paramètres de style qui seront appliqués aux éléments supprimés. |
|
|  | [setDeletedItemStyle(StyleSettings value)](#setDeletedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-) | Définit les paramètres de style qui seront appliqués aux éléments supprimés. |
|
|  | [getChangedItemStyle()](#getChangedItemStyle--) | Obtient les paramètres de style qui seront appliqués aux éléments modifiés. |
|
|  | [setChangedItemStyle(StyleSettings value)](#setChangedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-) | Définit des paramètres de style qui seront appliqués aux éléments modifiés. |
|
|  | [getSensitivityOfComparison()](#getSensitivityOfComparison--) | Obtient une sensibilité de comparaison. |
|
|  | [setSensitivityOfComparison(int value)](#setSensitivityOfComparison-int-) | Définit une sensibilité de comparaison. |
|
|  | [setSensitivityOfComparisonForTables(Integer value)](#setSensitivityOfComparisonForTables-java.lang.Integer-) | Définit une sensibilité de comparaison pour les tableaux. |
|
|  | [getSensitivityOfComparisonForTables()](#getSensitivityOfComparisonForTables--) | Obtient une sensibilité de comparaison pour les tableaux. |
|
|  | [setWordsSeparatorChars(char[] value)](#setWordsSeparatorChars-char---) | Définit un tableau de délimiteurs qui sera utilisé pour diviser le texte en mots. |
|
|  | [getPasswordSaveOption()](#getPasswordSaveOption--) | Obtient une option d’enregistrement de mot de passe représentée par l’objet [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption). |
|
|  | [setPasswordSaveOption(PasswordSaveOption value)](#setPasswordSaveOption-com.groupdocs.comparison.options.enums.PasswordSaveOption-) | Définit une option d’enregistrement de mot de passe représentée par l’objet [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption). |
|
|  | [getOriginalSize()](#getOriginalSize--) | Obtient les tailles originales des documents comparés représentées par l’objet [OriginalSize](../../com.groupdocs.comparison.options/originalsize). |
|
|  | [setOriginalSize(OriginalSize value)](#setOriginalSize-com.groupdocs.comparison.options.OriginalSize-) | Définit les tailles originales des documents comparés représentées par l’objet [OriginalSize](../../com.groupdocs.comparison.options/originalsize). |
|
|  | [getDiagramMasterSetting()](#getDiagramMasterSetting--) | Obtient un paramètre de page maître pour les documents Diagram représenté par l’objet [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting). |
|
|  | [setDiagramMasterSetting(DiagramMasterSetting value)](#setDiagramMasterSetting-com.groupdocs.comparison.options.style.DiagramMasterSetting-) | Définit un paramètre de page maître pour les documents Diagram représenté par l’objet [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting). |
|
|  | [isDirectoryCompare()](#isDirectoryCompare--) | Renvoie un indicateur qui indique si la comparaison de répertoires est activée. |
|
|  | [setDirectoryCompare(boolean directoryCompare)](#setDirectoryCompare-boolean-) | Définit un indicateur qui indique si la comparaison de répertoires doit être activée. |
|
|  | [isShowOnlyChanged()](#isShowOnlyChanged--) | Renvoie une valeur booléenne qui indique si seuls les éléments modifiés doivent être affichés. |
|
|  | [setShowOnlyChanged(boolean showOnlyChanged)](#setShowOnlyChanged-boolean-) | Définit la valeur indiquant si seuls les éléments modifiés doivent être affichés. |
|
|  | [getFolderComparisonExtension()](#getFolderComparisonExtension--) | Obtient le format du fichier de comparaison de dossiers résultant. |
|
|  | [setFolderComparisonExtension(FolderComparisonExtension folderComparisonExtension)](#setFolderComparisonExtension-com.groupdocs.comparison.options.enums.FolderComparisonExtension-) | Définit le format du fichier de comparaison de dossiers résultant. |
|
### CompareOptions() {#CompareOptions--}
```
public CompareOptions()
```


Initialise une nouvelle instance de la classe CompareOptions.


### CompareOptions(StyleSettings insertedItemStyle, StyleSettings deletedItemStyle, StyleSettings changedItemStyle) {#CompareOptions-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-}
```
public CompareOptions(StyleSettings insertedItemStyle, StyleSettings deletedItemStyle, StyleSettings changedItemStyle)
```


Initialise une nouvelle instance de la classe CompareOptions avec des paramètres pour différents styles.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | insertedItemStyle | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Paramètres de style pour les éléments insérés |
|
|  | deletedItemStyle | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Paramètres de style pour les éléments supprimés |
|
|  | changedItemStyle | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Paramètres de style pour les éléments de style modifiés |
|

### ignoreChangeSettings {#ignoreChangeSettings}
```
public IgnoreChangeSensitivitySettings ignoreChangeSettings
```


### getIgnoreChangeSettings() {#getIgnoreChangeSettings--}
```
public IgnoreChangeSensitivitySettings getIgnoreChangeSettings()
```


Récupère les paramètres pour ignorer les modifications basées sur la similarité.


**Returns:**
com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings - Paramètres pour ignorer les modifications.

### setIgnoreChangeSettings(IgnoreChangeSensitivitySettings ignoreChangeSettings) {#setIgnoreChangeSettings-com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings-}
```
public void setIgnoreChangeSettings(IgnoreChangeSensitivitySettings ignoreChangeSettings)
```


Définit les paramètres pour ignorer les modifications basées sur la similarité.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | ignoreChangeSettings | com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings | Paramètres pour ignorer les modifications. |
|

### getUserMasterPath() {#getUserMasterPath--}
```
public String getUserMasterPath()
```


Obtient le chemin du modèle maître de l'utilisateur pour les Diagrammes.


**Returns:**
java.lang.String - Le chemin vers le modèle maître de l'utilisateur pour les Diagrammes.

### setUserMasterPath(String userMasterPath) {#setUserMasterPath-java.lang.String-}
```
public void setUserMasterPath(String userMasterPath)
```


Définit le chemin du modèle maître de l'utilisateur pour les Diagrammes.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | userMasterPath | java.lang.String | Le chemin vers le modèle maître de l'utilisateur pour les Diagrammes. |
|

### getComparisonType() {#getComparisonType--}
```
public ComparisonType getComparisonType()
```


Obtient un type de documents source et cible en tant qu'objet [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) afin que Comparison sache comment les comparer.
Lorsque cette option est définie, l'option [LoadOptions.getFileType()](../../com.groupdocs.comparison.options.load/loadoptions#getFileType--) sera omise.


**Returns:**
[ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) - the type of source and target documents

### setComparisonType(ComparisonType comparisonType) {#setComparisonType-com.groupdocs.comparison.options.enums.ComparisonType-}
```
public void setComparisonType(ComparisonType comparisonType)
```


Définit un type de documents source et cible en tant qu'objet [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) afin que Comparison sache comment les comparer.
Lorsque cette option est définie, l'option [LoadOptions.setFileType(FileType)](../../com.groupdocs.comparison.options.load/loadoptions#setFileType-FileType-) sera omise.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | comparisonType | [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) | Le type des documents source et cible |
|

### getPaperSize() {#getPaperSize--}
```
public final PaperSize getPaperSize()
```


Obtient une taille de papier dans le document résultat en tant qu'objet [PaperSize](../../com.groupdocs.comparison.options.enums/papersize).


**Returns:**
[PaperSize](../../com.groupdocs.comparison.options.enums/papersize) - the size of a paper in result document

### setPaperSize(PaperSize value) {#setPaperSize-com.groupdocs.comparison.options.enums.PaperSize-}
```
public final void setPaperSize(PaperSize value)
```


Définit une taille de papier dans le document résultat en tant qu'objet [PaperSize](../../com.groupdocs.comparison.options.enums/papersize).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [PaperSize](../../com.groupdocs.comparison.options.enums/papersize) | La taille d'une feuille dans le document résultat |
|

### getCalculateCoordinatesMode() {#getCalculateCoordinatesMode--}
```
public CalculateCoordinatesModeEnumeration getCalculateCoordinatesMode()
```


Obtient un mode de calcul des coordonnées en tant qu'objet [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration).


**Returns:**
[CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) - the calculate coordinates mode

### setCalculateCoordinatesMode(CalculateCoordinatesModeEnumeration calculateCoordinatesMode) {#setCalculateCoordinatesMode-com.groupdocs.comparison.options.enums.CalculateCoordinatesModeEnumeration-}
```
public void setCalculateCoordinatesMode(CalculateCoordinatesModeEnumeration calculateCoordinatesMode)
```


Définit un mode de calcul des coordonnées en tant qu'objet [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | calculateCoordinatesMode | [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) | Le mode de calcul des coordonnées |
|

### isShowDeletedContent() {#isShowDeletedContent--}
```
public final boolean isShowDeletedContent()
```


Obtient un indicateur qui indique s'il faut afficher les composants supprimés dans le document résultant ou non.


**Returns:**
booléen - vrai si les composants supprimés dans le document résultant seront affichés, sinon faux

### setShowDeletedContent(boolean value) {#setShowDeletedContent-boolean-}
```
public final void setShowDeletedContent(boolean value)
```


Définit un indicateur qui indique s'il faut afficher les composants supprimés dans le document résultant ou non.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | boolean | vrai si les composants supprimés dans le document résultant doivent être affichés, sinon faux |
|

### isShowInsertedContent() {#isShowInsertedContent--}
```
public final boolean isShowInsertedContent()
```


Obtient un indicateur qui indique s'il faut afficher les composants insérés dans le document résultant ou non.


**Returns:**
booléen - vrai si les composants insérés dans le document résultant doivent être affichés, sinon faux

### setShowInsertedContent(boolean value) {#setShowInsertedContent-boolean-}
```
public final void setShowInsertedContent(boolean value)
```


Définit un indicateur qui indique s'il faut afficher les composants insérés dans le document résultant ou non.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | boolean | vrai si les composants insérés dans le document résultant doivent être affichés, sinon faux |
|

### isGenerateSummaryPage() {#isGenerateSummaryPage--}
```
public final boolean isGenerateSummaryPage()
```


Obtient un indicateur qui indique s'il faut ajouter une page de résumé avec les statistiques des modifications détectées au document résultant ou non.


**Returns:**
booléen - vrai si la page de résumé sera ajoutée, sinon faux

### setGenerateSummaryPage(boolean value) {#setGenerateSummaryPage-boolean-}
```
public final void setGenerateSummaryPage(boolean value)
```


Définit un indicateur qui indique s'il faut ajouter une page de résumé avec les statistiques des modifications détectées au document résultant ou non.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | boolean | vrai si la page de résumé doit être ajoutée, sinon faux |
|

### isExtendedSummaryPage() {#isExtendedSummaryPage--}
```
public boolean isExtendedSummaryPage()
```


Obtient un indicateur qui indique s'il faut ajouter des informations de comparaison de fichiers étendues à la page de résumé ou non.


**Returns:**
booléen - vrai si les informations de comparaison de fichiers étendues seront ajoutées à la page de résumé, sinon faux

### setExtendedSummaryPage(boolean value) {#setExtendedSummaryPage-boolean-}
```
public void setExtendedSummaryPage(boolean value)
```


Définit un indicateur qui indique s'il faut ajouter des informations de comparaison de fichiers étendues à la page de résumé ou non.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | boolean | vrai si les informations de comparaison de fichiers étendues doivent être ajoutées à la page de résumé, sinon faux |
|

### isShowOnlySummaryPage() {#isShowOnlySummaryPage--}
```
public boolean isShowOnlySummaryPage()
```


Obtient un indicateur qui indique s'il faut ne laisser dans le document résultant qu'une page avec les statistiques des modifications détectées ou non.


**Returns:**
booléen - vrai si, dans le document résultant, seule une page contenant les statistiques des modifications détectées restera, sinon faux

### setShowOnlySummaryPage(boolean value) {#setShowOnlySummaryPage-boolean-}
```
public void setShowOnlySummaryPage(boolean value)
```


Définit un indicateur qui indique s'il faut ne laisser dans le document résultant qu'une page avec les statistiques des modifications détectées ou non.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | boolean | vrai si, dans le document résultant, seule une page contenant les statistiques des modifications détectées doit rester, sinon faux |
|

### isDetectStyleChanges() {#isDetectStyleChanges--}
```
public final boolean isDetectStyleChanges()
```


Obtient un indicateur qui indique s'il faut détecter les changements de style ou non.


**Returns:**
booléen - vrai si les changements de style seront détectés, sinon faux

### setDetectStyleChanges(boolean value) {#setDetectStyleChanges-boolean-}
```
public final void setDetectStyleChanges(boolean value)
```


Définit un indicateur qui indique s'il faut détecter les changements de style ou non.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | boolean | vrai si les changements de style doivent être détectés, sinon faux |
|

### isMarkNestedContent() {#isMarkNestedContent--}
```
public final boolean isMarkNestedContent()
```


Obtient un indicateur qui indique s'il faut marquer les enfants des éléments supprimés ou insérés comme supprimés ou insérés.


**Returns:**
booléen - vrai si les enfants des éléments supprimés ou insérés seront marqués comme supprimés ou insérés, sinon faux

### setMarkNestedContent(boolean value) {#setMarkNestedContent-boolean-}
```
public final void setMarkNestedContent(boolean value)
```


Définit un indicateur qui indique s'il faut marquer les enfants des éléments supprimés ou insérés comme supprimés ou insérés.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | boolean | vrai si les enfants des éléments supprimés ou insérés doivent être marqués comme supprimés ou insérés, sinon faux |
|

### isCalculateCoordinates() {#isCalculateCoordinates--}
```
public final boolean isCalculateCoordinates()
```


Obtient un indicateur qui indique s'il faut calculer les coordonnées des composants modifiés.


**Returns:**
booléen - vrai si les coordonnées des composants modifiés seront calculées, sinon faux

### setCalculateCoordinates(boolean value) {#setCalculateCoordinates-boolean-}
```
public final void setCalculateCoordinates(boolean value)
```


Définit un indicateur qui indique s'il faut calculer les coordonnées des composants modifiés.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | boolean | vrai si les coordonnées des composants modifiés doivent être calculées, sinon faux |
|

### isHeaderFootersComparison() {#isHeaderFootersComparison--}
```
public final boolean isHeaderFootersComparison()
```


Obtient un indicateur qui indique s'il faut comparer le contenu des en-têtes/pieds de page.


**Returns:**
booléen - vrai si le contenu des en-têtes/pieds de page sera comparé, sinon faux

### setHeaderFootersComparison(boolean value) {#setHeaderFootersComparison-boolean-}
```
public final void setHeaderFootersComparison(boolean value)
```


Définit un indicateur qui indique s'il faut comparer le contenu des en-têtes/pieds de page.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | boolean | true si le contenu des en-têtes/pieds de page doit être comparé, sinon false |
|

### getDetalisationLevel() {#getDetalisationLevel--}
```
public final DetalisationLevel getDetalisationLevel()
```


Obtient un niveau de détaillage de comparaison représenté par [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel).
La valeur par défaut est [DetalisationLevel.LOW](../../com.groupdocs.comparison.options.style/detalisationlevel#LOW).


**Returns:**
[DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) - the level of comparison detalization

### setDetalisationLevel(DetalisationLevel value) {#setDetalisationLevel-com.groupdocs.comparison.options.style.DetalisationLevel-}
```
public final void setDetalisationLevel(DetalisationLevel value)
```


Définit un niveau de détaillage de comparaison représenté par [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel).
La valeur par défaut est [DetalisationLevel.LOW](../../com.groupdocs.comparison.options.style/detalisationlevel#LOW)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) | Le niveau de détaillisation de la comparaison |
|

### isMarkChangedContent() {#isMarkChangedContent--}
```
public final boolean isMarkChangedContent()
```


Obtient un indicateur qui indique si les cadres pour les formes dans le traitement de texte et pour les rectangles dans les documents image seront utilisés.


**Returns:**
booléen - true si les cadres seront utilisés, sinon false

### setMarkChangedContent(boolean value) {#setMarkChangedContent-boolean-}
```
public final void setMarkChangedContent(boolean value)
```


Définit un indicateur qui indique si les cadres pour les formes dans le traitement de texte et pour les rectangles dans les documents image seront utilisés.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | boolean | true si les cadres doivent être utilisés, sinon false |
|

### getInsertedItemStyle() {#getInsertedItemStyle--}
```
public final StyleSettings getInsertedItemStyle()
```


Obtient les paramètres de style qui seront appliqués aux éléments insérés.


**Returns:**
[StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) - style settings of inserted items

### setInsertedItemStyle(StyleSettings value) {#setInsertedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-}
```
public final void setInsertedItemStyle(StyleSettings value)
```


Définit les paramètres de style qui seront appliqués aux éléments insérés.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Paramètres de style des éléments insérés |
|

### getDeletedItemStyle() {#getDeletedItemStyle--}
```
public final StyleSettings getDeletedItemStyle()
```


Obtient les paramètres de style qui seront appliqués aux éléments supprimés.


**Returns:**
[StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) - style settings of deleted items

### setDeletedItemStyle(StyleSettings value) {#setDeletedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-}
```
public final void setDeletedItemStyle(StyleSettings value)
```


Définit les paramètres de style qui seront appliqués aux éléments supprimés.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Paramètres de style des éléments supprimés |
|

### getChangedItemStyle() {#getChangedItemStyle--}
```
public final StyleSettings getChangedItemStyle()
```


Obtient les paramètres de style qui seront appliqués aux éléments modifiés.


**Returns:**
[StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) - style settings of changed items

### setChangedItemStyle(StyleSettings value) {#setChangedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-}
```
public final void setChangedItemStyle(StyleSettings value)
```


Définit des paramètres de style qui seront appliqués aux éléments modifiés.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Paramètres de style des éléments modifiés |
|

### getSensitivityOfComparison() {#getSensitivityOfComparison--}
```
public final int getSensitivityOfComparison()
```


Obtient une sensibilité de comparaison.
Le pourcentage d'éléments supprimés et insérés de deux objets comparés par rapport à l'ensemble des éléments de ces objets.

* If this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Returns:**
int - la sensibilité de la comparaison

### setSensitivityOfComparison(int value) {#setSensitivityOfComparison-int-}
```
public final void setSensitivityOfComparison(int value)
```


Définit une sensibilité de comparaison.
Le pourcentage d'éléments supprimés et insérés de deux objets comparés par rapport à l'ensemble des éléments de ces objets.

* If this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | int | La sensibilité de la comparaison |
|

### setSensitivityOfComparisonForTables(Integer value) {#setSensitivityOfComparisonForTables-java.lang.Integer-}
```
public void setSensitivityOfComparisonForTables(Integer value)
```


Définit une sensibilité de comparaison pour les tableaux.
Si la valeur est nulle, SensitivityOfComparison est utilisé à la place. Le pourcentage d'éléments supprimés et insérés de deux objets comparés par rapport à l'ensemble des éléments de ces objets.

* if this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs, if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.lang.Integer | La sensibilité de la comparaison pour les tables |
|

### getSensitivityOfComparisonForTables() {#getSensitivityOfComparisonForTables--}
```
public final Integer getSensitivityOfComparisonForTables()
```


Obtient une sensibilité de comparaison pour les tableaux.
Si la valeur est nulle, SensitivityOfComparison est utilisé à la place. Le pourcentage d'éléments supprimés et insérés de deux objets comparés par rapport à l'ensemble des éléments de ces objets.

* if this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs, if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Returns:**
java.lang.Integer - La sensibilité de la comparaison pour les tables

### setWordsSeparatorChars(char[] value) {#setWordsSeparatorChars-char---}
```
public final void setWordsSeparatorChars(char[] value)
```


Définit un tableau de délimiteurs qui sera utilisé pour diviser le texte en mots.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | char[] | Le tableau de délimiteurs pour diviser le texte en mots |
|

### getPasswordSaveOption() {#getPasswordSaveOption--}
```
public final PasswordSaveOption getPasswordSaveOption()
```


Obtient une option d’enregistrement de mot de passe représentée par l’objet [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption).


**Returns:**
[PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) - the password save option

### setPasswordSaveOption(PasswordSaveOption value) {#setPasswordSaveOption-com.groupdocs.comparison.options.enums.PasswordSaveOption-}
```
public final void setPasswordSaveOption(PasswordSaveOption value)
```


Définit une option d’enregistrement de mot de passe représentée par l’objet [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) | L'option d'enregistrement du mot de passe |
|

### getOriginalSize() {#getOriginalSize--}
```
public final OriginalSize getOriginalSize()
```


Obtient les tailles originales des documents comparés représentées par l’objet [OriginalSize](../../com.groupdocs.comparison.options/originalsize).


**Returns:**
[OriginalSize](../../com.groupdocs.comparison.options/originalsize) - the original size of documents

### setOriginalSize(OriginalSize value) {#setOriginalSize-com.groupdocs.comparison.options.OriginalSize-}
```
public final void setOriginalSize(OriginalSize value)
```


Définit les tailles originales des documents comparés représentées par l’objet [OriginalSize](../../com.groupdocs.comparison.options/originalsize).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [OriginalSize](../../com.groupdocs.comparison.options/originalsize) | La taille originale des documents |
|

### getDiagramMasterSetting() {#getDiagramMasterSetting--}
```
public final DiagramMasterSetting getDiagramMasterSetting()
```


Obtient un paramètre de page maître pour les documents Diagram représenté par l’objet [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting).


**Returns:**
[DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) - the diagram master page setting

### setDiagramMasterSetting(DiagramMasterSetting value) {#setDiagramMasterSetting-com.groupdocs.comparison.options.style.DiagramMasterSetting-}
```
public final void setDiagramMasterSetting(DiagramMasterSetting value)
```


Définit un paramètre de page maître pour les documents Diagram représenté par l’objet [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) | Le paramètre de page maître du diagramme |
|

### isDirectoryCompare() {#isDirectoryCompare--}
```
public boolean isDirectoryCompare()
```


Renvoie un indicateur qui indique si la comparaison de répertoires est activée.


**Returns:**
booléen - true si la comparaison de répertoires est activée, sinon false

### setDirectoryCompare(boolean directoryCompare) {#setDirectoryCompare-boolean-}
```
public void setDirectoryCompare(boolean directoryCompare)
```


Définit un indicateur qui indique si la comparaison de répertoires doit être activée.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | directoryCompare | boolean | true si la comparaison de répertoires doit être activée, sinon false |
|

### isShowOnlyChanged() {#isShowOnlyChanged--}
```
public boolean isShowOnlyChanged()
```


Renvoie une valeur booléenne qui indique si seuls les éléments modifiés doivent être affichés.


**Returns:**
booléen - true si seuls les éléments modifiés doivent être affichés, sinon false

### setShowOnlyChanged(boolean showOnlyChanged) {#setShowOnlyChanged-boolean-}
```
public void setShowOnlyChanged(boolean showOnlyChanged)
```


Définit la valeur indiquant si seuls les éléments modifiés doivent être affichés.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | showOnlyChanged | boolean | la valeur booléenne indiquant si seuls les éléments modifiés doivent être affichés |
|

### getFolderComparisonExtension() {#getFolderComparisonExtension--}
```
public FolderComparisonExtension getFolderComparisonExtension()
```


Obtient le format du fichier de comparaison de dossiers résultant.


**Returns:**
com.groupdocs.comparison.options.enums.FolderComparisonExtension - le FolderComparisonExtension représentant le format du fichier de comparaison de dossiers résultant

### setFolderComparisonExtension(FolderComparisonExtension folderComparisonExtension) {#setFolderComparisonExtension-com.groupdocs.comparison.options.enums.FolderComparisonExtension-}
```
public void setFolderComparisonExtension(FolderComparisonExtension folderComparisonExtension)
```


Définit le format du fichier de comparaison de dossiers résultant.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | folderComparisonExtension | com.groupdocs.comparison.options.enums.FolderComparisonExtension | le FolderComparisonExtension représentant le format du fichier de comparaison de dossiers résultant |
|

