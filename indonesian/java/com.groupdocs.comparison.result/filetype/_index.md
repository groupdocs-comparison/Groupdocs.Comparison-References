---
title: "FileType"
second_title: "Referensi API GroupDocs.Comparison untuk Java"
description: "Enum FileType mewakili tipe file yang digunakan dalam proses perbandingan dokumen."
type: docs
weight: 16
url: /id/java/com.groupdocs.comparison.result/filetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public enum FileType extends Enum<FileType> implements System.IEquatable<FileType>
```

Enum FileType mewakili tipe file yang digunakan dalam proses perbandingan dokumen.


Ini mendefinisikan berbagai jenis file seperti dokumen Word, file PDF, dan lainnya.
Menyediakan metode untuk memperoleh daftar semua jenis file yang didukung oleh GroupDocs.Comparison, mendeteksi jenis file berdasarkan ekstensi, dll.
Gunakan enum ini untuk menentukan jenis file saat bekerja dengan pustaka GroupDocs.Comparison.

* Learn more about file formats supported by GroupDocs.Comparison: [Full list of supported document formats](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* Learn more about getting supported file types in Java: [How to get supported file formats in Java](../https://docs.groupdocs.com/display/comparisonjava/Get+supported+file+formats)


Contoh penggunaan:

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


## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [UNKNOWN](#UNKNOWN) | Tipe tidak diketahui |
|
|  | [AS](#AS) | format Bahasa Pemrograman ActionScript |
|
|  | [AS3](#AS3) | format Bahasa Pemrograman ActionScript |
|
|  | [ASM](#ASM) | format Bahasa Pemrograman Assembler |
|
|  | [BAT](#BAT) | File skrip di DOS, OS/2, dan Microsoft Windows |
|
|  | [CMD](#CMD) | File skrip di DOS, OS/2, dan Microsoft Windows |
|
|  | [C](#C) | format Bahasa Pemrograman Berbasis C |
|
|  | [H](#H) | File header berbasis C berisi definisi Fungsi dan Variabel |
|
|  | [PDF](#PDF) | format Adobe Portable Document |
|
|  | [DOC](#DOC) | Dokumen Microsoft Word 97-2003 |
|
|  | [DOCM](#DOCM) | Dokumen Microsoft Word yang Mendukung Makro |
|
|  | [DOCX](#DOCX) | Dokumen Microsoft Word |
|
|  | [DOT](#DOT) | Templat Microsoft Word 97-2003 |
|
|  | [DOTM](#DOTM) | Templat Microsoft Word yang Mendukung Makro |
|
|  | [DOTX](#DOTX) | Templat Microsoft Word |
|
|  | [XLS](#XLS) | Lembar Kerja Microsoft Excel 97-2003 |
|
|  | [XLT](#XLT) | Templat Microsoft Excel |
|
|  | [XLSX](#XLSX) | Lembar Kerja Microsoft Excel |
|
|  | [XLTM](#XLTM) | Templat Microsoft Excel yang Mendukung Makro |
|
|  | [XLSB](#XLSB) | Microsoft Excel Lembar Kerja Biner |
|
|  | [XLSM](#XLSM) | Microsoft Excel Lembar Kerja Makro-Aktif |
|
|  | [POT](#POT) | Microsoft PowerPoint templat |
|
|  | [POTX](#POTX) | Microsoft PowerPoint Templat |
|
|  | [POTM](#POTM) | Microsoft PowerPoint Templat dengan dukungan Makro |
|
|  | [PPS](#PPS) | Microsoft PowerPoint 97-2003 Tayangan Slide |
|
|  | [PPSX](#PPSX) | Microsoft PowerPoint Tayangan Slide |
|
|  | [PPTX](#PPTX) | Microsoft PowerPoint Presentasi |
|
|  | [PPT](#PPT) | Microsoft PowerPoint 97-2003 Presentasi |
|
|  | [PPTM](#PPTM) | Microsoft PowerPoint Presentasi Makro-Aktif |
|
|  | [PPSM](#PPSM) | Microsoft PowerPoint Presentasi Tayangan Slide Makro-Aktif |
|
|  | [VSDX](#VSDX) | Microsoft Visio Gambar |
|
|  | [VSD](#VSD) | Microsoft Visio 2003-2010 Gambar |
|
|  | [VSS](#VSS) | Microsoft Visio 2003-2010 Stensil |
|
|  | [VST](#VST) | Microsoft Visio 2003-2010 Templat |
|
|  | [VDX](#VDX) | Microsoft Visio 2003-2010 Gambar XML |
|
|  | [ONE](#ONE) | Microsoft OneNote Dokumen |
|
|  | [ODT](#ODT) | OpenDocument Teks |
|
|  | [ODP](#ODP) | OpenDocument Presentasi |
|
|  | [OTP](#OTP) | OpenDocument Templat Presentasi |
|
|  | [ODS](#ODS) | OpenDocument Lembar Hitung |
|
|  | [OTT](#OTT) | OpenDocument Templat Teks |
|
|  | [RTF](#RTF) | Dokumen Teks Kaya |
|
|  | [TXT](#TXT) | Dokumen Teks Biasa |
|
|  | [CSV](#CSV) | File Nilai Dipisahkan Koma |
|
|  | [HTML](#HTML) | Bahasa Markup Hiperteks |
|
|  | [MHTML](#MHTML) | HTML MIME |
|
|  | [MOBI](#MOBI) | format e-book Mobipocket |
|
|  | [DCM](#DCM) | Pencitraan Digital dan Komunikasi dalam Kedokteran |
|
|  | [DJVU](#DJVU) | format Deja Vu |
|
|  | [DWG](#DWG) | Format Data Desain Autodesk |
|
|  | [DXF](#DXF) | Pertukaran Gambar AutoCAD |
|
|  | [BMP](#BMP) | Gambar Bitmap |
|
|  | [GIF](#GIF) | Format Pertukaran Grafik |
|
|  | [JPEG](#JPEG) | Kelompok Ahli Fotografi Bersama |
|
|  | [JPG](#JPG) | Kelompok Ahli Fotografi Bersama |
|
|  | [PNG](#PNG) | Grafik Jaringan Portabel |
|
|  | [SVG](#SVG) | Grafik Vektor Skalar |
|
|  | [EML](#EML) | Pesan Email |
|
|  | [EMLX](#EMLX) | File Email Apple Mail |
|
|  | [MSG](#MSG) | Pesan Email Microsoft Outlook |
|
|  | [CAD](#CAD) | format file CAD |
|
|  | [CPP](#CPP) | format Bahasa Pemrograman Berbasis C |
|
|  | [CC](#CC) | format Bahasa Pemrograman Berbasis C |
|
|  | [CXX](#CXX) | format Bahasa Pemrograman Berbasis C |
|
|  | [HXX](#HXX) | Berkas Header yang ditulis dalam bahasa pemrograman C++ |
|
|  | [HH](#HH) | Informasi header yang dirujuk oleh berkas kode sumber C++ |
|
|  | [HPP](#HPP) | Berkas Header yang ditulis dalam bahasa pemrograman C++ |
|
|  | [CMAKE](#CMAKE) | Alat untuk mengelola proses build perangkat lunak |
|
|  | [CS](#CS) | format Bahasa Pemrograman CSharp |
|
|  | [CSX](#CSX) | format berkas skrip CSharp |
|
|  | [CAKE](#CAKE) | format sistem otomasi build lintas platform CSharp |
|
|  | [DIFF](#DIFF) | format alat perbandingan data |
|
|  | [PATCH](#PATCH) | format daftar perbedaan |
|
|  | [REJ](#REJ) | format berkas yang ditolak |
|
|  | [GROOVY](#GROOVY) | File kode sumber yang ditulis dalam format Groovy |
|
|  | [GVY](#GVY) | File kode sumber yang ditulis dalam format Groovy |
|
|  | [GRADLE](#GRADLE) | Format sistem otomatisasi build |
|
|  | [HAML](#HAML) | Bahasa markup untuk pembuatan HTML yang disederhanakan |
|
|  | [JS](#JS) | Format Bahasa Pemrograman JavaScript |
|
|  | [ES6](#ES6) | Format bahasa skrip JavaScript yang distandarisasi |
|
|  | [MJS](#MJS) | Ekstensi untuk file modul EcmaScript (ES) |
|
|  | [PAC](#PAC) | File Proxy Auto-Configuration untuk format fungsi JavaScript |
|
|  | [JSON](#JSON) | Format ringan untuk menyimpan dan mentransfer data |
|
|  | [BOWERRC](#BOWERRC) | File konfigurasi untuk kontrol paket di sisi server |
|
|  | [JSHINTRC](#JSHINTRC) | Alat kualitas kode JavaScript |
|
|  | [JSCSRC](#JSCSRC) | Format file konfigurasi JavaScript |
|
|  | [WEBMANIFEST](#WEBMANIFEST) | File manifest berisi informasi tentang aplikasi |
|
|  | [JSMAP](#JSMAP) | File JSON yang berisi informasi tentang cara menerjemahkan kode kembali ke kode sumber |
|
|  | [HAR](#HAR) | Format HTTP Archive |
|
|  | [JAVA](#JAVA) | Format Bahasa Pemrograman Java |
|
|  | [LESS](#LESS) | Format bahasa lembar gaya preprocessor dinamis |
|
|  | [LOG](#LOG) | Logging menyimpan registri peristiwa, proses, pesan, dan komunikasi |
|
|  | [MAKE](#MAKE) | Makefile adalah file yang berisi sekumpulan arahan yang digunakan oleh alat otomatisasi build make untuk menghasilkan target/tujuan |
|
|  | [MK](#MK) | Makefile adalah file yang berisi sekumpulan arahan yang digunakan oleh alat otomatisasi build make untuk menghasilkan target/tujuan |
|
|  | [MD](#MD) | Format Bahasa Markdown |
|
|  | [MKD](#MKD) | Format Bahasa Markdown |
|
|  | [MDWN](#MDWN) | Format Bahasa Markdown |
|
|  | [MDOWN](#MDOWN) | Format Bahasa Markdown |
|
|  | [MARKDOWN](#MARKDOWN) | Format Bahasa Markdown |
|
|  | [MARKDN](#MARKDN) | Format Bahasa Markdown |
|
|  | [MDTXT](#MDTXT) | Format Bahasa Markdown |
|
|  | [MDTEXT](#MDTEXT) | Format Bahasa Markdown |
|
|  | [ML](#ML) | Format Bahasa Pemrograman Caml |
|
|  | [MLI](#MLI) | Format Bahasa Pemrograman Caml |
|
|  | [OBJC](#OBJC) | Format Bahasa Pemrograman Objective-C |
|
|  | [OBJCP](#OBJCP) | Format Bahasa Pemrograman Objective-C++ |
|
|  | [PHP](#PHP) | Format Bahasa Pemrograman PHP |
|
|  | [PHP4](#PHP4) | Format Bahasa Pemrograman PHP |
|
|  | [PHP5](#PHP5) | Format Bahasa Pemrograman PHP |
|
|  | [PHTML](#PHTML) | Ekstensi file standar untuk format program PHP 2 |
|
|  | [CTP](#CTP) | Format Template CakePHP |
|
|  | [PL](#PL) | Format Bahasa Pemrograman Perl |
|
|  | [PM](#PM) | Format modul Perl |
|
|  | [POD](#POD) | Format bahasa markup ringan Perl |
|
|  | [T](#T) | Format berkas uji Perl |
|
|  | [PSGI](#PSGI) | Antarmuka antara server web dan aplikasi web serta kerangka kerja yang ditulis dalam pemrograman Perl |
|
|  | [P6](#P6) | Format Bahasa Pemrograman Perl |
|
|  | [PL6](#PL6) | Format Bahasa Pemrograman Perl |
|
|  | [PM6](#PM6) | Format modul Perl |
|
|  | [NQP](#NQP) | Bahasa menengah yang digunakan untuk membangun kompiler Rakudo Perl 6 |
|
|  | [PROP](#PROP) | Format berkas properti |
|
|  | [CFG](#CFG) | Berkas konfigurasi yang digunakan untuk menyimpan pengaturan |
|
|  | [CONF](#CONF) | Berkas konfigurasi yang digunakan pada sistem berbasis Unix dan Linux |
|
|  | [DIR](#DIR) | Direktori adalah lokasi untuk menyimpan berkas di komputer |
|
|  | [PY](#PY) | Format Bahasa Pemrograman Python |
|
|  | [RPY](#RPY) | Mesin berkas berbasis Python untuk membuat dan menjalankan permainan |
|
|  | [PYW](#PYW) | Berkas yang digunakan di Windows untuk menunjukkan bahwa skrip perlu dijalankan |
|
|  | [CPY](#CPY) | Format Skrip Python Kontroler |
|
|  | [GYP](#GYP) | Format alat otomasi pembangunan |
|
|  | [GYPI](#GYPI) | Format alat otomasi pembangunan |
|
|  | [PYI](#PYI) | Format berkas Antarmuka Python |
|
|  | [IPY](#IPY) | Format Skrip IPython |
|
|  | [RST](#RST) | Bahasa markup ringan |
|
|  | [RB](#RB) | Format Bahasa Pemrograman Ruby |
|
|  | [ERB](#ERB) | Format Bahasa Pemrograman Ruby |
|
|  | [RJS](#RJS) | Format Bahasa Pemrograman Ruby |
|
|  | [GEMSPEC](#GEMSPEC) | Berkas pengembang yang menentukan atribut RubyGems |
|
|  | [RAKE](#RAKE) | Alat otomasi pembangunan Ruby |
|
|  | [RU](#RU) | Format berkas konfigurasi Rack |
|
|  | [PODSPEC](#PODSPEC) | Format pengaturan pembangunan Ruby |
|
|  | [RBI](#RBI) | Format berkas Antarmuka Ruby |
|
|  | [SASS](#SASS) | Format bahasa lembar gaya |
|
|  | [SCSS](#SCSS) | Format bahasa lembar gaya |
|
|  | [SCALA](#SCALA) | Format Bahasa Pemrograman Scala |
|
|  | [SBT](#SBT) | Alat build SBT untuk format Scala |
|
|  | [SC](#SC) | Format lembar kerja Scala |
|
|  | [SH](#SH) | Format skrip yang diprogram untuk bash |
|
|  | [BASH](#BASH) | Jenis interpreter yang memproses perintah shell |
|
|  | [BASHRC](#BASHRC) | File menentukan perilaku shell interaktif |
|
|  | [EBUILD](#EBUILD) | Skrip bash khusus yang mengotomatisasi prosedur kompilasi dan instalasi untuk paket perangkat lunak |
|
|  | [SQL](#SQL) | Format Structured Query Language |
|
|  | [DSQL](#DSQL) | Format Dynamic Structured Query Language |
|
|  | [VIM](#VIM) | Format file kode sumber Vim |
|
|  | [YAML](#YAML) | Format bahasa serialisasi data yang dapat dibaca manusia |
|
|  | [YML](#YML) | Format bahasa serialisasi data yang dapat dibaca manusia |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromFileNameOrExtension(String value)](#fromFileNameOrExtension-java.lang.String-) | Kembalikan FileType berdasarkan nama file atau ekstensi |
|
|  | [getSupportedFileTypes()](#getSupportedFileTypes--) | Mendapatkan daftar tipe file yang didukung |
|
|  | [areEquals(FileType left, FileType right)](#areEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-) | Memeriksa kesetaraan tipe file yang diberikan |
|
|  | [areNotEquals(FileType left, FileType right)](#areNotEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-) | Memeriksa apakah tipe file yang diberikan tidak sama |
|
|  | [getFileFormat()](#getFileFormat--) | Mendapatkan deskripsi teks dari tipe file |
|
|  | [getExtension()](#getExtension--) | Mendapatkan ekstensi dari tipe file |
|
|  | [toString()](#toString--) | Mendapatkan representasi string dari [FileType](../../com.groupdocs.comparison.result/filetype), misalnya |
'Format Bahasa Pemrograman PHP (.php)'

|
### UNKNOWN {#UNKNOWN}
```
public static final FileType UNKNOWN
```


Tipe tidak diketahui


### AS {#AS}
```
public static final FileType AS
```


format Bahasa Pemrograman ActionScript


### AS3 {#AS3}
```
public static final FileType AS3
```


format Bahasa Pemrograman ActionScript


### ASM {#ASM}
```
public static final FileType ASM
```


format Bahasa Pemrograman Assembler


### BAT {#BAT}
```
public static final FileType BAT
```


File skrip di DOS, OS/2, dan Microsoft Windows


### CMD {#CMD}
```
public static final FileType CMD
```


File skrip di DOS, OS/2, dan Microsoft Windows


### C {#C}
```
public static final FileType C
```


format Bahasa Pemrograman Berbasis C


### H {#H}
```
public static final FileType H
```


File header berbasis C berisi definisi Fungsi dan Variabel


### PDF {#PDF}
```
public static final FileType PDF
```


format Adobe Portable Document


### DOC {#DOC}
```
public static final FileType DOC
```


Dokumen Microsoft Word 97-2003


### DOCM {#DOCM}
```
public static final FileType DOCM
```


Dokumen Microsoft Word yang Mendukung Makro


### DOCX {#DOCX}
```
public static final FileType DOCX
```


Dokumen Microsoft Word


### DOT {#DOT}
```
public static final FileType DOT
```


Templat Microsoft Word 97-2003


### DOTM {#DOTM}
```
public static final FileType DOTM
```


Templat Microsoft Word yang Mendukung Makro


### DOTX {#DOTX}
```
public static final FileType DOTX
```


Templat Microsoft Word


### XLS {#XLS}
```
public static final FileType XLS
```


Lembar Kerja Microsoft Excel 97-2003


### XLT {#XLT}
```
public static final FileType XLT
```


Templat Microsoft Excel


### XLSX {#XLSX}
```
public static final FileType XLSX
```


Lembar Kerja Microsoft Excel


### XLTM {#XLTM}
```
public static final FileType XLTM
```


Templat Microsoft Excel yang Mendukung Makro


### XLSB {#XLSB}
```
public static final FileType XLSB
```


Microsoft Excel Lembar Kerja Biner


### XLSM {#XLSM}
```
public static final FileType XLSM
```


Microsoft Excel Lembar Kerja Makro-Aktif


### POT {#POT}
```
public static final FileType POT
```


Microsoft PowerPoint templat


### POTX {#POTX}
```
public static final FileType POTX
```


Microsoft PowerPoint Templat


### POTM {#POTM}
```
public static final FileType POTM
```


Microsoft PowerPoint Templat dengan dukungan Makro


### PPS {#PPS}
```
public static final FileType PPS
```


Microsoft PowerPoint 97-2003 Tayangan Slide


### PPSX {#PPSX}
```
public static final FileType PPSX
```


Microsoft PowerPoint Tayangan Slide


### PPTX {#PPTX}
```
public static final FileType PPTX
```


Microsoft PowerPoint Presentasi


### PPT {#PPT}
```
public static final FileType PPT
```


Microsoft PowerPoint 97-2003 Presentasi


### PPTM {#PPTM}
```
public static final FileType PPTM
```


Microsoft PowerPoint Presentasi Makro-Aktif


### PPSM {#PPSM}
```
public static final FileType PPSM
```


Microsoft PowerPoint Presentasi Tayangan Slide Makro-Aktif


### VSDX {#VSDX}
```
public static final FileType VSDX
```


Microsoft Visio Gambar


### VSD {#VSD}
```
public static final FileType VSD
```


Microsoft Visio 2003-2010 Gambar


### VSS {#VSS}
```
public static final FileType VSS
```


Microsoft Visio 2003-2010 Stensil


### VST {#VST}
```
public static final FileType VST
```


Microsoft Visio 2003-2010 Templat


### VDX {#VDX}
```
public static final FileType VDX
```


Microsoft Visio 2003-2010 Gambar XML


### ONE {#ONE}
```
public static final FileType ONE
```


Microsoft OneNote Dokumen


### ODT {#ODT}
```
public static final FileType ODT
```


OpenDocument Teks


### ODP {#ODP}
```
public static final FileType ODP
```


OpenDocument Presentasi


### OTP {#OTP}
```
public static final FileType OTP
```


OpenDocument Templat Presentasi


### ODS {#ODS}
```
public static final FileType ODS
```


OpenDocument Lembar Hitung


### OTT {#OTT}
```
public static final FileType OTT
```


OpenDocument Templat Teks


### RTF {#RTF}
```
public static final FileType RTF
```


Dokumen Teks Kaya


### TXT {#TXT}
```
public static final FileType TXT
```


Dokumen Teks Biasa


### CSV {#CSV}
```
public static final FileType CSV
```


File Nilai Dipisahkan Koma


### HTML {#HTML}
```
public static final FileType HTML
```


Bahasa Markup Hiperteks


### MHTML {#MHTML}
```
public static final FileType MHTML
```


HTML MIME


### MOBI {#MOBI}
```
public static final FileType MOBI
```


format e-book Mobipocket


### DCM {#DCM}
```
public static final FileType DCM
```


Pencitraan Digital dan Komunikasi dalam Kedokteran


### DJVU {#DJVU}
```
public static final FileType DJVU
```


format Deja Vu


### DWG {#DWG}
```
public static final FileType DWG
```


Format Data Desain Autodesk


### DXF {#DXF}
```
public static final FileType DXF
```


Pertukaran Gambar AutoCAD


### BMP {#BMP}
```
public static final FileType BMP
```


Gambar Bitmap


### GIF {#GIF}
```
public static final FileType GIF
```


Format Pertukaran Grafik


### JPEG {#JPEG}
```
public static final FileType JPEG
```


Kelompok Ahli Fotografi Bersama


### JPG {#JPG}
```
public static final FileType JPG
```


Kelompok Ahli Fotografi Bersama


### PNG {#PNG}
```
public static final FileType PNG
```


Grafik Jaringan Portabel


### SVG {#SVG}
```
public static final FileType SVG
```


Grafik Vektor Skalar


### EML {#EML}
```
public static final FileType EML
```


Pesan Email


### EMLX {#EMLX}
```
public static final FileType EMLX
```


File Email Apple Mail


### MSG {#MSG}
```
public static final FileType MSG
```


Pesan Email Microsoft Outlook


### CAD {#CAD}
```
public static final FileType CAD
```


format file CAD


### CPP {#CPP}
```
public static final FileType CPP
```


format Bahasa Pemrograman Berbasis C


### CC {#CC}
```
public static final FileType CC
```


format Bahasa Pemrograman Berbasis C


### CXX {#CXX}
```
public static final FileType CXX
```


format Bahasa Pemrograman Berbasis C


### HXX {#HXX}
```
public static final FileType HXX
```


Berkas Header yang ditulis dalam bahasa pemrograman C++


### HH {#HH}
```
public static final FileType HH
```


Informasi header yang dirujuk oleh berkas kode sumber C++


### HPP {#HPP}
```
public static final FileType HPP
```


Berkas Header yang ditulis dalam bahasa pemrograman C++


### CMAKE {#CMAKE}
```
public static final FileType CMAKE
```


Alat untuk mengelola proses build perangkat lunak


### CS {#CS}
```
public static final FileType CS
```


format Bahasa Pemrograman CSharp


### CSX {#CSX}
```
public static final FileType CSX
```


format berkas skrip CSharp


### CAKE {#CAKE}
```
public static final FileType CAKE
```


format sistem otomasi build lintas platform CSharp


### DIFF {#DIFF}
```
public static final FileType DIFF
```


format alat perbandingan data


### PATCH {#PATCH}
```
public static final FileType PATCH
```


format daftar perbedaan


### REJ {#REJ}
```
public static final FileType REJ
```


format berkas yang ditolak


### GROOVY {#GROOVY}
```
public static final FileType GROOVY
```


File kode sumber yang ditulis dalam format Groovy


### GVY {#GVY}
```
public static final FileType GVY
```


File kode sumber yang ditulis dalam format Groovy


### GRADLE {#GRADLE}
```
public static final FileType GRADLE
```


Format sistem otomatisasi build


### HAML {#HAML}
```
public static final FileType HAML
```


Bahasa markup untuk pembuatan HTML yang disederhanakan


### JS {#JS}
```
public static final FileType JS
```


Format Bahasa Pemrograman JavaScript


### ES6 {#ES6}
```
public static final FileType ES6
```


Format bahasa skrip JavaScript yang distandarisasi


### MJS {#MJS}
```
public static final FileType MJS
```


Ekstensi untuk file modul EcmaScript (ES)


### PAC {#PAC}
```
public static final FileType PAC
```


File Proxy Auto-Configuration untuk format fungsi JavaScript


### JSON {#JSON}
```
public static final FileType JSON
```


Format ringan untuk menyimpan dan mentransfer data


### BOWERRC {#BOWERRC}
```
public static final FileType BOWERRC
```


File konfigurasi untuk kontrol paket di sisi server


### JSHINTRC {#JSHINTRC}
```
public static final FileType JSHINTRC
```


Alat kualitas kode JavaScript


### JSCSRC {#JSCSRC}
```
public static final FileType JSCSRC
```


Format file konfigurasi JavaScript


### WEBMANIFEST {#WEBMANIFEST}
```
public static final FileType WEBMANIFEST
```


File manifest berisi informasi tentang aplikasi


### JSMAP {#JSMAP}
```
public static final FileType JSMAP
```


File JSON yang berisi informasi tentang cara menerjemahkan kode kembali ke kode sumber


### HAR {#HAR}
```
public static final FileType HAR
```


Format HTTP Archive


### JAVA {#JAVA}
```
public static final FileType JAVA
```


Format Bahasa Pemrograman Java


### LESS {#LESS}
```
public static final FileType LESS
```


Format bahasa lembar gaya preprocessor dinamis


### LOG {#LOG}
```
public static final FileType LOG
```


Logging menyimpan registri peristiwa, proses, pesan, dan komunikasi


### MAKE {#MAKE}
```
public static final FileType MAKE
```


Makefile adalah file yang berisi sekumpulan arahan yang digunakan oleh alat otomatisasi build make untuk menghasilkan target/tujuan


### MK {#MK}
```
public static final FileType MK
```


Makefile adalah file yang berisi sekumpulan arahan yang digunakan oleh alat otomatisasi build make untuk menghasilkan target/tujuan


### MD {#MD}
```
public static final FileType MD
```


Format Bahasa Markdown


### MKD {#MKD}
```
public static final FileType MKD
```


Format Bahasa Markdown


### MDWN {#MDWN}
```
public static final FileType MDWN
```


Format Bahasa Markdown


### MDOWN {#MDOWN}
```
public static final FileType MDOWN
```


Format Bahasa Markdown


### MARKDOWN {#MARKDOWN}
```
public static final FileType MARKDOWN
```


Format Bahasa Markdown


### MARKDN {#MARKDN}
```
public static final FileType MARKDN
```


Format Bahasa Markdown


### MDTXT {#MDTXT}
```
public static final FileType MDTXT
```


Format Bahasa Markdown


### MDTEXT {#MDTEXT}
```
public static final FileType MDTEXT
```


Format Bahasa Markdown


### ML {#ML}
```
public static final FileType ML
```


Format Bahasa Pemrograman Caml


### MLI {#MLI}
```
public static final FileType MLI
```


Format Bahasa Pemrograman Caml


### OBJC {#OBJC}
```
public static final FileType OBJC
```


Format Bahasa Pemrograman Objective-C


### OBJCP {#OBJCP}
```
public static final FileType OBJCP
```


Format Bahasa Pemrograman Objective-C++


### PHP {#PHP}
```
public static final FileType PHP
```


Format Bahasa Pemrograman PHP


### PHP4 {#PHP4}
```
public static final FileType PHP4
```


Format Bahasa Pemrograman PHP


### PHP5 {#PHP5}
```
public static final FileType PHP5
```


Format Bahasa Pemrograman PHP


### PHTML {#PHTML}
```
public static final FileType PHTML
```


Ekstensi file standar untuk format program PHP 2


### CTP {#CTP}
```
public static final FileType CTP
```


Format Template CakePHP


### PL {#PL}
```
public static final FileType PL
```


Format Bahasa Pemrograman Perl


### PM {#PM}
```
public static final FileType PM
```


Format modul Perl


### POD {#POD}
```
public static final FileType POD
```


Format bahasa markup ringan Perl


### T {#T}
```
public static final FileType T
```


Format berkas uji Perl


### PSGI {#PSGI}
```
public static final FileType PSGI
```


Antarmuka antara server web dan aplikasi web serta kerangka kerja yang ditulis dalam pemrograman Perl


### P6 {#P6}
```
public static final FileType P6
```


Format Bahasa Pemrograman Perl


### PL6 {#PL6}
```
public static final FileType PL6
```


Format Bahasa Pemrograman Perl


### PM6 {#PM6}
```
public static final FileType PM6
```


Format modul Perl


### NQP {#NQP}
```
public static final FileType NQP
```


Bahasa menengah yang digunakan untuk membangun kompiler Rakudo Perl 6


### PROP {#PROP}
```
public static final FileType PROP
```


Format berkas properti


### CFG {#CFG}
```
public static final FileType CFG
```


Berkas konfigurasi yang digunakan untuk menyimpan pengaturan


### CONF {#CONF}
```
public static final FileType CONF
```


Berkas konfigurasi yang digunakan pada sistem berbasis Unix dan Linux


### DIR {#DIR}
```
public static final FileType DIR
```


Direktori adalah lokasi untuk menyimpan berkas di komputer


### PY {#PY}
```
public static final FileType PY
```


Format Bahasa Pemrograman Python


### RPY {#RPY}
```
public static final FileType RPY
```


Mesin berkas berbasis Python untuk membuat dan menjalankan permainan


### PYW {#PYW}
```
public static final FileType PYW
```


Berkas yang digunakan di Windows untuk menunjukkan bahwa skrip perlu dijalankan


### CPY {#CPY}
```
public static final FileType CPY
```


Format Skrip Python Kontroler


### GYP {#GYP}
```
public static final FileType GYP
```


Format alat otomasi pembangunan


### GYPI {#GYPI}
```
public static final FileType GYPI
```


Format alat otomasi pembangunan


### PYI {#PYI}
```
public static final FileType PYI
```


Format berkas Antarmuka Python


### IPY {#IPY}
```
public static final FileType IPY
```


Format Skrip IPython


### RST {#RST}
```
public static final FileType RST
```


Bahasa markup ringan


### RB {#RB}
```
public static final FileType RB
```


Format Bahasa Pemrograman Ruby


### ERB {#ERB}
```
public static final FileType ERB
```


Format Bahasa Pemrograman Ruby


### RJS {#RJS}
```
public static final FileType RJS
```


Format Bahasa Pemrograman Ruby


### GEMSPEC {#GEMSPEC}
```
public static final FileType GEMSPEC
```


Berkas pengembang yang menentukan atribut RubyGems


### RAKE {#RAKE}
```
public static final FileType RAKE
```


Alat otomasi pembangunan Ruby


### RU {#RU}
```
public static final FileType RU
```


Format berkas konfigurasi Rack


### PODSPEC {#PODSPEC}
```
public static final FileType PODSPEC
```


Format pengaturan pembangunan Ruby


### RBI {#RBI}
```
public static final FileType RBI
```


Format berkas Antarmuka Ruby


### SASS {#SASS}
```
public static final FileType SASS
```


Format bahasa lembar gaya


### SCSS {#SCSS}
```
public static final FileType SCSS
```


Format bahasa lembar gaya


### SCALA {#SCALA}
```
public static final FileType SCALA
```


Format Bahasa Pemrograman Scala


### SBT {#SBT}
```
public static final FileType SBT
```


Alat build SBT untuk format Scala


### SC {#SC}
```
public static final FileType SC
```


Format lembar kerja Scala


### SH {#SH}
```
public static final FileType SH
```


Format skrip yang diprogram untuk bash


### BASH {#BASH}
```
public static final FileType BASH
```


Jenis interpreter yang memproses perintah shell


### BASHRC {#BASHRC}
```
public static final FileType BASHRC
```


File menentukan perilaku shell interaktif


### EBUILD {#EBUILD}
```
public static final FileType EBUILD
```


Skrip bash khusus yang mengotomatisasi prosedur kompilasi dan instalasi untuk paket perangkat lunak


### SQL {#SQL}
```
public static final FileType SQL
```


Format Structured Query Language


### DSQL {#DSQL}
```
public static final FileType DSQL
```


Format Dynamic Structured Query Language


### VIM {#VIM}
```
public static final FileType VIM
```


Format file kode sumber Vim


### YAML {#YAML}
```
public static final FileType YAML
```


Format bahasa serialisasi data yang dapat dibaca manusia


### YML {#YML}
```
public static final FileType YML
```


Format bahasa serialisasi data yang dapat dibaca manusia


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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype)
### fromFileNameOrExtension(String value) {#fromFileNameOrExtension-java.lang.String-}
```
public static FileType fromFileNameOrExtension(String value)
```


Kembalikan FileType berdasarkan nama file atau ekstensi


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | java.lang.String | Nama file atau ekstensi, tidak null |
|

**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the file type

### getSupportedFileTypes() {#getSupportedFileTypes--}
```
public static List<FileType> getSupportedFileTypes()
```


Mendapatkan daftar tipe file yang didukung


**Returns:**
java.util.List<com.groupdocs.comparison.result.FileType> - daftar FileType

### areEquals(FileType left, FileType right) {#areEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-}
```
public static boolean areEquals(FileType left, FileType right)
```


Memeriksa kesetaraan tipe file yang diberikan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | left | [FileType](../../com.groupdocs.comparison.result/filetype) | Objek [FileType](../../com.groupdocs.comparison.result/filetype) kiri. |
|
|  | right | [FileType](../../com.groupdocs.comparison.result/filetype) | Objek [FileType](../../com.groupdocs.comparison.result/filetype) kanan. |
|

**Returns:**
boolean - true jika sama, false jika tidak

### areNotEquals(FileType left, FileType right) {#areNotEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-}
```
public static boolean areNotEquals(FileType left, FileType right)
```


Memeriksa apakah tipe file yang diberikan tidak sama


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | left | [FileType](../../com.groupdocs.comparison.result/filetype) | Objek [FileType](../../com.groupdocs.comparison.result/filetype) kiri. |
|
|  | right | [FileType](../../com.groupdocs.comparison.result/filetype) | Objek [FileType](../../com.groupdocs.comparison.result/filetype) kanan. |
|

**Returns:**
boolean - true jika tidak sama, sebaliknya false

### getFileFormat() {#getFileFormat--}
```
public String getFileFormat()
```


Mendapatkan deskripsi teks dari tipe file


**Returns:**
java.lang.String - deskripsi tipe file

### getExtension() {#getExtension--}
```
public String getExtension()
```


Mendapatkan ekstensi dari tipe file


**Returns:**
java.lang.String - ekstensi tipe file

### toString() {#toString--}
```
public String toString()
```


Mendapatkan representasi string dari [FileType](../../com.groupdocs.comparison.result/filetype), misalnya
'Format Bahasa Pemrograman PHP (.php)'



**Returns:**
java.lang.String - representasi string

