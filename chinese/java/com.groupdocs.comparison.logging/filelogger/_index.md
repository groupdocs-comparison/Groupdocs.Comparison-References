---
title: "FileLogger"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "将日志写入文件的日志记录器。"
type: docs
weight: 11
url: /zh/java/com.groupdocs.comparison.logging/filelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.foundation.logging.ILogger
```
public class FileLogger implements ILogger
```

将日志写入文件的日志记录器。


应与 [ComparisonLogger](../../com.groupdocs.comparison.logging/comparisonlogger) 一起使用。


示例用法：

````

 ComparisonLogger.setLogger(new FileLogger("/path/to/file.log.txt", false, true, true, true));
 
````


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [FileLogger(String filePath)](#FileLogger-java.lang.String-) | 使用文件路径初始化 FileLogger 类的新实例。 |
|
|  | [FileLogger(String filePath, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)](#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-) | 使用文件路径和日志级别配置初始化 FileLogger 类的新实例。 |
|
## 字段

| 字段 | 描述 |
| --- | --- |
| [MESSAGE](#MESSAGE) |  |
| [EXCEPTION](#EXCEPTION) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | 将跟踪消息写入文件。 |
|
|  | [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | 将跟踪消息写入文件。 |
|
|  | [isTraceEnabled()](#isTraceEnabled--) | 检查是否已启用跟踪日志记录。 |
|
|  | [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | 将调试消息写入文件。 |
|
|  | [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | 将调试消息写入文件。 |
|
|  | [isDebugEnabled()](#isDebugEnabled--) | 检查是否已启用调试日志记录。 |
|
|  | [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | 将警告消息写入文件。 |
|
|  | [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | 将警告消息写入文件。 |
|
|  | [isWarningEnabled()](#isWarningEnabled--) | 检查是否已启用警告日志记录。 |
|
|  | [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | 将错误消息写入文件。 |
|
|  | [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | 将错误消息写入文件。 |
|
|  | [isErrorEnabled()](#isErrorEnabled--) | 检查是否已启用错误日志记录。 |
|
### FileLogger(String filePath) {#FileLogger-java.lang.String-}
```
public FileLogger(String filePath)
```


使用文件路径初始化 FileLogger 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.lang.String | 用于写入日志的文件路径 |
|

### FileLogger(String filePath, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled) {#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-}
```
public FileLogger(String filePath, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)
```


使用文件路径和日志级别配置初始化 FileLogger 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.lang.String | 用于写入日志的文件路径 |
|
|  | isTraceEnabled | boolean | True 用于启用跟踪日志，false 否则 |
|
|  | isDebugEnabled | boolean | True 用于启用调试日志，false 否则 |
|
|  | isWarningEnabled | boolean | True 用于启用警告日志，false 否则 |
|
|  | isErrorEnabled | boolean | True 用于启用错误日志，false 否则 |
|

### MESSAGE {#MESSAGE}
```
public static final String MESSAGE
```


### EXCEPTION {#EXCEPTION}
```
public static final String EXCEPTION
```


### trace(String message, Object[] arguments) {#trace-java.lang.String-java.lang.Object...-}
```
public void trace(String message, Object[] arguments)
```


将跟踪消息写入文件。


跟踪日志消息提供关于应用程序流程的最大详细信息。
消息可以包含一个或少量 {}，这些将被相应的参数替换。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | message | java.lang.String | 该消息。 |
|
|  | arguments | java.lang.Object[] | 参数会按传入顺序替换消息中的 {}，null 将写为 'null' |
|

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void trace(Throwable throwable, String message, Object[] arguments)
```


将跟踪消息写入文件。


跟踪日志消息提供关于应用程序流程的最大详细信息。
消息可以包含一个或少量 {}，这些将被相应的参数替换。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | 将用于获取堆栈跟踪的 throwable 对象 |
|
|  | message | java.lang.String | 该消息。 |
|
|  | arguments | java.lang.Object[] | 参数会按传入顺序替换消息中的 {}，null 将写为 'null' |
|

### isTraceEnabled() {#isTraceEnabled--}
```
public boolean isTraceEnabled()
```


检查是否已启用跟踪日志记录。


**Returns:**
boolean - true 如果已启用，否则 false

### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public void debug(String message, Object[] arguments)
```


将调试消息写入文件。


调试日志消息提供关于应用程序流程中不同过程的信息。
消息可以包含一个或少量 {}，这些将被相应的参数替换。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | message | java.lang.String | 该消息。 |
|
|  | arguments | java.lang.Object[] | 参数会按传入顺序替换消息中的 {}，null 将写为 'null' |
|

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void debug(Throwable throwable, String message, Object[] arguments)
```


将调试消息写入文件。


调试日志消息提供关于应用程序流程中不同过程的信息。
消息可以包含一个或少量 {}，这些将被相应的参数替换。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | 将用于获取堆栈跟踪的 throwable 对象 |
|
|  | message | java.lang.String | 该消息。 |
|
|  | arguments | java.lang.Object[] | 参数会按传入顺序替换消息中的 {}，null 将写为 'null' |
|

### isDebugEnabled() {#isDebugEnabled--}
```
public boolean isDebugEnabled()
```


检查是否已启用调试日志记录。


**Returns:**
boolean - true 如果已启用，否则 false

### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public void warning(String message, Object[] arguments)
```


将警告消息写入文件。


警告日志消息提供关于应用程序流程中意外且可恢复事件的信息。
消息可以包含一个或少量 {}，这些将被相应的参数替换。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | message | java.lang.String | 该消息。 |
|
|  | arguments | java.lang.Object[] | 参数会按传入顺序替换消息中的 {}，null 将写为 'null' |
|

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void warning(Throwable throwable, String message, Object[] arguments)
```


将警告消息写入文件。


警告日志消息提供关于应用程序流程中意外且可恢复事件的信息。
消息可以包含一个或少量 {}，这些将被相应的参数替换。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | 将用于获取堆栈跟踪的 throwable 对象 |
|
|  | message | java.lang.String | 该消息。 |
|
|  | arguments | java.lang.Object[] | 参数会按传入顺序替换消息中的 {}，null 将写为 'null' |
|

### isWarningEnabled() {#isWarningEnabled--}
```
public boolean isWarningEnabled()
```


检查是否已启用警告日志记录。


**Returns:**
boolean - true 如果已启用，否则 false

### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public void error(String message, Object[] arguments)
```


将错误消息写入文件。


错误日志消息提供关于应用程序流程中不可恢复事件的信息。
消息可以包含一个或少量 {}，这些将被相应的参数替换。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | message | java.lang.String | 该消息。 |
|
|  | arguments | java.lang.Object[] | 参数会按传入顺序替换消息中的 {}，null 将写为 'null' |
|

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void error(Throwable throwable, String message, Object[] arguments)
```


将错误消息写入文件。


错误日志消息提供关于应用程序流程中不可恢复事件的信息。
消息可以包含一个或少量 {}，这些将被相应的参数替换。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | 将用于获取堆栈跟踪的 throwable 对象 |
|
|  | message | java.lang.String | 该消息。 |
|
|  | arguments | java.lang.Object[] | 参数会按传入顺序替换消息中的 {}，null 将写为 'null' |
|

### isErrorEnabled() {#isErrorEnabled--}
```
public boolean isErrorEnabled()
```


检查是否已启用错误日志记录。


**Returns:**
boolean - true 如果已启用，否则 false

