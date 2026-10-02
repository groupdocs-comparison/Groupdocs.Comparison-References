---
title: "ComparerSettings"
second_title: "GroupDocs.Comparison لـ Java API Reference"
description: "يحدد الإعدادات لتخصيص سلوك الفئة."
type: docs
weight: 11
url: /ar/java/com.groupdocs.comparison/comparersettings/
---
**Inheritance:**
java.lang.Object
```
public class ComparerSettings
```

يحدد الإعدادات لتخصيص سلوك الفئة [Comparer](../../com.groupdocs.comparison/comparer).


مثال على الاستخدام:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     final ComparerSettings comparerSettings = new ComparerSettings();
     comparerSettings.setLogger(new ConsoleLogger(false, false, true, true));

     comparer.compare(resultFile, comparerSettings);
 }
 
````


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [ComparerSettings()](#ComparerSettings--) | ينشئ نسخة جديدة من فئة ComparerSettings. |
|
|  | [ComparerSettings(ILogger logger)](#ComparerSettings-com.groupdocs.foundation.logging.ILogger-) | ينشئ نسخة جديدة من فئة ComparerSettings. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getLogger()](#getLogger--) | يحصل على تنفيذ المسجل المستخدم للتسجيل. |
|
|  | [setLogger(ILogger value)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | يضبط تنفيذ المسجل للتسجيل. |
|
### ComparerSettings() {#ComparerSettings--}
```
public ComparerSettings()
```


ينشئ نسخة جديدة من فئة ComparerSettings.


### ComparerSettings(ILogger logger) {#ComparerSettings-com.groupdocs.foundation.logging.ILogger-}
```
public ComparerSettings(ILogger logger)
```


ينشئ نسخة جديدة من فئة ComparerSettings.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | مسجل | com.groupdocs.foundation.logging.ILogger | المسجل الذي سيُستخدم |
|

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


يحصل على تنفيذ المسجل المستخدم للتسجيل.


**Returns:**
com.groupdocs.foundation.logging.ILogger - المسجل

### setLogger(ILogger value) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public final void setLogger(ILogger value)
```


يضبط تنفيذ المسجل للتسجيل.


استخدم com.groupdocs.foundation.logging.NullLogger#NULL_LOGGER.NULL_LOGGER لتعطيل التسجيل.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | com.groupdocs.foundation.logging.ILogger | تنفيذ المسجل لتعيينه |
|

