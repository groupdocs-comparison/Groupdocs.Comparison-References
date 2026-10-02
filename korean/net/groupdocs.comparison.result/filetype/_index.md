---
title: "FileType"
second_title: "GroupDocs.Comparison .NET용 API 참조"
description: "파일 유형을 나타냅니다. GroupDocs.Comparison에서 지원하는 모든 파일 유형 목록을 가져오고, 확장자를 통해 파일 유형을 감지하는 등의 메서드를 제공합니다."
type: docs
weight: 480
url: /ko/net/groupdocs.comparison.result/filetype/
---
## FileType class

파일 유형을 나타냅니다. GroupDocs.Comparison에서 지원하는 모든 파일 유형 목록을 얻고, 확장자를 통해 파일 유형을 감지하는 등의 메서드를 제공합니다.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Extension](../../groupdocs.comparison.result/filetype/extension) { get; } | 파일 확장자 |
| [FileFormat](../../groupdocs.comparison.result/filetype/fileformat) { get; } | 파일 형식 |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [FromFileNameOrExtension](../../groupdocs.comparison.result/filetype/fromfilenameorextension)(string) | 파일 이름 또는 확장자를 기반으로 FileType 반환 |
| [Equals](../../groupdocs.comparison.result/filetype/equals#equals)(FileType) | 파일 유형 동등성 검사 |
| override [Equals](../../groupdocs.comparison.result/filetype/equals#equals_1)(object) | 객체와의 동등성 검사 |
| override [GetHashCode](../../groupdocs.comparison.result/filetype/gethashcode)() | 해시 코드 가져오기 |
| override [ToString](../../groupdocs.comparison.result/filetype/tostring)() | ToString |
| static [GetSupportedFileTypes](../../groupdocs.comparison.result/filetype/getsupportedfiletypes)() | 지원되는 파일 유형 열거 가져오기 |
| [operator ==](../../groupdocs.comparison.result/filetype/op_equality) | 연산자 오버로드 |
| [operator !=](../../groupdocs.comparison.result/filetype/op_inequality) | 연산자 오버로드 |

## 필드

| 이름 | 설명 |
| --- | --- |
| static readonly [AS](../../groupdocs.comparison.result/filetype/as) | ActionScript 프로그래밍 언어 형식 |
| static readonly [AS3](../../groupdocs.comparison.result/filetype/as3) | ActionScript 프로그래밍 언어 형식 |
| static readonly [ASM](../../groupdocs.comparison.result/filetype/asm) | ASM 형식 |
| static readonly [BASH](../../groupdocs.comparison.result/filetype/bash) | 셸 명령을 처리하는 인터프리터 유형 |
| static readonly [BASHRC](../../groupdocs.comparison.result/filetype/bashrc) | 파일이 대화형 셸의 동작을 결정합니다 |
| static readonly [BAT](../../groupdocs.comparison.result/filetype/bat) | DOS, OS/2 및 Microsoft Windows의 스크립트 파일 |
| static readonly [BMP](../../groupdocs.comparison.result/filetype/bmp) | 비트맵 이미지 |
| static readonly [BOWERRC](../../groupdocs.comparison.result/filetype/bowerrc) | 서버 측 패키지 제어를 위한 구성 파일 |
| static readonly [C](../../groupdocs.comparison.result/filetype/c) | C 기반 프로그래밍 언어 형식 |
| static readonly [CAD](../../groupdocs.comparison.result/filetype/cad) | CAD 파일 형식 |
| static readonly [CAKE](../../groupdocs.comparison.result/filetype/cake) | CSharp 크로스 플랫폼 빌드 자동화 시스템 형식 |
| static readonly [CC](../../groupdocs.comparison.result/filetype/cc) | C 기반 프로그래밍 언어 형식 |
| static readonly [CFG](../../groupdocs.comparison.result/filetype/cfg) | 설정을 저장하는 데 사용되는 구성 파일 |
| static readonly [CMAKE](../../groupdocs.comparison.result/filetype/cmake) | 소프트웨어 빌드 프로세스를 관리하는 도구 |
| static readonly [CMD](../../groupdocs.comparison.result/filetype/cmd) | DOS, OS/2 및 Microsoft Windows의 스크립트 파일 |
| static readonly [CONF](../../groupdocs.comparison.result/filetype/conf) | Unix 및 Linux 기반 시스템에서 사용되는 구성 파일 |
| static readonly [CPP](../../groupdocs.comparison.result/filetype/cpp) | C 기반 프로그래밍 언어 형식 |
| static readonly [CPY](../../groupdocs.comparison.result/filetype/cpy) | Controller Python 스크립트 형식 |
| static readonly [CS](../../groupdocs.comparison.result/filetype/cs) | CSharp 프로그래밍 언어 형식 |
| static readonly [CSV](../../groupdocs.comparison.result/filetype/csv) | 쉼표로 구분된 값 파일 |
| static readonly [CSX](../../groupdocs.comparison.result/filetype/csx) | CSharp 스크립트 파일 형식 |
| static readonly [CTP](../../groupdocs.comparison.result/filetype/ctp) | CakePHP 템플릿 형식 |
| static readonly [CXX](../../groupdocs.comparison.result/filetype/cxx) | C 기반 프로그래밍 언어 형식 |
| static readonly [DCM](../../groupdocs.comparison.result/filetype/dcm) | 의료용 디지털 영상 및 통신 |
| static readonly [DIFF](../../groupdocs.comparison.result/filetype/diff) | 데이터 비교 도구 형식 |
| static readonly [DIR](../../groupdocs.comparison.result/filetype/dir) | 디렉터리는 컴퓨터에서 파일을 저장하는 위치 |
| static readonly [DJVU](../../groupdocs.comparison.result/filetype/djvu) | Deja Vu 형식 |
| static readonly [DOC](../../groupdocs.comparison.result/filetype/doc) | Microsoft Word 97-2003 문서 |
| static readonly [DOCM](../../groupdocs.comparison.result/filetype/docm) | Microsoft Word 매크로 사용 문서 |
| static readonly [DOCX](../../groupdocs.comparison.result/filetype/docx) | Microsoft Word 문서 |
| static readonly [DOT](../../groupdocs.comparison.result/filetype/dot) | Microsoft Word 97-2003 템플릿 |
| static readonly [DOTM](../../groupdocs.comparison.result/filetype/dotm) | Microsoft Word 매크로 사용 템플릿 |
| static readonly [DOTX](../../groupdocs.comparison.result/filetype/dotx) | Microsoft Word 템플릿 |
| static readonly [DSQL](../../groupdocs.comparison.result/filetype/dsql) | 동적 구조화 질의 언어 형식 |
| static readonly [DWG](../../groupdocs.comparison.result/filetype/dwg) | Autodesk 디자인 데이터 형식 |
| static readonly [DXF](../../groupdocs.comparison.result/filetype/dxf) | AutoCAD 도면 교환 |
| static readonly [EBUILD](../../groupdocs.comparison.result/filetype/ebuild) | 소프트웨어 패키지의 컴파일 및 설치 절차를 자동화하는 특수 bash 스크립트 |
| static readonly [EML](../../groupdocs.comparison.result/filetype/eml) | 이메일 메시지 |
| static readonly [EMLX](../../groupdocs.comparison.result/filetype/emlx) | Apple Mail 이메일 파일 |
| static readonly [ERB](../../groupdocs.comparison.result/filetype/erb) | Ruby 프로그래밍 언어 형식 |
| static readonly [ES6](../../groupdocs.comparison.result/filetype/es6) | JavaScript 표준화된 스크립팅 언어 형식 |
| static readonly [GEMSPEC](../../groupdocs.comparison.result/filetype/gemspec) | RubyGems의 속성을 지정하는 개발자 파일 |
| static readonly [GIF](../../groupdocs.comparison.result/filetype/gif) | 그래픽 교환 형식 |
| static readonly [GRADLE](../../groupdocs.comparison.result/filetype/gradle) | 빌드 자동화 시스템 형식 |
| static readonly [GROOVY](../../groupdocs.comparison.result/filetype/groovy) | Groovy 형식으로 작성된 소스 코드 파일 |
| static readonly [GVY](../../groupdocs.comparison.result/filetype/gvy) | Groovy 형식으로 작성된 소스 코드 파일 |
| static readonly [GYP](../../groupdocs.comparison.result/filetype/gyp) | 빌드 자동화 도구 형식 |
| static readonly [GYPI](../../groupdocs.comparison.result/filetype/gypi) | 빌드 자동화 도구 형식 |
| static readonly [H](../../groupdocs.comparison.result/filetype/h) | C 기반 헤더 파일은 함수와 변수의 정의를 포함합니다 |
| static readonly [HAML](../../groupdocs.comparison.result/filetype/haml) | 단순화된 HTML 생성을 위한 마크업 언어 |
| static readonly [HAR](../../groupdocs.comparison.result/filetype/har) | HTTP 아카이브 형식 |
| static readonly [HH](../../groupdocs.comparison.result/filetype/hh) | C++ 소스 코드 파일이 참조하는 헤더 정보 |
| static readonly [HPP](../../groupdocs.comparison.result/filetype/hpp) | C++ 프로그래밍 언어로 작성된 헤더 파일 |
| static readonly [HTML](../../groupdocs.comparison.result/filetype/html) | 하이퍼텍스트 마크업 언어 |
| static readonly [HXX](../../groupdocs.comparison.result/filetype/hxx) | C++ 프로그래밍 언어로 작성된 헤더 파일 |
| static readonly [IPY](../../groupdocs.comparison.result/filetype/ipy) | IPython 스크립트 형식 |
| static readonly [JAVA](../../groupdocs.comparison.result/filetype/java) | Java 프로그래밍 언어 형식 |
| static readonly [JPEG](../../groupdocs.comparison.result/filetype/jpeg) | Joint Photographic Experts Group |
| static readonly [JS](../../groupdocs.comparison.result/filetype/js) | JavaScript 프로그래밍 언어 형식 |
| static readonly [JSCSRC](../../groupdocs.comparison.result/filetype/jscsrc) | JavaScript 구성 파일 형식 |
| static readonly [JSHINTRC](../../groupdocs.comparison.result/filetype/jshintrc) | JavaScript 코드 품질 도구 |
| static readonly [JSMAP](../../groupdocs.comparison.result/filetype/jsmap) | 코드를 원본 코드로 되돌리는 방법에 대한 정보를 포함하는 JSON 파일 |
| static readonly [JSON](../../groupdocs.comparison.result/filetype/json) | 데이터 저장 및 전송을 위한 경량 형식 |
| static readonly [LESS](../../groupdocs.comparison.result/filetype/less) | 동적 전처리기 스타일 시트 언어 형식 |
| static readonly [LOG](../../groupdocs.comparison.result/filetype/log) | 로깅은 이벤트, 프로세스, 메시지 및 통신의 레지스트리를 유지합니다 |
| static readonly [MAKE](../../groupdocs.comparison.result/filetype/make) | Makefile은 목표/목적을 생성하기 위해 make 빌드 자동화 도구에서 사용하는 일련의 지시문을 포함하는 파일입니다 |
| static readonly [MARKDN](../../groupdocs.comparison.result/filetype/markdn) | Markdown 언어 형식 |
| static readonly [MARKDOWN](../../groupdocs.comparison.result/filetype/markdown) | Markdown 언어 형식 |
| static readonly [MD](../../groupdocs.comparison.result/filetype/md) | Markdown 언어 형식 |
| static readonly [MDOWN](../../groupdocs.comparison.result/filetype/mdown) | Markdown 언어 형식 |
| static readonly [MDTEXT](../../groupdocs.comparison.result/filetype/mdtext) | Markdown 언어 형식 |
| static readonly [MDTXT](../../groupdocs.comparison.result/filetype/mdtxt) | Markdown 언어 형식 |
| static readonly [MDWN](../../groupdocs.comparison.result/filetype/mdwn) | Markdown 언어 형식 |
| static readonly [MHTML](../../groupdocs.comparison.result/filetype/mhtml) | Mime HTML |
| static readonly [MJS](../../groupdocs.comparison.result/filetype/mjs) | EcmaScript (ES) 모듈 파일용 확장자 |
| static readonly [MK](../../groupdocs.comparison.result/filetype/mk) | Makefile은 목표/목적을 생성하기 위해 make 빌드 자동화 도구에서 사용하는 일련의 지시문을 포함하는 파일입니다 |
| static readonly [MKD](../../groupdocs.comparison.result/filetype/mkd) | Markdown 언어 형식 |
| static readonly [ML](../../groupdocs.comparison.result/filetype/ml) | Caml 프로그래밍 언어 형식 |
| static readonly [MLI](../../groupdocs.comparison.result/filetype/mli) | Caml 프로그래밍 언어 형식 |
| static readonly [MOBI](../../groupdocs.comparison.result/filetype/mobi) | Mobipocket 전자책 형식 |
| static readonly [MSG](../../groupdocs.comparison.result/filetype/msg) | Microsoft Outlook 이메일 메시지 |
| static readonly [NQP](../../groupdocs.comparison.result/filetype/nqp) | Rakudo Perl 6 컴파일러를 빌드하는 데 사용되는 중간 언어 |
| static readonly [OBJC](../../groupdocs.comparison.result/filetype/objc) | Objective-C 프로그래밍 언어 형식 |
| static readonly [OBJCP](../../groupdocs.comparison.result/filetype/objcp) | Objective-C++ 프로그래밍 언어 형식 |
| static readonly [ODP](../../groupdocs.comparison.result/filetype/odp) | OpenDocument 프레젠테이션 |
| static readonly [ODS](../../groupdocs.comparison.result/filetype/ods) | OpenDocument 스프레드시트 |
| static readonly [ODT](../../groupdocs.comparison.result/filetype/odt) | OpenDocument 텍스트 |
| static readonly [ONE](../../groupdocs.comparison.result/filetype/one) | Microsoft OneNote 문서 |
| static readonly [OTP](../../groupdocs.comparison.result/filetype/otp) | OpenDocument 프레젠테이션 템플릿 |
| static readonly [OTT](../../groupdocs.comparison.result/filetype/ott) | OpenDocument 텍스트 템플릿 |
| static readonly [P6](../../groupdocs.comparison.result/filetype/p6) | Perl 프로그래밍 언어 형식 |
| static readonly [PAC](../../groupdocs.comparison.result/filetype/pac) | Proxy Auto-Configuration 파일 JavaScript 함수용 형식 |
| static readonly [PATCH](../../groupdocs.comparison.result/filetype/patch) | 차이점 목록 형식 |
| static readonly [PDF](../../groupdocs.comparison.result/filetype/pdf) | Adobe Portable Document 형식 |
| static readonly [PHP](../../groupdocs.comparison.result/filetype/php) | PHP 프로그래밍 언어 형식 |
| static readonly [PHP4](../../groupdocs.comparison.result/filetype/php4) | PHP 프로그래밍 언어 형식 |
| static readonly [PHP5](../../groupdocs.comparison.result/filetype/php5) | PHP 프로그래밍 언어 형식 |
| static readonly [PHTML](../../groupdocs.comparison.result/filetype/phtml) | PHP 2 프로그램용 표준 파일 확장자 형식 |
| static readonly [PL](../../groupdocs.comparison.result/filetype/pl) | Perl 프로그래밍 언어 형식 |
| static readonly [PL6](../../groupdocs.comparison.result/filetype/pl6) | Perl 프로그래밍 언어 형식 |
| static readonly [PM](../../groupdocs.comparison.result/filetype/pm) | Perl 모듈 형식 |
| static readonly [PM6](../../groupdocs.comparison.result/filetype/pm6) | Perl 모듈 형식 |
| static readonly [PNG](../../groupdocs.comparison.result/filetype/png) | Portable Network Graphics |
| static readonly [POD](../../groupdocs.comparison.result/filetype/pod) | Perl 경량 마크업 언어 형식 |
| static readonly [PODSPEC](../../groupdocs.comparison.result/filetype/podspec) | Ruby 빌드 설정 형식 |
| static readonly [POT](../../groupdocs.comparison.result/filetype/pot) | Microsoft PowerPoint 템플릿 |
| static readonly [POTX](../../groupdocs.comparison.result/filetype/potx) | Microsoft PowerPoint 템플릿 |
| static readonly [PPS](../../groupdocs.comparison.result/filetype/pps) | Microsoft PowerPoint 97-2003 슬라이드 쇼 |
| static readonly [PPSX](../../groupdocs.comparison.result/filetype/ppsx) | Microsoft PowerPoint 슬라이드 쇼 |
| static readonly [PPT](../../groupdocs.comparison.result/filetype/ppt) | Microsoft PowerPoint 97-2003 프레젠테이션 |
| static readonly [PPTX](../../groupdocs.comparison.result/filetype/pptx) | Microsoft PowerPoint 프레젠테이션 |
| static readonly [PROP](../../groupdocs.comparison.result/filetype/prop) | Properties 파일 형식 |
| static readonly [PSGI](../../groupdocs.comparison.result/filetype/psgi) | Perl 프로그래밍으로 작성된 웹 서버와 웹 애플리케이션 및 프레임워크 간 인터페이스 |
| static readonly [PY](../../groupdocs.comparison.result/filetype/py) | Python 프로그래밍 언어 형식 |
| static readonly [PYI](../../groupdocs.comparison.result/filetype/pyi) | Python 인터페이스 파일 형식 |
| static readonly [PYW](../../groupdocs.comparison.result/filetype/pyw) | Windows에서 스크립트를 실행해야 함을 나타내는 파일 |
| static readonly [RAKE](../../groupdocs.comparison.result/filetype/rake) | Ruby 빌드 자동화 도구 |
| static readonly [RB](../../groupdocs.comparison.result/filetype/rb) | Ruby 프로그래밍 언어 형식 |
| static readonly [RBI](../../groupdocs.comparison.result/filetype/rbi) | Ruby 인터페이스 파일 형식 |
| static readonly [REJ](../../groupdocs.comparison.result/filetype/rej) | 거부된 파일 형식 |
| static readonly [RJS](../../groupdocs.comparison.result/filetype/rjs) | Ruby 프로그래밍 언어 형식 |
| static readonly [RPY](../../groupdocs.comparison.result/filetype/rpy) | 게임을 만들고 실행하기 위한 Python 기반 파일 엔진 |
| static readonly [RST](../../groupdocs.comparison.result/filetype/rst) | 경량 마크업 언어 |
| static readonly [RTF](../../groupdocs.comparison.result/filetype/rtf) | 리치 텍스트 문서 |
| static readonly [RU](../../groupdocs.comparison.result/filetype/ru) | Rack 구성 파일 형식 |
| static readonly [SASS](../../groupdocs.comparison.result/filetype/sass) | 스타일 시트 언어 형식 |
| static readonly [SBT](../../groupdocs.comparison.result/filetype/sbt) | Scala용 SBT 빌드 도구 형식 |
| static readonly [SC](../../groupdocs.comparison.result/filetype/sc) | Scala 워크시트 형식 |
| static readonly [SCALA](../../groupdocs.comparison.result/filetype/scala) | Scala 프로그래밍 언어 형식 |
| static readonly [SCSS](../../groupdocs.comparison.result/filetype/scss) | 스타일 시트 언어 형식 |
| static readonly [SH](../../groupdocs.comparison.result/filetype/sh) | bash용으로 프로그래밍된 스크립트 형식 |
| static readonly [SQL](../../groupdocs.comparison.result/filetype/sql) | 구조적 질의 언어 형식 |
| static readonly [SVG](../../groupdocs.comparison.result/filetype/svg) | Scalar 벡터 그래픽스 |
| static readonly [T](../../groupdocs.comparison.result/filetype/t) | Perl 테스트 파일 형식 |
| static readonly [TXT](../../groupdocs.comparison.result/filetype/txt) | 평문 텍스트 문서 |
| static readonly [UNKNOWN](../../groupdocs.comparison.result/filetype/unknown) | 알 수 없는 유형 |
| static readonly [VDX](../../groupdocs.comparison.result/filetype/vdx) | Microsoft Visio 2003-2010 XML 도면 |
| static readonly [VIM](../../groupdocs.comparison.result/filetype/vim) | Vim 소스 코드 파일 형식 |
| static readonly [VSD](../../groupdocs.comparison.result/filetype/vsd) | Microsoft Visio 2003-2010 도면 |
| static readonly [VSDX](../../groupdocs.comparison.result/filetype/vsdx) | Microsoft Visio 도면 |
| static readonly [VSS](../../groupdocs.comparison.result/filetype/vss) | Microsoft Visio 2003-2010 스텐실 |
| static readonly [VST](../../groupdocs.comparison.result/filetype/vst) | Microsoft Visio 2003-2010 템플릿 |
| static readonly [WEBMANIFEST](../../groupdocs.comparison.result/filetype/webmanifest) | 매니페스트 파일은 앱에 대한 정보를 포함합니다 |
| static readonly [XLS](../../groupdocs.comparison.result/filetype/xls) | Microsoft Excel 97-2003 워크시트 |
| static readonly [XLSB](../../groupdocs.comparison.result/filetype/xlsb) | Microsoft Excel 바이너리 워크시트 |
| static readonly [XLSM](../../groupdocs.comparison.result/filetype/xlsm) | Microsoft Excel 매크로 사용 워크시트 |
| static readonly [XLSX](../../groupdocs.comparison.result/filetype/xlsx) | Microsoft Excel 워크시트 |
| static readonly [XLT](../../groupdocs.comparison.result/filetype/xlt) | Microsoft Excel 템플릿 |
| static readonly [XLTM](../../groupdocs.comparison.result/filetype/xltm) | Microsoft Excel 매크로 사용 템플릿 |
| static readonly [YAML](../../groupdocs.comparison.result/filetype/yaml) | 인간이 읽을 수 있는 데이터 직렬화 언어 형식 |
| static readonly [YML](../../groupdocs.comparison.result/filetype/yml) | 인간이 읽을 수 있는 데이터 직렬화 언어 형식 |

### 비고

**Learn more**

* Learn more about file formats supported by GroupDocs.Comparison: [Full list of supported document formats](https://docs.groupdocs.com/display/comparisonnet/Supported+Document+Formats)
* Learn more about getting supported file types in C#: [How to get supported file formats in C#](https://docs.groupdocs.com/display/comparisonnet/Get+supported+file+formats)

### 또 보기

* namespace [GroupDocs.Comparison.Result](../../groupdocs.comparison.result)
* assembly [GroupDocs.Comparison](../../)

<!-- 수정 금지: xmldocmd에 의해 GroupDocs.Comparison.dll용으로 생성됨 -->
