---
title: "ChangeInfo"
second_title: "GroupDocs.Comparison voor Java API-referentie"
description: "De ChangeInfo-klasse vertegenwoordigt informatie over een specifieke wijziging in een documentvergelijking."
type: docs
weight: 10
url: /nl/java/com.groupdocs.comparison.result/changeinfo/
---
**Inheritance:**
java.lang.Object
```
public class ChangeInfo
```

De ChangeInfo-klasse vertegenwoordigt informatie over een specifieke wijziging in een documentvergelijking.


Het biedt details zoals het type wijziging, het getroffen gebied, en de inhoud vóór en na de wijziging.
Gebruik deze klasse om informatie over individuele wijzigingen binnen een vergelijkingsresultaat op te halen.


Voorbeeldgebruik:

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


## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [ChangeInfo()](#ChangeInfo--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getRow()](#getRow--) |  |
| [setRow(Integer row)](#setRow-java.lang.Integer-) |  |
| [getColumn()](#getColumn--) |  |
| [setColumn(Integer column)](#setColumn-java.lang.Integer-) |  |
| [getColumnHeader()](#getColumnHeader--) |  |
| [setColumnHeader(String columnHeader)](#setColumnHeader-java.lang.String-) |  |
|  | [getId()](#getId--) | Haalt de unieke id van de wijziging op. |
|
|  | [setId(int value)](#setId-int-) | Stelt de unieke id van de wijziging in. |
|
|  | [getComparisonAction()](#getComparisonAction--) | Haalt de actie op die op de wijziging zal worden toegepast. |
|
|  | [setComparisonAction(ComparisonAction value)](#setComparisonAction-com.groupdocs.comparison.result.ComparisonAction-) | Stelt de actie in die op de wijziging moet worden toegepast. |
|
|  | [getPageInfo()](#getPageInfo--) | Haalt informatie op over de pagina waarop de huidige wijziging is gevonden. |
|
|  | [setPageInfo(PageInfo value)](#setPageInfo-com.groupdocs.comparison.result.PageInfo-) | Stelt informatie in over de pagina waarop de huidige wijziging is gevonden. |
|
|  | [getBox()](#getBox--) | Haalt de coördinaten op van het gewijzigde element op de pagina. |
|
|  | [setBox(Rectangle value)](#setBox-com.groupdocs.comparison.result.Rectangle-) | Stelt de coördinaten in van het gewijzigde element op de pagina. |
|
|  | [getText()](#getText--) | Haalt de tekstwaarde van de wijziging op. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Stelt de tekstwaarde van de wijziging in. |
|
|  | [getStyleChanges()](#getStyleChanges--) | Haalt de lijst met stijlwijzigingen op. |
|
|  | [setStyleChanges(List<StyleChangeInfo> value)](#setStyleChanges-java.util.List-com.groupdocs.comparison.result.StyleChangeInfo--) | Stelt de lijst met stijlwijzigingen in. |
|
|  | [getAuthors()](#getAuthors--) | Haalt de lijst met auteurs op. |
|
|  | [setAuthors(List<String> value)](#setAuthors-java.util.List-java.lang.String--) | Stelt de lijst met auteurs in. |
|
|  | [getType()](#getType--) | Haalt het type van de wijziging op dat wordt weergegeven door de enum [ChangeType](../../com.groupdocs.comparison.result/changetype). |
|
|  | [getTargetText()](#getTargetText--) | Haalt de gewijzigde tekst op uit het doeldocument. |
|
|  | [setTargetText(String value)](#setTargetText-java.lang.String-) | Stelt de gewijzigde tekst in uit het doeldocument. |
|
|  | [getSourceText()](#getSourceText--) | Haalt de gewijzigde tekst op uit het brondocument. |
|
|  | [setSourceText(String value)](#setSourceText-java.lang.String-) | Stelt gewijzigde tekst in vanuit het brondocument. |
|
|  | [getComponentType()](#getComponentType--) | Haalt het type van het gewijzigde component op. |
|
|  | [setComponentType(String value)](#setComponentType-java.lang.String-) | Stelt het type van het gewijzigde component in. |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rij | java.lang.Integer |  |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| kolom | java.lang.Integer |  |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| kolomkop | java.lang.String |  |

### getId() {#getId--}
```
public final int getId()
```


Haalt de unieke id van de wijziging op.


**Returns:**
int - de id van de wijziging

### setId(int value) {#setId-int-}
```
public final void setId(int value)
```


Stelt de unieke id van de wijziging in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | int | De id van de wijziging |
|

### getComparisonAction() {#getComparisonAction--}
```
public final ComparisonAction getComparisonAction()
```


Haalt de actie op die op de wijziging zal worden toegepast.
Actie ([ComparisonAction.ACCEPT](../../com.groupdocs.comparison.result/comparisonaction#ACCEPT) of [ComparisonAction.REJECT](../../com.groupdocs.comparison.result/comparisonaction#REJECT)) vertelt de vergelijking wat te doen met deze wijziging.


**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) - the action that will be applied to the change

### setComparisonAction(ComparisonAction value) {#setComparisonAction-com.groupdocs.comparison.result.ComparisonAction-}
```
public final void setComparisonAction(ComparisonAction value)
```


Stelt de actie in die op de wijziging moet worden toegepast.
Actie ([ComparisonAction.ACCEPT](../../com.groupdocs.comparison.result/comparisonaction#ACCEPT) of [ComparisonAction.REJECT](../../com.groupdocs.comparison.result/comparisonaction#REJECT)) vertelt de vergelijking wat te doen met deze wijziging.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) | De actie die op de wijziging moet worden toegepast |
|

### getPageInfo() {#getPageInfo--}
```
public final PageInfo getPageInfo()
```


Haalt informatie op over de pagina waarop de huidige wijziging is gevonden.


**Returns:**
[PageInfo](../../com.groupdocs.comparison.result/pageinfo) - information about the page

### setPageInfo(PageInfo value) {#setPageInfo-com.groupdocs.comparison.result.PageInfo-}
```
public final void setPageInfo(PageInfo value)
```


Stelt informatie in over de pagina waarop de huidige wijziging is gevonden.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [PageInfo](../../com.groupdocs.comparison.result/pageinfo) | Informatie over de pagina |
|

### getBox() {#getBox--}
```
public final Rectangle getBox()
```


Haalt de coördinaten op van het gewijzigde element op de pagina.


**Returns:**
[Rectangle](../../com.groupdocs.comparison.result/rectangle) - coordinates of changed element

### setBox(Rectangle value) {#setBox-com.groupdocs.comparison.result.Rectangle-}
```
public final void setBox(Rectangle value)
```


Stelt de coördinaten in van het gewijzigde element op de pagina.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [Rectangle](../../com.groupdocs.comparison.result/rectangle) | Coördinaten van het gewijzigde element, niet null |
|

### getText() {#getText--}
```
public final String getText()
```


Haalt de tekstwaarde van de wijziging op.


**Returns:**
java.lang.String - tekstwaarde van de wijziging

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Stelt de tekstwaarde van de wijziging in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.lang.String | Tekstwaarde van de wijziging |
|

### getStyleChanges() {#getStyleChanges--}
```
public final List<StyleChangeInfo> getStyleChanges()
```


Haalt de lijst met stijlwijzigingen op.


**Returns:**
java.util.List<com.groupdocs.comparison.result.StyleChangeInfo> - de lijst met stijlwijzigingen

### setStyleChanges(List<StyleChangeInfo> value) {#setStyleChanges-java.util.List-com.groupdocs.comparison.result.StyleChangeInfo--}
```
public final void setStyleChanges(List<StyleChangeInfo> value)
```


Stelt de lijst met stijlwijzigingen in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.util.List<com.groupdocs.comparison.result.StyleChangeInfo> | De lijst met stijlwijzigingen |
|

### getAuthors() {#getAuthors--}
```
public final List<String> getAuthors()
```


Haalt de lijst met auteurs op.


**Returns:**
java.util.List<java.lang.String> - de lijst met auteurs

### setAuthors(List<String> value) {#setAuthors-java.util.List-java.lang.String--}
```
public final void setAuthors(List<String> value)
```


Stelt de lijst met auteurs in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.util.List<java.lang.String> | De lijst met auteurs |
|

### getType() {#getType--}
```
public final ChangeType getType()
```


Haalt het type van de wijziging op dat wordt weergegeven door de enum [ChangeType](../../com.groupdocs.comparison.result/changetype).


**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - the type of the change

### getTargetText() {#getTargetText--}
```
public String getTargetText()
```


Haalt de gewijzigde tekst op uit het doeldocument.


**Returns:**
java.lang.String - de gewijzigde tekst

### setTargetText(String value) {#setTargetText-java.lang.String-}
```
public void setTargetText(String value)
```


Stelt de gewijzigde tekst in uit het doeldocument.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.lang.String | De gewijzigde tekst |
|

### getSourceText() {#getSourceText--}
```
public String getSourceText()
```


Haalt de gewijzigde tekst op uit het brondocument.


**Returns:**
java.lang.String - de gewijzigde tekst

### setSourceText(String value) {#setSourceText-java.lang.String-}
```
public void setSourceText(String value)
```


Stelt gewijzigde tekst in vanuit het brondocument.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.lang.String | De gewijzigde tekst |
|

### getComponentType() {#getComponentType--}
```
public String getComponentType()
```


Haalt het type van het gewijzigde component op.


**Returns:**
java.lang.String - het type van het gewijzigde component

### setComponentType(String value) {#setComponentType-java.lang.String-}
```
public void setComponentType(String value)
```


Stelt het type van het gewijzigde component in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.lang.String | Het type van het gewijzigde component |
|

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
