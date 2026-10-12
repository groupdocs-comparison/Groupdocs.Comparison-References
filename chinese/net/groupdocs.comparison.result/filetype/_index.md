---
title: "FileType"
second_title: "GroupDocs.Comparison 适用于 .NET 的 API 参考"
description: "表示文件类型。提供方法获取 GroupDocs.Comparison 支持的所有文件类型列表、通过扩展名检测文件类型等。"
type: docs
weight: 480
url: /zh/net/groupdocs.comparison.result/filetype/
---
## FileType class

表示文件类型。提供获取 GroupDocs.Comparison 支持的所有文件类型列表、通过扩展名检测文件类型等方法。

```csharp
public sealed class FileType : IEquatable<FileType>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Extension](../../groupdocs.comparison.result/filetype/extension) { get; } | 文件扩展名 |
| [FileFormat](../../groupdocs.comparison.result/filetype/fileformat) { get; } | 文件格式 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [FromFileNameOrExtension](../../groupdocs.comparison.result/filetype/fromfilenameorextension)(string) | 根据文件名或扩展名返回 FileType |
| [Equals](../../groupdocs.comparison.result/filetype/equals#equals)(FileType) | 文件类型等价性检查 |
| override [Equals](../../groupdocs.comparison.result/filetype/equals#equals_1)(object) | 对象等价性检查 |
| override [GetHashCode](../../groupdocs.comparison.result/filetype/gethashcode)() | 获取哈希码 |
| override [ToString](../../groupdocs.comparison.result/filetype/tostring)() | ToString |
| static [GetSupportedFileTypes](../../groupdocs.comparison.result/filetype/getsupportedfiletypes)() | 获取受支持的文件类型枚举 |
| [operator ==](../../groupdocs.comparison.result/filetype/op_equality) | 运算符重载 |
| [operator !=](../../groupdocs.comparison.result/filetype/op_inequality) | 运算符重载 |

## 字段

| 名称 | 描述 |
| --- | --- |
| static readonly [AS](../../groupdocs.comparison.result/filetype/as) | ActionScript 编程语言格式 |
| static readonly [AS3](../../groupdocs.comparison.result/filetype/as3) | ActionScript 编程语言格式 |
| static readonly [ASM](../../groupdocs.comparison.result/filetype/asm) | ASM 格式 |
| static readonly [BASH](../../groupdocs.comparison.result/filetype/bash) | 处理 shell 命令的解释器类型 |
| static readonly [BASHRC](../../groupdocs.comparison.result/filetype/bashrc) | 文件决定交互式 shell 的行为 |
| static readonly [BAT](../../groupdocs.comparison.result/filetype/bat) | DOS、OS/2 和 Microsoft Windows 中的脚本文件 |
| static readonly [BMP](../../groupdocs.comparison.result/filetype/bmp) | Bitmap 图片 |
| static readonly [BOWERRC](../../groupdocs.comparison.result/filetype/bowerrc) | 服务器端包控制的配置文件 |
| static readonly [C](../../groupdocs.comparison.result/filetype/c) | 基于 C 的编程语言格式 |
| static readonly [CAD](../../groupdocs.comparison.result/filetype/cad) | CAD 文件格式 |
| static readonly [CAKE](../../groupdocs.comparison.result/filetype/cake) | CSharp 跨平台构建自动化系统格式 |
| static readonly [CC](../../groupdocs.comparison.result/filetype/cc) | 基于 C 的编程语言格式 |
| static readonly [CFG](../../groupdocs.comparison.result/filetype/cfg) | 用于存储设置的配置文件 |
| static readonly [CMAKE](../../groupdocs.comparison.result/filetype/cmake) | 用于管理软件构建过程的工具 |
| static readonly [CMD](../../groupdocs.comparison.result/filetype/cmd) | DOS、OS/2 和 Microsoft Windows 中的脚本文件 |
| static readonly [CONF](../../groupdocs.comparison.result/filetype/conf) | 在 Unix 和基于 Linux 的系统上使用的配置文件 |
| static readonly [CPP](../../groupdocs.comparison.result/filetype/cpp) | 基于 C 的编程语言格式 |
| static readonly [CPY](../../groupdocs.comparison.result/filetype/cpy) | Controller Python 脚本格式 |
| static readonly [CS](../../groupdocs.comparison.result/filetype/cs) | CSharp 编程语言格式 |
| static readonly [CSV](../../groupdocs.comparison.result/filetype/csv) | 逗号分隔值文件 |
| static readonly [CSX](../../groupdocs.comparison.result/filetype/csx) | CSharp 脚本文件格式 |
| static readonly [CTP](../../groupdocs.comparison.result/filetype/ctp) | CakePHP 模板格式 |
| static readonly [CXX](../../groupdocs.comparison.result/filetype/cxx) | 基于 C 的编程语言格式 |
| static readonly [DCM](../../groupdocs.comparison.result/filetype/dcm) | 医学数字成像与通信 |
| static readonly [DIFF](../../groupdocs.comparison.result/filetype/diff) | 数据比较工具格式 |
| static readonly [DIR](../../groupdocs.comparison.result/filetype/dir) | 目录是计算机上存储文件的位置 |
| static readonly [DJVU](../../groupdocs.comparison.result/filetype/djvu) | Deja Vu 格式 |
| static readonly [DOC](../../groupdocs.comparison.result/filetype/doc) | Microsoft Word 97-2003 文档 |
| static readonly [DOCM](../../groupdocs.comparison.result/filetype/docm) | Microsoft Word 启用宏的文档 |
| static readonly [DOCX](../../groupdocs.comparison.result/filetype/docx) | Microsoft Word 文档 |
| static readonly [DOT](../../groupdocs.comparison.result/filetype/dot) | Microsoft Word 97-2003 模板 |
| static readonly [DOTM](../../groupdocs.comparison.result/filetype/dotm) | Microsoft Word 启用宏的模板 |
| static readonly [DOTX](../../groupdocs.comparison.result/filetype/dotx) | Microsoft Word 模板 |
| static readonly [DSQL](../../groupdocs.comparison.result/filetype/dsql) | 动态结构化查询语言格式 |
| static readonly [DWG](../../groupdocs.comparison.result/filetype/dwg) | Autodesk 设计数据格式 |
| static readonly [DXF](../../groupdocs.comparison.result/filetype/dxf) | AutoCAD 绘图交换 |
| static readonly [EBUILD](../../groupdocs.comparison.result/filetype/ebuild) | 专用 bash 脚本，可自动化软件包的编译和安装过程 |
| static readonly [EML](../../groupdocs.comparison.result/filetype/eml) | 电子邮件消息 |
| static readonly [EMLX](../../groupdocs.comparison.result/filetype/emlx) | Apple Mail 电子邮件文件 |
| static readonly [ERB](../../groupdocs.comparison.result/filetype/erb) | Ruby 编程语言格式 |
| static readonly [ES6](../../groupdocs.comparison.result/filetype/es6) | JavaScript 标准化脚本语言格式 |
| static readonly [GEMSPEC](../../groupdocs.comparison.result/filetype/gemspec) | 指定 RubyGems 属性的开发者文件 |
| static readonly [GIF](../../groupdocs.comparison.result/filetype/gif) | 图形交换格式 |
| static readonly [GRADLE](../../groupdocs.comparison.result/filetype/gradle) | 构建自动化系统格式 |
| static readonly [GROOVY](../../groupdocs.comparison.result/filetype/groovy) | 使用 Groovy 编写的源代码文件 |
| static readonly [GVY](../../groupdocs.comparison.result/filetype/gvy) | 使用 Groovy 编写的源代码文件 |
| static readonly [GYP](../../groupdocs.comparison.result/filetype/gyp) | 构建自动化工具格式 |
| static readonly [GYPI](../../groupdocs.comparison.result/filetype/gypi) | 构建自动化工具格式 |
| static readonly [H](../../groupdocs.comparison.result/filetype/h) | 基于 C 的头文件包含函数和变量的定义 |
| static readonly [HAML](../../groupdocs.comparison.result/filetype/haml) | 用于简化 HTML 生成的标记语言 |
| static readonly [HAR](../../groupdocs.comparison.result/filetype/har) | HTTP 存档格式 |
| static readonly [HH](../../groupdocs.comparison.result/filetype/hh) | C++ 源代码文件引用的头部信息 |
| static readonly [HPP](../../groupdocs.comparison.result/filetype/hpp) | 用 C++ 编程语言编写的头文件 |
| static readonly [HTML](../../groupdocs.comparison.result/filetype/html) | 超文本标记语言 |
| static readonly [HXX](../../groupdocs.comparison.result/filetype/hxx) | 用 C++ 编程语言编写的头文件 |
| static readonly [IPY](../../groupdocs.comparison.result/filetype/ipy) | IPython 脚本格式 |
| static readonly [JAVA](../../groupdocs.comparison.result/filetype/java) | Java 编程语言格式 |
| static readonly [JPEG](../../groupdocs.comparison.result/filetype/jpeg) | 联合图像专家组 |
| static readonly [JS](../../groupdocs.comparison.result/filetype/js) | JavaScript 编程语言格式 |
| static readonly [JSCSRC](../../groupdocs.comparison.result/filetype/jscsrc) | JavaScript 配置文件格式 |
| static readonly [JSHINTRC](../../groupdocs.comparison.result/filetype/jshintrc) | JavaScript 代码质量工具 |
| static readonly [JSMAP](../../groupdocs.comparison.result/filetype/jsmap) | 包含将代码翻译回源代码信息的 JSON 文件 |
| static readonly [JSON](../../groupdocs.comparison.result/filetype/json) | 用于存储和传输数据的轻量级格式 |
| static readonly [LESS](../../groupdocs.comparison.result/filetype/less) | 动态预处理器样式表语言格式 |
| static readonly [LOG](../../groupdocs.comparison.result/filetype/log) | 日志记录保持事件、进程、消息和通信的注册表 |
| static readonly [MAKE](../../groupdocs.comparison.result/filetype/make) | Makefile 是一个包含一组指令的文件，这些指令由 make 构建自动化工具使用以生成目标/目标 |
| static readonly [MARKDN](../../groupdocs.comparison.result/filetype/markdn) | Markdown 语言格式 |
| static readonly [MARKDOWN](../../groupdocs.comparison.result/filetype/markdown) | Markdown 语言格式 |
| static readonly [MD](../../groupdocs.comparison.result/filetype/md) | Markdown 语言格式 |
| static readonly [MDOWN](../../groupdocs.comparison.result/filetype/mdown) | Markdown 语言格式 |
| static readonly [MDTEXT](../../groupdocs.comparison.result/filetype/mdtext) | Markdown 语言格式 |
| static readonly [MDTXT](../../groupdocs.comparison.result/filetype/mdtxt) | Markdown 语言格式 |
| static readonly [MDWN](../../groupdocs.comparison.result/filetype/mdwn) | Markdown 语言格式 |
| static readonly [MHTML](../../groupdocs.comparison.result/filetype/mhtml) | MIME HTML |
| static readonly [MJS](../../groupdocs.comparison.result/filetype/mjs) | EcmaScript (ES) 模块文件的扩展名 |
| static readonly [MK](../../groupdocs.comparison.result/filetype/mk) | Makefile 是一个包含一组指令的文件，这些指令由 make 构建自动化工具使用以生成目标/目标 |
| static readonly [MKD](../../groupdocs.comparison.result/filetype/mkd) | Markdown 语言格式 |
| static readonly [ML](../../groupdocs.comparison.result/filetype/ml) | Caml 编程语言格式 |
| static readonly [MLI](../../groupdocs.comparison.result/filetype/mli) | Caml 编程语言格式 |
| static readonly [MOBI](../../groupdocs.comparison.result/filetype/mobi) | Mobipocket 电子书格式 |
| static readonly [MSG](../../groupdocs.comparison.result/filetype/msg) | Microsoft Outlook 电子邮件 |
| static readonly [NQP](../../groupdocs.comparison.result/filetype/nqp) | 用于构建 Rakudo Perl 6 编译器的中间语言 |
| static readonly [OBJC](../../groupdocs.comparison.result/filetype/objc) | Objective-C 编程语言格式 |
| static readonly [OBJCP](../../groupdocs.comparison.result/filetype/objcp) | Objective-C++ 编程语言格式 |
| static readonly [ODP](../../groupdocs.comparison.result/filetype/odp) | OpenDocument 演示文稿 |
| static readonly [ODS](../../groupdocs.comparison.result/filetype/ods) | OpenDocument 电子表格 |
| static readonly [ODT](../../groupdocs.comparison.result/filetype/odt) | OpenDocument 文本 |
| static readonly [ONE](../../groupdocs.comparison.result/filetype/one) | Microsoft OneNote 文档 |
| static readonly [OTP](../../groupdocs.comparison.result/filetype/otp) | OpenDocument 演示文稿模板 |
| static readonly [OTT](../../groupdocs.comparison.result/filetype/ott) | OpenDocument 文本模板 |
| static readonly [P6](../../groupdocs.comparison.result/filetype/p6) | Perl 编程语言格式 |
| static readonly [PAC](../../groupdocs.comparison.result/filetype/pac) | JavaScript 函数格式的代理自动配置文件 |
| static readonly [PATCH](../../groupdocs.comparison.result/filetype/patch) | 差异列表格式 |
| static readonly [PDF](../../groupdocs.comparison.result/filetype/pdf) | Adobe 可移植文档格式 |
| static readonly [PHP](../../groupdocs.comparison.result/filetype/php) | PHP 编程语言格式 |
| static readonly [PHP4](../../groupdocs.comparison.result/filetype/php4) | PHP 编程语言格式 |
| static readonly [PHP5](../../groupdocs.comparison.result/filetype/php5) | PHP 编程语言格式 |
| static readonly [PHTML](../../groupdocs.comparison.result/filetype/phtml) | PHP 2 程序的标准文件扩展名格式 |
| static readonly [PL](../../groupdocs.comparison.result/filetype/pl) | Perl 编程语言格式 |
| static readonly [PL6](../../groupdocs.comparison.result/filetype/pl6) | Perl 编程语言格式 |
| static readonly [PM](../../groupdocs.comparison.result/filetype/pm) | Perl 模块格式 |
| static readonly [PM6](../../groupdocs.comparison.result/filetype/pm6) | Perl 模块格式 |
| static readonly [PNG](../../groupdocs.comparison.result/filetype/png) | 可移植网络图形 |
| static readonly [POD](../../groupdocs.comparison.result/filetype/pod) | Perl 轻量标记语言格式 |
| static readonly [PODSPEC](../../groupdocs.comparison.result/filetype/podspec) | Ruby 构建设置格式 |
| static readonly [POT](../../groupdocs.comparison.result/filetype/pot) | Microsoft PowerPoint 模板 |
| static readonly [POTX](../../groupdocs.comparison.result/filetype/potx) | Microsoft PowerPoint 模板 |
| static readonly [PPS](../../groupdocs.comparison.result/filetype/pps) | Microsoft PowerPoint 97-2003 幻灯片放映 |
| static readonly [PPSX](../../groupdocs.comparison.result/filetype/ppsx) | Microsoft PowerPoint 幻灯片放映 |
| static readonly [PPT](../../groupdocs.comparison.result/filetype/ppt) | Microsoft PowerPoint 97-2003 演示文稿 |
| static readonly [PPTX](../../groupdocs.comparison.result/filetype/pptx) | Microsoft PowerPoint 演示文稿 |
| static readonly [PROP](../../groupdocs.comparison.result/filetype/prop) | 属性文件格式 |
| static readonly [PSGI](../../groupdocs.comparison.result/filetype/psgi) | Perl 编程编写的 Web 服务器与 Web 应用程序和框架之间的接口 |
| static readonly [PY](../../groupdocs.comparison.result/filetype/py) | Python 编程语言格式 |
| static readonly [PYI](../../groupdocs.comparison.result/filetype/pyi) | Python 接口文件格式 |
| static readonly [PYW](../../groupdocs.comparison.result/filetype/pyw) | Windows 中用于指示脚本需要运行的文件 |
| static readonly [RAKE](../../groupdocs.comparison.result/filetype/rake) | Ruby 构建自动化工具 |
| static readonly [RB](../../groupdocs.comparison.result/filetype/rb) | Ruby 编程语言格式 |
| static readonly [RBI](../../groupdocs.comparison.result/filetype/rbi) | Ruby 接口文件格式 |
| static readonly [REJ](../../groupdocs.comparison.result/filetype/rej) | 被拒绝文件格式 |
| static readonly [RJS](../../groupdocs.comparison.result/filetype/rjs) | Ruby 编程语言格式 |
| static readonly [RPY](../../groupdocs.comparison.result/filetype/rpy) | 基于 Python 的文件引擎，用于创建和运行游戏 |
| static readonly [RST](../../groupdocs.comparison.result/filetype/rst) | 轻量级标记语言 |
| static readonly [RTF](../../groupdocs.comparison.result/filetype/rtf) | 富文本文档 |
| static readonly [RU](../../groupdocs.comparison.result/filetype/ru) | Rack 配置文件格式 |
| static readonly [SASS](../../groupdocs.comparison.result/filetype/sass) | 样式表语言格式 |
| static readonly [SBT](../../groupdocs.comparison.result/filetype/sbt) | Scala 的 SBT 构建工具格式 |
| static readonly [SC](../../groupdocs.comparison.result/filetype/sc) | Scala 工作表格式 |
| static readonly [SCALA](../../groupdocs.comparison.result/filetype/scala) | Scala 编程语言格式 |
| static readonly [SCSS](../../groupdocs.comparison.result/filetype/scss) | 样式表语言格式 |
| static readonly [SH](../../groupdocs.comparison.result/filetype/sh) | 为 bash 编写的脚本格式 |
| static readonly [SQL](../../groupdocs.comparison.result/filetype/sql) | 结构化查询语言格式 |
| static readonly [SVG](../../groupdocs.comparison.result/filetype/svg) | 标量矢量图形 |
| static readonly [T](../../groupdocs.comparison.result/filetype/t) | Perl 测试文件格式 |
| static readonly [TXT](../../groupdocs.comparison.result/filetype/txt) | 纯文本文档 |
| static readonly [UNKNOWN](../../groupdocs.comparison.result/filetype/unknown) | 未知类型 |
| static readonly [VDX](../../groupdocs.comparison.result/filetype/vdx) | Microsoft Visio 2003-2010 XML 绘图 |
| static readonly [VIM](../../groupdocs.comparison.result/filetype/vim) | Vim 源代码文件格式 |
| static readonly [VSD](../../groupdocs.comparison.result/filetype/vsd) | Microsoft Visio 2003-2010 绘图 |
| static readonly [VSDX](../../groupdocs.comparison.result/filetype/vsdx) | Microsoft Visio 绘图 |
| static readonly [VSS](../../groupdocs.comparison.result/filetype/vss) | Microsoft Visio 2003-2010 模板 |
| static readonly [VST](../../groupdocs.comparison.result/filetype/vst) | Microsoft Visio 2003-2010 模板 |
| static readonly [WEBMANIFEST](../../groupdocs.comparison.result/filetype/webmanifest) | 清单文件包含有关应用程序的信息 |
| static readonly [XLS](../../groupdocs.comparison.result/filetype/xls) | Microsoft Excel 97-2003 工作表 |
| static readonly [XLSB](../../groupdocs.comparison.result/filetype/xlsb) | Microsoft Excel 二进制工作表 |
| static readonly [XLSM](../../groupdocs.comparison.result/filetype/xlsm) | Microsoft Excel 启用宏的工作表 |
| static readonly [XLSX](../../groupdocs.comparison.result/filetype/xlsx) | Microsoft Excel 工作表 |
| static readonly [XLT](../../groupdocs.comparison.result/filetype/xlt) | Microsoft Excel 模板 |
| static readonly [XLTM](../../groupdocs.comparison.result/filetype/xltm) | Microsoft Excel 启用宏的模板 |
| static readonly [YAML](../../groupdocs.comparison.result/filetype/yaml) | 人类可读的数据序列化语言格式 |
| static readonly [YML](../../groupdocs.comparison.result/filetype/yml) | 人类可读的数据序列化语言格式 |

### 备注

**Learn more**

* Learn more about file formats supported by GroupDocs.Comparison: [Full list of supported document formats](https://docs.groupdocs.com/display/comparisonnet/Supported+Document+Formats)
* Learn more about getting supported file types in C#: [How to get supported file formats in C#](https://docs.groupdocs.com/display/comparisonnet/Get+supported+file+formats)

### 另见

* namespace [GroupDocs.Comparison.Result](../../groupdocs.comparison.result)
* assembly [GroupDocs.Comparison](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.Comparison.dll 生成 -->
