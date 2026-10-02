---
title: "DiagramMasterSetting"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "表示图表主比较的设置。"
type: docs
weight: 10
url: /zh/java/com.groupdocs.comparison.options.style/diagrammastersetting/
---
**Inheritance:**
java.lang.Object
```
public class DiagramMasterSetting
```

表示图表主比较的设置。


示例用法：

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    final DiagramMasterSetting diagramMasterSetting = new DiagramMasterSetting();
    diagramMasterSetting.setMasterPath(masterFilePath);

    final CompareOptions compareOptions = new CompareOptions();
    compareOptions.setDiagramMasterSetting(diagramMasterSetting);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [DiagramMasterSetting()](#DiagramMasterSetting--) | 初始化 DiagramMasterSetting 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [isUseSourceMaster()](#isUseSourceMaster--) | 获取一个标志，指示是否将使用源主路径。 |
|
|  | [setUseSourceMaster(boolean value)](#setUseSourceMaster-boolean-) | 获取一个标志，指示是否应使用源主路径。 |
|
|  | [getMasterPath()](#getMasterPath--) | 获取将用于渲染文档的主路径。 |
|
|  | [setMasterPath(String value)](#setMasterPath-java.lang.String-) | 设置应用于渲染文档的主路径。 |
|
### DiagramMasterSetting() {#DiagramMasterSetting--}
```
public DiagramMasterSetting()
```


初始化 DiagramMasterSetting 类的新实例。


### isUseSourceMaster() {#isUseSourceMaster--}
```
public final boolean isUseSourceMaster()
```


获取一个标志，指示是否将使用源主路径。


**Returns:**
boolean - 如果将显示源主路径，则为 true，否则为 false

### setUseSourceMaster(boolean value) {#setUseSourceMaster-boolean-}
```
public final void setUseSourceMaster(boolean value)
```


获取一个标志，指示是否应使用源主路径。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | 如果应显示源主路径，则为 true，否则为 false |
|

### getMasterPath() {#getMasterPath--}
```
public final String getMasterPath()
```


获取将用于渲染文档的主路径。MasterPath 用于从一组默认形状创建结果文档。


**Returns:**
java.lang.String - 如果已设置，则为主文档路径，否则为默认主路径

### setMasterPath(String value) {#setMasterPath-java.lang.String-}
```
public final void setMasterPath(String value)
```


设置应用于渲染文档的主路径。MasterPath 用于从一组默认形状创建结果文档。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.lang.String | 如果已设置，则为主文档路径，否则为默认主路径。 |
|

