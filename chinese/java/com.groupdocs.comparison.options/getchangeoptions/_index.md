---
title: "GetChangeOptions"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "允许配置过滤，以从比较结果中检索特定的更改类型。"
type: docs
weight: 13
url: /zh/java/com.groupdocs.comparison.options/getchangeoptions/
---
**Inheritance:**
java.lang.Object
```
public class GetChangeOptions
```

允许配置过滤，以从比较结果中检索特定的更改类型。


示例用法：

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);
     comparer.compare();

     GetChangeOptions getChangeOptions = new GetChangeOptions();

     getChangeOptions.setFilter(ChangeType.DELETED);

     ChangeInfo[] changes = comparer.getChanges(getChangeOptions);
     System.out.println(Arrays.toString(changes));
 }
 
````


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [GetChangeOptions()](#GetChangeOptions--) | 初始化 GetChangeOptions 类的新实例。 |
|
|  | [GetChangeOptions(ChangeType filter)](#GetChangeOptions-com.groupdocs.comparison.result.ChangeType-) | 为指定的过滤类型初始化 GetChangeOptions 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getFilter()](#getFilter--) | 获取用于从比较结果中检索特定更改类型的过滤器。 |
|
|  | [setFilter(ChangeType value)](#setFilter-com.groupdocs.comparison.result.ChangeType-) | 设置用于从比较结果中检索特定更改类型的过滤器。 |
|
### GetChangeOptions() {#GetChangeOptions--}
```
public GetChangeOptions()
```


初始化 GetChangeOptions 类的新实例。


### GetChangeOptions(ChangeType filter) {#GetChangeOptions-com.groupdocs.comparison.result.ChangeType-}
```
public GetChangeOptions(ChangeType filter)
```


为指定的过滤类型初始化 GetChangeOptions 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filter | [ChangeType](../../com.groupdocs.comparison.result/changetype) |  |

### getFilter() {#getFilter--}
```
public final ChangeType getFilter()
```


获取用于从比较结果中检索特定更改类型的过滤器。


**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - the filter specifying the types of changes to be retrieved.

### setFilter(ChangeType value) {#setFilter-com.groupdocs.comparison.result.ChangeType-}
```
public final void setFilter(ChangeType value)
```


设置用于从比较结果中检索特定更改类型的过滤器。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [ChangeType](../../com.groupdocs.comparison.result/changetype) | 指定要检索的更改类型的过滤器。 |
|

