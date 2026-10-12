---
title: "CompareOptions"
second_title: "GroupDocs.Comparison لـ Java API Reference"
description: "يسمح بتكوين عملية مقارنة المستندات."
type: docs
weight: 11
url: /ar/java/com.groupdocs.comparison.options/compareoptions/
---
**Inheritance:**
java.lang.Object
```
public class CompareOptions
```

يسمح بتكوين عملية مقارنة المستندات.


مثال على الاستخدام:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     final StyleSettings styleSettings = new StyleSettings();
     styleSettings.setHighlightColor(Color.RED);
     styleSettings.setFontColor(Color.GREEN);
     styleSettings.setUnderline(true);

     CompareOptions compareOptions = new CompareOptions();
     compareOptions.setInsertedItemStyle(styleSettings);

     comparer.compare(resultFile, compareOptions);
 }
 
````


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [CompareOptions()](#CompareOptions--) | يُنشئ مثيلاً جديداً لفئة **CompareOptions**. |
|
|  | [CompareOptions(StyleSettings insertedItemStyle, StyleSettings deletedItemStyle, StyleSettings changedItemStyle)](#CompareOptions-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-) | يُنشئ مثيلاً جديداً لفئة **CompareOptions** مع إعدادات لأنماط مختلفة. |
|
## الحقول

| حقل | الوصف |
| --- | --- |
| [ignoreChangeSettings](#ignoreChangeSettings) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getIgnoreChangeSettings()](#getIgnoreChangeSettings--) | احصل على الإعدادات لتجاهل التغييرات بناءً على التشابه. |
|
|  | [setIgnoreChangeSettings(IgnoreChangeSensitivitySettings ignoreChangeSettings)](#setIgnoreChangeSettings-com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings-) | يضبط الإعدادات لتجاهل التغييرات بناءً على التشابه. |
|
|  | [getUserMasterPath()](#getUserMasterPath--) | يحصل على المسار إلى قالب الماستر الخاص بالمستخدم للرسوم البيانية. |
|
|  | [setUserMasterPath(String userMasterPath)](#setUserMasterPath-java.lang.String-) | يضبط المسار إلى قالب الماستر الخاص بالمستخدم للرسوم البيانية. |
|
|  | [getComparisonType()](#getComparisonType--) | يحصل على نوع المستندات المصدر والهدف ككائن [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) بحيث يعرف Comparison كيفية مقارنتها. |
|
|  | [setComparisonType(ComparisonType comparisonType)](#setComparisonType-com.groupdocs.comparison.options.enums.ComparisonType-) | يضبط نوع المستندات المصدر والهدف ككائن [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) بحيث يعرف Comparison كيفية مقارنتها. |
|
|  | [getPaperSize()](#getPaperSize--) | يحصل على حجم الورق في المستند الناتج ككائن [PaperSize](../../com.groupdocs.comparison.options.enums/papersize). |
|
|  | [setPaperSize(PaperSize value)](#setPaperSize-com.groupdocs.comparison.options.enums.PaperSize-) | يضبط حجم الورق في المستند الناتج ككائن [PaperSize](../../com.groupdocs.comparison.options.enums/papersize). |
|
|  | [getCalculateCoordinatesMode()](#getCalculateCoordinatesMode--) | يحصل على وضع حساب الإحداثيات ككائن [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration). |
|
|  | [setCalculateCoordinatesMode(CalculateCoordinatesModeEnumeration calculateCoordinatesMode)](#setCalculateCoordinatesMode-com.groupdocs.comparison.options.enums.CalculateCoordinatesModeEnumeration-) | يضبط وضع حساب الإحداثيات ككائن [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration). |
|
|  | [isShowDeletedContent()](#isShowDeletedContent--) | يحصل على علم يوضح ما إذا كان يجب إظهار المكونات المحذوفة في المستند الناتج أم لا. |
|
|  | [setShowDeletedContent(boolean value)](#setShowDeletedContent-boolean-) | يضبط علم يوضح ما إذا كان يجب إظهار المكونات المحذوفة في المستند الناتج أم لا. |
|
|  | [isShowInsertedContent()](#isShowInsertedContent--) | يحصل على علم يوضح ما إذا كان يجب عرض المكونات المدخلة في المستند الناتج أم لا. |
|
|  | [setShowInsertedContent(boolean value)](#setShowInsertedContent-boolean-) | يضبط علمًا يوضح ما إذا كان يجب عرض المكونات المدخلة في المستند الناتج أم لا. |
|
|  | [isGenerateSummaryPage()](#isGenerateSummaryPage--) | يحصل على علم يوضح ما إذا كان يجب إضافة صفحة ملخص مع إحصاءات التغييرات المكتشفة إلى المستند الناتج أم لا. |
|
|  | [setGenerateSummaryPage(boolean value)](#setGenerateSummaryPage-boolean-) | يضبط علمًا يوضح ما إذا كان يجب إضافة صفحة ملخص مع إحصاءات التغييرات المكتشفة إلى المستند الناتج أم لا. |
|
|  | [isExtendedSummaryPage()](#isExtendedSummaryPage--) | يحصل على علم يوضح ما إذا كان يجب إضافة معلومات مقارنة ملفات موسعة إلى صفحة الملخص أم لا. |
|
|  | [setExtendedSummaryPage(boolean value)](#setExtendedSummaryPage-boolean-) | يضبط علمًا يوضح ما إذا كان يجب إضافة معلومات مقارنة ملفات موسعة إلى صفحة الملخص أم لا. |
|
|  | [isShowOnlySummaryPage()](#isShowOnlySummaryPage--) | يحصل على علم يوضح ما إذا كان يجب ترك صفحة واحدة فقط تحتوي على إحصاءات التغييرات المكتشفة في المستند الناتج أم لا. |
|
|  | [setShowOnlySummaryPage(boolean value)](#setShowOnlySummaryPage-boolean-) | يضبط علمًا يوضح ما إذا كان يجب ترك صفحة واحدة فقط تحتوي على إحصاءات التغييرات المكتشفة في المستند الناتج أم لا. |
|
|  | [isDetectStyleChanges()](#isDetectStyleChanges--) | يحصل على علم يوضح ما إذا كان يجب اكتشاف تغييرات النمط أم لا. |
|
|  | [setDetectStyleChanges(boolean value)](#setDetectStyleChanges-boolean-) | يضبط علمًا يوضح ما إذا كان يجب اكتشاف تغييرات النمط أم لا. |
|
|  | [isMarkNestedContent()](#isMarkNestedContent--) | يحصل على علم يوضح ما إذا كان يجب وضع علامة على العناصر الفرعية للعناصر المحذوفة أو المدخلة كحذف أو إدخال. |
|
|  | [setMarkNestedContent(boolean value)](#setMarkNestedContent-boolean-) | يضبط علمًا يوضح ما إذا كان يجب وضع علامة على العناصر الفرعية للعناصر المحذوفة أو المدخلة كحذف أو إدخال. |
|
|  | [isCalculateCoordinates()](#isCalculateCoordinates--) | يحصل على علم يوضح ما إذا كان يجب حساب الإحداثيات للمكونات المتغيرة. |
|
|  | [setCalculateCoordinates(boolean value)](#setCalculateCoordinates-boolean-) | يضبط علمًا يوضح ما إذا كان يجب حساب الإحداثيات للمكونات المتغيرة. |
|
|  | [isHeaderFootersComparison()](#isHeaderFootersComparison--) | يحصل على علم يوضح ما إذا كان يجب مقارنة محتويات الرأس/التذييل. |
|
|  | [setHeaderFootersComparison(boolean value)](#setHeaderFootersComparison-boolean-) | يضبط علمًا يوضح ما إذا كان يجب مقارنة محتويات الرأس/التذييل. |
|
|  | [getDetalisationLevel()](#getDetalisationLevel--) | يحصل على مستوى تفصيل المقارنة ممثل كـ [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel). |
|
|  | [setDetalisationLevel(DetalisationLevel value)](#setDetalisationLevel-com.groupdocs.comparison.options.style.DetalisationLevel-) | يضبط مستوى تفصيل المقارنة ممثل كـ [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel). |
|
|  | [isMarkChangedContent()](#isMarkChangedContent--) | يحصل على علم يوضح ما إذا كانت إطارات الأشكال في معالجة النصوص وللمستطيلات في مستندات الصور ستُستخدم. |
|
|  | [setMarkChangedContent(boolean value)](#setMarkChangedContent-boolean-) | يضبط علمًا يوضح ما إذا كانت إطارات الأشكال في معالجة النصوص وللمستطيلات في مستندات الصور ستُستخدم. |
|
|  | [getInsertedItemStyle()](#getInsertedItemStyle--) | يحصل على إعدادات النمط التي سيتم تطبيقها على العناصر المدخلة. |
|
|  | [setInsertedItemStyle(StyleSettings value)](#setInsertedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-) | يضبط إعدادات النمط التي سيتم تطبيقها على العناصر المدخلة. |
|
|  | [getDeletedItemStyle()](#getDeletedItemStyle--) | يحصل على إعدادات النمط التي سيتم تطبيقها على العناصر المحذوفة. |
|
|  | [setDeletedItemStyle(StyleSettings value)](#setDeletedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-) | يضبط إعدادات النمط التي سيتم تطبيقها على العناصر المحذوفة. |
|
|  | [getChangedItemStyle()](#getChangedItemStyle--) | يحصل على إعدادات النمط التي سيتم تطبيقها على العناصر المتغيرة. |
|
|  | [setChangedItemStyle(StyleSettings value)](#setChangedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-) | يضبط إعدادات النمط التي سيتم تطبيقها على العناصر المتغيّرة. |
|
|  | [getSensitivityOfComparison()](#getSensitivityOfComparison--) | يحصل على حساسية المقارنة. |
|
|  | [setSensitivityOfComparison(int value)](#setSensitivityOfComparison-int-) | يضبط حساسية المقارنة. |
|
|  | [setSensitivityOfComparisonForTables(Integer value)](#setSensitivityOfComparisonForTables-java.lang.Integer-) | يضبط حساسية المقارنة للجداول. |
|
|  | [getSensitivityOfComparisonForTables()](#getSensitivityOfComparisonForTables--) | يحصل على حساسية المقارنة للجداول. |
|
|  | [setWordsSeparatorChars(char[] value)](#setWordsSeparatorChars-char---) | يضبط مصفوفة من الفواصل التي ستُستخدم لتقسيم النص إلى كلمات. |
|
|  | [getPasswordSaveOption()](#getPasswordSaveOption--) | يحصل على خيار حفظ كلمة المرور الممثّل بواسطة كائن [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption). |
|
|  | [setPasswordSaveOption(PasswordSaveOption value)](#setPasswordSaveOption-com.groupdocs.comparison.options.enums.PasswordSaveOption-) | يضبط خيار حفظ كلمة المرور الممثّل بواسطة كائن [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption). |
|
|  | [getOriginalSize()](#getOriginalSize--) | يحصل على الأحجام الأصلية للمستندات المقارنة الممثّلة بكائن [OriginalSize](../../com.groupdocs.comparison.options/originalsize). |
|
|  | [setOriginalSize(OriginalSize value)](#setOriginalSize-com.groupdocs.comparison.options.OriginalSize-) | يضبط الأحجام الأصلية للمستندات المقارنة الممثّلة بكائن [OriginalSize](../../com.groupdocs.comparison.options/originalsize). |
|
|  | [getDiagramMasterSetting()](#getDiagramMasterSetting--) | يحصل على إعداد الصفحة الرئيسية لمستندات المخطط الممثّل بكائن [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting). |
|
|  | [setDiagramMasterSetting(DiagramMasterSetting value)](#setDiagramMasterSetting-com.groupdocs.comparison.options.style.DiagramMasterSetting-) | يضبط إعداد الصفحة الرئيسية لمستندات المخطط الممثّل بكائن [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting). |
|
|  | [isDirectoryCompare()](#isDirectoryCompare--) | يرجع علامة تشير إلى ما إذا كان مقارنة الدليل مفعّلة. |
|
|  | [setDirectoryCompare(boolean directoryCompare)](#setDirectoryCompare-boolean-) | يضبط علامة تشير إلى ما إذا كان يجب تفعيل مقارنة الدليل. |
|
|  | [isShowOnlyChanged()](#isShowOnlyChanged--) | يرجع قيمة منطقية تشير إلى ما إذا كان يجب عرض العناصر المتغيّرة فقط. |
|
|  | [setShowOnlyChanged(boolean showOnlyChanged)](#setShowOnlyChanged-boolean-) | يضبط القيمة التي تشير إلى ما إذا كان يجب عرض العناصر المتغيّرة فقط. |
|
|  | [getFolderComparisonExtension()](#getFolderComparisonExtension--) | يحصل على تنسيق ملف مقارنة المجلد الناتج. |
|
|  | [setFolderComparisonExtension(FolderComparisonExtension folderComparisonExtension)](#setFolderComparisonExtension-com.groupdocs.comparison.options.enums.FolderComparisonExtension-) | يضبط تنسيق ملف مقارنة المجلد الناتج. |
|
### CompareOptions() {#CompareOptions--}
```
public CompareOptions()
```


يُنشئ مثيلاً جديداً لفئة **CompareOptions**.


### CompareOptions(StyleSettings insertedItemStyle, StyleSettings deletedItemStyle, StyleSettings changedItemStyle) {#CompareOptions-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-}
```
public CompareOptions(StyleSettings insertedItemStyle, StyleSettings deletedItemStyle, StyleSettings changedItemStyle)
```


يُنشئ مثيلاً جديداً لفئة **CompareOptions** مع إعدادات لأنماط مختلفة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | insertedItemStyle | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | إعدادات النمط للعناصر المُدرجة |
|
|  | deletedItemStyle | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | إعدادات النمط للعناصر المحذوفة |
|
|  | changedItemStyle | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | إعدادات النمط للعناصر ذات النمط المتغيّر |
|

### ignoreChangeSettings {#ignoreChangeSettings}
```
public IgnoreChangeSensitivitySettings ignoreChangeSettings
```


### getIgnoreChangeSettings() {#getIgnoreChangeSettings--}
```
public IgnoreChangeSensitivitySettings getIgnoreChangeSettings()
```


احصل على الإعدادات لتجاهل التغييرات بناءً على التشابه.


**Returns:**
com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings - إعدادات لتجاهل التغييرات.

### setIgnoreChangeSettings(IgnoreChangeSensitivitySettings ignoreChangeSettings) {#setIgnoreChangeSettings-com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings-}
```
public void setIgnoreChangeSettings(IgnoreChangeSensitivitySettings ignoreChangeSettings)
```


يضبط الإعدادات لتجاهل التغييرات بناءً على التشابه.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | ignoreChangeSettings | com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings | إعدادات لتجاهل التغييرات. |
|

### getUserMasterPath() {#getUserMasterPath--}
```
public String getUserMasterPath()
```


يحصل على المسار إلى قالب الماستر الخاص بالمستخدم للرسوم البيانية.


**Returns:**
java.lang.String - المسار إلى قالب المستخدم الرئيسي للمخططات.

### setUserMasterPath(String userMasterPath) {#setUserMasterPath-java.lang.String-}
```
public void setUserMasterPath(String userMasterPath)
```


يضبط المسار إلى قالب الماستر الخاص بالمستخدم للرسوم البيانية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | userMasterPath | java.lang.String | المسار إلى قالب المستخدم الرئيسي للمخططات. |
|

### getComparisonType() {#getComparisonType--}
```
public ComparisonType getComparisonType()
```


يحصل على نوع المستندات المصدر والهدف ككائن [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) بحيث يعرف Comparison كيفية مقارنتها.
عند تعيين هذا الخيار، سيتم حذف خيار [LoadOptions.getFileType()](../../com.groupdocs.comparison.options.load/loadoptions#getFileType--).


**Returns:**
[ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) - the type of source and target documents

### setComparisonType(ComparisonType comparisonType) {#setComparisonType-com.groupdocs.comparison.options.enums.ComparisonType-}
```
public void setComparisonType(ComparisonType comparisonType)
```


يضبط نوع المستندات المصدر والهدف ككائن [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) بحيث يعرف Comparison كيفية مقارنتها.
عند تعيين هذا الخيار، سيتم حذف خيار [LoadOptions.setFileType(FileType)](../../com.groupdocs.comparison.options.load/loadoptions#setFileType-FileType-).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | comparisonType | [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) | نوع المستندات المصدر والهدف |
|

### getPaperSize() {#getPaperSize--}
```
public final PaperSize getPaperSize()
```


يحصل على حجم الورق في المستند الناتج ككائن [PaperSize](../../com.groupdocs.comparison.options.enums/papersize).


**Returns:**
[PaperSize](../../com.groupdocs.comparison.options.enums/papersize) - the size of a paper in result document

### setPaperSize(PaperSize value) {#setPaperSize-com.groupdocs.comparison.options.enums.PaperSize-}
```
public final void setPaperSize(PaperSize value)
```


يضبط حجم الورق في المستند الناتج ككائن [PaperSize](../../com.groupdocs.comparison.options.enums/papersize).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [PaperSize](../../com.groupdocs.comparison.options.enums/papersize) | حجم الورقة في المستند الناتج |
|

### getCalculateCoordinatesMode() {#getCalculateCoordinatesMode--}
```
public CalculateCoordinatesModeEnumeration getCalculateCoordinatesMode()
```


يحصل على وضع حساب الإحداثيات ككائن [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration).


**Returns:**
[CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) - the calculate coordinates mode

### setCalculateCoordinatesMode(CalculateCoordinatesModeEnumeration calculateCoordinatesMode) {#setCalculateCoordinatesMode-com.groupdocs.comparison.options.enums.CalculateCoordinatesModeEnumeration-}
```
public void setCalculateCoordinatesMode(CalculateCoordinatesModeEnumeration calculateCoordinatesMode)
```


يضبط وضع حساب الإحداثيات ككائن [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | calculateCoordinatesMode | [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) | وضع حساب الإحداثيات |
|

### isShowDeletedContent() {#isShowDeletedContent--}
```
public final boolean isShowDeletedContent()
```


يحصل على علم يوضح ما إذا كان يجب إظهار المكونات المحذوفة في المستند الناتج أم لا.


**Returns:**
boolean - true إذا كان سيتم إظهار المكونات المحذوفة في المستند الناتج، وإلا false

### setShowDeletedContent(boolean value) {#setShowDeletedContent-boolean-}
```
public final void setShowDeletedContent(boolean value)
```


يضبط علم يوضح ما إذا كان يجب إظهار المكونات المحذوفة في المستند الناتج أم لا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | boolean | true إذا كان يجب إظهار المكونات المحذوفة في المستند الناتج، وإلا false |
|

### isShowInsertedContent() {#isShowInsertedContent--}
```
public final boolean isShowInsertedContent()
```


يحصل على علم يوضح ما إذا كان يجب عرض المكونات المدخلة في المستند الناتج أم لا.


**Returns:**
boolean - true إذا كان يجب إظهار المكونات المدخلة في المستند الناتج، وإلا false

### setShowInsertedContent(boolean value) {#setShowInsertedContent-boolean-}
```
public final void setShowInsertedContent(boolean value)
```


يضبط علمًا يوضح ما إذا كان يجب عرض المكونات المدخلة في المستند الناتج أم لا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | boolean | true إذا كان يجب إظهار المكونات المدخلة في المستند الناتج، وإلا false |
|

### isGenerateSummaryPage() {#isGenerateSummaryPage--}
```
public final boolean isGenerateSummaryPage()
```


يحصل على علم يوضح ما إذا كان يجب إضافة صفحة ملخص مع إحصاءات التغييرات المكتشفة إلى المستند الناتج أم لا.


**Returns:**
boolean - true إذا سيتم إضافة صفحة الملخص، وإلا false

### setGenerateSummaryPage(boolean value) {#setGenerateSummaryPage-boolean-}
```
public final void setGenerateSummaryPage(boolean value)
```


يضبط علمًا يوضح ما إذا كان يجب إضافة صفحة ملخص مع إحصاءات التغييرات المكتشفة إلى المستند الناتج أم لا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | boolean | true إذا يجب إضافة صفحة الملخص، وإلا false |
|

### isExtendedSummaryPage() {#isExtendedSummaryPage--}
```
public boolean isExtendedSummaryPage()
```


يحصل على علم يوضح ما إذا كان يجب إضافة معلومات مقارنة ملفات موسعة إلى صفحة الملخص أم لا.


**Returns:**
boolean - true إذا سيتم إضافة معلومات مقارنة الملفات الموسعة إلى صفحة الملخص، وإلا false

### setExtendedSummaryPage(boolean value) {#setExtendedSummaryPage-boolean-}
```
public void setExtendedSummaryPage(boolean value)
```


يضبط علمًا يوضح ما إذا كان يجب إضافة معلومات مقارنة ملفات موسعة إلى صفحة الملخص أم لا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | boolean | true إذا يجب إضافة معلومات مقارنة الملفات الموسعة إلى صفحة الملخص، وإلا false |
|

### isShowOnlySummaryPage() {#isShowOnlySummaryPage--}
```
public boolean isShowOnlySummaryPage()
```


يحصل على علم يوضح ما إذا كان يجب ترك صفحة واحدة فقط تحتوي على إحصاءات التغييرات المكتشفة في المستند الناتج أم لا.


**Returns:**
boolean - true إذا سيبقى في المستند الناتج صفحة واحدة فقط تحتوي على إحصائيات التغييرات المكتشفة، وإلا false

### setShowOnlySummaryPage(boolean value) {#setShowOnlySummaryPage-boolean-}
```
public void setShowOnlySummaryPage(boolean value)
```


يضبط علمًا يوضح ما إذا كان يجب ترك صفحة واحدة فقط تحتوي على إحصاءات التغييرات المكتشفة في المستند الناتج أم لا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | boolean | true إذا يجب أن يبقى في المستند الناتج صفحة واحدة فقط تحتوي على إحصائيات التغييرات المكتشفة، وإلا false |
|

### isDetectStyleChanges() {#isDetectStyleChanges--}
```
public final boolean isDetectStyleChanges()
```


يحصل على علم يوضح ما إذا كان يجب اكتشاف تغييرات النمط أم لا.


**Returns:**
boolean - true إذا سيتم اكتشاف تغييرات النمط، وإلا false

### setDetectStyleChanges(boolean value) {#setDetectStyleChanges-boolean-}
```
public final void setDetectStyleChanges(boolean value)
```


يضبط علمًا يوضح ما إذا كان يجب اكتشاف تغييرات النمط أم لا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | boolean | true إذا يجب اكتشاف تغييرات النمط، وإلا false |
|

### isMarkNestedContent() {#isMarkNestedContent--}
```
public final boolean isMarkNestedContent()
```


يحصل على علم يوضح ما إذا كان يجب وضع علامة على العناصر الفرعية للعناصر المحذوفة أو المدخلة كحذف أو إدخال.


**Returns:**
boolean - true إذا سيتم وضع علامة على عناصر الأطفال للعناصر المحذوفة أو المدخلة كـ محذوفة أو مدخلة، وإلا false

### setMarkNestedContent(boolean value) {#setMarkNestedContent-boolean-}
```
public final void setMarkNestedContent(boolean value)
```


يضبط علمًا يوضح ما إذا كان يجب وضع علامة على العناصر الفرعية للعناصر المحذوفة أو المدخلة كحذف أو إدخال.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | boolean | true إذا يجب وضع علامة على عناصر الأطفال للعناصر المحذوفة أو المدخلة كـ محذوفة أو مدخلة، وإلا false |
|

### isCalculateCoordinates() {#isCalculateCoordinates--}
```
public final boolean isCalculateCoordinates()
```


يحصل على علم يوضح ما إذا كان يجب حساب الإحداثيات للمكونات المتغيرة.


**Returns:**
boolean - true إذا سيتم حساب إحداثيات المكونات المتغيرة، وإلا false

### setCalculateCoordinates(boolean value) {#setCalculateCoordinates-boolean-}
```
public final void setCalculateCoordinates(boolean value)
```


يضبط علمًا يوضح ما إذا كان يجب حساب الإحداثيات للمكونات المتغيرة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | boolean | true إذا يجب حساب إحداثيات المكونات المتغيرة، وإلا false |
|

### isHeaderFootersComparison() {#isHeaderFootersComparison--}
```
public final boolean isHeaderFootersComparison()
```


يحصل على علم يوضح ما إذا كان يجب مقارنة محتويات الرأس/التذييل.


**Returns:**
boolean - true إذا سيتم مقارنة محتويات الرأس/التذييل، وإلا false

### setHeaderFootersComparison(boolean value) {#setHeaderFootersComparison-boolean-}
```
public final void setHeaderFootersComparison(boolean value)
```


يضبط علمًا يوضح ما إذا كان يجب مقارنة محتويات الرأس/التذييل.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | boolean | true إذا يجب مقارنة محتويات الرأس/التذييل، وإلا false |
|

### getDetalisationLevel() {#getDetalisationLevel--}
```
public final DetalisationLevel getDetalisationLevel()
```


يحصل على مستوى تفصيل المقارنة ممثل كـ [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel).
القيمة الافتراضية هي [DetalisationLevel.LOW](../../com.groupdocs.comparison.options.style/detalisationlevel#LOW).


**Returns:**
[DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) - the level of comparison detalization

### setDetalisationLevel(DetalisationLevel value) {#setDetalisationLevel-com.groupdocs.comparison.options.style.DetalisationLevel-}
```
public final void setDetalisationLevel(DetalisationLevel value)
```


يضبط مستوى تفصيل المقارنة ممثل كـ [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel).
القيمة الافتراضية هي [DetalisationLevel.LOW](../../com.groupdocs.comparison.options.style/detalisationlevel#LOW)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) | مستوى تفصيل المقارنة |
|

### isMarkChangedContent() {#isMarkChangedContent--}
```
public final boolean isMarkChangedContent()
```


يحصل على علم يوضح ما إذا كانت إطارات الأشكال في معالجة النصوص وللمستطيلات في مستندات الصور ستُستخدم.


**Returns:**
منطقي - true إذا سيتم استخدام الإطارات، وإلا false

### setMarkChangedContent(boolean value) {#setMarkChangedContent-boolean-}
```
public final void setMarkChangedContent(boolean value)
```


يضبط علمًا يوضح ما إذا كانت إطارات الأشكال في معالجة النصوص وللمستطيلات في مستندات الصور ستُستخدم.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | boolean | true إذا يجب استخدام الإطارات، وإلا false |
|

### getInsertedItemStyle() {#getInsertedItemStyle--}
```
public final StyleSettings getInsertedItemStyle()
```


يحصل على إعدادات النمط التي سيتم تطبيقها على العناصر المدخلة.


**Returns:**
[StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) - style settings of inserted items

### setInsertedItemStyle(StyleSettings value) {#setInsertedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-}
```
public final void setInsertedItemStyle(StyleSettings value)
```


يضبط إعدادات النمط التي سيتم تطبيقها على العناصر المدخلة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | إعدادات النمط للعناصر المُدرجة |
|

### getDeletedItemStyle() {#getDeletedItemStyle--}
```
public final StyleSettings getDeletedItemStyle()
```


يحصل على إعدادات النمط التي سيتم تطبيقها على العناصر المحذوفة.


**Returns:**
[StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) - style settings of deleted items

### setDeletedItemStyle(StyleSettings value) {#setDeletedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-}
```
public final void setDeletedItemStyle(StyleSettings value)
```


يضبط إعدادات النمط التي سيتم تطبيقها على العناصر المحذوفة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | إعدادات النمط للعناصر المحذوفة |
|

### getChangedItemStyle() {#getChangedItemStyle--}
```
public final StyleSettings getChangedItemStyle()
```


يحصل على إعدادات النمط التي سيتم تطبيقها على العناصر المتغيرة.


**Returns:**
[StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) - style settings of changed items

### setChangedItemStyle(StyleSettings value) {#setChangedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-}
```
public final void setChangedItemStyle(StyleSettings value)
```


يضبط إعدادات النمط التي سيتم تطبيقها على العناصر المتغيّرة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | إعدادات النمط للعناصر المتغيّرة |
|

### getSensitivityOfComparison() {#getSensitivityOfComparison--}
```
public final int getSensitivityOfComparison()
```


يحصل على حساسية المقارنة.
النسبة المئوية للعناصر المحذوفة والمُدرجة لكائنين مُقارنَين بالنسبة إلى جميع عناصر هذه الكائنات.

* If this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Returns:**
int - حساسية المقارنة

### setSensitivityOfComparison(int value) {#setSensitivityOfComparison-int-}
```
public final void setSensitivityOfComparison(int value)
```


يضبط حساسية المقارنة.
النسبة المئوية للعناصر المحذوفة والمُدرجة لكائنين مُقارنَين بالنسبة إلى جميع عناصر هذه الكائنات.

* If this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | int | حساسية المقارنة |
|

### setSensitivityOfComparisonForTables(Integer value) {#setSensitivityOfComparisonForTables-java.lang.Integer-}
```
public void setSensitivityOfComparisonForTables(Integer value)
```


يضبط حساسية المقارنة للجداول.
إذا كانت القيمة null، يتم استخدام SensitivityOfComparison بدلاً منها. النسبة المئوية للعناصر المحذوفة والمُدرجة لكائنين مُقارنَين بالنسبة إلى جميع عناصر هذه الكائنات.

* if this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs, if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | java.lang.Integer | حساسية المقارنة للجداول |
|

### getSensitivityOfComparisonForTables() {#getSensitivityOfComparisonForTables--}
```
public final Integer getSensitivityOfComparisonForTables()
```


يحصل على حساسية المقارنة للجداول.
إذا كانت القيمة null، يتم استخدام SensitivityOfComparison بدلاً منها. النسبة المئوية للعناصر المحذوفة والمُدرجة لكائنين مُقارنَين بالنسبة إلى جميع عناصر هذه الكائنات.

* if this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs, if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Returns:**
java.lang.Integer - حساسية المقارنة للجداول

### setWordsSeparatorChars(char[] value) {#setWordsSeparatorChars-char---}
```
public final void setWordsSeparatorChars(char[] value)
```


يضبط مصفوفة من الفواصل التي ستُستخدم لتقسيم النص إلى كلمات.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | char[] | المصفوفة التي تحتوي على الفواصل لتقسيم النص إلى كلمات |
|

### getPasswordSaveOption() {#getPasswordSaveOption--}
```
public final PasswordSaveOption getPasswordSaveOption()
```


يحصل على خيار حفظ كلمة المرور الممثّل بواسطة كائن [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption).


**Returns:**
[PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) - the password save option

### setPasswordSaveOption(PasswordSaveOption value) {#setPasswordSaveOption-com.groupdocs.comparison.options.enums.PasswordSaveOption-}
```
public final void setPasswordSaveOption(PasswordSaveOption value)
```


يضبط خيار حفظ كلمة المرور الممثّل بواسطة كائن [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) | خيار حفظ كلمة المرور |
|

### getOriginalSize() {#getOriginalSize--}
```
public final OriginalSize getOriginalSize()
```


يحصل على الأحجام الأصلية للمستندات المقارنة الممثّلة بكائن [OriginalSize](../../com.groupdocs.comparison.options/originalsize).


**Returns:**
[OriginalSize](../../com.groupdocs.comparison.options/originalsize) - the original size of documents

### setOriginalSize(OriginalSize value) {#setOriginalSize-com.groupdocs.comparison.options.OriginalSize-}
```
public final void setOriginalSize(OriginalSize value)
```


يضبط الأحجام الأصلية للمستندات المقارنة الممثّلة بكائن [OriginalSize](../../com.groupdocs.comparison.options/originalsize).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [OriginalSize](../../com.groupdocs.comparison.options/originalsize) | الحجم الأصلي للمستندات |
|

### getDiagramMasterSetting() {#getDiagramMasterSetting--}
```
public final DiagramMasterSetting getDiagramMasterSetting()
```


يحصل على إعداد الصفحة الرئيسية لمستندات المخطط الممثّل بكائن [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting).


**Returns:**
[DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) - the diagram master page setting

### setDiagramMasterSetting(DiagramMasterSetting value) {#setDiagramMasterSetting-com.groupdocs.comparison.options.style.DiagramMasterSetting-}
```
public final void setDiagramMasterSetting(DiagramMasterSetting value)
```


يضبط إعداد الصفحة الرئيسية لمستندات المخطط الممثّل بكائن [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) | إعداد الصفحة الرئيسية للمخطط |
|

### isDirectoryCompare() {#isDirectoryCompare--}
```
public boolean isDirectoryCompare()
```


يرجع علامة تشير إلى ما إذا كان مقارنة الدليل مفعّلة.


**Returns:**
منطقي - true إذا تم تمكين مقارنة الدليل، وإلا false

### setDirectoryCompare(boolean directoryCompare) {#setDirectoryCompare-boolean-}
```
public void setDirectoryCompare(boolean directoryCompare)
```


يضبط علامة تشير إلى ما إذا كان يجب تفعيل مقارنة الدليل.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | directoryCompare | boolean | true إذا يجب تمكين مقارنة الدليل، وإلا false |
|

### isShowOnlyChanged() {#isShowOnlyChanged--}
```
public boolean isShowOnlyChanged()
```


يرجع قيمة منطقية تشير إلى ما إذا كان يجب عرض العناصر المتغيّرة فقط.


**Returns:**
منطقي - true إذا يجب عرض العناصر المتغيّرة فقط، وإلا false

### setShowOnlyChanged(boolean showOnlyChanged) {#setShowOnlyChanged-boolean-}
```
public void setShowOnlyChanged(boolean showOnlyChanged)
```


يضبط القيمة التي تشير إلى ما إذا كان يجب عرض العناصر المتغيّرة فقط.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | showOnlyChanged | boolean | القيمة المنطقية التي تشير إلى ما إذا كان يجب عرض العناصر المتغيّرة فقط |
|

### getFolderComparisonExtension() {#getFolderComparisonExtension--}
```
public FolderComparisonExtension getFolderComparisonExtension()
```


يحصل على تنسيق ملف مقارنة المجلد الناتج.


**Returns:**
com.groupdocs.comparison.options.enums.FolderComparisonExtension - الـFolderComparisonExtension التي تمثل تنسيق ملف مقارنة المجلد الناتج

### setFolderComparisonExtension(FolderComparisonExtension folderComparisonExtension) {#setFolderComparisonExtension-com.groupdocs.comparison.options.enums.FolderComparisonExtension-}
```
public void setFolderComparisonExtension(FolderComparisonExtension folderComparisonExtension)
```


يضبط تنسيق ملف مقارنة المجلد الناتج.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | folderComparisonExtension | com.groupdocs.comparison.options.enums.FolderComparisonExtension | الـFolderComparisonExtension التي تمثل تنسيق ملف مقارنة المجلد الناتج |
|

