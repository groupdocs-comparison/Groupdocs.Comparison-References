---
title: "Comparer"
second_title: "Référence API de GroupDocs.Comparison for Java"
description: "La classe Comparer offre des fonctionnalités pour comparer des documents et générer des résultats de comparaison."
type: docs
weight: 10
url: /fr/java/com.groupdocs.comparison/comparer/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public class Comparer implements System.IDisposable, Closeable
```

La classe Comparer offre des fonctionnalités pour comparer des documents et générer des résultats de comparaison.


Il vous permet de comparer différents types de documents, tels que PDF, Word, Excel, PowerPoint, et plus encore.


Exemple d'utilisation :

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     CompareOptions compareOptions = new CompareOptions();
     compareOptions.setDetectStyleChanges(true);

     comparer.compare(resultFile, compareOptions);
 }
 
````


## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [Comparer(String filePath)](#Comparer-java.lang.String-) | Initialise une nouvelle instance de la classe Comparer avec le chemin du fichier source spécifié. |
|
|  | [Comparer(String filePath, CompareOptions compareOptions)](#Comparer-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | Initialise une nouvelle instance de la classe Comparer avec le chemin du dossier spécifié et les options de comparaison. |
|
|  | [Comparer(Path filePath)](#Comparer-java.nio.file.Path-) | Initialise une nouvelle instance de la classe Comparer avec le chemin du fichier source spécifié. |
|
|  | [Comparer(String filePath, LoadOptions loadOptions)](#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-) | Initialise une nouvelle instance de Comparer avec le chemin du fichier source spécifié et [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions). |
|
|  | [Comparer(Path filePath, LoadOptions loadOptions)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-) | Initialise une nouvelle instance de Comparer avec le chemin du fichier source spécifié et [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions). |
|
|  | [Comparer(Path filePath, CompareOptions compareOptions)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | Initialise une nouvelle instance de Comparer avec le chemin du fichier source spécifié et [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions). |
|
|  | [Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings)](#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-) | Initialise une nouvelle instance de la classe Comparer avec le chemin du fichier source spécifié, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) et [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)](#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-) | Initialise une nouvelle instance de la classe Comparer avec le chemin du fichier source spécifié, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) et [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(String filePath, ComparerSettings settings)](#Comparer-java.lang.String-com.groupdocs.comparison.ComparerSettings-) | Initialise une nouvelle instance de la classe Comparer avec le chemin du fichier source spécifié et [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(Path filePath, ComparerSettings settings)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.ComparerSettings-) | Initialise une nouvelle instance de la classe Comparer avec le chemin du fichier source spécifié et [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-) | Initialise une nouvelle instance de la classe Comparer avec le chemin du fichier source spécifié, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) et [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-) | Initialise une nouvelle instance de la classe Comparer avec le chemin du fichier source spécifié, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) et [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(InputStream document)](#Comparer-java.io.InputStream-) | Initialise une nouvelle instance de la classe Comparer avec le flux du document source spécifié. |
|
|  | [Comparer(InputStream document, LoadOptions loadOptions)](#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-) | Initialise une nouvelle instance de Comparer avec le flux du document source spécifié et [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions). |
|
|  | [Comparer(InputStream document, ComparerSettings settings)](#Comparer-java.io.InputStream-com.groupdocs.comparison.ComparerSettings-) | Initialise une nouvelle instance de la classe Comparer avec le flux du document source spécifié et [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(InputStream document, LoadOptions loadOptions, ComparerSettings settings)](#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-) | Initialise une nouvelle instance de la classe Comparer avec le flux du document spécifié, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) et [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(ComparerSettings settings)](#Comparer-com.groupdocs.comparison.ComparerSettings-) | Initialise une nouvelle instance de la classe Comparer avec les [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
## Champs

| Champ | Description |
| --- | --- |
| [FILE_PATH](#FILE-PATH) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getSource()](#getSource--) | Obtient le document source qui est comparé. |
|
|  | [getTargets()](#getTargets--) | Liste des documents cibles à comparer avec le fichier source. |
|
|  | [compare()](#compare--) | Compare le fichier spécifié avec les documents cibles sans enregistrer le résultat avec les options par défaut. |
|
|  | [compare(String filePath)](#compare-java.lang.String-) | Compare le fichier spécifié avec les documents cibles et génère un résultat de comparaison. |
|
|  | [compare(Path filePath)](#compare-java.nio.file.Path-) | Compare le fichier spécifié avec les documents cibles et génère un résultat de comparaison. |
|
|  | [compare(OutputStream outputStream)](#compare-java.io.OutputStream-) | Compare le fichier spécifié avec les documents cibles et écrit le résultat de comparaison dans le flux de sortie. |
|
|  | [compare(String filePath, CompareOptions compareOptions)](#compare-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | Compare le fichier spécifié avec les documents cibles et écrit le résultat de comparaison dans le chemin de fichier fourni. |
|
|  | [compare(Path filePath, CompareOptions compareOptions)](#compare-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | Compare le fichier spécifié avec les documents cibles et écrit le résultat de comparaison dans le chemin de fichier fourni. |
|
|  | [compare(OutputStream stream, CompareOptions compareOptions)](#compare-java.io.OutputStream-com.groupdocs.comparison.options.CompareOptions-) | Compare le fichier spécifié avec les documents cibles et écrit le résultat de comparaison dans le flux de sortie. |
|
|  | [compare(SaveOptions saveOptions, CompareOptions compareOptions)](#compare-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | Compare le fichier spécifié avec les documents cibles sans enregistrer le résultat. |
|
|  | [compare(String filePath, SaveOptions saveOptions)](#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-) | Compare le fichier spécifié avec les documents cibles et écrit le résultat de comparaison dans le chemin de fichier fourni. |
|
|  | [compare(Path filePath, SaveOptions saveOptions)](#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-) | Compare le fichier spécifié avec les documents cibles et écrit le résultat de comparaison dans le chemin de fichier fourni. |
|
|  | [compare(OutputStream stream, SaveOptions saveOptions)](#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-) | Compare le fichier spécifié avec les documents cibles et écrit le résultat de comparaison dans le chemin de fichier fourni. |
|
|  | [compare(CompareOptions compareOptions)](#compare-com.groupdocs.comparison.options.CompareOptions-) | Compare le fichier spécifié avec les documents cibles sans enregistrer le résultat. |
|
|  | [compare(OutputStream outputStream, SaveOptions saveOptions, CompareOptions compareOptions)](#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | Compare le fichier spécifié avec les documents cibles et écrit le résultat de comparaison dans le flux de sortie fourni. |
|
|  | [compare(String filePath, SaveOptions saveOptions, CompareOptions compareOptions)](#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | Compare le fichier spécifié avec les documents cibles et écrit le résultat de comparaison dans le chemin de fichier fourni. |
|
|  | [compareDirectory(String filePath, CompareOptions compareOptions)](#compareDirectory-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | Compare le répertoire spécifié avec le répertoire cible et enregistre le résultat de comparaison dans le chemin de fichier fourni. |
|
|  | [compareDirectory(Path filePath, CompareOptions compareOptions)](#compareDirectory-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | Compare le répertoire spécifié avec le répertoire cible et enregistre le résultat de comparaison dans le chemin de fichier fourni. |
|
|  | [compare(Path filePath, SaveOptions saveOptions, CompareOptions compareOptions)](#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | Compare le fichier spécifié avec les documents cibles et écrit le résultat de comparaison dans le chemin de fichier fourni. |
|
|  | [add(String filePath)](#add-java.lang.String-) | Ajoute le document cible spécifié au processus de comparaison. |
|
|  | [add(String filePath, CompareOptions compareOptions)](#add-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | Ajoute le document ou le dossier cible spécifié au processus de comparaison. |
|
|  | [add(Path filePath)](#add-java.nio.file.Path-) | Ajoute le document cible spécifié au processus de comparaison. |
|
|  | [add(String[] filePaths)](#add-java.lang.String...-) | Ajoute les documents cibles spécifiés au processus de comparaison. |
|
|  | [add(Path[] filePaths)](#add-java.nio.file.Path...-) | Ajoute les documents cibles spécifiés au processus de comparaison. |
|
|  | [add(String filePath, LoadOptions loadOptions)](#add-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-) | Ajoute le document cible spécifié au processus de comparaison avec les options de chargement spécifiées. |
|
|  | [add(Path filePath, LoadOptions loadOptions)](#add-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-) | Ajoute le document cible spécifié au processus de comparaison avec les options de chargement spécifiées. |
|
|  | [add(Path filePath, CompareOptions compareOptions)](#add-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | Ajoute le document cible spécifié au processus de comparaison avec les options de chargement spécifiées. |
|
|  | [add(InputStream document)](#add-java.io.InputStream-) | Ajoute le document cible spécifié au processus de comparaison. |
|
|  | [add(InputStream[] documents)](#add-java.io.InputStream...-) | Ajoute les documents cibles spécifiés au processus de comparaison. |
|
|  | [add(InputStream document, LoadOptions loadOptions)](#add-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-) | Ajoute le document cible spécifié au processus de comparaison avec les options de chargement spécifiées. |
|
|  | [getChanges()](#getChanges--) | Récupère un tableau d'objets [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) représentant les modifications détectées pendant le processus de comparaison. |
|
|  | [getChanges(GetChangeOptions getChangeOptions)](#getChanges-com.groupdocs.comparison.options.GetChangeOptions-) | Récupère un tableau d'objets [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) représentant les modifications détectées pendant le processus de comparaison. |
|
|  | [applyChanges(String filePath, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.lang.String-com.groupdocs.comparison.options.ApplyChangeOptions-) | Accepte ou rejette les modifications et les applique au document résultat. |
|
|  | [applyChanges(Path filePath, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.ApplyChangeOptions-) | Accepte ou rejette les modifications et les applique au document résultant. |
|
|  | [applyChanges(OutputStream document, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.ApplyChangeOptions-) | Accepte ou rejette les modifications et les applique au document résultant. |
|
|  | [applyChanges(String filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-) | Accepte ou rejette les modifications et les applique au document résultant. |
|
|  | [applyChanges(Path filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-) | Accepte ou rejette les modifications et les applique au document résultant. |
|
|  | [applyChanges(OutputStream document, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-) | Accepte ou rejette les modifications et les applique au document résultant. |
|
|  | [getResultString()](#getResultString--) | Obtient la chaîne de résultat après la comparaison (pour la comparaison de texte uniquement). |
|
|  | [getSourceFolder()](#getSourceFolder--) | Renvoie le dossier source qui est comparé. |
|
|  | [getTargetFolder()](#getTargetFolder--) | Renvoie le dossier cible qui est comparé. |
|
|  | [selfComparisonCheck(Document source, Document target)](#selfComparisonCheck-com.groupdocs.comparison.Document-com.groupdocs.comparison.Document-) | Vérification d'auto-comparaison (e498c23). |
|
|  | [close()](#close--) | Libère les ressources. |
|
### Comparer(String filePath) {#Comparer-java.lang.String-}
```
public Comparer(String filePath)
```


Initialise une nouvelle instance de la classe Comparer avec le chemin du fichier source spécifié.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Le chemin du document source |
|

### Comparer(String filePath, CompareOptions compareOptions) {#Comparer-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(String filePath, CompareOptions compareOptions)
```


Initialise une nouvelle instance de la classe Comparer avec le chemin du dossier spécifié et les options de comparaison.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Le chemin du document source ou du dossier |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Les options de comparaison pour la comparaison de dossiers |
|

### Comparer(Path filePath) {#Comparer-java.nio.file.Path-}
```
public Comparer(Path filePath)
```


Initialise une nouvelle instance de la classe Comparer avec le chemin du fichier source spécifié.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Le chemin du document source |
|

### Comparer(String filePath, LoadOptions loadOptions) {#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Comparer(String filePath, LoadOptions loadOptions)
```


Initialise une nouvelle instance de Comparer avec le chemin du fichier source spécifié et [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Le chemin du document source |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Les options de chargement personnalisées à appliquer au document |
|

### Comparer(Path filePath, LoadOptions loadOptions) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Comparer(Path filePath, LoadOptions loadOptions)
```


Initialise une nouvelle instance de Comparer avec le chemin du fichier source spécifié et [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Le chemin du document source |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Les options de chargement personnalisées à appliquer au document |
|

### Comparer(Path filePath, CompareOptions compareOptions) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(Path filePath, CompareOptions compareOptions)
```


Initialise une nouvelle instance de Comparer avec le chemin du fichier source spécifié et [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Le chemin du document source |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Les options de comparaison pour la comparaison de dossiers |
|

### Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings) {#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings)
```


Initialise une nouvelle instance de la classe Comparer avec le chemin du fichier source spécifié, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) et [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Le chemin du document source |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Les options de chargement personnalisées à appliquer au document |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Les paramètres du comparateur à utiliser pour le processus de comparaison |
|

### Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions) {#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)
```


Initialise une nouvelle instance de la classe Comparer avec le chemin du fichier source spécifié, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) et [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Le chemin du document source, du dossier ou du texte à comparer |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Les options de chargement personnalisées à appliquer au document |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Les paramètres du comparateur à utiliser pour le processus de comparaison |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Les options de comparaison pour la comparaison de dossiers |
|

### Comparer(String filePath, ComparerSettings settings) {#Comparer-java.lang.String-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(String filePath, ComparerSettings settings)
```


Initialise une nouvelle instance de la classe Comparer avec le chemin du fichier source spécifié et [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Le chemin du document source |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Les paramètres du comparateur à utiliser pour le processus de comparaison |
|

### Comparer(Path filePath, ComparerSettings settings) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(Path filePath, ComparerSettings settings)
```


Initialise une nouvelle instance de la classe Comparer avec le chemin du fichier source spécifié et [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Le chemin du document source |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Les paramètres du comparateur à utiliser pour le processus de comparaison |
|

### Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings)
```


Initialise une nouvelle instance de la classe Comparer avec le chemin du fichier source spécifié, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) et [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Le chemin du document source |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Les options de chargement personnalisées à appliquer au document |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Les paramètres du comparateur à utiliser pour le processus de comparaison |
|

### Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)
```


Initialise une nouvelle instance de la classe Comparer avec le chemin du fichier source spécifié, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) et [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Le chemin du document source ou du dossier |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Les options de chargement personnalisées à appliquer au document |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Les paramètres du comparateur à utiliser pour le processus de comparaison |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Les options de comparaison pour la comparaison de dossiers |
|

### Comparer(InputStream document) {#Comparer-java.io.InputStream-}
```
public Comparer(InputStream document)
```


Initialise une nouvelle instance de la classe Comparer avec le flux du document source spécifié.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | document | java.io.InputStream | Le flux d'entrée du document source |
|

### Comparer(InputStream document, LoadOptions loadOptions) {#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Comparer(InputStream document, LoadOptions loadOptions)
```


Initialise une nouvelle instance de Comparer avec le flux du document source spécifié et [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | document | java.io.InputStream | Le flux d'entrée du document source |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Les options de chargement personnalisées à appliquer au document |
|

### Comparer(InputStream document, ComparerSettings settings) {#Comparer-java.io.InputStream-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(InputStream document, ComparerSettings settings)
```


Initialise une nouvelle instance de la classe Comparer avec le flux du document source spécifié et [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | document | java.io.InputStream | Le flux d'entrée du document source |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Les paramètres du comparateur à utiliser pour le processus de comparaison |
|

### Comparer(InputStream document, LoadOptions loadOptions, ComparerSettings settings) {#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(InputStream document, LoadOptions loadOptions, ComparerSettings settings)
```


Initialise une nouvelle instance de la classe Comparer avec le flux du document spécifié, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) et [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | document | java.io.InputStream | Le flux contenant les données d'un document à comparer |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Les options de chargement personnalisées à appliquer au document |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Les paramètres du comparateur à utiliser pour le processus de comparaison |
|

### Comparer(ComparerSettings settings) {#Comparer-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(ComparerSettings settings)
```


Initialise une nouvelle instance de la classe Comparer avec les [ComparerSettings](../../com.groupdocs.comparison/comparersettings).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | les paramètres |
|

### FILE_PATH {#FILE-PATH}
```
public static final String FILE_PATH
```


### getSource() {#getSource--}
```
public final Document getSource()
```


Obtient le document source qui est comparé.


**Returns:**
[Document](../../com.groupdocs.comparison/document) - the source document

### getTargets() {#getTargets--}
```
public final List<Document> getTargets()
```


Liste des documents cibles à comparer avec le fichier source.


**Returns:**
java.util.List<com.groupdocs.comparison.Document> - les documents cibles

### compare() {#compare--}
```
public final Path compare()
```


Compare le fichier spécifié avec les documents cibles sans enregistrer le résultat avec les options par défaut.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Returns:**
java.nio.file.Path - le chemin du document résultat ou null

### compare(String filePath) {#compare-java.lang.String-}
```
public final Path compare(String filePath)
```


Compare le fichier spécifié avec les documents cibles et génère un résultat de comparaison.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Chemin du document résultat |
|

**Returns:**
java.nio.file.Path - chemin du fichier résultat ou null. Dans certaines situations, son extension peut être modifiée

### compare(Path filePath) {#compare-java.nio.file.Path-}
```
public final Path compare(Path filePath)
```


Compare le fichier spécifié avec les documents cibles et génère un résultat de comparaison.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Chemin du document résultat |
|

**Returns:**
java.nio.file.Path - chemin du fichier résultat, dans certaines situations, son extension peut être modifiée

### compare(OutputStream outputStream) {#compare-java.io.OutputStream-}
```
public final Path compare(OutputStream outputStream)
```


Compare le fichier spécifié avec les documents cibles et écrit le résultat de comparaison dans le flux de sortie.


Remarque : dans les cas où la valeur de retour est null, utilisez les données qui ont été écrites dans outputStream

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | outputStream | java.io.OutputStream | Flux du document résultat |
|

**Returns:**
java.nio.file.Path - chemin du fichier résultat ou null lorsque les données de  outputStream  doivent être utilisées. Dans certaines situations, l'extension du fichier résultat peut être modifiée

### compare(String filePath, CompareOptions compareOptions) {#compare-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(String filePath, CompareOptions compareOptions)
```


Compare le fichier spécifié avec les documents cibles et écrit le résultat de comparaison dans le chemin de fichier fourni.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Chemin du fichier du document résultat |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Les options de comparaison à utiliser pour le processus de comparaison |
|

**Returns:**
java.nio.file.Path - chemin du fichier résultat, dans certaines situations, son extension peut être modifiée

### compare(Path filePath, CompareOptions compareOptions) {#compare-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(Path filePath, CompareOptions compareOptions)
```


Compare le fichier spécifié avec les documents cibles et écrit le résultat de comparaison dans le chemin de fichier fourni.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Chemin du fichier du document résultat |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Les options de comparaison à utiliser pour le processus de comparaison |
|

**Returns:**
java.nio.file.Path - chemin du fichier résultat, dans certaines situations, son extension peut être modifiée

### compare(OutputStream stream, CompareOptions compareOptions) {#compare-java.io.OutputStream-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(OutputStream stream, CompareOptions compareOptions)
```


Compare le fichier spécifié avec les documents cibles et écrit le résultat de comparaison dans le flux de sortie.


Remarque : si la valeur de retour est null, utilisez les données qui ont été écrites dans outputStream.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | flux | java.io.OutputStream | Flux du document résultat |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Les options de comparaison à utiliser pour le processus de comparaison |
|

**Returns:**
java.nio.file.Path - chemin du fichier résultat ou null lorsque les données de  outputStream  doivent être utilisées. Dans certaines situations, l'extension du fichier résultat peut être modifiée

### compare(SaveOptions saveOptions, CompareOptions compareOptions) {#compare-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(SaveOptions saveOptions, CompareOptions compareOptions)
```


Compare le fichier spécifié avec les documents cibles sans enregistrer le résultat.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparison options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Options d'enregistrement |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Les options de comparaison à utiliser pour le processus de comparaison |
|

**Returns:**
java.nio.file.Path - le chemin du document résultat ou null

### compare(String filePath, SaveOptions saveOptions) {#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-}
```
public final Path compare(String filePath, SaveOptions saveOptions)
```


Compare le fichier spécifié avec les documents cibles et écrit le résultat de comparaison dans le chemin de fichier fourni.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Chemin du fichier du document résultat |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Options d'enregistrement |
|

**Returns:**
java.nio.file.Path - chemin du fichier résultat, dans certaines situations, son extension peut être modifiée

### compare(Path filePath, SaveOptions saveOptions) {#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-}
```
public final Path compare(Path filePath, SaveOptions saveOptions)
```


Compare le fichier spécifié avec les documents cibles et écrit le résultat de comparaison dans le chemin de fichier fourni.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Chemin du fichier du document résultat |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Options d'enregistrement |
|

**Returns:**
java.nio.file.Path - chemin du fichier résultat, dans certaines situations, son extension peut être modifiée

### compare(OutputStream stream, SaveOptions saveOptions) {#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-}
```
public final Path compare(OutputStream stream, SaveOptions saveOptions)
```


Compare le fichier spécifié avec les documents cibles et écrit le résultat de comparaison dans le chemin de fichier fourni.


Remarque : dans le cas où la valeur de retour est nulle, utilisez les données qui ont été écrites dans outputStream

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | flux | java.io.OutputStream | Flux du document résultat |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Options d'enregistrement |
|

**Returns:**
java.nio.file.Path - chemin du fichier résultat ou null lorsque les données de  outputStream  doivent être utilisées. Dans certaines situations, l'extension du fichier résultat peut être modifiée

### compare(CompareOptions compareOptions) {#compare-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(CompareOptions compareOptions)
```


Compare le fichier spécifié avec les documents cibles sans enregistrer le résultat.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Les options de comparaison à utiliser pour le processus de comparaison |
|

**Returns:**
java.nio.file.Path - le chemin du fichier résultat ou null

### compare(OutputStream outputStream, SaveOptions saveOptions, CompareOptions compareOptions) {#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(OutputStream outputStream, SaveOptions saveOptions, CompareOptions compareOptions)
```


Compare le fichier spécifié avec les documents cibles et écrit le résultat de comparaison dans le flux de sortie fourni.


Remarque : dans le cas où la valeur de retour est nulle, utilisez les données qui ont été écrites dans outputStream

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | outputStream | java.io.OutputStream | Flux du document résultat |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Les options d’enregistrement à utiliser pour enregistrer le document résultat |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Les options de comparaison à utiliser pour le processus de comparaison |
|

**Returns:**
java.nio.file.Path - chemin du fichier résultat ou null lorsque les données de  outputStream  doivent être utilisées. Dans certaines situations, l'extension du fichier résultat peut être modifiée

### compare(String filePath, SaveOptions saveOptions, CompareOptions compareOptions) {#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(String filePath, SaveOptions saveOptions, CompareOptions compareOptions)
```


Compare le fichier spécifié avec les documents cibles et écrit le résultat de comparaison dans le chemin de fichier fourni.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparison options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Chemin du fichier du document résultat |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Les options d’enregistrement à utiliser pour enregistrer le document résultat |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Les options de comparaison à utiliser pour le processus de comparaison |
|

**Returns:**
java.nio.file.Path - chemin du fichier résultat, dans certaines situations, son extension peut être modifiée

### compareDirectory(String filePath, CompareOptions compareOptions) {#compareDirectory-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public void compareDirectory(String filePath, CompareOptions compareOptions)
```


Compare le répertoire spécifié avec le répertoire cible et enregistre le résultat de comparaison dans le chemin de fichier fourni.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Le chemin du fichier où le résultat de la comparaison sera enregistré. |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Les options à utiliser pour le processus de comparaison de répertoires. |
|

### compareDirectory(Path filePath, CompareOptions compareOptions) {#compareDirectory-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public void compareDirectory(Path filePath, CompareOptions compareOptions)
```


Compare le répertoire spécifié avec le répertoire cible et enregistre le résultat de comparaison dans le chemin de fichier fourni.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Le chemin du fichier où le résultat de la comparaison sera enregistré. |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Les options à utiliser pour le processus de comparaison de répertoires. |
|

### compare(Path filePath, SaveOptions saveOptions, CompareOptions compareOptions) {#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(Path filePath, SaveOptions saveOptions, CompareOptions compareOptions)
```


Compare le fichier spécifié avec les documents cibles et écrit le résultat de comparaison dans le chemin de fichier fourni.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Chemin du fichier du document résultat |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Les options d’enregistrement à utiliser pour enregistrer le document résultat |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Les options de comparaison à utiliser pour le processus de comparaison |
|

**Returns:**
java.nio.file.Path - chemin du fichier résultat, dans certaines situations, son extension peut être modifiée

### add(String filePath) {#add-java.lang.String-}
```
public final void add(String filePath)
```


Ajoute le document cible spécifié au processus de comparaison.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Le chemin vers le document cible à ajouter |
|

### add(String filePath, CompareOptions compareOptions) {#add-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public void add(String filePath, CompareOptions compareOptions)
```


Ajoute le document ou le dossier cible spécifié au processus de comparaison.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Le chemin vers le document ou le dossier cible à ajouter |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Les options pour la comparaison |
|

### add(Path filePath) {#add-java.nio.file.Path-}
```
public final void add(Path filePath)
```


Ajoute le document cible spécifié au processus de comparaison.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Le chemin vers le document cible à ajouter |
|

### add(String[] filePaths) {#add-java.lang.String...-}
```
public final void add(String[] filePaths)
```


Ajoute les documents cibles spécifiés au processus de comparaison.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePaths | java.lang.String[] | Chemins vers les documents cibles à ajouter |
|

### add(Path[] filePaths) {#add-java.nio.file.Path...-}
```
public final void add(Path[] filePaths)
```


Ajoute les documents cibles spécifiés au processus de comparaison.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePaths | java.nio.file.Path[] | Chemins vers les documents cibles à ajouter |
|

### add(String filePath, LoadOptions loadOptions) {#add-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-}
```
public final void add(String filePath, LoadOptions loadOptions)
```


Ajoute le document cible spécifié au processus de comparaison avec les options de chargement spécifiées.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Chemin vers le document cible à ajouter |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Les options de chargement personnalisées à appliquer au document |
|

### add(Path filePath, LoadOptions loadOptions) {#add-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-}
```
public final void add(Path filePath, LoadOptions loadOptions)
```


Ajoute le document cible spécifié au processus de comparaison avec les options de chargement spécifiées.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Chemin vers le document cible à ajouter |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Les options de chargement personnalisées à appliquer au document |
|

### add(Path filePath, CompareOptions compareOptions) {#add-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public final void add(Path filePath, CompareOptions compareOptions)
```


Ajoute le document cible spécifié au processus de comparaison avec les options de chargement spécifiées.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Le chemin vers le document ou le dossier cible à ajouter |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Les options pour la comparaison |
|

### add(InputStream document) {#add-java.io.InputStream-}
```
public final void add(InputStream document)
```


Ajoute le document cible spécifié au processus de comparaison.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | document | java.io.InputStream | Le flux contenant les données d'un document à comparer |
|

### add(InputStream[] documents) {#add-java.io.InputStream...-}
```
public final void add(InputStream[] documents)
```


Ajoute les documents cibles spécifiés au processus de comparaison.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | documents | java.io.InputStream[] | Flux contenant les données des documents à comparer |
|

### add(InputStream document, LoadOptions loadOptions) {#add-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-}
```
public final void add(InputStream document, LoadOptions loadOptions)
```


Ajoute le document cible spécifié au processus de comparaison avec les options de chargement spécifiées.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | document | java.io.InputStream | Le flux contenant les données d'un document à comparer |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Les options de chargement personnalisées à appliquer au document |
|

### getChanges() {#getChanges--}
```
public final ChangeInfo[] getChanges()
```


Récupère un tableau d'objets [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) représentant les modifications détectées pendant le processus de comparaison.


Utilisez cette méthode pour obtenir des informations détaillées sur les modifications entre le document source et le(s) document(s) cible(s).
Chaque objet [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) contient des informations telles que le type de modification, la zone affectée,
et le contenu avant et après la modification.

* More about how to obtain collection of detected differences between compared documents in Java: [How to get list of changes between documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Get+list+of+changes)
* More about how to get changes coordinates at pages image preview when comparing documents using GroupDocs.Comparison for Java: [How to get changes coordinates programmatically](../https://docs.groupdocs.com/display/comparisonjava/Get+changes+coordinates)


**Returns:**
com.groupdocs.comparison.result.ChangeInfo[] - un tableau d’objets [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) représentant les modifications détectées pendant le processus de comparaison

### getChanges(GetChangeOptions getChangeOptions) {#getChanges-com.groupdocs.comparison.options.GetChangeOptions-}
```
public final ChangeInfo[] getChanges(GetChangeOptions getChangeOptions)
```


Récupère un tableau d'objets [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) représentant les modifications détectées pendant le processus de comparaison.


Utilisez cette méthode pour obtenir des informations détaillées sur les modifications entre le document source et le(s) document(s) cible(s).
Chaque objet [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) contient des informations telles que le type de modification, la zone affectée,
et le contenu avant et après la modification.


Le paramètre [GetChangeOptions](../../com.groupdocs.comparison.options/getchangeoptions) permet de filtrer les changements de manière différente.

* More about how to obtain collection of detected differences between compared documents in Java: [How to get list of changes between documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Get+list+of+changes)
* More about how to get changes coordinates at pages image preview when comparing documents using GroupDocs.Comparison for Java: [How to get changes coordinates programmatically](../https://docs.groupdocs.com/display/comparisonjava/Get+changes+coordinates)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | getChangeOptions | [GetChangeOptions](../../com.groupdocs.comparison.options/getchangeoptions) | L’objet qui permet de filtrer les changements |
|

**Returns:**
com.groupdocs.comparison.result.ChangeInfo[] - un tableau d’objets [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) représentant les modifications détectées pendant le processus de comparaison

### applyChanges(String filePath, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.lang.String-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(String filePath, ApplyChangeOptions applyChangeOptions)
```


Accepte ou rejette les modifications et les applique au document résultat.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Chemin du fichier du document résultat |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | Les options personnalisées d’application des changements pour configurer le processus d’application des changements |
|

### applyChanges(Path filePath, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(Path filePath, ApplyChangeOptions applyChangeOptions)
```


Accepte ou rejette les modifications et les applique au document résultant.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Chemin du fichier du document résultat |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | Les options personnalisées d’application des changements pour configurer le processus d’application des changements |
|

### applyChanges(OutputStream document, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(OutputStream document, ApplyChangeOptions applyChangeOptions)
```


Accepte ou rejette les modifications et les applique au document résultant.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | document | java.io.OutputStream | Flux de sortie du document résultat |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | Les options personnalisées d’application des changements pour configurer le processus d’application des changements |
|

### applyChanges(String filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(String filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)
```


Accepte ou rejette les modifications et les applique au document résultant.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Chemin du fichier du document résultat |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Les options d’enregistrement pour configurer l’enregistrement du document résultat |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | Les options personnalisées d’application des changements pour configurer le processus d’application des changements |
|

### applyChanges(Path filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(Path filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)
```


Accepte ou rejette les modifications et les applique au document résultant.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Chemin du fichier du document résultat |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Les options d’enregistrement pour configurer l’enregistrement du document résultat |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | Les options personnalisées d’application des changements pour configurer le processus d’application des changements |
|

### applyChanges(OutputStream document, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(OutputStream document, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)
```


Accepte ou rejette les modifications et les applique au document résultant.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | document | java.io.OutputStream | Flux de sortie du document résultat |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Les options d’enregistrement pour configurer l’enregistrement du document résultat |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | Les options personnalisées d’application des changements pour configurer le processus d’application des changements |
|

### getResultString() {#getResultString--}
```
public String getResultString()
```


Obtient la chaîne de résultat après la comparaison (pour la comparaison de texte uniquement).


**Returns:**
java.lang.String - la chaîne résultat

### getSourceFolder() {#getSourceFolder--}
```
public String getSourceFolder()
```


Renvoie le dossier source qui est comparé.


**Returns:**
java.lang.String - le dossier source

### getTargetFolder() {#getTargetFolder--}
```
public String getTargetFolder()
```


Renvoie le dossier cible qui est comparé.


**Returns:**
java.lang.String - le dossier cible

### selfComparisonCheck(Document source, Document target) {#selfComparisonCheck-com.groupdocs.comparison.Document-com.groupdocs.comparison.Document-}
```
public static void selfComparisonCheck(Document source, Document target)
```


Vérification d'auto‑comparaison (e498c23). C# 7a7668c interne ; conservé public afin que les tests core.common puissent l’appeler.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [Document](../../com.groupdocs.comparison/document) |  |
| target | [Document](../../com.groupdocs.comparison/document) |  |

### close() {#close--}
```
public void close()
```


Libère les ressources.


