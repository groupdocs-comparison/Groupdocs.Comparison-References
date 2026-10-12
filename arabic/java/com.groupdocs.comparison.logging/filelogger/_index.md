---
title: "FileLogger"
second_title: "GroupDocs.Comparison لـ Java API Reference"
description: "مسجل يكتب السجلات إلى ملف."
type: docs
weight: 11
url: /ar/java/com.groupdocs.comparison.logging/filelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.foundation.logging.ILogger
```
public class FileLogger implements ILogger
```

مسجل يكتب السجلات إلى ملف.


يجب استخدامه مع [ComparisonLogger](../../com.groupdocs.comparison.logging/comparisonlogger).


مثال على الاستخدام:

````

 ComparisonLogger.setLogger(new FileLogger("/path/to/file.log.txt", false, true, true, true));
 
````


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [FileLogger(String filePath)](#FileLogger-java.lang.String-) | يقوم بتهيئة نسخة جديدة من الفئة FileLogger مع مسار الملف. |
|
|  | [FileLogger(String filePath, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)](#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-) | يقوم بتهيئة نسخة جديدة من الفئة FileLogger مع مسار الملف وتكوين مستويات السجلات. |
|
## الحقول

| حقل | الوصف |
| --- | --- |
| [MESSAGE](#MESSAGE) |  |
| [EXCEPTION](#EXCEPTION) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | يكتب رسالة تتبع إلى الملف. |
|
|  | [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | يكتب رسالة تتبع إلى الملف. |
|
|  | [isTraceEnabled()](#isTraceEnabled--) | يتحقق مما إذا كان تسجيل التتبع مفعلاً. |
|
|  | [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | يكتب رسالة تصحيح إلى الملف. |
|
|  | [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | يكتب رسالة تصحيح إلى الملف. |
|
|  | [isDebugEnabled()](#isDebugEnabled--) | يتحقق مما إذا كان تسجيل التصحيح مفعلاً. |
|
|  | [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | يكتب رسالة تحذير إلى الملف. |
|
|  | [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | يكتب رسالة تحذير إلى الملف. |
|
|  | [isWarningEnabled()](#isWarningEnabled--) | يتحقق مما إذا كان تسجيل التحذير مفعلاً. |
|
|  | [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | يكتب رسالة خطأ إلى الملف. |
|
|  | [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | يكتب رسالة خطأ إلى الملف. |
|
|  | [isErrorEnabled()](#isErrorEnabled--) | يتحقق مما إذا كان تسجيل الخطأ مفعلاً. |
|
### FileLogger(String filePath) {#FileLogger-java.lang.String-}
```
public FileLogger(String filePath)
```


يقوم بتهيئة نسخة جديدة من الفئة FileLogger مع مسار الملف.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | المسار إلى الملف الذي سيُستخدم لكتابة السجلات |
|

### FileLogger(String filePath, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled) {#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-}
```
public FileLogger(String filePath, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)
```


يقوم بتهيئة نسخة جديدة من الفئة FileLogger مع مسار الملف وتكوين مستويات السجلات.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | المسار إلى الملف الذي سيُستخدم لكتابة السجلات |
|
|  | isTraceEnabled | boolean | True لتمكين تسجيل التتبع، false خلاف ذلك |
|
|  | isDebugEnabled | boolean | True لتمكين تسجيل التصحيح، false خلاف ذلك |
|
|  | isWarningEnabled | boolean | True لتمكين تسجيل التحذير، false خلاف ذلك |
|
|  | isErrorEnabled | boolean | True لتمكين تسجيل الخطأ، false خلاف ذلك |
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


يكتب رسالة تتبع إلى الملف.


توفر رسائل سجل التتبع أقصى قدر من المعلومات التفصيلية حول تدفق التطبيق.
يمكن للرسالة أن تحتوي على واحدة أو عدة {} سيتم استبدالها بالوسائط المقابلة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | message | java.lang.String | الرسالة. |
|
|  | arguments | java.lang.Object[] | الوسائط، تستبدل {} في الرسالة بترتيب الإرسال، سيتم كتابة null كـ 'null' |
|

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void trace(Throwable throwable, String message, Object[] arguments)
```


يكتب رسالة تتبع إلى الملف.


توفر رسائل سجل التتبع أقصى قدر من المعلومات التفصيلية حول تدفق التطبيق.
يمكن للرسالة أن تحتوي على واحدة أو عدة {} سيتم استبدالها بالوسائط المقابلة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | كائن java.lang.Throwable الذي سيُستخدم للحصول على تتبع المكدس |
|
|  | message | java.lang.String | الرسالة. |
|
|  | arguments | java.lang.Object[] | الوسائط، تستبدل {} في الرسالة بترتيب الإرسال، سيتم كتابة null كـ 'null' |
|

### isTraceEnabled() {#isTraceEnabled--}
```
public boolean isTraceEnabled()
```


يتحقق مما إذا كان تسجيل التتبع مفعلاً.


**Returns:**
boolean - true إذا كان مفعلاً، وإلا false

### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public void debug(String message, Object[] arguments)
```


يكتب رسالة تصحيح إلى الملف.


توفر رسائل سجل التصحيح معلومات حول العمليات المختلفة في تدفق التطبيق.
يمكن للرسالة أن تحتوي على واحدة أو عدة {} سيتم استبدالها بالوسائط المقابلة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | message | java.lang.String | الرسالة. |
|
|  | arguments | java.lang.Object[] | الوسائط، تستبدل {} في الرسالة بترتيب الإرسال، سيتم كتابة null كـ 'null' |
|

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void debug(Throwable throwable, String message, Object[] arguments)
```


يكتب رسالة تصحيح إلى الملف.


توفر رسائل سجل التصحيح معلومات حول العمليات المختلفة في تدفق التطبيق.
يمكن للرسالة أن تحتوي على واحدة أو عدة {} سيتم استبدالها بالوسائط المقابلة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | كائن java.lang.Throwable الذي سيُستخدم للحصول على تتبع المكدس |
|
|  | message | java.lang.String | الرسالة. |
|
|  | arguments | java.lang.Object[] | الوسائط، تستبدل {} في الرسالة بترتيب الإرسال، سيتم كتابة null كـ 'null' |
|

### isDebugEnabled() {#isDebugEnabled--}
```
public boolean isDebugEnabled()
```


يتحقق مما إذا كان تسجيل التصحيح مفعلاً.


**Returns:**
boolean - true إذا كان مفعلاً، وإلا false

### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public void warning(String message, Object[] arguments)
```


يكتب رسالة تحذير إلى الملف.


توفر رسائل سجل التحذير معلومات حول الأحداث غير المتوقعة والقابلة للاسترداد في تدفق التطبيق.
يمكن للرسالة أن تحتوي على واحدة أو عدة {} سيتم استبدالها بالوسائط المقابلة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | message | java.lang.String | الرسالة. |
|
|  | arguments | java.lang.Object[] | الوسائط، تستبدل {} في الرسالة بترتيب الإرسال، سيتم كتابة null كـ 'null' |
|

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void warning(Throwable throwable, String message, Object[] arguments)
```


يكتب رسالة تحذير إلى الملف.


توفر رسائل سجل التحذير معلومات حول الأحداث غير المتوقعة والقابلة للاسترداد في تدفق التطبيق.
يمكن للرسالة أن تحتوي على واحدة أو عدة {} سيتم استبدالها بالوسائط المقابلة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | كائن java.lang.Throwable الذي سيُستخدم للحصول على تتبع المكدس |
|
|  | message | java.lang.String | الرسالة. |
|
|  | arguments | java.lang.Object[] | الوسائط، تستبدل {} في الرسالة بترتيب الإرسال، سيتم كتابة null كـ 'null' |
|

### isWarningEnabled() {#isWarningEnabled--}
```
public boolean isWarningEnabled()
```


يتحقق مما إذا كان تسجيل التحذير مفعلاً.


**Returns:**
boolean - true إذا كان مفعلاً، وإلا false

### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public void error(String message, Object[] arguments)
```


يكتب رسالة خطأ إلى الملف.


توفر رسائل سجل الخطأ معلومات حول الأحداث غير القابلة للاسترداد في تدفق التطبيق.
يمكن للرسالة أن تحتوي على واحدة أو عدة {} سيتم استبدالها بالوسائط المقابلة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | message | java.lang.String | الرسالة. |
|
|  | arguments | java.lang.Object[] | الوسائط، تستبدل {} في الرسالة بترتيب الإرسال، سيتم كتابة null كـ 'null' |
|

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void error(Throwable throwable, String message, Object[] arguments)
```


يكتب رسالة خطأ إلى الملف.


توفر رسائل سجل الخطأ معلومات حول الأحداث غير القابلة للاسترداد في تدفق التطبيق.
يمكن للرسالة أن تحتوي على واحدة أو عدة {} سيتم استبدالها بالوسائط المقابلة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | كائن java.lang.Throwable الذي سيُستخدم للحصول على تتبع المكدس |
|
|  | message | java.lang.String | الرسالة. |
|
|  | arguments | java.lang.Object[] | الوسائط، تستبدل {} في الرسالة بترتيب الإرسال، سيتم كتابة null كـ 'null' |
|

### isErrorEnabled() {#isErrorEnabled--}
```
public boolean isErrorEnabled()
```


يتحقق مما إذا كان تسجيل الخطأ مفعلاً.


**Returns:**
boolean - true إذا كان مفعلاً، وإلا false

