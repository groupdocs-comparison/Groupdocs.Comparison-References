---
title: "ChangeInfo"
second_title: "Riferimento API di GroupDocs.Comparison per Java"
description: "La classe ChangeInfo rappresenta le informazioni su una specifica modifica in un confronto di documenti."
type: docs
weight: 10
url: /it/java/com.groupdocs.comparison.result/changeinfo/
---
**Inheritance:**
java.lang.Object
```
public class ChangeInfo
```

La classe ChangeInfo rappresenta le informazioni su una specifica modifica in un confronto di documenti.


Fornisce dettagli come il tipo di modifica, l'area interessata e il contenuto prima e dopo la modifica.
Utilizza questa classe per recuperare informazioni sulle singole modifiche all'interno di un risultato di confronto.


Esempio di utilizzo:

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


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ChangeInfo()](#ChangeInfo--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getRow()](#getRow--) |  |
| [setRow(Integer row)](#setRow-java.lang.Integer-) |  |
| [getColumn()](#getColumn--) |  |
| [setColumn(Integer column)](#setColumn-java.lang.Integer-) |  |
| [getColumnHeader()](#getColumnHeader--) |  |
| [setColumnHeader(String columnHeader)](#setColumnHeader-java.lang.String-) |  |
|  | [getId()](#getId--) | Restituisce l'ID univoco della modifica. |
|
|  | [setId(int value)](#setId-int-) | Imposta l'ID univoco della modifica. |
|
|  | [getComparisonAction()](#getComparisonAction--) | Restituisce l'azione che sarà applicata alla modifica. |
|
|  | [setComparisonAction(ComparisonAction value)](#setComparisonAction-com.groupdocs.comparison.result.ComparisonAction-) | Imposta l'azione che dovrebbe essere applicata alla modifica. |
|
|  | [getPageInfo()](#getPageInfo--) | Restituisce informazioni sulla pagina in cui è stata trovata la modifica corrente. |
|
|  | [setPageInfo(PageInfo value)](#setPageInfo-com.groupdocs.comparison.result.PageInfo-) | Imposta informazioni sulla pagina in cui è stata trovata la modifica corrente. |
|
|  | [getBox()](#getBox--) | Restituisce le coordinate dell'elemento modificato sulla pagina. |
|
|  | [setBox(Rectangle value)](#setBox-com.groupdocs.comparison.result.Rectangle-) | Imposta le coordinate dell'elemento modificato sulla pagina. |
|
|  | [getText()](#getText--) | Restituisce il valore testuale della modifica. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Imposta il valore testuale della modifica. |
|
|  | [getStyleChanges()](#getStyleChanges--) | Restituisce l'elenco delle modifiche di stile. |
|
|  | [setStyleChanges(List<StyleChangeInfo> value)](#setStyleChanges-java.util.List-com.groupdocs.comparison.result.StyleChangeInfo--) | Imposta l'elenco delle modifiche di stile. |
|
|  | [getAuthors()](#getAuthors--) | Restituisce l'elenco degli autori. |
|
|  | [setAuthors(List<String> value)](#setAuthors-java.util.List-java.lang.String--) | Imposta l'elenco degli autori. |
|
|  | [getType()](#getType--) | Restituisce il tipo di modifica rappresentato dall'enum [ChangeType](../../com.groupdocs.comparison.result/changetype). |
|
|  | [getTargetText()](#getTargetText--) | Restituisce il testo modificato dal documento di destinazione. |
|
|  | [setTargetText(String value)](#setTargetText-java.lang.String-) | Imposta il testo modificato dal documento di destinazione. |
|
|  | [getSourceText()](#getSourceText--) | Restituisce il testo modificato dal documento di origine. |
|
|  | [setSourceText(String value)](#setSourceText-java.lang.String-) | Imposta il testo modificato dal documento sorgente. |
|
|  | [getComponentType()](#getComponentType--) | Ottiene il tipo del componente modificato. |
|
|  | [setComponentType(String value)](#setComponentType-java.lang.String-) | Imposta il tipo del componente modificato. |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| riga | java.lang.Integer |  |

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| colonna | java.lang.Integer |  |

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| intestazioneColonna | java.lang.String |  |

### getId() {#getId--}
```
public final int getId()
```


Restituisce l'ID univoco della modifica.


**Returns:**
int - l'id della modifica

### setId(int value) {#setId-int-}
```
public final void setId(int value)
```


Imposta l'ID univoco della modifica.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | int | L'id della modifica |
|

### getComparisonAction() {#getComparisonAction--}
```
public final ComparisonAction getComparisonAction()
```


Restituisce l'azione che sarà applicata alla modifica.
L'azione ([ComparisonAction.ACCEPT](../../com.groupdocs.comparison.result/comparisonaction#ACCEPT) o [ComparisonAction.REJECT](../../com.groupdocs.comparison.result/comparisonaction#REJECT)) indica a Comparison cosa fare con questa modifica.


**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) - the action that will be applied to the change

### setComparisonAction(ComparisonAction value) {#setComparisonAction-com.groupdocs.comparison.result.ComparisonAction-}
```
public final void setComparisonAction(ComparisonAction value)
```


Imposta l'azione che dovrebbe essere applicata alla modifica.
L'azione ([ComparisonAction.ACCEPT](../../com.groupdocs.comparison.result/comparisonaction#ACCEPT) o [ComparisonAction.REJECT](../../com.groupdocs.comparison.result/comparisonaction#REJECT)) indica a Comparison cosa fare con questa modifica.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) | L'azione che dovrebbe essere applicata alla modifica |
|

### getPageInfo() {#getPageInfo--}
```
public final PageInfo getPageInfo()
```


Restituisce informazioni sulla pagina in cui è stata trovata la modifica corrente.


**Returns:**
[PageInfo](../../com.groupdocs.comparison.result/pageinfo) - information about the page

### setPageInfo(PageInfo value) {#setPageInfo-com.groupdocs.comparison.result.PageInfo-}
```
public final void setPageInfo(PageInfo value)
```


Imposta informazioni sulla pagina in cui è stata trovata la modifica corrente.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [PageInfo](../../com.groupdocs.comparison.result/pageinfo) | Informazioni sulla pagina |
|

### getBox() {#getBox--}
```
public final Rectangle getBox()
```


Restituisce le coordinate dell'elemento modificato sulla pagina.


**Returns:**
[Rectangle](../../com.groupdocs.comparison.result/rectangle) - coordinates of changed element

### setBox(Rectangle value) {#setBox-com.groupdocs.comparison.result.Rectangle-}
```
public final void setBox(Rectangle value)
```


Imposta le coordinate dell'elemento modificato sulla pagina.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [Rectangle](../../com.groupdocs.comparison.result/rectangle) | Coordinate dell'elemento modificato, non null |
|

### getText() {#getText--}
```
public final String getText()
```


Restituisce il valore testuale della modifica.


**Returns:**
java.lang.String - valore testuale della modifica

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Imposta il valore testuale della modifica.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.lang.String | Valore testuale della modifica |
|

### getStyleChanges() {#getStyleChanges--}
```
public final List<StyleChangeInfo> getStyleChanges()
```


Restituisce l'elenco delle modifiche di stile.


**Returns:**
java.util.List<com.groupdocs.comparison.result.StyleChangeInfo> - l'elenco delle modifiche di stile

### setStyleChanges(List<StyleChangeInfo> value) {#setStyleChanges-java.util.List-com.groupdocs.comparison.result.StyleChangeInfo--}
```
public final void setStyleChanges(List<StyleChangeInfo> value)
```


Imposta l'elenco delle modifiche di stile.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.util.List<com.groupdocs.comparison.result.StyleChangeInfo> | L'elenco delle modifiche di stile |
|

### getAuthors() {#getAuthors--}
```
public final List<String> getAuthors()
```


Restituisce l'elenco degli autori.


**Returns:**
java.util.List<java.lang.String> - l'elenco degli autori

### setAuthors(List<String> value) {#setAuthors-java.util.List-java.lang.String--}
```
public final void setAuthors(List<String> value)
```


Imposta l'elenco degli autori.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.util.List<java.lang.String> | L'elenco degli autori |
|

### getType() {#getType--}
```
public final ChangeType getType()
```


Restituisce il tipo di modifica rappresentato dall'enum [ChangeType](../../com.groupdocs.comparison.result/changetype).


**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - the type of the change

### getTargetText() {#getTargetText--}
```
public String getTargetText()
```


Restituisce il testo modificato dal documento di destinazione.


**Returns:**
java.lang.String - il testo modificato

### setTargetText(String value) {#setTargetText-java.lang.String-}
```
public void setTargetText(String value)
```


Imposta il testo modificato dal documento di destinazione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.lang.String | Il testo modificato |
|

### getSourceText() {#getSourceText--}
```
public String getSourceText()
```


Restituisce il testo modificato dal documento di origine.


**Returns:**
java.lang.String - il testo modificato

### setSourceText(String value) {#setSourceText-java.lang.String-}
```
public void setSourceText(String value)
```


Imposta il testo modificato dal documento sorgente.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.lang.String | Il testo modificato |
|

### getComponentType() {#getComponentType--}
```
public String getComponentType()
```


Ottiene il tipo del componente modificato.


**Returns:**
java.lang.String - il tipo del componente modificato

### setComponentType(String value) {#setComponentType-java.lang.String-}
```
public void setComponentType(String value)
```


Imposta il tipo del componente modificato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.lang.String | Il tipo del componente modificato |
|

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
