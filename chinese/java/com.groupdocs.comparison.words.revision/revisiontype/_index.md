---
title: "RevisionType"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "表示文档中修订的类型。"
type: docs
weight: 14
url: /zh/java/com.groupdocs.comparison.words.revision/revisiontype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum RevisionType extends Enum<RevisionType>
```

表示文档中修订的类型。


示例用法：

````

 try (RevisionHandler revisionHandler = new RevisionHandler(sourceFile)) {
     List revisionList = revisionHandler.getRevisions();

     for (RevisionInfo revisionInfo : revisionList) {
         if (revisionInfo.getType() == RevisionType.DELETION)
             // Set an action to be applied to the revision
             revisionInfo.setAction(RevisionAction.Accept);
     }
     // Create an instance of ApplyRevisionOptions
     ApplyRevisionOptions revisionChanges = new ApplyRevisionOptions();
     revisionChanges.setChanges(revisionList);
     // Apply the revisions using the options
     revisionHandler.applyRevisionChanges(resultFile, revisionChanges);
 }
 
````


## 字段

| 字段 | 描述 |
| --- | --- |
|  | [INSERTION](#INSERTION) | 表示在文档中插入新内容时的类型。 |
|
|  | [DELETION](#DELETION) | 表示从文档中删除内容时的类型。 |
|
|  | [FORMAT_CHANGE](#FORMAT-CHANGE) | 表示对父节点应用格式更改时的类型。 |
|
|  | [STYLE_DEFINITION_CHANGE](#STYLE-DEFINITION-CHANGE) | 表示对父样式应用格式更改时的类型。 |
|
|  | [MOVING](#MOVING) | 表示在文档中移动内容时的类型。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromInt(int toIntValue)](#fromInt-int-) | 使用提供的数值创建枚举 RevisionType 的新常量。 |
|
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | 解析 RevisionType 的字符串表示以获取枚举常量。 |
|
|  | [toInt()](#toInt--) | RevisionType 的数值表示。 |
|
|  | [toString()](#toString--) | RevisionType 的字符串表示。 |
|
### INSERTION {#INSERTION}
```
public static final RevisionType INSERTION
```


表示在文档中插入新内容时的类型。


### DELETION {#DELETION}
```
public static final RevisionType DELETION
```


表示从文档中删除内容时的类型。


### FORMAT_CHANGE {#FORMAT-CHANGE}
```
public static final RevisionType FORMAT_CHANGE
```


表示对父节点应用格式更改时的类型。


### STYLE_DEFINITION_CHANGE {#STYLE-DEFINITION-CHANGE}
```
public static final RevisionType STYLE_DEFINITION_CHANGE
```


表示对父样式应用格式更改时的类型。


### MOVING {#MOVING}
```
public static final RevisionType MOVING
```


表示在文档中移动内容时的类型。


### values() {#values--}
```
public static RevisionType[] values()
```




**Returns:**
com.groupdocs.comparison.words.revision.RevisionType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static RevisionType valueOf(String name)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String |  |

**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype)
### fromInt(int toIntValue) {#fromInt-int-}
```
public static RevisionType fromInt(int toIntValue)
```


使用提供的数值创建枚举 RevisionType 的新常量。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | toIntValue | int | RevisionType 的数值表示 |
|

**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) - RevisionType enum constant associated with numeric value

### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static RevisionType fromString(String toStringValue)
```


解析 RevisionType 的字符串表示以获取枚举常量。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | toStringValue | java.lang.String | RevisionType 的字符串表示 |
|

**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) - RevisionType enum constant associated with input string

### toInt() {#toInt--}
```
public int toInt()
```


RevisionType 的数值表示。


**Returns:**
int - 枚举常量的数值

### toString() {#toString--}
```
public String toString()
```


RevisionType 的字符串表示。


**Returns:**
java.lang.String - 枚举常量的字符串值

