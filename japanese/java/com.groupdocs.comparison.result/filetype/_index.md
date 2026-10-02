---
title: "FileType"
second_title: "Java 用 GroupDocs.Comparison API リファレンス"
description: "FileType 列挙型は、ドキュメント比較プロセスで使用されるファイルのタイプを表します。"
type: docs
weight: 16
url: /ja/java/com.groupdocs.comparison.result/filetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public enum FileType extends Enum<FileType> implements System.IEquatable<FileType>
```

FileType 列挙型は、ドキュメント比較プロセスで使用されるファイルのタイプを表します。


Word 文書、PDF ファイルなど、さまざまなファイルタイプを定義します。
GroupDocs.Comparison がサポートするすべてのファイルタイプの一覧を取得したり、拡張子でファイルタイプを検出したりするメソッドを提供します。
GroupDocs.Comparison ライブラリを使用する際にファイルタイプを指定するためにこの列挙型を使用します。

* Learn more about file formats supported by GroupDocs.Comparison: [Full list of supported document formats](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* Learn more about getting supported file types in Java: [How to get supported file formats in Java](../https://docs.groupdocs.com/display/comparisonjava/Get+supported+file+formats)


使用例:

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


## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [UNKNOWN](#UNKNOWN) | 不明なタイプ |
|
|  | [AS](#AS) | ActionScript プログラミング言語形式 |
|
|  | [AS3](#AS3) | ActionScript プログラミング言語形式 |
|
|  | [ASM](#ASM) | アセンブラ プログラミング言語 フォーマット |
|
|  | [BAT](#BAT) | DOS、OS/2、Microsoft Windows のスクリプト ファイル |
|
|  | [CMD](#CMD) | DOS、OS/2、Microsoft Windows のスクリプト ファイル |
|
|  | [C](#C) | Cベースのプログラミング言語 フォーマット |
|
|  | [H](#H) | Cベースのヘッダーファイルは関数と変数の定義を含みます |
|
|  | [PDF](#PDF) | Adobe Portable Document フォーマット |
|
|  | [DOC](#DOC) | Microsoft Word 97-2003 ドキュメント |
|
|  | [DOCM](#DOCM) | Microsoft Word マクロ対応ドキュメント |
|
|  | [DOCX](#DOCX) | Microsoft Word ドキュメント |
|
|  | [DOT](#DOT) | Microsoft Word 97-2003 テンプレート |
|
|  | [DOTM](#DOTM) | Microsoft Word マクロ対応テンプレート |
|
|  | [DOTX](#DOTX) | Microsoft Word テンプレート |
|
|  | [XLS](#XLS) | Microsoft Excel 97-2003 ワークシート |
|
|  | [XLT](#XLT) | Microsoft Excel テンプレート |
|
|  | [XLSX](#XLSX) | Microsoft Excel ワークシート |
|
|  | [XLTM](#XLTM) | Microsoft Excel マクロ対応テンプレート |
|
|  | [XLSB](#XLSB) | Microsoft Excel バイナリ ワークシート |
|
|  | [XLSM](#XLSM) | Microsoft Excel マクロ対応ワークシート |
|
|  | [POT](#POT) | Microsoft PowerPoint テンプレート |
|
|  | [POTX](#POTX) | Microsoft PowerPoint テンプレート |
|
|  | [POTM](#POTM) | マクロ対応の Microsoft PowerPoint テンプレート |
|
|  | [PPS](#PPS) | Microsoft PowerPoint 97-2003 スライドショー |
|
|  | [PPSX](#PPSX) | Microsoft PowerPoint スライドショー |
|
|  | [PPTX](#PPTX) | Microsoft PowerPoint プレゼンテーション |
|
|  | [PPT](#PPT) | Microsoft PowerPoint 97-2003 プレゼンテーション |
|
|  | [PPTM](#PPTM) | Microsoft PowerPoint マクロ対応プレゼンテーション |
|
|  | [PPSM](#PPSM) | Microsoft PowerPoint マクロ有効スライドショー プレゼンテーション |
|
|  | [VSDX](#VSDX) | Microsoft Visio 図面 |
|
|  | [VSD](#VSD) | Microsoft Visio 2003-2010 図面 |
|
|  | [VSS](#VSS) | Microsoft Visio 2003-2010 ステンシル |
|
|  | [VST](#VST) | Microsoft Visio 2003-2010 テンプレート |
|
|  | [VDX](#VDX) | Microsoft Visio 2003-2010 XML 図面 |
|
|  | [ONE](#ONE) | Microsoft OneNote 文書 |
|
|  | [ODT](#ODT) | OpenDocument テキスト |
|
|  | [ODP](#ODP) | OpenDocument プレゼンテーション |
|
|  | [OTP](#OTP) | OpenDocument プレゼンテーション テンプレート |
|
|  | [ODS](#ODS) | OpenDocument スプレッドシート |
|
|  | [OTT](#OTT) | OpenDocument テキスト テンプレート |
|
|  | [RTF](#RTF) | リッチテキスト文書 |
|
|  | [TXT](#TXT) | プレーンテキスト文書 |
|
|  | [CSV](#CSV) | カンマ区切り値ファイル |
|
|  | [HTML](#HTML) | ハイパーテキストマークアップ言語 |
|
|  | [MHTML](#MHTML) | MIME HTML |
|
|  | [MOBI](#MOBI) | Mobipocket 電子書籍フォーマット |
|
|  | [DCM](#DCM) | 医療用デジタル画像通信 |
|
|  | [DJVU](#DJVU) | Deja Vu フォーマット |
|
|  | [DWG](#DWG) | Autodesk デザインデータ形式 |
|
|  | [DXF](#DXF) | AutoCAD 図面交換形式 |
|
|  | [BMP](#BMP) | ビットマップ画像 |
|
|  | [GIF](#GIF) | グラフィックス交換フォーマット |
|
|  | [JPEG](#JPEG) | Joint Photographic Experts Group |
|
|  | [JPG](#JPG) | Joint Photographic Experts Group |
|
|  | [PNG](#PNG) | ポータブルネットワークグラフィックス |
|
|  | [SVG](#SVG) | スカラー ベクター グラフィックス |
|
|  | [EML](#EML) | 電子メールメッセージ |
|
|  | [EMLX](#EMLX) | Apple Mail 電子メールファイル |
|
|  | [MSG](#MSG) | Microsoft Outlook 電子メールメッセージ |
|
|  | [CAD](#CAD) | CAD ファイル形式 |
|
|  | [CPP](#CPP) | Cベースのプログラミング言語 フォーマット |
|
|  | [CC](#CC) | Cベースのプログラミング言語 フォーマット |
|
|  | [CXX](#CXX) | Cベースのプログラミング言語 フォーマット |
|
|  | [HXX](#HXX) | C++ プログラミング言語で書かれたヘッダーファイル |
|
|  | [HH](#HH) | C++ ソースコードファイルが参照するヘッダー情報 |
|
|  | [HPP](#HPP) | C++ プログラミング言語で書かれたヘッダーファイル |
|
|  | [CMAKE](#CMAKE) | ソフトウェアのビルドプロセスを管理するツール |
|
|  | [CS](#CS) | CSharp プログラミング言語形式 |
|
|  | [CSX](#CSX) | CSharp スクリプトファイル形式 |
|
|  | [CAKE](#CAKE) | CSharp クロスプラットフォームビルド自動化システム形式 |
|
|  | [DIFF](#DIFF) | データ比較ツール形式 |
|
|  | [PATCH](#PATCH) | 差分リスト形式 |
|
|  | [REJ](#REJ) | 拒否されたファイル形式 |
|
|  | [GROOVY](#GROOVY) | Groovy 形式で書かれたソースコードファイル |
|
|  | [GVY](#GVY) | Groovy 形式で書かれたソースコードファイル |
|
|  | [GRADLE](#GRADLE) | ビルド自動化システム形式 |
|
|  | [HAML](#HAML) | 簡易 HTML 生成のためのマークアップ言語 |
|
|  | [JS](#JS) | JavaScript プログラミング言語形式 |
|
|  | [ES6](#ES6) | JavaScript 標準化されたスクリプト言語形式 |
|
|  | [MJS](#MJS) | EcmaScript (ES) モジュールファイルの拡張子 |
|
|  | [PAC](#PAC) | JavaScript 関数用プロキシ自動構成ファイル |
|
|  | [JSON](#JSON) | データの保存と転送のための軽量フォーマット |
|
|  | [BOWERRC](#BOWERRC) | サーバー側のパッケージ管理用設定ファイル |
|
|  | [JSHINTRC](#JSHINTRC) | JavaScript コード品質ツール |
|
|  | [JSCSRC](#JSCSRC) | JavaScript 設定ファイル形式 |
|
|  | [WEBMANIFEST](#WEBMANIFEST) | マニフェスト ファイルにはアプリに関する情報が含まれています |
|
|  | [JSMAP](#JSMAP) | コードを元のソースコードに戻す方法に関する情報を含む JSON ファイル |
|
|  | [HAR](#HAR) | HTTP アーカイブ形式 |
|
|  | [JAVA](#JAVA) | Java プログラミング言語形式 |
|
|  | [LESS](#LESS) | 動的プリプロセッサ スタイルシート言語形式 |
|
|  | [LOG](#LOG) | ロギングはイベント、プロセス、メッセージ、通信のレジストリを保持します |
|
|  | [MAKE](#MAKE) | Makefile は、make ビルド自動化ツールで使用され、ターゲット/ゴールを生成するための指示セットを含むファイルです |
|
|  | [MK](#MK) | Makefile は、make ビルド自動化ツールで使用され、ターゲット/ゴールを生成するための指示セットを含むファイルです |
|
|  | [MD](#MD) | Markdown 言語形式 |
|
|  | [MKD](#MKD) | Markdown 言語形式 |
|
|  | [MDWN](#MDWN) | Markdown 言語形式 |
|
|  | [MDOWN](#MDOWN) | Markdown 言語形式 |
|
|  | [MARKDOWN](#MARKDOWN) | Markdown 言語形式 |
|
|  | [MARKDN](#MARKDN) | Markdown 言語形式 |
|
|  | [MDTXT](#MDTXT) | Markdown 言語形式 |
|
|  | [MDTEXT](#MDTEXT) | Markdown 言語形式 |
|
|  | [ML](#ML) | Caml プログラミング言語形式 |
|
|  | [MLI](#MLI) | Caml プログラミング言語形式 |
|
|  | [OBJC](#OBJC) | Objective-C プログラミング言語形式 |
|
|  | [OBJCP](#OBJCP) | Objective-C++ プログラミング言語形式 |
|
|  | [PHP](#PHP) | PHP プログラミング言語形式 |
|
|  | [PHP4](#PHP4) | PHP プログラミング言語形式 |
|
|  | [PHP5](#PHP5) | PHP プログラミング言語形式 |
|
|  | [PHTML](#PHTML) | PHP 2 プログラムの標準ファイル拡張子形式 |
|
|  | [CTP](#CTP) | CakePHP テンプレート形式 |
|
|  | [PL](#PL) | Perl プログラミング言語形式 |
|
|  | [PM](#PM) | Perl モジュール形式 |
|
|  | [POD](#POD) | Perl 軽量マークアップ言語形式 |
|
|  | [T](#T) | Perl テストファイル形式 |
|
|  | [PSGI](#PSGI) | Perl プログラミングで書かれたウェブサーバーとウェブアプリケーションおよびフレームワーク間のインターフェース |
|
|  | [P6](#P6) | Perl プログラミング言語形式 |
|
|  | [PL6](#PL6) | Perl プログラミング言語形式 |
|
|  | [PM6](#PM6) | Perl モジュール形式 |
|
|  | [NQP](#NQP) | Rakuto Perl 6 コンパイラを構築するために使用される中間言語 |
|
|  | [PROP](#PROP) | プロパティ ファイル形式 |
|
|  | [CFG](#CFG) | 設定を保存するために使用される構成ファイル |
|
|  | [CONF](#CONF) | Unix および Linux ベースのシステムで使用される構成ファイル |
|
|  | [DIR](#DIR) | ディレクトリはコンピュータ上でファイルを保存する場所です |
|
|  | [PY](#PY) | Python プログラミング言語形式 |
|
|  | [RPY](#RPY) | ゲームを作成および実行するための Python ベースのファイルエンジン |
|
|  | [PYW](#PYW) | スクリプトの実行が必要であることを示すために Windows で使用されるファイル |
|
|  | [CPY](#CPY) | コントローラ Python スクリプト形式 |
|
|  | [GYP](#GYP) | ビルド自動化ツール形式 |
|
|  | [GYPI](#GYPI) | ビルド自動化ツール形式 |
|
|  | [PYI](#PYI) | Python インターフェイスファイル形式 |
|
|  | [IPY](#IPY) | IPython スクリプト形式 |
|
|  | [RST](#RST) | 軽量マークアップ言語 |
|
|  | [RB](#RB) | Ruby プログラミング言語形式 |
|
|  | [ERB](#ERB) | Ruby プログラミング言語形式 |
|
|  | [RJS](#RJS) | Ruby プログラミング言語形式 |
|
|  | [GEMSPEC](#GEMSPEC) | RubyGems の属性を指定する開発者ファイル |
|
|  | [RAKE](#RAKE) | Ruby ビルド自動化ツール |
|
|  | [RU](#RU) | Rack 設定ファイル形式 |
|
|  | [PODSPEC](#PODSPEC) | Ruby ビルド設定形式 |
|
|  | [RBI](#RBI) | Ruby インターフェイスファイル形式 |
|
|  | [SASS](#SASS) | スタイルシート言語形式 |
|
|  | [SCSS](#SCSS) | スタイルシート言語形式 |
|
|  | [SCALA](#SCALA) | Scala プログラミング言語形式 |
|
|  | [SBT](#SBT) | Scala 用 SBT ビルドツール形式 |
|
|  | [SC](#SC) | Scala ワークシート形式 |
|
|  | [SH](#SH) | bash 用にプログラムされたスクリプト形式 |
|
|  | [BASH](#BASH) | シェルコマンドを処理するインタプリタのタイプ |
|
|  | [BASHRC](#BASHRC) | 対話型シェルの動作を決定するファイル |
|
|  | [EBUILD](#EBUILD) | ソフトウェアパッケージのコンパイルとインストール手順を自動化する特殊な bash スクリプト |
|
|  | [SQL](#SQL) | 構造化照会言語形式 |
|
|  | [DSQL](#DSQL) | 動的構造化照会言語形式 |
|
|  | [VIM](#VIM) | Vim ソースコードファイル形式 |
|
|  | [YAML](#YAML) | 人間が読みやすいデータシリアライズ言語フォーマット |
|
|  | [YML](#YML) | 人間が読みやすいデータシリアライズ言語フォーマット |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromFileNameOrExtension(String value)](#fromFileNameOrExtension-java.lang.String-) | ファイル名または拡張子に基づいて FileType を返す |
|
|  | [getSupportedFileTypes()](#getSupportedFileTypes--) | サポートされているファイルタイプのリストを取得する |
|
|  | [areEquals(FileType left, FileType right)](#areEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-) | 提供されたファイルタイプの等価性をチェックする |
|
|  | [areNotEquals(FileType left, FileType right)](#areNotEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-) | 提供されたファイルタイプが等しくないかをチェックする |
|
|  | [getFileFormat()](#getFileFormat--) | ファイルタイプのテキスト説明を取得する |
|
|  | [getExtension()](#getExtension--) | ファイルタイプの拡張子を取得する |
|
|  | [toString()](#toString--) | [FileType](../../com.groupdocs.comparison.result/filetype) の文字列表現を取得します、例として |
'PHP プログラミング言語フォーマット (.php)'

|
### UNKNOWN {#UNKNOWN}
```
public static final FileType UNKNOWN
```


不明なタイプ


### AS {#AS}
```
public static final FileType AS
```


ActionScript プログラミング言語形式


### AS3 {#AS3}
```
public static final FileType AS3
```


ActionScript プログラミング言語形式


### ASM {#ASM}
```
public static final FileType ASM
```


アセンブラ プログラミング言語 フォーマット


### BAT {#BAT}
```
public static final FileType BAT
```


DOS、OS/2、Microsoft Windows のスクリプト ファイル


### CMD {#CMD}
```
public static final FileType CMD
```


DOS、OS/2、Microsoft Windows のスクリプト ファイル


### C {#C}
```
public static final FileType C
```


Cベースのプログラミング言語 フォーマット


### H {#H}
```
public static final FileType H
```


Cベースのヘッダーファイルは関数と変数の定義を含みます


### PDF {#PDF}
```
public static final FileType PDF
```


Adobe Portable Document フォーマット


### DOC {#DOC}
```
public static final FileType DOC
```


Microsoft Word 97-2003 ドキュメント


### DOCM {#DOCM}
```
public static final FileType DOCM
```


Microsoft Word マクロ対応ドキュメント


### DOCX {#DOCX}
```
public static final FileType DOCX
```


Microsoft Word ドキュメント


### DOT {#DOT}
```
public static final FileType DOT
```


Microsoft Word 97-2003 テンプレート


### DOTM {#DOTM}
```
public static final FileType DOTM
```


Microsoft Word マクロ対応テンプレート


### DOTX {#DOTX}
```
public static final FileType DOTX
```


Microsoft Word テンプレート


### XLS {#XLS}
```
public static final FileType XLS
```


Microsoft Excel 97-2003 ワークシート


### XLT {#XLT}
```
public static final FileType XLT
```


Microsoft Excel テンプレート


### XLSX {#XLSX}
```
public static final FileType XLSX
```


Microsoft Excel ワークシート


### XLTM {#XLTM}
```
public static final FileType XLTM
```


Microsoft Excel マクロ対応テンプレート


### XLSB {#XLSB}
```
public static final FileType XLSB
```


Microsoft Excel バイナリ ワークシート


### XLSM {#XLSM}
```
public static final FileType XLSM
```


Microsoft Excel マクロ対応ワークシート


### POT {#POT}
```
public static final FileType POT
```


Microsoft PowerPoint テンプレート


### POTX {#POTX}
```
public static final FileType POTX
```


Microsoft PowerPoint テンプレート


### POTM {#POTM}
```
public static final FileType POTM
```


マクロ対応の Microsoft PowerPoint テンプレート


### PPS {#PPS}
```
public static final FileType PPS
```


Microsoft PowerPoint 97-2003 スライドショー


### PPSX {#PPSX}
```
public static final FileType PPSX
```


Microsoft PowerPoint スライドショー


### PPTX {#PPTX}
```
public static final FileType PPTX
```


Microsoft PowerPoint プレゼンテーション


### PPT {#PPT}
```
public static final FileType PPT
```


Microsoft PowerPoint 97-2003 プレゼンテーション


### PPTM {#PPTM}
```
public static final FileType PPTM
```


Microsoft PowerPoint マクロ対応プレゼンテーション


### PPSM {#PPSM}
```
public static final FileType PPSM
```


Microsoft PowerPoint マクロ有効スライドショー プレゼンテーション


### VSDX {#VSDX}
```
public static final FileType VSDX
```


Microsoft Visio 図面


### VSD {#VSD}
```
public static final FileType VSD
```


Microsoft Visio 2003-2010 図面


### VSS {#VSS}
```
public static final FileType VSS
```


Microsoft Visio 2003-2010 ステンシル


### VST {#VST}
```
public static final FileType VST
```


Microsoft Visio 2003-2010 テンプレート


### VDX {#VDX}
```
public static final FileType VDX
```


Microsoft Visio 2003-2010 XML 図面


### ONE {#ONE}
```
public static final FileType ONE
```


Microsoft OneNote 文書


### ODT {#ODT}
```
public static final FileType ODT
```


OpenDocument テキスト


### ODP {#ODP}
```
public static final FileType ODP
```


OpenDocument プレゼンテーション


### OTP {#OTP}
```
public static final FileType OTP
```


OpenDocument プレゼンテーション テンプレート


### ODS {#ODS}
```
public static final FileType ODS
```


OpenDocument スプレッドシート


### OTT {#OTT}
```
public static final FileType OTT
```


OpenDocument テキスト テンプレート


### RTF {#RTF}
```
public static final FileType RTF
```


リッチテキスト文書


### TXT {#TXT}
```
public static final FileType TXT
```


プレーンテキスト文書


### CSV {#CSV}
```
public static final FileType CSV
```


カンマ区切り値ファイル


### HTML {#HTML}
```
public static final FileType HTML
```


ハイパーテキストマークアップ言語


### MHTML {#MHTML}
```
public static final FileType MHTML
```


MIME HTML


### MOBI {#MOBI}
```
public static final FileType MOBI
```


Mobipocket 電子書籍フォーマット


### DCM {#DCM}
```
public static final FileType DCM
```


医療用デジタル画像通信


### DJVU {#DJVU}
```
public static final FileType DJVU
```


Deja Vu フォーマット


### DWG {#DWG}
```
public static final FileType DWG
```


Autodesk デザインデータ形式


### DXF {#DXF}
```
public static final FileType DXF
```


AutoCAD 図面交換形式


### BMP {#BMP}
```
public static final FileType BMP
```


ビットマップ画像


### GIF {#GIF}
```
public static final FileType GIF
```


グラフィックス交換フォーマット


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


ポータブルネットワークグラフィックス


### SVG {#SVG}
```
public static final FileType SVG
```


スカラー ベクター グラフィックス


### EML {#EML}
```
public static final FileType EML
```


電子メールメッセージ


### EMLX {#EMLX}
```
public static final FileType EMLX
```


Apple Mail 電子メールファイル


### MSG {#MSG}
```
public static final FileType MSG
```


Microsoft Outlook 電子メールメッセージ


### CAD {#CAD}
```
public static final FileType CAD
```


CAD ファイル形式


### CPP {#CPP}
```
public static final FileType CPP
```


Cベースのプログラミング言語 フォーマット


### CC {#CC}
```
public static final FileType CC
```


Cベースのプログラミング言語 フォーマット


### CXX {#CXX}
```
public static final FileType CXX
```


Cベースのプログラミング言語 フォーマット


### HXX {#HXX}
```
public static final FileType HXX
```


C++ プログラミング言語で書かれたヘッダーファイル


### HH {#HH}
```
public static final FileType HH
```


C++ ソースコードファイルが参照するヘッダー情報


### HPP {#HPP}
```
public static final FileType HPP
```


C++ プログラミング言語で書かれたヘッダーファイル


### CMAKE {#CMAKE}
```
public static final FileType CMAKE
```


ソフトウェアのビルドプロセスを管理するツール


### CS {#CS}
```
public static final FileType CS
```


CSharp プログラミング言語形式


### CSX {#CSX}
```
public static final FileType CSX
```


CSharp スクリプトファイル形式


### CAKE {#CAKE}
```
public static final FileType CAKE
```


CSharp クロスプラットフォームビルド自動化システム形式


### DIFF {#DIFF}
```
public static final FileType DIFF
```


データ比較ツール形式


### PATCH {#PATCH}
```
public static final FileType PATCH
```


差分リスト形式


### REJ {#REJ}
```
public static final FileType REJ
```


拒否されたファイル形式


### GROOVY {#GROOVY}
```
public static final FileType GROOVY
```


Groovy 形式で書かれたソースコードファイル


### GVY {#GVY}
```
public static final FileType GVY
```


Groovy 形式で書かれたソースコードファイル


### GRADLE {#GRADLE}
```
public static final FileType GRADLE
```


ビルド自動化システム形式


### HAML {#HAML}
```
public static final FileType HAML
```


簡易 HTML 生成のためのマークアップ言語


### JS {#JS}
```
public static final FileType JS
```


JavaScript プログラミング言語形式


### ES6 {#ES6}
```
public static final FileType ES6
```


JavaScript 標準化されたスクリプト言語形式


### MJS {#MJS}
```
public static final FileType MJS
```


EcmaScript (ES) モジュールファイルの拡張子


### PAC {#PAC}
```
public static final FileType PAC
```


JavaScript 関数用プロキシ自動構成ファイル


### JSON {#JSON}
```
public static final FileType JSON
```


データの保存と転送のための軽量フォーマット


### BOWERRC {#BOWERRC}
```
public static final FileType BOWERRC
```


サーバー側のパッケージ管理用設定ファイル


### JSHINTRC {#JSHINTRC}
```
public static final FileType JSHINTRC
```


JavaScript コード品質ツール


### JSCSRC {#JSCSRC}
```
public static final FileType JSCSRC
```


JavaScript 設定ファイル形式


### WEBMANIFEST {#WEBMANIFEST}
```
public static final FileType WEBMANIFEST
```


マニフェスト ファイルにはアプリに関する情報が含まれています


### JSMAP {#JSMAP}
```
public static final FileType JSMAP
```


コードを元のソースコードに戻す方法に関する情報を含む JSON ファイル


### HAR {#HAR}
```
public static final FileType HAR
```


HTTP アーカイブ形式


### JAVA {#JAVA}
```
public static final FileType JAVA
```


Java プログラミング言語形式


### LESS {#LESS}
```
public static final FileType LESS
```


動的プリプロセッサ スタイルシート言語形式


### LOG {#LOG}
```
public static final FileType LOG
```


ロギングはイベント、プロセス、メッセージ、通信のレジストリを保持します


### MAKE {#MAKE}
```
public static final FileType MAKE
```


Makefile は、make ビルド自動化ツールで使用され、ターゲット/ゴールを生成するための指示セットを含むファイルです


### MK {#MK}
```
public static final FileType MK
```


Makefile は、make ビルド自動化ツールで使用され、ターゲット/ゴールを生成するための指示セットを含むファイルです


### MD {#MD}
```
public static final FileType MD
```


Markdown 言語形式


### MKD {#MKD}
```
public static final FileType MKD
```


Markdown 言語形式


### MDWN {#MDWN}
```
public static final FileType MDWN
```


Markdown 言語形式


### MDOWN {#MDOWN}
```
public static final FileType MDOWN
```


Markdown 言語形式


### MARKDOWN {#MARKDOWN}
```
public static final FileType MARKDOWN
```


Markdown 言語形式


### MARKDN {#MARKDN}
```
public static final FileType MARKDN
```


Markdown 言語形式


### MDTXT {#MDTXT}
```
public static final FileType MDTXT
```


Markdown 言語形式


### MDTEXT {#MDTEXT}
```
public static final FileType MDTEXT
```


Markdown 言語形式


### ML {#ML}
```
public static final FileType ML
```


Caml プログラミング言語形式


### MLI {#MLI}
```
public static final FileType MLI
```


Caml プログラミング言語形式


### OBJC {#OBJC}
```
public static final FileType OBJC
```


Objective-C プログラミング言語形式


### OBJCP {#OBJCP}
```
public static final FileType OBJCP
```


Objective-C++ プログラミング言語形式


### PHP {#PHP}
```
public static final FileType PHP
```


PHP プログラミング言語形式


### PHP4 {#PHP4}
```
public static final FileType PHP4
```


PHP プログラミング言語形式


### PHP5 {#PHP5}
```
public static final FileType PHP5
```


PHP プログラミング言語形式


### PHTML {#PHTML}
```
public static final FileType PHTML
```


PHP 2 プログラムの標準ファイル拡張子形式


### CTP {#CTP}
```
public static final FileType CTP
```


CakePHP テンプレート形式


### PL {#PL}
```
public static final FileType PL
```


Perl プログラミング言語形式


### PM {#PM}
```
public static final FileType PM
```


Perl モジュール形式


### POD {#POD}
```
public static final FileType POD
```


Perl 軽量マークアップ言語形式


### T {#T}
```
public static final FileType T
```


Perl テストファイル形式


### PSGI {#PSGI}
```
public static final FileType PSGI
```


Perl プログラミングで書かれたウェブサーバーとウェブアプリケーションおよびフレームワーク間のインターフェース


### P6 {#P6}
```
public static final FileType P6
```


Perl プログラミング言語形式


### PL6 {#PL6}
```
public static final FileType PL6
```


Perl プログラミング言語形式


### PM6 {#PM6}
```
public static final FileType PM6
```


Perl モジュール形式


### NQP {#NQP}
```
public static final FileType NQP
```


Rakuto Perl 6 コンパイラを構築するために使用される中間言語


### PROP {#PROP}
```
public static final FileType PROP
```


プロパティ ファイル形式


### CFG {#CFG}
```
public static final FileType CFG
```


設定を保存するために使用される構成ファイル


### CONF {#CONF}
```
public static final FileType CONF
```


Unix および Linux ベースのシステムで使用される構成ファイル


### DIR {#DIR}
```
public static final FileType DIR
```


ディレクトリはコンピュータ上でファイルを保存する場所です


### PY {#PY}
```
public static final FileType PY
```


Python プログラミング言語形式


### RPY {#RPY}
```
public static final FileType RPY
```


ゲームを作成および実行するための Python ベースのファイルエンジン


### PYW {#PYW}
```
public static final FileType PYW
```


スクリプトの実行が必要であることを示すために Windows で使用されるファイル


### CPY {#CPY}
```
public static final FileType CPY
```


コントローラ Python スクリプト形式


### GYP {#GYP}
```
public static final FileType GYP
```


ビルド自動化ツール形式


### GYPI {#GYPI}
```
public static final FileType GYPI
```


ビルド自動化ツール形式


### PYI {#PYI}
```
public static final FileType PYI
```


Python インターフェイスファイル形式


### IPY {#IPY}
```
public static final FileType IPY
```


IPython スクリプト形式


### RST {#RST}
```
public static final FileType RST
```


軽量マークアップ言語


### RB {#RB}
```
public static final FileType RB
```


Ruby プログラミング言語形式


### ERB {#ERB}
```
public static final FileType ERB
```


Ruby プログラミング言語形式


### RJS {#RJS}
```
public static final FileType RJS
```


Ruby プログラミング言語形式


### GEMSPEC {#GEMSPEC}
```
public static final FileType GEMSPEC
```


RubyGems の属性を指定する開発者ファイル


### RAKE {#RAKE}
```
public static final FileType RAKE
```


Ruby ビルド自動化ツール


### RU {#RU}
```
public static final FileType RU
```


Rack 設定ファイル形式


### PODSPEC {#PODSPEC}
```
public static final FileType PODSPEC
```


Ruby ビルド設定形式


### RBI {#RBI}
```
public static final FileType RBI
```


Ruby インターフェイスファイル形式


### SASS {#SASS}
```
public static final FileType SASS
```


スタイルシート言語形式


### SCSS {#SCSS}
```
public static final FileType SCSS
```


スタイルシート言語形式


### SCALA {#SCALA}
```
public static final FileType SCALA
```


Scala プログラミング言語形式


### SBT {#SBT}
```
public static final FileType SBT
```


Scala 用 SBT ビルドツール形式


### SC {#SC}
```
public static final FileType SC
```


Scala ワークシート形式


### SH {#SH}
```
public static final FileType SH
```


bash 用にプログラムされたスクリプト形式


### BASH {#BASH}
```
public static final FileType BASH
```


シェルコマンドを処理するインタプリタのタイプ


### BASHRC {#BASHRC}
```
public static final FileType BASHRC
```


対話型シェルの動作を決定するファイル


### EBUILD {#EBUILD}
```
public static final FileType EBUILD
```


ソフトウェアパッケージのコンパイルとインストール手順を自動化する特殊な bash スクリプト


### SQL {#SQL}
```
public static final FileType SQL
```


構造化照会言語形式


### DSQL {#DSQL}
```
public static final FileType DSQL
```


動的構造化照会言語形式


### VIM {#VIM}
```
public static final FileType VIM
```


Vim ソースコードファイル形式


### YAML {#YAML}
```
public static final FileType YAML
```


人間が読みやすいデータシリアライズ言語フォーマット


### YML {#YML}
```
public static final FileType YML
```


人間が読みやすいデータシリアライズ言語フォーマット


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
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype)
### fromFileNameOrExtension(String value) {#fromFileNameOrExtension-java.lang.String-}
```
public static FileType fromFileNameOrExtension(String value)
```


ファイル名または拡張子に基づいて FileType を返す


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | java.lang.String | ファイル名または拡張子、null ではありません |
|

**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the file type

### getSupportedFileTypes() {#getSupportedFileTypes--}
```
public static List<FileType> getSupportedFileTypes()
```


サポートされているファイルタイプのリストを取得する


**Returns:**
java.util.List<com.groupdocs.comparison.result.FileType> - FileType のリスト

### areEquals(FileType left, FileType right) {#areEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-}
```
public static boolean areEquals(FileType left, FileType right)
```


提供されたファイルタイプの等価性をチェックする


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | left | [FileType](../../com.groupdocs.comparison.result/filetype) | 左側の [FileType](../../com.groupdocs.comparison.result/filetype) オブジェクト。 |
|
|  | right | [FileType](../../com.groupdocs.comparison.result/filetype) | 右側の [FileType](../../com.groupdocs.comparison.result/filetype) オブジェクト。 |
|

**Returns:**
boolean - 等しい場合は true、そうでない場合は false

### areNotEquals(FileType left, FileType right) {#areNotEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-}
```
public static boolean areNotEquals(FileType left, FileType right)
```


提供されたファイルタイプが等しくないかをチェックする


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | left | [FileType](../../com.groupdocs.comparison.result/filetype) | 左側の [FileType](../../com.groupdocs.comparison.result/filetype) オブジェクト。 |
|
|  | right | [FileType](../../com.groupdocs.comparison.result/filetype) | 右側の [FileType](../../com.groupdocs.comparison.result/filetype) オブジェクト。 |
|

**Returns:**
boolean - 等しくない場合は true、そうでない場合は false

### getFileFormat() {#getFileFormat--}
```
public String getFileFormat()
```


ファイルタイプのテキスト説明を取得する


**Returns:**
java.lang.String - ファイルタイプの説明

### getExtension() {#getExtension--}
```
public String getExtension()
```


ファイルタイプの拡張子を取得する


**Returns:**
java.lang.String - ファイルタイプの拡張子

### toString() {#toString--}
```
public String toString()
```


[FileType](../../com.groupdocs.comparison.result/filetype) の文字列表現を取得します、例として
'PHP プログラミング言語フォーマット (.php)'



**Returns:**
java.lang.String - 文字列表現

