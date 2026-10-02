---
title: "LoadOptions"
second_title: "GroupDocs.Comparison لـ Java API Reference"
description: "يسمح بتحديد خيارات إضافية عند تحميل مستند."
type: docs
weight: 10
url: /ar/java/com.groupdocs.comparison.options.load/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

يسمح بتحديد خيارات إضافية عند تحميل مستند.


مثال على الاستخدام:

````

 final LoadOptions loadOptions = new LoadOptions();
 loadOptions.setPassword("passw");
 loadOptions.setFileType(FileType.PDF);

 try (Comparer comparer = new Comparer(sourceFile, loadOptions)) {
    comparer.add(targetFile);

    comparer.compare(resultFile);
 }
 
````


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [LoadOptions()](#LoadOptions--) | ينشئ مثيلاً جديداً لفئة LoadOptions. |
|
|  | [LoadOptions(boolean isLoadText)](#LoadOptions-boolean-) | ينشئ مثيلاً جديداً لفئة LoadOptions مع علم يعني أن سلسلة الإدخال هي نص للمقارنة، وليس مسارًا. |
|
|  | [LoadOptions(String password)](#LoadOptions-java.lang.String-) | ينشئ مثيلاً جديداً لفئة LoadOptions مع كلمة مرور لتحميل المستند. |
|
|  | [LoadOptions(boolean isLoadText, String password)](#LoadOptions-boolean-java.lang.String-) | ينشئ مثيلاً جديداً لفئة LoadOptions مع علم يعني أن سلسلة الإدخال هي نص للمقارنة وكلمة مرور لتحميل المستند. |
|
|  | [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.comparison.result.FileType-) | ينشئ مثيلاً جديداً لفئة LoadOptions مع نوع الملف. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [isLoadText()](#isLoadText--) | يحصل على علم يشير إلى أن السلسلة التي تم تمريرها إلى مُنشئ [Comparer](../../com.groupdocs.comparison/comparer) أو إلى طريقة [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) هي نص للمقارنة، وليس مسارات ملفات (للمقارنة النصية فقط). |
|
|  | [setLoadText(boolean value)](#setLoadText-boolean-) | يضبط علمًا يشير إلى أن السلسلة التي تم تمريرها إلى مُنشئ [Comparer](../../com.groupdocs.comparison/comparer) أو إلى طريقة [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) هي نص للمقارنة، وليس مسارات ملفات (للمقارنة النصية فقط). |
|
|  | [getPassword()](#getPassword--) | يحصل على كلمة مرور ستُستخدم لتحميل المستند. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | يضبط كلمة مرور يجب استخدامها لتحميل المستند. |
|
|  | [getFontDirectories()](#getFontDirectories--) | يحصل على قائمة بالأدلة التي توضع فيها ملفات الخطوط لتحميل المستند. |
|
|  | [setFontDirectories(List<String> value)](#setFontDirectories-java.util.List-java.lang.String--) | يضبط قائمة بالأدلة التي توضع فيها ملفات الخطوط لتحميل المستند. |
|
|  | [getFileType()](#getFileType--) | يحصل على نوع الملف الذي يتم تحميله. |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.comparison.result.FileType-) | يحدد نوع الملف الذي يتم تحميله. |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


ينشئ مثيلاً جديداً لفئة LoadOptions.


### LoadOptions(boolean isLoadText) {#LoadOptions-boolean-}
```
public LoadOptions(boolean isLoadText)
```


ينشئ مثيلاً جديداً لفئة LoadOptions مع علم يعني أن سلسلة الإدخال هي نص للمقارنة، وليس مسارًا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | isLoadText | boolean | العلم الذي يعني أن سلسلة الإدخال هي نص للمقارنة، وليس مسارًا |
|

### LoadOptions(String password) {#LoadOptions-java.lang.String-}
```
public LoadOptions(String password)
```


ينشئ مثيلاً جديداً لفئة LoadOptions مع كلمة مرور لتحميل المستند.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | كلمة مرور | java.lang.String | كلمة المرور لتحميل المستند |
|

### LoadOptions(boolean isLoadText, String password) {#LoadOptions-boolean-java.lang.String-}
```
public LoadOptions(boolean isLoadText, String password)
```


ينشئ مثيلاً جديداً لفئة LoadOptions مع علم يعني أن سلسلة الإدخال هي نص للمقارنة وكلمة مرور لتحميل المستند.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | isLoadText | boolean | العلم الذي يعني أن سلسلة الإدخال هي نص للمقارنة، وليس مسارًا |
|
|  | كلمة مرور | java.lang.String | كلمة المرور لتحميل المستند |
|

### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.comparison.result.FileType-}
```
public LoadOptions(FileType fileType)
```


ينشئ مثيلاً جديداً لفئة LoadOptions مع نوع الملف.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.comparison.result/filetype) | نوع الملف |
|

### isLoadText() {#isLoadText--}
```
public boolean isLoadText()
```


يحصل على علم يشير إلى أن السلسلة التي تم تمريرها إلى مُنشئ [Comparer](../../com.groupdocs.comparison/comparer) أو إلى طريقة [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) هي نص للمقارنة، وليس مسارات ملفات (للمقارنة النصية فقط).


**Returns:**
منطقي - true إذا كانت سلسلة الإدخال نصًا للمقارنة، وإلا false

### setLoadText(boolean value) {#setLoadText-boolean-}
```
public void setLoadText(boolean value)
```


يضبط علمًا يشير إلى أن السلسلة التي تم تمريرها إلى مُنشئ [Comparer](../../com.groupdocs.comparison/comparer) أو إلى طريقة [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) هي نص للمقارنة، وليس مسارات ملفات (للمقارنة النصية فقط).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | boolean | true إذا كانت سلسلة الإدخال نصًا للمقارنة، وإلا false |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


يحصل على كلمة مرور ستُستخدم لتحميل المستند.


**Returns:**
java.lang.String - كلمة المرور لتحميل المستند

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


يضبط كلمة مرور يجب استخدامها لتحميل المستند.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | java.lang.String | كلمة المرور لتحميل المستند |
|

### getFontDirectories() {#getFontDirectories--}
```
public List<String> getFontDirectories()
```


يحصل على قائمة بالأدلة التي توضع فيها ملفات الخطوط لتحميل المستند.


**Returns:**
java.util.List<java.lang.String> - قائمة الأدلة التي تحتوي على ملفات الخطوط

### setFontDirectories(List<String> value) {#setFontDirectories-java.util.List-java.lang.String--}
```
public void setFontDirectories(List<String> value)
```


يضبط قائمة بالأدلة التي توضع فيها ملفات الخطوط لتحميل المستند.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | java.util.List<java.lang.String> | قائمة الأدلة التي تحتوي على ملفات الخطوط |
|

### getFileType() {#getFileType--}
```
public FileType getFileType()
```


يحصل على نوع الملف الذي يتم تحميله.


**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the type of the file

### setFileType(FileType value) {#setFileType-com.groupdocs.comparison.result.FileType-}
```
public void setFileType(FileType value)
```


يحدد نوع الملف الذي يتم تحميله.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [FileType](../../com.groupdocs.comparison.result/filetype) | نوع الملف |
|

