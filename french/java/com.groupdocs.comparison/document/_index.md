---
title: "Document"
second_title: "Référence API de GroupDocs.Comparison for Java"
description: "Représente un document pour le processus de comparaison."
type: docs
weight: 12
url: /fr/java/com.groupdocs.comparison/document/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Document implements Closeable
```

Représente un document pour le processus de comparaison.


La classe Document fournit des méthodes pour charger, générer des images d'aperçu et manipuler les documents pendant le processus de comparaison.


Exemple d'utilisation :

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     try (IDocumentInfo info = comparer.getSource().getDocumentInfo()) {
         System.out.println("File type: " + info.getFileType());
         System.out.println("Number of pages: " + info.getPageCount());
         System.out.println("Document size: " + info.getSize());
     }
 }
 
````


## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [Document(InputStream stream)](#Document-java.io.InputStream-) | Initialise une nouvelle instance de la classe Document avec le flux de document spécifié. |
|
|  | [Document(String filePath)](#Document-java.lang.String-) | Initialise une nouvelle instance de la classe Document avec le chemin de document spécifié. |
|
|  | [Document(Path filePath)](#Document-java.nio.file.Path-) | Initialise une nouvelle instance de la classe Document avec le chemin de document spécifié. |
|
|  | [Document(Path filePath, String password)](#Document-java.nio.file.Path-java.lang.String-) | Initialise une nouvelle instance de la classe Document avec le chemin de document spécifié et un mot de passe. |
|
|  | [Document(Path filePath, LoadOptions loadOptions)](#Document-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-) | Initialise une nouvelle instance de la classe Document avec le chemin de document spécifié et les options de chargement. |
|
|  | [Document(String filePath, String password)](#Document-java.lang.String-java.lang.String-) | Initialise une nouvelle instance de la classe Document avec le chemin de document spécifié et un mot de passe. |
|
|  | [Document(String filePath, LoadOptions loadOptions)](#Document-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-) | Initialise une nouvelle instance de la classe Document avec le chemin de document spécifié et les options de chargement. |
|
|  | [Document(InputStream stream, String password)](#Document-java.io.InputStream-java.lang.String-) | Initialise une nouvelle instance de la classe Document avec le flux de document spécifié et un mot de passe. |
|
|  | [Document(String filePathOrTextContent, boolean isLoadText)](#Document-java.lang.String-boolean-) | Initialise une nouvelle instance de la classe Document avec le chemin de document ou le contenu texte spécifié et un indicateur qui indique ce qui a été passé. |
|
|  | [Document(InputStream inputStream, LoadOptions loadOptions)](#Document-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-) | Initialise une nouvelle instance de la classe Document avec le flux de document spécifié et les options de chargement. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getChanges()](#getChanges--) | Obtient une liste d'objets [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) représentant les modifications détectées pendant le processus de comparaison. |
|
|  | [setChanges(List<ChangeInfo> value)](#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--) | Définit une liste d'objets [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) représentant les modifications détectées pendant le processus de comparaison. |
|
|  | [getName()](#getName--) | Obtient le nom du document. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Définit le nom du document. |
|
|  | [getFileType()](#getFileType--) | Obtient le type du document. |
|
|  | [setFileType(FileType fileType)](#setFileType-com.groupdocs.comparison.result.FileType-) | Définit le type du document. |
|
|  | [createStream()](#createStream--) | Crée un nouveau flux avec le contenu du document. |
|
|  | [getStreamLength()](#getStreamLength--) | Obtient la taille du document |
|
|  | [getPassword()](#getPassword--) | Obtient le mot de passe du document |
|
|  | [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.comparison.options.PreviewOptions-) | Génère des aperçus de document basés sur les [PreviewOptions](../../com.groupdocs.comparison.options/previewoptions) fournis. |
|
|  | [getDocumentInfo()](#getDocumentInfo--) | Obtient des informations sur le document, y compris le type de document, le nombre de pages, les tailles de page et plus encore. |
|
| [close()](#close--) |  |
### Document(InputStream stream) {#Document-java.io.InputStream-}
```
public Document(InputStream stream)
```


Initialise une nouvelle instance de la classe Document avec le flux de document spécifié.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | flux | java.io.InputStream | Flux du document |
|

### Document(String filePath) {#Document-java.lang.String-}
```
public Document(String filePath)
```


Initialise une nouvelle instance de la classe Document avec le chemin de document spécifié.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Chemin du document |
|

### Document(Path filePath) {#Document-java.nio.file.Path-}
```
public Document(Path filePath)
```


Initialise une nouvelle instance de la classe Document avec le chemin de document spécifié.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Chemin du document |
|

### Document(Path filePath, String password) {#Document-java.nio.file.Path-java.lang.String-}
```
public Document(Path filePath, String password)
```


Initialise une nouvelle instance de la classe Document avec le chemin de document spécifié et un mot de passe.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Chemin du document |
|
|  | mot de passe | java.lang.String | Mot de passe du document |
|

### Document(Path filePath, LoadOptions loadOptions) {#Document-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Document(Path filePath, LoadOptions loadOptions)
```


Initialise une nouvelle instance de la classe Document avec le chemin de document spécifié et les options de chargement.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Chemin du document |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Options de chargement |
|

### Document(String filePath, String password) {#Document-java.lang.String-java.lang.String-}
```
public Document(String filePath, String password)
```


Initialise une nouvelle instance de la classe Document avec le chemin de document spécifié et un mot de passe.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Chemin du document |
|
|  | mot de passe | java.lang.String | Mot de passe du document |
|

### Document(String filePath, LoadOptions loadOptions) {#Document-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Document(String filePath, LoadOptions loadOptions)
```


Initialise une nouvelle instance de la classe Document avec le chemin de document spécifié et les options de chargement.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Chemin du document |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Options de chargement |
|

### Document(InputStream stream, String password) {#Document-java.io.InputStream-java.lang.String-}
```
public Document(InputStream stream, String password)
```


Initialise une nouvelle instance de la classe Document avec le flux de document spécifié et un mot de passe.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | flux | java.io.InputStream | Flux du document |
|
|  | mot de passe | java.lang.String | Mot de passe du document |
|

### Document(String filePathOrTextContent, boolean isLoadText) {#Document-java.lang.String-boolean-}
```
public Document(String filePathOrTextContent, boolean isLoadText)
```


Initialise une nouvelle instance de la classe Document avec le chemin de document ou le contenu texte spécifié et un indicateur qui indique ce qui a été passé.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePathOrTextContent | java.lang.String | le chemin du fichier |
|
|  | isLoadText | boolean | le texte chargé |
|

### Document(InputStream inputStream, LoadOptions loadOptions) {#Document-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Document(InputStream inputStream, LoadOptions loadOptions)
```


Initialise une nouvelle instance de la classe Document avec le flux de document spécifié et les options de chargement.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | inputStream | java.io.InputStream | Flux du document |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Options de chargement |
|

### getChanges() {#getChanges--}
```
public final List<ChangeInfo> getChanges()
```


Obtient une liste d'objets [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) représentant les modifications détectées pendant le processus de comparaison.


Utilisez cette méthode pour obtenir des informations détaillées sur les modifications entre le document source et le(s) document(s) cible(s).
Chaque objet [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) contient des informations telles que le type de modification, la zone affectée,
et le contenu avant et après la modification.


**Returns:**
java.util.List<com.groupdocs.comparison.result.ChangeInfo> - une liste d'objets [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) représentant les modifications détectées pendant le processus de comparaison

### setChanges(List<ChangeInfo> value) {#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--}
```
public final void setChanges(List<ChangeInfo> value)
```


Définit une liste d'objets [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) représentant les modifications détectées pendant le processus de comparaison.


Utilisez cette méthode pour obtenir des informations détaillées sur les modifications entre le document source et le(s) document(s) cible(s).
Chaque objet [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) contient des informations telles que le type de modification, la zone affectée,
et le contenu avant et après la modification.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | java.util.List<com.groupdocs.comparison.result.ChangeInfo> | une liste d'objets [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) représentant les modifications détectées pendant le processus de comparaison |
|

### getName() {#getName--}
```
public final String getName()
```


Obtient le nom du document.


**Returns:**
java.lang.String - le nom du document

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Définit le nom du document.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.lang.String | le nom du document |
|

### getFileType() {#getFileType--}
```
public FileType getFileType()
```


Obtient le type du document.


**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the type of the document

### setFileType(FileType fileType) {#setFileType-com.groupdocs.comparison.result.FileType-}
```
public void setFileType(FileType fileType)
```


Définit le type du document.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.comparison.result/filetype) | le type du document |
|

### createStream() {#createStream--}
```
public InputStream createStream()
```


Crée un nouveau flux avec le contenu du document.


**Returns:**
java.io.InputStream - le flux contenant le contenu du document

### getStreamLength() {#getStreamLength--}
```
public long getStreamLength()
```


Obtient la taille du document


**Returns:**
long - la taille du document

### getPassword() {#getPassword--}
```
public String getPassword()
```


Obtient le mot de passe du document


**Returns:**
java.lang.String - le mot de passe du document

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.comparison.options.PreviewOptions-}
```
public final void generatePreview(PreviewOptions previewOptions)
```


Génère des aperçus de document basés sur les [PreviewOptions](../../com.groupdocs.comparison.options/previewoptions) fournis.


Cette méthode génère des aperçus des pages du document selon les options spécifiées, telles que le format d'aperçu,
les numéros de page et le fournisseur de flux de sortie. Les aperçus générés peuvent être enregistrés ou traités davantage selon les besoins.

* Learn more about how to generate previews for document pages: [How to generate document pages preview using GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Generate+document+pages+preview)


Exemple d'utilisation :

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     PreviewOptions previewOptions = new PreviewOptions(
             pageNumber -> Files.newOutputStream(Paths.get("preview-image-page-" + pageNumber + ".png"))
     );
     previewOptions.setPreviewFormat(PreviewFormats.PNG);
     previewOptions.setPageNumbers(new int[]{1, 2});
     comparer.getSource().generatePreview(previewOptions);
 }
 
````



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | previewOptions | [PreviewOptions](../../com.groupdocs.comparison.options/previewoptions) | Les options d'aperçu spécifiant le format, les numéros de page, etc. |
|

### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Obtient des informations sur le document, y compris le type de document, le nombre de pages, les tailles de page et plus encore.

* Learn more about document file type, page count, size, and other format-specific properties: [How to get document info using GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Get+file+info)


**Returns:**
[IDocumentInfo](../../com.groupdocs.comparison.interfaces/idocumentinfo) - the document information

### close() {#close--}
```
public void close()
```




