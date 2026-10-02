---
title: "RevisionHandler"
second_title: "Référence API de GroupDocs.Comparison for Java"
description: "Représente une classe qui contrôle la gestion des révisions."
type: docs
weight: 11
url: /fr/java/com.groupdocs.comparison.words.revision/revisionhandler/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class RevisionHandler implements Closeable
```

Représente une classe qui contrôle la gestion des révisions.


La classe RevisionHandler vous permet de travailler avec les révisions dans les documents.
Il fournit des méthodes pour récupérer la liste des révisions, appliquer les modifications aux révisions et enregistrer le document modifié.


Exemple d'utilisation :

````

 try (RevisionHandler revisionHandler = new RevisionHandler(sourceFile)) {
     List revisionList = revisionHandler.getRevisions();

     for (RevisionInfo revisionInfo : revisionList) {
         if (revisionInfo.getType() == RevisionType.DELETION)
             // Set an action to be applied to the revision
             revisionInfo.setAction(RevisionAction.Accept);
     }
     // Create an instance of ApplyRevisionOptions
     ApplyRevisionOptions revisionChanges = new ApplyRevisionOptions();
     revisionChanges.setChanges(revisionList);
     // Apply the revisions using the options
     revisionHandler.applyRevisionChanges(resultFile, revisionChanges);
 }
 
````


## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [RevisionHandler(String filePath)](#RevisionHandler-java.lang.String-) | Initialise une nouvelle instance de la classe RevisionHandler avec le chemin du fichier contenant les révisions. |
|
|  | [RevisionHandler(Path filePath)](#RevisionHandler-java.nio.file.Path-) | Initialise une nouvelle instance de la classe RevisionHandler avec le chemin du fichier contenant les révisions. |
|
|  | [RevisionHandler(InputStream file, FileType fileType)](#RevisionHandler-java.io.InputStream-com.groupdocs.comparison.result.FileType-) | Initialise une nouvelle instance de la classe RevisionHandler avec un flux de fichier contenant les révisions. |
|
|  | [RevisionHandler(Document document)](#RevisionHandler-com.aspose.words.Document-) | Initialise une nouvelle instance de la classe RevisionHandler avec un document. |
|
## Champs

| Champ | Description |
| --- | --- |
| [SOURCE_PATH_IS_NULL](#SOURCE-PATH-IS-NULL) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getRevisions()](#getRevisions--) | Obtient la liste de toutes les révisions. |
|
|  | [applyRevisionChanges(ApplyRevisionOptions changes)](#applyRevisionChanges-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | Traite les modifications des révisions et les applique au fichier original. |
|
|  | [applyRevisionChanges(Path filePath, ApplyRevisionOptions changes)](#applyRevisionChanges-java.nio.file.Path-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | Traite les modifications des révisions et écrit le résultat dans le fichier spécifié. |
|
|  | [applyRevisionChanges(String filePath, ApplyRevisionOptions changes)](#applyRevisionChanges-java.lang.String-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | Traite les modifications des révisions et écrit le résultat dans le fichier spécifié. |
|
|  | [applyRevisionChanges(OutputStream outputStream, ApplyRevisionOptions changes)](#applyRevisionChanges-java.io.OutputStream-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | Traite les modifications des révisions et écrit le résultat dans le flux du document. |
|
| [close()](#close--) |  |
### RevisionHandler(String filePath) {#RevisionHandler-java.lang.String-}
```
public RevisionHandler(String filePath)
```


Initialise une nouvelle instance de la classe RevisionHandler avec le chemin du fichier contenant les révisions.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Le chemin du fichier. |
|

### RevisionHandler(Path filePath) {#RevisionHandler-java.nio.file.Path-}
```
public RevisionHandler(Path filePath)
```


Initialise une nouvelle instance de la classe RevisionHandler avec le chemin du fichier contenant les révisions.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Le chemin du fichier. |
|

### RevisionHandler(InputStream file, FileType fileType) {#RevisionHandler-java.io.InputStream-com.groupdocs.comparison.result.FileType-}
```
public RevisionHandler(InputStream file, FileType fileType)
```


Initialise une nouvelle instance de la classe RevisionHandler avec un flux de fichier contenant les révisions.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fichier | java.io.InputStream | Le flux du document source. |
|
|  | fileType | [FileType](../../com.groupdocs.comparison.result/filetype) | Le type du fichier. |
|

### RevisionHandler(Document document) {#RevisionHandler-com.aspose.words.Document-}
```
public RevisionHandler(Document document)
```


Initialise une nouvelle instance de la classe RevisionHandler avec un document.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | document | com.aspose.words.Document | Le document. |
|

### SOURCE_PATH_IS_NULL {#SOURCE-PATH-IS-NULL}
```
public static final String SOURCE_PATH_IS_NULL
```


### getRevisions() {#getRevisions--}
```
public List<RevisionInfo> getRevisions()
```


Obtient la liste de toutes les révisions.


En raison du fait que les révisions étaient initialement triées dans un groupe, les révisions doivent être extraites d'une List.
Dans la List, une seule révision peut être divisée en plusieurs révisions avec le même texte général.
Étant donné que la List peut contenir des révisions avec le même texte général, cela doit être contrôlé lors de la création d'une liste de révisions pour l'utilisateur.
Cela est contrôlé ici en utilisant les groupes List\<RevisionGroup\>.


**Returns:**
java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> - la liste des révisions.

### applyRevisionChanges(ApplyRevisionOptions changes) {#applyRevisionChanges-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(ApplyRevisionOptions changes)
```


Traite les modifications des révisions et les applique au fichier original.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | La liste des révisions modifiées. |
|

### applyRevisionChanges(Path filePath, ApplyRevisionOptions changes) {#applyRevisionChanges-java.nio.file.Path-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(Path filePath, ApplyRevisionOptions changes)
```


Traite les modifications des révisions et écrit le résultat dans le fichier spécifié.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Le chemin du fichier résultat. |
|
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | La liste des révisions modifiées. |
|

### applyRevisionChanges(String filePath, ApplyRevisionOptions changes) {#applyRevisionChanges-java.lang.String-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(String filePath, ApplyRevisionOptions changes)
```


Traite les modifications des révisions et écrit le résultat dans le fichier spécifié.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Le chemin du fichier résultat. |
|
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | La liste des révisions modifiées. |
|

### applyRevisionChanges(OutputStream outputStream, ApplyRevisionOptions changes) {#applyRevisionChanges-java.io.OutputStream-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(OutputStream outputStream, ApplyRevisionOptions changes)
```


Traite les modifications des révisions et écrit le résultat dans le flux du document.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | outputStream | java.io.OutputStream | Le flux du document résultat. |
|
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | La liste des révisions modifiées. |
|

### close() {#close--}
```
public void close()
```




