---
title: "FileType"
second_title: "GroupDocs.Comparison .NET için API Referansı"
description: "Dosya tipini temsil eder. GroupDocs.Comparison tarafından desteklenen tüm dosya tiplerinin listesini elde etmek, dosya tipini uzantıya göre tespit etmek vb. yöntemler sağlar."
type: docs
weight: 480
url: /tr/net/groupdocs.comparison.result/filetype/
---
## FileType class

Dosya türünü temsil eder. GroupDocs.Comparison tarafından desteklenen tüm dosya türlerinin listesini elde etmek, uzantıya göre dosya türünü tespit etmek vb. yöntemler sağlar.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Extension](../../groupdocs.comparison.result/filetype/extension) { get; } | Dosya uzantısı |
| [FileFormat](../../groupdocs.comparison.result/filetype/fileformat) { get; } | Dosya formatı |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| static [FromFileNameOrExtension](../../groupdocs.comparison.result/filetype/fromfilenameorextension)(string) | Dosya adına veya uzantısına göre FileType döndür |
| [Equals](../../groupdocs.comparison.result/filetype/equals#equals)(FileType) | Dosya türü eşdeğerlik kontrolü |
| override [Equals](../../groupdocs.comparison.result/filetype/equals#equals_1)(object) | Nesne ile eşdeğerlik kontrolü |
| override [GetHashCode](../../groupdocs.comparison.result/filetype/gethashcode)() | Karma kodunu al |
| override [ToString](../../groupdocs.comparison.result/filetype/tostring)() | ToString |
| static [GetSupportedFileTypes](../../groupdocs.comparison.result/filetype/getsupportedfiletypes)() | Desteklenen dosya türleri enumerasyonunu al |
| [operator ==](../../groupdocs.comparison.result/filetype/op_equality) | Operatör aşırı yüklemesi |
| [operator !=](../../groupdocs.comparison.result/filetype/op_inequality) | Operatör aşırı yüklemesi |

## Alanlar

| Ad | Açıklama |
| --- | --- |
| static readonly [AS](../../groupdocs.comparison.result/filetype/as) | ActionScript Programlama Dili formatı |
| static readonly [AS3](../../groupdocs.comparison.result/filetype/as3) | ActionScript Programlama Dili formatı |
| static readonly [ASM](../../groupdocs.comparison.result/filetype/asm) | ASM formatı |
| static readonly [BASH](../../groupdocs.comparison.result/filetype/bash) | Kabuk komutlarını işleyen yorumlayıcı türü |
| static readonly [BASHRC](../../groupdocs.comparison.result/filetype/bashrc) | Dosya, etkileşimli kabukların davranışını belirler |
| static readonly [BAT](../../groupdocs.comparison.result/filetype/bat) | DOS, OS/2 ve Microsoft Windows'ta betik dosyası |
| static readonly [BMP](../../groupdocs.comparison.result/filetype/bmp) | Bitmap Resim |
| static readonly [BOWERRC](../../groupdocs.comparison.result/filetype/bowerrc) | Sunucu tarafında paket kontrolü için yapılandırma dosyası |
| static readonly [C](../../groupdocs.comparison.result/filetype/c) | C Tabanlı Programlama Dili formatı |
| static readonly [CAD](../../groupdocs.comparison.result/filetype/cad) | CAD dosya formatı |
| static readonly [CAKE](../../groupdocs.comparison.result/filetype/cake) | CSharp çapraz platform derleme otomasyon sistemi formatı |
| static readonly [CC](../../groupdocs.comparison.result/filetype/cc) | C Tabanlı Programlama Dili formatı |
| static readonly [CFG](../../groupdocs.comparison.result/filetype/cfg) | Ayarları depolamak için kullanılan yapılandırma dosyası |
| static readonly [CMAKE](../../groupdocs.comparison.result/filetype/cmake) | Yazılımın derleme sürecini yönetmek için araç |
| static readonly [CMD](../../groupdocs.comparison.result/filetype/cmd) | DOS, OS/2 ve Microsoft Windows'ta betik dosyası |
| static readonly [CONF](../../groupdocs.comparison.result/filetype/conf) | Unix ve Linux tabanlı sistemlerde kullanılan yapılandırma dosyası |
| static readonly [CPP](../../groupdocs.comparison.result/filetype/cpp) | C Tabanlı Programlama Dili formatı |
| static readonly [CPY](../../groupdocs.comparison.result/filetype/cpy) | Controller Python Betik formatı |
| static readonly [CS](../../groupdocs.comparison.result/filetype/cs) | CSharp Programlama Dili formatı |
| static readonly [CSV](../../groupdocs.comparison.result/filetype/csv) | Virgülle Ayrılmış Değerler Dosyası |
| static readonly [CSX](../../groupdocs.comparison.result/filetype/csx) | CSharp betik dosyası formatı |
| static readonly [CTP](../../groupdocs.comparison.result/filetype/ctp) | CakePHP Şablon biçimi |
| static readonly [CXX](../../groupdocs.comparison.result/filetype/cxx) | C Tabanlı Programlama Dili formatı |
| static readonly [DCM](../../groupdocs.comparison.result/filetype/dcm) | Tıpta Dijital Görüntüleme ve İletişim |
| static readonly [DIFF](../../groupdocs.comparison.result/filetype/diff) | Veri karşılaştırma aracı biçimi |
| static readonly [DIR](../../groupdocs.comparison.result/filetype/dir) | Dizin, bilgisayarda dosyaları depolamak için bir konumdur |
| static readonly [DJVU](../../groupdocs.comparison.result/filetype/djvu) | Deja Vu biçimi |
| static readonly [DOC](../../groupdocs.comparison.result/filetype/doc) | Microsoft Word 97-2003 Belgesi |
| static readonly [DOCM](../../groupdocs.comparison.result/filetype/docm) | Microsoft Word Makro Etkin Belgesi |
| static readonly [DOCX](../../groupdocs.comparison.result/filetype/docx) | Microsoft Word Belgesi |
| static readonly [DOT](../../groupdocs.comparison.result/filetype/dot) | Microsoft Word 97-2003 Şablonu |
| static readonly [DOTM](../../groupdocs.comparison.result/filetype/dotm) | Microsoft Word Makro Etkin Şablonu |
| static readonly [DOTX](../../groupdocs.comparison.result/filetype/dotx) | Microsoft Word Şablonu |
| static readonly [DSQL](../../groupdocs.comparison.result/filetype/dsql) | Dinamik Yapılandırılmış Sorgu Dili biçimi |
| static readonly [DWG](../../groupdocs.comparison.result/filetype/dwg) | Autodesk Tasarım Veri Biçimleri |
| static readonly [DXF](../../groupdocs.comparison.result/filetype/dxf) | AutoCAD Çizim Değişimi |
| static readonly [EBUILD](../../groupdocs.comparison.result/filetype/ebuild) | Yazılım paketleri için derleme ve kurulum prosedürlerini otomatikleştiren özelleştirilmiş bash betiği |
| static readonly [EML](../../groupdocs.comparison.result/filetype/eml) | E-posta Mesajı |
| static readonly [EMLX](../../groupdocs.comparison.result/filetype/emlx) | Apple Mail E-posta Dosyası |
| static readonly [ERB](../../groupdocs.comparison.result/filetype/erb) | Ruby Programlama Dili biçimi |
| static readonly [ES6](../../groupdocs.comparison.result/filetype/es6) | JavaScript standartlaştırılmış betik dili biçimi |
| static readonly [GEMSPEC](../../groupdocs.comparison.result/filetype/gemspec) | RubyGems'in özelliklerini belirten geliştirici dosyası |
| static readonly [GIF](../../groupdocs.comparison.result/filetype/gif) | Grafik Değişim Biçimi |
| static readonly [GRADLE](../../groupdocs.comparison.result/filetype/gradle) | Derleme otomasyonu sistem biçimi |
| static readonly [GROOVY](../../groupdocs.comparison.result/filetype/groovy) | Groovy biçiminde yazılmış kaynak kod dosyası |
| static readonly [GVY](../../groupdocs.comparison.result/filetype/gvy) | Groovy biçiminde yazılmış kaynak kod dosyası |
| static readonly [GYP](../../groupdocs.comparison.result/filetype/gyp) | Derleme otomasyonu aracı biçimi |
| static readonly [GYPI](../../groupdocs.comparison.result/filetype/gypi) | Derleme otomasyonu aracı biçimi |
| static readonly [H](../../groupdocs.comparison.result/filetype/h) | C Tabanlı başlık dosyaları Fonksiyonlar ve Değişkenlerin tanımlarını içerir |
| static readonly [HAML](../../groupdocs.comparison.result/filetype/haml) | Basitleştirilmiş HTML oluşturma için işaretleme dili |
| static readonly [HAR](../../groupdocs.comparison.result/filetype/har) | HTTP Arşivi formatı |
| static readonly [HH](../../groupdocs.comparison.result/filetype/hh) | Bir C++ kaynak kod dosyası tarafından başvurulan başlık bilgileri |
| static readonly [HPP](../../groupdocs.comparison.result/filetype/hpp) | C++ programlama diliyle yazılmış Başlık Dosyaları |
| static readonly [HTML](../../groupdocs.comparison.result/filetype/html) | HyperText İşaretleme Dili |
| static readonly [HXX](../../groupdocs.comparison.result/filetype/hxx) | C++ programlama diliyle yazılmış Başlık Dosyaları |
| static readonly [IPY](../../groupdocs.comparison.result/filetype/ipy) | IPython Betik formatı |
| static readonly [JAVA](../../groupdocs.comparison.result/filetype/java) | Java Programlama Dili formatı |
| static readonly [JPEG](../../groupdocs.comparison.result/filetype/jpeg) | Joint Photographic Experts Group |
| static readonly [JS](../../groupdocs.comparison.result/filetype/js) | JavaScript Programlama Dili formatı |
| static readonly [JSCSRC](../../groupdocs.comparison.result/filetype/jscsrc) | JavaScript yapılandırma dosyası formatı |
| static readonly [JSHINTRC](../../groupdocs.comparison.result/filetype/jshintrc) | JavaScript kod kalitesi aracı |
| static readonly [JSMAP](../../groupdocs.comparison.result/filetype/jsmap) | Kodu tekrar kaynak koda çevirmek için gereken bilgileri içeren JSON dosyası |
| static readonly [JSON](../../groupdocs.comparison.result/filetype/json) | Veri depolama ve taşıma için hafif bir format |
| static readonly [LESS](../../groupdocs.comparison.result/filetype/less) | Dinamik ön işlemci stil sayfası dili formatı |
| static readonly [LOG](../../groupdocs.comparison.result/filetype/log) | Günlükleme, olayların, süreçlerin, mesajların ve iletişimin bir kaydını tutar |
| static readonly [MAKE](../../groupdocs.comparison.result/filetype/make) | Makefile, bir hedef/amaç oluşturmak için make yapı otomasyon aracı tarafından kullanılan bir dizi yönerge içeren bir dosyadır |
| static readonly [MARKDN](../../groupdocs.comparison.result/filetype/markdn) | Markdown Dili formatı |
| static readonly [MARKDOWN](../../groupdocs.comparison.result/filetype/markdown) | Markdown Dili formatı |
| static readonly [MD](../../groupdocs.comparison.result/filetype/md) | Markdown Dili formatı |
| static readonly [MDOWN](../../groupdocs.comparison.result/filetype/mdown) | Markdown Dili formatı |
| static readonly [MDTEXT](../../groupdocs.comparison.result/filetype/mdtext) | Markdown Dili formatı |
| static readonly [MDTXT](../../groupdocs.comparison.result/filetype/mdtxt) | Markdown Dili formatı |
| static readonly [MDWN](../../groupdocs.comparison.result/filetype/mdwn) | Markdown Dili formatı |
| static readonly [MHTML](../../groupdocs.comparison.result/filetype/mhtml) | Mime HTML |
| static readonly [MJS](../../groupdocs.comparison.result/filetype/mjs) | EcmaScript (ES) modül dosyaları için uzantı |
| static readonly [MK](../../groupdocs.comparison.result/filetype/mk) | Makefile, bir hedef/amaç oluşturmak için make yapı otomasyon aracı tarafından kullanılan bir dizi yönerge içeren bir dosyadır |
| static readonly [MKD](../../groupdocs.comparison.result/filetype/mkd) | Markdown Dili formatı |
| static readonly [ML](../../groupdocs.comparison.result/filetype/ml) | Caml Programlama Dili formatı |
| static readonly [MLI](../../groupdocs.comparison.result/filetype/mli) | Caml Programlama Dili formatı |
| static readonly [MOBI](../../groupdocs.comparison.result/filetype/mobi) | Mobipocket e-kitap formatı |
| static readonly [MSG](../../groupdocs.comparison.result/filetype/msg) | Microsoft Outlook E-posta Mesajı |
| static readonly [NQP](../../groupdocs.comparison.result/filetype/nqp) | Rakudo Perl 6 derleyicisini oluşturmak için kullanılan ara dil |
| static readonly [OBJC](../../groupdocs.comparison.result/filetype/objc) | Objective-C Programlama Dili formatı |
| static readonly [OBJCP](../../groupdocs.comparison.result/filetype/objcp) | Objective-C++ Programlama Dili formatı |
| static readonly [ODP](../../groupdocs.comparison.result/filetype/odp) | OpenDocument Sunumu |
| static readonly [ODS](../../groupdocs.comparison.result/filetype/ods) | OpenDocument Tablosu |
| static readonly [ODT](../../groupdocs.comparison.result/filetype/odt) | OpenDocument Metni |
| static readonly [ONE](../../groupdocs.comparison.result/filetype/one) | Microsoft OneNote Belgesi |
| static readonly [OTP](../../groupdocs.comparison.result/filetype/otp) | OpenDocument Sunum Şablonu |
| static readonly [OTT](../../groupdocs.comparison.result/filetype/ott) | OpenDocument Metin Şablonu |
| static readonly [P6](../../groupdocs.comparison.result/filetype/p6) | Perl Programlama Dili biçimi |
| static readonly [PAC](../../groupdocs.comparison.result/filetype/pac) | JavaScript işlevi için Proxy Otomatik Yapılandırma dosyası biçimi |
| static readonly [PATCH](../../groupdocs.comparison.result/filetype/patch) | Farklar listesi biçimi |
| static readonly [PDF](../../groupdocs.comparison.result/filetype/pdf) | Adobe Taşınabilir Belge biçimi |
| static readonly [PHP](../../groupdocs.comparison.result/filetype/php) | PHP Programlama Dili biçimi |
| static readonly [PHP4](../../groupdocs.comparison.result/filetype/php4) | PHP Programlama Dili biçimi |
| static readonly [PHP5](../../groupdocs.comparison.result/filetype/php5) | PHP Programlama Dili biçimi |
| static readonly [PHTML](../../groupdocs.comparison.result/filetype/phtml) | PHP 2 programları için standart dosya uzantısı biçimi |
| static readonly [PL](../../groupdocs.comparison.result/filetype/pl) | Perl Programlama Dili biçimi |
| static readonly [PL6](../../groupdocs.comparison.result/filetype/pl6) | Perl Programlama Dili biçimi |
| static readonly [PM](../../groupdocs.comparison.result/filetype/pm) | Perl modülü biçimi |
| static readonly [PM6](../../groupdocs.comparison.result/filetype/pm6) | Perl modülü biçimi |
| static readonly [PNG](../../groupdocs.comparison.result/filetype/png) | Taşınabilir Ağ Grafikleri |
| static readonly [POD](../../groupdocs.comparison.result/filetype/pod) | Perl hafif işaretleme dili biçimi |
| static readonly [PODSPEC](../../groupdocs.comparison.result/filetype/podspec) | Ruby derleme ayarları biçimi |
| static readonly [POT](../../groupdocs.comparison.result/filetype/pot) | Microsoft PowerPoint şablonu |
| static readonly [POTX](../../groupdocs.comparison.result/filetype/potx) | Microsoft PowerPoint Şablonu |
| static readonly [PPS](../../groupdocs.comparison.result/filetype/pps) | Microsoft PowerPoint 97-2003 Slayt Gösterisi |
| static readonly [PPSX](../../groupdocs.comparison.result/filetype/ppsx) | Microsoft PowerPoint Slayt Gösterisi |
| static readonly [PPT](../../groupdocs.comparison.result/filetype/ppt) | Microsoft PowerPoint 97-2003 Sunumu |
| static readonly [PPTX](../../groupdocs.comparison.result/filetype/pptx) | Microsoft PowerPoint Sunumu |
| static readonly [PROP](../../groupdocs.comparison.result/filetype/prop) | Özellikler dosyası biçimi |
| static readonly [PSGI](../../groupdocs.comparison.result/filetype/psgi) | Perl programlamasında yazılmış web sunucuları ve web uygulamaları ile çerçeveler arasındaki arayüz |
| static readonly [PY](../../groupdocs.comparison.result/filetype/py) | Python Programlama Dili biçimi |
| static readonly [PYI](../../groupdocs.comparison.result/filetype/pyi) | Python Arayüz dosya biçimi |
| static readonly [PYW](../../groupdocs.comparison.result/filetype/pyw) | Windows'ta bir betiğin çalıştırılması gerektiğini göstermek için kullanılan dosyalar |
| static readonly [RAKE](../../groupdocs.comparison.result/filetype/rake) | Ruby derleme otomasyon aracı |
| static readonly [RB](../../groupdocs.comparison.result/filetype/rb) | Ruby Programlama Dili biçimi |
| static readonly [RBI](../../groupdocs.comparison.result/filetype/rbi) | Ruby Arayüz dosya biçimi |
| static readonly [REJ](../../groupdocs.comparison.result/filetype/rej) | Reddedilen dosyalar biçimi |
| static readonly [RJS](../../groupdocs.comparison.result/filetype/rjs) | Ruby Programlama Dili biçimi |
| static readonly [RPY](../../groupdocs.comparison.result/filetype/rpy) | Python tabanlı oyun oluşturma ve çalıştırma dosya motoru |
| static readonly [RST](../../groupdocs.comparison.result/filetype/rst) | Hafif işaretleme dili |
| static readonly [RTF](../../groupdocs.comparison.result/filetype/rtf) | Zengin Metin Belgesi |
| static readonly [RU](../../groupdocs.comparison.result/filetype/ru) | Rack yapılandırma dosya biçimi |
| static readonly [SASS](../../groupdocs.comparison.result/filetype/sass) | Stil sayfası dili biçimi |
| static readonly [SBT](../../groupdocs.comparison.result/filetype/sbt) | Scala için SBT derleme aracı biçimi |
| static readonly [SC](../../groupdocs.comparison.result/filetype/sc) | Scala çalışma sayfası biçimi |
| static readonly [SCALA](../../groupdocs.comparison.result/filetype/scala) | Scala Programlama Dili biçimi |
| static readonly [SCSS](../../groupdocs.comparison.result/filetype/scss) | Stil sayfası dili biçimi |
| static readonly [SH](../../groupdocs.comparison.result/filetype/sh) | bash için programlanmış betik biçimi |
| static readonly [SQL](../../groupdocs.comparison.result/filetype/sql) | Yapılandırılmış Sorgu Dili biçimi |
| static readonly [SVG](../../groupdocs.comparison.result/filetype/svg) | Scalar Vektör Grafikleri |
| static readonly [T](../../groupdocs.comparison.result/filetype/t) | Perl test dosya biçimi |
| static readonly [TXT](../../groupdocs.comparison.result/filetype/txt) | Düz Metin Belgesi |
| static readonly [UNKNOWN](../../groupdocs.comparison.result/filetype/unknown) | Bilinmeyen tür |
| static readonly [VDX](../../groupdocs.comparison.result/filetype/vdx) | Microsoft Visio 2003-2010 XML Çizimi |
| static readonly [VIM](../../groupdocs.comparison.result/filetype/vim) | Vim kaynak kod dosya biçimi |
| static readonly [VSD](../../groupdocs.comparison.result/filetype/vsd) | Microsoft Visio 2003-2010 Çizimi |
| static readonly [VSDX](../../groupdocs.comparison.result/filetype/vsdx) | Microsoft Visio Çizimi |
| static readonly [VSS](../../groupdocs.comparison.result/filetype/vss) | Microsoft Visio 2003-2010 Şablonu |
| static readonly [VST](../../groupdocs.comparison.result/filetype/vst) | Microsoft Visio 2003-2010 Şablonu |
| static readonly [WEBMANIFEST](../../groupdocs.comparison.result/filetype/webmanifest) | Manifest dosyası uygulama hakkında bilgi içerir |
| static readonly [XLS](../../groupdocs.comparison.result/filetype/xls) | Microsoft Excel 97-2003 Çalışma Sayfası |
| static readonly [XLSB](../../groupdocs.comparison.result/filetype/xlsb) | Microsoft Excel İkili Çalışma Sayfası |
| static readonly [XLSM](../../groupdocs.comparison.result/filetype/xlsm) | Microsoft Excel Makro Etkin Çalışma Sayfası |
| static readonly [XLSX](../../groupdocs.comparison.result/filetype/xlsx) | Microsoft Excel Çalışma Sayfası |
| static readonly [XLT](../../groupdocs.comparison.result/filetype/xlt) | Microsoft Excel şablonu |
| static readonly [XLTM](../../groupdocs.comparison.result/filetype/xltm) | Microsoft Excel makro etkin şablonu |
| static readonly [YAML](../../groupdocs.comparison.result/filetype/yaml) | İnsan tarafından okunabilir veri-serializasyon dili biçimi |
| static readonly [YML](../../groupdocs.comparison.result/filetype/yml) | İnsan tarafından okunabilir veri-serializasyon dili biçimi |

### Açıklamalar

**Learn more**

* Learn more about file formats supported by GroupDocs.Comparison: [Full list of supported document formats](https://docs.groupdocs.com/display/comparisonnet/Supported+Document+Formats)
* Learn more about getting supported file types in C#: [How to get supported file formats in C#](https://docs.groupdocs.com/display/comparisonnet/Get+supported+file+formats)

### Ayrıca Bakınız

* namespace [GroupDocs.Comparison.Result](../../groupdocs.comparison.result)
* assembly [GroupDocs.Comparison](../../)

<!-- DÜZENLEMEYİN: GroupDocs.Comparison.dll için xmldocmd tarafından oluşturuldu -->
