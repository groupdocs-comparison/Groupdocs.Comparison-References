---
title: "Comparer"
second_title: "GroupDocs.Comparison لـ Java API Reference"
description: "توفر فئة Comparer وظائف لمقارنة المستندات وتوليد نتائج المقارنة."
type: docs
weight: 10
url: /ar/java/com.groupdocs.comparison/comparer/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public class Comparer implements System.IDisposable, Closeable
```

توفر فئة Comparer وظائف لمقارنة المستندات وتوليد نتائج المقارنة.


تسمح لك بمقارنة أنواع مختلفة من المستندات، مثل PDF وWord وExcel وPowerPoint، وأكثر.


مثال على الاستخدام:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     CompareOptions compareOptions = new CompareOptions();
     compareOptions.setDetectStyleChanges(true);

     comparer.compare(resultFile, compareOptions);
 }
 
````


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [Comparer(String filePath)](#Comparer-java.lang.String-) | يُنشئ مثيلًا جديدًا من فئة Comparer بالمسار المصدر المحدد للملف. |
|
|  | [Comparer(String filePath, CompareOptions compareOptions)](#Comparer-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | يُنشئ مثيلًا جديدًا من فئة Comparer بالمسار المحدد للمجلد وخيارات المقارنة. |
|
|  | [Comparer(Path filePath)](#Comparer-java.nio.file.Path-) | يُنشئ مثيلًا جديدًا من فئة Comparer بالمسار المصدر المحدد للملف. |
|
|  | [Comparer(String filePath, LoadOptions loadOptions)](#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-) | يُنشئ مثيلًا جديدًا من Comparer بالمسار المصدر المحدد للملف و[LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions). |
|
|  | [Comparer(Path filePath, LoadOptions loadOptions)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-) | يُنشئ مثيلًا جديدًا من Comparer بالمسار المصدر المحدد للملف و[LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions). |
|
|  | [Comparer(Path filePath, CompareOptions compareOptions)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | يُنشئ مثيلًا جديدًا من Comparer بالمسار المصدر المحدد للملف و[LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions). |
|
|  | [Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings)](#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-) | يُنشئ مثلاً جديدًا من فئة Comparer بالمسار المحدد لملف المصدر، [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) و[ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)](#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-) | يُنشئ مثلاً جديدًا من فئة Comparer بالمسار المحدد لملف المصدر، [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) و[ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(String filePath, ComparerSettings settings)](#Comparer-java.lang.String-com.groupdocs.comparison.ComparerSettings-) | يُنشئ مثلاً جديدًا من فئة Comparer بالمسار المحدد لملف المصدر و[ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(Path filePath, ComparerSettings settings)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.ComparerSettings-) | يُنشئ مثلاً جديدًا من فئة Comparer بالمسار المحدد لملف المصدر و[ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-) | يُنشئ مثلاً جديدًا من فئة Comparer بالمسار المحدد لملف المصدر، [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) و[ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-) | يُنشئ مثلاً جديدًا من فئة Comparer بالمسار المحدد لملف المصدر، [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) و[ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(InputStream document)](#Comparer-java.io.InputStream-) | يُنشئ مثلاً جديدًا من فئة Comparer بتدفق المستند المصدر المحدد. |
|
|  | [Comparer(InputStream document, LoadOptions loadOptions)](#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-) | يُنشئ مثلاً جديدًا من Comparer بتدفق المستند المصدر المحدد و[LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions). |
|
|  | [Comparer(InputStream document, ComparerSettings settings)](#Comparer-java.io.InputStream-com.groupdocs.comparison.ComparerSettings-) | يُنشئ مثلاً جديدًا من فئة Comparer بتدفق المستند المصدر المحدد و[ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(InputStream document, LoadOptions loadOptions, ComparerSettings settings)](#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-) | يُنشئ مثلاً جديدًا من فئة Comparer بتدفق المستند المحدد، [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) و[ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(ComparerSettings settings)](#Comparer-com.groupdocs.comparison.ComparerSettings-) | يُنشئ مثلاً جديدًا من فئة Comparer بالـ[ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
## الحقول

| حقل | الوصف |
| --- | --- |
| [FILE_PATH](#FILE-PATH) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getSource()](#getSource--) | يحصل على المستند المصدر الذي يتم مقارنته. |
|
|  | [getTargets()](#getTargets--) | قائمة المستندات الهدف للمقارنة مع ملف المصدر. |
|
|  | [compare()](#compare--) | يقارن الملف المحدد مع المستندات الهدف دون حفظ النتيجة باستخدام الخيارات الافتراضية. |
|
|  | [compare(String filePath)](#compare-java.lang.String-) | يقارن الملف المحدد مع المستندات الهدف وينتج نتيجة مقارنة. |
|
|  | [compare(Path filePath)](#compare-java.nio.file.Path-) | يقارن الملف المحدد مع المستندات الهدف وينتج نتيجة مقارنة. |
|
|  | [compare(OutputStream outputStream)](#compare-java.io.OutputStream-) | يقارن الملف المحدد مع المستندات الهدف ويكتب نتيجة المقارنة إلى تدفق الإخراج. |
|
|  | [compare(String filePath, CompareOptions compareOptions)](#compare-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | يقارن الملف المحدد مع المستندات الهدف ويكتب نتيجة المقارنة إلى مسار الملف المحدد. |
|
|  | [compare(Path filePath, CompareOptions compareOptions)](#compare-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | يقارن الملف المحدد مع المستندات الهدف ويكتب نتيجة المقارنة إلى مسار الملف المحدد. |
|
|  | [compare(OutputStream stream, CompareOptions compareOptions)](#compare-java.io.OutputStream-com.groupdocs.comparison.options.CompareOptions-) | يقارن الملف المحدد مع المستندات الهدف ويكتب نتيجة المقارنة إلى تدفق الإخراج. |
|
|  | [compare(SaveOptions saveOptions, CompareOptions compareOptions)](#compare-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | يقارن الملف المحدد مع المستندات الهدف دون حفظ النتيجة. |
|
|  | [compare(String filePath, SaveOptions saveOptions)](#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-) | يقارن الملف المحدد مع المستندات الهدف ويكتب نتيجة المقارنة إلى مسار الملف المحدد. |
|
|  | [compare(Path filePath, SaveOptions saveOptions)](#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-) | يقارن الملف المحدد مع المستندات الهدف ويكتب نتيجة المقارنة إلى مسار الملف المحدد. |
|
|  | [compare(OutputStream stream, SaveOptions saveOptions)](#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-) | يقارن الملف المحدد مع المستندات الهدف ويكتب نتيجة المقارنة إلى مسار الملف المحدد. |
|
|  | [compare(CompareOptions compareOptions)](#compare-com.groupdocs.comparison.options.CompareOptions-) | يقارن الملف المحدد مع المستندات الهدف دون حفظ النتيجة. |
|
|  | [compare(OutputStream outputStream, SaveOptions saveOptions, CompareOptions compareOptions)](#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | يقارن الملف المحدد مع المستندات الهدف ويكتب نتيجة المقارنة إلى تدفق الإخراج المحدد. |
|
|  | [compare(String filePath, SaveOptions saveOptions, CompareOptions compareOptions)](#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | يقارن الملف المحدد مع المستندات الهدف ويكتب نتيجة المقارنة إلى مسار الملف المحدد. |
|
|  | [compareDirectory(String filePath, CompareOptions compareOptions)](#compareDirectory-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | يقارن الدليل المحدد مع الدليل الهدف ويحفظ نتيجة المقارنة إلى مسار الملف المحدد. |
|
|  | [compareDirectory(Path filePath, CompareOptions compareOptions)](#compareDirectory-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | يقارن الدليل المحدد مع الدليل الهدف ويحفظ نتيجة المقارنة إلى مسار الملف المحدد. |
|
|  | [compare(Path filePath, SaveOptions saveOptions, CompareOptions compareOptions)](#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | يقارن الملف المحدد مع المستندات الهدف ويكتب نتيجة المقارنة إلى مسار الملف المحدد. |
|
|  | [add(String filePath)](#add-java.lang.String-) | يضيف المستند الهدف المحدد إلى عملية المقارنة. |
|
|  | [add(String filePath, CompareOptions compareOptions)](#add-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | يضيف المستند أو المجلد الهدف المحدد إلى عملية المقارنة. |
|
|  | [add(Path filePath)](#add-java.nio.file.Path-) | يضيف المستند الهدف المحدد إلى عملية المقارنة. |
|
|  | [add(String[] filePaths)](#add-java.lang.String...-) | يضيف المستندات الهدف المحددة إلى عملية المقارنة. |
|
|  | [add(Path[] filePaths)](#add-java.nio.file.Path...-) | يضيف المستندات الهدف المحددة إلى عملية المقارنة. |
|
|  | [add(String filePath, LoadOptions loadOptions)](#add-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-) | يضيف المستند الهدف المحدد إلى عملية المقارنة مع خيارات التحميل المحددة. |
|
|  | [add(Path filePath, LoadOptions loadOptions)](#add-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-) | يضيف المستند الهدف المحدد إلى عملية المقارنة مع خيارات التحميل المحددة. |
|
|  | [add(Path filePath, CompareOptions compareOptions)](#add-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | يضيف المستند الهدف المحدد إلى عملية المقارنة مع خيارات التحميل المحددة. |
|
|  | [add(InputStream document)](#add-java.io.InputStream-) | يضيف المستند الهدف المحدد إلى عملية المقارنة. |
|
|  | [add(InputStream[] documents)](#add-java.io.InputStream...-) | يضيف المستندات الهدف المحددة إلى عملية المقارنة. |
|
|  | [add(InputStream document, LoadOptions loadOptions)](#add-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-) | يضيف المستند الهدف المحدد إلى عملية المقارنة مع خيارات التحميل المحددة. |
|
|  | [getChanges()](#getChanges--) | يسترجع مصفوفة من كائنات [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) التي تمثل التغييرات المكتشفة أثناء عملية المقارنة. |
|
|  | [getChanges(GetChangeOptions getChangeOptions)](#getChanges-com.groupdocs.comparison.options.GetChangeOptions-) | يسترجع مصفوفة من كائنات [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) التي تمثل التغييرات المكتشفة أثناء عملية المقارنة. |
|
|  | [applyChanges(String filePath, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.lang.String-com.groupdocs.comparison.options.ApplyChangeOptions-) | يقبل أو يرفض التغييرات ويطبقها على المستند الناتج. |
|
|  | [applyChanges(Path filePath, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.ApplyChangeOptions-) | يقبل أو يرفض التغييرات ويطبقها على المستند الناتج. |
|
|  | [applyChanges(OutputStream document, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.ApplyChangeOptions-) | يقبل أو يرفض التغييرات ويطبقها على المستند الناتج. |
|
|  | [applyChanges(String filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-) | يقبل أو يرفض التغييرات ويطبقها على المستند الناتج. |
|
|  | [applyChanges(Path filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-) | يقبل أو يرفض التغييرات ويطبقها على المستند الناتج. |
|
|  | [applyChanges(OutputStream document, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-) | يقبل أو يرفض التغييرات ويطبقها على المستند الناتج. |
|
|  | [getResultString()](#getResultString--) | يحصل على سلسلة النتيجة بعد المقارنة (للمقارنة النصية فقط). |
|
|  | [getSourceFolder()](#getSourceFolder--) | يعيد المجلد المصدر الذي يتم مقارنته. |
|
|  | [getTargetFolder()](#getTargetFolder--) | يعيد المجلد الهدف الذي يتم مقارنته. |
|
|  | [selfComparisonCheck(Document source, Document target)](#selfComparisonCheck-com.groupdocs.comparison.Document-com.groupdocs.comparison.Document-) | فحص المقارنة الذاتية (e498c23). |
|
|  | [close()](#close--) | يطلق الموارد. |
|
### Comparer(String filePath) {#Comparer-java.lang.String-}
```
public Comparer(String filePath)
```


يُنشئ مثيلًا جديدًا من فئة Comparer بالمسار المصدر المحدد للملف.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | المسار إلى المستند المصدر |
|

### Comparer(String filePath, CompareOptions compareOptions) {#Comparer-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(String filePath, CompareOptions compareOptions)
```


يُنشئ مثيلًا جديدًا من فئة Comparer بالمسار المحدد للمجلد وخيارات المقارنة.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | المسار إلى المستند المصدر أو المجلد |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | خيارات المقارنة للمقارنة بين المجلدات |
|

### Comparer(Path filePath) {#Comparer-java.nio.file.Path-}
```
public Comparer(Path filePath)
```


يُنشئ مثيلًا جديدًا من فئة Comparer بالمسار المصدر المحدد للملف.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | المسار إلى المستند المصدر |
|

### Comparer(String filePath, LoadOptions loadOptions) {#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Comparer(String filePath, LoadOptions loadOptions)
```


يُنشئ مثيلًا جديدًا من Comparer بالمسار المصدر المحدد للملف و[LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | المسار إلى المستند المصدر |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | خيارات التحميل المخصصة التي سيتم تطبيقها على المستند |
|

### Comparer(Path filePath, LoadOptions loadOptions) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Comparer(Path filePath, LoadOptions loadOptions)
```


يُنشئ مثيلًا جديدًا من Comparer بالمسار المصدر المحدد للملف و[LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | المسار إلى المستند المصدر |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | خيارات التحميل المخصصة التي سيتم تطبيقها على المستند |
|

### Comparer(Path filePath, CompareOptions compareOptions) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(Path filePath, CompareOptions compareOptions)
```


يُنشئ مثيلًا جديدًا من Comparer بالمسار المصدر المحدد للملف و[LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | المسار إلى المستند المصدر |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | خيارات المقارنة للمقارنة بين المجلدات |
|

### Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings) {#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings)
```


يُنشئ مثلاً جديدًا من فئة Comparer بالمسار المحدد لملف المصدر، [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) و[ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | المسار إلى المستند المصدر |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | خيارات التحميل المخصصة التي سيتم تطبيقها على المستند |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | إعدادات المقارن التي ستُستخدم لعملية المقارنة |
|

### Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions) {#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)
```


يُنشئ مثلاً جديدًا من فئة Comparer بالمسار المحدد لملف المصدر، [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) و[ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | المسار إلى المستند المصدر أو المجلد أو النص الذي سيتم مقارنته |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | خيارات التحميل المخصصة التي سيتم تطبيقها على المستند |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | إعدادات المقارن التي ستُستخدم لعملية المقارنة |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | خيارات المقارنة للمقارنة بين المجلدات |
|

### Comparer(String filePath, ComparerSettings settings) {#Comparer-java.lang.String-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(String filePath, ComparerSettings settings)
```


يُنشئ مثلاً جديدًا من فئة Comparer بالمسار المحدد لملف المصدر و[ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | المسار إلى المستند المصدر |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | إعدادات المقارن التي ستُستخدم لعملية المقارنة |
|

### Comparer(Path filePath, ComparerSettings settings) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(Path filePath, ComparerSettings settings)
```


يُنشئ مثلاً جديدًا من فئة Comparer بالمسار المحدد لملف المصدر و[ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | المسار إلى المستند المصدر |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | إعدادات المقارن التي ستُستخدم لعملية المقارنة |
|

### Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings)
```


يُنشئ مثلاً جديدًا من فئة Comparer بالمسار المحدد لملف المصدر، [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) و[ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | المسار إلى المستند المصدر |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | خيارات التحميل المخصصة التي سيتم تطبيقها على المستند |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | إعدادات المقارن التي ستُستخدم لعملية المقارنة |
|

### Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)
```


يُنشئ مثلاً جديدًا من فئة Comparer بالمسار المحدد لملف المصدر، [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) و[ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | المسار إلى المستند المصدر أو المجلد |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | خيارات التحميل المخصصة التي سيتم تطبيقها على المستند |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | إعدادات المقارن التي ستُستخدم لعملية المقارنة |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | خيارات المقارنة للمقارنة بين المجلدات |
|

### Comparer(InputStream document) {#Comparer-java.io.InputStream-}
```
public Comparer(InputStream document)
```


يُنشئ مثلاً جديدًا من فئة Comparer بتدفق المستند المصدر المحدد.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | مستند | java.io.InputStream | دفق الإدخال للمستند المصدر |
|

### Comparer(InputStream document, LoadOptions loadOptions) {#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Comparer(InputStream document, LoadOptions loadOptions)
```


يُنشئ مثلاً جديدًا من Comparer بتدفق المستند المصدر المحدد و[LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | مستند | java.io.InputStream | دفق الإدخال للمستند المصدر |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | خيارات التحميل المخصصة التي سيتم تطبيقها على المستند |
|

### Comparer(InputStream document, ComparerSettings settings) {#Comparer-java.io.InputStream-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(InputStream document, ComparerSettings settings)
```


يُنشئ مثلاً جديدًا من فئة Comparer بتدفق المستند المصدر المحدد و[ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | مستند | java.io.InputStream | دفق الإدخال للمستند المصدر |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | إعدادات المقارن التي ستُستخدم لعملية المقارنة |
|

### Comparer(InputStream document, LoadOptions loadOptions, ComparerSettings settings) {#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(InputStream document, LoadOptions loadOptions, ComparerSettings settings)
```


يُنشئ مثلاً جديدًا من فئة Comparer بتدفق المستند المحدد، [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) و[ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | مستند | java.io.InputStream | الدفق الذي يحتوي على بيانات مستند للمقارنة |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | خيارات التحميل المخصصة التي سيتم تطبيقها على المستند |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | إعدادات المقارن التي ستُستخدم لعملية المقارنة |
|

### Comparer(ComparerSettings settings) {#Comparer-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(ComparerSettings settings)
```


يُنشئ مثلاً جديدًا من فئة Comparer بالـ[ComparerSettings](../../com.groupdocs.comparison/comparersettings).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | الإعدادات |
|

### FILE_PATH {#FILE-PATH}
```
public static final String FILE_PATH
```


### getSource() {#getSource--}
```
public final Document getSource()
```


يحصل على المستند المصدر الذي يتم مقارنته.


**Returns:**
[Document](../../com.groupdocs.comparison/document) - the source document

### getTargets() {#getTargets--}
```
public final List<Document> getTargets()
```


قائمة المستندات الهدف للمقارنة مع ملف المصدر.


**Returns:**
java.util.List<com.groupdocs.comparison.Document> - المستندات الهدف

### compare() {#compare--}
```
public final Path compare()
```


يقارن الملف المحدد مع المستندات الهدف دون حفظ النتيجة باستخدام الخيارات الافتراضية.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Returns:**
java.nio.file.Path - مسار مستند النتيجة أو null

### compare(String filePath) {#compare-java.lang.String-}
```
public final Path compare(String filePath)
```


يقارن الملف المحدد مع المستندات الهدف وينتج نتيجة مقارنة.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | مسار مستند النتيجة |
|

**Returns:**
java.nio.file.Path - مسار ملف النتيجة أو null. في بعض الحالات يمكن تغيير امتداله

### compare(Path filePath) {#compare-java.nio.file.Path-}
```
public final Path compare(Path filePath)
```


يقارن الملف المحدد مع المستندات الهدف وينتج نتيجة مقارنة.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | مسار مستند النتيجة |
|

**Returns:**
java.nio.file.Path - مسار ملف النتيجة، في بعض الحالات يمكن تغيير امتداله

### compare(OutputStream outputStream) {#compare-java.io.OutputStream-}
```
public final Path compare(OutputStream outputStream)
```


يقارن الملف المحدد مع المستندات الهدف ويكتب نتيجة المقارنة إلى تدفق الإخراج.


ملاحظة: في الحالات التي تكون فيها قيمة الإرجاع null، استخدم البيانات التي كُتبت في outputStream

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | outputStream | java.io.OutputStream | دفق مستند النتيجة |
|

**Returns:**
java.nio.file.Path - مسار ملف النتيجة أو null عندما يجب استخدام البيانات من  outputStream . في بعض الحالات يمكن تغيير امتداد ملف النتيجة

### compare(String filePath, CompareOptions compareOptions) {#compare-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(String filePath, CompareOptions compareOptions)
```


يقارن الملف المحدد مع المستندات الهدف ويكتب نتيجة المقارنة إلى مسار الملف المحدد.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | مسار ملف مستند النتيجة |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | خيارات المقارنة التي ستُستخدم لعملية المقارنة |
|

**Returns:**
java.nio.file.Path - مسار ملف النتيجة، في بعض الحالات يمكن تغيير امتداله

### compare(Path filePath, CompareOptions compareOptions) {#compare-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(Path filePath, CompareOptions compareOptions)
```


يقارن الملف المحدد مع المستندات الهدف ويكتب نتيجة المقارنة إلى مسار الملف المحدد.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | مسار ملف مستند النتيجة |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | خيارات المقارنة التي ستُستخدم لعملية المقارنة |
|

**Returns:**
java.nio.file.Path - مسار ملف النتيجة، في بعض الحالات يمكن تغيير امتداله

### compare(OutputStream stream, CompareOptions compareOptions) {#compare-java.io.OutputStream-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(OutputStream stream, CompareOptions compareOptions)
```


يقارن الملف المحدد مع المستندات الهدف ويكتب نتيجة المقارنة إلى تدفق الإخراج.


ملاحظة: في حالة كون قيمة الإرجاع null، استخدم البيانات التي كُتبت في outputStream.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | تدفق | java.io.OutputStream | دفق مستند النتيجة |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | خيارات المقارنة التي ستُستخدم لعملية المقارنة |
|

**Returns:**
java.nio.file.Path - مسار ملف النتيجة أو null عندما يجب استخدام البيانات من  outputStream . في بعض الحالات يمكن تغيير امتداد ملف النتيجة

### compare(SaveOptions saveOptions, CompareOptions compareOptions) {#compare-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(SaveOptions saveOptions, CompareOptions compareOptions)
```


يقارن الملف المحدد مع المستندات الهدف دون حفظ النتيجة.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparison options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | خيارات الحفظ |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | خيارات المقارنة التي ستُستخدم لعملية المقارنة |
|

**Returns:**
java.nio.file.Path - مسار مستند النتيجة أو null

### compare(String filePath, SaveOptions saveOptions) {#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-}
```
public final Path compare(String filePath, SaveOptions saveOptions)
```


يقارن الملف المحدد مع المستندات الهدف ويكتب نتيجة المقارنة إلى مسار الملف المحدد.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | مسار ملف مستند النتيجة |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | خيارات الحفظ |
|

**Returns:**
java.nio.file.Path - مسار ملف النتيجة، في بعض الحالات يمكن تغيير امتداله

### compare(Path filePath, SaveOptions saveOptions) {#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-}
```
public final Path compare(Path filePath, SaveOptions saveOptions)
```


يقارن الملف المحدد مع المستندات الهدف ويكتب نتيجة المقارنة إلى مسار الملف المحدد.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | مسار ملف مستند النتيجة |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | خيارات الحفظ |
|

**Returns:**
java.nio.file.Path - مسار ملف النتيجة، في بعض الحالات يمكن تغيير امتداله

### compare(OutputStream stream, SaveOptions saveOptions) {#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-}
```
public final Path compare(OutputStream stream, SaveOptions saveOptions)
```


يقارن الملف المحدد مع المستندات الهدف ويكتب نتيجة المقارنة إلى مسار الملف المحدد.


ملاحظة: في حالة كون قيمة الإرجاع null، استخدم البيانات التي تم كتابتها في outputStream

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | تدفق | java.io.OutputStream | دفق مستند النتيجة |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | خيارات الحفظ |
|

**Returns:**
java.nio.file.Path - مسار ملف النتيجة أو null عندما يجب استخدام البيانات من  outputStream . في بعض الحالات يمكن تغيير امتداد ملف النتيجة

### compare(CompareOptions compareOptions) {#compare-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(CompareOptions compareOptions)
```


يقارن الملف المحدد مع المستندات الهدف دون حفظ النتيجة.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | خيارات المقارنة التي ستُستخدم لعملية المقارنة |
|

**Returns:**
java.nio.file.Path - المسار إلى ملف النتيجة أو null

### compare(OutputStream outputStream, SaveOptions saveOptions, CompareOptions compareOptions) {#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(OutputStream outputStream, SaveOptions saveOptions, CompareOptions compareOptions)
```


يقارن الملف المحدد مع المستندات الهدف ويكتب نتيجة المقارنة إلى تدفق الإخراج المحدد.


ملاحظة: في حالة كون قيمة الإرجاع null، استخدم البيانات التي تم كتابتها في outputStream

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | outputStream | java.io.OutputStream | دفق مستند النتيجة |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | خيارات الحفظ التي سيتم استخدامها لحفظ مستند النتيجة |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | خيارات المقارنة التي ستُستخدم لعملية المقارنة |
|

**Returns:**
java.nio.file.Path - مسار ملف النتيجة أو null عندما يجب استخدام البيانات من  outputStream . في بعض الحالات يمكن تغيير امتداد ملف النتيجة

### compare(String filePath, SaveOptions saveOptions, CompareOptions compareOptions) {#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(String filePath, SaveOptions saveOptions, CompareOptions compareOptions)
```


يقارن الملف المحدد مع المستندات الهدف ويكتب نتيجة المقارنة إلى مسار الملف المحدد.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparison options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | مسار ملف مستند النتيجة |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | خيارات الحفظ التي سيتم استخدامها لحفظ مستند النتيجة |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | خيارات المقارنة التي ستُستخدم لعملية المقارنة |
|

**Returns:**
java.nio.file.Path - مسار ملف النتيجة، في بعض الحالات يمكن تغيير امتداله

### compareDirectory(String filePath, CompareOptions compareOptions) {#compareDirectory-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public void compareDirectory(String filePath, CompareOptions compareOptions)
```


يقارن الدليل المحدد مع الدليل الهدف ويحفظ نتيجة المقارنة إلى مسار الملف المحدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | مسار الملف حيث سيتم حفظ نتيجة المقارنة. |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | الخيارات التي سيتم استخدامها لعملية مقارنة الدليل. |
|

### compareDirectory(Path filePath, CompareOptions compareOptions) {#compareDirectory-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public void compareDirectory(Path filePath, CompareOptions compareOptions)
```


يقارن الدليل المحدد مع الدليل الهدف ويحفظ نتيجة المقارنة إلى مسار الملف المحدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | مسار الملف حيث سيتم حفظ نتيجة المقارنة. |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | الخيارات التي سيتم استخدامها لعملية مقارنة الدليل. |
|

### compare(Path filePath, SaveOptions saveOptions, CompareOptions compareOptions) {#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(Path filePath, SaveOptions saveOptions, CompareOptions compareOptions)
```


يقارن الملف المحدد مع المستندات الهدف ويكتب نتيجة المقارنة إلى مسار الملف المحدد.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | مسار ملف مستند النتيجة |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | خيارات الحفظ التي سيتم استخدامها لحفظ مستند النتيجة |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | خيارات المقارنة التي ستُستخدم لعملية المقارنة |
|

**Returns:**
java.nio.file.Path - مسار ملف النتيجة، في بعض الحالات يمكن تغيير امتداله

### add(String filePath) {#add-java.lang.String-}
```
public final void add(String filePath)
```


يضيف المستند الهدف المحدد إلى عملية المقارنة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | المسار إلى المستند الهدف الذي سيتم إضافته |
|

### add(String filePath, CompareOptions compareOptions) {#add-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public void add(String filePath, CompareOptions compareOptions)
```


يضيف المستند أو المجلد الهدف المحدد إلى عملية المقارنة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | المسار إلى المستند أو المجلد الهدف الذي سيتم إضافته |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | الخيارات للمقارنة |
|

### add(Path filePath) {#add-java.nio.file.Path-}
```
public final void add(Path filePath)
```


يضيف المستند الهدف المحدد إلى عملية المقارنة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | المسار إلى المستند الهدف الذي سيتم إضافته |
|

### add(String[] filePaths) {#add-java.lang.String...-}
```
public final void add(String[] filePaths)
```


يضيف المستندات الهدف المحددة إلى عملية المقارنة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePaths | java.lang.String[] | المسارات إلى المستندات الهدف التي سيتم إضافتها |
|

### add(Path[] filePaths) {#add-java.nio.file.Path...-}
```
public final void add(Path[] filePaths)
```


يضيف المستندات الهدف المحددة إلى عملية المقارنة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePaths | java.nio.file.Path[] | المسارات إلى المستندات الهدف التي سيتم إضافتها |
|

### add(String filePath, LoadOptions loadOptions) {#add-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-}
```
public final void add(String filePath, LoadOptions loadOptions)
```


يضيف المستند الهدف المحدد إلى عملية المقارنة مع خيارات التحميل المحددة.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | المسار إلى المستند الهدف الذي سيتم إضافته |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | خيارات التحميل المخصصة التي سيتم تطبيقها على المستند |
|

### add(Path filePath, LoadOptions loadOptions) {#add-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-}
```
public final void add(Path filePath, LoadOptions loadOptions)
```


يضيف المستند الهدف المحدد إلى عملية المقارنة مع خيارات التحميل المحددة.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | المسار إلى المستند الهدف الذي سيتم إضافته |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | خيارات التحميل المخصصة التي سيتم تطبيقها على المستند |
|

### add(Path filePath, CompareOptions compareOptions) {#add-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public final void add(Path filePath, CompareOptions compareOptions)
```


يضيف المستند الهدف المحدد إلى عملية المقارنة مع خيارات التحميل المحددة.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | المسار إلى المستند أو المجلد الهدف الذي سيتم إضافته |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | الخيارات للمقارنة |
|

### add(InputStream document) {#add-java.io.InputStream-}
```
public final void add(InputStream document)
```


يضيف المستند الهدف المحدد إلى عملية المقارنة.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | مستند | java.io.InputStream | الدفق الذي يحتوي على بيانات مستند للمقارنة |
|

### add(InputStream[] documents) {#add-java.io.InputStream...-}
```
public final void add(InputStream[] documents)
```


يضيف المستندات الهدف المحددة إلى عملية المقارنة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | documents | java.io.InputStream[] | تيارات تحتوي على بيانات المستندات التي سيتم مقارنتها |
|

### add(InputStream document, LoadOptions loadOptions) {#add-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-}
```
public final void add(InputStream document, LoadOptions loadOptions)
```


يضيف المستند الهدف المحدد إلى عملية المقارنة مع خيارات التحميل المحددة.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | مستند | java.io.InputStream | الدفق الذي يحتوي على بيانات مستند للمقارنة |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | خيارات التحميل المخصصة التي سيتم تطبيقها على المستند |
|

### getChanges() {#getChanges--}
```
public final ChangeInfo[] getChanges()
```


يسترجع مصفوفة من كائنات [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) التي تمثل التغييرات المكتشفة أثناء عملية المقارنة.


استخدم هذه الطريقة للحصول على معلومات مفصلة حول التغييرات بين المستند المصدر والمستند الهدف (المستندات).
كل كائن [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) يحتوي على معلومات مثل نوع التغيير، المنطقة المتأثرة،
والمحتوى قبل وبعد التغيير.

* More about how to obtain collection of detected differences between compared documents in Java: [How to get list of changes between documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Get+list+of+changes)
* More about how to get changes coordinates at pages image preview when comparing documents using GroupDocs.Comparison for Java: [How to get changes coordinates programmatically](../https://docs.groupdocs.com/display/comparisonjava/Get+changes+coordinates)


**Returns:**
com.groupdocs.comparison.result.ChangeInfo[] - مصفوفة من كائنات [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) تمثل التغييرات التي تم اكتشافها أثناء عملية المقارنة

### getChanges(GetChangeOptions getChangeOptions) {#getChanges-com.groupdocs.comparison.options.GetChangeOptions-}
```
public final ChangeInfo[] getChanges(GetChangeOptions getChangeOptions)
```


يسترجع مصفوفة من كائنات [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) التي تمثل التغييرات المكتشفة أثناء عملية المقارنة.


استخدم هذه الطريقة للحصول على معلومات مفصلة حول التغييرات بين المستند المصدر والمستند الهدف (المستندات).
كل كائن [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) يحتوي على معلومات مثل نوع التغيير، المنطقة المتأثرة،
والمحتوى قبل وبعد التغيير.


المعامل [GetChangeOptions](../../com.groupdocs.comparison.options/getchangeoptions) يسمح بفلترة التغييرات بطريقة مختلفة.

* More about how to obtain collection of detected differences between compared documents in Java: [How to get list of changes between documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Get+list+of+changes)
* More about how to get changes coordinates at pages image preview when comparing documents using GroupDocs.Comparison for Java: [How to get changes coordinates programmatically](../https://docs.groupdocs.com/display/comparisonjava/Get+changes+coordinates)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | getChangeOptions | [GetChangeOptions](../../com.groupdocs.comparison.options/getchangeoptions) | الكائن الذي يسمح بفلترة التغييرات |
|

**Returns:**
com.groupdocs.comparison.result.ChangeInfo[] - مصفوفة من كائنات [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) تمثل التغييرات التي تم اكتشافها أثناء عملية المقارنة

### applyChanges(String filePath, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.lang.String-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(String filePath, ApplyChangeOptions applyChangeOptions)
```


يقبل أو يرفض التغييرات ويطبقها على المستند الناتج.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | مسار ملف مستند النتيجة |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | خيارات تطبيق التغييرات المخصصة لتكوين عملية تطبيق التغييرات |
|

### applyChanges(Path filePath, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(Path filePath, ApplyChangeOptions applyChangeOptions)
```


يقبل أو يرفض التغييرات ويطبقها على المستند الناتج.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | مسار ملف مستند النتيجة |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | خيارات تطبيق التغييرات المخصصة لتكوين عملية تطبيق التغييرات |
|

### applyChanges(OutputStream document, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(OutputStream document, ApplyChangeOptions applyChangeOptions)
```


يقبل أو يرفض التغييرات ويطبقها على المستند الناتج.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | مستند | java.io.OutputStream | تيار إخراج مستند النتيجة |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | خيارات تطبيق التغييرات المخصصة لتكوين عملية تطبيق التغييرات |
|

### applyChanges(String filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(String filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)
```


يقبل أو يرفض التغييرات ويطبقها على المستند الناتج.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | مسار ملف مستند النتيجة |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | خيارات الحفظ لتكوين حفظ مستند النتيجة |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | خيارات تطبيق التغييرات المخصصة لتكوين عملية تطبيق التغييرات |
|

### applyChanges(Path filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(Path filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)
```


يقبل أو يرفض التغييرات ويطبقها على المستند الناتج.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | مسار ملف مستند النتيجة |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | خيارات الحفظ لتكوين حفظ مستند النتيجة |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | خيارات تطبيق التغييرات المخصصة لتكوين عملية تطبيق التغييرات |
|

### applyChanges(OutputStream document, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(OutputStream document, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)
```


يقبل أو يرفض التغييرات ويطبقها على المستند الناتج.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | مستند | java.io.OutputStream | تيار إخراج مستند النتيجة |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | خيارات الحفظ لتكوين حفظ مستند النتيجة |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | خيارات تطبيق التغييرات المخصصة لتكوين عملية تطبيق التغييرات |
|

### getResultString() {#getResultString--}
```
public String getResultString()
```


يحصل على سلسلة النتيجة بعد المقارنة (للمقارنة النصية فقط).


**Returns:**
java.lang.String - سلسلة النتيجة

### getSourceFolder() {#getSourceFolder--}
```
public String getSourceFolder()
```


يعيد المجلد المصدر الذي يتم مقارنته.


**Returns:**
java.lang.String - مجلد المصدر

### getTargetFolder() {#getTargetFolder--}
```
public String getTargetFolder()
```


يعيد المجلد الهدف الذي يتم مقارنته.


**Returns:**
java.lang.String - مجلد الهدف

### selfComparisonCheck(Document source, Document target) {#selfComparisonCheck-com.groupdocs.comparison.Document-com.groupdocs.comparison.Document-}
```
public static void selfComparisonCheck(Document source, Document target)
```


فحص المقارنة الذاتية (e498c23). C# 7a7668c داخلي؛ تم إبقاؤه عامًا حتى تتمكن اختبارات core.common من الاستدعاء.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [Document](../../com.groupdocs.comparison/document) |  |
| target | [Document](../../com.groupdocs.comparison/document) |  |

### close() {#close--}
```
public void close()
```


يطلق الموارد.


