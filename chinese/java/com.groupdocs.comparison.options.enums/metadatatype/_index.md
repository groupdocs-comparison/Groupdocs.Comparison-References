---
title: "MetadataType"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "确定结果文档将从何处获取元数据信息。"
type: docs
weight: 12
url: /zh/java/com.groupdocs.comparison.options.enums/metadatatype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum MetadataType extends Enum<MetadataType>
```

确定结果文档将从何处获取元数据信息。


示例用法：

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    SaveOptions saveOptions = new SaveOptions();
    saveOptions.setCloneMetadataType(MetadataType.FILE_AUTHOR);

    comparer.compare(resultFile, saveOptions);
 }
 
````


## 字段

| 字段 | 描述 |
| --- | --- |
|  | [DEFAULT](#DEFAULT) | 元数据将保持不变。 |
|
|  | [SOURCE](#SOURCE) | Metedata 将从源文档中获取。 |
|
|  | [TARGET](#TARGET) | Metedata 将从目标文档中获取。 |
|
|  | [FILE_AUTHOR](#FILE-AUTHOR) | Metedata 将由用户设置。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | 解析 MetadataType 的字符串表示以获取枚举常量。 |
|
|  | [toString()](#toString--) | MetadataType 的字符串表示形式。 |
|
### DEFAULT {#DEFAULT}
```
public static final MetadataType DEFAULT
```


元数据将保持不变。


### SOURCE {#SOURCE}
```
public static final MetadataType SOURCE
```


Metedata 将从源文档中获取。


### TARGET {#TARGET}
```
public static final MetadataType TARGET
```


Metedata 将从目标文档中获取。


### FILE_AUTHOR {#FILE-AUTHOR}
```
public static final MetadataType FILE_AUTHOR
```


Metedata 将由用户设置。


### values() {#values--}
```
public static MetadataType[] values()
```




**Returns:**
com.groupdocs.comparison.options.enums.MetadataType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static MetadataType valueOf(String name)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String |  |

**Returns:**
[MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static MetadataType fromString(String toStringValue)
```


解析 MetadataType 的字符串表示以获取枚举常量。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | toStringValue | java.lang.String | MetadataType 的字符串表示形式 |
|

**Returns:**
[MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) - MetadataType enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


MetadataType 的字符串表示形式。


**Returns:**
java.lang.String - 枚举常量的字符串值

