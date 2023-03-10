---
title: FileType
second_title: .NET API Başvurusu için GroupDocs.Comparison
description: Dosya türünü temsil eder. GroupDocs.Comparison tarafından desteklenen tüm dosya türlerinin listesini elde etmek dosya türünü uzantıya göre algılamak için yöntemler sağlar etc.
type: docs
weight: 400
url: /tr/net/groupdocs.comparison.result/filetype/
---
## FileType class

Dosya türünü temsil eder. GroupDocs.Comparison tarafından desteklenen tüm dosya türlerinin listesini elde etmek, dosya türünü uzantıya göre algılamak için yöntemler sağlar etc.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Extension](../../groupdocs.comparison.result/filetype/extension) { get; } | Dosya uzantısı |
| [FileFormat](../../groupdocs.comparison.result/filetype/fileformat) { get; } | Dosya biçimi |

## yöntemler

| İsim | Tanım |
| --- | --- |
| static [FromFileNameOrExtension](../../groupdocs.comparison.result/filetype/fromfilenameorextension)(string) | Dosya adı veya uzantısına göre FileType döndürür |
| [Equals](../../groupdocs.comparison.result/filetype/equals#equals)(FileType) | Dosya türü eşdeğerliği kontrolü |
| override [Equals](../../groupdocs.comparison.result/filetype/equals#equals_1)(object) | object ile denklik kontrolü |
| override [GetHashCode](../../groupdocs.comparison.result/filetype/gethashcode)() | Hash kodunu al |
| override [ToString](../../groupdocs.comparison.result/filetype/tostring)() | ToString |
| static [GetSupportedFileTypes](../../groupdocs.comparison.result/filetype/getsupportedfiletypes)() | Desteklenen dosya türlerini alın |
| [operator ==](../../groupdocs.comparison.result/filetype/op_equality) | Operatör aşırı yükü |
| [operator !=](../../groupdocs.comparison.result/filetype/op_inequality) | Operatör aşırı yükü |

## Alanlar

| İsim | Tanım |
| --- | --- |
| static [AS](../../groupdocs.comparison.result/filetype/as) | ActionScript Programlama Dili format |
| static [AS3](../../groupdocs.comparison.result/filetype/as3) | ActionScript Programlama Dili format |
| static [ASM](../../groupdocs.comparison.result/filetype/asm) | ASM biçimi |
| static [BASH](../../groupdocs.comparison.result/filetype/bash) | Kabuk komutlarını işleyen yorumlayıcı türü |
| static [BASHRC](../../groupdocs.comparison.result/filetype/bashrc) | Dosya, etkileşimli kabukların davranışını belirler |
| static [BAT](../../groupdocs.comparison.result/filetype/bat) | DOS, OS/2 ve Microsoft Windows 'de betik dosyası |
| static [BMP](../../groupdocs.comparison.result/filetype/bmp) | Bit Eşlem Resmi |
| static [BOWERRC](../../groupdocs.comparison.result/filetype/bowerrc) | Sunucu tarafında paket kontrolü için yapılandırma dosyası |
| static [C](../../groupdocs.comparison.result/filetype/c) | C Tabanlı Programlama Dili format |
| static [CAD](../../groupdocs.comparison.result/filetype/cad) | CAD dosya formatı |
| static [CAKE](../../groupdocs.comparison.result/filetype/cake) | CSharp platformlar arası yapı otomasyon sistemi format |
| static [CC](../../groupdocs.comparison.result/filetype/cc) | C Tabanlı Programlama Dili format |
| static [CFG](../../groupdocs.comparison.result/filetype/cfg) | Ayarları depolamak için kullanılan yapılandırma dosyası |
| static [CMAKE](../../groupdocs.comparison.result/filetype/cmake) | Software oluşturma sürecini yönetmek için araç |
| static [CMD](../../groupdocs.comparison.result/filetype/cmd) | DOS, OS/2 ve Microsoft Windows 'de betik dosyası |
| static [CONF](../../groupdocs.comparison.result/filetype/conf) | Unix ve Linux tabanlı sistemlerde kullanılan yapılandırma dosyası |
| static [CPP](../../groupdocs.comparison.result/filetype/cpp) | C Tabanlı Programlama Dili format |
| static [CPY](../../groupdocs.comparison.result/filetype/cpy) | Denetleyici Python Komut Dosyası format |
| static [CS](../../groupdocs.comparison.result/filetype/cs) | CSharp Programlama Dili format |
| static [CSV](../../groupdocs.comparison.result/filetype/csv) | Virgülle Ayrılmış Değerler Dosyası |
| static [CSX](../../groupdocs.comparison.result/filetype/csx) | CSharp betik dosyası format |
| static [CTP](../../groupdocs.comparison.result/filetype/ctp) | CakePHP Şablonu format |
| static [CXX](../../groupdocs.comparison.result/filetype/cxx) | C Tabanlı Programlama Dili format |
| static [DCM](../../groupdocs.comparison.result/filetype/dcm) | Tıpta Dijital Görüntüleme ve İletişim |
| static [DIFF](../../groupdocs.comparison.result/filetype/diff) | Veri karşılaştırma aracı format |
| static [DIR](../../groupdocs.comparison.result/filetype/dir) | Dizin, bilgisayar üzerinde dosyaları depolamak için bir konumdur |
| static [DJVU](../../groupdocs.comparison.result/filetype/djvu) | Deja Vu biçimi |
| static [DOC](../../groupdocs.comparison.result/filetype/doc) | Microsoft Word 97-2003 Document |
| static [DOCM](../../groupdocs.comparison.result/filetype/docm) | Microsoft Word Makro Etkin Belge |
| static [DOCX](../../groupdocs.comparison.result/filetype/docx) | Microsoft Word Belgesi |
| static [DOT](../../groupdocs.comparison.result/filetype/dot) | Microsoft Word 97-2003 Şablonu |
| static [DOTM](../../groupdocs.comparison.result/filetype/dotm) | Microsoft Word Makro Etkin Şablon |
| static [DOTX](../../groupdocs.comparison.result/filetype/dotx) | Microsoft Word Şablonu |
| static [DSQL](../../groupdocs.comparison.result/filetype/dsql) | Dinamik Yapılandırılmış Sorgu Dili format |
| static [DWG](../../groupdocs.comparison.result/filetype/dwg) | Autodesk Tasarım Veri Biçimleri |
| static [DXF](../../groupdocs.comparison.result/filetype/dxf) | AutoCAD Çizim Değişimi |
| static [EBUILD](../../groupdocs.comparison.result/filetype/ebuild) | Yazılım paketleri için derleme ve kurulum prosedürlerini otomatikleştiren özel bash betiği |
| static [EML](../../groupdocs.comparison.result/filetype/eml) | E-posta Mesajı |
| static [EMLX](../../groupdocs.comparison.result/filetype/emlx) | Apple Mail E-posta Dosyası |
| static [ERB](../../groupdocs.comparison.result/filetype/erb) | Ruby Programlama Dili format |
| static [ES6](../../groupdocs.comparison.result/filetype/es6) | JavaScript standardize betik dili biçimi |
| static [GEMSPEC](../../groupdocs.comparison.result/filetype/gemspec) | Bir RubyGems özniteliklerini belirten geliştirici dosyası |
| static [GIF](../../groupdocs.comparison.result/filetype/gif) | Grafik Değişim Biçimi |
| static [GRADLE](../../groupdocs.comparison.result/filetype/gradle) | Yapı-otomasyon sistemi format |
| static [GROOVY](../../groupdocs.comparison.result/filetype/groovy) | Groovy formatında yazılmış kaynak kod dosyası |
| static [GVY](../../groupdocs.comparison.result/filetype/gvy) | Groovy formatında yazılmış kaynak kod dosyası |
| static [GYP](../../groupdocs.comparison.result/filetype/gyp) | Derleme otomasyon aracı format |
| static [GYPI](../../groupdocs.comparison.result/filetype/gypi) | Derleme otomasyon aracı format |
| static [H](../../groupdocs.comparison.result/filetype/h) | C-Tabanlı başlık dosyaları, İşlevlerin ve Değişkenlerin tanımlarını içerir |
| static [HAML](../../groupdocs.comparison.result/filetype/haml) | Basitleştirilmiş HTML üretimi için işaretleme dili |
| static [HAR](../../groupdocs.comparison.result/filetype/har) | HTTP Arşiv formatı |
| static [HH](../../groupdocs.comparison.result/filetype/hh) | Bir C++ kaynak kodu tarafından başvurulan başlık bilgisi file |
| static [HPP](../../groupdocs.comparison.result/filetype/hpp) | C++ programlama dilinde yazılmış Başlık Dosyaları |
| static [HTML](../../groupdocs.comparison.result/filetype/html) | Köprü Metni İşaretleme Dili |
| static [HXX](../../groupdocs.comparison.result/filetype/hxx) | C++ programlama dilinde yazılmış Başlık Dosyaları |
| static [IPY](../../groupdocs.comparison.result/filetype/ipy) | IPython Komut Dosyası biçimi |
| static [JAVA](../../groupdocs.comparison.result/filetype/java) | Java Programlama Dili format |
| static [JPEG](../../groupdocs.comparison.result/filetype/jpeg) | Ortak Fotoğraf Uzmanları Grubu |
| static [JS](../../groupdocs.comparison.result/filetype/js) | JavaScript Programlama Dili format |
| static [JSCSRC](../../groupdocs.comparison.result/filetype/jscsrc) | JavaScript yapılandırma dosyası format |
| static [JSHINTRC](../../groupdocs.comparison.result/filetype/jshintrc) | JavaScript kodu kalite aracı |
| static [JSMAP](../../groupdocs.comparison.result/filetype/jsmap) | Kodun kaynak code 'ye nasıl çevrileceğine ilişkin bilgiler içeren JSON dosyası |
| static [JSON](../../groupdocs.comparison.result/filetype/json) | Verileri depolamak ve taşımak için hafif biçim |
| static [LESS](../../groupdocs.comparison.result/filetype/less) | Dinamik önişlemci stil sayfası dil format |
| static [LOG](../../groupdocs.comparison.result/filetype/log) | Günlüğe kaydetme, olayların, işlemlerin, mesajların ve iletişimin kaydını tutar |
| static [MAKE](../../groupdocs.comparison.result/filetype/make) | Makefile, make build otomasyon aracı tarafından bir hedef/goal oluşturmak için kullanılan bir dizi yönerge içeren bir dosyadır. |
| static [MARKDN](../../groupdocs.comparison.result/filetype/markdn) | İşaretleme Dili format |
| static [MARKDOWN](../../groupdocs.comparison.result/filetype/markdown) | İşaretleme Dili format |
| static [MD](../../groupdocs.comparison.result/filetype/md) | İşaretleme Dili format |
| static [MDOWN](../../groupdocs.comparison.result/filetype/mdown) | İşaretleme Dili format |
| static [MDTEXT](../../groupdocs.comparison.result/filetype/mdtext) | İşaretleme Dili format |
| static [MDTXT](../../groupdocs.comparison.result/filetype/mdtxt) | İşaretleme Dili format |
| static [MDWN](../../groupdocs.comparison.result/filetype/mdwn) | İşaretleme Dili format |
| static [MHTML](../../groupdocs.comparison.result/filetype/mhtml) | Mime HTML |
| static [MJS](../../groupdocs.comparison.result/filetype/mjs) | EcmaScript (ES) modülü dosyaları için uzantı |
| static [MK](../../groupdocs.comparison.result/filetype/mk) | Makefile, make build otomasyon aracı tarafından bir hedef/goal oluşturmak için kullanılan bir dizi yönerge içeren bir dosyadır. |
| static [MKD](../../groupdocs.comparison.result/filetype/mkd) | İşaretleme Dili format |
| static [ML](../../groupdocs.comparison.result/filetype/ml) | Caml Programlama Dili format |
| static [MLI](../../groupdocs.comparison.result/filetype/mli) | Caml Programlama Dili format |
| static [MOBI](../../groupdocs.comparison.result/filetype/mobi) | Mobipocket e-kitap formatı |
| static [MSG](../../groupdocs.comparison.result/filetype/msg) | Microsoft Outlook E-posta Mesajı |
| static [NQP](../../groupdocs.comparison.result/filetype/nqp) | Rakudo Perl 6 derleyicisini oluşturmak için kullanılan ara dil |
| static [OBJC](../../groupdocs.comparison.result/filetype/objc) | Objective-C Programlama Dili format |
| static [OBJCP](../../groupdocs.comparison.result/filetype/objcp) | Objective-C++ Programlama Dili format |
| static [ODP](../../groupdocs.comparison.result/filetype/odp) | OpenDocument Sunumu |
| static [ODS](../../groupdocs.comparison.result/filetype/ods) | OpenDocument Hesap Tablosu |
| static [ODT](../../groupdocs.comparison.result/filetype/odt) | OpenDocument Metni |
| static [ONE](../../groupdocs.comparison.result/filetype/one) | Microsoft OneNote Belgesi |
| static [OTP](../../groupdocs.comparison.result/filetype/otp) | OpenDocument Sunum Şablonu |
| static [OTT](../../groupdocs.comparison.result/filetype/ott) | OpenDocument Metin Şablonu |
| static [P6](../../groupdocs.comparison.result/filetype/p6) | Perl Programlama Dili format |
| static [PAC](../../groupdocs.comparison.result/filetype/pac) | JavaScript işlevi format için Proxy Otomatik Yapılandırma dosyası |
| static [PATCH](../../groupdocs.comparison.result/filetype/patch) | Farklılıkların listesi format |
| static [PDF](../../groupdocs.comparison.result/filetype/pdf) | Adobe Taşınabilir Belge formatı |
| static [PHP](../../groupdocs.comparison.result/filetype/php) | PHP Programlama Dili format |
| static [PHP4](../../groupdocs.comparison.result/filetype/php4) | PHP Programlama Dili format |
| static [PHP5](../../groupdocs.comparison.result/filetype/php5) | PHP Programlama Dili format |
| static [PHTML](../../groupdocs.comparison.result/filetype/phtml) | PHP 2 programları için standart dosya uzantısı format |
| static [PL](../../groupdocs.comparison.result/filetype/pl) | Perl Programlama Dili format |
| static [PL6](../../groupdocs.comparison.result/filetype/pl6) | Perl Programlama Dili format |
| static [PM](../../groupdocs.comparison.result/filetype/pm) | Perl modülü formatı |
| static [PM6](../../groupdocs.comparison.result/filetype/pm6) | Perl modülü formatı |
| static [PNG](../../groupdocs.comparison.result/filetype/png) | Taşınabilir Ağ Grafikleri |
| static [POD](../../groupdocs.comparison.result/filetype/pod) | Perl hafif biçimlendirme dili format |
| static [PODSPEC](../../groupdocs.comparison.result/filetype/podspec) | Ruby oluşturma ayarları format |
| static [POT](../../groupdocs.comparison.result/filetype/pot) | Microsoft PowerPoint şablonu |
| static [POTX](../../groupdocs.comparison.result/filetype/potx) | Microsoft PowerPoint Şablonu |
| static [PPS](../../groupdocs.comparison.result/filetype/pps) | Microsoft PowerPoint 97-2003 Slayt Gösterisi |
| static [PPSX](../../groupdocs.comparison.result/filetype/ppsx) | Microsoft PowerPoint Slayt Gösterisi |
| static [PPT](../../groupdocs.comparison.result/filetype/ppt) | Microsoft PowerPoint 97-2003 Sunumu |
| static [PPTX](../../groupdocs.comparison.result/filetype/pptx) | Microsoft PowerPoint Sunumu |
| static [PROP](../../groupdocs.comparison.result/filetype/prop) | Özellikler dosyası format |
| static [PSGI](../../groupdocs.comparison.result/filetype/psgi) | Web sunucuları ve web uygulamaları arasındaki arabirim ve Perl programlamasında yazılmış çerçeveler |
| static [PY](../../groupdocs.comparison.result/filetype/py) | Python Programlama Dili format |
| static [PYI](../../groupdocs.comparison.result/filetype/pyi) | Python Arayüz dosyası format |
| static [PYW](../../groupdocs.comparison.result/filetype/pyw) | Windows'ta bir betiğin çalıştırılması gerektiğini belirtmek için kullanılan dosyalar |
| static [RAKE](../../groupdocs.comparison.result/filetype/rake) | Ruby yapı otomasyon aracı |
| static [RB](../../groupdocs.comparison.result/filetype/rb) | Ruby Programlama Dili format |
| static [RBI](../../groupdocs.comparison.result/filetype/rbi) | Ruby Arayüzü dosya formatı |
| static [REJ](../../groupdocs.comparison.result/filetype/rej) | Reddedilen dosyalar format |
| static [RJS](../../groupdocs.comparison.result/filetype/rjs) | Ruby Programlama Dili format |
| static [RPY](../../groupdocs.comparison.result/filetype/rpy) | Oyunlar oluşturmak ve çalıştırmak için Python tabanlı dosya motoru |
| static [RST](../../groupdocs.comparison.result/filetype/rst) | Basit biçimlendirme dili |
| static [RTF](../../groupdocs.comparison.result/filetype/rtf) | Zengin Metin Belgesi |
| static [RU](../../groupdocs.comparison.result/filetype/ru) | Raf yapılandırma dosyası format |
| static [SASS](../../groupdocs.comparison.result/filetype/sass) | Stil sayfası dil biçimi |
| static [SBT](../../groupdocs.comparison.result/filetype/sbt) | Scala format için SBT oluşturma aracı |
| static [SC](../../groupdocs.comparison.result/filetype/sc) | Scala çalışma sayfası formatı |
| static [SCALA](../../groupdocs.comparison.result/filetype/scala) | Scala Programlama Dili format |
| static [SCSS](../../groupdocs.comparison.result/filetype/scss) | Stil sayfası dil biçimi |
| static [SH](../../groupdocs.comparison.result/filetype/sh) | Bash formatı için programlanmış komut dosyası |
| static [SQL](../../groupdocs.comparison.result/filetype/sql) | Yapılandırılmış Sorgu Dili format |
| static [SVG](../../groupdocs.comparison.result/filetype/svg) | Skaler Vektör Grafikleri |
| static [T](../../groupdocs.comparison.result/filetype/t) | Perl test dosyası formatı |
| static [TXT](../../groupdocs.comparison.result/filetype/txt) | Düz Metin Belgesi |
| static [UNKNOWN](../../groupdocs.comparison.result/filetype/unknown) | Bilinmeyen tür |
| static [VDX](../../groupdocs.comparison.result/filetype/vdx) | Microsoft Visio 2003-2010 XML Çizimi |
| static [VIM](../../groupdocs.comparison.result/filetype/vim) | Vim kaynak kodu dosyası format |
| static [VSD](../../groupdocs.comparison.result/filetype/vsd) | Microsoft Visio 2003-2010 Çizimi |
| static [VSDX](../../groupdocs.comparison.result/filetype/vsdx) | Microsoft Visio Çizimi |
| static [VSS](../../groupdocs.comparison.result/filetype/vss) | Microsoft Visio 2003-2010 Şablon |
| static [VST](../../groupdocs.comparison.result/filetype/vst) | Microsoft Visio 2003-2010 Şablonu |
| static [WEBMANIFEST](../../groupdocs.comparison.result/filetype/webmanifest) | Manifest dosyası, app hakkında bilgi içerir |
| static [XLS](../../groupdocs.comparison.result/filetype/xls) | Microsoft Excel 97-2003 Çalışma Sayfası |
| static [XLSB](../../groupdocs.comparison.result/filetype/xlsb) | Microsoft Excel İkili Çalışma Sayfası |
| static [XLSM](../../groupdocs.comparison.result/filetype/xlsm) | Microsoft Excel Makro Etkin Çalışma Sayfası |
| static [XLSX](../../groupdocs.comparison.result/filetype/xlsx) | Microsoft Excel Çalışma Sayfası |
| static [XLT](../../groupdocs.comparison.result/filetype/xlt) | Microsoft Excel şablonu |
| static [XLTM](../../groupdocs.comparison.result/filetype/xltm) | Makro özellikli Microsoft Excel şablonu |
| static [YAML](../../groupdocs.comparison.result/filetype/yaml) | İnsan tarafından okunabilen veri serileştirme dili format |
| static [YML](../../groupdocs.comparison.result/filetype/yml) | İnsan tarafından okunabilen veri serileştirme dili format |

### Notlar

**Daha fazla bilgi edin**

* GroupDocs tarafından desteklenen dosya biçimleri hakkında daha fazla bilgi edinin.Comparison: [Desteklenen belge biçimlerinin tam listesi](https://docs.groupdocs.com/display/comparisonnet/Supported+Document+Formats)
* C#'ta desteklenen dosya türleri hakkında daha fazla bilgi edinin: [C#'ta desteklenen dosya biçimleri nasıl elde edilir?](https://docs.groupdocs.com/display/comparisonnet/Get+supported+file+formats)

### Ayrıca bakınız

* ad alanı [GroupDocs.Comparison.Result](../../groupdocs.comparison.result)
* toplantı [GroupDocs.Comparison](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Comparison.dll -->
