---
title: "FileType"
second_title: "GroupDocs.Comparison for Java API Referansı"
description: "FileType enum'ı, belge karşılaştırma sürecinde kullanılan dosya tipini temsil eder."
type: docs
weight: 16
url: /tr/java/com.groupdocs.comparison.result/filetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public enum FileType extends Enum<FileType> implements System.IEquatable<FileType>
```

FileType enum'ı, belge karşılaştırma sürecinde kullanılan dosya tipini temsil eder.


Word belgeleri, PDF dosyaları ve daha fazlası gibi farklı dosya türlerini tanımlar.
GroupDocs.Comparison tarafından desteklenen tüm dosya türlerinin listesini elde etmek, uzantıya göre dosya türünü tespit etmek vb. yöntemler sağlar.
GroupDocs.Comparison kütüphanesiyle çalışırken dosya türünü belirtmek için bu enum'ı kullanın.

* Learn more about file formats supported by GroupDocs.Comparison: [Full list of supported document formats](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* Learn more about getting supported file types in Java: [How to get supported file formats in Java](../https://docs.groupdocs.com/display/comparisonjava/Get+supported+file+formats)


Örnek kullanım:

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


## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [UNKNOWN](#UNKNOWN) | Bilinmeyen tür |
|
|  | [AS](#AS) | ActionScript Programlama Dili formatı |
|
|  | [AS3](#AS3) | ActionScript Programlama Dili formatı |
|
|  | [ASM](#ASM) | Assembler Programlama Dili biçimi |
|
|  | [BAT](#BAT) | DOS, OS/2 ve Microsoft Windows'ta betik dosyası |
|
|  | [CMD](#CMD) | DOS, OS/2 ve Microsoft Windows'ta betik dosyası |
|
|  | [C](#C) | C Tabanlı Programlama Dili biçimi |
|
|  | [H](#H) | C Tabanlı başlık dosyaları fonksiyonlar ve değişkenler tanımlarını içerir |
|
|  | [PDF](#PDF) | Adobe Taşınabilir Belge biçimi |
|
|  | [DOC](#DOC) | Microsoft Word 97-2003 Belgesi |
|
|  | [DOCM](#DOCM) | Microsoft Word Makro Etkin Belgesi |
|
|  | [DOCX](#DOCX) | Microsoft Word Belgesi |
|
|  | [DOT](#DOT) | Microsoft Word 97-2003 Şablonu |
|
|  | [DOTM](#DOTM) | Microsoft Word Makro Etkin Şablonu |
|
|  | [DOTX](#DOTX) | Microsoft Word Şablonu |
|
|  | [XLS](#XLS) | Microsoft Excel 97-2003 Çalışma Sayfası |
|
|  | [XLT](#XLT) | Microsoft Excel şablonu |
|
|  | [XLSX](#XLSX) | Microsoft Excel Çalışma Sayfası |
|
|  | [XLTM](#XLTM) | Microsoft Excel Makro Etkin Şablonu |
|
|  | [XLSB](#XLSB) | Microsoft Excel İkili Çalışma Sayfası |
|
|  | [XLSM](#XLSM) | Microsoft Excel Makro Etkin Çalışma Sayfası |
|
|  | [POT](#POT) | Microsoft PowerPoint şablonu |
|
|  | [POTX](#POTX) | Microsoft PowerPoint Şablonu |
|
|  | [POTM](#POTM) | Microsoft PowerPoint Şablonu, Makrolar için destekli |
|
|  | [PPS](#PPS) | Microsoft PowerPoint 97-2003 Slayt Gösterisi |
|
|  | [PPSX](#PPSX) | Microsoft PowerPoint Slayt Gösterisi |
|
|  | [PPTX](#PPTX) | Microsoft PowerPoint Sunumu |
|
|  | [PPT](#PPT) | Microsoft PowerPoint 97-2003 Sunumu |
|
|  | [PPTM](#PPTM) | Microsoft PowerPoint Makro Etkin Sunumu |
|
|  | [PPSM](#PPSM) | Microsoft PowerPoint Makro Etkin Slayt Gösterisi Sunumu |
|
|  | [VSDX](#VSDX) | Microsoft Visio Çizimi |
|
|  | [VSD](#VSD) | Microsoft Visio 2003-2010 Çizimi |
|
|  | [VSS](#VSS) | Microsoft Visio 2003-2010 Şablonu |
|
|  | [VST](#VST) | Microsoft Visio 2003-2010 Şablonu |
|
|  | [VDX](#VDX) | Microsoft Visio 2003-2010 XML Çizimi |
|
|  | [ONE](#ONE) | Microsoft OneNote Belgesi |
|
|  | [ODT](#ODT) | OpenDocument Metni |
|
|  | [ODP](#ODP) | OpenDocument Sunumu |
|
|  | [OTP](#OTP) | OpenDocument Sunum Şablonu |
|
|  | [ODS](#ODS) | OpenDocument Elektronik Tablosu |
|
|  | [OTT](#OTT) | OpenDocument Metin Şablonu |
|
|  | [RTF](#RTF) | Zengin Metin Belgesi |
|
|  | [TXT](#TXT) | Düz Metin Belgesi |
|
|  | [CSV](#CSV) | Virgülle Ayrılmış Değerler Dosyası |
|
|  | [HTML](#HTML) | HyperText İşaretleme Dili |
|
|  | [MHTML](#MHTML) | MIME HTML |
|
|  | [MOBI](#MOBI) | Mobipocket e-kitap formatı |
|
|  | [DCM](#DCM) | Tıpta Dijital Görüntüleme ve İletişim |
|
|  | [DJVU](#DJVU) | Deja Vu formatı |
|
|  | [DWG](#DWG) | Autodesk Tasarım Veri Formatları |
|
|  | [DXF](#DXF) | AutoCAD Çizim Değişimi |
|
|  | [BMP](#BMP) | Bitmap Resmi |
|
|  | [GIF](#GIF) | Grafik Değişim Biçimi |
|
|  | [JPEG](#JPEG) | Ortak Fotoğraf Uzmanları Grubu |
|
|  | [JPG](#JPG) | Ortak Fotoğraf Uzmanları Grubu |
|
|  | [PNG](#PNG) | Taşınabilir Ağ Grafikleri |
|
|  | [SVG](#SVG) | Skaler Vektör Grafikleri |
|
|  | [EML](#EML) | E-posta Mesajı |
|
|  | [EMLX](#EMLX) | Apple Mail E-posta Dosyası |
|
|  | [MSG](#MSG) | Microsoft Outlook E-posta Mesajı |
|
|  | [CAD](#CAD) | CAD dosya biçimi |
|
|  | [CPP](#CPP) | C Tabanlı Programlama Dili biçimi |
|
|  | [CC](#CC) | C Tabanlı Programlama Dili biçimi |
|
|  | [CXX](#CXX) | C Tabanlı Programlama Dili biçimi |
|
|  | [HXX](#HXX) | C++ programlama dilinde yazılmış Başlık Dosyaları |
|
|  | [HH](#HH) | C++ kaynak kod dosyası tarafından başvuran başlık bilgileri |
|
|  | [HPP](#HPP) | C++ programlama dilinde yazılmış Başlık Dosyaları |
|
|  | [CMAKE](#CMAKE) | Yazılımın derleme sürecini yönetmek için araç |
|
|  | [CS](#CS) | CSharp Programlama Dili biçimi |
|
|  | [CSX](#CSX) | CSharp betik dosyası biçimi |
|
|  | [CAKE](#CAKE) | CSharp çapraz platform derleme otomasyon sistemi biçimi |
|
|  | [DIFF](#DIFF) | Veri karşılaştırma aracı biçimi |
|
|  | [PATCH](#PATCH) | Farkların listesi biçimi |
|
|  | [REJ](#REJ) | Reddedilen dosyalar biçimi |
|
|  | [GROOVY](#GROOVY) | Groovy formatında yazılmış kaynak kod dosyası |
|
|  | [GVY](#GVY) | Groovy formatında yazılmış kaynak kod dosyası |
|
|  | [GRADLE](#GRADLE) | Derleme otomasyon sistemi biçimi |
|
|  | [HAML](#HAML) | Basitleştirilmiş HTML üretimi için işaretleme dili |
|
|  | [JS](#JS) | JavaScript Programlama Dili biçimi |
|
|  | [ES6](#ES6) | JavaScript standartlaştırılmış betik dili biçimi |
|
|  | [MJS](#MJS) | EcmaScript (ES) modül dosyaları için uzantı |
|
|  | [PAC](#PAC) | JavaScript işlevi biçimi için Proxy Otomatik Yapılandırma dosyası |
|
|  | [JSON](#JSON) | Veri depolama ve taşıma için hafif biçim |
|
|  | [BOWERRC](#BOWERRC) | Sunucu tarafında paket kontrolü için yapılandırma dosyası |
|
|  | [JSHINTRC](#JSHINTRC) | JavaScript kod kalitesi aracı |
|
|  | [JSCSRC](#JSCSRC) | JavaScript yapılandırma dosyası biçimi |
|
|  | [WEBMANIFEST](#WEBMANIFEST) | Manifest dosyası uygulama hakkında bilgi içerir |
|
|  | [JSMAP](#JSMAP) | Kodun kaynak koda geri çevrilmesiyle ilgili bilgileri içeren JSON dosyası |
|
|  | [HAR](#HAR) | HTTP Arşiv biçimi |
|
|  | [JAVA](#JAVA) | Java Programlama Dili biçimi |
|
|  | [LESS](#LESS) | Dinamik ön işlemci stil sayfası dili biçimi |
|
|  | [LOG](#LOG) | Günlük tutma olayların, süreçlerin, mesajların ve iletişimin bir kaydını tutar |
|
|  | [MAKE](#MAKE) | Makefile, bir hedef/amaç oluşturmak için make yapı otomasyon aracı tarafından kullanılan bir dizi yönerge içeren bir dosyadır |
|
|  | [MK](#MK) | Makefile, bir hedef/amaç oluşturmak için make yapı otomasyon aracı tarafından kullanılan bir dizi yönerge içeren bir dosyadır |
|
|  | [MD](#MD) | Markdown Dili biçimi |
|
|  | [MKD](#MKD) | Markdown Dili biçimi |
|
|  | [MDWN](#MDWN) | Markdown Dili biçimi |
|
|  | [MDOWN](#MDOWN) | Markdown Dili biçimi |
|
|  | [MARKDOWN](#MARKDOWN) | Markdown Dili biçimi |
|
|  | [MARKDN](#MARKDN) | Markdown Dili biçimi |
|
|  | [MDTXT](#MDTXT) | Markdown Dili biçimi |
|
|  | [MDTEXT](#MDTEXT) | Markdown Dili biçimi |
|
|  | [ML](#ML) | Caml Programlama Dili biçimi |
|
|  | [MLI](#MLI) | Caml Programlama Dili biçimi |
|
|  | [OBJC](#OBJC) | Objective-C Programlama Dili biçimi |
|
|  | [OBJCP](#OBJCP) | Objective-C++ Programlama Dili biçimi |
|
|  | [PHP](#PHP) | PHP Programlama Dili biçimi |
|
|  | [PHP4](#PHP4) | PHP Programlama Dili biçimi |
|
|  | [PHP5](#PHP5) | PHP Programlama Dili biçimi |
|
|  | [PHTML](#PHTML) | PHP 2 programları için standart dosya uzantısı biçimi |
|
|  | [CTP](#CTP) | CakePHP Şablon biçimi |
|
|  | [PL](#PL) | Perl Programlama Dili biçimi |
|
|  | [PM](#PM) | Perl modülü biçimi |
|
|  | [POD](#POD) | Perl hafif işaretleme dili biçimi |
|
|  | [T](#T) | Perl test dosyası biçimi |
|
|  | [PSGI](#PSGI) | Perl programlamasıyla yazılmış web sunucuları ile web uygulamaları ve çerçeveleri arasındaki arayüz |
|
|  | [P6](#P6) | Perl Programlama Dili biçimi |
|
|  | [PL6](#PL6) | Perl Programlama Dili biçimi |
|
|  | [PM6](#PM6) | Perl modülü biçimi |
|
|  | [NQP](#NQP) | Rakudo Perl 6 derleyicisini oluşturmak için kullanılan ara dil |
|
|  | [PROP](#PROP) | Özellikler dosyası biçimi |
|
|  | [CFG](#CFG) | Ayarları depolamak için kullanılan yapılandırma dosyası |
|
|  | [CONF](#CONF) | Unix ve Linux tabanlı sistemlerde kullanılan yapılandırma dosyası |
|
|  | [DIR](#DIR) | Dizin, bilgisayarda dosyaları depolamak için bir konumdur |
|
|  | [PY](#PY) | Python Programlama Dili format |
|
|  | [RPY](#RPY) | Python tabanlı dosya motoru, oyunları oluşturmak ve çalıştırmak için |
|
|  | [PYW](#PYW) | Windows'ta bir betiğin çalıştırılması gerektiğini göstermek için kullanılan dosyalar |
|
|  | [CPY](#CPY) | Kontrolcü Python Betiği format |
|
|  | [GYP](#GYP) | Derleme otomasyon aracı format |
|
|  | [GYPI](#GYPI) | Derleme otomasyon aracı format |
|
|  | [PYI](#PYI) | Python Arayüz dosya formatı |
|
|  | [IPY](#IPY) | IPython Betiği format |
|
|  | [RST](#RST) | Hafif işaretleme dili |
|
|  | [RB](#RB) | Ruby Programlama Dili format |
|
|  | [ERB](#ERB) | Ruby Programlama Dili format |
|
|  | [RJS](#RJS) | Ruby Programlama Dili format |
|
|  | [GEMSPEC](#GEMSPEC) | RubyGems'in özelliklerini belirten geliştirici dosyası |
|
|  | [RAKE](#RAKE) | Ruby derleme otomasyon aracı |
|
|  | [RU](#RU) | Rack yapılandırma dosyası formatı |
|
|  | [PODSPEC](#PODSPEC) | Ruby derleme ayarları formatı |
|
|  | [RBI](#RBI) | Ruby Arayüz dosya formatı |
|
|  | [SASS](#SASS) | Stil sayfası dili formatı |
|
|  | [SCSS](#SCSS) | Stil sayfası dili formatı |
|
|  | [SCALA](#SCALA) | Scala Programlama Dili format |
|
|  | [SBT](#SBT) | Scala için SBT derleme aracı formatı |
|
|  | [SC](#SC) | Scala çalışma sayfası formatı |
|
|  | [SH](#SH) | Bash için programlanmış betik formatı |
|
|  | [BASH](#BASH) | Kabuk komutlarını işleyen yorumlayıcı türü |
|
|  | [BASHRC](#BASHRC) | Etkileşimli kabukların davranışını belirleyen dosya |
|
|  | [EBUILD](#EBUILD) | Yazılım paketleri için derleme ve kurulum prosedürlerini otomatikleştiren özel bash betiği |
|
|  | [SQL](#SQL) | Yapılandırılmış Sorgu Dili formatı |
|
|  | [DSQL](#DSQL) | Dinamik Yapılandırılmış Sorgu Dili formatı |
|
|  | [VIM](#VIM) | Vim kaynak kod dosyası formatı |
|
|  | [YAML](#YAML) | İnsan tarafından okunabilir veri serileştirme dili formatı |
|
|  | [YML](#YML) | İnsan tarafından okunabilir veri serileştirme dili formatı |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromFileNameOrExtension(String value)](#fromFileNameOrExtension-java.lang.String-) | Dosya adı veya uzantısına göre FileType döndürür |
|
|  | [getSupportedFileTypes()](#getSupportedFileTypes--) | Desteklenen dosya türlerinin listesini alır |
|
|  | [areEquals(FileType left, FileType right)](#areEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-) | Sağlanan dosya türlerinin eşitliğini kontrol eder |
|
|  | [areNotEquals(FileType left, FileType right)](#areNotEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-) | Sağlanan dosya türlerinin eşit olmadığını kontrol eder |
|
|  | [getFileFormat()](#getFileFormat--) | Dosya türünün metin açıklamasını alır |
|
|  | [getExtension()](#getExtension--) | Dosya türünün uzantısını alır |
|
|  | [toString()](#toString--) | [FileType](../../com.groupdocs.comparison.result/filetype) öğesinin dize temsilini alır, örneğin |
'PHP Programlama Dili formatı (.php)'

|
### UNKNOWN {#UNKNOWN}
```
public static final FileType UNKNOWN
```


Bilinmeyen tür


### AS {#AS}
```
public static final FileType AS
```


ActionScript Programlama Dili formatı


### AS3 {#AS3}
```
public static final FileType AS3
```


ActionScript Programlama Dili formatı


### ASM {#ASM}
```
public static final FileType ASM
```


Assembler Programlama Dili biçimi


### BAT {#BAT}
```
public static final FileType BAT
```


DOS, OS/2 ve Microsoft Windows'ta betik dosyası


### CMD {#CMD}
```
public static final FileType CMD
```


DOS, OS/2 ve Microsoft Windows'ta betik dosyası


### C {#C}
```
public static final FileType C
```


C Tabanlı Programlama Dili biçimi


### H {#H}
```
public static final FileType H
```


C Tabanlı başlık dosyaları fonksiyonlar ve değişkenler tanımlarını içerir


### PDF {#PDF}
```
public static final FileType PDF
```


Adobe Taşınabilir Belge biçimi


### DOC {#DOC}
```
public static final FileType DOC
```


Microsoft Word 97-2003 Belgesi


### DOCM {#DOCM}
```
public static final FileType DOCM
```


Microsoft Word Makro Etkin Belgesi


### DOCX {#DOCX}
```
public static final FileType DOCX
```


Microsoft Word Belgesi


### DOT {#DOT}
```
public static final FileType DOT
```


Microsoft Word 97-2003 Şablonu


### DOTM {#DOTM}
```
public static final FileType DOTM
```


Microsoft Word Makro Etkin Şablonu


### DOTX {#DOTX}
```
public static final FileType DOTX
```


Microsoft Word Şablonu


### XLS {#XLS}
```
public static final FileType XLS
```


Microsoft Excel 97-2003 Çalışma Sayfası


### XLT {#XLT}
```
public static final FileType XLT
```


Microsoft Excel şablonu


### XLSX {#XLSX}
```
public static final FileType XLSX
```


Microsoft Excel Çalışma Sayfası


### XLTM {#XLTM}
```
public static final FileType XLTM
```


Microsoft Excel Makro Etkin Şablonu


### XLSB {#XLSB}
```
public static final FileType XLSB
```


Microsoft Excel İkili Çalışma Sayfası


### XLSM {#XLSM}
```
public static final FileType XLSM
```


Microsoft Excel Makro Etkin Çalışma Sayfası


### POT {#POT}
```
public static final FileType POT
```


Microsoft PowerPoint şablonu


### POTX {#POTX}
```
public static final FileType POTX
```


Microsoft PowerPoint Şablonu


### POTM {#POTM}
```
public static final FileType POTM
```


Microsoft PowerPoint Şablonu, Makrolar için destekli


### PPS {#PPS}
```
public static final FileType PPS
```


Microsoft PowerPoint 97-2003 Slayt Gösterisi


### PPSX {#PPSX}
```
public static final FileType PPSX
```


Microsoft PowerPoint Slayt Gösterisi


### PPTX {#PPTX}
```
public static final FileType PPTX
```


Microsoft PowerPoint Sunumu


### PPT {#PPT}
```
public static final FileType PPT
```


Microsoft PowerPoint 97-2003 Sunumu


### PPTM {#PPTM}
```
public static final FileType PPTM
```


Microsoft PowerPoint Makro Etkin Sunumu


### PPSM {#PPSM}
```
public static final FileType PPSM
```


Microsoft PowerPoint Makro Etkin Slayt Gösterisi Sunumu


### VSDX {#VSDX}
```
public static final FileType VSDX
```


Microsoft Visio Çizimi


### VSD {#VSD}
```
public static final FileType VSD
```


Microsoft Visio 2003-2010 Çizimi


### VSS {#VSS}
```
public static final FileType VSS
```


Microsoft Visio 2003-2010 Şablonu


### VST {#VST}
```
public static final FileType VST
```


Microsoft Visio 2003-2010 Şablonu


### VDX {#VDX}
```
public static final FileType VDX
```


Microsoft Visio 2003-2010 XML Çizimi


### ONE {#ONE}
```
public static final FileType ONE
```


Microsoft OneNote Belgesi


### ODT {#ODT}
```
public static final FileType ODT
```


OpenDocument Metni


### ODP {#ODP}
```
public static final FileType ODP
```


OpenDocument Sunumu


### OTP {#OTP}
```
public static final FileType OTP
```


OpenDocument Sunum Şablonu


### ODS {#ODS}
```
public static final FileType ODS
```


OpenDocument Elektronik Tablosu


### OTT {#OTT}
```
public static final FileType OTT
```


OpenDocument Metin Şablonu


### RTF {#RTF}
```
public static final FileType RTF
```


Zengin Metin Belgesi


### TXT {#TXT}
```
public static final FileType TXT
```


Düz Metin Belgesi


### CSV {#CSV}
```
public static final FileType CSV
```


Virgülle Ayrılmış Değerler Dosyası


### HTML {#HTML}
```
public static final FileType HTML
```


HyperText İşaretleme Dili


### MHTML {#MHTML}
```
public static final FileType MHTML
```


MIME HTML


### MOBI {#MOBI}
```
public static final FileType MOBI
```


Mobipocket e-kitap formatı


### DCM {#DCM}
```
public static final FileType DCM
```


Tıpta Dijital Görüntüleme ve İletişim


### DJVU {#DJVU}
```
public static final FileType DJVU
```


Deja Vu formatı


### DWG {#DWG}
```
public static final FileType DWG
```


Autodesk Tasarım Veri Formatları


### DXF {#DXF}
```
public static final FileType DXF
```


AutoCAD Çizim Değişimi


### BMP {#BMP}
```
public static final FileType BMP
```


Bitmap Resmi


### GIF {#GIF}
```
public static final FileType GIF
```


Grafik Değişim Biçimi


### JPEG {#JPEG}
```
public static final FileType JPEG
```


Ortak Fotoğraf Uzmanları Grubu


### JPG {#JPG}
```
public static final FileType JPG
```


Ortak Fotoğraf Uzmanları Grubu


### PNG {#PNG}
```
public static final FileType PNG
```


Taşınabilir Ağ Grafikleri


### SVG {#SVG}
```
public static final FileType SVG
```


Skaler Vektör Grafikleri


### EML {#EML}
```
public static final FileType EML
```


E-posta Mesajı


### EMLX {#EMLX}
```
public static final FileType EMLX
```


Apple Mail E-posta Dosyası


### MSG {#MSG}
```
public static final FileType MSG
```


Microsoft Outlook E-posta Mesajı


### CAD {#CAD}
```
public static final FileType CAD
```


CAD dosya biçimi


### CPP {#CPP}
```
public static final FileType CPP
```


C Tabanlı Programlama Dili biçimi


### CC {#CC}
```
public static final FileType CC
```


C Tabanlı Programlama Dili biçimi


### CXX {#CXX}
```
public static final FileType CXX
```


C Tabanlı Programlama Dili biçimi


### HXX {#HXX}
```
public static final FileType HXX
```


C++ programlama dilinde yazılmış Başlık Dosyaları


### HH {#HH}
```
public static final FileType HH
```


C++ kaynak kod dosyası tarafından başvuran başlık bilgileri


### HPP {#HPP}
```
public static final FileType HPP
```


C++ programlama dilinde yazılmış Başlık Dosyaları


### CMAKE {#CMAKE}
```
public static final FileType CMAKE
```


Yazılımın derleme sürecini yönetmek için araç


### CS {#CS}
```
public static final FileType CS
```


CSharp Programlama Dili biçimi


### CSX {#CSX}
```
public static final FileType CSX
```


CSharp betik dosyası biçimi


### CAKE {#CAKE}
```
public static final FileType CAKE
```


CSharp çapraz platform derleme otomasyon sistemi biçimi


### DIFF {#DIFF}
```
public static final FileType DIFF
```


Veri karşılaştırma aracı biçimi


### PATCH {#PATCH}
```
public static final FileType PATCH
```


Farkların listesi biçimi


### REJ {#REJ}
```
public static final FileType REJ
```


Reddedilen dosyalar biçimi


### GROOVY {#GROOVY}
```
public static final FileType GROOVY
```


Groovy formatında yazılmış kaynak kod dosyası


### GVY {#GVY}
```
public static final FileType GVY
```


Groovy formatında yazılmış kaynak kod dosyası


### GRADLE {#GRADLE}
```
public static final FileType GRADLE
```


Derleme otomasyon sistemi biçimi


### HAML {#HAML}
```
public static final FileType HAML
```


Basitleştirilmiş HTML üretimi için işaretleme dili


### JS {#JS}
```
public static final FileType JS
```


JavaScript Programlama Dili biçimi


### ES6 {#ES6}
```
public static final FileType ES6
```


JavaScript standartlaştırılmış betik dili biçimi


### MJS {#MJS}
```
public static final FileType MJS
```


EcmaScript (ES) modül dosyaları için uzantı


### PAC {#PAC}
```
public static final FileType PAC
```


JavaScript işlevi biçimi için Proxy Otomatik Yapılandırma dosyası


### JSON {#JSON}
```
public static final FileType JSON
```


Veri depolama ve taşıma için hafif biçim


### BOWERRC {#BOWERRC}
```
public static final FileType BOWERRC
```


Sunucu tarafında paket kontrolü için yapılandırma dosyası


### JSHINTRC {#JSHINTRC}
```
public static final FileType JSHINTRC
```


JavaScript kod kalitesi aracı


### JSCSRC {#JSCSRC}
```
public static final FileType JSCSRC
```


JavaScript yapılandırma dosyası biçimi


### WEBMANIFEST {#WEBMANIFEST}
```
public static final FileType WEBMANIFEST
```


Manifest dosyası uygulama hakkında bilgi içerir


### JSMAP {#JSMAP}
```
public static final FileType JSMAP
```


Kodun kaynak koda geri çevrilmesiyle ilgili bilgileri içeren JSON dosyası


### HAR {#HAR}
```
public static final FileType HAR
```


HTTP Arşiv biçimi


### JAVA {#JAVA}
```
public static final FileType JAVA
```


Java Programlama Dili biçimi


### LESS {#LESS}
```
public static final FileType LESS
```


Dinamik ön işlemci stil sayfası dili biçimi


### LOG {#LOG}
```
public static final FileType LOG
```


Günlük tutma olayların, süreçlerin, mesajların ve iletişimin bir kaydını tutar


### MAKE {#MAKE}
```
public static final FileType MAKE
```


Makefile, bir hedef/amaç oluşturmak için make yapı otomasyon aracı tarafından kullanılan bir dizi yönerge içeren bir dosyadır


### MK {#MK}
```
public static final FileType MK
```


Makefile, bir hedef/amaç oluşturmak için make yapı otomasyon aracı tarafından kullanılan bir dizi yönerge içeren bir dosyadır


### MD {#MD}
```
public static final FileType MD
```


Markdown Dili biçimi


### MKD {#MKD}
```
public static final FileType MKD
```


Markdown Dili biçimi


### MDWN {#MDWN}
```
public static final FileType MDWN
```


Markdown Dili biçimi


### MDOWN {#MDOWN}
```
public static final FileType MDOWN
```


Markdown Dili biçimi


### MARKDOWN {#MARKDOWN}
```
public static final FileType MARKDOWN
```


Markdown Dili biçimi


### MARKDN {#MARKDN}
```
public static final FileType MARKDN
```


Markdown Dili biçimi


### MDTXT {#MDTXT}
```
public static final FileType MDTXT
```


Markdown Dili biçimi


### MDTEXT {#MDTEXT}
```
public static final FileType MDTEXT
```


Markdown Dili biçimi


### ML {#ML}
```
public static final FileType ML
```


Caml Programlama Dili biçimi


### MLI {#MLI}
```
public static final FileType MLI
```


Caml Programlama Dili biçimi


### OBJC {#OBJC}
```
public static final FileType OBJC
```


Objective-C Programlama Dili biçimi


### OBJCP {#OBJCP}
```
public static final FileType OBJCP
```


Objective-C++ Programlama Dili biçimi


### PHP {#PHP}
```
public static final FileType PHP
```


PHP Programlama Dili biçimi


### PHP4 {#PHP4}
```
public static final FileType PHP4
```


PHP Programlama Dili biçimi


### PHP5 {#PHP5}
```
public static final FileType PHP5
```


PHP Programlama Dili biçimi


### PHTML {#PHTML}
```
public static final FileType PHTML
```


PHP 2 programları için standart dosya uzantısı biçimi


### CTP {#CTP}
```
public static final FileType CTP
```


CakePHP Şablon biçimi


### PL {#PL}
```
public static final FileType PL
```


Perl Programlama Dili biçimi


### PM {#PM}
```
public static final FileType PM
```


Perl modülü biçimi


### POD {#POD}
```
public static final FileType POD
```


Perl hafif işaretleme dili biçimi


### T {#T}
```
public static final FileType T
```


Perl test dosyası biçimi


### PSGI {#PSGI}
```
public static final FileType PSGI
```


Perl programlamasıyla yazılmış web sunucuları ile web uygulamaları ve çerçeveleri arasındaki arayüz


### P6 {#P6}
```
public static final FileType P6
```


Perl Programlama Dili biçimi


### PL6 {#PL6}
```
public static final FileType PL6
```


Perl Programlama Dili biçimi


### PM6 {#PM6}
```
public static final FileType PM6
```


Perl modülü biçimi


### NQP {#NQP}
```
public static final FileType NQP
```


Rakudo Perl 6 derleyicisini oluşturmak için kullanılan ara dil


### PROP {#PROP}
```
public static final FileType PROP
```


Özellikler dosyası biçimi


### CFG {#CFG}
```
public static final FileType CFG
```


Ayarları depolamak için kullanılan yapılandırma dosyası


### CONF {#CONF}
```
public static final FileType CONF
```


Unix ve Linux tabanlı sistemlerde kullanılan yapılandırma dosyası


### DIR {#DIR}
```
public static final FileType DIR
```


Dizin, bilgisayarda dosyaları depolamak için bir konumdur


### PY {#PY}
```
public static final FileType PY
```


Python Programlama Dili format


### RPY {#RPY}
```
public static final FileType RPY
```


Python tabanlı dosya motoru, oyunları oluşturmak ve çalıştırmak için


### PYW {#PYW}
```
public static final FileType PYW
```


Windows'ta bir betiğin çalıştırılması gerektiğini göstermek için kullanılan dosyalar


### CPY {#CPY}
```
public static final FileType CPY
```


Kontrolcü Python Betiği format


### GYP {#GYP}
```
public static final FileType GYP
```


Derleme otomasyon aracı format


### GYPI {#GYPI}
```
public static final FileType GYPI
```


Derleme otomasyon aracı format


### PYI {#PYI}
```
public static final FileType PYI
```


Python Arayüz dosya formatı


### IPY {#IPY}
```
public static final FileType IPY
```


IPython Betiği format


### RST {#RST}
```
public static final FileType RST
```


Hafif işaretleme dili


### RB {#RB}
```
public static final FileType RB
```


Ruby Programlama Dili format


### ERB {#ERB}
```
public static final FileType ERB
```


Ruby Programlama Dili format


### RJS {#RJS}
```
public static final FileType RJS
```


Ruby Programlama Dili format


### GEMSPEC {#GEMSPEC}
```
public static final FileType GEMSPEC
```


RubyGems'in özelliklerini belirten geliştirici dosyası


### RAKE {#RAKE}
```
public static final FileType RAKE
```


Ruby derleme otomasyon aracı


### RU {#RU}
```
public static final FileType RU
```


Rack yapılandırma dosyası formatı


### PODSPEC {#PODSPEC}
```
public static final FileType PODSPEC
```


Ruby derleme ayarları formatı


### RBI {#RBI}
```
public static final FileType RBI
```


Ruby Arayüz dosya formatı


### SASS {#SASS}
```
public static final FileType SASS
```


Stil sayfası dili formatı


### SCSS {#SCSS}
```
public static final FileType SCSS
```


Stil sayfası dili formatı


### SCALA {#SCALA}
```
public static final FileType SCALA
```


Scala Programlama Dili format


### SBT {#SBT}
```
public static final FileType SBT
```


Scala için SBT derleme aracı formatı


### SC {#SC}
```
public static final FileType SC
```


Scala çalışma sayfası formatı


### SH {#SH}
```
public static final FileType SH
```


Bash için programlanmış betik formatı


### BASH {#BASH}
```
public static final FileType BASH
```


Kabuk komutlarını işleyen yorumlayıcı türü


### BASHRC {#BASHRC}
```
public static final FileType BASHRC
```


Etkileşimli kabukların davranışını belirleyen dosya


### EBUILD {#EBUILD}
```
public static final FileType EBUILD
```


Yazılım paketleri için derleme ve kurulum prosedürlerini otomatikleştiren özel bash betiği


### SQL {#SQL}
```
public static final FileType SQL
```


Yapılandırılmış Sorgu Dili formatı


### DSQL {#DSQL}
```
public static final FileType DSQL
```


Dinamik Yapılandırılmış Sorgu Dili formatı


### VIM {#VIM}
```
public static final FileType VIM
```


Vim kaynak kod dosyası formatı


### YAML {#YAML}
```
public static final FileType YAML
```


İnsan tarafından okunabilir veri serileştirme dili formatı


### YML {#YML}
```
public static final FileType YML
```


İnsan tarafından okunabilir veri serileştirme dili formatı


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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype)
### fromFileNameOrExtension(String value) {#fromFileNameOrExtension-java.lang.String-}
```
public static FileType fromFileNameOrExtension(String value)
```


Dosya adı veya uzantısına göre FileType döndürür


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.lang.String | Dosya adı veya uzantı, null olmamalıdır |
|

**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the file type

### getSupportedFileTypes() {#getSupportedFileTypes--}
```
public static List<FileType> getSupportedFileTypes()
```


Desteklenen dosya türlerinin listesini alır


**Returns:**
java.util.List<com.groupdocs.comparison.result.FileType> - FileType listesi

### areEquals(FileType left, FileType right) {#areEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-}
```
public static boolean areEquals(FileType left, FileType right)
```


Sağlanan dosya türlerinin eşitliğini kontrol eder


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | left | [FileType](../../com.groupdocs.comparison.result/filetype) | Sol [FileType](../../com.groupdocs.comparison.result/filetype) nesnesi. |
|
|  | right | [FileType](../../com.groupdocs.comparison.result/filetype) | Sağ [FileType](../../com.groupdocs.comparison.result/filetype) nesnesi. |
|

**Returns:**
boolean - eşitse true, aksi takdirde false

### areNotEquals(FileType left, FileType right) {#areNotEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-}
```
public static boolean areNotEquals(FileType left, FileType right)
```


Sağlanan dosya türlerinin eşit olmadığını kontrol eder


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | left | [FileType](../../com.groupdocs.comparison.result/filetype) | Sol [FileType](../../com.groupdocs.comparison.result/filetype) nesnesi. |
|
|  | right | [FileType](../../com.groupdocs.comparison.result/filetype) | Sağ [FileType](../../com.groupdocs.comparison.result/filetype) nesnesi. |
|

**Returns:**
boolean - eşit değilse true, aksi takdirde false

### getFileFormat() {#getFileFormat--}
```
public String getFileFormat()
```


Dosya türünün metin açıklamasını alır


**Returns:**
java.lang.String - dosya türü açıklaması

### getExtension() {#getExtension--}
```
public String getExtension()
```


Dosya türünün uzantısını alır


**Returns:**
java.lang.String - dosya türünün uzantısı

### toString() {#toString--}
```
public String toString()
```


[FileType](../../com.groupdocs.comparison.result/filetype) öğesinin dize temsilini alır, örneğin
'PHP Programlama Dili formatı (.php)'



**Returns:**
java.lang.String - dize temsili

