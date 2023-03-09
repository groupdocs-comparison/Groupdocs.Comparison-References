---
title: FileType
second_title: .NET API 참조용 GroupDocs.Comparison
description: 파일 형식을 나타냅니다. GroupDocs.Comparison에서 지원하는 모든 파일 유형 목록을 가져오고 확장자 등으로 파일 유형을 감지하는 방법을 제공합니다.
type: docs
weight: 400
url: /ko/net/groupdocs.comparison.result/filetype/
---
## FileType class

파일 형식을 나타냅니다. GroupDocs.Comparison에서 지원하는 모든 파일 유형 목록을 가져오고, 확장자 등으로 파일 유형을 감지하는 방법을 제공합니다.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Extension](../../groupdocs.comparison.result/filetype/extension) { get; } | 파일 확장자 |
| [FileFormat](../../groupdocs.comparison.result/filetype/fileformat) { get; } | 파일 형식 |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| static [FromFileNameOrExtension](../../groupdocs.comparison.result/filetype/fromfilenameorextension)(string) | 파일 이름 또는 extension 를 기반으로 FileType 반환 |
| [Equals](../../groupdocs.comparison.result/filetype/equals#equals)(FileType) | 파일 형식 동등성 check |
| override [Equals](../../groupdocs.comparison.result/filetype/equals#equals_1)(object) | object 와의 동등성 검사 |
| override [GetHashCode](../../groupdocs.comparison.result/filetype/gethashcode)() | 해시 코드 가져오기 |
| override [ToString](../../groupdocs.comparison.result/filetype/tostring)() | ToString |
| static [GetSupportedFileTypes](../../groupdocs.comparison.result/filetype/getsupportedfiletypes)() | 지원되는 파일 형식 가져오기 enumeration |
| [operator ==](../../groupdocs.comparison.result/filetype/op_equality) | 연산자 overload |
| [operator !=](../../groupdocs.comparison.result/filetype/op_inequality) | 연산자 overload |

## 필드

| 이름 | 설명 |
| --- | --- |
| static [AS](../../groupdocs.comparison.result/filetype/as) | ActionScript 프로그래밍 언어 format |
| static [AS3](../../groupdocs.comparison.result/filetype/as3) | ActionScript 프로그래밍 언어 format |
| static [ASM](../../groupdocs.comparison.result/filetype/asm) | ASM 형식 |
| static [BASH](../../groupdocs.comparison.result/filetype/bash) | 쉘 명령을 처리하는 인터프리터 유형 |
| static [BASHRC](../../groupdocs.comparison.result/filetype/bashrc) | 파일은 대화형 shells 의 동작을 결정합니다. |
| static [BAT](../../groupdocs.comparison.result/filetype/bat) | DOS, OS/2 및 Microsoft Windows 의 스크립트 파일 |
| static [BMP](../../groupdocs.comparison.result/filetype/bmp) | 비트맵 그림 |
| static [BOWERRC](../../groupdocs.comparison.result/filetype/bowerrc) | 서버 측 패키지 제어를 위한 구성 파일 |
| static [C](../../groupdocs.comparison.result/filetype/c) | C 기반 프로그래밍 언어 format |
| static [CAD](../../groupdocs.comparison.result/filetype/cad) | CAD 파일 형식 |
| static [CAKE](../../groupdocs.comparison.result/filetype/cake) | CSharp 크로스 플랫폼 빌드 자동화 시스템 format |
| static [CC](../../groupdocs.comparison.result/filetype/cc) | C 기반 프로그래밍 언어 format |
| static [CFG](../../groupdocs.comparison.result/filetype/cfg) | settings 저장에 사용되는 구성 파일 |
| static [CMAKE](../../groupdocs.comparison.result/filetype/cmake) | 소프트웨어 의 빌드 프로세스를 관리하기 위한 도구 |
| static [CMD](../../groupdocs.comparison.result/filetype/cmd) | DOS, OS/2 및 Microsoft Windows 의 스크립트 파일 |
| static [CONF](../../groupdocs.comparison.result/filetype/conf) | Unix 및 Linux 기반 시스템에서 사용되는 구성 파일 |
| static [CPP](../../groupdocs.comparison.result/filetype/cpp) | C 기반 프로그래밍 언어 format |
| static [CPY](../../groupdocs.comparison.result/filetype/cpy) | 컨트롤러 Python 스크립트 format |
| static [CS](../../groupdocs.comparison.result/filetype/cs) | CSharp 프로그래밍 언어 format |
| static [CSV](../../groupdocs.comparison.result/filetype/csv) | 쉼표로 구분된 값 File |
| static [CSX](../../groupdocs.comparison.result/filetype/csx) | CSharp 스크립트 파일 형식 |
| static [CTP](../../groupdocs.comparison.result/filetype/ctp) | CakePHP 템플릿 format |
| static [CXX](../../groupdocs.comparison.result/filetype/cxx) | C 기반 프로그래밍 언어 format |
| static [DCM](../../groupdocs.comparison.result/filetype/dcm) | 의학의 디지털 이미징 및 커뮤니케이션 |
| static [DIFF](../../groupdocs.comparison.result/filetype/diff) | 데이터 비교 도구 format |
| static [DIR](../../groupdocs.comparison.result/filetype/dir) | 디렉터리는 computer 에 파일을 저장하는 위치입니다. |
| static [DJVU](../../groupdocs.comparison.result/filetype/djvu) | 데자뷰 형식 |
| static [DOC](../../groupdocs.comparison.result/filetype/doc) | Microsoft Word 97-2003 문서 |
| static [DOCM](../../groupdocs.comparison.result/filetype/docm) | Microsoft Word 매크로 사용 문서 |
| static [DOCX](../../groupdocs.comparison.result/filetype/docx) | 마이크로소프트 워드 문서 |
| static [DOT](../../groupdocs.comparison.result/filetype/dot) | 마이크로소프트 워드 97-2003 Template |
| static [DOTM](../../groupdocs.comparison.result/filetype/dotm) | Microsoft Word 매크로 사용 Template |
| static [DOTX](../../groupdocs.comparison.result/filetype/dotx) | 마이크로소프트 워드 템플릿 |
| static [DSQL](../../groupdocs.comparison.result/filetype/dsql) | 동적 구조적 쿼리 언어 format |
| static [DWG](../../groupdocs.comparison.result/filetype/dwg) | Autodesk 설계 데이터 형식 |
| static [DXF](../../groupdocs.comparison.result/filetype/dxf) | AutoCAD 도면 교환 |
| static [EBUILD](../../groupdocs.comparison.result/filetype/ebuild) | 소프트웨어 패키지의 컴파일 및 설치 절차를 자동화하는 특수 bash 스크립트 |
| static [EML](../../groupdocs.comparison.result/filetype/eml) | 이메일 메시지 |
| static [EMLX](../../groupdocs.comparison.result/filetype/emlx) | Apple 메일 이메일 File |
| static [ERB](../../groupdocs.comparison.result/filetype/erb) | 루비 프로그래밍 언어 format |
| static [ES6](../../groupdocs.comparison.result/filetype/es6) | JavaScript 표준화 스크립팅 언어 형식 |
| static [GEMSPEC](../../groupdocs.comparison.result/filetype/gemspec) | RubyGems 의 속성을 지정하는 개발자 파일 |
| static [GIF](../../groupdocs.comparison.result/filetype/gif) | 그래픽 교환 Format |
| static [GRADLE](../../groupdocs.comparison.result/filetype/gradle) | 빌드 자동화 시스템 format |
| static [GROOVY](../../groupdocs.comparison.result/filetype/groovy) | Groovy 형식으로 작성된 소스 코드 파일 |
| static [GVY](../../groupdocs.comparison.result/filetype/gvy) | Groovy 형식으로 작성된 소스 코드 파일 |
| static [GYP](../../groupdocs.comparison.result/filetype/gyp) | 빌드 자동화 도구 format |
| static [GYPI](../../groupdocs.comparison.result/filetype/gypi) | 빌드 자동화 도구 format |
| static [H](../../groupdocs.comparison.result/filetype/h) | C 기반 헤더 파일에는 함수 및 변수 정의가 포함되어 있습니다 |
| static [HAML](../../groupdocs.comparison.result/filetype/haml) | 간소화된 HTML 생성을 위한 마크업 언어 |
| static [HAR](../../groupdocs.comparison.result/filetype/har) | HTTP 아카이브 형식 |
| static [HH](../../groupdocs.comparison.result/filetype/hh) | C++ 소스 코드 file 에서 참조하는 헤더 정보 |
| static [HPP](../../groupdocs.comparison.result/filetype/hpp) | C++ 프로그래밍 언어로 작성된 헤더 파일 |
| static [HTML](../../groupdocs.comparison.result/filetype/html) | 하이퍼텍스트 마크업 언어 |
| static [HXX](../../groupdocs.comparison.result/filetype/hxx) | C++ 프로그래밍 언어로 작성된 헤더 파일 |
| static [IPY](../../groupdocs.comparison.result/filetype/ipy) | IPython 스크립트 형식 |
| static [JAVA](../../groupdocs.comparison.result/filetype/java) | 자바 프로그래밍 언어 format |
| static [JPEG](../../groupdocs.comparison.result/filetype/jpeg) | 공동 사진 전문가 그룹 |
| static [JS](../../groupdocs.comparison.result/filetype/js) | JavaScript 프로그래밍 언어 format |
| static [JSCSRC](../../groupdocs.comparison.result/filetype/jscsrc) | JavaScript 구성 파일 format |
| static [JSHINTRC](../../groupdocs.comparison.result/filetype/jshintrc) | JavaScript 코드 품질 tool |
| static [JSMAP](../../groupdocs.comparison.result/filetype/jsmap) | 코드를 다시 소스 코드로 변환하는 방법에 대한 정보가 포함된 JSON 파일 |
| static [JSON](../../groupdocs.comparison.result/filetype/json) | 데이터 저장 및 전송을 위한 경량 형식 |
| static [LESS](../../groupdocs.comparison.result/filetype/less) | 동적 전처리기 스타일 시트 언어 format |
| static [LOG](../../groupdocs.comparison.result/filetype/log) | 로깅은 이벤트, 프로세스, 메시지 및 통신의 레지스트리를 유지합니다 |
| static [MAKE](../../groupdocs.comparison.result/filetype/make) | Makefile은 target/goal 를 생성하기 위해 make 빌드 자동화 도구에서 사용하는 일련의 지시문이 포함된 파일입니다. |
| static [MARKDN](../../groupdocs.comparison.result/filetype/markdn) | 마크다운 언어 format |
| static [MARKDOWN](../../groupdocs.comparison.result/filetype/markdown) | 마크다운 언어 format |
| static [MD](../../groupdocs.comparison.result/filetype/md) | 마크다운 언어 format |
| static [MDOWN](../../groupdocs.comparison.result/filetype/mdown) | 마크다운 언어 format |
| static [MDTEXT](../../groupdocs.comparison.result/filetype/mdtext) | 마크다운 언어 format |
| static [MDTXT](../../groupdocs.comparison.result/filetype/mdtxt) | 마크다운 언어 format |
| static [MDWN](../../groupdocs.comparison.result/filetype/mdwn) | 마크다운 언어 format |
| static [MHTML](../../groupdocs.comparison.result/filetype/mhtml) | 마임 HTML |
| static [MJS](../../groupdocs.comparison.result/filetype/mjs) | EcmaScript(ES) 모듈 확장 파일 |
| static [MK](../../groupdocs.comparison.result/filetype/mk) | Makefile은 target/goal 를 생성하기 위해 make 빌드 자동화 도구에서 사용하는 일련의 지시문이 포함된 파일입니다. |
| static [MKD](../../groupdocs.comparison.result/filetype/mkd) | 마크다운 언어 format |
| static [ML](../../groupdocs.comparison.result/filetype/ml) | Caml 프로그래밍 언어 format |
| static [MLI](../../groupdocs.comparison.result/filetype/mli) | Caml 프로그래밍 언어 format |
| static [MOBI](../../groupdocs.comparison.result/filetype/mobi) | 모비포켓 전자책 포맷 |
| static [MSG](../../groupdocs.comparison.result/filetype/msg) | Microsoft Outlook 이메일 메시지 |
| static [NQP](../../groupdocs.comparison.result/filetype/nqp) | Rakudo Perl 6 컴파일러를 빌드하는 데 사용되는 중간 언어 |
| static [OBJC](../../groupdocs.comparison.result/filetype/objc) | 목표-C 프로그래밍 언어 format |
| static [OBJCP](../../groupdocs.comparison.result/filetype/objcp) | 오브젝티브-C++ 프로그래밍 언어 format |
| static [ODP](../../groupdocs.comparison.result/filetype/odp) | OpenDocument Presentation |
| static [ODS](../../groupdocs.comparison.result/filetype/ods) | OpenDocument 스프레드시트 |
| static [ODT](../../groupdocs.comparison.result/filetype/odt) | OpenDocument Text |
| static [ONE](../../groupdocs.comparison.result/filetype/one) | 마이크로소프트 원노트 문서 |
| static [OTP](../../groupdocs.comparison.result/filetype/otp) | OpenDocument 프레젠테이션 템플릿 |
| static [OTT](../../groupdocs.comparison.result/filetype/ott) | OpenDocument 텍스트 Template |
| static [P6](../../groupdocs.comparison.result/filetype/p6) | Perl 프로그래밍 언어 format |
| static [PAC](../../groupdocs.comparison.result/filetype/pac) | JavaScript 함수용 프록시 자동 구성 파일 format |
| static [PATCH](../../groupdocs.comparison.result/filetype/patch) | 차이점 목록 format |
| static [PDF](../../groupdocs.comparison.result/filetype/pdf) | Adobe 휴대용 문서 형식 |
| static [PHP](../../groupdocs.comparison.result/filetype/php) | PHP 프로그래밍 언어 format |
| static [PHP4](../../groupdocs.comparison.result/filetype/php4) | PHP 프로그래밍 언어 format |
| static [PHP5](../../groupdocs.comparison.result/filetype/php5) | PHP 프로그래밍 언어 format |
| static [PHTML](../../groupdocs.comparison.result/filetype/phtml) | PHP 2 프로그램용 표준 파일 확장자 format |
| static [PL](../../groupdocs.comparison.result/filetype/pl) | Perl 프로그래밍 언어 format |
| static [PL6](../../groupdocs.comparison.result/filetype/pl6) | Perl 프로그래밍 언어 format |
| static [PM](../../groupdocs.comparison.result/filetype/pm) | 펄 모듈 format |
| static [PM6](../../groupdocs.comparison.result/filetype/pm6) | 펄 모듈 format |
| static [PNG](../../groupdocs.comparison.result/filetype/png) | 휴대용 네트워크 Graphics |
| static [POD](../../groupdocs.comparison.result/filetype/pod) | Perl 경량 마크업 언어 format |
| static [PODSPEC](../../groupdocs.comparison.result/filetype/podspec) | Ruby 빌드 설정 format |
| static [POT](../../groupdocs.comparison.result/filetype/pot) | 마이크로소프트 파워포인트 템플릿 |
| static [POTX](../../groupdocs.comparison.result/filetype/potx) | 마이크로소프트 파워포인트 템플릿 |
| static [PPS](../../groupdocs.comparison.result/filetype/pps) | Microsoft PowerPoint 97-2003 슬라이드 쇼 |
| static [PPSX](../../groupdocs.comparison.result/filetype/ppsx) | Microsoft PowerPoint 슬라이드 쇼 |
| static [PPT](../../groupdocs.comparison.result/filetype/ppt) | Microsoft PowerPoint 97-2003 Presentation |
| static [PPTX](../../groupdocs.comparison.result/filetype/pptx) | Microsoft PowerPoint 프레젠테이션 |
| static [PROP](../../groupdocs.comparison.result/filetype/prop) | 속성 파일 format |
| static [PSGI](../../groupdocs.comparison.result/filetype/psgi) | Perl programming 로 작성된 웹 서버와 웹 애플리케이션 및 프레임워크 간의 인터페이스 |
| static [PY](../../groupdocs.comparison.result/filetype/py) | 파이썬 프로그래밍 언어 format |
| static [PYI](../../groupdocs.comparison.result/filetype/pyi) | Python 인터페이스 파일 format |
| static [PYW](../../groupdocs.comparison.result/filetype/pyw) | 스크립트를 실행해야 함을 나타내기 위해 Windows에서 사용되는 파일 |
| static [RAKE](../../groupdocs.comparison.result/filetype/rake) | Ruby 빌드 자동화 도구 |
| static [RB](../../groupdocs.comparison.result/filetype/rb) | 루비 프로그래밍 언어 format |
| static [RBI](../../groupdocs.comparison.result/filetype/rbi) | Ruby 인터페이스 파일 format |
| static [REJ](../../groupdocs.comparison.result/filetype/rej) | 거부된 파일 format |
| static [RJS](../../groupdocs.comparison.result/filetype/rjs) | 루비 프로그래밍 언어 format |
| static [RPY](../../groupdocs.comparison.result/filetype/rpy) | 게임을 만들고 실행하는 Python 기반 파일 엔진 |
| static [RST](../../groupdocs.comparison.result/filetype/rst) | 경량 마크업 언어 |
| static [RTF](../../groupdocs.comparison.result/filetype/rtf) | 리치 텍스트 Document |
| static [RU](../../groupdocs.comparison.result/filetype/ru) | 랙 구성 파일 format |
| static [SASS](../../groupdocs.comparison.result/filetype/sass) | 스타일 시트 언어 format |
| static [SBT](../../groupdocs.comparison.result/filetype/sbt) | Scala용 SBT 빌드 도구 format |
| static [SC](../../groupdocs.comparison.result/filetype/sc) | 스칼라 워크시트 format |
| static [SCALA](../../groupdocs.comparison.result/filetype/scala) | 스칼라 프로그래밍 언어 format |
| static [SCSS](../../groupdocs.comparison.result/filetype/scss) | 스타일 시트 언어 format |
| static [SH](../../groupdocs.comparison.result/filetype/sh) | bash format 용으로 프로그래밍된 스크립트 |
| static [SQL](../../groupdocs.comparison.result/filetype/sql) | 구조적 쿼리 언어 format |
| static [SVG](../../groupdocs.comparison.result/filetype/svg) | 스칼라 벡터 Graphics |
| static [T](../../groupdocs.comparison.result/filetype/t) | Perl 테스트 파일 형식 |
| static [TXT](../../groupdocs.comparison.result/filetype/txt) | 일반 텍스트 문서 |
| static [UNKNOWN](../../groupdocs.comparison.result/filetype/unknown) | 알 수 없는 유형 |
| static [VDX](../../groupdocs.comparison.result/filetype/vdx) | Microsoft Visio 2003-2010 XML 도면 |
| static [VIM](../../groupdocs.comparison.result/filetype/vim) | Vim 소스 코드 파일 format |
| static [VSD](../../groupdocs.comparison.result/filetype/vsd) | Microsoft Visio 2003-2010 Drawing |
| static [VSDX](../../groupdocs.comparison.result/filetype/vsdx) | Microsoft Visio Drawing |
| static [VSS](../../groupdocs.comparison.result/filetype/vss) | Microsoft Visio 2003-2010 스텐실 |
| static [VST](../../groupdocs.comparison.result/filetype/vst) | Microsoft Visio 2003-2010 Template |
| static [WEBMANIFEST](../../groupdocs.comparison.result/filetype/webmanifest) | 매니페스트 파일에는 app 에 대한 정보가 포함되어 있습니다. |
| static [XLS](../../groupdocs.comparison.result/filetype/xls) | Microsoft Excel 97-2003 워크시트 |
| static [XLSB](../../groupdocs.comparison.result/filetype/xlsb) | Microsoft Excel 바이너리 워크시트 |
| static [XLSM](../../groupdocs.comparison.result/filetype/xlsm) | Microsoft Excel 매크로 사용 워크시트 |
| static [XLSX](../../groupdocs.comparison.result/filetype/xlsx) | Microsoft Excel 워크시트 |
| static [XLT](../../groupdocs.comparison.result/filetype/xlt) | 마이크로소프트 엑셀 템플릿 |
| static [XLTM](../../groupdocs.comparison.result/filetype/xltm) | Microsoft Excel 매크로 사용 template |
| static [YAML](../../groupdocs.comparison.result/filetype/yaml) | 사람이 읽을 수 있는 데이터 직렬화 언어 format |
| static [YML](../../groupdocs.comparison.result/filetype/yml) | 사람이 읽을 수 있는 데이터 직렬화 언어 format |

### 비고

**더 알아보기**

* GroupDocs.Comparison: 에서 지원하는 파일 형식에 대해 자세히 알아보십시오.[지원되는 문서 형식의 전체 목록](https://docs.groupdocs.com/display/comparisonnet/Supported+Document+Formats)
* C#에서 지원되는 파일 형식 가져오기에 대해 자세히 알아보기: [C#에서 지원되는 파일 형식을 얻는 방법](https://docs.groupdocs.com/display/comparisonnet/Get+supported+file+formats)

### 또한보십시오

* 네임스페이스 [GroupDocs.Comparison.Result](../../groupdocs.comparison.result)
* 집회 [GroupDocs.Comparison](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Comparison.dll -->
