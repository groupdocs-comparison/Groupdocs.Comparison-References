---
title: "FileType"
second_title: "GroupDocs.Comparison for .NET API リファレンス"
description: "ファイルタイプを表します。GroupDocs.Comparison がサポートするすべてのファイルタイプのリスト取得や、拡張子によるファイルタイプの検出などのメソッドを提供します。"
type: docs
weight: 480
url: /ja/net/groupdocs.comparison.result/filetype/
---
## FileType class

ファイルタイプを表します。GroupDocs.Comparison がサポートするすべてのファイルタイプの一覧を取得したり、拡張子からファイルタイプを検出したりするメソッドを提供します。

```csharp
public sealed class FileType : IEquatable<FileType>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Extension](../../groupdocs.comparison.result/filetype/extension) { get; } | ファイル拡張子 |
| [FileFormat](../../groupdocs.comparison.result/filetype/fileformat) { get; } | ファイル形式 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [FromFileNameOrExtension](../../groupdocs.comparison.result/filetype/fromfilenameorextension)(string) | ファイル名または拡張子に基づいて FileType を返す |
| [Equals](../../groupdocs.comparison.result/filetype/equals#equals)(FileType) | ファイルタイプの等価性チェック |
| override [Equals](../../groupdocs.comparison.result/filetype/equals#equals_1)(object) | オブジェクトとの等価性チェック |
| override [GetHashCode](../../groupdocs.comparison.result/filetype/gethashcode)() | ハッシュコードを取得 |
| override [ToString](../../groupdocs.comparison.result/filetype/tostring)() | ToString |
| static [GetSupportedFileTypes](../../groupdocs.comparison.result/filetype/getsupportedfiletypes)() | サポートされているファイルタイプの列挙を取得 |
| [operator ==](../../groupdocs.comparison.result/filetype/op_equality) | 演算子オーバーロード |
| [operator !=](../../groupdocs.comparison.result/filetype/op_inequality) | 演算子オーバーロード |

## フィールド

| 名前 | 説明 |
| --- | --- |
| static readonly [AS](../../groupdocs.comparison.result/filetype/as) | ActionScript プログラミング言語のフォーマット |
| static readonly [AS3](../../groupdocs.comparison.result/filetype/as3) | ActionScript プログラミング言語のフォーマット |
| static readonly [ASM](../../groupdocs.comparison.result/filetype/asm) | ASM フォーマット |
| static readonly [BASH](../../groupdocs.comparison.result/filetype/bash) | シェルコマンドを処理するインタプリタのタイプ |
| static readonly [BASHRC](../../groupdocs.comparison.result/filetype/bashrc) | ファイルは対話型シェルの動作を決定します |
| static readonly [BAT](../../groupdocs.comparison.result/filetype/bat) | DOS、OS/2、Microsoft Windows のスクリプトファイル |
| static readonly [BMP](../../groupdocs.comparison.result/filetype/bmp) | ビットマップ画像 |
| static readonly [BOWERRC](../../groupdocs.comparison.result/filetype/bowerrc) | サーバー側のパッケージ管理用設定ファイル |
| static readonly [C](../../groupdocs.comparison.result/filetype/c) | Cベースのプログラミング言語のフォーマット |
| static readonly [CAD](../../groupdocs.comparison.result/filetype/cad) | CAD ファイルフォーマット |
| static readonly [CAKE](../../groupdocs.comparison.result/filetype/cake) | CSharp クロスプラットフォームビルド自動化システムのフォーマット |
| static readonly [CC](../../groupdocs.comparison.result/filetype/cc) | Cベースのプログラミング言語のフォーマット |
| static readonly [CFG](../../groupdocs.comparison.result/filetype/cfg) | 設定を保存するための設定ファイル |
| static readonly [CMAKE](../../groupdocs.comparison.result/filetype/cmake) | ソフトウェアのビルドプロセスを管理するツール |
| static readonly [CMD](../../groupdocs.comparison.result/filetype/cmd) | DOS、OS/2、Microsoft Windows のスクリプトファイル |
| static readonly [CONF](../../groupdocs.comparison.result/filetype/conf) | Unix および Linux 系統のシステムで使用される設定ファイル |
| static readonly [CPP](../../groupdocs.comparison.result/filetype/cpp) | Cベースのプログラミング言語のフォーマット |
| static readonly [CPY](../../groupdocs.comparison.result/filetype/cpy) | Controller Python スクリプトフォーマット |
| static readonly [CS](../../groupdocs.comparison.result/filetype/cs) | CSharp プログラミング言語のフォーマット |
| static readonly [CSV](../../groupdocs.comparison.result/filetype/csv) | カンマ区切り値ファイル |
| static readonly [CSX](../../groupdocs.comparison.result/filetype/csx) | CSharp スクリプトファイルフォーマット |
| static readonly [CTP](../../groupdocs.comparison.result/filetype/ctp) | CakePHP テンプレート形式 |
| static readonly [CXX](../../groupdocs.comparison.result/filetype/cxx) | Cベースのプログラミング言語のフォーマット |
| static readonly [DCM](../../groupdocs.comparison.result/filetype/dcm) | 医療用デジタル画像通信 |
| static readonly [DIFF](../../groupdocs.comparison.result/filetype/diff) | データ比較ツール形式 |
| static readonly [DIR](../../groupdocs.comparison.result/filetype/dir) | ディレクトリはコンピュータ上でファイルを保存する場所です |
| static readonly [DJVU](../../groupdocs.comparison.result/filetype/djvu) | Deja Vu 形式 |
| static readonly [DOC](../../groupdocs.comparison.result/filetype/doc) | Microsoft Word 97-2003 ドキュメント |
| static readonly [DOCM](../../groupdocs.comparison.result/filetype/docm) | Microsoft Word マクロ有効ドキュメント |
| static readonly [DOCX](../../groupdocs.comparison.result/filetype/docx) | Microsoft Word ドキュメント |
| static readonly [DOT](../../groupdocs.comparison.result/filetype/dot) | Microsoft Word 97-2003 テンプレート |
| static readonly [DOTM](../../groupdocs.comparison.result/filetype/dotm) | Microsoft Word マクロ有効テンプレート |
| static readonly [DOTX](../../groupdocs.comparison.result/filetype/dotx) | Microsoft Word テンプレート |
| static readonly [DSQL](../../groupdocs.comparison.result/filetype/dsql) | 動的構造化クエリ言語形式 |
| static readonly [DWG](../../groupdocs.comparison.result/filetype/dwg) | Autodesk デザインデータ形式 |
| static readonly [DXF](../../groupdocs.comparison.result/filetype/dxf) | AutoCAD 図面交換 |
| static readonly [EBUILD](../../groupdocs.comparison.result/filetype/ebuild) | ソフトウェアパッケージのコンパイルとインストール手順を自動化する特殊な bash スクリプト |
| static readonly [EML](../../groupdocs.comparison.result/filetype/eml) | 電子メールメッセージ |
| static readonly [EMLX](../../groupdocs.comparison.result/filetype/emlx) | Apple Mail 電子メールファイル |
| static readonly [ERB](../../groupdocs.comparison.result/filetype/erb) | Ruby プログラミング言語形式 |
| static readonly [ES6](../../groupdocs.comparison.result/filetype/es6) | JavaScript 標準化スクリプト言語形式 |
| static readonly [GEMSPEC](../../groupdocs.comparison.result/filetype/gemspec) | RubyGems の属性を指定する開発者ファイル |
| static readonly [GIF](../../groupdocs.comparison.result/filetype/gif) | Graphics Interchange Format |
| static readonly [GRADLE](../../groupdocs.comparison.result/filetype/gradle) | ビルド自動化システム形式 |
| static readonly [GROOVY](../../groupdocs.comparison.result/filetype/groovy) | Groovy 形式で書かれたソースコードファイル |
| static readonly [GVY](../../groupdocs.comparison.result/filetype/gvy) | Groovy 形式で書かれたソースコードファイル |
| static readonly [GYP](../../groupdocs.comparison.result/filetype/gyp) | ビルド自動化ツール形式 |
| static readonly [GYPI](../../groupdocs.comparison.result/filetype/gypi) | ビルド自動化ツール形式 |
| static readonly [H](../../groupdocs.comparison.result/filetype/h) | C ベースのヘッダーファイルは関数と変数の定義を含みます |
| static readonly [HAML](../../groupdocs.comparison.result/filetype/haml) | 簡易HTML生成のためのマークアップ言語 |
| static readonly [HAR](../../groupdocs.comparison.result/filetype/har) | HTTPアーカイブ形式 |
| static readonly [HH](../../groupdocs.comparison.result/filetype/hh) | C++ソースコードファイルが参照するヘッダー情報 |
| static readonly [HPP](../../groupdocs.comparison.result/filetype/hpp) | C++プログラミング言語で書かれたヘッダーファイル |
| static readonly [HTML](../../groupdocs.comparison.result/filetype/html) | ハイパーテキストマークアップ言語 |
| static readonly [HXX](../../groupdocs.comparison.result/filetype/hxx) | C++プログラミング言語で書かれたヘッダーファイル |
| static readonly [IPY](../../groupdocs.comparison.result/filetype/ipy) | IPythonスクリプト形式 |
| static readonly [JAVA](../../groupdocs.comparison.result/filetype/java) | Javaプログラミング言語形式 |
| static readonly [JPEG](../../groupdocs.comparison.result/filetype/jpeg) | Joint Photographic Experts Group |
| static readonly [JS](../../groupdocs.comparison.result/filetype/js) | JavaScriptプログラミング言語形式 |
| static readonly [JSCSRC](../../groupdocs.comparison.result/filetype/jscsrc) | JavaScript構成ファイル形式 |
| static readonly [JSHINTRC](../../groupdocs.comparison.result/filetype/jshintrc) | JavaScriptコード品質ツール |
| static readonly [JSMAP](../../groupdocs.comparison.result/filetype/jsmap) | コードを元のソースコードに戻す方法に関する情報を含むJSONファイル |
| static readonly [JSON](../../groupdocs.comparison.result/filetype/json) | データの保存と転送のための軽量フォーマット |
| static readonly [LESS](../../groupdocs.comparison.result/filetype/less) | 動的プリプロセッサスタイルシート言語形式 |
| static readonly [LOG](../../groupdocs.comparison.result/filetype/log) | ロギングはイベント、プロセス、メッセージ、通信のレジストリを保持します |
| static readonly [MAKE](../../groupdocs.comparison.result/filetype/make) | Makefileは、makeビルド自動化ツールで使用され、ターゲット/ゴールを生成するための指示セットを含むファイルです |
| static readonly [MARKDN](../../groupdocs.comparison.result/filetype/markdn) | Markdown言語形式 |
| static readonly [MARKDOWN](../../groupdocs.comparison.result/filetype/markdown) | Markdown言語形式 |
| static readonly [MD](../../groupdocs.comparison.result/filetype/md) | Markdown言語形式 |
| static readonly [MDOWN](../../groupdocs.comparison.result/filetype/mdown) | Markdown言語形式 |
| static readonly [MDTEXT](../../groupdocs.comparison.result/filetype/mdtext) | Markdown言語形式 |
| static readonly [MDTXT](../../groupdocs.comparison.result/filetype/mdtxt) | Markdown言語形式 |
| static readonly [MDWN](../../groupdocs.comparison.result/filetype/mdwn) | Markdown言語形式 |
| static readonly [MHTML](../../groupdocs.comparison.result/filetype/mhtml) | MIME HTML |
| static readonly [MJS](../../groupdocs.comparison.result/filetype/mjs) | EcmaScript（ES）モジュールファイルの拡張子 |
| static readonly [MK](../../groupdocs.comparison.result/filetype/mk) | Makefileは、makeビルド自動化ツールで使用され、ターゲット/ゴールを生成するための指示セットを含むファイルです |
| static readonly [MKD](../../groupdocs.comparison.result/filetype/mkd) | Markdown言語形式 |
| static readonly [ML](../../groupdocs.comparison.result/filetype/ml) | Camlプログラミング言語形式 |
| static readonly [MLI](../../groupdocs.comparison.result/filetype/mli) | Camlプログラミング言語形式 |
| static readonly [MOBI](../../groupdocs.comparison.result/filetype/mobi) | Mobipocket電子書籍フォーマット |
| static readonly [MSG](../../groupdocs.comparison.result/filetype/msg) | Microsoft Outlookメールメッセージ |
| static readonly [NQP](../../groupdocs.comparison.result/filetype/nqp) | Rakuto Perl 6コンパイラを構築するために使用される中間言語 |
| static readonly [OBJC](../../groupdocs.comparison.result/filetype/objc) | Objective-Cプログラミング言語形式 |
| static readonly [OBJCP](../../groupdocs.comparison.result/filetype/objcp) | Objective-C++プログラミング言語形式 |
| static readonly [ODP](../../groupdocs.comparison.result/filetype/odp) | OpenDocument プレゼンテーション |
| static readonly [ODS](../../groupdocs.comparison.result/filetype/ods) | OpenDocument スプレッドシート |
| static readonly [ODT](../../groupdocs.comparison.result/filetype/odt) | OpenDocument テキスト |
| static readonly [ONE](../../groupdocs.comparison.result/filetype/one) | Microsoft OneNote ドキュメント |
| static readonly [OTP](../../groupdocs.comparison.result/filetype/otp) | OpenDocument プレゼンテーション テンプレート |
| static readonly [OTT](../../groupdocs.comparison.result/filetype/ott) | OpenDocument テキスト テンプレート |
| static readonly [P6](../../groupdocs.comparison.result/filetype/p6) | Perl プログラミング言語 フォーマット |
| static readonly [PAC](../../groupdocs.comparison.result/filetype/pac) | Proxy Auto-Configuration ファイル（JavaScript 関数用）フォーマット |
| static readonly [PATCH](../../groupdocs.comparison.result/filetype/patch) | 差分リスト フォーマット |
| static readonly [PDF](../../groupdocs.comparison.result/filetype/pdf) | Adobe Portable Document フォーマット |
| static readonly [PHP](../../groupdocs.comparison.result/filetype/php) | PHP プログラミング言語 フォーマット |
| static readonly [PHP4](../../groupdocs.comparison.result/filetype/php4) | PHP プログラミング言語 フォーマット |
| static readonly [PHP5](../../groupdocs.comparison.result/filetype/php5) | PHP プログラミング言語 フォーマット |
| static readonly [PHTML](../../groupdocs.comparison.result/filetype/phtml) | PHP 2 プログラム用 標準ファイル拡張子 フォーマット |
| static readonly [PL](../../groupdocs.comparison.result/filetype/pl) | Perl プログラミング言語 フォーマット |
| static readonly [PL6](../../groupdocs.comparison.result/filetype/pl6) | Perl プログラミング言語 フォーマット |
| static readonly [PM](../../groupdocs.comparison.result/filetype/pm) | Perl モジュール フォーマット |
| static readonly [PM6](../../groupdocs.comparison.result/filetype/pm6) | Perl モジュール フォーマット |
| static readonly [PNG](../../groupdocs.comparison.result/filetype/png) | Portable Network Graphics |
| static readonly [POD](../../groupdocs.comparison.result/filetype/pod) | Perl 軽量マークアップ言語 フォーマット |
| static readonly [PODSPEC](../../groupdocs.comparison.result/filetype/podspec) | Ruby ビルド設定 フォーマット |
| static readonly [POT](../../groupdocs.comparison.result/filetype/pot) | Microsoft PowerPoint テンプレート |
| static readonly [POTX](../../groupdocs.comparison.result/filetype/potx) | Microsoft PowerPoint テンプレート |
| static readonly [PPS](../../groupdocs.comparison.result/filetype/pps) | Microsoft PowerPoint 97-2003 スライドショー |
| static readonly [PPSX](../../groupdocs.comparison.result/filetype/ppsx) | Microsoft PowerPoint スライドショー |
| static readonly [PPT](../../groupdocs.comparison.result/filetype/ppt) | Microsoft PowerPoint 97-2003 プレゼンテーション |
| static readonly [PPTX](../../groupdocs.comparison.result/filetype/pptx) | Microsoft PowerPoint プレゼンテーション |
| static readonly [PROP](../../groupdocs.comparison.result/filetype/prop) | プロパティ ファイル フォーマット |
| static readonly [PSGI](../../groupdocs.comparison.result/filetype/psgi) | Perl プログラミングで書かれたウェブサーバーとウェブアプリケーションおよびフレームワーク間のインターフェース |
| static readonly [PY](../../groupdocs.comparison.result/filetype/py) | Python プログラミング言語 フォーマット |
| static readonly [PYI](../../groupdocs.comparison.result/filetype/pyi) | Python インターフェイス ファイル形式 |
| static readonly [PYW](../../groupdocs.comparison.result/filetype/pyw) | Windows でスクリプトの実行が必要であることを示すために使用されるファイル |
| static readonly [RAKE](../../groupdocs.comparison.result/filetype/rake) | Ruby ビルド自動化ツール |
| static readonly [RB](../../groupdocs.comparison.result/filetype/rb) | Ruby プログラミング言語形式 |
| static readonly [RBI](../../groupdocs.comparison.result/filetype/rbi) | Ruby インターフェイス ファイル形式 |
| static readonly [REJ](../../groupdocs.comparison.result/filetype/rej) | 拒否されたファイル形式 |
| static readonly [RJS](../../groupdocs.comparison.result/filetype/rjs) | Ruby プログラミング言語形式 |
| static readonly [RPY](../../groupdocs.comparison.result/filetype/rpy) | ゲームの作成と実行のための Python ベースのファイルエンジン |
| static readonly [RST](../../groupdocs.comparison.result/filetype/rst) | 軽量マークアップ言語 |
| static readonly [RTF](../../groupdocs.comparison.result/filetype/rtf) | リッチテキスト ドキュメント |
| static readonly [RU](../../groupdocs.comparison.result/filetype/ru) | Rack 設定ファイル形式 |
| static readonly [SASS](../../groupdocs.comparison.result/filetype/sass) | スタイルシート言語形式 |
| static readonly [SBT](../../groupdocs.comparison.result/filetype/sbt) | Scala 用 SBT ビルドツール形式 |
| static readonly [SC](../../groupdocs.comparison.result/filetype/sc) | Scala ワークシート形式 |
| static readonly [SCALA](../../groupdocs.comparison.result/filetype/scala) | Scala プログラミング言語形式 |
| static readonly [SCSS](../../groupdocs.comparison.result/filetype/scss) | スタイルシート言語形式 |
| static readonly [SH](../../groupdocs.comparison.result/filetype/sh) | bash 用にプログラムされたスクリプト形式 |
| static readonly [SQL](../../groupdocs.comparison.result/filetype/sql) | 構造化問い合わせ言語形式 |
| static readonly [SVG](../../groupdocs.comparison.result/filetype/svg) | スカラー ベクトル グラフィックス |
| static readonly [T](../../groupdocs.comparison.result/filetype/t) | Perl テストファイル形式 |
| static readonly [TXT](../../groupdocs.comparison.result/filetype/txt) | プレーンテキスト ドキュメント |
| static readonly [UNKNOWN](../../groupdocs.comparison.result/filetype/unknown) | 不明なタイプ |
| static readonly [VDX](../../groupdocs.comparison.result/filetype/vdx) | Microsoft Visio 2003-2010 XML 図面 |
| static readonly [VIM](../../groupdocs.comparison.result/filetype/vim) | Vim ソースコードファイル形式 |
| static readonly [VSD](../../groupdocs.comparison.result/filetype/vsd) | Microsoft Visio 2003-2010 図面 |
| static readonly [VSDX](../../groupdocs.comparison.result/filetype/vsdx) | Microsoft Visio 図面 |
| static readonly [VSS](../../groupdocs.comparison.result/filetype/vss) | Microsoft Visio 2003-2010 ステンシル |
| static readonly [VST](../../groupdocs.comparison.result/filetype/vst) | Microsoft Visio 2003-2010 テンプレート |
| static readonly [WEBMANIFEST](../../groupdocs.comparison.result/filetype/webmanifest) | マニフェスト ファイルにはアプリに関する情報が含まれています |
| static readonly [XLS](../../groupdocs.comparison.result/filetype/xls) | Microsoft Excel 97-2003 ワークシート |
| static readonly [XLSB](../../groupdocs.comparison.result/filetype/xlsb) | Microsoft Excel バイナリ ワークシート |
| static readonly [XLSM](../../groupdocs.comparison.result/filetype/xlsm) | Microsoft Excel マクロ有効ワークシート |
| static readonly [XLSX](../../groupdocs.comparison.result/filetype/xlsx) | Microsoft Excel ワークシート |
| static readonly [XLT](../../groupdocs.comparison.result/filetype/xlt) | Microsoft Excel テンプレート |
| static readonly [XLTM](../../groupdocs.comparison.result/filetype/xltm) | Microsoft Excel マクロ有効テンプレート |
| static readonly [YAML](../../groupdocs.comparison.result/filetype/yaml) | 人間が読みやすいデータシリアライズ言語フォーマット |
| static readonly [YML](../../groupdocs.comparison.result/filetype/yml) | 人間が読みやすいデータシリアライズ言語フォーマット |

### 備考

**Learn more**

* Learn more about file formats supported by GroupDocs.Comparison: [Full list of supported document formats](https://docs.groupdocs.com/display/comparisonnet/Supported+Document+Formats)
* Learn more about getting supported file types in C#: [How to get supported file formats in C#](https://docs.groupdocs.com/display/comparisonnet/Get+supported+file+formats)

### 関連項目

* namespace [GroupDocs.Comparison.Result](../../groupdocs.comparison.result)
* assembly [GroupDocs.Comparison](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Comparison.dll 用に生成されました -->
