---
title: "FileType"
second_title: "GroupDocs.Comparison for Java API 참조"
description: "FileType 열거형은 문서 비교 프로세스에 사용되는 파일 유형을 나타냅니다."
type: docs
weight: 16
url: /ko/java/com.groupdocs.comparison.result/filetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public enum FileType extends Enum<FileType> implements System.IEquatable<FileType>
```

FileType 열거형은 문서 비교 프로세스에 사용되는 파일 유형을 나타냅니다.


다양한 파일 유형을 정의합니다. Word 문서, PDF 파일 등.
GroupDocs.Comparison에서 지원하는 모든 파일 유형 목록을 얻고, 확장자로 파일 유형을 감지하는 등의 메서드를 제공합니다.
GroupDocs.Comparison 라이브러리를 사용할 때 파일 유형을 지정하기 위해 이 열거형을 사용합니다.

* Learn more about file formats supported by GroupDocs.Comparison: [Full list of supported document formats](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* Learn more about getting supported file types in Java: [How to get supported file formats in Java](../https://docs.groupdocs.com/display/comparisonjava/Get+supported+file+formats)


사용 예시:

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


## 필드

| 필드 | 설명 |
| --- | --- |
|  | [UNKNOWN](#UNKNOWN) | 알 수 없는 유형 |
|
|  | [AS](#AS) | ActionScript 프로그래밍 언어 형식 |
|
|  | [AS3](#AS3) | ActionScript 프로그래밍 언어 형식 |
|
|  | [ASM](#ASM) | Assembler 프로그래밍 언어 형식 |
|
|  | [BAT](#BAT) | DOS, OS/2 및 Microsoft Windows용 스크립트 파일 |
|
|  | [CMD](#CMD) | DOS, OS/2 및 Microsoft Windows용 스크립트 파일 |
|
|  | [C](#C) | C 기반 프로그래밍 언어 형식 |
|
|  | [H](#H) | C 기반 헤더 파일에는 함수와 변수 정의가 포함됩니다. |
|
|  | [PDF](#PDF) | Adobe Portable Document 형식 |
|
|  | [DOC](#DOC) | Microsoft Word 97-2003 문서 |
|
|  | [DOCM](#DOCM) | Microsoft Word 매크로 사용 문서 |
|
|  | [DOCX](#DOCX) | Microsoft Word 문서 |
|
|  | [DOT](#DOT) | Microsoft Word 97-2003 템플릿 |
|
|  | [DOTM](#DOTM) | Microsoft Word 매크로 사용 템플릿 |
|
|  | [DOTX](#DOTX) | Microsoft Word 템플릿 |
|
|  | [XLS](#XLS) | Microsoft Excel 97-2003 워크시트 |
|
|  | [XLT](#XLT) | Microsoft Excel 템플릿 |
|
|  | [XLSX](#XLSX) | Microsoft Excel 워크시트 |
|
|  | [XLTM](#XLTM) | Microsoft Excel 매크로 사용 템플릿 |
|
|  | [XLSB](#XLSB) | Microsoft Excel 이진 워크시트 |
|
|  | [XLSM](#XLSM) | Microsoft Excel 매크로 사용 워크시트 |
|
|  | [POT](#POT) | Microsoft PowerPoint 템플릿 |
|
|  | [POTX](#POTX) | Microsoft PowerPoint 템플릿 |
|
|  | [POTM](#POTM) | Microsoft PowerPoint 매크로 지원 템플릿 |
|
|  | [PPS](#PPS) | Microsoft PowerPoint 97-2003 슬라이드 쇼 |
|
|  | [PPSX](#PPSX) | Microsoft PowerPoint 슬라이드 쇼 |
|
|  | [PPTX](#PPTX) | Microsoft PowerPoint 프레젠테이션 |
|
|  | [PPT](#PPT) | Microsoft PowerPoint 97-2003 프레젠테이션 |
|
|  | [PPTM](#PPTM) | Microsoft PowerPoint 매크로 사용 프레젠테이션 |
|
|  | [PPSM](#PPSM) | Microsoft PowerPoint 매크로 사용 슬라이드 쇼 프레젠테이션 |
|
|  | [VSDX](#VSDX) | Microsoft Visio 도면 |
|
|  | [VSD](#VSD) | Microsoft Visio 2003-2010 도면 |
|
|  | [VSS](#VSS) | Microsoft Visio 2003-2010 스텐실 |
|
|  | [VST](#VST) | Microsoft Visio 2003-2010 템플릿 |
|
|  | [VDX](#VDX) | Microsoft Visio 2003-2010 XML 도면 |
|
|  | [ONE](#ONE) | Microsoft OneNote 문서 |
|
|  | [ODT](#ODT) | OpenDocument 텍스트 |
|
|  | [ODP](#ODP) | OpenDocument 프레젠테이션 |
|
|  | [OTP](#OTP) | OpenDocument 프레젠테이션 템플릿 |
|
|  | [ODS](#ODS) | OpenDocument 스프레드시트 |
|
|  | [OTT](#OTT) | OpenDocument 텍스트 템플릿 |
|
|  | [RTF](#RTF) | 리치 텍스트 문서 |
|
|  | [TXT](#TXT) | 일반 텍스트 문서 |
|
|  | [CSV](#CSV) | 쉼표 구분 값 파일 |
|
|  | [HTML](#HTML) | 하이퍼텍스트 마크업 언어 |
|
|  | [MHTML](#MHTML) | MIME HTML |
|
|  | [MOBI](#MOBI) | Mobipocket 전자책 포맷 |
|
|  | [DCM](#DCM) | 의료용 디지털 영상 및 통신 |
|
|  | [DJVU](#DJVU) | Deja Vu 포맷 |
|
|  | [DWG](#DWG) | Autodesk 디자인 데이터 포맷 |
|
|  | [DXF](#DXF) | AutoCAD 도면 교환 |
|
|  | [BMP](#BMP) | 비트맵 이미지 |
|
|  | [GIF](#GIF) | 그래픽 교환 포맷 |
|
|  | [JPEG](#JPEG) | 합동 사진 전문가 그룹 |
|
|  | [JPG](#JPG) | 합동 사진 전문가 그룹 |
|
|  | [PNG](#PNG) | 휴대용 네트워크 그래픽스 |
|
|  | [SVG](#SVG) | 스칼라 벡터 그래픽스 |
|
|  | [EML](#EML) | 이메일 메시지 |
|
|  | [EMLX](#EMLX) | Apple Mail 이메일 파일 |
|
|  | [MSG](#MSG) | Microsoft Outlook 이메일 메시지 |
|
|  | [CAD](#CAD) | CAD 파일 포맷 |
|
|  | [CPP](#CPP) | C 기반 프로그래밍 언어 형식 |
|
|  | [CC](#CC) | C 기반 프로그래밍 언어 형식 |
|
|  | [CXX](#CXX) | C 기반 프로그래밍 언어 형식 |
|
|  | [HXX](#HXX) | C++ 프로그래밍 언어로 작성된 헤더 파일 |
|
|  | [HH](#HH) | C++ 소스 코드 파일이 참조하는 헤더 정보 |
|
|  | [HPP](#HPP) | C++ 프로그래밍 언어로 작성된 헤더 파일 |
|
|  | [CMAKE](#CMAKE) | 소프트웨어 빌드 프로세스를 관리하는 도구 |
|
|  | [CS](#CS) | CSharp 프로그래밍 언어 포맷 |
|
|  | [CSX](#CSX) | CSharp 스크립트 파일 포맷 |
|
|  | [CAKE](#CAKE) | CSharp 크로스 플랫폼 빌드 자동화 시스템 포맷 |
|
|  | [DIFF](#DIFF) | 데이터 비교 도구 포맷 |
|
|  | [PATCH](#PATCH) | 차이점 목록 포맷 |
|
|  | [REJ](#REJ) | 거부된 파일 포맷 |
|
|  | [GROOVY](#GROOVY) | Groovy 형식으로 작성된 소스 코드 파일 |
|
|  | [GVY](#GVY) | Groovy 형식으로 작성된 소스 코드 파일 |
|
|  | [GRADLE](#GRADLE) | 빌드 자동화 시스템 형식 |
|
|  | [HAML](#HAML) | 단순화된 HTML 생성을 위한 마크업 언어 |
|
|  | [JS](#JS) | JavaScript 프로그래밍 언어 형식 |
|
|  | [ES6](#ES6) | JavaScript 표준화 스크립트 언어 형식 |
|
|  | [MJS](#MJS) | EcmaScript (ES) 모듈 파일용 확장자 |
|
|  | [PAC](#PAC) | JavaScript 함수 형식용 프록시 자동 구성 파일 |
|
|  | [JSON](#JSON) | 데이터 저장 및 전송을 위한 경량 형식 |
|
|  | [BOWERRC](#BOWERRC) | 서버 측 패키지 제어를 위한 구성 파일 |
|
|  | [JSHINTRC](#JSHINTRC) | JavaScript 코드 품질 도구 |
|
|  | [JSCSRC](#JSCSRC) | JavaScript 구성 파일 형식 |
|
|  | [WEBMANIFEST](#WEBMANIFEST) | 매니페스트 파일에는 앱에 대한 정보가 포함됩니다 |
|
|  | [JSMAP](#JSMAP) | 코드를 소스 코드로 되돌리는 방법에 대한 정보를 포함하는 JSON 파일 |
|
|  | [HAR](#HAR) | HTTP 아카이브 형식 |
|
|  | [JAVA](#JAVA) | Java 프로그래밍 언어 형식 |
|
|  | [LESS](#LESS) | 동적 전처리기 스타일 시트 언어 형식 |
|
|  | [LOG](#LOG) | 로깅은 이벤트, 프로세스, 메시지 및 통신의 레지스트리를 유지합니다 |
|
|  | [MAKE](#MAKE) | Makefile은 목표/목적을 생성하기 위해 make 빌드 자동화 도구가 사용하는 일련의 지시문을 포함하는 파일입니다 |
|
|  | [MK](#MK) | Makefile은 목표/목적을 생성하기 위해 make 빌드 자동화 도구가 사용하는 일련의 지시문을 포함하는 파일입니다 |
|
|  | [MD](#MD) | Markdown 언어 형식 |
|
|  | [MKD](#MKD) | Markdown 언어 형식 |
|
|  | [MDWN](#MDWN) | Markdown 언어 형식 |
|
|  | [MDOWN](#MDOWN) | Markdown 언어 형식 |
|
|  | [MARKDOWN](#MARKDOWN) | Markdown 언어 형식 |
|
|  | [MARKDN](#MARKDN) | Markdown 언어 형식 |
|
|  | [MDTXT](#MDTXT) | Markdown 언어 형식 |
|
|  | [MDTEXT](#MDTEXT) | Markdown 언어 형식 |
|
|  | [ML](#ML) | Caml 프로그래밍 언어 형식 |
|
|  | [MLI](#MLI) | Caml 프로그래밍 언어 형식 |
|
|  | [OBJC](#OBJC) | Objective-C 프로그래밍 언어 형식 |
|
|  | [OBJCP](#OBJCP) | Objective-C++ 프로그래밍 언어 형식 |
|
|  | [PHP](#PHP) | PHP 프로그래밍 언어 형식 |
|
|  | [PHP4](#PHP4) | PHP 프로그래밍 언어 형식 |
|
|  | [PHP5](#PHP5) | PHP 프로그래밍 언어 형식 |
|
|  | [PHTML](#PHTML) | PHP 2 프로그램용 표준 파일 확장자 형식 |
|
|  | [CTP](#CTP) | CakePHP 템플릿 형식 |
|
|  | [PL](#PL) | Perl 프로그래밍 언어 형식 |
|
|  | [PM](#PM) | Perl 모듈 형식 |
|
|  | [POD](#POD) | Perl 경량 마크업 언어 형식 |
|
|  | [T](#T) | Perl 테스트 파일 형식 |
|
|  | [PSGI](#PSGI) | Perl 프로그래밍으로 작성된 웹 서버와 웹 애플리케이션 및 프레임워크 사이의 인터페이스 |
|
|  | [P6](#P6) | Perl 프로그래밍 언어 형식 |
|
|  | [PL6](#PL6) | Perl 프로그래밍 언어 형식 |
|
|  | [PM6](#PM6) | Perl 모듈 형식 |
|
|  | [NQP](#NQP) | Rakudo Perl 6 컴파일러를 빌드하는 데 사용되는 중간 언어 |
|
|  | [PROP](#PROP) | Properties 파일 형식 |
|
|  | [CFG](#CFG) | 설정을 저장하는 데 사용되는 구성 파일 |
|
|  | [CONF](#CONF) | Unix 및 Linux 기반 시스템에서 사용되는 구성 파일 |
|
|  | [DIR](#DIR) | Directory는 컴퓨터에서 파일을 저장하는 위치입니다 |
|
|  | [PY](#PY) | Python 프로그래밍 언어 형식 |
|
|  | [RPY](#RPY) | 게임을 만들고 실행하기 위한 Python 기반 파일 엔진 |
|
|  | [PYW](#PYW) | 스크립트를 실행해야 함을 나타내기 위해 Windows에서 사용되는 파일 |
|
|  | [CPY](#CPY) | Controller Python 스크립트 형식 |
|
|  | [GYP](#GYP) | 빌드 자동화 도구 형식 |
|
|  | [GYPI](#GYPI) | 빌드 자동화 도구 형식 |
|
|  | [PYI](#PYI) | Python 인터페이스 파일 형식 |
|
|  | [IPY](#IPY) | IPython 스크립트 형식 |
|
|  | [RST](#RST) | 경량 마크업 언어 |
|
|  | [RB](#RB) | Ruby 프로그래밍 언어 형식 |
|
|  | [ERB](#ERB) | Ruby 프로그래밍 언어 형식 |
|
|  | [RJS](#RJS) | Ruby 프로그래밍 언어 형식 |
|
|  | [GEMSPEC](#GEMSPEC) | RubyGems의 속성을 지정하는 개발자 파일 |
|
|  | [RAKE](#RAKE) | Ruby 빌드 자동화 도구 |
|
|  | [RU](#RU) | Rack 구성 파일 형식 |
|
|  | [PODSPEC](#PODSPEC) | Ruby 빌드 설정 형식 |
|
|  | [RBI](#RBI) | Ruby 인터페이스 파일 형식 |
|
|  | [SASS](#SASS) | 스타일 시트 언어 형식 |
|
|  | [SCSS](#SCSS) | 스타일 시트 언어 형식 |
|
|  | [SCALA](#SCALA) | Scala 프로그래밍 언어 형식 |
|
|  | [SBT](#SBT) | Scala용 SBT 빌드 도구 형식 |
|
|  | [SC](#SC) | Scala 워크시트 형식 |
|
|  | [SH](#SH) | bash용 스크립트 형식 |
|
|  | [BASH](#BASH) | 셸 명령을 처리하는 인터프리터 유형 |
|
|  | [BASHRC](#BASHRC) | 파일은 대화형 셸의 동작을 결정합니다 |
|
|  | [EBUILD](#EBUILD) | 소프트웨어 패키지의 컴파일 및 설치 절차를 자동화하는 특수 bash 스크립트 |
|
|  | [SQL](#SQL) | 구조화 질의 언어 형식 |
|
|  | [DSQL](#DSQL) | 동적 구조화 질의 언어 형식 |
|
|  | [VIM](#VIM) | Vim 소스 코드 파일 형식 |
|
|  | [YAML](#YAML) | 인간이 읽을 수 있는 데이터 직렬화 언어 형식 |
|
|  | [YML](#YML) | 인간이 읽을 수 있는 데이터 직렬화 언어 형식 |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromFileNameOrExtension(String value)](#fromFileNameOrExtension-java.lang.String-) | 파일 이름 또는 확장자를 기반으로 FileType을 반환합니다 |
|
|  | [getSupportedFileTypes()](#getSupportedFileTypes--) | 지원되는 파일 유형 목록을 가져옵니다 |
|
|  | [areEquals(FileType left, FileType right)](#areEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-) | 제공된 파일 유형의 동일성을 확인합니다 |
|
|  | [areNotEquals(FileType left, FileType right)](#areNotEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-) | 제공된 파일 유형이 같지 않은지 확인합니다 |
|
|  | [getFileFormat()](#getFileFormat--) | 파일 유형의 텍스트 설명을 가져옵니다 |
|
|  | [getExtension()](#getExtension--) | 파일 유형의 확장자를 가져옵니다 |
|
|  | [toString()](#toString--) | 예를 들어 [FileType](../../com.groupdocs.comparison.result/filetype)의 문자열 표현을 가져옵니다 |
'PHP 프로그래밍 언어 형식 (.php)'

|
### UNKNOWN {#UNKNOWN}
```
public static final FileType UNKNOWN
```


알 수 없는 유형


### AS {#AS}
```
public static final FileType AS
```


ActionScript 프로그래밍 언어 형식


### AS3 {#AS3}
```
public static final FileType AS3
```


ActionScript 프로그래밍 언어 형식


### ASM {#ASM}
```
public static final FileType ASM
```


Assembler 프로그래밍 언어 형식


### BAT {#BAT}
```
public static final FileType BAT
```


DOS, OS/2 및 Microsoft Windows용 스크립트 파일


### CMD {#CMD}
```
public static final FileType CMD
```


DOS, OS/2 및 Microsoft Windows용 스크립트 파일


### C {#C}
```
public static final FileType C
```


C 기반 프로그래밍 언어 형식


### H {#H}
```
public static final FileType H
```


C 기반 헤더 파일에는 함수와 변수 정의가 포함됩니다.


### PDF {#PDF}
```
public static final FileType PDF
```


Adobe Portable Document 형식


### DOC {#DOC}
```
public static final FileType DOC
```


Microsoft Word 97-2003 문서


### DOCM {#DOCM}
```
public static final FileType DOCM
```


Microsoft Word 매크로 사용 문서


### DOCX {#DOCX}
```
public static final FileType DOCX
```


Microsoft Word 문서


### DOT {#DOT}
```
public static final FileType DOT
```


Microsoft Word 97-2003 템플릿


### DOTM {#DOTM}
```
public static final FileType DOTM
```


Microsoft Word 매크로 사용 템플릿


### DOTX {#DOTX}
```
public static final FileType DOTX
```


Microsoft Word 템플릿


### XLS {#XLS}
```
public static final FileType XLS
```


Microsoft Excel 97-2003 워크시트


### XLT {#XLT}
```
public static final FileType XLT
```


Microsoft Excel 템플릿


### XLSX {#XLSX}
```
public static final FileType XLSX
```


Microsoft Excel 워크시트


### XLTM {#XLTM}
```
public static final FileType XLTM
```


Microsoft Excel 매크로 사용 템플릿


### XLSB {#XLSB}
```
public static final FileType XLSB
```


Microsoft Excel 이진 워크시트


### XLSM {#XLSM}
```
public static final FileType XLSM
```


Microsoft Excel 매크로 사용 워크시트


### POT {#POT}
```
public static final FileType POT
```


Microsoft PowerPoint 템플릿


### POTX {#POTX}
```
public static final FileType POTX
```


Microsoft PowerPoint 템플릿


### POTM {#POTM}
```
public static final FileType POTM
```


Microsoft PowerPoint 매크로 지원 템플릿


### PPS {#PPS}
```
public static final FileType PPS
```


Microsoft PowerPoint 97-2003 슬라이드 쇼


### PPSX {#PPSX}
```
public static final FileType PPSX
```


Microsoft PowerPoint 슬라이드 쇼


### PPTX {#PPTX}
```
public static final FileType PPTX
```


Microsoft PowerPoint 프레젠테이션


### PPT {#PPT}
```
public static final FileType PPT
```


Microsoft PowerPoint 97-2003 프레젠테이션


### PPTM {#PPTM}
```
public static final FileType PPTM
```


Microsoft PowerPoint 매크로 사용 프레젠테이션


### PPSM {#PPSM}
```
public static final FileType PPSM
```


Microsoft PowerPoint 매크로 사용 슬라이드 쇼 프레젠테이션


### VSDX {#VSDX}
```
public static final FileType VSDX
```


Microsoft Visio 도면


### VSD {#VSD}
```
public static final FileType VSD
```


Microsoft Visio 2003-2010 도면


### VSS {#VSS}
```
public static final FileType VSS
```


Microsoft Visio 2003-2010 스텐실


### VST {#VST}
```
public static final FileType VST
```


Microsoft Visio 2003-2010 템플릿


### VDX {#VDX}
```
public static final FileType VDX
```


Microsoft Visio 2003-2010 XML 도면


### ONE {#ONE}
```
public static final FileType ONE
```


Microsoft OneNote 문서


### ODT {#ODT}
```
public static final FileType ODT
```


OpenDocument 텍스트


### ODP {#ODP}
```
public static final FileType ODP
```


OpenDocument 프레젠테이션


### OTP {#OTP}
```
public static final FileType OTP
```


OpenDocument 프레젠테이션 템플릿


### ODS {#ODS}
```
public static final FileType ODS
```


OpenDocument 스프레드시트


### OTT {#OTT}
```
public static final FileType OTT
```


OpenDocument 텍스트 템플릿


### RTF {#RTF}
```
public static final FileType RTF
```


리치 텍스트 문서


### TXT {#TXT}
```
public static final FileType TXT
```


일반 텍스트 문서


### CSV {#CSV}
```
public static final FileType CSV
```


쉼표 구분 값 파일


### HTML {#HTML}
```
public static final FileType HTML
```


하이퍼텍스트 마크업 언어


### MHTML {#MHTML}
```
public static final FileType MHTML
```


MIME HTML


### MOBI {#MOBI}
```
public static final FileType MOBI
```


Mobipocket 전자책 포맷


### DCM {#DCM}
```
public static final FileType DCM
```


의료용 디지털 영상 및 통신


### DJVU {#DJVU}
```
public static final FileType DJVU
```


Deja Vu 포맷


### DWG {#DWG}
```
public static final FileType DWG
```


Autodesk 디자인 데이터 포맷


### DXF {#DXF}
```
public static final FileType DXF
```


AutoCAD 도면 교환


### BMP {#BMP}
```
public static final FileType BMP
```


비트맵 이미지


### GIF {#GIF}
```
public static final FileType GIF
```


그래픽 교환 포맷


### JPEG {#JPEG}
```
public static final FileType JPEG
```


합동 사진 전문가 그룹


### JPG {#JPG}
```
public static final FileType JPG
```


합동 사진 전문가 그룹


### PNG {#PNG}
```
public static final FileType PNG
```


휴대용 네트워크 그래픽스


### SVG {#SVG}
```
public static final FileType SVG
```


스칼라 벡터 그래픽스


### EML {#EML}
```
public static final FileType EML
```


이메일 메시지


### EMLX {#EMLX}
```
public static final FileType EMLX
```


Apple Mail 이메일 파일


### MSG {#MSG}
```
public static final FileType MSG
```


Microsoft Outlook 이메일 메시지


### CAD {#CAD}
```
public static final FileType CAD
```


CAD 파일 포맷


### CPP {#CPP}
```
public static final FileType CPP
```


C 기반 프로그래밍 언어 형식


### CC {#CC}
```
public static final FileType CC
```


C 기반 프로그래밍 언어 형식


### CXX {#CXX}
```
public static final FileType CXX
```


C 기반 프로그래밍 언어 형식


### HXX {#HXX}
```
public static final FileType HXX
```


C++ 프로그래밍 언어로 작성된 헤더 파일


### HH {#HH}
```
public static final FileType HH
```


C++ 소스 코드 파일이 참조하는 헤더 정보


### HPP {#HPP}
```
public static final FileType HPP
```


C++ 프로그래밍 언어로 작성된 헤더 파일


### CMAKE {#CMAKE}
```
public static final FileType CMAKE
```


소프트웨어 빌드 프로세스를 관리하는 도구


### CS {#CS}
```
public static final FileType CS
```


CSharp 프로그래밍 언어 포맷


### CSX {#CSX}
```
public static final FileType CSX
```


CSharp 스크립트 파일 포맷


### CAKE {#CAKE}
```
public static final FileType CAKE
```


CSharp 크로스 플랫폼 빌드 자동화 시스템 포맷


### DIFF {#DIFF}
```
public static final FileType DIFF
```


데이터 비교 도구 포맷


### PATCH {#PATCH}
```
public static final FileType PATCH
```


차이점 목록 포맷


### REJ {#REJ}
```
public static final FileType REJ
```


거부된 파일 포맷


### GROOVY {#GROOVY}
```
public static final FileType GROOVY
```


Groovy 형식으로 작성된 소스 코드 파일


### GVY {#GVY}
```
public static final FileType GVY
```


Groovy 형식으로 작성된 소스 코드 파일


### GRADLE {#GRADLE}
```
public static final FileType GRADLE
```


빌드 자동화 시스템 형식


### HAML {#HAML}
```
public static final FileType HAML
```


단순화된 HTML 생성을 위한 마크업 언어


### JS {#JS}
```
public static final FileType JS
```


JavaScript 프로그래밍 언어 형식


### ES6 {#ES6}
```
public static final FileType ES6
```


JavaScript 표준화 스크립트 언어 형식


### MJS {#MJS}
```
public static final FileType MJS
```


EcmaScript (ES) 모듈 파일용 확장자


### PAC {#PAC}
```
public static final FileType PAC
```


JavaScript 함수 형식용 프록시 자동 구성 파일


### JSON {#JSON}
```
public static final FileType JSON
```


데이터 저장 및 전송을 위한 경량 형식


### BOWERRC {#BOWERRC}
```
public static final FileType BOWERRC
```


서버 측 패키지 제어를 위한 구성 파일


### JSHINTRC {#JSHINTRC}
```
public static final FileType JSHINTRC
```


JavaScript 코드 품질 도구


### JSCSRC {#JSCSRC}
```
public static final FileType JSCSRC
```


JavaScript 구성 파일 형식


### WEBMANIFEST {#WEBMANIFEST}
```
public static final FileType WEBMANIFEST
```


매니페스트 파일에는 앱에 대한 정보가 포함됩니다


### JSMAP {#JSMAP}
```
public static final FileType JSMAP
```


코드를 소스 코드로 되돌리는 방법에 대한 정보를 포함하는 JSON 파일


### HAR {#HAR}
```
public static final FileType HAR
```


HTTP 아카이브 형식


### JAVA {#JAVA}
```
public static final FileType JAVA
```


Java 프로그래밍 언어 형식


### LESS {#LESS}
```
public static final FileType LESS
```


동적 전처리기 스타일 시트 언어 형식


### LOG {#LOG}
```
public static final FileType LOG
```


로깅은 이벤트, 프로세스, 메시지 및 통신의 레지스트리를 유지합니다


### MAKE {#MAKE}
```
public static final FileType MAKE
```


Makefile은 목표/목적을 생성하기 위해 make 빌드 자동화 도구가 사용하는 일련의 지시문을 포함하는 파일입니다


### MK {#MK}
```
public static final FileType MK
```


Makefile은 목표/목적을 생성하기 위해 make 빌드 자동화 도구가 사용하는 일련의 지시문을 포함하는 파일입니다


### MD {#MD}
```
public static final FileType MD
```


Markdown 언어 형식


### MKD {#MKD}
```
public static final FileType MKD
```


Markdown 언어 형식


### MDWN {#MDWN}
```
public static final FileType MDWN
```


Markdown 언어 형식


### MDOWN {#MDOWN}
```
public static final FileType MDOWN
```


Markdown 언어 형식


### MARKDOWN {#MARKDOWN}
```
public static final FileType MARKDOWN
```


Markdown 언어 형식


### MARKDN {#MARKDN}
```
public static final FileType MARKDN
```


Markdown 언어 형식


### MDTXT {#MDTXT}
```
public static final FileType MDTXT
```


Markdown 언어 형식


### MDTEXT {#MDTEXT}
```
public static final FileType MDTEXT
```


Markdown 언어 형식


### ML {#ML}
```
public static final FileType ML
```


Caml 프로그래밍 언어 형식


### MLI {#MLI}
```
public static final FileType MLI
```


Caml 프로그래밍 언어 형식


### OBJC {#OBJC}
```
public static final FileType OBJC
```


Objective-C 프로그래밍 언어 형식


### OBJCP {#OBJCP}
```
public static final FileType OBJCP
```


Objective-C++ 프로그래밍 언어 형식


### PHP {#PHP}
```
public static final FileType PHP
```


PHP 프로그래밍 언어 형식


### PHP4 {#PHP4}
```
public static final FileType PHP4
```


PHP 프로그래밍 언어 형식


### PHP5 {#PHP5}
```
public static final FileType PHP5
```


PHP 프로그래밍 언어 형식


### PHTML {#PHTML}
```
public static final FileType PHTML
```


PHP 2 프로그램용 표준 파일 확장자 형식


### CTP {#CTP}
```
public static final FileType CTP
```


CakePHP 템플릿 형식


### PL {#PL}
```
public static final FileType PL
```


Perl 프로그래밍 언어 형식


### PM {#PM}
```
public static final FileType PM
```


Perl 모듈 형식


### POD {#POD}
```
public static final FileType POD
```


Perl 경량 마크업 언어 형식


### T {#T}
```
public static final FileType T
```


Perl 테스트 파일 형식


### PSGI {#PSGI}
```
public static final FileType PSGI
```


Perl 프로그래밍으로 작성된 웹 서버와 웹 애플리케이션 및 프레임워크 사이의 인터페이스


### P6 {#P6}
```
public static final FileType P6
```


Perl 프로그래밍 언어 형식


### PL6 {#PL6}
```
public static final FileType PL6
```


Perl 프로그래밍 언어 형식


### PM6 {#PM6}
```
public static final FileType PM6
```


Perl 모듈 형식


### NQP {#NQP}
```
public static final FileType NQP
```


Rakudo Perl 6 컴파일러를 빌드하는 데 사용되는 중간 언어


### PROP {#PROP}
```
public static final FileType PROP
```


Properties 파일 형식


### CFG {#CFG}
```
public static final FileType CFG
```


설정을 저장하는 데 사용되는 구성 파일


### CONF {#CONF}
```
public static final FileType CONF
```


Unix 및 Linux 기반 시스템에서 사용되는 구성 파일


### DIR {#DIR}
```
public static final FileType DIR
```


Directory는 컴퓨터에서 파일을 저장하는 위치입니다


### PY {#PY}
```
public static final FileType PY
```


Python 프로그래밍 언어 형식


### RPY {#RPY}
```
public static final FileType RPY
```


게임을 만들고 실행하기 위한 Python 기반 파일 엔진


### PYW {#PYW}
```
public static final FileType PYW
```


스크립트를 실행해야 함을 나타내기 위해 Windows에서 사용되는 파일


### CPY {#CPY}
```
public static final FileType CPY
```


Controller Python 스크립트 형식


### GYP {#GYP}
```
public static final FileType GYP
```


빌드 자동화 도구 형식


### GYPI {#GYPI}
```
public static final FileType GYPI
```


빌드 자동화 도구 형식


### PYI {#PYI}
```
public static final FileType PYI
```


Python 인터페이스 파일 형식


### IPY {#IPY}
```
public static final FileType IPY
```


IPython 스크립트 형식


### RST {#RST}
```
public static final FileType RST
```


경량 마크업 언어


### RB {#RB}
```
public static final FileType RB
```


Ruby 프로그래밍 언어 형식


### ERB {#ERB}
```
public static final FileType ERB
```


Ruby 프로그래밍 언어 형식


### RJS {#RJS}
```
public static final FileType RJS
```


Ruby 프로그래밍 언어 형식


### GEMSPEC {#GEMSPEC}
```
public static final FileType GEMSPEC
```


RubyGems의 속성을 지정하는 개발자 파일


### RAKE {#RAKE}
```
public static final FileType RAKE
```


Ruby 빌드 자동화 도구


### RU {#RU}
```
public static final FileType RU
```


Rack 구성 파일 형식


### PODSPEC {#PODSPEC}
```
public static final FileType PODSPEC
```


Ruby 빌드 설정 형식


### RBI {#RBI}
```
public static final FileType RBI
```


Ruby 인터페이스 파일 형식


### SASS {#SASS}
```
public static final FileType SASS
```


스타일 시트 언어 형식


### SCSS {#SCSS}
```
public static final FileType SCSS
```


스타일 시트 언어 형식


### SCALA {#SCALA}
```
public static final FileType SCALA
```


Scala 프로그래밍 언어 형식


### SBT {#SBT}
```
public static final FileType SBT
```


Scala용 SBT 빌드 도구 형식


### SC {#SC}
```
public static final FileType SC
```


Scala 워크시트 형식


### SH {#SH}
```
public static final FileType SH
```


bash용 스크립트 형식


### BASH {#BASH}
```
public static final FileType BASH
```


셸 명령을 처리하는 인터프리터 유형


### BASHRC {#BASHRC}
```
public static final FileType BASHRC
```


파일은 대화형 셸의 동작을 결정합니다


### EBUILD {#EBUILD}
```
public static final FileType EBUILD
```


소프트웨어 패키지의 컴파일 및 설치 절차를 자동화하는 특수 bash 스크립트


### SQL {#SQL}
```
public static final FileType SQL
```


구조화 질의 언어 형식


### DSQL {#DSQL}
```
public static final FileType DSQL
```


동적 구조화 질의 언어 형식


### VIM {#VIM}
```
public static final FileType VIM
```


Vim 소스 코드 파일 형식


### YAML {#YAML}
```
public static final FileType YAML
```


인간이 읽을 수 있는 데이터 직렬화 언어 형식


### YML {#YML}
```
public static final FileType YML
```


인간이 읽을 수 있는 데이터 직렬화 언어 형식


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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |

**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype)
### fromFileNameOrExtension(String value) {#fromFileNameOrExtension-java.lang.String-}
```
public static FileType fromFileNameOrExtension(String value)
```


파일 이름 또는 확장자를 기반으로 FileType을 반환합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | java.lang.String | 파일 이름 또는 확장자, null이 아님 |
|

**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the file type

### getSupportedFileTypes() {#getSupportedFileTypes--}
```
public static List<FileType> getSupportedFileTypes()
```


지원되는 파일 유형 목록을 가져옵니다


**Returns:**
java.util.List<com.groupdocs.comparison.result.FileType> - FileType 목록

### areEquals(FileType left, FileType right) {#areEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-}
```
public static boolean areEquals(FileType left, FileType right)
```


제공된 파일 유형의 동일성을 확인합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | left | [FileType](../../com.groupdocs.comparison.result/filetype) | 왼쪽 [FileType](../../com.groupdocs.comparison.result/filetype) 객체. |
|
|  | right | [FileType](../../com.groupdocs.comparison.result/filetype) | 오른쪽 [FileType](../../com.groupdocs.comparison.result/filetype) 객체. |
|

**Returns:**
boolean - 동일하면 true, 그렇지 않으면 false

### areNotEquals(FileType left, FileType right) {#areNotEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-}
```
public static boolean areNotEquals(FileType left, FileType right)
```


제공된 파일 유형이 같지 않은지 확인합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | left | [FileType](../../com.groupdocs.comparison.result/filetype) | 왼쪽 [FileType](../../com.groupdocs.comparison.result/filetype) 객체. |
|
|  | right | [FileType](../../com.groupdocs.comparison.result/filetype) | 오른쪽 [FileType](../../com.groupdocs.comparison.result/filetype) 객체. |
|

**Returns:**
boolean - 같지 않으면 true, 그렇지 않으면 false

### getFileFormat() {#getFileFormat--}
```
public String getFileFormat()
```


파일 유형의 텍스트 설명을 가져옵니다


**Returns:**
java.lang.String - 파일 유형 설명

### getExtension() {#getExtension--}
```
public String getExtension()
```


파일 유형의 확장자를 가져옵니다


**Returns:**
java.lang.String - 파일 유형의 확장자

### toString() {#toString--}
```
public String toString()
```


예를 들어 [FileType](../../com.groupdocs.comparison.result/filetype)의 문자열 표현을 가져옵니다
'PHP 프로그래밍 언어 형식 (.php)'



**Returns:**
java.lang.String - 문자열 표현

