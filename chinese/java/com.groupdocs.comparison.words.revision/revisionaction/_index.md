---
title: "RevisionAction"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "表示可以应用于修订的操作。"
type: docs
weight: 13
url: /zh/java/com.groupdocs.comparison.words.revision/revisionaction/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum RevisionAction extends Enum<RevisionAction>
```

表示可以应用于修订的操作。


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
|  | [NONE](#NONE) | 表示不需要采取任何操作。 |
|
|  | [ACCEPT](#ACCEPT) | 表示如果修订的类型是 INSERTION，则会显示该修订；如果类型是 DELETION，则会删除该修订。 |
|
|  | [REJECT](#REJECT) | 表示如果修订的类型是 INSERTION，则会删除该修订；如果类型是 DELETION，则会显示该修订。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### NONE {#NONE}
```
public static final RevisionAction NONE
```


表示不需要采取任何操作。


### ACCEPT {#ACCEPT}
```
public static final RevisionAction ACCEPT
```


表示如果修订的类型是 INSERTION，则会显示该修订；如果类型是 DELETION，则会删除该修订。


### REJECT {#REJECT}
```
public static final RevisionAction REJECT
```


表示如果修订的类型是 INSERTION，则会删除该修订；如果类型是 DELETION，则会显示该修订。


### values() {#values--}
```
public static RevisionAction[] values()
```




**Returns:**
com.groupdocs.comparison.words.revision.RevisionAction[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static RevisionAction valueOf(String name)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String |  |

**Returns:**
[RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction)
