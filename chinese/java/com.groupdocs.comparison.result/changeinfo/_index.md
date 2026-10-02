---
title: "ChangeInfo"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "ChangeInfo 类表示文档比较中特定更改的信息。"
type: docs
weight: 10
url: /zh/java/com.groupdocs.comparison.result/changeinfo/
---
**Inheritance:**
java.lang.Object
```
public class ChangeInfo
```

ChangeInfo 类表示文档比较中特定更改的信息。


它提供了诸如更改类型、受影响区域以及更改前后的内容等详细信息。
使用此类检索比较结果中各个更改的详细信息。


示例用法：

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


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ChangeInfo()](#ChangeInfo--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getRow()](#getRow--) |  |
| [setRow(Integer row)](#setRow-java.lang.Integer-) |  |
| [getColumn()](#getColumn--) |  |
| [setColumn(Integer column)](#setColumn-java.lang.Integer-) |  |
| [getColumnHeader()](#getColumnHeader--) |  |
| [setColumnHeader(String columnHeader)](#setColumnHeader-java.lang.String-) |  |
|  | [getId()](#getId--) | 获取更改的唯一标识。 |
|
|  | [setId(int value)](#setId-int-) | 设置更改的唯一标识。 |
|
|  | [getComparisonAction()](#getComparisonAction--) | 获取将应用于更改的操作。 |
|
|  | [setComparisonAction(ComparisonAction value)](#setComparisonAction-com.groupdocs.comparison.result.ComparisonAction-) | 设置应应用于更改的操作。 |
|
|  | [getPageInfo()](#getPageInfo--) | 获取当前更改所在页面的信息。 |
|
|  | [setPageInfo(PageInfo value)](#setPageInfo-com.groupdocs.comparison.result.PageInfo-) | 设置当前更改所在页面的信息。 |
|
|  | [getBox()](#getBox--) | 获取页面上更改元素的坐标。 |
|
|  | [setBox(Rectangle value)](#setBox-com.groupdocs.comparison.result.Rectangle-) | 设置页面上更改元素的坐标。 |
|
|  | [getText()](#getText--) | 获取更改的文本值。 |
|
|  | [setText(String value)](#setText-java.lang.String-) | 设置更改的文本值。 |
|
|  | [getStyleChanges()](#getStyleChanges--) | 获取样式更改列表。 |
|
|  | [setStyleChanges(List<StyleChangeInfo> value)](#setStyleChanges-java.util.List-com.groupdocs.comparison.result.StyleChangeInfo--) | 设置样式更改列表。 |
|
|  | [getAuthors()](#getAuthors--) | 获取作者列表。 |
|
|  | [setAuthors(List<String> value)](#setAuthors-java.util.List-java.lang.String--) | 设置作者列表。 |
|
|  | [getType()](#getType--) | 获取由枚举 [ChangeType](../../com.groupdocs.comparison.result/changetype) 表示的更改类型。 |
|
|  | [getTargetText()](#getTargetText--) | 获取目标文档中的更改文本。 |
|
|  | [setTargetText(String value)](#setTargetText-java.lang.String-) | 设置目标文档中的更改文本。 |
|
|  | [getSourceText()](#getSourceText--) | 获取源文档中的更改文本。 |
|
|  | [setSourceText(String value)](#setSourceText-java.lang.String-) | 设置来自源文档的已更改文本。 |
|
|  | [getComponentType()](#getComponentType--) | 获取已更改组件的类型。 |
|
|  | [setComponentType(String value)](#setComponentType-java.lang.String-) | 设置已更改组件的类型。 |
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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 行 | java.lang.Integer |  |

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 列 | java.lang.Integer |  |

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 列标题 | java.lang.String |  |

### getId() {#getId--}
```
public final int getId()
```


获取更改的唯一标识。


**Returns:**
int - 更改的 ID

### setId(int value) {#setId-int-}
```
public final void setId(int value)
```


设置更改的唯一标识。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | int | 更改的 ID |
|

### getComparisonAction() {#getComparisonAction--}
```
public final ComparisonAction getComparisonAction()
```


获取将应用于更改的操作。
操作 ([ComparisonAction.ACCEPT](../../com.groupdocs.comparison.result/comparisonaction#ACCEPT) 或 [ComparisonAction.REJECT](../../com.groupdocs.comparison.result/comparisonaction#REJECT)) 告诉比较在此更改上应执行什么操作。


**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) - the action that will be applied to the change

### setComparisonAction(ComparisonAction value) {#setComparisonAction-com.groupdocs.comparison.result.ComparisonAction-}
```
public final void setComparisonAction(ComparisonAction value)
```


设置应应用于更改的操作。
操作 ([ComparisonAction.ACCEPT](../../com.groupdocs.comparison.result/comparisonaction#ACCEPT) 或 [ComparisonAction.REJECT](../../com.groupdocs.comparison.result/comparisonaction#REJECT)) 告诉比较在此更改上应执行什么操作。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) | 应应用于此更改的操作 |
|

### getPageInfo() {#getPageInfo--}
```
public final PageInfo getPageInfo()
```


获取当前更改所在页面的信息。


**Returns:**
[PageInfo](../../com.groupdocs.comparison.result/pageinfo) - information about the page

### setPageInfo(PageInfo value) {#setPageInfo-com.groupdocs.comparison.result.PageInfo-}
```
public final void setPageInfo(PageInfo value)
```


设置当前更改所在页面的信息。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [PageInfo](../../com.groupdocs.comparison.result/pageinfo) | 页面信息 |
|

### getBox() {#getBox--}
```
public final Rectangle getBox()
```


获取页面上更改元素的坐标。


**Returns:**
[Rectangle](../../com.groupdocs.comparison.result/rectangle) - coordinates of changed element

### setBox(Rectangle value) {#setBox-com.groupdocs.comparison.result.Rectangle-}
```
public final void setBox(Rectangle value)
```


设置页面上更改元素的坐标。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [Rectangle](../../com.groupdocs.comparison.result/rectangle) | 已更改元素的坐标，不能为空 |
|

### getText() {#getText--}
```
public final String getText()
```


获取更改的文本值。


**Returns:**
java.lang.String - 更改的文本值

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


设置更改的文本值。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.lang.String | 更改的文本值 |
|

### getStyleChanges() {#getStyleChanges--}
```
public final List<StyleChangeInfo> getStyleChanges()
```


获取样式更改列表。


**Returns:**
java.util.List<com.groupdocs.comparison.result.StyleChangeInfo> - 样式更改列表

### setStyleChanges(List<StyleChangeInfo> value) {#setStyleChanges-java.util.List-com.groupdocs.comparison.result.StyleChangeInfo--}
```
public final void setStyleChanges(List<StyleChangeInfo> value)
```


设置样式更改列表。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.util.List<com.groupdocs.comparison.result.StyleChangeInfo> | 样式更改列表 |
|

### getAuthors() {#getAuthors--}
```
public final List<String> getAuthors()
```


获取作者列表。


**Returns:**
java.util.List<java.lang.String> - 作者列表

### setAuthors(List<String> value) {#setAuthors-java.util.List-java.lang.String--}
```
public final void setAuthors(List<String> value)
```


设置作者列表。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.util.List<java.lang.String> | 作者列表 |
|

### getType() {#getType--}
```
public final ChangeType getType()
```


获取由枚举 [ChangeType](../../com.groupdocs.comparison.result/changetype) 表示的更改类型。


**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - the type of the change

### getTargetText() {#getTargetText--}
```
public String getTargetText()
```


获取目标文档中的更改文本。


**Returns:**
java.lang.String - 已更改的文本

### setTargetText(String value) {#setTargetText-java.lang.String-}
```
public void setTargetText(String value)
```


设置目标文档中的更改文本。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.lang.String | 已更改的文本 |
|

### getSourceText() {#getSourceText--}
```
public String getSourceText()
```


获取源文档中的更改文本。


**Returns:**
java.lang.String - 已更改的文本

### setSourceText(String value) {#setSourceText-java.lang.String-}
```
public void setSourceText(String value)
```


设置来自源文档的已更改文本。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.lang.String | 已更改的文本 |
|

### getComponentType() {#getComponentType--}
```
public String getComponentType()
```


获取已更改组件的类型。


**Returns:**
java.lang.String - 已更改组件的类型

### setComponentType(String value) {#setComponentType-java.lang.String-}
```
public void setComponentType(String value)
```


设置已更改组件的类型。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.lang.String | 已更改组件的类型 |
|

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
