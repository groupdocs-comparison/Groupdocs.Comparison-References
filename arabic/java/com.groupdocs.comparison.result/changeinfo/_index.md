---
title: "ChangeInfo"
second_title: "GroupDocs.Comparison لـ Java API Reference"
description: "تمثل فئة ChangeInfo معلومات حول تغيير محدد في مقارنة المستند."
type: docs
weight: 10
url: /ar/java/com.groupdocs.comparison.result/changeinfo/
---
**Inheritance:**
java.lang.Object
```
public class ChangeInfo
```

تمثل فئة ChangeInfo معلومات حول تغيير محدد في مقارنة المستند.


يوفر تفاصيل مثل نوع التغيير، المنطقة المتأثرة، والمحتوى قبل وبعد التغيير.
استخدم هذه الفئة لاسترجاع المعلومات حول التغييرات الفردية داخل نتيجة المقارنة.


مثال على الاستخدام:

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


## المنشئات

| منشئ | الوصف |
| --- | --- |
| [ChangeInfo()](#ChangeInfo--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getRow()](#getRow--) |  |
| [setRow(Integer row)](#setRow-java.lang.Integer-) |  |
| [getColumn()](#getColumn--) |  |
| [setColumn(Integer column)](#setColumn-java.lang.Integer-) |  |
| [getColumnHeader()](#getColumnHeader--) |  |
| [setColumnHeader(String columnHeader)](#setColumnHeader-java.lang.String-) |  |
|  | [getId()](#getId--) | يحصل على المعرف الفريد للتغيير. |
|
|  | [setId(int value)](#setId-int-) | يضبط المعرف الفريد للتغيير. |
|
|  | [getComparisonAction()](#getComparisonAction--) | يحصل على الإجراء الذي سيُطبق على التغيير. |
|
|  | [setComparisonAction(ComparisonAction value)](#setComparisonAction-com.groupdocs.comparison.result.ComparisonAction-) | يضبط الإجراء الذي يجب تطبيقه على التغيير. |
|
|  | [getPageInfo()](#getPageInfo--) | يحصل على معلومات حول الصفحة التي تم العثور فيها على التغيير الحالي. |
|
|  | [setPageInfo(PageInfo value)](#setPageInfo-com.groupdocs.comparison.result.PageInfo-) | يضبط معلومات حول الصفحة التي تم العثور فيها على التغيير الحالي. |
|
|  | [getBox()](#getBox--) | يحصل على إحداثيات العنصر المتغير على الصفحة. |
|
|  | [setBox(Rectangle value)](#setBox-com.groupdocs.comparison.result.Rectangle-) | يضبط إحداثيات العنصر المتغير على الصفحة. |
|
|  | [getText()](#getText--) | يحصل على قيمة النص للتغيير. |
|
|  | [setText(String value)](#setText-java.lang.String-) | يضبط قيمة النص للتغيير. |
|
|  | [getStyleChanges()](#getStyleChanges--) | يحصل على قائمة تغييرات النمط. |
|
|  | [setStyleChanges(List<StyleChangeInfo> value)](#setStyleChanges-java.util.List-com.groupdocs.comparison.result.StyleChangeInfo--) | يضبط قائمة تغييرات النمط. |
|
|  | [getAuthors()](#getAuthors--) | يحصل على قائمة المؤلفين. |
|
|  | [setAuthors(List<String> value)](#setAuthors-java.util.List-java.lang.String--) | يضبط قائمة المؤلفين. |
|
|  | [getType()](#getType--) | يحصل على نوع التغيير الممثل بواسطة تعداد [ChangeType](../../com.groupdocs.comparison.result/changetype). |
|
|  | [getTargetText()](#getTargetText--) | يحصل على النص المتغير من المستند الهدف. |
|
|  | [setTargetText(String value)](#setTargetText-java.lang.String-) | يضبط النص المتغير من المستند الهدف. |
|
|  | [getSourceText()](#getSourceText--) | يحصل على النص المتغير من المستند المصدر. |
|
|  | [setSourceText(String value)](#setSourceText-java.lang.String-) | يضبط النص المتغيّر من المستند المصدر. |
|
|  | [getComponentType()](#getComponentType--) | يحصل على نوع المكوّن المتغيّر. |
|
|  | [setComponentType(String value)](#setComponentType-java.lang.String-) | يضبط نوع المكوّن المتغيّر. |
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
| معامل | نوع | الوصف |
| --- | --- | --- |
| صف | java.lang.Integer |  |

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
| معامل | نوع | الوصف |
| --- | --- | --- |
| عمود | java.lang.Integer |  |

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
| معامل | نوع | الوصف |
| --- | --- | --- |
| رأس العمود | java.lang.String |  |

### getId() {#getId--}
```
public final int getId()
```


يحصل على المعرف الفريد للتغيير.


**Returns:**
int - معرف التغيير

### setId(int value) {#setId-int-}
```
public final void setId(int value)
```


يضبط المعرف الفريد للتغيير.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | int | معرف التغيير |
|

### getComparisonAction() {#getComparisonAction--}
```
public final ComparisonAction getComparisonAction()
```


يحصل على الإجراء الذي سيُطبق على التغيير.
الإجراء ([ComparisonAction.ACCEPT](../../com.groupdocs.comparison.result/comparisonaction#ACCEPT) أو [ComparisonAction.REJECT](../../com.groupdocs.comparison.result/comparisonaction#REJECT)) يخبر المقارنة بما يجب القيام به لهذا التغيير.


**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) - the action that will be applied to the change

### setComparisonAction(ComparisonAction value) {#setComparisonAction-com.groupdocs.comparison.result.ComparisonAction-}
```
public final void setComparisonAction(ComparisonAction value)
```


يضبط الإجراء الذي يجب تطبيقه على التغيير.
الإجراء ([ComparisonAction.ACCEPT](../../com.groupdocs.comparison.result/comparisonaction#ACCEPT) أو [ComparisonAction.REJECT](../../com.groupdocs.comparison.result/comparisonaction#REJECT)) يخبر المقارنة بما يجب القيام به لهذا التغيير.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) | الإجراء الذي يجب تطبيقه على التغيير |
|

### getPageInfo() {#getPageInfo--}
```
public final PageInfo getPageInfo()
```


يحصل على معلومات حول الصفحة التي تم العثور فيها على التغيير الحالي.


**Returns:**
[PageInfo](../../com.groupdocs.comparison.result/pageinfo) - information about the page

### setPageInfo(PageInfo value) {#setPageInfo-com.groupdocs.comparison.result.PageInfo-}
```
public final void setPageInfo(PageInfo value)
```


يضبط معلومات حول الصفحة التي تم العثور فيها على التغيير الحالي.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [PageInfo](../../com.groupdocs.comparison.result/pageinfo) | معلومات حول الصفحة |
|

### getBox() {#getBox--}
```
public final Rectangle getBox()
```


يحصل على إحداثيات العنصر المتغير على الصفحة.


**Returns:**
[Rectangle](../../com.groupdocs.comparison.result/rectangle) - coordinates of changed element

### setBox(Rectangle value) {#setBox-com.groupdocs.comparison.result.Rectangle-}
```
public final void setBox(Rectangle value)
```


يضبط إحداثيات العنصر المتغير على الصفحة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [Rectangle](../../com.groupdocs.comparison.result/rectangle) | إحداثيات العنصر المتغيّر، غير فارغة |
|

### getText() {#getText--}
```
public final String getText()
```


يحصل على قيمة النص للتغيير.


**Returns:**
java.lang.String - قيمة النص للتغيير

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


يضبط قيمة النص للتغيير.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | java.lang.String | قيمة النص للتغيير |
|

### getStyleChanges() {#getStyleChanges--}
```
public final List<StyleChangeInfo> getStyleChanges()
```


يحصل على قائمة تغييرات النمط.


**Returns:**
java.util.List<com.groupdocs.comparison.result.StyleChangeInfo> - قائمة تغييرات النمط

### setStyleChanges(List<StyleChangeInfo> value) {#setStyleChanges-java.util.List-com.groupdocs.comparison.result.StyleChangeInfo--}
```
public final void setStyleChanges(List<StyleChangeInfo> value)
```


يضبط قائمة تغييرات النمط.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | java.util.List<com.groupdocs.comparison.result.StyleChangeInfo> | قائمة تغييرات النمط |
|

### getAuthors() {#getAuthors--}
```
public final List<String> getAuthors()
```


يحصل على قائمة المؤلفين.


**Returns:**
java.util.List<java.lang.String> - قائمة المؤلفين

### setAuthors(List<String> value) {#setAuthors-java.util.List-java.lang.String--}
```
public final void setAuthors(List<String> value)
```


يضبط قائمة المؤلفين.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | java.util.List<java.lang.String> | قائمة المؤلفين |
|

### getType() {#getType--}
```
public final ChangeType getType()
```


يحصل على نوع التغيير الممثل بواسطة تعداد [ChangeType](../../com.groupdocs.comparison.result/changetype).


**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - the type of the change

### getTargetText() {#getTargetText--}
```
public String getTargetText()
```


يحصل على النص المتغير من المستند الهدف.


**Returns:**
java.lang.String - النص المتغيّر

### setTargetText(String value) {#setTargetText-java.lang.String-}
```
public void setTargetText(String value)
```


يضبط النص المتغير من المستند الهدف.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | java.lang.String | النص المتغيّر |
|

### getSourceText() {#getSourceText--}
```
public String getSourceText()
```


يحصل على النص المتغير من المستند المصدر.


**Returns:**
java.lang.String - النص المتغيّر

### setSourceText(String value) {#setSourceText-java.lang.String-}
```
public void setSourceText(String value)
```


يضبط النص المتغيّر من المستند المصدر.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | java.lang.String | النص المتغيّر |
|

### getComponentType() {#getComponentType--}
```
public String getComponentType()
```


يحصل على نوع المكوّن المتغيّر.


**Returns:**
java.lang.String - نوع المكوّن المتغيّر

### setComponentType(String value) {#setComponentType-java.lang.String-}
```
public void setComponentType(String value)
```


يضبط نوع المكوّن المتغيّر.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | java.lang.String | نوع المكوّن المتغيّر |
|

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
