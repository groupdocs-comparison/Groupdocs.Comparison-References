---
title: "ApplyChangeOptions"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "允许在将更改应用到结果文档之前更新更改列表。"
type: docs
weight: 10
url: /zh/java/com.groupdocs.comparison.options/applychangeoptions/
---
**Inheritance:**
java.lang.Object
```
public class ApplyChangeOptions
```

允许在将更改应用到结果文档之前更新更改列表。


示例用法：

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);
     comparer.compare();
     ChangeInfo[] changes = comparer.getChanges();
     changes[0].setComparisonAction(ComparisonAction.REJECT);

     final ApplyChangeOptions applyChangeOptions = new ApplyChangeOptions(changes);

     comparer.applyChanges(resultFile, applyChangeOptions);
 }
 
````


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [ApplyChangeOptions()](#ApplyChangeOptions--) | 初始化 ApplyChangeOptions 类的新实例。 |
|
|  | [ApplyChangeOptions(List<ChangeInfo> changes)](#ApplyChangeOptions-java.util.List-com.groupdocs.comparison.result.ChangeInfo--) | 使用更改列表初始化 ApplyChangeOptions 类的新实例。 |
|
|  | [ApplyChangeOptions(ChangeInfo[] changes)](#ApplyChangeOptions-com.groupdocs.comparison.result.ChangeInfo---) | 使用更改数组初始化 ApplyChangeOptions 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getChanges()](#getChanges--) | 获取必须应用于生成文档的更改数组。 |
|
|  | [setChanges(ChangeInfo[] value)](#setChanges-com.groupdocs.comparison.result.ChangeInfo---) | 设置必须应用于生成文档的更改数组。 |
|
|  | [setChanges(List<ChangeInfo> value)](#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--) | 设置必须应用于生成文档的更改列表。 |
|
|  | [isSaveOriginalState()](#isSaveOriginalState--) | 获取决定是否应保存原始状态的标志。 |
|
|  | [setSaveOriginalState(boolean saveOriginalState)](#setSaveOriginalState-boolean-) | 设置决定是否应保存原始状态的标志。 |
|
### ApplyChangeOptions() {#ApplyChangeOptions--}
```
public ApplyChangeOptions()
```


初始化 ApplyChangeOptions 类的新实例。


### ApplyChangeOptions(List<ChangeInfo> changes) {#ApplyChangeOptions-java.util.List-com.groupdocs.comparison.result.ChangeInfo--}
```
public ApplyChangeOptions(List<ChangeInfo> changes)
```


使用更改列表初始化 ApplyChangeOptions 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 更改 | java.util.List<com.groupdocs.comparison.result.ChangeInfo> | 要应用的更改列表 |
|

### ApplyChangeOptions(ChangeInfo[] changes) {#ApplyChangeOptions-com.groupdocs.comparison.result.ChangeInfo---}
```
public ApplyChangeOptions(ChangeInfo[] changes)
```


使用更改数组初始化 ApplyChangeOptions 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | changes | [ChangeInfo\[\]](../../com.groupdocs.comparison.result/changeinfo) | 要应用的更改列表 |
|

### getChanges() {#getChanges--}
```
public final ChangeInfo[] getChanges()
```


获取必须应用于生成文档的更改数组。


**Returns:**
com.groupdocs.comparison.result.ChangeInfo[] - 要应用的更改数组

### setChanges(ChangeInfo[] value) {#setChanges-com.groupdocs.comparison.result.ChangeInfo---}
```
public final void setChanges(ChangeInfo[] value)
```


设置必须应用于生成文档的更改数组。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [ChangeInfo\[\]](../../com.groupdocs.comparison.result/changeinfo) | 要应用的更改数组 |
|

### setChanges(List<ChangeInfo> value) {#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--}
```
public final void setChanges(List<ChangeInfo> value)
```


设置必须应用于生成文档的更改列表。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.util.List<com.groupdocs.comparison.result.ChangeInfo> | 要应用的更改列表 |
|

### isSaveOriginalState() {#isSaveOriginalState--}
```
public boolean isSaveOriginalState()
```


获取决定是否应保存原始状态的标志。默认值：false。


**Returns:**
boolean - 如果应保存原始状态则为 true，否则为 false

### setSaveOriginalState(boolean saveOriginalState) {#setSaveOriginalState-boolean-}
```
public void setSaveOriginalState(boolean saveOriginalState)
```


设置决定是否应保存原始状态的标志。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | saveOriginalState | boolean | 如果应保存原始状态则为 true，否则为 false |
|

