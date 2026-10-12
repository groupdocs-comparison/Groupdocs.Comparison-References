---
title: "FileType"
second_title: "مرجع API لـ GroupDocs.Comparison لـ .NET"
description: "يمثل نوع الملف. يوفر طرقًا للحصول على قائمة بجميع أنواع الملفات المدعومة من قبل GroupDocs.Comparison واكتشاف نوع الملف حسب الامتداد إلخ."
type: docs
weight: 480
url: /ar/net/groupdocs.comparison.result/filetype/
---
## FileType class

يمثل نوع الملف. يوفر طرقًا للحصول على قائمة بجميع أنواع الملفات المدعومة من قبل GroupDocs.Comparison، واكتشاف نوع الملف حسب الامتداد، إلخ.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Extension](../../groupdocs.comparison.result/filetype/extension) { get; } | امتداد الملف |
| [FileFormat](../../groupdocs.comparison.result/filetype/fileformat) { get; } | تنسيق الملف |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [FromFileNameOrExtension](../../groupdocs.comparison.result/filetype/fromfilenameorextension)(string) | إرجاع FileType بناءً على اسم الملف أو الامتداد |
| [Equals](../../groupdocs.comparison.result/filetype/equals#equals)(FileType) | التحقق من تكافؤ نوع الملف |
| override [Equals](../../groupdocs.comparison.result/filetype/equals#equals_1)(object) | التحقق من التكافؤ مع الكائن |
| override [GetHashCode](../../groupdocs.comparison.result/filetype/gethashcode)() | الحصول على رمز التجزئة |
| override [ToString](../../groupdocs.comparison.result/filetype/tostring)() | ToString |
| static [GetSupportedFileTypes](../../groupdocs.comparison.result/filetype/getsupportedfiletypes)() | الحصول على تعداد أنواع الملفات المدعومة |
| [operator ==](../../groupdocs.comparison.result/filetype/op_equality) | إعادة تعريف المشغل |
| [operator !=](../../groupdocs.comparison.result/filetype/op_inequality) | إعادة تعريف المشغل |

## الحقول

| الاسم | الوصف |
| --- | --- |
| static readonly [AS](../../groupdocs.comparison.result/filetype/as) | تنسيق لغة البرمجة ActionScript |
| static readonly [AS3](../../groupdocs.comparison.result/filetype/as3) | تنسيق لغة البرمجة ActionScript |
| static readonly [ASM](../../groupdocs.comparison.result/filetype/asm) | تنسيق ASM |
| static readonly [BASH](../../groupdocs.comparison.result/filetype/bash) | نوع المفسّر الذي يعالج أوامر الصدفة |
| static readonly [BASHRC](../../groupdocs.comparison.result/filetype/bashrc) | الملف يحدد سلوك الصدافات التفاعلية |
| static readonly [BAT](../../groupdocs.comparison.result/filetype/bat) | ملف سكريبت في DOS و OS/2 و Microsoft Windows |
| static readonly [BMP](../../groupdocs.comparison.result/filetype/bmp) | صورة Bitmap |
| static readonly [BOWERRC](../../groupdocs.comparison.result/filetype/bowerrc) | ملف تكوين للتحكم في الحزم على جانب الخادم |
| static readonly [C](../../groupdocs.comparison.result/filetype/c) | تنسيق لغة البرمجة المستندة إلى C |
| static readonly [CAD](../../groupdocs.comparison.result/filetype/cad) | تنسيق ملف CAD |
| static readonly [CAKE](../../groupdocs.comparison.result/filetype/cake) | تنسيق نظام أتمتة البناء متعدد المنصات CSharp |
| static readonly [CC](../../groupdocs.comparison.result/filetype/cc) | تنسيق لغة البرمجة المستندة إلى C |
| static readonly [CFG](../../groupdocs.comparison.result/filetype/cfg) | ملف تكوين يُستخدم لتخزين الإعدادات |
| static readonly [CMAKE](../../groupdocs.comparison.result/filetype/cmake) | أداة لإدارة عملية بناء البرمجيات |
| static readonly [CMD](../../groupdocs.comparison.result/filetype/cmd) | ملف سكريبت في DOS و OS/2 و Microsoft Windows |
| static readonly [CONF](../../groupdocs.comparison.result/filetype/conf) | ملف تكوين يُستخدم على الأنظمة المستندة إلى Unix و Linux |
| static readonly [CPP](../../groupdocs.comparison.result/filetype/cpp) | تنسيق لغة البرمجة المستندة إلى C |
| static readonly [CPY](../../groupdocs.comparison.result/filetype/cpy) | تنسيق سكريبت Python للمتحكم |
| static readonly [CS](../../groupdocs.comparison.result/filetype/cs) | تنسيق لغة البرمجة CSharp |
| static readonly [CSV](../../groupdocs.comparison.result/filetype/csv) | ملف القيم المفصولة بفواصل |
| static readonly [CSX](../../groupdocs.comparison.result/filetype/csx) | تنسيق ملف سكريبت CSharp |
| static readonly [CTP](../../groupdocs.comparison.result/filetype/ctp) | تنسيق قالب CakePHP |
| static readonly [CXX](../../groupdocs.comparison.result/filetype/cxx) | تنسيق لغة البرمجة المستندة إلى C |
| static readonly [DCM](../../groupdocs.comparison.result/filetype/dcm) | التصوير الرقمي والاتصالات في الطب |
| static readonly [DIFF](../../groupdocs.comparison.result/filetype/diff) | تنسيق أداة مقارنة البيانات |
| static readonly [DIR](../../groupdocs.comparison.result/filetype/dir) | الدليل هو موقع لتخزين الملفات على الحاسوب |
| static readonly [DJVU](../../groupdocs.comparison.result/filetype/djvu) | تنسيق Deja Vu |
| static readonly [DOC](../../groupdocs.comparison.result/filetype/doc) | مستند Microsoft Word 97-2003 |
| static readonly [DOCM](../../groupdocs.comparison.result/filetype/docm) | مستند Microsoft Word يدعم الماكرو |
| static readonly [DOCX](../../groupdocs.comparison.result/filetype/docx) | مستند Microsoft Word |
| static readonly [DOT](../../groupdocs.comparison.result/filetype/dot) | قالب Microsoft Word 97-2003 |
| static readonly [DOTM](../../groupdocs.comparison.result/filetype/dotm) | قالب Microsoft Word يدعم الماكرو |
| static readonly [DOTX](../../groupdocs.comparison.result/filetype/dotx) | قالب Microsoft Word |
| static readonly [DSQL](../../groupdocs.comparison.result/filetype/dsql) | تنسيق لغة الاستعلام الهيكلية الديناميكية |
| static readonly [DWG](../../groupdocs.comparison.result/filetype/dwg) | تنسيقات بيانات التصميم من Autodesk |
| static readonly [DXF](../../groupdocs.comparison.result/filetype/dxf) | تبادل رسومات AutoCAD |
| static readonly [EBUILD](../../groupdocs.comparison.result/filetype/ebuild) | برنامج نصي bash متخصص يقوم بأتمتة إجراءات التجميع والتثبيت لحزم البرمجيات |
| static readonly [EML](../../groupdocs.comparison.result/filetype/eml) | رسالة بريد إلكتروني |
| static readonly [EMLX](../../groupdocs.comparison.result/filetype/emlx) | ملف بريد إلكتروني من Apple Mail |
| static readonly [ERB](../../groupdocs.comparison.result/filetype/erb) | تنسيق لغة البرمجة Ruby |
| static readonly [ES6](../../groupdocs.comparison.result/filetype/es6) | تنسيق لغة البرمجة النصية المعيارية JavaScript |
| static readonly [GEMSPEC](../../groupdocs.comparison.result/filetype/gemspec) | ملف المطور الذي يحدد سمات RubyGems |
| static readonly [GIF](../../groupdocs.comparison.result/filetype/gif) | تنسيق تبادل الرسومات |
| static readonly [GRADLE](../../groupdocs.comparison.result/filetype/gradle) | تنسيق نظام أتمتة البناء |
| static readonly [GROOVY](../../groupdocs.comparison.result/filetype/groovy) | ملف شفرة مصدر مكتوب بتنسيق Groovy |
| static readonly [GVY](../../groupdocs.comparison.result/filetype/gvy) | ملف شفرة مصدر مكتوب بتنسيق Groovy |
| static readonly [GYP](../../groupdocs.comparison.result/filetype/gyp) | تنسيق أداة أتمتة البناء |
| static readonly [GYPI](../../groupdocs.comparison.result/filetype/gypi) | تنسيق أداة أتمتة البناء |
| static readonly [H](../../groupdocs.comparison.result/filetype/h) | ملفات رؤوس مبنية على C تحتوي على تعريفات الدوال والمتغيرات |
| static readonly [HAML](../../groupdocs.comparison.result/filetype/haml) | لغة توصيف لإنشاء HTML مبسط |
| static readonly [HAR](../../groupdocs.comparison.result/filetype/har) | تنسيق أرشيف HTTP |
| static readonly [HH](../../groupdocs.comparison.result/filetype/hh) | معلومات الرأس المشار إليها بواسطة ملف مصدر C++ |
| static readonly [HPP](../../groupdocs.comparison.result/filetype/hpp) | ملفات الرأس المكتوبة بلغة البرمجة C++ |
| static readonly [HTML](../../groupdocs.comparison.result/filetype/html) | لغة توصيف النص الفائق |
| static readonly [HXX](../../groupdocs.comparison.result/filetype/hxx) | ملفات الرأس المكتوبة بلغة البرمجة C++ |
| static readonly [IPY](../../groupdocs.comparison.result/filetype/ipy) | تنسيق سكريبت IPython |
| static readonly [JAVA](../../groupdocs.comparison.result/filetype/java) | تنسيق لغة البرمجة Java |
| static readonly [JPEG](../../groupdocs.comparison.result/filetype/jpeg) | مجموعة الخبراء المشتركة للتصوير الفوتوغرافي |
| static readonly [JS](../../groupdocs.comparison.result/filetype/js) | تنسيق لغة البرمجة JavaScript |
| static readonly [JSCSRC](../../groupdocs.comparison.result/filetype/jscsrc) | تنسيق ملف إعداد JavaScript |
| static readonly [JSHINTRC](../../groupdocs.comparison.result/filetype/jshintrc) | أداة جودة كود JavaScript |
| static readonly [JSMAP](../../groupdocs.comparison.result/filetype/jsmap) | ملف JSON يحتوي على معلومات حول كيفية ترجمة الكود مرة أخرى إلى الكود المصدري |
| static readonly [JSON](../../groupdocs.comparison.result/filetype/json) | تنسيق خفيف الوزن لتخزين ونقل البيانات |
| static readonly [LESS](../../groupdocs.comparison.result/filetype/less) | تنسيق لغة أوراق الأنماط للمعالج المسبق الديناميكي |
| static readonly [LOG](../../groupdocs.comparison.result/filetype/log) | التسجيل يحافظ على سجل الأحداث والعمليات والرسائل والاتصالات |
| static readonly [MAKE](../../groupdocs.comparison.result/filetype/make) | Makefile هو ملف يحتوي على مجموعة من التوجيهات المستخدمة بواسطة أداة أتمتة البناء make لتوليد هدف/غاية |
| static readonly [MARKDN](../../groupdocs.comparison.result/filetype/markdn) | تنسيق لغة Markdown |
| static readonly [MARKDOWN](../../groupdocs.comparison.result/filetype/markdown) | تنسيق لغة Markdown |
| static readonly [MD](../../groupdocs.comparison.result/filetype/md) | تنسيق لغة Markdown |
| static readonly [MDOWN](../../groupdocs.comparison.result/filetype/mdown) | تنسيق لغة Markdown |
| static readonly [MDTEXT](../../groupdocs.comparison.result/filetype/mdtext) | تنسيق لغة Markdown |
| static readonly [MDTXT](../../groupdocs.comparison.result/filetype/mdtxt) | تنسيق لغة Markdown |
| static readonly [MDWN](../../groupdocs.comparison.result/filetype/mdwn) | تنسيق لغة Markdown |
| static readonly [MHTML](../../groupdocs.comparison.result/filetype/mhtml) | Mime HTML |
| static readonly [MJS](../../groupdocs.comparison.result/filetype/mjs) | امتداد لملفات وحدات EcmaScript (ES) |
| static readonly [MK](../../groupdocs.comparison.result/filetype/mk) | Makefile هو ملف يحتوي على مجموعة من التوجيهات المستخدمة بواسطة أداة أتمتة البناء make لتوليد هدف/غاية |
| static readonly [MKD](../../groupdocs.comparison.result/filetype/mkd) | تنسيق لغة Markdown |
| static readonly [ML](../../groupdocs.comparison.result/filetype/ml) | تنسيق لغة البرمجة Caml |
| static readonly [MLI](../../groupdocs.comparison.result/filetype/mli) | تنسيق لغة البرمجة Caml |
| static readonly [MOBI](../../groupdocs.comparison.result/filetype/mobi) | تنسيق كتاب إلكتروني Mobipocket |
| static readonly [MSG](../../groupdocs.comparison.result/filetype/msg) | رسالة بريد إلكتروني من Microsoft Outlook |
| static readonly [NQP](../../groupdocs.comparison.result/filetype/nqp) | لغة وسيطة تُستخدم لبناء مترجم Rakudo Perl 6 |
| static readonly [OBJC](../../groupdocs.comparison.result/filetype/objc) | تنسيق لغة البرمجة Objective-C |
| static readonly [OBJCP](../../groupdocs.comparison.result/filetype/objcp) | تنسيق لغة البرمجة Objective-C++ |
| static readonly [ODP](../../groupdocs.comparison.result/filetype/odp) | عرض OpenDocument |
| static readonly [ODS](../../groupdocs.comparison.result/filetype/ods) | جدول بيانات OpenDocument |
| static readonly [ODT](../../groupdocs.comparison.result/filetype/odt) | نص OpenDocument |
| static readonly [ONE](../../groupdocs.comparison.result/filetype/one) | مستند Microsoft OneNote |
| static readonly [OTP](../../groupdocs.comparison.result/filetype/otp) | قالب عرض OpenDocument |
| static readonly [OTT](../../groupdocs.comparison.result/filetype/ott) | قالب نص OpenDocument |
| static readonly [P6](../../groupdocs.comparison.result/filetype/p6) | تنسيق لغة البرمجة Perl |
| static readonly [PAC](../../groupdocs.comparison.result/filetype/pac) | تنسيق ملف تكوين الوكيل التلقائي لوظيفة JavaScript |
| static readonly [PATCH](../../groupdocs.comparison.result/filetype/patch) | تنسيق قائمة الاختلافات |
| static readonly [PDF](../../groupdocs.comparison.result/filetype/pdf) | تنسيق المستند المحمول Adobe |
| static readonly [PHP](../../groupdocs.comparison.result/filetype/php) | تنسيق لغة البرمجة PHP |
| static readonly [PHP4](../../groupdocs.comparison.result/filetype/php4) | تنسيق لغة البرمجة PHP |
| static readonly [PHP5](../../groupdocs.comparison.result/filetype/php5) | تنسيق لغة البرمجة PHP |
| static readonly [PHTML](../../groupdocs.comparison.result/filetype/phtml) | تنسيق الامتداد القياسي لبرامج PHP 2 |
| static readonly [PL](../../groupdocs.comparison.result/filetype/pl) | تنسيق لغة البرمجة Perl |
| static readonly [PL6](../../groupdocs.comparison.result/filetype/pl6) | تنسيق لغة البرمجة Perl |
| static readonly [PM](../../groupdocs.comparison.result/filetype/pm) | تنسيق وحدة Perl |
| static readonly [PM6](../../groupdocs.comparison.result/filetype/pm6) | تنسيق وحدة Perl |
| static readonly [PNG](../../groupdocs.comparison.result/filetype/png) | رسومات الشبكة المحمولة |
| static readonly [POD](../../groupdocs.comparison.result/filetype/pod) | تنسيق لغة الترميز الخفيفة Perl |
| static readonly [PODSPEC](../../groupdocs.comparison.result/filetype/podspec) | تنسيق إعدادات بناء Ruby |
| static readonly [POT](../../groupdocs.comparison.result/filetype/pot) | قالب Microsoft PowerPoint |
| static readonly [POTX](../../groupdocs.comparison.result/filetype/potx) | قالب Microsoft PowerPoint |
| static readonly [PPS](../../groupdocs.comparison.result/filetype/pps) | عرض شرائح Microsoft PowerPoint 97-2003 |
| static readonly [PPSX](../../groupdocs.comparison.result/filetype/ppsx) | عرض شرائح Microsoft PowerPoint |
| static readonly [PPT](../../groupdocs.comparison.result/filetype/ppt) | عرض تقديمي Microsoft PowerPoint 97-2003 |
| static readonly [PPTX](../../groupdocs.comparison.result/filetype/pptx) | عرض تقديمي Microsoft PowerPoint |
| static readonly [PROP](../../groupdocs.comparison.result/filetype/prop) | تنسيق ملف الخصائص |
| static readonly [PSGI](../../groupdocs.comparison.result/filetype/psgi) | واجهة بين خوادم الويب وتطبيقات الويب والأطر المكتوبة بلغة البرمجة Perl |
| static readonly [PY](../../groupdocs.comparison.result/filetype/py) | تنسيق لغة البرمجة Python |
| static readonly [PYI](../../groupdocs.comparison.result/filetype/pyi) | تنسيق ملف واجهة Python |
| static readonly [PYW](../../groupdocs.comparison.result/filetype/pyw) | الملفات المستخدمة في Windows للإشارة إلى ضرورة تشغيل البرنامج النصي |
| static readonly [RAKE](../../groupdocs.comparison.result/filetype/rake) | أداة أتمتة بناء Ruby |
| static readonly [RB](../../groupdocs.comparison.result/filetype/rb) | تنسيق لغة البرمجة Ruby |
| static readonly [RBI](../../groupdocs.comparison.result/filetype/rbi) | تنسيق ملف واجهة Ruby |
| static readonly [REJ](../../groupdocs.comparison.result/filetype/rej) | تنسيق الملفات المرفوضة |
| static readonly [RJS](../../groupdocs.comparison.result/filetype/rjs) | تنسيق لغة البرمجة Ruby |
| static readonly [RPY](../../groupdocs.comparison.result/filetype/rpy) | محرك ملفات مبني على Python لإنشاء وتشغيل الألعاب |
| static readonly [RST](../../groupdocs.comparison.result/filetype/rst) | لغة توصيف خفيفة الوزن |
| static readonly [RTF](../../groupdocs.comparison.result/filetype/rtf) | مستند نص غني |
| static readonly [RU](../../groupdocs.comparison.result/filetype/ru) | تنسيق ملف تكوين Rack |
| static readonly [SASS](../../groupdocs.comparison.result/filetype/sass) | تنسيق لغة أوراق الأنماط |
| static readonly [SBT](../../groupdocs.comparison.result/filetype/sbt) | تنسيق أداة بناء SBT للغة Scala |
| static readonly [SC](../../groupdocs.comparison.result/filetype/sc) | تنسيق ورقة عمل Scala |
| static readonly [SCALA](../../groupdocs.comparison.result/filetype/scala) | تنسيق لغة البرمجة Scala |
| static readonly [SCSS](../../groupdocs.comparison.result/filetype/scss) | تنسيق لغة أوراق الأنماط |
| static readonly [SH](../../groupdocs.comparison.result/filetype/sh) | تنسيق برنامج نصي مبرمج لـ bash |
| static readonly [SQL](../../groupdocs.comparison.result/filetype/sql) | تنسيق لغة الاستعلام البنيوية |
| static readonly [SVG](../../groupdocs.comparison.result/filetype/svg) | رسومات المتجهات السكالارية |
| static readonly [T](../../groupdocs.comparison.result/filetype/t) | تنسيق ملف اختبار Perl |
| static readonly [TXT](../../groupdocs.comparison.result/filetype/txt) | مستند نص عادي |
| static readonly [UNKNOWN](../../groupdocs.comparison.result/filetype/unknown) | نوع غير معروف |
| static readonly [VDX](../../groupdocs.comparison.result/filetype/vdx) | رسم XML لبرنامج Microsoft Visio 2003-2010 |
| static readonly [VIM](../../groupdocs.comparison.result/filetype/vim) | تنسيق ملف شفرة المصدر Vim |
| static readonly [VSD](../../groupdocs.comparison.result/filetype/vsd) | رسم Microsoft Visio 2003-2010 |
| static readonly [VSDX](../../groupdocs.comparison.result/filetype/vsdx) | رسم Microsoft Visio |
| static readonly [VSS](../../groupdocs.comparison.result/filetype/vss) | قالب رسومي Microsoft Visio 2003-2010 |
| static readonly [VST](../../groupdocs.comparison.result/filetype/vst) | قالب Microsoft Visio 2003-2010 |
| static readonly [WEBMANIFEST](../../groupdocs.comparison.result/filetype/webmanifest) | ملف البيان يتضمن معلومات حول التطبيق |
| static readonly [XLS](../../groupdocs.comparison.result/filetype/xls) | ورقة عمل Microsoft Excel 97-2003 |
| static readonly [XLSB](../../groupdocs.comparison.result/filetype/xlsb) | ورقة عمل ثنائية Microsoft Excel |
| static readonly [XLSM](../../groupdocs.comparison.result/filetype/xlsm) | ورقة عمل Microsoft Excel مدعومة بالماكرو |
| static readonly [XLSX](../../groupdocs.comparison.result/filetype/xlsx) | ورقة عمل Microsoft Excel |
| static readonly [XLT](../../groupdocs.comparison.result/filetype/xlt) | قالب Microsoft Excel |
| static readonly [XLTM](../../groupdocs.comparison.result/filetype/xltm) | قالب Microsoft Excel مدعوم بالماكرو |
| static readonly [YAML](../../groupdocs.comparison.result/filetype/yaml) | تنسيق لغة تسلسل البيانات القابل للقراءة من قبل الإنسان |
| static readonly [YML](../../groupdocs.comparison.result/filetype/yml) | تنسيق لغة تسلسل البيانات القابل للقراءة من قبل الإنسان |

### ملاحظات

**Learn more**

* Learn more about file formats supported by GroupDocs.Comparison: [Full list of supported document formats](https://docs.groupdocs.com/display/comparisonnet/Supported+Document+Formats)
* Learn more about getting supported file types in C#: [How to get supported file formats in C#](https://docs.groupdocs.com/display/comparisonnet/Get+supported+file+formats)

### انظر أيضًا

* namespace [GroupDocs.Comparison.Result](../../groupdocs.comparison.result)
* assembly [GroupDocs.Comparison](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldoccmd لـ GroupDocs.Comparison.dll -->
