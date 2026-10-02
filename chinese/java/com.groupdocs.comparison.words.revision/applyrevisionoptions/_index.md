---
title: "ApplyRevisionOptions"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "ApplyRevisionOptions 类允许您在修订应用到最终文档之前更新其状态。"
type: docs
weight: 10
url: /zh/java/com.groupdocs.comparison.words.revision/applyrevisionoptions/
---
**Inheritance:**
java.lang.Object
```
public class ApplyRevisionOptions
```

ApplyRevisionOptions 类允许您在修订应用到最终文档之前更新其状态。


它提供了各种构造函数和属性，以自定义修订应用过程。


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


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [ApplyRevisionOptions()](#ApplyRevisionOptions--) | 初始化 ApplyRevisionOptions 类的新实例。 |
|
|  | [ApplyRevisionOptions(List<RevisionInfo> changes)](#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--) | 使用指定的修订列表实例化一个新的 ApplyRevisionOptions 对象。 |
|
|  | [ApplyRevisionOptions(List<RevisionInfo> changes, RevisionAction revisionAction)](#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--com.groupdocs.comparison.words.revision.RevisionAction-) | 实例化一个新的 ApplyRevisionOptions 对象，使用指定的修订列表和通用修订操作。 |
|
|  | [ApplyRevisionOptions(RevisionAction revisionAction)](#ApplyRevisionOptions-com.groupdocs.comparison.words.revision.RevisionAction-) | 实例化一个新的 ApplyRevisionOptions 对象，使用通用修订操作。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getChanges()](#getChanges--) | 获取要应用的修订列表。 |
|
|  | [setChanges(List<RevisionInfo> changes)](#setChanges-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--) | 设置要应用的修订列表。 |
|
|  | [getCommonHandler()](#getCommonHandler--) | 获取要应用于所有修订的通用修订操作。 |
|
|  | [setCommonHandler(RevisionAction commonHandler)](#setCommonHandler-com.groupdocs.comparison.words.revision.RevisionAction-) | 设置要应用于所有修订的通用修订操作。 |
|
### ApplyRevisionOptions() {#ApplyRevisionOptions--}
```
public ApplyRevisionOptions()
```


初始化 ApplyRevisionOptions 类的新实例。


### ApplyRevisionOptions(List<RevisionInfo> changes) {#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--}
```
public ApplyRevisionOptions(List<RevisionInfo> changes)
```


使用指定的修订列表实例化一个新的 ApplyRevisionOptions 对象。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 更改 | java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> | 要应用的修订列表 |
|

### ApplyRevisionOptions(List<RevisionInfo> changes, RevisionAction revisionAction) {#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--com.groupdocs.comparison.words.revision.RevisionAction-}
```
public ApplyRevisionOptions(List<RevisionInfo> changes, RevisionAction revisionAction)
```


实例化一个新的 ApplyRevisionOptions 对象，使用指定的修订列表和通用修订操作。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 更改 | java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> | 要应用的修订列表 |
|
|  | revisionAction | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | 要应用于所有修订的通用修订操作 |
|

### ApplyRevisionOptions(RevisionAction revisionAction) {#ApplyRevisionOptions-com.groupdocs.comparison.words.revision.RevisionAction-}
```
public ApplyRevisionOptions(RevisionAction revisionAction)
```


实例化一个新的 ApplyRevisionOptions 对象，使用通用修订操作。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | revisionAction | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | 要应用于所有修订的通用修订操作 |
|

### getChanges() {#getChanges--}
```
public List<RevisionInfo> getChanges()
```


获取要应用的修订列表。


**Returns:**
java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> - 修订列表

### setChanges(List<RevisionInfo> changes) {#setChanges-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--}
```
public void setChanges(List<RevisionInfo> changes)
```


设置要应用的修订列表。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 更改 | java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> | 修订列表 |
|

### getCommonHandler() {#getCommonHandler--}
```
public RevisionAction getCommonHandler()
```


获取要应用于所有修订的通用修订操作。


**Returns:**
[RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) - the common revision action

### setCommonHandler(RevisionAction commonHandler) {#setCommonHandler-com.groupdocs.comparison.words.revision.RevisionAction-}
```
public void setCommonHandler(RevisionAction commonHandler)
```


设置要应用于所有修订的通用修订操作。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | commonHandler | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | 通用修订操作 |
|

