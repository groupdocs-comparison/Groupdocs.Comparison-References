---
title: "PasswordSaveOption"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "枚举在比较过程中在文档中保存密码信息的选项。"
type: docs
weight: 14
url: /zh/java/com.groupdocs.comparison.options.enums/passwordsaveoption/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PasswordSaveOption extends Enum<PasswordSaveOption>
```

枚举在比较过程中在文档中保存密码信息的选项。


示例用法：

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setPasswordSaveOption(PasswordSaveOption.SOURCE);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## 字段

| 字段 | 描述 |
| --- | --- |
|  | [NONE](#NONE) | 不要保存密码。 |
|
|  | [SOURCE](#SOURCE) | 使用来源文档中的密码。 |
|
|  | [TARGET](#TARGET) | 使用目标文档中的密码。 |
|
|  | [USER](#USER) | \* 使用用户提供的密码。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | 解析 PasswordSaveOption 的字符串表示以获取枚举常量。 |
|
|  | [toString()](#toString--) | PasswordSaveOption 的字符串表示。 |
|
### NONE {#NONE}
```
public static final PasswordSaveOption NONE
```


不要保存密码。


### SOURCE {#SOURCE}
```
public static final PasswordSaveOption SOURCE
```


使用来源文档中的密码。


### TARGET {#TARGET}
```
public static final PasswordSaveOption TARGET
```


使用目标文档中的密码。


### USER {#USER}
```
public static final PasswordSaveOption USER
```


\* 使用用户提供的密码。


### values() {#values--}
```
public static PasswordSaveOption[] values()
```




**Returns:**
com.groupdocs.comparison.options.enums.PasswordSaveOption[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PasswordSaveOption valueOf(String name)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String |  |

**Returns:**
[PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static PasswordSaveOption fromString(String toStringValue)
```


解析 PasswordSaveOption 的字符串表示以获取枚举常量。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | toStringValue | java.lang.String | PasswordSaveOption 的字符串表示 |
|

**Returns:**
[PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) - PasswordSaveOption enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


PasswordSaveOption 的字符串表示。


**Returns:**
java.lang.String - 枚举常量的字符串值

