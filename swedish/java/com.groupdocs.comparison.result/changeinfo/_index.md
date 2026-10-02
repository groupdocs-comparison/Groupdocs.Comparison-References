---
title: "ChangeInfo"
second_title: "GroupDocs.Comparison för Java API-referens"
description: "Klassen ChangeInfo representerar information om en specifik ändring i en dokumentjämförelse."
type: docs
weight: 10
url: /sv/java/com.groupdocs.comparison.result/changeinfo/
---
**Inheritance:**
java.lang.Object
```
public class ChangeInfo
```

Klassen ChangeInfo representerar information om en specifik ändring i en dokumentjämförelse.


Den ger detaljer såsom typ av förändring, det påverkade området och innehållet före och efter förändringen.
Använd den här klassen för att hämta information om enskilda förändringar i ett jämförelsresultat.


Exempel på användning:

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


## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [ChangeInfo()](#ChangeInfo--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getRow()](#getRow--) |  |
| [setRow(Integer row)](#setRow-java.lang.Integer-) |  |
| [getColumn()](#getColumn--) |  |
| [setColumn(Integer column)](#setColumn-java.lang.Integer-) |  |
| [getColumnHeader()](#getColumnHeader--) |  |
| [setColumnHeader(String columnHeader)](#setColumnHeader-java.lang.String-) |  |
|  | [getId()](#getId--) | Hämtar unik id för förändringen. |
|
|  | [setId(int value)](#setId-int-) | Sätter unik id för förändringen. |
|
|  | [getComparisonAction()](#getComparisonAction--) | Hämtar åtgärden som kommer att tillämpas på förändringen. |
|
|  | [setComparisonAction(ComparisonAction value)](#setComparisonAction-com.groupdocs.comparison.result.ComparisonAction-) | Sätter åtgärden som bör tillämpas på förändringen. |
|
|  | [getPageInfo()](#getPageInfo--) | Hämtar information om sidan där den aktuella förändringen hittades. |
|
|  | [setPageInfo(PageInfo value)](#setPageInfo-com.groupdocs.comparison.result.PageInfo-) | Sätter information om sidan där den aktuella förändringen hittades. |
|
|  | [getBox()](#getBox--) | Hämtar koordinater för det ändrade elementet på sidan. |
|
|  | [setBox(Rectangle value)](#setBox-com.groupdocs.comparison.result.Rectangle-) | Sätter koordinater för det ändrade elementet på sidan. |
|
|  | [getText()](#getText--) | Hämtar textvärdet för förändringen. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Sätter textvärdet för förändringen. |
|
|  | [getStyleChanges()](#getStyleChanges--) | Hämtar listan över stiländringar. |
|
|  | [setStyleChanges(List<StyleChangeInfo> value)](#setStyleChanges-java.util.List-com.groupdocs.comparison.result.StyleChangeInfo--) | Sätter listan över stiländringar. |
|
|  | [getAuthors()](#getAuthors--) | Hämtar listan över författare. |
|
|  | [setAuthors(List<String> value)](#setAuthors-java.util.List-java.lang.String--) | Sätter listan över författare. |
|
|  | [getType()](#getType--) | Hämtar typen av förändring som representeras av enum [ChangeType](../../com.groupdocs.comparison.result/changetype). |
|
|  | [getTargetText()](#getTargetText--) | Hämtar ändrad text från måldokumentet. |
|
|  | [setTargetText(String value)](#setTargetText-java.lang.String-) | Sätter ändrad text från måldokumentet. |
|
|  | [getSourceText()](#getSourceText--) | Hämtar ändrad text från källdokumentet. |
|
|  | [setSourceText(String value)](#setSourceText-java.lang.String-) | Ställer in ändrad text från källdokumentet. |
|
|  | [getComponentType()](#getComponentType--) | Hämtar typen av den ändrade komponenten. |
|
|  | [setComponentType(String value)](#setComponentType-java.lang.String-) | Ställer in typen av den ändrade komponenten. |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rad | java.lang.Integer |  |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| kolumn | java.lang.Integer |  |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| columnHeader | java.lang.String |  |

### getId() {#getId--}
```
public final int getId()
```


Hämtar unik id för förändringen.


**Returns:**
int - id för ändringen

### setId(int value) {#setId-int-}
```
public final void setId(int value)
```


Sätter unik id för förändringen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | int | Id för ändringen |
|

### getComparisonAction() {#getComparisonAction--}
```
public final ComparisonAction getComparisonAction()
```


Hämtar åtgärden som kommer att tillämpas på förändringen.
Åtgärden ([ComparisonAction.ACCEPT](../../com.groupdocs.comparison.result/comparisonaction#ACCEPT) eller [ComparisonAction.REJECT](../../com.groupdocs.comparison.result/comparisonaction#REJECT)) talar om för jämförelsen vad som ska göras med denna ändring.


**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) - the action that will be applied to the change

### setComparisonAction(ComparisonAction value) {#setComparisonAction-com.groupdocs.comparison.result.ComparisonAction-}
```
public final void setComparisonAction(ComparisonAction value)
```


Sätter åtgärden som bör tillämpas på förändringen.
Åtgärden ([ComparisonAction.ACCEPT](../../com.groupdocs.comparison.result/comparisonaction#ACCEPT) eller [ComparisonAction.REJECT](../../com.groupdocs.comparison.result/comparisonaction#REJECT)) talar om för jämförelsen vad som ska göras med denna ändring.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) | Åtgärden som ska tillämpas på ändringen |
|

### getPageInfo() {#getPageInfo--}
```
public final PageInfo getPageInfo()
```


Hämtar information om sidan där den aktuella förändringen hittades.


**Returns:**
[PageInfo](../../com.groupdocs.comparison.result/pageinfo) - information about the page

### setPageInfo(PageInfo value) {#setPageInfo-com.groupdocs.comparison.result.PageInfo-}
```
public final void setPageInfo(PageInfo value)
```


Sätter information om sidan där den aktuella förändringen hittades.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [PageInfo](../../com.groupdocs.comparison.result/pageinfo) | Information om sidan |
|

### getBox() {#getBox--}
```
public final Rectangle getBox()
```


Hämtar koordinater för det ändrade elementet på sidan.


**Returns:**
[Rectangle](../../com.groupdocs.comparison.result/rectangle) - coordinates of changed element

### setBox(Rectangle value) {#setBox-com.groupdocs.comparison.result.Rectangle-}
```
public final void setBox(Rectangle value)
```


Sätter koordinater för det ändrade elementet på sidan.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [Rectangle](../../com.groupdocs.comparison.result/rectangle) | Koordinater för ändrat element, inte null |
|

### getText() {#getText--}
```
public final String getText()
```


Hämtar textvärdet för förändringen.


**Returns:**
java.lang.String - textvärde för ändringen

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Sätter textvärdet för förändringen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | java.lang.String | Textvärde för ändringen |
|

### getStyleChanges() {#getStyleChanges--}
```
public final List<StyleChangeInfo> getStyleChanges()
```


Hämtar listan över stiländringar.


**Returns:**
java.util.List<com.groupdocs.comparison.result.StyleChangeInfo> - listan över stiländringar

### setStyleChanges(List<StyleChangeInfo> value) {#setStyleChanges-java.util.List-com.groupdocs.comparison.result.StyleChangeInfo--}
```
public final void setStyleChanges(List<StyleChangeInfo> value)
```


Sätter listan över stiländringar.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | java.util.List<com.groupdocs.comparison.result.StyleChangeInfo> | Listan över stiländringar |
|

### getAuthors() {#getAuthors--}
```
public final List<String> getAuthors()
```


Hämtar listan över författare.


**Returns:**
java.util.List<java.lang.String> - listan över författare

### setAuthors(List<String> value) {#setAuthors-java.util.List-java.lang.String--}
```
public final void setAuthors(List<String> value)
```


Sätter listan över författare.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | java.util.List<java.lang.String> | Listan över författare |
|

### getType() {#getType--}
```
public final ChangeType getType()
```


Hämtar typen av förändring som representeras av enum [ChangeType](../../com.groupdocs.comparison.result/changetype).


**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - the type of the change

### getTargetText() {#getTargetText--}
```
public String getTargetText()
```


Hämtar ändrad text från måldokumentet.


**Returns:**
java.lang.String - den ändrade texten

### setTargetText(String value) {#setTargetText-java.lang.String-}
```
public void setTargetText(String value)
```


Sätter ändrad text från måldokumentet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | java.lang.String | Den ändrade texten |
|

### getSourceText() {#getSourceText--}
```
public String getSourceText()
```


Hämtar ändrad text från källdokumentet.


**Returns:**
java.lang.String - den ändrade texten

### setSourceText(String value) {#setSourceText-java.lang.String-}
```
public void setSourceText(String value)
```


Ställer in ändrad text från källdokumentet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | java.lang.String | Den ändrade texten |
|

### getComponentType() {#getComponentType--}
```
public String getComponentType()
```


Hämtar typen av den ändrade komponenten.


**Returns:**
java.lang.String - typen av den ändrade komponenten

### setComponentType(String value) {#setComponentType-java.lang.String-}
```
public void setComponentType(String value)
```


Ställer in typen av den ändrade komponenten.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | java.lang.String | Typen av den ändrade komponenten |
|

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
