---
title: "ComparisonLogger"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "实现日志方法并提供配置集成日志或设置用户自定义日志记录器的方式。"
type: docs
weight: 10
url: /zh/java/com.groupdocs.comparison.logging/comparisonlogger/
---
**Inheritance:**
java.lang.Object
```
public class ComparisonLogger
```

实现日志方法并提供配置集成日志或设置用户自定义日志记录器的方式。


该类允许设置集成或自定义日志记录器并写入日志消息。


示例用法：

````

 ComparisonLogger.setLogger(new com.groupdocs.comparison.logging.ConsoleLogger(false, true, true, true));
 ComparisonLogger.warning(exceptionObject, "Warning message with parameters: {}, {}", "parameter1", 2);
 
````


## 方法

| 方法 | 描述 |
| --- | --- |
|  | [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | 将跟踪消息写入预配置的日志记录器。 |
|
|  | [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | 将跟踪消息、堆栈跟踪和异常信息写入预配置的日志记录器。 |
|
|  | [isTraceEnabled()](#isTraceEnabled--) | 检查预配置的日志记录器中是否启用了跟踪日志记录。 |
|
|  | [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | 将调试消息写入预配置的日志记录器。 |
|
|  | [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | 将调试消息、堆栈跟踪和异常信息写入预配置的日志记录器。 |
|
|  | [isDebugEnabled()](#isDebugEnabled--) | 检查预配置的日志记录器中是否启用了调试日志记录。 |
|
|  | [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | 将警告消息写入预配置的日志记录器。 |
|
|  | [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | 将警告消息、堆栈跟踪和异常信息写入预配置的日志记录器。 |
|
|  | [isWarningEnabled()](#isWarningEnabled--) | 检查预配置的日志记录器中是否启用了警告日志记录。 |
|
|  | [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | 将错误消息写入预配置的日志记录器。 |
|
|  | [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | 将错误消息、堆栈跟踪和异常信息写入预配置的日志记录器。 |
|
|  | [isErrorEnabled()](#isErrorEnabled--) | 检查预配置的日志记录器中是否启用了错误日志记录。 |
|
|  | [getLogger()](#getLogger--) | 获取将用于写入所有类型日志的预配置日志记录器。 |
|
|  | [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | 设置将用于写入所有类型日志的日志记录器。 |
|
### trace(String message, Object[] arguments) {#trace-java.lang.String-java.lang.Object...-}
```
public static void trace(String message, Object[] arguments)
```


将跟踪消息写入预配置的日志记录器。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | message | java.lang.String | 该消息，如果为 null，则行为取决于日志记录器 |
|
|  | arguments | java.lang.Object[] | 要嵌入到消息中的参数，如果为 null，则行为取决于日志记录器 |
|

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void trace(Throwable throwable, String message, Object[] arguments)
```


将跟踪消息、堆栈跟踪和异常信息写入预配置的日志记录器。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | 将用于获取堆栈跟踪的 throwable 对象，如果为 null，则行为取决于日志记录器 |
|
|  | message | java.lang.String | 该消息，如果为 null，则行为取决于日志记录器 |
|
|  | arguments | java.lang.Object[] | 要嵌入到消息中的参数，如果为 null，则行为取决于日志记录器 |
|

### isTraceEnabled() {#isTraceEnabled--}
```
public static boolean isTraceEnabled()
```


检查预配置的日志记录器中是否启用了跟踪日志记录。


**Returns:**
boolean - 如果在预配置的日志记录器中启用则为 true，否则为 false

### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public static void debug(String message, Object[] arguments)
```


将调试消息写入预配置的日志记录器。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | message | java.lang.String | 该消息，如果为 null，则行为取决于日志记录器 |
|
|  | arguments | java.lang.Object[] | 要嵌入到消息中的参数，如果为 null，则行为取决于日志记录器 |
|

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void debug(Throwable throwable, String message, Object[] arguments)
```


将调试消息、堆栈跟踪和异常信息写入预配置的日志记录器。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | 将用于获取堆栈跟踪的 throwable 对象，如果为 null，则行为取决于日志记录器 |
|
|  | message | java.lang.String | 该消息，如果为 null，则行为取决于日志记录器 |
|
|  | arguments | java.lang.Object[] | 要嵌入到消息中的参数，如果为 null，则行为取决于日志记录器 |
|

### isDebugEnabled() {#isDebugEnabled--}
```
public static boolean isDebugEnabled()
```


检查预配置的日志记录器中是否启用了调试日志记录。


**Returns:**
boolean - 如果在预配置的日志记录器中启用则为 true，否则为 false

### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public static void warning(String message, Object[] arguments)
```


将警告消息写入预配置的日志记录器。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | message | java.lang.String | 该消息，如果为 null，则行为取决于日志记录器 |
|
|  | arguments | java.lang.Object[] | 要嵌入到消息中的参数，如果为 null，则行为取决于日志记录器 |
|

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void warning(Throwable throwable, String message, Object[] arguments)
```


将警告消息、堆栈跟踪和异常信息写入预配置的日志记录器。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | 将用于获取堆栈跟踪的 throwable 对象，如果为 null，则行为取决于日志记录器 |
|
|  | message | java.lang.String | 该消息，如果为 null，则行为取决于日志记录器 |
|
|  | arguments | java.lang.Object[] | 要嵌入到消息中的参数，如果为 null，则行为取决于日志记录器 |
|

### isWarningEnabled() {#isWarningEnabled--}
```
public static boolean isWarningEnabled()
```


检查预配置的日志记录器中是否启用了警告日志记录。


**Returns:**
boolean - 如果在预配置的日志记录器中启用则为 true，否则为 false

### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public static void error(String message, Object[] arguments)
```


将错误消息写入预配置的日志记录器。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | message | java.lang.String | 该消息，如果为 null，则行为取决于日志记录器 |
|
|  | arguments | java.lang.Object[] | 要嵌入到消息中的参数，如果为 null，则行为取决于日志记录器 |
|

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void error(Throwable throwable, String message, Object[] arguments)
```


将错误消息、堆栈跟踪和异常信息写入预配置的日志记录器。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | 将用于获取堆栈跟踪的 throwable 对象，如果为 null，则行为取决于日志记录器 |
|
|  | message | java.lang.String | 该消息，如果为 null，则行为取决于日志记录器 |
|
|  | arguments | java.lang.Object[] | 要嵌入到消息中的参数，如果为 null，则行为取决于日志记录器 |
|

### isErrorEnabled() {#isErrorEnabled--}
```
public static boolean isErrorEnabled()
```


检查预配置的日志记录器中是否启用了错误日志记录。


**Returns:**
boolean - 如果在预配置的日志记录器中启用则为 true，否则为 false

### getLogger() {#getLogger--}
```
public static synchronized ILogger getLogger()
```


获取将用于写入所有类型日志的预配置日志记录器。


**Returns:**
com.groupdocs.foundation.logging.ILogger - 日志记录器

### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public static synchronized void setLogger(ILogger logger)
```


设置将用于写入所有类型日志的日志记录器。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 日志记录器 | com.groupdocs.foundation.logging.ILogger | 日志记录器 |
|

