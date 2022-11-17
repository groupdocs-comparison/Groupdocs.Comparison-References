---
title: FileType
second_title: GroupDocs.Comparison لمرجع .NET API
description: يمثل نوع الملف. يوفر طرقًا للحصول على قائمة بجميع أنواع الملفات التي يدعمها GroupDocs.Comparison  واكتشاف نوع الملف بالامتداد وما إلى ذلك.
type: docs
weight: 400
url: /ar/net/groupdocs.comparison.result/filetype/
---
## FileType class

يمثل نوع الملف. يوفر طرقًا للحصول على قائمة بجميع أنواع الملفات التي يدعمها GroupDocs.Comparison ، واكتشاف نوع الملف بالامتداد وما إلى ذلك.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [Extension](../../groupdocs.comparison.result/filetype/extension) { get; } | امتداد الملف |
| [FileFormat](../../groupdocs.comparison.result/filetype/fileformat) { get; } | تنسيق الملف |

## طُرق

| اسم | وصف |
| --- | --- |
| static [FromFileNameOrExtension](../../groupdocs.comparison.result/filetype/fromfilenameorextension)(string) | إرجاع نوع الملف بناءً على اسم الملف أو الامتداد |
| [Equals](../../groupdocs.comparison.result/filetype/equals#equals)(FileType) | فحص معادلة نوع الملف |
| override [Equals](../../groupdocs.comparison.result/filetype/equals#equals_1)(object) | فحص التكافؤ باستخدام object |
| override [GetHashCode](../../groupdocs.comparison.result/filetype/gethashcode)() | احصل على كود التجزئة |
| override [ToString](../../groupdocs.comparison.result/filetype/tostring)() | ToString |
| static [GetSupportedFileTypes](../../groupdocs.comparison.result/filetype/getsupportedfiletypes)() | الحصول على تعداد أنواع الملفات المدعومة |
| [operator ==](../../groupdocs.comparison.result/filetype/op_equality) | حمل المشغل الزائد |
| [operator !=](../../groupdocs.comparison.result/filetype/op_inequality) | حمل المشغل الزائد |

## مجالات

| اسم | وصف |
| --- | --- |
| static [AS](../../groupdocs.comparison.result/filetype/as) | تنسيق لغة برمجة أكشن سكريبت |
| static [AS3](../../groupdocs.comparison.result/filetype/as3) | تنسيق لغة برمجة أكشن سكريبت |
| static [ASM](../../groupdocs.comparison.result/filetype/asm) | تنسيق ASM |
| static [BASH](../../groupdocs.comparison.result/filetype/bash) | نوع المترجم الذي يعالج أوامر shell |
| static [BASHRC](../../groupdocs.comparison.result/filetype/bashrc) | يحدد الملف سلوك الأصداف التفاعلية |
| static [BAT](../../groupdocs.comparison.result/filetype/bat) | ملف نصي في DOS و OS / 2 و Microsoft Windows |
| static [BMP](../../groupdocs.comparison.result/filetype/bmp) | صورة نقطية |
| static [BOWERRC](../../groupdocs.comparison.result/filetype/bowerrc) | ملف التكوين للتحكم في الحزمة على جانب الخادم |
| static [C](../../groupdocs.comparison.result/filetype/c) | تنسيق لغة البرمجة المستندة إلى C |
| static [CAD](../../groupdocs.comparison.result/filetype/cad) | تنسيق ملف CAD |
| static [CAKE](../../groupdocs.comparison.result/filetype/cake) | CSharp تنسيق نظام أتمتة بناء متعدد المنصات |
| static [CC](../../groupdocs.comparison.result/filetype/cc) | تنسيق لغة البرمجة المستندة إلى C |
| static [CFG](../../groupdocs.comparison.result/filetype/cfg) | ملف التكوين المستخدم لتخزين الإعدادات |
| static [CMAKE](../../groupdocs.comparison.result/filetype/cmake) | أداة لإدارة عملية بناء البرنامج |
| static [CMD](../../groupdocs.comparison.result/filetype/cmd) | ملف نصي في DOS و OS / 2 و Microsoft Windows |
| static [CONF](../../groupdocs.comparison.result/filetype/conf) | ملف التكوين المستخدم في الأنظمة المستندة إلى Unix و Linux |
| static [CPP](../../groupdocs.comparison.result/filetype/cpp) | تنسيق لغة البرمجة المستندة إلى C |
| static [CPY](../../groupdocs.comparison.result/filetype/cpy) | وحدة تحكم تنسيق Python Script |
| static [CS](../../groupdocs.comparison.result/filetype/cs) | تنسيق لغة برمجة CSharp |
| static [CSV](../../groupdocs.comparison.result/filetype/csv) | ملف قيم مفصولة بفواصل |
| static [CSX](../../groupdocs.comparison.result/filetype/csx) | تنسيق ملف البرنامج النصي CSharp |
| static [CTP](../../groupdocs.comparison.result/filetype/ctp) | كعكة تنسيق قالب PHP |
| static [CXX](../../groupdocs.comparison.result/filetype/cxx) | تنسيق لغة البرمجة المستندة إلى C |
| static [DCM](../../groupdocs.comparison.result/filetype/dcm) | التصوير الرقمي والاتصالات في الطب |
| static [DIFF](../../groupdocs.comparison.result/filetype/diff) | تنسيق أداة مقارنة البيانات |
| static [DIR](../../groupdocs.comparison.result/filetype/dir) | الدليل هو موقع لتخزين الملفات على الكمبيوتر |
| static [DJVU](../../groupdocs.comparison.result/filetype/djvu) | تنسيق Deja Vu |
| static [DOC](../../groupdocs.comparison.result/filetype/doc) | مستند Microsoft Word 97-2003 |
| static [DOCM](../../groupdocs.comparison.result/filetype/docm) | مستند ممكّن بماكرو لـ Microsoft Word |
| static [DOCX](../../groupdocs.comparison.result/filetype/docx) | مستند Microsoft Word |
| static [DOT](../../groupdocs.comparison.result/filetype/dot) | قالب Microsoft Word 97-2003 |
| static [DOTM](../../groupdocs.comparison.result/filetype/dotm) | قالب تم تمكين ماكرو لـ Microsoft Word |
| static [DOTX](../../groupdocs.comparison.result/filetype/dotx) | قالب Microsoft Word |
| static [DSQL](../../groupdocs.comparison.result/filetype/dsql) | تنسيق لغة الاستعلام الهيكلية الديناميكية |
| static [DWG](../../groupdocs.comparison.result/filetype/dwg) | تنسيقات بيانات تصميم Autodesk |
| static [DXF](../../groupdocs.comparison.result/filetype/dxf) | تبادل رسم AutoCAD |
| static [EBUILD](../../groupdocs.comparison.result/filetype/ebuild) | سكربت bash المتخصص الذي يعمل على أتمتة إجراءات التجميع والتثبيت لحزم البرامج |
| static [EML](../../groupdocs.comparison.result/filetype/eml) | رسالة بريد إلكتروني |
| static [EMLX](../../groupdocs.comparison.result/filetype/emlx) | ملف البريد الإلكتروني لـ Apple Mail |
| static [ERB](../../groupdocs.comparison.result/filetype/erb) | تنسيق لغة برمجة روبي |
| static [ES6](../../groupdocs.comparison.result/filetype/es6) | تنسيق لغة البرمجة النصية المعيارية لـ JavaScript |
| static [GEMSPEC](../../groupdocs.comparison.result/filetype/gemspec) | ملف المطور الذي يحدد سمات RubyGems |
| static [GIF](../../groupdocs.comparison.result/filetype/gif) | تنسيق تبادل الرسومات |
| static [GRADLE](../../groupdocs.comparison.result/filetype/gradle) | تنسيق نظام أتمتة البناء |
| static [GROOVY](../../groupdocs.comparison.result/filetype/groovy) | ملف كود المصدر مكتوب بتنسيق Groovy |
| static [GVY](../../groupdocs.comparison.result/filetype/gvy) | ملف كود المصدر مكتوب بتنسيق Groovy |
| static [GYP](../../groupdocs.comparison.result/filetype/gyp) | إنشاء تنسيق أداة التشغيل الآلي |
| static [GYPI](../../groupdocs.comparison.result/filetype/gypi) | إنشاء تنسيق أداة التشغيل الآلي |
| static [H](../../groupdocs.comparison.result/filetype/h) | تحتوي ملفات الرأس المستندة إلى C على تعريفات للوظائف والمتغيرات |
| static [HAML](../../groupdocs.comparison.result/filetype/haml) | لغة ترميزية لإنشاء HTML مبسط |
| static [HAR](../../groupdocs.comparison.result/filetype/har) | تنسيق أرشيف HTTP |
| static [HH](../../groupdocs.comparison.result/filetype/hh) | معلومات الرأس المشار إليها بواسطة ملف شفرة مصدر C ++ file |
| static [HPP](../../groupdocs.comparison.result/filetype/hpp) | ملفات الرأس المكتوبة بلغة البرمجة C ++ |
| static [HTML](../../groupdocs.comparison.result/filetype/html) | لغة ترميز النص التشعبي |
| static [HXX](../../groupdocs.comparison.result/filetype/hxx) | ملفات الرأس المكتوبة بلغة البرمجة C ++ |
| static [IPY](../../groupdocs.comparison.result/filetype/ipy) | تنسيق البرنامج النصي IPython |
| static [JAVA](../../groupdocs.comparison.result/filetype/java) | تنسيق لغة برمجة جافا |
| static [JPEG](../../groupdocs.comparison.result/filetype/jpeg) | مجموعة خبراء التصوير المشتركة |
| static [JS](../../groupdocs.comparison.result/filetype/js) | تنسيق لغة برمجة JavaScript |
| static [JSCSRC](../../groupdocs.comparison.result/filetype/jscsrc) | تنسيق ملف تكوين JavaScript |
| static [JSHINTRC](../../groupdocs.comparison.result/filetype/jshintrc) | أداة جودة كود JavaScript |
| static [JSMAP](../../groupdocs.comparison.result/filetype/jsmap) | ملف JSON يحتوي على معلومات حول كيفية ترجمة التعليمات البرمجية مرة أخرى إلى كود المصدر |
| static [JSON](../../groupdocs.comparison.result/filetype/json) | تنسيق خفيف الوزن لتخزين البيانات ونقلها |
| static [LESS](../../groupdocs.comparison.result/filetype/less) | تنسيق لغة ورقة نمط المعالج الديناميكي |
| static [LOG](../../groupdocs.comparison.result/filetype/log) | يحتفظ التسجيل بسجل للأحداث والعمليات والرسائل والاتصالات |
| static [MAKE](../../groupdocs.comparison.result/filetype/make) | Makefile هو ملف يحتوي على مجموعة من التوجيهات المستخدمة بواسطة أداة أتمتة الإنشاء لإنشاء هدف / هدف |
| static [MARKDN](../../groupdocs.comparison.result/filetype/markdn) | تنسيق لغة Markdown |
| static [MARKDOWN](../../groupdocs.comparison.result/filetype/markdown) | تنسيق لغة Markdown |
| static [MD](../../groupdocs.comparison.result/filetype/md) | تنسيق لغة Markdown |
| static [MDOWN](../../groupdocs.comparison.result/filetype/mdown) | تنسيق لغة Markdown |
| static [MDTEXT](../../groupdocs.comparison.result/filetype/mdtext) | تنسيق لغة Markdown |
| static [MDTXT](../../groupdocs.comparison.result/filetype/mdtxt) | تنسيق لغة Markdown |
| static [MDWN](../../groupdocs.comparison.result/filetype/mdwn) | تنسيق لغة Markdown |
| static [MHTML](../../groupdocs.comparison.result/filetype/mhtml) | Mime HTML |
| static [MJS](../../groupdocs.comparison.result/filetype/mjs) | امتداد ملفات الوحدة النمطية EcmaScript (ES ) |
| static [MK](../../groupdocs.comparison.result/filetype/mk) | Makefile هو ملف يحتوي على مجموعة من التوجيهات المستخدمة بواسطة أداة أتمتة الإنشاء لإنشاء هدف / هدف |
| static [MKD](../../groupdocs.comparison.result/filetype/mkd) | تنسيق لغة Markdown |
| static [ML](../../groupdocs.comparison.result/filetype/ml) | تنسيق لغة البرمجة Caml |
| static [MLI](../../groupdocs.comparison.result/filetype/mli) | تنسيق لغة البرمجة Caml |
| static [MOBI](../../groupdocs.comparison.result/filetype/mobi) | تنسيق الكتاب الإلكتروني من Mobipocket |
| static [MSG](../../groupdocs.comparison.result/filetype/msg) | رسالة بريد إلكتروني في Microsoft Outlook |
| static [NQP](../../groupdocs.comparison.result/filetype/nqp) | لغة وسيطة مستخدمة لبناء مترجم Rakudo Perl 6 |
| static [OBJC](../../groupdocs.comparison.result/filetype/objc) | تنسيق لغة البرمجة Objective-C |
| static [OBJCP](../../groupdocs.comparison.result/filetype/objcp) | تنسيق لغة البرمجة Objective-C ++ |
| static [ODP](../../groupdocs.comparison.result/filetype/odp) | عرض OpenDocument |
| static [ODS](../../groupdocs.comparison.result/filetype/ods) | جدول بيانات OpenDocument |
| static [ODT](../../groupdocs.comparison.result/filetype/odt) | OpenDocument Text |
| static [ONE](../../groupdocs.comparison.result/filetype/one) | مستند Microsoft OneNote |
| static [OTP](../../groupdocs.comparison.result/filetype/otp) | قالب العرض التقديمي OpenDocument |
| static [OTT](../../groupdocs.comparison.result/filetype/ott) | قالب نص OpenDocument |
| static [P6](../../groupdocs.comparison.result/filetype/p6) | تنسيق لغة برمجة Perl |
| static [PAC](../../groupdocs.comparison.result/filetype/pac) | ملف التكوين التلقائي للوكيل لتنسيق وظيفة JavaScript |
| static [PATCH](../../groupdocs.comparison.result/filetype/patch) | قائمة الاختلافات format |
| static [PDF](../../groupdocs.comparison.result/filetype/pdf) | تنسيق Adobe Portable Document |
| static [PHP](../../groupdocs.comparison.result/filetype/php) | تنسيق لغة البرمجة PHP |
| static [PHP4](../../groupdocs.comparison.result/filetype/php4) | تنسيق لغة البرمجة PHP |
| static [PHP5](../../groupdocs.comparison.result/filetype/php5) | تنسيق لغة البرمجة PHP |
| static [PHTML](../../groupdocs.comparison.result/filetype/phtml) | امتداد الملف القياسي لبرامج PHP 2 format |
| static [PL](../../groupdocs.comparison.result/filetype/pl) | تنسيق لغة برمجة Perl |
| static [PL6](../../groupdocs.comparison.result/filetype/pl6) | تنسيق لغة برمجة Perl |
| static [PM](../../groupdocs.comparison.result/filetype/pm) | تنسيق وحدة Perl |
| static [PM6](../../groupdocs.comparison.result/filetype/pm6) | تنسيق وحدة Perl |
| static [PNG](../../groupdocs.comparison.result/filetype/png) | رسومات الشبكة المحمولة |
| static [POD](../../groupdocs.comparison.result/filetype/pod) | تنسيق لغة الترميز الخفيف Perl |
| static [PODSPEC](../../groupdocs.comparison.result/filetype/podspec) | تنسيق إعدادات بناء Ruby |
| static [POT](../../groupdocs.comparison.result/filetype/pot) | قالب Microsoft PowerPoint |
| static [POTX](../../groupdocs.comparison.result/filetype/potx) | قالب Microsoft PowerPoint |
| static [PPS](../../groupdocs.comparison.result/filetype/pps) | عرض شرائح Microsoft PowerPoint 97-2003 |
| static [PPSX](../../groupdocs.comparison.result/filetype/ppsx) | عرض شرائح Microsoft PowerPoint |
| static [PPT](../../groupdocs.comparison.result/filetype/ppt) | عرض تقديمي لبرنامج Microsoft PowerPoint 97-2003 |
| static [PPTX](../../groupdocs.comparison.result/filetype/pptx) | Microsoft PowerPoint Presentation |
| static [PROP](../../groupdocs.comparison.result/filetype/prop) | تنسيق ملف الخصائص |
| static [PSGI](../../groupdocs.comparison.result/filetype/psgi) | واجهة بين خوادم الويب وتطبيقات الويب وأطر العمل المكتوبة في لغة البرمجة Perl |
| static [PY](../../groupdocs.comparison.result/filetype/py) | تنسيق لغة برمجة Python |
| static [PYI](../../groupdocs.comparison.result/filetype/pyi) | تنسيق ملف واجهة Python |
| static [PYW](../../groupdocs.comparison.result/filetype/pyw) | الملفات المستخدمة في Windows للإشارة إلى أن البرنامج النصي يحتاج إلى التشغيل |
| static [RAKE](../../groupdocs.comparison.result/filetype/rake) | أداة أتمتة بناء Ruby |
| static [RB](../../groupdocs.comparison.result/filetype/rb) | تنسيق لغة برمجة روبي |
| static [RBI](../../groupdocs.comparison.result/filetype/rbi) | تنسيق ملف واجهة روبي |
| static [REJ](../../groupdocs.comparison.result/filetype/rej) | تنسيق الملفات المرفوضة |
| static [RJS](../../groupdocs.comparison.result/filetype/rjs) | تنسيق لغة برمجة روبي |
| static [RPY](../../groupdocs.comparison.result/filetype/rpy) | محرك الملفات المستند إلى Python لإنشاء وتشغيل الألعاب |
| static [RST](../../groupdocs.comparison.result/filetype/rst) | لغة ترميز خفيفة الوزن |
| static [RTF](../../groupdocs.comparison.result/filetype/rtf) | مستند نص منسق |
| static [RU](../../groupdocs.comparison.result/filetype/ru) | تنسيق ملف تكوين الرف |
| static [SASS](../../groupdocs.comparison.result/filetype/sass) | تنسيق لغة ورقة الأنماط |
| static [SBT](../../groupdocs.comparison.result/filetype/sbt) | أداة إنشاء SBT لتنسيق Scala |
| static [SC](../../groupdocs.comparison.result/filetype/sc) | تنسيق ورقة عمل Scala |
| static [SCALA](../../groupdocs.comparison.result/filetype/scala) | تنسيق لغة برمجة Scala |
| static [SCSS](../../groupdocs.comparison.result/filetype/scss) | تنسيق لغة ورقة الأنماط |
| static [SH](../../groupdocs.comparison.result/filetype/sh) | نص برمجي لتنسيق bash |
| static [SQL](../../groupdocs.comparison.result/filetype/sql) | تنسيق لغة الاستعلام المهيكلة |
| static [SVG](../../groupdocs.comparison.result/filetype/svg) | رسومات المتجهات العددية |
| static [T](../../groupdocs.comparison.result/filetype/t) | تنسيق ملف اختبار Perl |
| static [TXT](../../groupdocs.comparison.result/filetype/txt) | مستند نص عادي |
| static [UNKNOWN](../../groupdocs.comparison.result/filetype/unknown) | نوع غير معروف |
| static [VDX](../../groupdocs.comparison.result/filetype/vdx) | Microsoft Visio 2003-2010 XML Drawing |
| static [VIM](../../groupdocs.comparison.result/filetype/vim) | تنسيق ملف التعليمات البرمجية المصدر لـ Vim |
| static [VSD](../../groupdocs.comparison.result/filetype/vsd) | Microsoft Visio 2003-2010 Drawing |
| static [VSDX](../../groupdocs.comparison.result/filetype/vsdx) | رسم Microsoft Visio |
| static [VSS](../../groupdocs.comparison.result/filetype/vss) | Microsoft Visio 2003-2010 Stencil |
| static [VST](../../groupdocs.comparison.result/filetype/vst) | Microsoft Visio 2003-2010 Template |
| static [WEBMANIFEST](../../groupdocs.comparison.result/filetype/webmanifest) | ملف البيان يتضمن معلومات حول التطبيق |
| static [XLS](../../groupdocs.comparison.result/filetype/xls) | ورقة عمل Microsoft Excel 97-2003 |
| static [XLSB](../../groupdocs.comparison.result/filetype/xlsb) | Microsoft Excel Binary Worksheet |
| static [XLSM](../../groupdocs.comparison.result/filetype/xlsm) | ورقة عمل Microsoft Excel تم تمكين ماكرو |
| static [XLSX](../../groupdocs.comparison.result/filetype/xlsx) | ورقة عمل Microsoft Excel |
| static [XLT](../../groupdocs.comparison.result/filetype/xlt) | قالب Microsoft Excel |
| static [XLTM](../../groupdocs.comparison.result/filetype/xltm) | قالب ممكّن للماكرو في Microsoft Excel |
| static [YAML](../../groupdocs.comparison.result/filetype/yaml) | تنسيق لغة تسلسل البيانات القابلة للقراءة البشرية |
| static [YML](../../groupdocs.comparison.result/filetype/yml) | تنسيق لغة تسلسل البيانات القابلة للقراءة البشرية |

### ملاحظات

**يتعلم أكثر**

* تعرف على المزيد حول تنسيقات الملفات التي يدعمها GroupDoc. المقارنة: [قائمة كاملة بتنسيقات المستندات المدعومة](https://docs.groupdocs.com/display/comparisonnet/Supported+Document+Formats)
* تعرف على المزيد حول الحصول على أنواع الملفات المدعومة في C #: [كيفية الحصول على تنسيقات الملفات المدعومة في C #](https://docs.groupdocs.com/display/comparisonnet/Get+supported+file+formats)

### أنظر أيضا

* مساحة الاسم [GroupDocs.Comparison.Result](../../groupdocs.comparison.result)
* المجسم [GroupDocs.Comparison](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Comparison.dll -->
