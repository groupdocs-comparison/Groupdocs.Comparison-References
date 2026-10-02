---
title: "RevisionInfo"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "表示文档中的一次修订。"
type: docs
weight: 12
url: /zh/java/com.groupdocs.comparison.words.revision/revisioninfo/
---
**Inheritance:**
java.lang.Object
```
public class RevisionInfo
```

表示文档中的一次修订。


修订封装了对文档所做的修订更改的信息。
此类提供方法来检索修订的信息，例如其类型，
内容、作者等。

示例用法：

````

 try (RevisionHandler revisionHandler = new RevisionHandler(sourceFile)) {
     List revisionList = revisionHandler.getRevisions();

     for (RevisionInfo revisionInfo : revisionList) {
         System.out.println("Revision Type: " + revisionInfo.getType());
         System.out.println("Text: " + revisionInfo.getText());
         System.out.println("Author: " + revisionInfo.getAuthor());
     }
 }
 
````


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [RevisionInfo()](#RevisionInfo--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getAction()](#getAction--) | 获取与修订关联的操作（接受或拒绝）。 |
|
|  | [setAction(RevisionAction value)](#setAction-com.groupdocs.comparison.words.revision.RevisionAction-) | 设置与修订关联的值（接受或拒绝）。 |
|
|  | [getText()](#getText--) | 获取修订的文本内容。 |
|
|  | [setText(String value)](#setText-java.lang.String-) | 设置修订的值内容。 |
|
|  | [getAuthor()](#getAuthor--) | 获取修订的作者。 |
|
|  | [setAuthor(String value)](#setAuthor-java.lang.String-) | 设置修订的值。 |
|
|  | [getType()](#getType--) | 获取修订的类型，依据类型，操作（接受或拒绝）的逻辑会改变。 |
|
|  | [setType(RevisionType value)](#setType-com.groupdocs.comparison.words.revision.RevisionType-) | 设置修订的值，依据该值，操作（接受或拒绝）的逻辑会改变。 |
|
### RevisionInfo() {#RevisionInfo--}
```
public RevisionInfo()
```


### getAction() {#getAction--}
```
public RevisionAction getAction()
```


获取与修订关联的操作（接受或拒绝）。此字段允许您影响修订的显示。


**Returns:**
[RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) - the action associated with the revision.

### setAction(RevisionAction value) {#setAction-com.groupdocs.comparison.words.revision.RevisionAction-}
```
public void setAction(RevisionAction value)
```


设置与修订关联的值（接受或拒绝）。此字段允许您影响修订的显示。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | 与修订关联的值。 |
|

### getText() {#getText--}
```
public String getText()
```


获取修订的文本内容。


**Returns:**
java.lang.String - 修订的文本内容。

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


设置修订的值内容。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.lang.String | 修订的值内容。 |
|

### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


获取修订的作者。


**Returns:**
java.lang.String - 修订的作者。

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public void setAuthor(String value)
```


设置修订的值。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.lang.String | 修订的值。 |
|

### getType() {#getType--}
```
public RevisionType getType()
```


获取修订的类型，依据类型，操作（接受或拒绝）的逻辑会改变。


**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) - the type of the revision.

### setType(RevisionType value) {#setType-com.groupdocs.comparison.words.revision.RevisionType-}
```
public void setType(RevisionType value)
```


设置修订的值，依据该值，操作（接受或拒绝）的逻辑会改变。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) | 修订的值。 |
|

