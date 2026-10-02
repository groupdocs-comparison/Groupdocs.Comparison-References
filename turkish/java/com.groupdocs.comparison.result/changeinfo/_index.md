---
title: "ChangeInfo"
second_title: "GroupDocs.Comparison for Java API Referansı"
description: "ChangeInfo sınıfı, belge karşılaştırmasındaki belirli bir değişiklik hakkında bilgi temsil eder."
type: docs
weight: 10
url: /tr/java/com.groupdocs.comparison.result/changeinfo/
---
**Inheritance:**
java.lang.Object
```
public class ChangeInfo
```

ChangeInfo sınıfı, belge karşılaştırmasındaki belirli bir değişiklik hakkında bilgi temsil eder.


Değişiklik türü, etkilenen alan ve değişiklik öncesi ve sonrası içerik gibi ayrıntıları sağlar.
Bu sınıfı, bir karşılaştırma sonucundaki bireysel değişiklikler hakkında bilgi almak için kullanın.


Örnek kullanım:

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


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ChangeInfo()](#ChangeInfo--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getRow()](#getRow--) |  |
| [setRow(Integer row)](#setRow-java.lang.Integer-) |  |
| [getColumn()](#getColumn--) |  |
| [setColumn(Integer column)](#setColumn-java.lang.Integer-) |  |
| [getColumnHeader()](#getColumnHeader--) |  |
| [setColumnHeader(String columnHeader)](#setColumnHeader-java.lang.String-) |  |
|  | [getId()](#getId--) | Değişikliğin benzersiz kimliğini alır. |
|
|  | [setId(int value)](#setId-int-) | Değişikliğin benzersiz kimliğini ayarlar. |
|
|  | [getComparisonAction()](#getComparisonAction--) | Değişikliğe uygulanacak eylemi alır. |
|
|  | [setComparisonAction(ComparisonAction value)](#setComparisonAction-com.groupdocs.comparison.result.ComparisonAction-) | Değişikliğe uygulanması gereken eylemi ayarlar. |
|
|  | [getPageInfo()](#getPageInfo--) | Geçerli değişikliğin bulunduğu sayfa hakkında bilgi alır. |
|
|  | [setPageInfo(PageInfo value)](#setPageInfo-com.groupdocs.comparison.result.PageInfo-) | Geçerli değişikliğin bulunduğu sayfa hakkında bilgiyi ayarlar. |
|
|  | [getBox()](#getBox--) | Sayfadaki değiştirilen öğenin koordinatlarını alır. |
|
|  | [setBox(Rectangle value)](#setBox-com.groupdocs.comparison.result.Rectangle-) | Sayfadaki değiştirilen öğenin koordinatlarını ayarlar. |
|
|  | [getText()](#getText--) | Değişikliğin metin değerini alır. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Değişikliğin metin değerini ayarlar. |
|
|  | [getStyleChanges()](#getStyleChanges--) | Stil değişikliklerinin listesini alır. |
|
|  | [setStyleChanges(List<StyleChangeInfo> value)](#setStyleChanges-java.util.List-com.groupdocs.comparison.result.StyleChangeInfo--) | Stil değişikliklerinin listesini ayarlar. |
|
|  | [getAuthors()](#getAuthors--) | Yazarların listesini alır. |
|
|  | [setAuthors(List<String> value)](#setAuthors-java.util.List-java.lang.String--) | Yazarların listesini ayarlar. |
|
|  | [getType()](#getType--) | Enum [ChangeType](../../com.groupdocs.comparison.result/changetype) tarafından temsil edilen değişikliğin türünü alır. |
|
|  | [getTargetText()](#getTargetText--) | Hedef belgeden değiştirilen metni alır. |
|
|  | [setTargetText(String value)](#setTargetText-java.lang.String-) | Hedef belgeden değiştirilen metni ayarlar. |
|
|  | [getSourceText()](#getSourceText--) | Kaynak belgeden değiştirilen metni alır. |
|
|  | [setSourceText(String value)](#setSourceText-java.lang.String-) | Kaynak belgeden değiştirilen metni ayarlar. |
|
|  | [getComponentType()](#getComponentType--) | Değiştirilen bileşenin türünü alır. |
|
|  | [setComponentType(String value)](#setComponentType-java.lang.String-) | Değiştirilen bileşenin türünü ayarlar. |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| satır | java.lang.Integer |  |

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sütun | java.lang.Integer |  |

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| columnHeader | java.lang.String |  |

### getId() {#getId--}
```
public final int getId()
```


Değişikliğin benzersiz kimliğini alır.


**Returns:**
int - değişikliğin kimliği

### setId(int value) {#setId-int-}
```
public final void setId(int value)
```


Değişikliğin benzersiz kimliğini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | int | Değişikliğin kimliği |
|

### getComparisonAction() {#getComparisonAction--}
```
public final ComparisonAction getComparisonAction()
```


Değişikliğe uygulanacak eylemi alır.
Eylem ([ComparisonAction.ACCEPT](../../com.groupdocs.comparison.result/comparisonaction#ACCEPT) veya [ComparisonAction.REJECT](../../com.groupdocs.comparison.result/comparisonaction#REJECT)) karşılaştırmaya bu değişiklikle ne yapılacağını söyler.


**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) - the action that will be applied to the change

### setComparisonAction(ComparisonAction value) {#setComparisonAction-com.groupdocs.comparison.result.ComparisonAction-}
```
public final void setComparisonAction(ComparisonAction value)
```


Değişikliğe uygulanması gereken eylemi ayarlar.
Eylem ([ComparisonAction.ACCEPT](../../com.groupdocs.comparison.result/comparisonaction#ACCEPT) veya [ComparisonAction.REJECT](../../com.groupdocs.comparison.result/comparisonaction#REJECT)) karşılaştırmaya bu değişiklikle ne yapılacağını söyler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) | Değişikliğe uygulanması gereken eylem |
|

### getPageInfo() {#getPageInfo--}
```
public final PageInfo getPageInfo()
```


Geçerli değişikliğin bulunduğu sayfa hakkında bilgi alır.


**Returns:**
[PageInfo](../../com.groupdocs.comparison.result/pageinfo) - information about the page

### setPageInfo(PageInfo value) {#setPageInfo-com.groupdocs.comparison.result.PageInfo-}
```
public final void setPageInfo(PageInfo value)
```


Geçerli değişikliğin bulunduğu sayfa hakkında bilgiyi ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [PageInfo](../../com.groupdocs.comparison.result/pageinfo) | Sayfa hakkında bilgi |
|

### getBox() {#getBox--}
```
public final Rectangle getBox()
```


Sayfadaki değiştirilen öğenin koordinatlarını alır.


**Returns:**
[Rectangle](../../com.groupdocs.comparison.result/rectangle) - coordinates of changed element

### setBox(Rectangle value) {#setBox-com.groupdocs.comparison.result.Rectangle-}
```
public final void setBox(Rectangle value)
```


Sayfadaki değiştirilen öğenin koordinatlarını ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [Rectangle](../../com.groupdocs.comparison.result/rectangle) | Değiştirilen öğenin koordinatları, null değil |
|

### getText() {#getText--}
```
public final String getText()
```


Değişikliğin metin değerini alır.


**Returns:**
java.lang.String - değişikliğin metin değeri

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Değişikliğin metin değerini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.lang.String | Değişikliğin metin değeri |
|

### getStyleChanges() {#getStyleChanges--}
```
public final List<StyleChangeInfo> getStyleChanges()
```


Stil değişikliklerinin listesini alır.


**Returns:**
java.util.List<com.groupdocs.comparison.result.StyleChangeInfo> - stil değişikliklerinin listesi

### setStyleChanges(List<StyleChangeInfo> value) {#setStyleChanges-java.util.List-com.groupdocs.comparison.result.StyleChangeInfo--}
```
public final void setStyleChanges(List<StyleChangeInfo> value)
```


Stil değişikliklerinin listesini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.util.List<com.groupdocs.comparison.result.StyleChangeInfo> | Stil değişikliklerinin listesi |
|

### getAuthors() {#getAuthors--}
```
public final List<String> getAuthors()
```


Yazarların listesini alır.


**Returns:**
java.util.List<java.lang.String> - yazarların listesi

### setAuthors(List<String> value) {#setAuthors-java.util.List-java.lang.String--}
```
public final void setAuthors(List<String> value)
```


Yazarların listesini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.util.List<java.lang.String> | Yazarların listesi |
|

### getType() {#getType--}
```
public final ChangeType getType()
```


Enum [ChangeType](../../com.groupdocs.comparison.result/changetype) tarafından temsil edilen değişikliğin türünü alır.


**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - the type of the change

### getTargetText() {#getTargetText--}
```
public String getTargetText()
```


Hedef belgeden değiştirilen metni alır.


**Returns:**
java.lang.String - değiştirilen metin

### setTargetText(String value) {#setTargetText-java.lang.String-}
```
public void setTargetText(String value)
```


Hedef belgeden değiştirilen metni ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.lang.String | Değiştirilen metin |
|

### getSourceText() {#getSourceText--}
```
public String getSourceText()
```


Kaynak belgeden değiştirilen metni alır.


**Returns:**
java.lang.String - değiştirilen metin

### setSourceText(String value) {#setSourceText-java.lang.String-}
```
public void setSourceText(String value)
```


Kaynak belgeden değiştirilen metni ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.lang.String | Değiştirilen metin |
|

### getComponentType() {#getComponentType--}
```
public String getComponentType()
```


Değiştirilen bileşenin türünü alır.


**Returns:**
java.lang.String - değiştirilen bileşenin türü

### setComponentType(String value) {#setComponentType-java.lang.String-}
```
public void setComponentType(String value)
```


Değiştirilen bileşenin türünü ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.lang.String | Değiştirilen bileşenin türü |
|

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
