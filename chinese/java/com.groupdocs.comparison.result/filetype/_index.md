---
title: "FileType"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "FileType 枚举表示文档比较过程中使用的文件类型。"
type: docs
weight: 16
url: /zh/java/com.groupdocs.comparison.result/filetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public enum FileType extends Enum<FileType> implements System.IEquatable<FileType>
```

FileType 枚举表示文档比较过程中使用的文件类型。


它定义了不同的文件类型，例如 Word 文档、PDF 文件等。
提供方法以获取 GroupDocs.Comparison 支持的所有文件类型列表、通过扩展名检测文件类型等。
在使用 GroupDocs.Comparison 库时，使用此枚举来指定文件类型。

* Learn more about file formats supported by GroupDocs.Comparison: [Full list of supported document formats](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* Learn more about getting supported file types in Java: [How to get supported file formats in Java](../https://docs.groupdocs.com/display/comparisonjava/Get+supported+file+formats)


示例用法：

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


## 字段

| 字段 | 描述 |
| --- | --- |
|  | [UNKNOWN](#UNKNOWN) | 未知类型 |
|
|  | [AS](#AS) | ActionScript 编程语言格式 |
|
|  | [AS3](#AS3) | ActionScript 编程语言格式 |
|
|  | [ASM](#ASM) | 汇编编程语言格式 |
|
|  | [BAT](#BAT) | DOS、OS/2 和 Microsoft Windows 下的脚本文件 |
|
|  | [CMD](#CMD) | DOS、OS/2 和 Microsoft Windows 下的脚本文件 |
|
|  | [C](#C) | 基于 C 的编程语言格式 |
|
|  | [H](#H) | 基于 C 的头文件包含函数和变量的定义 |
|
|  | [PDF](#PDF) | Adobe 可移植文档格式 |
|
|  | [DOC](#DOC) | Microsoft Word 97-2003 文档 |
|
|  | [DOCM](#DOCM) | Microsoft Word 启用宏的文档 |
|
|  | [DOCX](#DOCX) | Microsoft Word 文档 |
|
|  | [DOT](#DOT) | Microsoft Word 97-2003 模板 |
|
|  | [DOTM](#DOTM) | Microsoft Word 启用宏的模板 |
|
|  | [DOTX](#DOTX) | Microsoft Word 模板 |
|
|  | [XLS](#XLS) | Microsoft Excel 97-2003 工作表 |
|
|  | [XLT](#XLT) | Microsoft Excel 模板 |
|
|  | [XLSX](#XLSX) | Microsoft Excel 工作表 |
|
|  | [XLTM](#XLTM) | Microsoft Excel 启用宏的模板 |
|
|  | [XLSB](#XLSB) | Microsoft Excel 二进制工作表 |
|
|  | [XLSM](#XLSM) | Microsoft Excel 启用宏的工作表 |
|
|  | [POT](#POT) | Microsoft PowerPoint 模板 |
|
|  | [POTX](#POTX) | Microsoft PowerPoint 模板 |
|
|  | [POTM](#POTM) | Microsoft PowerPoint 支持宏的模板 |
|
|  | [PPS](#PPS) | Microsoft PowerPoint 97-2003 幻灯片放映 |
|
|  | [PPSX](#PPSX) | Microsoft PowerPoint 幻灯片放映 |
|
|  | [PPTX](#PPTX) | Microsoft PowerPoint 演示文稿 |
|
|  | [PPT](#PPT) | Microsoft PowerPoint 97-2003 演示文稿 |
|
|  | [PPTM](#PPTM) | Microsoft PowerPoint 启用宏的演示文稿 |
|
|  | [PPSM](#PPSM) | Microsoft PowerPoint 启用宏的幻灯片放映演示文稿 |
|
|  | [VSDX](#VSDX) | Microsoft Visio 绘图 |
|
|  | [VSD](#VSD) | Microsoft Visio 2003-2010 绘图 |
|
|  | [VSS](#VSS) | Microsoft Visio 2003-2010 模板 |
|
|  | [VST](#VST) | Microsoft Visio 2003-2010 模板 |
|
|  | [VDX](#VDX) | Microsoft Visio 2003-2010 XML 绘图 |
|
|  | [ONE](#ONE) | Microsoft OneNote 文档 |
|
|  | [ODT](#ODT) | OpenDocument 文本 |
|
|  | [ODP](#ODP) | OpenDocument 演示文稿 |
|
|  | [OTP](#OTP) | OpenDocument 演示文稿模板 |
|
|  | [ODS](#ODS) | OpenDocument 电子表格 |
|
|  | [OTT](#OTT) | OpenDocument 文本模板 |
|
|  | [RTF](#RTF) | 富文本文档 |
|
|  | [TXT](#TXT) | 纯文本文档 |
|
|  | [CSV](#CSV) | 逗号分隔值文件 |
|
|  | [HTML](#HTML) | 超文本标记语言 |
|
|  | [MHTML](#MHTML) | MIME HTML |
|
|  | [MOBI](#MOBI) | Mobipocket 电子书格式 |
|
|  | [DCM](#DCM) | 医学数字成像与通信 |
|
|  | [DJVU](#DJVU) | Deja Vu 格式 |
|
|  | [DWG](#DWG) | Autodesk 设计数据格式 |
|
|  | [DXF](#DXF) | AutoCAD 绘图交换 |
|
|  | [BMP](#BMP) | 位图图片 |
|
|  | [GIF](#GIF) | 图形交换格式 |
|
|  | [JPEG](#JPEG) | 联合图像专家组 |
|
|  | [JPG](#JPG) | 联合图像专家组 |
|
|  | [PNG](#PNG) | 可移植网络图形 |
|
|  | [SVG](#SVG) | 标量矢量图形 |
|
|  | [EML](#EML) | 电子邮件消息 |
|
|  | [EMLX](#EMLX) | Apple Mail 电子邮件文件 |
|
|  | [MSG](#MSG) | Microsoft Outlook 电子邮件消息 |
|
|  | [CAD](#CAD) | CAD 文件格式 |
|
|  | [CPP](#CPP) | 基于 C 的编程语言格式 |
|
|  | [CC](#CC) | 基于 C 的编程语言格式 |
|
|  | [CXX](#CXX) | 基于 C 的编程语言格式 |
|
|  | [HXX](#HXX) | 用 C++ 编程语言编写的头文件 |
|
|  | [HH](#HH) | C++ 源代码文件引用的头信息 |
|
|  | [HPP](#HPP) | 用 C++ 编程语言编写的头文件 |
|
|  | [CMAKE](#CMAKE) | 用于管理软件构建过程的工具 |
|
|  | [CS](#CS) | CSharp 编程语言格式 |
|
|  | [CSX](#CSX) | CSharp 脚本文件格式 |
|
|  | [CAKE](#CAKE) | CSharp 跨平台构建自动化系统格式 |
|
|  | [DIFF](#DIFF) | 数据比较工具格式 |
|
|  | [PATCH](#PATCH) | 差异列表格式 |
|
|  | [REJ](#REJ) | 被拒绝文件格式 |
|
|  | [GROOVY](#GROOVY) | 以 Groovy 格式编写的源代码文件 |
|
|  | [GVY](#GVY) | 以 Groovy 格式编写的源代码文件 |
|
|  | [GRADLE](#GRADLE) | 构建自动化系统格式 |
|
|  | [HAML](#HAML) | 用于简化 HTML 生成的标记语言 |
|
|  | [JS](#JS) | JavaScript 编程语言格式 |
|
|  | [ES6](#ES6) | JavaScript 标准化脚本语言格式 |
|
|  | [MJS](#MJS) | EcmaScript（ES）模块文件的扩展名 |
|
|  | [PAC](#PAC) | 用于 JavaScript 函数的代理自动配置文件格式 |
|
|  | [JSON](#JSON) | 用于存储和传输数据的轻量级格式 |
|
|  | [BOWERRC](#BOWERRC) | 服务器端包管理的配置文件 |
|
|  | [JSHINTRC](#JSHINTRC) | JavaScript 代码质量工具 |
|
|  | [JSCSRC](#JSCSRC) | JavaScript 配置文件格式 |
|
|  | [WEBMANIFEST](#WEBMANIFEST) | 清单文件包含有关应用程序的信息 |
|
|  | [JSMAP](#JSMAP) | 包含将代码翻译回源代码方法信息的 JSON 文件 |
|
|  | [HAR](#HAR) | HTTP 存档格式 |
|
|  | [JAVA](#JAVA) | Java 编程语言格式 |
|
|  | [LESS](#LESS) | 动态预处理器样式表语言格式 |
|
|  | [LOG](#LOG) | 日志记录维护事件、进程、消息和通信的注册表 |
|
|  | [MAKE](#MAKE) | Makefile 是一个包含一组指令的文件，这些指令由 make 构建自动化工具用于生成目标/目标 |
|
|  | [MK](#MK) | Makefile 是一个包含一组指令的文件，这些指令由 make 构建自动化工具用于生成目标/目标 |
|
|  | [MD](#MD) | Markdown 语言格式 |
|
|  | [MKD](#MKD) | Markdown 语言格式 |
|
|  | [MDWN](#MDWN) | Markdown 语言格式 |
|
|  | [MDOWN](#MDOWN) | Markdown 语言格式 |
|
|  | [MARKDOWN](#MARKDOWN) | Markdown 语言格式 |
|
|  | [MARKDN](#MARKDN) | Markdown 语言格式 |
|
|  | [MDTXT](#MDTXT) | Markdown 语言格式 |
|
|  | [MDTEXT](#MDTEXT) | Markdown 语言格式 |
|
|  | [ML](#ML) | Caml 编程语言格式 |
|
|  | [MLI](#MLI) | Caml 编程语言格式 |
|
|  | [OBJC](#OBJC) | Objective-C 编程语言格式 |
|
|  | [OBJCP](#OBJCP) | Objective-C++ 编程语言格式 |
|
|  | [PHP](#PHP) | PHP 编程语言格式 |
|
|  | [PHP4](#PHP4) | PHP 编程语言格式 |
|
|  | [PHP5](#PHP5) | PHP 编程语言格式 |
|
|  | [PHTML](#PHTML) | PHP 2 程序的标准文件扩展名格式 |
|
|  | [CTP](#CTP) | CakePHP 模板格式 |
|
|  | [PL](#PL) | Perl 编程语言格式 |
|
|  | [PM](#PM) | Perl 模块格式 |
|
|  | [POD](#POD) | Perl 轻量级标记语言格式 |
|
|  | [T](#T) | Perl 测试文件格式 |
|
|  | [PSGI](#PSGI) | Perl 编程编写的 Web 服务器与 Web 应用程序和框架之间的接口 |
|
|  | [P6](#P6) | Perl 编程语言格式 |
|
|  | [PL6](#PL6) | Perl 编程语言格式 |
|
|  | [PM6](#PM6) | Perl 模块格式 |
|
|  | [NQP](#NQP) | 用于构建 Rakuto Perl 6 编译器的中间语言 |
|
|  | [PROP](#PROP) | 属性文件格式 |
|
|  | [CFG](#CFG) | 用于存储设置的配置文件 |
|
|  | [CONF](#CONF) | 在 Unix 和基于 Linux 的系统上使用的配置文件 |
|
|  | [DIR](#DIR) | 目录是计算机上用于存储文件的位置 |
|
|  | [PY](#PY) | Python 编程语言格式 |
|
|  | [RPY](#RPY) | 基于 Python 的文件引擎，用于创建和运行游戏 |
|
|  | [PYW](#PYW) | Windows 中用于指示脚本需要运行的文件 |
|
|  | [CPY](#CPY) | Controller Python 脚本格式 |
|
|  | [GYP](#GYP) | 构建自动化工具格式 |
|
|  | [GYPI](#GYPI) | 构建自动化工具格式 |
|
|  | [PYI](#PYI) | Python 接口文件格式 |
|
|  | [IPY](#IPY) | IPython 脚本格式 |
|
|  | [RST](#RST) | 轻量级标记语言 |
|
|  | [RB](#RB) | Ruby 编程语言格式 |
|
|  | [ERB](#ERB) | Ruby 编程语言格式 |
|
|  | [RJS](#RJS) | Ruby 编程语言格式 |
|
|  | [GEMSPEC](#GEMSPEC) | 指定 RubyGems 属性的开发者文件 |
|
|  | [RAKE](#RAKE) | Ruby 构建自动化工具 |
|
|  | [RU](#RU) | Rack 配置文件格式 |
|
|  | [PODSPEC](#PODSPEC) | Ruby 构建设置格式 |
|
|  | [RBI](#RBI) | Ruby 接口文件格式 |
|
|  | [SASS](#SASS) | 样式表语言格式 |
|
|  | [SCSS](#SCSS) | 样式表语言格式 |
|
|  | [SCALA](#SCALA) | Scala 编程语言格式 |
|
|  | [SBT](#SBT) | Scala 的 SBT 构建工具格式 |
|
|  | [SC](#SC) | Scala 工作表格式 |
|
|  | [SH](#SH) | 为 bash 编写的脚本格式 |
|
|  | [BASH](#BASH) | 处理 shell 命令的解释器类型 |
|
|  | [BASHRC](#BASHRC) | 决定交互式 shell 行为的文件 |
|
|  | [EBUILD](#EBUILD) | 用于自动化软件包编译和安装过程的专用 bash 脚本 |
|
|  | [SQL](#SQL) | 结构化查询语言格式 |
|
|  | [DSQL](#DSQL) | 动态结构化查询语言格式 |
|
|  | [VIM](#VIM) | Vim 源代码文件格式 |
|
|  | [YAML](#YAML) | 人类可读的数据序列化语言格式 |
|
|  | [YML](#YML) | 人类可读的数据序列化语言格式 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromFileNameOrExtension(String value)](#fromFileNameOrExtension-java.lang.String-) | 根据文件名或扩展名返回 FileType |
|
|  | [getSupportedFileTypes()](#getSupportedFileTypes--) | 获取支持的文件类型列表 |
|
|  | [areEquals(FileType left, FileType right)](#areEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-) | 检查提供的文件类型是否相等 |
|
|  | [areNotEquals(FileType left, FileType right)](#areNotEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-) | 检查提供的文件类型是否不相等 |
|
|  | [getFileFormat()](#getFileFormat--) | 获取文件类型的文本描述 |
|
|  | [getExtension()](#getExtension--) | 获取文件类型的扩展名 |
|
|  | [toString()](#toString--) | 获取 [FileType](../../com.groupdocs.comparison.result/filetype) 的字符串表示，例如 |
'PHP 编程语言格式 (.php)'

|
### UNKNOWN {#UNKNOWN}
```
public static final FileType UNKNOWN
```


未知类型


### AS {#AS}
```
public static final FileType AS
```


ActionScript 编程语言格式


### AS3 {#AS3}
```
public static final FileType AS3
```


ActionScript 编程语言格式


### ASM {#ASM}
```
public static final FileType ASM
```


汇编编程语言格式


### BAT {#BAT}
```
public static final FileType BAT
```


DOS、OS/2 和 Microsoft Windows 下的脚本文件


### CMD {#CMD}
```
public static final FileType CMD
```


DOS、OS/2 和 Microsoft Windows 下的脚本文件


### C {#C}
```
public static final FileType C
```


基于 C 的编程语言格式


### H {#H}
```
public static final FileType H
```


基于 C 的头文件包含函数和变量的定义


### PDF {#PDF}
```
public static final FileType PDF
```


Adobe 可移植文档格式


### DOC {#DOC}
```
public static final FileType DOC
```


Microsoft Word 97-2003 文档


### DOCM {#DOCM}
```
public static final FileType DOCM
```


Microsoft Word 启用宏的文档


### DOCX {#DOCX}
```
public static final FileType DOCX
```


Microsoft Word 文档


### DOT {#DOT}
```
public static final FileType DOT
```


Microsoft Word 97-2003 模板


### DOTM {#DOTM}
```
public static final FileType DOTM
```


Microsoft Word 启用宏的模板


### DOTX {#DOTX}
```
public static final FileType DOTX
```


Microsoft Word 模板


### XLS {#XLS}
```
public static final FileType XLS
```


Microsoft Excel 97-2003 工作表


### XLT {#XLT}
```
public static final FileType XLT
```


Microsoft Excel 模板


### XLSX {#XLSX}
```
public static final FileType XLSX
```


Microsoft Excel 工作表


### XLTM {#XLTM}
```
public static final FileType XLTM
```


Microsoft Excel 启用宏的模板


### XLSB {#XLSB}
```
public static final FileType XLSB
```


Microsoft Excel 二进制工作表


### XLSM {#XLSM}
```
public static final FileType XLSM
```


Microsoft Excel 启用宏的工作表


### POT {#POT}
```
public static final FileType POT
```


Microsoft PowerPoint 模板


### POTX {#POTX}
```
public static final FileType POTX
```


Microsoft PowerPoint 模板


### POTM {#POTM}
```
public static final FileType POTM
```


Microsoft PowerPoint 支持宏的模板


### PPS {#PPS}
```
public static final FileType PPS
```


Microsoft PowerPoint 97-2003 幻灯片放映


### PPSX {#PPSX}
```
public static final FileType PPSX
```


Microsoft PowerPoint 幻灯片放映


### PPTX {#PPTX}
```
public static final FileType PPTX
```


Microsoft PowerPoint 演示文稿


### PPT {#PPT}
```
public static final FileType PPT
```


Microsoft PowerPoint 97-2003 演示文稿


### PPTM {#PPTM}
```
public static final FileType PPTM
```


Microsoft PowerPoint 启用宏的演示文稿


### PPSM {#PPSM}
```
public static final FileType PPSM
```


Microsoft PowerPoint 启用宏的幻灯片放映演示文稿


### VSDX {#VSDX}
```
public static final FileType VSDX
```


Microsoft Visio 绘图


### VSD {#VSD}
```
public static final FileType VSD
```


Microsoft Visio 2003-2010 绘图


### VSS {#VSS}
```
public static final FileType VSS
```


Microsoft Visio 2003-2010 模板


### VST {#VST}
```
public static final FileType VST
```


Microsoft Visio 2003-2010 模板


### VDX {#VDX}
```
public static final FileType VDX
```


Microsoft Visio 2003-2010 XML 绘图


### ONE {#ONE}
```
public static final FileType ONE
```


Microsoft OneNote 文档


### ODT {#ODT}
```
public static final FileType ODT
```


OpenDocument 文本


### ODP {#ODP}
```
public static final FileType ODP
```


OpenDocument 演示文稿


### OTP {#OTP}
```
public static final FileType OTP
```


OpenDocument 演示文稿模板


### ODS {#ODS}
```
public static final FileType ODS
```


OpenDocument 电子表格


### OTT {#OTT}
```
public static final FileType OTT
```


OpenDocument 文本模板


### RTF {#RTF}
```
public static final FileType RTF
```


富文本文档


### TXT {#TXT}
```
public static final FileType TXT
```


纯文本文档


### CSV {#CSV}
```
public static final FileType CSV
```


逗号分隔值文件


### HTML {#HTML}
```
public static final FileType HTML
```


超文本标记语言


### MHTML {#MHTML}
```
public static final FileType MHTML
```


MIME HTML


### MOBI {#MOBI}
```
public static final FileType MOBI
```


Mobipocket 电子书格式


### DCM {#DCM}
```
public static final FileType DCM
```


医学数字成像与通信


### DJVU {#DJVU}
```
public static final FileType DJVU
```


Deja Vu 格式


### DWG {#DWG}
```
public static final FileType DWG
```


Autodesk 设计数据格式


### DXF {#DXF}
```
public static final FileType DXF
```


AutoCAD 绘图交换


### BMP {#BMP}
```
public static final FileType BMP
```


位图图片


### GIF {#GIF}
```
public static final FileType GIF
```


图形交换格式


### JPEG {#JPEG}
```
public static final FileType JPEG
```


联合图像专家组


### JPG {#JPG}
```
public static final FileType JPG
```


联合图像专家组


### PNG {#PNG}
```
public static final FileType PNG
```


可移植网络图形


### SVG {#SVG}
```
public static final FileType SVG
```


标量矢量图形


### EML {#EML}
```
public static final FileType EML
```


电子邮件消息


### EMLX {#EMLX}
```
public static final FileType EMLX
```


Apple Mail 电子邮件文件


### MSG {#MSG}
```
public static final FileType MSG
```


Microsoft Outlook 电子邮件消息


### CAD {#CAD}
```
public static final FileType CAD
```


CAD 文件格式


### CPP {#CPP}
```
public static final FileType CPP
```


基于 C 的编程语言格式


### CC {#CC}
```
public static final FileType CC
```


基于 C 的编程语言格式


### CXX {#CXX}
```
public static final FileType CXX
```


基于 C 的编程语言格式


### HXX {#HXX}
```
public static final FileType HXX
```


用 C++ 编程语言编写的头文件


### HH {#HH}
```
public static final FileType HH
```


C++ 源代码文件引用的头信息


### HPP {#HPP}
```
public static final FileType HPP
```


用 C++ 编程语言编写的头文件


### CMAKE {#CMAKE}
```
public static final FileType CMAKE
```


用于管理软件构建过程的工具


### CS {#CS}
```
public static final FileType CS
```


CSharp 编程语言格式


### CSX {#CSX}
```
public static final FileType CSX
```


CSharp 脚本文件格式


### CAKE {#CAKE}
```
public static final FileType CAKE
```


CSharp 跨平台构建自动化系统格式


### DIFF {#DIFF}
```
public static final FileType DIFF
```


数据比较工具格式


### PATCH {#PATCH}
```
public static final FileType PATCH
```


差异列表格式


### REJ {#REJ}
```
public static final FileType REJ
```


被拒绝文件格式


### GROOVY {#GROOVY}
```
public static final FileType GROOVY
```


以 Groovy 格式编写的源代码文件


### GVY {#GVY}
```
public static final FileType GVY
```


以 Groovy 格式编写的源代码文件


### GRADLE {#GRADLE}
```
public static final FileType GRADLE
```


构建自动化系统格式


### HAML {#HAML}
```
public static final FileType HAML
```


用于简化 HTML 生成的标记语言


### JS {#JS}
```
public static final FileType JS
```


JavaScript 编程语言格式


### ES6 {#ES6}
```
public static final FileType ES6
```


JavaScript 标准化脚本语言格式


### MJS {#MJS}
```
public static final FileType MJS
```


EcmaScript（ES）模块文件的扩展名


### PAC {#PAC}
```
public static final FileType PAC
```


用于 JavaScript 函数的代理自动配置文件格式


### JSON {#JSON}
```
public static final FileType JSON
```


用于存储和传输数据的轻量级格式


### BOWERRC {#BOWERRC}
```
public static final FileType BOWERRC
```


服务器端包管理的配置文件


### JSHINTRC {#JSHINTRC}
```
public static final FileType JSHINTRC
```


JavaScript 代码质量工具


### JSCSRC {#JSCSRC}
```
public static final FileType JSCSRC
```


JavaScript 配置文件格式


### WEBMANIFEST {#WEBMANIFEST}
```
public static final FileType WEBMANIFEST
```


清单文件包含有关应用程序的信息


### JSMAP {#JSMAP}
```
public static final FileType JSMAP
```


包含将代码翻译回源代码方法信息的 JSON 文件


### HAR {#HAR}
```
public static final FileType HAR
```


HTTP 存档格式


### JAVA {#JAVA}
```
public static final FileType JAVA
```


Java 编程语言格式


### LESS {#LESS}
```
public static final FileType LESS
```


动态预处理器样式表语言格式


### LOG {#LOG}
```
public static final FileType LOG
```


日志记录维护事件、进程、消息和通信的注册表


### MAKE {#MAKE}
```
public static final FileType MAKE
```


Makefile 是一个包含一组指令的文件，这些指令由 make 构建自动化工具用于生成目标/目标


### MK {#MK}
```
public static final FileType MK
```


Makefile 是一个包含一组指令的文件，这些指令由 make 构建自动化工具用于生成目标/目标


### MD {#MD}
```
public static final FileType MD
```


Markdown 语言格式


### MKD {#MKD}
```
public static final FileType MKD
```


Markdown 语言格式


### MDWN {#MDWN}
```
public static final FileType MDWN
```


Markdown 语言格式


### MDOWN {#MDOWN}
```
public static final FileType MDOWN
```


Markdown 语言格式


### MARKDOWN {#MARKDOWN}
```
public static final FileType MARKDOWN
```


Markdown 语言格式


### MARKDN {#MARKDN}
```
public static final FileType MARKDN
```


Markdown 语言格式


### MDTXT {#MDTXT}
```
public static final FileType MDTXT
```


Markdown 语言格式


### MDTEXT {#MDTEXT}
```
public static final FileType MDTEXT
```


Markdown 语言格式


### ML {#ML}
```
public static final FileType ML
```


Caml 编程语言格式


### MLI {#MLI}
```
public static final FileType MLI
```


Caml 编程语言格式


### OBJC {#OBJC}
```
public static final FileType OBJC
```


Objective-C 编程语言格式


### OBJCP {#OBJCP}
```
public static final FileType OBJCP
```


Objective-C++ 编程语言格式


### PHP {#PHP}
```
public static final FileType PHP
```


PHP 编程语言格式


### PHP4 {#PHP4}
```
public static final FileType PHP4
```


PHP 编程语言格式


### PHP5 {#PHP5}
```
public static final FileType PHP5
```


PHP 编程语言格式


### PHTML {#PHTML}
```
public static final FileType PHTML
```


PHP 2 程序的标准文件扩展名格式


### CTP {#CTP}
```
public static final FileType CTP
```


CakePHP 模板格式


### PL {#PL}
```
public static final FileType PL
```


Perl 编程语言格式


### PM {#PM}
```
public static final FileType PM
```


Perl 模块格式


### POD {#POD}
```
public static final FileType POD
```


Perl 轻量级标记语言格式


### T {#T}
```
public static final FileType T
```


Perl 测试文件格式


### PSGI {#PSGI}
```
public static final FileType PSGI
```


Perl 编程编写的 Web 服务器与 Web 应用程序和框架之间的接口


### P6 {#P6}
```
public static final FileType P6
```


Perl 编程语言格式


### PL6 {#PL6}
```
public static final FileType PL6
```


Perl 编程语言格式


### PM6 {#PM6}
```
public static final FileType PM6
```


Perl 模块格式


### NQP {#NQP}
```
public static final FileType NQP
```


用于构建 Rakuto Perl 6 编译器的中间语言


### PROP {#PROP}
```
public static final FileType PROP
```


属性文件格式


### CFG {#CFG}
```
public static final FileType CFG
```


用于存储设置的配置文件


### CONF {#CONF}
```
public static final FileType CONF
```


在 Unix 和基于 Linux 的系统上使用的配置文件


### DIR {#DIR}
```
public static final FileType DIR
```


目录是计算机上用于存储文件的位置


### PY {#PY}
```
public static final FileType PY
```


Python 编程语言格式


### RPY {#RPY}
```
public static final FileType RPY
```


基于 Python 的文件引擎，用于创建和运行游戏


### PYW {#PYW}
```
public static final FileType PYW
```


Windows 中用于指示脚本需要运行的文件


### CPY {#CPY}
```
public static final FileType CPY
```


Controller Python 脚本格式


### GYP {#GYP}
```
public static final FileType GYP
```


构建自动化工具格式


### GYPI {#GYPI}
```
public static final FileType GYPI
```


构建自动化工具格式


### PYI {#PYI}
```
public static final FileType PYI
```


Python 接口文件格式


### IPY {#IPY}
```
public static final FileType IPY
```


IPython 脚本格式


### RST {#RST}
```
public static final FileType RST
```


轻量级标记语言


### RB {#RB}
```
public static final FileType RB
```


Ruby 编程语言格式


### ERB {#ERB}
```
public static final FileType ERB
```


Ruby 编程语言格式


### RJS {#RJS}
```
public static final FileType RJS
```


Ruby 编程语言格式


### GEMSPEC {#GEMSPEC}
```
public static final FileType GEMSPEC
```


指定 RubyGems 属性的开发者文件


### RAKE {#RAKE}
```
public static final FileType RAKE
```


Ruby 构建自动化工具


### RU {#RU}
```
public static final FileType RU
```


Rack 配置文件格式


### PODSPEC {#PODSPEC}
```
public static final FileType PODSPEC
```


Ruby 构建设置格式


### RBI {#RBI}
```
public static final FileType RBI
```


Ruby 接口文件格式


### SASS {#SASS}
```
public static final FileType SASS
```


样式表语言格式


### SCSS {#SCSS}
```
public static final FileType SCSS
```


样式表语言格式


### SCALA {#SCALA}
```
public static final FileType SCALA
```


Scala 编程语言格式


### SBT {#SBT}
```
public static final FileType SBT
```


Scala 的 SBT 构建工具格式


### SC {#SC}
```
public static final FileType SC
```


Scala 工作表格式


### SH {#SH}
```
public static final FileType SH
```


为 bash 编写的脚本格式


### BASH {#BASH}
```
public static final FileType BASH
```


处理 shell 命令的解释器类型


### BASHRC {#BASHRC}
```
public static final FileType BASHRC
```


决定交互式 shell 行为的文件


### EBUILD {#EBUILD}
```
public static final FileType EBUILD
```


用于自动化软件包编译和安装过程的专用 bash 脚本


### SQL {#SQL}
```
public static final FileType SQL
```


结构化查询语言格式


### DSQL {#DSQL}
```
public static final FileType DSQL
```


动态结构化查询语言格式


### VIM {#VIM}
```
public static final FileType VIM
```


Vim 源代码文件格式


### YAML {#YAML}
```
public static final FileType YAML
```


人类可读的数据序列化语言格式


### YML {#YML}
```
public static final FileType YML
```


人类可读的数据序列化语言格式


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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String |  |

**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype)
### fromFileNameOrExtension(String value) {#fromFileNameOrExtension-java.lang.String-}
```
public static FileType fromFileNameOrExtension(String value)
```


根据文件名或扩展名返回 FileType


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.lang.String | 文件名或扩展名，不能为空 |
|

**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the file type

### getSupportedFileTypes() {#getSupportedFileTypes--}
```
public static List<FileType> getSupportedFileTypes()
```


获取支持的文件类型列表


**Returns:**
java.util.List<com.groupdocs.comparison.result.FileType> - FileType 列表

### areEquals(FileType left, FileType right) {#areEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-}
```
public static boolean areEquals(FileType left, FileType right)
```


检查提供的文件类型是否相等


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | left | [FileType](../../com.groupdocs.comparison.result/filetype) | 左侧 [FileType](../../com.groupdocs.comparison.result/filetype) 对象。 |
|
|  | right | [FileType](../../com.groupdocs.comparison.result/filetype) | 右侧 [FileType](../../com.groupdocs.comparison.result/filetype) 对象。 |
|

**Returns:**
boolean - 相等返回 true，否则返回 false

### areNotEquals(FileType left, FileType right) {#areNotEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-}
```
public static boolean areNotEquals(FileType left, FileType right)
```


检查提供的文件类型是否不相等


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | left | [FileType](../../com.groupdocs.comparison.result/filetype) | 左侧 [FileType](../../com.groupdocs.comparison.result/filetype) 对象。 |
|
|  | right | [FileType](../../com.groupdocs.comparison.result/filetype) | 右侧 [FileType](../../com.groupdocs.comparison.result/filetype) 对象。 |
|

**Returns:**
boolean - 如果不相等则为 true，否则为 false

### getFileFormat() {#getFileFormat--}
```
public String getFileFormat()
```


获取文件类型的文本描述


**Returns:**
java.lang.String - 文件类型描述

### getExtension() {#getExtension--}
```
public String getExtension()
```


获取文件类型的扩展名


**Returns:**
java.lang.String - 文件类型的扩展名

### toString() {#toString--}
```
public String toString()
```


获取 [FileType](../../com.groupdocs.comparison.result/filetype) 的字符串表示，例如
'PHP 编程语言格式 (.php)'



**Returns:**
java.lang.String - 字符串表示

