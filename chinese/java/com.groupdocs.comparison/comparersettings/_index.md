---
title: "ComparerSettings"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "定义用于自定义该类行为的设置。"
type: docs
weight: 11
url: /zh/java/com.groupdocs.comparison/comparersettings/
---
**Inheritance:**
java.lang.Object
```
public class ComparerSettings
```

定义用于自定义 [Comparer](../../com.groupdocs.comparison/comparer) 类行为的设置。


示例用法：

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     final ComparerSettings comparerSettings = new ComparerSettings();
     comparerSettings.setLogger(new ConsoleLogger(false, false, true, true));

     comparer.compare(resultFile, comparerSettings);
 }
 
````


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [ComparerSettings()](#ComparerSettings--) | 实例化 ComparerSettings 类的新实例。 |
|
|  | [ComparerSettings(ILogger logger)](#ComparerSettings-com.groupdocs.foundation.logging.ILogger-) | 实例化 ComparerSettings 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getLogger()](#getLogger--) | 获取用于日志记录的 logger 实现。 |
|
|  | [setLogger(ILogger value)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | 设置用于日志记录的 logger 实现。 |
|
### ComparerSettings() {#ComparerSettings--}
```
public ComparerSettings()
```


实例化 ComparerSettings 类的新实例。


### ComparerSettings(ILogger logger) {#ComparerSettings-com.groupdocs.foundation.logging.ILogger-}
```
public ComparerSettings(ILogger logger)
```


实例化 ComparerSettings 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 日志记录器 | com.groupdocs.foundation.logging.ILogger | 要使用的 logger |
|

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


获取用于日志记录的 logger 实现。


**Returns:**
com.groupdocs.foundation.logging.ILogger - 日志记录器

### setLogger(ILogger value) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public final void setLogger(ILogger value)
```


设置用于日志记录的 logger 实现。


使用 com.groupdocs.foundation.logging.NullLogger#NULL_LOGGER.NULL_LOGGER 来禁用日志记录。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | com.groupdocs.foundation.logging.ILogger | 要设置的 logger 实现 |
|

