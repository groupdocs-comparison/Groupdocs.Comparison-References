---
title: "ChangeInfo"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "ChangeInfo क्लास दस्तावेज़ तुलना में एक विशिष्ट परिवर्तन की जानकारी दर्शाती है।"
type: docs
weight: 10
url: /hi/java/com.groupdocs.comparison.result/changeinfo/
---
**Inheritance:**
java.lang.Object
```
public class ChangeInfo
```

ChangeInfo क्लास दस्तावेज़ तुलना में एक विशिष्ट परिवर्तन की जानकारी दर्शाती है।


यह परिवर्तन के प्रकार, प्रभावित क्षेत्र, और परिवर्तन से पहले तथा बाद की सामग्री जैसी विवरण प्रदान करता है।
तुलना परिणाम के भीतर व्यक्तिगत परिवर्तनों के बारे में जानकारी प्राप्त करने के लिए इस क्लास का उपयोग करें।


उदाहरण उपयोग:

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


## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [ChangeInfo()](#ChangeInfo--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getRow()](#getRow--) |  |
| [setRow(Integer row)](#setRow-java.lang.Integer-) |  |
| [getColumn()](#getColumn--) |  |
| [setColumn(Integer column)](#setColumn-java.lang.Integer-) |  |
| [getColumnHeader()](#getColumnHeader--) |  |
| [setColumnHeader(String columnHeader)](#setColumnHeader-java.lang.String-) |  |
|  | [getId()](#getId--) | परिवर्तन का अद्वितीय आईडी प्राप्त करता है। |
|
|  | [setId(int value)](#setId-int-) | परिवर्तन का अद्वितीय आईडी सेट करता है। |
|
|  | [getComparisonAction()](#getComparisonAction--) | परिवर्तन पर लागू की जाने वाली क्रिया प्राप्त करता है। |
|
|  | [setComparisonAction(ComparisonAction value)](#setComparisonAction-com.groupdocs.comparison.result.ComparisonAction-) | परिवर्तन पर लागू की जानी वाली क्रिया सेट करता है। |
|
|  | [getPageInfo()](#getPageInfo--) | वर्तमान परिवर्तन जिस पृष्ठ पर मिला, उसके बारे में जानकारी प्राप्त करता है। |
|
|  | [setPageInfo(PageInfo value)](#setPageInfo-com.groupdocs.comparison.result.PageInfo-) | वर्तमान परिवर्तन जिस पृष्ठ पर मिला, उसके बारे में जानकारी सेट करता है। |
|
|  | [getBox()](#getBox--) | पृष्ठ पर बदलें तत्व के निर्देशांक प्राप्त करता है। |
|
|  | [setBox(Rectangle value)](#setBox-com.groupdocs.comparison.result.Rectangle-) | पृष्ठ पर बदलें तत्व के निर्देशांक सेट करता है। |
|
|  | [getText()](#getText--) | परिवर्तन का टेक्स्ट मान प्राप्त करता है। |
|
|  | [setText(String value)](#setText-java.lang.String-) | परिवर्तन का टेक्स्ट मान सेट करता है। |
|
|  | [getStyleChanges()](#getStyleChanges--) | स्टाइल परिवर्तनों की सूची प्राप्त करता है। |
|
|  | [setStyleChanges(List<StyleChangeInfo> value)](#setStyleChanges-java.util.List-com.groupdocs.comparison.result.StyleChangeInfo--) | स्टाइल परिवर्तनों की सूची सेट करता है। |
|
|  | [getAuthors()](#getAuthors--) | लेखकों की सूची प्राप्त करता है। |
|
|  | [setAuthors(List<String> value)](#setAuthors-java.util.List-java.lang.String--) | लेखकों की सूची सेट करता है। |
|
|  | [getType()](#getType--) | enum [ChangeType](../../com.groupdocs.comparison.result/changetype) द्वारा प्रतिनिधित्व किए गए परिवर्तन के प्रकार को प्राप्त करता है। |
|
|  | [getTargetText()](#getTargetText--) | लक्ष्य दस्तावेज़ से बदला गया टेक्स्ट प्राप्त करता है। |
|
|  | [setTargetText(String value)](#setTargetText-java.lang.String-) | लक्ष्य दस्तावेज़ से बदला गया टेक्स्ट सेट करता है। |
|
|  | [getSourceText()](#getSourceText--) | स्रोत दस्तावेज़ से बदला गया टेक्स्ट प्राप्त करता है। |
|
|  | [setSourceText(String value)](#setSourceText-java.lang.String-) | स्रोत दस्तावेज़ से बदला गया पाठ सेट करता है। |
|
|  | [getComponentType()](#getComponentType--) | बदले गए घटक का प्रकार प्राप्त करता है। |
|
|  | [setComponentType(String value)](#setComponentType-java.lang.String-) | बदले गए घटक का प्रकार सेट करता है। |
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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| पंक्ति | java.lang.Integer |  |

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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| स्तंभ | java.lang.Integer |  |

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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| स्तंभशीर्षक | java.lang.String |  |

### getId() {#getId--}
```
public final int getId()
```


परिवर्तन का अद्वितीय आईडी प्राप्त करता है।


**Returns:**
int - परिवर्तन की आईडी

### setId(int value) {#setId-int-}
```
public final void setId(int value)
```


परिवर्तन का अद्वितीय आईडी सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | int | परिवर्तन की आईडी |
|

### getComparisonAction() {#getComparisonAction--}
```
public final ComparisonAction getComparisonAction()
```


परिवर्तन पर लागू की जाने वाली क्रिया प्राप्त करता है।
क्रिया ([ComparisonAction.ACCEPT](../../com.groupdocs.comparison.result/comparisonaction#ACCEPT) या [ComparisonAction.REJECT](../../com.groupdocs.comparison.result/comparisonaction#REJECT)) तुलना को बताती है कि इस परिवर्तन के साथ क्या करना है।


**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) - the action that will be applied to the change

### setComparisonAction(ComparisonAction value) {#setComparisonAction-com.groupdocs.comparison.result.ComparisonAction-}
```
public final void setComparisonAction(ComparisonAction value)
```


परिवर्तन पर लागू की जानी वाली क्रिया सेट करता है।
क्रिया ([ComparisonAction.ACCEPT](../../com.groupdocs.comparison.result/comparisonaction#ACCEPT) या [ComparisonAction.REJECT](../../com.groupdocs.comparison.result/comparisonaction#REJECT)) तुलना को बताती है कि इस परिवर्तन के साथ क्या करना है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | [ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) | परिवर्तन पर लागू की जानी वाली क्रिया |
|

### getPageInfo() {#getPageInfo--}
```
public final PageInfo getPageInfo()
```


वर्तमान परिवर्तन जिस पृष्ठ पर मिला, उसके बारे में जानकारी प्राप्त करता है।


**Returns:**
[PageInfo](../../com.groupdocs.comparison.result/pageinfo) - information about the page

### setPageInfo(PageInfo value) {#setPageInfo-com.groupdocs.comparison.result.PageInfo-}
```
public final void setPageInfo(PageInfo value)
```


वर्तमान परिवर्तन जिस पृष्ठ पर मिला, उसके बारे में जानकारी सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | [PageInfo](../../com.groupdocs.comparison.result/pageinfo) | पृष्ठ के बारे में जानकारी |
|

### getBox() {#getBox--}
```
public final Rectangle getBox()
```


पृष्ठ पर बदलें तत्व के निर्देशांक प्राप्त करता है।


**Returns:**
[Rectangle](../../com.groupdocs.comparison.result/rectangle) - coordinates of changed element

### setBox(Rectangle value) {#setBox-com.groupdocs.comparison.result.Rectangle-}
```
public final void setBox(Rectangle value)
```


पृष्ठ पर बदलें तत्व के निर्देशांक सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | [Rectangle](../../com.groupdocs.comparison.result/rectangle) | बदले गए तत्व के निर्देशांक, null नहीं |
|

### getText() {#getText--}
```
public final String getText()
```


परिवर्तन का टेक्स्ट मान प्राप्त करता है।


**Returns:**
java.lang.String - परिवर्तन का पाठ मान

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


परिवर्तन का टेक्स्ट मान सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | java.lang.String | परिवर्तन का पाठ मान |
|

### getStyleChanges() {#getStyleChanges--}
```
public final List<StyleChangeInfo> getStyleChanges()
```


स्टाइल परिवर्तनों की सूची प्राप्त करता है।


**Returns:**
java.util.List<com.groupdocs.comparison.result.StyleChangeInfo> - शैली परिवर्तनों की सूची

### setStyleChanges(List<StyleChangeInfo> value) {#setStyleChanges-java.util.List-com.groupdocs.comparison.result.StyleChangeInfo--}
```
public final void setStyleChanges(List<StyleChangeInfo> value)
```


स्टाइल परिवर्तनों की सूची सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | java.util.List<com.groupdocs.comparison.result.StyleChangeInfo> | शैली परिवर्तनों की सूची |
|

### getAuthors() {#getAuthors--}
```
public final List<String> getAuthors()
```


लेखकों की सूची प्राप्त करता है।


**Returns:**
java.util.List<java.lang.String> - लेखकों की सूची

### setAuthors(List<String> value) {#setAuthors-java.util.List-java.lang.String--}
```
public final void setAuthors(List<String> value)
```


लेखकों की सूची सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | java.util.List<java.lang.String> | लेखकों की सूची |
|

### getType() {#getType--}
```
public final ChangeType getType()
```


enum [ChangeType](../../com.groupdocs.comparison.result/changetype) द्वारा प्रतिनिधित्व किए गए परिवर्तन के प्रकार को प्राप्त करता है।


**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - the type of the change

### getTargetText() {#getTargetText--}
```
public String getTargetText()
```


लक्ष्य दस्तावेज़ से बदला गया टेक्स्ट प्राप्त करता है।


**Returns:**
java.lang.String - बदला गया पाठ

### setTargetText(String value) {#setTargetText-java.lang.String-}
```
public void setTargetText(String value)
```


लक्ष्य दस्तावेज़ से बदला गया टेक्स्ट सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | java.lang.String | बदला गया पाठ |
|

### getSourceText() {#getSourceText--}
```
public String getSourceText()
```


स्रोत दस्तावेज़ से बदला गया टेक्स्ट प्राप्त करता है।


**Returns:**
java.lang.String - बदला गया पाठ

### setSourceText(String value) {#setSourceText-java.lang.String-}
```
public void setSourceText(String value)
```


स्रोत दस्तावेज़ से बदला गया पाठ सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | java.lang.String | बदला गया पाठ |
|

### getComponentType() {#getComponentType--}
```
public String getComponentType()
```


बदले गए घटक का प्रकार प्राप्त करता है।


**Returns:**
java.lang.String - बदले गए घटक का प्रकार

### setComponentType(String value) {#setComponentType-java.lang.String-}
```
public void setComponentType(String value)
```


बदले गए घटक का प्रकार सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | java.lang.String | बदले गए घटक का प्रकार |
|

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
