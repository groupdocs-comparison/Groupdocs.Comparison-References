---
title: "FileType"
second_title: "Referensi API GroupDocs.Comparison untuk .NET"
description: "Mewakili tipe file. Menyediakan metode untuk memperoleh daftar semua tipe file yang didukung oleh GroupDocs.Comparison, mendeteksi tipe file berdasarkan ekstensi, dll."
type: docs
weight: 480
url: /id/net/groupdocs.comparison.result/filetype/
---
## FileType class

Merepresentasikan tipe file. Menyediakan metode untuk memperoleh daftar semua tipe file yang didukung oleh GroupDocs.Comparison, mendeteksi tipe file berdasarkan ekstensi, dll.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Extension](../../groupdocs.comparison.result/filetype/extension) { get; } | Ekstensi file |
| [FileFormat](../../groupdocs.comparison.result/filetype/fileformat) { get; } | Format file |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [FromFileNameOrExtension](../../groupdocs.comparison.result/filetype/fromfilenameorextension)(string) | Kembalikan FileType berdasarkan nama file atau ekstensi |
| [Equals](../../groupdocs.comparison.result/filetype/equals#equals)(FileType) | Pemeriksaan kesetaraan tipe file |
| override [Equals](../../groupdocs.comparison.result/filetype/equals#equals_1)(object) | Pemeriksaan kesetaraan dengan objek |
| override [GetHashCode](../../groupdocs.comparison.result/filetype/gethashcode)() | Dapatkan kode hash |
| override [ToString](../../groupdocs.comparison.result/filetype/tostring)() | ToString |
| static [GetSupportedFileTypes](../../groupdocs.comparison.result/filetype/getsupportedfiletypes)() | Dapatkan enumerasi tipe file yang didukung |
| [operator ==](../../groupdocs.comparison.result/filetype/op_equality) | Overload operator |
| [operator !=](../../groupdocs.comparison.result/filetype/op_inequality) | Overload operator |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| static readonly [AS](../../groupdocs.comparison.result/filetype/as) | Format Bahasa Pemrograman ActionScript |
| static readonly [AS3](../../groupdocs.comparison.result/filetype/as3) | Format Bahasa Pemrograman ActionScript |
| static readonly [ASM](../../groupdocs.comparison.result/filetype/asm) | Format ASM |
| static readonly [BASH](../../groupdocs.comparison.result/filetype/bash) | Jenis interpreter yang memproses perintah shell |
| static readonly [BASHRC](../../groupdocs.comparison.result/filetype/bashrc) | File yang menentukan perilaku shell interaktif |
| static readonly [BAT](../../groupdocs.comparison.result/filetype/bat) | File skrip di DOS, OS/2, dan Microsoft Windows |
| static readonly [BMP](../../groupdocs.comparison.result/filetype/bmp) | Gambar Bitmap |
| static readonly [BOWERRC](../../groupdocs.comparison.result/filetype/bowerrc) | File konfigurasi untuk kontrol paket di sisi server |
| static readonly [C](../../groupdocs.comparison.result/filetype/c) | Format Bahasa Pemrograman Berbasis C |
| static readonly [CAD](../../groupdocs.comparison.result/filetype/cad) | Format file CAD |
| static readonly [CAKE](../../groupdocs.comparison.result/filetype/cake) | Format sistem otomasi build lintas platform CSharp |
| static readonly [CC](../../groupdocs.comparison.result/filetype/cc) | Format Bahasa Pemrograman Berbasis C |
| static readonly [CFG](../../groupdocs.comparison.result/filetype/cfg) | File konfigurasi yang digunakan untuk menyimpan pengaturan |
| static readonly [CMAKE](../../groupdocs.comparison.result/filetype/cmake) | Alat untuk mengelola proses build perangkat lunak |
| static readonly [CMD](../../groupdocs.comparison.result/filetype/cmd) | File skrip di DOS, OS/2, dan Microsoft Windows |
| static readonly [CONF](../../groupdocs.comparison.result/filetype/conf) | File konfigurasi yang digunakan pada sistem berbasis Unix dan Linux |
| static readonly [CPP](../../groupdocs.comparison.result/filetype/cpp) | Format Bahasa Pemrograman Berbasis C |
| static readonly [CPY](../../groupdocs.comparison.result/filetype/cpy) | Format Skrip Python Controller |
| static readonly [CS](../../groupdocs.comparison.result/filetype/cs) | Format Bahasa Pemrograman CSharp |
| static readonly [CSV](../../groupdocs.comparison.result/filetype/csv) | File Nilai Dipisahkan Koma |
| static readonly [CSX](../../groupdocs.comparison.result/filetype/csx) | Format file skrip CSharp |
| static readonly [CTP](../../groupdocs.comparison.result/filetype/ctp) | Format templat CakePHP |
| static readonly [CXX](../../groupdocs.comparison.result/filetype/cxx) | Format Bahasa Pemrograman Berbasis C |
| static readonly [DCM](../../groupdocs.comparison.result/filetype/dcm) | Penginderaan Digital dan Komunikasi dalam Kedokteran |
| static readonly [DIFF](../../groupdocs.comparison.result/filetype/diff) | Format alat perbandingan data |
| static readonly [DIR](../../groupdocs.comparison.result/filetype/dir) | Direktori adalah lokasi untuk menyimpan file di komputer |
| static readonly [DJVU](../../groupdocs.comparison.result/filetype/djvu) | Format Deja Vu |
| static readonly [DOC](../../groupdocs.comparison.result/filetype/doc) | Dokumen Microsoft Word 97-2003 |
| static readonly [DOCM](../../groupdocs.comparison.result/filetype/docm) | Dokumen Microsoft Word yang Mendukung Makro |
| static readonly [DOCX](../../groupdocs.comparison.result/filetype/docx) | Dokumen Microsoft Word |
| static readonly [DOT](../../groupdocs.comparison.result/filetype/dot) | Templat Microsoft Word 97-2003 |
| static readonly [DOTM](../../groupdocs.comparison.result/filetype/dotm) | Templat Microsoft Word yang Mendukung Makro |
| static readonly [DOTX](../../groupdocs.comparison.result/filetype/dotx) | Templat Microsoft Word |
| static readonly [DSQL](../../groupdocs.comparison.result/filetype/dsql) | Format Dynamic Structured Query Language |
| static readonly [DWG](../../groupdocs.comparison.result/filetype/dwg) | Format Data Desain Autodesk |
| static readonly [DXF](../../groupdocs.comparison.result/filetype/dxf) | Pertukaran Gambar AutoCAD |
| static readonly [EBUILD](../../groupdocs.comparison.result/filetype/ebuild) | Skrip bash khusus yang mengotomatiskan prosedur kompilasi dan instalasi untuk paket perangkat lunak |
| static readonly [EML](../../groupdocs.comparison.result/filetype/eml) | Pesan Email |
| static readonly [EMLX](../../groupdocs.comparison.result/filetype/emlx) | File Email Apple Mail |
| static readonly [ERB](../../groupdocs.comparison.result/filetype/erb) | Format Bahasa Pemrograman Ruby |
| static readonly [ES6](../../groupdocs.comparison.result/filetype/es6) | Format bahasa skrip JavaScript yang distandarisasi |
| static readonly [GEMSPEC](../../groupdocs.comparison.result/filetype/gemspec) | File pengembang yang menentukan atribut RubyGems |
| static readonly [GIF](../../groupdocs.comparison.result/filetype/gif) | Format Pertukaran Grafik |
| static readonly [GRADLE](../../groupdocs.comparison.result/filetype/gradle) | Format sistem otomatisasi build |
| static readonly [GROOVY](../../groupdocs.comparison.result/filetype/groovy) | File kode sumber yang ditulis dalam format Groovy |
| static readonly [GVY](../../groupdocs.comparison.result/filetype/gvy) | File kode sumber yang ditulis dalam format Groovy |
| static readonly [GYP](../../groupdocs.comparison.result/filetype/gyp) | Format alat otomatisasi build |
| static readonly [GYPI](../../groupdocs.comparison.result/filetype/gypi) | Format alat otomatisasi build |
| static readonly [H](../../groupdocs.comparison.result/filetype/h) | File header berbasis C berisi definisi Fungsi dan Variabel |
| static readonly [HAML](../../groupdocs.comparison.result/filetype/haml) | Bahasa markup untuk pembuatan HTML yang disederhanakan |
| static readonly [HAR](../../groupdocs.comparison.result/filetype/har) | Format HTTP Archive |
| static readonly [HH](../../groupdocs.comparison.result/filetype/hh) | Informasi header yang dirujuk oleh file kode sumber C++ |
| static readonly [HPP](../../groupdocs.comparison.result/filetype/hpp) | File Header yang ditulis dalam bahasa pemrograman C++ |
| static readonly [HTML](../../groupdocs.comparison.result/filetype/html) | HyperText Markup Language |
| static readonly [HXX](../../groupdocs.comparison.result/filetype/hxx) | File Header yang ditulis dalam bahasa pemrograman C++ |
| static readonly [IPY](../../groupdocs.comparison.result/filetype/ipy) | Format Skrip IPython |
| static readonly [JAVA](../../groupdocs.comparison.result/filetype/java) | Format Bahasa Pemrograman Java |
| static readonly [JPEG](../../groupdocs.comparison.result/filetype/jpeg) | Joint Photographic Experts Group |
| static readonly [JS](../../groupdocs.comparison.result/filetype/js) | Format Bahasa Pemrograman JavaScript |
| static readonly [JSCSRC](../../groupdocs.comparison.result/filetype/jscsrc) | Format berkas konfigurasi JavaScript |
| static readonly [JSHINTRC](../../groupdocs.comparison.result/filetype/jshintrc) | Alat kualitas kode JavaScript |
| static readonly [JSMAP](../../groupdocs.comparison.result/filetype/jsmap) | Berkas JSON yang berisi informasi tentang cara menerjemahkan kode kembali ke kode sumber |
| static readonly [JSON](../../groupdocs.comparison.result/filetype/json) | Format ringan untuk menyimpan dan mentransfer data |
| static readonly [LESS](../../groupdocs.comparison.result/filetype/less) | Format bahasa lembar gaya preprocessor dinamis |
| static readonly [LOG](../../groupdocs.comparison.result/filetype/log) | Logging menyimpan registri peristiwa, proses, pesan, dan komunikasi |
| static readonly [MAKE](../../groupdocs.comparison.result/filetype/make) | Makefile adalah berkas yang berisi sekumpulan arahan yang digunakan oleh alat otomasi build make untuk menghasilkan target/tujuan |
| static readonly [MARKDN](../../groupdocs.comparison.result/filetype/markdn) | Format Bahasa Markdown |
| static readonly [MARKDOWN](../../groupdocs.comparison.result/filetype/markdown) | Format Bahasa Markdown |
| static readonly [MD](../../groupdocs.comparison.result/filetype/md) | Format Bahasa Markdown |
| static readonly [MDOWN](../../groupdocs.comparison.result/filetype/mdown) | Format Bahasa Markdown |
| static readonly [MDTEXT](../../groupdocs.comparison.result/filetype/mdtext) | Format Bahasa Markdown |
| static readonly [MDTXT](../../groupdocs.comparison.result/filetype/mdtxt) | Format Bahasa Markdown |
| static readonly [MDWN](../../groupdocs.comparison.result/filetype/mdwn) | Format Bahasa Markdown |
| static readonly [MHTML](../../groupdocs.comparison.result/filetype/mhtml) | Mime HTML |
| static readonly [MJS](../../groupdocs.comparison.result/filetype/mjs) | Ekstensi untuk berkas modul EcmaScript (ES) |
| static readonly [MK](../../groupdocs.comparison.result/filetype/mk) | Makefile adalah berkas yang berisi sekumpulan arahan yang digunakan oleh alat otomasi build make untuk menghasilkan target/tujuan |
| static readonly [MKD](../../groupdocs.comparison.result/filetype/mkd) | Format Bahasa Markdown |
| static readonly [ML](../../groupdocs.comparison.result/filetype/ml) | Format Bahasa Pemrograman Caml |
| static readonly [MLI](../../groupdocs.comparison.result/filetype/mli) | Format Bahasa Pemrograman Caml |
| static readonly [MOBI](../../groupdocs.comparison.result/filetype/mobi) | Format e-book Mobipocket |
| static readonly [MSG](../../groupdocs.comparison.result/filetype/msg) | Pesan Email Microsoft Outlook |
| static readonly [NQP](../../groupdocs.comparison.result/filetype/nqp) | Bahasa menengah yang digunakan untuk membangun kompiler Rakudo Perl 6 |
| static readonly [OBJC](../../groupdocs.comparison.result/filetype/objc) | Format Bahasa Pemrograman Objective-C |
| static readonly [OBJCP](../../groupdocs.comparison.result/filetype/objcp) | Format Bahasa Pemrograman Objective-C++ |
| static readonly [ODP](../../groupdocs.comparison.result/filetype/odp) | Presentasi OpenDocument |
| static readonly [ODS](../../groupdocs.comparison.result/filetype/ods) | Lembar Kerja OpenDocument |
| static readonly [ODT](../../groupdocs.comparison.result/filetype/odt) | Teks OpenDocument |
| static readonly [ONE](../../groupdocs.comparison.result/filetype/one) | Dokumen Microsoft OneNote |
| static readonly [OTP](../../groupdocs.comparison.result/filetype/otp) | Templat Presentasi OpenDocument |
| static readonly [OTT](../../groupdocs.comparison.result/filetype/ott) | Templat Teks OpenDocument |
| static readonly [P6](../../groupdocs.comparison.result/filetype/p6) | Format Bahasa Pemrograman Perl |
| static readonly [PAC](../../groupdocs.comparison.result/filetype/pac) | Format file Proxy Auto-Configuration untuk fungsi JavaScript |
| static readonly [PATCH](../../groupdocs.comparison.result/filetype/patch) | Format daftar perbedaan |
| static readonly [PDF](../../groupdocs.comparison.result/filetype/pdf) | Format Dokumen Portabel Adobe |
| static readonly [PHP](../../groupdocs.comparison.result/filetype/php) | Format Bahasa Pemrograman PHP |
| static readonly [PHP4](../../groupdocs.comparison.result/filetype/php4) | Format Bahasa Pemrograman PHP |
| static readonly [PHP5](../../groupdocs.comparison.result/filetype/php5) | Format Bahasa Pemrograman PHP |
| static readonly [PHTML](../../groupdocs.comparison.result/filetype/phtml) | Format ekstensi file standar untuk program PHP 2 |
| static readonly [PL](../../groupdocs.comparison.result/filetype/pl) | Format Bahasa Pemrograman Perl |
| static readonly [PL6](../../groupdocs.comparison.result/filetype/pl6) | Format Bahasa Pemrograman Perl |
| static readonly [PM](../../groupdocs.comparison.result/filetype/pm) | Format modul Perl |
| static readonly [PM6](../../groupdocs.comparison.result/filetype/pm6) | Format modul Perl |
| static readonly [PNG](../../groupdocs.comparison.result/filetype/png) | Grafik Jaringan Portabel |
| static readonly [POD](../../groupdocs.comparison.result/filetype/pod) | Format bahasa markup ringan Perl |
| static readonly [PODSPEC](../../groupdocs.comparison.result/filetype/podspec) | Format pengaturan build Ruby |
| static readonly [POT](../../groupdocs.comparison.result/filetype/pot) | Templat Microsoft PowerPoint |
| static readonly [POTX](../../groupdocs.comparison.result/filetype/potx) | Templat Microsoft PowerPoint |
| static readonly [PPS](../../groupdocs.comparison.result/filetype/pps) | Pertunjukan Slide Microsoft PowerPoint 97-2003 |
| static readonly [PPSX](../../groupdocs.comparison.result/filetype/ppsx) | Pertunjukan Slide Microsoft PowerPoint |
| static readonly [PPT](../../groupdocs.comparison.result/filetype/ppt) | Presentasi Microsoft PowerPoint 97-2003 |
| static readonly [PPTX](../../groupdocs.comparison.result/filetype/pptx) | Presentasi Microsoft PowerPoint |
| static readonly [PROP](../../groupdocs.comparison.result/filetype/prop) | Format file properti |
| static readonly [PSGI](../../groupdocs.comparison.result/filetype/psgi) | Antarmuka antara server web dan aplikasi web serta kerangka kerja yang ditulis dalam pemrograman Perl |
| static readonly [PY](../../groupdocs.comparison.result/filetype/py) | Format Bahasa Pemrograman Python |
| static readonly [PYI](../../groupdocs.comparison.result/filetype/pyi) | Format berkas Antarmuka Python |
| static readonly [PYW](../../groupdocs.comparison.result/filetype/pyw) | Berkas yang digunakan di Windows untuk menunjukkan bahwa skrip perlu dijalankan |
| static readonly [RAKE](../../groupdocs.comparison.result/filetype/rake) | Alat otomatisasi build Ruby |
| static readonly [RB](../../groupdocs.comparison.result/filetype/rb) | Format Bahasa Pemrograman Ruby |
| static readonly [RBI](../../groupdocs.comparison.result/filetype/rbi) | Format berkas Antarmuka Ruby |
| static readonly [REJ](../../groupdocs.comparison.result/filetype/rej) | Format berkas yang ditolak |
| static readonly [RJS](../../groupdocs.comparison.result/filetype/rjs) | Format Bahasa Pemrograman Ruby |
| static readonly [RPY](../../groupdocs.comparison.result/filetype/rpy) | Mesin berkas berbasis Python untuk membuat dan menjalankan game |
| static readonly [RST](../../groupdocs.comparison.result/filetype/rst) | Bahasa markup ringan |
| static readonly [RTF](../../groupdocs.comparison.result/filetype/rtf) | Dokumen Teks Kaya |
| static readonly [RU](../../groupdocs.comparison.result/filetype/ru) | Format berkas konfigurasi Rack |
| static readonly [SASS](../../groupdocs.comparison.result/filetype/sass) | Format bahasa lembar gaya |
| static readonly [SBT](../../groupdocs.comparison.result/filetype/sbt) | Alat build SBT untuk format Scala |
| static readonly [SC](../../groupdocs.comparison.result/filetype/sc) | Format lembar kerja Scala |
| static readonly [SCALA](../../groupdocs.comparison.result/filetype/scala) | Format Bahasa Pemrograman Scala |
| static readonly [SCSS](../../groupdocs.comparison.result/filetype/scss) | Format bahasa lembar gaya |
| static readonly [SH](../../groupdocs.comparison.result/filetype/sh) | Skrip yang diprogram untuk format bash |
| static readonly [SQL](../../groupdocs.comparison.result/filetype/sql) | Format Bahasa Query Terstruktur |
| static readonly [SVG](../../groupdocs.comparison.result/filetype/svg) | Grafik Vektor Skalar |
| static readonly [T](../../groupdocs.comparison.result/filetype/t) | Format berkas uji Perl |
| static readonly [TXT](../../groupdocs.comparison.result/filetype/txt) | Dokumen Teks Biasa |
| static readonly [UNKNOWN](../../groupdocs.comparison.result/filetype/unknown) | Tipe tidak diketahui |
| static readonly [VDX](../../groupdocs.comparison.result/filetype/vdx) | Gambar XML Microsoft Visio 2003-2010 |
| static readonly [VIM](../../groupdocs.comparison.result/filetype/vim) | Format berkas kode sumber Vim |
| static readonly [VSD](../../groupdocs.comparison.result/filetype/vsd) | Gambar Microsoft Visio 2003-2010 |
| static readonly [VSDX](../../groupdocs.comparison.result/filetype/vsdx) | Gambar Microsoft Visio |
| static readonly [VSS](../../groupdocs.comparison.result/filetype/vss) | Stensil Microsoft Visio 2003-2010 |
| static readonly [VST](../../groupdocs.comparison.result/filetype/vst) | Templat Microsoft Visio 2003-2010 |
| static readonly [WEBMANIFEST](../../groupdocs.comparison.result/filetype/webmanifest) | File manifes berisi informasi tentang aplikasi |
| static readonly [XLS](../../groupdocs.comparison.result/filetype/xls) | Lembar kerja Microsoft Excel 97-2003 |
| static readonly [XLSB](../../groupdocs.comparison.result/filetype/xlsb) | Lembar kerja Biner Microsoft Excel |
| static readonly [XLSM](../../groupdocs.comparison.result/filetype/xlsm) | Lembar kerja Microsoft Excel dengan Makro |
| static readonly [XLSX](../../groupdocs.comparison.result/filetype/xlsx) | Lembar kerja Microsoft Excel |
| static readonly [XLT](../../groupdocs.comparison.result/filetype/xlt) | Templat Microsoft Excel |
| static readonly [XLTM](../../groupdocs.comparison.result/filetype/xltm) | Templat Microsoft Excel dengan makro |
| static readonly [YAML](../../groupdocs.comparison.result/filetype/yaml) | Format bahasa serialisasi data yang dapat dibaca manusia |
| static readonly [YML](../../groupdocs.comparison.result/filetype/yml) | Format bahasa serialisasi data yang dapat dibaca manusia |

### Catatan

**Learn more**

* Learn more about file formats supported by GroupDocs.Comparison: [Full list of supported document formats](https://docs.groupdocs.com/display/comparisonnet/Supported+Document+Formats)
* Learn more about getting supported file types in C#: [How to get supported file formats in C#](https://docs.groupdocs.com/display/comparisonnet/Get+supported+file+formats)

### Lihat Juga

* namespace [GroupDocs.Comparison.Result](../../groupdocs.comparison.result)
* assembly [GroupDocs.Comparison](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Comparison.dll -->
