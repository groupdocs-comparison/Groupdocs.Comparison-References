---
title: "IDocumentInfo"
second_title: "Référence API de GroupDocs.Comparison for Java"
description: "Fournit l'accès aux propriétés du document."
type: docs
weight: 10
url: /fr/java/com.groupdocs.comparison.interfaces/idocumentinfo/
---
**All Implemented Interfaces:**
java.io.Closeable
```
public interface IDocumentInfo extends Closeable
```

Fournit l'accès aux propriétés du document.


Plus de détails sur son utilisation peuvent être trouvés dans la méthode [Document.getDocumentInfo()](../../com.groupdocs.comparison/document#getDocumentInfo--) ou dans une [documentation](../https://docs.groupdocs.com/comparison/java/get-file-info/).


Exemple d'utilisation :

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    try (IDocumentInfo documentInfo = comparer.getSource().getDocumentInfo()) {
      for (int i = 0; i < documentInfo.getPageCount(); i++) {
          System.out.printf("File type: %s%nNumber of pages: %d", documentInfo.getFileType().getFileFormat(), documentInfo.getPageCount());
      }
    }
 }
 
````


## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getFileType()](#getFileType--) | Obtient le type du fichier représenté par l'énumération [FileType](../../com.groupdocs.comparison.result/filetype). |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.comparison.result.FileType-) | Définit le type du fichier en utilisant l'énumération [FileType](../../com.groupdocs.comparison.result/filetype). |
|
|  | [getPageCount()](#getPageCount--) | Obtient le nombre du fichier. |
|
|  | [setPageCount(int value)](#setPageCount-int-) | Définit le nombre du fichier. |
|
|  | [getSize()](#getSize--) | Obtient la taille du fichier. |
|
|  | [setSize(long value)](#setSize-long-) | Définit la taille du fichier. |
|
|  | [getPagesInfo()](#getPagesInfo--) | Obtient les informations pour chaque page du fichier en utilisant la classe [PageInfo](../../com.groupdocs.comparison.result/pageinfo). |
|
|  | [setPagesInfo(List<PageInfo> pageInfos)](#setPagesInfo-java.util.List-com.groupdocs.comparison.result.PageInfo--) | Définit les informations pour chaque page du fichier en utilisant la classe [PageInfo](../../com.groupdocs.comparison.result/pageinfo). |
|
|  | [close()](#close--) | Détruit l'objet, rendant impossible l'obtention des informations du document en utilisant cette instance de l'objet [IDocumentInfo](../../com.groupdocs.comparison.interfaces/idocumentinfo). |
|
### getFileType() {#getFileType--}
```
public abstract FileType getFileType()
```


Obtient le type du fichier représenté par l'énumération [FileType](../../com.groupdocs.comparison.result/filetype).


**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the type of the file

### setFileType(FileType value) {#setFileType-com.groupdocs.comparison.result.FileType-}
```
public abstract void setFileType(FileType value)
```


Définit le type du fichier en utilisant l'énumération [FileType](../../com.groupdocs.comparison.result/filetype).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [FileType](../../com.groupdocs.comparison.result/filetype) | Le type du fichier |
|

### getPageCount() {#getPageCount--}
```
public abstract int getPageCount()
```


Obtient le nombre du fichier.


**Returns:**
int - le nombre du fichier

### setPageCount(int value) {#setPageCount-int-}
```
public abstract void setPageCount(int value)
```


Définit le nombre du fichier.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | int | Le nombre du fichier |
|

### getSize() {#getSize--}
```
public abstract long getSize()
```


Obtient la taille du fichier.


**Returns:**
long - la taille du fichier

### setSize(long value) {#setSize-long-}
```
public abstract void setSize(long value)
```


Définit la taille du fichier.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | long | La taille du fichier |
|

### getPagesInfo() {#getPagesInfo--}
```
public abstract List<PageInfo> getPagesInfo()
```


Obtient les informations pour chaque page du fichier en utilisant la classe [PageInfo](../../com.groupdocs.comparison.result/pageinfo).


**Returns:**
java.util.List<com.groupdocs.comparison.result.PageInfo> - informations pour chaque page du fichier

### setPagesInfo(List<PageInfo> pageInfos) {#setPagesInfo-java.util.List-com.groupdocs.comparison.result.PageInfo--}
```
public abstract void setPagesInfo(List<PageInfo> pageInfos)
```


Définit les informations pour chaque page du fichier en utilisant la classe [PageInfo](../../com.groupdocs.comparison.result/pageinfo).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | pageInfos | java.util.List<com.groupdocs.comparison.result.PageInfo> | Informations pour chaque page du fichier |
|

### close() {#close--}
```
public abstract void close()
```


Détruit l'objet, rendant impossible l'obtention des informations du document en utilisant cette instance de l'objet [IDocumentInfo](../../com.groupdocs.comparison.interfaces/idocumentinfo).
Supprime également les fichiers temporaires et libère les ressources utilisées.


