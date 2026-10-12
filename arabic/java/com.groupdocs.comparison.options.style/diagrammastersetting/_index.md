---
title: "DiagramMasterSetting"
second_title: "GroupDocs.Comparison لـ Java API Reference"
description: "يمثل إعدادات مقارنة المخطط الرئيسي."
type: docs
weight: 10
url: /ar/java/com.groupdocs.comparison.options.style/diagrammastersetting/
---
**Inheritance:**
java.lang.Object
```
public class DiagramMasterSetting
```

يمثل إعدادات مقارنة المخطط الرئيسي.


مثال على الاستخدام:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    final DiagramMasterSetting diagramMasterSetting = new DiagramMasterSetting();
    diagramMasterSetting.setMasterPath(masterFilePath);

    final CompareOptions compareOptions = new CompareOptions();
    compareOptions.setDiagramMasterSetting(diagramMasterSetting);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [DiagramMasterSetting()](#DiagramMasterSetting--) | ينشئ مثيلًا جديدًا من فئة DiagramMasterSetting. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [isUseSourceMaster()](#isUseSourceMaster--) | يحصل على علم يشير إلى ما إذا كان سيتم استخدام مسار المصدر الرئيسي. |
|
|  | [setUseSourceMaster(boolean value)](#setUseSourceMaster-boolean-) | يحصل على علم يشير إلى ما إذا كان يجب استخدام مسار المصدر الرئيسي. |
|
|  | [getMasterPath()](#getMasterPath--) | يحصل على مسار رئيسي سيُستخدم لتصميم المستندات. |
|
|  | [setMasterPath(String value)](#setMasterPath-java.lang.String-) | يضبط مسارًا رئيسيًا يجب استخدامه لتصميم المستندات. |
|
### DiagramMasterSetting() {#DiagramMasterSetting--}
```
public DiagramMasterSetting()
```


ينشئ مثيلًا جديدًا من فئة DiagramMasterSetting.


### isUseSourceMaster() {#isUseSourceMaster--}
```
public final boolean isUseSourceMaster()
```


يحصل على علم يشير إلى ما إذا كان سيتم استخدام مسار المصدر الرئيسي.


**Returns:**
boolean - true إذا كان مسار المصدر الرئيسي سيُعرض، وإلا false

### setUseSourceMaster(boolean value) {#setUseSourceMaster-boolean-}
```
public final void setUseSourceMaster(boolean value)
```


يحصل على علم يشير إلى ما إذا كان يجب استخدام مسار المصدر الرئيسي.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | boolean | true إذا كان يجب عرض مسار المصدر الرئيسي، وإلا false |
|

### getMasterPath() {#getMasterPath--}
```
public final String getMasterPath()
```


يحصل على مسار رئيسي سيُستخدم لتصميم المستندات. يُحتاج إلى MasterPath لإنشاء مستند نتيجة من مجموعة من الأشكال الافتراضية.


**Returns:**
java.lang.String - مسار المستند الرئيسي إذا تم تعيينه، وإلا مسار الرئيسي الافتراضي

### setMasterPath(String value) {#setMasterPath-java.lang.String-}
```
public final void setMasterPath(String value)
```


يضبط مسارًا رئيسيًا يجب استخدامه لتصميم المستندات. يُحتاج إلى MasterPath لإنشاء مستند نتيجة من مجموعة من الأشكال الافتراضية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | java.lang.String | مسار المستند الرئيسي إذا تم تعيينه، وإلا مسار الرئيسي الافتراضي |
|

