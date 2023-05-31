---
title: FileType
second_title: GroupDocs.Comparison for Java API Reference
description: The FileType enum represents the type of a file used in the document comparison process.
type: docs
weight: 16
url: /java/com.groupdocs.comparison.result/filetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public enum FileType extends Enum<FileType> implements System.IEquatable<FileType>
```

The FileType enum represents the type of a file used in the document comparison process.

It defines different file types such as Word documents, PDF files, and more. Provides methods to obtain list of all file types supported by GroupDocs.Comparison, detect file type by extension etc. Use this enum to specify the file type when working with the GroupDocs.Comparison library.

 *  Learn more about file formats supported by GroupDocs.Comparison: [Full list of supported document formats][]
 *  Learn more about getting supported file types in Java: [How to get supported file formats in Java][]

Example usage:

```

  // Set the file type to Word document
  final FileType fileType = FileType.DOCX;
  // Perform comparison using the specified file type
  final LoadOptions loadOptions = new LoadOptions(fileType);
  try (Comparer comparer = new Comparer(sourceFile, loadOptions)) {
      comparer.add(targetFile);

      comparer.compare(resultFile, compareOptions);
 }
 
```


[Full list of supported document formats]: https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats
[How to get supported file formats in Java]: https://docs.groupdocs.com/display/comparisonjava/Get+supported+file+formats
## Fields

| Field | Description |
| --- | --- |
| [UNKNOWN](#UNKNOWN) | Unknown type |
| [AS](#AS) | ActionScript Programming Language format |
| [AS3](#AS3) | ActionScript Programming Language format |
| [ASM](#ASM) | Assembler Programming Language format |
| [BAT](#BAT) | Script file in DOS, OS/2 and Microsoft Windows |
| [CMD](#CMD) | Script file in DOS, OS/2 and Microsoft Windows |
| [C](#C) | C-Based Programming Language format |
| [H](#H) | C-Based header files contain definitions of Functions and Variables |
| [PDF](#PDF) | Adobe Portable Document format |
| [DOC](#DOC) | Microsoft Word 97-2003 Document |
| [DOCM](#DOCM) | Microsoft Word Macro-Enabled Document |
| [DOCX](#DOCX) | Microsoft Word Document |
| [DOT](#DOT) | Microsoft Word 97-2003 Template |
| [DOTM](#DOTM) | Microsoft Word Macro-Enabled Template |
| [DOTX](#DOTX) | Microsoft Word Template |
| [XLS](#XLS) | Microsoft Excel 97-2003 Worksheet |
| [XLT](#XLT) | Microsoft Excel template |
| [XLSX](#XLSX) | Microsoft Excel Worksheet |
| [XLTM](#XLTM) | Microsoft Excel macro-enabled template |
| [XLSB](#XLSB) | Microsoft Excel Binary Worksheet |
| [XLSM](#XLSM) | Microsoft Excel Macro-Enabled Worksheet |
| [POT](#POT) | Microsoft PowerPoint template |
| [POTX](#POTX) | Microsoft PowerPoint Template |
| [POTM](#POTM) | Microsoft PowerPoint Template with support for Macros |
| [PPS](#PPS) | Microsoft PowerPoint 97-2003 Slide Show |
| [PPSX](#PPSX) | Microsoft PowerPoint Slide Show |
| [PPTX](#PPTX) | Microsoft PowerPoint Presentation |
| [PPT](#PPT) | Microsoft PowerPoint 97-2003 Presentation |
| [PPTM](#PPTM) | Microsoft PowerPoint Macro-Enabled Presentation |
| [PPSM](#PPSM) | Microsoft PowerPoint Macro-Enabled Slide Show Presentation |
| [VSDX](#VSDX) | Microsoft Visio Drawing |
| [VSD](#VSD) | Microsoft Visio 2003-2010 Drawing |
| [VSS](#VSS) | Microsoft Visio 2003-2010 Stencil |
| [VST](#VST) | Microsoft Visio 2003-2010 Template |
| [VDX](#VDX) | Microsoft Visio 2003-2010 XML Drawing |
| [ONE](#ONE) | Microsoft OneNote Document |
| [ODT](#ODT) | OpenDocument Text |
| [ODP](#ODP) | OpenDocument Presentation |
| [OTP](#OTP) | OpenDocument Presentation Template |
| [ODS](#ODS) | OpenDocument Spreadsheet |
| [OTT](#OTT) | OpenDocument Text Template |
| [RTF](#RTF) | Rich Text Document |
| [TXT](#TXT) | Plain Text Document |
| [CSV](#CSV) | Comma Separated Values File |
| [HTML](#HTML) | HyperText Markup Language |
| [MHTML](#MHTML) | Mime HTML |
| [MOBI](#MOBI) | Mobipocket e-book format |
| [DCM](#DCM) | Digital Imaging and Communications in Medicine |
| [DJVU](#DJVU) | Deja Vu format |
| [DWG](#DWG) | Autodesk Design Data Formats |
| [DXF](#DXF) | AutoCAD Drawing Interchange |
| [BMP](#BMP) | Bitmap Picture |
| [GIF](#GIF) | Graphics Interchange Format |
| [JPEG](#JPEG) | Joint Photographic Experts Group |
| [JPG](#JPG) | Joint Photographic Experts Group |
| [PNG](#PNG) | Portable Network Graphics |
| [SVG](#SVG) | Scalar Vector Graphics |
| [EML](#EML) | E-mail Message |
| [EMLX](#EMLX) | Apple Mail E-mail File |
| [MSG](#MSG) | Microsoft Outlook E-mail Message |
| [CAD](#CAD) | CAD file format |
| [CPP](#CPP) | C-Based Programming Language format |
| [CC](#CC) | C-Based Programming Language format |
| [CXX](#CXX) | C-Based Programming Language format |
| [HXX](#HXX) | Header Files that are written in the C++ programming language |
| [HH](#HH) | Header information referenced by a C++ source code file |
| [HPP](#HPP) | Header Files that are written in the C++ programming language |
| [CMAKE](#CMAKE) | Tool for managing the build process of software |
| [CS](#CS) | CSharp Programming Language format |
| [CSX](#CSX) | CSharp script file format |
| [CAKE](#CAKE) | CSharp cross-platform build automation system format |
| [DIFF](#DIFF) | Data comparison tool format |
| [PATCH](#PATCH) | List of differences format |
| [REJ](#REJ) | Rejected files format |
| [GROOVY](#GROOVY) | Source code file written in Groovy format |
| [GVY](#GVY) | Source code file written in Groovy format |
| [GRADLE](#GRADLE) | Build-automation system format |
| [HAML](#HAML) | Markup language for simplified HTML generation |
| [JS](#JS) | JavaScript Programming Language format |
| [ES6](#ES6) | JavaScript standardised scripting language format |
| [MJS](#MJS) | Extension for EcmaScript (ES) module files |
| [PAC](#PAC) | Proxy Auto-Configuration file for JavaScript function format |
| [JSON](#JSON) | Lightweight format for storing and transporting data |
| [BOWERRC](#BOWERRC) | Configuration file for package control on the server-side |
| [JSHINTRC](#JSHINTRC) | JavaScript code quality tool |
| [JSCSRC](#JSCSRC) | JavaScript configuration file format |
| [WEBMANIFEST](#WEBMANIFEST) | Manifest file includes information about the app |
| [JSMAP](#JSMAP) | JSON file that contains information on how to translate code back to source code |
| [HAR](#HAR) | The HTTP Archive format |
| [JAVA](#JAVA) | Java Programming Language format |
| [LESS](#LESS) | Dynamic preprocessor style sheet language format |
| [LOG](#LOG) | Logging keeps a registry of events, processes, messages and communication |
| [MAKE](#MAKE) | Makefile is a file containing a set of directives used by a make build automation tool to generate a target/goal |
| [MK](#MK) | Makefile is a file containing a set of directives used by a make build automation tool to generate a target/goal |
| [MD](#MD) | Markdown Language format |
| [MKD](#MKD) | Markdown Language format |
| [MDWN](#MDWN) | Markdown Language format |
| [MDOWN](#MDOWN) | Markdown Language format |
| [MARKDOWN](#MARKDOWN) | Markdown Language format |
| [MARKDN](#MARKDN) | Markdown Language format |
| [MDTXT](#MDTXT) | Markdown Language format |
| [MDTEXT](#MDTEXT) | Markdown Language format |
| [ML](#ML) | Caml Programming Language format |
| [MLI](#MLI) | Caml Programming Language format |
| [OBJC](#OBJC) | Objective-C Programming Language format |
| [OBJCP](#OBJCP) | Objective-C++ Programming Language format |
| [PHP](#PHP) | PHP Programming Language format |
| [PHP4](#PHP4) | PHP Programming Language format |
| [PHP5](#PHP5) | PHP Programming Language format |
| [PHTML](#PHTML) | Standard file extension for PHP 2 programs format |
| [CTP](#CTP) | CakePHP Template format |
| [PL](#PL) | Perl Programming Language format |
| [PM](#PM) | Perl module format |
| [POD](#POD) | Perl lightweight markup language format |
| [T](#T) | Perl test file format |
| [PSGI](#PSGI) | Interface between web servers and web applications and frameworks written in the Perl programming |
| [P6](#P6) | Perl Programming Language format |
| [PL6](#PL6) | Perl Programming Language format |
| [PM6](#PM6) | Perl module format |
| [NQP](#NQP) | Intermediate language used to build the Rakudo Perl 6 compiler |
| [PROP](#PROP) | Properties file format |
| [CFG](#CFG) | Configuration file used for storing settings |
| [CONF](#CONF) | Configuration file used on Unix and Linux based systems |
| [DIR](#DIR) | Directory is a location for storing files on computer |
| [PY](#PY) | Python Programming Language format |
| [RPY](#RPY) | Python-based file engine to create and run games |
| [PYW](#PYW) | Files used in Windows to indicate a script needs to be run |
| [CPY](#CPY) | Controller Python Script format |
| [GYP](#GYP) | Build automation tool format |
| [GYPI](#GYPI) | Build automation tool format |
| [PYI](#PYI) | Python Interface file format |
| [IPY](#IPY) | IPython Script format |
| [RST](#RST) | Lightweight markup language |
| [RB](#RB) | Ruby Programming Language format |
| [ERB](#ERB) | Ruby Programming Language format |
| [RJS](#RJS) | Ruby Programming Language format |
| [GEMSPEC](#GEMSPEC) | Developer file that specifies the attributes of a RubyGems |
| [RAKE](#RAKE) | Ruby build automation tool |
| [RU](#RU) | Rack configuration file format |
| [PODSPEC](#PODSPEC) | Ruby build settings format |
| [RBI](#RBI) | Ruby Interface file format |
| [SASS](#SASS) | Style sheet language format |
| [SCSS](#SCSS) | Style sheet language format |
| [SCALA](#SCALA) | Scala Programming Language format |
| [SBT](#SBT) | SBT build tool for Scala format |
| [SC](#SC) | Scala worksheet format |
| [SH](#SH) | Script programmed for bash format |
| [BASH](#BASH) | Type of interpreter that processes shell commands |
| [BASHRC](#BASHRC) | File determines the behavior of interactive shells |
| [EBUILD](#EBUILD) | Specialized bash script which automates compilation and installation procedures for software packages |
| [SQL](#SQL) | Structured Query Language format |
| [DSQL](#DSQL) | Dynamic Structured Query Language format |
| [VIM](#VIM) | Vim source code file format |
| [YAML](#YAML) | Human-readable data-serialization language format |
| [YML](#YML) | Human-readable data-serialization language format |
## Methods

| Method | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [fromFileNameOrExtension(String value)](#fromFileNameOrExtension-java.lang.String-) | Return FileType based on file name or extension |
| [getSupportedFileTypes()](#getSupportedFileTypes--) | Gets list of supported file types |
| [areEquals(FileType left, FileType right)](#areEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-) | Checks the equality of provided file types |
| [areNotEquals(FileType left, FileType right)](#areNotEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-) | Checks are provided file types not equals |
| [getFileFormat()](#getFileFormat--) | Gets text description of the file type |
| [getExtension()](#getExtension--) | Gets the extension of the file type |
| [toString()](#toString--) | Gets string representation of [FileType](../../com.groupdocs.comparison.result/filetype), for example  'PHP Programming Language format (.php)'  |
### UNKNOWN {#UNKNOWN}
```
public static final FileType UNKNOWN
```


Unknown type

### AS {#AS}
```
public static final FileType AS
```


ActionScript Programming Language format

### AS3 {#AS3}
```
public static final FileType AS3
```


ActionScript Programming Language format

### ASM {#ASM}
```
public static final FileType ASM
```


Assembler Programming Language format

### BAT {#BAT}
```
public static final FileType BAT
```


Script file in DOS, OS/2 and Microsoft Windows

### CMD {#CMD}
```
public static final FileType CMD
```


Script file in DOS, OS/2 and Microsoft Windows

### C {#C}
```
public static final FileType C
```


C-Based Programming Language format

### H {#H}
```
public static final FileType H
```


C-Based header files contain definitions of Functions and Variables

### PDF {#PDF}
```
public static final FileType PDF
```


Adobe Portable Document format

### DOC {#DOC}
```
public static final FileType DOC
```


Microsoft Word 97-2003 Document

### DOCM {#DOCM}
```
public static final FileType DOCM
```


Microsoft Word Macro-Enabled Document

### DOCX {#DOCX}
```
public static final FileType DOCX
```


Microsoft Word Document

### DOT {#DOT}
```
public static final FileType DOT
```


Microsoft Word 97-2003 Template

### DOTM {#DOTM}
```
public static final FileType DOTM
```


Microsoft Word Macro-Enabled Template

### DOTX {#DOTX}
```
public static final FileType DOTX
```


Microsoft Word Template

### XLS {#XLS}
```
public static final FileType XLS
```


Microsoft Excel 97-2003 Worksheet

### XLT {#XLT}
```
public static final FileType XLT
```


Microsoft Excel template

### XLSX {#XLSX}
```
public static final FileType XLSX
```


Microsoft Excel Worksheet

### XLTM {#XLTM}
```
public static final FileType XLTM
```


Microsoft Excel macro-enabled template

### XLSB {#XLSB}
```
public static final FileType XLSB
```


Microsoft Excel Binary Worksheet

### XLSM {#XLSM}
```
public static final FileType XLSM
```


Microsoft Excel Macro-Enabled Worksheet

### POT {#POT}
```
public static final FileType POT
```


Microsoft PowerPoint template

### POTX {#POTX}
```
public static final FileType POTX
```


Microsoft PowerPoint Template

### POTM {#POTM}
```
public static final FileType POTM
```


Microsoft PowerPoint Template with support for Macros

### PPS {#PPS}
```
public static final FileType PPS
```


Microsoft PowerPoint 97-2003 Slide Show

### PPSX {#PPSX}
```
public static final FileType PPSX
```


Microsoft PowerPoint Slide Show

### PPTX {#PPTX}
```
public static final FileType PPTX
```


Microsoft PowerPoint Presentation

### PPT {#PPT}
```
public static final FileType PPT
```


Microsoft PowerPoint 97-2003 Presentation

### PPTM {#PPTM}
```
public static final FileType PPTM
```


Microsoft PowerPoint Macro-Enabled Presentation

### PPSM {#PPSM}
```
public static final FileType PPSM
```


Microsoft PowerPoint Macro-Enabled Slide Show Presentation

### VSDX {#VSDX}
```
public static final FileType VSDX
```


Microsoft Visio Drawing

### VSD {#VSD}
```
public static final FileType VSD
```


Microsoft Visio 2003-2010 Drawing

### VSS {#VSS}
```
public static final FileType VSS
```


Microsoft Visio 2003-2010 Stencil

### VST {#VST}
```
public static final FileType VST
```


Microsoft Visio 2003-2010 Template

### VDX {#VDX}
```
public static final FileType VDX
```


Microsoft Visio 2003-2010 XML Drawing

### ONE {#ONE}
```
public static final FileType ONE
```


Microsoft OneNote Document

### ODT {#ODT}
```
public static final FileType ODT
```


OpenDocument Text

### ODP {#ODP}
```
public static final FileType ODP
```


OpenDocument Presentation

### OTP {#OTP}
```
public static final FileType OTP
```


OpenDocument Presentation Template

### ODS {#ODS}
```
public static final FileType ODS
```


OpenDocument Spreadsheet

### OTT {#OTT}
```
public static final FileType OTT
```


OpenDocument Text Template

### RTF {#RTF}
```
public static final FileType RTF
```


Rich Text Document

### TXT {#TXT}
```
public static final FileType TXT
```


Plain Text Document

### CSV {#CSV}
```
public static final FileType CSV
```


Comma Separated Values File

### HTML {#HTML}
```
public static final FileType HTML
```


HyperText Markup Language

### MHTML {#MHTML}
```
public static final FileType MHTML
```


Mime HTML

### MOBI {#MOBI}
```
public static final FileType MOBI
```


Mobipocket e-book format

### DCM {#DCM}
```
public static final FileType DCM
```


Digital Imaging and Communications in Medicine

### DJVU {#DJVU}
```
public static final FileType DJVU
```


Deja Vu format

### DWG {#DWG}
```
public static final FileType DWG
```


Autodesk Design Data Formats

### DXF {#DXF}
```
public static final FileType DXF
```


AutoCAD Drawing Interchange

### BMP {#BMP}
```
public static final FileType BMP
```


Bitmap Picture

### GIF {#GIF}
```
public static final FileType GIF
```


Graphics Interchange Format

### JPEG {#JPEG}
```
public static final FileType JPEG
```


Joint Photographic Experts Group

### JPG {#JPG}
```
public static final FileType JPG
```


Joint Photographic Experts Group

### PNG {#PNG}
```
public static final FileType PNG
```


Portable Network Graphics

### SVG {#SVG}
```
public static final FileType SVG
```


Scalar Vector Graphics

### EML {#EML}
```
public static final FileType EML
```


E-mail Message

### EMLX {#EMLX}
```
public static final FileType EMLX
```


Apple Mail E-mail File

### MSG {#MSG}
```
public static final FileType MSG
```


Microsoft Outlook E-mail Message

### CAD {#CAD}
```
public static final FileType CAD
```


CAD file format

### CPP {#CPP}
```
public static final FileType CPP
```


C-Based Programming Language format

### CC {#CC}
```
public static final FileType CC
```


C-Based Programming Language format

### CXX {#CXX}
```
public static final FileType CXX
```


C-Based Programming Language format

### HXX {#HXX}
```
public static final FileType HXX
```


Header Files that are written in the C++ programming language

### HH {#HH}
```
public static final FileType HH
```


Header information referenced by a C++ source code file

### HPP {#HPP}
```
public static final FileType HPP
```


Header Files that are written in the C++ programming language

### CMAKE {#CMAKE}
```
public static final FileType CMAKE
```


Tool for managing the build process of software

### CS {#CS}
```
public static final FileType CS
```


CSharp Programming Language format

### CSX {#CSX}
```
public static final FileType CSX
```


CSharp script file format

### CAKE {#CAKE}
```
public static final FileType CAKE
```


CSharp cross-platform build automation system format

### DIFF {#DIFF}
```
public static final FileType DIFF
```


Data comparison tool format

### PATCH {#PATCH}
```
public static final FileType PATCH
```


List of differences format

### REJ {#REJ}
```
public static final FileType REJ
```


Rejected files format

### GROOVY {#GROOVY}
```
public static final FileType GROOVY
```


Source code file written in Groovy format

### GVY {#GVY}
```
public static final FileType GVY
```


Source code file written in Groovy format

### GRADLE {#GRADLE}
```
public static final FileType GRADLE
```


Build-automation system format

### HAML {#HAML}
```
public static final FileType HAML
```


Markup language for simplified HTML generation

### JS {#JS}
```
public static final FileType JS
```


JavaScript Programming Language format

### ES6 {#ES6}
```
public static final FileType ES6
```


JavaScript standardised scripting language format

### MJS {#MJS}
```
public static final FileType MJS
```


Extension for EcmaScript (ES) module files

### PAC {#PAC}
```
public static final FileType PAC
```


Proxy Auto-Configuration file for JavaScript function format

### JSON {#JSON}
```
public static final FileType JSON
```


Lightweight format for storing and transporting data

### BOWERRC {#BOWERRC}
```
public static final FileType BOWERRC
```


Configuration file for package control on the server-side

### JSHINTRC {#JSHINTRC}
```
public static final FileType JSHINTRC
```


JavaScript code quality tool

### JSCSRC {#JSCSRC}
```
public static final FileType JSCSRC
```


JavaScript configuration file format

### WEBMANIFEST {#WEBMANIFEST}
```
public static final FileType WEBMANIFEST
```


Manifest file includes information about the app

### JSMAP {#JSMAP}
```
public static final FileType JSMAP
```


JSON file that contains information on how to translate code back to source code

### HAR {#HAR}
```
public static final FileType HAR
```


The HTTP Archive format

### JAVA {#JAVA}
```
public static final FileType JAVA
```


Java Programming Language format

### LESS {#LESS}
```
public static final FileType LESS
```


Dynamic preprocessor style sheet language format

### LOG {#LOG}
```
public static final FileType LOG
```


Logging keeps a registry of events, processes, messages and communication

### MAKE {#MAKE}
```
public static final FileType MAKE
```


Makefile is a file containing a set of directives used by a make build automation tool to generate a target/goal

### MK {#MK}
```
public static final FileType MK
```


Makefile is a file containing a set of directives used by a make build automation tool to generate a target/goal

### MD {#MD}
```
public static final FileType MD
```


Markdown Language format

### MKD {#MKD}
```
public static final FileType MKD
```


Markdown Language format

### MDWN {#MDWN}
```
public static final FileType MDWN
```


Markdown Language format

### MDOWN {#MDOWN}
```
public static final FileType MDOWN
```


Markdown Language format

### MARKDOWN {#MARKDOWN}
```
public static final FileType MARKDOWN
```


Markdown Language format

### MARKDN {#MARKDN}
```
public static final FileType MARKDN
```


Markdown Language format

### MDTXT {#MDTXT}
```
public static final FileType MDTXT
```


Markdown Language format

### MDTEXT {#MDTEXT}
```
public static final FileType MDTEXT
```


Markdown Language format

### ML {#ML}
```
public static final FileType ML
```


Caml Programming Language format

### MLI {#MLI}
```
public static final FileType MLI
```


Caml Programming Language format

### OBJC {#OBJC}
```
public static final FileType OBJC
```


Objective-C Programming Language format

### OBJCP {#OBJCP}
```
public static final FileType OBJCP
```


Objective-C++ Programming Language format

### PHP {#PHP}
```
public static final FileType PHP
```


PHP Programming Language format

### PHP4 {#PHP4}
```
public static final FileType PHP4
```


PHP Programming Language format

### PHP5 {#PHP5}
```
public static final FileType PHP5
```


PHP Programming Language format

### PHTML {#PHTML}
```
public static final FileType PHTML
```


Standard file extension for PHP 2 programs format

### CTP {#CTP}
```
public static final FileType CTP
```


CakePHP Template format

### PL {#PL}
```
public static final FileType PL
```


Perl Programming Language format

### PM {#PM}
```
public static final FileType PM
```


Perl module format

### POD {#POD}
```
public static final FileType POD
```


Perl lightweight markup language format

### T {#T}
```
public static final FileType T
```


Perl test file format

### PSGI {#PSGI}
```
public static final FileType PSGI
```


Interface between web servers and web applications and frameworks written in the Perl programming

### P6 {#P6}
```
public static final FileType P6
```


Perl Programming Language format

### PL6 {#PL6}
```
public static final FileType PL6
```


Perl Programming Language format

### PM6 {#PM6}
```
public static final FileType PM6
```


Perl module format

### NQP {#NQP}
```
public static final FileType NQP
```


Intermediate language used to build the Rakudo Perl 6 compiler

### PROP {#PROP}
```
public static final FileType PROP
```


Properties file format

### CFG {#CFG}
```
public static final FileType CFG
```


Configuration file used for storing settings

### CONF {#CONF}
```
public static final FileType CONF
```


Configuration file used on Unix and Linux based systems

### DIR {#DIR}
```
public static final FileType DIR
```


Directory is a location for storing files on computer

### PY {#PY}
```
public static final FileType PY
```


Python Programming Language format

### RPY {#RPY}
```
public static final FileType RPY
```


Python-based file engine to create and run games

### PYW {#PYW}
```
public static final FileType PYW
```


Files used in Windows to indicate a script needs to be run

### CPY {#CPY}
```
public static final FileType CPY
```


Controller Python Script format

### GYP {#GYP}
```
public static final FileType GYP
```


Build automation tool format

### GYPI {#GYPI}
```
public static final FileType GYPI
```


Build automation tool format

### PYI {#PYI}
```
public static final FileType PYI
```


Python Interface file format

### IPY {#IPY}
```
public static final FileType IPY
```


IPython Script format

### RST {#RST}
```
public static final FileType RST
```


Lightweight markup language

### RB {#RB}
```
public static final FileType RB
```


Ruby Programming Language format

### ERB {#ERB}
```
public static final FileType ERB
```


Ruby Programming Language format

### RJS {#RJS}
```
public static final FileType RJS
```


Ruby Programming Language format

### GEMSPEC {#GEMSPEC}
```
public static final FileType GEMSPEC
```


Developer file that specifies the attributes of a RubyGems

### RAKE {#RAKE}
```
public static final FileType RAKE
```


Ruby build automation tool

### RU {#RU}
```
public static final FileType RU
```


Rack configuration file format

### PODSPEC {#PODSPEC}
```
public static final FileType PODSPEC
```


Ruby build settings format

### RBI {#RBI}
```
public static final FileType RBI
```


Ruby Interface file format

### SASS {#SASS}
```
public static final FileType SASS
```


Style sheet language format

### SCSS {#SCSS}
```
public static final FileType SCSS
```


Style sheet language format

### SCALA {#SCALA}
```
public static final FileType SCALA
```


Scala Programming Language format

### SBT {#SBT}
```
public static final FileType SBT
```


SBT build tool for Scala format

### SC {#SC}
```
public static final FileType SC
```


Scala worksheet format

### SH {#SH}
```
public static final FileType SH
```


Script programmed for bash format

### BASH {#BASH}
```
public static final FileType BASH
```


Type of interpreter that processes shell commands

### BASHRC {#BASHRC}
```
public static final FileType BASHRC
```


File determines the behavior of interactive shells

### EBUILD {#EBUILD}
```
public static final FileType EBUILD
```


Specialized bash script which automates compilation and installation procedures for software packages

### SQL {#SQL}
```
public static final FileType SQL
```


Structured Query Language format

### DSQL {#DSQL}
```
public static final FileType DSQL
```


Dynamic Structured Query Language format

### VIM {#VIM}
```
public static final FileType VIM
```


Vim source code file format

### YAML {#YAML}
```
public static final FileType YAML
```


Human-readable data-serialization language format

### YML {#YML}
```
public static final FileType YML
```


Human-readable data-serialization language format

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
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype)
### fromFileNameOrExtension(String value) {#fromFileNameOrExtension-java.lang.String-}
```
public static FileType fromFileNameOrExtension(String value)
```


Return FileType based on file name or extension

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | File name or extension, not null |

**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the file type
### getSupportedFileTypes() {#getSupportedFileTypes--}
```
public static List<FileType> getSupportedFileTypes()
```


Gets list of supported file types

**Returns:**
java.util.List<com.groupdocs.comparison.result.FileType> - list of FileType
### areEquals(FileType left, FileType right) {#areEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-}
```
public static boolean areEquals(FileType left, FileType right)
```


Checks the equality of provided file types

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left | [FileType](../../com.groupdocs.comparison.result/filetype) | Left [FileType](../../com.groupdocs.comparison.result/filetype) object. |
| right | [FileType](../../com.groupdocs.comparison.result/filetype) | Right [FileType](../../com.groupdocs.comparison.result/filetype) object. |

**Returns:**
boolean - true if equal, otherwise false
### areNotEquals(FileType left, FileType right) {#areNotEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-}
```
public static boolean areNotEquals(FileType left, FileType right)
```


Checks are provided file types not equals

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left | [FileType](../../com.groupdocs.comparison.result/filetype) | Left [FileType](../../com.groupdocs.comparison.result/filetype) object. |
| right | [FileType](../../com.groupdocs.comparison.result/filetype) | Right [FileType](../../com.groupdocs.comparison.result/filetype) object. |

**Returns:**
boolean - true if not equal, otherwise false
### getFileFormat() {#getFileFormat--}
```
public String getFileFormat()
```


Gets text description of the file type

**Returns:**
java.lang.String - file type descriptiuon
### getExtension() {#getExtension--}
```
public String getExtension()
```


Gets the extension of the file type

**Returns:**
java.lang.String - extension of the file type
### toString() {#toString--}
```
public String toString()
```


Gets string representation of [FileType](../../com.groupdocs.comparison.result/filetype), for example  'PHP Programming Language format (.php)' 

**Returns:**
java.lang.String - string representation
