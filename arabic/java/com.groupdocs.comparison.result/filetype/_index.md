---
title: "FileType"
second_title: "GroupDocs.Comparison لـ Java API Reference"
description: "يمثل تعداد FileType نوع الملف المستخدم في عملية مقارنة المستندات."
type: docs
weight: 16
url: /ar/java/com.groupdocs.comparison.result/filetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public enum FileType extends Enum<FileType> implements System.IEquatable<FileType>
```

يمثل تعداد FileType نوع الملف المستخدم في عملية مقارنة المستندات.


يحدد أنواع ملفات مختلفة مثل مستندات Word وملفات PDF وغيرها.
يوفر طرقًا للحصول على قائمة بجميع أنواع الملفات المدعومة من قبل GroupDocs.Comparison، واكتشاف نوع الملف حسب الامتداد، إلخ.
استخدم هذا التعداد لتحديد نوع الملف عند العمل مع مكتبة GroupDocs.Comparison.

* Learn more about file formats supported by GroupDocs.Comparison: [Full list of supported document formats](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* Learn more about getting supported file types in Java: [How to get supported file formats in Java](../https://docs.groupdocs.com/display/comparisonjava/Get+supported+file+formats)


مثال على الاستخدام:

````

  // Set the file type to Word document
  final FileType fileType = FileType.DOCX;
  // Perform comparison using the specified file type
  final LoadOptions loadOptions = new LoadOptions(fileType);
  try (Comparer comparer = new Comparer(sourceFile, loadOptions)) {
      comparer.add(targetFile);

      comparer.compare(resultFile, compareOptions);
 }
 
````


## الحقول

| حقل | الوصف |
| --- | --- |
|  | [UNKNOWN](#UNKNOWN) | نوع غير معروف |
|
|  | [AS](#AS) | تنسيق لغة البرمجة ActionScript |
|
|  | [AS3](#AS3) | تنسيق لغة البرمجة ActionScript |
|
|  | [ASM](#ASM) | تنسيق لغة البرمجة Assembler |
|
|  | [BAT](#BAT) | ملف سكريبت في DOS وOS/2 وMicrosoft Windows |
|
|  | [CMD](#CMD) | ملف سكريبت في DOS وOS/2 وMicrosoft Windows |
|
|  | [C](#C) | تنسيق لغة البرمجة المستندة إلى C |
|
|  | [H](#H) | ملفات الرأس المستندة إلى C تحتوي على تعريفات الدوال والمتغيرات |
|
|  | [PDF](#PDF) | تنسيق Adobe Portable Document |
|
|  | [DOC](#DOC) | مستند Microsoft Word 97-2003 |
|
|  | [DOCM](#DOCM) | مستند Microsoft Word مع تمكين الماكرو |
|
|  | [DOCX](#DOCX) | مستند Microsoft Word |
|
|  | [DOT](#DOT) | قالب Microsoft Word 97-2003 |
|
|  | [DOTM](#DOTM) | قالب Microsoft Word مع تمكين الماكرو |
|
|  | [DOTX](#DOTX) | قالب Microsoft Word |
|
|  | [XLS](#XLS) | ورقة عمل Microsoft Excel 97-2003 |
|
|  | [XLT](#XLT) | قالب Microsoft Excel |
|
|  | [XLSX](#XLSX) | ورقة عمل Microsoft Excel |
|
|  | [XLTM](#XLTM) | قالب Microsoft Excel مع تمكين الماكرو |
|
|  | [XLSB](#XLSB) | Microsoft Excel ورقة عمل ثنائية |
|
|  | [XLSM](#XLSM) | Microsoft Excel ورقة عمل مدعومة بالماكرو |
|
|  | [POT](#POT) | قالب Microsoft PowerPoint |
|
|  | [POTX](#POTX) | قالب Microsoft PowerPoint |
|
|  | [POTM](#POTM) | قالب Microsoft PowerPoint مع دعم الماكرو |
|
|  | [PPS](#PPS) | عرض شرائح Microsoft PowerPoint 97-2003 |
|
|  | [PPSX](#PPSX) | عرض شرائح Microsoft PowerPoint |
|
|  | [PPTX](#PPTX) | عرض تقديمي Microsoft PowerPoint |
|
|  | [PPT](#PPT) | عرض تقديمي Microsoft PowerPoint 97-2003 |
|
|  | [PPTM](#PPTM) | عرض تقديمي Microsoft PowerPoint مدعوم بالماكرو |
|
|  | [PPSM](#PPSM) | عرض شرائح تقديمي Microsoft PowerPoint مدعوم بالماكرو |
|
|  | [VSDX](#VSDX) | رسم Microsoft Visio |
|
|  | [VSD](#VSD) | رسم Microsoft Visio 2003-2010 |
|
|  | [VSS](#VSS) | قالب Microsoft Visio 2003-2010 |
|
|  | [VST](#VST) | قالب Microsoft Visio 2003-2010 |
|
|  | [VDX](#VDX) | رسم XML Microsoft Visio 2003-2010 |
|
|  | [ONE](#ONE) | مستند Microsoft OneNote |
|
|  | [ODT](#ODT) | نص OpenDocument |
|
|  | [ODP](#ODP) | عرض تقديمي OpenDocument |
|
|  | [OTP](#OTP) | قالب عرض تقديمي OpenDocument |
|
|  | [ODS](#ODS) | جدول بيانات OpenDocument |
|
|  | [OTT](#OTT) | قالب نص OpenDocument |
|
|  | [RTF](#RTF) | مستند نص غني |
|
|  | [TXT](#TXT) | مستند نص عادي |
|
|  | [CSV](#CSV) | ملف قيم مفصولة بفواصل |
|
|  | [HTML](#HTML) | لغة توصيف النص الفائق |
|
|  | [MHTML](#MHTML) | MIME HTML |
|
|  | [MOBI](#MOBI) | تنسيق الكتب الإلكترونية Mobipocket |
|
|  | [DCM](#DCM) | التصوير الرقمي والاتصالات في الطب |
|
|  | [DJVU](#DJVU) | تنسيق Deja Vu |
|
|  | [DWG](#DWG) | تنسيقات بيانات التصميم Autodesk |
|
|  | [DXF](#DXF) | تبادل رسومات AutoCAD |
|
|  | [BMP](#BMP) | صورة Bitmap |
|
|  | [GIF](#GIF) | تنسيق تبادل الرسومات |
|
|  | [JPEG](#JPEG) | مجموعة الخبراء المشتركة للتصوير الفوتوغرافي |
|
|  | [JPG](#JPG) | مجموعة الخبراء المشتركة للتصوير الفوتوغرافي |
|
|  | [PNG](#PNG) | رسومات الشبكة المحمولة |
|
|  | [SVG](#SVG) | رسومات المتجهات العددية |
|
|  | [EML](#EML) | رسالة بريد إلكتروني |
|
|  | [EMLX](#EMLX) | ملف بريد إلكتروني Apple Mail |
|
|  | [MSG](#MSG) | رسالة بريد إلكتروني Microsoft Outlook |
|
|  | [CAD](#CAD) | تنسيق ملف CAD |
|
|  | [CPP](#CPP) | تنسيق لغة البرمجة المستندة إلى C |
|
|  | [CC](#CC) | تنسيق لغة البرمجة المستندة إلى C |
|
|  | [CXX](#CXX) | تنسيق لغة البرمجة المستندة إلى C |
|
|  | [HXX](#HXX) | ملفات الرأس المكتوبة بلغة البرمجة C++ |
|
|  | [HH](#HH) | معلومات الرأس المشار إليها بواسطة ملف شفرة مصدر C++ |
|
|  | [HPP](#HPP) | ملفات الرأس المكتوبة بلغة البرمجة C++ |
|
|  | [CMAKE](#CMAKE) | أداة لإدارة عملية بناء البرمجيات |
|
|  | [CS](#CS) | تنسيق لغة البرمجة CSharp |
|
|  | [CSX](#CSX) | تنسيق ملف سكريبت CSharp |
|
|  | [CAKE](#CAKE) | تنسيق نظام أتمتة بناء متعدد المنصات CSharp |
|
|  | [DIFF](#DIFF) | تنسيق أداة مقارنة البيانات |
|
|  | [PATCH](#PATCH) | تنسيق قائمة الاختلافات |
|
|  | [REJ](#REJ) | تنسيق الملفات المرفوضة |
|
|  | [GROOVY](#GROOVY) | ملف شفرة المصدر مكتوب بصيغة Groovy |
|
|  | [GVY](#GVY) | ملف شفرة المصدر مكتوب بصيغة Groovy |
|
|  | [GRADLE](#GRADLE) | صيغة نظام أتمتة البناء |
|
|  | [HAML](#HAML) | لغة توصيف لإنشاء HTML مبسط |
|
|  | [JS](#JS) | صيغة لغة برمجة JavaScript |
|
|  | [ES6](#ES6) | صيغة لغة البرمجة النصية المعيارية JavaScript |
|
|  | [MJS](#MJS) | امتداد لملفات وحدات EcmaScript (ES) |
|
|  | [PAC](#PAC) | ملف تكوين الوكيل التلقائي لتنسيق دالة JavaScript |
|
|  | [JSON](#JSON) | صيغة خفيفة لتخزين ونقل البيانات |
|
|  | [BOWERRC](#BOWERRC) | ملف تكوين للتحكم في الحزم على جانب الخادم |
|
|  | [JSHINTRC](#JSHINTRC) | أداة جودة شفرة JavaScript |
|
|  | [JSCSRC](#JSCSRC) | صيغة ملف تكوين JavaScript |
|
|  | [WEBMANIFEST](#WEBMANIFEST) | ملف البيان يتضمن معلومات عن التطبيق |
|
|  | [JSMAP](#JSMAP) | ملف JSON يحتوي على معلومات حول كيفية ترجمة الشفرة إلى شفرة المصدر |
|
|  | [HAR](#HAR) | صيغة أرشيف HTTP |
|
|  | [JAVA](#JAVA) | صيغة لغة برمجة Java |
|
|  | [LESS](#LESS) | صيغة لغة ورقة الأنماط المعالجة مسبقًا الديناميكية |
|
|  | [LOG](#LOG) | التسجيل يحافظ على سجل الأحداث والعمليات والرسائل والاتصالات |
|
|  | [MAKE](#MAKE) | Makefile هو ملف يحتوي على مجموعة من التوجيهات المستخدمة بواسطة أداة أتمتة بناء make لتوليد هدف/غاية |
|
|  | [MK](#MK) | Makefile هو ملف يحتوي على مجموعة من التوجيهات المستخدمة بواسطة أداة أتمتة بناء make لتوليد هدف/غاية |
|
|  | [MD](#MD) | صيغة لغة Markdown |
|
|  | [MKD](#MKD) | صيغة لغة Markdown |
|
|  | [MDWN](#MDWN) | صيغة لغة Markdown |
|
|  | [MDOWN](#MDOWN) | صيغة لغة Markdown |
|
|  | [MARKDOWN](#MARKDOWN) | صيغة لغة Markdown |
|
|  | [MARKDN](#MARKDN) | صيغة لغة Markdown |
|
|  | [MDTXT](#MDTXT) | صيغة لغة Markdown |
|
|  | [MDTEXT](#MDTEXT) | صيغة لغة Markdown |
|
|  | [ML](#ML) | صيغة لغة برمجة Caml |
|
|  | [MLI](#MLI) | صيغة لغة برمجة Caml |
|
|  | [OBJC](#OBJC) | صيغة لغة برمجة Objective-C |
|
|  | [OBJCP](#OBJCP) | صيغة لغة برمجة Objective-C++ |
|
|  | [PHP](#PHP) | صيغة لغة برمجة PHP |
|
|  | [PHP4](#PHP4) | صيغة لغة برمجة PHP |
|
|  | [PHP5](#PHP5) | صيغة لغة برمجة PHP |
|
|  | [PHTML](#PHTML) | صيغة الامتداد القياسي لبرامج PHP 2 |
|
|  | [CTP](#CTP) | صيغة قالب CakePHP |
|
|  | [PL](#PL) | تنسيق لغة البرمجة Perl |
|
|  | [PM](#PM) | تنسيق وحدة Perl |
|
|  | [POD](#POD) | تنسيق لغة الترميز الخفيفة Perl |
|
|  | [T](#T) | تنسيق ملف اختبار Perl |
|
|  | [PSGI](#PSGI) | واجهة بين خوادم الويب وتطبيقات الويب والأطر المكتوبة بلغة البرمجة Perl |
|
|  | [P6](#P6) | تنسيق لغة البرمجة Perl |
|
|  | [PL6](#PL6) | تنسيق لغة البرمجة Perl |
|
|  | [PM6](#PM6) | تنسيق وحدة Perl |
|
|  | [NQP](#NQP) | لغة وسيطة تُستخدم لبناء مترجم Rakuto Perl 6 |
|
|  | [PROP](#PROP) | تنسيق ملف الخصائص |
|
|  | [CFG](#CFG) | ملف التكوين يُستخدم لتخزين الإعدادات |
|
|  | [CONF](#CONF) | ملف التكوين يُستخدم على الأنظمة القائمة على Unix و Linux |
|
|  | [DIR](#DIR) | الدليل هو موقع لتخزين الملفات على الكمبيوتر |
|
|  | [PY](#PY) | تنسيق لغة البرمجة Python |
|
|  | [RPY](#RPY) | محرك ملفات مبني على Python لإنشاء وتشغيل الألعاب |
|
|  | [PYW](#PYW) | ملفات تُستخدم في Windows لتشير إلى أن السكريبت يحتاج إلى التنفيذ |
|
|  | [CPY](#CPY) | تنسيق سكريبت Python للمتحكم |
|
|  | [GYP](#GYP) | تنسيق أداة أتمتة البناء |
|
|  | [GYPI](#GYPI) | تنسيق أداة أتمتة البناء |
|
|  | [PYI](#PYI) | تنسيق ملف واجهة Python |
|
|  | [IPY](#IPY) | تنسيق سكريبت IPython |
|
|  | [RST](#RST) | لغة ترميز خفيفة |
|
|  | [RB](#RB) | تنسيق لغة البرمجة Ruby |
|
|  | [ERB](#ERB) | تنسيق لغة البرمجة Ruby |
|
|  | [RJS](#RJS) | تنسيق لغة البرمجة Ruby |
|
|  | [GEMSPEC](#GEMSPEC) | ملف المطور الذي يحدد خصائص RubyGems |
|
|  | [RAKE](#RAKE) | أداة أتمتة بناء Ruby |
|
|  | [RU](#RU) | تنسيق ملف تكوين Rack |
|
|  | [PODSPEC](#PODSPEC) | تنسيق إعدادات بناء Ruby |
|
|  | [RBI](#RBI) | تنسيق ملف واجهة Ruby |
|
|  | [SASS](#SASS) | تنسيق لغة الأنماط |
|
|  | [SCSS](#SCSS) | تنسيق لغة الأنماط |
|
|  | [SCALA](#SCALA) | تنسيق لغة البرمجة سكالا |
|
|  | [SBT](#SBT) | تنسيق أداة بناء SBT للسكالا |
|
|  | [SC](#SC) | تنسيق ورقة عمل سكالا |
|
|  | [SH](#SH) | تنسيق سكريبت مبرمج للباش |
|
|  | [BASH](#BASH) | نوع المفسّر الذي يعالج أوامر الصدفة |
|
|  | [BASHRC](#BASHRC) | الملف يحدد سلوك الصدافات التفاعلية |
|
|  | [EBUILD](#EBUILD) | سكريبت باش متخصص يُؤتمت إجراءات التجميع والتثبيت لحزم البرمجيات |
|
|  | [SQL](#SQL) | تنسيق لغة الاستعلام البنيوية |
|
|  | [DSQL](#DSQL) | تنسيق لغة الاستعلام البنيوية الديناميكية |
|
|  | [VIM](#VIM) | تنسيق ملف شفرة المصدر لفيم |
|
|  | [YAML](#YAML) | تنسيق لغة تسلسل البيانات القابلة للقراءة من قبل الإنسان |
|
|  | [YML](#YML) | تنسيق لغة تسلسل البيانات القابلة للقراءة من قبل الإنسان |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromFileNameOrExtension(String value)](#fromFileNameOrExtension-java.lang.String-) | إرجاع FileType بناءً على اسم الملف أو الامتداد |
|
|  | [getSupportedFileTypes()](#getSupportedFileTypes--) | يحصل على قائمة بأنواع الملفات المدعومة |
|
|  | [areEquals(FileType left, FileType right)](#areEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-) | يفحص مساواة أنواع الملفات المقدمة |
|
|  | [areNotEquals(FileType left, FileType right)](#areNotEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-) | يفحص عدم مساواة أنواع الملفات المقدمة |
|
|  | [getFileFormat()](#getFileFormat--) | يحصل على الوصف النصي لنوع الملف |
|
|  | [getExtension()](#getExtension--) | يحصل على امتداد نوع الملف |
|
|  | [toString()](#toString--) | يحصل على تمثيل السلسلة لـ [FileType](../../com.groupdocs.comparison.result/filetype)، على سبيل المثال |
'تنسيق لغة البرمجة PHP (.php)'

|
### UNKNOWN {#UNKNOWN}
```
public static final FileType UNKNOWN
```


نوع غير معروف


### AS {#AS}
```
public static final FileType AS
```


تنسيق لغة البرمجة ActionScript


### AS3 {#AS3}
```
public static final FileType AS3
```


تنسيق لغة البرمجة ActionScript


### ASM {#ASM}
```
public static final FileType ASM
```


تنسيق لغة البرمجة Assembler


### BAT {#BAT}
```
public static final FileType BAT
```


ملف سكريبت في DOS وOS/2 وMicrosoft Windows


### CMD {#CMD}
```
public static final FileType CMD
```


ملف سكريبت في DOS وOS/2 وMicrosoft Windows


### C {#C}
```
public static final FileType C
```


تنسيق لغة البرمجة المستندة إلى C


### H {#H}
```
public static final FileType H
```


ملفات الرأس المستندة إلى C تحتوي على تعريفات الدوال والمتغيرات


### PDF {#PDF}
```
public static final FileType PDF
```


تنسيق Adobe Portable Document


### DOC {#DOC}
```
public static final FileType DOC
```


مستند Microsoft Word 97-2003


### DOCM {#DOCM}
```
public static final FileType DOCM
```


مستند Microsoft Word مع تمكين الماكرو


### DOCX {#DOCX}
```
public static final FileType DOCX
```


مستند Microsoft Word


### DOT {#DOT}
```
public static final FileType DOT
```


قالب Microsoft Word 97-2003


### DOTM {#DOTM}
```
public static final FileType DOTM
```


قالب Microsoft Word مع تمكين الماكرو


### DOTX {#DOTX}
```
public static final FileType DOTX
```


قالب Microsoft Word


### XLS {#XLS}
```
public static final FileType XLS
```


ورقة عمل Microsoft Excel 97-2003


### XLT {#XLT}
```
public static final FileType XLT
```


قالب Microsoft Excel


### XLSX {#XLSX}
```
public static final FileType XLSX
```


ورقة عمل Microsoft Excel


### XLTM {#XLTM}
```
public static final FileType XLTM
```


قالب Microsoft Excel مع تمكين الماكرو


### XLSB {#XLSB}
```
public static final FileType XLSB
```


Microsoft Excel ورقة عمل ثنائية


### XLSM {#XLSM}
```
public static final FileType XLSM
```


Microsoft Excel ورقة عمل مدعومة بالماكرو


### POT {#POT}
```
public static final FileType POT
```


قالب Microsoft PowerPoint


### POTX {#POTX}
```
public static final FileType POTX
```


قالب Microsoft PowerPoint


### POTM {#POTM}
```
public static final FileType POTM
```


قالب Microsoft PowerPoint مع دعم الماكرو


### PPS {#PPS}
```
public static final FileType PPS
```


عرض شرائح Microsoft PowerPoint 97-2003


### PPSX {#PPSX}
```
public static final FileType PPSX
```


عرض شرائح Microsoft PowerPoint


### PPTX {#PPTX}
```
public static final FileType PPTX
```


عرض تقديمي Microsoft PowerPoint


### PPT {#PPT}
```
public static final FileType PPT
```


عرض تقديمي Microsoft PowerPoint 97-2003


### PPTM {#PPTM}
```
public static final FileType PPTM
```


عرض تقديمي Microsoft PowerPoint مدعوم بالماكرو


### PPSM {#PPSM}
```
public static final FileType PPSM
```


عرض شرائح تقديمي Microsoft PowerPoint مدعوم بالماكرو


### VSDX {#VSDX}
```
public static final FileType VSDX
```


رسم Microsoft Visio


### VSD {#VSD}
```
public static final FileType VSD
```


رسم Microsoft Visio 2003-2010


### VSS {#VSS}
```
public static final FileType VSS
```


قالب Microsoft Visio 2003-2010


### VST {#VST}
```
public static final FileType VST
```


قالب Microsoft Visio 2003-2010


### VDX {#VDX}
```
public static final FileType VDX
```


رسم XML Microsoft Visio 2003-2010


### ONE {#ONE}
```
public static final FileType ONE
```


مستند Microsoft OneNote


### ODT {#ODT}
```
public static final FileType ODT
```


نص OpenDocument


### ODP {#ODP}
```
public static final FileType ODP
```


عرض تقديمي OpenDocument


### OTP {#OTP}
```
public static final FileType OTP
```


قالب عرض تقديمي OpenDocument


### ODS {#ODS}
```
public static final FileType ODS
```


جدول بيانات OpenDocument


### OTT {#OTT}
```
public static final FileType OTT
```


قالب نص OpenDocument


### RTF {#RTF}
```
public static final FileType RTF
```


مستند نص غني


### TXT {#TXT}
```
public static final FileType TXT
```


مستند نص عادي


### CSV {#CSV}
```
public static final FileType CSV
```


ملف قيم مفصولة بفواصل


### HTML {#HTML}
```
public static final FileType HTML
```


لغة توصيف النص الفائق


### MHTML {#MHTML}
```
public static final FileType MHTML
```


MIME HTML


### MOBI {#MOBI}
```
public static final FileType MOBI
```


تنسيق الكتب الإلكترونية Mobipocket


### DCM {#DCM}
```
public static final FileType DCM
```


التصوير الرقمي والاتصالات في الطب


### DJVU {#DJVU}
```
public static final FileType DJVU
```


تنسيق Deja Vu


### DWG {#DWG}
```
public static final FileType DWG
```


تنسيقات بيانات التصميم Autodesk


### DXF {#DXF}
```
public static final FileType DXF
```


تبادل رسومات AutoCAD


### BMP {#BMP}
```
public static final FileType BMP
```


صورة Bitmap


### GIF {#GIF}
```
public static final FileType GIF
```


تنسيق تبادل الرسومات


### JPEG {#JPEG}
```
public static final FileType JPEG
```


مجموعة الخبراء المشتركة للتصوير الفوتوغرافي


### JPG {#JPG}
```
public static final FileType JPG
```


مجموعة الخبراء المشتركة للتصوير الفوتوغرافي


### PNG {#PNG}
```
public static final FileType PNG
```


رسومات الشبكة المحمولة


### SVG {#SVG}
```
public static final FileType SVG
```


رسومات المتجهات العددية


### EML {#EML}
```
public static final FileType EML
```


رسالة بريد إلكتروني


### EMLX {#EMLX}
```
public static final FileType EMLX
```


ملف بريد إلكتروني Apple Mail


### MSG {#MSG}
```
public static final FileType MSG
```


رسالة بريد إلكتروني Microsoft Outlook


### CAD {#CAD}
```
public static final FileType CAD
```


تنسيق ملف CAD


### CPP {#CPP}
```
public static final FileType CPP
```


تنسيق لغة البرمجة المستندة إلى C


### CC {#CC}
```
public static final FileType CC
```


تنسيق لغة البرمجة المستندة إلى C


### CXX {#CXX}
```
public static final FileType CXX
```


تنسيق لغة البرمجة المستندة إلى C


### HXX {#HXX}
```
public static final FileType HXX
```


ملفات الرأس المكتوبة بلغة البرمجة C++


### HH {#HH}
```
public static final FileType HH
```


معلومات الرأس المشار إليها بواسطة ملف شفرة مصدر C++


### HPP {#HPP}
```
public static final FileType HPP
```


ملفات الرأس المكتوبة بلغة البرمجة C++


### CMAKE {#CMAKE}
```
public static final FileType CMAKE
```


أداة لإدارة عملية بناء البرمجيات


### CS {#CS}
```
public static final FileType CS
```


تنسيق لغة البرمجة CSharp


### CSX {#CSX}
```
public static final FileType CSX
```


تنسيق ملف سكريبت CSharp


### CAKE {#CAKE}
```
public static final FileType CAKE
```


تنسيق نظام أتمتة بناء متعدد المنصات CSharp


### DIFF {#DIFF}
```
public static final FileType DIFF
```


تنسيق أداة مقارنة البيانات


### PATCH {#PATCH}
```
public static final FileType PATCH
```


تنسيق قائمة الاختلافات


### REJ {#REJ}
```
public static final FileType REJ
```


تنسيق الملفات المرفوضة


### GROOVY {#GROOVY}
```
public static final FileType GROOVY
```


ملف شفرة المصدر مكتوب بصيغة Groovy


### GVY {#GVY}
```
public static final FileType GVY
```


ملف شفرة المصدر مكتوب بصيغة Groovy


### GRADLE {#GRADLE}
```
public static final FileType GRADLE
```


صيغة نظام أتمتة البناء


### HAML {#HAML}
```
public static final FileType HAML
```


لغة توصيف لإنشاء HTML مبسط


### JS {#JS}
```
public static final FileType JS
```


صيغة لغة برمجة JavaScript


### ES6 {#ES6}
```
public static final FileType ES6
```


صيغة لغة البرمجة النصية المعيارية JavaScript


### MJS {#MJS}
```
public static final FileType MJS
```


امتداد لملفات وحدات EcmaScript (ES)


### PAC {#PAC}
```
public static final FileType PAC
```


ملف تكوين الوكيل التلقائي لتنسيق دالة JavaScript


### JSON {#JSON}
```
public static final FileType JSON
```


صيغة خفيفة لتخزين ونقل البيانات


### BOWERRC {#BOWERRC}
```
public static final FileType BOWERRC
```


ملف تكوين للتحكم في الحزم على جانب الخادم


### JSHINTRC {#JSHINTRC}
```
public static final FileType JSHINTRC
```


أداة جودة شفرة JavaScript


### JSCSRC {#JSCSRC}
```
public static final FileType JSCSRC
```


صيغة ملف تكوين JavaScript


### WEBMANIFEST {#WEBMANIFEST}
```
public static final FileType WEBMANIFEST
```


ملف البيان يتضمن معلومات عن التطبيق


### JSMAP {#JSMAP}
```
public static final FileType JSMAP
```


ملف JSON يحتوي على معلومات حول كيفية ترجمة الشفرة إلى شفرة المصدر


### HAR {#HAR}
```
public static final FileType HAR
```


صيغة أرشيف HTTP


### JAVA {#JAVA}
```
public static final FileType JAVA
```


صيغة لغة برمجة Java


### LESS {#LESS}
```
public static final FileType LESS
```


صيغة لغة ورقة الأنماط المعالجة مسبقًا الديناميكية


### LOG {#LOG}
```
public static final FileType LOG
```


التسجيل يحافظ على سجل الأحداث والعمليات والرسائل والاتصالات


### MAKE {#MAKE}
```
public static final FileType MAKE
```


Makefile هو ملف يحتوي على مجموعة من التوجيهات المستخدمة بواسطة أداة أتمتة بناء make لتوليد هدف/غاية


### MK {#MK}
```
public static final FileType MK
```


Makefile هو ملف يحتوي على مجموعة من التوجيهات المستخدمة بواسطة أداة أتمتة بناء make لتوليد هدف/غاية


### MD {#MD}
```
public static final FileType MD
```


صيغة لغة Markdown


### MKD {#MKD}
```
public static final FileType MKD
```


صيغة لغة Markdown


### MDWN {#MDWN}
```
public static final FileType MDWN
```


صيغة لغة Markdown


### MDOWN {#MDOWN}
```
public static final FileType MDOWN
```


صيغة لغة Markdown


### MARKDOWN {#MARKDOWN}
```
public static final FileType MARKDOWN
```


صيغة لغة Markdown


### MARKDN {#MARKDN}
```
public static final FileType MARKDN
```


صيغة لغة Markdown


### MDTXT {#MDTXT}
```
public static final FileType MDTXT
```


صيغة لغة Markdown


### MDTEXT {#MDTEXT}
```
public static final FileType MDTEXT
```


صيغة لغة Markdown


### ML {#ML}
```
public static final FileType ML
```


صيغة لغة برمجة Caml


### MLI {#MLI}
```
public static final FileType MLI
```


صيغة لغة برمجة Caml


### OBJC {#OBJC}
```
public static final FileType OBJC
```


صيغة لغة برمجة Objective-C


### OBJCP {#OBJCP}
```
public static final FileType OBJCP
```


صيغة لغة برمجة Objective-C++


### PHP {#PHP}
```
public static final FileType PHP
```


صيغة لغة برمجة PHP


### PHP4 {#PHP4}
```
public static final FileType PHP4
```


صيغة لغة برمجة PHP


### PHP5 {#PHP5}
```
public static final FileType PHP5
```


صيغة لغة برمجة PHP


### PHTML {#PHTML}
```
public static final FileType PHTML
```


صيغة الامتداد القياسي لبرامج PHP 2


### CTP {#CTP}
```
public static final FileType CTP
```


صيغة قالب CakePHP


### PL {#PL}
```
public static final FileType PL
```


تنسيق لغة البرمجة Perl


### PM {#PM}
```
public static final FileType PM
```


تنسيق وحدة Perl


### POD {#POD}
```
public static final FileType POD
```


تنسيق لغة الترميز الخفيفة Perl


### T {#T}
```
public static final FileType T
```


تنسيق ملف اختبار Perl


### PSGI {#PSGI}
```
public static final FileType PSGI
```


واجهة بين خوادم الويب وتطبيقات الويب والأطر المكتوبة بلغة البرمجة Perl


### P6 {#P6}
```
public static final FileType P6
```


تنسيق لغة البرمجة Perl


### PL6 {#PL6}
```
public static final FileType PL6
```


تنسيق لغة البرمجة Perl


### PM6 {#PM6}
```
public static final FileType PM6
```


تنسيق وحدة Perl


### NQP {#NQP}
```
public static final FileType NQP
```


لغة وسيطة تُستخدم لبناء مترجم Rakuto Perl 6


### PROP {#PROP}
```
public static final FileType PROP
```


تنسيق ملف الخصائص


### CFG {#CFG}
```
public static final FileType CFG
```


ملف التكوين يُستخدم لتخزين الإعدادات


### CONF {#CONF}
```
public static final FileType CONF
```


ملف التكوين يُستخدم على الأنظمة القائمة على Unix و Linux


### DIR {#DIR}
```
public static final FileType DIR
```


الدليل هو موقع لتخزين الملفات على الكمبيوتر


### PY {#PY}
```
public static final FileType PY
```


تنسيق لغة البرمجة Python


### RPY {#RPY}
```
public static final FileType RPY
```


محرك ملفات مبني على Python لإنشاء وتشغيل الألعاب


### PYW {#PYW}
```
public static final FileType PYW
```


ملفات تُستخدم في Windows لتشير إلى أن السكريبت يحتاج إلى التنفيذ


### CPY {#CPY}
```
public static final FileType CPY
```


تنسيق سكريبت Python للمتحكم


### GYP {#GYP}
```
public static final FileType GYP
```


تنسيق أداة أتمتة البناء


### GYPI {#GYPI}
```
public static final FileType GYPI
```


تنسيق أداة أتمتة البناء


### PYI {#PYI}
```
public static final FileType PYI
```


تنسيق ملف واجهة Python


### IPY {#IPY}
```
public static final FileType IPY
```


تنسيق سكريبت IPython


### RST {#RST}
```
public static final FileType RST
```


لغة ترميز خفيفة


### RB {#RB}
```
public static final FileType RB
```


تنسيق لغة البرمجة Ruby


### ERB {#ERB}
```
public static final FileType ERB
```


تنسيق لغة البرمجة Ruby


### RJS {#RJS}
```
public static final FileType RJS
```


تنسيق لغة البرمجة Ruby


### GEMSPEC {#GEMSPEC}
```
public static final FileType GEMSPEC
```


ملف المطور الذي يحدد خصائص RubyGems


### RAKE {#RAKE}
```
public static final FileType RAKE
```


أداة أتمتة بناء Ruby


### RU {#RU}
```
public static final FileType RU
```


تنسيق ملف تكوين Rack


### PODSPEC {#PODSPEC}
```
public static final FileType PODSPEC
```


تنسيق إعدادات بناء Ruby


### RBI {#RBI}
```
public static final FileType RBI
```


تنسيق ملف واجهة Ruby


### SASS {#SASS}
```
public static final FileType SASS
```


تنسيق لغة الأنماط


### SCSS {#SCSS}
```
public static final FileType SCSS
```


تنسيق لغة الأنماط


### SCALA {#SCALA}
```
public static final FileType SCALA
```


تنسيق لغة البرمجة سكالا


### SBT {#SBT}
```
public static final FileType SBT
```


تنسيق أداة بناء SBT للسكالا


### SC {#SC}
```
public static final FileType SC
```


تنسيق ورقة عمل سكالا


### SH {#SH}
```
public static final FileType SH
```


تنسيق سكريبت مبرمج للباش


### BASH {#BASH}
```
public static final FileType BASH
```


نوع المفسّر الذي يعالج أوامر الصدفة


### BASHRC {#BASHRC}
```
public static final FileType BASHRC
```


الملف يحدد سلوك الصدافات التفاعلية


### EBUILD {#EBUILD}
```
public static final FileType EBUILD
```


سكريبت باش متخصص يُؤتمت إجراءات التجميع والتثبيت لحزم البرمجيات


### SQL {#SQL}
```
public static final FileType SQL
```


تنسيق لغة الاستعلام البنيوية


### DSQL {#DSQL}
```
public static final FileType DSQL
```


تنسيق لغة الاستعلام البنيوية الديناميكية


### VIM {#VIM}
```
public static final FileType VIM
```


تنسيق ملف شفرة المصدر لفيم


### YAML {#YAML}
```
public static final FileType YAML
```


تنسيق لغة تسلسل البيانات القابلة للقراءة من قبل الإنسان


### YML {#YML}
```
public static final FileType YML
```


تنسيق لغة تسلسل البيانات القابلة للقراءة من قبل الإنسان


### values() {#values--}
```
public static FileType[] values()
```




**Returns:**
com.groupdocs.comparison.result.FileType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static FileType valueOf(String name)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String |  |

**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype)
### fromFileNameOrExtension(String value) {#fromFileNameOrExtension-java.lang.String-}
```
public static FileType fromFileNameOrExtension(String value)
```


إرجاع FileType بناءً على اسم الملف أو الامتداد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | java.lang.String | اسم الملف أو الامتداد، غير فارغ |
|

**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the file type

### getSupportedFileTypes() {#getSupportedFileTypes--}
```
public static List<FileType> getSupportedFileTypes()
```


يحصل على قائمة بأنواع الملفات المدعومة


**Returns:**
java.util.List<com.groupdocs.comparison.result.FileType> - قائمة بأنواع FileType

### areEquals(FileType left, FileType right) {#areEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-}
```
public static boolean areEquals(FileType left, FileType right)
```


يفحص مساواة أنواع الملفات المقدمة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | left | [FileType](../../com.groupdocs.comparison.result/filetype) | كائن [FileType](../../com.groupdocs.comparison.result/filetype) الأيسر. |
|
|  | right | [FileType](../../com.groupdocs.comparison.result/filetype) | كائن [FileType](../../com.groupdocs.comparison.result/filetype) الأيمن. |
|

**Returns:**
منطقي - true إذا كان متساويًا، وإلا false

### areNotEquals(FileType left, FileType right) {#areNotEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-}
```
public static boolean areNotEquals(FileType left, FileType right)
```


يفحص عدم مساواة أنواع الملفات المقدمة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | left | [FileType](../../com.groupdocs.comparison.result/filetype) | كائن [FileType](../../com.groupdocs.comparison.result/filetype) الأيسر. |
|
|  | right | [FileType](../../com.groupdocs.comparison.result/filetype) | كائن [FileType](../../com.groupdocs.comparison.result/filetype) الأيمن. |
|

**Returns:**
منطقي - true إذا لم يكن متساويًا، وإلا false

### getFileFormat() {#getFileFormat--}
```
public String getFileFormat()
```


يحصل على الوصف النصي لنوع الملف


**Returns:**
java.lang.String - وصف نوع الملف

### getExtension() {#getExtension--}
```
public String getExtension()
```


يحصل على امتداد نوع الملف


**Returns:**
java.lang.String - امتداد نوع الملف

### toString() {#toString--}
```
public String toString()
```


يحصل على تمثيل السلسلة لـ [FileType](../../com.groupdocs.comparison.result/filetype)، على سبيل المثال
'تنسيق لغة البرمجة PHP (.php)'



**Returns:**
java.lang.String - تمثيل النص

