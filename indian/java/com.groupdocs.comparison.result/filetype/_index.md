---
title: "FileType"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "FileType enum दस्तावेज़ तुलना प्रक्रिया में उपयोग की जाने वाली फ़ाइल के प्रकार को दर्शाता है।"
type: docs
weight: 16
url: /hi/java/com.groupdocs.comparison.result/filetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public enum FileType extends Enum<FileType> implements System.IEquatable<FileType>
```

FileType enum दस्तावेज़ तुलना प्रक्रिया में उपयोग की जाने वाली फ़ाइल के प्रकार को दर्शाता है।


यह विभिन्न फ़ाइल प्रकारों को परिभाषित करता है जैसे Word दस्तावेज़, PDF फ़ाइलें, और अधिक।
GroupDocs.Comparison द्वारा समर्थित सभी फ़ाइल प्रकारों की सूची प्राप्त करने, एक्सटेंशन द्वारा फ़ाइल प्रकार का पता लगाने आदि के लिए विधियाँ प्रदान करता है।
GroupDocs.Comparison लाइब्रेरी के साथ काम करते समय फ़ाइल प्रकार निर्दिष्ट करने के लिए इस enum का उपयोग करें।

* Learn more about file formats supported by GroupDocs.Comparison: [Full list of supported document formats](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* Learn more about getting supported file types in Java: [How to get supported file formats in Java](../https://docs.groupdocs.com/display/comparisonjava/Get+supported+file+formats)


उदाहरण उपयोग:

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


## फ़ील्ड

| फ़ील्ड | विवरण |
| --- | --- |
|  | [UNKNOWN](#UNKNOWN) | अज्ञात प्रकार |
|
|  | [AS](#AS) | ActionScript प्रोग्रामिंग भाषा फ़ॉर्मेट |
|
|  | [AS3](#AS3) | ActionScript प्रोग्रामिंग भाषा फ़ॉर्मेट |
|
|  | [ASM](#ASM) | Assembler प्रोग्रामिंग भाषा फ़ॉर्मेट |
|
|  | [BAT](#BAT) | DOS, OS/2 और Microsoft Windows में स्क्रिप्ट फ़ाइल |
|
|  | [CMD](#CMD) | DOS, OS/2 और Microsoft Windows में स्क्रिप्ट फ़ाइल |
|
|  | [C](#C) | C-आधारित प्रोग्रामिंग भाषा फ़ॉर्मेट |
|
|  | [H](#H) | C-आधारित हेडर फ़ाइलों में फ़ंक्शन्स और वेरिएबल्स की परिभाषाएँ होती हैं |
|
|  | [PDF](#PDF) | Adobe पोर्टेबल डॉक्यूमेंट फ़ॉर्मेट |
|
|  | [DOC](#DOC) | Microsoft Word 97-2003 दस्तावेज़ |
|
|  | [DOCM](#DOCM) | Microsoft Word मैक्रो-सक्षम दस्तावेज़ |
|
|  | [DOCX](#DOCX) | Microsoft Word दस्तावेज़ |
|
|  | [DOT](#DOT) | Microsoft Word 97-2003 टेम्पलेट |
|
|  | [DOTM](#DOTM) | Microsoft Word मैक्रो-सक्षम टेम्पलेट |
|
|  | [DOTX](#DOTX) | Microsoft Word टेम्पलेट |
|
|  | [XLS](#XLS) | Microsoft Excel 97-2003 कार्यपत्रक |
|
|  | [XLT](#XLT) | Microsoft Excel टेम्पलेट |
|
|  | [XLSX](#XLSX) | Microsoft Excel कार्यपत्रक |
|
|  | [XLTM](#XLTM) | Microsoft Excel मैक्रो-सक्षम टेम्पलेट |
|
|  | [XLSB](#XLSB) | Microsoft Excel बाइनरी वर्कशीट |
|
|  | [XLSM](#XLSM) | Microsoft Excel मैक्रो-सक्षम वर्कशीट |
|
|  | [POT](#POT) | Microsoft PowerPoint टेम्पलेट |
|
|  | [POTX](#POTX) | Microsoft PowerPoint टेम्पलेट |
|
|  | [POTM](#POTM) | Microsoft PowerPoint टेम्पलेट जिसमें मैक्रो समर्थन है |
|
|  | [PPS](#PPS) | Microsoft PowerPoint 97-2003 स्लाइड शो |
|
|  | [PPSX](#PPSX) | Microsoft PowerPoint स्लाइड शो |
|
|  | [PPTX](#PPTX) | Microsoft PowerPoint प्रस्तुति |
|
|  | [PPT](#PPT) | Microsoft PowerPoint 97-2003 प्रस्तुति |
|
|  | [PPTM](#PPTM) | Microsoft PowerPoint मैक्रो-सक्षम प्रस्तुति |
|
|  | [PPSM](#PPSM) | Microsoft PowerPoint मैक्रो-सक्षम स्लाइड शो प्रस्तुति |
|
|  | [VSDX](#VSDX) | Microsoft Visio ड्राइंग |
|
|  | [VSD](#VSD) | Microsoft Visio 2003-2010 ड्राइंग |
|
|  | [VSS](#VSS) | Microsoft Visio 2003-2010 स्टेंसिल |
|
|  | [VST](#VST) | Microsoft Visio 2003-2010 टेम्पलेट |
|
|  | [VDX](#VDX) | Microsoft Visio 2003-2010 XML ड्राइंग |
|
|  | [ONE](#ONE) | Microsoft OneNote दस्तावेज़ |
|
|  | [ODT](#ODT) | OpenDocument टेक्स्ट |
|
|  | [ODP](#ODP) | OpenDocument प्रस्तुति |
|
|  | [OTP](#OTP) | OpenDocument प्रस्तुति टेम्पलेट |
|
|  | [ODS](#ODS) | OpenDocument स्प्रेडशीट |
|
|  | [OTT](#OTT) | OpenDocument टेक्स्ट टेम्पलेट |
|
|  | [RTF](#RTF) | रिच टेक्स्ट दस्तावेज़ |
|
|  | [TXT](#TXT) | सादा टेक्स्ट दस्तावेज़ |
|
|  | [CSV](#CSV) | कॉमा सेपरेटेड वैल्यूज़ फ़ाइल |
|
|  | [HTML](#HTML) | हाइपरटेक्स्ट मार्कअप भाषा |
|
|  | [MHTML](#MHTML) | माइम एचटीएमएल |
|
|  | [MOBI](#MOBI) | मोबिपॉकेट ई-बुक फ़ॉर्मेट |
|
|  | [DCM](#DCM) | डिजिटल इमेजिंग और मेडिसिन में संचार |
|
|  | [DJVU](#DJVU) | डेज़ा वु फ़ॉर्मेट |
|
|  | [DWG](#DWG) | ऑटोडेस्क डिज़ाइन डेटा फ़ॉर्मेट्स |
|
|  | [DXF](#DXF) | ऑटोकैड ड्राइंग इंटरचेंज |
|
|  | [BMP](#BMP) | बिटमैप चित्र |
|
|  | [GIF](#GIF) | ग्राफिक्स इंटरचेंज फ़ॉर्मेट |
|
|  | [JPEG](#JPEG) | जॉइंट फ़ोटोग्राफ़िक एक्सपर्ट्स ग्रुप |
|
|  | [JPG](#JPG) | जॉइंट फ़ोटोग्राफ़िक एक्सपर्ट्स ग्रुप |
|
|  | [PNG](#PNG) | पोर्टेबल नेटवर्क ग्राफ़िक्स |
|
|  | [SVG](#SVG) | स्केलर वेक्टर ग्राफ़िक्स |
|
|  | [EML](#EML) | ई-मेल संदेश |
|
|  | [EMLX](#EMLX) | एपल मेल ई-मेल फ़ाइल |
|
|  | [MSG](#MSG) | माइक्रोसॉफ्ट आउटलुक ई-मेल संदेश |
|
|  | [CAD](#CAD) | सीएडी फ़ाइल फ़ॉर्मेट |
|
|  | [CPP](#CPP) | C-आधारित प्रोग्रामिंग भाषा फ़ॉर्मेट |
|
|  | [CC](#CC) | C-आधारित प्रोग्रामिंग भाषा फ़ॉर्मेट |
|
|  | [CXX](#CXX) | C-आधारित प्रोग्रामिंग भाषा फ़ॉर्मेट |
|
|  | [HXX](#HXX) | हेडर फ़ाइलें जो C++ प्रोग्रामिंग भाषा में लिखी गई हैं |
|
|  | [HH](#HH) | हेडर जानकारी जिसे C++ स्रोत कोड फ़ाइल द्वारा संदर्भित किया गया है |
|
|  | [HPP](#HPP) | हेडर फ़ाइलें जो C++ प्रोग्रामिंग भाषा में लिखी गई हैं |
|
|  | [CMAKE](#CMAKE) | सॉफ़्टवेयर के बिल्ड प्रक्रिया को प्रबंधित करने के लिए टूल |
|
|  | [CS](#CS) | CSharp प्रोग्रामिंग भाषा फ़ॉर्मेट |
|
|  | [CSX](#CSX) | CSharp स्क्रिप्ट फ़ाइल फ़ॉर्मेट |
|
|  | [CAKE](#CAKE) | CSharp क्रॉस-प्लेटफ़ॉर्म बिल्ड ऑटोमेशन सिस्टम फ़ॉर्मेट |
|
|  | [DIFF](#DIFF) | डेटा तुलना टूल फ़ॉर्मेट |
|
|  | [PATCH](#PATCH) | भिन्नताओं की सूची फ़ॉर्मेट |
|
|  | [REJ](#REJ) | अस्वीकृत फ़ाइलें फ़ॉर्मेट |
|
|  | [GROOVY](#GROOVY) | Groovy फ़ॉर्मेट में लिखा गया स्रोत कोड फ़ाइल |
|
|  | [GVY](#GVY) | Groovy फ़ॉर्मेट में लिखा गया स्रोत कोड फ़ाइल |
|
|  | [GRADLE](#GRADLE) | बिल्ड-ऑटोमेशन सिस्टम फ़ॉर्मेट |
|
|  | [HAML](#HAML) | सरलीकृत HTML निर्माण के लिए मार्कअप भाषा |
|
|  | [JS](#JS) | JavaScript प्रोग्रामिंग भाषा फ़ॉर्मेट |
|
|  | [ES6](#ES6) | JavaScript मानकीकृत स्क्रिप्टिंग भाषा फ़ॉर्मेट |
|
|  | [MJS](#MJS) | EcmaScript (ES) मॉड्यूल फ़ाइलों के लिए एक्सटेंशन |
|
|  | [PAC](#PAC) | JavaScript फ़ंक्शन फ़ॉर्मेट के लिए प्रॉक्सी ऑटो-कॉन्फ़िगरेशन फ़ाइल |
|
|  | [JSON](#JSON) | डेटा को संग्रहीत और परिवहन करने के लिए हल्का फ़ॉर्मेट |
|
|  | [BOWERRC](#BOWERRC) | सर्वर-साइड पर पैकेज नियंत्रण के लिए कॉन्फ़िगरेशन फ़ाइल |
|
|  | [JSHINTRC](#JSHINTRC) | JavaScript कोड गुणवत्ता उपकरण |
|
|  | [JSCSRC](#JSCSRC) | JavaScript कॉन्फ़िगरेशन फ़ाइल फ़ॉर्मेट |
|
|  | [WEBMANIFEST](#WEBMANIFEST) | मैनिफेस्ट फ़ाइल में ऐप के बारे में जानकारी शामिल है |
|
|  | [JSMAP](#JSMAP) | JSON फ़ाइल जिसमें कोड को वापस स्रोत कोड में अनुवाद करने के बारे में जानकारी होती है |
|
|  | [HAR](#HAR) | HTTP आर्काइव फ़ॉर्मेट |
|
|  | [JAVA](#JAVA) | Java प्रोग्रामिंग भाषा फ़ॉर्मेट |
|
|  | [LESS](#LESS) | डायनामिक प्रीप्रोसेसर स्टाइल शीट भाषा फ़ॉर्मेट |
|
|  | [LOG](#LOG) | लॉगिंग घटनाओं, प्रक्रियाओं, संदेशों और संचार की रजिस्ट्री रखती है |
|
|  | [MAKE](#MAKE) | Makefile एक फ़ाइल है जिसमें निर्देशों का सेट होता है जिसे मेक बिल्ड ऑटोमेशन टूल द्वारा लक्ष्य/उद्देश्य उत्पन्न करने के लिए उपयोग किया जाता है |
|
|  | [MK](#MK) | Makefile एक फ़ाइल है जिसमें निर्देशों का सेट होता है जिसे मेक बिल्ड ऑटोमेशन टूल द्वारा लक्ष्य/उद्देश्य उत्पन्न करने के लिए उपयोग किया जाता है |
|
|  | [MD](#MD) | मार्कडाउन भाषा फ़ॉर्मेट |
|
|  | [MKD](#MKD) | मार्कडाउन भाषा फ़ॉर्मेट |
|
|  | [MDWN](#MDWN) | मार्कडाउन भाषा फ़ॉर्मेट |
|
|  | [MDOWN](#MDOWN) | मार्कडाउन भाषा फ़ॉर्मेट |
|
|  | [MARKDOWN](#MARKDOWN) | मार्कडाउन भाषा फ़ॉर्मेट |
|
|  | [MARKDN](#MARKDN) | मार्कडाउन भाषा फ़ॉर्मेट |
|
|  | [MDTXT](#MDTXT) | मार्कडाउन भाषा फ़ॉर्मेट |
|
|  | [MDTEXT](#MDTEXT) | मार्कडाउन भाषा फ़ॉर्मेट |
|
|  | [ML](#ML) | Caml प्रोग्रामिंग भाषा फ़ॉर्मेट |
|
|  | [MLI](#MLI) | Caml प्रोग्रामिंग भाषा फ़ॉर्मेट |
|
|  | [OBJC](#OBJC) | Objective-C प्रोग्रामिंग भाषा फ़ॉर्मेट |
|
|  | [OBJCP](#OBJCP) | Objective-C++ प्रोग्रामिंग भाषा फ़ॉर्मेट |
|
|  | [PHP](#PHP) | PHP प्रोग्रामिंग भाषा फ़ॉर्मेट |
|
|  | [PHP4](#PHP4) | PHP प्रोग्रामिंग भाषा फ़ॉर्मेट |
|
|  | [PHP5](#PHP5) | PHP प्रोग्रामिंग भाषा फ़ॉर्मेट |
|
|  | [PHTML](#PHTML) | PHP 2 प्रोग्रामों के लिए मानक फ़ाइल एक्सटेंशन फ़ॉर्मेट |
|
|  | [CTP](#CTP) | CakePHP टेम्प्लेट फ़ॉर्मेट |
|
|  | [PL](#PL) | Perl प्रोग्रामिंग भाषा फ़ॉर्मेट |
|
|  | [PM](#PM) | Perl मॉड्यूल फ़ॉर्मेट |
|
|  | [POD](#POD) | Perl लाइटवेट मार्कअप भाषा फ़ॉर्मेट |
|
|  | [T](#T) | Perl टेस्ट फ़ाइल फ़ॉर्मेट |
|
|  | [PSGI](#PSGI) | Perl प्रोग्रामिंग में लिखे गए वेब सर्वरों और वेब एप्लिकेशन तथा फ्रेमवर्क्स के बीच इंटरफ़ेस |
|
|  | [P6](#P6) | Perl प्रोग्रामिंग भाषा फ़ॉर्मेट |
|
|  | [PL6](#PL6) | Perl प्रोग्रामिंग भाषा फ़ॉर्मेट |
|
|  | [PM6](#PM6) | Perl मॉड्यूल फ़ॉर्मेट |
|
|  | [NQP](#NQP) | Rakudo Perl 6 कंपाइलर बनाने के लिए उपयोग की जाने वाली मध्यवर्ती भाषा |
|
|  | [PROP](#PROP) | प्रॉपर्टीज़ फ़ाइल फ़ॉर्मेट |
|
|  | [CFG](#CFG) | सेटिंग्स संग्रहीत करने के लिए उपयोग की जाने वाली कॉन्फ़िगरेशन फ़ाइल |
|
|  | [CONF](#CONF) | Unix और Linux आधारित सिस्टम पर उपयोग की जाने वाली कॉन्फ़िगरेशन फ़ाइल |
|
|  | [DIR](#DIR) | डायरेक्टरी कंप्यूटर पर फ़ाइलें संग्रहीत करने का स्थान है |
|
|  | [PY](#PY) | Python प्रोग्रामिंग भाषा फ़ॉर्मेट |
|
|  | [RPY](#RPY) | गेम बनाने और चलाने के लिए Python-आधारित फ़ाइल इंजन |
|
|  | [PYW](#PYW) | Windows में उपयोग की जाने वाली फ़ाइलें जो संकेत देती हैं कि स्क्रिप्ट चलाने की आवश्यकता है |
|
|  | [CPY](#CPY) | कंट्रोलर Python स्क्रिप्ट फ़ॉर्मेट |
|
|  | [GYP](#GYP) | बिल्ड ऑटोमेशन टूल फ़ॉर्मेट |
|
|  | [GYPI](#GYPI) | बिल्ड ऑटोमेशन टूल फ़ॉर्मेट |
|
|  | [PYI](#PYI) | Python इंटरफ़ेस फ़ाइल फ़ॉर्मेट |
|
|  | [IPY](#IPY) | IPython स्क्रिप्ट फ़ॉर्मेट |
|
|  | [RST](#RST) | लाइटवेट मार्कअप भाषा |
|
|  | [RB](#RB) | Ruby प्रोग्रामिंग भाषा फ़ॉर्मेट |
|
|  | [ERB](#ERB) | Ruby प्रोग्रामिंग भाषा फ़ॉर्मेट |
|
|  | [RJS](#RJS) | Ruby प्रोग्रामिंग भाषा फ़ॉर्मेट |
|
|  | [GEMSPEC](#GEMSPEC) | डेवलपर फ़ाइल जो RubyGems के गुणों को निर्दिष्ट करती है |
|
|  | [RAKE](#RAKE) | Ruby बिल्ड ऑटोमेशन टूल |
|
|  | [RU](#RU) | Rack कॉन्फ़िगरेशन फ़ाइल फ़ॉर्मेट |
|
|  | [PODSPEC](#PODSPEC) | Ruby बिल्ड सेटिंग्स फ़ॉर्मेट |
|
|  | [RBI](#RBI) | Ruby इंटरफ़ेस फ़ाइल फ़ॉर्मेट |
|
|  | [SASS](#SASS) | स्टाइल शीट भाषा फ़ॉर्मेट |
|
|  | [SCSS](#SCSS) | स्टाइल शीट भाषा फ़ॉर्मेट |
|
|  | [SCALA](#SCALA) | Scala प्रोग्रामिंग भाषा फ़ॉर्मेट |
|
|  | [SBT](#SBT) | Scala के लिए SBT बिल्ड टूल फ़ॉर्मेट |
|
|  | [SC](#SC) | Scala वर्कशीट फ़ॉर्मेट |
|
|  | [SH](#SH) | bash के लिए प्रोग्राम किया गया स्क्रिप्ट फ़ॉर्मेट |
|
|  | [BASH](#BASH) | शेल कमांड्स को प्रोसेस करने वाला इंटरप्रेटर प्रकार |
|
|  | [BASHRC](#BASHRC) | फ़ाइल इंटरैक्टिव शेल्स के व्यवहार को निर्धारित करती है |
|
|  | [EBUILD](#EBUILD) | सॉफ़्टवेयर पैकेजों के लिए संकलन और इंस्टॉलेशन प्रक्रियाओं को स्वचालित करने वाली विशेषीकृत bash स्क्रिप्ट |
|
|  | [SQL](#SQL) | Structured Query Language फ़ॉर्मेट |
|
|  | [DSQL](#DSQL) | Dynamic Structured Query Language फ़ॉर्मेट |
|
|  | [VIM](#VIM) | Vim स्रोत कोड फ़ाइल फ़ॉर्मेट |
|
|  | [YAML](#YAML) | मानव-पठनीय डेटा-सीरियलाइज़ेशन भाषा फ़ॉर्मेट |
|
|  | [YML](#YML) | मानव-पठनीय डेटा-सीरियलाइज़ेशन भाषा फ़ॉर्मेट |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromFileNameOrExtension(String value)](#fromFileNameOrExtension-java.lang.String-) | फ़ाइल नाम या एक्सटेंशन के आधार पर FileType लौटाएँ |
|
|  | [getSupportedFileTypes()](#getSupportedFileTypes--) | समर्थित फ़ाइल प्रकारों की सूची प्राप्त करता है |
|
|  | [areEquals(FileType left, FileType right)](#areEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-) | प्रदान किए गए फ़ाइल प्रकारों की समानता जाँचता है |
|
|  | [areNotEquals(FileType left, FileType right)](#areNotEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-) | जाँचता है कि प्रदान किए गए फ़ाइल प्रकार समान नहीं हैं |
|
|  | [getFileFormat()](#getFileFormat--) | फ़ाइल प्रकार का टेक्स्ट विवरण प्राप्त करता है |
|
|  | [getExtension()](#getExtension--) | फ़ाइल प्रकार का एक्सटेंशन प्राप्त करता है |
|
|  | [toString()](#toString--) | उदाहरण के लिए, [FileType](../../com.groupdocs.comparison.result/filetype) की स्ट्रिंग प्रतिनिधित्व प्राप्त करता है |
'PHP प्रोग्रामिंग भाषा फ़ॉर्मेट (.php)'

|
### UNKNOWN {#UNKNOWN}
```
public static final FileType UNKNOWN
```


अज्ञात प्रकार


### AS {#AS}
```
public static final FileType AS
```


ActionScript प्रोग्रामिंग भाषा फ़ॉर्मेट


### AS3 {#AS3}
```
public static final FileType AS3
```


ActionScript प्रोग्रामिंग भाषा फ़ॉर्मेट


### ASM {#ASM}
```
public static final FileType ASM
```


Assembler प्रोग्रामिंग भाषा फ़ॉर्मेट


### BAT {#BAT}
```
public static final FileType BAT
```


DOS, OS/2 और Microsoft Windows में स्क्रिप्ट फ़ाइल


### CMD {#CMD}
```
public static final FileType CMD
```


DOS, OS/2 और Microsoft Windows में स्क्रिप्ट फ़ाइल


### C {#C}
```
public static final FileType C
```


C-आधारित प्रोग्रामिंग भाषा फ़ॉर्मेट


### H {#H}
```
public static final FileType H
```


C-आधारित हेडर फ़ाइलों में फ़ंक्शन्स और वेरिएबल्स की परिभाषाएँ होती हैं


### PDF {#PDF}
```
public static final FileType PDF
```


Adobe पोर्टेबल डॉक्यूमेंट फ़ॉर्मेट


### DOC {#DOC}
```
public static final FileType DOC
```


Microsoft Word 97-2003 दस्तावेज़


### DOCM {#DOCM}
```
public static final FileType DOCM
```


Microsoft Word मैक्रो-सक्षम दस्तावेज़


### DOCX {#DOCX}
```
public static final FileType DOCX
```


Microsoft Word दस्तावेज़


### DOT {#DOT}
```
public static final FileType DOT
```


Microsoft Word 97-2003 टेम्पलेट


### DOTM {#DOTM}
```
public static final FileType DOTM
```


Microsoft Word मैक्रो-सक्षम टेम्पलेट


### DOTX {#DOTX}
```
public static final FileType DOTX
```


Microsoft Word टेम्पलेट


### XLS {#XLS}
```
public static final FileType XLS
```


Microsoft Excel 97-2003 कार्यपत्रक


### XLT {#XLT}
```
public static final FileType XLT
```


Microsoft Excel टेम्पलेट


### XLSX {#XLSX}
```
public static final FileType XLSX
```


Microsoft Excel कार्यपत्रक


### XLTM {#XLTM}
```
public static final FileType XLTM
```


Microsoft Excel मैक्रो-सक्षम टेम्पलेट


### XLSB {#XLSB}
```
public static final FileType XLSB
```


Microsoft Excel बाइनरी वर्कशीट


### XLSM {#XLSM}
```
public static final FileType XLSM
```


Microsoft Excel मैक्रो-सक्षम वर्कशीट


### POT {#POT}
```
public static final FileType POT
```


Microsoft PowerPoint टेम्पलेट


### POTX {#POTX}
```
public static final FileType POTX
```


Microsoft PowerPoint टेम्पलेट


### POTM {#POTM}
```
public static final FileType POTM
```


Microsoft PowerPoint टेम्पलेट जिसमें मैक्रो समर्थन है


### PPS {#PPS}
```
public static final FileType PPS
```


Microsoft PowerPoint 97-2003 स्लाइड शो


### PPSX {#PPSX}
```
public static final FileType PPSX
```


Microsoft PowerPoint स्लाइड शो


### PPTX {#PPTX}
```
public static final FileType PPTX
```


Microsoft PowerPoint प्रस्तुति


### PPT {#PPT}
```
public static final FileType PPT
```


Microsoft PowerPoint 97-2003 प्रस्तुति


### PPTM {#PPTM}
```
public static final FileType PPTM
```


Microsoft PowerPoint मैक्रो-सक्षम प्रस्तुति


### PPSM {#PPSM}
```
public static final FileType PPSM
```


Microsoft PowerPoint मैक्रो-सक्षम स्लाइड शो प्रस्तुति


### VSDX {#VSDX}
```
public static final FileType VSDX
```


Microsoft Visio ड्राइंग


### VSD {#VSD}
```
public static final FileType VSD
```


Microsoft Visio 2003-2010 ड्राइंग


### VSS {#VSS}
```
public static final FileType VSS
```


Microsoft Visio 2003-2010 स्टेंसिल


### VST {#VST}
```
public static final FileType VST
```


Microsoft Visio 2003-2010 टेम्पलेट


### VDX {#VDX}
```
public static final FileType VDX
```


Microsoft Visio 2003-2010 XML ड्राइंग


### ONE {#ONE}
```
public static final FileType ONE
```


Microsoft OneNote दस्तावेज़


### ODT {#ODT}
```
public static final FileType ODT
```


OpenDocument टेक्स्ट


### ODP {#ODP}
```
public static final FileType ODP
```


OpenDocument प्रस्तुति


### OTP {#OTP}
```
public static final FileType OTP
```


OpenDocument प्रस्तुति टेम्पलेट


### ODS {#ODS}
```
public static final FileType ODS
```


OpenDocument स्प्रेडशीट


### OTT {#OTT}
```
public static final FileType OTT
```


OpenDocument टेक्स्ट टेम्पलेट


### RTF {#RTF}
```
public static final FileType RTF
```


रिच टेक्स्ट दस्तावेज़


### TXT {#TXT}
```
public static final FileType TXT
```


सादा टेक्स्ट दस्तावेज़


### CSV {#CSV}
```
public static final FileType CSV
```


कॉमा सेपरेटेड वैल्यूज़ फ़ाइल


### HTML {#HTML}
```
public static final FileType HTML
```


हाइपरटेक्स्ट मार्कअप भाषा


### MHTML {#MHTML}
```
public static final FileType MHTML
```


माइम एचटीएमएल


### MOBI {#MOBI}
```
public static final FileType MOBI
```


मोबिपॉकेट ई-बुक फ़ॉर्मेट


### DCM {#DCM}
```
public static final FileType DCM
```


डिजिटल इमेजिंग और मेडिसिन में संचार


### DJVU {#DJVU}
```
public static final FileType DJVU
```


डेज़ा वु फ़ॉर्मेट


### DWG {#DWG}
```
public static final FileType DWG
```


ऑटोडेस्क डिज़ाइन डेटा फ़ॉर्मेट्स


### DXF {#DXF}
```
public static final FileType DXF
```


ऑटोकैड ड्राइंग इंटरचेंज


### BMP {#BMP}
```
public static final FileType BMP
```


बिटमैप चित्र


### GIF {#GIF}
```
public static final FileType GIF
```


ग्राफिक्स इंटरचेंज फ़ॉर्मेट


### JPEG {#JPEG}
```
public static final FileType JPEG
```


जॉइंट फ़ोटोग्राफ़िक एक्सपर्ट्स ग्रुप


### JPG {#JPG}
```
public static final FileType JPG
```


जॉइंट फ़ोटोग्राफ़िक एक्सपर्ट्स ग्रुप


### PNG {#PNG}
```
public static final FileType PNG
```


पोर्टेबल नेटवर्क ग्राफ़िक्स


### SVG {#SVG}
```
public static final FileType SVG
```


स्केलर वेक्टर ग्राफ़िक्स


### EML {#EML}
```
public static final FileType EML
```


ई-मेल संदेश


### EMLX {#EMLX}
```
public static final FileType EMLX
```


एपल मेल ई-मेल फ़ाइल


### MSG {#MSG}
```
public static final FileType MSG
```


माइक्रोसॉफ्ट आउटलुक ई-मेल संदेश


### CAD {#CAD}
```
public static final FileType CAD
```


सीएडी फ़ाइल फ़ॉर्मेट


### CPP {#CPP}
```
public static final FileType CPP
```


C-आधारित प्रोग्रामिंग भाषा फ़ॉर्मेट


### CC {#CC}
```
public static final FileType CC
```


C-आधारित प्रोग्रामिंग भाषा फ़ॉर्मेट


### CXX {#CXX}
```
public static final FileType CXX
```


C-आधारित प्रोग्रामिंग भाषा फ़ॉर्मेट


### HXX {#HXX}
```
public static final FileType HXX
```


हेडर फ़ाइलें जो C++ प्रोग्रामिंग भाषा में लिखी गई हैं


### HH {#HH}
```
public static final FileType HH
```


हेडर जानकारी जिसे C++ स्रोत कोड फ़ाइल द्वारा संदर्भित किया गया है


### HPP {#HPP}
```
public static final FileType HPP
```


हेडर फ़ाइलें जो C++ प्रोग्रामिंग भाषा में लिखी गई हैं


### CMAKE {#CMAKE}
```
public static final FileType CMAKE
```


सॉफ़्टवेयर के बिल्ड प्रक्रिया को प्रबंधित करने के लिए टूल


### CS {#CS}
```
public static final FileType CS
```


CSharp प्रोग्रामिंग भाषा फ़ॉर्मेट


### CSX {#CSX}
```
public static final FileType CSX
```


CSharp स्क्रिप्ट फ़ाइल फ़ॉर्मेट


### CAKE {#CAKE}
```
public static final FileType CAKE
```


CSharp क्रॉस-प्लेटफ़ॉर्म बिल्ड ऑटोमेशन सिस्टम फ़ॉर्मेट


### DIFF {#DIFF}
```
public static final FileType DIFF
```


डेटा तुलना टूल फ़ॉर्मेट


### PATCH {#PATCH}
```
public static final FileType PATCH
```


भिन्नताओं की सूची फ़ॉर्मेट


### REJ {#REJ}
```
public static final FileType REJ
```


अस्वीकृत फ़ाइलें फ़ॉर्मेट


### GROOVY {#GROOVY}
```
public static final FileType GROOVY
```


Groovy फ़ॉर्मेट में लिखा गया स्रोत कोड फ़ाइल


### GVY {#GVY}
```
public static final FileType GVY
```


Groovy फ़ॉर्मेट में लिखा गया स्रोत कोड फ़ाइल


### GRADLE {#GRADLE}
```
public static final FileType GRADLE
```


बिल्ड-ऑटोमेशन सिस्टम फ़ॉर्मेट


### HAML {#HAML}
```
public static final FileType HAML
```


सरलीकृत HTML निर्माण के लिए मार्कअप भाषा


### JS {#JS}
```
public static final FileType JS
```


JavaScript प्रोग्रामिंग भाषा फ़ॉर्मेट


### ES6 {#ES6}
```
public static final FileType ES6
```


JavaScript मानकीकृत स्क्रिप्टिंग भाषा फ़ॉर्मेट


### MJS {#MJS}
```
public static final FileType MJS
```


EcmaScript (ES) मॉड्यूल फ़ाइलों के लिए एक्सटेंशन


### PAC {#PAC}
```
public static final FileType PAC
```


JavaScript फ़ंक्शन फ़ॉर्मेट के लिए प्रॉक्सी ऑटो-कॉन्फ़िगरेशन फ़ाइल


### JSON {#JSON}
```
public static final FileType JSON
```


डेटा को संग्रहीत और परिवहन करने के लिए हल्का फ़ॉर्मेट


### BOWERRC {#BOWERRC}
```
public static final FileType BOWERRC
```


सर्वर-साइड पर पैकेज नियंत्रण के लिए कॉन्फ़िगरेशन फ़ाइल


### JSHINTRC {#JSHINTRC}
```
public static final FileType JSHINTRC
```


JavaScript कोड गुणवत्ता उपकरण


### JSCSRC {#JSCSRC}
```
public static final FileType JSCSRC
```


JavaScript कॉन्फ़िगरेशन फ़ाइल फ़ॉर्मेट


### WEBMANIFEST {#WEBMANIFEST}
```
public static final FileType WEBMANIFEST
```


मैनिफेस्ट फ़ाइल में ऐप के बारे में जानकारी शामिल है


### JSMAP {#JSMAP}
```
public static final FileType JSMAP
```


JSON फ़ाइल जिसमें कोड को वापस स्रोत कोड में अनुवाद करने के बारे में जानकारी होती है


### HAR {#HAR}
```
public static final FileType HAR
```


HTTP आर्काइव फ़ॉर्मेट


### JAVA {#JAVA}
```
public static final FileType JAVA
```


Java प्रोग्रामिंग भाषा फ़ॉर्मेट


### LESS {#LESS}
```
public static final FileType LESS
```


डायनामिक प्रीप्रोसेसर स्टाइल शीट भाषा फ़ॉर्मेट


### LOG {#LOG}
```
public static final FileType LOG
```


लॉगिंग घटनाओं, प्रक्रियाओं, संदेशों और संचार की रजिस्ट्री रखती है


### MAKE {#MAKE}
```
public static final FileType MAKE
```


Makefile एक फ़ाइल है जिसमें निर्देशों का सेट होता है जिसे मेक बिल्ड ऑटोमेशन टूल द्वारा लक्ष्य/उद्देश्य उत्पन्न करने के लिए उपयोग किया जाता है


### MK {#MK}
```
public static final FileType MK
```


Makefile एक फ़ाइल है जिसमें निर्देशों का सेट होता है जिसे मेक बिल्ड ऑटोमेशन टूल द्वारा लक्ष्य/उद्देश्य उत्पन्न करने के लिए उपयोग किया जाता है


### MD {#MD}
```
public static final FileType MD
```


मार्कडाउन भाषा फ़ॉर्मेट


### MKD {#MKD}
```
public static final FileType MKD
```


मार्कडाउन भाषा फ़ॉर्मेट


### MDWN {#MDWN}
```
public static final FileType MDWN
```


मार्कडाउन भाषा फ़ॉर्मेट


### MDOWN {#MDOWN}
```
public static final FileType MDOWN
```


मार्कडाउन भाषा फ़ॉर्मेट


### MARKDOWN {#MARKDOWN}
```
public static final FileType MARKDOWN
```


मार्कडाउन भाषा फ़ॉर्मेट


### MARKDN {#MARKDN}
```
public static final FileType MARKDN
```


मार्कडाउन भाषा फ़ॉर्मेट


### MDTXT {#MDTXT}
```
public static final FileType MDTXT
```


मार्कडाउन भाषा फ़ॉर्मेट


### MDTEXT {#MDTEXT}
```
public static final FileType MDTEXT
```


मार्कडाउन भाषा फ़ॉर्मेट


### ML {#ML}
```
public static final FileType ML
```


Caml प्रोग्रामिंग भाषा फ़ॉर्मेट


### MLI {#MLI}
```
public static final FileType MLI
```


Caml प्रोग्रामिंग भाषा फ़ॉर्मेट


### OBJC {#OBJC}
```
public static final FileType OBJC
```


Objective-C प्रोग्रामिंग भाषा फ़ॉर्मेट


### OBJCP {#OBJCP}
```
public static final FileType OBJCP
```


Objective-C++ प्रोग्रामिंग भाषा फ़ॉर्मेट


### PHP {#PHP}
```
public static final FileType PHP
```


PHP प्रोग्रामिंग भाषा फ़ॉर्मेट


### PHP4 {#PHP4}
```
public static final FileType PHP4
```


PHP प्रोग्रामिंग भाषा फ़ॉर्मेट


### PHP5 {#PHP5}
```
public static final FileType PHP5
```


PHP प्रोग्रामिंग भाषा फ़ॉर्मेट


### PHTML {#PHTML}
```
public static final FileType PHTML
```


PHP 2 प्रोग्रामों के लिए मानक फ़ाइल एक्सटेंशन फ़ॉर्मेट


### CTP {#CTP}
```
public static final FileType CTP
```


CakePHP टेम्प्लेट फ़ॉर्मेट


### PL {#PL}
```
public static final FileType PL
```


Perl प्रोग्रामिंग भाषा फ़ॉर्मेट


### PM {#PM}
```
public static final FileType PM
```


Perl मॉड्यूल फ़ॉर्मेट


### POD {#POD}
```
public static final FileType POD
```


Perl लाइटवेट मार्कअप भाषा फ़ॉर्मेट


### T {#T}
```
public static final FileType T
```


Perl टेस्ट फ़ाइल फ़ॉर्मेट


### PSGI {#PSGI}
```
public static final FileType PSGI
```


Perl प्रोग्रामिंग में लिखे गए वेब सर्वरों और वेब एप्लिकेशन तथा फ्रेमवर्क्स के बीच इंटरफ़ेस


### P6 {#P6}
```
public static final FileType P6
```


Perl प्रोग्रामिंग भाषा फ़ॉर्मेट


### PL6 {#PL6}
```
public static final FileType PL6
```


Perl प्रोग्रामिंग भाषा फ़ॉर्मेट


### PM6 {#PM6}
```
public static final FileType PM6
```


Perl मॉड्यूल फ़ॉर्मेट


### NQP {#NQP}
```
public static final FileType NQP
```


Rakudo Perl 6 कंपाइलर बनाने के लिए उपयोग की जाने वाली मध्यवर्ती भाषा


### PROP {#PROP}
```
public static final FileType PROP
```


प्रॉपर्टीज़ फ़ाइल फ़ॉर्मेट


### CFG {#CFG}
```
public static final FileType CFG
```


सेटिंग्स संग्रहीत करने के लिए उपयोग की जाने वाली कॉन्फ़िगरेशन फ़ाइल


### CONF {#CONF}
```
public static final FileType CONF
```


Unix और Linux आधारित सिस्टम पर उपयोग की जाने वाली कॉन्फ़िगरेशन फ़ाइल


### DIR {#DIR}
```
public static final FileType DIR
```


डायरेक्टरी कंप्यूटर पर फ़ाइलें संग्रहीत करने का स्थान है


### PY {#PY}
```
public static final FileType PY
```


Python प्रोग्रामिंग भाषा फ़ॉर्मेट


### RPY {#RPY}
```
public static final FileType RPY
```


गेम बनाने और चलाने के लिए Python-आधारित फ़ाइल इंजन


### PYW {#PYW}
```
public static final FileType PYW
```


Windows में उपयोग की जाने वाली फ़ाइलें जो संकेत देती हैं कि स्क्रिप्ट चलाने की आवश्यकता है


### CPY {#CPY}
```
public static final FileType CPY
```


कंट्रोलर Python स्क्रिप्ट फ़ॉर्मेट


### GYP {#GYP}
```
public static final FileType GYP
```


बिल्ड ऑटोमेशन टूल फ़ॉर्मेट


### GYPI {#GYPI}
```
public static final FileType GYPI
```


बिल्ड ऑटोमेशन टूल फ़ॉर्मेट


### PYI {#PYI}
```
public static final FileType PYI
```


Python इंटरफ़ेस फ़ाइल फ़ॉर्मेट


### IPY {#IPY}
```
public static final FileType IPY
```


IPython स्क्रिप्ट फ़ॉर्मेट


### RST {#RST}
```
public static final FileType RST
```


लाइटवेट मार्कअप भाषा


### RB {#RB}
```
public static final FileType RB
```


Ruby प्रोग्रामिंग भाषा फ़ॉर्मेट


### ERB {#ERB}
```
public static final FileType ERB
```


Ruby प्रोग्रामिंग भाषा फ़ॉर्मेट


### RJS {#RJS}
```
public static final FileType RJS
```


Ruby प्रोग्रामिंग भाषा फ़ॉर्मेट


### GEMSPEC {#GEMSPEC}
```
public static final FileType GEMSPEC
```


डेवलपर फ़ाइल जो RubyGems के गुणों को निर्दिष्ट करती है


### RAKE {#RAKE}
```
public static final FileType RAKE
```


Ruby बिल्ड ऑटोमेशन टूल


### RU {#RU}
```
public static final FileType RU
```


Rack कॉन्फ़िगरेशन फ़ाइल फ़ॉर्मेट


### PODSPEC {#PODSPEC}
```
public static final FileType PODSPEC
```


Ruby बिल्ड सेटिंग्स फ़ॉर्मेट


### RBI {#RBI}
```
public static final FileType RBI
```


Ruby इंटरफ़ेस फ़ाइल फ़ॉर्मेट


### SASS {#SASS}
```
public static final FileType SASS
```


स्टाइल शीट भाषा फ़ॉर्मेट


### SCSS {#SCSS}
```
public static final FileType SCSS
```


स्टाइल शीट भाषा फ़ॉर्मेट


### SCALA {#SCALA}
```
public static final FileType SCALA
```


Scala प्रोग्रामिंग भाषा फ़ॉर्मेट


### SBT {#SBT}
```
public static final FileType SBT
```


Scala के लिए SBT बिल्ड टूल फ़ॉर्मेट


### SC {#SC}
```
public static final FileType SC
```


Scala वर्कशीट फ़ॉर्मेट


### SH {#SH}
```
public static final FileType SH
```


bash के लिए प्रोग्राम किया गया स्क्रिप्ट फ़ॉर्मेट


### BASH {#BASH}
```
public static final FileType BASH
```


शेल कमांड्स को प्रोसेस करने वाला इंटरप्रेटर प्रकार


### BASHRC {#BASHRC}
```
public static final FileType BASHRC
```


फ़ाइल इंटरैक्टिव शेल्स के व्यवहार को निर्धारित करती है


### EBUILD {#EBUILD}
```
public static final FileType EBUILD
```


सॉफ़्टवेयर पैकेजों के लिए संकलन और इंस्टॉलेशन प्रक्रियाओं को स्वचालित करने वाली विशेषीकृत bash स्क्रिप्ट


### SQL {#SQL}
```
public static final FileType SQL
```


Structured Query Language फ़ॉर्मेट


### DSQL {#DSQL}
```
public static final FileType DSQL
```


Dynamic Structured Query Language फ़ॉर्मेट


### VIM {#VIM}
```
public static final FileType VIM
```


Vim स्रोत कोड फ़ाइल फ़ॉर्मेट


### YAML {#YAML}
```
public static final FileType YAML
```


मानव-पठनीय डेटा-सीरियलाइज़ेशन भाषा फ़ॉर्मेट


### YML {#YML}
```
public static final FileType YML
```


मानव-पठनीय डेटा-सीरियलाइज़ेशन भाषा फ़ॉर्मेट


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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String |  |

**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype)
### fromFileNameOrExtension(String value) {#fromFileNameOrExtension-java.lang.String-}
```
public static FileType fromFileNameOrExtension(String value)
```


फ़ाइल नाम या एक्सटेंशन के आधार पर FileType लौटाएँ


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | java.lang.String | फ़ाइल नाम या एक्सटेंशन, null नहीं |
|

**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the file type

### getSupportedFileTypes() {#getSupportedFileTypes--}
```
public static List<FileType> getSupportedFileTypes()
```


समर्थित फ़ाइल प्रकारों की सूची प्राप्त करता है


**Returns:**
java.util.List<com.groupdocs.comparison.result.FileType> - FileType की सूची

### areEquals(FileType left, FileType right) {#areEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-}
```
public static boolean areEquals(FileType left, FileType right)
```


प्रदान किए गए फ़ाइल प्रकारों की समानता जाँचता है


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | left | [FileType](../../com.groupdocs.comparison.result/filetype) | बायाँ [FileType](../../com.groupdocs.comparison.result/filetype) ऑब्जेक्ट। |
|
|  | right | [FileType](../../com.groupdocs.comparison.result/filetype) | दायाँ [FileType](../../com.groupdocs.comparison.result/filetype) ऑब्जेक्ट। |
|

**Returns:**
boolean - यदि समान हो तो true, अन्यथा false

### areNotEquals(FileType left, FileType right) {#areNotEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-}
```
public static boolean areNotEquals(FileType left, FileType right)
```


जाँचता है कि प्रदान किए गए फ़ाइल प्रकार समान नहीं हैं


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | left | [FileType](../../com.groupdocs.comparison.result/filetype) | बायाँ [FileType](../../com.groupdocs.comparison.result/filetype) ऑब्जेक्ट। |
|
|  | right | [FileType](../../com.groupdocs.comparison.result/filetype) | दायाँ [FileType](../../com.groupdocs.comparison.result/filetype) ऑब्जेक्ट। |
|

**Returns:**
बूलियन - यदि असमान हो तो सत्य, अन्यथा असत्य

### getFileFormat() {#getFileFormat--}
```
public String getFileFormat()
```


फ़ाइल प्रकार का टेक्स्ट विवरण प्राप्त करता है


**Returns:**
java.lang.String - फ़ाइल प्रकार विवरण

### getExtension() {#getExtension--}
```
public String getExtension()
```


फ़ाइल प्रकार का एक्सटेंशन प्राप्त करता है


**Returns:**
java.lang.String - फ़ाइल प्रकार का एक्सटेंशन

### toString() {#toString--}
```
public String toString()
```


उदाहरण के लिए, [FileType](../../com.groupdocs.comparison.result/filetype) की स्ट्रिंग प्रतिनिधित्व प्राप्त करता है
'PHP प्रोग्रामिंग भाषा फ़ॉर्मेट (.php)'



**Returns:**
java.lang.String - स्ट्रिंग प्रतिनिधित्व

