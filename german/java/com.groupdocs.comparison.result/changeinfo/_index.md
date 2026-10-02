---
title: "ChangeInfo"
second_title: "GroupDocs.Comparison für Java API-Referenz"
description: "Die Klasse ChangeInfo stellt Informationen über eine spezifische Änderung in einem Dokumentenvergleich dar."
type: docs
weight: 10
url: /de/java/com.groupdocs.comparison.result/changeinfo/
---
**Inheritance:**
java.lang.Object
```
public class ChangeInfo
```

Die Klasse ChangeInfo stellt Informationen über eine spezifische Änderung in einem Dokumentenvergleich dar.


Sie liefert Details wie den Typ der Änderung, den betroffenen Bereich und den Inhalt vor und nach der Änderung.
Verwenden Sie diese Klasse, um Informationen über einzelne Änderungen innerhalb eines Vergleichsergebnisses abzurufen.


Beispielverwendung:

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


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ChangeInfo()](#ChangeInfo--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getRow()](#getRow--) |  |
| [setRow(Integer row)](#setRow-java.lang.Integer-) |  |
| [getColumn()](#getColumn--) |  |
| [setColumn(Integer column)](#setColumn-java.lang.Integer-) |  |
| [getColumnHeader()](#getColumnHeader--) |  |
| [setColumnHeader(String columnHeader)](#setColumnHeader-java.lang.String-) |  |
|  | [getId()](#getId--) | Liefert die eindeutige ID der Änderung. |
|
|  | [setId(int value)](#setId-int-) | Setzt die eindeutige ID der Änderung. |
|
|  | [getComparisonAction()](#getComparisonAction--) | Liefert die Aktion, die auf die Änderung angewendet wird. |
|
|  | [setComparisonAction(ComparisonAction value)](#setComparisonAction-com.groupdocs.comparison.result.ComparisonAction-) | Setzt die Aktion, die auf die Änderung angewendet werden soll. |
|
|  | [getPageInfo()](#getPageInfo--) | Liefert Informationen über die Seite, auf der die aktuelle Änderung gefunden wurde. |
|
|  | [setPageInfo(PageInfo value)](#setPageInfo-com.groupdocs.comparison.result.PageInfo-) | Setzt Informationen über die Seite, auf der die aktuelle Änderung gefunden wurde. |
|
|  | [getBox()](#getBox--) | Liefert die Koordinaten des geänderten Elements auf der Seite. |
|
|  | [setBox(Rectangle value)](#setBox-com.groupdocs.comparison.result.Rectangle-) | Setzt die Koordinaten des geänderten Elements auf der Seite. |
|
|  | [getText()](#getText--) | Liefert den Textwert der Änderung. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Setzt den Textwert der Änderung. |
|
|  | [getStyleChanges()](#getStyleChanges--) | Liefert die Liste der Stiländerungen. |
|
|  | [setStyleChanges(List<StyleChangeInfo> value)](#setStyleChanges-java.util.List-com.groupdocs.comparison.result.StyleChangeInfo--) | Setzt die Liste der Stiländerungen. |
|
|  | [getAuthors()](#getAuthors--) | Liefert die Liste der Autoren. |
|
|  | [setAuthors(List<String> value)](#setAuthors-java.util.List-java.lang.String--) | Setzt die Liste der Autoren. |
|
|  | [getType()](#getType--) | Liefert den Typ der Änderung, dargestellt durch das Enum [ChangeType](../../com.groupdocs.comparison.result/changetype). |
|
|  | [getTargetText()](#getTargetText--) | Liefert den geänderten Text aus dem Zieldokument. |
|
|  | [setTargetText(String value)](#setTargetText-java.lang.String-) | Setzt den geänderten Text aus dem Zieldokument. |
|
|  | [getSourceText()](#getSourceText--) | Liefert den geänderten Text aus dem Quelldokument. |
|
|  | [setSourceText(String value)](#setSourceText-java.lang.String-) | Setzt den geänderten Text aus dem Quelldokument. |
|
|  | [getComponentType()](#getComponentType--) | Ermittelt den Typ der geänderten Komponente. |
|
|  | [setComponentType(String value)](#setComponentType-java.lang.String-) | Setzt den Typ der geänderten Komponente. |
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Zeile | java.lang.Integer |  |

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Spalte | java.lang.Integer |  |

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Spaltenkopf | java.lang.String |  |

### getId() {#getId--}
```
public final int getId()
```


Liefert die eindeutige ID der Änderung.


**Returns:**
int - die ID der Änderung

### setId(int value) {#setId-int-}
```
public final void setId(int value)
```


Setzt die eindeutige ID der Änderung.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | int | Die ID der Änderung |
|

### getComparisonAction() {#getComparisonAction--}
```
public final ComparisonAction getComparisonAction()
```


Liefert die Aktion, die auf die Änderung angewendet wird.
Aktion ([ComparisonAction.ACCEPT](../../com.groupdocs.comparison.result/comparisonaction#ACCEPT) oder [ComparisonAction.REJECT](../../com.groupdocs.comparison.result/comparisonaction#REJECT)) gibt an, was die Vergleichsfunktion mit dieser Änderung tun soll.


**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) - the action that will be applied to the change

### setComparisonAction(ComparisonAction value) {#setComparisonAction-com.groupdocs.comparison.result.ComparisonAction-}
```
public final void setComparisonAction(ComparisonAction value)
```


Setzt die Aktion, die auf die Änderung angewendet werden soll.
Aktion ([ComparisonAction.ACCEPT](../../com.groupdocs.comparison.result/comparisonaction#ACCEPT) oder [ComparisonAction.REJECT](../../com.groupdocs.comparison.result/comparisonaction#REJECT)) gibt an, was die Vergleichsfunktion mit dieser Änderung tun soll.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) | Die Aktion, die auf die Änderung angewendet werden soll |
|

### getPageInfo() {#getPageInfo--}
```
public final PageInfo getPageInfo()
```


Liefert Informationen über die Seite, auf der die aktuelle Änderung gefunden wurde.


**Returns:**
[PageInfo](../../com.groupdocs.comparison.result/pageinfo) - information about the page

### setPageInfo(PageInfo value) {#setPageInfo-com.groupdocs.comparison.result.PageInfo-}
```
public final void setPageInfo(PageInfo value)
```


Setzt Informationen über die Seite, auf der die aktuelle Änderung gefunden wurde.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [PageInfo](../../com.groupdocs.comparison.result/pageinfo) | Informationen zur Seite |
|

### getBox() {#getBox--}
```
public final Rectangle getBox()
```


Liefert die Koordinaten des geänderten Elements auf der Seite.


**Returns:**
[Rectangle](../../com.groupdocs.comparison.result/rectangle) - coordinates of changed element

### setBox(Rectangle value) {#setBox-com.groupdocs.comparison.result.Rectangle-}
```
public final void setBox(Rectangle value)
```


Setzt die Koordinaten des geänderten Elements auf der Seite.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [Rectangle](../../com.groupdocs.comparison.result/rectangle) | Koordinaten des geänderten Elements, nicht null |
|

### getText() {#getText--}
```
public final String getText()
```


Liefert den Textwert der Änderung.


**Returns:**
java.lang.String - Textwert der Änderung

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Setzt den Textwert der Änderung.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | java.lang.String | Textwert der Änderung |
|

### getStyleChanges() {#getStyleChanges--}
```
public final List<StyleChangeInfo> getStyleChanges()
```


Liefert die Liste der Stiländerungen.


**Returns:**
java.util.List<com.groupdocs.comparison.result.StyleChangeInfo> - die Liste der Stiländerungen

### setStyleChanges(List<StyleChangeInfo> value) {#setStyleChanges-java.util.List-com.groupdocs.comparison.result.StyleChangeInfo--}
```
public final void setStyleChanges(List<StyleChangeInfo> value)
```


Setzt die Liste der Stiländerungen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | java.util.List<com.groupdocs.comparison.result.StyleChangeInfo> | Die Liste der Stiländerungen |
|

### getAuthors() {#getAuthors--}
```
public final List<String> getAuthors()
```


Liefert die Liste der Autoren.


**Returns:**
java.util.List<java.lang.String> - die Liste der Autoren

### setAuthors(List<String> value) {#setAuthors-java.util.List-java.lang.String--}
```
public final void setAuthors(List<String> value)
```


Setzt die Liste der Autoren.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | java.util.List<java.lang.String> | Die Liste der Autoren |
|

### getType() {#getType--}
```
public final ChangeType getType()
```


Liefert den Typ der Änderung, dargestellt durch das Enum [ChangeType](../../com.groupdocs.comparison.result/changetype).


**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - the type of the change

### getTargetText() {#getTargetText--}
```
public String getTargetText()
```


Liefert den geänderten Text aus dem Zieldokument.


**Returns:**
java.lang.String - der geänderte Text

### setTargetText(String value) {#setTargetText-java.lang.String-}
```
public void setTargetText(String value)
```


Setzt den geänderten Text aus dem Zieldokument.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | java.lang.String | Der geänderte Text |
|

### getSourceText() {#getSourceText--}
```
public String getSourceText()
```


Liefert den geänderten Text aus dem Quelldokument.


**Returns:**
java.lang.String - der geänderte Text

### setSourceText(String value) {#setSourceText-java.lang.String-}
```
public void setSourceText(String value)
```


Setzt den geänderten Text aus dem Quelldokument.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | java.lang.String | Der geänderte Text |
|

### getComponentType() {#getComponentType--}
```
public String getComponentType()
```


Ermittelt den Typ der geänderten Komponente.


**Returns:**
java.lang.String - der Typ der geänderten Komponente

### setComponentType(String value) {#setComponentType-java.lang.String-}
```
public void setComponentType(String value)
```


Setzt den Typ der geänderten Komponente.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | java.lang.String | Der Typ der geänderten Komponente |
|

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
