---
title: "ComparisonLogger"
second_title: "GroupDocs.Comparison لـ Java API Reference"
description: "تنفذ طرق التسجيل وطريقة لتكوين مسجل مدمج أو تعيين مسجل معرف من قبل المستخدم."
type: docs
weight: 10
url: /ar/java/com.groupdocs.comparison.logging/comparisonlogger/
---
**Inheritance:**
java.lang.Object
```
public class ComparisonLogger
```

تنفذ طرق التسجيل وطريقة لتكوين مسجل مدمج أو تعيين مسجل معرف من قبل المستخدم.


تسمح الفئة بإعداد مسجل مدمج أو مخصص وكتابة رسائل السجل.


مثال على الاستخدام:

````

 ComparisonLogger.setLogger(new com.groupdocs.comparison.logging.ConsoleLogger(false, true, true, true));
 ComparisonLogger.warning(exceptionObject, "Warning message with parameters: {}, {}", "parameter1", 2);
 
````


## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | يكتب رسالة تتبع إلى المسجل المُعد مسبقًا. |
|
|  | [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | يكتب رسالة تتبع، وتتبع المكدس، ورسالة من استثناء إلى المسجل المُعد مسبقًا. |
|
|  | [isTraceEnabled()](#isTraceEnabled--) | يتحقق مما إذا كان تسجيل التتبع مفعلاً في المسجل المُعد مسبقًا. |
|
|  | [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | يكتب رسالة تصحيح إلى المسجل المُعد مسبقًا. |
|
|  | [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | يكتب رسالة تصحيح، وتتبع المكدس، ورسالة من استثناء إلى المسجل المُعد مسبقًا. |
|
|  | [isDebugEnabled()](#isDebugEnabled--) | يتحقق مما إذا كان تسجيل التصحيح مفعلاً في المسجل المُعد مسبقًا. |
|
|  | [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | يكتب رسالة تحذير إلى المسجل المُعد مسبقًا. |
|
|  | [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | يكتب رسالة تحذير، وتتبع المكدس، ورسالة من استثناء إلى المسجل المُعد مسبقًا. |
|
|  | [isWarningEnabled()](#isWarningEnabled--) | يتحقق مما إذا كان تسجيل التحذير مفعلاً في المسجل المُعد مسبقًا. |
|
|  | [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | يكتب رسالة خطأ إلى المسجل المُعد مسبقًا. |
|
|  | [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | يكتب رسالة خطأ، وتتبع المكدس، ورسالة من استثناء إلى المسجل المُعد مسبقًا. |
|
|  | [isErrorEnabled()](#isErrorEnabled--) | يتحقق مما إذا كان تسجيل الخطأ مفعلاً في المسجل المُعد مسبقًا. |
|
|  | [getLogger()](#getLogger--) | يحصل على المسجل المُعد مسبقًا الذي سيُستخدم لكتابة جميع أنواع السجلات. |
|
|  | [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | يضبط المسجل الذي سيُستخدم لكتابة جميع أنواع السجلات. |
|
### trace(String message, Object[] arguments) {#trace-java.lang.String-java.lang.Object...-}
```
public static void trace(String message, Object[] arguments)
```


يكتب رسالة تتبع إلى المسجل المُعد مسبقًا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | message | java.lang.String | الرسالة، إذا كانت فارغة يعتمد السلوك على المسجل |
|
|  | arguments | java.lang.Object[] | المعاملات التي سيتم تضمينها في الرسالة، إذا كانت فارغة يعتمد السلوك على المسجل |
|

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void trace(Throwable throwable, String message, Object[] arguments)
```


يكتب رسالة تتبع، وتتبع المكدس، ورسالة من استثناء إلى المسجل المُعد مسبقًا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | الكائن القابل للرمي الذي سيُستخدم للحصول على تتبع المكدس، إذا كان فارغًا يعتمد السلوك على المسجل |
|
|  | message | java.lang.String | الرسالة، إذا كانت فارغة يعتمد السلوك على المسجل |
|
|  | arguments | java.lang.Object[] | المعاملات التي سيتم تضمينها في الرسالة، إذا كانت فارغة يعتمد السلوك على المسجل |
|

### isTraceEnabled() {#isTraceEnabled--}
```
public static boolean isTraceEnabled()
```


يتحقق مما إذا كان تسجيل التتبع مفعلاً في المسجل المُعد مسبقًا.


**Returns:**
منطقي - صحيح إذا كان مفعلاً في المسجل المُعد مسبقًا، وإلا خاطئ

### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public static void debug(String message, Object[] arguments)
```


يكتب رسالة تصحيح إلى المسجل المُعد مسبقًا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | message | java.lang.String | الرسالة، إذا كانت فارغة يعتمد السلوك على المسجل |
|
|  | arguments | java.lang.Object[] | المعاملات التي سيتم تضمينها في الرسالة، إذا كانت فارغة يعتمد السلوك على المسجل |
|

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void debug(Throwable throwable, String message, Object[] arguments)
```


يكتب رسالة تصحيح، وتتبع المكدس، ورسالة من استثناء إلى المسجل المُعد مسبقًا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | الكائن القابل للرمي الذي سيُستخدم للحصول على تتبع المكدس، إذا كان فارغًا يعتمد السلوك على المسجل |
|
|  | message | java.lang.String | الرسالة، إذا كانت فارغة يعتمد السلوك على المسجل |
|
|  | arguments | java.lang.Object[] | المعاملات التي سيتم تضمينها في الرسالة، إذا كانت فارغة يعتمد السلوك على المسجل |
|

### isDebugEnabled() {#isDebugEnabled--}
```
public static boolean isDebugEnabled()
```


يتحقق مما إذا كان تسجيل التصحيح مفعلاً في المسجل المُعد مسبقًا.


**Returns:**
منطقي - صحيح إذا كان مفعلاً في المسجل المُعد مسبقًا، وإلا خاطئ

### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public static void warning(String message, Object[] arguments)
```


يكتب رسالة تحذير إلى المسجل المُعد مسبقًا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | message | java.lang.String | الرسالة، إذا كانت فارغة يعتمد السلوك على المسجل |
|
|  | arguments | java.lang.Object[] | المعاملات التي سيتم تضمينها في الرسالة، إذا كانت فارغة يعتمد السلوك على المسجل |
|

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void warning(Throwable throwable, String message, Object[] arguments)
```


يكتب رسالة تحذير، وتتبع المكدس، ورسالة من استثناء إلى المسجل المُعد مسبقًا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | الكائن القابل للرمي الذي سيُستخدم للحصول على تتبع المكدس، إذا كان فارغًا يعتمد السلوك على المسجل |
|
|  | message | java.lang.String | الرسالة، إذا كانت فارغة يعتمد السلوك على المسجل |
|
|  | arguments | java.lang.Object[] | المعاملات التي سيتم تضمينها في الرسالة، إذا كانت فارغة يعتمد السلوك على المسجل |
|

### isWarningEnabled() {#isWarningEnabled--}
```
public static boolean isWarningEnabled()
```


يتحقق مما إذا كان تسجيل التحذير مفعلاً في المسجل المُعد مسبقًا.


**Returns:**
منطقي - صحيح إذا كان مفعلاً في المسجل المُعد مسبقًا، وإلا خاطئ

### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public static void error(String message, Object[] arguments)
```


يكتب رسالة خطأ إلى المسجل المُعد مسبقًا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | message | java.lang.String | الرسالة، إذا كانت فارغة يعتمد السلوك على المسجل |
|
|  | arguments | java.lang.Object[] | المعاملات التي سيتم تضمينها في الرسالة، إذا كانت فارغة يعتمد السلوك على المسجل |
|

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void error(Throwable throwable, String message, Object[] arguments)
```


يكتب رسالة خطأ، وتتبع المكدس، ورسالة من استثناء إلى المسجل المُعد مسبقًا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | الكائن القابل للرمي الذي سيُستخدم للحصول على تتبع المكدس، إذا كان فارغًا يعتمد السلوك على المسجل |
|
|  | message | java.lang.String | الرسالة، إذا كانت فارغة يعتمد السلوك على المسجل |
|
|  | arguments | java.lang.Object[] | المعاملات التي سيتم تضمينها في الرسالة، إذا كانت فارغة يعتمد السلوك على المسجل |
|

### isErrorEnabled() {#isErrorEnabled--}
```
public static boolean isErrorEnabled()
```


يتحقق مما إذا كان تسجيل الخطأ مفعلاً في المسجل المُعد مسبقًا.


**Returns:**
منطقي - صحيح إذا كان مفعلاً في المسجل المُعد مسبقًا، وإلا خاطئ

### getLogger() {#getLogger--}
```
public static synchronized ILogger getLogger()
```


يحصل على المسجل المُعد مسبقًا الذي سيُستخدم لكتابة جميع أنواع السجلات.


**Returns:**
com.groupdocs.foundation.logging.ILogger - المسجل

### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public static synchronized void setLogger(ILogger logger)
```


يضبط المسجل الذي سيُستخدم لكتابة جميع أنواع السجلات.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | مسجل | com.groupdocs.foundation.logging.ILogger | المسجل |
|

