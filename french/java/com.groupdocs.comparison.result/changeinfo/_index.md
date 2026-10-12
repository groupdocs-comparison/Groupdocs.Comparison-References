---
title: "ChangeInfo"
second_title: "Référence API de GroupDocs.Comparison for Java"
description: "La classe ChangeInfo représente les informations concernant une modification spécifique dans une comparaison de documents."
type: docs
weight: 10
url: /fr/java/com.groupdocs.comparison.result/changeinfo/
---
**Inheritance:**
java.lang.Object
```
public class ChangeInfo
```

La classe ChangeInfo représente les informations concernant une modification spécifique dans une comparaison de documents.


Il fournit des détails tels que le type de modification, la zone affectée, et le contenu avant et après la modification.
Utilisez cette classe pour récupérer des informations sur les modifications individuelles dans un résultat de comparaison.


Exemple d'utilisation :

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     comparer.compare(resultFile);
     // Get a list of changes from the comparison result
     ChangeInfo[] changes = comparer.getChanges();
     // Iterate through the changes and retrieve information
     for (ChangeInfo change : changes) {
         ChangeType changeType = change.getType();
         String componentType = change.getComponentType();
         PageInfo pageInfo = change.getPageInfo();
         // Process the change information as needed
         // ...
     }
 }
 
````


## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ChangeInfo()](#ChangeInfo--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getRow()](#getRow--) |  |
| [setRow(Integer row)](#setRow-java.lang.Integer-) |  |
| [getColumn()](#getColumn--) |  |
| [setColumn(Integer column)](#setColumn-java.lang.Integer-) |  |
| [getColumnHeader()](#getColumnHeader--) |  |
| [setColumnHeader(String columnHeader)](#setColumnHeader-java.lang.String-) |  |
|  | [getId()](#getId--) | Obtient l'identifiant unique de la modification. |
|
|  | [setId(int value)](#setId-int-) | Définit l'identifiant unique de la modification. |
|
|  | [getComparisonAction()](#getComparisonAction--) | Obtient l'action qui sera appliquée à la modification. |
|
|  | [setComparisonAction(ComparisonAction value)](#setComparisonAction-com.groupdocs.comparison.result.ComparisonAction-) | Définit l'action qui doit être appliquée à la modification. |
|
|  | [getPageInfo()](#getPageInfo--) | Obtient des informations sur la page où la modification actuelle a été trouvée. |
|
|  | [setPageInfo(PageInfo value)](#setPageInfo-com.groupdocs.comparison.result.PageInfo-) | Définit des informations sur la page où la modification actuelle a été trouvée. |
|
|  | [getBox()](#getBox--) | Obtient les coordonnées de l'élément modifié sur la page. |
|
|  | [setBox(Rectangle value)](#setBox-com.groupdocs.comparison.result.Rectangle-) | Définit les coordonnées de l'élément modifié sur la page. |
|
|  | [getText()](#getText--) | Obtient la valeur texte de la modification. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Définit la valeur texte de la modification. |
|
|  | [getStyleChanges()](#getStyleChanges--) | Obtient la liste des modifications de style. |
|
|  | [setStyleChanges(List<StyleChangeInfo> value)](#setStyleChanges-java.util.List-com.groupdocs.comparison.result.StyleChangeInfo--) | Définit la liste des modifications de style. |
|
|  | [getAuthors()](#getAuthors--) | Obtient la liste des auteurs. |
|
|  | [setAuthors(List<String> value)](#setAuthors-java.util.List-java.lang.String--) | Définit la liste des auteurs. |
|
|  | [getType()](#getType--) | Obtient le type de la modification représenté par l'énumération [ChangeType](../../com.groupdocs.comparison.result/changetype). |
|
|  | [getTargetText()](#getTargetText--) | Obtient le texte modifié du document cible. |
|
|  | [setTargetText(String value)](#setTargetText-java.lang.String-) | Définit le texte modifié du document cible. |
|
|  | [getSourceText()](#getSourceText--) | Obtient le texte modifié du document source. |
|
|  | [setSourceText(String value)](#setSourceText-java.lang.String-) | Définit le texte modifié à partir du document source. |
|
|  | [getComponentType()](#getComponentType--) | Obtient le type du composant modifié. |
|
|  | [setComponentType(String value)](#setComponentType-java.lang.String-) | Définit le type du composant modifié. |
|
| [toString()](#toString--) |  |
### ChangeInfo() {#ChangeInfo--}
```
public ChangeInfo()
```


### getRow() {#getRow--}
```
public Integer getRow()
```




**Returns:**
java.lang.Integer
### setRow(Integer row) {#setRow-java.lang.Integer-}
```
public void setRow(Integer row)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| ligne | java.lang.Integer |  |

### getColumn() {#getColumn--}
```
public Integer getColumn()
```




**Returns:**
java.lang.Integer
### setColumn(Integer column) {#setColumn-java.lang.Integer-}
```
public void setColumn(Integer column)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| colonne | java.lang.Integer |  |

### getColumnHeader() {#getColumnHeader--}
```
public String getColumnHeader()
```




**Returns:**
java.lang.String
### setColumnHeader(String columnHeader) {#setColumnHeader-java.lang.String-}
```
public void setColumnHeader(String columnHeader)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| columnHeader | java.lang.String |  |

### getId() {#getId--}
```
public final int getId()
```


Obtient l'identifiant unique de la modification.


**Returns:**
int - l'identifiant du changement

### setId(int value) {#setId-int-}
```
public final void setId(int value)
```


Définit l'identifiant unique de la modification.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | int | L'identifiant du changement |
|

### getComparisonAction() {#getComparisonAction--}
```
public final ComparisonAction getComparisonAction()
```


Obtient l'action qui sera appliquée à la modification.
L'action ([ComparisonAction.ACCEPT](../../com.groupdocs.comparison.result/comparisonaction#ACCEPT) ou [ComparisonAction.REJECT](../../com.groupdocs.comparison.result/comparisonaction#REJECT)) indique à la comparaison quoi faire avec ce changement.


**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) - the action that will be applied to the change

### setComparisonAction(ComparisonAction value) {#setComparisonAction-com.groupdocs.comparison.result.ComparisonAction-}
```
public final void setComparisonAction(ComparisonAction value)
```


Définit l'action qui doit être appliquée à la modification.
L'action ([ComparisonAction.ACCEPT](../../com.groupdocs.comparison.result/comparisonaction#ACCEPT) ou [ComparisonAction.REJECT](../../com.groupdocs.comparison.result/comparisonaction#REJECT)) indique à la comparaison quoi faire avec ce changement.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) | L'action qui doit être appliquée au changement |
|

### getPageInfo() {#getPageInfo--}
```
public final PageInfo getPageInfo()
```


Obtient des informations sur la page où la modification actuelle a été trouvée.


**Returns:**
[PageInfo](../../com.groupdocs.comparison.result/pageinfo) - information about the page

### setPageInfo(PageInfo value) {#setPageInfo-com.groupdocs.comparison.result.PageInfo-}
```
public final void setPageInfo(PageInfo value)
```


Définit des informations sur la page où la modification actuelle a été trouvée.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [PageInfo](../../com.groupdocs.comparison.result/pageinfo) | Informations sur la page |
|

### getBox() {#getBox--}
```
public final Rectangle getBox()
```


Obtient les coordonnées de l'élément modifié sur la page.


**Returns:**
[Rectangle](../../com.groupdocs.comparison.result/rectangle) - coordinates of changed element

### setBox(Rectangle value) {#setBox-com.groupdocs.comparison.result.Rectangle-}
```
public final void setBox(Rectangle value)
```


Définit les coordonnées de l'élément modifié sur la page.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [Rectangle](../../com.groupdocs.comparison.result/rectangle) | Coordonnées de l'élément modifié, non nul |
|

### getText() {#getText--}
```
public final String getText()
```


Obtient la valeur texte de la modification.


**Returns:**
java.lang.String - valeur texte du changement

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Définit la valeur texte de la modification.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.lang.String | Valeur texte du changement |
|

### getStyleChanges() {#getStyleChanges--}
```
public final List<StyleChangeInfo> getStyleChanges()
```


Obtient la liste des modifications de style.


**Returns:**
java.util.List<com.groupdocs.comparison.result.StyleChangeInfo> - la liste des changements de style

### setStyleChanges(List<StyleChangeInfo> value) {#setStyleChanges-java.util.List-com.groupdocs.comparison.result.StyleChangeInfo--}
```
public final void setStyleChanges(List<StyleChangeInfo> value)
```


Définit la liste des modifications de style.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.util.List<com.groupdocs.comparison.result.StyleChangeInfo> | La liste des changements de style |
|

### getAuthors() {#getAuthors--}
```
public final List<String> getAuthors()
```


Obtient la liste des auteurs.


**Returns:**
java.util.List<java.lang.String> - la liste des auteurs

### setAuthors(List<String> value) {#setAuthors-java.util.List-java.lang.String--}
```
public final void setAuthors(List<String> value)
```


Définit la liste des auteurs.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.util.List<java.lang.String> | La liste des auteurs |
|

### getType() {#getType--}
```
public final ChangeType getType()
```


Obtient le type de la modification représenté par l'énumération [ChangeType](../../com.groupdocs.comparison.result/changetype).


**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - the type of the change

### getTargetText() {#getTargetText--}
```
public String getTargetText()
```


Obtient le texte modifié du document cible.


**Returns:**
java.lang.String - le texte modifié

### setTargetText(String value) {#setTargetText-java.lang.String-}
```
public void setTargetText(String value)
```


Définit le texte modifié du document cible.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.lang.String | Le texte modifié |
|

### getSourceText() {#getSourceText--}
```
public String getSourceText()
```


Obtient le texte modifié du document source.


**Returns:**
java.lang.String - le texte modifié

### setSourceText(String value) {#setSourceText-java.lang.String-}
```
public void setSourceText(String value)
```


Définit le texte modifié à partir du document source.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.lang.String | Le texte modifié |
|

### getComponentType() {#getComponentType--}
```
public String getComponentType()
```


Obtient le type du composant modifié.


**Returns:**
java.lang.String - le type du composant modifié

### setComponentType(String value) {#setComponentType-java.lang.String-}
```
public void setComponentType(String value)
```


Définit le type du composant modifié.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.lang.String | Le type du composant modifié |
|

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
