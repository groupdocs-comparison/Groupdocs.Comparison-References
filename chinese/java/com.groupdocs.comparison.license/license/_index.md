---
title: "许可证"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "License 类提供用于设置和应用 GroupDocs.Comparison 许可证的方法。"
type: docs
weight: 10
url: /zh/java/com.groupdocs.comparison.license/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

License 类提供用于设置和应用 GroupDocs.Comparison 许可证的方法。


它允许您根据所应用的许可证启用或禁用库的特定功能。

* More about GroupDocs.Comparison licensing: [Evaluation Limitations and Licensing](../https://docs.groupdocs.com/display/comparisonjava/Evaluation+Limitations+and+Licensing+of+GroupDocs.Comparison)


示例用法：

````

 final License license = new License();
 license.setLicense("GroupDocs.License.lic");
 
````


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [License()](#License--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [isValidLicense()](#isValidLicense--) | 获取一个值，指示许可证是否已设置。 |
|
|  | [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | 使用输入流为 Comparison 设置许可证。 |
|
|  | [setLicense(Path licensePath)](#setLicense-java.nio.file.Path-) | 使用许可证文件路径为 Comparison 设置许可证。 |
|
|  | [setLicense(String licensePath)](#setLicense-java.lang.String-) | 使用许可证文件路径为 Comparison 设置许可证。 |
|
### License() {#License--}
```
public License()
```


### isValidLicense() {#isValidLicense--}
```
public static boolean isValidLicense()
```


获取一个值，指示许可证是否已设置。


**Returns:**
布尔值 - 如果许可证设置成功则为 true，否则为 false

### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


使用输入流为 Comparison 设置许可证。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | licenseStream | java.io.InputStream | 许可证流，null 将取消许可证设置 |
|

### setLicense(Path licensePath) {#setLicense-java.nio.file.Path-}
```
public final void setLicense(Path licensePath)
```


使用许可证文件路径为 Comparison 设置许可证。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | licensePath | java.nio.file.Path | 许可证文件路径 |
|

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


使用许可证文件路径为 Comparison 设置许可证。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | licensePath | java.lang.String | 许可证文件路径 |
|

