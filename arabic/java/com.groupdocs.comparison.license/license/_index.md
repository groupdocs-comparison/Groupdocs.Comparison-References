---
title: "رخصة"
second_title: "GroupDocs.Comparison لـ Java API Reference"
description: "توفر فئة License طرقًا لتعيين وتطبيق التراخيص لـ GroupDocs.Comparison."
type: docs
weight: 10
url: /ar/java/com.groupdocs.comparison.license/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

توفر فئة License طرقًا لتعيين وتطبيق التراخيص لـ GroupDocs.Comparison.


يسمح لك بتمكين أو تعطيل ميزات محددة من المكتبة بناءً على الرخصة المطبقة.

* More about GroupDocs.Comparison licensing: [Evaluation Limitations and Licensing](../https://docs.groupdocs.com/display/comparisonjava/Evaluation+Limitations+and+Licensing+of+GroupDocs.Comparison)


مثال على الاستخدام:

````

 final License license = new License();
 license.setLicense("GroupDocs.License.lic");
 
````


## المنشئات

| منشئ | الوصف |
| --- | --- |
| [License()](#License--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [isValidLicense()](#isValidLicense--) | يحصل على قيمة تشير إلى ما إذا تم تعيين الرخصة أم لا. |
|
|  | [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | يضبط رخصة للمقارنة باستخدام تدفق الإدخال. |
|
|  | [setLicense(Path licensePath)](#setLicense-java.nio.file.Path-) | يضبط رخصة للمقارنة باستخدام مسار ملف الرخصة. |
|
|  | [setLicense(String licensePath)](#setLicense-java.lang.String-) | يضبط رخصة للمقارنة باستخدام مسار ملف الرخصة. |
|
### License() {#License--}
```
public License()
```


### isValidLicense() {#isValidLicense--}
```
public static boolean isValidLicense()
```


يحصل على قيمة تشير إلى ما إذا تم تعيين الرخصة أم لا.


**Returns:**
منطقي - true إذا تم تعيين الرخصة بنجاح، وإلا false

### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


يضبط رخصة للمقارنة باستخدام تدفق الإدخال.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | licenseStream | java.io.InputStream | تدفق الرخصة، null يزيل تعيين الرخصة. |
|

### setLicense(Path licensePath) {#setLicense-java.nio.file.Path-}
```
public final void setLicense(Path licensePath)
```


يضبط رخصة للمقارنة باستخدام مسار ملف الرخصة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | licensePath | java.nio.file.Path | مسار ملف الرخصة |
|

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


يضبط رخصة للمقارنة باستخدام مسار ملف الرخصة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | licensePath | java.lang.String | مسار ملف الرخصة |
|

